---
title: Informazioni sull'applicazione per LMS365 di ELEARNINGFORCE International
ms.author: elmalova
author: elenamalova
ms.date: 02/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per LMS365, i relativi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 44ed1631c7d0221b463f518f2494b7a8744eef30
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552217"
---
# <a name="lms365"></a>LMS365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 25 febbraio 2021</p>

* <a href="https://teams.microsoft.com/l/app/d136f17e-df84-47f2-97a4-13aa24c0c647" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381467" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da ELEARNINGFORCE International a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | LMS365 |
| ID | WA104381467 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | ELEARNINGFORCE International |
| URL del sito Web partner | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| URL della pagina Teams informazioni sull'applicazione | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| URL dell'Informativa sulla privacy | [https://www.elearningforce.com/privacy](https://www.elearningforce.com/privacy) |
| URL delle Condizioni d'uso | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da ELEARNINGFORCE International su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | applicazione | Nessuno | Consente all'app di espandere i membri del gruppo Active Web, necessari per iscrivere un gruppo di utenti ai corsi. | A1a0B277-0efb-4F00-9661-6D1A3DF3CDDC |
>| Mail.Invia | delegato | Nessuno | L'autorizzazione viene richiesta dinamicamente durante la configurazione dell'account di posta elettronica per la notifica. Consente all'app di inviare messaggi di posta elettronica di notifica | A1a0B277-0efb-4F00-9661-6D1A3DF3CDDC |
>| RoleManagement.Read.Directory | applicazione | Nessuno | Consente all'app di SharePoint dominio durante il provisioning del tenant. Il dominio viene utilizzato per la costruzione degli URL. | A1a0B277-0efb-4F00-9661-6D1A3DF3CDDC |
>| Utente.Invita.Tutti | delegato | Nessuno | Consente all'app di invitare utenti esterni per conto utente connesso corrente | A1a0B277-0efb-4F00-9661-6D1A3DF3CDDC |
>| User.Read | delegato | Nessuno | Accedere e leggere il profilo utente. | A1a0B277-0efb-4F00-9661-6D1A3DF3CDDC |
>| User.Read.All | delegato | Nessuno | Consente all'app di leggere il profilo completo dell'utente connesso corrente. | A1a0B277-0efb-4F00-9661-6D1A3DF3CDDC |
>| User.Read.All | applicazione | Consente all'app di leggere il profilo utente completo. È&#8217;leggere gli utenti e i&#8217; per creare report gerarchici. | I seguenti dati personali vengono memorizzati in un database dedicato per il rispettivo cliente utilizzato per la funzionalità dashboard di Gestione &amp; all'asei motivi all'interno dell'applicazione. Nome account, Nome visualizzato utente, Indirizzo e-mail, Reparto, Titolo professionale, Office, Paese, Città, ID manager/E-mail | A1a0B277-0efb-4F00-9661-6D1A3DF3CDDC |
>| profilo | delegato | Nessuno | Visualizzare il profilo di base dell'utente. | A1a0B277-0efb-4F00-9661-6D1A3DF3CDDC |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati tramite altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono utilizzare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni di identificazione dell'organizzazione ( OII). Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **OII viene raccolto?** |  **Quale OII viene raccolto?** | **Giustificazione per la raccolta di OII?** | **OII è memorizzato?** | **Giustificazione per l'archiviazione di OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Usiamo il Nome solo per visualizzare un messaggio personalizzato quando il Bot saluta l'utente. | I dati personali vengono archiviati in un database di Azure dedicato per il rispettivo cliente utilizzato per la funzionalità dashboard di Gestione &amp; all'asei all'interno dell'applicazione LMS365. | Nome account, Nome visualizzato utente, Indirizzo e-mail, Reparto, Titolo professionale, Office, Paese, Città, ID manager/E-mail |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì, utilizziamo telemetria/registri di Insights Log Analytics che vengono utilizzati solo per la risoluzione dei problemi e hanno un criterio di conservazione di 90 giorni dopo il quale tutti i dati vengono eliminati.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>LMS365 è dotato di una funzione di purga che rimuoverà tutti i dati personali dal database LMS365 dei clienti.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da ELEARNINGFORCE International su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Ti integri con Microsoft Identify Platform (Azure AD)?  | Sì |
| Hai esaminato e rispettato tutte le best practice applicabili descritte nell'elenco di controllo Microsoft Identity Platform integrazione?  | Sì |
| La tua app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Piattaforme del dispositivo, stato del dispositivo, app client |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate staticamente dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| La tua app supporta la multi-tenancy? | Sì |
| La tua app ha un client riservato? | No |
| Possiedi tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| La tua app espone api Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso corretto? | Sì |
| La tua app usa le API di anteprima? | No |
| La tua app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
