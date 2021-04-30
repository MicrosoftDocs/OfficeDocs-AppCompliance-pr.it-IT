---
title: Informazioni sull'applicazione per gli annunci intelligenti da parte di Clever Ads
ms.author: elmalova
author: elenamalova
ms.date: 04/24/2020
ms.topic: article
ms.service: attestation
description: Tutte le informazioni di sicurezza e conformità disponibili per Clever Ads, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 23ea73534c5bafc739798de6e9326ee908961c03
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095376"
---
# <a name="clever-ads"></a>Clever Ads

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: April 24, 2020</p>

* <a href="https://teams.microsoft.com/l/app/ac2b56c0-f2a5-4e90-b618-882f8d3596f0" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001182" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Clever Ads a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Clever Ads |
| ID | WA200001182 |
| Funzionalità | Bot, scheda, estensione per la messaggistica, connettore |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Clever Ads |
| URL del sito Web del partner | [https://www.cleverads.com/](https://www.cleverads.com/) |
| URL dell'informativa sulla privacy | [https://www.cleverads.com/privacy-policy](https://www.cleverads.com/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://www.cleverads.com/terms-conditions](https://www.cleverads.com/terms-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Clever Ads su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegated | User.Read: archiviamo UPN, AzureObjectId per identificare l'utente. | User.Read, consente all'utente di accedere al dashboard dell'app. Usiamo UPN, AzureObjectId per l'accesso dell'utente. | ac2b56c0-f2a5-4e90-b618-882f8d3596f0 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| L'app accede all'elenco per identificare se un utente appartiene o meno al team e inviare i messaggi pianificati dall'utente ai propri team. | Archiviamo l'ID utente, azureObjectId, UPN, tenantId, conversationId e serviceUrl in modo da poter inviare messaggi all'utente o al team e identificarlo quando si accede alla scheda del dashboard. |  |



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Le informazioni dell'organizzazione non vengono archiviate nella telemetria o nei log. Registriamo solo le azioni dell'utente come inviare un messaggio al bot o fare clic su un pulsante, anche in questi registri l'ID dell'utente è il nostro ID utente interno, non correlato con l'ID di Microsoft Teams.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati delle applicazioni vengono archiviati in un database MySQL ospitato in Google Cloud, viene aggiunto un sistema di backup per i database e vengono gestiti tramite PMA e IP protetti.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35867' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35867" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

