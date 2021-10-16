---
title: Application Information for ecBooking by Expert Systems IVR(Asia) Co.Ltd.
ms.author: elmalova
author: elenamalova
ms.date: 02/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per ecBooking, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 418f653876e6a93d6772317016e460fc0da70954
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411704"
---
# <a name="ecbooking"></a>ecBooking

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 28, 2020</p>

* <a href="https://teams.microsoft.com/l/app/fe9627db-f23e-42b1-b454-d4d1ca5af33e" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002096" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Expert Systems IVR(Asia) Co.Ltd. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | ecBooking |
| ID | WA200002096 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Expert Systems IVR (Asia) Co.Ltd. |
| URL del sito Web del partner | [https://www.esi-asia.com](https://www.esi-asia.com) |
| URL della Teams info dell'applicazione | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/) |
| URL dell'informativa sulla privacy | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/#1510822239639-efecac03-d43200b0-aa88) |
| URL delle Condizioni per l'utilizzo | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/#1598241760681-29d114e0-5c2b) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Expert Systems IVR(Asia) Co.Ltd. informazioni su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | application | Vengono archiviati dati come e-mail utente, eventi utente. Gli eventi utente vengono raccolti per controllare la disponibilità delle sale e creare eventi. | Id dell'evento degli utenti, nome della posizione e dettagli di altri eventi verranno archiviati. I dati vengono raccolti per controllare la disponibilità delle sale e creare eventi. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| Mail.Send | application | Dati come e-mail utente. I messaggi di posta elettronica dell'utente vengono raccolti per l'invio di e-mail di promemoria per la prenotazione della sala. | Dati come e-mail utente. I messaggi di posta elettronica dell'utente vengono raccolti per l'invio di e-mail di promemoria per la prenotazione della sala. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| User.Read | delegated | Dati come ID utente, nome e posta elettronica. I dati utente vengono raccolti per l'accesso dell'utente nell'applicazione. | Dati come ID utente, nome e posta elettronica. I dati utente vengono raccolti per l'accesso dell'utente nell'applicazione. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| User.Read.All | application | Dati come ID utente, nome e posta elettronica. I dati utente vengono raccolti per l'accesso dell'utente nell'applicazione. | Dati come ID utente, nome e posta elettronica. I dati utente vengono raccolti per l'accesso dell'utente nell'applicazione. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| email | delegated | Dati come e-mail utente. L'e-mail dell'utente è stata raccolta per controllare la disponibilità dell'utente e creare eventi. | Dati come e-mail utente. L'e-mail dell'utente è stata raccolta per controllare la disponibilità dell'utente e creare eventi. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| openid | delegated | L'openid dell'utente per consentire all'utente di accedere all'applicazione. | L'openid dell'utente per consentire all'utente di accedere all'applicazione. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Vengono archiviati dati come e-mail utente, eventi utente. 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Dati archiviati nel database.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36415' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36415" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Expert Systems IVR(Asia) Co.Ltd. informazioni su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/><br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

