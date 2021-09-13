---
title: Application Information for Cuckoo Workout by Cuckoo Networks Oy
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Cuckoo Workout, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3544854ed952a23af34da1cc1b0ab82465c0966e
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59289390"
---
# <a name="cuckoo-workout"></a>Cuckoo Workout

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 3, 2021</p>

* <a href="https://teams.microsoft.com/l/app/71138876-8738-4935-95b6-ae7c2fbe4e54" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002750" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Cuckoo Networks Oy a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Cuckoo Workout |
| ID | WA200002750 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Cuckoo Networks Oy |
| URL del sito Web del partner | [https://cuckooworkout.com](https://cuckooworkout.com) |
| URL della Teams info dell'applicazione | [https://cuckooworkout.com](https://cuckooworkout.com) |
| URL dell'informativa sulla privacy | [https://cuckooworkout.com/service-privacy-policy/](https://cuckooworkout.com/service-privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://cuckooworkout.com/terms-of-service/](https://cuckooworkout.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Cuckoo Networks Oy su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegated | Nome utente, ID tenant per le comunicazioni e il mapping delle sottoscrizioni | Nome utente, ID tenant per le comunicazioni e il mapping delle sottoscrizioni | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |
>| email | delegated | Posta elettronica, necessaria per l'autenticazione e il supporto | Posta elettronica, necessaria per l'autenticazione e il supporto | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |
>| offline_access | delegated | N/D | N/D | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |
>| openid | delegated | ID utente per l'autenticazione | ID utente per l'autenticazione | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |
>| profilo | delegated | ID profilo per l'autenticazione | ID profilo per l'autenticazione | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Amazon AWS | Tenant ID | Per associare l'utente al piano di sottoscrizione aziendale  |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Autenticazione e verifica dello stato | Teams utente, ID tenant | Autenticazione e verifica dello stato |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Chat, visualizzazioni video, impostazioni utente, lingua. Criteri di conservazione e rimozione in base al GDPR.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>L'amministratore con privilegi di amministratore può eseguire l'eliminazione, la conservazione, il controllo, l'archiviazione, i criteri degli utenti finali e così via.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/41840' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/41840" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Cuckoo Networks Oy su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
