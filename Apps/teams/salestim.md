---
title: Informazioni sull'applicazione per SalesTim di SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per SalesTim, i relativi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c9094f50723c7094f895d21f8a9569dedbb5863b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553917"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Ultimo aggiornamento da parte dello sviluppatore: 27 ottobre 2020</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da SalesTim a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | SalesTim |
| ID | WA200001393 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | SalesTim |
| URL del sito Web partner | [https://www.salestim.com](https://www.salestim.com) |
| URL dell'Informativa sulla privacy | [https://www.salestim.com/legal/privacy](https://www.salestim.com/legal/privacy) |
| URL delle Condizioni d'uso | [https://www.salestim.com/legal/tos](https://www.salestim.com/legal/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da SalesTim su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | delegato | No | Consenti all'app di installare e aggiornare i propri pacchetti nel catalogo delle app aziendali. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | delegato | Non&#8217;solo alcuni ID utente, non i dati del profilo. | Consente a un utente di selezionare altri utenti in varie posizioni dell'applicazione, ad esempio selezionando gli approvatori in un flusso di lavoro. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | delegato | Non&#8217;solo gli ID gruppi/team, non&#8217;archiviando i contenuti di gruppi/team. | Consente all'app di creare gruppi, leggere tutte le proprietà e le appartenenze dei gruppi per conto dell'utente che ha effettuato l'accesso. Inoltre, consente ai proprietari dei gruppi di gestire i propri gruppi e consente ai membri del gruppo di aggiornare il contenuto del gruppo. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Invia | delegato | È&#8217;i metadati di questa azione, ad esempio la data di notifica, il destinatario (solo ID), l'ID richiesta. | Consente all'app di inviare messaggi di posta elettronica di notifica, ad esempio durante un flusso di lavoro di approvazione. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | delegato | Stiamo usando alcuni servizi di Azure per archiviare i dati, in particolare Redis in Azure e Cosmos DB | Consente all'app di gestire le unità (file e cartelle) associate a un team, durante un processo di provisioning del team. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | delegato | Non&#8217;solo alcuni ID utente, non i dati del profilo. | Consente all'app di leggere il set completo di proprietà del profilo, report e gestori di qualsiasi utente. Viene utilizzato soprattutto durante il processo di targeting del pubblico, per filtrare alcuni contenuti in base al profilo utente corrente. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| accesso offline | delegato | No | Consente all'app di eseguire alcune operazioni e azioni in background come utente. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft non sono trasferiti** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Stiamo usando Intercom come applicazione di supporto principale. Intercom può contenere alcune informazioni di base del profilo utente, come descritto di seguito: https://developers.salestim.com/platform/datamanagement.html#support-data |  | Stiamo usando le API GitHub generare automaticamente problemi dal nostro ambiente di produzione. Stiamo anche memorizzando alcuni registri tecnici in GitHub (come descritto qui: https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) . Questi problemi e registri possono contenere alcune informazioni di base sul profilo utente. Questi problemi e registri vengono eliminati automaticamente ogni 15 giorni. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>Non è possibile accedere all'I EUII.


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Tutti i dati raccolti sono descritti qui: https://developers.salestim.com/platform/datamanagement.html#application-data Come descritto, i registri vengono temporaneamente memorizzati per 15 giorni, quindi eliminati automaticamente.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>La maggior parte dei dati viene archiviata in Azure Cosmos DB.
L'accesso all'ambiente di produzione è limitato a due persone e questi account di amministratore vengono applicati all'autenticazione a più fattori.
Questi account sono dedicati e diversi dai nostri account aziendali.
I dati vengono crittografati a riposo in tutti i servizi di Azure in uso.
Le distribuzioni negli ambienti di produzione vengono automatizzate tramite un ramo protetto dedicato nel nostro GitHub, in cui solo due persone possono approvare le modifiche.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

