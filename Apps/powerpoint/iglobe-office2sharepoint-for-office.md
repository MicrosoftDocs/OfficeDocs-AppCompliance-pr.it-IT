---
title: Informazioni sull'applicazione per Office2SharePoint per Office di iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Office2SharePoint per Office, i relativi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 1d1fccbab2aab91eacbc5a43ef79462dd536ff6e
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553617"
---
# <a name="office2sharepoint-for-office"></a>Office2SharePoint per Office

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Ultimo aggiornamento da parte dello sviluppatore: 17 novembre 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381787" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da iGlobe a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Office2SharePoint per Office |
| ID | WA104381787 |
| Office 365 client supportati | Excel 2016 o versioni successive su Mac, Excel 2016 o versioni successive su Windows, Excel sul web, Word 2016 o versioni successive su Mac, Word sul web, Word 2016 o versioni successive su Windows, PowerPoint 2016 o versioni successive su Mac, PowerPoint sul web, PowerPoint 2016 o versioni successive su Windows |
| Nome della società partner | iGlobe |
| URL del sito Web partner | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL dell'Informativa sulla privacy | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL delle Condizioni d'uso | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-office2sharepoint) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da iGlobe su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.AccessAsUser.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Consente all'app di avere lo stesso accesso alle informazioni nella directory dell'utente che ha effettuato l'accesso. | 5971c986-9d39-409C-A6F8-1385B1f690ef |
>| Directory.Read.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Verificare la presenza di autorizzazioni e ottenere i siti e gli elenchi. Creare cartelle, ottenere file e salvare file. | 5971c986-9d39-409C-A6F8-1385B1f690ef |
>| Directory.ReadWrite.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Verificare la presenza di autorizzazioni e ottenere i siti e gli elenchi. Creare cartelle, ottenere file e salvare file. | 5971c986-9d39-409C-A6F8-1385B1f690ef |
>| Group.Read.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere i siti del gruppo utenti. | 5971c986-9d39-409C-A6F8-1385B1f690ef |
>| Group.ReadWrite.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per accedere alle e-mail o i messaggi selezionati e ottenere gli allegati. Dal messaggio o aggiungere dal SharePoint o gruppi alla posta. | 5971c986-9d39-409C-A6F8-1385B1f690ef |
>| Mail.ReadWrite | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per accedere alle e-mail o i messaggi selezionati e ottenere gli allegati. Dal messaggio o aggiungere dal SharePoint o gruppi alla posta. | 5971c986-9d39-409C-A6F8-1385B1f690ef |
>| Sites.Manage.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Consente all'applicazione di creare o eliminare raccolte documenti ed elenchi in tutte le raccolte siti per conto dell'utente che ha effettuato l'accesso. | 5971c986-9d39-409C-A6F8-1385B1f690ef |
>| Sites.Read.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere gli utenti SharePoint sito. Ottenere file e salvare allegati dalla posta selezionata. | 5971c986-9d39-409C-A6F8-1385B1f690ef |
>| Sites.ReadWrite.All | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere SharePoint elenco, raccolte e file. Per salvare i file SharePoint elenchi. | 5971c986-9d39-409C-A6F8-1385B1f690ef |
>| User.Read | delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere gli utenti SharePoint siti, OneDrive e siti di gruppo. | 5971c986-9d39-409C-A6F8-1385B1f690ef |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati tramite altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono utilizzare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni di identificazione dell'organizzazione ( OII). Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **OII viene raccolto?** |  **Quale OII viene raccolto?** | **Giustificazione per la raccolta di OII?** | **OII è memorizzato?** | **Giustificazione per l'archiviazione di OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - EWS. AccessAsUser.All | No |  |  |  |  |
>| Exchange - Mail.ReadWrite | No |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | No |  |  |  |  |
>| SharePoint- AllSites.Manage | No |  |  |  |  |
>| SharePoint - AllSites.Write | No |  |  |  |  |
>| SharePoint - File.Scrittura | No |  |  |  |  |
>| SharePoint - User.Read.All | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>iGlobe raccoglie dati per operare in modo efficace e fornirti le migliori esperienze con i nostri prodotti e servizi. Per le licenze: dati raccolti per amministrare l&#8217;artino delle licenze dell'organizzazione, ad esempio quando si distribuisce un componente aggiuntivo gratuito, si crea una sottoscrizione di valutazione o si acquista una sottoscrizione. Vengono raccolte le seguenti informazioni. A fini finanziari: Nome e indirizzo della società Utenti sottoscritti: nome utente ed e-mail


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Tutti i dati dell'applicazione si trova nel tenant del cliente ed è controllato dall'amministratore del tenant come tutti gli altri servizi in Office 365. Nessun dato dell'applicazione viene archiviato nel componente aggiuntivo. Un componente aggiuntivo moderno viene eseguito in un browser in modalità sandbox, &#8220;fuori processo&#8221;. Il componente aggiuntivo può accedere solo ai dati con cui l'utente sta lavorando. Interagisce con i dati degli utenti utilizzando servizi Microsoft.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da iGlobe su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Ti integri con Microsoft Identify Platform (Azure AD)?  | Sì |
| Hai esaminato e rispettato tutte le best practice applicabili descritte nell'elenco di controllo Microsoft Identity Platform integrazione?  | Sì |
| La tua app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Impostazioni predefinite di protezione e qualsiasi altro criterio comune come Blocca autenticazione legacy* Richiedi autenticazione a più fattori per gli amministratori* Richiedi autenticazione a più fattori per la gestione di Azure* Richiedi autenticazione a più fattori per tutti gli utenti* |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate staticamente dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| La tua app supporta la multi-tenancy? | Sì |
| La tua app ha un client riservato? | Sì |
| Possiedi tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| La tua app espone api Web? | No |
| La tua app usa le API di anteprima? | No |
| La tua app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
