---
title: Informazioni sull'applicazione per Zoho Sprints di Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Zoho Sprints, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: fc19b083312c4c8222b894ae6bb35b0bbdd5314e
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552677"
---
# <a name="zoho-sprints"></a>Zoho Sprints

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 16 dicembre 2019</p>

* <a href="https://teams.microsoft.com/l/app/153059f1-912e-45d6-a13a-037675d66974" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000188" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Zoho Corporation Private Limited a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Zoho Sprints |
| ID | WA200000188 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Zoho Corporation Private Limited |
| URL del sito Web partner | [https://www.zoho.com/sprints/](https://www.zoho.com/sprints/) |
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
>| Calendars.ReadWrite | delegato | L'ID cartella alendar viene archiviato per sincronizzare i contatti da Zoho Sprints a Microsoft &amp; viceversa. |  | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| Contatti.LetturaScrivi | delegato | Id cartella contatti archiviato per sincronizzare i contatti. |  | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| Files.Read.All | delegato |  |  | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| Files.Read.Selected | delegato | UserPrincipalName è memorizzato per l'identificazione dell'utente. | Leggere i file selezionati dall'utente | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| User.Read | delegato |  | Accedere e leggere il profilo utente | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| User.ReadBasic.All | delegato |  | Consentire agli utenti di importare utenti di Office365 in Zoho Sprints. | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| e-mail | delegato |  |  | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |
>| offline_access | delegato |  | Mantenimento dell'accesso ai dati a cui è stato concesso l'accesso | F6d7187A-B437-4ECA-BBC5-C1331609FE07 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>Non è possibile accedere all'I EUII.


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

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35375' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35375" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

