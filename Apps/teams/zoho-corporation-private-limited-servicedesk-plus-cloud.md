---
title: Informazioni sulle applicazioni per ServiceDesk Plus Cloud di Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per ServiceDesk Plus Cloud, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 04797702995180e8a0a5305e88d49903eff80690
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550546"
---
# <a name="servicedesk-plus-cloud"></a>ServiceDesk Plus Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 16 dicembre 2019</p>

* <a href="https://teams.microsoft.com/l/app/04fdcea1-3511-499c-966d-099d59aef45f" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000037" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Zoho Corporation Private Limited a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | ServiceDesk Plus Cloud |
| ID | WA200000037 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Zoho Corporation Private Limited |
| URL del sito Web partner | [https://www.manageengine.com/products/service-desk](https://www.manageengine.com/products/service-desk) |
| URL della pagina Teams informazioni sull'applicazione | [https://help.sdpondemand.com/servicedeskplus_cloud_for_teams](https://help.sdpondemand.com/servicedeskplus_cloud_for_teams) |
| URL dell'Informativa sulla privacy | [https://www.manageengine.com/privacy.html](https://www.manageengine.com/privacy.html) |
| URL delle Condizioni d'uso | [https://ondemand.manageengine.com/terms.html](https://ondemand.manageengine.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Zoho Corporation Private Limited su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | applicazione |  |  | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| Files.Read | delegato |  |  | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| Files.Read.Selected | delegato |  |  | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| User.Read | delegato | ID e-mail dell'utente. | Consente all'utente di accedere e consente all'app di accedere al proprio UPN per abilitare l'accesso invisibile all'utente. | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| User.Read.All | applicazione |  |  | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| User.ReadBasic.All | delegato | ID e-mail, Nome, ID dipendente, Titolo professionale, Telefono, Cellulare, Sito, Reparto, Impostazioni locali, Foto profilo dell'utente. | Consente di importare le informazioni di base degli utenti da Azure Active Directory. | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| e-mail | delegato | ID e-mail dell'utente. | Visualizzare l'indirizzo di posta elettronica dell'utente. | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| offline_access | delegato |  | Mantenere l'accesso ai dati a cui gli è stato concesso l'accesso. | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| profilo | delegato |  | Visualizzare il profilo di base dell'utente. | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>Non è possibile accedere all'I EUII.


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Non raccogliamo EUII / PII in telemetria / registri. Abbiamo script in atto che cercano modelli e avvisano per risolverlo

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Tutti i dati sono crittografati su REST. Solo le persone autorizzate hanno accesso al sistema che è comunque protetto dall'accesso, completamente controllato per ogni tipo di accesso. Autenticazione a più fattori in atto per l'accesso, gli account autorizzati vengono gestiti in una directory aziendale e in un host


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

