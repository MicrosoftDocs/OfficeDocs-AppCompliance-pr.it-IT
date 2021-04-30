---
title: Application Information for Wrike di Wrike Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per Wrike, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ca428571b8e7c0a3487299f8aab5f3e0d5899c33
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096151"
---
# <a name="wrike"></a>Wrike

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: March 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/05274a45-7312-4c23-8f64-d57fe4a28d6d" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381390" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Wrike Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Wrike |
| ID | WA104381390 |
| Funzionalità | Bot, scheda, estensione per la messaggistica |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Wrike Inc. |
| URL del sito Web del partner | [https://www.wrike.com](https://www.wrike.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://help.wrike.com/hc/en-us/articles/115001825869-Micro...](https://help.wrike.com/hc/en-us/articles/115001825869-Microsoft-Teams) |
| URL dell'informativa sulla privacy | [https://www.wrike.com/security/privacy/](https://www.wrike.com/security/privacy/) |
| URL delle Condizioni per l'utilizzo | [https://www.wrike.com/security/terms/](https://www.wrike.com/security/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Wrike Inc. Su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>Questa applicazione non utilizza Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API JavaScript per Office | Sì | Il componente aggiuntivo usa l'API Office.js per l'integrazione con l'Office applicazione. |  | I dati dell'organizzazione non vengono archiviati nei database di Wrike. |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutte le informazioni non servizi Microsoft OII vengono trasferite a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento di OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike ha le integrazioni con i fornitori seguenti che hanno accesso ad alcuni dati: Marketo è servizi di acquisizione dei lead di posta elettronica- vengono forniti solo nomi e messaggi di posta elettronica. Outreach è l'impegno per le vendite basato sul cloud: vengono forniti solo nomi e messaggi di posta elettronica. Sistema CRM Salesforce: contiene informazioni di contatto e fatturazione (senza dati sensibili) dei clienti. Zuora - Fatturazione e fatturazione dei clienti. È disponibile un DPA per tutti i fornitori. |  | Usiamo l'API JS Office, ma non raccogliamo/processiamo/archiviamo informazioni sull'organizzazione. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Wrike ha un'architettura multi-tenant che separa logicamente i clienti&#8217; dati tramite il controllo di accesso in base ai metadati dei clienti. Questi metadati sono associati al tenant specifico e ai relativi diritti di accesso in base alle regole di accesso basate sui ruoli all'interno dello specifico account Wrike. I dati sono logicamente isolati e separati e l'accesso ai dati è disponibile solo tramite l'applicazione per garantire sicurezza e privacy. La sicurezza a livello di applicazione impedisce ai tenant di accedere o modificare i dati dell'applicazione di proprietà di un altro tenant. L'applicazione di Wrike dispone di un'autenticazione estesa, controllo dell'accesso basato sui ruoli, autorizzazione e meccanismi di condivisione e controllo dei dati (vedere e che consentono l'accesso ai dati solo per https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles https://help.wrike.com/hc/en-us/articles/209602969) gli utenti autorizzati. Inoltre, la crittografia in pausa viene applicata per i file utente caricati nei server Wrike nell'archiviazione dei file tramite l'applicazione Web e l'API; i file vengono crittografati automaticamente utilizzando la crittografia AES a 256 bit. Inoltre, tutti i server vengono crittografati a riposo utilizzando la crittografia del file system e inoltre Wrike offre il componente aggiuntivo Wrike Lock per la chiave di crittografia gestita da un cliente, vedere https://www.wrike.com/add-on-wrike-lock/ e https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock . Come ulteriore livello di sicurezza dei dati, Wrike offre funzionalità di controllo e creazione di report che consentono agli amministratori di eseguire revisioni complete della sicurezza, pur essendo in grado di aumentare la visibilità su ciò che accade nel proprio account Wrike, altri dettagli sono disponibili all'indirizzo https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports . Infine, Wrike offre funzionalità che consentono il monitoraggio granulare dei ruoli di accesso per consentire ai clienti di controllare completamente la condivisione dei dati esistenti, vedere i dettagli all'indirizzo https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports .
L'accesso ai dati dei clienti può essere considerato in due casi:
- Accesso da parte del team di supporto Wrike: in caso di risoluzione dei problemi o di verifica del problema, il supporto richiede l'accesso al tuo account; l'accesso può essere concesso solo dall'utente. Questo è abilitato da un token di sicurezza generato dal sistema che fornisci fuori banda al team di supporto, consentendo al supporto di approfondire la risoluzione del problema per un periodo di tempo limitato. Questo approccio sistemico garantisce ulteriore riservatezza per i dati archiviati in Wrike.
- Accesso da parte del team operativo Wrike: il team operativo Wrike è responsabile della manutenzione e del supporto dell'ambiente di produzione, tra cui monitoraggio, applicazione di patch e aggiornamento, recapito delle nuove build alla produzione e così via. L'accesso in questo caso è severamente proibito sia dagli aspetti procedurali che tecnici, e sono in atto controlli di autorizzazione rigorosi, tra cui VPN, 2FA e certificato personale, inoltre viene monitorato in dettaglio tramite HIDS (Sistema di rilevamento delle intrusioni basato su host) e esaminato dal team Wrike Operational Security. Nel caso di Amazon Servizio di gestione delle chiavi (funzionalità Wrike Lock), i dati dei clienti vengono archiviati crittografati nel database Wrike, quindi i dati non sono direttamente o indirettamente disponibili dal team operativo Wrike, perché i dati possono essere decrittografati utilizzando l'accesso a Amazon Servizio di gestione delle chiavi del cliente, che viene gestito e controllato solo dal cliente.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

