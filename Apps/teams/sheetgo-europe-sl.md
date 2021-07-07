---
title: Informazioni sull'applicazione per Sheetgo di SHEETGO EUROPE SL
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Sheetgo, i relativi criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 7061510a0fb54a3e46e9ca80032a93e97a0e5868
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281058"
---
# <a name="sheetgo"></a>Sheetgo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/583de270-58d0-4f94-af06-bf971f82fd94" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002067" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da SHEETGO EUROPE SL a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Sheetgo |
| ID | WA200002067 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | SHEETGO EUROPE SL |
| URL del sito Web del partner | [https://www.sheetgo.com/](https://www.sheetgo.com/) |
| URL dell'informativa sulla privacy | [https://www.sheetgo.com/legal/privacy/](https://www.sheetgo.com/legal/privacy/) |
| URL delle Condizioni per l'utilizzo | [https://www.sheetgo.com/legal/terms/](https://www.sheetgo.com/legal/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da SHEETGO EUROPE SL su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>Questa applicazione non utilizza Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutte le informazioni non servizi Microsoft OII vengono trasferite a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento di OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| MongoDB: Registrare i dati del sistema e degli utenti per funzionare, Google BigQuery: Registrare l'utilizzo dei registri di sistema, Google Firestore: Un sistema che gestisce e orchestra lo stato dei nostri microservizi, Stripe: Sistema di pagamento |  | Queste applicazioni non usano API Microsoft aggiuntive |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Telemetria/log include l'indirizzo di posta elettronica dell'utente solo come informazioni identificabili dall'utente finale. Quando richiesto dall'utente, il team di supporto dell'applicazione esegue una routine automatica interna che sfoca gli indirizzi di posta elettronica tra telemetria/log e rende i dati dell'utente non più identificabili.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>MongoDB: registrare i dati del sistema e degli utenti per funzionare Google BigQuery: registrare i registri di sistema di utilizzo di Google Firestore: un sistema che gestisce e orchestra lo stato dei nostri microservizi. L'unico dato critico che questo servizio transita è la credenziale dell'utente, che viene crittografata utilizzando il sistema AES256 Stripe: Payment.
 
Tutti i dati in transito utilizzano HTTPS per le connessioni protette e tutti i dati sensibili vengono crittografati tramite AES256

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

