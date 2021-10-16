---
title: Informazioni sull'applicazione per Waldo by Kickle
ms.author: elmalova
author: elenamalova
ms.date: 08/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Waldo, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 31c6c4b1240c9920a24f013c9d7ac6c61a30c90b
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413748"
---
# <a name="waldo"></a>Waldo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 30, 2021</p>

* <a href="https://teams.microsoft.com/l/app/1d041f16-ab49-4627-bfda-6b60ad2cab6a" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003139" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Kickle a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Waldo |
| ID | WA200003139 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Kickle |
| URL del sito Web del partner | [https://hellowaldo.app](https://hellowaldo.app) |
| URL della Teams info dell'applicazione | [https://hellowaldo.app/takeatour/](https://hellowaldo.app/takeatour/) |
| URL dell'informativa sulla privacy | [https://hellowaldo.app/privacy-policy/](https://hellowaldo.app/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://hellowaldo.app/terms-and-conditions](https://hellowaldo.app/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Kickle su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.ReadBasic | delegated | In base alla cronologia delle chat, Waldo identifica i colleghi. Questo elenco viene utilizzato in seguito per visualizzare lo stato nella visualizzazione calendario. | Waldo archivia l'ID utente di ogni collega. Questi ID vengono usati per visualizzare l'elenco dei colleghi con cui si lavora. | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| User.Read | delegated | Questa autorizzazione viene utilizzata dall'utente del componente di Microsoft Graph Toolkit | N/D | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| User.ReadBasic.All | delegated | Questa autorizzazione viene utilizzata dall'utente del componente di Microsoft Graph Toolkit | N/D | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| offline_access | delegated | Usato dall'app per eseguire attività in background per conto dell'utente (token di rinnovo per l'autenticazione) | N/D | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| openid | delegated | Obbligatorio per l'autenticazione | N/D | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>L'organizzazione può visualizzare gli amministratori di Waldo, i contatti amministrativi e i contatti tecnici all'indirizzo https://app.hellowaldo.app/admin-orga-contacts .  L'organizzazione può contattarci all'hello@kickle.com per rimuovere informazioni personali dall'app. Ciò potrebbe limitare il servizio che possiamo fornire.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Kickle su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | No |
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

