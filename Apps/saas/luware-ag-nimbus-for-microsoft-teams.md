---
title: Informazioni sull'applicazione per Luware Nimbus per Microsoft Teams da Luware AG
ms.author: elmalova
author: elenamalova
ms.date: 10/07/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e conformità disponibili per Luware Nimbus per Microsoft Teams, i criteri di gestione dei dati, le informazioni sul catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 34991a9d979fb497a02c074ade1bd8a7f8faea0d
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430536"
---
# <a name="luware-nimbus-for-microsoft-teams"></a>Luware Nimbus per Microsoft Teams

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: October 1, 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/luwareagzurich.advanced_routing_azure_marketplace" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Luware AG a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Luware Nimbus per Microsoft Teams |
| ID | luwareagzurich.advanced_routing_azure_marketplace |
| Nome società partner | Luware AG |
| URL del sito Web del partner | [https://luware.com](https://luware.com) |
| URL dell'informativa sulla privacy | [https://luware.com/en/privacy-policy](https://luware.com/en/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://luware.com/en/agreements/saas/](https://luware.com/en/agreements/saas/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Luware AG su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegated | Console Operatore: leggere Calendario dell'utente connesso mostra calendario con appuntamenti | Nessuno | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Calendars.Read.Shared | delegated | Console Operatore: leggere Calendari condivisi per visualizzare il calendario con gli appuntamenti | Nessuno | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Contacts.Read | delegated | Console Operatore: cercare nella Exchange contatti dell'utente connesso | Nessuno | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Contacts.Read.Shared | delegated | Console Operatore: ricerca nei contatti Exchange condivisi | Nessuno | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| GroupMember.Read.All | application | Ottenere membri del team, leggere i gruppi di sicurezza | Queste informazioni vengono archiviate quando gli agenti del servizio clienti vengono gestiti tramite appartenenze a gruppi | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Presence.Read.All | delegated | Pagina Mostra presenza nella ricerca contatti nella console operatore | Nessuno | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| User.Read | delegated | Ottenere UserInformation (dall'utente connesso) | Nessuno | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| User.Read.All | entrambi | App Nimbus - Ottenere CallerInformation. In una chiamata interna al centro contatti viene esempta una ricerca inversa su chi potrebbe essere, in modo da poter mostrare queste informazioni all'agente. Nella Console operatore (con autorizzazione delegata) viene ricercata l'intera directory interna per le destinazioni di trasferimento. | Per i report REasons su chi ha chiamato di più, archiviamo i dati. | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| User.ReadBasic.All | delegated | Ricerca utente limitata | Nessuno | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Calls.AccessMedia.All | application | Molte di queste app/bot (una per coda del Centro contatti): sottoscrivere toni DTMF in cui il cliente può effettivamente selezionare la sua posizione nell'IVR | Tutte le informazioni DTMF per i modi selezionati tramite il sistema IVR per il motivo della segnalazione | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |
>| Calls.Initiate.All | application | Molte di queste app/bot (una per coda del Contact Center): effettuare chiamate all'agente  | Tutte le informazioni cdR per il motivo della segnalazione | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |
>| Calls.InitiateGroupCall.All | application | Molte di queste app/bot (una per coda del Contact Center): effettuare chiamate all'agente  | Tutte le informazioni cdR per il motivo della segnalazione | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |
>| Calls.JoinGroupCall.All | application | Molte di queste app/bot (una per coda del Centro contatti): partecipare a una chiamata inoltrata per riprodurre gli annunci | Tutte le informazioni cdR per il motivo della segnalazione | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Dati di report aggregati (Call Detail Records, informazioni sul chiamante, trattamento delle chiamate e dettagli del percorso delle chiamate e così via): 24 mesi Dati di configurazione: Durata del contratto del cliente +30 giorni Registri applicazioni: archiviazione temporanea dei registri delle applicazioni interne (per aiutare i tecnici del supporto tecnico a risolvere i problemi relativi alle prestazioni e al funzionamento dei componenti dell'applicazione) 30 giorni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>https://luware.com/en/privacy-policy/

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Luware AG su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | App client, utenti e gruppi |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | Sì |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
