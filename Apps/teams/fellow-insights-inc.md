---
title: Application Information for Fellow by Fellow Insights Inc
ms.author: elmalova
author: elenamalova
ms.date: 05/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Fellow, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 581b41bdf80bcbdd77bb3406b35556308a13b8f9
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59281556"
---
# <a name="fellow"></a>Fellow

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 21, 2021</p>

* <a href="https://teams.microsoft.com/l/app/f6671df0-1909-428c-91f7-1c42df04d3e4" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002576" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Fellow Insights Inc a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Fellow |
| ID | WA200002576 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Fellow Insights, Inc. |
| URL del sito Web del partner | [https://fellow.app](https://fellow.app) |
| URL dell'informativa sulla privacy | [https://fellow.app/privacy-policy/](https://fellow.app/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://fellow.app/terms-of-use/](https://fellow.app/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Fellow Insights Inc su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | entrambi | Il collega si connette con i calendari dell'utente per fornire loro la possibilità di prendere appunti sui dati. | Fellow archivia tutti i dati dell'evento per il calendario principale dell'utente. Gli allegati non vengono archiviati. Viene usato all'interno di Fellow per offrire un'esperienza di prendere nota basata sul calendario. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Channel.ReadBasic.All | delegated | Raccogliamo i nomi dei canali di cui un utente è membro per mostrare loro un elenco di canali a cui possono inviare note. | I nomi e gli ID dei canali di cui un utente è membro vengono memorizzati nella cache per consentire agli utenti di inviare note dal collega al canale specificato. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Directory.Read.All | application | Questi dati vengono raccolti solo se viene eseguita un'installazione dell'amministratore per l'intera organizzazione. I dati della directory vengono utilizzati per sincronizzare un elenco di utenti ed eseguire automaticamente il provisioning degli account. | Se e solo se l'amministratore esegue un'installazione a livello di organizzazione dall'interno delle impostazioni dell'area di lavoro all'interno di Fellow, gli amministratori hanno la possibilità di abilitare la sincronizzazione automatica di tutti gli utenti da Azure AD a Fellow (provisioning automatico). In questo caso, vengono archiviate informazioni utente quali ID, Nome, Posta elettronica e Manager e appartenenze a gruppi (per le funzionalità di gestione dei team). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Group.Read.All | application | Questi dati vengono raccolti solo se viene eseguita un'installazione dell'amministratore per l'intera organizzazione. I dati della directory vengono utilizzati per sincronizzare un elenco di utenti ed eseguire automaticamente il provisioning degli account. | Se e solo se l'amministratore esegue un'installazione a livello di organizzazione dall'interno delle impostazioni dell'area di lavoro all'interno di Fellow, gli amministratori hanno la possibilità di abilitare la sincronizzazione automatica di tutti gli utenti da Azure AD a Fellow (provisioning automatico). In questo caso, vengono archiviate informazioni utente quali ID, Nome, Posta elettronica e Manager e appartenenze a gruppi (per le funzionalità di gestione dei team). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| People.Read | delegated | I contatti dell'utente vengono raccolti, in displayNames e indirizzi di posta elettronica specifici dei contatti. Questo viene usato all'interno di Fellow per fornire un elenco di utenti da invitare a invitare in una nota / condividere una nota con. | I contatti dell'utente vengono raccolti, in displayNames e indirizzi di posta elettronica specifici dei contatti. Questo viene usato all'interno di Fellow per fornire un elenco di utenti da invitare a invitare in una nota / condividere una nota con. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| People.Read.All | application | Questi dati vengono raccolti solo se viene eseguita un'installazione dell'amministratore per l'intera organizzazione. I contatti dell'utente vengono raccolti, in displayNames e indirizzi di posta elettronica specifici dei contatti. Questo viene usato all'interno di Fellow per fornire un elenco di utenti da invitare a invitare in una nota / condividere una nota con. | Se e solo se l'amministratore esegue un'installazione a livello di organizzazione dall'interno delle impostazioni dell'area di lavoro all'interno di Fellow, gli amministratori hanno la possibilità di abilitare la sincronizzazione automatica di tutti gli utenti da Azure AD a Fellow (provisioning automatico). In questo caso i contatti dell'utente vengono raccolti, in displayNames e indirizzi di posta elettronica specifici del contatto. Questo viene usato all'interno di Fellow per fornire un elenco di utenti da invitare a invitare in una nota / condividere una nota con. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Team.ReadBasic.All | delegated | Viene raccolto un elenco di team di cui fa parte l'utente. Questo viene usato all'interno di fellow allo scopo di consentire all'utente di inviare note da Fellow a un team. | I nomi e gli ID dei team di cui è membro un utente vengono memorizzati nella cache per consentire agli utenti di inviare note da Colleghi al canale di teams specificato. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read | delegated | Vengono raccolte le informazioni di base dell'utente. Nome utente, e-mail, posizione professionale. Queste informazioni vengono utilizzate all'interno di Fellow per creare account utente e account aziendali. | Vengono archiviate le informazioni di base dell'utente. Nome utente, e-mail, posizione professionale. Queste informazioni vengono utilizzate all'interno di Fellow per gestire gli account utente e gli account aziendali. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read.All | application | Questi dati vengono raccolti solo se viene eseguita un'installazione dell'amministratore per l'intera organizzazione. I dati della directory vengono utilizzati per sincronizzare un elenco di utenti ed eseguire automaticamente il provisioning degli account. | Se e solo se l'amministratore esegue un'installazione a livello di organizzazione dall'interno delle impostazioni dell'area di lavoro all'interno di Fellow, gli amministratori hanno la possibilità di abilitare la sincronizzazione automatica di tutti gli utenti da Azure AD a Fellow (provisioning automatico). In questo caso, vengono archiviate informazioni utente quali ID, Nome, Posta elettronica e Manager e appartenenze a gruppi (per le funzionalità di gestione dei team). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| offline_access | delegated | Token di aggiornamento dell'utente per mantenere l'accesso ai dati raccolti tramite altri ambiti. | Il token di aggiornamento dell'utente viene archiviato nel database. Viene usato all'interno di Fellow per sincronizzare gli eventi in background per l'esperienza di prendere nota basata sul calendario, nonché per le notifiche per prendere nota degli eventi pianificati. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Fellow archivia le informazioni fornite direttamente dall'utente, inclusi i dati personali. Fellow archivia anche alcune informazioni di sistemi di terze parti, ad esempio i dati OAuth, i dati del calendario e le informazioni personali, ad esempio la posta &amp; elettronica del nome. Conserviamo tutti i dati a tempo indeterminato, per tutto il tempo necessario e legalmente consentito per lo scopo per cui sono stati raccolti. Queste informazioni vengono eliminate in modo sicuro in una data precedente alla ricezione di una richiesta da parte degli utenti. I dati del registro vengono conservati per 30 giorni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Tutti i trasferimenti di dati vengono eseguiti tramite API protette per i sistemi back-end. Fellow impiega molti controlli per garantire la sicurezza e la riservatezza dei suoi sistemi, in base al framework SOC 2 definito da AICPA. I controlli dei colleghi vengono sottoposti a un controllo annuale per garantire la conformità continua. Un report SOC 2 può essere condiviso su richiesta e NDA.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Fellow Insights Inc su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | ,<br/><br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
