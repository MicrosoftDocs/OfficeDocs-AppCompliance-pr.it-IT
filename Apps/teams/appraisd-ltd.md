---
title: Application Information for Appraisd by Appraisd ltd.
ms.author: elmalova
author: elenamalova
ms.date: 09/07/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per la valutazione, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 0b098dc89b60ad052d520b8c6ea56a2bda237544
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410440"
---
# <a name="appraisd"></a>Appraisd

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 7, 2021</p>

* <a href="https://teams.microsoft.com/l/app/4f037969-20ef-4a41-8330-422b7b115eb6" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003123" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Appraisd ltd. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Appraisd |
| ID | WA200003123 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Appraisd ltd. |
| URL del sito Web del partner | [https://www.appraisd.com](https://www.appraisd.com) |
| URL della Teams info dell'applicazione | [https://www.appraisd.com](https://www.appraisd.com) |
| URL dell'informativa sulla privacy | [https://help.appraisd.com/hc/en-us/articles/360007779298-Pr...](https://help.appraisd.com/hc/en-us/articles/360007779298-Privacy-Policy) |
| URL delle Condizioni per l'utilizzo | [https://www.appraisd.com/terms](https://www.appraisd.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Appraisd ltd. sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| People.Read | delegated | La selezione utenti presenta all'utente un elenco dei membri del team. Ciò consente di supportare le funzionalità di base all'interno di Valutazione. | Questi dati non vengono archiviati. | [4f037969-20ef-4a41-8330-422b7b115eb6](https://docs.microsoft.com/microsoft-365-app-certification/azure/4f037969-20ef-4a41-8330-422b7b115eb6) |
>| User.Read | delegated | L'indirizzo di posta elettronica dell'utente (upn) e l'ID utente vengono utilizzati per trovare l'utente all'interno di Valutazione e collegarlo al Teams account. | L'indirizzo di posta elettronica dell'utente (upn) e l'ID utente vengono archiviati per ricordare il collegamento tra l'account di valutazione dell'utente e Teams utente. | [4f037969-20ef-4a41-8330-422b7b115eb6](https://docs.microsoft.com/microsoft-365-app-certification/azure/4f037969-20ef-4a41-8330-422b7b115eb6) |
>| User.ReadBasic.All | delegated | La selezione utenti presenta all'utente informazioni di base sul membro del team. Ciò consente di supportare le funzionalità di base all'interno di Valutazione. | Questi dati non vengono archiviati. | [4f037969-20ef-4a41-8330-422b7b115eb6](https://docs.microsoft.com/microsoft-365-app-certification/azure/4f037969-20ef-4a41-8330-422b7b115eb6) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Per supportare le funzionalità di base in Valutazione. | Indirizzo di posta elettronica, ID utente | Per creare un collegamento tra gli account di valutazione e Teams utente e supportare le funzionalità di base in Valutazione. |


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

Queste informazioni sono state fornite da Appraisd ltd. sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

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
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

