---
title: Informazioni sull'applicazione per MIPA - Assistente personale di iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/06/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per MIPA - L'Assistente personale, i relativi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3c6e09d38057c2a84196982a94ea8f938b295fbe
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552087"
---
# <a name="mipa---your-personal-assistant"></a>MIPA - Your Personal Assistant

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Ultimo aggiornamento da parte dello sviluppatore: 6 novembre 2020</p>

* <a href="https://teams.microsoft.com/l/app/eec9d2db-2325-43f5-83c7-eac7c5253a87" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000148" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da iGlobe a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | MIPA - Your Personal Assistant |
| ID | WA200000148 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | iGlobe |
| URL del sito Web partner | [https://mipa.iglobe.dk/](https://mipa.iglobe.dk/) |
| URL della pagina Teams informazioni sull'applicazione | [https://mipa.iglobe.dk/Support](https://mipa.iglobe.dk/Support) |
| URL dell'Informativa sulla privacy | [https://instassl.iglobecrm.com/legal-information](https://instassl.iglobecrm.com/legal-information) |
| URL delle Condizioni d'uso | [https://mipa.iglobe.dk/EULA](https://mipa.iglobe.dk/EULA) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da iGlobe su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere e aggiornare interi calendario | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Contatti.LetturaScrivi | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere e aggiornare interi calendario | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Directory.AccessAsUser.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere, aggiornare, creare attività di panner, leggere gli utenti file recenti e condivisi. Per verificare il consenso dell'utente e avere accesso all'utilizzo dell'API. | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Directory.ReadWrite.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere, aggiornare, creare attività di panner, leggere gli utenti file recenti e condivisi, Per ottenere SharePoint elenco, raccolte e file. Per salvare i file SharePoint elenchi. | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Files.ReadWrite.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere, aggiornare, creare attività di panner, leggere gli utenti file recenti e condivisi, Per ottenere SharePoint elenco, raccolte e file. Per salvare i file SharePoint elenchi. | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Group.Read.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere, aggiornare, creare attività di panner, leggere gli utenti file recenti e condivisi, Per ottenere SharePoint elenco, raccolte e file. Per salvare i file SharePoint elenchi. | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Group.ReadWrite.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere, aggiornare, creare attività di panner, leggere gli utenti file recenti e condivisi, Per ottenere SharePoint elenco, raccolte e file. Per salvare i file SharePoint elenchi. Integrazione in iGlobe CRM Office 365 | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Mail.ReadWrite | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere e aggiornare la posta contrassegnata | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| MailboxSettings.ReadWrite | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere e aggiornare interi calendario, leggere e aggiornare la posta contrassegnata, leggere e aggiornare Outlook To Do interi | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Tasks.ReadWrite | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere e aggiornare interi calaender, leggere e aggiornare Outlook a Do Entreies | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| User.Read | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere e aggiornare interi calaender, leggere e aggiornare Outlook a Do Entreies | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| User.Read.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere e aggiornare interi calendario, leggere e aggiornare Outlook a Fare entreies, Leggere, Aggiornare, Creare attività panner | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| User.ReadBasic.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere e aggiornare interi calendario, leggere e aggiornare Outlook a Fare entreies, Leggere, Aggiornare, Creare attività panner | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| User.ReadWrite | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere e aggiornare interi calaender, leggere e aggiornare Outlook a Do Entreies | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| e-mail | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Consente all'app di leggere l'indirizzo di posta elettronica principale degli utenti ( per SSO). | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| offline_access | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Consente all'app di visualizzare e aggiornare i dati a cui gli hai dato accesso, anche quando gli utenti non utilizzano attualmente l'app. In questo modo l'app non offre autorizzazioni aggiuntive ( per SSO). | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| openid | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Consente agli utenti di accedere all'app con i propri account aziendali o dell'istituto di istruzione e consente all'app di visualizzare le informazioni di base del profilo utente( per SSO). | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| profilo | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Leggere e aggiornare interi calendario, leggere e aggiornare Outlook a Fare entreies, Leggere, Aggiornare, Creare attività panner | e854ea05-68ab-4204-babe-db4a784fb4d16 |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati tramite altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono utilizzare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni di identificazione dell'organizzazione ( OII). Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **OII viene raccolto?** |  **Quale OII viene raccolto?** | **Giustificazione per la raccolta di OII?** | **OII è memorizzato?** | **Giustificazione per l'archiviazione di OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - Calendars.ReadWrite.All | No |  |  |  |  |
>| Exchange - EWS. AccessAsUser.All | No |  |  |  |  |
>| Exchange - Mail.Read | No |  |  |  |  |
>| Exchange - Mail.ReadWrite.All | No |  |  |  |  |
>| Exchange - MailboxSettings.Read | No |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | No |  |  |  |  |
>| Exchange - Tasks.ReadWrite | No |  |  |  |  |
>| SharePoint - File.Lettura | No |  |  |  |  |
>| SharePoint - File.Scrittura | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>Non è possibile accedere all'I EUII.


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

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Visualizzare in una nuova scheda</a>

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
| Le autorizzazioni registrate staticamente dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | No |
| La tua app supporta la multi-tenancy? | Sì |
| La tua app ha un client riservato? | Sì |
| Possiedi tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| La tua app espone api Web? | No |
| La tua app usa le API di anteprima? | No |
| La tua app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
