---
title: Informazioni sull'applicazione per SurveyMonkey di SurveyMonkey
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per SurveyMonkey, i relativi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 57ba8ed84e0d9ea4101ea82ed5d92aef1f634ed1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552727"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 16 dicembre 2019</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da SurveyMonkey a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | SurveyMonkey |
| ID | WA104381088 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | SurveyMonkey |
| URL del sito Web partner | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| URL dell'Informativa sulla privacy | [https://www.surveymonkey.com/privacy](https://www.surveymonkey.com/privacy) |
| URL delle Condizioni d'uso | [https://www.surveymonkey.com/mp/policy/terms-of-use/](https://www.surveymonkey.com/mp/policy/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da SurveyMonkey su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | delegato | No | Per fornire un elenco di gruppi/canali con cui condividere un sondaggio |  |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft non sono trasferiti** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Solo l'ID utente MS viene archiviato in SurveyMonkey per associare risposte e sondaggi all'utente del team. |  | Per i team usiamo l'SDK javascript Microsoft Teams nel modulo di attività crea, rileva e rileva i risultati del sondaggio modale. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Facciamo una chiamata a v3/conversations/{id}/pagedmembers per verificare che l'app sia aggiunta a un team e ottenere il conteggio dei membri. È per il monitoraggio interno dell'utilizzo, guardiamo solo le dimensioni del roster di chat, altre informazioni vengono ignorate. | Sì, le dimensioni della chat vengono memorizzate (un singolo numero intero) |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>EUII - Ogni volta che un sondaggio riceve una risposta viene creato un registro di successo/esito negativo e si tenta di inviarla a Teams tramite il connettore, questo registro include user_id, survey_id, integration_id (che nel database può essere utilizzato per cercare MS Team ID, MS User ID)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Il nostro data center principale si trova a Las Vegas, NV e il nostro data center secondario si trova a Santa Clara, CA. SurveyMonkey possiede e gestisce tutti i suoi server e l'infrastruttura in queste posizioni. Abbiamo anche una residenza dati canadese disponibile per alcuni clienti di SurveyMonkey Enterprise residenti in Canada. Tutti i dati vengono crittografati a riposo utilizzando TDE con AES256 e i dati in transito vengono crittografati utilizzando TLS 1.2.

SurveyMonkey utilizza l'autenticazione utente centrale per mantenere la gestione delle identità e degli accessi. Questo sistema gestisce tutta l'autenticazione e l'autorizzazione a tutte le infrastrutture, i sistemi e i servizi aziendali e di produzione. Le rigide politiche di accesso vengono mantenute e riviste su base trimestrale. Le recensioni includono, a titolo titolo titolo titolo pertanto, ma non sono limitate a: elenchi di accesso degli utenti, gruppi di criteri e revisioni di accesso di terze parti. Per accedere al nostro ambiente di produzione (cioè per ottenere un account privilegiato), è necessario ottenere l'approvazione del manager, completare una serie di corsi di formazione richiesti e ottenere l'approvazione del nostro team di sicurezza. A quel tempo, viene esato il provisioning di un account VPN aggiuntivo, che differenzia l'account &#8216;normale&#8217; da un account &#8216;un account&#8217; privilegiato.

Solo i dispositivi emessi dall'azienda possono accedere alla nostra rete di produzione. Tutte le impostazioni predefinite del fornitore wireless vengono modificate prima dell'installazione, incluse, a titolo pertanto, le chiavi di crittografia wireless predefinite, le password e le stringhe della community SNMP. 2FA e VPN sono necessari per farlo da remoto. Abbiamo una rete wifi separata per l'accesso degli ospiti presso i nostri uffici aziendali.

Tutti i servizi, i protocolli e le porte consentite devono avere una giustificazione e un'approvazione aziendali documentate, incluso l'uso di funzionalità di sicurezza implementate per quei protocolli considerati non sicuri. Router e firewall sono configurati per limitare la divulgazione IP a parti non autorizzate o non intenzionali e limitare l'accesso internet in ingresso agli indirizzi IP all'interno del firewall DMZ e i set di regole del router vengono esaminati almeno ogni sei mesi.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

