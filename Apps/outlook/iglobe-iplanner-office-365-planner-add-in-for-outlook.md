---
title: Application Information for iPlanner Office 365 Planner Add-in for Outlook by iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 08/28/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per il componente aggiuntivo planner iPlanner Office 365 per Outlook, i criteri di gestione dei dati, le informazioni sul catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ce453be96beb466b4420912a29b30593851f3547
ms.sourcegitcommit: 9010c9bace5d935309eae5098f5a126a55270eb6
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/18/2021
ms.locfileid: "59436437"
---
# <a name="iplanner-office-365-planner-add-in-for-outlook"></a>Componente aggiuntivo iPlanner Office 365 Planner per Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: August 28, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380147" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da iGlobe a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Componente aggiuntivo iPlanner Office 365 Planner per Outlook |
| ID | WA104380147 |
| Office 365 client supportati | Outlook 2013 o versioni successive Windows, Outlook 2016 o versioni successive su Mac, Outlook sul web |
| Nome società partner | iGlobe |
| URL del sito Web del partner | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL dell'informativa sulla privacy | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| URL delle Condizioni per l'utilizzo | [https://iglobecrm.com/content/end-user-license-agreement-ig...](https://iglobecrm.com/content/end-user-license-agreement-iglobe-iplanner-add-ins) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da iGlobe su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere l'attività di pianificazione e aggiungere nuove attività, aggiornare il bucket e la linea di nuoto per l'utente specifico | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Contacts.ReadWrite | delegated | Nessun dato viene archiviato nei database dell'applicazione. | per creare un appuntamento nel calendario degli utenti alla data di scadenza delle attività | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Directory.AccessAsUser.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Consente all'app di avere lo stesso accesso alle informazioni nella directory dell'utente connesso. | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Files.Read | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per accedere a un file come allegato e caricare file in un'attività | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Files.ReadWrite.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Ottenere l'oggetto della posta dal messaggio selezionato. Consente all'app di ottenere informazioni dal messaggio di posta elettronica selezionato, consentendo di copiare il campo della descrizione nella descrizione dell'attività e di salvare gli allegati dalla posta o dalla posta stessa all'attività. | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Group.Read.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. |  per ottenere l'attività planner e aggiungere nuove attività aggiornare il bucket e la linea di nuoto per l'utente specifico | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| User.Read | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere l'attività di pianificazione e aggiungere nuove attività, aggiornare il bucket e la linea di nuoto per l'utente specifico | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| User.ReadBasic.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. |  Verificare l'autorizzazione e ottenere l'attività di pianificazione e aggiungere nuove attività aggiornare il bucket e la linea di nuoto per l'utente specifico | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| profile | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere l'attività di pianificazione e aggiungere nuove attività, aggiornare il bucket e la linea di nuoto per l'utente specifico | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione . Elenca tutte le API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Exchange - EWS. AccessAsUser.All | No |  |  |  |  |
>| Exchange - Mail.Read.All | No |  |  |  |  |
>| SharePoint - AllSites.Manage | No |  |  |  |  |
>| SharePoint - AllSites.Read | No |  |  |  |  |
>| SharePoint - AllSites.Write | No |  |  |  |  |
>| SharePoint - MyFiles.Read | No |  |  |  |  |
>| SharePoint - MyFiles.Write | No |  |  |  |  |

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

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35757' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35757" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da iGlobe sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Impostazioni predefinite di sicurezza e qualsiasi altro criterio comune come Blocca autenticazione legacy* Richiedi MFA per gli amministratori* Richiedi MFA per la gestione di Azure* Richiedi MFA per tutti gli utenti* |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
