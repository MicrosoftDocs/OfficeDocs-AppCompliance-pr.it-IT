---
title: Informazioni sull'applicazione per Smartsheet per Smartsheet
ms.author: elmalova
author: elenamalova
ms.date: 11/11/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e conformità disponibili per Smartsheet, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d8bbe31189a44c240bc648670a0a04e0b5fce6ec
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429063"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Smartsheet a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Smartsheet |
| ID | WA104380975 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Smartsheet |
| URL del sito Web del partner | [https://www.smartsheet.com](https://www.smartsheet.com) |
| URL della Teams info dell'applicazione | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| URL dell'informativa sulla privacy | [https://www.smartsheet/legal/privacy](https://www.smartsheet/legal/privacy) |
| URL delle Condizioni per l'utilizzo | [https://Default Contratto per l'utente: https://www.smartsheet.com/.. .](https://Default User Agreement: https://www.smartsheet.com/legal/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Smartsheet su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.ReadWrite.All | delegated | Nessuna. | Consente all'app di installare le app per conto dell'utente. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| Directory.Read.All | delegated | tenantId per il recupero delle informazioni da visualizzare nell'interfaccia utente. | Ci consente di leggere le app in uso da questo tenant in modo da poter controllare se è necessario installare l'app per loro. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| Group.Read.All | delegated | teamId/groupId per il recapito dei messaggi. | Consente alla nostra app di leggere informazioni di base su un gruppo (o Teams team) e sulle conversazioni. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| Group.ReadWrite.All | delegated | teamId/groupId per il recapito dei messaggi. | Consente all'app di avviare nuove conversazioni nei team. Questa autorizzazione include anche l'ambito Read.All precedente, ma è necessaria anche per motivi tecnici. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| User.Read.All | delegated | userId. | Ci consente di leggere le informazioni di base su un utente durante il processo di autenticazione. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| offline_access | delegated | refreshToken. | Consente alla nostra app di ricevere token di aggiornamento e aggiornare il token di autenticazione per conto dell'utente quando usa l'app. | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API Bot Framework | Sì | Usiamo l'API Bot Framework per recapitare i messaggi come app per l'app teams. Smartsheet archivia le informazioni userId per tenere traccia di chi sta parlando il bot Smartsheet. |  | Nessuno |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Smartsheet archivia le informazioni in uno stato di rest crittografato all'interno dell'ambiente di data center di produzione ospitato con Equinix e in AWS S3 in cui archiviamo gli allegati dei clienti in bucket crittografati privati. |  | Usiamo l'API del framework bot per recapitare i messaggi come app per l'app teams. Smartsheet archivia le informazioni userId per tenere traccia di chi sta parlando il bot Smartsheet. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Smartsheet lo usa per tenere traccia di chi parla anche il bot. Durante il flusso di autenticazione iniziale, creiamo un record bot per l'utente nel sistema di notifica Smartsheet. | Per Smartsheet per Teams bot, archiviamo la posta elettronica dell'utente e l'id utente da Teams per tenere traccia di chi sta parlando con il bot.  In Smartsheet vengono archiviati tenantId per aiutare i gruppi di elenchi di cui l'utente fa parte nella directory e groupIds per il recapito dei messaggi. |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Smartsheet crittografa tutte le informazioni utente archiviate e i nostri amministratori devono usare la 2FA. Smartsheet opera come provider SaaS senza visualizzazione e, per impostazione predefinita, non vengono esaminati i contenuti che i clienti decidano di caricare o immettere nella piattaforma.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

