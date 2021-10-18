---
title: Informazioni sull'applicazione per 365Projects di 365Apps
ms.author: elmalova
author: elenamalova
ms.date: 03/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per 365Projects, i relativi criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 30670ebb5d80435dfbe77b3e735aeb72a695907c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430918"
---
# <a name="365projects"></a>365Projects

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 16, 2021</p>

* <a href="https://teams.microsoft.com/l/app/a9c31598-b014-4e20-b3bd-3d275fa738d3" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002160" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da 365Apps a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | 365Projects |
| ID | WA200002160 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | 365Apps |
| URL del sito Web del partner | [https://365apps.com.au](https://365apps.com.au) |
| URL della Teams info dell'applicazione | [https://365projects.app](https://365projects.app) |
| URL dell'informativa sulla privacy | [https://365projects.app/privacy](https://365projects.app/privacy) |
| URL delle Condizioni per l'utilizzo | [https://365projects.app/eula](https://365projects.app/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da 365Apps su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegated | canali all'interno del team per collegare il progetto al canale | canali all'interno del team per collegare il progetto al canale | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| Group.Read.All | delegated | ottenere attività di pianificazione/pianificazione del team, sarà meglio se un altro ambito con privilegi minimi consente all'app di ottenere piani utente e pianifica attività, ma purtroppo non ci sono ambiti che consentono questo | non archiviata nel database | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| Group.ReadWrite.All | application | Creare Teams  | non archiviato nel database | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| People.Read | delegated | nome utente, per aggiungerli come membri del team o assegnare loro attività | il Guid utente viene archiviato nell'assegnazione dell'attività | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| Team.ReadBasic.All | delegated | Nomi dei team aggiunti, per collegare il progetto a Teams Channel | Il Guid del team viene archiviato nei metadati del progetto per stabilire il collegamento | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| User.Read | delegated | recupero delle informazioni utente per la visualizzazione nell'intestazione  | la posta elettronica dell'utente viene archiviata come proprietario al primo provisioning del tenant | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| User.Read.All | delegated | leggere gli utenti per aggiornare l'assegnazione delle attività | solo il Guid utente non viene archiviato nel database | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>L'app non archivia i dati utente oltre al Guid dell'amministratore dell'app (il primo utente usa l'app nel tenant) 

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da 365Apps sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | ,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/> |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
