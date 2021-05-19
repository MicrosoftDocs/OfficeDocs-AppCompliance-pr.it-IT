---
title: Informazioni sulle applicazioni per Wunder365 di JiJi Technologies Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/15/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Wunder365, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c4b1e022c3ed482c3020284f07a7d1f986d7cbb3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552517"
---
# <a name="wunder365"></a>Wunder365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 15 dicembre 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200000391" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da JiJi Technologies Private Limited a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Wunder365 |
| ID | WA200000391 |
| Office 365 client supportati | Outlook 2016 o più tardi Windows, Outlook 2016 o più tardi su Mac, Outlook sul Web |
| Nome della società partner | JiJi Technologies Private Limited |
| URL del sito Web partner | [https://apps4.pro/](https://apps4.pro/) |
| URL dell'Informativa sulla privacy | [https://www.wunder365.com/outlook-addin-privacy-policy](https://www.wunder365.com/outlook-addin-privacy-policy) |
| URL delle Condizioni d'uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da JiJi Technologies Private Limited su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | delegato | Nessun dato memorizzato. | Per ottenere/aggiornare le attività di Planner, pubblicare gli aggiornamenti delle attività nel canale del team | 3c95A8B6-B71C-4C4A-8A1A-C7B9B80D9E9C |
>| Mail.Invia | delegato | Nessun dato memorizzato. | Consenti all'app di inviare notifiche tramite posta elettronica agli utenti | 3c95A8B6-B71C-4C4A-8A1A-C7B9B80D9E9C |
>| offline_access | delegato | Nessun dato memorizzato. | Per mantenere l'accesso dell'utente. | 3c95A8B6-B71C-4C4A-8A1A-C7B9B80D9E9C |
>| openid | delegato | Nessun dato memorizzato. | Consente agli utenti di accedere con l'account organizzativo | 3c95A8B6-B71C-4C4A-8A1A-C7B9B80D9E9C |
>| profilo | delegato | UPN, ID utente, ID e-mail, ID tenant per la verifica delle licenze, licenza gratuita. | Consente agli utenti di accedere con l'account organizzativo | 3c95A8B6-B71C-4C4A-8A1A-C7B9B80D9E9C |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Stiamo accedendo a Azure Application Insights. Stiamo registrando l'ID tenant e l'ID e-mail dell'utente per identificare i problemi e aiutare i clienti a risolvere i problemi.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Tutte le applicazioni Web Archiviazione le risorse di accesso si trovano in un abbonamento non connesso all'AAD aziendale con solo amministratori che hanno accesso alle risorse. 2FA è necessario per questi amministratori. 


#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da JiJi Technologies Private Limited su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Ti integri con Microsoft Identify Platform (Azure AD)?  | Sì |
| Hai esaminato e rispettato tutte le best practice applicabili descritte nell'elenco di controllo Microsoft Identity Platform integrazione?  | Sì |
| La tua app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Richiesta di autenticazione a più fattori per gli utenti con ruoli amministrativi, richiesta di autenticazione a più fattori per le attività di gestione di Azure, blocco degli accessi per gli utenti che tentano di usare protocolli di autenticazione legacy, richiesta di percorsi attendibili per la registrazione dell'autenticazione a più fattori di Azure AD, blocco o concessione dell'accesso da posizioni specifiche, blocco del comportamento di accesso rischioso |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate staticamente dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| La tua app supporta la multi-tenancy? | Sì |
| La tua app ha un client riservato? | Sì |
| Possiedi tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa eviti di usare? | - Gli URI di reindirizzamento dei caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una SPA<br/>- Flusso ROPC (Resource Owner Password Credential) |
| La tua app espone api Web? | No |
| La tua app usa le API di anteprima? | Sì |
| La tua app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
