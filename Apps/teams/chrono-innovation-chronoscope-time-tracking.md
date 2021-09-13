---
title: Informazioni sull'applicazione per il rilevamento del tempo del cronoscopio da parte di Chrono Innovation
ms.author: elmalova
author: elenamalova
ms.date: 07/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per chronoscope Time Tracking, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9e87baec293d3c18e48da28e1714fce9703f446f
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282144"
---
# <a name="chronoscope-time-tracking"></a>Cronoscopio Time Tracking

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 23, 2021</p>

* <a href="https://teams.microsoft.com/l/app/5b3ded07-fa1a-4fd8-a323-e5fe3f8cf740" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003095" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Chrono Innovation a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Cronoscopio Time Tracking |
| ID | WA200003095 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Chrono Innovation |
| URL del sito Web del partner | [https://www.chronoinnovation.com](https://www.chronoinnovation.com) |
| URL della Teams info dell'applicazione | [https://www.chronoscope.app](https://www.chronoscope.app) |
| URL dell'informativa sulla privacy | [https://www.chronoscope.app/privacy-policy](https://www.chronoscope.app/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://www.chronoscope.app/terms-of-service](https://www.chronoscope.app/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Chrono Innovation su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AccessReview.Read.All | application | the teams tenantId, teams addObjectId e teams user account information. Durante il collegamento degli utenti di Chronoscope, stiamo convalidando che il messaggio di posta elettronica corrisponde a un account Teams in modo da poter collegare l'account senza un passaggio manuale da parte dell'utente | teams tenantId, teams addObjectId e le informazioni sull'account utente di teams. Durante il collegamento degli utenti di Chronoscope, stiamo convalidando che il messaggio di posta elettronica corrisponde a un account Teams in modo da poter collegare l'account senza un passaggio manuale da parte dell'utente | [9bc8244d-a186-4b12-809e-c47b3eee73c6](https://docs.microsoft.com/microsoft-365-app-certification/azure/9bc8244d-a186-4b12-809e-c47b3eee73c6) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| per trovare l'utente di teams workspaQuando si collegano utenti chronoscope, viene convalidato che il messaggio di posta elettronica corrisponde a un account Teams in modo da poter collegare l'account senza un passaggio manuale dal file user.ce nel database dell'applicazione e autenticare l'utente di teams | tenantId , informazioni sull'account utente come userId, addObjectId, givenName,email,role,objectId | Quando si collegano gli utenti di Chronoscope, viene convalidato che il messaggio di posta elettronica corrisponde a un account Teams in modo da poter collegare l'account senza un passaggio manuale dell'utente. Anche per essere in grado di inviare notifiche sulle voci di tempo utente precompilato in modo che possano salvarle/modificarle/eliminarle. |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Informazioni relative alle voci relative all'ora. Chrono Innovation rimuoverà i dati dei clienti 90 giorni dopo l'eliminazione dell'account Chronoscope

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Gli amministratori hanno il controllo completo sulle informazioni che risiedono nei sistemi di qualsiasi partner

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Chrono Innovation su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/> |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
