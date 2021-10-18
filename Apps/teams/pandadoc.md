---
title: Informazioni sull'applicazione per PandaDoc di PandaDoc
ms.author: elmalova
author: elenamalova
ms.date: 08/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per PandaDoc, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4119b4540bd4326be32adb8a8f0b6bc999cb20c1
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60427958"
---
# <a name="pandadoc"></a>PandaDoc

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 19, 2021</p>

* <a href="https://teams.microsoft.com/l/app/769d6db6-6890-4f70-8088-5943fdeac3c5" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002927" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da PandaDoc a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | PandaDoc |
| ID | WA200002927 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | PandaDoc |
| URL del sito Web del partner | [https://www.pandadoc.com](https://www.pandadoc.com) |
| URL della Teams info dell'applicazione | [https://www.pandadoc.com](https://www.pandadoc.com) |
| URL dell'informativa sulla privacy | [https://www.pandadoc.com/privacy-notice/?utm_source=microso...](https://www.pandadoc.com/privacy-notice/?utm_source=microsoft-teams&amp;utm_medium=partner&amp;utm_campaign=2021-2-inbd-marketplace-websitevisit-pandadoc-privacy) |
| URL delle Condizioni per l'utilizzo | [https://www.pandadoc.com/terms-of-use/](https://www.pandadoc.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da PandaDoc su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | entrambi | per ottenere un elenco di ID di canali per ogni comando ricevuto in precedenza e ottenere gli ID unità file per ogni canale. | I dati non vengono archiviati | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| ChannelSettings.Read.All | entrambi | per ottenere un elenco di ID di canali per ogni comando ricevuto in precedenza e ottenere gli ID unità file per ogni canale.  | I dati non vengono archiviati | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| ChannelSettings.ReadWrite.All | entrambi | per ottenere un elenco di ID di canali per ogni comando ricevuto in precedenza e ottenere gli ID unità file per ogni canale. | I dati non vengono archiviati | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Directory.Read.All | entrambi | Per ottenere gli ID dei team in Microsoft Teams di cui l'utente è un membro diretto. Successivamente, i canali di ricezione per ogni identificatore di comando. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Directory.ReadWrite.All | entrambi | Per ottenere gli ID dei team in Microsoft Teams di cui l'utente è un membro diretto. Successivamente, i canali di ricezione per ogni identificatore di comando. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read | entrambi | per l'utente sso da Tab (esempio - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necessario per ottenere un token utente con accesso a Microsoft Graph e ottenere ulteriormente i file utente. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read.All | entrambi | per l'utente sso da Tab (esempio - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necessario per ottenere un token utente con accesso a Microsoft Graph e ottenere ulteriormente i file utente. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read.Selected | entrambi | per l'utente sso da Tab (esempio - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necessario per ottenere un token utente con accesso a Microsoft Graph e ottenere ulteriormente i file utente. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Group.Read.All | entrambi | per ottenere un elenco di ID di canali per ogni comando ricevuto in precedenza e ottenere gli ID unità file per ogni canale. Documentazione - https://docs.microsoft.com/en-us/graph/api/channel-list?view=graph-rest-1.0&amp ;tabs=http | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Group.ReadWrite.All | entrambi | per ottenere un elenco di ID di canali per ogni comando ricevuto in precedenza e ottenere gli ID unità file per ogni canale. Documentazione - https://docs.microsoft.com/en-us/graph/api/channel-list?view=graph-rest-1.0&amp ;tabs=http | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Team.ReadBasic.All | entrambi | per ottenere gli ID dei team in Microsoft Teams di cui l'utente è un membro diretto. Successivamente, i canali di ricezione per ogni identificatore di comando. Per ottenere gli ID dell'insieme di credenziali dei file, è innanzitutto necessario ottenere un elenco dei team immessi dall'utente. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamSettings.Read.All | entrambi | Per ottenere gli ID dei team in Microsoft Teams di cui l'utente è un membro diretto. Successivamente, i canali di ricezione per ogni identificatore di comando. Per ottenere gli ID dell'insieme di credenziali dei file, è innanzitutto necessario ottenere un elenco dei team immessi dall'utente. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamSettings.ReadWrite.All | entrambi | o ottenere gli ID dei team in Microsoft Teams di cui l'utente è un membro diretto. Successivamente, i canali di ricezione per ogni identificatore di comando. Per ottenere gli ID dell'insieme di credenziali dei file, è innanzitutto necessario ottenere un elenco dei team immessi dall'utente. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamsAppInstallation.ReadWriteSelfForTeam.All | entrambi | necessario per installare l'applicazione in un utente in Team e installare il bot nella chat. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | entrambi | necessario per installare l'applicazione in un utente in Team e installare il bot nella chat. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.Read | entrambi | per l'utente sso da Tab (esempio - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necessario per ottenere un token utente con accesso a Microsoft Graph e ottenere ulteriormente i file utente. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.Read.All | entrambi |  per ottenere gli ID dei team in Microsoft Teams di cui l'utente è un membro diretto. Successivamente, i canali di ricezione per ogni identificatore di comando. Per ottenere gli ID dell'insieme di credenziali dei file, è innanzitutto necessario ottenere un elenco dei team immessi dall'utente. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.ReadWrite.All | entrambi |  per ottenere gli ID dei team in Microsoft Teams di cui l'utente è un membro diretto. Successivamente, i canali di ricezione per ogni identificatore di comando. Per ottenere gli ID dell'insieme di credenziali dei file, è innanzitutto necessario ottenere un elenco dei team immessi dall'utente. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| email | entrambi | per l'utente sso da Tab (esempio - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necessario per ottenere un token utente con accesso a Microsoft Graph e ottenere ulteriormente i file utente. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| offline_access | entrambi | per l'utente sso da Tab (esempio - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necessario per ottenere un token utente con accesso a Microsoft Graph e ottenere ulteriormente i file utente. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| openid | entrambi | per l'utente sso da Tab (esempio - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necessario per ottenere un token utente con accesso a Microsoft Graph e ottenere ulteriormente i file utente. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| profile | entrambi | per l'utente sso da Tab (esempio - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necessario per ottenere un token utente con accesso a Microsoft Graph e ottenere ulteriormente i file utente. | I dati non vengono archiviati. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| PandaDoc API | No |  |  |  |  |
>| MS Graph | No |  |  |  |  |
>| Elementor | No |  |  |  |  |

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

>I nostri contratti per i fornitori rispetteranno i rispettivi obblighi di noi stessi e dei fornitori per quanto riguarda la privacy e la sicurezza dei dati e ogni anno subiamo revisioni di sicurezza/privacy dei nostri fornitori chiave.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21283' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21283" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da PandaDoc sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | No |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | No |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/> |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | Sì |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
