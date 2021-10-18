---
title: Informazioni sull'applicazione per MailClark di MailClark
ms.author: elmalova
author: elenamalova
ms.date: 04/29/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per MailClark, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ece7ceb2478b0d374e1ab6241d87199b06999b4e
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60444476"
---
# <a name="mailclark"></a>MailClark

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/64f174e8-7e14-4b48-871e-2fb7b17be302" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381679" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da MailClark a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | MailClark |
| ID | WA104381679 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | MailClark |
| URL del sito Web del partner | [https://mailclark.ai/microsoft-teams-integration](https://mailclark.ai/microsoft-teams-integration) |
| URL della Teams info dell'applicazione | [https://mailclark.ai/support](https://mailclark.ai/support) |
| URL dell'informativa sulla privacy | [https://mailclark.ai/privacy](https://mailclark.ai/privacy) |
| URL delle Condizioni per l'utilizzo | [https://mailclark.ai/tos](https://mailclark.ai/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da MailClark su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Mail.ReadWrite | application |  | Lettura: Per sottoscrivere le notifiche push per i messaggi di posta elettronica in arrivo. Scrittura: per creare bozze. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.Send | application |  | Per inviare bozze. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | application | Dettagli dell'account, ad esempio indirizzo di posta elettronica. | Per identificare l'account. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| offline_access | application | Token di aggiornamento | Per rinnovare l'autenticazione fino alla disconnessione dell'account. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| openid | application |  | Obbligatorio per l'autenticazione. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| profile | application |  | Per autenticare l'utente. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Per assegnare persone alle conversazioni | Nome, cognome, nome visualizzato, indirizzo di posta elettronica |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>ID tenant, ID utente (indirizzo di posta elettronica)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Come parte della conformità al GDPR, gli amministratori possono richiedere eliminazioni, accesso ai dati e altro ancora (per informazioni dettagliate, vedere Scheda Legale).


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35675' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35675" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

