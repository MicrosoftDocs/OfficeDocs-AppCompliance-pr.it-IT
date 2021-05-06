---
title: Application Information for Smart Connessione for Jira by yasoon GmbH
ms.author: elmalova
author: elenamalova
ms.date: 01/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Smart Connessione per Jira, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 523d22f08ed48e7947f9023a284db0c2bde53fc9
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251645"
---
# <a name="smart-connect-for-jira"></a>Smart Connect for Jira

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 22, 2021</p>

* <a href="https://teams.microsoft.com/l/app/6402de97-ce33-4386-bf28-b37e9e139c09" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002055" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da yasoon GmbH a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Smart Connect for Jira |
| ID | WA200002055 |
| Funzionalità | Bot, estensione per la messaggistica |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | yasoon GmbH |
| URL del sito Web del partner | [https://yasoon.com](https://yasoon.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://yasoon.com/microsoft-teams-for-jira/](https://yasoon.com/microsoft-teams-for-jira/) |
| URL dell'informativa sulla privacy | [https://yasoon.com/privacy-policy-services](https://yasoon.com/privacy-policy-services) |
| URL delle Condizioni per l'utilizzo | [https://yasoon.com/terms-of-use](https://yasoon.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da yasoon GmbH sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Channel.ReadBasic.All | delegated | L'autorizzazione viene utilizzata per consentire all'utente di selezionare uno di questi canali aggiunti in Jira. | ID canale, per scopi di memorizzazione nella cache | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelMessage.Read.Group | application | Consente all'app di mostrare i messaggi del canale collegato in Jira. | ID messaggio per il collegamento dei messaggi ai problemi di Jira | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelMessage.Send | delegated | Non vengono usati dati, questa API viene usata per consentire all'utente di rispondere ai messaggi di canale da Jira. | Nessuno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelSettings.Read.Group | application | Usato per cercare informazioni dettagliate su un canale. | Nessuno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| Chat.ReadWrite | delegated | Usato per consentire all'utente di aggiungere nuove risposte alle chat e visualizzare i messaggi di chat da Jira. | Nessuno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| Member.Read.Group | application | Usato per i controlli delle autorizzazioni, consente all'app di convalidare l'appartenenza al team degli utenti. | Nessuno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| Team.ReadBasic.All | delegated | L'autorizzazione viene utilizzata per consentire all'utente di selezionare uno di questi team aggiunti in Jira. | ID team a scopo di memorizzazione nella cache | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| TeamSettings.Read.Group | application | Consente all'app di leggere le impostazioni del team per rispettare determinate impostazioni predefinite. | Nessuno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| User.ReadBasic.All | delegated | Consente all'utente di selezionare i colleghi da @menzionare in un messaggio di canale | Nessuno | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutte le informazioni non servizi Microsoft OII vengono trasferite a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento di OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Atlassian Jira ed eventualmente uno dei nostri appaltatori, può essere visto qui: https://go.yasoon.com/contractors | Metadati dei messaggi (ID, timestamp), metadati dell'utente e dell'organizzazione (ID utente, ID organizzazione) e indirizzi di posta elettronica degli utenti | Supporto della funzionalità dell'app (ad esempio, corrispondenza degli account di Atlassian con Office) e abilitazione del supporto per la risoluzione dei problemi più velocemente. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Corrispondenza tra gli utenti Teams account con l'account Jira di Atlassian degli utenti | No |  |



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Metadati utente (id)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Lavoriamo solo con servizi che offrono garanzie rigorose sulla privacy dei dati. 

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da yasoon GmbH sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
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
