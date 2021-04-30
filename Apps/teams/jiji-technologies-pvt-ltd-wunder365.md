---
title: Informazioni sull'applicazione per Wunder365 di JiJi Technologies Pvt Ltd
ms.author: elmalova
author: elenamalova
ms.date: 12/15/2020
ms.topic: article
ms.service: attestation
description: Tutte le informazioni di sicurezza e conformità disponibili per Wunder365, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 0b981fe705d94b5a87414ce2c12b7cafec4c97f1
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094996"
---
# <a name="wunder365"></a>Wunder365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 15, 2020</p>

* <a href="https://teams.microsoft.com/l/app/7e8f9ad5-07d9-4259-8713-d316f451cbf3" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000742" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da JiJi Technologies Pvt Ltd a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Wunder365 |
| ID | WA200000742 |
| Funzionalità | Bot, scheda, estensione per la messaggistica |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | JiJi Technologies Pvt Ltd |
| URL del sito Web del partner | [https://www.wunder365.com](https://www.wunder365.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://www.wunder365.com/wunder365-for-office](https://www.wunder365.com/wunder365-for-office) |
| URL dell'informativa sulla privacy | [https://www.wunder365.com/teams-app-privacy-policy](https://www.wunder365.com/teams-app-privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://www.wunder365.com/terms-of-service](https://www.wunder365.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da JiJi Technologies Pvt Ltd su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | delegated | Nessun dato archiviato. | Per ottenere/aggiornare le attività di Planner, pubblicare gli aggiornamenti delle attività nel canale del team | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| Mail.Send | delegated | Nessun dato archiviato. | Consenti all'app di inviare notifiche tramite posta elettronica agli utenti | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| offline_access | delegated | Nessun dato archiviato. | Per mantenere l'utente connesso. | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| openid | delegated | Nessun dato archiviato. | Consente agli utenti di accedere con un account aziendale | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| profilo | delegated | UPN, ID utente, ID e-mail,ID tenant per la verifica delle licenze, licenza gratuita. | Consente agli utenti di accedere con un account aziendale | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API REST di SharePoint | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Stiamo accedendo ad Azure Application Insights. Stiamo registrare l'ID tenant e l'ID di posta elettronica dell'utente per identificare i problemi e aiutare i clienti a risolvere i problemi.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Tutte le applicazioni Web e le Archiviazione si trovano in una sottoscrizione non connessa all'AAD aziendale con solo amministratori che hanno accesso alle risorse. Per questi amministratori è necessaria la 2FA. 


#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da JiJi Technologies Pvt Ltd su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Richiedere l'autenticazione a più fattori per gli utenti con ruoli amministrativi, Richiedere l'autenticazione a più fattori per le attività di gestione di Azure, Blocco degli accessi per gli utenti che tentano di utilizzare protocolli di autenticazione legacy, Richiesta di percorsi attendibili per la registrazione di Azure AD Multi-Factor Authentication, Blocco o concessione dell'accesso da posizioni specifiche, Blocco del comportamento di accesso rischioso |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,
<br />
- OAuth2 Implicit Flow, a meno che non sia necessario per una spa
<br />
- Flusso roPC (Resource Owner Password Credential) | | L'app espone qualsiasi API Web? | No | | La tua app usa le API di anteprima? | Sì | | L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
