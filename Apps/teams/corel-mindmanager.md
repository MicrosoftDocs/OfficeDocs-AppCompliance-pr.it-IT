---
title: Informazioni sull'applicazione per MindManager da Corel
ms.author: elmalova
author: elenamalova
ms.date: 06/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per MindManager, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f9cd3639b4c7abf8cb5472213e11faa879fb7917
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411090"
---
# <a name="mindmanager"></a>MindManager

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 3, 2021</p>

* <a href="https://teams.microsoft.com/l/app/cebe4a59-b076-47f3-a7bf-79148daf82f7" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002261" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Corel a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | MindManager |
| ID | WA200002261 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Corel |
| URL del sito Web del partner | [https://www.mindmanager.com](https://www.mindmanager.com) |
| URL dell'informativa sulla privacy | [https://www.corel.com/en/corel-privacy-policy/](https://www.corel.com/en/corel-privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://www.mindjet.com/go/mmcloudterms](https://www.mindjet.com/go/mmcloudterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Corel su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Send | delegated | Informazioni sulle modifiche apportate all'interno di un file MindManager che possono quindi essere pubblicate come messaggio | metadati dei file, contenuto del file: per il browser dei file, l'utente può esplorare i propri file per aprire un file MindManager (con estensione mmap). | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| Chat.Send | delegated | Informazioni sulle modifiche apportate all'interno di un file MindManager che possono quindi essere pubblicate come messaggio | metadati dei file, contenuto del file: per il browser dei file, l'utente può esplorare i propri file per aprire un file MindManager (con estensione mmap). | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| Files.ReadWrite | delegated | elenco dei siti, presentazione delle cartelle, metadati dei file, contenuto dei file: per il browser dei file, l'utente può esplorare i propri file per aprire un file MindManager (con estensione mmap). | - Dati del profilo: per identificare l'utente e mostrare il proprio profilo - contenuto del file: durante la sessione di co-modifica (modifica collaborativa in tempo reale sui file con estensione mmap di MindManager) | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| Sites.ReadWrite.All | delegated | elenco dei siti, presentazione delle cartelle, metadati dei file, contenuto dei file: per il browser dei file, l'utente può esplorare i propri file per aprire un file MindManager (con estensione mmap). | contenuto dei file: durante la sessione di modifica in modalità co-modifica (modifica collaborativa in tempo reale sui file con estensione mmap di MindManager) | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| User.Read | delegated | dati del profilo: per identificare l'utente e mostrare il proprio profilo | dati del profilo: per identificare l'utente e mostrare il proprio profilo | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |
>| offline_access | delegated | In questo modo è possibile salvare un file nel percorso originale per conto dell'utente in un secondo momento, se necessario. | contenuto dei file: durante la sessione di modifica in modalità co-modifica (modifica collaborativa in tempo reale sui file con estensione mmap di MindManager) | [51e2b67d-9854-446a-8da1-cdd89ef0b987](https://docs.microsoft.com/microsoft-365-app-certification/azure/51e2b67d-9854-446a-8da1-cdd89ef0b987) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Amazon Web Services | Nome organizzazione, Dominio organizzazione | L'organizzazione necessita di una configurazione dell'account all'interno dell'infrastruttura applicativa per usare l'applicazione all'interno Teams |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Qui sono stati trattati: https://www.mindjet.com/go/mmcloudterms

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/38778' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/38778" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Corel sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

