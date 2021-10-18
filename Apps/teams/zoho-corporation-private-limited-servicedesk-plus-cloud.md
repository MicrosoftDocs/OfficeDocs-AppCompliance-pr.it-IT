---
title: Informazioni sull'applicazione per ServiceDesk Plus Cloud di Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 09/04/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per ServiceDesk Plus Cloud, i criteri di gestione dei dati, le informazioni del catalogo app di Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a58e7ab50729d9cfbc12b798a4b62c70b1546150
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60434410"
---
# <a name="servicedesk-plus-cloud"></a>ServiceDesk Plus Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/04fdcea1-3511-499c-966d-099d59aef45f" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000037" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Zoho Corporation Private Limited a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | ServiceDesk Plus Cloud |
| ID | WA200000037 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Zoho Corporation Private Limited |
| URL del sito Web del partner | [https://www.manageengine.com/products/service-desk](https://www.manageengine.com/products/service-desk) |
| URL della Teams info dell'applicazione | [https://help.sdpondemand.com/servicedeskplus_cloud_for_teams](https://help.sdpondemand.com/servicedeskplus_cloud_for_teams) |
| URL dell'informativa sulla privacy | [https://www.manageengine.com/privacy.html](https://www.manageengine.com/privacy.html) |
| URL delle Condizioni per l'utilizzo | [https://ondemand.manageengine.com/terms.html](https://ondemand.manageengine.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Zoho Corporation Private Limited su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | application |  |  | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| Files.Read | delegated |  |  | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| Files.Read.Selected | delegated |  |  | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| User.Read | delegated | ID di posta elettronica dell'utente. | Consente all'utente di accedere e consente all'app di accedere all'UPN per abilitare l'accesso invisibile all'utente. | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| User.Read.All | application |  |  | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| User.ReadBasic.All | delegated | EMAIL ID, Name, Employee ID, Job title, Telefono, Mobile, Site, Department, Locale, Profile photo of the user. | Consente di importare le informazioni di base degli utenti Azure Active Directory. | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| email | delegated | ID di posta elettronica dell'utente. | Visualizzare l'indirizzo di posta elettronica dell'utente. | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| offline_access | delegated |  | Mantenere l'accesso ai dati a cui gli è stato assegnato l'accesso. | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| profile | delegated |  | Visualizzare il profilo di base dell'utente. | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


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

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

