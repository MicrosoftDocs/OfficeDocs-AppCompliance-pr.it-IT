---
title: Informazioni sulla domanda di lavoro | Procedura guidata per Office per ufficioa lavoro
ms.author: elmalova
author: elenamalova
ms.date: 12/08/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per gli uffici al | Procedura guidata per Office, i relativi criteri di gestione dei dati, le relative informazioni Microsoft Cloud App Security catalogo delle app e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: da73df8e4d8c4b22d5aa042dafcadfa72e885ef4
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552597"
---
# <a name="officeatwork--wizard-for-office"></a>ufficial lavoro | Procedura guidata per Office

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Ultimo aggiornamento da parte dello sviluppatore: 8 dicembre 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380519" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da officeatwork a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | officeatwork - Procedura guidata per Office |
| ID | WA104380519 |
| Office 365 client supportati | Word 2016 o versioni successive su Mac, Word 2016 o versioni successive Windows, Word su iPad, Word sul web |
| Nome della società partner | officeatwork |
| URL del sito Web partner | [https://links.officeatwork.com/officeatwork-home](https://links.officeatwork.com/officeatwork-home) |
| URL dell'Informativa sulla privacy | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| URL delle Condizioni d'uso | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da officeatwork su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Contatti.Lettura | delegato | Non vengono memorizzati dati. | Contatti: per consentire la lettura di tutti i contatti dell'utente che ha effettuato l'accesso. | 0c67871C-FFBC-4B37-BD61-AFCE12B299F9 |
>| Files.Read | delegato | Non vengono memorizzati dati. | OneDrive - File (Contenuto): per consentire la lettura dei file dell'utente che ha effettuato l'accesso. | 0c67871C-FFBC-4B37-BD61-AFCE12B299F9 |
>| Files.Read.All | delegato | Non vengono memorizzati dati. | Teams - File (Contenuto): per consentire la lettura di tutti i file dell'utente che ha effettuato l'accesso. | 0c67871C-FFBC-4B37-BD61-AFCE12B299F9 |
>| Group.Read.All | delegato | Non vengono memorizzati dati. | Office 365 Utenti - Limita al gruppo: per abilitare la lettura di tutti i gruppi dell'utente che ha effettuato l'accesso. | 0c67871C-FFBC-4B37-BD61-AFCE12B299F9 |
>| Sites.Read.All | delegato | Non vengono memorizzati dati. | SharePoint Online: per abilitare la lettura dei dati da SharePoint Online. | 0c67871C-FFBC-4B37-BD61-AFCE12B299F9 |
>| User.Read | delegato | Non vengono memorizzati dati. | Sing-In: per consentire all'app officeatwork di leggere le proprietà di base dell'utente. | 0c67871C-FFBC-4B37-BD61-AFCE12B299F9 |
>| User.Read.All | delegato | Non vengono memorizzati dati. | Office 365 Utenti - Tutte le proprietà: per abilitare la lettura di tutte le proprietà di tutti gli utenti. | 0c67871C-FFBC-4B37-BD61-AFCE12B299F9 |
>| User.ReadBasic.All | delegato | Non vengono memorizzati dati. | Office 365 Utenti - Proprietà di base: per consentire la lettura delle proprietà di base di tutti gli utenti | 0c67871C-FFBC-4B37-BD61-AFCE12B299F9 |
>| offline_access | delegato | Non vengono memorizzati dati. | Sing-In: per abilitare l'accesso automatico tramite token di aggiornamento, come senza, gli utenti dovrebbero accedere manualmente ogni volta che avviano l'app officeatwork. Questo ambito è necessario solo per le applicazioni host non abilitate per SSO. | 0c67871C-FFBC-4B37-BD61-AFCE12B299F9 |
>| openid | delegato | Non vengono memorizzati dati. | Sing-In: per consentire agli utenti di accedere all'app officeatwork con il proprio account organizzativo e/o Microsoft | 0c67871C-FFBC-4B37-BD61-AFCE12B299F9 |
>| profilo | delegato | Non vengono memorizzati dati. | Sing-In: per mostrare l'utente che ha effettuato l'accesso nell'app officeatwork. Ciò consente di assicurare/confermare all'utente l'account utilizzato per accedere all'app officeatwork. | 0c67871C-FFBC-4B37-BD61-AFCE12B299F9 |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati tramite altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono utilizzare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni di identificazione dell'organizzazione ( OII). Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **OII viene raccolto?** |  **Quale OII viene raccolto?** | **Giustificazione per la raccolta di OII?** | **OII è memorizzato?** | **Giustificazione per l'archiviazione di OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API REST di SharePoint | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì, gli eventi includono l'oid e il tenantId e vengono inviati ad AppInsights di Azure. Gli eventi vengono eliminati automaticamente dopo 90 giorni. Se un cliente desidera che questi dati siano cancellati, può utilizzare il link fornito nell'informativa sulla privacy per avviare la cancellazione di tali dati.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>I dati delle impostazioni delle applicazioni (flag di funzionalità, nome visualizzato dell'organizzazione, ID tenant, elenco di amministratori oidi) vengono archiviati in un'istanza di Azure Cosmos DB (un file per tenant). I file DB sono crittografati e l'accesso è limitato a tecnici officeatwork selezionati e personale di supporto. Il cliente può accedere e modificare i dati delle impostazioni dell'app officeatwork utilizzando l'interfaccia di amministrazione Web App.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35749' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35749" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da officeatwork su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Ti integri con Microsoft Identify Platform (Azure AD)?  | Sì |
| Hai esaminato e rispettato tutte le best practice applicabili descritte nell'elenco di controllo Microsoft Identity Platform integrazione?  | Sì |
| La tua app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Impostazioni predefinite per la sicurezza |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate staticamente dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | No |
| La tua app supporta la multi-tenancy? | Sì |
| La tua app ha un client riservato? | Sì |
| Possiedi tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa eviti di usare? | - Gli URI di reindirizzamento dei caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una SPA<br/>- Flusso ROPC (Resource Owner Password Credential) |
| La tua app espone api Web? | No |
| La tua app usa le API di anteprima? | No |
| La tua app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
