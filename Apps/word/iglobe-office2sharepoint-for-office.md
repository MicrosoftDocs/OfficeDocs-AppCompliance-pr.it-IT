---
title: Informazioni sull'applicazione per Office2SharePoint per Office da iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 08/12/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni sulla sicurezza e conformità disponibili per Office2SharePoint per Office, i criteri di gestione dei dati, le informazioni sul catalogo app di Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 12b87e9addae70858503bb2d32def94cae657be2
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283794"
---
# <a name="office2sharepoint-for-office"></a>Office2SharePoint per Office

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: August 12, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381787" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da iGlobe a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Office2SharePoint per Office |
| ID | WA104381787 |
| Office 365 client supportati | Excel 2016 o versioni successive su Mac, Excel 2016 o versioni successive su Windows, Excel sul web, Word 2016 o versioni successive su Mac, Word sul web, Word 2016 o versioni successive su Windows, PowerPoint 2016 o versioni successive su Mac, PowerPoint sul web, PowerPoint 2016 o versioni successive su Windows |
| Nome società partner | iGlobe |
| URL del sito Web del partner | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL dell'informativa sulla privacy | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL delle Condizioni per l'utilizzo | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-office2sharepoint) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da iGlobe su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.AccessAsUser.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Consente all'app di avere lo stesso accesso alle informazioni nella directory dell'utente connesso. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Directory.Read.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Verificare l'autorizzazione e ottenere i siti e gli elenchi. Crea cartelle, ottieni i file e salva i file. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Directory.ReadWrite.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Verificare l'autorizzazione e ottenere i siti e gli elenchi. Crea cartelle, ottieni i file e salva i file. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Group.Read.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere gli utenti Siti di gruppo. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Group.ReadWrite.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per accedere alla posta selezionata e ottenere gli allegati. Dalla posta o aggiungere da SharePoint o gruppi al messaggio di posta elettronica. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Mail.ReadWrite | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per accedere alla posta selezionata e ottenere gli allegati. Dalla posta o aggiungere da SharePoint o gruppi al messaggio di posta elettronica. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Sites.Manage.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Consente all'applicazione di creare o eliminare raccolte documenti ed elenchi in tutte le raccolte siti per conto dell'utente connesso. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Sites.Read.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere gli utenti SharePoint sito. Recuperare i file e salvare gli allegati dal messaggio di posta selezionato. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Sites.ReadWrite.All | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere SharePoint, raccolte e file. Per salvare i file in SharePoint elenchi. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| User.Read | delegated | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere gli utenti SharePoint siti, OneDrive e gruppi. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Exchange - EWS. AccessAsUser.All | No |  |  |  |  |
>| Exchange - Mail.ReadWrite | No |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | No |  |  |  |  |
>| SharePoint- AllSites.Manage | No |  |  |  |  |
>| SharePoint - AllSites.Write | No |  |  |  |  |
>| SharePoint - MyFiles.Write | No |  |  |  |  |
>| SharePoint - User.Read.All | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>iGlobe raccoglie i dati per operare in modo efficace e offrire le migliori esperienze con i nostri prodotti e servizi. Per le licenze: dati raccolti per amministrare l'&#8217;dell'account di licenza dell'organizzazione, ad esempio quando si distribuisce un componente aggiuntivo gratuito, si crea una sottoscrizione di valutazione o si acquista una sottoscrizione. Vengono raccolte le informazioni seguenti. Per scopi finanziari: nome e indirizzo della società Utenti sottoscritti: nome utente e posta elettronica


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Tutti i dati dell'applicazione si trova nel tenant del cliente ed è controllato dall'amministratore tenant come tutti gli altri servizi in Office 365. Nel componente aggiuntivo non vengono archiviati dati dell'applicazione. Un componente aggiuntivo moderno viene eseguito in un browser in modalità sandbox, &#8220;fuori processo&#8221;. Il componente aggiuntivo può accedere solo ai dati con cui l'utente sta lavorando. Interagisce con i dati degli utenti usando servizi Microsoft.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da iGlobe sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
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
