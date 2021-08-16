---
title: Informazioni sull'applicazione per AtBot di H3 Solutions, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per AtBot, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d71404e66489ba3f1e81ca5f1a1a92c17b36f9e6
ms.sourcegitcommit: 7ef4a79aa28ac4dcce067b1f6f8693eeec6335e9
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/13/2021
ms.locfileid: "58239746"
---
# <a name="atbot"></a>AtBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 10, 2021</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381219" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da H3 Solutions, Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | AtBot |
| ID | WA104381219 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | H3 Solutions, Inc. |
| URL del sito Web del partner | [https://atbot.io](https://atbot.io) |
| URL della Teams info dell'applicazione | [https://admin.atbot.io/Docs/GettingStarted](https://admin.atbot.io/Docs/GettingStarted) |
| URL dell'informativa sulla privacy | [https://admin.atbot.io/privacy](https://admin.atbot.io/privacy) |
| URL delle Condizioni per l'utilizzo | [https://admin.atbot.io/terms](https://admin.atbot.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da H3 Solutions, Inc. Sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | application | Nome gruppo AAD, GUID gruppo AAD, UPN | Enumerare i gruppi AAD per consentire la limitazione per motivi di sicurezza delle competenze dei bot. Enumerare gli utenti per poter applicare le licenze. Enumerare gli utenti da aggiungere come Amministratori/Collaboratori | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| Directory.Read.All | delegated | Nome gruppo AAD, GUID gruppo AAD, UPN | Enumerare i gruppi AAD per consentire la limitazione per motivi di sicurezza delle competenze dei bot. Enumerare gli utenti per poter applicare le licenze. Enumerare gli utenti da aggiungere come Amministratori/Collaboratori | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| People.Read | delegated | No | Enumerare le persone in un'azione Ottieni persona da Flow.  Consente al bot di recuperare le persone dall'endpoint /People in Microsoft Graph. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| User.Read | delegated | ID tenant, UPN | Ci consente di accedere all'ID tenant&#8217;utente e all'UPN per consentire di collegare flussi/app per la logica creati agli utenti che li hanno creati. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| email | delegated | Gli indirizzi di posta elettronica vengono utilizzati per contattare il supporto tramite il nostro sistema di supporto. | Ci consente di accedere all'indirizzo di posta elettronica dell'utente. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| offline_access | delegated | Token di accesso/aggiornamento. | Ci consente di usare un token di aggiornamento per mantenere gli utenti connessi. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| openid | delegated | UPN, identifica l'utente all'interno del sistema | Consente agli utenti di accedere. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| profilo | delegated | UPN | Accesso all'UPN dell'utente. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Il bot può accedere all'UPN dell'utente per @mention utenti o inviare loro messaggi. | UPN | È necessario archiviare l'UPN per consentire agli utenti di accedere al sistema |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>ID tenant, UPN. Usiamo Application Insights e i log avranno una durata di 90 giorni prima di essere archiviati automaticamente. (https://docs.microsoft.com/azure/azure-monitor/app/data-retention-privacy)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Gli amministratori hanno la possibilità di eliminare configurazioni di bot che possono contenere nomi/GUID di gruppi AAD.
Dopo l'annullamento del servizio, tutti gli UPN verranno rimossi dal database delle licenze.
Vedere "Servizi di Azure" in Data Residency.  La maggior parte dei dati specifici del cliente prodotti tramite l'uso di AtBot viene archiviata nel tenant del cliente e pertanto gli amministratori di tale tenant hanno il controllo completo dei dati presenti.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da H3 Solutions, Inc. Sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
