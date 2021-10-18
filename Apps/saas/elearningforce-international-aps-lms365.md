---
title: Informazioni sull'applicazione per LMS365 di ELEARNINGFORCE International Aps
ms.author: elmalova
author: elenamalova
ms.date: 08/03/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni di sicurezza e conformità disponibili per LMS365, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a580699104f234a96cd57fb5641e8e2b0d947255
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428429"
---
# <a name="lms365"></a>LMS365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: July 28, 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/elearningforce.lms365_spfx" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da ELEARNINGFORCE International Aps a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | LMS365 |
| ID | elearningforce.lms365_spfx |
| Nome società partner | ELEARNINGFORCE International Aps |
| URL del sito Web del partner | [https://www.elearningforce.com](https://www.elearningforce.com) |
| URL dell'informativa sulla privacy | [https://www.lms365.com/privacy](https://www.lms365.com/privacy) |
| URL delle Condizioni per l'utilizzo | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da ELEARNINGFORCE International Aps su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| GroupMember.Read.All | application | Nessuno | Consente all'app di espandere i membri del gruppo AD, che è necessario registrare ai corsi. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| Mail.Send | delegated | Nessuno | L'autorizzazione viene richiesta in modo dinamico durante la configurazione dell'account di posta elettronica per la notifica. Consente all'app di inviare messaggi di posta elettronica di notifica | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| RoleManagement.Read.Directory | application | Nessuno | Consente all'app di ottenere SharePoint dominio durante il provisioning del tenant. Il dominio viene utilizzato per la creazione di URL. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| User.Invite.All | delegated | Nessuno | Consente all'app di invitare utenti esterni per conto dell'utente attualmente connesso | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| User.Read | delegated | Nessuno | Accedere e leggere il profilo utente. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| User.Read.All | delegated | Nessuno | Consente all'app di leggere il profilo completo dell'utente attualmente connesso. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| User.Read.All | application | Consente all'app di leggere il profilo utente completo. È&#8217;necessario leggere gli utenti&#8217; manager per creare report di gerarchia. | I dati personali seguenti vengono archiviati in un database dedicato per il rispettivo cliente utilizzato per la funzionalità dashboard di Learner Management &amp; Manager all'interno dell'applicazione. Account Name, User Display Name, Email Address, Department, Job Title, Office, Country, City, Manager ID/Email | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| profile | delegated | Nessuno | Visualizzare il profilo di base dell'utente. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì, usiamo i Insights log di telemetria/log di Log Analytics che vengono usati solo per la risoluzione dei problemi e hanno un criterio di conservazione di 90 giorni dopo il quale tutti i dati vengono eliminati.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>LMS365 è dotato di una funzione di eliminazione che rimuoverà i dati personali dai client LMS365 Database.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da ELEARNINGFORCE International Aps sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Piattaforme dei dispositivi, stato del dispositivo, app client |
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
