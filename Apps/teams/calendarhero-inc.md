---
title: Informazioni sull'applicazione per CalendarHero di CalendarHero Inc
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per CalendarHero, i relativi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d27858000c591c320cfadc301ea16ddf2fac89bd
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553332"
---
# <a name="calendarhero"></a>CalendarHero

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 17 marzo 2020</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da CalendarHero Inc a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | CalendarHero |
| ID | WA200000150 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | CalendarHero Inc |
| URL del sito Web partner | [https://calendarhero.com](https://calendarhero.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| URL dell'Informativa sulla privacy | [https://calendarhero.com/privacy](https://calendarhero.com/privacy) |
| URL delle Condizioni d'uso | [https://calendarhero.com/terms-of-use](https://calendarhero.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da CalendarHero Inc su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | ambedue | Le riunioni vengono memorizzate nella cache nel mongoDB in Azure, ma le descrizioni vengono crittografate. | Accesso agli eventi del calendario dell'utente. |  |
>| Contatti.LetturaScrivi | ambedue | Nome dei contatti e indirizzo di posta elettronica. | Leggere i contatti dell'utente (in modo da poterli invitare a una riunione). |  |
>| Group.Read.All | ambedue | Nome e membri del gruppo. | (Facoltativo) leggere i gruppi di utenti aziendali (per la pianificazione con i gruppi). |  |
>| Mail.Read | ambedue | Contattare e-mail/nome, frequenza/recency delle interazioni. | (Facoltativo) viene utilizzato per leggere i metadati dell'e-mail a sotto chi sono i contatti più importanti dell'utente (tramite Machine Learning). |  |
>| MailboxSettings.ReadWrite | ambedue | Fuso orario dell'utente. | Fuso orario dell'utente. |  |
>| User.Read.All | ambedue | E-mail del nome &amp; dell'utente (archiviata come contatto). | (Facoltativo) leggere gli utenti aziendali (per la pianificazione con i colleghi) |  |
>| offline_access | applicazione | No | Dobbiamo leggere e scrivere attraverso il nostro back-end in qualsiasi momento, senza che l'utente sia presente. |  |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| importare nomi/e-mail di colleghi in modo che il bot assistente riunione possa pianificare riunioni con loro | nome &amp; e-mail. entrambi sono memorizzati nel nostro database per una rapida ricerca e per la ricerca parziale dei nomi (ad es. incontrare Joe P) |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>L'indirizzo e-mail di un utente e/o contatto viene utilizzato per registrare eventi a LogDNA, il nostro provider di registrazione.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Tutti i dati vengono archiviati nel data center cloud di MS Azure situato a Quebec City, in Canada. Diversi campi sono crittografati con AES256. L'accesso al database è disponibile solo per gli ingegneri e i nostri server back-end tramite credenziali a livello di utente/servizio.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

