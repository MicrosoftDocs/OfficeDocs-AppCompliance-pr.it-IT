---
title: Application Information for ti8m places by ti &amp; m AG
ms.author: elmalova
author: elenamalova
ms.date: 10/04/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per le posizioni ti8m, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 92b67a17394d796e0d743c6b3c570698e54e2fec
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411431"
---
# <a name="ti8m-places"></a>ti8m places

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 16, 2021</p>

* <a href="https://teams.microsoft.com/l/app/9e384ce2-2db2-412e-8da7-08c5cf4c418e" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003311" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da ti &amp; m AG a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | ti8m places |
| ID | WA200003311 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | ti&amp;m AG |
| URL del sito Web del partner | [https://www.ti8m.com/places](https://www.ti8m.com/places) |
| URL della Teams info dell'applicazione | [https://www.ti8m.ch/places](https://www.ti8m.ch/places) |
| URL dell'informativa sulla privacy | [https://ti8m.com/products/places/places-datenschutzerklaeru...](https://ti8m.com/products/places/places-datenschutzerklaerung) |
| URL delle Condizioni per l'utilizzo | [https://ti8m.com/products/places/places-nutzungsbedingungen](https://ti8m.com/products/places/places-nutzungsbedingungen) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da ti m AG su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti &amp; dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite.Shared | delegated | Annullare gli eventi nei calendari degli utenti e degli ambienti di lavoro  | ID evento se una voce di calendario prenotata deve essere annullata | [43134ae0-301f-4762-b7a9-aa9f2ff77b38](https://docs.microsoft.com/microsoft-365-app-certification/azure/43134ae0-301f-4762-b7a9-aa9f2ff77b38) |
>| Directory.ReadWrite.All | delegated | Installazione e creazione di gruppi AAD amministrativi - Gruppi di sicurezza  | GroupNames e GroupIDs | [43134ae0-301f-4762-b7a9-aa9f2ff77b38](https://docs.microsoft.com/microsoft-365-app-certification/azure/43134ae0-301f-4762-b7a9-aa9f2ff77b38) |
>| Place.ReadWrite.All | delegated | Elenco di luoghi di lavoro e nomi delle mappe  | WORKPLACE ID, Email Adresse of Workplace e Displayname. Usato per la prenotazione di un luogo di lavoro | [43134ae0-301f-4762-b7a9-aa9f2ff77b38](https://docs.microsoft.com/microsoft-365-app-certification/azure/43134ae0-301f-4762-b7a9-aa9f2ff77b38) |
>| User.Read | delegated | Username, Email and Displayname, Necessary to show Userdata in Application | Username, Email and Displayname, Necessary to show Userdata in Application | [43134ae0-301f-4762-b7a9-aa9f2ff77b38](https://docs.microsoft.com/microsoft-365-app-certification/azure/43134ae0-301f-4762-b7a9-aa9f2ff77b38) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>archiviazione, eliminazione

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da ti m AG su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni &amp; e altri criteri di identità.

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
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

