---
title: Informazioni sull'applicazione per il connettore di confluenza spostando il lavoro in avanti
ms.author: elmalova
author: elenamalova
ms.date: 09/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per Il connettore di confluenza, i criteri di gestione dei dati, le informazioni sul catalogo app di Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: bcf00959b3f6e667adedf8dbffd017d01e1bbc65
ms.sourcegitcommit: d5c60e66355ffa8fb84565e565f8bb15a665a099
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/24/2021
ms.locfileid: "59785470"
---
# <a name="confluence-connector"></a>Connettore di confluenza

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 22, 2021</p>

* <a href="https://teams.microsoft.com/l/app/3c9fd7ca-5386-4179-9bb7-7fcdcc373017" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001604" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Move Work Forward to Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Connettore di confluenza |
| ID | WA200001604 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Move Work Forward |
| URL del sito Web del partner | [https://www.moveworkforward.com](https://www.moveworkforward.com) |
| URL della Teams info dell'applicazione | [https://www.moveworkforward.com/product/microsoft-teams-con...](https://www.moveworkforward.com/product/microsoft-teams-confluence-connector) |
| URL dell'informativa sulla privacy | [https://moveworkforward.com/privacy-policy](https://moveworkforward.com/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://www.moveworkforward.com/license-agreement/eula](https://www.moveworkforward.com/license-agreement/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Move Work Forward su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegated | Il nome e l'ID del canale vengono usati per inviare notifiche da Jira a Microsoft Teams. | L'ID del canale e il nome vengono archiviati per configurare le notifiche da Jira a Microsoft Teams. | [f3943662-e828-40ed-9c6e-369680fe421f](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3943662-e828-40ed-9c6e-369680fe421f) |
>| Teams. ReadBasic.All | delegated | L'autorizzazione viene utilizzata per consentire all'utente di selezionare uno di questi team aggiunti in Jira. | ID del team e nome da visualizzare nella schermata Configurazione in Jira. | [f3943662-e828-40ed-9c6e-369680fe421f](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3943662-e828-40ed-9c6e-369680fe421f) |
>| TeamsAppInstallation.ReadForTeam | delegated | Leggere le app Teams installate nei team. Quando si configura il recapito Microsoft Teams l'app può inviare a Teams con il bot installato. | Nothing | [f3943662-e828-40ed-9c6e-369680fe421f](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3943662-e828-40ed-9c6e-369680fe421f) |
>| User.Read | delegated | Consente all'utente di creare un canale di discussione con i colleghi e di @menzionare in un messaggio di canale | Nothing | [f3943662-e828-40ed-9c6e-369680fe421f](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3943662-e828-40ed-9c6e-369680fe421f) |
>| email | delegated | La posta elettronica viene utilizzata per associare gli utenti di Atlassian e Microsoft | Il messaggio di posta elettronica non viene archiviato. Utilizzato solo durante il processo di corrispondenza. | [f3943662-e828-40ed-9c6e-369680fe421f](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3943662-e828-40ed-9c6e-369680fe421f) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Saluta gli utenti per nome quando installi l'app. Abbinare Microsoft Teams e gli utenti di Atlante. | No |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Registriamo l'URL del tenant, che viene archiviato nei log per un massimo di 5 giorni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Lavoriamo solo con servizi che offrono garanzie rigorose sulla privacy dei dati.

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

Queste informazioni sono state fornite da Move Work Forward sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/><br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
