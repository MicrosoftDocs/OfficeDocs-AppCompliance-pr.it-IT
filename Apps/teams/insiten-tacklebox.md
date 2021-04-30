---
title: Informazioni sull'applicazione per TackleBox di Insiten
ms.author: elmalova
author: elenamalova
ms.date: 01/12/2021
ms.topic: article
ms.service: attestation
description: Tutte le informazioni di sicurezza e conformità disponibili per TackleBox, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 19ff04953cb67cdcfcd6ea0b430ed3c1eb56f081
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095015"
---
# <a name="tacklebox"></a>TackleBox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 12, 2021</p>

* <a href="https://teams.microsoft.com/l/app/dc37dab6-b497-4259-9aad-e40bfa023796" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002310" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Insiten a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | TackleBox |
| ID | WA200002310 |
| Funzionalità | Scheda, connettore |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Insiten |
| URL del sito Web del partner | [https://tacklebox.app/](https://tacklebox.app/) |
| URL della pagina Teams informazioni sull'applicazione | [https://tacklebox.app](https://tacklebox.app) |
| URL dell'informativa sulla privacy | [https://tacklebox.app/privacy/](https://tacklebox.app/privacy/) |
| URL delle Condizioni per l'utilizzo | [https://tacklebox.app/terms/](https://tacklebox.app/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Insiten su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | delegated | Consente agli utenti di esplorare le OneDrive, le cartelle e i file. collegare i file a TackleBox; leggere Excel file per estrarre automaticamente grafici, grafici, tabelle, aree di stampa e intervalli denominati; creare e aggiornare PowerPoint file con questi Excel visivi | Drive ID, Folder ID, File ID, View Link, Created By, Created Date, Modified By, Modified Date, Version ID, File Name | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| Sites.Read.All | delegated | Consentire agli utenti di esplorare e collegare Excel file che si trovano in canali Teams privati | Nessuno | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| User.Read | delegated | Consente all'app di leggere il profilo degli utenti connessi e di ritrattare l'indirizzo di posta elettronica per le notifiche | Posta elettronica | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| openid | delegated | Consente agli utenti di accedere all'applicazione usando Microsoft 365 account | ID tenant e ID oggetto per l'utente | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| profilo | delegated | Consente all'app di visualizzare il profilo di base degli utenti (nome, nome utente) per facilitare la collaborazione | UPN, Nome, Cognome | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Indirizzi di posta elettronica e nomi di account. Gli account disattivati e i dettagli utente associati vengono eliminati dopo 3 mesi.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Non applicabile: tutti i dati vengono archiviati in Microsoft Azure

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35957' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35957" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Insiten su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

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
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
