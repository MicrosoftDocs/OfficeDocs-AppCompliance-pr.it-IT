---
title: Informazioni sull'applicazione per Priority Matrix di Appfluence Inc
ms.author: elmalova
author: elenamalova
ms.date: 04/16/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Priority Matrix, i relativi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 50814045f621d38df3a4a8ce65fb361d72a6f7a3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552397"
---
# <a name="priority-matrix"></a>Priority Matrix

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Ultimo aggiornamento da parte dello sviluppatore: 16 aprile 2021</p>

* <a href="https://teams.microsoft.com/l/app/5be2b320-a5b7-4221-893c-dee506e4e365" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382005" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Appfluence Inc a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Priority Matrix |
| ID | WA104382005 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Appfluence Inc |
| URL del sito Web partner | [https://appfluence.com](https://appfluence.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://appfluence.com/project-management-integration-for-m...](https://appfluence.com/project-management-integration-for-microsoft-teams/) |
| URL dell'Informativa sulla privacy | [https://appfluence.com/privacy](https://appfluence.com/privacy) |
| URL delle Condizioni d'uso | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Appfluence Inc su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | delegato | Solo quando un nuovo utente viene aggiunto all'account, archiviamo la sua e-mail. | Nella creazione di nuovi account, lo usiamo per suggerire altri membri del team. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| User.ReadBasic.All | delegato | Solo quando un nuovo utente viene aggiunto all'account, archiviamo la sua e-mail. | Nella creazione di nuovi account, lo usiamo per suggerire altri membri del team. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| offline_access | delegato | Archiviamo il token di accesso al fine di eseguire richieste per conto dell'utente | Aggiorna il token senza disturbare l'utente. (Matrice di priorità per Teams) | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| Files.Read.All | delegato | Non memorizzamo alcuna informazione sui file, a meno che l'utente non crei esplicitamente e consapevolmente un elemento Priority Matrix che si collega al file originale. | Nella nostra funzione One-to-One (disponibile tramite la nostra app web e anche i nostri componenti aggiuntivi Outlook/Teams), utilizziamo questa funzione per evidenziare i file SharePoint/OneDrive condivisi tra due utenti nel nostro sistema, come un modo per facilitare le riunioni e la collaborazione complessiva. | Affadfb6-F17B-428F-97F9-9AAE3B6175BC |
>| User.Read | delegato | Le informazioni di base del profilo utente (nome visualizzato, nome, cognome, e-mail, avatar) sono memorizzate da noi. | Ottieni il nome, l'e-mail, l'avatar dell'utente, per personalizzare il suo account con noi. | Affadfb6-F17B-428F-97F9-9AAE3B6175BC |
>| openid | delegato | Archiviamo la connessione SSO per indicare la modalità di accesso per l'utente. | Per accedere agli utenti tramite Single Sign-On. | Affadfb6-F17B-428F-97F9-9AAE3B6175BC |
>| Calendars.Read | delegato | Un piccolo numero di eventi del calendario viene trasformato in attività archiviate nel nostro sistema. | Leggi gli eventi del calendario in modo che possano essere visualizzati nella nostra vista 1:1. Anche per inizializzare nuovi account.  | D76F016F-52C7-41B5-835B-900361D7040C |
>| Mail.Read | delegato | Archiviamo le attività create nel nostro sistema, con un link al messaggio originale. | Utilizzato nel nostro Outlook aggiuntivo per trasformare le e-mail in attività e per visualizzare il lavoro condiviso in visualizzazione 1:1. | D76F016F-52C7-41B5-835B-900361D7040C |
>| Attività.Lettura | delegato | Alcune Outlook/Planner vengono replicate nel nostro sistema per aiutare i nuovi utenti. | Abbiamo avviato nuovi account utente con le loro Graph attività. | D76F016F-52C7-41B5-835B-900361D7040C |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Il bot è in grado di creare attività e assegnarle a un compagno di squadra specifico, e per farlo deve conoscere il loro nome. | No |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì, utilizziamo l'e-mail dell'utente come ID univoco nel nostro sistema, e che viene utilizzato per tracciare gli errori dell'applicazione e per tenere traccia degli eventi chiave nel sistema (download, accesso, versioni delle applicazioni, ecc.) in modo che il nostro team di assistenza clienti possa fornire una risposta rapida alle domande dei clienti. Come parte della nostra conformità gdpr, eliminiamo tutti i dati dei clienti entro 2 settimane da una richiesta di cancellazione, anche se in pratica lo facciamo lo stesso giorno, poiché abbiamo script interni per farlo in modo semi-automatico.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>I dati dell'applicazione vengono archiviati in modo sicuro in un database crittografato con accesso limitato a un piccolo gruppo di amministratori. Al fine di garantire un accesso più sicuro, applichiamo l'autenticazione a 2 fattori, limitiamo l'accesso a un set controllato di indirizzi IP e localizziamo il database nella propria subnet privata, direttamente inaccessibile da Internet aperto.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Appfluence Inc su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Ti integri con Microsoft Identify Platform (Azure AD)?  | Sì |
| Hai esaminato e rispettato tutte le best practice applicabili descritte nell'elenco di controllo Microsoft Identity Platform integrazione?  | Sì |
| La tua app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate staticamente dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| La tua app supporta la multi-tenancy? | Sì |
| La tua app ha un client riservato? | Sì |
| Possiedi tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa eviti di usare? | - Gli URI di reindirizzamento dei caratteri jolly,<br/><br/>- Flusso ROPC (Resource Owner Password Credential) |
| La tua app espone api Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso corretto? | Sì |
| La tua app usa le API di anteprima? | No |
| La tua app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
