---
title: Informazioni sull'applicazione per PagerDuty di PagerDuty, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 09/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per PagerDuty, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: a296483ba42328a306131aee8a2f29aed8d7006b
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412836"
---
# <a name="pagerduty"></a>PagerDuty

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 27, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c8c302dc-4e77-4536-890d-0c2bffbef9cc" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001637" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da PagerDuty, Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | PagerDuty |
| ID | WA200001637 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | PagerDuty, Inc. |
| URL del sito Web del partner | [https://www.pagerduty.com](https://www.pagerduty.com) |
| URL della Teams info dell'applicazione | [https://www.pagerduty.com/integrations/microsoft-teams](https://www.pagerduty.com/integrations/microsoft-teams) |
| URL dell'informativa sulla privacy | [https://www.pagerduty.com/privacy-policy/](https://www.pagerduty.com/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://www.pagerduty.com/service-terms-use/](https://www.pagerduty.com/service-terms-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da PagerDuty, Inc. Sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| OnlineMeetings.ReadWrite | delegated | Dalla creazione/risposta alle riunioni vengono utilizzati campi di questo tipo: join_web_url, audioconferenze. Questi campi sono necessari per mostrare all'utente un collegamento a una riunione o modi alternativi per connettersi durante la riunione. | Salviamo: join_web_url, audioConferencing. Questi campi sono necessari per mostrare all'utente un collegamento a una riunione o modi alternativi per connettersi durante la riunione. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadForTeam | delegated | Using for adding pagerduty app to chat. | Using for adding pagerduty app to chat. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadWriteForTeam.All | delegated | Using for adding pagerduty app to chat. | Using for adding pagerduty app to chat. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsTab.ReadWrite.All | delegated | Uso per l'aggiunta di un'app pagerduty come scheda in riunione | Uso per l'aggiunta di un'app pagerduty come scheda in riunione | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.Read | delegated | Vengono utilizzati i dati: id, userPrincipalName . Viene utilizzato per consentire agli utenti di Microsoft Teams di aggiungerli alla riunione come partecipanti | Vengono utilizzati i dati: id, userPrincipalName . Viene utilizzato per consentire agli utenti di Microsoft Teams di aggiungerli alla riunione come partecipanti | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.ReadBasic.All | delegated | Vengono utilizzati i dati: id, userPrincipalName . Viene utilizzato per consentire agli utenti di Microsoft Teams di aggiungerli alla riunione come partecipanti | Vengono utilizzati i dati: id, userPrincipalName . Viene utilizzato per consentire agli utenti di Microsoft Teams di aggiungerli alla riunione come partecipanti | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| email | delegated | Utilizzo per le richieste di autorizzazione e token. Vengono utilizzati i dati: access_token, refresh_token, expires_in, ambito | access_token, refresh_token, expires_in, ambito. Questi dati sono necessari per ottenere informazioni sulle riunioni online e degli utenti | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| offline_access | delegated | Utilizzo per le richieste di autorizzazione e token. Vengono utilizzati i dati: access_token, refresh_token, expires_in, ambito | access_token, refresh_token, expires_in, ambito. Questi dati vengono reiqured per ottenere informazioni sulle riunioni online e degli utenti | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| openid | delegated | Utilizzo per le richieste di autorizzazione e token. Vengono utilizzati i dati: access_token, refresh_token, expires_in, ambito | access_token, refresh_token, expires_in, ambito. Questi dati vengono requred per ottenere informazioni sull'utente e creare/ottenere riunioni online | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| profile | delegated | Utilizzo per le richieste di autorizzazione e token. Vengono utilizzati i dati: access_token, refresh_token, expires_in, ambito | access_token, refresh_token, expires_in, ambito. Questi dati vengono requred per ottenere informazioni sull'utente e creare/ottenere riunioni online | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| OnlineMeetings.ReadWrite | delegated | Dalla creazione/risposta alle riunioni vengono utilizzati campi di questo tipo: join_web_url, audioconferenze. Questi campi sono necessari per mostrare all'utente un collegamento a una riunione o modi alternativi per connettersi durante la riunione. | Salviamo: join_web_url, audioConferencing. Questi campi sono necessari per mostrare all'utente un collegamento a una riunione o modi alternativi per connettersi durante la riunione. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam | delegated | Uso per l'aggiunta di un'app pagerduty alla chat. | Uso per l'aggiunta di un'app pagerduty alla chat. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam.All | delegated | Uso per l'aggiunta di un'app pagerduty alla chat. | Uso per l'aggiunta di un'app pagerduty alla chat. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsTab.ReadWrite.All | delegated | Uso per l'aggiunta di un'app pagerduty come scheda in riunione | Uso per l'aggiunta di un'app pagerduty come scheda in riunione | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.Read | delegated | Vengono utilizzati i dati: id, userPrincipalName . Viene utilizzato per consentire agli utenti di Microsoft Teams di aggiungerli alla riunione come partecipanti | Vengono utilizzati i dati: id, userPrincipalName . Viene utilizzato per consentire agli utenti di Microsoft Teams di aggiungerli alla riunione come partecipanti | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.ReadBasic.All | delegated | Vengono utilizzati i dati: id, userPrincipalName . Viene utilizzato per consentire agli utenti di Microsoft Teams di aggiungerli alla riunione come partecipanti | Vengono utilizzati i dati: id, userPrincipalName . Viene utilizzato per consentire agli utenti di Microsoft Teams di aggiungerli alla riunione come partecipanti | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| email | delegated | Utilizzo per le richieste di autorizzazione e token. Vengono utilizzati i dati: access_token, refresh_token, expires_in, ambito | access_token, refresh_token, expires_in, ambito. Questi dati sono necessari per ottenere informazioni sulle riunioni online e degli utenti | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| offline_access | delegated | Utilizzo per le richieste di autorizzazione e token. Vengono utilizzati i dati: access_token, refresh_token, expires_in, ambito | access_token, refresh_token, expires_in, ambito. Questi dati sono necessari per ottenere informazioni sulle riunioni online e degli utenti | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| openid | delegated | Utilizzo per le richieste di autorizzazione e token. Vengono utilizzati i dati: access_token, refresh_token, expires_in, ambito | access_token, refresh_token, expires_in, ambito. Questi dati vengono requred per ottenere informazioni sull'utente e creare/ottenere riunioni online | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| profile | delegated | Utilizzo per le richieste di autorizzazione e token. Vengono utilizzati i dati: access_token, refresh_token, expires_in, ambito | access_token, refresh_token, expires_in, ambito. Questi dati vengono requred per ottenere informazioni sull'utente e creare/ottenere riunioni online | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| I dati mantenuti da PagerDuty sono limitati ai dati del computer dei prodotti di monitoraggio e le informazioni sulle informazioni personali sono limitate a: indirizzo di posta elettronica aziendale, nome, cognome e numero di telefono. Un elenco dei sottoprocessori con accesso a questi dati è disponibile qui: https://www.pagerduty.com/subprocessors/ | I dati mantenuti da PagerDuty sono limitati ai dati del computer dei prodotti di monitoraggio e le informazioni sulle informazioni personali sono limitate a: indirizzo di posta elettronica aziendale, nome, cognome e numero di telefono. Un elenco dei sottoprocessori con accesso a questi dati è disponibile qui: https://www.pagerduty.com/subprocessors/ | I dati mantenuti da PagerDuty sono limitati ai dati del computer dei prodotti di monitoraggio e le informazioni sulle informazioni personali sono limitate a: indirizzo di posta elettronica aziendale, nome, cognome e numero di telefono. Un elenco dei sottoprocessori con accesso a questi dati è disponibile qui: Ulteriori informazioni sulla privacy dei dati https://www.pagerduty.com/subprocessors/ sono disponibili qui: https://www.pagerduty.com/privacy-policy/ |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>PagerDuty richiede standard di sicurezza dei dati almeno quanto quelli gestiti da PagerDuty per essere gestiti da tutti i fornitori con cui trasferisciamo i dati, incluso un obbligo contrattuale sotto forma di DPA firmato. Altre info sui nostri standard di sicurezza dei dati sono disponibili qui: https://www.pagerduty.com/data-security-policy/

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da PagerDuty, Inc. Sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

