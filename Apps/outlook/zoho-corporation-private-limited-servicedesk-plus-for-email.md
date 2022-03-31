---
title: Informazioni sull'applicazione per ServiceDesk Plus per la posta elettronica di Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 09/04/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per ServiceDesk Plus for Email, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f41cd7e3b578b3eea68a8d83c8bc8f39c64f2735
ms.sourcegitcommit: b7ef94cf5fb12f6730a8688834ceee4f8fe8e0da
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/25/2022
ms.locfileid: "64462129"
---
# <a name="servicedesk-plus-for-email"></a>ServiceDesk Plus per la posta elettronica

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381518" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Zoho Corporation Private Limited a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | ServiceDesk Plus per la posta elettronica |
| ID | WA104381518 |
| Office 365 client supportati | Outlook 2013 o versioni successive Windows, Outlook 2016 o versioni successive su Mac, Outlook sul web |
| Nome società partner | Zoho Corporation Private Limited |
| URL del sito Web del partner | [https://www.manageengine.com/products/service-desk](https://www.manageengine.com/products/service-desk) |
| URL dell'informativa sulla privacy | [https://www.manageengine.com/privacy.html](https://www.manageengine.com/privacy.html) |
| URL delle Condizioni per l'utilizzo | [https://ondemand.manageengine.com/terms.html](https://ondemand.manageengine.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Zoho Corporation Private Limited su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft necessarie](/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD ID app** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | application |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | delegated |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | delegated |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | delegated | ID di posta elettronica dell'utente. | Consente all'utente di accedere e consente all'app di accedere all'UPN per abilitare l'accesso invisibile all'utente. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | application |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | delegated | EMAIL ID, Name, Employee ID, Job title, Telefono, Mobile, Site, Department, Locale, Profile photo of the user. | Consente di importare le informazioni di base degli utenti Azure Active Directory. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | delegated | ID di posta elettronica dell'utente. | Visualizzare l'indirizzo di posta elettronica dell'utente. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | delegated |  | Mantenere l'accesso ai dati a cui gli è stato assegnato l'accesso. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profile | delegated |  | Visualizzare il profilo di base dell'utente. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Non raccogliamo informazioni personali/informazioni personali nella telemetria/log. Sono presenti script che ricercano modelli e avvisi per correggerlo

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Tutti i dati vengono crittografati in REST. Solo le persone autorizzate hanno accesso al sistema che è comunque protetto dall'accesso, completamente controllati per tutti i tipi di accesso. MFA sul posto per l'accesso, gli account autorizzati vengono mantenuti in una directory aziendale e in un host


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

