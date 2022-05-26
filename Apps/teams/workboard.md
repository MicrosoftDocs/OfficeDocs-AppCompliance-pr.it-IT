---
title: Informazioni sull'applicazione per Workboard by Workboard
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 06/04/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Esaminare tutte le informazioni di sicurezza e conformità disponibili per Workboard, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ccf27f1fa0c6db96446fc0fa7afc686fe2a49e20
ms.sourcegitcommit: ef767e1079411056cb3ca86d6b29084e31b0ef1c
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/26/2022
ms.locfileid: "65688101"
---
# <a name="application-information-for-workboard"></a>Informazioni sull'applicazione per Workboard

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Ultimo aggiornamento da parte dello sviluppatore: 4 giugno 2021</p>

* <a href="https://teams.microsoft.com/l/app/28d0282b-3cd2-49f0-90bb-a016843750c6" target="_blank">Visualizza in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381599" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Workboard a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Workboard |
| ID | WA104381599 |
| client Office 365 supportati | Microsoft Teams |
| Nome della società partner | Workboard |
| URL del sito Web del partner | [https://www.workboard.com](https://www.workboard.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://www.workboard.com/microsoft/](https://www.workboard.com/microsoft/) |
| URL dell'informativa sulla privacy | [https://www.workboard.com/license/privacy-policy.html](https://www.workboard.com/license/privacy-policy.html) |
| URL delle condizioni per l'utilizzo | [https://www.workboard.com/license/terms_of_use_v1.php](https://www.workboard.com/license/terms_of_use_v1.php) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Workboard su come questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elencare le [autorizzazioni di Microsoft Graph](/graph/permissions-reference) necessarie per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | Delegato | indirizzo di posta elettronica e id degli utenti.  Viene usato per eseguire il mapping dell'utente all'ID utente di WorkBoard | WorkBoard archivia solo l'identità dell'utente nei relativi database | [User.Read](/graph/permissions-reference#user-permissions) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con un servizio non Microsoft, elencare il servizio non Microsoft usato dall'app, i dati trasferiti e includere una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono usati servizi Microsoft.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni identificabili dell'utente finale (EUII): il roster (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunto. Questa app usa questa funzionalità?

>| **Giustificazione dell'accesso a EUII?**  | **L'identità dell'identità dell'utente viene archiviata in uno o più database?** | **Giustificazione dell'archiviazione dell'IUE?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| L'ID utente viene usato per le notifiche proattive inviate a Teams da WorkBord | ID e indirizzo di posta elettronica utente | Usato per eseguire il mapping dell'utente all'ID utente di WorkBoard |


#### <a name="telemetry-data"></a>Dati di telemetria

Nei dati di telemetria o nei log dell'applicazione vengono visualizzate informazioni personali dell'organizzazione o informazioni personali dell'utente finale( EUII) ? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Nei log o nei dati di telemetria delle applicazioni non vengono visualizzati dati OII o EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio l'eliminazione, la conservazione, il controllo, l'archiviazione, i criteri degli utenti finali e così via.

>WorkBoard non archivia i dati dell'organizzazione nei sistemi dei partner

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni aziendali

Gli esseri umani sono coinvolti nella revisione o nell'analisi di eventuali dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono riportate le informazioni del catalogo [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='informazioni Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/29004' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/29004" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Workboard sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione dell'applicazione e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Si esegue l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di controllo di integrazione Microsoft Identity Platform?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | WorkBoard ha implementato i propri criteri di accesso applicati all'interno dell'app.  L'organizzazione, il team e l'identità dell'utente vengono usati per determinare i diritti di accesso. |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app ha un client riservato? | No |
| Si è proprietari di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per l'app? | Sì |
| L'app espone eventuali API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| L'app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
