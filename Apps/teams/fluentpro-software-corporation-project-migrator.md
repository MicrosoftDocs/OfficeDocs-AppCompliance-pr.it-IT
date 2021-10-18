---
title: Informazioni sull'applicazione Project Migrator di FluentPro Software Corporation
ms.author: elmalova
author: elenamalova
ms.date: 08/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Project Migrator, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 1569bf8fe9cf8dd2e1f96e857d0a9f2a63af774a
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428068"
---
# <a name="project-migrator"></a>Project Migrator

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 17, 2021</p>

* <a href="https://teams.microsoft.com/l/app/8cd35615-e306-4b3d-8e93-17520129b60a" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003160" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da FluentPro Software Corporation a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Project Migrator |
| ID | WA200003160 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | FluentPro Software Corporation |
| URL del sito Web del partner | [https://projectmigrator.com](https://projectmigrator.com) |
| URL della Teams info dell'applicazione | [https://help.fluentpro.com/147404-project-migrator](https://help.fluentpro.com/147404-project-migrator) |
| URL dell'informativa sulla privacy | [https://projectmigrator.com/privacy-policy](https://projectmigrator.com/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://projectmigrator.com/terms-of-use](https://projectmigrator.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da FluentPro Software Corporation sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegated | Leggere i gruppi e la relativa appartenenza per eseguire la migrazione all'altro tenant. | Nessun dato archiviato per questa autorizzazione.  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| Group.ReadWrite.All | delegated | Nome gruppo, Membri, Piani e Attività. Utilizzare informazioni su gruppi, piani e attività per la migrazione dei dati di Planner. | Nome gruppo, Nome piano e Nome attività. Utilizzato per il riepilogo delle informazioni sulla migrazione.  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| Sites.ReadWrite.All | delegated | Eseguire la SharePoint documenti per gli allegati delle attività di MS Planner. | Nessun dato archiviato per questa autorizzazione.  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| User.Read | delegated | UPN per archiviare le informazioni di riepilogo della migrazione di MS Planner collegate all'account. | UPN. | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| User.ReadBasic.All | delegated | Utilizzare le informazioni utente per eseguire la migrazione delle assegnazioni delle attività di MS Planner e dell'appartenenza ai gruppi. | Nessun dato archiviato per questa autorizzazione.  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| offline_access | delegated | I token di aggiornamento e accesso vengono utilizzati per accedere ai dati di MS Planner. | Il token di aggiornamento crittografato viene archiviato per accedere ai dati di MS Planner. | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| User.Read | delegated | First Name, Last Name, Company Name, Telefono, Corporate Email. Dati utilizzati per i processi di registrazione e autenticazione. | First Name, Last Name, Company Name, Telefono, Corporate Email, UPN. | [c36d31a2-8de1-4eb5-9e7d-01da45244c04](https://docs.microsoft.com/microsoft-365-app-certification/azure/c36d31a2-8de1-4eb5-9e7d-01da45244c04) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>https://projectmigrator.com/privacy-policy

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da FluentPro Software Corporation sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | No |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | Sì |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
