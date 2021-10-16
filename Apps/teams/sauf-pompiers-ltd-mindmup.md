---
title: Informazioni sull'applicazione per MindMup di Sauf Pompiers Ltd
ms.author: elmalova
author: elenamalova
ms.date: 08/09/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per MindMup, i criteri di gestione dei dati, le informazioni del catalogo app di Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 75588e4a5c58969377568884cf709309026b6029
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413418"
---
# <a name="mindmup"></a>MindMup

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 9, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c12a3d54-d294-4a51-8cd3-4a48b6c7e6f2" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001759" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Sauf Pompiers Ltd a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | MindMup |
| ID | WA200001759 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Sauf Pompiers Ltd |
| URL del sito Web del partner | [https://www.mindmup.com](https://www.mindmup.com) |
| URL della Teams info dell'applicazione | [https://www.mindmup.com/tutorials/microsoft-teams.html](https://www.mindmup.com/tutorials/microsoft-teams.html) |
| URL dell'informativa sulla privacy | [https://www.mindmup.com/resources/privacy_policy.html](https://www.mindmup.com/resources/privacy_policy.html) |
| URL delle Condizioni per l'utilizzo | [https://www.mindmup.com/resources/terms_mindmup.html](https://www.mindmup.com/resources/terms_mindmup.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Sauf Pompiers Ltd su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Teams. ReadBasic.All | delegated | identificatori del team e nomi dei team per gli utenti | Per consentire agli utenti di condividere documenti con team di cui sono membri | [c12a3d54-d294-4a51-8cd3-4a48b6c7e6f2](https://docs.microsoft.com/microsoft-365-app-certification/azure/c12a3d54-d294-4a51-8cd3-4a48b6c7e6f2) |
>| User.Read | delegated | Identificatore utente, indirizzo di posta elettronica da visualizzare dopo l'autenticazione | identifer utente, indirizzo di posta elettronica | [c12a3d54-d294-4a51-8cd3-4a48b6c7e6f2](https://docs.microsoft.com/microsoft-365-app-certification/azure/c12a3d54-d294-4a51-8cd3-4a48b6c7e6f2) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Sistemi di archiviazione AWS utilizzati per salvare in modo permanente le informazioni di base dei profili utente, per supportare la condivisione di documenti e l'accesso sicuro ai documenti degli utenti in MindMup | id tenant | controllo di accesso |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>I registri di accesso di sicurezza registrano l'ID utente, l'ID tenant di Office 365 e i timestamp di accesso. Sono persistenti per prevenire frodi e abusi.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I documenti utente vengono archiviati in AWS (us-east-1), crittografati durante il transito e crittografati in pausa. i dati sono disponibili per gli utenti che hanno creato i documenti e per tutti gli utenti con cui il proprietario ha condiviso esplicitamente il documento.

Tutti gli accessi operatore/amministratore sono protetti da 2FA.

L'accesso dell'utente e dell'amministratore client viene fornito dall'autenticazione integrata Microsoft/Azure AD, con opzioni 2FA direttamente disponibili tramite SSO.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35953' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35953" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Sauf Pompiers Ltd su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/><br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

