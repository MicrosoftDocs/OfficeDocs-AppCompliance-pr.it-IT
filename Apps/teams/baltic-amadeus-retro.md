---
title: Informazioni sull'applicazione per Retro di Baltic Amadeus
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Retro, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 49b17e202fb358284b9a36ed33646926d649afe3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553457"
---
# <a name="retro"></a>Retro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 3 novembre 2020</p>

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Baltic Amadeus a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Retro |
| ID | WA200001892 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Baltic Amadeus |
| URL del sito Web partner | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| URL dell'Informativa sulla privacy | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| URL delle Condizioni d'uso | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Baltic Amadeus su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>Questa applicazione non utilizza Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft non sono trasferiti** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| L'app retro ha una propria API Web che non è considerata un servizio Microsoft. Come accennato in precedenza, memorizza Email e Fullname per l'identificazione e scopi di visualizzazione dei contenuti appropriati. Questi dati non vengono inviati da nessun'altra parte. Inoltre, Retro ha una funzionalità opzionale per esportare i dati sprint nello spazio di confluenza Atlassian. Per fare ciò, l'utente deve inserire il proprio nome utente e password di confluenza. Questi dati vengono utilizzati solo per effettuare richieste autenticate all'API di confluenza per conto dell'utente e non vengono archiviati né registrati da nessuna parte. |  | Retro ha una propria API Web registrata anche in azure. Per utilizzarlo, l'utente deve essere autenticato tramite Microsoft Identity Platform. L'utente deve essere autenticato in modo che l'app Retro possa serverare contenuti specifici dell'utente |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Bot accede al roster per verificare quale membro si è unito o ha lasciato il team. In base a ciò, aggiunge o disattiva tale utente dal progetto in modo che l'utente non sia più visualizzato nell'elenco dei partecipanti allo sprint. | Email e FullName sono collegati tra loro e vengono archiviati nel database. La posta elettronica viene utilizzata per l'identificazione dell'utente al fine di visualizzare il contenuto appropriato per l'utente connesso. FullName viene utilizzato per visualizzare puproses, in modo che altri utenti possano sapere per chi stanno valutando o scrivendo feedback.  |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>No. L'unico processo che genera telemetria/registri nell'app Retro è la registrazione degli errori. I registri errori non includono euii o oii

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>I dati vengono archiviati nel database di Azure SQL Server. Viene memorizzato tramite l'app Retro e il bot Retro.
Per impostazione predefinita, il database azure sql ha abilitato la crittografia dei dati trasparente.
Il database è bloccato dietro l'autenticazione di base.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

