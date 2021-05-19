---
title: Informazioni sull'applicazione per Nulia Works di Nulia
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Nulia Works, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4471074b2e15b41894f709cb2a25dee1d0dc5187
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552897"
---
# <a name="nulia-works"></a>Nulia Works

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 11 marzo 2021</p>

* <a href="https://teams.microsoft.com/l/app/e49e0f69-600c-460c-80b3-8809a9d97a4c" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002051" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Nulia a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Nulia Works |
| ID | WA200002051 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Nulia |
| URL del sito Web partner | [https://nulia.com](https://nulia.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://nulia.com/product](https://nulia.com/product) |
| URL dell'Informativa sulla privacy | [https://nulia.com/privacy](https://nulia.com/privacy) |
| URL delle Condizioni d'uso | [https://nulia.com/terms](https://nulia.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Nulia su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | applicazione | Utilizziamo i dati raccolti per segnare i progressi degli utenti su competenze e risultati. Raccogliamo i conteggi degli utilizzi tra più carichi di lavoro O365. | Archiviamo tutti i dati che raccogliamo nell'archiviazione BLOB. Utilizziamo questi dati per ottenere un punteggio per gli utenti sull'avanzamento delle competenze e dei risultati. Ad esempio, contiamo il numero di eventi del calendario di un utente. Questo valore influisce sul loro progresso di abilità. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia utilizza l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Contatti.Lettura | applicazione | Utilizziamo i dati raccolti per segnare i progressi degli utenti su competenze e risultati. Raccogliamo i conteggi degli utilizzi tra più carichi di lavoro O365. | Archiviamo tutti i dati che raccogliamo nell'archiviazione BLOB. Utilizziamo questi dati per ottenere un punteggio per gli utenti sull'avanzamento delle competenze e dei risultati. Ad esempio, contiamo il numero di contatti creati da un utente. Questo valore influisce sul loro progresso di abilità. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia utilizza l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Files.Read.All | applicazione | Utilizziamo i dati raccolti per segnare i progressi degli utenti su competenze e risultati. Raccogliamo i conteggi degli utilizzi tra più carichi di lavoro O365. | Archiviamo tutti i dati che raccogliamo nell'archiviazione BLOB. Utilizziamo questi dati per ottenere un punteggio per gli utenti sull'avanzamento delle competenze e dei risultati. Ad esempio, contiamo il numero di file che un utente sta sincronizzando con il proprio computer. Questo valore influisce sul loro progresso di abilità. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia utilizza l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Group.Read.All | applicazione | Utilizziamo i dati raccolti per segnare i progressi degli utenti su competenze e risultati. Raccogliamo i conteggi degli utilizzi tra più carichi di lavoro O365. | Archiviamo tutti i dati che raccogliamo nell'archiviazione BLOB. Utilizziamo questi dati per ottenere un punteggio per gli utenti sull'avanzamento delle competenze e dei risultati. Ad esempio, recuperiamo dai gruppi il numero di Teams a cui appartiene un utente. Questo valore influisce sul loro progresso di abilità. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia utilizza l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Mail.Read | applicazione | Utilizziamo i dati raccolti per segnare i progressi degli utenti su competenze e risultati. Raccogliamo i conteggi degli utilizzi tra più carichi di lavoro O365. | Archiviamo tutti i dati che raccogliamo nell'archiviazione BLOB. Utilizziamo questi dati per ottenere un punteggio per gli utenti sull'avanzamento delle competenze e dei risultati. Ad esempio, contiamo il numero di cartelle di posta personalizzate create da un utente. Questo valore influisce sul loro progresso di abilità. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia utilizza l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| MailboxSettings.Read | applicazione | Utilizziamo i dati raccolti per segnare i progressi degli utenti su competenze e risultati. Raccogliamo i conteggi degli utilizzi tra più carichi di lavoro O365. | Archiviamo tutti i dati che raccogliamo nell'archiviazione BLOB. Utilizziamo questi dati per ottenere un punteggio per gli utenti sull'avanzamento delle competenze e dei risultati. Ad esempio, vediamo se un utente ha un set di risposta fuori sede. Questo valore influisce sul loro progresso di abilità. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia utilizza l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Note.Lettura | applicazione | Utilizziamo i dati raccolti per segnare i progressi degli utenti su competenze e risultati. Raccogliamo i conteggi degli utilizzi tra più carichi di lavoro O365. | Archiviamo tutti i dati che raccogliamo nell'archiviazione BLOB. Utilizziamo questi dati per ottenere un punteggio per gli utenti sull'avanzamento delle competenze e dei risultati. Ad esempio, contiamo il numero di blocchi appunti condivisi da un utente. Questo valore influisce sul loro progresso di abilità. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia utilizza l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Reports.Read.All | applicazione | Utilizziamo i dati raccolti per segnare i progressi degli utenti su competenze e risultati. Raccogliamo i conteggi degli utilizzi tra più carichi di lavoro O365. | Archiviamo tutti i dati che raccogliamo nell'archiviazione BLOB. Utilizziamo questi dati per ottenere un punteggio per gli utenti sull'avanzamento delle competenze e dei risultati. Ad esempio, recuperiamo dall'utente il numero di Teams messaggi inviati in un giorno. Questo valore influisce sul loro progresso di abilità. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia utilizza l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Sites.Read.All | applicazione | Utilizziamo i dati raccolti per segnare i progressi degli utenti su competenze e risultati. Raccogliamo i conteggi degli utilizzi tra più carichi di lavoro O365. | Archiviamo tutti i dati che raccogliamo nell'archiviazione BLOB. Utilizziamo questi dati per ottenere un punteggio per gli utenti sull'avanzamento delle competenze e dei risultati. Ad esempio, contiamo il numero di raccolte siti create dall'utente. Questo valore influisce sul loro progresso di abilità. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia utilizza l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| User.Read | applicazione | Vengono visualizzati il nome visualizzato, il reparto e l'immagine del profilo dell'utente. | Salviamo il nome visualizzato e il reparto nel nostro database in modo da non dover colpire il Graph ogni volta. Non memorizzamo l'immagine del profilo. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia utilizza l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Organization.Read.All | applicazione | Raccogliamo il nome e l'URL Yammer tenant. Lo usiamo per avviare la Yammer quando l'utente fa clic su &quot; un pulsante Prova nella nostra app relativo alle Yammer &quot; attività. | Archiviamo tutti i dati che raccogliamo nell'archiviazione BLOB. Ad esempio, lo usiamo per avviare Yammer quando l'utente fa clic su &quot; un pulsante Prova nella nostra app relativo alle Yammer &quot; attività. | Utilizziamo i dati raccolti per segnare i progressi degli utenti su competenze e risultati. Raccogliamo i conteggi degli utilizzi tra più carichi di lavoro O365. |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>Non è possibile accedere all'I EUII.


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nei registri o nella telemetria delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Non controlliamo i dati sui sistemi dei partner

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Nulia su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Ti integri con Microsoft Identify Platform (Azure AD)?  | Sì |
| Hai esaminato e rispettato tutte le best practice applicabili descritte nell'elenco di controllo Microsoft Identity Platform integrazione?  | Sì |
| La tua app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
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
