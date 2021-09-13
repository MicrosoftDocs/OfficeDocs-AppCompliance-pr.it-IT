---
title: Application Information for C.AI Adoption Bot by contexxt.ai
ms.author: elmalova
author: elenamalova
ms.date: 05/06/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per C.AI Adoption Bot, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5bb11c96f750701128470f3e1c61ea0f5d476233
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59281274"
---
# <a name="cai-adoption-bot"></a>C.AI Adoption Bot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 6, 2021</p>

* <a href="https://teams.microsoft.com/l/app/f5323aab-3063-46cb-b632-ee01d95de494" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002633" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da contexxt.ai a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | C.AI Adoption Bot |
| ID | WA200002633 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | contexxt.ai |
| URL del sito Web del partner | [https://contexxt.ai](https://contexxt.ai) |
| URL della Teams info dell'applicazione | [https://contexxt.ai/cai-adoption-bot/](https://contexxt.ai/cai-adoption-bot/) |
| URL dell'informativa sulla privacy | [https://contexxt.ai/privacy-policy](https://contexxt.ai/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://contexxt.ai/terms-of-use](https://contexxt.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da contexxt.ai su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | application | Disponibilità dell'utente in grado di inviare suggerimenti al momento giusto e non durante i tempi di messa a fuoco, ad esempio | Disponibilità dell'utente anonimizzata in grado di inviare suggerimenti al momento giusto e non durante i tempi di messa a fuoco, ad esempio | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| ChannelMessage.Read.All | application | Microsoft Teams metadati del canale, ad esempio Private o no o la quantità di conversazioni per canale per analizzare l'utilizzo di Teams | Metadati del canale Microsoft Teams anonimi, ad esempio Private o no o la quantità di conversazioni per canale per analizzare l'utilizzo di Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Chat.Read.All | application | Microsoft Teams metadati della chat, ad esempio se un messaggio è stato apprezzato o quante chat di gruppo e 1:1 esistono per analizzare l'utilizzo di Teams | Metadati di chat Microsoft Teams anonimi, ad esempio se un messaggio è stato mi piace o quante chat di gruppo e 1:1 esistono per analizzare l'utilizzo di Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Directory.Read.All | application | ID oggetto utente per poter inviare suggerimenti all'utente specifico in un secondo momento. | Hash (anonimizzato) ID oggetto dell'utente per poter inviare suggerimenti per specificare l'utente in un secondo momento. | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Group.Read.All | application | Microsoft Teams metadati, ad esempio la quantità di Teams e canali per analizzare l'utilizzo di Teams | Microsoft Teams metadati, ad esempio la quantità di Teams e canali per analizzare l'utilizzo di Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Mail.Read | application | Metadati di Microsoft Exchange, ad esempio la quantità di messaggi di posta elettronica e di gruppo e messaggi di posta elettronica 1:1 per analizzare l'utilizzo di Exchange (rispetto a Teams) | Metadati di Microsoft Exchange anonimi, ad esempio la quantità di messaggi di posta elettronica e di gruppo e messaggi di posta elettronica 1:1 per analizzare l'utilizzo di Exchange (rispetto a Teams) | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| User.Read.All | application | Microsoft Teams metadati di chat e conversazioni, ad esempio se un utente è stato menzionato per analizzare l'utilizzo di Teams | Metadati di chat e conversazioni Microsoft Teams anonimi, ad esempio se un utente è stato menzionato per analizzare l'utilizzo di Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| In Bot Framework, l'ID utente verrà trasmesso automaticamente in grado di comunicare con l'utente. I dati di utilizzo aggiuntivi di C.AI Adoption Analytics vengono usati per individualizzare l'esperienza di apprendimento per l'utente, pertanto, inviando solo suggerimenti appropriati e utili agli utenti, che potrebbero non conoscere questi suggerimenti | No |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Le organizzazioni possono gestire (assegnare/rimuovere) le licenze per gli utenti. Le organizzazioni possono assegnare ruoli diversi per gestire le licenze. Gli amministratori possono sempre richiedere l'eliminazione dei propri dati.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37589' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37589" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da contexxt.ai su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

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
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
