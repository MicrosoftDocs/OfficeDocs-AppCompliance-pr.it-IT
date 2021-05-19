---
title: Informazioni sull'applicazione Studi.ly fornite da inLogic-Office Store
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Studi.ly, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 26a89739809e0d398db2a823bd714aa06a2d210d
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553057"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 24 agosto 2020</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da inLogic-Office Store a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Studi.ly |
| ID | WA200001668 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | inLogic-Office Store |
| URL del sito Web partner | [https://www.studi.ly](https://www.studi.ly) |
| URL dell'Informativa sulla privacy | [https://www.studi.ly/Studily_Privacy_Statement.pdf](https://www.studi.ly/Studily_Privacy_Statement.pdf) |
| URL delle Condizioni d'uso | [https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf](https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da inLogic-Office Store su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegato | Stiamo memorizzando lezioni, scuole e membri e termini informazioni dall'API educativa nella nostra API e ne abbiamo bisogno perché se lo otteniamo ogni volta dall'API grafico che fa funzionare lentamente la nostra applicazione. Lo sincronizziamo su un evento basato sul tempo, dall'API educativa al nostro database. |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.Read.All | delegato | Stiamo memorizzando lezioni, scuole e membri e termini informazioni dall'API educativa nella nostra API e ne abbiamo bisogno perché se lo otteniamo ogni volta dall'API grafico che fa funzionare lentamente la nostra applicazione. Lo sincronizziamo su un evento basato sul tempo, dall'API educativa al nostro database. | Scrivere directory nei gruppi per assegnazioni e materiali. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.ReadWrite.All | applicazione | Stiamo memorizzando lezioni, scuole e membri e termini informazioni dall'API educativa nella nostra API e ne abbiamo bisogno perché se lo otteniamo ogni volta dall'API grafico che fa funzionare lentamente la nostra applicazione. Lo sincronizziamo su un evento basato sul tempo, dall'API educativa al nostro database. | Scrivere directory nei gruppi per assegnazioni e materiali. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.Lettura.Tutti | applicazione | Stiamo memorizzando lezioni, scuole e membri e termini informazioni dall'API educativa nella nostra API e ne abbiamo bisogno perché se le otteniamo ogni volta dall'API grafico che fa funzionare lentamente la nostra applicazione. Lo sincronizziamo su un evento basato sul tempo, dall'API educativa al nostro database. | Leggi Lezioni di formazione, scuola, membri e termini.Ottieni tutte le classi e le scuole di un tenant per la sincronizzazione nel database delle app. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadBasic | delegato | Stiamo memorizzando lezioni, scuole e membri e termini informazioni dall'API educativa nella nostra API e ne abbiamo bisogno perché se lo otteniamo ogni volta dall'API grafico che fa funzionare lentamente la nostra applicazione. Lo sincronizziamo su un evento basato sul tempo, dall'API educativa al nostro database. | Leggi Lezioni di formazione, scuola, membri e termini.Ottieni tutte le classi e le scuole di un tenant per la sincronizzazione nel database delle app. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadWrite.All | applicazione | Stiamo memorizzando lezioni, scuole e membri e termini informazioni dall'API educativa nella nostra API e ne abbiamo bisogno perché se lo otteniamo ogni volta dall'API grafico che fa funzionare lentamente la nostra applicazione. Lo sincronizziamo su un evento basato sul tempo, dall'API educativa al nostro database. | Leggi Lezioni di formazione, scuola, membri e termini.Ottieni tutte le classi e le scuole di un tenant per la sincronizzazione nel database delle app. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Files.ReadWrite.All | delegato | Stiamo memorizzando lezioni, scuole e membri e termini informazioni dall'API educativa nella nostra API e ne abbiamo bisogno perché se lo otteniamo ogni volta dall'API grafico che fa funzionare lentamente la nostra applicazione. Lo sincronizziamo su un evento basato sul tempo, dall'API educativa al nostro database. | Leggi Scrivi file da un'unità | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.Read.All | delegato | Stiamo memorizzando lezioni, scuole e membri e termini informazioni dall'API educativa nella nostra API e ne abbiamo bisogno perché se lo otteniamo ogni volta dall'API grafico che fa funzionare lentamente la nostra applicazione. Lo sincronizziamo su un evento basato sul tempo, dall'API educativa al nostro database. | Questa autorizzazione ha consentito all'app di ottenere diversi eventi claender per gruppi del tenant.,subject,start,end,extensions | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.ReadWrite.All | ambedue | Stiamo memorizzando lezioni, scuole e membri e termini informazioni dall'API educativa nella nostra API e ne abbiamo bisogno perché se lo otteniamo ogni volta dall'API grafico che fa funzionare lentamente la nostra applicazione. Lo sincronizziamo su un evento basato sul tempo, dall'API educativa al nostro database. | Questa autorizzazione ha consentito all'app di ottenere diversi eventi claender per gruppi del tenant.,subject,start,end,extensions | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Member.Read.Hidden | applicazione |  |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Sites.ReadWrite.All | ambedue | Stiamo memorizzando lezioni, scuole e membri e termini informazioni dall'API educativa nella nostra API e ne abbiamo bisogno perché se lo otteniamo ogni volta dall'API grafico che fa funzionare lentamente la nostra applicazione. Lo sincronizziamo su un evento basato sul tempo, dall'API educativa al nostro database. | Leggi Scrivi file da un'unità | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.Read | delegato | Stiamo memorizzando lezioni, scuole e membri e termini informazioni dall'API educativa nella nostra API e ne abbiamo bisogno perché se lo otteniamo ogni volta dall'API grafico che fa funzionare lentamente la nostra applicazione. Lo sincronizziamo su un evento basato sul tempo, dall'API educativa al nostro database. | Lettura delle informazioni sull'utente | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.ReadBasic.All | delegato | Stiamo memorizzando lezioni, scuole e membri e termini informazioni dall'API educativa nella nostra API e ne abbiamo bisogno perché se lo otteniamo ogni volta dall'API grafico che fa funzionare lentamente la nostra applicazione. Lo sincronizziamo su un evento basato sul tempo, dall'API educativa al nostro database. | Lettura delle informazioni sull'utente | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>Non è possibile accedere all'I EUII.


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Tali dati non compaiono nei registri

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>È archiviato nel database di Azure cosmos e qualsiasi crittografia e archiviazione disponibile per impostazione predefinita con il database cosmos è applicabile a questa applicazione.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

