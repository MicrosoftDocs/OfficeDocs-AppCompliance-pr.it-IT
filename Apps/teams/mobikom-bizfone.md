---
title: Informazioni sull'applicazione per Bizfone di MobiKOM
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Bizfone, i relativi criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 20f1497c8cb4541982082a6bfbccd0f4968a8663
ms.sourcegitcommit: b1e752ea527ba6049cdc4f5d12cbd5b4dbd7f5b3
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/27/2021
ms.locfileid: "58673234"
---
# <a name="bizfone"></a>Bizfone

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2021</p>

* <a href="https://teams.microsoft.com/l/app/5be25d59-35cd-4318-83b0-2a5d5668ddcd" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000874" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da MobiKOM a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Bizfone |
| ID | WA200000874 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | MobiKOM |
| URL del sito Web del partner | [https://mobikom.dk](https://mobikom.dk) |
| URL della Teams info dell'applicazione | [https://mobikom.dk/faq/](https://mobikom.dk/faq/) |
| URL dell'informativa sulla privacy | [https://mobikom.dk/privatlivs-og-cookiepolitik/](https://mobikom.dk/privatlivs-og-cookiepolitik/) |
| URL delle Condizioni per l'utilizzo | [https://mobikom.dk/salgs-og-leveringsbetingelser/](https://mobikom.dk/salgs-og-leveringsbetingelser/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da MobiKOM su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegated | I calendari vengono utilizzati per consentire agli utenti di mostrare i propri contatti ai colleghi e di utilizzare le riunioni per configurare la telefonia | I calendari vengono utilizzati per consentire agli utenti di mostrare i propri contatti ai colleghi e di utilizzare le riunioni per configurare la telefonia | [1dd6ac57-e6f0-4995-a57f-b6d074c16e11](https://docs.microsoft.com/microsoft-365-app-certification/azure/1dd6ac57-e6f0-4995-a57f-b6d074c16e11) |
>| Contacts.Read | delegated | I contatti degli utenti possono essere archiviati se vogliono mostrarli nell'app per semplificare la composizione dei contatti | I contatti degli utenti possono essere archiviati se vogliono mostrarli nell'app per semplificare la composizione dei contatti | [1dd6ac57-e6f0-4995-a57f-b6d074c16e11](https://docs.microsoft.com/microsoft-365-app-certification/azure/1dd6ac57-e6f0-4995-a57f-b6d074c16e11) |
>| User.Read | delegated | L'utente letto in questa applicazione viene utilizzato a scopo di identificazione. | L'utente letto in questa applicazione viene utilizzato a scopo di identificazione. | [1dd6ac57-e6f0-4995-a57f-b6d074c16e11](https://docs.microsoft.com/microsoft-365-app-certification/azure/1dd6ac57-e6f0-4995-a57f-b6d074c16e11) |
>| User.Read | delegated | I dati non vengono archiviati. L'applicazione viene semplicemente utilizzata per scopi di autenticazione | I dati non vengono archiviati. L'applicazione viene semplicemente utilizzata per scopi di autenticazione | [fc8f7563-e8ea-4b6d-9622-82775a21a35a](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc8f7563-e8ea-4b6d-9622-82775a21a35a) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| EWS. AccessAsUser.All | Sì | Nome della società, nomi dei dipendenti e numeri di telefono | Per poter mostrare i dati agli utenti nell'app e usarli | Nome della società, nomi dei dipendenti e numeri di telefono | Per poter mostrare i dati agli utenti nell'app e usarli |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Ribbon Communications, Voxbone, team.blue, Fakturaservice.dk A/S, Elastic | Nome della società, nomi dei dipendenti e numeri di telefono | La barra multifunzione fornisce Teams SBC. Voxbone viene utilizzato per i numeri internazionali, ma solo se sono disponibili. team.blue è il nostro provider di hosting. FakturaService.dk'utente viene utilizzato per la fatturazione. Elastic viene utilizzato per la registrazione |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Ogni utente è un dipendente di un'azienda che utilizza i nostri servizi. Hanno un amministratore che può eliminare e modificare i dati. Le DPA sono già in atto prima che gli utenti finali oscintino l'accesso

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da MobiKOM su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Autenticazione a più fattori |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | Sì |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
