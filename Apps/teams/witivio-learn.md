---
title: Application Information for Learn by Witivio
ms.author: elmalova
author: elenamalova
ms.date: 03/31/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Learn, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f931e75f0a5736ffa49c7366d9928db774c4bdbf
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283806"
---
# <a name="learn"></a>Formazione

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 31, 2020</p>

* <a href="https://teams.microsoft.com/l/app/2d96b540-aa26-431b-bc31-222321c762e3" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001308" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Witivio a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Formazione |
| ID | WA200001308 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Witivio |
| URL del sito Web del partner | [https://www.witivio.com](https://www.witivio.com) |
| URL dell'informativa sulla privacy | [https://www.witivio.com/en/privacy](https://www.witivio.com/en/privacy) |
| URL delle Condizioni per l'utilizzo | [https://witivio.com/en/terms-of-use](https://witivio.com/en/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Witivio su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegated | N/D | Microsoft raccoglie l'UPN e l'ID AAD per l'autorizzazione. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |
>| User.ReadBasic.All | delegated | N/D | Microsoft raccoglie l'UPN e l'ID AAD per l'autorizzazione. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |
>| openid | delegated | N/D | Microsoft raccoglie l'UPN e l'ID AAD per l'autorizzazione. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |
>| profilo | delegated | N/D | Microsoft raccoglie l'UPN e l'ID AAD per l'autorizzazione. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Usiamo l'elenco per: 1) autorizzazione (concedere l'accesso al bot), 2) rilevare il nome per fornire un'esperienza utente descrittiva, 3) Per gestire i chatlog per l'amministratore aziendale del bot | N/D. Oppure i bot sono solo personali |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>La telemetria del bot contiene l'UPN e la diagnostica fr ID AAD.
Solo gli amministratori DI PROD/Run hanno accesso alla telemetria di produzione. I log vengono archiviati per 90 giorni e possono essere eliminati su richiesta su un portale dedicato support.witivio.com o tramite posta elettronica a dpo@witivio.com

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Witivio usa solo componenti di Azure, distribuiti nell'area nord Europa. Usiamo informazioni dettagliate sulle applicazioni e Cosmos database per l'analisi e l'archiviazione dei dati.
Witivio usa MFA per tutti gli utenti, inclusi gli amministratori. Gli amministratori hanno un account utente (per la workstation) e un account con privilegi per accedere ai ressource di Azure.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

