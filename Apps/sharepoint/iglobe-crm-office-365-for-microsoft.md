---
title: Informazioni sull'applicazione per iGlobe CRM Office 365 per Microsoft Office 365 da iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per iGlobe CRM Office 365 per Microsoft Office 365, i relativi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: b52fcc6ec5d5f5f36c11379c736e098048e58b6b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553507"
---
# <a name="iglobe-crm-office-365-for-microsoft-office-365"></a>iGlobe CRM Office 365 per Microsoft Office 365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Ultimo aggiornamento da parte dello sviluppatore: 17 novembre 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379222" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da iGlobe a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | iGlobe CRM Office 365 per Microsoft Office 365 |
| ID | WA104379222 |
| Office 365 client supportati | SharePoint 2013 o versione successiva |
| Nome della società partner | iGlobe |
| URL del sito Web partner | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL dell'Informativa sulla privacy | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL delle Condizioni d'uso | [https://www.iglobecrm.com/content/iglobe-crm-office-365-end...](https://www.iglobecrm.com/content/iglobe-crm-office-365-end-user-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da iGlobe su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Avere accesso ai calendari utente quando si dreating un rapporto di riunione dal canlendar in a iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Contatti.LetturaScrivi | delegato |  Directory.AccessAsUser.All | Consente all'app di avere lo stesso accesso alle informazioni nella directory dell'utente che ha effettuato l'accesso. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.Read.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Verificare la presenza di autorizzazioni e ottenere i siti e gli elenchi. Creare cartelle, ottenere file e salvare file. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.ReadWrite.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Consente all'app di avere lo stesso accesso alle informazioni nella directory dell'utente che ha effettuato l'accesso. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Files.ReadWrite.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere, aggiornare, creare attività di panner, leggere gli utenti file recenti e condivisi, Per ottenere SharePoint elenco, raccolte e file. Per salvare file e dati in SharePoint elenchi. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.Read.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere, aggiornare, creare attività di panner, leggere gli utenti file recenti e condivisi, Per ottenere SharePoint elenco, raccolte e file. Per salvare i file SharePoint elenchi. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.ReadWrite.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere, aggiornare, creare attività di panner, leggere gli utenti file recenti e condivisi, Per ottenere SharePoint elenco, raccolte e file. Per salvare i file SharePoint elenchi. Integrazione in iGlobe CRM Office 365 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Mail.ReadWrite | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Svae l'eamil a iGlobe CRM e ottenere l'informatiopn da iGlobe a un nuovo e-amil | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Manage.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Creare, modificare ed eliminare elementi ed elenchi in iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Read.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere elementi in iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.ReadWrite.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. |  Modificare ed eliminare elementi ed elenchi in iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Tasks.ReadWrite | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Creare attività di pianificazione da iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| User.Read | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere informazioni su iGlobe CRM per l'utente specifico | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati tramite altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono utilizzare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni di identificazione dell'organizzazione ( OII). Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **OII viene raccolto?** |  **Quale OII viene raccolto?** | **Giustificazione per la raccolta di OII?** | **OII è memorizzato?** | **Giustificazione per l'archiviazione di OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - Calendars.ReadWrite.All | No |  |  |  |  |
>| Exchange - Mail.Lettura.All | No |  |  |  |  |
>| Exchange - Contatti.Lettura | No |  |  |  |  |
>| Exchange - EWS. AccessAsUser.All | No |  |  |  |  |
>| Exchange - Tasks.ReadWrite | No |  |  |  |  |
>| SharePoint - AllSites.Manage | No |  |  |  |  |
>| SharePoint - AllSites.Read | No |  |  |  |  |
>|  SharePoint -AllSites.Write | No |  |  |  |  |
>| SharePoint - File.Scrittura | No |  |  |  |  |
>| SharePoint - Siti.Gestisci.Tutti | No |  |  |  |  |
>| SharePoint - Siti.Lettura.Tutti | No |  |  |  |  |
>| SharePoint - Sites.ReadWrite.All | No |  |  |  |  |
>| SharePoint - Siti.Ricerca.Tutti | No |  |  |  |  |
>|  SharePoint - TermStore.Read.All | No |  |  |  |  |
>| SharePoint - TermStore.ReadWrite.All | No |  |  |  |  |

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

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">Visualizzare in una nuova scheda</a>

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
