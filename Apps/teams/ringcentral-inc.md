---
title: Informazioni sull'applicazione per RingCentral di RingCentral, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per RingCentral, i relativi criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 823ebf982464166302bca0fcb7690f3b9b444a88
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429794"
---
# <a name="ringcentral"></a>RingCentral

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: May 18, 2021</p>

* <a href="https://teams.microsoft.com/l/app/2f285d77-896a-4c5f-901e-0902316003b5" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000135" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da RingCentral, Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | RingCentral |
| ID | WA200000135 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | RingCentral, Inc. |
| URL del sito Web del partner | [https://www.ringcentral.com](https://www.ringcentral.com) |
| URL della Teams info dell'applicazione | [https://www.ringcentral.com/apps/ringcentral-for-microsoft-...](https://www.ringcentral.com/apps/ringcentral-for-microsoft-teams) |
| URL dell'informativa sulla privacy | [https://www.ringcentral.com/legal/privacy-notice.html](https://www.ringcentral.com/legal/privacy-notice.html) |
| URL delle Condizioni per l'utilizzo | [https://www.ringcentral.com/legal/last-update-October-15-20...](https://www.ringcentral.com/legal/last-update-October-15-2019/eulatos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da RingCentral, Inc. Sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegated |  Consente all'applicazione di inviare gli inviti alle riunioni tramite il calendario | Nessuno | [ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |
>| offline_access | delegated |  Consente all'applicazione di ottenere e aggiornare il token oauth |  Token di accesso, token di aggiornamento per l'accesso all'API ms Graph | [ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |
>| User.Read | delegated |  Consente all'app di leggere un&#8217;di base (e-mail, nome) per fare corrispondenze di contatto alla fine. E consente all'utente di accedere e collegare il proprio account O365 con l'account RingCentral |  Posta elettronica, nome, cognome | [0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |
>| User.Read.All | delegated | Consente all'applicazione di leggere il profilo completo di un utente con numeri di telefono per effettuare chiamate telefoniche con i nostri servizi. | Nessuno | [0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Se usiamo un'altra organizzazione, controlliamo comunque le tue informazioni personali. E abbiamo controlli rigorosi in atto per assicurarsi che&#8217;correttamente protetto. Infine, la sezione precedente descrive le situazioni in cui le informazioni personali vengono condivise con altre organizzazioni, enti pubblici e forze dell'ordine.  Quando condividiamo le tue informazioni con altre organizzazioni,&#8217;garantiremo che&#8217;protetto, per quanto ragionevolmente possibile.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11833' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11833" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da RingCentral, Inc. Sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
