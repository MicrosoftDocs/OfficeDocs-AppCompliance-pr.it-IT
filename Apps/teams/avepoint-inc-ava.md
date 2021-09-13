---
title: Informazioni sull'applicazione per AVA di AvePoint, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per AVA, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 462181d4ba98d11e5aeae15a4827c6138bc80924
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283495"
---
# <a name="ava"></a>AVA

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 23, 2020</p>

* <a href="https://teams.microsoft.com/l/app/93106045-6f96-41e3-8a9d-694b6bbcac60" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381883" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da AvePoint, Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | AVA |
| ID | WA104381883 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | AvePoint, Inc. |
| URL del sito Web del partner | [https://www.avepoint.com/](https://www.avepoint.com/) |
| URL della Teams info dell'applicazione | [https://www.avepoint.com/support/](https://www.avepoint.com/support/) |
| URL dell'informativa sulla privacy | [https://www.avepoint.com/company/privacy-policy/](https://www.avepoint.com/company/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://www.avepoint.com/company/terms-of-use](https://www.avepoint.com/company/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da AvePoint, Inc. Sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Mail.ReadWrite.Shared | delegated | Nessuno | Cerca nei messaggi di posta elettronica dell'utente e sposta il messaggio nella cartella specificata | [6f30434d-3cfa-4cf8-9810-6fcf79ae750a](https://docs.microsoft.com/microsoft-365-app-certification/azure/6f30434d-3cfa-4cf8-9810-6fcf79ae750a) |
>| User.Read | delegated |  Token di accesso dell'utente - usato per cercare e ripristinare i dati dell'utente | Consente all'utente di accedere e assegnare il token di accesso all'app | [6f30434d-3cfa-4cf8-9810-6fcf79ae750a](https://docs.microsoft.com/microsoft-365-app-certification/azure/6f30434d-3cfa-4cf8-9810-6fcf79ae750a) |
>| User.ReadWrite | delegated | DisplayName, UserPrincipalName, JobTitle, Organization, Country, MySiteUrl - registrare le informazioni di base dell'utente che ha usato l'app | Ottenere le informazioni di base sul profilo dell'utente | [6f30434d-3cfa-4cf8-9810-6fcf79ae750a](https://docs.microsoft.com/microsoft-365-app-certification/azure/6f30434d-3cfa-4cf8-9810-6fcf79ae750a) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API REST di SharePoint | Sì | File di ricerca nel riciclo e ripristino di questi file nel sito personale dell'utente. Richiede l'autorizzazione AllSites.Manage. |  | Nessuno |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì, la posta elettronica e l'ID tenant dell'utente verranno visualizzati nei log. I log vengono archiviati in una posizione protetta e solo il personale autorizzato può accedere durante la risoluzione dei problemi. I log verranno archiviati dopo 60 giorni per scopi di controllo della sicurezza e verranno eliminati dopo un anno.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati dell'applicazione vengono archiviati in database SQL di Azure e Archiviazione di Azure. La SQL e Archiviazione di Azure azure sono abilitate.
Solo gli amministratori autorizzati possono accedere ai dati. L'autenticazione a più fattori è necessaria per l'accesso degli amministratori. Le operazioni vengono verificate. L'elenco indirizzi IP viene utilizzato anche per limitare l'accesso ai dati.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalogo vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

