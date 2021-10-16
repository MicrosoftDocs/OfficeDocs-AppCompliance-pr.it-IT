---
title: Informazioni sull'applicazione per SalesTim di SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 10/09/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni di sicurezza e conformità disponibili per SalesTim, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9d0d5a3653bdbb15f1c2d5946db3325881c57e67
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412766"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: October 9, 2021</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da SalesTim a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | SalesTim |
| ID | WA200001393 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | SalesTim |
| URL del sito Web del partner | [https://www.salestim.com](https://www.salestim.com) |
| URL della Teams info dell'applicazione | [https://www.salestim.com](https://www.salestim.com) |
| URL dell'informativa sulla privacy | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| URL delle Condizioni per l'utilizzo | [https://www.salestim.com/legal/tos](https://www.salestim.com/legal/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da SalesTim su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.ReadWrite.All | delegated | ID degli utenti invitati a un canale dai criteri di appartenenza | L'ID degli utenti invitati a un canale dai criteri di appartenenza sono archiviati nei nostri audit trail | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Directory.AccessAsUser.All | delegated | ID utente. Consente a un utente di selezionare altri utenti in diverse posizioni dell'applicazione, ad esempio selezionando i responsabili approvazione in un flusso di lavoro. | ID utente. Consente a un utente di selezionare altri utenti in diverse posizioni dell'applicazione, ad esempio selezionando i responsabili approvazione in un flusso di lavoro. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Group.ReadWrite.All | entrambi | È&#8217;solo l'archiviazione di gruppi/ID team,&#8217;non vengono archiviati i contenuti di gruppi/team. Consente all'app di creare gruppi, leggere tutte le proprietà e le appartenenze del gruppo per conto dell'utente connesso. Consente inoltre ai proprietari dei gruppi di gestire i propri gruppi e consente ai membri del gruppo di aggiornare il contenuto del gruppo. | È&#8217;solo l'archiviazione di gruppi/ID team,&#8217;non vengono archiviati i contenuti di gruppi/team. Consente all'app di creare gruppi, leggere tutte le proprietà e le appartenenze del gruppo per conto dell'utente connesso. Consente inoltre ai proprietari dei gruppi di gestire i propri gruppi e consente ai membri del gruppo di aggiornare il contenuto del gruppo. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Mail.Send | delegated | ID utente. Microsoft&#8217;i metadati di questa azione, ad esempio la data di notifica, i destinatari, l'ID richiesta. | ID utente. Microsoft&#8217;i metadati di questa azione, ad esempio la data di notifica, i destinatari, l'ID richiesta. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| User.Read.All | entrambi | ID utente e dati del profilo. Consente a un utente di selezionare altri utenti in diverse posizioni dell'applicazione, ad esempio selezionando i responsabili approvazione in un flusso di lavoro. | ID utente. Consente a un utente di selezionare altri utenti in diverse posizioni dell'applicazione, ad esempio selezionando i responsabili approvazione in un flusso di lavoro. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| offline_access | delegated | Token di aggiornamento. Consente all'app di eseguire alcune operazioni e azioni in background come utente. | Token di aggiornamento. Consente all'app di eseguire alcune operazioni e azioni in background come utente. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Microsoft Marketplace | Sì | Tenant ID | Usato per gestire le sottoscrizioni dei clienti | Tenant ID | Usato per gestire le sottoscrizioni dei clienti |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Stiamo usando Intercom come principale applicazione di supporto ai clienti.  | Tenant ID | Stiamo usando l'ID tenant dell'organizzazione per correlare le richieste di supporto dei clienti a un ambiente Microsoft 365 specifico. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Tutti i dati raccolti sono descritti qui: come descritto, i log vengono temporaneamente https://developers.salestim.com/platform/datamanagement.html#application-data archiviati per 15 giorni e quindi eliminati automaticamente.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Stiamo applicando un criterio di conservazione nell'ambito della revisione mensile dello smaltimento dei record &quot; dei &quot; clienti.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da SalesTim su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Autenticazione a più fattori. Consentire solo ai dispositivi registrati in Intune di accedere a servizi specifici. Limitazione delle posizioni utente e degli intervalli IP |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

