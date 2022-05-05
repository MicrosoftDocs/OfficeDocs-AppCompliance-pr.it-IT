---
title: Informazioni sull'applicazione per researcHR di KBE&#26666;&#24335;&#20250;&#31038;
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per researcHR, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 66460d332f54b1868fbcd2895b6de088bb362d97
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/05/2022
ms.locfileid: "65229010"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 5 agosto 2021</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">Visualizza in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da KBE&#26666;&#24335;&#20250;&#31038; a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | researcHR |
| ID | WA200002557 |
| client Office 365 supportati | Microsoft Teams |
| Nome della società partner | KBE&#26666;&#24335;&#20250;&#31038; |
| URL del sito Web del partner | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| URL della pagina Teams informazioni sull'applicazione | [https://app.researchr.work](https://app.researchr.work) |
| URL dell'informativa sulla privacy | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| URL delle condizioni per l'utilizzo | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da KBE&#26666;&#24335;&#20250;&#31038; su come questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elencare le [autorizzazioni di Microsoft Graph](/graph/permissions-reference) necessarie per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **ID app Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | Applicazione | Questo ambito viene usato per consentire al bot di creare un nuovo canale nel client Teams. Vedere: /graph/api/channel-post | Questi dati non vengono archiviati nel database. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Directory.Read.All | Applicazione | Questo ambito viene usato per ottenere gli ID e i nomi dei canali per visualizzare questi dati nel sito Web. Vedere: /graph/api/channel-list | Questi dati non vengono archiviati nel database. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Group.Read.All | Applicazione | Questo ambito viene usato per ottenere gli ID e i nomi dei canali per visualizzare questi dati nel sito Web. Vedere: /graph/api/channel-list | Questi dati non vengono archiviati nel database. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Team.ReadBasic.All | Applicazione | Questo ambito viene usato per ottenere i membri del team in modo che gli utenti possano visualizzare i membri del team nel sito Web. Vedere: /graph/api/group-list-members | Questi dati non vengono archiviati nel database esterno. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.Read.All | Applicazione | Questo ambito viene usato per ottenere i canali aggiunti all'utente in modo che gli utenti possano visualizzare i team aggiunti nel sito Web. Vedere: /graph/api/user-list-jointeams | Questi dati non vengono archiviati nel database. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.ReadBasic.All | Delegato | Questo ambito viene usato per abilitare l'account di accesso OAuth e raccogliere l'ID AAD dell'utente, il token di accesso e il token di aggiornamento. Vedere: /graph/auth-v2-user | Archiviamo l'ID AAD dell'utente, il token di accesso e il token di aggiornamento nel database in modo che l'utente possa accedere al sito Web con OAuth. | [82df726e-0de2-46af-b4f1-0645fd95fc97].. /azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| offline_access | Delegato | Questo ambito viene usato per ottenere il token di aggiornamento in modo che sia possibile aggiornare il token di accesso degli utenti autenticati senza interazioni con l'utente. Vedere: /azure/active-directory/develop/v2-permissions-and-consent#offline_access | Il token di aggiornamento viene archiviato nel database in modo da poter aggiornare il token di accesso senza interazioni con l'utente. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con un servizio non Microsoft, elencare il servizio non Microsoft usato dall'app, i dati trasferiti e includere una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono usati servizi Microsoft.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni identificabili dell'utente finale (EUII): il roster (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunto. Questa app usa questa funzionalità?

>Non è possibile accedere all'identità dell'identità dell'utente.


#### <a name="telemetry-data"></a>Dati di telemetria

Nei dati di telemetria o nei log dell'applicazione vengono visualizzate informazioni personali dell'organizzazione o informazioni personali dell'utente finale( EUII) ? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Nei log o nei dati di telemetria delle applicazioni non vengono visualizzati dati OII o EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio l'eliminazione, la conservazione, il controllo, l'archiviazione, i criteri degli utenti finali e così via.

>Tutti i dati nel database sono crittografati. I backup dei dati del database verranno eseguiti e archiviati per un determinato periodo di tempo in base ai criteri operativi interni. Nel caso in cui un utente annulla questo servizio, elimineremo le informazioni utente dell'utente senza ritardi, tranne nella misura necessaria per soddisfare gli obblighi di archiviazione previsti dalla legge. Ecco i dettagli. https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni aziendali

Gli esseri umani sono coinvolti nella revisione o nell'analisi di eventuali dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono riportate le informazioni del catalogo [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='informazioni Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da KBE&#26666;&#24335;&#20250;&#31038; su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione dell'applicazione e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
