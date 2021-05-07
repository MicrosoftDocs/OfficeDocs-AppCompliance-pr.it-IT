---
title: Informazioni sull'applicazione per Tikit di Cireson
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Tikit, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c30afd0d75f8832bf94fedbf48cd64406a5a2a29
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252716"
---
# <a name="tikit"></a>Tikit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 11, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b13c40ee-e073-459e-96b5-3f3cca046a37" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002602" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Cireson a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Tikit |
| ID | WA200002602 |
| Funzionalità | Bot, estensione per la messaggistica |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Cireson |
| URL del sito Web del partner | [https://tikit.ai](https://tikit.ai) |
| URL della pagina Teams informazioni sull'applicazione | [https://tikit.ai](https://tikit.ai) |
| URL dell'informativa sulla privacy | [https://tikit.ai/privacy-statement](https://tikit.ai/privacy-statement) |
| URL delle Condizioni per l'utilizzo | [https://tikit.ai/terms-service](https://tikit.ai/terms-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Cireson su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Device.Read | application | Informazioni del grafico utente usate per l'accesso Single #A0 tramite la comunicazione bot di Teams  | Vengono archiviati i ruoli utente, il nome della famiglia, il nome, l'indirizzo di posta elettronica, l'ID AAD Teams ID utente. Questa informazione viene utilizzata per l'autenticazione delle applicazioni, la sicurezza, il controllo degli accessi in base al ruolo, l'integrazione dei team, le notifiche di Teams e il mapping delle relazioni utente   | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.AccessAsUser.All | delegated | Nomi e ruoli dei gruppi per il controllo degli accessi in base al ruolo | Nome gruppo &amp; Nome ruolo, è necessario fornire un controllo di accesso mappato sicuro. | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.Read.All | delegated | Nomi e ruoli dei gruppi per il controllo degli accessi in base al ruolo | Nome gruppo &amp; Nome ruolo, è necessario fornire un controllo di accesso mappato sicuro. | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Group.Read.All | entrambi | Nomi e ruoli dei gruppi per il controllo degli accessi in base al ruolo | Nomi e ruoli dei gruppi per il controllo degli accessi in base al ruolo | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read | delegated | Ruoli utente, nome della famiglia, nome specificato, posta elettronica, ID AAD, Teams ID utente, utilizzato per l'autenticazione  | Ruoli utente, nome della famiglia, nome specificato, posta elettronica, ID AAD, Teams ID utente, utilizzato per l'autenticazione  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read.All | application | Ruoli utente, nome della famiglia, nome specificato, posta elettronica, ID AAD, Teams ID utente, utilizzato per l'autenticazione  | Ruoli utente, nome della famiglia, nome specificato, posta elettronica, ID AAD, Teams ID utente, utilizzato per l'autenticazione  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.ReadBasic.All | delegated | Ruoli utente, nome della famiglia, nome specificato, posta elettronica, ID AAD, Teams ID utente, utilizzato per l'autenticazione  | Ruoli utente, nome della famiglia, nome specificato, posta elettronica, ID AAD, Teams ID utente, utilizzato per l'autenticazione  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| e-mail | delegated | Posta elettronica utente utilizzata per l'accesso e identificazione associata di entità correlate. &quot;Utente assegnato&quot; | Posta elettronica utente utilizzata per l'accesso e identificazione associata di entità correlate. &quot;Utente assegnato&quot; | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| openid | delegated | utilizzato per l'autenticazione tramite MSAL per requisiti  | utilizzato per l'autenticazione tramite MSAL per requisiti  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| profilo | delegated | utilizzato per l'autenticazione tramite MSAL per requisiti  | utilizzato per l'autenticazione tramite MSAL per requisiti  | b13c40ee-e073-459e-96b5-3f3cca046a37 |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| QnA Maker | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Nome e posta elettronica per le relazioni tra entità utente &quot; Richiedente ticket&quot;  | Nome e posta elettronica  | per le relazioni tra entità utente &quot; Richiedente ticket&quot;  |



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Archiviamo il nome dell'azienda, l'ID tenant, la posta elettronica, l'ID client bot nelle informazioni dettagliate sull'app, con un criterio di conservazione a 30 dat.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Non abbiamo dati in un sistema partner.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Cireson sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

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
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | Sì |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
