---
title: Application Information for Beesy by BeesApps
ms.author: elmalova
author: elenamalova
ms.date: 01/31/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per Beesy, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b4fca2218dfc87e1e268fa9d95a6e7c7e7d8349b
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60434455"
---
# <a name="beesy"></a>Beesy

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 6, 2020</p>

* <a href="https://teams.microsoft.com/l/app/03a513ab-60d8-4d27-8c9a-5182934a43bb" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001248" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da BeesApps a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Beesy |
| ID | WA200001248 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | BeesApps |
| URL del sito Web del partner | [https://www.beesapps.com/](https://www.beesapps.com/) |
| URL dell'informativa sulla privacy | [https://www.beesy.me/legal/privacypolicy_en.pdf](https://www.beesy.me/legal/privacypolicy_en.pdf) |
| URL delle Condizioni per l'utilizzo | [https://www.beesy.me/legal/termsofservice_en_v1.03.pdf](https://www.beesy.me/legal/termsofservice_en_v1.03.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da BeesApps su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegated | Archiviamo solo l'ID UPN per confrontare quello fornito richiedendo tramite un token AAD per verificare se l'account esiste nel sistema. | consente all'utente di accedere e consente all'app di accedere al proprio UPN per abilitare l'accesso invisibile all'utente | [d27f56ed-ddc7-4cf8-86ac-721b76c7d287](https://docs.microsoft.com/microsoft-365-app-certification/azure/d27f56ed-ddc7-4cf8-86ac-721b76c7d287) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Accedono a questi dati per fornire contesto al bot per registrare le azioni direttamente alla persona che chatta (il bot è un assistente virtuale). | Non vengono archiviati dati direttamente dall'elenco, il membro del team viene confrontato con una persona già integrata beesy.me dati del servizio, ma solo la corrispondenza. |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun log EUII o OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati vengono archiviati nei server dedicati, questi server sono accessibili solo tramite VPN di connessione privata, VPN protetta da certificato SSL e password, solo per l'amministratore. Altri server comunicano tramite vlan privato livello 2, server sempre dedicati.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35940' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35940" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

