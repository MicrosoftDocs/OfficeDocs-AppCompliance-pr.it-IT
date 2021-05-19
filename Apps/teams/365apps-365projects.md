---
title: Informazioni sull'applicazione per 365Projects di 365Apps
ms.author: elmalova
author: elenamalova
ms.date: 03/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per 365Projects, i relativi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d760c1c5bacf37fa23e26f4a9a15eb7dbbd75bb1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553467"
---
# <a name="365projects"></a>365Projects

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 16 marzo 2021</p>

* <a href="https://teams.microsoft.com/l/app/a9c31598-b014-4e20-b3bd-3d275fa738d3" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002160" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da 365Apps a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | 365Projects |
| ID | WA200002160 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | 365Apps |
| URL del sito Web partner | [https://365projects.app](https://365projects.app) |
| URL della pagina Teams informazioni sull'applicazione | [https://365projects.app](https://365projects.app) |
| URL dell'Informativa sulla privacy | [https://365projects.app/privacy](https://365projects.app/privacy) |
| URL delle Condizioni d'uso | [https://365projects.app/eula](https://365projects.app/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da 365Apps su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Channel.ReadBasic.All | delegato | canali all'interno del team per collegare il progetto con il canale | canali all'interno del team per collegare il progetto con il canale | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Group.Read.All | delegato | ottenere attività di pianificazione/pianificazione del team, sarà meglio se un altro ambito con privilegi minimo consente all'app di ottenere piani utente e pianifica attività, ma purtroppo non ci sono ambiti che lo consentano | non archiviare in DB | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Group.ReadWrite.All | applicazione | Crea Teams  | non archiviato in DB | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Persone.Lettura | delegato | nome utente, per aggiungerli come membri del team o assegnare loro attività | Il GUID utente viene archiviato nell'assegnazione dell'attività | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Team.ReadBasic.All | delegato | Nomi team uniti, per collegare il progetto a Teams Channel | Il GUID del team viene archiviato nei metadati del progetto per stabilire il collegamento | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| User.Read | delegato | Ottenere informazioni utente per mostrarlo nell'intestazione  | La posta elettronica dell'utente viene archiviata come proprietario al primo provisioning del tenant | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| User.Read.All | delegato | Leggere gli utenti per aggiornare l'assegnazione delle attività | Solo il GUID utente non viene memorizzato, nessuna informazione identificata personale viene memorizzata nel database | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>Non è possibile accedere all'I EUII.


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nei registri o nella telemetria delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>L'app non archivia i dati utente a parte il GUID dell'amministratore dell'app (il primo utente usa l'app all'interno del tenant) 

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da 365Apps su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Ti integri con Microsoft Identify Platform (Azure AD)?  | Sì |
| Hai esaminato e rispettato tutte le best practice applicabili descritte nell'elenco di controllo Microsoft Identity Platform integrazione?  | Sì |
| La tua app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate staticamente dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| La tua app supporta la multi-tenancy? | Sì |
| La tua app ha un client riservato? | No |
| Possiedi tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa eviti di usare? | ,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una SPA<br/> |
| La tua app espone api Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso corretto? | Sì |
| La tua app usa le API di anteprima? | No |
| La tua app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
