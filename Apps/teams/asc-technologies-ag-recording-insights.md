---
title: Application Information for ASC Recording Insights by ASC Technologies AG
ms.author: elmalova
author: elenamalova
ms.date: 08/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per ASC Recording Insights, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 4d3e2f1ec03c2437e12576b0fdff68b06392ae9c
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412581"
---
# <a name="asc-recording-insights"></a>ASC Recording Insights

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 2, 2021</p>

* <a href="https://teams.microsoft.com/l/app/8f79287d-5850-42f1-9af2-48ddf6ef89a8" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000708" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da ASC Technologies AG a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | ASC Recording Insights |
| ID | WA200000708 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | ASC Technologies AG |
| URL del sito Web del partner | [https://asctechnologies.com/english/index.html](https://asctechnologies.com/english/index.html) |
| URL della Teams info dell'applicazione | [https://asctechnologies.com/english/ASC_Recording_Insights_...](https://asctechnologies.com/english/ASC_Recording_Insights_Compliance_Recording_for_Microsoft_Teams.html) |
| URL dell'informativa sulla privacy | [https://teams.asc-recording.app/privacy](https://teams.asc-recording.app/privacy) |
| URL delle Condizioni per l'utilizzo | [https://asctechnologies.com/english/asc_impressum.html](https://asctechnologies.com/english/asc_impressum.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da ASC Technologies AG su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | application | Informazioni sulle riunioni dell'utente | ID oggetto delle riunioni | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| Chat.Read | application | Chat generate degli utenti | ID oggetto delle chat | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| Chat.Read.All | application | Chat generate degli utenti | ID oggetto delle chat | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| Group.Read.All | application | Appartenenza a un gruppo di utenti ad Active Directory | ID oggetto del gruppo AD | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| OnlineMeetings.Read.All | application | Informazioni sulle riunioni dell'utente | ID oggetto delle riunioni | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| User.Read | application | Nome e cognome degli utenti | ID oggetto dell'utente | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| User.ReadBasic.All | application | Dati di base dell'utente | ID oggetto dell'utente | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API di esportazione | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Non abbiamo dati nei sistemi del partner

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da ASC Technologies AG su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | ,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/> |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

