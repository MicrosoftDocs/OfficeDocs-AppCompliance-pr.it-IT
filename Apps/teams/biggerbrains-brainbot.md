---
title: Informazioni sull'applicazione per BrainBot di Biggerbrains
ms.author: elmalova
author: elenamalova
ms.date: 04/28/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per BrainBot, i criteri di gestione dei dati, le informazioni del catalogo app di Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 74b3ca5d6a674ea7322995eb9941dadcd939b01c
ms.sourcegitcommit: 84c041bf4c0e79f1f3a14c4885ca5acd8709b129
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/06/2021
ms.locfileid: "52258863"
---
# <a name="brainbot"></a>BrainBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: April 28, 2021</p>

* <a href="https://teams.microsoft.com/l/app/3c95872f-ca12-456e-84b9-c717fe93330c" target="_blank">Visualizzazione in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381981" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Biggerbrains a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | BrainBot |
| ID | WA104381981 |
| Funzionalità | Bot |
| Client di Office 365 supportati | Microsoft Teams |
| Nome società partner | Biggerbrains |
| URL del sito Web del partner | [https://brainbot.ai](https://brainbot.ai) |
| URL della pagina delle informazioni dell'applicazione Teams | [https://brainbot.ai](https://brainbot.ai) |
| URL dell'informativa sulla privacy | [https://brainbot.ai/privacypolicy/](https://brainbot.ai/privacypolicy/) |
| URL delle Condizioni per l'utilizzo | [https://brainbot.ai/terms/](https://brainbot.ai/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Biggerbrains su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni di Microsoft Graph necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | application | Usiamo i nomi completi &amp; degli indirizzi di posta elettronica come parte del processo di autenticazione. Inoltre, gli indirizzi di posta elettronica vengono utilizzati per inviare sequenze di apprendimento all'utente quando ha sottoscritto una | Usiamo i nomi completi &amp; degli indirizzi di posta elettronica come parte del processo di autenticazione. Inoltre, gli indirizzi di posta elettronica vengono utilizzati per inviare sequenze di apprendimento all'utente quando ha sottoscritto una | b256b34a-b377-4fc2-b25a-a8f5f0594e86 |


#### <a name="non-microsoft-services-used"></a>Servizi non Microsoft utilizzati

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>I servizi non Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Usiamo i nomi completi &amp; degli indirizzi di posta elettronica come parte del processo di autenticazione. Inoltre, gli indirizzi di posta elettronica vengono utilizzati per inviare sequenze di apprendimento all'utente quando ha sottoscritto una | Nomi completi degli &amp; indirizzi di posta elettronica | Vengono usati per l'accesso e come parte della funzionalità dell'app per inviare sequenze di apprendimento all'utente quando ne ha sottoscritto una |



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>le risposte degli utenti alle valutazioni della formazione vengono archiviate fino a quando l'utente o l'organizzazione non ne ha richiesto la rimozione.  Gli account inattivi vengono eliminati dopo 12 mesi. 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>n/d, non vengono archiviati dati nei sistemi partner

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [catalogo di Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Informazioni sulla sicurezza delle app cloud Microsoft' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37584' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37584" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Biggerbrains su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di controllo per l'integrazione della piattaforma di identità Microsoft?  | No |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | No |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- Flusso implicito OAuth2, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
