---
title: Informazioni sull'applicazione per MIPA - Assistente personale di iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/06/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni sulla sicurezza e conformità disponibili per MIPA - Assistente personale, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
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
<p>Last updated by the developer on: November 6, 2020</p>

* <a href="https://teams.microsoft.com/l/app/eec9d2db-2325-43f5-83c7-eac7c5253a87" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000148" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da iGlobe a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | MIPA - Your Personal Assistant |
| ID | WA200000148 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | iGlobe |
| URL del sito Web del partner | [https://mipa.iglobe.dk/](https://mipa.iglobe.dk/) |
| URL della pagina Teams informazioni sull'applicazione | [https://mipa.iglobe.dk/Support](https://mipa.iglobe.dk/Support) |
| URL dell'informativa sulla privacy | [https://instassl.iglobecrm.com/legal-information](https://instassl.iglobecrm.com/legal-information) |
| URL delle Condizioni per l'utilizzo | [https://mipa.iglobe.dk/EULA](https://mipa.iglobe.dk/EULA) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da iGlobe su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Lettura e aggiornamento di interi calender | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Contacts.ReadWrite | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Lettura e aggiornamento di interi calender | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Directory.AccessAsUser.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Lettura, aggiornamento, creazione attività panner, lettura dei file recenti e condivisi degli utenti. Per verificare che l'utente abbia il consenso e abbia accesso all'uso dell'API. | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Directory.ReadWrite.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Lettura, aggiornamento, creazione attività panner, lettura dei file recenti e condivisi degli utenti, Per ottenere SharePoint, raccolte e file. Per salvare i file in SharePoint elenchi. | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Files.ReadWrite.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Lettura, aggiornamento, creazione attività panner, lettura dei file recenti e condivisi degli utenti, Per ottenere SharePoint, raccolte e file. Per salvare i file in SharePoint elenchi. | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Group.Read.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Lettura, aggiornamento, creazione attività panner, lettura dei file recenti e condivisi degli utenti, Per ottenere SharePoint, raccolte e file. Per salvare i file in SharePoint elenchi. | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Group.ReadWrite.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Lettura, aggiornamento, creazione attività panner, lettura dei file recenti e condivisi degli utenti, Per ottenere SharePoint, raccolte e file. Per salvare i file in SharePoint elenchi. Integrazione in iGlobe CRM Office 365 | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Mail.ReadWrite | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Lettura e aggiornamento della posta contrassegnata | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| MailboxSettings.ReadWrite | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Lettura e aggiornamento dei messaggi interi, lettura e aggiornamento della posta contrassegnata, lettura e aggiornamento Outlook To Do interi | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Tasks.ReadWrite | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Lettura e aggiornamento di interi calender, lettura e aggiornamento Outlook a Do Entreies | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| User.Read | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Lettura e aggiornamento di interi calender, lettura e aggiornamento Outlook a Do Entreies | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| User.Read.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Leggere e aggiornare interi calender, Lettura e aggiornamento Outlook a Do Entreies, Read, Update, Create Panner Tasks | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| User.ReadBasic.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Leggere e aggiornare interi calender, Lettura e aggiornamento Outlook a Do Entreies, Read, Update, Create Panner Tasks | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| User.ReadWrite | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Lettura e aggiornamento di interi calender, lettura e aggiornamento Outlook a Do Entreies | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| e-mail | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Consente all'app di leggere l'indirizzo di posta elettronica principale degli utenti ( per SSO). | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| offline_access | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Consente all'app di visualizzare e aggiornare i dati a cui hai concesso l'accesso, anche quando gli utenti attualmente non usano l'app. In questo modo non vengono concesse all'app autorizzazioni aggiuntive ( per SSO). | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| openid | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Consente agli utenti di accedere all'app con i propri account aziendali o dell'istituto di istruzione e consente all'app di visualizzare le informazioni di base del profilo utente( per SSO). | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| profilo | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Leggere e aggiornare interi calender, Lettura e aggiornamento Outlook a Do Entreies, Read, Update, Create Panner Tasks | e854ea05-68ab-4204-babe-db4a784fb4d16 |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - Calendars.ReadWrite.All | No |  |  |  |  |
>| Exchange - EWS. AccessAsUser.All | No |  |  |  |  |
>| Exchange - Mail.Read | No |  |  |  |  |
>| Exchange - Mail.ReadWrite.All | No |  |  |  |  |
>| Exchange - MailboxSettings.Read | No |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | No |  |  |  |  |
>| Exchange - Tasks.ReadWrite | No |  |  |  |  |
>| SharePoint - MyFiles.Read | No |  |  |  |  |
>| SharePoint - MyFiles.Write | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>iGlobe raccoglie i dati per operare in modo efficace e offrire le migliori esperienze con i nostri prodotti e servizi. Per le licenze: dati raccolti per amministrare l'account di licenza dell'organizzazione&#8217;, ad esempio quando si distribuisce un componente aggiuntivo gratuito, si crea una sottoscrizione di valutazione o si acquista una sottoscrizione. Vengono raccolte le informazioni seguenti. 
- Per scopi finanziari: nome e indirizzo della società
- Utenti sottoscritti: nome utente e posta elettronica

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Tutti i dati si trova nel tenant del cliente. Non vengono archiviati dati dell'applicazione. Un componente aggiuntivo moderno viene eseguito in un browser in modalità sandbox, &#8220;fuori processo&#8221;. Interagisce con i dati degli utenti usando servizi Microsoft. Il componente aggiuntivo può accedere solo ai dati con cui l'utente sta lavorando.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da iGlobe sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Impostazioni predefinite di sicurezza e qualsiasi altro criterio comune come Blocca autenticazione legacy* Richiedi MFA per gli amministratori* Richiedi MFA per la gestione di Azure* Richiedi MFA per tutti gli utenti* |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | No |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
