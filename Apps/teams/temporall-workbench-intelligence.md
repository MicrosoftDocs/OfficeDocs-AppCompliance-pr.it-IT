---
title: Informazioni sull'applicazione per Workbench Intelligence di Temporall
ms.author: elmalova
author: elenamalova
ms.date: 09/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Workbench Intelligence, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: bf2a249e9eb0cf8e572158d9b393b49fc81153ff
ms.sourcegitcommit: d5c60e66355ffa8fb84565e565f8bb15a665a099
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/24/2021
ms.locfileid: "59785471"
---
# <a name="workbench-intelligence"></a>Workbench Intelligence

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 22, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d5630318-189a-4912-abae-99b1f8f82cce" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002705" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Temporall a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Workbench Intelligence |
| ID | WA200002705 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Temporall |
| URL del sito Web del partner | [https://www.temporall.com](https://www.temporall.com) |
| URL della Teams info dell'applicazione | [https://www.temporall.com/teams_intelligence/](https://www.temporall.com/teams_intelligence/) |
| URL dell'informativa sulla privacy | [https://temporall.com/privacy-policy/](https://temporall.com/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://www.temporall.com/eula](https://www.temporall.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Temporall su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.Read.All | delegated | Ottiene un elenco di app di teams installate per ottenere l'ID app locale per l'ID esterno noto. | ID dell'app locale. È necessario essere in grado di identificare l'app quando viene installata in un tenant diverso. | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Channel.ReadBasic.All | application | Nome ID &amp; canale. Giustificazione: consentire l'aggiunta/uscita dal canale per sincronizzare l'attività dei messaggi.  | Oggetto dati non elaborati restituito dal canale di recupero. Giustificazione: Temporall Workbench consente agli utenti di filtrare e classificare i dati in base ai canali. Questi dati non elaborati vengono salvati per fare riferimento all'oggetto originale | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| ChannelMessage.Read.All | application | Tipo di attività &amp; del messaggio, insieme alla destinazione del &amp; mittente. Dati ricevuti da queste route: /teams/${teamId}/channels/${channelId}/messages /teams/${teamId}/channels/${channelId}/messages/${messageId}. Giustificazione: per poter calcolare il report delle metriche &amp; sull'attività dei messaggi. Questo costituisce il fulcro del modulo di analisi della rete organizzativa per poter disegnare un diagramma di attività tra i team degli &amp; utenti. | Microsoft rileva la quantità di nuovi messaggi/risposte/reazioni/menzioni che archiviano queste metriche insieme &amp; all'oggetto messaggio non elaborato restituito. I dati sono necessari perché fanno parte delle funzionalità di base. L'esecuzione dell'analisi sui dati dei messaggi richiede che sia salvata nel database per ottenere prestazioni ottimali, riducendo inoltre la necessità di effettuare chiamate di follow-up per gli stessi dati | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Directory.Read.All | application | ClientId, Elenco di utenti, elenco di organizzazioni e canali secondari. Giustificazione: necessario per leggere gli utenti &amp; di sincronizzazione in Temporall Workbench | User Name, Email, Icon, Conversational Reference. Justification:&#160;Temporall Workbench consente agli utenti di filtrare e classificare i dati in base ai canali. I dati dell'organizzazione vengono archiviati per riconnettersi ai team dopo l'installazione | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Group.ReadWrite.All | application | Nome ID &amp; gruppo. Giustificazione: per installare l'app in ogni gruppo/canale | Nome id &amp; gruppo insieme all'oggetto dati non elaborati per riferimento. Giustificazione: Temporall Workbench consente agli utenti di filtrare e classificare i dati in base a gruppi/team. Questi dati non elaborati vengono salvati per fare riferimento all'oggetto originale | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamMember.Read.All | application | Appartenenza degli utenti al team. Giustificazione: consente la sincronizzazione di tutti gli utenti in Teams con Temporall Workbench | Indirizzo di posta elettronica, nome e cognome. Giustificazione: consentire la corrispondenza degli utenti nei team con gli utenti in Temporall Workbench per consentire la sincronizzazione degli utenti tramite posta elettronica. | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamsAppInstallation.ReadWriteForTeam.All | application | Leggi l'elenco delle app installate per Team. Giustificazione: controlla se l'app è già installata altrimenti la installa per essere in grado di ottenere l'attività dei messaggi tramite l'api graph | N/D | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamsAppInstallation.ReadWriteForUser.All | application | Leggi l'elenco delle app installate. Controlla se l'app è già installata altrimenti la installa per interagire con l'utente tramite un questionario | ND | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| User.Read | delegated | Informazioni di base &amp; sull'azienda dell'utente. Giustificazione: usato per classificare l'attività dei messaggi per utente, consente al bot di partecipare alla messaggistica proattiva. | User Name, Email, Icon, Conversational Reference. Giustificazione: consente al bot di inviare in modo proattivo messaggi agli utenti con informazioni pertinenti. Utenti del gruppo per la visualizzazione dei dati | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Cloud | Informazioni LDAP | La nostra piattaforma risiede sulla piattaforma Google Cloud |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>https://temporall.com/privacy-policy/

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

Queste informazioni sono state fornite da Temporall su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

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
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | Sì |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
