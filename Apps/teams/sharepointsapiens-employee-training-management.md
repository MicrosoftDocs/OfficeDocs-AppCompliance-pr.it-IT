---
title: Informazioni sull'applicazione per la gestione della formazione dei dipendenti SharePoint| Sapiens
ms.author: elmalova
author: elenamalova
ms.date: 05/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Employee Training Management, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a4d2ce3475ce082060bc632d439d0c79770486c2
ms.sourcegitcommit: 0f47d02fff001cd7cba6a7ab9e276e020cfc053e
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/27/2021
ms.locfileid: "53610054"
---
# <a name="employee-training-management"></a>Gestione della formazione dei dipendenti

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 31, 2021</p>

* <a href="https://teams.microsoft.com/l/app/17b6b751-7463-4afd-a3ae-ad26a20c8904" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001512" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da SharePoint| Sapiens a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Gestione della formazione dei dipendenti |
| ID | WA200001512 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | SharePoint|Sapiens |
| URL del sito Web del partner | [https://www.sharepointsapiens.com](https://www.sharepointsapiens.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://www.sharepointsapiens.com/employee-training-managem...](https://www.sharepointsapiens.com/employee-training-management-office365/documentation/teams/) |
| URL dell'informativa sulla privacy | [https://www.sharepointsapiens.com/privacy/](https://www.sharepointsapiens.com/privacy/) |
| URL delle Condizioni per l'utilizzo | [https://addins.sharepointsapiens.com/licensing/services-agr...](https://addins.sharepointsapiens.com/licensing/services-agreement.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da SharePoint| Sapiens su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.ReadBasic.All | delegated | Indirizzo di posta elettronica e nome delle Exchange e delle risorse per abilitare la prenotazione di sale e risorse | Non verranno archiviati dati | [9e8e113c-8a08-4606-b08a-de4decc7252f](https://docs.microsoft.com/microsoft-365-app-certification/azure/9e8e113c-8a08-4606-b08a-de4decc7252f) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Office 365 Exchange Online | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutte le informazioni non servizi Microsoft OII vengono trasferite a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento di OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Mailgun.com (facoltativo), Stripe.com (facoltativo) | Nome e indirizzo della società per la fatturazione se Stripe.com viene utilizzato per la fatturazione, inviti di calendario e risposte all'indirizzo e-mail degli utenti se mailgun viene utilizzato come servizio di posta | Se si sceglie di utilizzare il servizio di posta elettronica anziché il servizio di posta elettronica online di Exchange, i servizi inviano e ricevono posta elettronica tramite l'API e l'infrastruttura di mailgun. Se si sceglie di utilizzare la propria cassetta Exchange, nessun dato verrà elaborato da mailgun. Se si sceglie di utilizzare la carta di credito per pagare le tariffe di sottoscrizione, i dati raccolti verranno controllati ed elaborati da stripe.com. Se si sceglie di acquistare tramite ordine di acquisto e fattura anziché con carta di credito, nessun dato verrà elaborato da stripe.com. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Non verrà archiviata alcuna euii. TenantID e SharePoint dominio verranno archiviati nella telemetria dell'app. I log e i dati di telemetria verranno archiviati per 90 giorni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Tutti i dati vengono archiviati nel sito Web SharePoint del cliente. I dati dei clienti non vengono archiviati altrove, ad eccezione delle impostazioni, delle licenze e delle informazioni sull'utilizzo dell'app.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36018' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36018" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da SharePoint| Sapiens su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/><br/> |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
