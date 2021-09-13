---
title: Informazioni sull'applicazione per ora agente virtuale da ServiceNow
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Now Virtual Agent, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 1ac2988c550894341d5933afbc59de6f63c51b68
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282397"
---
# <a name="now-virtual-agent"></a>Now Virtual Agent

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/49471a10-fdbc-4ffb-b0b8-944f3df985d9" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381816" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da ServiceNow a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Now Virtual Agent |
| ID | WA104381816 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | ServiceNow |
| URL del sito Web del partner | [https://www.servicenow.com/](https://www.servicenow.com/) |
| URL della Teams info dell'applicazione | [https://docs.servicenow.com/bundle/london-servicenow-platfo...](https://docs.servicenow.com/bundle/london-servicenow-platform/page/administer/virtual-agent/task/install-va-integrations.html#install-va-integrations) |
| URL dell'informativa sulla privacy | [https://www.servicenow.com/service-privacy.html](https://www.servicenow.com/service-privacy.html) |
| URL delle Condizioni per l'utilizzo | [https://www.servicenow.com/terms-of-use.html](https://www.servicenow.com/terms-of-use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da ServiceNow su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegated | Il dominio viene archiviato nel data center per scopi futuri di routing dei messaggi. | Quando l'amministratore di ServiceNow installa l'integrazione con MS Teams, l'amministratore deve accedere al proprio account ms Teams. Il dominio viene letto dall'indirizzo di posta elettronica (non dall'indirizzo di posta elettronica completo). | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Non out-of-box da ServiceNow. I clienti possono sfruttare il framework agente virtuale per creare funzionalità aggiuntive che possono potenzialmente accedere alle informazioni dell'organizzazione o degli utenti finali. Gli utenti possono digitare informazioni personali identificabili durante l'interazione con il bot e inviare le informazioni a ServiceNow.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Per informazioni [dettagliate, fare riferimento](/microsoft-365-app-certification/teams/servicenow-now-virtual-agent?pivots=csa) alla sezione Cloud Security Alliance.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalogo vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10638' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10638" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

