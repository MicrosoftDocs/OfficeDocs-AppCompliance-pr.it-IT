---
title: Informazioni sull'applicazione per isLucid by UAB Lucid Agreements
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e conformità disponibili per isLucid, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 7270fa4f4a08ca820d1fe7452dea13fb107f2294
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414903"
---
# <a name="islucid"></a>isLucid

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 9, 2021</p>

* <a href="https://teams.microsoft.com/l/app/a5711b63-5e70-4e4e-b040-0d714b64f684" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002385" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite dai contratti UAB Lucid a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | isLucid |
| ID | WA200002385 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | UAB Lucid Agreements |
| URL del sito Web del partner | [https://islucid.com](https://islucid.com) |
| URL della Teams info dell'applicazione | [https://islucid.com](https://islucid.com) |
| URL dell'informativa sulla privacy | [https://islucid.com/privacy-policy/](https://islucid.com/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://islucid.com/eula/](https://islucid.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite dagli accordi di lucidità UAB sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calls.AccessMedia.All | entrambi | Con un consenso specifico dell'utente per ogni chiamata separatamente (trascrizione avviata) accede al flusso audio. Il flusso audio viene inoltrato a un servizio di trascrizione per consentire agli utenti di ottenere ulteriori funzionalità. | Archivi app in contenitori separati in Azure (archiviazione BLOB e Cosmos DB per ogni client separatamente) trascrizione e meta informazioni correlate. Ciò è necessario per fornire un ulteriore accesso alle informazioni di una riunione per l'utente, che ha utilizzato l'applicazione e si trovava nella riunione specifica. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Calls.JoinGroupCall.All | entrambi | Con un consenso specifico dell'utente per ogni chiamata separatamente (trascrizione avviata) accede al flusso audio. Il flusso audio viene inoltrato a un servizio di trascrizione per consentire agli utenti di ottenere ulteriori funzionalità. | Archivi app in contenitori separati in Azure (archiviazione BLOB e Cosmos DB per ogni client separatamente) trascrizione e meta informazioni correlate. Ciò è necessario per fornire un ulteriore accesso alle informazioni di una riunione per l'utente, che ha utilizzato l'applicazione e si trovava nella riunione specifica. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Group.ReadWrite.All | entrambi | Quando l'utente utilizza l'integrazione con Microsoft Planner per creare attività dalla chiamata e archiviarle automaticamente in MS Planner, isLucid raccoglie per quell'utente gruppi, piani, assegnatari disponibili. Senza questa autorizzazione, l'utente non sarebbe in grado di creare attività dalla trascrizione utilizzando isLucid | Il titolo dell'attività, il creatore dell'attività, il timestamp dell'attività e la descrizione dell'attività vengono archiviati in modo che gli utenti possono accedere alla cronologia delle attività, effettuata da una riunione specifica. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| OnlineMeetings.Read.All | entrambi | L'applicazione raccoglie i titoli delle riunioni in modo che gli utenti in un secondo momento (al termine della riunione) trovino più facilmente le trascrizioni e le attività precedenti. | Titolo della riunione, timestamp della riunione, organizzatore della riunione | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Tasks.ReadWrite | entrambi | Quando l'utente utilizza l'integrazione con Microsoft Planner per creare attività dalla chiamata e archiviarle automaticamente in MS Planner, isLucid raccoglie per quell'utente gruppi, piani, assegnatari disponibili. Senza questa autorizzazione, l'utente non sarebbe in grado di creare attività dalla trascrizione utilizzando isLucid | Il titolo dell'attività, il creatore dell'attività, il timestamp dell'attività e la descrizione dell'attività vengono archiviati in modo che gli utenti possono accedere alla cronologia delle attività, effettuata da una riunione specifica. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| User.ReadWrite.All | entrambi | Quando l'utente utilizza l'integrazione con Microsoft Planner per creare attività dalla chiamata e archiviarle automaticamente in MS Planner, isLucid raccoglie per quell'utente gruppi, piani, assegnatari disponibili. Senza questa autorizzazione, l'utente non sarebbe in grado di creare attività dalla trascrizione utilizzando isLucid | Il titolo dell'attività, il creatore dell'attività, il timestamp dell'attività e la descrizione dell'attività vengono archiviati in modo che gli utenti possono accedere alla cronologia delle attività, effettuata da una riunione specifica. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| openid | entrambi | ID utente, ID tenant raccolto per fornire agli utenti Azure Active Directory di accesso | ID utente, ID tenant per ulteriori rights management | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| hubspot.com | Nome, cognome, e-mail e Telefono numero di nuovi utenti registrati | Microsoft utilizza Hubspot CRM per la gestione delle informazioni correlate alle vendite |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Il bot abilita l'invio del flusso audio al servizio di trascrizione. Per fornire una trascrizione leggibile, è necessario associare l'audio agli utenti (altoparlanti). Senza fornire tali trascrizioni di informazioni sono inutili | Nome, cognome, stato se si tratta di un account guest o microsoft | Il bot abilita l'invio del flusso audio al servizio di trascrizione. Per fornire una trascrizione leggibile, è necessario associare l'audio agli utenti (altoparlanti). Le informazioni sui partecipanti alla riunione sono rilevanti anche per consentire agli utenti di visualizzare chi partecipava alla riunione. |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Gli utenti che usano il servizio generano trascrizioni. Nelle trascrizioni presentate i partecipanti alla riunione (nomi, cognomi). Potenzialmente, durante la chiamata è possibile menzionare qualsiasi elemento. Questi dati vengono archiviati per gli utenti purché utilizzino i nostri servizi. Una volta che il client termina di usarlo, entro 30 giorni distruriamo tutti i dati associati.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Non controlliamo alcun dato sui nostri client quando gli acquisti dei client vengono acquistati come soluzione ospitata. Per la soluzione SaaS consentiamo agli utenti di annullare l'uso dei nostri servizi e quindi eliminiamo Cosmos db isntance, associato al partner. È in corso l'invio di informazioni anche all'API di conformità

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite dai contratti UAB Lucid su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | Sì |
| Il modello di autorizzazione consente l'esito positivo delle chiamate solo se l'app client riceve il consenso appropriato? | Sì |
| La tua app usa le API di anteprima? | Sì |
| L'app usa API deprecate? | Sì |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

