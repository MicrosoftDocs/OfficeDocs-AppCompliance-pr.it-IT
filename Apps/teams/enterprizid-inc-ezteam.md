---
title: Informazioni sull'applicazione per ezTeam di EnterprizID Inc
ms.author: elmalova
author: elenamalova
ms.date: 02/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per ezTeam, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: da54d5a540fd43c2bdc25a6f4e31ba88520ecbc3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553177"
---
# <a name="ezteam"></a>ezTeam

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 24 febbraio 2021</p>

* <a href="https://teams.microsoft.com/l/app/b02f0b53-d3b7-4d53-85a9-f820f5ab33c7" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002546" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da EnterprizID Inc a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | ezTeam |
| ID | WA200002546 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | EnterprizID Inc |
| URL del sito Web partner | [https://enterprizid.com](https://enterprizid.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://enterprizid.com/discover/](https://enterprizid.com/discover/) |
| URL dell'Informativa sulla privacy | [https://enterprizid.com/privacy-policy/](https://enterprizid.com/privacy-policy/) |
| URL delle Condizioni d'uso | [https://enterprizid.com/terms-of-use/](https://enterprizid.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da EnterprizID Inc su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.Read.All | delegato | Elenco delle app disponibili all'Teams in modo da poterlo mostrare su un Teams di creazione di richieste | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Application.Read.All | delegato | Consente all'app di leggere applicazioni e entità servizio per conto dell'utente che ha effettuato l'accesso. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.AccessAsUser.All | delegato | Consente all'app di avere lo stesso accesso alle informazioni nella directory dell'utente che ha effettuato l'accesso. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | delegato | Consente all'app di leggere i dati nella directory dell'organizzazione, ad esempio utenti, gruppi e app. | Teams Informazioni sulla proprietà e sull'appartenenza  | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | applicazione | Consente all'app di leggere i dati nella directory dell'organizzazione, ad esempio utenti, gruppi e app, senza un utente con accesso. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | delegato | Consente all'app di leggere e scrivere dati nella directory dell'organizzazione, ad esempio utenti e gruppi | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | applicazione | Consente all'app di leggere e scrivere dati nella directory dell'organizzazione, ad esempio utenti e gruppi, senza un utente con accesso. Non consente l'eliminazione di utenti o gruppi. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Files.Read.All | applicazione | Consente all'app di leggere tutti i file in tutte le raccolte siti senza un utente con accesso. | Quantità di dati sotto la governance dell'utente finale in GB | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Gruppo.Crea | applicazione | Consente all'app di creare gruppi senza un utente con accesso. | Dettagli sulle nuove proprietà del gruppo. | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | delegato | Consente all'app di elencare i gruppi e di leggerne le proprietà e tutte le appartenenze ai gruppi per conto dell'utente che ha effettuato l'accesso. Utilizzato per determinare la mia Teams  | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | applicazione | Consente all'app di leggere le proprietà e le appartenenze dei gruppi e di leggere il calendario e le conversazioni per tutti i gruppi, senza un utente con accesso. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | delegato | Consente all'app di creare gruppi e leggere tutte le proprietà e le appartenenze dei gruppi per conto dell'utente che ha effettuato l'accesso.  | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | applicazione | Consente all'app di creare gruppi, leggere tutte le proprietà e le appartenenze dei gruppi, aggiornare le proprietà e le appartenenze dei gruppi ed eliminare i gruppi. Consente inoltre all'app di leggere e scrivere calendario e conversazioni di gruppo.  | Ultima attività del Team. | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember.Read.All | applicazione | Consente all'app di leggere le appartenenze e le proprietà di base del gruppo per tutti i gruppi senza un utente con accesso. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember.ReadWrite.All | applicazione | Consente all'app di elencare gruppi, leggere le proprietà di base, leggere e aggiornare l'appartenenza ai gruppi a cui l'app ha accesso senza un utente con accesso. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| People.Read.All | applicazione | Consente all'app di leggere l'elenco di persone rilevanti con punteggio di qualsiasi utente, senza un utente che ha effettuato l'accesso. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports.Read.All | delegato | Consente a un'app di leggere tutti i report sull'utilizzo del servizio per conto dell'utente che ha effettuato l'accesso. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports.Read.All | applicazione | Consente a un'app di leggere tutti i report sull'utilizzo del servizio senza un utente con accesso. | Ultima attività utente per gruppo | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Sites.ReadWrite.All | applicazione | Consente all'app di creare, leggere, aggiornare ed eliminare documenti ed elementi di elenco in tutte le raccolte siti senza un utente con accesso. | Primi 10 siti per dimensione per ogni utente | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read | delegato | Consente agli utenti di accedere all'app e consente all'app di leggere il profilo degli utenti con accesso. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read.All | applicazione | Consente all'app di leggere i profili utente senza un utente con accesso. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| offline_access | delegato | Consente all'app di visualizzare e aggiornare i dati a cui gli hai dato accesso, anche quando gli utenti non utilizzano attualmente l'app.  | Notifiche bot | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| openid | delegato | Consente agli utenti di accedere all'app con i propri account aziendali o dell'istituto di istruzione e consente all'app di visualizzare le informazioni di base del profilo utente. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| profilo | delegato | Consente all'app di visualizzare il profilo di base degli utenti (nome, immagine, nome utente) | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Messaggi di benvenuto, approvazione e attestazione elaborano le notifiche | Archiviamo il nome visualizzato delle identità  | Il nostro strumento consente agli utenti finali di creare richieste per diversi articoli in assistenza e memorizzamo il nome visualizzato del richiedente. Una richiesta seguirebbe un flusso di lavoro di approvazione e abbiamo bisogno del nome visualizzato dell'approvatore per visualizzare i dettagli della richiesta. Inoltre, nei membri di un processo di certificazione del team etinchiamo il nome visualizzato dei membri. |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Nome completo utente finale e organizzazione. Le politiche di conservazione e rimozione sono disponibili nella https://enterprizid.com/privacy-policy sezione Conservazione dei dati personali &quot; &quot; dell'utente

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Abbiamo abilitato la gestione degli accessi privilegiati (PMA) in Azure e le identità con privilegi per connettersi alle risorse usano 2FA per aumentare la sicurezza. Usiamo Azure come provider di partner cloud e siamo soggetti alla privacy e alle condizioni di utilizzo di Azure

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da EnterprizID Inc su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Ti integri con Microsoft Identify Platform (Azure AD)?  | Sì |
| Hai esaminato e rispettato tutte le best practice applicabili descritte nell'elenco di controllo Microsoft Identity Platform integrazione?  | Sì |
| La tua app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
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
