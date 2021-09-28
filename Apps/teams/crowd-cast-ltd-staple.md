---
title: Informazioni sull'applicazione per Staple by Crowd Cast, Ltd.
ms.author: elmalova
author: elenamalova
ms.date: 09/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Staple, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: fa258f568d799ceb8891cd374aa33277dbc6c2c4
ms.sourcegitcommit: 3ac3366e04e24db2d12183ef212738d5b599f553
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/28/2021
ms.locfileid: "59975232"
---
# <a name="staple"></a>Graffetta

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 27, 2021</p>

* <a href="https://teams.microsoft.com/l/app/ac9ca94a-e666-4f61-959a-12c063e13e69" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003281" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Crowd Cast, Ltd. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Graffetta |
| ID | WA200003281 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Crowd Cast, Ltd. |
| URL del sito Web del partner | [https://crowdcast.jp/ja/](https://crowdcast.jp/ja/) |
| URL della Teams info dell'applicazione | [https://intercom.help/staple/ja](https://intercom.help/staple/ja) |
| URL dell'informativa sulla privacy | [https://crowdcast.jp/ja/privacy/](https://crowdcast.jp/ja/privacy/) |
| URL delle Condizioni per l'utilizzo | [https://go.microsoft.com](https://go.microsoft.com) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Crowd Cast, Ltd. su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Organization.Read.All | application | Usato per la raccolta dell'ID tenant. Usato per garantire che gli utenti che eseguono l'autenticazione con la piattaforma siano membri di un tenant specifico. | id tenant. Usato per garantire che gli utenti che eseguono l'autenticazione con la piattaforma siano membri di un tenant specifico. | [ac9ca94a-e666-4f61-959a-12c063e13e69](https://docs.microsoft.com/microsoft-365-app-certification/azure/ac9ca94a-e666-4f61-959a-12c063e13e69) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | application | Teams'app si installa autonomamente nel team dell'utente | N/D | [ac9ca94a-e666-4f61-959a-12c063e13e69](https://docs.microsoft.com/microsoft-365-app-certification/azure/ac9ca94a-e666-4f61-959a-12c063e13e69) |
>| AppCatalog.Read.All | delegated | Legge il catalogo app di un utente per verificare se l'app teams è installata. | N/D | [bbdcd676-7448-453c-bec7-70e5384bc290](https://docs.microsoft.com/microsoft-365-app-certification/azure/bbdcd676-7448-453c-bec7-70e5384bc290) |
>| User.Read | delegated | Usato per leggere l'ID di un utente per assicurarsi che i messaggi siano inviati all'utente corretto. | ID utente archiviato per inviare messaggi proattivi all'utente. | [bbdcd676-7448-453c-bec7-70e5384bc290](https://docs.microsoft.com/microsoft-365-app-certification/azure/bbdcd676-7448-453c-bec7-70e5384bc290) |
>| openid | delegated | Accedere a un utente per leggere le informazioni di base del profilo | N/D | [bbdcd676-7448-453c-bec7-70e5384bc290](https://docs.microsoft.com/microsoft-365-app-certification/azure/bbdcd676-7448-453c-bec7-70e5384bc290) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati di controllo dell'amministratore dell'organizzazione nei sistemi di un partner (AWS, Heroku).

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Crowd Cast, Ltd. sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
