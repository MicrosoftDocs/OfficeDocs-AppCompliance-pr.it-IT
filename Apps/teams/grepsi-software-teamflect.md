---
title: Informazioni sull'applicazione per Teamflect di Grepsi Software
ms.author: elmalova
author: elenamalova
ms.date: 08/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e conformità disponibili per Teamflect, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 99c3dad8bedb9cf986207cb577ca7d58aa8cbef1
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410229"
---
# <a name="teamflect"></a>Teamflect

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 17, 2021</p>

* <a href="https://teams.microsoft.com/l/app/e46015e9-f2ae-4dbc-be6b-f05043192e62" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001860" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Grepsi Software a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Teamflect |
| ID | WA200001860 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Grepsi Software |
| URL del sito Web del partner | [https://teamflect.com](https://teamflect.com) |
| URL dell'informativa sulla privacy | [https://www.teamflect.com/privacy](https://www.teamflect.com/privacy) |
| URL delle Condizioni per l'utilizzo | [https://teamflect.com/terms](https://teamflect.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Grepsi Software su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | application | Questa autorizzazione viene utilizzata per accedere ai calendari degli utenti per identificare le riunioni 1-on-1 | I metadati degli elementi del calendario vengono archiviati nei database | [c5da92a9-873e-4ea1-86c7-03ec9c1384f0](https://docs.microsoft.com/microsoft-365-app-certification/azure/c5da92a9-873e-4ea1-86c7-03ec9c1384f0) |
>| Directory.Read.All | delegated | Directory aziendale: questa autorizzazione viene utilizzata per visualizzare agli utenti finali un elenco dei colleghi quando eseguono una ricerca | n/d | [c5da92a9-873e-4ea1-86c7-03ec9c1384f0](https://docs.microsoft.com/microsoft-365-app-certification/azure/c5da92a9-873e-4ea1-86c7-03ec9c1384f0) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Mailjet | Dominio dell'organizzazione | Usiamo provider di posta elettronica di terze parti per inviare notifiche tramite posta elettronica agli utenti finali. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| L'applicazione bot invia notifiche agli utenti finali. Come parte di queste notifiche, il bot gestisce ed elabora i dati, ma questo bot è ospitato anche in Microsoft Azure Datacenter e non trasferisce dati EUII all'esterno o ai servizi di terze parti. | No |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>I dati degli utenti vengono archiviati solo se continuano a usare l'applicazione. Eliminiamo tutti i dati relativi agli utenti inattivi dopo un periodo di 5 anni o su richiesta dell'utente finale.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Microsoft usa Microsoft Azure per ospitare i server applicazioni e i database. Usiamo solo un servizio di posta elettronica di terze parti per recapitare notifiche tramite posta elettronica ai nostri utenti. Questo sistema di posta elettronica di terze parti archivia gli indirizzi di posta elettronica dell'utente finale, ma è controllato da microsoft in base ai criteri di conservazione e privacy dei dati.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Grepsi Software sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | BlockAccess, RequireMFA |
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

