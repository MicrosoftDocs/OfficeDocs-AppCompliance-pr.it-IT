---
title: Application Information for LawToolBox Matters for Outlook, Teams &amp; SharePoint by LawToolBox.com Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per LawToolBox Matters per Outlook, Teams SharePoint, i criteri di gestione dei dati, le informazioni sul catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema &amp; CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 039b83277d1e3a6823b16079ec6a0fa8fbec68d2
ms.sourcegitcommit: 1d47df35430334cfc0c60f7ea0b62392b99b7cbf
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/13/2021
ms.locfileid: "60286013"
---
# <a name="lawtoolbox-matters-for-outlook-teams-amp-sharepoint"></a>LawToolBox Matters for Outlook, Teams &amp; SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 24, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003103" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da LawToolBox.com Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | LawToolBox Matters for Outlook, Teams &amp; SharePoint |
| ID | WA200003103 |
| Office 365 client supportati | Outlook 2013 o versioni successive Windows, Outlook 2016 o versioni successive su Mac, Outlook sul web |
| Nome società partner | LawToolBox.com Inc. |
| URL del sito Web del partner | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| URL dell'informativa sulla privacy | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://www.lawtoolbox.com/customersupport/2019/LawToolBox_...](https://www.lawtoolbox.com/customersupport/2019/LawToolBox_End_User_License_Agreement_and_SLA_LAWTOOLBOX_2019_APR.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da LawToolBox.com Inc. Su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegated | questa autorizzazione è limitata ad accedere ai contatti dell&#8217;utente a cui ha già accesso &#8211; viene utilizzato per consentire agli utenti di recuperare le proprie informazioni del calendario | [Facoltativo] Leggere il calendario dell'utente. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Calendars.ReadWrite | delegated | questa autorizzazione è limitata ad accedere ai contatti dell&#8217;utente a cui ha già accesso &#8211; questa autorizzazione viene utilizzata per consentire agli utenti di recuperare le proprie informazioni del calendario e scrivere nei calendari | Per creare l'invito del calendario nel calendario dell'utente. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Calendars.ReadWrite.Shared | delegated | questa autorizzazione è limitata ad accedere ai contatti dell&#8217;utente a cui ha già accesso &#8211; viene utilizzato per consentire agli utenti di recuperare le proprie informazioni del calendario | Per creare l'invito del calendario nel calendario condiviso. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Contacts.ReadWrite | delegated | questa autorizzazione ha accesso limitato all'utente&#8217;ai contatti a cui ha già accesso.  Questa autorizzazione viene utilizzata per consentire all'utente di cercare i propri contatti di O365 e aggiungere a LawToolBox &#8211; non viene aggiunto automaticamente alcun contatto (può essere revocato se non si desidera che questa funzionalità e i contatti possano essere aggiunti manualmente | [Facoltativo]- per leggere i contatti dell'utente e connettere gli utenti dall'elenco dei contatti al gruppo. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Contacts.ReadWrite.Shared | delegated | usiamo questa autorizzazione per consentire all'utente di cercare contatti O365 condivisi e aggiungere a LawToolBox &#8211; non aggiungiamo automaticamente alcun contatto | [Facoltativo]- Per leggere i contatti condivisi degli utenti per gestire l'elenco dei contatti rilevanti per il caso. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Directory.AccessAsUser.All | delegated | usiamo nel portale di amministrazione per recuperare l'elenco degli utenti dal tenant di O365 da aggiungere al tuo account | [Facoltativo] Leggere le informazioni relative a gruppi e utenti come utente. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Directory.ReadWrite.All | delegated | usiamo nel portale di amministrazione per recuperare l'elenco degli utenti dal tenant di O365 da aggiungere al tuo account | [Facoltativo] Leggere le informazioni relative a gruppi e utenti come utente. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.Read | delegated | in questo modo il componente aggiuntivo può leggere ed elencare i file utente a cui l'utente ha già accesso | [Facoltativo] Leggere i dati dell'OneDrive. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.Read.All | delegated | usiamo questa autorizzazione per leggere ed elencare i file utente a cui l'utente ha già accesso | [Facoltativo]-Lettura dell'OneDrive. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.ReadWrite | delegated | leggiamo i file da Teams, gruppi e OneDrive per le riunioni (se lo revochi impedirà al nostro componente aggiuntivo di elencare i file di materia nelle nostre app) | [Facoltativo]-Leggere e modificare i file nel OneDrive. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.ReadWrite.All | delegated | leggiamo i file da Teams, gruppi e OneDrive per le riunioni (se lo revochi impedirai a LTB di elencare i file di materia nelle nostre app).  L'utente può utilizzare solo il componente aggiuntivo per leggere ed elencare i file utente a cui l'utente ha già accesso | [Facoltativo] File di OneDrive utente di lettura/scrittura associato all'oggetto Matter. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Group.ReadWrite.All | delegated | GroupID, GroupName, GroupEmail | Creiamo un gruppo per ogni materia creata nel nostro sistema. Questo consente agli utenti di archiviare le informazioni relative alla materia nel gruppo, che a sua volta salva i dati nel proprio tenant. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.Read | delegated | usiamo questa autorizzazione per leggere i messaggi di posta elettronica PACER nel componente aggiuntivo di Outlook per aprire automaticamente la questione e anche per leggere i contatti dalla posta elettronica da aggiungere al nostro sistema di contatti  | [Facoltativo] [InProgress] Leggere la posta elettronica dell'utente per Matters. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.ReadWrite | delegated | usiamo questa autorizzazione per leggere i messaggi di posta elettronica PACER nel componente aggiuntivo di Outlook per aprire automaticamente la questione e anche per leggere i contatti dalla posta elettronica da aggiungere al nostro sistema di contatti  | [Facoltativo] [InProgress] Posta elettronica di lettura/scrittura per gli utenti. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.ReadWrite.Shared | delegated | usiamo questa autorizzazione per leggere i messaggi di posta elettronica PACER nel componente aggiuntivo di Outlook per aprire automaticamente la questione e anche per leggere i contatti dalla posta elettronica da aggiungere al nostro sistema di contatti  | [Facoltativo] [InProgress] Posta elettronica di lettura/scrittura per gli utenti. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.Send | delegated | Usiamo questo invio di messaggi di posta elettronica come utente per consentire a un utente di inviare report solo dei dati a cui ha già accesso nel nostro sistema | [Facoltativo] [InProgress] Invia scadenze tramite posta elettronica come utente. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Tasks.ReadWrite.Shared | delegated | questa autorizzazione è limitata ad accedere alle attività dell&#8217;utente a cui ha già accesso &#8211; questa autorizzazione viene utilizzata per consentire agli utenti di recuperare e aggiornare le proprie informazioni sulle attività.  | [Optional]-[InProgress] Read Write Deadlines as Task for users. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.Read | delegated | utilizzato per suggerire contatti recenti da aggiungere a riunioni o contatti | Leggere le informazioni dell'utente. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.ReadWrite | delegated | utilizzato per suggerire contatti recenti da aggiungere a riunioni o contatti | Informazioni utente di lettura/scrittura. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.ReadWrite.All | delegated | questo è necessario per leggere l'API Teams, creare Teams, creare un evento calendario, creare canali, Teams funzionalità di condivisione file | Informazioni utente di lettura/scrittura. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| email | delegated | Email, Office365 UserID, ObjectID, TenantID. | Leggere l'indirizzo di posta elettronica dell'utente. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| profile | delegated | questa operazione è necessaria per l'autenticazione SSO: questa autorizzazione viene utilizzata anche per recuperare le immagini e i nomi salvati nel tenant M365 per visualizzarli in modo che l'utente sappia di essere nella casella degli strumenti corretta | Leggere le informazioni sul profilo utente. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>User Email,UserID, AccessToken, Groups information in our debug log

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I record dei casi vengono conservati a meno che non si riceva una richiesta di eliminazione dei dati.

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

Queste informazioni sono state fornite da LawToolBox.com Inc. Sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Per un maggiore controllo, l'amministratore può implementare le autorizzazioni per le app |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | ,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/> |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
