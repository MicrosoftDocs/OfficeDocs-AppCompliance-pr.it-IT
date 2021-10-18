---
title: Application Information for Zignals by Alight
ms.author: elmalova
author: elenamalova
ms.date: 08/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Zignals, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f0c3c319b43d72bf3c825700cfe3bfe1e93e0d5f
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60434695"
---
# <a name="zignals"></a>Zignals

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 17, 2021</p>

* <a href="https://teams.microsoft.com/l/app/a0b58ca7-958d-4343-a2dc-a75f2eeb0953" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003201" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Alight a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Zignals |
| ID | WA200003201 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Alight |
| URL del sito Web del partner | [https://www.alight.eu](https://www.alight.eu) |
| URL della Teams info dell'applicazione | [https://zignals.eu/zignals-support/](https://zignals.eu/zignals-support/) |
| URL dell'informativa sulla privacy | [https://www.zignals.eu/privacy-policy-zignals-for-teams/](https://www.zignals.eu/privacy-policy-zignals-for-teams/) |
| URL delle Condizioni per l'utilizzo | [https://zignals.eu/terms](https://zignals.eu/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Alight su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegated | Per l'area Riunioni personali si ottengono le riunioni &quot; &quot; dell'utente oggi e domani. | Nessuna informazione viene archiviata nel database delle app. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| Sites.ReadWrite.All | delegated | Tutti i siti di SharePoint seguiti dall'utente vengono visualizzati nell'area My Teamwork e vengono visualizzate tutte le attività SharePoint dell'utente e vengono visualizzate &quot; &quot; nell'area &quot; Attività personali &quot; . | Nessuna informazione viene archiviata nel database delle app. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| Tasks.ReadWrite | delegated | Microsoft legge la pianificazione dell'utente e To Do attività e le visualizza nell'area &quot; Attività. &quot; | Nessuna informazione viene archiviata nel database delle app. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| Team.ReadBasic.All | delegated | I team aggiunti all'utente vengono visualizzati &quot; nell'area My &quot; Teamwork. | Nessuna informazione viene archiviata nel database delle app. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| User.ReadBasic.All | delegated | &quot;Nell'area Documenti viene visualizzato l'utente di cui &quot; è stata collaborazione | Nessuna informazione viene archiviata nel database delle app. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| User.ReadWrite | delegated | I documenti recenti dell'utente vengono visualizzati nell'area &quot; &quot; Documenti. Le app preferite dell'utente vengono archiviate come estensione dello schema in MS Graph. Questo livello di autorizzazione è necessario per leggere e scrivere dati nel grafico. | Nessuna informazione viene archiviata nel database delle app. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| email | delegated | Ottenere la posta elettronica degli utenti (ambito Teams MS standard) | Non archiviato nel database | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| offline_access | delegated | Ambito Teams ms standard | Non archiviato nel database | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| openid | delegated | Accedere agli utenti. | Nessuna informazione viene archiviata nel database delle app. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| profile | delegated | Processo di accesso MS Teams | Non archiviato nel database | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati vengono archiviati solo in Azure. Qui usiamo l'interfaccia dell'amministratore per controllare i dati (incl. eliminazione, controllo e così via)

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Alight sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione dell'applicazione e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | Sì |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
