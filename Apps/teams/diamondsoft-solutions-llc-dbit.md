---
title: Informazioni sulle applicazioni per DBit di Diamondsoft Solutions, LLC
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per DBit, i relativi criteri di gestione dei dati, le informazioni sul catalogo Microsoft Cloud App Security app e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 23995f613c3c3b6d7b2ab7d161f8710ccddf07d0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553957"
---
# <a name="dbit"></a>DBit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 23 giugno 2020</p>

* <a href="https://teams.microsoft.com/l/app/b28bb657-8edd-47ae-a912-c5fc11b3e89e" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001536" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Diamondsoft Solutions, LLC a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | DBit |
| ID | WA200001536 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Diamondsoft Solutions, LLC |
| URL del sito Web partner | [https://www.dbit.io/index.html](https://www.dbit.io/index.html) |
| URL dell'Informativa sulla privacy | [https://www.dbit.io/privacypolicy.html](https://www.dbit.io/privacypolicy.html) |
| URL delle Condizioni d'uso | [https://www.dbit.io/termsofuse.html](https://www.dbit.io/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Diamondsoft Solutions, LLC su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che la tua organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegato | Non memorizzamo le Graph nel nostro sistema o database. | Accedere e leggere il profilo utente | 1533d702-7604-463a-9fa3-63077c425e76 |
>| e-mail | delegato | Non memorizzamo le Graph nel nostro sistema o database. | Visualizzare l'indirizzo di posta elettronica degli utenti | 1533d702-7604-463a-9fa3-63077c425e76 |
>| offline_access | delegato | Non memorizzamo le Graph nel nostro sistema o database. | Mantenimento dell'accesso ai dati a cui è stato concesso l'accesso | 1533d702-7604-463a-9fa3-63077c425e76 |
>| openid | delegato | Non memorizzamo le Graph nel nostro sistema o database. | Accedere agli utenti | 1533d702-7604-463a-9fa3-63077c425e76 |
>| profilo | delegato | Non memorizzamo le Graph nel nostro sistema o database. | Visualizzare il profilo di base degli utenti | 1533d702-7604-463a-9fa3-63077c425e76 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Per creare un messaggio di benvenuto | Non memorizzamo le informazioni sul roster nel nostro sistema o database. |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Non raccogliamo queste informazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Usiamo Azure Cache Redis, la durata massima dei dati nella cache è di 300 minuti. Gli elementi di dati della cache vengono crittografati con AES256. Solo il servizio dell'app può connettersi a Azure Cache Redis tramite SSL, la stringa di connessione viene archiviata in Azure Environmental Variable.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35912' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35912" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

