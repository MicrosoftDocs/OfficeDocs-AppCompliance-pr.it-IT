---
title: Informazioni sull'applicazione per Uploader
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Uploader, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 0dec6f3975671223610272950956d4e5fd4085c0
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/05/2022
ms.locfileid: "65226110"
---
# <a name="application-information-for-uploader-by-officeatwork"></a>Informazioni sull'applicazione per Uploader by officeatwork

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 23 giugno 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/officeatwork-ag.uploader" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da officeatwork a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Autore del caricamento |
| ID | officeatwork-ag.uploader |
| Nome della società partner | officeatwork |
| URL del sito Web del partner | [https://www.officeatwork.com](https://www.officeatwork.com) |
| URL dell'informativa sulla privacy | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| URL delle condizioni per l'utilizzo | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da officeatwork sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elencare le [autorizzazioni di Microsoft Graph](/graph/permissions-reference) necessarie per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **ID app Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | Delegato | Nessun dato archiviato. | OneDrive: per poter leggere e scrivere dati nel OneDrive dell'utente. | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| Group.ReadWrite.All | Delegato | Nessun dato archiviato. | Teams: per leggere e scrivere dati in un gruppo. | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| GroupMember.Read.All | Delegato | Nessun dato archiviato. | SharePoint Online - Supporto per i gruppi di sicurezza: per consentire all'app di elencare i gruppi, leggere le proprietà di base dei gruppi e leggere le appartenenze di tutti i gruppi a cui l'utente connesso ha accesso. | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| Sites.Read.All | Delegato | Nessun dato archiviato. | SharePoint Online: per abilitare la lettura dei dati in SharePoint Online, l'utente connesso ha accesso a . Per abilitare il caricamento dei dati in SharePoint Online | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| User.Read | Delegato | Nessun dato archiviato. | Sing-In: per abilitare l'app officeatwork per leggere le proprietà di base dell'utente. | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| User.Read.All | Delegato | Nessun dato archiviato. | Teams: per scoprire a quali gruppi appartiene un utente. | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| offline_access | Delegato | Nessun dato archiviato. | Sing-In: per abilitare l'accesso automatico tramite i token di aggiornamento, come senza, gli utenti dovrebbero accedere manualmente ogni volta che avviano l'app officeatwork. Questo ambito è necessario solo per le applicazioni host non abilitate per l'accesso SSO. | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| openid | Delegato | Nessun dato archiviato. | Sing-In: per consentire agli utenti di accedere all'app officeatwork con il proprio account aziendale e/o Microsoft. | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| profile | Delegato | Nessun dato archiviato. | Sing-In: per visualizzare l'utente connesso nell'app officeatwork. Ciò consente di assicurare/confermare all'utente l'account usato per accedere all'app officeatwork. | f5c9f179-b9a5-4364-8f99-18d203b902ad |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati tramite altre API Microsoft

Le app e i componenti aggiuntivi basati su Microsoft 365 possono usare altre API Microsoft diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elencare eventuali API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Quale OII è raccolto?** | **Giustificazione per la raccolta dell'OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione dell'OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API REST di SharePoint | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con un servizio non Microsoft, elencare il servizio non Microsoft usato dall'app, i dati trasferiti e includere una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono usati servizi Microsoft.



#### <a name="telemetry-data"></a>Dati di telemetria

Nei dati di telemetria o nei log dell'applicazione vengono visualizzate informazioni personali dell'organizzazione o informazioni personali dell'utente finale( EUII) ? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì, gli eventi includono oid e tenantId e vengono inviati ad Azure AppInsights. Gli eventi vengono eliminati automaticamente dopo 90 giorni. Se un cliente desidera eliminare questi dati, può usare il collegamento fornito nell'informativa sulla privacy per avviare l'eliminazione di tali dati.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio l'eliminazione, la conservazione, il controllo, l'archiviazione, i criteri degli utenti finali e così via.

>I dati delle impostazioni delle applicazioni (flag di funzionalità, nome visualizzato dell'organizzazione, tenantId, elenco di id amministratori) vengono archiviati in un'istanza del database di Azure Cosmos (un file per tenant). I file di database sono crittografati e l'accesso è limitato ai tecnici e al personale di supporto di officeatwork selezionati. Il cliente può accedere ai dati delle impostazioni dell'app officeatwork e modificarli usando l'app Web dell'interfaccia di amministrazione.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni aziendali

Gli esseri umani sono coinvolti nella revisione o nell'analisi di eventuali dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono riportate le informazioni del catalogo [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='informazioni Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35750' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35750" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da officeatwork su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione dell'applicazione e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di controllo di integrazione Microsoft Identity Platform?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Impostazioni predefinite per la sicurezza |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | No |
| L'app supporta la multi-tenancy? | Sì |
| L'app ha un client riservato? | Sì |
| Si è proprietari di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per l'app? | Sì |
| Per l'app, cosa si evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per un'applicazione APS<br/>- Flusso ROPC (Resource Owner Password Credential) |
| L'app espone eventuali API Web? | No |
| L'app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
