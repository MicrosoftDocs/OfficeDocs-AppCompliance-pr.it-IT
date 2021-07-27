---
title: Informazioni sull'applicazione per Cloverpop di Cloverpop
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Cloverpop, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3865c07aca73134fd9029ee0550559d9a4f93fd2
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521869"
---
# <a name="cloverpop"></a>Cloverpop

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2020</p>

* <a href="https://teams.microsoft.com/l/app/3f8519a6-2428-4088-8d12-1b4fd234ff19" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001803" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Cloverpop a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Cloverpop |
| ID | WA200001803 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Cloverpop |
| URL del sito Web del partner | [https://www.cloverpop.com/](https://www.cloverpop.com/) |
| URL dell'informativa sulla privacy | [https://www.cloverpop.com/privacy-policy/](https://www.cloverpop.com/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://www.cloverpop.com/terms-of-service](https://www.cloverpop.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Cloverpop su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegated | archiviare i dati utente come. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Quando gli utenti creano e interagiscono con le decisioni, questi dati vengono associati all'utente, al team e all'organizzazione che li ha creati. Dobbiamo anche visualizzare questa proprietà in un'esperienza utente facile da usare, quindi stiamo archiviando le informazioni di visualizzazione, ad esempio l'utente&#8217;avatar. | consente all'utente di accedere e consente all'app di accedere all'UPN per abilitare il&#8221; di accesso invisibile all'utente - posta elettronica, nome, oid, tid, givenName, surname, familyName, user avatar(photo), organization displayName | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |
>| openid | delegated | Archiviare i dati utente come. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Quando gli utenti creano e interagiscono con le decisioni, questi dati vengono associati all'utente, al team e all'organizzazione che li ha creati. Dobbiamo anche visualizzare questa proprietà in un'esperienza utente facile da usare, quindi stiamo archiviando le informazioni di visualizzazione, ad esempio l'utente&#8217;avatar. | Per implementare &#8220;accedere con Teams&#8221;'app Web. | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |
>| profilo | delegated | Archiviare i dati utente come. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Quando gli utenti creano e interagiscono con le decisioni, questi dati vengono associati all'utente, al team e all'organizzazione che li ha creati. Dobbiamo anche visualizzare questa proprietà in un'esperienza utente facile da usare, quindi stiamo archiviando le informazioni di visualizzazione, ad esempio l'utente&#8217;avatar. | Per implementare &#8220;accedere con Teams&#8221;'app Web. | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Microsoft accede ai dati del nome del primo/ultimo/nome visualizzato per visualizzare in modo accurato le azioni intraprese da utenti specifici relativi a una decisione. L'indirizzo di posta elettronica viene utilizzato come identificatore univoco per ogni utente nel database in quanto consente a ogni utente di appartenere a più organizzazioni. Accedono a questi dati solo quando interagiscono con la nostra app, ad esempio se rispondono a un sondaggio. | Vengono archiviati i dati del nome del primo/ultimo/nome visualizzato per visualizzare in modo accurato le azioni intraprese da utenti specifici relativi a una decisione.  L'indirizzo di posta elettronica viene archiviato perché viene utilizzato come identificatore univoco per ogni utente nel database in quanto consente a ogni utente di appartenere a più organizzazioni. Questi dati vengono archiviati solo quando interagiscono con la nostra app, ad esempio se rispondono a un sondaggio. I dati sulle decisioni devono essere un sistema di registrazione per le decisioni, quindi è importante archiviare i dati per identificare in che modo ogni utente coinvolto in una decisione ha contribuito a tale decisione. |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì.
L'ID del team viene visualizzato nei log quando l'app interagisce in un team.
Abbiamo accesso limitato ai log di produzione ai nostri tre fondatori che hanno tutti sede negli Stati Uniti.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>L'app Cloverpop è stata creata usando Ruby on Rails ed è ospitata sulla piattaforma Heroku PaaS (piattaforma come servizio) che utilizza AWS per la sua infrastruttura cloud. Heroku e AWS hanno entrambi report SOC accessibili. L'app usa PostgreSQL per l'archiviazione dei dati crittografati in pausa ed è un ambiente multi-tenant.
 
Per tutto il codice sono stati scritti test automatizzati che riguardano la sicurezza dell'accesso ai dati. Ogni build viene sottoposta a un rigoroso processo di revisione del codice per la sicurezza e a un processo di test qa manuale che include anche controlli per l'autenticazione degli utenti e l'accesso ai dati tramite azioni utente disponibili. Esiste una chiara separazione tra l'ambiente di produzione e tutti gli altri ambienti, ad esempio lo sviluppo e il testing.
 
Solo il personale selezionato ha accesso all'ambiente di produzione e al database: i fondatori dell'azienda e una piccola parte di dipendenti sottoposti a controlli in background e che hanno un'esigenza quantificata (ad esempio il supporto dei clienti).

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

