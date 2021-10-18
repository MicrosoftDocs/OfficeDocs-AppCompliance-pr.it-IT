---
title: Informazioni sull'applicazione per Arrangr di Arrangr, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Arrangr, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f4a5df023e906ad18e260debe09953351210d5bc
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60427868"
---
# <a name="arrangr"></a>Arrangr

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 15, 2021</p>

* <a href="https://teams.microsoft.com/l/app/57de46f8-193a-400c-9a34-c862333aed55" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002975" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Arrangr, Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Arrangr |
| ID | WA200002975 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Arrangr, Inc. |
| URL del sito Web del partner | [https://arrangr.com](https://arrangr.com) |
| URL della Teams info dell'applicazione | [https://arrangr.com/welcome](https://arrangr.com/welcome) |
| URL dell'informativa sulla privacy | [https://arrangr.com/privacy_policy](https://arrangr.com/privacy_policy) |
| URL delle Condizioni per l'utilizzo | [https://arrangr.com/terms_of_use](https://arrangr.com/terms_of_use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Arrangr, Inc. Su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated | Microsoft raccoglie i nomi dei calendari degli utenti e i dettagli relativi agli eventi del calendario per facilitare la pianificazione delle riunioni. | I nomi dei calendari connessi vengono archiviati in modo che possano visualizzare e modificare i calendari connessi. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Channel.ReadBasic.All | delegated | Raccogli l'elenco dei canali disponibili per l'utente, in modo che possiamo mostrargli un elenco dei canali in cui sceglierne uno in cui condividere un invito di Arrangr. | Le informazioni non vengono archiviate nei canali dell'utente | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ChannelMessage.Send | delegated | Questa autorizzazione viene utilizzata per inviare inviti di Arrangr nei canali del team per conto dell'utente. Non viene utilizzato per la raccolta di dati. | Non vengono archiviati dati raccolti con questa autorizzazione. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Chat.ReadWrite | delegated | Questa autorizzazione viene utilizzata per inviare inviti di Arrangr in Teams chat per conto dell'utente. Questa autorizzazione non viene utilizzata per raccogliere dati. | Non vengono archiviati dati raccolti con questa autorizzazione. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ChatMessage.Send | delegated | Questa autorizzazione viene utilizzata per inviare inviti di Arrangr in 1:1 e chat di gruppo per conto dell'utente. Non viene utilizzato per raccogliere dati. | Non vengono archiviati dati raccolti con questa autorizzazione. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| OnlineMeetings.ReadWrite | delegated | Arrangr raccoglie Microsoft Teams collegamenti alle riunioni nel processo di generazione con questa autorizzazione. Generiamo Teams riunioni per conto dell'utente in modo che possano organizzare Teams chiamate su Arrangr. | I collegamenti alle riunioni vengono archiviati in modo che possano essere condivisi con le parti appropriate per partecipare alla riunione. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| People.Read | delegated | Raccogliamo nomi e messaggi di posta elettronica di persone rilevanti per l'utente. In questo modo possiamo semplificare la selezione da parte dell'utente come destinatari degli inviti di Arrangr. | Se l'utente finisce per selezionare un destinatario offerto tramite questa API, salviamo il nome e la posta elettronica di tale destinatario per condurre la riunione e per semplificare la selezione di un destinatario in futuro. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Team.ReadBasic.All | delegated | Raccogliamo i nomi del Teams dell'utente, in modo che possano selezionare Teams che desiderano connettersi a Arrangr e in quale team vogliono condividere un invito di Arrangr. | Arrangr archivia i nomi di Teams che l'utente ha scelto di collegare a Arrangr, in modo da poter visualizzare questi Teams nelle loro impostazioni e consentire loro di scegliere tra quelle Teams quando decidono dove condividere un invito di Arrangr. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| TeamsAppInstallation.ReadWriteSelfForUser | delegated | Leggiamo se la nostra app è stata installata o meno nell'account Teams dell'utente, in modo che possiamo chiedere loro se vogliono installare la nostra app e in modo che possiamo installarla per loro. | I dati raccolti tramite questa autorizzazione non vengono archiviati. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| profile | delegated | Nome e indirizzo di posta elettronica | Nome e indirizzo di posta elettronica, per mostrare all'utente quale account ha connesso al servizio. | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook | Sì | Nome, posta elettronica, nomi di calendario, informazioni sull'evento del calendario | Queste informazioni vengono raccolte per consentire agli utenti di connettere il proprio calendario a Arrangr per facilitare la pianificazione delle riunioni | Nome, posta elettronica, nomi di calendario | Archiviamo queste informazioni in modo da mostrare agli utenti quali account e calendari hanno connesso al nostro servizio |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Cloud, SendGrid, Stripe, Quaderno | Google Cloud archivia tutti i dati utente, i nomi utente e i messaggi di posta elettronica vengono condivisi con SendGrid per inviare messaggi di posta elettronica agli utenti, rimuovere i nomi utente ricevuti, i messaggi di posta elettronica e le informazioni di pagamento per l'elaborazione dei pagamenti. Quaderno riceve nomi utente, messaggi di posta elettronica e informazioni geografiche per facilitare la conformità all'imposta sulle vendite. | Google Cloud è necessario per archiviare i dati per ricordare gli utenti e fornire le informazioni che hanno scelto di archiviare in Arrangr. Per inviare messaggi di posta elettronica ai nostri usi, dobbiamo fornire i loro indirizzi di posta elettronica a SendGrid. Per raccogliere i pagamenti, dobbiamo elaborare le informazioni di pagamento in Stripe, ma le informazioni di pagamento non vengono archiviate nei nostri server. Quaderno è necessario per calcolare l'imposta sulle vendite e garantire il rispetto delle normative fiscali. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Gli utenti utilizzeranno l'estensione di messaggistica per pianificare riunioni con altri utenti. Dobbiamo mostrare all'utente l'account a cui è connesso e dobbiamo essere in grado di associare l'invito inviato all'utente corretto di Arrangr. | Nomi utente, messaggi di posta elettronica e informazioni di comunicazione. | Queste informazioni sono necessarie per coordinare le riunioni tra più parti e condividere con i dettagli per la connessione e con chi stanno incontrando. |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Controlliamo i dati archiviati in Google Cloud Datastore tramite l'API e possiamo eliminare tutti i dati necessari. I nostri utenti possono richiedere la rimozione degli account e l'eliminazione dei dati.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Arrangr, Inc. Sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
