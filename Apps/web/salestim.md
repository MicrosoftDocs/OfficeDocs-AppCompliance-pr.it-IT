---
title: Informazioni sull'applicazione per SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per SalesTim, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9fce7871fc306b19170cddb2d1524ef7a82a01f4
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/05/2022
ms.locfileid: "65222437"
---
# <a name="application-information-for-salestim-by-salestim"></a>Informazioni sull'applicazione per SalesTim by SalesTim

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 24 giugno 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/salestim.salestim" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da SalesTim a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | SalesTim |
| ID | salestim.salestim |
| Nome della società partner | SalesTim |
| URL del sito Web del partner | [https://salestim.com](https://salestim.com) |
| URL dell'informativa sulla privacy | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| URL delle condizioni per l'utilizzo | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da SalesTim su come questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elencare le [autorizzazioni di Microsoft Graph](/graph/permissions-reference) necessarie per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **ID app Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Delegato | NO | Consentire all'app di installare e aggiornare i propri pacchetti nel catalogo delle app aziendali. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | Delegato | È&#8217;archiviare solo alcuni ID utente, non i dati del profilo. | Consente a un utente di selezionare altri utenti in diverse posizioni dell'applicazione, ad esempio selezionando i responsabili approvazione in un flusso di lavoro. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | Delegato | È&#8217;la memorizzazione solo di gruppi/ID di team, non&#8217;di archiviare i contenuti di gruppi/team. | Consente all'app di creare gruppi, leggere tutte le proprietà dei gruppi e le appartenenze per conto dell'utente connesso. Consente inoltre ai proprietari dei gruppi di gestire i gruppi e ai membri del gruppo di aggiornare il contenuto del gruppo. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | Delegato | È&#8217;archiviare nuovamente i metadati di questa azione, ad esempio la data di notifica, il destinatario (solo ID), l'ID richiesta. | Consente all'app di inviare messaggi di posta elettronica di notifica, ad esempio durante un flusso di lavoro di approvazione. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | Delegato | Alcuni servizi di Azure vengono usati per archiviare i dati, in particolare Redis in Azure e nel database Cosmos | Consente all'app di gestire le unità (file e cartelle) associate a un team durante un processo di provisioning del team. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | Delegato | È&#8217;archiviare solo alcuni ID utente, non i dati del profilo. | Consente all'app di leggere il set completo di proprietà del profilo, report e manager di qualsiasi utente. Viene usato soprattutto durante il processo di assegnazione dei destinatari per filtrare alcuni contenuti in base al profilo utente corrente. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| offline_access | Delegato | No | Consente all'app di eseguire alcune operazioni e azioni in background come utente. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con un servizio non Microsoft, elencare il servizio non Microsoft usato dall'app, i dati trasferiti e includere una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Si usa Intercom come applicazione di supporto principale. Intercom può contenere alcune informazioni di base sul profilo utente, come descritto di seguito: https://developers.salestim.com/platform/datamanagement.html#support-data | Nome dell'azienda | Stiamo usando GitHub API per generare automaticamente i problemi dall'ambiente di produzione. Vengono archiviati anche alcuni log tecnici in GitHub (come descritto di seguito: https://developers.salestim.com/platform/datamanagement.html#error-reporting-data). Questi problemi e log possono contenere alcune informazioni di base sul profilo utente. Questi problemi e log vengono eliminati automaticamente ogni 15 giorni. |



#### <a name="telemetry-data"></a>Dati di telemetria

Nei dati di telemetria o nei log dell'applicazione vengono visualizzate informazioni personali dell'organizzazione o informazioni personali dell'utente finale( EUII) ? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Tutti i dati raccolti sono descritti qui: https://developers.salestim.com/platform/datamanagement.html#application-data come descritto, i log vengono archiviati temporaneamente per 15 giorni e quindi eliminati automaticamente.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio l'eliminazione, la conservazione, il controllo, l'archiviazione, i criteri degli utenti finali e così via.

>La maggior parte dei dati viene archiviata in Azure Cosmos DB.
L'accesso all'ambiente di produzione è limitato a due persone e questi account amministratore vengono applicati a MFA.
Questi account sono dedicati e diversi dagli account aziendali.
I dati vengono crittografati inattivi in tutti i servizi di Azure in uso.
Le distribuzioni negli ambienti di produzione sono automatizzate tramite un ramo protetto dedicato nell'ambiente GitHub, in cui solo due persone possono approvare le modifiche.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni aziendali

Gli esseri umani sono coinvolti nella revisione o nell'analisi di eventuali dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono riportate le informazioni del catalogo [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='informazioni Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da SalesTim sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione dell'applicazione e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di controllo di integrazione Microsoft Identity Platform?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | MFA, Condizioni di posizione |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app ha un client riservato? | Sì |
| Si è proprietari di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per l'app? | Sì |
| Per l'app, cosa si evita di usare? | ,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per un'applicazione APS<br/> |
| L'app espone eventuali API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| L'app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
