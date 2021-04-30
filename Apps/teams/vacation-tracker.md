---
title: Informazioni sull'applicazione per Vacation Tracker da Vacation Tracker
ms.author: elmalova
author: elenamalova
ms.date: 02/05/2021
ms.topic: article
ms.service: attestation
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per Vacation Tracker, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 33a6ecf06db07878a62a9b9a9edf4360f2507ee7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094820"
---
# <a name="vacation-tracker"></a>Vacation Tracker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: February 5, 2021</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Vacation Tracker a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Vacation Tracker |
| ID | WA200002167 |
| Funzionalità | Bot, scheda |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Vacation Tracker |
| URL del sito Web del partner | [https://vacationtracker.io](https://vacationtracker.io) |
| URL della pagina Teams informazioni sull'applicazione | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| URL dell'informativa sulla privacy | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Vacation Tracker su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | delegated | Gli ID e i nomi dei canali pubblici vengono letti quando gli utenti impostano le notifiche settimanali o giornaliere. | Gli utenti possono selezionare un canale in cui desiderano ricevere notifiche giornaliere o settimanali da Vacation Tracker. Quando un utente sceglie il canale preferito, archivia l'ID del canale. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| Team.ReadBasic.All | delegated | Vengono elencati i Microsoft Teams team aggiunti durante l'iscrizione per consentire agli utenti di selezionare un team a cui iscriversi per Vacation Tracker. In alternativa, possono iscriversi all'intera organizzazione. | L'ID del team Microsoft Teams per un team selezionato viene archiviata solo se l'utente accede a Vacation Tracker come singolo team (non come intera organizzazione). Usiamo gli ID del team per connettere un utente connesso a un account esistente in Vacation Tracker. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read | delegated | Raccogliamo le informazioni dell'utente di base, inclusi il nome, l'ID e l'ID tenant. Questi dati vengono utilizzati per connettere gli utenti connessi all'organizzazione in Vacation Tracker. | Il nome, l'ID e l'ID tenant dell'utente vengono archiviati. Questi dati vengono utilizzati per connettere gli utenti connessi all'organizzazione in Vacation Tracker. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read.All | delegated | I nostri utenti possono importare tutti gli utenti dall'Microsoft 365 o Microsoft Teams team. Questa autorizzazione viene utilizzata per importare solo utenti con licenza per un team Microsoft Teams o un'organizzazione selezionati. | Vengono archiviate informazioni di base sugli utenti importati, tra cui il nome, l'indirizzo di posta elettronica e l'ID utente. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.ReadBasic.All | delegated | Microsoft consente agli utenti di importare gli altri utenti dall'organizzazione o dal Microsoft Teams team. Questa autorizzazione viene utilizzata per elencare gli utenti disponibili e i relativi indirizzi di posta elettronica nel popup di importazione. | Quando gli utenti selezionano i propri colleghi da importare in Vacation Tracker, archiviamo informazioni di base su questi utenti importati, tra cui il nome, l'indirizzo e-mail e l'ID utente. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| e-mail | delegated | Quando l'utente accede utilizzando Microsoft AAD, il suo indirizzo di posta elettronica viene archiviato come identificatore univoco. | I messaggi di posta elettronica dell'utente vengono archiviati come identificatore univoco. Non usiamo questo messaggio di posta elettronica per le comunicazioni, gli utenti immettono il loro indirizzo di posta elettronica aziendale che usiamo per la comunicazione durante l'iscrizione. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| offline_access | delegated | Con questa autorizzazione non vengono raccolti dati. Viene utilizzato per mantenere l'accesso ai dati a cui si è autorizzati ad accedere. | Con questa autorizzazione non vengono archiviati dati. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| openid | delegated | Questa autorizzazione viene utilizzata per accedere o registrare gli utenti a Vacation Tracker. Con questa autorizzazione non vengono raccolti dati specifici. | Questa autorizzazione viene utilizzata per accedere o registrare gli utenti a Vacation Tracker. Con questa autorizzazione non vengono archiviati dati specifici. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| profilo | delegated | Raccogliamo le informazioni dell'utente di base, inclusi il nome, l'ID e l'ID tenant. Questi dati vengono utilizzati per connettere gli utenti connessi all'organizzazione in Vacation Tracker. | Il nome, l'ID e l'ID tenant dell'utente vengono archiviati. Questi dati vengono utilizzati per connettere gli utenti connessi all'organizzazione in Vacation Tracker. | eab5463e-8168-40ee-887a-7ac78de1d266 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutte le informazioni non servizi Microsoft OII vengono trasferite a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento di OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Stripe, AWS, Crisp, Customer.io, Segment, Amplitude, Google Tag Manager | Nome società (come immesso dall'utente) | Quando un utente si immissione, immette il nome della società e questo nome viene utilizzato come nome dell'organizzazione all'interno del prodotto |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Il bot può visualizzare le informazioni di base sull'utente che comunica con il bot. Tuttavia, queste informazioni non vengono archiviate o usate. Usiamo solo l'ID dell'utente, l'ID conversazione e un messaggio inviato al bot. | Archiviamo l'indirizzo di posta elettronica dell'utente, il nome dell'utente (come definito in Microsoft AAD) e la foto del profilo dell'utente (da Microsoft AAD) | Usiamo un indirizzo di posta elettronica come identificatore univoco per i nostri utenti e il nome e la foto del profilo dell'utente per consentire ad amministratori e responsabili approvazione della stessa società di riconoscere i dipendenti nel dashboard.  |



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nome della società e viene conservato e rimosso in base ai criteri di conservazione standard di un anno per questo tipo di dati

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Per iniziare, raccogliamo la quantità minima di dati richiesti dagli utenti. Quindi condividiamo il minimo possibile con i nostri partner e infine abbiamo criteri di conservazione dei dati in modo che tutti i dati vengono rimossi entro un anno, se applicabile.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Vacation Tracker su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

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
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,
<br />
- OAuth2 Implicit Flow, a meno che non sia necessario per una spa
<br />
- Flusso roPC (Resource Owner Password Credential) | | L'app espone qualsiasi API Web? | Sì | | Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì | | La tua app usa le API di anteprima? | No | | L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
