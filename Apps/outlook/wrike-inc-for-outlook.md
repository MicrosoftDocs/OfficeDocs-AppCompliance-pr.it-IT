---
title: Informazioni sull'applicazione per Wrike Outlook da Wrike Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Wrike for Outlook, i relativi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 1ee6c98b2513459c588100a9b3b19ba529d98af0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553697"
---
# <a name="wrike-for-outlook"></a>Wrike per Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Ultimo aggiornamento da parte dello sviluppatore: 23 marzo 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381120" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

informazioni fornite da Wrike Inc.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Wrike per Outlook |
| ID | WA104381120 |
| Office 365 client supportati | Outlook 2013 o versioni successive su Windows, Outlook 2016 o versioni successive su Mac, Outlook su iOS, Outlook sul Web, Outlook su Android |
| Nome della società partner | Wrike Inc. |
| URL del sito Web partner | [https://wrike.com/](https://wrike.com/) |
| URL dell'Informativa sulla privacy | [https://www.wrike.com/security/privacy](https://www.wrike.com/security/privacy) |
| URL delle Condizioni d'uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Wrike Inc.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>Questa applicazione non utilizza Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati tramite altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono utilizzare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni di identificazione dell'organizzazione ( OII). Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **OII viene raccolto?** |  **Quale OII viene raccolto?** | **Giustificazione per la raccolta di OII?** | **OII è memorizzato?** | **Giustificazione per l'archiviazione di OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API JavaScript per Office | Sì | Il componente aggiuntivo usa l'API Office.js per integrarsi con l'Office applicazione. |  | Nessun dato organizzativo viene archiviato nei database di Wrike. |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft non sono trasferiti** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike ha le integrazioni con i seguenti fornitori che hanno accesso ad alcuni dati: Marketo è servizi di acquisizione di lead di posta elettronica - vengono forniti solo nomi ed e-mail. La sensibilizzazione è un coinvolgimento delle vendite basato sul cloud: vengono forniti solo nomi ed e-mail. Sistema CRM Salesforce - dispone di informazioni di contatto e di fatturazione (senza dati sensibili) dei clienti. Zuora - clienti di fatturazione e fatturazione. C'è un DPA in atto per tutti i fornitori. |  | Utilizziamo JS Office API, tuttavia non raccogliamo/ emoboriamo / archiviamo alcuna informazione organizzativa. |



#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Wrike ha un'architettura multi-tenant che separa logicamente i clienti&#8217; dati attraverso il controllo degli accessi basato sui metadati dei clienti. Questi metadati sono associati al tenant specifico e ai relativi diritti di accesso in base alle regole di accesso basate sui ruoli all'interno dell'account Wrike specifico. I dati sono logicamente isolati e segregati e l'accesso ai dati è disponibile solo tramite l'applicazione per garantire sicurezza e privacy. La protezione a livello di applicazione impedisce ai tenant di accedere o modificare i dati dell'applicazione di proprietà di un altro tenant. L'applicazione di Wrike dispone di ampi meccanismi di autenticazione, controllo degli accessi basati sui ruoli, autorizzazione e condivisione e controllo dei dati (vedere e https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles https://help.wrike.com/hc/en-us/articles/209602969) che consentono l'accesso ai dati solo per gli utenti autorizzati). Inoltre, la crittografia a riposo viene applicata per i file utente caricati sui server Wrike nell'archiviazione dei file tramite applicazione Web e API; i file vengono crittografati automaticamente utilizzando la crittografia AES a 256 bit. Inoltre, tutti i server sono crittografati a riposo utilizzando la crittografia del file system e inoltre Wrike offre il componente aggiuntivo Wrike Lock per la chiave di crittografia gestita da un cliente, vedere https://www.wrike.com/add-on-wrike-lock/ e https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock . Come ulteriore livello di sicurezza dei dati, Wrike offre funzionalità di controllo e reporting che consentono agli amministratori di condurre revisioni complete della sicurezza pur essendo in grado di aumentare la visibilità su ciò che sta accadendo nel proprio account Wrike, ulteriori dettagli sono disponibili all'indirizzo https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports . Infine, Wrike fornisce funzionalità che consentono il monitoraggio granulare dei ruoli di accesso per aiutare i clienti a controllare completamente la condivisione dei dati esistente, vedere i dettagli all'indirizzo https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports .
L'accesso ai dati dei clienti può essere considerato in due casi:
- Accesso da parte del team di supporto Wrike: in caso di risoluzione dei problemi o verifica del problema richiede supporto per accedere al tuo account; che l'accesso può essere concesso solo da te. Questo è abilitato da un token di sicurezza generato dal sistema che fornisci fuori banda al nostro team di supporto, consentendo al supporto di approfondire la risoluzione del problema per un periodo di tempo limitato. Questo approccio sistemico garantisce un'ulteriore riservatezza per i tuoi dati memorizzati in Wrike.
- Accesso da parte del team operativo Wrike: il team operativo Wrike è responsabile della manutenzione e del supporto dell'ambiente di produzione, tra cui monitoraggio, patch e aggiornamento, consegna delle nuove build alla produzione, ecc. L'accesso in questo caso è severamente vietato sia per gli aspetti procedurali che tecnici, e sono in atto forti controlli di autorizzazione tra cui VPN, 2FA e certificato personale, inoltre è monitorato nei dettagli utilizzando HIDS (Host-based Intrusion Detection System) e rivisto dal team di sicurezza operativa Wrike. Nel caso di Amazon Servizio di gestione delle chiavi (funzionalità Wrike Lock), i dati dei clienti vengono memorizzati crittografati nel database Wrike, quindi i dati non sono direttamente o indirettamente disponibili dal team operativo Wrike, perché i dati possono essere decifrati utilizzando l'accesso al Servizio di gestione delle chiavi Amazon del cliente, che è gestito e controllato solo dal cliente.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

