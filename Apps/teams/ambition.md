---
title: Informazioni sull'applicazione per l'ambizioso
ms.author: elmalova
author: elenamalova
ms.date: 08/17/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Ambition, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: d6c4a598cd115edd52e6dbd37cabd60b7a011aad
ms.sourcegitcommit: 3621f286e5bbd52acf5e0d9c8e4287fcc8c15e38
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/26/2021
ms.locfileid: "58567258"
---
# <a name="ambition"></a>Ambizioso

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 17, 2021</p>

* <a href="https://teams.microsoft.com/l/app/250ef61a-9fa3-434b-ae2a-0ecbe3f8116b" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003159" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Ambition a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Ambizioso |
| ID | WA200003159 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Ambizioso |
| URL del sito Web del partner | [https://ambition.com](https://ambition.com) |
| URL della Teams info dell'applicazione | [https://ambition.com](https://ambition.com) |
| URL dell'informativa sulla privacy | [https://ambition.com/privacy/](https://ambition.com/privacy/) |
| URL delle Condizioni per l'utilizzo | [https://ambition.com/pages/terms/](https://ambition.com/pages/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Ambition su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegated | Inviare notifiche di ambizioso al canale | Nome ID &amp; canale. | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| Group.Read.All | delegated | Configurare una notifica di un flusso di lavoro per un determinato canale all'interno di un team. | ID del nome del &amp; team. | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| User.Read | delegated | Per identificare l'amministratore che ha autorizzato l'app Ambition | Nome utente &amp; e-mail, per la sincronizzazione con gli utenti di Ambition | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| User.ReadBasic.All | delegated | I nomi degli utenti &amp; e-mail, per sincronizzare gli utenti con i loro account Diao. | Vengono archiviati i &amp; messaggi di posta elettronica dei nomi degli utenti. | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| offline_access | delegated | Per sincronizzare Microsoft Teams dati mentre gli utenti sono offline. | Il token di aggiornamento del token di accesso OAuth &amp; viene archiviato. | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| openid | delegated | Questa operazione è necessaria per usare la funzionalità di accesso di Microsoft | N/D | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| https://ambition.com/pages/subprocessors/ | Nome dipendente, Cognome, Indirizzo di posta elettronica | Scopi di visualizzazione/ricerca/filtro |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Scopi di visualizzazione.  | Nomina &amp; i messaggi di posta elettronica. | Per collegare gli utenti Microsoft ai propri account Diass. |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>https://ambition.com/privacy/

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Autorizzazioni di accesso necessarie.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

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

Queste informazioni sono state fornite da Ambition su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

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
