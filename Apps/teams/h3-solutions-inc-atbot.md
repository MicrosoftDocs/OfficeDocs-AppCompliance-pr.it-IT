---
title: Informazioni sull'applicazione per AtBot di H3 Solutions, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per AtBot, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3f56d0b3eb19f5bed8f7092507c8605af936b911
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552137"
---
# <a name="atbot"></a>AtBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 16 dicembre 2019</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381219" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da H3 Solutions, Inc.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | AtBot |
| ID | WA104381219 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | H3 Solutions, Inc. |
| URL del sito Web partner | [https://atbot.io](https://atbot.io) |
| URL della pagina Teams informazioni sull'applicazione | [https://admin.atbot.io/Docs/GettingStarted](https://admin.atbot.io/Docs/GettingStarted) |
| URL dell'Informativa sulla privacy | [https://admin.atbot.io/privacy](https://admin.atbot.io/privacy) |
| URL delle Condizioni d'uso | [https://admin.atbot.io/terms](https://admin.atbot.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da H3 Solutions, Inc.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | applicazione | Nome gruppo AAD, GUID gruppo AAD, UPN | Enumerare i gruppi AAD per consentire il taglio della sicurezza delle competenze del bot. Enumerare gli utenti per poter applicare licenze. Enumerare gli utenti da aggiungere come amministratori/collaboratori | 066A6B3A-F7A0-450A-98C7-34DB1DA31594 |
>| Directory.Read.All | delegato | Nome gruppo AAD, GUID gruppo AAD, UPN | Enumerare i gruppi AAD per consentire il taglio della sicurezza delle competenze del bot. Enumerare gli utenti per poter applicare licenze. Enumerare gli utenti da aggiungere come amministratori/collaboratori | 066A6B3A-F7A0-450A-98C7-34DB1DA31594 |
>| Persone.Lettura | delegato | No | Enumerare le persone in un'azione Ottieni persona da Flow.  Consente al bot di recuperare persone dall'endpoint /People in Microsoft Graph. | 066A6B3A-F7A0-450A-98C7-34DB1DA31594 |
>| User.Read | delegato | ID tenant, UPN | Ci dà accesso all'ID tenant e all&#8217;'UPN dell'utente per consentirci di legare flussi / app logiche create agli utenti che li hanno creati. | 066A6B3A-F7A0-450A-98C7-34DB1DA31594 |
>| e-mail | delegato | No | Ci dà accesso all'indirizzo e-mail dell'utente. | 066A6B3A-F7A0-450A-98C7-34DB1DA31594 |
>| offline_access | delegato | Token di accesso/aggiornamento. | Consente di utilizzare un token di aggiornamento per mantenere gli utenti connessi. | 066A6B3A-F7A0-450A-98C7-34DB1DA31594 |
>| openid | delegato | No | Consente agli utenti di accedere. | 066A6B3A-F7A0-450A-98C7-34DB1DA31594 |
>| profilo | delegato | UPN | Accesso all'UPN dell'utente. | 066A6B3A-F7A0-450A-98C7-34DB1DA31594 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| La creazione di menzioni nei messaggi di chat generati dai bot | No |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>ID tenant, UPN Utilizziamo Application Insights e i nostri registri dureranno 90 giorni prima di essere archiviati automaticamente. (https://docs.microsoft.com/azure/azure-monitor/app/data-retention-privacy)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Gli amministratori hanno la possibilità di eliminare le configurazioni bot che possono contenere nomi/GUID di gruppo AAD.
Al momento dell'annullamento del servizio, tutti gli UPN verranno rimossi dal database delle licenze.
Vedere 'Servizi di Azure' in Data Residency.  Gran parte dei dati specifici del cliente prodotti tramite l'uso di AtBot vengono archiviati nel tenant del cliente e quindi gli amministratori di quel tenant hanno il pieno controllo dei dati lì.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

