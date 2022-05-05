---
title: Informazioni sull'applicazione per Sobol
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Sobol, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 562b420ee2289b9caac8d7be016d2b5619a6f682
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/05/2022
ms.locfileid: "65227230"
---
# <a name="application-information-for-sobol"></a>Informazioni sull'applicazione per Sobol

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 24 giugno 2021</p>

* <a href="https://teams.microsoft.com/l/app/659f0ad6-8b3d-4846-8c4c-00ea9dfd64c8" target="_blank">Visualizza in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002999" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da ConsenSys AG&#8217;sobol a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Sobol |
| ID | WA200002999 |
| client Office 365 supportati | Microsoft Teams |
| Nome della società partner | ConsenSys AG&#8217;s Sobol |
| URL del sito Web del partner | [https://sobol.io](https://sobol.io) |
| URL della pagina Teams informazioni sull'applicazione | [https://sobol.io/features](https://sobol.io/features) |
| URL dell'informativa sulla privacy | [https://sobol.io/privacy-policy](https://sobol.io/privacy-policy) |
| URL delle condizioni per l'utilizzo | [https://sobol.io/terms-of-service/](https://sobol.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da ConsenSys AG&#8217;s Sobol su come questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elencare le [autorizzazioni di Microsoft Graph](/graph/permissions-reference) necessarie per questa app.

>Questa applicazione non usa Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con un servizio non Microsoft, elencare il servizio non Microsoft usato dall'app, i dati trasferiti e includere una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Hubspot, Fullstory | username, email | marketing e analisi |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni identificabili dell'utente finale (EUII): il roster (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunto. Questa app usa questa funzionalità?

>Non è possibile accedere all'identità dell'identità dell'utente.


#### <a name="telemetry-data"></a>Dati di telemetria

Nei dati di telemetria o nei log dell'applicazione vengono visualizzate informazioni personali dell'organizzazione o informazioni personali dell'utente finale( EUII) ? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>username, email. Rimozione dopo 2 anni o su richiesta dell'utente.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio l'eliminazione, la conservazione, il controllo, l'archiviazione, i criteri degli utenti finali e così via.

>Gli amministratori hanno la possibilità completa di controllare ed eliminare le informazioni. Raccogliamo le informazioni minime necessarie per identificare gli utenti.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni aziendali

Gli esseri umani sono coinvolti nella revisione o nell'analisi di eventuali dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

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

Queste informazioni sono state fornite da ConsenSys AG&#8217;s Sobol sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione dell'applicazione e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
