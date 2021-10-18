---
title: Informazioni sull'applicazione per il tragitto pendolarmente
ms.author: elmalova
author: elenamalova
ms.date: 10/07/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Commuty, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 60cfe397fcc43a029863e12bddacb6667877ca4e
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60444602"
---
# <a name="commuty"></a>Pendolarità

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: October 7, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003325" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Commuty a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Pendolarità |
| ID | WA200003325 |
| Office 365 client supportati | Outlook 2016 o versioni successive Windows, Outlook 2016 o versioni successive su Mac, Outlook sul web |
| Nome società partner | Pendolarità |
| URL del sito Web del partner | [https://www.commuty.net](https://www.commuty.net) |
| URL dell'informativa sulla privacy | [https://support.commuty.net/article/33-privacy-policy](https://support.commuty.net/article/33-privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://support.commuty.net/article/32-terms-conditions](https://support.commuty.net/article/32-terms-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Commuty su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated | Eventi calendario | Nessuno, viene usato solo per sincronizzare i dati di Commuty con Calendario di Outlook. I dati vengono sempre forniti su un'interfaccia utente commutata (che può essere tramite il Outlook componente aggiuntivo). | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| email | delegated | Indirizzo di posta elettronica | Nessuno, viene usato solo per associare un utente commutato all'identità AD | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| offline_access | delegated | N/D | N/D | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| openid | delegated | Autenticazione | Nessuno | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| profile | delegated | Identità | Nessuno | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Dati personali comuni (Indirizzo di posta elettronica principale, Indirizzo secondario in cui possono ricevere notifiche (facoltativo), Nome, Cognome ,numero di Telefono (facoltativo), Immagine del profilo (facoltativo), Lingua preferita, Indirizzo personale (facoltativo, può essere solo città),Dati di parcheggio (targhe), Dati di mobilità: (Passaggio del carpooling, Più spostamenti a casa, Departure-Return ore (facoltativo), Disponibilità dell'auto (facoltativo), Pendolari, Giorni fuori sede. Retention: on user request OR on end of contract with our client

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Ogni client di Commuty firma il nostro DPA ( https://dpa.commuty.net) , che include una breve visualizzazione su questo.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Commuty sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
