---
title: Informazioni sull'applicazione per Karma di Sliday LTD
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Karma, le sue politiche di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9da5f26e68be07cc9817c50434e214de3f3784c4
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551636"
---
# <a name="karma"></a>Karma

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 16 dicembre 2019</p>

* <a href="https://teams.microsoft.com/l/app/9ff28b02-ccc5-4cac-9d17-4cf6987c371f" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381640" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Sliday LTD a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Karma |
| ID | WA104381640 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Sliday LTD |
| URL del sito Web partner | [https://karmabot.chat/ms](https://karmabot.chat/ms) |
| URL della pagina Teams informazioni sull'applicazione | [https://karmabot.readme.io/](https://karmabot.readme.io/) |
| URL dell'Informativa sulla privacy | [https://karmabot.readme.io/v3.0/docs/privacy-policy-for-mic...](https://karmabot.readme.io/v3.0/docs/privacy-policy-for-microsoft-teams) |
| URL delle Condizioni d'uso | [https://karmabot.readme.io/docs/karma-end-user-license-agre...](https://karmabot.readme.io/docs/karma-end-user-license-agreement-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Sliday LTD su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | applicazione | Nome, cognome e indirizzo e-mail dell'azienda. Nome, cognome per l'amministratore che deve fare report. Indirizzo e-mail per la comunicazione in merito al Karma, scopi di fatturazione ed herarchia. | Nome visualizzato del consenso dell'amministratore. Accedere e leggere il profilo utente. Descrizione del consenso dell'amministratore. Consente agli utenti di accedere all'app e consente all'app di leggere il profilo degli utenti con accesso. Consente inoltre all'app di leggere le informazioni aziendali di base degli utenti con accesso. Nome visualizzato del consenso utenteArti consegnare e leggere il tuo profilo. Descrizione del consenso dell'utente. Ti consente di accedere all'app con il tuo account aziendale e lasciare che l'app legga il tuo profilo. Consente inoltre all'app di leggere le informazioni aziendali di base. | 9ff28B02-CCC5-4Cac-9D17-4CF6987C371F |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Nome, cognome e indirizzo e-mail dell'azienda Nome, cognome per l'amministratore che deve segnalare l'indirizzo e-mail per la comunicazione in relazione al Karma. L'elenco è necessario ai fini della fatturazione e per dividere gli utenti in massa in dipartimenti separati. | Nome, cognome e indirizzo di posta elettronica della società Nome, cognome per i report rivolti all'amministratore. Indirizzo e-mail per la comunicazione per quanto riguarda karma, scopi di fatturazione e gerarchia degli utenti Karma. |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Archiviamo gli ID tenant e gli ID utente nei registri. Entrambi non sono identificabili.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>1. **Esiste una soluzione DLP? Cosa viene implementato per prevenire le perdite di dati?**

SÌ, i dati sono crittografati sia in transito che a riposo.

2. **Che tipo di meccanismi implementi per assicurarti che l'integrità dei dati sia protetta da errori, corruzione o uso improprio e con quale frequenza sono controllati**

Tutti i server eseguono RAID hardware con livelli RAID diversi, ma in ogni caso, richiede più errori dell'unità contemporaneamente per qualsiasi perdita di dati. Andiamo più al sicuro e abbiamo backup sia automatici che manuali. Il backup dei database viene eseguito automaticamente ogni giorno e archiviato per sette giorni.
Il backup automatico delle macchine virtuali viene eseguito automaticamente ogni settimana e archiviato per 1 mese.

**Istantanee e backup vengono archiviati in una rete interna non visibile pubblicamente.**

3. **Descrivere come assicurarsi che i dati del cliente siano correttamente separati da da altri clienti nelle soluzioni multi-tenant e come controllare che i dati di produzione non siano replicati o utilizzati in ambienti non di produzione**

Archiviato in database diversi.

4. **Che tipo di crittografia proponete (algoritmi, protocolli, lunghezze delle chiavi) per i dati in transito e i dati a riposo**

Tutti i dati in transito sono crittografati da TLS o SSL. HTTP è crittografato dal traffico del database TLS 1.2 o TLS 1.3 crittografato da SSL.

I dati vengono archiviati nel digital ocean cloud center nei data center degli Stati Uniti.

5. **Descrivere come gestire chiavi di crittografia univoche (processo, archiviazione, utilizzo, RACI, SOD) per il proprio utilizzo e per ciascuno tenant**

Gestito da Digital Ocean.

6. **Descrivere il processo di gestione di Access in atto alla fine del provider, sottolineando come garantire la rimozione tempestiva degli accessi non più necessari e come controllare l'adeguatezza dei privilegi al ruolo lavorativo. Descrivere inoltre i processi di riconvalida e la frequenza della sua esecuzione**

Utilizziamo l'autenticazione a due fattori per accedere al pannello di controllo. Solo 3 persone hanno accesso a questo, cambiamo le password ogni mese, teniamo controllati i registri di accesso e ci assicuriamo che le persone che non lavorano più con noi abbiano i loro account rimossi dalla piattaforma.

7. **Fornire la procedura implementata alla fine per gestire gli ID condivisi (ad esempio root, Sys, System e così via), gli ID di gruppo (account generici utilizzati da più persone appartenenti allo stesso team, ad esempio) e gli account locali. Descrivere come limitare, registrare e monitorare l'utilizzo e l'accesso degli account privilegiati ai dispositivi di sicurezza (ad esempio, hypervisor, firewall, scanner di vulnerabilità, sniffer di rete, API, ecc.), come si garantisce che gli utenti che cambiano team o se ne vanno non possano più accedere all'ID gruppo e qual è il livello di tracciabilità di tali ID**

Usiamo 1Password per condividere&#8217;ID condivisibili, abbiamo un feed attività separato ogni volta che è stato effettuato l'accesso alla risorsa condivisa da un deposito di password condiviso. A meno che non sia assolutamente necessario, non utilizziamo account condivisi e utilizziamo invece singoli account. Non è stato possibile accedere a nessuna informazione nel database Karma tramite un accesso condiviso. 2FA viene utilizzato per accedere a 1Password per recuperare un singolo accesso.

8. **Descrivere il processo per garantire e monitorare il rispetto della segregazione dei compiti e la frequenza con cui è controllata**

Abbiamo organizzato incontri mensili che coprono la segregazione dei dazi, l'importanza dell'uso di login dedicato e 2FA ogni accesso possibile.

Il nostro SIEM contiene: registri firewall, registri dei server Web e registri delle applicazioni. SIEM viene analizzato quotidianamente e al ricevimento. I registri vengono conservati per 1 mese e rimossi in modo sicuro dopo tale data.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

