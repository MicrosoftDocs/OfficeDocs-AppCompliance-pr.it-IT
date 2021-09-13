---
title: Informazioni sull'applicazione per Remind by 88 Ventures Limited
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Remind, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f39e0c35b88e3212743e30c7ab5ac40c74c708c3
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59280014"
---
# <a name="remind"></a>Remind

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 28, 2020</p>

* <a href="https://teams.microsoft.com/l/app/88546d4f-9973-4716-98e4-cd181c04bc2d" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001444" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da 88 Ventures Limited a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Remind |
| ID | WA200001444 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | 88 Ventures Limited |
| URL del sito Web del partner | [https://moonbearapp.com](https://moonbearapp.com) |
| URL dell'informativa sulla privacy | [https://teamsreminder.app/#privacy](https://teamsreminder.app/#privacy) |
| URL delle Condizioni per l'utilizzo | [https://teamsreminder.app/#terms](https://teamsreminder.app/#terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da 88 Ventures Limited sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegated | nessuna informazione archiviata nel database | consente all'amministratore di esplorare la directory degli utenti dell'organizzazione per gli utenti che hanno impostato promemoria pubblici | [88546d4f-9973-4716-98e4-cd181c04bc2d](https://docs.microsoft.com/microsoft-365-app-certification/azure/88546d4f-9973-4716-98e4-cd181c04bc2d) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| (1) Quando un utente imposta un promemoria su un messaggio, il bot tenta di ottenere il nome della persona che originariamente ha inviato il messaggio per visualizzare le informazioni nell'elenco dei promemoria dell'utente (2) Quando un utente imposta un promemoria per un altro canale o membro della chat, il bot tenta di ottenere l'identità (utente o bot) e il nome dell'utente menzionato per visualizzarlo nell'elenco dei promemoria dell'utente | (1) Quando un utente imposta un promemoria su un messaggio, il bot tenta di ottenere il nome della persona che originariamente ha inviato il messaggio per visualizzare le informazioni nell'elenco dei promemoria dell'utente (2) Quando un utente imposta un promemoria per un altro canale o membro della chat, il bot tenta di ottenere l'identità (utente o bot) e il nome dell'utente menzionato per visualizzarlo nell'elenco dei promemoria dell'utente |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun EEUI e OII è condiviso con la telemetria o la funzionalità di registrazione

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Crittografia in pausa, autenticazione a due fattori (2FA) per limitare l'accesso all'infrastruttura IT e ai dati dei clienti, intervalli IP protetti tra sistemi

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalogo vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

