---
title: Application Information for atSpoke by Townsend Street Labs, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per atSpoke, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 14f44eb8a74cde9a7803e079e561f93f0391561b
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/06/2021
ms.locfileid: "52248064"
---
# <a name="atspoke"></a>atSpoke

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/dfaf15dc-4e94-4484-a25d-79358fe70d8b" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001454" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Townsend Street Labs, Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | atSpoke |
| ID | WA200001454 |
| Funzionalità | Bot |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Townsend Street Labs, Inc. |
| URL del sito Web del partner | [https://www.atspoke.com](https://www.atspoke.com) |
| URL dell'informativa sulla privacy | [https://www.atspoke.com/privacy-policy/](https://www.atspoke.com/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://www.atspoke.com/terms-of-service](https://www.atspoke.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Townsend Street Labs, Inc. Sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | delegated | atSpoke archivia l'ID gruppo Microsoft | Consente di leggere e scrivere informazioni di gruppo tra atSpoke e Microsoft Teams.  | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| User.ReadWrite.All | delegated | atSpoke archivia la posta elettronica e l'ID utente dell'utente | Consente di leggere e scrivere informazioni utente tra atSpoke e Microsoft Teams. | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| offline_access | delegated | atSpoke non archivia dati per questo. | Viene usato per la sincronizzazione in background. | dfaf15dc-4e94-4484-a25d-79358fe70d8b |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutte le informazioni non servizi Microsoft OII vengono trasferite a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento di OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Sì, usiamo servizi di terze parti per l'efficienza operativa. Google, Inc.: dati archiviati in volumi logici, backup di archiviazione in una rete Google Cloud nativa, registri di servizi e API o registri applicazioni. Gli eventi transazionali registrati possono contenere identificatori utente, informazioni di contatto e contenuto del cliente. MongoDB, Inc.: dati archiviati in raccolte di database basate su cloud. - Contenuto del cliente che include le richieste inviate dagli utenti, le risposte alle richieste aggiunte dagli utenti e gli articoli della Knowledge Base aggiunti dagli utenti. - Identificatori utente (nome, posta elettronica, avatar e numero di telefono utilizzati per creare un account utente Spoke). Mailgun Technologies, Inc.: Identificatore utente e informazioni di contatto per inviare comunicazioni di posta elettronica (ad esempio nome e posta elettronica). Twilio, Inc.: Numero di telefono dell'utente e contenuto del cliente: contenuto scambiato mediante l'utilizzo dei servizi di Twilio&#8217;, ad esempio testo, corpo dei messaggi, contenuti multimediali vocali e video, immagini e audio. Mixpanel, Inc.: I dati personali trasferiti includono nome, posta elettronica, indirizzo IP e dati personali inclusi nel contenuto del messaggio. Cloudinary, Inc.: contenuto dei clienti basato su file inviato dagli utenti finali. Elasticsearch, Inc.: gli eventi transazionali dell'applicazione registrati possono contenere testo troncato dal contenuto del cliente. Stitch, Inc.: Informazioni di contatto, informazioni sull'utilizzo, identificatori non tradizionali degli utenti autorizzati del sottoscrittore e qualsiasi altro dato personale che il Sottoscrittore o gli utenti autorizzati inviano alla piattaforma. Mode Analytics, Inc.: informazioni sugli identificatori utente per fornire analisi per utente. DataDog: gli eventi transazionali dell'applicazione registrati possono contenere testo troncato dal contenuto del cliente; la conservazione dei log è di 14 giorni. Fullstory, Inc.: registrazioni delle azioni eseguite nell'interfaccia utente Web; include l'account utente di Spoke per l'identificazione. |  | Stiamo usando l'API REST di Bot Framework. Usiamo questa API per inviare e ricevere messaggi al servizio bot askSpoke. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Consente a atSpoke di sincronizzare gli utenti da Microsoft Teams creare utenti e definire le autorizzazioni. | atSpoke archivia solo la posta elettronica Microsoft Teams gli utenti possono accedere a atSpoke come utente valido. |  |



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nei registri dell'applicazione sono contenuti il nome e il cognome dell'utente, l'indirizzo di posta elettronica dell'utente e l'ID oggetto assegnato ad Azure per utenti e gruppi. I log vengono conservati solo per 14 giorni, a quel punto scadono automaticamente. L'accesso ai log è protetto da manomissioni e solo determinati membri del personale hanno accesso per visualizzare i registri.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati dell'applicazione vengono archiviati in un'istanza gestita di MongoDB. L'accesso al servizio gestito Atlas MongoDB Database viene eseguito tramite un processo di richiesta di accesso utente standardizzato che richiede l'approvazione. Le revisioni periodiche dell'accesso utente vengono eseguite con l'accesso alla gestione. Microsoft limita il numero di membri del personale con accesso ai dati sensibili dei clienti e non consente di modificare direttamente i dati di alcun computer.&#8232; L'accesso remoto a questo database richiede l'autenticazione a più fattori. Il database e tutti i backup vengono crittografati in fase di ripristino utilizzando la crittografia AES-256 bit.


#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

