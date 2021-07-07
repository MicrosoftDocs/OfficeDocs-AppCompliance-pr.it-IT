---
title: Informazioni sull'applicazione monday.com da monday.com
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e conformità disponibili per monday.com, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 1252ff537b354a1a8bc068e9c6ac6779c7af3fc4
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281218"
---
# <a name="mondaycom"></a>monday.com

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 28, 2020</p>

* <a href="https://teams.microsoft.com/l/app/eab2d3ce-6d6a-4415-abc4-5f40a8317b1f" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001798" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da monday.com a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | monday.com |
| ID | WA200001798 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | monday.com |
| URL del sito Web del partner | [https://monday.com/](https://monday.com/) |
| URL dell'informativa sulla privacy | [https://monday.com/terms/privacy](https://monday.com/terms/privacy) |
| URL delle Condizioni per l'utilizzo | [https://monday.com/terms/tos](https://monday.com/terms/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da monday.com su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>Questa applicazione non utilizza Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutte le informazioni non servizi Microsoft OII vengono trasferite a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento di OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| monday.com utilizza i sottoprocessori seguenti per le prestazioni del servizio:&#160;https://monday.com/terms/subprocessors |  | monday.com non usa LE API. Usiamo i seguenti framework Microsoft per le prestazioni del servizio (come descritto in precedenza nella risposta): &#8216;botbuilder&#8217; &#8216;botframework-connector&#8217; &#8216;@micorosft/teams-js&#8217; |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>monday.com i log delle applicazioni che contengono contenuto generato dagli utenti per un periodo di tempo limitato per consentire al personale R D di risolvere i bug e i problemi segnalati &amp; dagli utenti. I registri di sicurezza che contengono indirizzi IP vengono conservati per un periodo di tempo più lungo, in base ai criteri di conservazione dei dati.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>monday.com servizio è ospitato nell'infrastruttura AWS nella Virginia settentrionale in più aree di disponibilità, con un sito di ripristino di emergenza stabilito in un'area diversa. Alcuni dati di backup vengono archiviati in GCP (Stati Uniti, più aree). L'accesso al monday.com è controllato dagli amministratori dell'organizzazione utente e viene ottenuto utilizzando le funzionalità seguenti:
- Tipi di utenti
- Autorizzazioni a livello di account
- Aree di lavoro
- Tipi di schede
- Autorizzazioni a livello di scheda
- Le autorizzazioni a livello monday.com supportano i metodi di autenticazione seguenti:
- Credentials
- Google SSO (per Pro piano)
- Okta, OneLogin e SAML 2.0 personalizzato (per il piano Enterprise) 2FA tramite SMS o tramite un'app di autenticazione possono essere abilitati facoltativamente dagli amministratori dell'account tramite il pannello di amministrazione della piattaforma.
Tutti i dati in pausa vengono crittografati utilizzando AES-256. Tutti i dati in transito tra reti aperte vengono crittografati utilizzando TLS 1.3 (TLS 1.2 almeno).

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

