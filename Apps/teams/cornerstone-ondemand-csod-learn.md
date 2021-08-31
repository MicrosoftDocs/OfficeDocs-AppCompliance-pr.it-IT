---
title: Informazioni sull'applicazione per CSOD Learn by Cornerstone OnDemand
ms.author: elmalova
author: elenamalova
ms.date: 07/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e conformità disponibili per CSOD Learn, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 2064ed00ba6306d86a09b3eff9dc6e56c8d1cc40
ms.sourcegitcommit: 34fde42f42c623b37d1db154bf348bdc8b76a8c7
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/19/2021
ms.locfileid: "58407481"
---
# <a name="csod-learn"></a>Informazioni su CSOD

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 1, 2021</p>

* <a href="https://teams.microsoft.com/l/app/81726ee9-4d27-47ad-8b22-08147c6f8613" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003020" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Cornerstone OnDemand a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Informazioni su CSOD |
| ID | WA200003020 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Cornerstone OnDemand |
| URL del sito Web del partner | [https://www.cornerstoneondemand.com](https://www.cornerstoneondemand.com) |
| URL dell'informativa sulla privacy | [https://www.cornerstoneondemand.com/client-privacy-policy/](https://www.cornerstoneondemand.com/client-privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://www.microsoft.com/en-us/microsoft-teams/group-chat-...](https://www.microsoft.com/en-us/microsoft-teams/group-chat-software) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Cornerstone OnDemand su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>Questa applicazione non utilizza Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| I dati dell'organizzazione vengono condivisi tra CSOD Services e Microsoft. Per ulteriori informazioni, fare riferimento ai termini del contratto con CSOD | I dati dell'organizzazione vengono condivisi tra CSOD Services e Microsoft. Per ulteriori informazioni, fare riferimento ai termini del contratto con CSOD | Il servizio CSOD non usa Graph API. Usiamo i framework Microsoft botbuilder^4.9.2 per le prestazioni del servizio. I dati OII vengono utilizzati dal servizio per identificare l'utente del servizio CSOD. Per ulteriori informazioni, fare riferimento ai termini del contratto con CSOD |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| si prega di fare riferimento ai termini del contratto con CSOD per informazioni a questo proposito | mapping aadObjectId dell'utente finale all'ID interno utente CSOD | si prega di fare riferimento ai termini del contratto con CSOD per informazioni a questo proposito |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Il servizio CSOD archivia i log delle applicazioni che contengono l'interazione dell'utente con l'app per un periodo di tempo limitato per risolvere i bug e i problemi segnalati dall'utente. Le singole istruzioni di registro sono costituite dall'ID utente interno dell'utente finale, dal nome dell'organizzazione configurato all'interno del servizio CSOD e dall'azione appropriata eseguita. v

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>L'accesso al servizio CSOD è controllato dagli amministratori dell'organizzazione dell'utente finale. Per ulteriori informazioni, fare riferimento ai termini del contratto con CSOD

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Cornerstone OnDemand sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
