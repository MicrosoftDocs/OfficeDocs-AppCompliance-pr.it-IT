---
title: Informazioni sull'applicazione per il componente aggiuntivo Office 365 Planner iPlanner per Outlook di iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per il componente aggiuntivo iPlanner Office 365 Planner per Outlook, i relativi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c7eef95df6de269d9e383e604aa8ff32518584e1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552537"
---
# <a name="iplanner-office-365-planner-add-in-for-outlook"></a>Componente aggiuntivo iPlanner Office 365 Planner per Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Ultimo aggiornamento da parte dello sviluppatore: 17 novembre 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380147" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da iGlobe a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Componente aggiuntivo iPlanner Office 365 Planner per Outlook |
| ID | WA104380147 |
| Office 365 client supportati | Outlook 2013 o versioni successive Windows, Outlook 2016 o versioni successive su Mac, Outlook sul Web |
| Nome della società partner | iGlobe |
| URL del sito Web partner | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL dell'Informativa sulla privacy | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| URL delle Condizioni d'uso | [https://iglobecrm.com/content/end-user-license-agreement-ig...](https://iglobecrm.com/content/end-user-license-agreement-iglobe-iplanner-add-ins) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da iGlobe su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere l'attività di pianificazione e aggiungere nuove attività, aggiornare il bucket e la linea di nuoto per l'utente specifico | A6f5C2F4-0BC2-48BF-8AFE-6C93583A152B |
>| Contatti.LetturaScrivi | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per creare un appuntamento nel calendario utenti nella data di scadenza delle attività | A6f5C2F4-0BC2-48BF-8AFE-6C93583A152B |
>| Directory.AccessAsUser.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Consente all'app di avere lo stesso accesso alle informazioni nella directory dell'utente che ha effettuato l'accesso. | A6f5C2F4-0BC2-48BF-8AFE-6C93583A152B |
>| Files.Read | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per accedere al file come allegato e caricare file in un'attività | A6f5C2F4-0BC2-48BF-8AFE-6C93583A152B |
>| Files.ReadWrite.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Ottenere l'oggetto della posta dal messaggio selezionato. Consente all'app di ottenere informazioni dal messaggio di posta elettronica selezionato, consentendo di copiare il campo di descrizione nella descrizione dell'attività e consentendo di salvare gli allegati dalla posta o dalla posta stessa all'attività. | A6f5C2F4-0BC2-48BF-8AFE-6C93583A152B |
>| Group.Read.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. |  Per ottenere l'attività di pianificazione e aggiungere nuove attività, aggiornare il bucket e la linea di nuoto per l'utente specifico | A6f5C2F4-0BC2-48BF-8AFE-6C93583A152B |
>| User.Read | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere l'attività di pianificazione e aggiungere nuove attività, aggiornare il bucket e la linea di nuoto per l'utente specifico | A6f5C2F4-0BC2-48BF-8AFE-6C93583A152B |
>| User.ReadBasic.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. |  Verificare la presenza di autorizzazioni e ottenere l'attività di pianificazione e aggiungere nuove attività aggiornare il bucket e la linea di nuoto per l'utente specifico | A6f5C2F4-0BC2-48BF-8AFE-6C93583A152B |
>| profilo | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere l'attività di pianificazione e aggiungere nuove attività, aggiornare il bucket e la linea di nuoto per l'utente specifico | A6f5C2F4-0BC2-48BF-8AFE-6C93583A152B |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati tramite altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono utilizzare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni di identificazione dell'organizzazione ( OII). Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **OII viene raccolto?** |  **Quale OII viene raccolto?** | **Giustificazione per la raccolta di OII?** | **OII è memorizzato?** | **Giustificazione per l'archiviazione di OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - EWS. AccessAsUser.All | No |  |  |  |  |
>| Exchange - Mail.Lettura.All | No |  |  |  |  |
>| SharePoint - AllSites.Manage | No |  |  |  |  |
>| SharePoint - AllSites.Read | No |  |  |  |  |
>| SharePoint - AllSites.Write | No |  |  |  |  |
>| SharePoint - File.Lettura | No |  |  |  |  |
>| SharePoint - File.Scrittura | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>iGlobe raccoglie dati per operare in modo efficace e fornirti le migliori esperienze con i nostri prodotti e servizi. Per le licenze: dati raccolti per amministrare l&#8217;artino delle licenze dell'organizzazione, ad esempio quando si distribuisce un componente aggiuntivo gratuito, si crea una sottoscrizione di valutazione o si acquista una sottoscrizione. Vengono raccolte le seguenti informazioni. 
- A fini finanziari: nome e indirizzo della società
- Utenti sottoscritti: nome utente ed e-mail

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Tutti i dati si basano sul tenant del cliente. Non vengono archiviati dati dell'applicazione. Un componente aggiuntivo moderno viene eseguito in un browser in modalità sandbox, &#8220;fuori processo&#8221;. Interagisce con i dati degli utenti utilizzando servizi Microsoft. Il componente aggiuntivo può accedere solo ai dati con cui l'utente sta lavorando.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35757' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35757" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da iGlobe su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Ti integri con Microsoft Identify Platform (Azure AD)?  | Sì |
| Hai esaminato e rispettato tutte le best practice applicabili descritte nell'elenco di controllo Microsoft Identity Platform integrazione?  | Sì |
| La tua app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Impostazioni predefinite di protezione e qualsiasi altro criterio comune come Blocca autenticazione legacy* Richiedi autenticazione a più fattori per gli amministratori* Richiedi autenticazione a più fattori per la gestione di Azure* Richiedi autenticazione a più fattori per tutti gli utenti* |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate staticamente dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| La tua app supporta la multi-tenancy? | Sì |
| La tua app ha un client riservato? | Sì |
| Possiedi tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| La tua app espone api Web? | No |
| La tua app usa le API di anteprima? | No |
| La tua app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
