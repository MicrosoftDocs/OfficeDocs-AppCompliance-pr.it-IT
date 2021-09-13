---
title: Informazioni sull'applicazione per Myfone di Flexfone
ms.author: elmalova
author: elenamalova
ms.date: 07/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Myfone, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 37967a116553b7c7b83b1809c9b23a56822be5ed
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282817"
---
# <a name="myfone"></a>Myfone

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 15, 2021</p>

* <a href="https://teams.microsoft.com/l/app/5f447fa4-da1f-4651-a0da-d2488a404c19" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000716" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Flexfone a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Myfone |
| ID | WA200000716 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Flexfone |
| URL del sito Web del partner | [https://flexfone.dk](https://flexfone.dk) |
| URL della Teams info dell'applicazione | [https://faq.flexfone.dk/da](https://faq.flexfone.dk/da) |
| URL dell'informativa sulla privacy | [https://flexfone.dk/privatlivs-og-cookiepolitik](https://flexfone.dk/privatlivs-og-cookiepolitik) |
| URL delle Condizioni per l'utilizzo | [https://flexfone.dk/Content/pdf/Slutkundebetingelser.pdf](https://flexfone.dk/Content/pdf/Slutkundebetingelser.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Flexfone sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegated | I calendari vengono utilizzati per consentire agli utenti di mostrare i propri contatti ai colleghi e di utilizzare le riunioni per configurare la telefonia | I calendari vengono utilizzati per consentire agli utenti di mostrare i propri contatti ai colleghi e di utilizzare le riunioni per configurare la telefonia | [cdd5ed6f-ceda-4d46-a522-b7526d6d9e50](https://docs.microsoft.com/microsoft-365-app-certification/azure/cdd5ed6f-ceda-4d46-a522-b7526d6d9e50) |
>| Contacts.Read | delegated | I contatti degli utenti possono essere archiviati se vogliono mostrarli nell'app per semplificare la composizione dei contatti | I contatti degli utenti possono essere archiviati se vogliono mostrarli nell'app per semplificare la composizione dei contatti | [cdd5ed6f-ceda-4d46-a522-b7526d6d9e50](https://docs.microsoft.com/microsoft-365-app-certification/azure/cdd5ed6f-ceda-4d46-a522-b7526d6d9e50) |
>| User.Read | delegated | L'utente letto in questa applicazione viene utilizzato a scopo di identificazione. | L'utente letto in questa applicazione viene utilizzato a scopo di identificazione. | [cdd5ed6f-ceda-4d46-a522-b7526d6d9e50](https://docs.microsoft.com/microsoft-365-app-certification/azure/cdd5ed6f-ceda-4d46-a522-b7526d6d9e50) |
>| User.Read | delegated | I dati non vengono archiviati. L'applicazione viene semplicemente utilizzata per scopi di autenticazione | I dati non vengono archiviati. L'applicazione viene semplicemente utilizzata per scopi di autenticazione | [f0199b83-0ca3-4b41-a23b-d9b234484438](https://docs.microsoft.com/microsoft-365-app-certification/azure/f0199b83-0ca3-4b41-a23b-d9b234484438) |

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

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalogo vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Flexfone sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

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
