---
title: Informazioni sull'applicazione per Salesforce da salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Tutte le informazioni sulla sicurezza e conformità disponibili per Salesforce, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 88e6a4913e3a3c85ea76fd58c1a724f957c9a3e6
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095887"
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
| Office 365 client supportati | Outlook 2013 o versioni successive su Windows, Outlook 2016 o versione successiva su Mac, Outlook sul Web |
| Nome società partner | salesforce.com |
| URL del sito Web del partner | [https://www.salesforce.com/](https://www.salesforce.com/) |
| URL dell'informativa sulla privacy | [https://www.salesforce.com/company/privacy](https://www.salesforce.com/company/privacy) |
| URL delle Condizioni per l'utilizzo | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474843361/Product_42949677285/Asset_540860c0-685e-4047-9f3a-082a748e57a2/LIGHTNINGFOROUTLOOKOrderFormSu.doc) |

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



#### <a name="add-in-data-access"></a>Accesso ai dati del componente aggiuntivo

Elenca le autorizzazioni richieste da questa app per accedere ai dati dell'organizzazione, la giustificazione e lo scopo di questa autorizzazione (per cosa l'app usa queste informazioni?) e se l'app archivia queste informazioni nei relativi database.

>| **Autorizzazione**  | **Descrizione** |
>|:----------------|:----------------|
>| ReadWrite Mailbox | Questo componente aggiuntivo può leggere o modificare il contenuto di qualsiasi elemento nella cassetta postale e creare nuovi elementi. Può accedere alle informazioni personali, ad esempio il corpo, l'oggetto, il mittente, i destinatari o gli allegati, in qualsiasi messaggio o elemento del calendario. Può inviare questi dati a un servizio di terze parti. |
>| Invia dati | Può inviare dati tramite Internet |

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

