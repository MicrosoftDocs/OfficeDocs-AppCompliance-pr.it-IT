---
title: Application Information for FormMachines Connector for SharePoint by ENTERPRISE DIGITAL MACHINES PTY LTD
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per FormMachines Connector per SharePoint, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f550b89335a7ce75d23d01728478e121f10c6fd3
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/02/2021
ms.locfileid: "53282561"
---
# <a name="formmachines-connector-for-sharepoint"></a>Connettore FormMachines per SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 3, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200000357" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da ENTERPRISE DIGITAL MACHINES PTY LTD a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Connettore FormMachines per SharePoint |
| ID | WA200000357 |
| Office 365 client supportati | SharePoint 2016 o versione successiva |
| Nome società partner | ENTERPRISE DIGITAL MACHINES PTY LTD |
| URL del sito Web del partner | [https://www.formmachines.com](https://www.formmachines.com) |
| URL dell'informativa sulla privacy | [https://www.formmachines.com?dirKey=fm-privacy](https://www.formmachines.com?dirKey=fm-privacy) |
| URL delle Condizioni per l'utilizzo | [https://www.formmachines.com?dirKey=fm-terms-of-use](https://www.formmachines.com?dirKey=fm-terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da ENTERPRISE DIGITAL MACHINES PTY LTD su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegated | (login, email, Azure Guid, displayName, first_login_date_time) | consente all'utente di accedere e consente all'app di accedere al proprio UPN per abilitare l'accesso invisibile all'utente, ci consente di identificare in modo univoco ogni utente | 8c87660f-d36f-41f6-b0ae-025253f380aaa |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>. Vengono solo rilevati errori . Nel registro errori vengono registrate solo le informazioni relative agli errori. Il client o il cliente che ha generato un determinato errore non viene raccolto. Solo i tecnici del supporto hanno accesso ai log degli errori. I log degli errori vengono visualizzati online, non scaricati e visualizzati. I log degli errori vengono eliminati automaticamente dopo 30 giorni

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>. I dati vengono archiviati in data center basati su Azure US. I dati forniti dal client, ad esempio modelli e invii, vengono crittografati nel database . I file allegati vengono archiviati in contenitori BLOB di Azure privati, gli utenti devono eseguire l'autenticazione prima di accedervi. Abbiamo al massimo due amministratori che possono accedere alle risorse di produzione per la risoluzione dei problemi e la distribuzione. Questi due account di amministratore sono partizionati in modo diverso rispetto a tutti gli altri account. Il numero di accessi dell'amministratore non supererà mai due

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

