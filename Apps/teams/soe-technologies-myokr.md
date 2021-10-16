---
title: Informazioni sull'applicazione per myOKR di SOE Technologies
ms.author: elmalova
author: elenamalova
ms.date: 10/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per myOKR, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c4a3e8872b8042f0114925c0e89de12b98ef5440
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411471"
---
# <a name="myokr"></a>myOKR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 18, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c0b70874-2c95-4be7-a0cb-0d893e25a2a3" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003308" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da SOE Technologies a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | myOKR |
| ID | WA200003308 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | INC Technologies |
| URL del sito Web del partner | [https://www.myokr.co](https://www.myokr.co) |
| URL della Teams info dell'applicazione | [https://www.myokr.co](https://www.myokr.co) |
| URL dell'informativa sulla privacy | [https://www.myokr.co/privacy](https://www.myokr.co/privacy) |
| URL delle Condizioni per l'utilizzo | [https://www.myokr.co/terms](https://www.myokr.co/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da SOE Technologies su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated | Ottenere i dettagli del calendario dell'utente per creare una riunione 1:1 nel calendario utente, aggiornare o eliminare creato dalla piattaforma myOKR e visualizzare le fasce orarie gratuite | Archiviamo l'ID calendario creato e l'URL di partecipazione nel database per le riunioni create nella piattaforma myOKR | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| User.Read | delegated | Usiamo l'ID oggetto azure dell'utente per effettuare l'accesso dell'utente all'app myOKR usando l'autenticazione Microsoft per la posta elettronica | e-mail utente e ID oggetto azure active | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| User.Read.All | application | Sincronizzare le informazioni utente con la piattaforma myOKR e visualizzare l'analisi dell'applicazione myOKR all'amministratore in base a diversi tagli utente, ad esempio posizione, department &amp; manager | Archiviamo id utente, nome, e-mail, reparto, titolo e informazioni sul manager nel sistema myOKR | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| offline_access | delegated | ID azure active directory dell'utente | Viene utilizzato l'accesso offline per creare riunioni ricorrenti nel calendario degli utenti | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| openid | delegated | Usiamo l'ID oggetto azure dell'utente per effettuare l'accesso utente all'app myOKR usando l'autenticazione Microsoft | L'ID azure attivo dell'utente viene archiviato nel messaggio di posta elettronica | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| L'ID di Active Directory dell'utente viene archiviata in base alla posta elettronica dell'utente per inviare messaggi proattivi dal bot. | Email, Name, Manager Information, Title, User Azure Active Directory ID  | Queste informazioni vengono utilizzate nell'applicazione myOKR per creare un account utente, consentire al manager di visualizzare i dettagli del reportee su platfrom, consentire all'amministratore di visualizzare l'analisi complessiva e i report in base a reparto, posizione e manager |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>SpOC dell'organizzazione ci comunica per la chiusura del servizio e i relativi dati vengono eliminati dopo 30 giorni dopo l'intimità e il roll over dai backup del database dopo altri 30 giorni.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da SOE Technologies sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

