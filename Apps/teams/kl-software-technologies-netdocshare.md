---
title: Informazioni sull'applicazione per netDocShare di KL Software Technologies
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per netDocShare, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c8e050b7ecf4f4b4b3156e571d6afdcd75a6ceb2
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282775"
---
# <a name="netdocshare"></a>netDocShare

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/f1a2add5-d007-4062-a10a-60f4ea29fdbc" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001619" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da KL Software Technologies a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | netDocShare |
| ID | WA200001619 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | KL Software Technologies |
| URL del sito Web del partner | [https://www.klstinc.com](https://www.klstinc.com) |
| URL dell'informativa sulla privacy | [https://netdocshare.com/privacy-policy/](https://netdocshare.com/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://netdocshare.com/terms-of-use/](https://netdocshare.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da KL Software Technologies su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>Questa applicazione non utilizza Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì. Archiviamo EUII e OII in NoSQL Mongo DB personalizzato ospitato Microsoft Azure. Dopo che il client ha interrotto la sottoscrizione, queste informazioni verranno eliminate dal database precedente.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati dell'applicazione vengono archiviati in NoSQL Mongo DB ospitato Microsoft Azure. I dati vengono crittografati e solo due amministratori del tenant di Azure possono accedervi. 2FA è abilitato per tutti gli account amministratore ed entrambi gli account amministratore sono account utente aziendali di Azure AD

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalogo vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35898' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35898" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

