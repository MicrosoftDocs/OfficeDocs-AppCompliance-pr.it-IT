---
title: Informazioni sull'applicazione per il segnale dinamico tramite segnale dinamico
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Dynamic Signal, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 19391d80121046303135b26da6714bb700bc7f73
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/06/2021
ms.locfileid: "52250734"
---
# <a name="dynamic-signal"></a>Dynamic Signal

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Segnale dinamico a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Dynamic Signal |
| ID | WA200000102 |
| Funzionalità | Bot, scheda |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Dynamic Signal |
| URL del sito Web del partner | [https://dynamicsignal.com](https://dynamicsignal.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| URL dell'informativa sulla privacy | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| URL delle Condizioni per l'utilizzo | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Dynamic Signal sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegated | Segnale dinamico sincronizza l'utente da Azure AD alla sua piattaforma per consentire l'attivazione e la disattivazione semplificate degli utenti in tempo reale. I dati vengono archiviati all'interno di Segnale dinamico per consentire agli utenti di utilizzare tale applicazione durante la sincronizzazione. | Autorizzazioni di lettura di un utente specifico per sincronizzare gli utenti della piattaforma segnale dinamico con Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| User.Read.All | delegated | Segnale dinamico sincronizza l'utente da Azure AD alla sua piattaforma per consentire l'attivazione e la disattivazione semplificate degli utenti in tempo reale. I dati vengono archiviati all'interno di Segnale dinamico per consentire agli utenti di utilizzare tale applicazione durante la sincronizzazione. | Autorizzazioni di lettura di un utente specifico per sincronizzare gli utenti della piattaforma segnale dinamico con Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| offline_access | delegated | Segnale dinamico sincronizza l'utente da Azure AD alla sua piattaforma per consentire l'attivazione e la disattivazione semplificate degli utenti in tempo reale. I dati vengono archiviati all'interno di Segnale dinamico per consentire agli utenti di utilizzare tale applicazione durante la sincronizzazione. | Mantenere l'accesso ai gruppi e ai team del tenant. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| openid | delegated | Segnale dinamico sincronizza l'utente da Azure AD alla sua piattaforma per consentire l'attivazione e la disattivazione semplificate degli utenti in tempo reale. I dati vengono archiviati all'interno di Segnale dinamico per consentire agli utenti di utilizzare tale applicazione durante la sincronizzazione. | Autenticare gli utenti con l'applicazione segnale dinamico. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| accedere openid con openid directory.readwrite.all accesso al dominio e ai gruppi del tenant, aggiungere un'app a un team offline_access mantenere l'accesso ai gruppi e ai team del tenant | openid Consenti l'autenticazione indipendente. directory.readwrite.all access to the tenant's domain and groups, add an app to a team offline_access retain access to the tenant's groups and teams Note: Dynamic Signal's application uses the teams bot to apply groups and permissions created within Dynamic Signal to Teams so that a user that is active in Dynamic Signal will have access to the same groups and users that within Teams. |  |



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>L'app segnale dinamico e la piattaforma utilizzano le informazioni utente per facilitare l'integrazione con Microsoft Teams. Queste informazioni sono disponibili per gli utenti con autorizzazioni appropriate all'interno della piattaforma Segnale dinamico. Le informazioni rilevanti sono Nome, Nome visualizzato e Posta elettronica. Queste informazioni vengono archiviate nei registri della piattaforma segnale dinamico in conformità ai criteri della rispettiva organizzazione con la licenza segnale dinamico.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati delle informazioni personali raccolti durante la registrazione e archiviati nella piattaforma Dynamic Signal includono: Nome, Cognome, E-mail/Identificatore e tutti i campi personalizzati impostati dal marchio e/o dai partner dell'agenzia. Quando i membri usano Facebook o Twitter usando la registrazione oAuth, alcuni dei dati degli utenti esposti vengono presentati alla piattaforma Segnale dinamico per precompilare i dati. Questi dati includono nome, posizione e foto. Gli utenti hanno il controllo sulle informazioni e sui dati presentati agli utenti nelle pagine bio della community. I membri possono acconsentire esplicitamente al caricamento delle foto personali o del marchio, alla connessione di account/canali di social network e all'utilizzo/punti nel programma da presentare nella pagina bio.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

