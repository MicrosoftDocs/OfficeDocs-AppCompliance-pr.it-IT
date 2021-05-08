---
title: Informazioni sull'applicazione per Adobe Sign per Word e PowerPoint di Adobe Inc.
ms.author: elmalova
author: elenamalova
ms.date: 02/12/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per Adobe Sign per Word e PowerPoint, i criteri di gestione dei dati, le informazioni sul catalogo app di Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3ac861b6472b9c96483ea3e8a9ad8fd4d7f02834
ms.sourcegitcommit: 84c041bf4c0e79f1f3a14c4885ca5acd8709b129
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/06/2021
ms.locfileid: "52258943"
---
# <a name="adobe-sign-for-word-and-powerpoint"></a>Adobe Sign per Word e PowerPoint

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: February 12, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381155" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Adobe Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Adobe Sign per Word e PowerPoint |
| ID | WA104381155 |
| Client di Office 365 supportati | Word 2016 o versione successiva su Mac, PowerPoint 2013 Service Pack 1 o versione successiva in Windows, Word 2013 Service Pack 1 o versione successiva in Windows, Word sul Web, PowerPoint sul Web, PowerPoint 2016 o versione successiva su Mac |
| Nome società partner | Adobe Inc. |
| URL del sito Web del partner | [https://www.adobe.com/](https://www.adobe.com/) |
| URL dell'informativa sulla privacy | [https://www.adobe.com/privacy/policies-business/esign.html](https://www.adobe.com/privacy/policies-business/esign.html) |
| URL delle Condizioni per l'utilizzo | [https://support.office.com/client/61994a3b-2c87-41c4-a88d-a...](https://support.office.com/client/61994a3b-2c87-41c4-a88d-a6455efa362d?omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Adobe Inc. Su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni di Microsoft Graph necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | delegated | Per popolare il documento allegato, i messaggi di posta elettronica del mittente e del destinatario e il contenuto del messaggio dai messaggi di posta elettronica a Adobe Sign da inviare per la firma. Ciò consente di risparmiare tempo all'utente per digitare di nuovo i campi in Adobe Sign. Dopo la firma di un contratto, componi automaticamente un nuovo messaggio di posta elettronica per l'utente per inviare un messaggio di posta elettronica per informare i destinatari che la transazione è stata eseguita. | Adobe Sign salverà gli allegati come file temporanei, con una scadenza di 24 ore. | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| People.Read | delegated | Per riempire automaticamente l'indirizzo di posta elettronica nell'esperienza invia per la firma, digitando alcune lettere iniziali, non è necessario che gli utenti di &quot; &quot; digitare l'intero messaggio di posta elettronica. | Adobe Sign archivia solo i messaggi di posta elettronica e displayName dei destinatari nei contratti. | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| User.Read | delegated | Per leggere il profilo dell'utente e associare il proprio profilo (fondamentalmente, la posta elettronica e l'ID utente) al database in modo che possa usare Adobe Sign. | Per leggere il profilo dell'utente e associare il proprio profilo (fondamentalmente, la posta elettronica e l'ID utente) al database in modo che possa usare Adobe Sign. | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| offline_access | delegated | Per aggiornare il token di accesso, quando quello corrente è scaduto. Ad esempio, quando l'utente è in una finestra di invio per la firma e lo lascia inattivo per troppo tempo, è necessario aggiornare un nuovo token quando l'utente &quot; &quot; è attivo. | Per aggiornare il token di accesso, quando quello corrente è scaduto. Ad esempio, quando l'utente è in una finestra di invio per la firma e lo lascia inattivo per troppo tempo, è necessario aggiornare un nuovo token quando l'utente &quot; &quot; è attivo. | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| openid | delegated | Email e UserId. Per accedere all'utente per garantire il consenso per l'autorizzazione all'uso dell'app Adobe Sign.  | Email è l'identificatore univoco per gli utenti in Adobe Sign. Archiviamo l'ID di posta elettronica in modo da poter mappare tutte le attività dell'utente al suo record Adobe Sign.  | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |


#### <a name="non-microsoft-services-used"></a>Servizi non Microsoft utilizzati

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>I servizi non Microsoft non vengono utilizzati.



#### <a name="add-in-data-access"></a>Accesso ai dati del componente aggiuntivo

Elenca le autorizzazioni richieste da questa app per accedere ai dati dell'organizzazione, la giustificazione e lo scopo di questa autorizzazione (per cosa l'app usa queste informazioni?) e se l'app archivia queste informazioni nei relativi database.

>| **Autorizzazione**  | **Descrizione** |
>|:----------------|:----------------|
>| ReadWrite Document | Può leggere e apportare modifiche al documento |
>| Invia dati | Può inviare dati tramite Internet |

#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>I log contengono informazioni sufficienti per identificare e risolvere i problemi dei clienti. I registri vengono conservati per 90 giorni e l'accesso è limitato. Il database archivia le informazioni di identificazione con hash per l'autenticazione mentre l'utente è offline. I criteri di conservazione del database sono a 30 giorni dall'ultimo utilizzo

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Non è presente alcuna interazione dell'amministratore del cliente nel sistema per l'applicazione Microsoft Teams.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [catalogo di Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Informazioni sulla sicurezza delle app cloud Microsoft' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Adobe Inc. Sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di controllo per l'integrazione della piattaforma di identità Microsoft?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- Flusso implicito OAuth2, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
