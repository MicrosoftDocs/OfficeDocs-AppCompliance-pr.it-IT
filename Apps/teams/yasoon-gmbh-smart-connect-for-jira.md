---
title: Informazioni sull'applicazione per smart Connessione per Jira di yasoon GmbH
ms.author: elmalova
author: elenamalova
ms.date: 01/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Smart Connessione per Jira, le sue politiche di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza / conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 6fb1be576d588727c75f14d72db48bc3a7a8aeb5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550736"
---
# <a name="smart-connect-for-jira"></a>Smart Connect for Jira

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 22 gennaio 2021</p>

* <a href="https://teams.microsoft.com/l/app/6402de97-ce33-4386-bf28-b37e9e139c09" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002055" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da yasoon GmbH a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Smart Connect for Jira |
| ID | WA200002055 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | yasoon GmbH |
| URL del sito Web partner | [https://yasoon.com](https://yasoon.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://yasoon.com/microsoft-teams-for-jira/](https://yasoon.com/microsoft-teams-for-jira/) |
| URL dell'Informativa sulla privacy | [https://yasoon.com/privacy-policy-services](https://yasoon.com/privacy-policy-services) |
| URL delle Condizioni d'uso | [https://yasoon.com/terms-of-use](https://yasoon.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da yasoon GmbH su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Channel.ReadBasic.All | delegato | L'autorizzazione viene utilizzata per consente all'utente di selezionare uno di questi canali uniti in Jira. | ID canale, ai fini della memorizzazione nella cache | 89D5Ca9F-D63B-4885-BD30-6E7433C1540C |
>| ChannelMessage.Read.Group | applicazione | Consente all'app di visualizzare i messaggi del canale collegato in Jira. | ID messaggio per il collegamento di messaggi a problemi Jira | 89D5Ca9F-D63B-4885-BD30-6E7433C1540C |
>| ChannelMessage.Invia | delegato | Non vengono utilizzati dati, questa API viene utilizzata per consentire all'utente di rispondere ai messaggi del canale da Jira. | Nessuno | 89D5Ca9F-D63B-4885-BD30-6E7433C1540C |
>| ChannelSettings.Read.Group | applicazione | Utilizzato per cercare informazioni dettagliate su un canale. | Nessuno | 89D5Ca9F-D63B-4885-BD30-6E7433C1540C |
>| Chat.ReadWrite | delegato | Utilizzato per consentire all'utente di aggiungere nuove risposte alle chat e visualizzare i messaggi di chat da Jira. | Nessuno | 89D5Ca9F-D63B-4885-BD30-6E7433C1540C |
>| Membro.Lettura.Gruppo | applicazione | Utilizzato per i controlli delle autorizzazioni, consente all'app di convalidare l'appartenenza del team agli utenti. | Nessuno | 89D5Ca9F-D63B-4885-BD30-6E7433C1540C |
>| Team.ReadBasic.All | delegato | L'autorizzazione viene utilizzata per consente all'utente di selezionare uno di questi team uniti in Jira. | ID team per scopi di memorizzazione nella cache | 89D5Ca9F-D63B-4885-BD30-6E7433C1540C |
>| TeamSettings.Read.Group | applicazione | Consente all'app di leggere le impostazioni del team per rispettare determinate impostazioni predefinite. | Nessuno | 89D5Ca9F-D63B-4885-BD30-6E7433C1540C |
>| User.ReadBasic.All | delegato | Consente all'utente di selezionare i colleghi da @-mention in un messaggio del canale | Nessuno | 89D5Ca9F-D63B-4885-BD30-6E7433C1540C |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft non sono trasferiti** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Atlassian Jira e forse uno dei nostri appaltatori, può essere visto qui: https://go.yasoon.com/contractors | Metadati dei messaggi (ID, timestamp), metadati dell'utente e dell'organizzazione (ID utente, ID organizzazione) e indirizzi di posta elettronica dell'utente | Supportare la funzionalità dell'app (ad esempio, abbinare gli account Atlassian con Office account) e consentire al nostro supporto di risolvere i problemi più velocemente. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Corrispondenza tra gli utenti Teams account con l'account Atlassian Jira degli utenti | No |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Metadati utente (ID)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Lavoriamo solo con servizi che offrono rigorose garanzie sulla privacy dei dati. 

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da yasoon GmbH su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Ti integri con Microsoft Identify Platform (Azure AD)?  | Sì |
| Hai esaminato e rispettato tutte le best practice applicabili descritte nell'elenco di controllo Microsoft Identity Platform integrazione?  | Sì |
| La tua app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate staticamente dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| La tua app supporta la multi-tenancy? | Sì |
| La tua app ha un client riservato? | No |
| Possiedi tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa eviti di usare? | - Gli URI di reindirizzamento dei caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una SPA<br/>- Flusso ROPC (Resource Owner Password Credential) |
| La tua app espone api Web? | No |
| La tua app usa le API di anteprima? | Sì |
| La tua app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
