---
title: Informazioni sull'applicazione per Lucidspark di Lucid Software
ms.author: elmalova
author: elenamalova
ms.date: 05/13/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Lucidspark, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c05b4a1f7c5a1707ce7ab4f2d3230bdf1c7bdb4d
ms.sourcegitcommit: 1b9ad544fd91bb0fb25e467baf2d368a812dc476
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 06/14/2021
ms.locfileid: "52927276"
---
# <a name="lucidspark"></a>Lucidspark

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 13, 2021</p>

* <a href="https://teams.microsoft.com/l/app/e9ab21fa-5fd5-48bb-a85d-4de7ced89cd1" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002583" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Lucid Software a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Lucidspark |
| ID | WA200002583 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Lucid Software |
| URL del sito Web del partner | [https://lucid.co](https://lucid.co) |
| URL della pagina Teams informazioni sull'applicazione | [https://lucidchart.zendesk.com](https://lucidchart.zendesk.com) |
| URL dell'informativa sulla privacy | [https://lucid.co/privacy](https://lucid.co/privacy) |
| URL delle Condizioni per l'utilizzo | [https://lucid.co/tos](https://lucid.co/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Lucid Software su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| e-mail | delegated | Nome e indirizzo di posta elettronica. | Le autorizzazioni di posta elettronica, openid e profilo consentono a Lucidspark di generare un token openid per un utente e ottenere informazioni di base sufficienti sull'utente per registrare un account Lucidspark per loro, se necessario. Per verificare i dati che provengono da Microsoft, viene inviata una richiesta per ottenere la chiave pubblica con cui viene firmata la risposta. Nessun altro dato viene ricevuto o inviato a Microsoft come parte del flusso SSO. | 3557d5c0-bcab-410b-8a03-f7045aa48de0 |
>| openid | delegated | Nome e indirizzo di posta elettronica. | Le autorizzazioni di posta elettronica, openid e profilo consentono a Lucidspark di generare un token openid per un utente e ottenere informazioni di base sufficienti sull'utente per registrare un account Lucidspark per loro, se necessario. Per verificare i dati che provengono da Microsoft, viene inviata una richiesta per ottenere la chiave pubblica con cui viene firmata la risposta. Nessun altro dato viene ricevuto o inviato a Microsoft come parte del flusso SSO. | 3557d5c0-bcab-410b-8a03-f7045aa48de0 |
>| profilo | delegated | Nome e indirizzo di posta elettronica. | Le autorizzazioni di posta elettronica, openid e profilo consentono a Lucidspark di generare un token openid per un utente e ottenere informazioni di base sufficienti sull'utente per registrare un account Lucidspark per loro, se necessario. Per verificare i dati che provengono da Microsoft, viene inviata una richiesta per ottenere la chiave pubblica con cui viene firmata la risposta. Nessun altro dato viene ricevuto o inviato a Microsoft come parte del flusso SSO. | 3557d5c0-bcab-410b-8a03-f7045aa48de0 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutte le informazioni non servizi Microsoft OII vengono trasferite a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento di OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| I dati di Lucidspark e lucidchart sono archiviati in AWS e Snowflake | Nome dell'organizzazione, informazioni di contatto e livello di licenza | Non usiamo api Microsoft. Usiamo openID per ottenere i dati utente di base per eseguire SSO. Usiamo l'API di selezione file, ma questo non ci consente di accedere ai file dell'utente diversi da quelli che ci inviano tramite la selezione. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Registriamo la posta elettronica e gli indirizzi IP per motivi di sicurezza e supporto. Tutti gli accessi ai log registrati &amp; sono effettivamente immutabili in un sistema di terze parti. L'accesso ai log richiede L'autenticazione a più fattori.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati di Lucidspark e lucidchart sono archiviati in AWS. Viene crittografato in fase di riposo e in transito. Lucid usa le regole di privilegio minimo e MFA.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39482' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39482" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Lucid Software sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
