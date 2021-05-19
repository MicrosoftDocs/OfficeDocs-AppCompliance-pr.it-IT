---
title: Informazioni sull'applicazione per il segnale dinamico tramite segnale dinamico
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Dynamic Signal, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0d3c59f6809bafe16eec2a1d709f40a980576b1b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552227"
---
# <a name="dynamic-signal"></a>Dynamic Signal

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 16 dicembre 2019</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Dynamic Signal a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Dynamic Signal |
| ID | WA200000102 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Dynamic Signal |
| URL del sito Web partner | [https://dynamicsignal.com](https://dynamicsignal.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| URL dell'Informativa sulla privacy | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| URL delle Condizioni d'uso | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Dynamic Signal su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegato | Dynamic Signal sincronizza l'utente da Azure AD alla sua piattaforma per consentire un'attivazione e una disattivazione semplificate degli utenti in tempo reale. I dati vengono archiviati all'interno di Dynamic Signal per consentire agli utenti di utilizzare tale applicazione durante la sincronizzazione. | Autorizzazioni di lettura di un utente specifico per sincronizzare gli utenti della piattaforma Dynamic Signal con Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| User.Read.All | delegato | Dynamic Signal sincronizza l'utente da Azure AD alla sua piattaforma per consentire un'attivazione e una disattivazione semplificate degli utenti in tempo reale. I dati vengono archiviati all'interno di Dynamic Signal per consentire agli utenti di utilizzare tale applicazione durante la sincronizzazione. | Autorizzazioni di lettura di un utente specifico per sincronizzare gli utenti della piattaforma Dynamic Signal con Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| offline_access | delegato | Dynamic Signal sincronizza l'utente da Azure AD alla sua piattaforma per consentire un'attivazione e una disattivazione semplificate degli utenti in tempo reale. I dati vengono archiviati all'interno di Dynamic Signal per consentire agli utenti di utilizzare tale applicazione durante la sincronizzazione. | Mantenere l'accesso ai gruppi e ai team del tenant. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| openid | delegato | Dynamic Signal sincronizza l'utente da Azure AD alla sua piattaforma per consentire un'attivazione e una disattivazione semplificate degli utenti in tempo reale. I dati vengono archiviati all'interno di Dynamic Signal per consentire agli utenti di utilizzare tale applicazione durante la sincronizzazione. | Autenticare gli utenti con l'applicazione Dynamic Signal. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| OpenID Accedere utilizzando openid directory.readwrite.all accesso al dominio e ai gruppi del tenant, aggiungere un'app a un team offline_access mantenere l'accesso ai gruppi e ai team del tenant | openid Consente l'autenticazione indipendente. directory.readwrite.all accesso al dominio e ai gruppi del tenant, aggiungere un'app a un team offline_access mantenere l'accesso ai gruppi e ai team del tenant Nota: l'applicazione di Dynamic Signal utilizza il bot teams per applicare gruppi e autorizzazioni creati all'interno di Dynamic Signal a Teams in modo che un utente attivo in Dynamic Signal abbia accesso agli stessi gruppi e utenti che all'interno di Teams. |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>L'app e la piattaforma Dynamic Signal utilizzano le informazioni degli utenti per facilitare l'integrazione con Microsoft Teams. Queste informazioni sono disponibili per gli utenti con autorizzazioni appropriate all'interno della piattaforma Dynamic Signal. Le informazioni rilevanti sono Nome, Nome visualizzato ed E-mail. Queste informazioni vengono memorizzate all'interno dei registri della piattaforma Dynamic Signal in conformità con i criteri della rispettiva organizzazione con la licenza Dynamic Signal.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>I dati PII raccolti durante la registrazione e memorizzati all'interno della piattaforma Dynamic Signal includono: Nome, Cognome, E-mail/Identificatore e tutti i campi personalizzati impostati dal marchio e/o dai partner dell'agenzia. Quando i membri utilizzano Facebook o Twitter utilizzando oAuth Registration, alcuni dei dati utente esposti vengono presentati alla piattaforma Dynamic Signal per pre-compilare i dati. Questi dati includono nome, posizione e foto. Gli utenti hanno il controllo su quali informazioni e dati vengono presentati agli utenti sulle pagine bio per la comunità. I membri possono scegliere di caricare foto personali o del marchio, collegare account / canali social e utilizzo / punti nel programma da presentare nella pagina bio.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

