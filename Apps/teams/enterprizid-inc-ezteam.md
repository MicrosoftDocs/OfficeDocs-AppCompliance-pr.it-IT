---
title: Informazioni sull'applicazione per ezTeam di EnterprizID Inc
ms.author: elmalova
author: elenamalova
ms.date: 03/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per ezTeam, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 8a058d3d4e8d96a0c915585e75b7c0e53c2f2341
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428803"
---
# <a name="ezteam"></a>ezTeam

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: February 24, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b02f0b53-d3b7-4d53-85a9-f820f5ab33c7" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002546" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da EnterprizID Inc a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | ezTeam |
| ID | WA200002546 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | EnterprizID Inc |
| URL del sito Web del partner | [https://enterprizid.com](https://enterprizid.com) |
| URL della Teams info dell'applicazione | [https://enterprizid.com/discover/](https://enterprizid.com/discover/) |
| URL dell'informativa sulla privacy | [https://enterprizid.com/privacy-policy/](https://enterprizid.com/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://enterprizid.com/terms-of-use/](https://enterprizid.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da EnterprizID Inc su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.Read.All | delegated | Elenco di app disponibili in Teams in modo da poterlo visualizzare nel processo di Teams di creazione delle richieste | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Application.Read.All | delegated | Consente all'app di leggere le applicazioni e le entità servizio per conto dell'utente connesso. | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.AccessAsUser.All | delegated | Consente all'app di avere lo stesso accesso alle informazioni nella directory dell'utente connesso. | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.Read.All | delegated | Consente all'app di leggere i dati nella directory dell'organizzazione, ad esempio utenti, gruppi e app. | Teams Informazioni sulla proprietà e sull'appartenenza  | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.Read.All | application | Consente all'app di leggere i dati nella directory dell'organizzazione, ad esempio utenti, gruppi e app, senza un utente connesso. | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.ReadWrite.All | delegated | Consente all'app di leggere e scrivere dati nella directory dell'organizzazione, ad esempio utenti e gruppi | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.ReadWrite.All | application | Consente all'app di leggere e scrivere dati nella directory dell'organizzazione, ad esempio utenti e gruppi, senza un utente connesso. Non consente l'eliminazione di utenti o gruppi. | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Files.Read.All | application | Consente all'app di leggere tutti i file in tutte le raccolte siti senza un utente connesso. | Quantità di dati sotto la governance degli utenti finali in GB | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.Create | application | Consente all'app di creare gruppi senza un utente connesso. | Dettagli sulle nuove proprietà del gruppo. | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.Read.All | delegated | Consente all'app di elencare i gruppi e di leggerne le proprietà e tutte le appartenenze a gruppi per conto dell'utente connesso. Usato per determinare My Teams  | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.Read.All | application | Consente all'app di leggere le proprietà e le appartenenze ai gruppi e di leggere il calendario e le conversazioni per tutti i gruppi, senza un utente connesso. | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.ReadWrite.All | delegated | Consente all'app di creare gruppi e leggere tutte le proprietà e le appartenenze dei gruppi per conto dell'utente connesso.  | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.ReadWrite.All | application | Consente all'app di creare gruppi, leggere tutte le proprietà e le appartenenze ai gruppi, aggiornare le proprietà e le appartenenze dei gruppi ed eliminare i gruppi. Consente inoltre all'app di leggere e scrivere il calendario e le conversazioni di gruppo.  | Ultima attività del team. | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| GroupMember.Read.All | application | Consente all'app di leggere le appartenenze e le proprietà di base dei gruppi per tutti i gruppi senza un utente connesso. | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| GroupMember.ReadWrite.All | application | Consente all'app di elencare i gruppi, leggere le proprietà di base, leggere e aggiornare l'appartenenza dei gruppi a cui l'app ha accesso senza un utente connesso. | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| People.Read.All | application | Consente all'app di leggere l'elenco di persone pertinenti con punteggio di qualsiasi utente, senza un utente connesso. | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Reports.Read.All | delegated | Consente a un'app di leggere tutti i report sull'utilizzo del servizio per conto dell'utente connesso. | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Reports.Read.All | application | Consente a un'app di leggere tutti i report sull'utilizzo del servizio senza un utente connesso. | Ultima attività utente per gruppo | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Sites.ReadWrite.All | application | Consente all'app di creare, leggere, aggiornare ed eliminare documenti ed elementi di elenco in tutte le raccolte siti senza un utente connesso. | Top 10 sites by size for each user | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| User.Read | delegated | Consente agli utenti di accedere all'app e consente all'app di leggere il profilo degli utenti connessi. | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| User.Read.All | application | Consente all'app di leggere i profili utente senza un utente connesso. | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| offline_access | delegated | Consente all'app di visualizzare e aggiornare i dati a cui hai concesso l'accesso, anche quando gli utenti attualmente non usano l'app.  | Notifiche bot | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| openid | delegated | Consente agli utenti di accedere all'app con i propri account aziendali o dell'istituto di istruzione e consente all'app di visualizzare le informazioni di base del profilo utente. | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| profile | delegated | Consente all'app di visualizzare il profilo di base degli utenti (nome, immagine, nome utente) | N/D | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Notifiche relative a messaggi di benvenuto, approvazione e attestazione | Archiviamo il nome visualizzato delle identità  | Il nostro strumento consente agli utenti finali di creare richieste per diversi elementi del servizio e archiviamo il nome visualizzato del richiedente. Una richiesta segue un flusso di lavoro di approvazione e il nome visualizzato del responsabile approvazione deve essere visualizzato nei dettagli della richiesta. Inoltre, nei membri di un processo di certificazione del team è elencato il nome visualizzato dei membri. |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nome completo dell'utente finale e dell'organizzazione. I criteri di conservazione e rimozione sono disponibili https://enterprizid.com/privacy-policy nella sezione Conservazione dei dati &quot; &quot; personali

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Abbiamo abilitato Privileged Access Management (PMA) in Azure e le identità con privilegi per connettersi alle risorse usano la 2FA per aumentare la sicurezza. Usiamo Azure come provider di partner cloud e siamo soggetti alla privacy e alle condizioni per l'uso di Azure

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da EnterprizID Inc su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | Sì |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
