---
title: Informazioni sull'applicazione per Salesforce da parte salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Salesforce, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 29c00595a806c5144b34701ba54860353f9cafc0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553707"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 16 dicembre 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da salesforce.com a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Salesforce |
| ID | WA104379334 |
| Office 365 client supportati | Outlook 2013 o versioni successive Windows, Outlook 2016 o versioni successive su Mac, Outlook sul Web |
| Nome della società partner | salesforce.com |
| URL del sito Web partner | [https://www.salesforce.com/](https://www.salesforce.com/) |
| URL dell'Informativa sulla privacy | [https://www.salesforce.com/company/privacy](https://www.salesforce.com/company/privacy) |
| URL delle Condizioni d'uso | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474843361/Product_42949677285/Asset_540860c0-685e-4047-9f3a-082a748e57a2/LIGHTNINGFOROUTLOOKOrderFormSu.doc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da salesforce.com su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>Questa applicazione non utilizza Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati tramite altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono utilizzare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni di identificazione dell'organizzazione ( OII). Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **OII viene raccolto?** |  **Quale OII viene raccolto?** | **Giustificazione per la raccolta di OII?** | **OII è memorizzato?** | **Giustificazione per l'archiviazione di OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API JavaScript per Office | Sì | Il componente aggiuntivo utilizza funzioni di Office.js ed EWS per copiare contenuti e allegati su un'e-mail Outlook utente ha deciso di accedere a Salesforce. Funzionalità simili vengono utilizzate sul lato calendario, per accedere agli appuntamenti in Salesforce. |  | Il componente aggiuntivo utilizza funzioni come getUserIdentityTokenAsync per ottenere l'identità utente Outlook corrente, GetItem (.js ed EWS) per ottenere e impostare AdditionalProperties e il contenuto del messaggio di posta elettronica corrente durante il salvataggio nei record Salesforce, GetAttachment (EWS) per recuperare gli allegati da Exchange e aggiungere all'e-mail Salesforce accoppiata, UpdateItem (.js), GetFolder (.js) per ottenere la cartella bozze CreateItem (.js), che viene utilizzata per creare una bozza di messaggio. |  |
>| Servizi Web Exchange (EWS) | Sì | Il componente aggiuntivo utilizza funzioni di Office.js ed EWS per copiare contenuti e allegati su un'e-mail Outlook utente ha deciso di accedere a Salesforce. Funzionalità simili vengono utilizzate sul lato calendario, per accedere agli appuntamenti in Salesforce. |  | Il componente aggiuntivo utilizza funzioni come getUserIdentityTokenAsync per ottenere l'identità utente Outlook corrente, GetItem (.js ed EWS) per ottenere e impostare AdditionalProperties e il contenuto del messaggio di posta elettronica corrente durante il salvataggio nei record Salesforce, GetAttachment (EWS) per recuperare gli allegati da Exchange e aggiungere all'e-mail Salesforce accoppiata, UpdateItem (.js), GetFolder (.js) per ottenere la cartella bozze CreateItem (.js), che viene utilizzata per creare una bozza di messaggio. |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Lo storage Salesforce è descritto nella Guida alla sicurezza all'ora https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

