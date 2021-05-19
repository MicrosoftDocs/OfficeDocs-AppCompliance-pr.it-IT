---
title: Informazioni sull'applicazione per i progetti Zoho di Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Zoho Projects, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6e447efd8259b94dbc41eed731912a2288600a5f
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552687"
---
# <a name="zoho-projects"></a>Zoho Projects

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 16 dicembre 2019</p>

* <a href="https://teams.microsoft.com/l/app/4a39aea9-8537-4c2f-b66d-ca364eb3b80d" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381668" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Zoho Corporation Private Limited a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Zoho Projects |
| ID | WA104381668 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Zoho Corporation Private Limited |
| URL del sito Web partner | [https://www.zoho.com/projects/](https://www.zoho.com/projects/) |
| URL della pagina Teams informazioni sull'applicazione | [https://www.zoho.com/projects/help/microsoft-teams-integrat...](https://www.zoho.com/projects/help/microsoft-teams-integration.html) |
| URL dell'Informativa sulla privacy | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL delle Condizioni d'uso | [https://www.zoho.com/terms.html](https://www.zoho.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Zoho Corporation Private Limited su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegato |  | Avere pieno accesso ai calendari degli utenti. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| Files.Read | delegato |  | Leggi tutti i file. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| Files.Read.All | delegato |  | Leggere tutti i file a cui l'utente può accedere. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| Files.Read.Selected | delegato |  | Leggere i file selezionati dall'utente. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| Attività.Lettura | delegato |  | Leggere le attività degli utenti. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| Tasks.ReadWrite | delegato |  | Creare, leggere, aggiornare ed eliminare attività e progetti utente. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| Tasks.ReadWrite.Shared | delegato |  | Leggere e scrivere attività utente e condivise. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| User.Read | delegato |  | Accedere e leggere il profilo utente. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| User.ReadBasic.All | delegato |  | Leggi tutti i profili di base di tutti gli utenti. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |
>| offline_access | delegato |  | Mantenere l'accesso ai dati a cui gli è stato concesso l'accesso. | 621d9ae7-c14e-4fab-9604-63e1ffc9e721 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>Non è possibile accedere all'I EUII.


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Le informazioni sensibili come quanto sopra vengono rilevate tramite strumenti e archiviate come bug. Questi vengono risolti e corretti per gli aggiornamenti riusciti.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Le informazioni sui partner non vengono archiviate.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22961' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22961" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

