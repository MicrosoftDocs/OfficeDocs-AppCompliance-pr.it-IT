---
title: Wrike for Office Documents Application Information
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni di sicurezza e conformità disponibili per Wrike per Office Documents, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d91cf614ca0e3b52eae4b626baf15e038c29f51b
ms.sourcegitcommit: ec1d4f7013722fe672830e3664b0fb8b0f33bd37
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/12/2022
ms.locfileid: "64784535"
---
# <a name="wrike-for-office-documents-application-information"></a>Wrike for Office Documents Application Information

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Ultimo aggiornamento da parte dello sviluppatore: 23 marzo 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379841" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Wrike Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Wrike per documenti Office |
| ID | WA104379841 |
| client Office 365 supportati | Excel 2016 o versioni successive Windows, Word 2013 o versioni successive Windows, PowerPoint 2013 o versioni successive Windows, Excel 2016 o versioni successive in Mac, Excel sul web, Word 2016 o versioni successive in Mac, Word sul web, PowerPoint 2016 o versione successiva su Mac, PowerPoint sul web |
| Nome della società partner | Wrike Inc. |
| URL del sito Web del partner | [https://www.wrike.com/](https://www.wrike.com/) |
| URL dell'informativa sulla privacy | [https://www.wrike.com/privacy/](https://www.wrike.com/privacy/) |
| URL delle condizioni per l'utilizzo | [https://www.wrike.com/terms/](https://www.wrike.com/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Wrike Inc. Su come questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elencare le [autorizzazioni di Microsoft Graph](/graph/permissions-reference) necessarie per questa app.

>Questa applicazione non usa Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati tramite altre API Microsoft

Le app e i componenti aggiuntivi basati su Microsoft 365 possono usare altre API Microsoft diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elencare eventuali API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Quale OII è raccolto?** | **Giustificazione per la raccolta dell'OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione dell'OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API JavaScript per Office | Sì | Il componente aggiuntivo usa l'API Office.js per l'integrazione con l'applicazione Office. |  | Nei database di Wrike non vengono archiviati dati dell'organizzazione. |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con un servizio non Microsoft, elencare il servizio non Microsoft usato dall'app, i dati trasferiti e includere una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike ha le integrazioni con i fornitori seguenti che hanno accesso ad alcuni dati: Marketo è servizi di acquisizione dei lead di posta elettronica. Vengono forniti solo nomi e messaggi di posta elettronica. Outreach è l'engagement delle vendite basato sul cloud: vengono forniti solo nomi e messaggi di posta elettronica. Sistema CRM di Salesforce: include informazioni di contatto e informazioni di fatturazione (nessun dato sensibile) dei clienti. Zuora : clienti di fatturazione e fatturazione. È disponibile un DPA per tutti i fornitori. |  | Microsoft usa JS Office API, ma non raccoglie/elabora/archivia informazioni aziendali. |



#### <a name="telemetry-data"></a>Dati di telemetria

Nei dati di telemetria o nei log dell'applicazione vengono visualizzate informazioni personali dell'organizzazione o informazioni personali dell'utente finale( EUII) ? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio l'eliminazione, la conservazione, il controllo, l'archiviazione, i criteri degli utenti finali e così via.

>Wrike ha un'architettura multi-tenant che separa logicamente i clienti&#8217; dati tramite il controllo di accesso in base ai metadati dei clienti. Questi metadati sono associati al tenant specifico e ai relativi diritti di accesso in base alle regole di accesso in base al ruolo all'interno dell'account Wrike specifico. I dati sono isolati logicamente e separati e l'accesso ai dati è disponibile solo tramite l'applicazione per garantire sicurezza e privacy. La sicurezza a livello di applicazione impedisce ai tenant di accedere o modificare i dati dell'applicazione di proprietà di un altro tenant. L'applicazione Wrike dispone di meccanismi completi di autenticazione, controllo degli accessi in base al ruolo, autorizzazione e condivisione e controllo dei dati (vedere https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles e https://help.wrike.com/hc/en-us/articles/209602969) che consentono l'accesso ai dati solo per gli utenti autorizzati. Inoltre, la crittografia inattivi viene applicata per i file utente caricati nei server Wrike nell'archiviazione file tramite l'applicazione Web e l'API; i file vengono crittografati automaticamente usando la crittografia AES a 256 bit. Inoltre, tutti i server vengono crittografati inattivi usando la crittografia del file system e inoltre Wrike offre il componente aggiuntivo Wrike Lock per la chiave di crittografia gestita da un cliente, vedere https://www.wrike.com/add-on-wrike-lock/ e https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock. Come ulteriore livello di sicurezza dei dati, Wrike offre funzionalità di controllo e creazione di report che consentono agli amministratori di eseguire revisioni complete della sicurezza e di aumentare la visibilità su ciò che accade nell'account Wrike. Altri dettagli sono disponibili all'indirizzo https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports. Infine, Wrike offre funzionalità che consentono il rilevamento granulare dei ruoli di accesso per consentire ai clienti di controllare completamente la condivisione dati esistente per visualizzare i dettagli in https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports.
L'accesso ai dati dei clienti può essere considerato in due casi:
- Accesso da parte del team di supporto di Wrike: in caso di risoluzione dei problemi o di verifica del problema è necessario il supporto per l'accesso all'account; che l'accesso può essere concesso solo dall'utente. Questo è abilitato da un token di sicurezza generato dal sistema che viene fornito fuori banda al team di supporto, consentendo al supporto di approfondire la risoluzione del problema per un periodo di tempo limitato. Questo approccio sistemico garantisce maggiore riservatezza per i dati archiviati in Wrike.
- Accesso da parte del team operativo di Wrike: il team operativo di Wrike è responsabile della manutenzione e del supporto dell'ambiente di produzione, tra cui il monitoraggio, l'applicazione di patch e l'aggiornamento, il recapito delle nuove build all'ambiente di produzione e così via. L'accesso in questo caso è rigorosamente vietato sia da aspetti procedurali che tecnici e sono in atto controlli di autorizzazione rigorosi, tra cui VPN, 2FA e certificato personale, inoltre viene monitorato nei dettagli tramite HIDS (Host-based Intrusion Detection System) e esaminato dal team di sicurezza operativa di Wrike. In caso di Amazon Servizio di gestione delle chiavi (funzionalità Wrike Lock), i dati del cliente vengono archiviati crittografati nel database Wrike, quindi i dati non sono direttamente o indirettamente disponibili dal team operativo di Wrike, perché i dati possono essere decrittografati usando l'accesso ad Amazon Servizio di gestione delle chiavi del cliente, gestito e controllato solo dal cliente.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni aziendali

Gli esseri umani sono coinvolti nella revisione o nell'analisi di eventuali dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono riportate le informazioni del catalogo [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='informazioni Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

