---
title: Application Information for Cassaforte Spaces di eCare Vault Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Cassaforte Spaces, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 39ca1a0a99e62bbedb14d0248cb751bf4089a70f
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414692"
---
# <a name="safe-spaces"></a>Spazi sicuri

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 14, 2021</p>

* <a href="https://teams.microsoft.com/l/app/ec321cf7-ae3e-4ed4-a707-ff5c18e77313" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002691" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da eCare Vault Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Spazi sicuri |
| ID | WA200002691 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | eCare Vault Inc. |
| URL del sito Web del partner | [https://ecarevault.com](https://ecarevault.com) |
| URL della Teams info dell'applicazione | [https://ecarevault.com/ecare-vault-for-teams](https://ecarevault.com/ecare-vault-for-teams) |
| URL dell'informativa sulla privacy | [https://ecarevault.com/ecare-vault-privacy-policy](https://ecarevault.com/ecare-vault-privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://downloads.ecarevault.com/downloads/eCare+Vault+-+Te...](https://downloads.ecarevault.com/downloads/eCare+Vault+-+Terms+of+Service.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da eCare Vault Inc. Su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| EduRoster.Read | delegated | Nome e Data di nascita vengono utilizzati per prepopolare i campi di input | Nessuno: tutti i dati archiviati vengono inviati dall'utente (dati prepopolato solo nei campi, quindi inviati dall'utente) | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| Group.Read.All | delegated | Usato per ottenere informazioni sui canali disponibili per la visualizzazione nell'applicazione | Nessuna di questa autorizzazione | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| GroupMember.Read.All | delegated | AAD ID dei membri del gruppo utilizzati per generare un elenco di team eCare Vault | AAD L'ID utente viene archiviato per l'associazione a un account utente eCare Vault per ogni membro | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| User.Read | delegated | Indirizzo di posta elettronica AAD ID utente Usato per registrare gli utenti e associarli agli account utente &amp; di eCare Vault | indirizzo di posta elettronica AAD ID utente per gli account utente e invio di notifiche all'utente tramite Bot Framework | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| User.Read.All | delegated | Nome e ID AAD e Indirizzo di posta elettronica, solo per gli utenti membri di un Canale in cui è installato Cassaforte Spaces | Nome, ID AAD e indirizzo di posta elettronica archiviati in account utente eCare Vault | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| email | delegated | Solo indirizzo di posta elettronica | Nessuno - Utente che decide di inviare un modulo che  | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| openid | delegated | Indirizzo di posta elettronica AAD ID utente Usato per registrare gli utenti e associarli agli account utente &amp; di eCare Vault | indirizzo di posta elettronica AAD ID utente per gli account utente e invio di notifiche all'utente tramite Bot Framework | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| profile | delegated | Il nome dell'utente viene usato per popolare la schermata di iscrizione dell'utente. | Nessuno direttamente: l'utente sceglie di inviare il proprio nome al sistema al momento della registrazione | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| MSAL (Endpoint di autenticazione Microsoft) | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| eCare Vault | Informazioni tenant/società, Nome dominio di accesso utente, Informazioni di accesso utente, Microsoft Teams identificatori &amp; del canale del team. | Cassaforte Spaces è un'applicazione complementare alla piattaforma eCare Vault. L'OII è necessario per collegare gli utenti da Microsoft Teams a utenti di eCare Vault per l'azienda. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Tutti i dati che vengono trasmessi ai sistemi partner (non include alcuna OII, PII o PHI) vengono trasferiti sotto un baa per garantire la conformità HIPAA.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da eCare Vault Inc. Su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

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
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | Sì |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

