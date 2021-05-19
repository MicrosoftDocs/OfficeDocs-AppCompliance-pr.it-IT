---
title: Informazioni sull'applicazione per Cloverpop di Cloverpop
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Cloverpop, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: eaee7a04f4d8e74f97eef1fae358f80a0c3e2249
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553227"
---
# <a name="cloverpop"></a>Cloverpop

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 24 agosto 2020</p>

* <a href="https://teams.microsoft.com/l/app/3f8519a6-2428-4088-8d12-1b4fd234ff19" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001803" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Cloverpop a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Cloverpop |
| ID | WA200001803 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Cloverpop |
| URL del sito Web partner | [https://www.cloverpop.com](https://www.cloverpop.com) |
| URL dell'Informativa sulla privacy | [https://www.cloverpop.com/privacy-policy/](https://www.cloverpop.com/privacy-policy/) |
| URL delle Condizioni d'uso | [https://www.cloverpop.com/terms-of-service](https://www.cloverpop.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Cloverpop su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegato | memorizzare i dati degli utenti come. e-mail, oid, givenName, familyName, user avatar, user object id. ID organizzazione(tenantId), nome visualizzato organizzazione, Inoltre archiviamo sui nostri team/nomi di canali laterali, id, membri del team. Quando gli utenti creano e interagiscono con le decisioni, associamo questi dati all'utente, al team e all'organizzazione che li hanno creati. Dobbiamo anche mostrare questa proprietà in un'esperienza utente rispettosa dell'uomo, quindi stiamo memorizzando le informazioni di visualizzazione, ad esempio l'utente&#8217;'avatar. | consente all'utente di accedere e dà all'app l'accesso al proprio UPN per abilitare l'accesso invisibile all'utente&#8221; - e-mail, nome, oid, tid, givenName, cognome, familyName, avatar utente(foto), display dell'organizzazioneNome | 1040474B-572D-4575-A423-95Dd262a8b8a |
>| openid | delegato | Archiviare i dati degli utenti come. e-mail, oid, givenName, familyName, user avatar, user object id. ID organizzazione(tenantId), nome visualizzato organizzazione, Inoltre archiviamo sui nostri team/nomi di canali laterali, id, membri del team. Quando gli utenti creano e interagiscono con le decisioni, associamo questi dati all'utente, al team e all'organizzazione che li hanno creati. Dobbiamo anche mostrare questa proprietà in un'esperienza utente rispettosa dell'uomo, quindi stiamo memorizzando le informazioni di visualizzazione, ad esempio l'utente&#8217;'avatar. | Per implementare &#8220;accedere con Teams&#8221; nella nostra app Web. | 1040474B-572D-4575-A423-95Dd262a8b8a |
>| profilo | delegato | Archiviare i dati degli utenti come. e-mail, oid, givenName, familyName, user avatar, user object id. ID organizzazione(tenantId), nome visualizzato organizzazione, Inoltre archiviamo sui nostri team/nomi di canali laterali, id, membri del team. Quando gli utenti creano e interagiscono con le decisioni, associamo questi dati all'utente, al team e all'organizzazione che li hanno creati. Dobbiamo anche mostrare questa proprietà in un'esperienza utente rispettosa dell'uomo, quindi stiamo memorizzando le informazioni di visualizzazione, ad esempio l'utente&#8217;'avatar. | Per implementare &#8220;accedere con Teams&#8221; nella nostra app Web. | 1040474B-572D-4575-A423-95Dd262a8b8a |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Accediamo ai dati del nome/cognome/nome visualizzato al fine di visualizzare con precisione quali azioni sono state intraprese da utenti specifici in relazione a una decisione. Utilizziamo l'indirizzo e-mail come identificatore univoco per ogni utente nel nostro db in quanto permettiamo a ogni utente di appartenere a più organizzazioni. Accediamo a questi dati solo quando interagiscono con la nostra app, ad esempio se rispondono a un sondaggio. | Archiviamo i dati del nome/cognome/nome visualizzato al fine di visualizzare con precisione quali azioni sono state intraprese da utenti specifici in relazione a una decisione.  Archiviamo l'indirizzo e-mail perché lo usiamo come identificatore univoco per ogni utente nel nostro db in quanto permettiamo a ogni utente di appartenere a più organizzazioni. Archiviamo questi dati solo quando interagiscono con la nostra app, ad esempio se rispondono a un sondaggio. I nostri dati decisionali dovrebbero essere un sistema di registrazione per le decisioni, quindi è importante archiviare i dati per identificare il modo in cui ogni utente coinvolto in una decisione ha contribuito a tale decisione. |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì.
L'ID del team viene visualizzato nei nostri registri quando la nostra app viene interagita in un team.
Abbiamo accesso limitato ai nostri registri di produzione ai nostri tre fondatori che hanno tutti sede negli Stati Uniti.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>L'app Cloverpop è costruita utilizzando Ruby on Rails ed è ospitata su Heroku PaaS (piattaforma come servizio) che utilizza AWS per la sua infrastruttura cloud. Heroku e AWS hanno entrambi rapporti SOC a cui è possibile accedere. La nostra app utilizza PostgreSQL per l'archiviazione dei dati crittografati a riposo ed è un ambiente multi-tenant.
 
Tutto il nostro codice ha test automatizzati scritti per questo che copre la sicurezza dell'accesso ai dati. Ogni compilazione viene sottoposta a un rigoroso processo di revisione del codice per la sicurezza e a un processo di test di controllo qualità manuale che include anche controlli per l'autenticazione dell'utente e l'accesso ai dati attraverso le azioni utente disponibili. C'è una chiara separazione tra il nostro ambiente di produzione e tutti gli altri ambienti, come lo sviluppo e i test.
 
Solo il personale selezionato ha accesso all'ambiente di produzione e al database: i fondatori dell'azienda e una piccola manciata di dipendenti controllati che sono stati sottoposti a controlli dei precedenti e hanno un bisogno quantificato (come l'assistenza clienti).

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

