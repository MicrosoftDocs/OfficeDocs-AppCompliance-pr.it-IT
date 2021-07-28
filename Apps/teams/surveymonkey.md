---
title: Informazioni sull'applicazione per SurveyMonkey di SurveyMonkey
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per SurveyMonkey, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f4898e476e0848ba728d07d0d851fc09f239aecf
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/22/2021
ms.locfileid: "53528202"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da SurveyMonkey a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | SurveyMonkey |
| ID | WA104381088 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | SurveyMonkey |
| URL del sito Web del partner | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| URL dell'informativa sulla privacy | [https://www.surveymonkey.com/mp/legal/privacy-policy/](https://www.surveymonkey.com/mp/legal/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://www.surveymonkey.com/mp/legal/terms-of-use/](https://www.surveymonkey.com/mp/legal/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da SurveyMonkey su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | delegated | No | Per fornire un elenco di gruppi/canali con cui condividere un sondaggio | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutte le informazioni non servizi Microsoft OII vengono trasferite a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento di OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Solo l'ID utente MS viene archiviato in SurveyMonkey per associare risposte e sondaggi all'utente del team. |  | Per i team usiamo il Microsoft Teams SDK javascript nel modulo delle attività crea, prendi sondaggi e risultati del sondaggio in modalità modale. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Esercitiamo una chiamata a v3/conversations/{id}/pagedmembers per verificare che l'app sia stata aggiunta a un team e ottenere il numero di membri. È per il monitoraggio interno dell'utilizzo, vediamo solo le dimensioni dell'elenco delle chat, altre informazioni vengono ignorate. | Sì, vengono archiviate le dimensioni della chat (un singolo numero intero) |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>EUII - Ogni volta che un sondaggio riceve una risposta, viene creato un log di esito positivo/negativo e si tenta di inviare tale risposta a Teams tramite il connettore, questo registro include user_id, survey_id, integration_id (che nel database può essere utilizzato per cercare l'ID team MS, l'ID utente MS)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Il nostro data center principale si trova a Las Vegas, NV e il nostro data center secondario si trova a Santa Clara, CA. SurveyMonkey possiede e gestisce tutti i server e l'infrastruttura in queste posizioni. Abbiamo anche una residenza dati canadese per alcuni clienti di SurveyMonkey Enterprise residenti in Canada. Tutti i dati vengono crittografati in pausa utilizzando TDE con AES256 e i dati in transito vengono crittografati con TLS 1.2.

SurveyMonkey utilizza l'autenticazione utente centrale per mantenere la gestione delle identità e degli accessi. Questo sistema gestisce tutte le autenticazioni e le autorizzazioni per qualsiasi infrastruttura, sistemi e servizi aziendali e di produzione. I criteri di accesso rigorosi vengono mantenuti e esaminati su base trimestrale. Le recensioni includono, ma non sono limitate a: elenchi di accesso degli utenti, gruppi di criteri e revisioni di accesso di terze parti. Per accedere all'ambiente di produzione (ad esempio per ottenere un account con privilegi), è necessario ottenere l'approvazione del manager, completare una serie di corsi di formazione necessari e ottenere l'approvazione dal team di sicurezza. In quel momento viene effettuato il provisioning di un account VPN aggiuntivo, che differenzia l'account &#8216;&#8217; normale da un account &#8216;con&#8217; privilegiato.

Solo i dispositivi emessi dall'azienda possono accedere alla rete di produzione. Tutte le impostazioni predefinite del fornitore wireless vengono modificate prima dell'installazione, incluse le chiavi di crittografia wireless predefinite, le password e le stringhe della community SNMP. Per eseguire questa operazione in remoto sono necessari 2FA e VPN. Abbiamo una rete WiFi separata per l'accesso guest presso i nostri uffici aziendali.

Tutti i servizi, i protocolli e le porte consentite devono avere una giustificazione e un'approvazione aziendali documentate, incluso l'utilizzo di funzionalità di sicurezza implementate per i protocolli considerati non sicuri. I router e i firewall sono configurati per limitare la divulgazione ip a parti non autorizzate o indesiderate e limitare l'accesso Internet in ingresso agli indirizzi IP all'interno del firewall DMZ e i set di regole del router vengono esaminati almeno ogni sei mesi.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

