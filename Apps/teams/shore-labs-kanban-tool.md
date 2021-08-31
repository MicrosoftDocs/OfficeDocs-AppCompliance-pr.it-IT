---
title: Application Information for Kanban Tool by Shore Labs
ms.author: elmalova
author: elenamalova
ms.date: 06/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Lo strumento Kanban, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: b73351d77f68cf00b904d95336f83d8089095791
ms.sourcegitcommit: 78e63c8004c49fa95d80618b9fee424f1084e43d
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/19/2021
ms.locfileid: "58404986"
---
# <a name="kanban-tool"></a>Strumento Kanban

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 15, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b3c15d4f-1972-4836-a1eb-7575dd56a17e" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002121" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Shore Labs a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Strumento Kanban |
| ID | WA200002121 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Shore Labs |
| URL del sito Web del partner | [https://www.shorelabs.com](https://www.shorelabs.com) |
| URL della Teams info dell'applicazione | [https://kanbantool.com](https://kanbantool.com) |
| URL dell'informativa sulla privacy | [https://kanbantool.com/policy/privacy](https://kanbantool.com/policy/privacy) |
| URL delle Condizioni per l'utilizzo | [https://kanbantool.com/policy/terms-of-service](https://kanbantool.com/policy/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Shore Labs su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | delegated | Indirizzo di posta elettronica dell'utente per la comunicazione, la corrispondenza dell'identità e il recapito delle notifiche. | Indirizzo di posta elettronica. | [4e820d60-9e62-403c-accd-857b987cc13c](https://docs.microsoft.com/microsoft-365-app-certification/azure/4e820d60-9e62-403c-accd-857b987cc13c) |
>| Team.ReadBasic.All | delegated | Identificatori e nomi dei team di cui l'utente è membro diretto. Vengono utilizzati per assegnare automaticamente gli utenti ai gruppi corretti nello strumento Kanban. | Gli identificatori e i nomi dei team di cui l'utente connesso è un membro diretto sono mappati a gruppi nello strumento Kanban. Ciò consente la gestione degli accessi in base al gruppo e la condivisione di Boards Disa Boards tra team diversi nella stessa organizzazione. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| User.Read | delegated | Informazioni aziendali di base degli utenti connessi. Viene utilizzato per popolare i dettagli dell'account per i nuovi account e per riconoscere gli utenti che appartengono all'organizzazione per fornire funzionalità Sign-On singola. | Nome e un identificatore Microsoft univoco dell'organizzazione. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| offline_access | delegated | Consente la funzionalità "Accedi con Microsoft" e la sincronizzazione dei dati a cui hai fornito l'accesso all'app, al momento dell'accesso dell'utente. | Mantenere l'accesso ai dati a cui gli è stato assegnato l'accesso. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| openid | delegated | Token OPEN ID che consentono agli utenti di accedere all'app con i propri account aziendali o dell'istituto di istruzione tramite il pulsante "Accedi con Microsoft". | Identificatore non modificabile per l'account utente nel sistema di identità Microsoft. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| profilo | delegated | Nome utente da popolare automaticamente nello strumento Kanban e mantenere sincronizzato con le modifiche apportate Microsoft Teams. | Nome completo dell'utente. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Lo strumento Kanban usa i sottoprocessori seguenti per le prestazioni del servizio: https://kanbantool.com/policy/privacy#appointed-subprocessors |   | Usiamo queste terze parti per fornire e gestire l'infrastruttura tecnica e assistere nell'elaborazione di fatturazione e pagamento. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Microsoft raccoglie automaticamente informazioni tecniche sull'account e sulle attività dell'utente nel Servizio. Tali informazioni vengono archiviate in file di registro interni e possono includere dati OII e EUII, se facevano parte dell'attività effettuata. I file di registro non vengono condivisi con terze parti. Lo scopo della raccolta dei dati di registro è per motivi legali e normativi, mirare all'identificazione dell'origine di eventuali violazioni della sicurezza o uso improprio del servizio, per la limitazione della frequenza delle richieste e la profilatura delle prestazioni

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Gli amministratori di account hanno accesso completo, inclusa la possibilità di modificare e rimuovere i dati personali relativi al proprio account, e sono i controller di dati effettivi.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalogo vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Shore Labs su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | ,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
