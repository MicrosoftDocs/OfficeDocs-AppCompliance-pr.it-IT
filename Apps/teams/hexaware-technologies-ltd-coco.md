---
title: Informazioni sull'applicazione per COCO di Hexaware Technologies Ltd.
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
description: Tutte le informazioni di sicurezza e conformità disponibili per COCO, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: bd1965766fabddf8350010b3aefca2ebf9ceedbf
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095115"
---
# <a name="coco"></a>COCO

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: June 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/c3f021f9-1fe2-44c7-972e-58f3cd0e7762" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001468" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Hexaware Technologies Ltd. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | COCO |
| ID | WA200001468 |
| Funzionalità | Bot, scheda |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Hexaware Technologies Ltd. |
| URL del sito Web del partner | [https://hexaware.com/](https://hexaware.com/) |
| URL dell'informativa sulla privacy | [https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-...](https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf) |
| URL delle Condizioni per l'utilizzo | [https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-...](https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf#page=6) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Hexaware Technologies Ltd. sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.AccessAsUser.All | delegated | Nessuno | Accedere alla directory come utente connesso | 82eb2bf2-969c-46da-9e89-1db59ac4fbb3 |
>| Directory.Read.All | application | Nessuno | Leggere i dati della directory | 82eb2bf2-969c-46da-9e89-1db59ac4fbb3 |
>| Directory.ReadWrite.All | delegated | Nessuno | Lettura e scrittura dei dati della directory | 82eb2bf2-969c-46da-9e89-1db59ac4fbb3 |
>| User.Read | delegated | Nessuno | Accedere e leggere il profilo utente | 82eb2bf2-969c-46da-9e89-1db59ac4fbb3 |
>| User.Read.All | application | Nessuno | Leggere i profili completi di tutti gli utenti | 82eb2bf2-969c-46da-9e89-1db59ac4fbb3 |
>| User.ReadWrite.All | delegated | Nessuno | Lettura e scrittura dei profili completi di tutti gli utenti | 82eb2bf2-969c-46da-9e89-1db59ac4fbb3 |
>| openid | delegated | Nessuno | Accedere agli utenti | 82eb2bf2-969c-46da-9e89-1db59ac4fbb3 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Per gestire i dati della sessione | Nome, ID posta elettronica |  |



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>ND

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35906' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35906" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

