---
title: Informazioni sull'applicazione per Soapbox di Soapbox
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per Soapbox, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6e2b43df38aac6307c36c4a2cc8d00fe1c3fb629
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552777"
---
# <a name="soapbox"></a>Soapbox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/b49e7913-3b3f-4125-adde-2b698fc12c8b" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381501" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Soapbox a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Soapbox |
| ID | WA104381501 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Soapbox |
| URL del sito Web del partner | [https://soapboxhq.com](https://soapboxhq.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://msteams.services.soapboxhq.com/faqs](https://msteams.services.soapboxhq.com/faqs) |
| URL dell'informativa sulla privacy | [https://soapboxhq.com/privacy-policy/microsoft-teams](https://soapboxhq.com/privacy-policy/microsoft-teams) |
| URL delle Condizioni per l'utilizzo | [https://soapboxhq.com/terms-of-service](https://soapboxhq.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Soapbox su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegated | Token di sincronizzazione. | L'accesso al calendario è necessario per sincronizzare le riunioni SoapBox con gli eventi del calendario |  |
>| User.Read | delegated | Nome, e-mail, ID utente Microsoft. | Il nome e la posta elettronica vengono utilizzati per creare utenti SoapBox. |  |
>| offline_access | delegated |  | L'accesso offline ai calendari è necessario per rendere le notifiche SoapBox rilevanti per gli eventi del calendario sincronizzati. |  |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| L'app accede a Team Roster e Chat Roster che usiamo per creare canali del team in SoapBox con i membri del team/chat | Nome, posta elettronica, ID utente Microsoft degli utenti per migliorare l'aspetto dell'app per gli utenti di Microsoft Teams e garantire che ogni utente possa impegnarsi completamente nel software per le riunioni. |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì. Name, Email and Microsoft User ID appear within our unified logging platform for a max of 30 days to assist in identifying issues and help users use the platform. Dopo 30 giorni, i dati vengono rimossi dai server di registrazione.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>L'infrastruttura principale è archiviata in AWS in una rete privata. Abbiamo anche i bot configurati in Heroku e Azure. L'accesso ai server è limitato con i requisiti chiave SSH. Tutte le richieste sono su SSL (TLS 1.3). Usiamo le richieste firmate per garantire che il traffico dai bot alla piattaforma sia sicuro. I dati vengono crittografati in pausa. Il personale delle operazioni di sviluppo richiede 2FA per accedere ai propri account

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35464' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35464" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

