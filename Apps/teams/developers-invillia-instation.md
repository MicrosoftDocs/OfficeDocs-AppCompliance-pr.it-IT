---
title: Informazioni sull'applicazione per InStation da parte degli sviluppatori Invillia
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per InStation, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza / conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 40c86e4284ed201fedf63bfe3bbd7570b61049b7
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552247"
---
# <a name="instation"></a>InStation

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 6 agosto 2020</p>

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite dagli sviluppatori Invillia a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | InStation |
| ID | WA200001701 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Developers Invillia |
| URL del sito Web partner | [https://instation.invillia.com/](https://instation.invillia.com/) |
| URL dell'Informativa sulla privacy | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| URL delle Condizioni d'uso | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite dagli sviluppatori Invillia su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| OnlineMeetings.Read.All | delegato | negozi: id, join_url, join_web_url e chat_id. Consente all'app di creare riunioni | negozi: id, join_url, join_web_url e chat_id. Consente all'app di creare riunioni | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| OnlineMeetings.ReadWrite.All | delegato | negozi: id, join_url, join_web_url e chat_id. Consente all'app di creare riunioni | negozi: id, join_url, join_web_url e chat_id. Consente all'app di creare riunioni | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read | delegato | Consente all'app di accedere all'organizzazione al primo passaggio | attività e avalibilità. Consente all'app di acquisire lo stato degli utenti; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read.All | delegato | Consente all'app di accedere all'organizzazione al primo passaggio, | attività e avalibilità. Consente all'app di acquisire lo stato degli utenti; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read | delegato | negozi: id, posta, nome visualizzato, cognome e immagine. Consente all'app di cercare i dati dell'utente; | negozi: id, posta, nome visualizzato, cognome e immagine. Consente all'app di cercare i dati dell'utente; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read.All | delegato | negozi: id, posta, nome visualizzato, cognome e immagine. Consente all'app di cercare i dati dell'utente; | negozi: id, posta, nome visualizzato, cognome e immagine. Consente all'app di cercare i dati dell'utente; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| e-mail | delegato | Consente all'app di acquisire le informazioni di base&#180;'amministratore sul primo account di accesso | Consente all'app di acquisire le informazioni di base&#180;'amministratore sul primo account di accesso | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| offline_access | delegato | negozi: token e token di aggiornamento. Consente all'app di eseguire un aggiornamento sul token MS | negozi: token e token di aggiornamento. Consente all'app di eseguire un aggiornamento sul token MS | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| openid | delegato | Consente all'app di accedere all'organizzazione al primo passaggio | Consente all'app di accedere all'organizzazione al primo passaggio | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| profilo | delegato | Consente all'app di acquisire le informazioni di&#180;dell'amministratore sul primo account di accesso; | Consente all'app di acquisire le informazioni di&#180;dell'amministratore sul primo account di accesso; | 0c841985-9919-4c0a-b87d-b06b301148b3 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>Non è possibile accedere all'I EUII.


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Salviamo solo i registri di utilizzo degli utenti all'interno della nostra applicazione.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Salviamo solo i registri di utilizzo degli utenti all'interno della nostra applicazione. Niente di confidenziale, che non richiede alcuna crittografia e solo i nostri amministratori specifici hanno accesso a questi dati.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

