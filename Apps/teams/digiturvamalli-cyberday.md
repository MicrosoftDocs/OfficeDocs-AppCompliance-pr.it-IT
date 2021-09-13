---
title: Application Information for Cyberday by Digiturvamalli
ms.author: elmalova
author: elenamalova
ms.date: 08/09/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e conformità disponibili per Cyberday, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f2adf667a89ff8dcdd1a1f56b1f0ef91951f3eb1
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282102"
---
# <a name="cyberday"></a>Cyberday

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 9, 2021</p>

* <a href="https://teams.microsoft.com/l/app/a8e43ae4-a97b-4d1a-b364-b27794da19a4" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001774" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Digiturvamalli a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Cyberday |
| ID | WA200001774 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Digiturvamalli |
| URL del sito Web del partner | [https://cyberday.ai](https://cyberday.ai) |
| URL della Teams info dell'applicazione | [https://cyberday.ai](https://cyberday.ai) |
| URL dell'informativa sulla privacy | [https://cyberday.ai/privacy](https://cyberday.ai/privacy) |
| URL delle Condizioni per l'utilizzo | [https://cyberday.ai/terms-of-use](https://cyberday.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Digiturvamalli sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegated | Usare la posta elettronica per identificare l'utente e la visualizzazione per gli amministratori dell'app che sono questo utente | Email, Teams User ID | [1c7d277c-ff8a-4ea4-bc14-7d06314f8941](https://docs.microsoft.com/microsoft-365-app-certification/azure/1c7d277c-ff8a-4ea4-bc14-7d06314f8941) |
>| openid | delegated | Usare l'ID utente per identificare l'utente | Email, Teams User ID | [1c7d277c-ff8a-4ea4-bc14-7d06314f8941](https://docs.microsoft.com/microsoft-365-app-certification/azure/1c7d277c-ff8a-4ea4-bc14-7d06314f8941) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Heroku (Salesforce Inc.) | Teams tenant e Teams tenant | L'elaborazione di queste informazioni è necessaria per le prestazioni di un contratto in base alle condizioni per l'uso. L'ID tenant e il dominio vengono utilizzati per connettere gli utenti di Cyberday agli account dell'organizzazione corretti (ad esempio, visualizzare linee guida di sicurezza corrette). |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>I log vengono conservati, ad esempio, di accessi/autenticazione (conservazione 2 giorni), invio e recapito della posta elettronica (conservazione 90 giorni) e traffico API /errori (conservazione 90 giorni). Inoltre, se non diversamente concordato, tutti i dati controllati dal cliente inviati al servizio vengono eliminati entro sei mesi dalla risoluzione del contratto per gli utenti.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Diritti completi per gli amministratori (ad esempio eliminazione, conservazione, controllo, archiviazione) e altri requisiti impostati per i partner nei contratti di trattamento dei dati separatamente con ogni responsabile del trattamento dei dati.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalogo vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Digiturvamalli sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Tutto |
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
