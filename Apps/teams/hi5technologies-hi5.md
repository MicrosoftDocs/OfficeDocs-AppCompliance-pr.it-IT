---
title: Informazioni sull'applicazione per Hi5 di Hi5Technologies
ms.author: elmalova
author: elenamalova
ms.date: 07/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Hi5, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 1356b3e31e309379e1943dc5ca59e10c72c23410
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59281257"
---
# <a name="hi5"></a>Hi5

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 21, 2021</p>

* <a href="https://teams.microsoft.com/l/app/ca334a56-72b5-4613-81d4-77b1148df03c" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001610" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Hi5Technologies a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Hi5 |
| ID | WA200001610 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Hi5Technologies |
| URL del sito Web del partner | [https://www.get5.io](https://www.get5.io) |
| URL della Teams info dell'applicazione | [https://help.get5.io](https://help.get5.io) |
| URL dell'informativa sulla privacy | [https://www.get5.io/privacy](https://www.get5.io/privacy) |
| URL delle Condizioni per l'utilizzo | [https://www.get5.io/terms](https://www.get5.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Hi5Technologies sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegated | Vengono archiviate solo le informazioni sulla sessione degli utenti da Teams e l'utente deve approvarlo aggiungendo notifiche (possono rimuoverle in qualsiasi momento). Non vengono archiviate altre informazioni. | Obbligatorio per l'accesso SSO e l'autenticazione nel server | [7cb50e3e-0427-409e-90d2-638eb28217c3](https://docs.microsoft.com/microsoft-365-app-certification/azure/7cb50e3e-0427-409e-90d2-638eb28217c3) |
>| email | delegated | Vengono archiviate solo le informazioni sulla sessione degli utenti da Teams e l'utente deve approvarlo aggiungendo notifiche (possono rimuoverle in qualsiasi momento). Non vengono archiviate altre informazioni. | Obbligatorio per l'accesso SSO e l'autenticazione nel server | [7cb50e3e-0427-409e-90d2-638eb28217c3](https://docs.microsoft.com/microsoft-365-app-certification/azure/7cb50e3e-0427-409e-90d2-638eb28217c3) |
>| offline_access | delegated | Vengono archiviate solo le informazioni sulla sessione degli utenti da Teams e l'utente deve approvarlo aggiungendo notifiche (possono rimuoverle in qualsiasi momento). Non vengono archiviate altre informazioni. | Mantiene che l'utente veda le informazioni corrette e possiamo inviare le informazioni corrette ad altri utenti che aderiscono alla stessa società/area di lavoro. | [7cb50e3e-0427-409e-90d2-638eb28217c3](https://docs.microsoft.com/microsoft-365-app-certification/azure/7cb50e3e-0427-409e-90d2-638eb28217c3) |
>| openid | delegated | Vengono archiviate solo le informazioni sulla sessione degli utenti da Teams e l'utente deve approvarlo aggiungendo notifiche (possono rimuoverle in qualsiasi momento). Non vengono archiviate altre informazioni. | Obbligatorio per l'accesso SSO e l'autenticazione nel server | [7cb50e3e-0427-409e-90d2-638eb28217c3](https://docs.microsoft.com/microsoft-365-app-certification/azure/7cb50e3e-0427-409e-90d2-638eb28217c3) |
>| profilo | delegated | Vengono archiviate solo le informazioni sulla sessione degli utenti da Teams e l'utente deve approvarlo aggiungendo notifiche (possono rimuoverle in qualsiasi momento). Non vengono archiviate altre informazioni. | Obbligatorio per l'accesso SSO e l'autenticazione nel server | [7cb50e3e-0427-409e-90d2-638eb28217c3](https://docs.microsoft.com/microsoft-365-app-certification/azure/7cb50e3e-0427-409e-90d2-638eb28217c3) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Per notificare all'utente in un canale che gli è stato assegnato un Hi5 | Non vengono archiviate informazioni, l'utente sarà @ solo dalla scheda inviata di nuovo nel canale | Non vengono archiviate informazioni, l'utente sarà @ solo dalla scheda inviata di nuovo nel canale |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>No, Hi5 è semplicemente iFramed in e tutti i dati vengono archiviati in modo sicuro.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Stiamo usando OAuth e forniamo 3 opzioni di accesso:
- Googles SSO (OAuth).
- Microsoft SSO (OAuth).
- La nostra crittografia, che è una combinazione di crittografia SHA e AES.
Dopo l'autenticazione e l'accesso, il livello di autorizzazione concede l'accesso alle sezioni autorizzate all'interno della piattaforma Hi5.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalogo vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Hi5Technologies sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | No |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | Sì |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
