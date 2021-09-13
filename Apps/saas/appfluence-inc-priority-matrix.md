---
title: Informazioni sull'applicazione per Priority Matrix di Appfluence Inc
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni di sicurezza e conformità disponibili per Priority Matrix, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 145ad1b57c9ad1ee705014c1e098f2f6ffdd9800
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59280027"
---
# <a name="priority-matrix"></a>Priority Matrix

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: June 23, 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/appfluenceinc.m_pm_msft" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Appfluence Inc a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Priority Matrix |
| ID | appfluenceinc.m_pm_msft |
| Nome società partner | Appfluence Inc |
| URL del sito Web del partner | [https://appfluence.com/office-365-project-management-integr...](https://appfluence.com/office-365-project-management-integration/) |
| URL dell'informativa sulla privacy | [https://appfluence.com/privacy](https://appfluence.com/privacy) |
| URL delle Condizioni per l'utilizzo | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Appfluence Inc su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegated | Solo quando viene aggiunto un nuovo utente all'account, vengono archiviati i messaggi di posta elettronica. | Durante la creazione di un nuovo account, viene utilizzato per suggerire altri membri del team. | [5be2b320-a5b7-4221-893c-dee506e4e365](https://docs.microsoft.com/microsoft-365-app-certification/azure/5be2b320-a5b7-4221-893c-dee506e4e365) |
>| User.ReadBasic.All | delegated | Solo quando viene aggiunto un nuovo utente all'account, vengono archiviati i messaggi di posta elettronica. | Durante la creazione di un nuovo account, viene utilizzato per suggerire altri membri del team. | [5be2b320-a5b7-4221-893c-dee506e4e365](https://docs.microsoft.com/microsoft-365-app-certification/azure/5be2b320-a5b7-4221-893c-dee506e4e365) |
>| offline_access | delegated | Archiviamo il token di accesso per eseguire richieste per conto dell'utente | Aggiorna token senza disturbare l'utente. (Matrice di priorità per Teams) | [5be2b320-a5b7-4221-893c-dee506e4e365](https://docs.microsoft.com/microsoft-365-app-certification/azure/5be2b320-a5b7-4221-893c-dee506e4e365) |
>| Files.Read.All | delegated | Non vengono archiviate informazioni sui file, a meno che l'utente non crei esplicitamente e consapevolmente un elemento priority matrix che si collega al file originale. | Nella funzionalità One-on-One (disponibile tramite l'app Web e anche i componenti aggiuntivi Outlook/Teams), usiamo questa funzionalità per evidenziare i file SharePoint/OneDrive condivisi tra due utenti del sistema, per facilitare le riunioni e la collaborazione complessiva. | [affadfb6-f17b-428f-97f9-9aae3b6175bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/affadfb6-f17b-428f-97f9-9aae3b6175bc) |
>| User.Read | delegated | Le informazioni di base del profilo utente (nome visualizzato, nome, cognome, e-mail, avatar) vengono archiviate da Microsoft. | Ottieni il nome, l'indirizzo di posta elettronica, l'avatar dell'utente per personalizzare il proprio account con noi. | [affadfb6-f17b-428f-97f9-9aae3b6175bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/affadfb6-f17b-428f-97f9-9aae3b6175bc) |
>| openid | delegated | La connessione SSO viene archiviata per indicare la modalità di accesso per l'utente. | Per accedere agli utenti tramite single sign-on. | [affadfb6-f17b-428f-97f9-9aae3b6175bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/affadfb6-f17b-428f-97f9-9aae3b6175bc) |
>| Calendars.Read | delegated | Un numero limitato di eventi di calendario viene trasformato in attività archiviate nel sistema. | Leggere gli eventi del calendario in modo che possano essere visualizzati nella visualizzazione 1:1. Anche per inizializzare nuovi account. | [d76f016f-52c7-41b5-835b-900361d7040c](https://docs.microsoft.com/microsoft-365-app-certification/azure/d76f016f-52c7-41b5-835b-900361d7040c) |
>| Mail.Read | delegated | Le attività create nel sistema vengono archiviate con un collegamento al messaggio originale. | Usato nel nostro Outlook componente aggiuntivo per trasformare i messaggi di posta elettronica in attività e per visualizzare il lavoro condiviso in visualizzazione 1:1. | [d76f016f-52c7-41b5-835b-900361d7040c](https://docs.microsoft.com/microsoft-365-app-certification/azure/d76f016f-52c7-41b5-835b-900361d7040c) |
>| Tasks.Read | delegated | Alcune Outlook/Planner vengono replicate nel sistema per aiutare i nuovi utenti. | I nuovi account utente vengono bootstrap con le Graph attività. | [d76f016f-52c7-41b5-835b-900361d7040c](https://docs.microsoft.com/microsoft-365-app-certification/azure/d76f016f-52c7-41b5-835b-900361d7040c) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì, il messaggio di posta elettronica dell'utente viene utilizzato come ID univoco nel sistema e usato per tenere traccia degli errori delle applicazioni e per tenere traccia degli eventi chiave nel sistema (download, accesso, versioni dell'applicazione e così via) in modo che il team del servizio clienti possa fornire una risposta rapida alle richieste dei clienti. Come parte della conformità al GDPR, eliminiamo tutti i dati dei clienti entro 2 settimane da una richiesta di eliminazione, anche se in pratica lo facciamo lo stesso giorno, poiché abbiamo script interni per eseguire questa operazione in modo semiautomo.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati dell'applicazione vengono archiviati in modo sicuro in un database crittografato con accesso limitato a un piccolo gruppo di amministratori. Per proteggere ulteriormente l'accesso, viene applicata l'autenticazione a 2 fattori, si limita l'accesso a un set controllato di indirizzi IP e si individua il database nella propria subnet privata, direttamente inaccessibile da Internet aperto.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalogo vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Appfluence Inc su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/><br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
