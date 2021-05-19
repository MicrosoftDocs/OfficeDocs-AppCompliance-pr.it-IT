---
title: Informazioni sull'applicazione per atSpoke di Townsend Street Labs, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per atSpoke, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9a159ce3ac976eb1916cd94b3eb1cf002f8e13c1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551196"
---
# <a name="atspoke"></a>atSpoke

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 3 giugno 2020</p>

* <a href="https://teams.microsoft.com/l/app/dfaf15dc-4e94-4484-a25d-79358fe70d8b" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001454" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Townsend Street Labs, Inc.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | atSpoke |
| ID | WA200001454 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Townsend Street Labs, Inc. |
| URL del sito Web partner | [https://www.atspoke.com](https://www.atspoke.com) |
| URL dell'Informativa sulla privacy | [https://www.atspoke.com/privacy-policy/](https://www.atspoke.com/privacy-policy/) |
| URL delle Condizioni d'uso | [https://www.atspoke.com/terms-of-service](https://www.atspoke.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Townsend Street Labs, Inc.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | delegato | atSpoke archivia l'ID gruppo Microsoft | Consente di leggere e scrivere informazioni di gruppo tra atSpoke e Microsoft Teams.  | DFAF15DC-4E94-4484-A25D-79358Fe70D8B |
>| User.ReadWrite.All | delegato | atSpoke memorizza la posta elettronica e l'ID utente dell'utente | Consente di leggere e scrivere informazioni utente tra atSpoke e Microsoft Teams. | DFAF15DC-4E94-4484-A25D-79358Fe70D8B |
>| offline_access | delegato | atSpoke non memorizza alcun dato per questo. | Questo viene utilizzato per la sincronizzazione in background. | DFAF15DC-4E94-4484-A25D-79358Fe70D8B |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft non sono trasferiti** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Sì, utilizziamo servizi di terze parti per l'efficienza operativa. Google, Inc.: dati memorizzati su volumi logici, backup di archiviazione in rete Google Cloud nativa, registri di servizi e API o registri delle applicazioni. Gli eventi transazionali registrati possono contenere identificatori utente, informazioni di contatto e contenuto del cliente. MongoDB, Inc.: dati archiviati in raccolte di database basate su cloud. - Contenuto del cliente che include richieste archiviate dagli utenti, risposte alle richieste aggiunte dagli utenti e articoli della Knowledge Base aggiunti dagli utenti. - Identificatori utente (nome, e-mail, avatar e numero di telefono utilizzati per creare un account utente Spoke). Mailgun Technologies, Inc.: Identificatore utente e informazioni di contatto per inviare comunicazioni via e-mail (ad esempio nome ed e-mail). Twilio, Inc.: Numero di telefono dell'utente e contenuto del cliente: contenuti scambiati tramite l'utilizzo dei Servizi di Twilio&#8217;, come testo, corpi di messaggi, supporti vocali e video, immagini e audio. Mixpanel, Inc.: I dati personali trasferiti includono nome, e-mail, indirizzo IP e dati personali inclusi nel contenuto del messaggio. Cloudinary, Inc.: contenuto dei clienti basato su file inviato dagli utenti finali. Elasticsearch, Inc.: gli eventi transazionali dell'applicazione registrata possono contenere testo troncato dal contenuto del cliente. Stitch, Inc.: Informazioni di contatto, informazioni sull'utilizzo, identificatori non tradizionali degli utenti autorizzati dell'abbonato e qualsiasi altro dato personale che l'abbonato o i suoi utenti autorizzati inviano alla Piattaforma. Mode Analytics, Inc.: informazioni sugli identificatori utente per fornire analisi per utente. DataDog: gli eventi transazionali dell'applicazione registrati possono contenere testo troncato dal contenuto del cliente; la conservazione del registro è di 14 giorni. Fullstory, Inc.: Registrazioni delle azioni intraprese sulla nostra interfaccia utente web; include l'account utente di Spoke a scopo identificativo. |  | Stiamo usando l'API REST di Bot Framework. Utilizziamo questa API per inviare e ricevere messaggi al servizio bot askSpoke. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Consente ad atSpoke di sincronizzare gli utenti da Microsoft Teams creare utenti e definire le autorizzazioni. | atSpoke memorizza solo l'e-mail in Microsoft Teams gli utenti possono accedere ad atSpoke come utente valido. |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Nei registri dell'applicazione sono contenuti il nome e il cognome di un utente, l'indirizzo di posta elettronica dell'utente e l'ID oggetto assegnato ad Azure per utenti e gruppi. I registri vengono conservati solo per 14 giorni, a quel punto scadono automaticamente. L'accesso al registro è protetto dalla manomissione e solo alcuni membri del personale hanno accesso per visualizzare i registri.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>I dati dell'applicazione vengono archiviati in un'istanza MongoDB gestita. Il provisioning dell'accesso al database Atlas MongoDB del servizio gestito viene esedrato tramite un processo standardizzato di richiesta di accesso utente che richiede approvazioni. Le revisioni periodiche dell'accesso degli utenti vengono eseguite con la conclusione della gestione. Limitiamo il numero di dipendenti con accesso ai dati sensibili dei clienti e non permettiamo di modificare direttamente i dati di alcun computer.&#8232; L'accesso remoto a questo database richiede l'autenticazione a più fattori. Il database e tutti i backup vengono crittografati a riposo utilizzando la crittografia AES-256 bit.


#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

