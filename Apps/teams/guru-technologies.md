---
title: Informazioni sull'applicazione per Guru by Guru Technologies
ms.author: elmalova
author: elenamalova
ms.date: 03/01/2021
ms.topic: article
ms.service: attestation
description: Tutte le informazioni di sicurezza e conformità disponibili per Guru, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 052d06638dc6cf9d38180dd3c740cada21070dba
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095136"
---
# <a name="guru"></a>Guru

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 1, 2021</p>

* <a href="https://teams.microsoft.com/l/app/094bf90e-e413-4740-b2dc-68d624d0e40e" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001719" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Guru Technologies a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Guru |
| ID | WA200001719 |
| Funzionalità | Bot, estensione per la messaggistica |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Guru Technologies |
| URL del sito Web del partner | [https://www.getguru.com/](https://www.getguru.com/) |
| URL della pagina Teams informazioni sull'applicazione | [https://www.getguru.com/integrations/microsoft-teams](https://www.getguru.com/integrations/microsoft-teams) |
| URL dell'informativa sulla privacy | [https://www.getguru.com/privacy](https://www.getguru.com/privacy) |
| URL delle Condizioni per l'utilizzo | [https://www.getguru.com/terms-of-service](https://www.getguru.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Guru Technologies su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>Questa applicazione non utilizza Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutte le informazioni non servizi Microsoft OII vengono trasferite a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento di OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Applicazione dell'utente finale di Guru e database interni | quando un utente o una società configura l'app Guru per Teams, informazioni comuni come nome utente, posta elettronica e nome della società associate al profilo utente vengono registrate e accessibili da Guru | Dato che un utente deve disporre sia di un account Teams che di un account Guru per utilizzare l'integrazione, è possibile tenere traccia e seguire gli utenti che abilitano l'integrazione per fornire supporto e gestione a tali utenti |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>quando un utente o una società configura l'app Guru per Teams, informazioni comuni come nome utente, posta elettronica e nome della società associate al profilo utente vengono registrate e accessibili da Guru. Al termine di un account, i dati vengono conservati per 90 giorni e quindi rimossi. 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Il Impostazioni team di Guru consente agli amministratori di un team di determinare quali gruppi e controlli di accesso/ruolo effettuare il provisioning in base alla raccolta, con la possibilità di aggiungere, rimuovere e rias assegnare schede a utenti alternativi. Enterprise clienti che hanno distribuito SSO hanno anche il vantaggio della console del provider SSO per eseguire l'onboard o l'offboard e stabilire gruppi tramite SCIM

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36912' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36912" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Guru Technologies su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
