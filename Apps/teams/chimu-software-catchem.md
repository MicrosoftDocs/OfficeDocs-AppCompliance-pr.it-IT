---
title: Informazioni sull'applicazione per CatchEm di Chimu Software
ms.author: elmalova
author: elenamalova
ms.date: 03/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per CatchEm, i relativi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 55b248c8f99e18d08ddf60dec177ce92b543f008
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552317"
---
# <a name="catchem"></a>CatchEm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 27 marzo 2021</p>

* <a href="https://teams.microsoft.com/l/app/fc686a41-3bd0-45b3-a56d-f278888fd694" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002639" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Chimu Software a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | CatchEm |
| ID | WA200002639 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Chimu Software |
| URL del sito Web partner | [https://www.chimusoftware.com](https://www.chimusoftware.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://catchem.apps.chimusoftware.com/help](https://catchem.apps.chimusoftware.com/help) |
| URL dell'Informativa sulla privacy | [https://www.chimusoftware.com/apps/catchem/privacy.html](https://www.chimusoftware.com/apps/catchem/privacy.html) |
| URL delle Condizioni d'uso | [https://www.chimusoftware.com/apps/catchem/termsofuse.html](https://www.chimusoftware.com/apps/catchem/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Chimu Software su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Chat.ReadBasic | delegato | Questa autorizzazione è necessaria per determinare i contatti di un utente dell'applicazione. AadObjectId: per identificare in modo univoco un utente. TenantId: per determinare se un contatto è interno o esterno all'utente. DisplayName, GivenName, Surname: per identificare i contatti agli utenti dell'applicazione. Email, UserPrincipalName: per distinguere tra contatti con lo stesso nome e per consentire la funzionalità &quot; click to &quot; chat. ID chat più recente: per abilitare &quot; la funzionalità click to &quot; chat | Questa autorizzazione è necessaria per determinare i contatti di un utente dell'applicazione. AadObjectId: per identificare in modo univoco un utente. TenantId: per determinare se un contatto è interno o esterno all'utente. DisplayName, GivenName, Surname: per identificare i contatti agli utenti dell'applicazione. Email, UserPrincipalName: per distinguere tra contatti con lo stesso nome e per consentire la funzionalità &quot; click to &quot; chat. ID chat più recente: per abilitare &quot; la funzionalità click to &quot; chat | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| Persone.Lettura | delegato | Per migliorare l'accuratezza dei dati per i contatti esterni. DisplayName: per identificare i contatti per gli utenti dell'applicazione. | Per migliorare l'accuratezza dei dati per i contatti esterni. DisplayName: per identificare i contatti per gli utenti dell'applicazione. | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| Presence.Read.All | delegato | Stato presenza corrente contatti | N/D | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| TeamsActivity.Invia | ambedue | Per inviare notifiche agli utenti quando cambia lo stato presenza di un contatto | N/D | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| TeamsAppInstallation.ReadWriteSelfForUser | delegato | Per abilitare gli aggiornamenti automatici per l'applicazione | N/D | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| User.Read | delegato | AadObjectId: per identificare in modo univoco un utente. TenantId: per determinare se un contatto è interno o esterno all'utente. DisplayName, GivenName, Surname: per identificare i contatti agli utenti dell'applicazione. Email, indirizzi di messaggistica istantanea, UserPrincipalName: per distinguere tra contatti con lo stesso nome e per consentire la &quot; funzionalità click to &quot; chat. CompanyName, Paese: Analytics. AccountEnabled, DeletedDateTime: eliminazione automatica dei dati utente per gli utenti disabili | AadObjectId: per identificare in modo univoco un utente. TenantId: per determinare se un contatto è interno o esterno all'utente. DisplayName, GivenName, Surname: per identificare i contatti agli utenti dell'applicazione. Email, indirizzi di messaggistica istantanea, UserPrincipalName: per distinguere tra contatti con lo stesso nome e per consentire la &quot; funzionalità click to &quot; chat. CompanyName, Paese: Analytics. AccountEnabled, DeletedDateTime: eliminazione automatica dei dati utente per gli utenti disabili | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| User.ReadBasic.All | delegato | Per migliorare l'accuratezza dei dati per i contatti interni. AadObjectId: per identificare in modo univoco un utente. TenantId: per determinare se un contatto è interno o esterno all'utente. DisplayName, GivenName, Surname: per identificare i contatti agli utenti dell'applicazione. Email, UserPrincipalName: per distinguere tra contatti con lo stesso nome e per consentire la funzionalità &quot; click to &quot; chat. | Per migliorare l'accuratezza dei dati per i contatti interni. AadObjectId: per identificare in modo univoco un utente. TenantId: per determinare se un contatto è interno o esterno all'utente. DisplayName, GivenName, Surname: per identificare i contatti agli utenti dell'applicazione. Email, UserPrincipalName: per distinguere tra contatti con lo stesso nome e per consentire la funzionalità &quot; click to &quot; chat. | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| offline_access | delegato | Graph token di sicurezza, per consentire all'applicazione di notificare le modifiche alla presenza dei contatti e aggiornare gli elenchi di contatti quando l'utente non utilizza attivamente l'applicazione | Graph token di sicurezza | fc686a41-3bd0-45b3-a56d-f278888fd694 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Il &quot; tag dalla funzionalità del messaggio deve utilizzare il nome visualizzato del contatto da mostrare &quot; all'utente dell'applicazione | Nome visualizzato del contatto | Per poter presentare il nome del contatto all'utente dell'applicazione |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nei registri o nella telemetria delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>N/D

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Chimu Software su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Ti integri con Microsoft Identify Platform (Azure AD)?  | Sì |
| Hai esaminato e rispettato tutte le best practice applicabili descritte nell'elenco di controllo Microsoft Identity Platform integrazione?  | Sì |
| La tua app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate staticamente dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | No |
| La tua app supporta la multi-tenancy? | Sì |
| La tua app ha un client riservato? | Sì |
| Possiedi tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| La tua app espone api Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso corretto? | Sì |
| La tua app usa le API di anteprima? | Sì |
| La tua app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
