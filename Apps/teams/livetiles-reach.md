---
title: Informazioni sull'applicazione per la copertura di LiveTiles
ms.author: elmalova
author: elenamalova
ms.date: 03/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Reach, i relativi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 83df050a6f58bc1d0b7d49239b40ddf2ba80849a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551997"
---
# <a name="reach"></a>Reach

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 22 marzo 2021</p>

* <a href="https://teams.microsoft.com/l/app/5df8ebd2-bf7b-4fb5-bb35-0bfbf5d10a23" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002045" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da LiveTiles a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Reach |
| ID | WA200002045 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | LiveTiles |
| URL del sito Web partner | [https://livetilesglobal.com](https://livetilesglobal.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://livetilesglobal.com/products/livetiles-reach/](https://livetilesglobal.com/products/livetiles-reach/) |
| URL dell'Informativa sulla privacy | [https://livetilesglobal.com/privacy-policy](https://livetilesglobal.com/privacy-policy) |
| URL delle Condizioni d'uso | [https://livetilesglobal.com/eula](https://livetilesglobal.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da LiveTiles su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| TeamsActivity.Invia | applicazione | Nessuno | Nessuno | A7c1920D-3AC0-42DB-9757-078A2B321FD8  |
>| User.Read | delegato | User DisplayName, User Email Address, UPN. Necessario per consentire agli utenti di accedere all'app e ottenere informazioni di base dell'utente che ha effettuato l'accesso, ad esempio il nome visualizzato. L'indirizzo e-mail viene utilizzato per inviare notifiche via e-mail.  | User DisplayName, User Email Address, UPN. Necessario per consentire agli utenti di accedere all'app e ottenere informazioni di base dell'utente che ha effettuato l'accesso, ad esempio il nome visualizzato. L'indirizzo e-mail viene utilizzato per inviare notifiche via e-mail.  | D492530A-8CFF-481C-90DA-9C3C3F1Be7DA |
>| User.ReadBasic.All | delegato | User DisplayName, User Email Address, UPN, User Department, User Job Title, User Mobile Telefono Number, User Business Telefono Number, User Office Location. Necessario per consentire agli utenti di cercare altri utenti all'interno dell'app (Rubrica) e visualizzare il profilo di base e le informazioni di contatto di altri utenti.  | nessuno | D492530A-8CFF-481C-90DA-9C3C3F1Be7DA |
>| Directory.Read.All | applicazione | Appartenenza a gruppi, gruppi Active Directory nella directory. L'appartenenza al gruppo degli utenti viene archiviata in una cache per ridurre al minimo le chiamate Graph Microsoft. Necessario per consentire agli utenti di cercare gruppi di Active Directory. Inoltre, questa autorizzazione è necessaria affinché l'applicazione risolva l'appartenenza a gruppi Active Web di utenti nei processi Web del back-end. | Appartenenza al gruppo degli utenti. L'appartenenza al gruppo degli utenti viene archiviata in una cache per ridurre al minimo le chiamate Graph Microsoft. Necessario per consentire agli utenti di cercare gruppi di Active Directory. Inoltre, questa autorizzazione è necessaria affinché l'applicazione risolva l'appartenenza a gruppi Active Web di utenti nei processi Web del back-end.  | D492530A-8CFF-481C-90DA-9C3C3F1Be7DA  |
>| User.Read.All | applicazione | I dati recuperati dal profilo utente dipendono dalla configurazione della funzionalità Audience Targeting specificata all'interno dell'app. Necessario per consentire all'app di leggere i profili utente senza un utente che ha effettuato l'accesso. I dati del profilo di lettura sono necessari per la funzionalità di targeting delle informazioni all'interno dell'applicazione, in modo che le informazioni vengono visualizzate a utenti specifici in base a un valore specifico della proprietà del profilo.  | nessuno | D492530A-8CFF-481C-90DA-9C3C3F1Be7DA  |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft non sono trasferiti** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| SendGrid, OneSignal | indirizzo e-mail, nome visualizzato | Inviare notifiche all'utente tramite e-mail e notifiche push mobili |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>Non è possibile accedere all'I EUII.


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>indirizzo e-mail, UPN. massimo 60 giorni di conservazione, dopo di che sono stati rimossi

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Gli amministratori possono contattare il supporto per qualsiasi richiesta

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da LiveTiles su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Ti integri con Microsoft Identify Platform (Azure AD)?  | Sì |
| Hai esaminato e rispettato tutte le best practice applicabili descritte nell'elenco di controllo Microsoft Identity Platform integrazione?  | No |
| La tua app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Autenticazione a più fattori, limitazione delle posizioni utente e degli intervalli IP |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate staticamente dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| La tua app supporta la multi-tenancy? | Sì |
| La tua app ha un client riservato? | No |
| Possiedi tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa eviti di usare? | - Gli URI di reindirizzamento dei caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una SPA<br/>- Flusso ROPC (Resource Owner Password Credential) |
| La tua app espone api Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso corretto? | Sì |
| La tua app usa le API di anteprima? | Sì |
| La tua app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
