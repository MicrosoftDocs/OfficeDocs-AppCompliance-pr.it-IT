---
title: Informazioni sull'applicazione per le segnalazioni dei dipendenti da Recruitday Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per le segnalazioni dei dipendenti, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 3f169a817828d56501225bd8a92752ec7f799771
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428983"
---
# <a name="employee-referrals"></a>Referenze dipendenti

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 3, 2021</p>

* <a href="https://teams.microsoft.com/l/app/c179cdf6-f93d-4aa3-9e2d-e934e5a81846" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002708" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Recruitday Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Referenze dipendenti |
| ID | WA200002708 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Recruitday Inc. |
| URL del sito Web del partner | [https://www.recruitday.com](https://www.recruitday.com) |
| URL della Teams info dell'applicazione | [https://employer.recruitday.com/solutions/employee-referral...](https://employer.recruitday.com/solutions/employee-referrals/microsoft-teams) |
| URL dell'informativa sulla privacy | [https://www.recruitday.com/privacy-policy](https://www.recruitday.com/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://www.recruitday.com/terms-of-use](https://www.recruitday.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Recruitday Inc. Su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | entrambi | Il nome e il cognome (dell'utente dell'app, ad esempio il dipendente) verranno utilizzati principalmente dall'utente HR per identificare facilmente il dipendente che ha fatto riferimento a un candidato per il monitoraggio delle applicazioni di riferimento e i premi. Verrà inoltre usato per affrontare correttamente il dipendente quando vengono inviate notifiche di posta elettronica generate dal sistema. | Il nome e il cognome (dell'utente dell'app, ad esempio il dipendente) verranno utilizzati principalmente dall'utente HR per identificare facilmente il dipendente che ha fatto riferimento a un candidato per il monitoraggio delle applicazioni di riferimento e i premi. Verrà inoltre usato per affrontare correttamente il dipendente quando vengono inviate notifiche di posta elettronica generate dal sistema. | [7414b436-87d1-4904-9d52-ff47885b89f1](https://docs.microsoft.com/microsoft-365-app-certification/azure/7414b436-87d1-4904-9d52-ff47885b89f1) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 1. Per essere elaborato da Recruitday per i seguenti scopi: 1.1. Creare l'account dipendente 1.2. Invia notifiche generate dal sistema relative a transazioni e promemoria 2. Per l'elaborazione da parte dell'organizzazione dell'utente per i seguenti scopi: 2.1. Identificare l'origine di un riferimento 2.2. Determinare a chi verrà assegnato il riconoscimento di segnalazione per la corretta segnalazione 2.3. Determinare quali dipendenti non potranno accedere al sistema (ad esempio, bloccare l'accesso) | Nome, Cognome, Indirizzo di posta elettronica | 1. Per essere elaborato da Recruitday per i seguenti scopi: 1.1. Creare l'account dipendente 1.2. Invia notifiche generate dal sistema relative a transazioni e promemoria 2. Per l'elaborazione da parte dell'organizzazione dell'utente per i seguenti scopi: 2.1. Identificare l'origine di un riferimento 2.2. Determinare a chi verrà assegnato il riconoscimento di segnalazione per la corretta segnalazione 2.3. Determinare quali dipendenti non potranno accedere al sistema (ad esempio, bloccare l'accesso) |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>L'amministratore può archiviare i dati dell'utente tramite il portale. Altre funzioni come delete, update e così via verranno eseguite tramite richiesta a Recruitday.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Recruitday Inc. Su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | No |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
