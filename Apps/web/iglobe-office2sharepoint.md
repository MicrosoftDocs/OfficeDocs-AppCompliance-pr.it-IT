---
title: Informazioni sull'applicazione per Office2SharePoint
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Office2SharePoint, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9d063ac1a7cee57ef2bee185ed43a2c3385c06c2
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225014"
---
# <a name="application-information-for-office2sharepoint"></a>Informazioni sull'applicazione per Office2SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 22 giugno 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.o2s" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da iGlobe a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Office2SharePoint |
| ID | 17859280.o2s |
| Nome della società partner | iGlobe |
| URL del sito Web del partner | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL dell'informativa sulla privacy | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL delle condizioni per l'utilizzo | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-office2sharepoint) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da iGlobe sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elencare le [autorizzazioni di Microsoft Graph](/graph/permissions-reference) necessarie per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **ID app Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.AccessAsUser.All | Delegato | Nessun dato viene archiviato nei database dell'applicazione. | Consente all'app di avere lo stesso accesso alle informazioni nella directory dell'utente connesso. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.Read.All | Delegato | Nessun dato viene archiviato nei database dell'applicazione. | Verificare l'autorizzazione e ottenere i siti e gli elenchi. Creare cartelle, ottenere file e salvare i file. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.ReadWrite.All | Delegato | Nessun dato viene archiviato nei database dell'applicazione. | Verificare l'autorizzazione e ottenere i siti e gli elenchi. Creare cartelle, ottenere file e salvare i file. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.Read.All | Delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere i siti del gruppo utenti. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.ReadWrite.All | Delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per accedere ai messaggi di posta selezionati e ottenere gli allegati. Dalla posta elettronica o aggiungere dal sito SharePoint o Gruppi alla posta elettronica. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Manage.All | Delegato | Nessun dato viene archiviato nei database dell'applicazione. | Consente all'applicazione di creare o eliminare raccolte documenti ed elenchi in tutte le raccolte siti per conto dell'utente connesso. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Read.All | Delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere gli utenti SharePoint sito. Recupera i file e salva gli allegati dalla posta selezionata. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.ReadWrite.All | Delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere SharePoint elenco, librerie e file. Per salvare i file negli elenchi SharePoint. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| User.Read | Delegato | Nessun dato viene archiviato nei database dell'applicazione. | Per ottenere gli utenti SharePoint sito, OneDrive e siti di gruppo. | 5971c986-9d39-409c-a6f8-1385b1f690ef |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati tramite altre API Microsoft

Le app e i componenti aggiuntivi basati su Microsoft 365 possono usare altre API Microsoft diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elencare eventuali API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Quale OII è raccolto?** | **Giustificazione per la raccolta dell'OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione dell'OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - EWS. AccessAsUser.All | No |  |  |  |  |
>| Exchange - Mail.ReadWrite | No |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | No |  |  |  |  |
>| SharePoint- AllSites.Manage | No |  |  |  |  |
>| SharePoint - AllSites.Write | No |  |  |  |  |
>| SharePoint - MyFiles.Write | No |  |  |  |  |
>| SharePoint - User.Read.All | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con un servizio non Microsoft, elencare il servizio non Microsoft usato dall'app, i dati trasferiti e includere una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono usati servizi Microsoft.



#### <a name="telemetry-data"></a>Dati di telemetria

Nei dati di telemetria o nei log dell'applicazione vengono visualizzate informazioni personali dell'organizzazione o informazioni personali dell'utente finale( EUII) ? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>iGlobe raccoglie i dati per operare in modo efficace e offrire le migliori esperienze con i nostri prodotti e servizi. Per le licenze: dati raccolti per amministrare l'organizzazione&#8217;'account di licenza, ad esempio quando si distribuiscono componenti aggiuntivi gratuiti, si crea una sottoscrizione di valutazione o si acquista una sottoscrizione. Vengono raccolte le informazioni seguenti. Per scopi finanziari: Nome e indirizzo della società Utenti sottoscritti: nome utente e indirizzo di posta elettronica

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio l'eliminazione, la conservazione, il controllo, l'archiviazione, i criteri degli utenti finali e così via.

>Tutti i dati dell'applicazione si trova nel tenant del cliente ed è controllato dall'amministratore del tenant come tutti gli altri servizi in Office 365. Nel componente aggiuntivo non vengono archiviati dati dell'applicazione. Un componente aggiuntivo moderno viene eseguito in un browser in modalità sandbox, &#8220;fuori processo&#8221;. Il componente aggiuntivo può accedere solo ai dati con cui l'utente sta lavorando. Interagisce con i dati degli utenti usando servizi Microsoft.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni aziendali

Gli esseri umani sono coinvolti nella revisione o nell'analisi di eventuali dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono riportate le informazioni del catalogo [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='informazioni Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da iGlobe sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione dell'applicazione e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di controllo di integrazione Microsoft Identity Platform?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Impostazioni predefinite per la sicurezza e qualsiasi altro criterio comune, ad esempio Blocca autenticazione legacy* Richiedi MFA per gli amministratori* Richiedi MFA per la gestione di Azure* Richiedi MFA per tutti gli utenti* |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app ha un client riservato? | Sì |
| Si è proprietari di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per l'app? | Sì |
| L'app espone eventuali API Web? | No |
| L'app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
