---
title: Informazioni sull'applicazione per Reach by LiveTiles
ms.author: elmalova
author: elenamalova
ms.date: 03/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Reach, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 81a3afa06f4843c68a5e32da49f7e7be09e0684a
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252456"
---
# <a name="reach"></a>Reach

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 22, 2021</p>

* <a href="https://teams.microsoft.com/l/app/5df8ebd2-bf7b-4fb5-bb35-0bfbf5d10a23" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002045" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da LiveTiles a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Reach |
| ID | WA200002045 |
| Funzionalità | Scheda |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | LiveTiles |
| URL del sito Web del partner | [https://livetilesglobal.com](https://livetilesglobal.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://livetilesglobal.com/products/livetiles-reach/](https://livetilesglobal.com/products/livetiles-reach/) |
| URL dell'informativa sulla privacy | [https://livetilesglobal.com/privacy-policy](https://livetilesglobal.com/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://livetilesglobal.com/eula](https://livetilesglobal.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da LiveTiles su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| TeamsActivity.Send | application | Nessuno | Nessuno | a7c1920d-3ac0-42db-9757-078a2b321fd8  |
>| User.Read | delegated | User DisplayName, User Email Address, UPN. Obbligatorio per consentire agli utenti di accedere all'app e ottenere le informazioni di base dell'utente connesso, ad esempio il nome visualizzato. L'indirizzo di posta elettronica viene utilizzato per inviare notifiche tramite posta elettronica.  | User DisplayName, User Email Address, UPN. Obbligatorio per consentire agli utenti di accedere all'app e ottenere le informazioni di base dell'utente connesso, ad esempio il nome visualizzato. L'indirizzo di posta elettronica viene utilizzato per inviare notifiche tramite posta elettronica.  | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| User.ReadBasic.All | delegated | User DisplayName, User Email Address, UPN, User Department, User Job Title, User Mobile Telefono Number, User Business Telefono Number, User Office Location. Obbligatorio per consentire agli utenti di cercare altri utenti all'interno dell'app (Rubrica telefonica) e visualizzare le informazioni di contatto e il profilo di base di altri utenti.  | nessuno | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| Directory.Read.All | application | Appartenenza a gruppi, Gruppi di Active Directory in Directory. L'appartenenza a gruppi di utenti viene archiviata in una cache per ridurre al minimo le chiamate all'API microsoft Graph. Obbligatorio per consentire agli utenti di cercare gruppi di Active Directory. Inoltre, questa autorizzazione è necessaria per consentire all'applicazione di risolvere l'appartenenza al gruppo ACTIVE degli utenti nei processi Web del back-end. | Appartenenza a un gruppo di utenti. L'appartenenza a gruppi di utenti viene archiviata in una cache per ridurre al minimo le chiamate all'API microsoft Graph. Obbligatorio per consentire agli utenti di cercare gruppi di Active Directory. Inoltre, questa autorizzazione è necessaria per consentire all'applicazione di risolvere l'appartenenza al gruppo ACTIVE degli utenti nei processi Web del back-end.  | d492530a-8cff-481c-90da-9c3c3f1be7da  |
>| User.Read.All | application | I dati recuperati dal profilo utente dipendono dalla configurazione della funzionalità Di destinazione del gruppo di destinatari specificata nell'app. Obbligatorio per consentire all'app di leggere i profili utente senza un utente connesso. La lettura dei dati del profilo è necessaria per la funzionalità di destinazione delle informazioni all'interno dell'applicazione, in modo che le informazioni vengono visualizzate a utenti specifici in base a un valore di proprietà del profilo specifico.  | nessuno | d492530a-8cff-481c-90da-9c3c3f1be7da  |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutte le informazioni non servizi Microsoft OII vengono trasferite a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento di OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| SendGrid, OneSignal | indirizzo di posta elettronica, nome visualizzato | Inviare una notifica all'utente tramite posta elettronica e notifiche push per dispositivi mobili |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>indirizzo di posta elettronica, UPN. conservazione massima di 60 giorni, dopo di che vengono rimossi

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Gli amministratori possono contattare il supporto per qualsiasi richiesta di informazioni

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da LiveTiles su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | No |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Autenticazione a più fattori, limitazione delle posizioni utente e degli intervalli IP |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | Sì |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
