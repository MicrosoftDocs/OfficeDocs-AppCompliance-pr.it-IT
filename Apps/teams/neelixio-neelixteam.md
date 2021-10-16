---
title: Informazioni sull'applicazione per Neelix.Team da Neelix.IO
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e conformità disponibili per Neelix.Team, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c67a0cb706d4e9651b40dc4070ed9608cbd858d5
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413638"
---
# <a name="neelixteam"></a>Neelix.Team

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 10, 2021</p>

* <a href="https://teams.microsoft.com/l/app/bed170ee-dbd7-4efa-b48e-b0937ded1689" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003047" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Neelix.IO a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Neelix.Team |
| ID | WA200003047 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Neelix.IO |
| URL del sito Web del partner | [https://www.neelix.team](https://www.neelix.team) |
| URL della Teams info dell'applicazione | [https://www.neelix.team](https://www.neelix.team) |
| URL dell'informativa sulla privacy | [https://www.neelix.team/data-security-policy](https://www.neelix.team/data-security-policy) |
| URL delle Condizioni per l'utilizzo | [https://www.neelix.io/terms-of-use-en](https://www.neelix.io/terms-of-use-en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Neelix.IO su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegated | l'app usa ID e nomi di canale per offrire agli utenti la comodità di gestire le preferenze predefinite quando inviano feedback da MS Treams | Gli ID canale e i nomi vengono archiviati per la gestione delle impostazioni predefinite per comodità degli utenti | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| Team.ReadBasic.All | delegated | l'app usa id e nomi del team per offrire agli utenti la comodità di gestire le preferenze predefinite quando inviano feedback da MS Treams | vengono archiviati gli ID e i nomi del team. Questi dati ci consentono di configurare impostazioni predefinite di comodità che consentono il completamento più rapido del modulo di feedback. | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| email | delegated | la posta elettronica viene utilizzata come parte della registrazione dell'utente all'interno di Neelix. Dopo la registrazione iniziale, la posta elettronica viene usata per le notifiche.  | la posta elettronica viene archiviata nel profilo utente. La posta elettronica viene utilizzata anche per controllare che l'utente non teni di usare la stessa posta elettronica tramite un altro canale oauth. | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| offline_access | delegated | Usato per ottenere il token di aggiornamento |  il token di aggiornamento viene archiviato per ottenere un nuovo token di accesso | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| profile | delegated | Il nome utente viene utilizzato per creare un account utente durante la registrazione con Neelix.  | Il nome utente viene archiviato nell'account utente. Ciò è necessario perché l'utente sia riconosciuto da altri membri del team nel journal del team. L'utente può aggiornare il nome archiviato in Neelix. | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| User.Read | delegated | L'app bot usa user.read per poter inviare informazioni all'utente in modo che la piattaforma di base Neelix possa identificare l'utente | Le informazioni non vengono archiviate | [bed170ee-dbd7-4efa-b48e-b0937ded1689](https://docs.microsoft.com/microsoft-365-app-certification/azure/bed170ee-dbd7-4efa-b48e-b0937ded1689) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Microsoft Identity Platform | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Gli ID tenant vengono inviati al servizio back-end in esecuzione in Google Cloud Platform | ID tenant | Gli ID tenant vengono utilizzati per l'identificazione dell'utente durante oauth |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| L'app usa l'ID utente per identificare l'utente in base alle informazioni registrate nella piattaforma Neelix | No |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Gli ID tenant vengono registrati nei registri di sistema. I criteri di conservazione dei registri sono di 30 giorni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Criteri degli utenti finali, procedure di conformità al GDPR, procedure di annullamento dell'account e di acrichival dei dati

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Neelix.IO su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

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

