---
title: Informazioni sull'applicazione per Go1 di Go1
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
description: Tutte le informazioni di sicurezza e conformità disponibili per Go1, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c4aa471780bb83662032de178323c24036e2713c
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095165"
---
# <a name="go1"></a>Go1

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/c859de61-8a6b-42e6-ba88-f639df33bc72" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001484" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Go1 a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Go1 |
| ID | WA200001484 |
| Funzionalità | Bot, scheda, estensione per la messaggistica |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Go1 |
| URL del sito Web del partner | [https://www.go1.com/](https://www.go1.com/) |
| URL dell'informativa sulla privacy | [https://www.go1.com/en-au/terms/privacy-policy](https://www.go1.com/en-au/terms/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://www.go1.com/en-au/terms/user-terms](https://www.go1.com/en-au/terms/user-terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Go1 su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | application | l'app non archivia i dati dei file | consente agli utenti di caricare e condividere file da onedrive | c859de61-8a6b-42e6-ba88-f639df33bc72 |
>| Group.ReadWrite.All | application | Teams il nome del canale e l'ID univoco archiviati per supportare l'ambiente di apprendimento per la gestione dell'app | consente all'app di configurare in modo dinamico Teams e canali per supportare l'apprendimento strutturato in Teams ambiente | c859de61-8a6b-42e6-ba88-f639df33bc72 |
>| User.Read.All | application | nome degli utenti, posta elettronica e UPN archiviati per offrire un'esperienza di apprendimento personale diretta | consente di utilizzare per firmare e supportare la condivisione delle risorse di apprendimento tra i membri del team | c859de61-8a6b-42e6-ba88-f639df33bc72 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutte le informazioni non servizi Microsoft OII vengono trasferite a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento di OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Il nome e il cognome degli utenti possono essere condivisi con i provider di contenuti di GO1 durante la riproduzione del contenuto del corso. Questo viene condiviso solo quando il provider di contenuti lo richiede per creare un'esperienza di apprendimento personalizzata. |  | N/D |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>GO1 riduce al minimo l'archiviazione di qualsiasi informazione personale o organizzativa identificabile. I log delle applicazioni dettagliati che archiviano questi dati vengono eliminati entro 90 giorni dalla creazione.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>La 2FA è necessaria per tutti i sistemi del personale. Accesso al sistema GO1 gestito dal ruolo. Solo ai ruoli che richiedono l'accesso per eseguire i propri processi viene assegnato l'accesso ai sistemi di produzione. I criteri interni richiedono che i dati vengono sempre crittografati in transito e in pausa.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/16262' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/16262" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

