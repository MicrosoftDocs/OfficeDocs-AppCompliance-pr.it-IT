---
title: Application Information for Board Connessione by Engage Squared
ms.author: elmalova
author: elenamalova
ms.date: 02/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per Board Connessione, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: fdc58284721104fde1bb122f13532d9ecf63aabb
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/06/2021
ms.locfileid: "52250714"
---
# <a name="board-connect"></a>Board Connect

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: February 16, 2021</p>

* <a href="https://teams.microsoft.com/l/app/e8f06a4e-cefe-4b1e-a24b-c97bea471130" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001955" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Engage Squared a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Board Connect |
| ID | WA200001955 |
| Funzionalità | Scheda |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Engage Squared |
| URL del sito Web del partner | [https://boardconnect.app](https://boardconnect.app) |
| URL della pagina Teams informazioni sull'applicazione | [https://boardconnect.app](https://boardconnect.app) |
| URL dell'informativa sulla privacy | [https://boardconnect.app/privacy](https://boardconnect.app/privacy) |
| URL delle Condizioni per l'utilizzo | [https://boardconnect.app/terms](https://boardconnect.app/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Engage Squared su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegated | Per consentire all'app di aggiornare i calendari degli utenti in modo da riflettere le risposte di partecipazione alle riunioni inviate tramite l'app. | Non vengono archiviati dati all'interno dell'archivio tabelle di Azure | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| Group.ReadWrite.All | delegated | Per consentire all'app di creare, aggiornare ed eliminare eventi del calendario di gruppo. | Archiviamo l'ID del gruppo insieme all'ID tenant, che viene archiviato e usato dal punto di vista delle licenze, in modo da poter verificare che l'organizzazione sia concessa in licenza per Il consiglio di amministrazione Connessione. Viene inoltre utilizzato per tenere traccia del numero di installazioni delle applicazioni presenti all'interno del tenant in quanto questo è in linea con il modello di gestione delle licenze | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| Sites.Manage.All | delegated | Per consentire all'app di creare elenchi e raccolte, gestire gli elementi di elenco e i documenti in una raccolta siti del team. | Nessuno | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| User.Read | delegated | Per consentire agli utenti di accedere all'app e consentire all'app di leggere il profilo dell'utente attualmente connesso. | I dati di questo endpoint non vengono archiviati nell'archivio tabelle di Azure | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| User.ReadBasic.All | delegated | Per consentire all'app di leggere un set di base di proprietà del profilo di altri utenti per conto dell'utente connesso, per visualizzarlo nell'app. Sono inclusi nome visualizzato, nome e cognome, indirizzo di posta elettronica e foto. | Nessuno, i dati non vengono archiviati nell'archiviazione tabelle di Azure | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| offline_access | delegated | Per consentire all'app di ottenere un token di aggiornamento, che può usare per ottenere un nuovo token di accesso alla scadenza di quello corrente. | Nessuno, i dati non vengono archiviati all'interno dell'archivio tabelle di Azure | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |


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

>2FA per tutti gli amministratori, solo due utenti al quadrato possono accedere

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Engage Squared su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/> |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
