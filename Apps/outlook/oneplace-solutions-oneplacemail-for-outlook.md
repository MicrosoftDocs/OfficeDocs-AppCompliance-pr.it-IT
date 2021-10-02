---
title: Informazioni sull'applicazione per OnePlaceMail per Outlook soluzioni OnePlace
ms.author: elmalova
author: elenamalova
ms.date: 09/30/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per OnePlaceMail per Outlook, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 196720a00525971f29618d48436cf11b37a3aaac
ms.sourcegitcommit: 874e586a5a9a5eb0c5c5aae0c59f7c75c0742ec4
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/01/2021
ms.locfileid: "60080647"
---
# <a name="oneplacemail-for-outlook"></a>OnePlaceMail per Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 30, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380723" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da OnePlace Solutions a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | OnePlaceMail per Outlook |
| ID | WA104380723 |
| Office 365 client supportati | Outlook 2013 o versioni successive su Windows, Outlook 2016 o versioni successive su Mac, Outlook su iOS, Outlook su Android, Outlook sul web |
| Nome società partner | Soluzioni OnePlace |
| URL del sito Web del partner | [https://www.oneplacesolutions.com](https://www.oneplacesolutions.com) |
| URL dell'informativa sulla privacy | [https://www.oneplacesolutions.com/oneplacemailapp-privacy](https://www.oneplacesolutions.com/oneplacemailapp-privacy) |
| URL delle Condizioni per l'utilizzo | [https://www.oneplacesolutions.com/eula.html](https://www.oneplacesolutions.com/eula.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da OnePlace Solutions sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | delegated | Necessario per determinare Teams di cui l'utente corrente è membro. | Nessuno | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| Mail.ReadWrite.Shared | delegated | Necessario per accedere alle proprietà della posta per impostare SharePoint colonne e aggiungere la categoria Trasferito a SharePoint sull'elemento di posta | Nessuno | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| MailboxSettings.ReadWrite | delegated | Nessun dato raccolto o utilizzato, viene utilizzato per aggiungere una categoria all'elenco delle categorie principali in una cassetta postale degli utenti | Nessuno | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| Sites.ReadWrite.All | delegated | Obbligatorio per impostare le proprietà per gli elementi caricati dall'app SharePoint. | Nessuno | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.Read | delegated | Obbligatorio per l'autenticazione a Microsoft Graph. | I dati seguenti vengono archiviati dall'app in un database e vengono usati per la registrazione delle licenze utente e di sottoscrizione: ID utente, e-mail, nome, cognome. | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadBasic.All | delegated | Obbligatorio per visualizzare l'immagine del profilo utente nel campo selezione utenti. | Nessuno | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadBasic.All | delegated | Obbligatorio per visualizzare l'immagine del profilo utente nel campo selezione utenti. | Nessuno | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadWrite.All | delegated | Necessario per determinare se il servizio Teams è abilitato all'interno degli utenti Office 365 tenancy. | Nessuno | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint | Sì | SharePoint URL, nomi di raccolta/elenco/cartella | Le informazioni organizzative a cui si accede da vengono utilizzate per facilitare il processo di salvataggio di posta elettronica e allegati da Exchange a SharePoint. Questi dati aggiuntivi non vengono archiviati in pausa e vengono crittografati in transito. Esempi di questi dati includono SharePoint colonna, ad esempio i valori delle colonne Choice, i valori di tassonomia, i nomi dei tipi di contenuto, i nomi delle cartelle, i nomi dei siti.  | Anche se questi dati non vengono archiviati o raccolti dall'app, è possibile che vengano visualizzati in telemetria/log in cui vengono conservati per 90 giorni. | I dati non vengono archiviati |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Il servizio Di ricarica viene utilizzato per la gestione e la fatturazione delle sottoscrizioni. Per la creazione dell'abbonamento in-app (gratuito) il nome, cognome, indirizzo e-mail dell'utente sono condivisi con Chargify. Per le sottoscrizioni acquistate (che supportano più utenti con licenza) i dettagli dei singoli utenti non vengono condivisi con il servizio Chargify. | Indirizzo di posta elettronica | Per comunicare gli eventi del ciclo di vita della sottoscrizione all'utente |



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>EUII e OII vengono visualizzati nella telemetria. Queste informazioni vengono archiviate in Application Insights, crittografate in pausa, controllate ed eliminate dopo 90 giorni

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati archiviati nell'applicazione vengono crittografati in transito e in pausa. Ci affidiamo Office 365 credenziali per le nostre app, quindi non archiviamo le password degli utenti nel nostro sistema. L'accesso ai dati/log/telemetria archiviati è strettamente controllato dal personale dell'amministrazione interna con la necessità di accedere alle informazioni allo scopo di eseguire e monitorare l'integrità dell'app. Two-Factor l'autenticazione applicata a tutto il personale dell'amministrazione interna.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalogo vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da OnePlace Solutions sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

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
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
