---
title: Informazioni sull'applicazione per MyHub di AvePoint, inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/21/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per MyHub, i relativi criteri di gestione dei dati, le informazioni sul catalogo Microsoft Cloud App Security delle app e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
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
<p>Ultimo aggiornamento da parte dello sviluppatore: 21 dicembre 2020</p>

* <a href="https://teams.microsoft.com/l/app/c3ff6344-f6f0-4bfa-8697-b9d47b32ca4b" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000726" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da AvePoint, inc.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | MyHub |
| ID | WA200000726 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | AvePoint, inc. |
| URL del sito Web partner | [https://www.avepoint.com](https://www.avepoint.com) |
| URL dell'Informativa sulla privacy | [https://www.avepoint.com/company/privacy-policy](https://www.avepoint.com/company/privacy-policy) |
| URL delle Condizioni d'uso | [https://www.avepoint.com/company/terms-and-conditions/](https://www.avepoint.com/company/terms-and-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da AvePoint, inc.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | ambedue | I dati di configurazione dell'applicazione vengono archiviati dal punto di vista della gestione dei dati | Leggere i dati della directory | 4d69a8E1-9C38-4B33-B76F-9D59B5AE051B |
>| Group.ReadWrite.All | ambedue | I dati di configurazione dell'applicazione vengono archiviati dal punto di vista della gestione dei dati | Leggere e scrivere tutti i gruppi | 4d69a8E1-9C38-4B33-B76F-9D59B5AE051B |
>| Mail.Invia | delegato | I dati di configurazione dell'applicazione vengono archiviati dal punto di vista della gestione dei dati | Inviare posta come utente | 4d69a8E1-9C38-4B33-B76F-9D59B5AE051B |
>| Reports.Read.All | applicazione | I dati di configurazione dell'applicazione vengono archiviati dal punto di vista della gestione dei dati | Leggere tutti i report sull'utilizzo | 4d69a8E1-9C38-4B33-B76F-9D59B5AE051B |
>| Sites.FullControl.All | applicazione | I dati di configurazione dell'applicazione vengono archiviati dal punto di vista della gestione dei dati | Avere il pieno controllo di tutte le raccolte siti | 4d69a8E1-9C38-4B33-B76F-9D59B5AE051B |
>| Sites.Read.All | applicazione | I dati di configurazione dell'applicazione vengono archiviati dal punto di vista della gestione dei dati | Leggere elementi in tutte le raccolte siti  | 4d69a8E1-9C38-4B33-B76F-9D59B5AE051B |
>| Sites.ReadWrite.All | delegato | I dati di configurazione dell'applicazione vengono archiviati dal punto di vista della gestione dei dati | Modificare o eliminare elementi in tutte le raccolte siti | 4d69a8E1-9C38-4B33-B76F-9D59B5AE051B |
>| User.Read.All | ambedue | I dati di configurazione dell'applicazione vengono archiviati dal punto di vista della gestione dei dati | Leggi tutti gli utenti&#8217; profili completi | 4d69a8E1-9C38-4B33-B76F-9D59B5AE051B |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>Non è possibile accedere all'I EUII.


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì, l'id e-mail e tenant dell'utente verrà visualizzato nei registri. I registri vengono archiviati in posizione protetta e solo il personale autorizzato può accedere durante la risoluzione dei problemi. I registri verranno archiviati dopo 60 giorni a scopo di controllo della sicurezza e verranno eliminati dopo un anno.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>I dati dell'Applicazione vengono archiviati in database SQL di Azure e Archiviazione di Azure. Azure SQL e Archiviazione di Azure crittografia sono abilitati.
Solo gli amministratori autorizzati possono accedere ai dati. L'autenticazione a più fattori è necessaria per l'accesso degli amministratori. Le operazioni sono controllate. La whitelist IP viene utilizzata anche per limitare l'accesso ai dati.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35843' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35843" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

