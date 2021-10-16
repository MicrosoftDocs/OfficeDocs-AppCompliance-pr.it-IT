---
title: Application Information for Lumio by SMART by SMART Technologies ULC
ms.author: elmalova
author: elenamalova
ms.date: 04/29/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Lumio by SMART, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: e5749e9439f48960293fbb13d3efe8f3ef00158d
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413488"
---
# <a name="lumio-by-smart"></a>Lumio by SMART

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: April 19, 2021</p>

* <a href="https://teams.microsoft.com/l/app/e0ffcbc7-f3f2-46b7-a189-afd01c545782" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001874" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da SMART Technologies ULC a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Lumio by SMART |
| ID | WA200001874 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | SMART Technologies ULC |
| URL del sito Web del partner | [https://smarttech.com](https://smarttech.com) |
| URL della Teams info dell'applicazione | [https://www.smarttech.com/smart-learning-suite/](https://www.smarttech.com/smart-learning-suite/) |
| URL dell'informativa sulla privacy | [https://www.smarttech.com/en/legal/privacy-policies](https://www.smarttech.com/en/legal/privacy-policies) |
| URL delle Condizioni per l'utilizzo | [https://www.smarttech.com/legal/sls-terms](https://www.smarttech.com/legal/sls-terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da SMART Technologies ULC su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegated | I dati vengono utilizzati per verificare le autorizzazioni del gruppo non vengono raccolti dati.  | Nessun dato di directory archiviato nel database | [14cf575a-fae2-48e2-af39-e3448d3a48bb](https://docs.microsoft.com/microsoft-365-app-certification/azure/14cf575a-fae2-48e2-af39-e3448d3a48bb) |
>| Group.Read.All | delegated | il gruppo di cui sono appart, questo viene usato per verificare che siano parte del gruppo di studenti o insegnanti per determinare la funzionalità. Nessun dato raccolto.  | Solo i dati archiviati sono l'ID univoco dei client | [14cf575a-fae2-48e2-af39-e3448d3a48bb](https://docs.microsoft.com/microsoft-365-app-certification/azure/14cf575a-fae2-48e2-af39-e3448d3a48bb) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Supportiamo il diritto all'oblio in tutti i sistemi partner, inclusi i registri, il controllo e l'archiviazione. Si tratta di un processo manuale in cui un amministratore di sistema per quel partner rimuove, modifica o archivia i dati. 

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37582' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37582" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da SMART Technologies ULC su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

