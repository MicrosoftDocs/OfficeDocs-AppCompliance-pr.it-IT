---
title: Informazioni sull'applicazione per TeamsChamp di TeamsChamp
ms.author: elmalova
author: elenamalova
ms.date: 07/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per TeamsChamp, i criteri di gestione dei dati, le informazioni del catalogo app di Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 8ba17c02a5478213d3666651efdbb5e4ed342147
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283632"
---
# <a name="teamschamp"></a>TeamsChamp

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 1, 2021</p>

* <a href="https://teams.microsoft.com/l/app/4fea4594-3f83-4e33-9929-9af6b78a7340" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001487" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da TeamsChamp a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | TeamsChamp |
| ID | WA200001487 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | TeamsChamp |
| URL del sito Web del partner | [https://www.encamina.com](https://www.encamina.com) |
| URL della Teams info dell'applicazione | [https://www.teamschamp.com](https://www.teamschamp.com) |
| URL dell'informativa sulla privacy | [https://www.teamschamp.com/privacy-policy/](https://www.teamschamp.com/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://www.teamschamp.com/terms/](https://www.teamschamp.com/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da TeamsChamp su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegated | Accedere e leggere il profilo degli utenti | Nessun dato archiviato nel bbdd | [79d7af39-4f57-4e95-adaf-ec8ff756d0df](https://docs.microsoft.com/microsoft-365-app-certification/azure/79d7af39-4f57-4e95-adaf-ec8ff756d0df) |
>| User.ReadBasic.All | delegated | Leggere il profilo di base di tutti gli utenti | Nessun dato archiviato nel bbdd | [79d7af39-4f57-4e95-adaf-ec8ff756d0df](https://docs.microsoft.com/microsoft-365-app-certification/azure/79d7af39-4f57-4e95-adaf-ec8ff756d0df) |
>| profilo | delegated | Visualizzare il profilo di base degli utenti | Nessun dato archiviato nel bbdd | [79d7af39-4f57-4e95-adaf-ec8ff756d0df](https://docs.microsoft.com/microsoft-365-app-certification/azure/79d7af39-4f57-4e95-adaf-ec8ff756d0df) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Stripe payments | Nome del comnpany, CIF/PARTITA IVA, Indirizzo fiscale | Pagamenti |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Informazioni personali come nome completo, e-mail

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>eliminazione, conservazione, controllo, archiviazione, tutte le gestioni nell'interfaccia di amministrazione stripe

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36549' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36549" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da TeamsChamp sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
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
