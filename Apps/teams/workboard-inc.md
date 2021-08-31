---
title: Informazioni sull'applicazione per Workboard di Workboard Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/04/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni di sicurezza e conformità disponibili per Workboard, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 0b2e460bf569a55b6a0179e7009ea92a5319ebab
ms.sourcegitcommit: b1e752ea527ba6049cdc4f5d12cbd5b4dbd7f5b3
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/27/2021
ms.locfileid: "58673119"
---
# <a name="workboard"></a>Workboard

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: June 4, 2021</p>

* <a href="https://teams.microsoft.com/l/app/28d0282b-3cd2-49f0-90bb-a016843750c6" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381599" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Workboard Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Workboard |
| ID | WA104381599 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Workboard Inc. |
| URL del sito Web del partner | [https://www.workboard.com](https://www.workboard.com) |
| URL della Teams info dell'applicazione | [https://www.workboard.com/microsoft/](https://www.workboard.com/microsoft/) |
| URL dell'informativa sulla privacy | [https://www.workboard.com/license/privacy-policy.html](https://www.workboard.com/license/privacy-policy.html) |
| URL delle Condizioni per l'utilizzo | [https://www.workboard.com/license/terms_of_use_v1.php](https://www.workboard.com/license/terms_of_use_v1.php) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Workboard Inc. Sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegated | indirizzo di posta elettronica e ID degli utenti.  Viene usato per mappare l'utente all'ID utente di WorkBoard | WorkBoard archivia solo l'identità dell'utente nei database | [User.Read](https://docs.microsoft.com/microsoft-365-app-certification/azure/User.Read) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| L'ID utente viene utilizzato per le notifiche proattive inviate Teams da WorkBord | Id e indirizzo di posta elettronica utente | Usato per mappare l'utente all'ID utente di WorkBoard |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>WorkBoard non archivia i dati dell'organizzazione nei sistemi del partner

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/29004' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/29004" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Workboard Inc. Sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | WorkBoard ha implementato i propri criteri di accesso applicati all'interno dell'app.  L'organizzazione, il team e l'identità dell'utente vengono utilizzati per determinare i diritti di accesso. |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
