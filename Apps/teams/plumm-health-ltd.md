---
title: Application Information for Plumm by Plumm Health LTD
ms.author: elmalova
author: elenamalova
ms.date: 08/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Prudenza, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 0ecc8063bb993d681ec98a3750ada9afb63bdb81
ms.sourcegitcommit: d67be08c82a50cc263a4bdeb176f41dd60716159
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/15/2021
ms.locfileid: "60378642"
---
# <a name="plumm"></a>Prugna

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 18, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d66da813-3337-4f88-8e08-f01c0bbb8f34" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003326" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Plumm Health LTD a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Prugna |
| ID | WA200003326 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Plumm Health LTD |
| URL del sito Web del partner | [https://www.plummhealth.com](https://www.plummhealth.com) |
| URL della Teams info dell'applicazione | [https://www.plummhealth.com/about-us](https://www.plummhealth.com/about-us) |
| URL dell'informativa sulla privacy | [https://www.plummhealth.com/privacy-policy](https://www.plummhealth.com/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://www.plummhealth.com/terms-of-use](https://www.plummhealth.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Plumm Health LTD su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsActivity.Send | application | Usiamo l'ID utente in questa autorizzazione. Viene usato per l'invio di notifiche richieste all'utente in base all'utilizzo del servizio. Questo è importante per consentire all'utente di ricevere notifiche appropriate per il proprio account nell'app. | In questa autorizzazione non vengono archiviati dati nel database. In realtà, l'ID utente viene utilizzato per inviare una notifica appropriata a ogni singolo utente in base all'utilizzo. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| TeamsAppInstallation.ReadWriteForUser.All | application | L'ID di installazione viene ricevuto utilizzando questa autorizzazione. Questo è importante per essere in grado di inviare la notifica appropriata e corretta per ogni singolo utente. | Non archiviamo dati nella nostra app usando questa autorizzazione. Non è necessario perché è necessario solo l'ID di installazione che viene ottenuto in fase di esecuzione fornendo l'ID utente. Questa operazione viene ottenuta in modo dinamico in fase di esecuzione, pertanto non è necessario archiviare l'ID di installazione. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read | delegated | Stiamo raccogliendo nome, immagine e posta elettronica per i nostri utenti tramite questa autorizzazione. Questo è necessario per consentire a Microsoft di identificare singoli utenti e questi punti dati verranno visualizzati ovunque sia necessario, ad esempio la pagina del profilo individuale e la comunicazione e-mail/notifica. | Queste autorizzazioni consentono all'app di visualizzare il profilo di base degli utenti (nome, immagine, posta elettronica). Questi dati verranno usati per visualizzare il nome e/o l'immagine del profilo dell'utente nell'account dell'app insieme a microsoft e per le comunicazioni e/o le notifiche tramite posta elettronica. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read.All | application | Questa autorizzazione consente all'app di leggere i profili utente senza un utente connesso. In questo momento stiamo raccogliendo solo nome, immagine del profilo e posta elettronica. Questo è necessario per consentire a Microsoft di identificare singoli utenti e questi punti dati verranno visualizzati ovunque sia necessario, ad esempio la pagina del profilo individuale e la comunicazione e-mail/notifica. | Queste autorizzazioni consentono all'app di visualizzare il profilo di base degli utenti (nome, immagine, posta elettronica). Questi dati verranno usati per visualizzare il nome e/o l'immagine del profilo dell'utente nell'account dell'app insieme a microsoft e per le comunicazioni e/o le notifiche tramite posta elettronica. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| email | delegated | Viene raccolto l'ID di posta elettronica dell'utente. Richiediamo questi dati per concedere l'accesso all'utente per i nostri servizi e accedere alla nostra app e ricevere notifiche relative ai loro account e ai nostri servizi su questo ID di posta elettronica.  | L'ID di posta elettronica viene archiviato nel database. Dobbiamo archiviare l'ID di posta elettronica per identificare in modo univoco gli utenti, fornire loro l'accesso alla nostra app, aiutarli ad accedere e aiutarli a ricevere notifiche sul loro account con noi. Ad esempio, un utente con ID abc@xyz.com di posta elettronica potrà accedere all'app e ai servizi quando esegue l'accesso a Teams &quot; con questo ID di posta &quot; elettronica. In base all'utilizzo, saremo in grado di inviare notifiche a questo utente sul suo ID di posta elettronica. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| openid | delegated | Per questa autorizzazione, non vengono raccolti dati.  | Per questa autorizzazione, non vengono raccolti dati. Questa autorizzazione consente agli utenti di accedere alla nostra app con l'ID di posta elettronica aziendale e consente all'app di visualizzare le informazioni di base del profilo utente. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| profile | delegated | Stiamo raccogliendo nome, immagine e posta elettronica per i nostri utenti tramite questa autorizzazione. Questo è necessario per consentire a Microsoft di identificare singoli utenti e questi punti dati verranno visualizzati ovunque sia necessario, ad esempio la pagina del profilo individuale e la comunicazione e-mail/notifica. | Queste autorizzazioni consentono all'app di visualizzare il profilo di base degli utenti (nome, immagine, posta elettronica). Questi dati verranno usati per visualizzare il nome e/o l'immagine del profilo dell'utente nell'account dell'app insieme a microsoft e per le comunicazioni e/o le notifiche tramite posta elettronica. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Intercom | Nome, Cognome, Posta elettronica | Intercom è il nostro CRM che ci aiuta a gestire le comunicazioni con tutti i nostri utenti. Ecco perché è necessario inviare il nome, il cognome e l'ID di posta elettronica degli utenti al CRM in modo che i messaggi o i messaggi di posta elettronica appropriati possano essere inviati agli utenti. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Vengono archiviati i dati di utilizzo del servizio, ad esempio il numero di sessioni di terapia utilizzate, i corsi visualizzati, le sessioni visualizzate, la data delle sessioni e così via. Conserviamo i dati per i nostri utenti fino a quando l'utente non chiede esplicitamente che il suo account sia eliminato o "dimenticato".

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Microsoft gestisce i dati inviati al CRM tramite il server. I dati minimi necessari per il funzionamento vengono passati al CRM (Intercom). Plumm mantiene il controllo completo sui dati passati al CRM, sulla conservazione dei dati su Intercom e sull'eliminazione. Ecco un collegamento per esaminare i criteri dei dati dei clienti di Intercom: https://www.intercom.com/legal/terms-and-policies#customer-data

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Plumm Health LTD su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | No |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | ,<br/><br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
