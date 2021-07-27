---
title: Application Information for Berrycast by Technologies Openmind Inc, Les
ms.author: elmalova
author: elenamalova
ms.date: 07/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e conformità disponibili per Berrycast, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 714db08e839b60403a567b2cab1af888c4cb7b6f
ms.sourcegitcommit: c545fba57f8ca821caf6ef55f5b4b068b5f35984
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/24/2021
ms.locfileid: "53578232"
---
# <a name="berrycast"></a>Berrycast

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 23, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c7cde650-1e32-11eb-af14-639b3a7d6491" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002798" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Technologies Openmind Inc, Les a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Berrycast |
| ID | WA200002798 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Technologies Openmind Inc, Les |
| URL del sito Web del partner | [https://www.berrycast.com](https://www.berrycast.com) |
| URL dell'informativa sulla privacy | [https://www.berrycast.com/privacy-policy](https://www.berrycast.com/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://www.berrycast.com/terms-of-use](https://www.berrycast.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Technologies Openmind Inc, Les su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| People.Read | delegated | Per ottenere tutti i contatti utente | L'indirizzo di posta elettronica, il nome del pugno, il cognome e l'immagine dei contatti vengono archiviati per fornire l'accesso rapido alla condivisione dei record | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| User.Read | delegated | Per identificare l'utente con informazioni di base (nome, cognome e immagine) | Per visualizzare il nome. cognome e immagine nell'applicazione | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| e-mail | delegated | Per identificare l'utente | Per identificare l'utente per la registrazione e l'invio di notifiche | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| offline_access | delegated | Mantenimento dell'accesso ai dati a cui è stato concesso l'accesso | N/D | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| openid | delegated | Per identificare l'utente | Per identificare l'utente per la registrazione | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutte le informazioni non servizi Microsoft OII vengono trasferite a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento di OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Stripe, Intercom, MixPanel, Amplitude | posta elettronica, identificazione univoca utente, nome, cognome  | Per elaborare il pagamento sicuro, eseguire una campagna di marketing, avere un servizio clienti efficiente e tenere traccia dell'analisi degli utenti per migliorare il prodotto |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Email, firstname, lastname and we remove all data if the user delete his account 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Eliminiamo tutti i dati relativi a un utente se elimina il suo account.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/38163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/38163" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Technologies Openmind Inc, Les su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | No |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
