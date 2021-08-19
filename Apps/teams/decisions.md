---
title: Informazioni sull'applicazione per le decisioni in base alle decisioni
ms.author: elmalova
author: elenamalova
ms.date: 06/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per Decisions, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 19a710fc8edbcb5243b81755ce3d61e8bcaa5b25
ms.sourcegitcommit: 3660f89e183c638979a31c295ac059daa6c387dd
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/18/2021
ms.locfileid: "58391899"
---
# <a name="decisions"></a>Decisioni

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 2, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d3d1be68-066c-4967-a74b-9edcf902dcfb" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381880" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Decisions to Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Decisioni |
| ID | WA104381880 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Decisioni |
| URL del sito Web del partner | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| URL dell'informativa sulla privacy | [https://www.meetingdecisions.com/privacy](https://www.meetingdecisions.com/privacy) |
| URL delle Condizioni per l'utilizzo | [https://www.meetingdecisions.com/terms-of-service](https://www.meetingdecisions.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Decisions about how this app collects and stores organizational data and the control that your organization will have over the data the app collects.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated | Usato per leggere le informazioni dall'utente&#8217;calendario per abilitare funzionalità come l'elenco delle riunioni e la ricerca. Offre inoltre all'utente la possibilità di eliminare riunioni specifiche dal calendario quando l'elemento viene eliminato da Decisioni. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Chat.ReadWrite | delegated | Usato per inviare decisioni per il voto e creare elenchi di oratore per singoli elementi dell'agenda direttamente nella chat Microsoft Teams riunione. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Directory.Read.All | delegated | Usato per raccogliere informazioni di base sul tenant Office 365 al momento della registrazione, ad esempio il nome del tenant e i domini verificati. È inoltre necessario per verificare l'appartenenza ai gruppi. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.Read.All | delegated | Usato per leggere i file condivisi con l'utente per unire tali file nella Rubrica riunioni PDF. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.ReadWrite.All | delegated | Usato per fornire agli utenti il supporto per le annotazioni dei file personali. I file con annotazioni vengono archiviati privatamente nell'&#8217;utente OneDrive for Business. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Group.ReadWrite.All | delegated | Usato per creare strutture di cartelle nel Office 365 di&#8217;di SharePoint per le agende delle riunioni, i file correlati e le conversazioni di gruppo.   Nota: gli utenti delle decisioni non avranno mai accesso ad alcuna risorsa (ad esempio, gruppi) a cui non hanno già accesso nel tenant di Office 365'organizzazione. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Mail.Send | delegated | Usato per consentire agli utenti di Decisioni di inviare notifiche ai partecipanti alla riunione, ad esempio aggiornamenti dell'agenda e collegamenti alla riunione per co-autori. I messaggi di posta elettronica passano ai partecipanti alla riunione o alla lista di distribuzione selezionata dal proprietario della riunione. Tutte le notifiche e i messaggi di posta elettronica inviati vengono attivamente inviati dagli utenti di Decisions.  Nota: in questo modo l'utente non può accedere alla posta in arrivo tramite Decisioni. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| MailboxSettings.Read | delegated | Usato per identificare un utente&#8217;preferenze di lingua. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Notes.ReadWrite | delegated | Consente di configurare blocchi appunti privati per le riunioni per prendere appunti e preparare osservazioni e domande. Consente inoltre di archiviare i minuti delle riunioni di gruppo all'interno del blocco appunti OneNote, se il gruppo sceglie di usare OneNote. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Sites.ReadWrite.All | delegated | Consente di creare strutture di cartelle in canali privati per le informazioni sulla riunione. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Tasks.ReadWrite | delegated | Usato per sincronizzare le attività e le decisioni in Microsoft Planner. Consente inoltre agli utenti di esportare attività e decisioni per Excel. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser | delegated | Necessario per installare l'app Decisioni a livello di programmazione in chat. Questa operazione è necessaria prima di aggiungere la scheda Decisioni per l'esperienza di riunione. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser.All | delegated | Necessario per installare l'app Decisioni a livello di programmazione in chat. Questa operazione è necessaria prima di aggiungere la scheda Decisioni per l'esperienza di riunione. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab.Create | delegated | Richiedi l'aggiunta della scheda In-Meeting/Channel in Teams. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab.Read.All | delegated | Obbligatorio per verificare se la scheda è installata o meno. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| User.ReadBasic.All | delegated | Usato per visualizzare nome e cognome, foto e indirizzo di posta elettronica dei membri del gruppo e dei partecipanti esterni. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| profilo | delegated | Usato per accedere. | I dati dei clienti vengono archiviati nel tenant&#8217;del cliente Office 365 e che tutti i dati dei clienti vengono elaborati solo nei dispositivi dei clienti. Il database Decisions mantiene solo i riferimenti agli oggetti nei Office 365 tenant, non ai dati effettivi. Fare riferimento https://www.meetingdecisions.com/security-and-privacy a per ulteriori dettagli. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati forniti dal Cliente durante l'utilizzo del Software sono disponibili solo per il Cliente.  Il servizio viene fornito in Microsoft Office 365 cloud e Microsoft Azure. Tutti i dati dei clienti vengono archiviati nel tenant Microsoft Office 365 clienti. Tutti i dati archiviati o elaborati nel servizio sono anonimi e non tracciabili per singole persone. Di conseguenza, Le decisioni non archiviano, raccolgono o elaborano dati personali per conto del Cliente.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Decisions about how this app handles authentication, authorization, application registration best practices, and other Identity criteria.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Tutto |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
