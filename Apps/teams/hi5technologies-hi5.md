---
title: Informazioni sull'applicazione per Hi5 di Hi5Technologies
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Hi5, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 983f86210f224bc492f54a7ab65192dee5b4ad6c
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552117"
---
# <a name="hi5"></a>Hi5

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 3 novembre 2020</p>

* <a href="https://teams.microsoft.com/l/app/ca334a56-72b5-4613-81d4-77b1148df03c" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001610" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Hi5Technologies a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Hi5 |
| ID | WA200001610 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Hi5Technologies |
| URL del sito Web partner | [https://www.get5.io/](https://www.get5.io/) |
| URL dell'Informativa sulla privacy | [https://www.get5.io/privacy](https://www.get5.io/privacy) |
| URL delle Condizioni d'uso | [https://www.get5.io/terms](https://www.get5.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Hi5Technologies su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegato | Archiviamo le informazioni sulla sessione degli utenti Teams e l'utente deve approvarle aggiungendo notifiche (possono rimuoverle in qualsiasi momento). Non vengono memorizzate altre informazioni. | Necessario per l'accesso e l'autenticazione SSO sul nostro server | 7cb50e3e-0427-409E-90D2-638EB28217C3 |
>| e-mail | delegato | Archiviamo le informazioni sulla sessione degli utenti Teams e l'utente deve approvarle aggiungendo notifiche (possono rimuoverle in qualsiasi momento). Non vengono memorizzate altre informazioni. | Necessario per l'accesso e l'autenticazione SSO sul nostro server | 7cb50e3e-0427-409E-90D2-638EB28217C3 |
>| offline_access | delegato | Archiviamo le informazioni sulla sessione degli utenti Teams e l'utente deve approvarle aggiungendo notifiche (possono rimuoverle in qualsiasi momento). Non vengono memorizzate altre informazioni. | Sostiene che l'utente sta vedendo le informazioni corrette e possiamo inviare le informazioni corrette ad altri che partecipano alla stessa azienda / area di lavoro. | 7cb50e3e-0427-409E-90D2-638EB28217C3 |
>| openid | delegato | Archiviamo le informazioni sulla sessione degli utenti Teams e l'utente deve approvarle aggiungendo notifiche (possono rimuoverle in qualsiasi momento). Non vengono memorizzate altre informazioni. | Necessario per l'accesso e l'autenticazione SSO sul nostro server | 7cb50e3e-0427-409E-90D2-638EB28217C3 |
>| profilo | delegato | Archiviamo le informazioni sulla sessione degli utenti Teams e l'utente deve approvarle aggiungendo notifiche (possono rimuoverle in qualsiasi momento). Non vengono memorizzate altre informazioni. | Necessario per l'accesso e l'autenticazione SSO sul nostro server | 7cb50e3e-0427-409E-90D2-638EB28217C3 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Per informare l'utente in un canale che gli è stato assegnato un Hi5 | Nessuna informazione è memorizzata, l'utente sarà solo @ dalla carta rispedita nel canale |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>No, Hi5 è semplicemente iFramed in e tutti i dati vengono archiviati in modo sicuro.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Stiamo utilizzando OAuth e forniamo 3 opzioni di accesso:
- Googles SSO (OAuth).
- Microsoft SSO (OAuth).
- La nostra crittografia che è una combinazione di crittografia SHA e AES.
Una volta autenticato e connesso, il tuo livello di autorizzazione ti consente di accedere alle sezioni autorizzate all'interno della piattaforma Hi5.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

