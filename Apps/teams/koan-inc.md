---
title: Application Information for Koan by Koan, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Koan, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 7bd65669087e3e0cb934bf7cb3da4c70bba08d73
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282984"
---
# <a name="koan"></a>Koan

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 1, 2021</p>

* <a href="https://teams.microsoft.com/l/app/dae2b2c3-b014-4188-a887-c87c3ca4a227" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002936" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Koan, Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Koan |
| ID | WA200002936 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Koan, Inc. |
| URL del sito Web del partner | [https://www.koan.co](https://www.koan.co) |
| URL della Teams info dell'applicazione | [https://www.koan.co/how-it-works](https://www.koan.co/how-it-works) |
| URL dell'informativa sulla privacy | [https://www.koan.co/privacy-policy](https://www.koan.co/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://www.koan.co/terms-of-service](https://www.koan.co/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Koan, Inc. Su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegated | Vengono utilizzati l'ID canale e il nome del canale. Usiamo i dati in modo che gli utenti possano selezionare dove devono recapitare le notifiche di Reflection. | L'ID del canale e il nome del canale vengono archiviati come parte della configurazione degli utenti. | [5b599e19-a609-432b-9074-c9d4457e8766](https://docs.microsoft.com/microsoft-365-app-certification/azure/5b599e19-a609-432b-9074-c9d4457e8766) |
>| Team.ReadBasic.All | entrambi | L'ID del team e il nome del team vengono raccolti e usati. Usiamo i dati in modo che gli utenti possano selezionare dove devono recapitare le notifiche di Reflection. | L'ID del team e il nome del team vengono archiviati come parte della configurazione degli utenti. | [5b599e19-a609-432b-9074-c9d4457e8766](https://docs.microsoft.com/microsoft-365-app-certification/azure/5b599e19-a609-432b-9074-c9d4457e8766) |
>| User.Read | delegated | Vengono utilizzati il nome utente, l'ID utente e l'indirizzo di posta elettronica dell'utente. I dati vengono utilizzati per collegare gli account utente tra Microsoft Teams e Koan. Ha applicato solo per le menzioni. | Nessuno dei dati è archiviato | [5b599e19-a609-432b-9074-c9d4457e8766](https://docs.microsoft.com/microsoft-365-app-certification/azure/5b599e19-a609-432b-9074-c9d4457e8766) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Intercom, Hubspot | Informazioni sul profilo utente | Supporto clienti |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Nomi utente, profilo di collegamento tra Microsoft Teams e Koan | No |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Conserviamo l'accesso amministrativo per eliminare, archiviare ed eliminare i dati nei sistemi partner.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalogo vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Koan, Inc. Sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
