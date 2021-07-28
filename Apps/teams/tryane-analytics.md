---
title: Informazioni sull'applicazione per Tryane Analytics di Tryane
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Tryane Analytics, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2bfff7785dbad9398697aef468115cb8f7275acd
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/22/2021
ms.locfileid: "53527552"
---
# <a name="tryane-analytics"></a>Tryane Analytics

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 28, 2020</p>

* <a href="https://teams.microsoft.com/l/app/87631b95-fcd9-46e9-8d86-3d5205c04fec" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001827" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Tryane a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Tryane Analytics |
| ID | WA200001827 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Tryane |
| URL del sito Web del partner | [https://www.tryane.com](https://www.tryane.com) |
| URL dell'informativa sulla privacy | [https://analytics.tryane.com/docs/en/privacy_policy.html](https://analytics.tryane.com/docs/en/privacy_policy.html) |
| URL delle Condizioni per l'utilizzo | [https://analytics.tryane.com/docs/en/terms_of_use.html](https://analytics.tryane.com/docs/en/terms_of_use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Tryane su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ActivityFeed.Read | application |  | Leggere tutte le attività degli utenti nei team | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Channel.ReadBasic.All | application |  | Tutti Elenca tutti i canali con nomi, descrizioni | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| ChannelMessage.Read.All | application |  | Elencare tutti i messaggi dei canali&#8217; metadati | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Directory.Read.All | application |  | Identificare gli utenti con una licenza del team nel tenant | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Member.Read.Hidden | application |  | Ottenere un elenco di tutti i team, i membri&#8217;team e le appartenenze nascoste | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Reports.Read.All | application |  | Leggere tutte le attività degli utenti nei team | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| Team.ReadBasic.All | application |  | Elencare tutti i canali e le proprietà dei team | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |
>| User.Read | delegated | ID utente, Nome, Indirizzo e-mail, Data creazione. Questi dati vengono archiviati per fornire analisi di utilizzo in Teams | Identificare l'utente corrente durante l'abbonamento | [9b03f15d-1219-4b2f-9699-640be54e1319](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b03f15d-1219-4b2f-9699-640be54e1319) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>La regola organizzativa descritta nei criteri di sicurezza IT e negli standard di codifica ci impedisce di visualizzare l'IEE e l'OII nei registri

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Where/How: Azure/Azure Database for PostgreSQL servers Who può accedervi: l'applicazione e gli amministratori del database Controllo autorizzazione: 
 - Controllo di autorizzazione individuale: RBAC
 - Controllo dell'autorizzazione del sistema: endpoint privati nelle reti virtuali di Azure

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

