---
title: Informazioni sull'applicazione per Sheetgo fornite da SHEETGO EUROPE SL
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Esaminare tutte le informazioni di sicurezza e conformità disponibili per Sheetgo, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 001ad5dcce2a95885420f8413bfbfe03562eb5b2
ms.sourcegitcommit: ef767e1079411056cb3ca86d6b29084e31b0ef1c
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/26/2022
ms.locfileid: "65690431"
---
# <a name="sheetgo-application-information"></a>Informazioni sull'applicazione Sheetgo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 3 novembre 2020</p>

* <a href="https://teams.microsoft.com/l/app/583de270-58d0-4f94-af06-bf971f82fd94" target="_blank">Visualizza in Teams store</a>
* <a href="https://appsource.microsoft.com/en-US/product/office/WA200002128?tab=Overview" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da SHEETGO EUROPE SL a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Sheetgo |
| ID | WA200002067 |
| client Office 365 supportati | Microsoft Teams |
| Nome della società partner | SHEETGO EUROPE SL |
| URL del sito Web del partner | [https://www.sheetgo.com/](https://www.sheetgo.com/) |
| URL dell'informativa sulla privacy | [https://www.sheetgo.com/legal/privacy/](https://www.sheetgo.com/legal/privacy/) |
| URL delle condizioni per l'utilizzo | [https://www.sheetgo.com/legal/terms/](https://www.sheetgo.com/legal/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da SHEETGO EUROPE SL su come questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elencare le [autorizzazioni di Microsoft Graph](/graph/permissions-reference) necessarie per questa app.

>Questa applicazione non usa Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con un servizio non Microsoft, elencare il servizio non Microsoft usato dall'app, i dati trasferiti e includere una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| MongoDB: Registrare i dati del sistema e degli utenti per funzionare, Google BigQuery: Registrare l'utilizzo dei log del sistema, Google Firestore: Un sistema che gestisce e orchestra lo stato dei microservizi, Stripe: Sistema di pagamento |  | Queste applicazioni non usano API Microsoft aggiuntive |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni identificabili dell'utente finale (EUII): il roster (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunto. Questa app usa questa funzionalità?

>Non è possibile accedere all'identità dell'identità dell'utente.


#### <a name="telemetry-data"></a>Dati di telemetria

Nei dati di telemetria o nei log dell'applicazione vengono visualizzate informazioni personali dell'organizzazione o informazioni personali dell'utente finale( EUII) ? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>I log/dati di telemetria includono l'indirizzo di posta elettronica dell'utente solo come informazioni identificabili per l'utente finale. Quando richiesto dall'utente, il team di supporto dell'applicazione esegue una routine automatica interna che sfoca gli indirizzi di posta elettronica tra i dati di telemetria/log e rende i dati utente non più identificabili.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio l'eliminazione, la conservazione, il controllo, l'archiviazione, i criteri degli utenti finali e così via.

>MongoDB: registrare i dati del sistema e degli utenti per funzionare con Google BigQuery: registrare l'utilizzo dei log di sistema Google Firestore: un sistema che gestisce e orchestra lo stato dei microservizi. Gli unici dati critici che questo servizio transita sono le credenziali utente, crittografate tramite AES256 Stripe: Sistema di pagamento.
 
Tutti i dati in transito usano HTTPS per connessioni sicure e tutti i dati sensibili vengono crittografati tramite AES256

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni aziendali

Gli esseri umani sono coinvolti nella revisione o nell'analisi di eventuali dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono riportate le informazioni del catalogo [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='informazioni Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

