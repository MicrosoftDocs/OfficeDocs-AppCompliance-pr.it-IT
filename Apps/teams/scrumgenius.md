---
title: Informazioni sull'applicazione per ScrumGenius di ScrumGenius
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per ScrumGenius, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: be8873fecd5dc50ab4db6def68c7c25f73e677fd
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59281160"
---
# <a name="scrumgenius"></a>ScrumGenius

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/14510476-fa9d-4dad-add9-aa5975a60a8b" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381097" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da ScrumGenius a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | ScrumGenius |
| ID | WA104381097 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | ScrumGenius |
| URL del sito Web del partner | [https://scrumgenius.com](https://scrumgenius.com) |
| URL dell'informativa sulla privacy | [https://scrumgenius.com/privacy/](https://scrumgenius.com/privacy/) |
| URL delle Condizioni per l'utilizzo | [https://scrumgenius.com/tos/](https://scrumgenius.com/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da ScrumGenius sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegated | Date di ferie impostate nel calendario dell'utente. | Per consentire agli utenti di sincronizzare le proprie ferie con ScrumGenius. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | delegated | Nome e indirizzo di posta elettronica dell'utente. | Per consentire all'utente di accedere con Microsoft Login. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Accedono all'elenco dei team, quindi quando un amministratore del team installa scrumgenius, possiamo sincronizzare il resto dell'elenco dei team con scrumgenius in modo da poter eseguire l'onboardboard con la piattaforma per consentire loro di configurare un report di supporto e assegnare i membri del team che dovrebbero ottenere il report. | nome, cognome, nome visualizzato, indirizzo di posta elettronica |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>No. L'utente viene connesso al nostro ID interno per i log.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Sì, i dati dell'applicazione sono crittografati in transito e in pausa. Solo l'app Web può accedere direttamente al database. L'accesso esterno è limitato e usiamo intervalli IP per proteggere l'accesso.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalogo vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35745' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35745" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

