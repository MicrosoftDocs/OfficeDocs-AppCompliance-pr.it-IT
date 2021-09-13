---
title: Informazioni sull'applicazione per il testo per contatto approvato
ms.author: elmalova
author: elenamalova
ms.date: 05/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Text, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: fec1cbe4c30ef87592503e6e00ad1063cf953e05
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59279960"
---
# <a name="text"></a>Testo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 10, 2021</p>

* <a href="https://teams.microsoft.com/l/app/a622ceb4-b6e2-4557-8218-e22e80975ba4" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000383" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Contatto approvato a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Testo |
| ID | WA200000383 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Contatto approvato |
| URL del sito Web del partner | [https://www.approvedcontact.com](https://www.approvedcontact.com) |
| URL dell'informativa sulla privacy | [https://sales.approvedcontact.com/wp-content/uploads/text-p...](https://sales.approvedcontact.com/wp-content/uploads/text-privacy-policy.pdf) |
| URL delle Condizioni per l'utilizzo | [https://approvedcontact.com/Terms%20of%20use.pdf](https://approvedcontact.com/Terms%20of%20use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Approved Contact su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | delegated | Per il bot di testo acquisisciamo l'identificatore del team per la creazione di canali futuri per i messaggi di testo in ingresso. | Ci consente di creare Teams per gli utenti. | [a622ceb4-b6e2-4557-8218-e22e80975ba4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a622ceb4-b6e2-4557-8218-e22e80975ba4) |
>| email | delegated | indirizzi di posta elettronica | Recupero delle informazioni di contatto dell'utente. | [a622ceb4-b6e2-4557-8218-e22e80975ba4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a622ceb4-b6e2-4557-8218-e22e80975ba4) |
>| offline_access | delegated | I token di aggiornamento vengono archiviati nel database. | Usato per salvare in modo permanente i token di aggiornamento nel database | [a622ceb4-b6e2-4557-8218-e22e80975ba4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a622ceb4-b6e2-4557-8218-e22e80975ba4) |
>| openid | delegated | Credenziali di accesso | Consente all'utente di eseguire l'accesso. in modo che i testi possano essere recapitati Teams canali | [a622ceb4-b6e2-4557-8218-e22e80975ba4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a622ceb4-b6e2-4557-8218-e22e80975ba4) |
>| profilo | delegated | indirizzi di posta elettronica | Recupero delle informazioni di contatto dell'utente. | [a622ceb4-b6e2-4557-8218-e22e80975ba4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a622ceb4-b6e2-4557-8218-e22e80975ba4) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Usato per salvare in modo permanente i token di aggiornamento nel database | Archiviamo gli indirizzi di posta elettronica. | Usato per salvare in modo permanente i token di aggiornamento nel database |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì, registriamo gli indirizzi di posta elettronica per la connessione degli acquisti di licenze a Commercial Appsource. Microsoft offre la possibilità di eliminare queste informazioni dai log.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Solo gli sviluppatori hanno accesso ai log. Microsoft applica la 2FA per l'accesso a tutte le piattaforme di sviluppo.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35752' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35752" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite dal contatto approvato sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
