---
title: Informazioni sull'applicazione per Salesforce da salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e conformità disponibili per Salesforce, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b5999dd08ed27ce75bc958e431c0974e10830a3c
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281698"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da salesforce.com a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Salesforce |
| ID | WA104379334 |
| Office 365 client supportati | Outlook 2013 o versioni successive Windows, Outlook 2016 o versioni successive su Mac, Outlook sul web |
| Nome società partner | salesforce.com |
| URL del sito Web del partner | [https://www.salesforce.com](https://www.salesforce.com) |
| URL dell'informativa sulla privacy | [https://www.salesforce.com/company/privacy/](https://www.salesforce.com/company/privacy/) |
| URL delle Condizioni per l'utilizzo | [https://store.office.com/en-us/WebAppLandingPage.aspx?p4=TC...](https://store.office.com/en-us/WebAppLandingPage.aspx?p4=TC&amp;p5=WA104379334&amp;cmu=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da salesforce.com su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>Questa applicazione non utilizza Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API JavaScript per Office | Sì | Il componente aggiuntivo utilizza le funzioni di Office.js ed EWS per copiare il contenuto e gli allegati di un messaggio di posta elettronica che un utente Outlook ha deciso di accedere a Salesforce. Funzionalità simili vengono utilizzate sul lato calendario per registrare gli appuntamenti in Salesforce. |  | Il componente aggiuntivo usa funzioni come getUserIdentityTokenAsync per ottenere l'identità Outlook utente corrente, GetItem (.js and EWS) to get and set AdditionalProperties and the content of the current email message when saving to Salesforce records, GetAttachment (EWS) to retrieve the attachments from Exchange and add to the paired Salesforce email, UpdateItem (.js), GetFolder (.js) to get the drafts folder, CreateItem (.js), which is used to create a draft message. |  |
>| Servizi Web Exchange (EWS) | Sì | Il componente aggiuntivo utilizza le funzioni di Office.js ed EWS per copiare il contenuto e gli allegati di un messaggio di posta elettronica che un utente Outlook ha deciso di accedere a Salesforce. Funzionalità simili vengono utilizzate sul lato calendario per registrare gli appuntamenti in Salesforce. |  | Il componente aggiuntivo usa funzioni come getUserIdentityTokenAsync per ottenere l'identità Outlook utente corrente, GetItem (.js and EWS) to get and set AdditionalProperties and the content of the current email message when saving to Salesforce records, GetAttachment (EWS) to retrieve the attachments from Exchange and add to the paired Salesforce email, UpdateItem (.js), GetFolder (.js) to get the drafts folder, CreateItem (.js), which is used to create a draft message. |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>L'archiviazione salesforce è descritta nella Guida alla sicurezza all'indirizzo https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

