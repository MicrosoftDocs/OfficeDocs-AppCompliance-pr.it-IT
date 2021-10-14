---
title: Application Information for School Day Wellbeing by School Day Helsinki Oy
ms.author: elmalova
author: elenamalova
ms.date: 10/12/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per School Day Wellbeing, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9b953bd648ecc795e57e22dd505676d755b1ee32
ms.sourcegitcommit: d49943662d5e28a9c1289ee23318818f1f68ff96
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/14/2021
ms.locfileid: "60337909"
---
# <a name="school-day-wellbeing"></a>School Day Wellbeing

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: October 12, 2021</p>

* <a href="https://teams.microsoft.com/l/app/7caaa66b-34b0-4c15-a65d-dba6edf0c8fd" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001430" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da School Day Helsinki Oy a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | School Day Wellbeing |
| ID | WA200001430 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | School Day Helsinki Oy |
| URL del sito Web del partner | [https://www.schoolday.com](https://www.schoolday.com) |
| URL della Teams info dell'applicazione | [https://www.schoolday.com/en/resources/faq](https://www.schoolday.com/en/resources/faq) |
| URL dell'informativa sulla privacy | [https://www.schoolday.com/privacy](https://www.schoolday.com/privacy) |
| URL delle Condizioni per l'utilizzo | [https://www.schoolday.com/eula](https://www.schoolday.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da School Day Helsinki Oy su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| GroupMember.Read.All | delegated | Nome del gruppo e appartenenze ai gruppi. L'utente che è insegnante può aggiungere studenti al Giorno della scuola dai propri gruppi. | Nome del gruppo, membri del gruppo. Il gruppo in School Day può essere denominato in base al gruppo di O365. I membri del gruppo vengono aggiunti a questa classe come studenti. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| Team.ReadBasic.All | delegated | Il nome del team viene utilizzato quando l'utente docente vuole aggiungere studenti dai propri team e gruppi. | Il nome del team non viene archiviato in School Day. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| User.Read | delegated | La posta elettronica, il nome e il token ID utente vengono usati per la gestione e l'autenticazione degli utenti. | La posta elettronica, il nome e il token dell'utente vengono archiviati a scopo di gestione e autenticazione degli utenti. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| User.ReadBasic.All | delegated | Immagini del profilo utente da utilizzare negli avatar degli utenti. | L'immagine del profilo utente non viene archiviata. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| email | delegated | La posta elettronica dell'utente viene raccolta per l'autenticazione dell'account. | La posta elettronica dell'utente viene archiviata a scopo di creazione e/o autenticazione dell'account. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| offline_access | delegated | Autenticazione: aggiornamento del token di accesso. Esperienza utente più fluida. | Token di accesso per l'autenticazione. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| openid | delegated | Identificatore univoco dell'utente per l'accesso OpenID.  | L'identificatore univoco dell'utente viene archiviato ai fini dell'autenticazione. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| profile | delegated | Nome utente e ID oggetto preferiti per la gestione degli utenti e l'autenticazione. | ID oggetto per la gestione degli utenti e l'autenticazione. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Strumento di lettura immersiva | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Account utente, gruppi a cui appartiene l'utente, benessere dei dati di risposta alle domande. Dopo l'eliminazione dell'account, i dati vengono rimossi entro 90 giorni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>L'amministratore dell'organizzazione può controllare i dati (CRUD) tramite gli strumenti di amministrazione di School Day. 

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

Queste informazioni sono state fornite da School Day Helsinki Oy su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

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
