---
title: Informazioni sull'applicazione per Trivia di Springworks HR Tech
ms.author: elmalova
author: elenamalova
ms.date: 01/13/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Trivia, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: fbd1b9f5f308f3690a9d55a40993ba6122e8f81b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553847"
---
# <a name="trivia"></a>Trivia

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 13 gennaio 2021</p>

* <a href="https://teams.microsoft.com/l/app/391082c3-968b-47b1-9c92-b5daf008000b" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001956" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Springworks HR Tech a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Trivia |
| ID | WA200001956 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Springworks HR Tech |
| URL del sito Web partner | [https://springworks.in/](https://springworks.in/) |
| URL della pagina Teams informazioni sull'applicazione | [https://www.springworks.in/trivia](https://www.springworks.in/trivia) |
| URL dell'Informativa sulla privacy | [https://trivia.springworks.in/policy](https://trivia.springworks.in/policy) |
| URL delle Condizioni d'uso | [https://trivia.springworks.in/tnc](https://trivia.springworks.in/tnc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Springworks HR Tech su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | delegato | No | Per ottenere l'elenco Teams che l'utente fa parte | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| Team.ReadBasic.All | delegato | Sì, archiviare l'elenco dei team in cui è stato aggiunto il bot | Per raccogliere informazioni di base su tutti i team presenti in un'area di lavoro | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| User.Read.All | delegato | Sì, per archiviare aadObjectId univoco di un utente. Anche vari dettagli dell'utente come nome utente, e-mail, ecc. E visualizzarlo sulla dashboard di Trivia | Per ottenere i dettagli di tutti gli utenti presenti in un'area di lavoro | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| openid | delegato | Sì, per archiviare gli utenti che hanno e accedi all'app. |  Consentire sia all'utente di utilizzare l'App con il proprio account che all'App di utilizzare i dati dell'utente | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| profilo | delegato | Sì, per archiviare gli ID utente e i nomi degli host di quiz e altre funzionalità e identificarli in modo univoco | Per leggere le informazioni di base del profilo dell'utente come nome utente, e-mail | 43bc466a-7678-476f-b904-2d933c5bbfc3 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft non sono trasferiti** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| AWS, Mailchimp, Stripe.  | Nome del cliente, e-mail, IP, informazioni di pagamento | Utilizziamo queste terze parti per fornire la migliore esperienza del cliente ai nostri clienti |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Questi dati vengono utilizzati per visualizzare e memorizzare l'elenco dei partecipanti a un quiz e ad altre funzionalità di questo tipo | Nome, E-mail | Sì, memorizzando i dati dell'host e dei partecipanti di quiz e altre funzionalità per l'analisi e la comunicazione con l'host in caso di errori |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>OII: nome organizzazione, ID tenant visualizzato nei registri; EUII: l'ID oggetto aad, il nome completo, l'e-mail vengono visualizzati nei registri. abbiamo un post di periodo di conservazione di 30 giorni che i registri vengono eliminati automaticamente. 


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Dati archiviati in RDS, AWS. è criptato. L'accesso è solo a un DevOps ingegnere, direttore tecnico e fondatore

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Springworks HR Tech su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Ti integri con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
