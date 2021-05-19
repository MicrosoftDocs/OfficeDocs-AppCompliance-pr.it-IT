---
title: Informazioni sull'applicazione per Tryane Analytics di Tryane
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Tryane Analytics, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 265fa798414c907f25690252e1714bebfdbdde1b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551106"
---
# <a name="tryane-analytics"></a>Tryane Analytics

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 28 settembre 2020</p>

* <a href="https://teams.microsoft.com/l/app/87631b95-fcd9-46e9-8d86-3d5205c04fec" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001827" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Tryane a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Tryane Analytics |
| ID | WA200001827 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | Tryane |
| URL del sito Web partner | [https://tryane.com/en/produit/tat/](https://tryane.com/en/produit/tat/) |
| URL dell'Informativa sulla privacy | [https://tryane.com/tryane-analytics/privacy_policy.html](https://tryane.com/tryane-analytics/privacy_policy.html) |
| URL delle Condizioni d'uso | [https://tryane.com/tryane-analytics/terms_of_use.html](https://tryane.com/tryane-analytics/terms_of_use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Tryane su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ActivityFeed.Lettura | applicazione |  | Leggi tutte le attività degli utenti nei team | 9b03f15D-1219-4b2f-9699-640be54e1319 |
>| Channel.ReadBasic.All | applicazione |  | Tutti Elenca tutti i canali con nomi, descrizioni | 9b03f15D-1219-4b2f-9699-640be54e1319 |
>| ChannelMessage.Read.All | applicazione |  | Elencare tutti i messaggi dei canali&#8217; metadati | 9b03f15D-1219-4b2f-9699-640be54e1319 |
>| Directory.Read.All | applicazione |  | Identificare gli utenti con una licenza team nel tenant | 9b03f15D-1219-4b2f-9699-640be54e1319 |
>| Member.Read.Hidden | applicazione |  | Ottieni un elenco di tutti i team, i membri&#8217;team e le iscrizioni nascoste | 9b03f15D-1219-4b2f-9699-640be54e1319 |
>| Reports.Read.All | applicazione |  | Leggi tutte le attività degli utenti nei team | 9b03f15D-1219-4b2f-9699-640be54e1319 |
>| Team.ReadBasic.All | applicazione |  | Elencare tutti i canali e le proprietà dei team | 9b03f15D-1219-4b2f-9699-640be54e1319 |
>| User.Read | delegato | ID utente, Nome, Indirizzo di posta elettronica, Data di creazione. Archiviamo questi dati al fine di fornire analisi dei dati di utilizzo su Teams | Identificare l'utente corrente durante l'abbonamento | 9b03f15D-1219-4b2f-9699-640be54e1319 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>Non è possibile accedere all'I EUII.


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>La regola organizzativa descritta nei nostri standard di sicurezza IT e di codifica ci impedisce di visualizzare EUII e OII nei registri

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Dove/Come: Database di Azure/Azure per server PostgreSQL Who accedervi: l'applicazione e il controllo di autorizzazione degli amministratori di database: 
 - Controllo individuale dell'autorizzazione: RBAC
 - Controllo dell'autorizzazione di sistema: endpoint privati nelle reti virtuali di Azure

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

