---
title: Informazioni sull'applicazione per Lucidchart di Lucid Software
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Lucidchart, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2f074d098f4a1819a7c5b2236e5e1a6e957f884c
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282463"
---
# <a name="lucidchart"></a>Lucidchart

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/7f905be6-3226-4a4c-9c54-ab1edce3c99c" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381935" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Lucid Software a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Lucidchart |
| ID | WA104381935 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Lucid Software |
| URL del sito Web del partner | [https://www.lucidchart.com](https://www.lucidchart.com) |
| URL della Teams info dell'applicazione | [https://lucidchart.zendesk.com/](https://lucidchart.zendesk.com/) |
| URL dell'informativa sulla privacy | [https://www.lucidchart.com/pages/privacy](https://www.lucidchart.com/pages/privacy) |
| URL delle Condizioni per l'utilizzo | [https://www.lucidchart.com/pages/tos](https://www.lucidchart.com/pages/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Lucid Software su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | delegated | Nome e indirizzo di posta elettronica. | Le autorizzazioni di posta elettronica, openid e profilo consentono a Lucidchart di generare un token openid per un utente e ottenere informazioni di base sufficienti sull'utente per registrare un account Lucidchart per loro, se necessario. Per verificare i dati che provengono da Microsoft, viene inviata una richiesta per ottenere la chiave pubblica con cui viene firmata la risposta. Nessun altro dato viene ricevuto o inviato a Microsoft come parte del flusso SSO. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| openid | delegated | Nome e indirizzo di posta elettronica. | Le autorizzazioni di posta elettronica, openid e profilo consentono a Lucidchart di generare un token openid per un utente e ottenere informazioni di base sufficienti sull'utente per registrare un account Lucidchart per loro, se necessario. Per verificare i dati che provengono da Microsoft, viene inviata una richiesta per ottenere la chiave pubblica con cui viene firmata la risposta. Nessun altro dato viene ricevuto o inviato a Microsoft come parte del flusso SSO. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| profilo | delegated | Nome e indirizzo di posta elettronica. | Le autorizzazioni di posta elettronica, openid e profilo consentono a Lucidchart di generare un token openid per un utente e ottenere informazioni di base sufficienti sull'utente per registrare un account Lucidchart per loro, se necessario. Per verificare i dati che provengono da Microsoft, viene inviata una richiesta per ottenere la chiave pubblica con cui viene firmata la risposta. Nessun altro dato viene ricevuto o inviato a Microsoft come parte del flusso SSO. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API JavaScript per Office | Sì | Usiamo javascript SDK Office OneDrive per aprire lo strumento OneDrive selezione file usando OneDrive.open(). Non generiamo alcun token di accesso e non eserciteremo alcuna richiesta per OneDrive api di microsoft; l OneDrive SDK di Selezione file esegue questa operazione. Vengono visualizzati solo i nomi di file che l'utente sceglie. |  | Se l'utente seleziona un file usando lo strumento OneDrive selezione file, il nome del file viene archiviato. |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| I dati di Lucidchart vengono archiviati in AWS. |  | Non usiamo api Microsoft. Usiamo openID per ottenere i dati utente di base per eseguire SSO. Usiamo l'API di selezione file, ma questo non ci consente di accedere ai file dell'utente diversi da quelli che ci inviano tramite la selezione. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Registriamo la posta elettronica e gli indirizzi IP per motivi di sicurezza e supporto. Tutti gli accessi ai log registrati &amp; sono effettivamente immutabili in un sistema di terze parti. L'accesso ai log richiede L'autenticazione a più fattori.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati di Lucidchart vengono archiviati in AWS. Viene crittografato in fase di riposo e in transito. Lucidchart usa le regole dei privilegi minimi e dell'autenticazione a più fattori.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalogo vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

