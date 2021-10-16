---
title: Informazioni sull'applicazione per ThoughtWire EWS di ThoughtWire Corp.
ms.author: elmalova
author: elenamalova
ms.date: 09/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per ThoughtWire EWS, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: ef425a6acb8cfe166502b4c4817229b1b33da14b
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414913"
---
# <a name="thoughtwire-ews"></a>ThoughtWire EWS

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 17, 2021</p>

* <a href="https://teams.microsoft.com/l/app/ed27363f-755e-4658-b7bf-409d475959d6" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003239" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da ThoughtWire Corp. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | ThoughtWire EWS |
| ID | WA200003239 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | ThoughtWire Corp. |
| URL del sito Web del partner | [https://thoughtwire.com](https://thoughtwire.com) |
| URL dell'informativa sulla privacy | [https://thoughtwire.com/privacy-policy](https://thoughtwire.com/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://www.thoughtwire.com/end-user-license-agreement/](https://www.thoughtwire.com/end-user-license-agreement/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da ThoughtWire Corp. Su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Create | application | Consente all'applicazione di creare gruppi/team per reparti/unità ospedaliere. | Nessuno | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| Group.ReadWrite.All | application | Obbligatorio per l'applicazione per determinare quali gruppi potrebbe essere necessario creare/ri-creare e per gestire l'appartenenza. | Nessuno | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| GroupMember.ReadWrite.All | application | Obbligatorio in modo che l'applicazione possa gestire l'appartenenza ai gruppi. Ad esempio, l'aggiunta/rimozione di infermieri da un team quando cambiano i turni. | Nessuno | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| TeamMember.ReadWrite.All | application | Obbligatorio in modo che l'applicazione possa gestire l'appartenenza ai gruppi. Ad esempio, l'aggiunta/rimozione di infermieri da un team quando cambiano i turni. | Nessuno | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| TeamsAppInstallation.ReadWriteForTeam | application | Consente all'applicazione di installare automaticamente il bot ThoughtWire nei team creati/gestiti. | Nessuno | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| User.Read | application | Consentire all'applicazione di recuperare l'AADID/nome utente di un utente come richiesto durante la gestione dell'appartenenza e/o il recupero del nome utente per l'identità dell'utente all'interno dell'applicazione. | Nessuno | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Il nome utente è necessario per identificare l'utente che esegue le azioni. | Nome utente e ID utente | Controllo di notifiche ed eventi. |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>ThoughtWire seleziona i partner che soddisfano o superano i processi di controllo dei dati. I dati non vengono forniti ai sistemi partner a meno che non sia assolutamente necessario. Tutti i servizi ThoughtWire e i sistemi partner correlati vengono controllati e approvati dai clienti.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da ThoughtWire Corp. Sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | No |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

