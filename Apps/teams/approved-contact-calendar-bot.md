---
title: Informazioni sull'applicazione per bot del calendario per contatto approvato
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Tutte le informazioni di sicurezza e conformità disponibili per Bot calendario, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 80bb5043cb912e55215ba8578f4c70804acc8ac9
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095596"
---
# <a name="calendar-bot"></a>Calendar BOT

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/f02fddc9-159a-4d58-9800-d94c4f64bfe8" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381271" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Contatto approvato a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Calendar BOT |
| ID | WA104381271 |
| Funzionalità | Bot, scheda |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Contatto approvato |
| URL del sito Web del partner | [https://approvedcontact.com](https://approvedcontact.com) |
| URL dell'informativa sulla privacy | [https://approvedcontact.com/Privacy%20Policy%20Bot.pdf](https://approvedcontact.com/Privacy%20Policy%20Bot.pdf) |
| URL delle Condizioni per l'utilizzo | [https://approvedcontact.com/Terms%20of%20use.pdf](https://approvedcontact.com/Terms%20of%20use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Approved Contact su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegated | Per il BOT calendario vengono archiviati i tempi di disponibilità degli utenti per trovare i tempi liberi per più persone.  | Leggere e confrontare il tempo di disponibilità e pianificare le riunioni. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| Contacts.Read | delegated | Sì, vengono archiviate le informazioni di contatto. | Importazione e sincronizzazione dei contatti. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.Read | delegated | Sì | Informazioni di base sul profilo. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.ReadBasic.All | delegated | No | Usato per visualizzare i profili dei colleghi, confrontare i tempi liberi e pianificare sale riunioni. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| offline_access | delegated | Sì, orari di disponibilità per gli utenti offline. | Chiama Graph quando l'utente non usa attivamente il sito. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| openid | delegated | No | Office 365 SSO. | adef9811-448f-4dd5-88d9-68734050fe58 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| L'elenco viene utilizzato per confrontare gli orari di disponibilità per tutti gli utenti del team per pianificare le riunioni in un orario aperto. | È sufficiente archiviare l'indirizzo di posta elettronica in modo da poter confrontare i tempi di disponibilità. |  |



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

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

