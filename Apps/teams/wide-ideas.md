---
title: Informazioni sull'applicazione per idee ampie per idee ampie
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Wide Ideas, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 7d1186c5a9c17d2bf835569dad87e0f36aaf1d3c
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252216"
---
# <a name="wide-ideas"></a>Wide Ideas

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 3, 2020</p>

* <a href="https://teams.microsoft.com/l/app/2a64f929-bed9-44d9-aa65-d7b921889959" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000819" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Wide Ideas a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Wide Ideas |
| ID | WA200000819 |
| Funzionalità | Bot, scheda |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Wide Ideas |
| URL del sito Web del partner | [https://getwideideas.com](https://getwideideas.com) |
| URL dell'informativa sulla privacy | [https://getwideideas.com/privacy-policy](https://getwideideas.com/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://getwideideas.com/terms](https://getwideideas.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Wide Ideas su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | application | Salviamo l'ID gruppo e quali utenti appartengono a quali gruppi | Consente all'app di leggere i dati nella directory dell'organizzazione Clienti, ad esempio utenti e gruppi.  | 77baef51-6387-4aff-9b3f-23e4654c30cd |
>| Group.ReadWrite.All | application | Salviamo l'ID canale associato al gruppo. | Consente all'utente di creare team, canali e schede all'interno Microsoft Teams dal Portale per i clienti. In questo modo l'utente può anche sincronizzare i team Microsoft Teams nel Portale clienti. | 77baef51-6387-4aff-9b3f-23e4654c30cd |
>| User.Read | delegated | Salviamo il nome &amp; e-mail | Consente agli utenti di accedere e concedere l'accesso a Microsoft Graph per loro conto | 77baef51-6387-4aff-9b3f-23e4654c30cd |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutte le informazioni non servizi Microsoft OII vengono trasferite a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento di OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Mailjet Email che viene utilizzato per le notifiche di posta elettronica. |  | N/D |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Per creare utenti nel back-end e concedere le autorizzazioni per accedere al contenuto collegato al team. | We store: Name - To shown the name of the user, Email address - To identify the user |  |



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>I registri archiviano solo il numero IP. 

L'organizzazione può inviarci una richiesta come fornitore se desidera eliminare i dati.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Archiviazione dei dati: tutti i dati dei clienti vengono archiviati in Microsoft Azure servizi. Gli utenti devono essere autenticati a 2 fattori tramite Azure AD. L'accesso basato sui ruoli (RBAC) è attivo. Tutti gli accessi Microsoft Azure vengono effettuati rigorosamente tramite connessioni crittografate. Tutti i dati vengono crittografati a riposo. Tutti i servizi sono protetti da Azure Security Center. 

È inoltre disponibile un criterio di accesso in base al principio dei privilegi minimi. 


#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

