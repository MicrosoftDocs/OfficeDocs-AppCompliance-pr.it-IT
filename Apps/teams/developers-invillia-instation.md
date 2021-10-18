---
title: Informazioni sull'applicazione per InStation da parte degli sviluppatori invillia
ms.author: elmalova
author: elenamalova
ms.date: 06/30/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per InStation, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 71210aafa0ff6cd960e69f64e10e735fa225660e
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60426816"
---
# <a name="instation"></a>InStation

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 6, 2020</p>

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Sviluppatori Invillia a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | InStation |
| ID | WA200001701 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Developers Invillia |
| URL del sito Web del partner | [https://invillia.com/](https://invillia.com/) |
| URL dell'informativa sulla privacy | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite dagli sviluppatori invillia sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| OnlineMeetings.Read.All | delegated | stores: id, join_url, join_web_url e chat_id. Consente all'app di creare riunioni | stores: id, join_url, join_web_url e chat_id. Consente all'app di creare riunioni | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| OnlineMeetings.ReadWrite.All | delegated | stores: id, join_url, join_web_url e chat_id. Consente all'app di creare riunioni | stores: id, join_url, join_web_url e chat_id. Consente all'app di creare riunioni | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| Presence.Read | delegated | Consente all'app di accedere all'organizzazione nel primo passaggio | l'attività e l'avalibilità. Consente all'app di acquisire lo stato degli utenti; | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| Presence.Read.All | delegated | Consente all'app di accedere all'organizzazione nel primo passaggio, | l'attività e l'avalibilità. Consente all'app di acquisire lo stato degli utenti; | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| User.Read | delegated | stores: id, mail, display name, surname and picture. Consente all'app di cercare dati utente. | stores: id, mail, display name, surname and picture. Consente all'app di cercare dati utente. | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| User.Read.All | delegated | stores: id, mail, display name, surname and picture. Consente all'app di cercare dati utente. | stores: id, mail, display name, surname and picture. Consente all'app di cercare dati utente. | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| email | delegated | Consente all'app di acquisire le&#180;di base dell'amministratore al primo accesso | Consente all'app di acquisire le&#180;di base dell'amministratore al primo accesso | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| offline_access | delegated | stores: token e token di aggiornamento. Consente all'app di eseguire un aggiornamento sul token MS | stores: token e token di aggiornamento. Consente all'app di eseguire un aggiornamento sul token MS | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| openid | delegated | Consente all'app di accedere all'organizzazione nel primo passaggio | Consente all'app di accedere all'organizzazione nel primo passaggio | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| profile | delegated | Consente all'app di acquisire le informazioni di&#180;amministratore sul primo accesso; | Consente all'app di acquisire le informazioni di&#180;amministratore sul primo accesso; | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Salviamo solo i log di utilizzo degli utenti all'interno dell'applicazione.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Salviamo solo i log di utilizzo degli utenti all'interno dell'applicazione. Niente di riservato, che non richiede alcuna crittografia e solo i nostri amministratori specifici hanno accesso a questi dati.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

