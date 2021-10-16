---
title: Informazioni sull'applicazione Power BI collaborazione di Ataira
ms.author: elmalova
author: elenamalova
ms.date: 07/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per Power BI Collaboration, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 2e015b1596c02f6841609f1dba61577f25c738e4
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411915"
---
# <a name="power-bi-collaboration"></a>Opzioni di collaborazione di Power BI

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 14, 2021</p>

* <a href="https://teams.microsoft.com/l/app/90381cb0-998f-4ba3-9699-130201de5ddb" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381384" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Ataira a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Opzioni di collaborazione di Power BI |
| ID | WA104381384 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Ataira |
| URL del sito Web del partner | [https://www.ataira.com](https://www.ataira.com) |
| URL della Teams info dell'applicazione | [https://www.ataira.com/Microsoft/PowerBI/Collaboration](https://www.ataira.com/Microsoft/PowerBI/Collaboration) |
| URL dell'informativa sulla privacy | [https://www.ataira.com/PrivacyPolicy](https://www.ataira.com/PrivacyPolicy) |
| URL delle Condizioni per l'utilizzo | [https://www.ataira.com/TermsofUse](https://www.ataira.com/TermsofUse) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Ataira su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegated | Autorizzazioni anche per ChannelMessage.Send Team.ReadBasic.All User.Read. Vengono usati per consentire all'utente di selezionare il Teams e il canale per le notifiche | Monitoraggio dell'utilizzo, degli errori e delle licenze. [callback_group_id] ,[datetime_id] ,[session_id] ,[app_type] ,[raw_url] ,[user_id] ,[list_name] ,[user_name] ,[state] ,[priority] ,[user_domain] ,[url_text ,[group_name] ,[title_name] ,[comments] ,[file_name] ,[description] ,[group_pbi_name] ,[item_type] ,[organization_id] ,[user_objectid] ,[organization_displayName] ,[group_id] | [00738e07-f9a4-4bf5-b6f9-851ec7ea31d5](https://docs.microsoft.com/microsoft-365-app-certification/azure/00738e07-f9a4-4bf5-b6f9-851ec7ea31d5) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| https://analysis.windows.net/powerbi/api/ | Sì | posta elettronica utente, nome area di lavoro, nome elemento, url di incorporamento | Usato per popolare report e dashboard nell'interfaccia SharePoint componente aggiuntivo | [api_pbi_id] ,[datetime_id] ,[session_id] ,[user_name] ,[user_domain] ,[WorkSpace_Name] ,[WorkSpace_Id] ,[item_Id] ,[item_type] ,[item_name] ,[webUrl] ,[embedUrl] ,[displayName] ,[item_title] ,[isOwnedByMe] | Monitoraggio di utilizzo, errori e licenze |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Meta dati necessari per popolare Power BI report e dashboard, autenticazione Graph Teams API. Altri criteri relativi a dati e privacy sono disponibili sul sito Web. https://www.ataira.com/PrivacyPolicy E poi anche nella pagina di configurazione dell'app in modo specifico per la privacy dei dati. https://www.ataira.com/Microsoft/PowerBI/CollaborationSupport

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>N/D

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/41844' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/41844" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Ataira sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Autenticazione a più fattori Che consente solo ai dispositivi registrati in Intune di accedere a servizi specifici Limitando le posizioni utente e gli intervalli IP |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

