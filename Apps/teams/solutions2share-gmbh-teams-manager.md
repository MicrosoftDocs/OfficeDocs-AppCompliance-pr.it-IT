---
title: Application Information for Teams Manager by Solutions2Share GmbH
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e conformità disponibili per Teams Manager, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f941df5497b74f3558a56c0407456b42f3b2095d
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552767"
---
# <a name="teams-manager"></a>Teams Manager

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/87000000-3db9-bb44-5015-0b4a327a6597" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000764" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Solutions2Share GmbH a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Teams Manager |
| ID | WA200000764 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Solutions2Share GmbH |
| URL del sito Web del partner | [https://www.teams-manager.com](https://www.teams-manager.com) |
| URL dell'informativa sulla privacy | [https://www.teams-manager.com/privacy](https://www.teams-manager.com/privacy) |
| URL delle Condizioni per l'utilizzo | [https://www.teams-manager.com/terms-of-use/](https://www.teams-manager.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Solutions2Share GmbH su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | entrambi | Stiamo archiviando TenantID e TeamId per mappare i modelli.  | Consenti l'inserimento Teams e crea Teams. | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| Notes.ReadWrite.All | application | Nessuno | Consente all'app di aggiungere blocchi appunti a un team approvato. | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| User.Read | delegated | Nessuno | Consente all'utente di accedere e consente all'app di accedere all'UPN per abilitare l'accesso invisibile all'utente. | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| User.Read.All | entrambi | L'ID dell'utente immesso nella sezione responsabile approvazione/amministratore viene salvato. | Elenca tutti gli utenti per mostrarli nella selezione utenti all'interno dell'app. | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| User.ReadBasic.All | delegated | Nessuno | Elenca tutti gli utenti per mostrarli nella selezione utenti all'interno dell'app. | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Stiamo accedendo ad Azure Log Analytics e stiamo usando i criteri di archiviazione/conservazione.
Stiamo registrare l'ID tenant e l'ID del team per identificare i problemi e aiutare i clienti a risolvere i problemi.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Abbiamo un processo di conformità e funzionamento per il controllo degli accessi. Tutti i dati e i token correlati agli utenti vengono crittografati. I dati vengono archiviati in un database SQL di Azure. Stiamo usando il Firewall per consentire solo le connessioni da ip specifici (intervalli IP protetti tra sistemi). Abbiamo abilitato Privileged Access Management (PMA) in Azure.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

