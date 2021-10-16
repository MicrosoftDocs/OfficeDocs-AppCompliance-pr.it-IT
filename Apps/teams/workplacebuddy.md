---
title: Informazioni sull'applicazione per WorkplaceBuddy di WorkplaceBuddy
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per WorkplaceBuddy, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: bd37d51a5316ba906d6e7fc1314fe2974d1aa502
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412686"
---
# <a name="workplacebuddy"></a>WorkplaceBuddy

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 23, 2021</p>

* <a href="https://teams.microsoft.com/l/app/6fef6052-d84d-4071-b679-8b542512a621" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001238" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da WorkplaceBuddy a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | WorkplaceBuddy |
| ID | WA200001238 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | WorkplaceBuddy |
| URL del sito Web del partner | [https://www.workplacebuddy.com](https://www.workplacebuddy.com) |
| URL della Teams info dell'applicazione | [https://www.workplacebuddy.com](https://www.workplacebuddy.com) |
| URL dell'informativa sulla privacy | [https://www.workplacebuddy.com/privacy-policy.pdf](https://www.workplacebuddy.com/privacy-policy.pdf) |
| URL delle Condizioni per l'utilizzo | [https://www.workplacebuddy.com/terms-of-use.pdf](https://www.workplacebuddy.com/terms-of-use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da WorkplaceBuddy su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegated | Questi dati vengono sincronizzati per consentire alle schede di WorkplaceBuddy Teams di lavorare e per selezionare utenti specifici con il chatbot | Solo nome, ID e membri | [39073da9-c47c-4da8-b57a-3786461db8f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/39073da9-c47c-4da8-b57a-3786461db8f4) |
>| Group.Read.All | delegated | Questi dati vengono sincronizzati per consentire alle schede di WorkplaceBuddy Teams di lavorare e per selezionare utenti specifici con il chatbot | Solo nome, ID e membri | [39073da9-c47c-4da8-b57a-3786461db8f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/39073da9-c47c-4da8-b57a-3786461db8f4) |
>| User.Read | delegated | Questi dati vengono sincronizzati per consentire agli utenti di accedere | Name, Email, Profile Picture, ID | [39073da9-c47c-4da8-b57a-3786461db8f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/39073da9-c47c-4da8-b57a-3786461db8f4) |
>| User.ReadBasic.All | delegated | Questi dati vengono sincronizzati per consentire agli utenti di accedere | Name, Email, Profile Picture, ID | [39073da9-c47c-4da8-b57a-3786461db8f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/39073da9-c47c-4da8-b57a-3786461db8f4) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Questi dati sono necessari per offrire un'esperienza personalizzata | Nome, E-mail, ID | Questi dati sono necessari per offrire un'esperienza personalizzata |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>N/D

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da WorkplaceBuddy sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/><br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

