---
title: Informazioni sull'applicazione per eTeamer da &#28145;&#22323;&#20234;&#30331;&#36719;&#20214;&#26377;&#38480;&#20844;&#21496;
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 05/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e conformità disponibili per eTeamer, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a542760d33527db8de77e8643bdffd9b2cb67f07
ms.sourcegitcommit: 9199fd569c5e7c5dd338abd87428c94798a22352
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/23/2022
ms.locfileid: "63748260"
---
# <a name="eteamer"></a>eTeamer

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 25, 2021</p>

* <a href="https://teams.microsoft.com/l/app/5b4afbd0-a5ff-49c8-a0c7-c28eb5e87ef8" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001621" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da &#28145;&#22323;&#20234;&#30331;&#36719;&#20214;&#26377;&#38480;&#20844;&#21496; a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | eTeamer |
| ID | WA200001621 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | &#28145;&#22323;&#20234;&#30331;&#36719;&#20214;&#26377;&#38480;&#20844;&#21496; |
| URL del sito Web del partner | [https://ecms2.edensoft.com.cn/#/Eden](https://ecms2.edensoft.com.cn/#/Eden) |
| URL dell'informativa sulla privacy | [https://ecms2.edensoft.com.cn/#/Privacy](https://ecms2.edensoft.com.cn/#/Privacy) |
| URL delle Condizioni per l'utilizzo | [https://ecms2.edensoft.com.cn/#/Service](https://ecms2.edensoft.com.cn/#/Service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da &#28145;&#22323;&#20234;&#30331;&#36719;&#20214;&#26377;&#38480;&#20844;&#21496; su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD ID app** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.ReadWrite.All | entrambi | L'ID applicazione tenant e la password dell'applicazione vengono raccolti per l'autorizzazione implicita OAuth 2.0 per sincronizzare le informazioni utente | L'ID tenant, l'ID applicazione tenant, la password dell'applicazione e le informazioni utente vengono archiviati nel database, che viene utilizzato per ottenere le informazioni sui file di canale degli utenti in Teams e operare sui file | [3407e97c-3eed-4eca-add5-2549ed881269](../azure/3407e97c-3eed-4eca-add5-2549ed881269.md) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>L'applicazione è costituita da 6 moduli, suddivisi in 55 Impostazioni, che supportano l'autorizzazione di un singolo file, nonché l'autorizzazione di un singolo utente/ruolo

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/40122' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/40122" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da &#28145;&#22323;&#20234;&#30331;&#36719;&#20214;&#26377;&#38480;&#20844;&#21496; su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

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
| Per la tua app, cosa evita di usare? | ,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | Sì |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
