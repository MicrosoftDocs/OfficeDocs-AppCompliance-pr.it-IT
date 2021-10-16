---
title: Application Information for Q by ModuleQ
ms.author: elmalova
author: elenamalova
ms.date: 07/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per domande e risposte, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 25c9ce55aae852632170f5926c480f2369da97e5
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410109"
---
# <a name="q"></a>Q

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 8, 2021</p>

* <a href="https://teams.microsoft.com/l/app/72bb25c7-3644-4318-8249-a08e5493a520" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381433" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da ModuleQ a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Q |
| ID | WA104381433 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | ModuleQ |
| URL del sito Web del partner | [https://moduleq.com](https://moduleq.com) |
| URL della Teams info dell'applicazione | [https://moduleq.com/product](https://moduleq.com/product) |
| URL dell'informativa sulla privacy | [https://moduleq.com/privacy-policy/](https://moduleq.com/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://moduleq.com/terms-of-service](https://moduleq.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da ModuleQ su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | application | archivia i dati delle riunioni, ad eccezione del corpo del messaggio e degli allegati | Consente all'applicazione di leggere gli eventi del calendario di un utente per comprendere in modo intelligente le priorità aziendali dell'utente. | [418a1ee4-ca76-4b38-b4b3-8cca25417a6c](https://docs.microsoft.com/microsoft-365-app-certification/azure/418a1ee4-ca76-4b38-b4b3-8cca25417a6c) |
>| Group.Read.All | delegated | Nessuno | Consente all'app di interagire in un team per la condivisione di contenuto. | [418a1ee4-ca76-4b38-b4b3-8cca25417a6c](https://docs.microsoft.com/microsoft-365-app-certification/azure/418a1ee4-ca76-4b38-b4b3-8cca25417a6c) |
>| Mail.Read | application | archivia i dati di posta elettronica, ad eccezione del corpo del messaggio e degli allegati | Consente all'applicazione di leggere la posta di un utente per comprendere in modo intelligente le priorità aziendali dell'utente | [418a1ee4-ca76-4b38-b4b3-8cca25417a6c](https://docs.microsoft.com/microsoft-365-app-certification/azure/418a1ee4-ca76-4b38-b4b3-8cca25417a6c) |
>| User.Read | delegated | token di autenticazione e posta elettronica utente | Consente all'utente di accedere e collegare il proprio account Office 365 con l'account ModuleQ | [418a1ee4-ca76-4b38-b4b3-8cca25417a6c](https://docs.microsoft.com/microsoft-365-app-certification/azure/418a1ee4-ca76-4b38-b4b3-8cca25417a6c) |
>| User.Read.All | delegated | Nessuno | Consenti all'app di ottenere l'Teams di cui fa parte l'utente. Usato solo per la condivisione  | [418a1ee4-ca76-4b38-b4b3-8cca25417a6c](https://docs.microsoft.com/microsoft-365-app-certification/azure/418a1ee4-ca76-4b38-b4b3-8cca25417a6c) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Registriamo un GUID utente interno e i nomi e i domini dell'organizzazione. Al momento non sono disponibili controlli di archiviazione o eliminazione.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati vengono archiviati nel Microsoft Azure Cloud in più microservizi in base alla loro funzione. Tutti i dati identificabili dall'utente vengono crittografati sul lato client con la crittografia AES-256 prima della trasmissione per l'archiviazione. I dati possono essere visualizzati dai tecnici per scopi di debug con l'approvazione da parte dei nostri dirigenti. L'accesso ai dati è controllato tramite VPN interna.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da ModuleQ sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/><br/> |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

