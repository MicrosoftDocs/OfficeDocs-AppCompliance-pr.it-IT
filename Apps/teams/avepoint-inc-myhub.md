---
title: Application Information for MyHub by AvePoint, inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/21/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni di sicurezza e conformità disponibili per MyHub, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ccf5367ea692731bafcdc03d04ab4dad2e76c976
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553387"
---
# <a name="myhub"></a>MyHub

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: December 21, 2020</p>

* <a href="https://teams.microsoft.com/l/app/c3ff6344-f6f0-4bfa-8697-b9d47b32ca4b" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000726" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da AvePoint, inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | MyHub |
| ID | WA200000726 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | AvePoint, inc. |
| URL del sito Web del partner | [https://www.avepoint.com](https://www.avepoint.com) |
| URL dell'informativa sulla privacy | [https://www.avepoint.com/company/privacy-policy](https://www.avepoint.com/company/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://www.avepoint.com/company/terms-and-conditions/](https://www.avepoint.com/company/terms-and-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da AvePoint, inc. Sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | entrambi | i dati di configurazione dell'applicazione vengono archiviati da un punto di vista della gestione dei dati | Leggere i dati della directory | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Group.ReadWrite.All | entrambi | i dati di configurazione dell'applicazione vengono archiviati da un punto di vista della gestione dei dati | Lettura e scrittura di tutti i gruppi | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Mail.Send | delegated | i dati di configurazione dell'applicazione vengono archiviati da un punto di vista della gestione dei dati | Inviare posta come utente | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Reports.Read.All | application | i dati di configurazione dell'applicazione vengono archiviati da un punto di vista della gestione dei dati | Leggere tutti i report di utilizzo | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.FullControl.All | application | i dati di configurazione dell'applicazione vengono archiviati da un punto di vista della gestione dei dati | Avere il controllo completo di tutte le raccolte siti | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.Read.All | application | i dati di configurazione dell'applicazione vengono archiviati da un punto di vista della gestione dei dati | Leggere gli elementi in tutte le raccolte siti  | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.ReadWrite.All | delegated | i dati di configurazione dell'applicazione vengono archiviati da un punto di vista della gestione dei dati | Modificare o eliminare elementi in tutte le raccolte siti | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| User.Read.All | entrambi | i dati di configurazione dell'applicazione vengono archiviati da un punto di vista della gestione dei dati | Leggere tutti gli utenti&#8217; profili completi | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì, la posta elettronica e l'ID tenant dell'utente verranno visualizzati nei log. I log vengono archiviati in una posizione protetta e solo il personale autorizzato può accedere durante la risoluzione dei problemi. I log verranno archiviati dopo 60 giorni per scopi di controllo della sicurezza e verranno eliminati dopo un anno.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati dell'applicazione vengono archiviati in database SQL di Azure e Archiviazione di Azure. La SQL e Archiviazione di Azure azure sono abilitate.
Solo gli amministratori autorizzati possono accedere ai dati. L'autenticazione a più fattori è necessaria per l'accesso degli amministratori. Le operazioni vengono verificate. L'elenco indirizzi IP viene utilizzato anche per limitare l'accesso ai dati.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35843' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35843" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

