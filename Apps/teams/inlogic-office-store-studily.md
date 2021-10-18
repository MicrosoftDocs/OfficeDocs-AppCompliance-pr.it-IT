---
title: Informazioni sull'applicazione Studi.ly da inLogic-Office Store
ms.author: elmalova
author: elenamalova
ms.date: 06/18/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Studi.ly, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 478c078c5f74535ff8b0381aa4eac038fa29dab7
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430828"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2020</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da inLogic-Office Store a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Studi.ly |
| ID | WA200001668 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | inLogic-Office Store |
| URL del sito Web del partner | [https://www.inlogic.dk](https://www.inlogic.dk) |
| URL dell'informativa sulla privacy | [https://studi.ly/Studily_Privacy_Statement.pdf](https://studi.ly/Studily_Privacy_Statement.pdf) |
| URL delle Condizioni per l'utilizzo | [https://studi.ly/Studily_Terms_Of_Use_v1.pdf](https://studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da inLogic-Office Store su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated | Stiamo archiviando le informazioni relative a classi, scuole e membri e ai termini dell'api per l'istruzione nella nostra api e ne abbiamo bisogno perché se lo riceviamo ogni volta dall'api del grafico che rallenta il funzionamento dell'applicazione. Viene sincronizzato in base a un evento basato sull'ora dall'api education al database. |  | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Directory.Read.All | delegated | Stiamo archiviando le informazioni relative a classi, scuole e membri e ai termini dell'api per l'istruzione nella nostra api e ne abbiamo bisogno perché se lo riceviamo ogni volta dall'api del grafico che rallenta il funzionamento dell'applicazione. Viene sincronizzato in base a un evento basato sull'ora dall'api education al database. | Scrivi directory nei gruppi per le assegnazioni e i materiali. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Directory.ReadWrite.All | application | Stiamo archiviando le informazioni relative a classi, scuole e membri e ai termini dell'api per l'istruzione nella nostra api e ne abbiamo bisogno perché se lo riceviamo ogni volta dall'api del grafico che rallenta il funzionamento dell'applicazione. Viene sincronizzato in base a un evento basato sull'ora dall'api education al database. | Scrivi directory nei gruppi per le assegnazioni e i materiali. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.Read.All | application | Stiamo archiviando le informazioni relative a classi, scuole, membri e termini dell'api education nella nostra api e ne abbiamo bisogno perché se lo riceviamo ogni volta dall'api del grafico che rallenta il funzionamento dell'applicazione. Viene sincronizzato in base a un evento basato sull'ora dall'api education al database. | Leggere Education Classes, School, Members e Terms.Get all classes and schools of a tenant for synchronization into app database. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.ReadBasic | delegated | Stiamo archiviando le informazioni relative a classi, scuole e membri e ai termini dell'api per l'istruzione nella nostra api e ne abbiamo bisogno perché se lo riceviamo ogni volta dall'api del grafico che rallenta il funzionamento dell'applicazione. Viene sincronizzato in base a un evento basato sull'ora dall'api education al database. | Leggere Education Classes, School, Members e Terms.Get all classes and schools of a tenant for synchronization into app database. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.ReadWrite.All | application | Stiamo archiviando le informazioni relative a classi, scuole e membri e ai termini dell'api per l'istruzione nella nostra api e ne abbiamo bisogno perché se lo riceviamo ogni volta dall'api del grafico che rallenta il funzionamento dell'applicazione. Viene sincronizzato in base a un evento basato sull'ora dall'api education al database. | Leggere Education Classes, School, Members e Terms.Get all classes and schools of a tenant for synchronization into app database. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Files.ReadWrite.All | delegated | Stiamo archiviando le informazioni relative a classi, scuole e membri e ai termini dell'api per l'istruzione nella nostra api e ne abbiamo bisogno perché se lo riceviamo ogni volta dall'api del grafico che rallenta il funzionamento dell'applicazione. Viene sincronizzato in base a un evento basato sull'ora dall'api education al database. | ReadWrite Files from One Drive | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Group.Read.All | delegated | Stiamo archiviando le informazioni relative a classi, scuole e membri e ai termini dell'api per l'istruzione nella nostra api e ne abbiamo bisogno perché se lo riceviamo ogni volta dall'api del grafico che rallenta il funzionamento dell'applicazione. Viene sincronizzato in base a un evento basato sull'ora dall'api education al database. | Questa autorizzazione ha consentito all'app di ottenere eventi claender diversi per i gruppi del tenant.,subject,start,end,extensions | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Group.ReadWrite.All | entrambi | Stiamo archiviando le informazioni relative a classi, scuole e membri e ai termini dell'api per l'istruzione nella nostra api e ne abbiamo bisogno perché se lo riceviamo ogni volta dall'api del grafico che rallenta il funzionamento dell'applicazione. Viene sincronizzato in base a un evento basato sull'ora dall'api education al database. | Questa autorizzazione ha consentito all'app di ottenere eventi claender diversi per i gruppi del tenant.,subject,start,end,extensions | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Member.Read.Hidden | application |  |  | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Sites.ReadWrite.All | entrambi | Stiamo archiviando le informazioni relative a classi, scuole e membri e ai termini dell'api per l'istruzione nella nostra api e ne abbiamo bisogno perché se lo riceviamo ogni volta dall'api del grafico che rallenta il funzionamento dell'applicazione. Viene sincronizzato in base a un evento basato sull'ora dall'api education al database. | ReadWrite Files from One Drive | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| User.Read | delegated | Stiamo archiviando le informazioni relative a classi, scuole e membri e ai termini dell'api per l'istruzione nella nostra api e ne abbiamo bisogno perché se lo riceviamo ogni volta dall'api del grafico che rallenta il funzionamento dell'applicazione. Viene sincronizzato in base a un evento basato sull'ora dall'api education al database. | Lettura delle informazioni utente | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| User.ReadBasic.All | delegated | Stiamo archiviando le informazioni relative a classi, scuole e membri e ai termini dell'api per l'istruzione nella nostra api e ne abbiamo bisogno perché se lo riceviamo ogni volta dall'api del grafico che rallenta il funzionamento dell'applicazione. Viene sincronizzato in base a un evento basato sull'ora dall'api education al database. | Lettura delle informazioni utente | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Tali dati non vengono visualizzati nei registri

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>È archiviato nel database cosmo di Azure e qualsiasi crittografia e archiviazione disponibili per impostazione predefinita con il database cosmos è applicabile a questa applicazione.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

