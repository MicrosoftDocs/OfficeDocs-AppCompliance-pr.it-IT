---
title: Informazioni sull'applicazione per Hi5 di Hi5Technologies
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Hi5, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
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
<p>Last updated by the developer on: November 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/ca334a56-72b5-4613-81d4-77b1148df03c" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001610" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Hi5Technologies a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Hi5 |
| ID | WA200001610 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Hi5Technologies |
| URL del sito Web del partner | [https://www.get5.io/](https://www.get5.io/) |
| URL dell'informativa sulla privacy | [https://www.get5.io/privacy](https://www.get5.io/privacy) |
| URL delle Condizioni per l'utilizzo | [https://www.get5.io/terms](https://www.get5.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Hi5Technologies sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegated | Vengono archiviate solo le informazioni sulla sessione degli utenti da Teams e l'utente deve approvarlo aggiungendo notifiche (possono rimuoverle in qualsiasi momento). Non vengono archiviate altre informazioni. | Obbligatorio per l'accesso SSO e l'autenticazione nel server | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| e-mail | delegated | Vengono archiviate solo le informazioni sulla sessione degli utenti da Teams e l'utente deve approvarlo aggiungendo notifiche (possono rimuoverle in qualsiasi momento). Non vengono archiviate altre informazioni. | Obbligatorio per l'accesso SSO e l'autenticazione nel server | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| offline_access | delegated | Vengono archiviate solo le informazioni sulla sessione degli utenti da Teams e l'utente deve approvarlo aggiungendo notifiche (possono rimuoverle in qualsiasi momento). Non vengono archiviate altre informazioni. | Mantiene che l'utente veda le informazioni corrette e che possiamo inviare le informazioni corrette ad altri utenti che aderiscono alla stessa società/area di lavoro. | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| openid | delegated | Vengono archiviate solo le informazioni sulla sessione degli utenti da Teams e l'utente deve approvarlo aggiungendo notifiche (possono rimuoverle in qualsiasi momento). Non vengono archiviate altre informazioni. | Obbligatorio per l'accesso SSO e l'autenticazione nel server | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| profilo | delegated | Vengono archiviate solo le informazioni sulla sessione degli utenti da Teams e l'utente deve approvarlo aggiungendo notifiche (possono rimuoverle in qualsiasi momento). Non vengono archiviate altre informazioni. | Obbligatorio per l'accesso SSO e l'autenticazione nel server | 7cb50e3e-0427-409e-90d2-638eb28217c3 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Per notificare all'utente in un canale che gli è stato assegnato un Hi5 | Non vengono archiviate informazioni, l'utente sarà @ solo dalla scheda inviata di nuovo nel canale |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>No, Hi5 è semplicemente iFramed in e tutti i dati vengono archiviati in modo sicuro.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Stiamo usando OAuth e forniamo 3 opzioni di accesso:
- Googles SSO (OAuth).
- Microsoft SSO (OAuth).
- La nostra crittografia, che è una combinazione di crittografia SHA e AES.
Dopo l'autenticazione e l'accesso, il livello di autorizzazione concede l'accesso alle sezioni autorizzate all'interno della piattaforma Hi5.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

