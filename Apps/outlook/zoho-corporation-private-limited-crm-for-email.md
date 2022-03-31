---
title: Informazioni sull'applicazione per Zoho CRM per la posta elettronica di Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 09/04/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Zoho CRM per la posta elettronica, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6c2ef2b28f2e6bbd83d1dec270c695435f705ba4
ms.sourcegitcommit: b7ef94cf5fb12f6730a8688834ceee4f8fe8e0da
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/25/2022
ms.locfileid: "64462849"
---
# <a name="zoho-crm-for-email"></a>Zoho CRM per la posta elettronica

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379468" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Zoho Corporation Private Limited a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Zoho CRM per la posta elettronica |
| ID | WA104379468 |
| Office 365 client supportati | Outlook 2013 o versioni successive Windows, Outlook 2016 o versioni successive su Mac, Outlook sul web |
| Nome società partner | Zoho Corporation Private Limited |
| URL del sito Web del partner | [https://www.zoho.com/](https://www.zoho.com/) |
| URL dell'informativa sulla privacy | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL delle Condizioni per l'utilizzo | [https://www.zoho.com/crm/zohocrm-terms.html](https://www.zoho.com/crm/zohocrm-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Zoho Corporation Private Limited su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft necessarie](/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD ID app** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated | L'ID cartella calendario viene archiviato per sincronizzare i contatti da Zoho CRM a Microsoft &amp; viceversa. Le informazioni del calendario event_name, event_location, participant_details vengono archiviate. | Consente all'utente di sincronizzare gli eventi di Office365 con Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | delegated | L'ID cartella Contatti viene archiviato per sincronizzare i contatti da Zoho CRM a Microsoft &amp; viceversa. Le informazioni di contatto first_name, last_name,indirizzo di posta elettronica vengono archiviate. | Consente all'utente di sincronizzare i contatti di Office365 con Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | delegated |  | Consente all'utente di importare il file di Office365 in Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.All | delegated |  | Consente all'utente di importare il file di Office365 in Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | delegated | UserPrincipalName viene archiviato per l'identificazione dell'utente | Consente all'utente di importare il file di Office365 in Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | delegated | Proprietà utente come first_name, last_name, indirizzo di posta elettronica. | Leggere i profili di base di tutti gli utenti | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | delegated | UserPrincipaName viene archiviato per l'indentificazione dell'utente | Visualizzare l'indirizzo di posta elettronica dell'utente | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | delegated |  | Mantenimento dell'accesso ai dati a cui è stato concesso l'accesso | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profile | delegated |  | Visualizzare il profilo di base dell'utente | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Non raccogliamo informazioni personali/informazioni personali in telemetria e log. Sono disponibili script per la ricerca e l'avviso per la correzione di tali dati visibili

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Il cliente può selezionare i dati che devono essere crittografati tramite EAR (Encryption At Rest) con restrizioni certaat. Per impostazione predefinita, verrà eseguito l'hashing delle password. L'accesso logico ai server viene fornito tramite una rete &amp; dedicata isolata ed è altamente protetto e


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

