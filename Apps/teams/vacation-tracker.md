---
title: Informazioni sull'applicazione per Vacation Tracker di Vacation Tracker
ms.author: elmalova
author: elenamalova
ms.date: 02/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Vacation Tracker, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 89ed0cc27e26acdeae13cc787fc180cc9f93b8ae
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550996"
---
# <a name="vacation-tracker"></a>Vacation Tracker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 5 febbraio 2021</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Vacation Tracker a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Vacation Tracker |
| ID | WA200002167 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Vacation Tracker |
| URL del sito Web partner | [https://vacationtracker.io](https://vacationtracker.io) |
| URL della pagina Teams informazioni sull'applicazione | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| URL dell'Informativa sulla privacy | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| URL delle Condizioni d'uso | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Vacation Tracker su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | delegato | Leggiamo gli ID e i nomi dei canali pubblici quando gli utenti impostano le notifiche settimanali o giornaliere. | Gli utenti possono selezionare un canale in cui desiderano ricevere notifiche giornaliere o settimanali da Vacation Tracker. Quando un utente sceglie il proprio canale preferito, archiviamo l'ID canale. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| Team.ReadBasic.All | delegato | Elenchiamo Microsoft Teams utente dei team di squadra uniti durante l'iscrizione per consentire agli utenti di selezionare un team a cui desiderano iscriversi a Vacation Tracker. In alternativa possono iscriversi con tutta la loro organizzazione. | Archiviamo l Microsoft Teams ID team per un team selezionato solo se l'utente si accede a Vacation Tracker come un singolo team (non come un'intera organizzazione). Usiamo gli ID del team per connettere un utente connesso con un account esistente in Vacation Tracker. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read | delegato | Raccogliamo le informazioni dell'utente di base, inclusi il nome, l'ID e l'ID tenant. Utilizziamo questi dati per connettere gli utenti connessi alla loro organizzazione in Vacation Tracker. | Archiviamo il nome, l'ID e l'ID tenant dell'utente. Utilizziamo questi dati per connettere gli utenti connessi alla loro organizzazione in Vacation Tracker. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read.All | delegato | I nostri utenti possono importare tutti gli utenti dalla loro Microsoft 365 o dal Microsoft Teams team. Questa autorizzazione viene utilizzate per importare solo utenti con licenza per un team o Microsoft Teams selezionato. | Archiviamo le informazioni di base sugli utenti importati, tra cui il loro nome, indirizzo e-mail e ID utente. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.ReadBasic.All | delegato | Permettiamo agli utenti di importare gli altri utenti dalla loro organizzazione o dal loro team Microsoft Teams lavoro. Utilizziamo questa autorizzazione per elencare gli utenti disponibili e i loro indirizzi e-mail nel popup di importazione. | Quando gli utenti selezionano i colleghi da importare in Vacation Tracker, archiviamo le informazioni di base su questi utenti importati, inclusi il nome, l'indirizzo e-mail e l'ID utente. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| e-mail | delegato | Quando l'utente accede utilizzando Microsoft AAD, archiviamo il proprio indirizzo di posta elettronica come identificatore univoco. | Archiviamo l'e-mail dell'utente come identificatore univoco. Non utilizziamo questa e-mail per la comunicazione, gli utenti inserisceno il loro indirizzo e-mail aziendale che utilizziamo per la comunicazione durante l'iscrizione. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| offline_access | delegato | Non raccogliamo dati con questa autorizzazione. Viene utilizzato per mantenere l'accesso ai dati a cui abbiamo il permesso di accedere. | Non archiviamo dati con questa autorizzazione. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| openid | delegato | Utilizziamo questa autorizzazione per accedere o iscrivere gli utenti a Vacation Tracker. Non raccogliamo dati specifici con questa autorizzazione. | Utilizziamo questa autorizzazione per accedere o iscrivere gli utenti a Vacation Tracker. Non archiviamo dati specifici con questa autorizzazione. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| profilo | delegato | Raccogliamo le informazioni dell'utente di base, inclusi il nome, l'ID e l'ID tenant. Utilizziamo questi dati per connettere gli utenti connessi alla loro organizzazione in Vacation Tracker. | Archiviamo il nome, l'ID e l'ID tenant dell'utente. Utilizziamo questi dati per connettere gli utenti connessi alla loro organizzazione in Vacation Tracker. | eab5463e-8168-40ee-887a-7ac78de1d266 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft non sono trasferiti** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Stripe, AWS, Crisp, Customer.io, Segment, Amplitude, Google Tag Manager | Nome società (immesso dall'utente) | Quando un utente si firma, immette il nome della società e noi usiamo questo nome come nome dell'organizzazione all'interno del prodotto |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Il bot può visualizzare le informazioni di base sull'utente che comunica con il bot. Tuttavia, non archiviamo o utilizziamo tali informazioni. Utilizziamo solo l'ID dell'utente, l'ID conversazione e un messaggio inviato al nostro bot. | Archiviamo l'indirizzo e-mail dell'utente, il nome dell'utente (come definito in Microsoft AAD) e la foto del profilo dell'utente (da Microsoft AAD) | Utilizziamo un indirizzo e-mail come identificatore univoco per i nostri utenti e il nome e la foto del profilo dell'utente per consentire agli amministratori e agli approvatori della stessa azienda di riconoscere i propri dipendenti nella nostra dashboard.  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>nome dell'azienda e viene conservato e rimosso in base alla nostra politica standard di conservazione di un anno per questo tipo di dati

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Per iniziare, raccogliamo la quantità minima di dati richiesti dagli utenti. Quindi condividiamo il minimo possibile con i nostri partner e infine abbiamo politiche di conservazione dei dati in modo che tutti i dati siano rimossi entro un anno, se applicabile.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Vacation Tracker su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Ti integri con Microsoft Identify Platform (Azure AD)?  | Sì |
| Hai esaminato e rispettato tutte le best practice applicabili descritte nell'elenco di controllo Microsoft Identity Platform integrazione?  | Sì |
| La tua app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate staticamente dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| La tua app supporta la multi-tenancy? | Sì |
| La tua app ha un client riservato? | Sì |
| Possiedi tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa eviti di usare? | - Gli URI di reindirizzamento dei caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una SPA<br/>- Flusso ROPC (Resource Owner Password Credential) |
| La tua app espone api Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso corretto? | Sì |
| La tua app usa le API di anteprima? | No |
| La tua app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
