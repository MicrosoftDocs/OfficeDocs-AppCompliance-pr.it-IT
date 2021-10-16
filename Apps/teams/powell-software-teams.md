---
title: Application Information for Powell Teams by Powell Software
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Powell Teams, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 745b6ff67059c682a0ccd67b7fac88fbe0ac3c04
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412826"
---
# <a name="powell-teams"></a>Powell Teams

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 9, 2021</p>

* <a href="https://teams.microsoft.com/l/app/423d394a-892e-44d1-b9f0-ff382643df42" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001585" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Powell Software a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Powell Teams |
| ID | WA200001585 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Powell Software |
| URL del sito Web del partner | [https://www.powell-software.com](https://www.powell-software.com) |
| URL della Teams info dell'applicazione | [https://helpteams.powell-software.com](https://helpteams.powell-software.com) |
| URL dell'informativa sulla privacy | [https://powell-software.com/en/powell-teams-privacy](https://powell-software.com/en/powell-teams-privacy) |
| URL delle Condizioni per l'utilizzo | [https://powell-software.com/en/powell-teams-terms-of-use/](https://powell-software.com/en/powell-teams-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Powell Software su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.AccessAsUser.All | delegated | ND | ND | [086ae3fb-fdf0-4c49-8c38-57d082b00dc4](https://docs.microsoft.com/microsoft-365-app-certification/azure/086ae3fb-fdf0-4c49-8c38-57d082b00dc4) |
>| Group.ReadWrite.All | delegated | ND | ND | [086ae3fb-fdf0-4c49-8c38-57d082b00dc4](https://docs.microsoft.com/microsoft-365-app-certification/azure/086ae3fb-fdf0-4c49-8c38-57d082b00dc4) |
>| Notes.Read.All | delegated | ND | ND | [086ae3fb-fdf0-4c49-8c38-57d082b00dc4](https://docs.microsoft.com/microsoft-365-app-certification/azure/086ae3fb-fdf0-4c49-8c38-57d082b00dc4) |
>| Notes.ReadWrite.All | delegated | ND | ND | [086ae3fb-fdf0-4c49-8c38-57d082b00dc4](https://docs.microsoft.com/microsoft-365-app-certification/azure/086ae3fb-fdf0-4c49-8c38-57d082b00dc4) |
>| Sites.Read.All | delegated | ND | ND | [086ae3fb-fdf0-4c49-8c38-57d082b00dc4](https://docs.microsoft.com/microsoft-365-app-certification/azure/086ae3fb-fdf0-4c49-8c38-57d082b00dc4) |
>| User.Read.All | delegated | ND | ND | [086ae3fb-fdf0-4c49-8c38-57d082b00dc4](https://docs.microsoft.com/microsoft-365-app-certification/azure/086ae3fb-fdf0-4c49-8c38-57d082b00dc4) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>ID Azure AD utente e ID tenant utente

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>nessun partner conserva i dati

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Powell Software sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | No |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | Sì |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

