---
title: Informazioni sull'applicazione per MyHub per Teams da AvePoint Inc.
ms.author: elmalova
author: elenamalova
ms.date: 10/06/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per MyHub per Teams, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: a19a24cc9178bbbaa16b337cd92fc11686d8d09c
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412636"
---
# <a name="myhub-for-teams"></a>MyHub per Teams

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 29, 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/avepoint.myhubforteams" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da AvePoint Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | MyHub per Teams |
| ID | avepoint.myhubforteams |
| Nome società partner | AvePoint Inc. |
| URL del sito Web del partner | [https://www.avepoint.com](https://www.avepoint.com) |
| URL dell'informativa sulla privacy | [https://www.avepoint.com/company/privacy-policy](https://www.avepoint.com/company/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://www.avepoint.com/company/terms-of-use](https://www.avepoint.com/company/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da AvePoint Inc. Su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | entrambi | i dati di configurazione dell'applicazione vengono archiviati da un punto di vista della gestione dei dati | Leggere i dati della directory | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Group.ReadWrite.All | entrambi | i dati di configurazione dell'applicazione vengono archiviati da un punto di vista della gestione dei dati | Lettura e scrittura di tutti i gruppi | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Mail.Send | delegated | i dati di configurazione dell'applicazione vengono archiviati da un punto di vista della gestione dei dati | Inviare posta come utente | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Reports.Read.All | application | i dati di configurazione dell'applicazione vengono archiviati da un punto di vista della gestione dei dati | Leggere tutti i report di utilizzo | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Sites.FullControl.All | application | i dati di configurazione dell'applicazione vengono archiviati da un punto di vista della gestione dei dati | Avere il controllo completo di tutte le raccolte siti | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Sites.Read.All | application | i dati di configurazione dell'applicazione vengono archiviati da un punto di vista della gestione dei dati | Leggere gli elementi in tutte le raccolte siti | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Sites.ReadWrite.All | delegated | i dati di configurazione dell'applicazione vengono archiviati da un punto di vista della gestione dei dati | Modificare o eliminare elementi in tutte le raccolte siti | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| User.Read.All | entrambi | i dati di configurazione dell'applicazione vengono archiviati da un punto di vista della gestione dei dati | Leggere tutti gli utenti&#65533; profili completi | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì, la posta elettronica e l'ID tenant dell'utente verranno visualizzati nei log. I log vengono archiviati in una posizione protetta e solo il personale autorizzato può accedere durante la risoluzione dei problemi. I log verranno archiviati dopo 60 giorni per scopi di controllo della sicurezza e verranno eliminati dopo un anno.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati dell'applicazione vengono archiviati in database SQL di Azure e Archiviazione di Azure. La SQL e Archiviazione di Azure azure sono abilitate.
Solo gli amministratori autorizzati possono accedere ai dati. L'autenticazione a più fattori è necessaria per l'accesso degli amministratori. Le operazioni vengono verificate. L'elenco indirizzi IP viene utilizzato anche per limitare l'accesso ai dati.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da AvePoint Inc. Sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | L'applicazione si federata con Azure AD, in modo da poter utilizzare tutte le regole di accesso condizionale. |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | Sì |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

