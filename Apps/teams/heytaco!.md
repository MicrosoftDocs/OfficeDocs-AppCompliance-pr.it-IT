---
title: Informazioni sull'applicazione per HeyTaco! di HeyTaco!
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
description: Tutte le informazioni sulla sicurezza e conformità disponibili per HeyTaco!, i criteri di gestione dei dati, le informazioni del catalogo app di Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 08b99f83abb4031719759544622437004b9aa56c
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095105"
---
# <a name="heytaco"></a>HeyTaco!

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/be8d11cf-265a-4974-9912-4ff28c29fc21" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001346" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da HeyTaco! a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | HeyTaco! |
| ID | WA200001346 |
| Funzionalità | Bot, scheda |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | HeyTaco! |
| URL del sito Web del partner | [https://www.heytaco.chat](https://www.heytaco.chat) |
| URL dell'informativa sulla privacy | [https://www.heytaco.chat/privacy](https://www.heytaco.chat/privacy) |
| URL delle Condizioni per l'utilizzo | [https://www.heytaco.chat/terms](https://www.heytaco.chat/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da HeyTaco! informazioni su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| e-mail | delegated | utilizzato per associare l'utente per i trasferimenti di dati da Slack a MS Teams | utilizzato per associare l'utente ai trasferimenti di dati da Slack a MS Team | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| openid | delegated | usato per accedere a HeyTaco! | usato per accedere a HeyTaco! | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| profilo | delegated | usato per acquisire il nome utente, l'immagine del profilo, lo scostamento del fuso orario, l'ID tenant e l'ID team | usato per acquisire nome utente, avatar, offset fuso orario, ID tenant e ID team | be8d11cf-265a-4974-9912-4ff28c29fc21 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Per indicare all'utente di aver ricevuto un taco e da chi è. | Indirizzo di posta elettronica (per i tacos di migrazione da una piattaforma a un'altra) Nome (per il saluto dell'utente) Immagine del profilo (da visualizzare nella classifica) Fuso orario (per mostrare correttamente i tacos dati nella pagina attività) ID tenant (Per l'aggregazione dei dati per tenant) ID team (Per l'aggregazione dei dati per team)  |  |



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>EUII e OII non sono connessi ad alcuna registrazione. Solo tipi di errore e tipi di azione.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>HeyTaco! i database e i backup dei dati sono ospitati in Amazon Web Services (AWS). 

Le operazioni del data center di Amazon sono state accreditate con ISO 27001, SOC 1 e SOC 2/SSAE 16/ISAE 3402 (in precedenza SAS 70 Type II), PCI Level 1, FISMA Moderate e Sarbanes-Oxley (SOX).

Quando invii informazioni tramite il nostro servizio, le tue informazioni vengono protette e crittografate sia in fase di riposo che in transito tramite connessioni sicure. Implementiamo una serie di misure di sicurezza per mantenere la sicurezza delle informazioni personali.

È in corso la gestione degli accessi con privilegi per proteggere i dati nei server.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

