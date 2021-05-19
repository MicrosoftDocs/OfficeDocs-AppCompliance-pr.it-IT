---
title: Informazioni sull'applicazione per Smartsheet di Smartsheet
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Smartsheet, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ddf77e7e73cc0bef1a21e72d1db328a4845a12f5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551526"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 16 dicembre 2019</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Smartsheet a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Smartsheet |
| ID | WA104380975 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Smartsheet |
| URL del sito Web partner | [https://help.smartsheet.com/articles/2476201](https://help.smartsheet.com/articles/2476201) |
| URL della pagina Teams informazioni sull'applicazione | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| URL dell'Informativa sulla privacy | [https://www.smartsheet.com/privacy](https://www.smartsheet.com/privacy) |
| URL delle Condizioni d'uso | [https://www.smartsheet.com/user-agreement](https://www.smartsheet.com/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Smartsheet su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | delegato | Nessuna. | Consente alla nostra app di installare app per conto dell'utente. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Directory.Read.All | delegato | tenantId per il recupero delle informazioni da visualizzare nell'interfaccia utente. | Ci consente di leggere quali app sta usando questo tenant in modo da poter verificare se è necessario installare l'app per loro. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.Read.All | delegato | teamId/groupId per il recapito dei messaggi. | Consente alla nostra app di leggere le informazioni di base su un gruppo (o Teams team) e le conversazioni. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.ReadWrite.All | delegato | teamId/groupId per il recapito dei messaggi. | Consente alla nostra app di avviare nuove conversazioni nei team. Questa autorizzazione include anche l'ambito Read.All di cui sopra, ma abbiamo bisogno anche di questo per motivi tecnici. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| User.Read.All | delegato | iduteute.d. | Consente di leggere le informazioni di base su un utente durante il processo di autenticazione. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| offline_access | delegato | refreshToken. | Consente alla nostra app di ricevere token di aggiornamento e aggiornare il token di autenticazione per conto dell'utente quando utilizza l'app. | c68947ae-a07f-44ce-9a13-7b559251731d |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati tramite altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono utilizzare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni di identificazione dell'organizzazione ( OII). Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **OII viene raccolto?** |  **Quale OII viene raccolto?** | **Giustificazione per la raccolta di OII?** | **OII è memorizzato?** | **Giustificazione per l'archiviazione di OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API Bot Framework | Sì | Usiamo l'API Bot Framework per recapitare i messaggi come app per l'app teams. Smartsheet archivia le informazioni userId per tenere traccia di chi sta parlando con il bot Smartsheet. |  | Nessuno |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft non sono trasferiti** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Smartsheet memorizza le informazioni in uno stato di riposo crittografato all'interno del nostro ambiente di data center di produzione ospitato con Equinix e in AWS S3, dove archiviamo gli allegati dei clienti in bucket crittografati privati. |  | Usiamo l'API del framework bot per recapitare i messaggi come app per l'app teams. Smartsheet archivia le informazioni userId per tenere traccia di chi sta parlando con il bot Smartsheet. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Smartsheet lo usa per tenere traccia anche di chi sta parlando il bot. Durante il flusso di autenticazione iniziale, creiamo un record bot per l'utente nel sistema di notifica Smartsheet. | Per smartsheet per Teams bot, archiviamo la posta elettronica e l'id utente dell'utente Teams per tenere traccia di chi sta parlando il bot.  Smartsheet archivia gli ID tenant per aiutare a elencare i gruppi di cui l'utente fa parte nella directory e groupIds per il recapito dei messaggi. |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Smartsheet crittografa tutte le informazioni utente archiviate e i nostri amministratori sono tenuti a utilizzare 2FA. Smartsheet opera come provider SaaS senza visualizzazione e, per impostazione predefinita, non rivediamo i contenuti che i clienti scelgono di caricare o entrare nella piattaforma.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

