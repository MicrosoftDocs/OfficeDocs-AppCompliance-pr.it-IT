---
title: Informazioni sull'applicazione per LawToolBox di LawToolBox.com Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per LawToolBox, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2e97d65822a5baeb0cd78101660084e4142e98ea
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553007"
---
# <a name="lawtoolbox"></a>LawToolBox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 16 dicembre 2019</p>

* <a href="https://teams.microsoft.com/l/app/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381656" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da LawToolBox.com Inc.

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | LawToolBox |
| ID | WA104381656 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | LawToolBox.com Inc. |
| URL del sito Web partner | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| URL della pagina Teams informazioni sull'applicazione | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718) |
| URL dell'Informativa sulla privacy | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| URL delle Condizioni d'uso | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da LawToolBox.com Inc.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | delegato |  | [Facoltativo] Leggi il calendario dell'utente. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| Calendars.ReadWrite | delegato |  | Per creare l'invito del calendario al calendario dell'utente. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| Calendars.ReadWrite.Shared | delegato |  | Per creare l'invito del calendario al calendario condiviso. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| Contatti.LetturaScrivi | delegato |  | [Facoltativo]- per leggere i contatti utente e connettere gli utenti dall'elenco contatti al gruppo. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| Contacts.ReadWrite.Shared | delegato |  | [Facoltativo]- per leggere gli utenti ha condiviso i contatti per servire l'elenco dei contatti rilevanti per il caso. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| Directory.AccessAsUser.All | delegato |  | [Facoltativo] Leggere le informazioni su gruppi e utenti come utente. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| Directory.ReadWrite.All | delegato |  | [Facoltativo] Leggere le informazioni su gruppi e utenti come utente. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| Files.Read | delegato |  | [Facoltativo] Leggi il controllo dell'OneDrive. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| Files.Read.All | delegato |  | [Optional]-Leggi il controllo dell'OneDrive. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| Files.ReadWrite | delegato |  | [Facoltativo]-Leggere e modificare i file nella finestra di dialogo di OneDrive. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| Files.ReadWrite.All | delegato |  | [Facoltativo] File di lettura/scrittura dell'OneDrive file associato alla questione. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| Group.ReadWrite.All | delegato | GroupID, GroupName, GroupEmail | Creiamo un gruppo per ogni materia creata nel nostro sistema. In questo modo l'utente archivia le informazioni relative alla materia nel gruppo, che a sua volta salva i propri dati nel proprio tenant. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| Mail.Read | delegato |  | [Facoltativo] [InProgress] Leggi l'email dell'utente per Matters. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| Mail.ReadWrite | delegato |  | [Facoltativo] [InProgress] Leggere/scrivere messaggi di posta elettronica per gli utenti. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| Mail.ReadWrite.Shared | delegato |  | [Facoltativo] [InProgress] Leggere/scrivere messaggi di posta elettronica per gli utenti. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| Mail.Invia | delegato |  | [Facoltativo] [InProgress] Inviare scadenze tramite posta elettronica come utente. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| Tasks.ReadWrite.Shared | delegato |  | [Optional]-[InProgress] Leggi le scadenze di scrittura come attività per gli utenti. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| User.Read | delegato |  | Leggere le informazioni dell'utente. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| User.ReadWrite | delegato |  | Leggere/scrivere le informazioni dell'utente. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| User.ReadWrite.All | delegato |  | Leggere/scrivere le informazioni dell'utente. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| e-mail | delegato | Posta elettronica, ID utente di Office365, IDO oggetto, ID Tenant. | Leggere l'indirizzo di posta elettronica dell'utente. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |
>| profilo | delegato |  | Leggere le informazioni del profilo utente. | 3ee373AA-62FA-4FC6-B11F-9627D5B4A73D |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Per identificare l'utente appena aggiunto nel team e verificare la presenza di un potenziale lead | Posta elettronica, IdUtevole |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>User Email,UserID, AccessToken, Raggruppa le informazioni nel registro di debug

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Conserviamo i record dei casi a meno che non riceviamo una richiesta di eliminazione dei dati.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

