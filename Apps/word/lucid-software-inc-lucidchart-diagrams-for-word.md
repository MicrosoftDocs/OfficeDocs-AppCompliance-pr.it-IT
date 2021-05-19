---
title: Informazioni sull'applicazione per diagrammi lucidi per Word di Lucid Software Inc
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Lucidchart Diagrams for Word, i relativi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4e7e4bd31854f3861d60e8c740c39a11edc5bb5f
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552637"
---
# <a name="lucidchart-diagrams-for-word"></a>Diagrammi lucidi per Word

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 16 dicembre 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380118" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Lucid Software Inc a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Diagrammi lucidi per Word |
| ID | WA104380118 |
| Office 365 client supportati | Word 2016 o versioni successive in Mac, Word 2013 o versioni successive Windows, Word sul web |
| Nome della società partner | Lucid Software Inc |
| URL del sito Web partner | [https://www.lucidchart.com/](https://www.lucidchart.com/) |
| URL dell'Informativa sulla privacy | [https://www.lucidchart.com/pages/privacy](https://www.lucidchart.com/pages/privacy) |
| URL delle Condizioni d'uso | [https://www.lucidchart.com/pages/tos](https://www.lucidchart.com/pages/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Lucid Software Inc su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| e-mail | delegato | Nome e indirizzo email. | Le autorizzazioni di posta elettronica, openid e profilo consentono a Lucidchart di generare un token openid per un utente e ottenere informazioni di base sufficienti sull'utente per registrare un account Lucidchart per loro, se necessario. Per verificare i dati che tornano da Microsoft, facciamo una richiesta per ottenere la chiave pubblica con cui è firmata la loro risposta. Nessun altro dato viene ricevuto o inviato a Microsoft come parte del nostro flusso SSO. |  |
>| openid | delegato | Nome e indirizzo email. | Le autorizzazioni di posta elettronica, openid e profilo consentono a Lucidchart di generare un token openid per un utente e ottenere informazioni di base sufficienti sull'utente per registrare un account Lucidchart per loro, se necessario. Per verificare i dati che tornano da Microsoft, facciamo una richiesta per ottenere la chiave pubblica con cui è firmata la loro risposta. Nessun altro dato viene ricevuto o inviato a Microsoft come parte del nostro flusso SSO. |  |
>| profilo | delegato | Nome e indirizzo email. | Le autorizzazioni di posta elettronica, openid e profilo consentono a Lucidchart di generare un token openid per un utente e ottenere informazioni di base sufficienti sull'utente per registrare un account Lucidchart per loro, se necessario. Per verificare i dati che tornano da Microsoft, facciamo una richiesta per ottenere la chiave pubblica con cui è firmata la loro risposta. Nessun altro dato viene ricevuto o inviato a Microsoft come parte del nostro flusso SSO. |  |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati tramite altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono utilizzare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni di identificazione dell'organizzazione ( OII). Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **OII viene raccolto?** |  **Quale OII viene raccolto?** | **Giustificazione per la raccolta di OII?** | **OII è memorizzato?** | **Giustificazione per l'archiviazione di OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API JavaScript per Office | Sì | Usiamo l'SDK javascript Office OneDrive per aprire il OneDrive di file utilizzando OneDrive.open(). Non generiamo token di accesso e non facciamo alcuna richiesta alle API OneDrive di internet; il OneDrive SDK di scelta dei file lo fa per noi. Vediamo solo i nomi di file che l'utente sceglie. |  | Se l'utente seleziona un file utilizzando il OneDrive di file, viene memorizzato il nome del file. |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft non sono trasferiti** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| I dati lucidchart vengono archiviati in AWS. |  | Non usiamo API Microsoft. Usiamo openID per ottenere i dati utente di base per eseguire SSO. Usiamo la loro API di selezione file, ma ciò non ci dà accesso ai file dell'utente diversi da quelli che ci inviano tramite la selezione. |



#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Registriamo e-mail e indirizzi IP per motivi di sicurezza e supporto. Tutti gli accessi ai registri sono &amp; registrati i registri sono effettivamente immutabili in un sistema di terze parti. L'accesso ai registri richiede l'autenticazione a più fattori.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>I dati lucidchart vengono archiviati in AWS. È criptato a riposo e in transito. Lucidchart utilizza le regole del privilegio minimo e dell'autenticazione a più fattori.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

