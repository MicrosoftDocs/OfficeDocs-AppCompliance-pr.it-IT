---
title: Informazioni sull'applicazione per HeyTaco! di HeyTaco!
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per HeyTaco!, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 66739977ba4aa3eef7456d4ec60530f94065a2b9
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553127"
---
# <a name="heytaco"></a>HeyTaco!

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 3 novembre 2020</p>

* <a href="https://teams.microsoft.com/l/app/be8d11cf-265a-4974-9912-4ff28c29fc21" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001346" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da HeyTaco! a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | HeyTaco! |
| ID | WA200001346 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | HeyTaco! |
| URL del sito Web partner | [https://www.heytaco.chat](https://www.heytaco.chat) |
| URL dell'Informativa sulla privacy | [https://www.heytaco.chat/privacy](https://www.heytaco.chat/privacy) |
| URL delle Condizioni d'uso | [https://www.heytaco.chat/terms](https://www.heytaco.chat/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da HeyTaco! su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| e-mail | delegato | utilizzato per abbinare l'utente per i trasferimenti di dati da Slack a MS Teams | utilizzato per abbinare l'utente per i trasferimenti di dati da Slack a MS Team | BE8D11CF-265A-4974-9912-4FF28C29FC21 |
>| openid | delegato | usato per firmare persona in HeyTaco! | usato per firmare persona in HeyTaco! | BE8D11CF-265A-4974-9912-4FF28C29FC21 |
>| profilo | delegato | utilizzato per acquisire nome utente, immagine del profilo, offset del fuso orario, ID tenant e ID team | utilizzato per acquisire nome utente, avatar, offset fuso orario, ID tenant e ID team | BE8D11CF-265A-4974-9912-4FF28C29FC21 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Per dire all'utente che hanno ricevuto un taco e da chi proviene. | Indirizzo di posta elettronica (per i tacos di migrazione da una piattaforma all'altra) Nome (per salutare l'utente) Immagine del profilo (per la visualizzazione in classifica) Fuso orario (per mostrare correttamente i tacos indicati nella pagina dell'attività) ID tenant (per aggregare i dati per tenant) ID team (per l'aggregazione dei dati per team)  |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>EUII e OII non sono connessi ad alcuna registrazione. Solo tipi di errore e tipi di azione.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>HeyTaco! i database e i backup dei dati sono ospitati su Amazon Web Services (AWS). 

Le operazioni del data center di Amazon sono state accreditate ai sensi di ISO 27001, SOC 1 e SOC 2/SSAE 16/ISAE 3402 (precedentemente SAS 70 Type II), PCI Level 1, FISMA Moderate e Sarbanes-Oxley (SOX).

Quando invii informazioni tramite il nostro servizio, le tue informazioni vengono protette e crittografate sia a riposo che in transito attraverso connessioni sicure. Implementiamo una varietà di misure di sicurezza per mantenere la sicurezza delle tue informazioni personali.

Disenziamo una gestione degli accessi privilegiati per proteggere i dati sui nostri server.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

