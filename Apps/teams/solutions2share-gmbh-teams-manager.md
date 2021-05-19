---
title: Informazioni sull'applicazione Teams Manager di Solutions2Share GmbH
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Teams Manager, i relativi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
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
<p>Ultimo aggiornamento da parte dello sviluppatore: 16 dicembre 2019</p>

* <a href="https://teams.microsoft.com/l/app/87000000-3db9-bb44-5015-0b4a327a6597" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000764" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Solutions2Share GmbH a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Teams Manager |
| ID | WA200000764 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Solutions2Share GmbH |
| URL del sito Web partner | [https://www.teams-manager.com](https://www.teams-manager.com) |
| URL dell'Informativa sulla privacy | [https://www.teams-manager.com/privacy](https://www.teams-manager.com/privacy) |
| URL delle Condizioni d'uso | [https://www.teams-manager.com/terms-of-use/](https://www.teams-manager.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Solutions2Share GmbH su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | ambedue | Stiamo archiviando TenantID e TeamId per mappare i modelli.  | Consenti l'inserzione Teams e crea Teams. | B9a1AAAB-E8AA-4B92-B4CE-F13Cae74Caa7 |
>| Notes.ReadWrite.All | applicazione | Nessuno | Consente all'app di aggiungere blocchi appunti a un team approvato. | B9a1AAAB-E8AA-4B92-B4CE-F13Cae74Caa7 |
>| User.Read | delegato | Nessuno | Consente all'utente di accedere e consente all'app di accedere al proprio UPN per abilitare l'accesso invisibile all'utente. | B9a1AAAB-E8AA-4B92-B4CE-F13Cae74Caa7 |
>| User.Read.All | ambedue | Salviamo l'ID dell'utente immesso nella sezione approvatore/amministratore. | Elenca tutti gli utenti per visualizzarli nella selezione utenti all'interno dell'app. | B9a1AAAB-E8AA-4B92-B4CE-F13Cae74Caa7 |
>| User.ReadBasic.All | delegato | Nessuno | Elenca tutti gli utenti per visualizzarli nella selezione utenti all'interno dell'app. | B9a1AAAB-E8AA-4B92-B4CE-F13Cae74Caa7 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>Non è possibile accedere all'I EUII.


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Stiamo accedendo ad Azure Log Analytics e stiamo usando i criteri di archiviazione /conservazione.
Stiamo registrando l'ID tenant e l'ID del team per identificare i problemi e aiutare i clienti a risolvere i problemi.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Abbiamo un processo di conformità e funzionamento per il controllo degli accessi. Tutti i dati e i token relativi agli utenti sono crittografati. I dati vengono memorizzati in un database SQL di Azure. Stiamo utilizzando il Firewall per consentire solo connessioni da IP specifici (intervalli IP protetti tra sistemi). Abbiamo abilitato la gestione degli accessi privilegiati (PMA) in Azure.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

