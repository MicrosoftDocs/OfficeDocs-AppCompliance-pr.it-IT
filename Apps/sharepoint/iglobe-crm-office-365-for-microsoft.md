---
title: Informazioni sull'applicazione per iGlobe CRM Office 365 per Microsoft Office 365 da iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni sulla sicurezza e conformità disponibili per iGlobe CRM Office 365 per Microsoft Office 365, i criteri di gestione dei dati, le informazioni sul catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5ec2f0c536f45192514218e7a0e5b7110fbfe650
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251665"
---
# <a name="iglobe-crm-office-365-for-microsoft-office-365"></a>iGlobe CRM Office 365 per Microsoft Office 365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: November 17, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379222" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da iGlobe a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | iGlobe CRM Office 365 per Microsoft Office 365 |
| ID | WA104379222 |
| Office 365 client supportati | SharePoint 2013 o versione successiva |
| Nome società partner | iGlobe |
| URL del sito Web del partner | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL dell'informativa sulla privacy | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL delle Condizioni per l'utilizzo | [https://www.iglobecrm.com/content/iglobe-crm-office-365-end...](https://www.iglobecrm.com/content/iglobe-crm-office-365-end-user-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da iGlobe su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Avere accesso ai calendari degli utenti quando si fa clic su un rapporto di riunione dal canlendar in a iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Contacts.ReadWrite | delegated |  Directory.AccessAsUser.All | Consente all'app di avere lo stesso accesso alle informazioni nella directory dell'utente connesso. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.Read.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Verificare l'autorizzazione e ottenere i siti e gli elenchi. Crea cartelle, ottieni i file e salva i file. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.ReadWrite.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Consente all'app di avere lo stesso accesso alle informazioni nella directory dell'utente connesso. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Files.ReadWrite.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Lettura, aggiornamento, creazione attività panner, lettura dei file recenti e condivisi degli utenti, Per ottenere SharePoint, raccolte e file. Per salvare file e dati in SharePoint elenchi. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.Read.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Lettura, aggiornamento, creazione attività panner, lettura dei file recenti e condivisi degli utenti, Per ottenere SharePoint, raccolte e file. Per salvare i file in SharePoint elenchi. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.ReadWrite.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Lettura, aggiornamento, creazione attività panner, lettura dei file recenti e condivisi degli utenti, Per ottenere SharePoint, raccolte e file. Per salvare i file in SharePoint elenchi. Integrazione in iGlobe CRM Office 365 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Mail.ReadWrite | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Svae the eamil to iGlobe CRM and get informatiopn from iGlobe to a new e-amil | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Manage.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Creare, modificare ed eliminare elementi ed elenchi in iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Read.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Leggere gli elementi in iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.ReadWrite.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. |  Modificare ed eliminare elementi ed elenchi in iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Tasks.ReadWrite | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Creare attività di pianificazione da iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| User.Read | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere informazioni su iGlobe CRM per l'utente speficic | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - Calendars.ReadWrite.All | No |  |  |  |  |
>| Exchange - Mail.Read.All | No |  |  |  |  |
>| Exchange - Contacts.Read | No |  |  |  |  |
>| Exchange - EWS. AccessAsUser.All | No |  |  |  |  |
>| Exchange - Tasks.ReadWrite | No |  |  |  |  |
>| SharePoint - AllSites.Manage | No |  |  |  |  |
>| SharePoint - AllSites.Read | No |  |  |  |  |
>|  SharePoint -AllSites.Write | No |  |  |  |  |
>| SharePoint - MyFiles.Write | No |  |  |  |  |
>| SharePoint - Sites.Manage.All | No |  |  |  |  |
>| SharePoint - Sites.Read.All | No |  |  |  |  |
>| SharePoint - Sites.ReadWrite.All | No |  |  |  |  |
>| SharePoint - Sites.Search.All | No |  |  |  |  |
>|  SharePoint - TermStore.Read.All | No |  |  |  |  |
>| SharePoint - TermStore.ReadWrite.All | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



#### <a name="add-in-data-access"></a>Accesso ai dati del componente aggiuntivo

Elenca le autorizzazioni richieste da questa app per accedere ai dati dell'organizzazione, la giustificazione e lo scopo di questa autorizzazione (per cosa l'app usa queste informazioni?) e se l'app archivia queste informazioni nei relativi database.

>| **Autorizzazione**  | **Descrizione** |
>|:----------------|:----------------|
>| Predefiniti | Non&#8217;leggere o apportare modifiche al documento |
>| Invia dati | Può inviare dati tramite Internet |

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

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">Visualizzazione in una nuova scheda</a>

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
