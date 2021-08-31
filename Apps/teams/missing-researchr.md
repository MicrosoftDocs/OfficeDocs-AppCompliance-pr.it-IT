---
title: Application Information for researcHR by KBE&#26666;&#24335;&#20250;&#31038;
ms.author: elmalova
author: elenamalova
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per il researcHR, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: b57d492945766c8d65417cf2f1d642ea4ecb8aae
ms.sourcegitcommit: 64333f4e583bacd85f1b47af6e1eaee266658924
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/20/2021
ms.locfileid: "58422734"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 5, 2021</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da KBE&#26666;&#24335;&#20250;&#31038; a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | researcHR |
| ID | WA200002557 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | KbE&#26666;&#24335;&#20250;&#31038; |
| URL del sito Web del partner | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| URL della Teams info dell'applicazione | [https://app.researchr.work](https://app.researchr.work) |
| URL dell'informativa sulla privacy | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| URL delle Condizioni per l'utilizzo | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da KBE&#26666;&#24335;&#20250;&#31038; su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | application | Questo ambito viene utilizzato per consentire al bot di creare un nuovo canale nel client Teams client. Vedi: https://docs.microsoft.com/en-us/graph/api/channel-post | Questi dati non vengono archiviati nel database. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Directory.Read.All | application | Usiamo questo ambito per ottenere gli ID e i nomi dei canali per visualizzare questi dati nel nostro sito Web. Vedi: https://docs.microsoft.com/en-us/graph/api/channel-list | Questi dati non vengono archiviati nel database. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Group.Read.All | application | Usiamo questo ambito per ottenere gli ID e i nomi dei canali per visualizzare questi dati nel nostro sito Web. Vedi: https://docs.microsoft.com/en-us/graph/api/channel-list | Questi dati non vengono archiviati nel database. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Team.ReadBasic.All | application | Questo ambito viene utilizzato per ottenere i membri del team in modo che gli utenti possano visualizzare i membri del team nel sito Web. Vedi: https://docs.microsoft.com/en-us/graph/api/group-list-members | Questi dati non vengono archiviati nel database in uscita. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| User.Read.All | application | Questo ambito viene utilizzato per ottenere i canali aggiunti dell'utente in modo che gli utenti possano visualizzare i team aggiunti nel sito Web. Vedi: https://docs.microsoft.com/en-us/graph/api/user-list-joinedteams | Questi dati non vengono archiviati nel database. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| User.ReadBasic.All | delegated | Questo ambito viene utilizzato per abilitare l'accesso OAuth e raccogliere l'ID AAD, il token di accesso e il token di aggiornamento dell'utente. Vedi: https://docs.microsoft.com/en-us/graph/auth-v2-user | L'ID AAD, il token di accesso e il token di aggiornamento dell'utente vengono archiviati nel database in modo che l'utente possa accedere al sito Web con OAuth. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| offline_access | delegated | Usiamo questo ambito per ottenere il token di aggiornamento in modo da poter aggiornare il token di accesso degli utenti autenticati senza alcuna interazione dell'utente. Vedi: https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-permissions-and-consent#offline_access | Il token di aggiornamento viene archiviato nel database in modo da poter aggiornare il token di accesso senza alcuna interazione dell'utente. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Tutti i dati nel database sono crittografati. I backup dei dati del database verranno evasi e archiviati per un determinato periodo di tempo in conformità ai criteri operativi interni. Nel caso in cui un utente annulli questo servizio, le informazioni dell'utente verranno eliminate senza indugio, tranne nella misura necessaria per adempiere agli obblighi di archiviazione previsti dalla legge. Ecco i dettagli. https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da KBE&#26666;&#24335;&#20250;&#31038; su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
