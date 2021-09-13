---
title: Informazioni sull'applicazione per Prezi Video di Prezi
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e conformità disponibili per Prezi Video, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8e7e9c70ee848fd284e3297a915ec9847d3ef1ee
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59280663"
---
# <a name="prezi-video"></a>Prezi Video

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/78bbd675-511e-41a2-9a1a-8793920efa9e" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001577" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Prezi a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Prezi Video |
| ID | WA200001577 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Prezi |
| URL del sito Web del partner | [https://prezi.com](https://prezi.com) |
| URL dell'informativa sulla privacy | [https://prezi.com/privacy-policy/](https://prezi.com/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://prezi.com/terms-of-use/](https://prezi.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Prezi su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>Questa applicazione non utilizza Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Per informazioni dettagliate, visitare https://prezi.com/privacy-policy/ |  | Le API/SDK seguenti vengono usate per l'integrazione insieme a 1. Botbuilder-SDK (python): usando questo SDK archiviamo l'ID oggetto Azure Active Directory (indicato dall'API come aad_object_id). Queste informazioni sono necessarie per mappare un Microsoft Teams utente a qualsiasi contenuto correlato a Prezi Video creato in prezi.com.  2. Botbuilder-js (javascript): non Microsoft Teams dati specifici vengono raccolti con questo SDK. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Il bot non accede alle informazioni sull'elenco menzionato. | Il bot non accede alle informazioni sull'elenco menzionato. |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nei registri dell'applicazione non viene visualizzato alcun codice EUII o OII.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>In un database RDS vengono archiviate le informazioni seguenti:

1. Azure Active Directory ID oggetto (indicato dall'API come aad_object_id) viene archiviato per recuperare un Microsoft Teams utente&#8217;video. Il aad_object_id viene recuperato in modo sicuro utilizzando l'sdk botbuilder ufficiale di Microsoft&#8217;sui nostri server.

2. Collegamenti video creati in prezi.com. Il contenuto creato prezi.com viene archiviato in base alla sezione 14 nell'URL seguente: https://prezi.com/privacy-policy/ 

I diritti di accesso ai sistemi esterni ad alto rischio (come AWS) vengono gestiti tramite una piattaforma di gestione unificata delle identità e degli accessi di terze parti (OneLogin).

I criteri password e l'autenticazione a più fattori vengono applicati al personale nella piattaforma unificata di gestione delle identità e degli accessi. Caso per caso, l'autenticazione a più fattori non è necessaria dagli indirizzi IP dell'ufficio.

I servizi e i database ospitati da AWS, per impostazione predefinita, non sono accessibili da nessuna parte; Le regole in ingresso esplicite devono essere aggiunte manualmente.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

