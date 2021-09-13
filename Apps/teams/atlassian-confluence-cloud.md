---
title: Application Information for Confluence Cloud by Atlassian
ms.author: elmalova
author: elenamalova
ms.date: 08/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Confluence Cloud, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 83a34d3ae66bd3cb82fcc9d18ad88ba7ee7c4983
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59281832"
---
# <a name="confluence-cloud"></a>Confluence Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 18, 2021</p>

* <a href="https://teams.microsoft.com/l/app/30bb610c-6321-40fe-a047-056e7d0dac96" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003113" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Atlassian a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Confluence Cloud |
| ID | WA200003113 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Atlassian |
| URL del sito Web del partner | [https://www.atlassian.com](https://www.atlassian.com) |
| URL dell'informativa sulla privacy | [https://www.atlassian.com/legal/privacy-policy](https://www.atlassian.com/legal/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://www.atlassian.com/licensing/marketplace/termsofuse](https://www.atlassian.com/licensing/marketplace/termsofuse) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Atlassian su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegated | - Abbiamo letto l'elenco dei membri di Chat in una riunione, in modo da conoscere l'elenco degli invitati alla riunione.   - Leggiamo gli utenti&#8217; nomi e indirizzi di posta elettronica che vengono visualizzati in modo condizionale nella nostra app per le riunioni. Ad esempio, visualizzare il nome dell'utente corrente che prende le note riunione.   - L'app legge l'utente&#8217;'evento di calendario in cui l'app è stata aggiunta a una riunione in modo da avere informazioni di base sulla riunione come il titolo della riunione. | Esempi di contenuto che raccogliamo e archiviamo includono: il riepilogo e la descrizione aggiunti a un problema JIRA, le pagine create in Confluence, gli archivi e le richieste pull in Bitbucket, i commenti immessi in relazione a un evento imprevisto in Statuspage e qualsiasi feedback fornitoci. Il contenuto include anche i file e i collegamenti caricati nei servizi. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| Chat.ReadBasic | delegated |  - Abbiamo letto l'elenco dei membri di Chat in una riunione, in modo da conoscere l'elenco degli invitati alla riunione.   - Leggiamo gli utenti&#8217; nomi e indirizzi di posta elettronica che vengono visualizzati in modo condizionale nella nostra app per le riunioni. Ad esempio, visualizzare il nome dell'utente corrente che prende le note riunione.   - L'app legge l'utente&#8217;'evento di calendario in cui l'app è stata aggiunta a una riunione in modo da avere informazioni di base sulla riunione come il titolo della riunione. | Esempi di contenuto che raccogliamo e archiviamo includono: il riepilogo e la descrizione aggiunti a un problema JIRA, le pagine create in Confluence, gli archivi e le richieste pull in Bitbucket, i commenti immessi in relazione a un evento imprevisto in Statuspage e qualsiasi feedback fornitoci. Il contenuto include anche i file e i collegamenti caricati nei servizi. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| User.ReadBasic.All | delegated | - Abbiamo letto l'elenco dei membri di Chat in una riunione, in modo da conoscere l'elenco degli invitati alla riunione.   - Leggiamo gli utenti&#8217; nomi e indirizzi di posta elettronica che vengono visualizzati in modo condizionale nella nostra app per le riunioni. Ad esempio, visualizzare il nome dell'utente corrente che prende le note riunione.   - L'app legge l'utente&#8217;'evento di calendario in cui l'app è stata aggiunta a una riunione in modo da avere informazioni di base sulla riunione come il titolo della riunione. | Esempi di contenuto che raccogliamo e archiviamo includono: il riepilogo e la descrizione aggiunti a un problema JIRA, le pagine create in Confluence, gli archivi e le richieste pull in Bitbucket, i commenti immessi in relazione a un evento imprevisto in Statuspage e qualsiasi feedback fornitoci. Il contenuto include anche i file e i collegamenti caricati nei servizi. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| email | delegated | - Abbiamo letto l'elenco dei membri di Chat in una riunione, in modo da conoscere l'elenco degli invitati alla riunione.   - Leggiamo gli utenti&#8217; nomi e indirizzi di posta elettronica che vengono visualizzati in modo condizionale nella nostra app per le riunioni. Ad esempio, visualizzare il nome dell'utente corrente che prende le note riunione.   - L'app legge l'utente&#8217;'evento di calendario in cui l'app è stata aggiunta a una riunione in modo da avere informazioni di base sulla riunione come il titolo della riunione. | Esempi di contenuto che raccogliamo e archiviamo includono: il riepilogo e la descrizione aggiunti a un problema JIRA, le pagine create in Confluence, gli archivi e le richieste pull in Bitbucket, i commenti immessi in relazione a un evento imprevisto in Statuspage e qualsiasi feedback fornitoci. Il contenuto include anche i file e i collegamenti caricati nei servizi. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| offline_access | delegated | - Abbiamo letto l'elenco dei membri di Chat in una riunione, in modo da conoscere l'elenco degli invitati alla riunione.   - Leggiamo gli utenti&#8217; nomi e indirizzi di posta elettronica che vengono visualizzati in modo condizionale nella nostra app per le riunioni. Ad esempio, visualizzare il nome dell'utente corrente che prende le note riunione.   - L'app legge l'utente&#8217;'evento di calendario in cui l'app è stata aggiunta a una riunione in modo da avere informazioni di base sulla riunione come il titolo della riunione. | Esempi di contenuto che raccogliamo e archiviamo includono: il riepilogo e la descrizione aggiunti a un problema JIRA, le pagine create in Confluence, gli archivi e le richieste pull in Bitbucket, i commenti immessi in relazione a un evento imprevisto in Statuspage e qualsiasi feedback fornitoci. Il contenuto include anche i file e i collegamenti caricati nei servizi. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| openid | delegated |  - Abbiamo letto l'elenco dei membri di Chat in una riunione, in modo da conoscere l'elenco degli invitati alla riunione.   - Leggiamo gli utenti&#8217; nomi e indirizzi di posta elettronica che vengono visualizzati in modo condizionale nella nostra app per le riunioni. Ad esempio, visualizzare il nome dell'utente corrente che prende le note riunione.   - L'app legge l'utente&#8217;'evento di calendario in cui l'app è stata aggiunta a una riunione in modo da avere informazioni di base sulla riunione come il titolo della riunione. | Esempi di contenuto che raccogliamo e archiviamo includono: il riepilogo e la descrizione aggiunti a un problema JIRA, le pagine create in Confluence, gli archivi e le richieste pull in Bitbucket, i commenti immessi in relazione a un evento imprevisto in Statuspage e qualsiasi feedback fornitoci. Il contenuto include anche i file e i collegamenti caricati nei servizi. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| profilo | delegated |  - Abbiamo letto l'elenco dei membri di Chat in una riunione, in modo da conoscere l'elenco degli invitati alla riunione.   - Leggiamo gli utenti&#8217; nomi e indirizzi di posta elettronica che vengono visualizzati in modo condizionale nella nostra app per le riunioni. Ad esempio, visualizzare il nome dell'utente corrente che prende le note riunione.   - L'app legge l'utente&#8217;'evento di calendario in cui l'app è stata aggiunta a una riunione in modo da avere informazioni di base sulla riunione come il titolo della riunione. | Esempi di contenuto che raccogliamo e archiviamo includono: il riepilogo e la descrizione aggiunti a un problema JIRA, le pagine create in Confluence, gli archivi e le richieste pull in Bitbucket, i commenti immessi in relazione a un evento imprevisto in Statuspage e qualsiasi feedback fornitoci. Il contenuto include anche i file e i collegamenti caricati nei servizi. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>https://www.atlassian.com/trust/privacy/how-we-handle-your-data

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalogo vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22926' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22926" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Atlassian su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | No |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
