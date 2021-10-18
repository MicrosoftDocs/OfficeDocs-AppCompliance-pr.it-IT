---
title: Application Information for email-texting by Voice Elements Corporation
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per l'invio di messaggi di posta elettronica, i criteri di gestione dei dati, le informazioni sul catalogo app di Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: dd581f2d3ad38cd31e18bf0adce01fd1a6b2744a
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60432831"
---
# <a name="email-texting"></a>email-texting

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: July 28, 2021</p>

* <a href="https://teams.microsoft.com/l/app/f76a92ed-2c10-4e37-ac84-f2474958d933" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003086" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Voice Elements Corporation a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | email-texting |
| ID | WA200003086 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Voice Elements Corporation |
| URL del sito Web del partner | [https://www.email-texting.com](https://www.email-texting.com) |
| URL della Teams info dell'applicazione | [https://www.email-texting.com](https://www.email-texting.com) |
| URL dell'informativa sulla privacy | [https://www.email-texting.com/privacy](https://www.email-texting.com/privacy) |
| URL delle Condizioni per l'utilizzo | [https://www.email-texting.com/terms-of-use](https://www.email-texting.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Voice Elements Corporation su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegated | Necessario per SSO da Teams | Identità degli utenti, necessaria per SSO | [806359be-da23-4538-80bb-baa82107ec2d](https://docs.microsoft.com/microsoft-365-app-certification/azure/806359be-da23-4538-80bb-baa82107ec2d) |
>| email | delegated | Necessario per SSO da Teams | Identità degli utenti, necessaria per SSO | [806359be-da23-4538-80bb-baa82107ec2d](https://docs.microsoft.com/microsoft-365-app-certification/azure/806359be-da23-4538-80bb-baa82107ec2d) |
>| openid | delegated | Necessario per SSO da Teams | Identità degli utenti, necessaria per SSO | [806359be-da23-4538-80bb-baa82107ec2d](https://docs.microsoft.com/microsoft-365-app-certification/azure/806359be-da23-4538-80bb-baa82107ec2d) |
>| profile | delegated | Necessario per SSO da Teams | Identità degli utenti, necessaria per SSO | [806359be-da23-4538-80bb-baa82107ec2d](https://docs.microsoft.com/microsoft-365-app-certification/azure/806359be-da23-4538-80bb-baa82107ec2d) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>I log vengono utilizzati a scopo di supporto e vengono conservati per 30 giorni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Nessuno

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Voice Elements Corporation sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/><br/> |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
