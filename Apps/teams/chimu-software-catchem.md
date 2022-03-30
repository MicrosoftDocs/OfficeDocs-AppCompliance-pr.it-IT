---
title: Informazioni sull'applicazione per CatchEm by Chimu Software
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per CatchEm, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c3773a334f6b0b778df0f26558517d87c6f7b10a
ms.sourcegitcommit: d8a3d237c4bd435183b9ce95c316b4d7ce9d7201
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/23/2022
ms.locfileid: "63772437"
---
# <a name="catchem"></a>CatchEm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 27, 2021</p>

* <a href="https://teams.microsoft.com/l/app/fc686a41-3bd0-45b3-a56d-f278888fd694" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002639" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Chimu Software a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | CatchEm |
| ID | WA200002639 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Chimu Software |
| URL del sito Web del partner | [https://chimusoftware.com](https://chimusoftware.com) |
| URL della Teams info dell'applicazione | [https://catchem.apps.chimusoftware.com/help](https://catchem.apps.chimusoftware.com/help) |
| URL dell'informativa sulla privacy | [https://www.chimusoftware.com/apps/catchem/privacy.html](https://www.chimusoftware.com/apps/catchem/privacy.html) |
| URL delle Condizioni per l'utilizzo | [https://www.chimusoftware.com/apps/catchem/termsofuse.html](https://www.chimusoftware.com/apps/catchem/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Chimu Software su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft necessarie](/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD ID app** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.ReadBasic | delegated | Questa autorizzazione è necessaria per determinare i contatti di un utente dell'applicazione. AadObjectId: per identificare in modo univoco un utente. TenantId: per determinare se un contatto è interno o esterno all'utente. DisplayName, GivenName, Surname: per identificare i contatti per gli utenti dell'applicazione. Email, UserPrincipalName: per distinguere i contatti con lo stesso nome &quot;e consentire la funzionalità di chat con clic&quot; . ID chat più recente: per abilitare la funzionalità &quot;di click to chat&quot; | Questa autorizzazione è necessaria per determinare i contatti di un utente dell'applicazione. AadObjectId: per identificare in modo univoco un utente. TenantId: per determinare se un contatto è interno o esterno all'utente. DisplayName, GivenName, Surname: per identificare i contatti per gli utenti dell'applicazione. Email, UserPrincipalName: per distinguere i contatti con lo stesso nome &quot;e consentire la funzionalità di chat con clic&quot; . ID chat più recente: per abilitare la funzionalità &quot;di click to chat&quot; | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| People.Read | delegated | Per migliorare l'accuratezza dei dati per i contatti esterni. DisplayName: per identificare i contatti per gli utenti dell'applicazione. | Per migliorare l'accuratezza dei dati per i contatti esterni. DisplayName: per identificare i contatti per gli utenti dell'applicazione. | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| Presence.Read.All | delegated | Stato presenza corrente contatti | N/D | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| TeamsActivity.Send | entrambi | Per inviare notifiche agli utenti quando cambia lo stato di presenza di un contatto | N/D | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| TeamsAppInstallation.ReadWriteSelfForUser | delegated | Per abilitare gli aggiornamenti automatici per l'applicazione | N/D | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| User.Read | delegated | AadObjectId: per identificare in modo univoco un utente. TenantId: per determinare se un contatto è interno o esterno all'utente. DisplayName, GivenName, Surname: per identificare i contatti per gli utenti dell'applicazione. Posta elettronica, Indirizzi di messaggistica istantanea, UserPrincipalName: &quot;per distinguere i contatti con lo stesso nome e consentire la funzionalità di chat con clic&quot; . CompanyName, Country: Analytics. AccountEnabled, DeletedDateTime: eliminazione automatica dei dati utente per gli utenti disabilitati | AadObjectId: per identificare in modo univoco un utente. TenantId: per determinare se un contatto è interno o esterno all'utente. DisplayName, GivenName, Surname: per identificare i contatti per gli utenti dell'applicazione. Posta elettronica, Indirizzi di messaggistica istantanea, UserPrincipalName: &quot;per distinguere i contatti con lo stesso nome e consentire la funzionalità di chat con clic&quot; . CompanyName, Country: Analytics. AccountEnabled, DeletedDateTime: eliminazione automatica dei dati utente per gli utenti disabilitati | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| User.ReadBasic.All | delegated | Per migliorare l'accuratezza dei dati per i contatti interni. AadObjectId: per identificare in modo univoco un utente. TenantId: per determinare se un contatto è interno o esterno all'utente. DisplayName, GivenName, Surname: per identificare i contatti per gli utenti dell'applicazione. Email, UserPrincipalName: per distinguere i contatti con lo stesso nome &quot;e consentire la funzionalità di chat con clic&quot; . | Per migliorare l'accuratezza dei dati per i contatti interni. AadObjectId: per identificare in modo univoco un utente. TenantId: per determinare se un contatto è interno o esterno all'utente. DisplayName, GivenName, Surname: per identificare i contatti per gli utenti dell'applicazione. Email, UserPrincipalName: per distinguere i contatti con lo stesso nome &quot;e consentire la funzionalità di chat con clic&quot; . | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| offline_access | delegated | Graph token di sicurezza, per consentire all'applicazione di notificare le modifiche della presenza dei contatti e aggiornare gli elenchi contatti quando l'utente non utilizza attivamente l'applicazione | Graph token di sicurezza | fc686a41-3bd0-45b3-a56d-f278888fd694 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Il &quot;tag dalla funzionalità del&quot; messaggio deve utilizzare il nome visualizzato del contatto da visualizzare all'utente dell'applicazione | Nome visualizzato del contatto | Per poter presentare il nome del contatto all'utente dell'applicazione |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>N/D

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Chimu Software su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

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
