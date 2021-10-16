---
title: Informazioni sull'applicazione per Navo by Regroove Solutions
ms.author: elmalova
author: elenamalova
ms.date: 01/20/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e conformità disponibili per Navo, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 554d59fbb03382ab517bb2f928823a33b2ec4ee0
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411531"
---
# <a name="navo"></a>Navo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2020</p>

* <a href="https://teams.microsoft.com/l/app/d8653da2-4682-4b92-b659-485087957897" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001047" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Regroove Solutions a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Navo |
| ID | WA200001047 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Regroove Solutions |
| URL del sito Web del partner | [https://regroove.ca ; https://getnavo.com](https://regroove.ca ; https://getnavo.com) |
| URL dell'informativa sulla privacy | [https://getnavo.com/privacy-policy/](https://getnavo.com/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://getnavo.com/terms-of-service/](https://getnavo.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Regroove Solutions sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | application | Il numero di utenti viene archiviata ed eseguita una query una sola volta per ogni ciclo di fatturazione. Usiamo anche l'ID tenancy come ID per l'organizzazione. | Ci consente di contare il numero di utenti presenti nella tenancy, che usiamo per scopi di fatturazione. Ci consente inoltre di eseguire query per vedere in quali gruppi si trova un utente, in modo da poter usare la limitazione per motivi di sicurezza per proteggere determinati dati. Viene inoltre eseguita una query sull'ID tenancy dell'organizzazione. | [75ce4e02-e37b-479c-81c7-438348a2a251](https://docs.microsoft.com/microsoft-365-app-certification/azure/75ce4e02-e37b-479c-81c7-438348a2a251) |
>| User.Read | delegated | Nessun dato archiviato | Accedere e leggere il profilo utente | [75ce4e02-e37b-479c-81c7-438348a2a251](https://docs.microsoft.com/microsoft-365-app-certification/azure/75ce4e02-e37b-479c-81c7-438348a2a251) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| L'ID tenancy e il numero di utenti vengono archiviati in Stripe. |  | User.Read | Delegated | Accedere e leggere il profilo utente - Nessun dato archiviato |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì, in Application Insights vengono archiviati l'ID utente autenticato e l'ID account utente (ID tenancy).

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Tutti i dati archiviati (non tramite un servizio come Stripe o Application Insights) vengono archiviati in un database Cosmos Azure. Tutti gli amministratori usano la 2FA e l'accesso è limitato a un sottoinsieme dei dipendenti.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35974' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35974" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


