---
title: Application Information for Retro by Baltic Amadeus
ms.author: elmalova
author: elenamalova
ms.date: 10/07/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Retro, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 044866a2d32323ea0c63243aebcba429e165e224
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429994"
---
# <a name="retro"></a>Retro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Baltic Amadeus a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Retro |
| ID | WA200001892 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Baltic Amadeus |
| URL del sito Web del partner | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| URL dell'informativa sulla privacy | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| URL delle Condizioni per l'utilizzo | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Baltic Amadeus su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>Questa applicazione non utilizza Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| L'app Retro ha una propria API Web che non è considerata un servizio Microsoft. Come accennato in precedenza, archivia posta elettronica e nome completo per scopi di identificazione e visualizzazione del contenuto appropriati. Questi dati non vengono inviati altrove. Inoltre, Retro ha una funzionalità facoltativa per esportare i dati dello sprint nello spazio di confluenza di Atlante. A tale scopo, l'utente deve immettere il nome utente e la password di confluenza. Questi dati vengono utilizzati solo per effettuare richieste autenticate di api di confluenza per conto dell'utente e non vengono archiviati né registrati da nessuna parte. |  | Retro ha una propria API Web registrata anche in azure. Per poterlo usare, l'utente deve essere autenticato tramite Microsoft Identity Platform. L'utente deve essere autenticato in modo che l'app Retro possa server contenuto specifico dell'utente |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Il bot accede all'elenco per verificare quale membro è stato aggiunto o lasciato dal team. In base a questo, aggiunge o disattiva l'utente dal progetto in modo che l'utente non sia più visualizzato nell'elenco dei partecipanti allo sprint. | I messaggi di posta elettronica e FullName sono collegati tra loro e vengono archiviati nel database. La posta elettronica viene utilizzata per l'identificazione dell'utente per visualizzare il contenuto appropriato per l'utente connesso. FullName viene utilizzato per la visualizzazione di puprose, in modo che altri utenti possano sapere per chi stanno valutando o scrivendo feedback.  |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>No. L'unico processo che genera telemetria/log nell'app Retro è la registrazione degli errori. I log degli errori non includono alcuna unità EUII o OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati vengono archiviati nel database sql server di azure. Viene archiviato tramite l'app Retro e il bot Retro.
Per impostazione predefinita, nel database sql di azure è abilitata la crittografia dei dati trasparente.
Il database è bloccato dall'autenticazione di base.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

