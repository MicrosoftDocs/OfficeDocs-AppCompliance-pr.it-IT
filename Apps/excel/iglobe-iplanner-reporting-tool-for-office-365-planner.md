---
title: Application Information for iPlanner reporting tool for Office 365 Planner by iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni di sicurezza e conformità disponibili per lo strumento di creazione di report iPlanner per Office 365 Planner, i criteri di gestione dei dati, le informazioni sul catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3591c67721188d8dc70bf4f2cf0e34bdb9ffc506
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/22/2021
ms.locfileid: "53526052"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>Strumento di reporting iPlanner per Office 365 Planner

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da iGlobe a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Strumento di reporting iPlanner per Office 365 Planner |
| ID | WA104380686 |
| Office 365 client supportati | Excel 2016 o versioni successive Windows, Excel sul web, Excel 2016 o versioni successive su Mac |
| Nome società partner | iGlobe |
| URL del sito Web del partner | [https://iglobecrm.com/](https://iglobecrm.com/) |
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
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per creare una voce di calendario nel calendario&#8217;'utente alla data di scadenza dell'attività. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Directory.AccessAsUser.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per verificare che l'utente abbia il consenso e abbia accesso all'uso dell'API. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Directory.ReadWrite.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere l'attività di pianificazione Outlook To Do, contrassegnare i messaggi di posta elettronica e aggiornarli. Per creare una nuova attività di Planner. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Files.ReadWrite.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per accedere ai file come allegati e caricare file in un'attività. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.Read.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere l'elenco dei piani e aggiornare l'attività. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.ReadWrite.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere l'attività di pianificazione e aggiungere nuove attività, aggiornare il bucket e la linea di nuoto. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.Read | delegated | Nessun dato viene archiviato nei database dell'applicazione. | User.Read, per ottenere l'attività di pianificazione Outlook To Do messaggi di posta elettronica contrassegnati e aggiornarli. Per creare una nuova attività di Planner | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.ReadWrite | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per visualizzare i messaggi e inviare posta. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.ReadWrite.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Ottenere l'oggetto della posta dal messaggio selezionato. Consente all'app di ottenere informazioni dal messaggio di posta elettronica selezionato, consentendo di copiare il campo della descrizione nella descrizione dell'attività e di salvare gli allegati dalla posta o dalla posta stessa all'attività. Invia notifica. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Tasks.ReadWrite | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere l'accesso degli utenti Outlook To Do e aggiornare User.Read, per ottenere l'attività di pianificazione Outlook To Do, contrassegnare i messaggi di posta elettronica e aggiornarli. Per creare una nuova attività di Planner. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Accedere e leggere il profilo utente | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



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

