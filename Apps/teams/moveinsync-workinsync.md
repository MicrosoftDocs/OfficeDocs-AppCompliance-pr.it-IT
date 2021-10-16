---
title: Informazioni sull'applicazione per WorkInSync da MoveInSync
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per WorkInSync, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 746a7b7c52d8905aaf65d86bc0f15202f486eb82
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413658"
---
# <a name="workinsync"></a>WorkInSync

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 1, 2021</p>

* <a href="https://teams.microsoft.com/l/app/4e00663a-be72-4de1-a163-269a477a7a6e" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002974" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da MoveInSync a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | WorkInSync |
| ID | WA200002974 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | MoveInSync |
| URL del sito Web del partner | [https://www.workinsync.io](https://www.workinsync.io) |
| URL della Teams info dell'applicazione | [https://www.workinsync.io/teams-app-for-workinsync/](https://www.workinsync.io/teams-app-for-workinsync/) |
| URL dell'informativa sulla privacy | [https://www.workinsync.io/privacy-policy/](https://www.workinsync.io/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://www.workinsync.io/terms-and-condition/](https://www.workinsync.io/terms-and-condition/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da MoveInSync sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegated | 1. Per ottenere i dettagli dei membri del gruppo transitivi. Vengono usati nella scheda Attività del team quando vengono installati nel contesto del canale. 2. Per ottenere l'elenco dei dettagli del profilo utente &amp;  connesso degli utenti nell'organizzazione. Vengono usati quando la scheda Attività del team viene installata nel contesto personale, come fall back per visualizzare l'anteprima dei membri del team in caso di errore dell'API degli utenti (utenti non outlook) | Nessuno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| People.Read | delegated | Per far in modo che le persone più correlate all'utente connesso siano mostrate nella scheda Attività del team viene installata nel contesto personale. | Nessuno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| Presence.Read | delegated | Per ottenere informazioni sulla presenza di un elenco di utenti nella scheda Attività del team sia nel contesto personale che nel contesto del canale | Nessuno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| Presence.Read.All | delegated | Per ottenere informazioni sulla presenza di un elenco di utenti nella scheda Attività del team sia nel contesto personale che nel contesto del canale | Nessuno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| User.Read.All | application | Usato per ottenere informazioni sul responsabile della segnalazione di qualsiasi utente per inviare notifiche di prenotazione e archiviazione/estrazione al responsabile | Nessuno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| User.ReadBasic.All | delegated | Usato per leggere la foto del profilo del dipendente | Nessuno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| email | delegated | Necessario per ottenere il token SSO usando Teams client | Nessuno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| offline_access | delegated | Necessario per ottenere il token SSO usando Teams client | Nessuno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| openid | delegated | Necessario per ottenere il token SSO usando Teams client | Nessuno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| profile | delegated | Necessario per ottenere il token SSO usando Teams client | Nessuno | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 1. Viene letto l'indirizzo di posta elettronica del dipendente (nome del principio utente) in modo che corrisponda all'elenco degli utenti registrati con WorkInSync.  | No |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati non vengono condivisi con o archiviati nei sistemi partner. Tutti gli archivi dati sono completamente di proprietà e gestiti solo da WorkInSync.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da MoveInSync sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Autenticazione a più fattori |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/><br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

