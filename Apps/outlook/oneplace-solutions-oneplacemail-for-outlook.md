---
title: Informazioni sull'applicazione per OnePlaceMail per Outlook da OnePlace Solutions
ms.author: elmalova
author: elenamalova
ms.date: 01/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per OnePlaceMail per Outlook, i relativi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5094d1ad5e7b028ac115529de16ddb9cbef2086f
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552497"
---
# <a name="oneplacemail-for-outlook"></a>OnePlaceMail per Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 31 gennaio 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380723" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da OnePlace Solutions a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | OnePlaceMail per Outlook |
| ID | WA104380723 |
| Office 365 client supportati | Outlook 2013 o versioni successive su Windows, Outlook 2016 o versioni successive su Mac, Outlook su iOS, Outlook su Android, Outlook sul Web |
| Nome della società partner | Soluzioni OnePlace |
| URL del sito Web partner | [https://www.oneplacesolutions.com/](https://www.oneplacesolutions.com/) |
| URL dell'Informativa sulla privacy | [https://www.oneplacesolutions.com/oneplacemailapp-privacy](https://www.oneplacesolutions.com/oneplacemailapp-privacy) |
| URL delle Condizioni d'uso | [https://www.oneplacesolutions.com/oneplacemailapp-eula](https://www.oneplacesolutions.com/oneplacemailapp-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da OnePlace Solutions su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | delegato | Necessario per determinare Teams l'utente corrente è membro di. | Nessuno | 44a72516-136f-4a55-ae26-ef09977230be |
>| Mail.ReadWrite.Shared | delegato | Necessario per accedere alle proprietà di posta elettronica per SharePoint colonne e aggiungere la categoria SharePoint all'elemento di posta | Nessuno | 44a72516-136f-4a55-ae26-ef09977230be |
>| MailboxSettings.ReadWrite | delegato | Nessun dato raccolto o utilizzato, viene utilizzato per aggiungere una categoria all'elenco delle categorie master in una cassetta postale degli utenti | Nessuno | 44a72516-136f-4a55-ae26-ef09977230be |
>| Sites.ReadWrite.All | delegato | Necessario per impostare le proprietà sugli elementi caricati dall'app SharePoint. | Nessuno | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.Read | delegato | Necessario per l'autenticazione al Graph Microsoft. | I dati seguenti vengono archiviati dall'app in un database e vengono utilizzati per il monitoraggio delle licenze di sottoscrizione e utente: ID utente, E-mail, Nome, Cognome. | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadBasic.All | delegato | Necessario per visualizzare l'immagine del profilo utente nel campo selezione utenti. | Nessuno | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadBasic.All | delegato | Necessario per visualizzare l'immagine del profilo utente nel campo selezione utenti. | Nessuno | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadWrite.All | delegato | Necessario per determinare se il servizio Teams è abilitato all'interno degli utenti Office 365 locazione. | Nessuno | 44a72516-136f-4a55-ae26-ef09977230be |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati tramite altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono utilizzare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni di identificazione dell'organizzazione ( OII). Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **OII viene raccolto?** |  **Quale OII viene raccolto?** | **Giustificazione per la raccolta di OII?** | **OII è memorizzato?** | **Giustificazione per l'archiviazione di OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | Sì | SharePoint URL, nomi di raccolta/elenco/cartella | Le informazioni organizzative a cui si accede vengono utilizzate per facilitare il processo di salvataggio di e-mail e allegati da Exchange a SharePoint. Questi dati aggiuntivi non vengono memorizzati a riposo e sono crittografati in transito. Esempi di questi dati includono SharePoint di colonna, ad esempio valori di colonna Scelta, valori tassonomia, nomi dei tipi di contenuto, nomi di cartelle, nomi di siti.  | Sebbene questi dati non siano archiviati o raccolti dall'app, potrebbero essere visualizzati nei registri/telemetria in cui vengono conservati per 90 giorni. | I dati non vengono archiviati |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft non sono trasferiti** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Il servizio Chargify viene utilizzato per la gestione e la fatturazione degli abbonamenti. Per la creazione di abbonamenti in-app (gratuiti) il nome, il cognome, l'indirizzo e-mail dell'utente vengono condivisi con Chargify. Per le sottoscrizioni acquistate (che supportano più utenti con licenza) i singoli dettagli utente non vengono condivisi con il servizio Chargify. | Indirizzo di posta elettronica | Per poter comunicare eventi del ciclo di vita della sottoscrizione all'utente |



#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>L'III e l'OII vengono visualizzati nella telemetria. Queste informazioni sono memorizzate in Application Insights, crittografate a riposo, controllate dall'accesso ed eliminate dopo 90 giorni

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>I dati memorizzati nell'applicazione vengono crittografati in transito e a riposo. Ci affidiamo Office 365 credenziali per le nostre app, quindi non archiviamo le password degli utenti nel nostro sistema. L'accesso ai dati/registri/telemetria archiviati è strettamente controllato dal personale dell'amministrazione interna con la necessità di accedere alle informazioni allo scopo di eseguire e monitorare lo stato dell'app. Two-Factor autenticazione applicata a tutto il personale amministrativo interno.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da OnePlace Solutions su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Ti integri con Microsoft Identify Platform (Azure AD)?  | Sì |
| Hai esaminato e rispettato tutte le best practice applicabili descritte nell'elenco di controllo Microsoft Identity Platform integrazione?  | Sì |
| La tua app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate staticamente dell'app riflettono accuratamente le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| La tua app supporta la multi-tenancy? | Sì |
| La tua app ha un client riservato? | Sì |
| Possiedi tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa eviti di usare? | - Gli URI di reindirizzamento dei caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una SPA<br/>- Flusso ROPC (Resource Owner Password Credential) |
| La tua app espone api Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso corretto? | Sì |
| La tua app usa le API di anteprima? | No |
| La tua app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
