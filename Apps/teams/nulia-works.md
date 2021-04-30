---
title: Informazioni sull'applicazione per Nulia Works di Nulia
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
description: Tutte le informazioni sulla sicurezza e conformità disponibili per Nulia Works, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 068879c3b4cb073f72886c0bbf2836c0b79a46b7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094427"
---
# <a name="nulia-works"></a>Nulia Works

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 11, 2021</p>

* <a href="https://teams.microsoft.com/l/app/e49e0f69-600c-460c-80b3-8809a9d97a4c" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002051" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Nulia a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Nulia Works |
| ID | WA200002051 |
| Funzionalità | Scheda, connettore |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Nulia |
| URL del sito Web del partner | [https://nulia.com](https://nulia.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://nulia.com/product](https://nulia.com/product) |
| URL dell'informativa sulla privacy | [https://nulia.com/privacy](https://nulia.com/privacy) |
| URL delle Condizioni per l'utilizzo | [https://nulia.com/terms](https://nulia.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Nulia su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | application | Usiamo i dati raccolti per segnare lo stato di avanzamento degli utenti su competenze e risultati. Vengono raccolti i conteggi di utilizzo in più carichi di lavoro di O365. | Tutti i dati raccolti vengono archiviati nell'archiviazione BLOB. Questi dati vengono utilizzati per segnare gli utenti in base alle competenze e all'avanzamento dei risultati. Ad esempio, contiamo il numero di eventi di calendario di un utente. Questo valore influisce sull'avanzamento delle competenze. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia usa l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Contacts.Read | application | Usiamo i dati raccolti per segnare lo stato di avanzamento degli utenti su competenze e risultati. Vengono raccolti i conteggi di utilizzo in più carichi di lavoro di O365. | Tutti i dati raccolti vengono archiviati nell'archiviazione BLOB. Questi dati vengono utilizzati per segnare gli utenti in base alle competenze e all'avanzamento dei risultati. Ad esempio, viene contato il numero di contatti creati da un utente. Questo valore influisce sull'avanzamento delle competenze. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia usa l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Files.Read.All | application | Usiamo i dati raccolti per segnare lo stato di avanzamento degli utenti su competenze e risultati. Vengono raccolti i conteggi di utilizzo in più carichi di lavoro di O365. | Tutti i dati raccolti vengono archiviati nell'archiviazione BLOB. Questi dati vengono utilizzati per segnare gli utenti in base alle competenze e all'avanzamento dei risultati. Ad esempio, contiamo il numero di file sincronizzati da un utente con il computer. Questo valore influisce sull'avanzamento delle competenze. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia usa l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Group.Read.All | application | Usiamo i dati raccolti per segnare lo stato di avanzamento degli utenti su competenze e risultati. Vengono raccolti i conteggi di utilizzo in più carichi di lavoro di O365. | Tutti i dati raccolti vengono archiviati nell'archiviazione BLOB. Questi dati vengono utilizzati per segnare gli utenti in base alle competenze e all'avanzamento dei risultati. Ad esempio, viene recuperato dai gruppi il numero di Teams a cui appartiene un utente. Questo valore influisce sull'avanzamento delle competenze. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia usa l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Mail.Read | application | Usiamo i dati raccolti per segnare lo stato di avanzamento degli utenti su competenze e risultati. Vengono raccolti i conteggi di utilizzo in più carichi di lavoro di O365. | Tutti i dati raccolti vengono archiviati nell'archiviazione BLOB. Questi dati vengono utilizzati per segnare gli utenti in base alle competenze e all'avanzamento dei risultati. Ad esempio, viene contato il numero di cartelle di posta personalizzate create da un utente. Questo valore influisce sull'avanzamento delle competenze. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia usa l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| MailboxSettings.Read | application | Usiamo i dati raccolti per segnare lo stato di avanzamento degli utenti su competenze e risultati. Vengono raccolti i conteggi di utilizzo in più carichi di lavoro di O365. | Tutti i dati raccolti vengono archiviati nell'archiviazione BLOB. Questi dati vengono utilizzati per segnare gli utenti in base alle competenze e all'avanzamento dei risultati. Ad esempio, vediamo se un utente ha un set di risposte fuori sede. Questo valore influisce sull'avanzamento delle competenze. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia usa l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Notes.Read | application | Usiamo i dati raccolti per segnare lo stato di avanzamento degli utenti su competenze e risultati. Vengono raccolti i conteggi di utilizzo in più carichi di lavoro di O365. | Tutti i dati raccolti vengono archiviati nell'archiviazione BLOB. Questi dati vengono utilizzati per segnare gli utenti in base alle competenze e all'avanzamento dei risultati. Ad esempio, viene contato il numero di blocchi appunti condivisi da un utente. Questo valore influisce sull'avanzamento delle competenze. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia usa l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Reports.Read.All | application | Usiamo i dati raccolti per segnare lo stato di avanzamento degli utenti su competenze e risultati. Vengono raccolti i conteggi di utilizzo in più carichi di lavoro di O365. | Tutti i dati raccolti vengono archiviati nell'archiviazione BLOB. Questi dati vengono utilizzati per segnare gli utenti in base alle competenze e all'avanzamento dei risultati. Ad esempio, recuperiamo dall'utente il numero Teams messaggi inviati in un giorno. Questo valore influisce sull'avanzamento delle competenze. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia usa l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Sites.Read.All | application | Usiamo i dati raccolti per segnare lo stato di avanzamento degli utenti su competenze e risultati. Vengono raccolti i conteggi di utilizzo in più carichi di lavoro di O365. | Tutti i dati raccolti vengono archiviati nell'archiviazione BLOB. Questi dati vengono utilizzati per segnare gli utenti in base alle competenze e all'avanzamento dei risultati. Ad esempio, viene contato il numero di raccolte siti create dall'utente. Questo valore influisce sull'avanzamento delle competenze. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia usa l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| User.Read | application | Vengono visualizzati il nome visualizzato, il reparto e l'immagine del profilo dell'utente. | Il nome visualizzato e il reparto vengono salvate nel database in modo che non sia necessario Graph ogni volta. L'immagine del profilo non viene archiviata. | Creiamo un nuovo ID applicazione per ogni cliente. Ad esempio, il tenant Nulia usa l'ID applicazione: 623B1D5D-6D82-493E-9990-1FBFE82ED046 |
>| Organization.Read.All | application | Raccogliamo il nome del tenant e l'YAMMER di base. Lo usiamo per avviare Yammer quando l'utente fa clic su un pulsante Prova nella nostra app relativa alle Yammer &quot; &quot; attività. | Tutti i dati raccolti vengono archiviati nell'archiviazione BLOB. Ad esempio, lo usiamo per avviare Yammer quando l'utente fa clic su un pulsante Prova nella nostra app relativa alle Yammer &quot; &quot; attività. | Usiamo i dati raccolti per segnare lo stato di avanzamento degli utenti su competenze e risultati. Vengono raccolti i conteggi di utilizzo in più carichi di lavoro di O365. |


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

>Non controlliamo i dati nei sistemi partner

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Nulia su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
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
