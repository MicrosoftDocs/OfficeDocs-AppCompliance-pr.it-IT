---
title: Informazioni sull'applicazione per Casedoc Virtual Hearing by Casedoc
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Casedoc Virtual Hearing, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 49c51cff0f00b33f25b22eb73bde4382be10c6ba
ms.sourcegitcommit: b97ed9e84303967085e6f3f93c80f7b97110194c
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/29/2021
ms.locfileid: "59992176"
---
# <a name="casedoc-virtual-hearing"></a>Casedoc Virtual Hearing

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 28, 2021</p>

* <a href="https://teams.microsoft.com/l/app/3e701664-cc46-49e4-b356-1a7ac6500998" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003164" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Casedoc a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Casedoc Virtual Hearing |
| ID | WA200003164 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Casedoc |
| URL del sito Web del partner | [https://www.casedoc.com](https://www.casedoc.com) |
| URL della Teams info dell'applicazione | [https://casedoc.com/virtual-hearing-for-teams/](https://casedoc.com/virtual-hearing-for-teams/) |
| URL dell'informativa sulla privacy | [https://casedoc.com/wp-content/uploads/2021/07/Casedoc_Priv...](https://casedoc.com/wp-content/uploads/2021/07/Casedoc_Privacy_Policy_2021.pdf) |
| URL delle Condizioni per l'utilizzo | [https://casedoc.com/wp-content/uploads/2020/10/Casedoc_Cust...](https://casedoc.com/wp-content/uploads/2020/10/Casedoc_Customer_Agreement.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Casedoc su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.ReadWrite.All | delegated | Applicazione di ricerca da aggiungere alla scheda riunione | Non vengono archiviati dati | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Calendars.ReadWrite | application | Ricerca di un elenco di eventi del calendario utente, usato per visualizzare l'elenco delle riunioni e i dati dell'evento nell'app. | Non vengono archiviati dati | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Directory.ReadWrite.All | application | Nessun dato raccolto | Non vengono archiviati dati | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Files.ReadWrite.All | application | Elencare i file caricati dall'app | Non vengono archiviati dati | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Group.ReadWrite.All | application | Nessun dato raccolto | Non vengono archiviati dati | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| MailboxSettings.Read | application | Impostazioni della posta dell'utente, fuso orario. Utilizzato per visualizzare il fuso orario corretto per l'utente | Non vengono archiviati dati | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| OnlineMeetings.ReadWrite | delegated | I dati delle riunioni vengono letti e archiviati, usati per visualizzare i dati delle riunioni nell'app | Non vengono archiviati dati | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsAppInstallation.ReadForUser | delegated | L'app elenco è installata per l'utente, usata per aggiungere l'app alla scheda riunione. | Non vengono archiviati dati | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsAppInstallation.ReadWriteForUser | delegated | Usato per aggiungere app alla scheda riunione. | Non vengono archiviati dati | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsTab.Create | delegated | Usato per aggiungere una scheda alla riunione. | Non vengono archiviati dati | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsTab.ReadWrite.All | delegated | Usato per aggiungere una scheda alla riunione. | Non vengono archiviati dati | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| User.Read.All | application | Utilizzato per cercare gli utenti per le riunioni. | Non vengono archiviati dati | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Log di controllo, conservazione in base ai criteri ISMS, ISO 27001

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>N/D

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

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

Queste informazioni sono state fornite da Casedoc sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

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
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | No |
| La tua app usa le API di anteprima? | Sì |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
