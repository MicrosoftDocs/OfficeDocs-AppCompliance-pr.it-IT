---
title: Informazioni sull'applicazione per Karma di Sliday LTD
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Tutte le informazioni di sicurezza e conformità disponibili per Karma, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d76ae661f25980b12ef5db6dff5a1253e77cc2f7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094339"
---
# <a name="karma"></a>Karma

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/9ff28b02-ccc5-4cac-9d17-4cf6987c371f" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381640" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Sliday LTD a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Karma |
| ID | WA104381640 |
| Funzionalità | Bot, scheda, estensione per la messaggistica |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Sliday LTD |
| URL del sito Web del partner | [https://karmabot.chat/ms](https://karmabot.chat/ms) |
| URL della pagina Teams informazioni sull'applicazione | [https://karmabot.readme.io/](https://karmabot.readme.io/) |
| URL dell'informativa sulla privacy | [https://karmabot.readme.io/v3.0/docs/privacy-policy-for-mic...](https://karmabot.readme.io/v3.0/docs/privacy-policy-for-microsoft-teams) |
| URL delle Condizioni per l'utilizzo | [https://karmabot.readme.io/docs/karma-end-user-license-agre...](https://karmabot.readme.io/docs/karma-end-user-license-agreement-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Sliday LTD su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | application | Nome, cognome e indirizzo di posta elettronica della società. Nome, cognome per la segnalazione dell'amministratore. Indirizzo di posta elettronica per la comunicazione in merito a Karma, scopi di fatturazione ed herarchy. | Nome visualizzato del consenso dell'amministratore. Accedere e leggere il profilo utente. Descrizione del consenso dell'amministratore. Consente agli utenti di accedere all'app e consente all'app di leggere il profilo degli utenti connessi. Consente inoltre all'app di leggere le informazioni aziendali di base degli utenti connessi. User consent display nameSign you in and read your profile. Descrizione del consenso dell'utente. Consente di accedere all'app con l'account dell'organizzazione e consentire all'app di leggere il profilo. Consente inoltre all'app di leggere le informazioni di base sull'azienda. | 9ff28b02-ccc5-4cac-9d17-4cf6987c371f |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Nome, cognome e indirizzo di posta elettronica della società Nome, cognome per l'amministratore che segnala l'indirizzo di posta elettronica per la comunicazione in merito a Karma. Il roster è necessario per scopi di fatturazione e per suddividere gli utenti in parti separate. | Nome, cognome e indirizzo di posta elettronica della società Nome, cognome per la segnalazione dell'amministratore. Indirizzo di posta elettronica per la comunicazione in merito a Karma, scopi di fatturazione e gerarchia degli utenti di Karma. |  |



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>L'ID tenant e l'ID utente vengono archiviati nei log. Entrambi non sono identificabili.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>1. **È disponibile una soluzione DLP? Cosa è implementato per evitare perdite di dati?**

SÌ, i dati vengono crittografati sia in transito che in pausa.

2. **Quali tipi di meccanismi vengono implementati per garantire che l'integrità dei dati sia protetta da errori, danneggiamenti o uso improprio e la frequenza con cui vengono controllati**

Tutti i server eseguono RAID hardware con livelli RAID diversi, ma in ogni caso sono necessari più errori di unità contemporaneamente per eventuali perdite di dati. Microsoft è molto sicura e dispone di backup sia automatici che manuali. Il backup dei database viene eseguito automaticamente ogni giorno e archiviato per sette giorni.
Il backup delle macchine virtuali viene eseguito automaticamente ogni settimana e archiviato per 1 mese.

**Gli snapshot e i backup vengono archiviati in una rete interna non visibile pubblicamente.**

3. **Descrivere come assicurarsi che i dati del cliente siano separati correttamente da altri clienti nelle soluzioni multi-tenant e come controllare che i dati di produzione non vengano replicati o utilizzati in ambienti non di produzione**

Archiviati in database diversi.

4. **Che tipo di crittografia si propone (algoritmi, protocolli, lunghezze delle chiavi) per i dati in transito e i dati in pausa**

Tutti i dati in transito sono crittografati da TLS o SSL. HTTP è crittografato da TLS 1.2 o TLS 1.3 Traffico del database crittografato da SSL.

I dati vengono archiviati in Digital ocean cloud center nei data center statunitensi.

5. **Descrivere come gestire le chiavi di crittografia univoche (processo, archiviazione, utilizzo, RACI, SOD) per uso personale e per ognuno dei tenant**

Gestito da Digital Ocean.

6. **Descrivere il processo di gestione degli accessi in atto al termine del provider indicando come garantire la rimozione in tempo reale degli accessi non più necessari e come controllare l'inadeguatezza dei privilegi per il ruolo del processo. Descrivere inoltre i processi di riconvalida e la frequenza di esecuzione**

Usiamo l'autenticazione a due fattori per accedere al pannello di controllo. Solo 3 persone hanno accesso a questo tipo di accesso, cambiano le password ogni mese, mantengono controllati i log di accesso e ci assicuriamo che gli account degli utenti che non lavorano più con noi siano stati rimossi dalla piattaforma.

7. **Fornire la procedura implementata al termine per gestire gli ID condivisi (ad esempio root, Sys, System e così via), gli ID di gruppo (account generici utilizzati da più persone appartenenti allo stesso team, ad esempio) e gli account locali. Descrivere come limitare, registrare e monitorare l'utilizzo e l'accesso degli account con privilegi ai dispositivi di sicurezza (ad esempio, hypervisor, firewall, scanner di vulnerabilità, sniffer di rete, API e così via), come si garantisce che gli utenti che cambiano team o lasciano non possano più accedere all'ID gruppo e qual è il livello di tracciabilità di tali ID**

Usiamo 1Password per condividere l'ID condivisibile&#8217;s, abbiamo un feed attività separato ogni volta che si accede alla risorsa condivisa da un deposito di password condiviso. A meno che non sia assolutamente necessario, non usiamo account condivisi e usiamo invece singoli account. Non è possibile accedere alle informazioni nel database Karma tramite un account di accesso condiviso. 2FA viene utilizzato per accedere a 1Password per recuperare un singolo account di accesso.

8. **Descrivere il processo per garantire e monitorare il rispetto della separazione dei compiti e la frequenza con cui viene controllato**

Abbiamo eseguito riunioni mensili che riguardano la separazione dei doveri, l'importanza dell'uso dedicato dell'accesso e 2FA ogni accesso possibile.

Il nostro SIEM contiene: registri del firewall, log del server Web e registri delle applicazioni. SIEM viene analizzato ogni giorno e al momento della ricezione. I log vengono conservati per 1 mese e rimossi in modo sicuro dopo di che.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

