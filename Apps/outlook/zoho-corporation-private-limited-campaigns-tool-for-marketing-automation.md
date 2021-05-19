---
title: Informazioni sulle applicazioni per lo strumento Zoho Campaigns per l'automazione del marketing di Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per lo strumento Zoho Campaigns per l'automazione del marketing, le sue politiche di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza / conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: e67de0ca2871d5432b5a29ead52194225bc51c9a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553687"
---
# <a name="zoho-campaigns-tool-for-marketing-automation"></a>Strumento Zoho Campaigns per l'automazione del marketing

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 16 dicembre 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380835" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Zoho Corporation Private Limited a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Strumento Zoho Campaigns per l'automazione del marketing |
| ID | WA104380835 |
| Office 365 client supportati | Outlook 2013 o versioni successive Windows, Outlook 2016 o versioni successive su Mac, Outlook sul Web |
| Nome della società partner | Zoho Corporation Private Limited |
| URL del sito Web partner | [https://www.zoho.com/](https://www.zoho.com/) |
| URL dell'Informativa sulla privacy | [https://zoho.com/privacy.html](https://zoho.com/privacy.html) |
| URL delle Condizioni d'uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Zoho Corporation Private Limited su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | delegato | L'ID calendario viene archiviato per creare eventi in quel calendario dalle campagne Zoho. | Consente all'utente di importare l'evento del calendario di Office365 in Zoho Campaigns. | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| Calendars.ReadWrite | delegato |  | Consente all'utente di aggiungere eventi campagne Zoho al calendario di Office365. | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| Contatti.Lettura | delegato |  Per salvare le informazioni di contatto. | Consente all'utente di importare contatti di Office365 in Zoho Campaigns. | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| Contatti.LetturaScrivi | delegato |  |  | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| User.Read | delegato |  |  | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| User.ReadBasic.All | delegato |  |  | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| e-mail | delegato | La posta elettronica viene archiviata per l'identificazione dell'utente. |  | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| offline_access | delegato |  |  | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| profilo | delegato |  |  | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Non raccogliamo EUII / PII in telemetria e registri. Abbiamo script in atto per cercare e avvisare per la correzione di tali dati visibili.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Il cliente può selezionare i dati che devono essere crittografati tramite EAR (Encryption At Rest) con restrizioni certaat. Le password verranno con hash per impostazione predefinita. L'accesso logico ai server è fornito attraverso una &amp; rete dedicata isolata ed è altamente protetto e


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28293' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28293" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

