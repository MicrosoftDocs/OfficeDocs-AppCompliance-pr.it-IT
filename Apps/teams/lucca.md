---
title: Informazioni sull'applicazione per Lucca di Lucca
ms.author: elmalova
author: elenamalova
ms.date: 09/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e conformità disponibili per Lucca, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c0ca2e6c6d07dd80afff02a4d9e5081e55633637
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60423168"
---
# <a name="lucca"></a>Lucca

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 23, 2021</p>

* <a href="https://teams.microsoft.com/l/app/53628f6a-ac66-4fde-8945-d639c8da4c0d" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001650" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Lucca a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Lucca |
| ID | WA200001650 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Lucca |
| URL del sito Web del partner | [https://www.lucca.fr](https://www.lucca.fr) |
| URL dell'informativa sulla privacy | [https://www.lucca.fr/privacy-policy](https://www.lucca.fr/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://cdn2.hubspot.net/hubfs/1582050/3-DOWNLOAD_FILES/Ter...](https://cdn2.hubspot.net/hubfs/1582050/3-DOWNLOAD_FILES/TermsAndConditions.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Lucca su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.Read.All | delegated | Non vengono raccolti dati. Sono stati usati per filtrare la pianificazione da visualizzare. Solo gli utenti che sono nel canale hanno la loro pianificazione visualizzata | Non vengono archiviati dati | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| Chat.ReadWrite | application | Non vengono raccolti o utilizzati dati. L'app pubblica solo un messaggio che contiene assenti del giorno | Non vengono archiviati dati | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| Group.Read.All | application | Raccogliamo GroupId per sapere in quale gruppo l'app deve inviare il messaggio con gli assenti.  | Archiviamo solo GroupId per salvare la configurazione effettuata dall'utente. Ci consente di sapere in quale gruppo inviare il messaggio | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| User.Read | delegated | Usato per accedere agli utenti | Non vengono archiviati dati | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| User.Read.All | application | Utilizzato per leggere i profili utente | Non vengono archiviati dati | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| email | delegated | Usato per visualizzare la posta elettronica dell'utente nella scheda dell'app | Non vengono archiviati dati | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| openid | delegated | Utilizzato per accedere all'utente | Non vengono archiviati dati | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| profile | delegated | Usato per visualizzare il profilo utente nella scheda dell'app | Non vengono archiviati dati | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |


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

>criteri per l'utente finale

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Lucca su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
