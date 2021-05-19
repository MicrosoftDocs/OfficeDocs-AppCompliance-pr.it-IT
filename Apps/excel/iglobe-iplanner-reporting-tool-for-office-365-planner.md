---
title: Informazioni sull'applicazione per lo strumento di reporting iPlanner per Office 365 Planner di iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per lo strumento di reporting iPlanner per Office 365 Planner, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a577fcc75982703bfae0de740a7e69d9d13e509a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548766"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>Strumento di reporting iPlanner per Office 365 Planner

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Ultimo aggiornamento da parte dello sviluppatore: 16 dicembre 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da iGlobe a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Strumento di reporting iPlanner per Office 365 Planner |
| ID | WA104380686 |
| Office 365 client supportati | Excel 2016 o più tardi Windows, Excel sul web, Excel 2016 o versioni successive su Mac |
| Nome della società partner | iGlobe |
| URL del sito Web partner | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL dell'Informativa sulla privacy | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| URL delle Condizioni d'uso | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474836912/Product_42949680354/Asset_9d620695-979f-49e4-bc56-98259b0cdeb2/EULAPlanner.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da iGlobe su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per creare una voce di calendario nel calendario&#8217;dell'utente alla data di scadenza dell'attività. |  |
>| Directory.AccessAsUser.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per verificare il consenso dell'utente e avere accesso all'utilizzo dell'API. |  |
>| Directory.ReadWrite.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere l'attività di pianificazione Outlook To Do, contrassegnare i messaggi di posta elettronica e aggiornarli. Per creare una nuova attività planner. |  |
>| Files.ReadWrite.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per accedere al file come allegato e caricare file in un'attività. |  |
>| Group.Read.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere l'elenco dei piani e aggiornare l'attività. |  |
>| Group.ReadWrite.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere l'attività di pianificazione e aggiungere nuove attività, aggiornare il secchio e la linea di nuoto. |  |
>| Mail.Read | delegato | Nessun dato viene archiviato nei database dell'applicazione. | User.Read, per ottenere l'attività di pianificazione Outlook To Do, messaggi di posta elettronica contrassegnati e aggiornarli. Per creare una nuova attività planner |  |
>| Mail.ReadWrite | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per visualizzare le e-mail e inviare posta. |  |
>| Mail.ReadWrite.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Ottenere l'oggetto della posta dal messaggio selezionato. Consente all'app di ottenere informazioni dal messaggio di posta elettronica selezionato, consentendo di copiare il campo di descrizione nella descrizione dell'attività e consentendo di salvare gli allegati dalla posta o dalla posta stessa all'attività. Invia notifica. |  |
>| Tasks.ReadWrite | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere gli utenti che hanno effettuato l'accesso Outlook To Do e aggiornare User.Read, per ottenere l'attività di pianificazione Outlook To Do, contrassegnare i messaggi di posta elettronica e aggiornarli. Per creare una nuova attività planner. |  |
>| User.Read | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Accedere e leggere il profilo utente |  |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



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

