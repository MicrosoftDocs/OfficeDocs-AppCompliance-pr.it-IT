---
title: Informazioni sull'applicazione per SalesTim di SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni di sicurezza e conformità disponibili per SalesTim, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b15cf2f87b6707b6fa82dfc3968444d7cad85e8a
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282078"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: October 27, 2020</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da SalesTim a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | SalesTim |
| ID | WA200001393 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | SalesTim |
| URL del sito Web del partner | [https://www.salestim.com/](https://www.salestim.com/) |
| URL dell'informativa sulla privacy | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| URL delle Condizioni per l'utilizzo | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da SalesTim su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.ReadWrite.All | delegated | NO | Consenti all'app di installare e aggiornare i propri pacchetti nel catalogo app aziendale. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Directory.AccessAsUser.All | delegated | È&#8217;solo alcuni ID utente, non i dati del profilo. | Consente a un utente di selezionare altri utenti in diverse posizioni dell'applicazione, ad esempio selezionando i responsabili approvazione in un flusso di lavoro. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Group.ReadWrite.All | delegated | È&#8217;solo l'archiviazione di gruppi/ID team,&#8217;non vengono archiviati i contenuti di gruppi/team. | Consente all'app di creare gruppi, leggere tutte le proprietà e le appartenenze del gruppo per conto dell'utente connesso. Consente inoltre ai proprietari dei gruppi di gestire i propri gruppi e consente ai membri del gruppo di aggiornare il contenuto del gruppo. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Mail.Send | delegated | Microsoft&#8217;i metadati di questa azione, ad esempio la data della notifica, il destinatario (solo ID), l'ID della richiesta. | Consente all'app di inviare messaggi di posta elettronica di notifica, ad esempio durante un flusso di lavoro di approvazione. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Sites.ReadWrite.All | delegated | Stiamo usando alcuni servizi di Azure per archiviare i dati, in particolare Redis in Azure e Cosmos DB | Consente all'app di gestire le unità (file e cartelle) associate a un team durante un processo di provisioning del team. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| User.Read.All | delegated | È&#8217;solo alcuni ID utente, non i dati del profilo. | Consente all'app di leggere il set completo di proprietà del profilo, report e responsabili di qualsiasi utente. Viene utilizzato soprattutto durante il processo di destinazione del gruppo di destinatari, per filtrare alcuni contenuti in base al profilo utente corrente. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| offlineaccess | delegated | No | Consente all'app di eseguire alcune operazioni e azioni in background come utente. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Stiamo usando Intercom come applicazione di supporto principale. Intercom può contenere alcune informazioni di base sul profilo utente, come descritto di seguito: https://developers.salestim.com/platform/datamanagement.html#support-data |  | Stiamo usando le API GitHub per generare automaticamente i problemi dall'ambiente di produzione. Vengono archiviati anche alcuni log tecnici in GitHub (come descritto qui: https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) . Questi problemi e registri possono contenere alcune informazioni di base sul profilo utente. Questi problemi e registri vengono eliminati automaticamente ogni 15 giorni. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Tutti i dati raccolti sono descritti qui: come descritto, i log vengono temporaneamente https://developers.salestim.com/platform/datamanagement.html#application-data archiviati per 15 giorni e quindi eliminati automaticamente.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>La maggior parte dei dati sono archiviati in Azure Cosmos DB.
L'accesso all'ambiente di produzione è limitato a due persone e questi account di amministratore vengono applicati a MFA.
Questi account sono dedicati e diversi dagli account aziendali.
I dati vengono crittografati a riposo in tutti i servizi di Azure in uso.
Le distribuzioni in ambienti di produzione vengono automatizzate tramite un ramo protetto dedicato nell'ambiente GitHub, in cui solo due persone possono approvare le modifiche.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

