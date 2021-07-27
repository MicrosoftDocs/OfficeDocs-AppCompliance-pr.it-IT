---
title: Informazioni sull'applicazione per Fusion Remote di Jujo Inc.
ms.author: elmalova
author: elenamalova
ms.date: 10/12/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Fusion Remote, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b920e0fa93512c7cc9429b02dcecd9c0e3fe27b6
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521501"
---
# <a name="fusion-remote"></a>Fusion Remote

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: October 12, 2020</p>

* <a href="https://teams.microsoft.com/l/app/efc5c93b-304e-48ae-a695-2edd81bf45fb" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001422" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Jujo Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Fusion Remote |
| ID | WA200001422 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Jujo Inc. |
| URL del sito Web del partner | [https://www.jujotech.com](https://www.jujotech.com) |
| URL dell'informativa sulla privacy | [https://www.jujothech.com/privacy-policy](https://www.jujothech.com/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://www.jujotech.com/terms-of-use](https://www.jujotech.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Jujo Inc. Su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.Read | delegated | Leggere i file utente | Leggere i file utente | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| Files.Read.All | delegated | Lettura di tutti i file a cui l'utente può accedere | Lettura di tutti i file a cui l'utente può accedere | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| Files.Read.Selected | delegated | Leggere i file selezionati dall'utente | Leggere i file selezionati dall'utente | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| Files.ReadWrite | delegated | Avere accesso completo ai file utente | Avere accesso completo ai file utente | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| Files.ReadWrite.All | delegated | Avere accesso completo a tutti i file a cui l'utente può accedere | Avere accesso completo a tutti i file a cui l'utente può accedere | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| Files.ReadWrite.AppFolder | delegated | Avere accesso completo alla cartella dell'applicazione (anteprima) | Avere accesso completo alla cartella dell'applicazione (anteprima) | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| Files.ReadWrite.Selected | delegated | Lettura e scrittura dei file selezionati dall'utente | Lettura e scrittura dei file selezionati dall'utente | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| User.Read | delegated | Accedere e leggere il profilo utente | Accedere e leggere il profilo utente | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| User.Read.All | delegated | Leggere i profili completi di tutti gli utenti | Leggere i profili completi di tutti gli utenti | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| User.ReadBasic.All | delegated | Leggere i profili di base di tutti gli utenti | Leggere i profili di base di tutti gli utenti | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| User.ReadWrite | delegated | Accesso in lettura e scrittura al profilo utente | Accesso in lettura e scrittura al profilo utente | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| User.ReadWrite.All | delegated | Lettura e scrittura dei profili completi di tutti gli utenti | Lettura e scrittura dei profili completi di tutti gli utenti | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| offline_access | delegated | Mantenimento dell'accesso ai dati a cui è stato concesso l'accesso | Mantenimento dell'accesso ai dati a cui è stato concesso l'accesso | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| openid | delegated | Accedere agli utenti | Accedere agli utenti | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Elenco riunioni | NESSUN DATO ARCHIVIATO NEL DATABASE |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I DATI VENGONO CRITTOGRAFATI NEL TRASPORTO E IN PAUSA. PMA È IMPIEGATO E GLI ACCOUNT AMMINISTRATORE POSSONO ESSERE ACCESSIBILI SOLO DA UNA GAMMA LIMITATA DI INDIRIZZI IP NELLA WHITELIST

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36077' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36077" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

