---
title: Informazioni sull'applicazione per Keepass Pro da Witivio
ms.author: elmalova
author: elenamalova
ms.date: 10/12/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Keepass Pro, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 11eafe0e282e58623a303e961731e51983034343
ms.sourcegitcommit: 1d47df35430334cfc0c60f7ea0b62392b99b7cbf
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/13/2021
ms.locfileid: "60290366"
---
# <a name="keepass-pro"></a>Keepass Pro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: October 12, 2021</p>

* <a href="https://teams.microsoft.com/l/app/dc00c22b-b7ad-4db8-bf35-c2660104d622" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003336" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Witivio a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Keepass Pro |
| ID | WA200003336 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Witivio |
| URL del sito Web del partner | [https://www.witivio.com](https://www.witivio.com) |
| URL della Teams info dell'applicazione | [https://www.teams-pro.com/en/browse-apps/keypass-pro/](https://www.teams-pro.com/en/browse-apps/keypass-pro/) |
| URL dell'informativa sulla privacy | [https://www.teams-pro.com/en/privacy-policy/](https://www.teams-pro.com/en/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://www.teams-pro.com/en/terms-of-use/](https://www.teams-pro.com/en/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Witivio su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite.All | delegated | Lettura e scrittura del file kbdx in sharepoint utente / onedrive | Account di accesso e password nel file KDBX. Witivio non archivia i dati nei server | [597cc93d-8951-4f62-b549-eca97ba5c042](https://docs.microsoft.com/microsoft-365-app-certification/azure/597cc93d-8951-4f62-b549-eca97ba5c042) |
>| User.Read | delegated | Recuperare le proprietà e le relazioni dell'oggetto utente | N/D | [597cc93d-8951-4f62-b549-eca97ba5c042](https://docs.microsoft.com/microsoft-365-app-certification/azure/597cc93d-8951-4f62-b549-eca97ba5c042) |
>| email | delegated | Visualizzare l'indirizzo di posta elettronica degli utenti.    | N/D | [597cc93d-8951-4f62-b549-eca97ba5c042](https://docs.microsoft.com/microsoft-365-app-certification/azure/597cc93d-8951-4f62-b549-eca97ba5c042) |
>| openid | delegated | Accedi agli utenti. | N/D | [597cc93d-8951-4f62-b549-eca97ba5c042](https://docs.microsoft.com/microsoft-365-app-certification/azure/597cc93d-8951-4f62-b549-eca97ba5c042) |
>| profile | delegated | Visualizzare il profilo di base degli utenti.  | N/D | [597cc93d-8951-4f62-b549-eca97ba5c042](https://docs.microsoft.com/microsoft-365-app-certification/azure/597cc93d-8951-4f62-b549-eca97ba5c042) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>lettura, scrittura ed eliminazione

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

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

Queste informazioni sono state fornite da Witivio sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
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
