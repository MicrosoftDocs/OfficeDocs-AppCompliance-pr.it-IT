---
title: Informazioni sull'applicazione per HelloSign per SharePoint da Dropbox Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per HelloSign per SharePoint, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: e50ca05aa40133e0aa57f3b1de23c4c93e10ab45
ms.sourcegitcommit: d67be08c82a50cc263a4bdeb176f41dd60716159
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/15/2021
ms.locfileid: "60378994"
---
# <a name="hellosign-for-sharepoint"></a>HelloSign per SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 3, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003245" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Dropbox Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | HelloSign per SharePoint |
| ID | WA200003245 |
| Office 365 client supportati | SharePoint 2013 o versione successiva |
| Nome società partner | Dropbox Inc. |
| URL del sito Web del partner | [https://hellosign.com](https://hellosign.com) |
| URL dell'informativa sulla privacy | [https://www.hellosign.com/privacy](https://www.hellosign.com/privacy) |
| URL delle Condizioni per l'utilizzo | [https://hellosign.com/terms](https://hellosign.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Dropbox Inc. Su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite.All | application | Viene utilizzato con Sites.ReadWrite.All per scrivere i file firmati HelloSign nel SharePoint sito | Non vengono archiviati dati relativi a questo ambito | [6fcff87e-0f86-49c3-81eb-bc028d1ccfe6](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fcff87e-0f86-49c3-81eb-bc028d1ccfe6) |
>| Sites.ReadWrite.All | application | Viene utilizzato con Files.ReadWrite.All per scrivere i file firmati HelloSign nel SharePoint sito | Non vengono archiviati dati relativi a questo ambito | [6fcff87e-0f86-49c3-81eb-bc028d1ccfe6](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fcff87e-0f86-49c3-81eb-bc028d1ccfe6) |
>| User.Read | delegated | Posta elettronica utilizzata per identificare l'utente nell'applicazione | Posta elettronica usata per il cross-reference con i nostri account HelloSign in base alla posta elettronica | [6fcff87e-0f86-49c3-81eb-bc028d1ccfe6](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fcff87e-0f86-49c3-81eb-bc028d1ccfe6) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint API | Sì | Posta elettronica, ID tenant e ID sito | Utilizzato per l'identificazione e l'autenticazione | Posta elettronica, ID tenant, ID sito | Utilizzato per l'identificazione e l'autenticazione |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| https://www.hellosign.com/subprocessors | Posta elettronica, ID tenant, ID sito | JN Projects, Inc. dba HelloSign (&#8220;HelloSign&#8221;) usa alcuni sottoprocessori per fornire i nostri servizi. Microsoft utilizza provider di servizi che possono archiviare ed elaborare i dati personali relativi all'utente e agli utenti finali (ognuno dei quali &#8220;Sub-Processor&#8221;). Questa pagina fornisce informazioni importanti sull'identità, la posizione e il ruolo di questi sub-processori materiali. I termini utilizzati in questa pagina, ma non definiti, hanno il significato definito nel Contratto di servizio (&#8220;Agreement&#8221;). |



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Sono disponibili funzionalità di eliminazione, conservazione e registrazione per i dati che risiedono nei sistemi partner

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

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

Queste informazioni sono state fornite da Dropbox Inc. Su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
