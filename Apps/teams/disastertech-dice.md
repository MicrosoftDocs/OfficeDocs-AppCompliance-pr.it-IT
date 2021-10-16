---
title: Informazioni sull'applicazione per DisasterTech DICE di DisasterTech
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per DisasterTech DICE, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: fd0c7aeda8b245db0b222ffcfd4d59deb3d0374d
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411070"
---
# <a name="disastertech-dice"></a>DisasterTech DICE

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2020</p>

* <a href="https://teams.microsoft.com/l/app/7df3e67b-ed62-48e9-a950-c95bd7ebce80" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001909" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da DisasterTech a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | DisasterTech DICE |
| ID | WA200001909 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | DisasterTech |
| URL del sito Web del partner | [https://www.disastertech.com](https://www.disastertech.com) |
| URL dell'informativa sulla privacy | [https://dice.disastertech.com/privacy.html](https://dice.disastertech.com/privacy.html) |
| URL delle Condizioni per l'utilizzo | [https://dice.disastertech.com/tos.html](https://dice.disastertech.com/tos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da DisasterTech su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegated | Indirizzo di posta elettronica utente archiviato per la definizione dei diritti di accesso e nome utente per identificare gli utenti in base al nome | Consente all'utente di accedere e consente all'app di accedere all'UPN per abilitare l'accesso invisibile all'utente, oltre Teams login, anche per stabilire nomi utente e indirizzi di posta elettronica. | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| email | delegated | Nessuno | Obbligatorio per Teams single Sign-On | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| offline_access | delegated | Nessuno | Obbligatorio per Teams single Sign-On | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| openid | delegated | Nessuno | Obbligatorio per Teams single Sign-On | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| profile | delegated | Nessuno | Obbligatorio Teams Single Sign-On. | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Il nome utente, il nome e il cognome vengono archiviati in un database PostgreSQL ospitato da Azure per consentire agli utenti di collaborare nell'applicazione. I controlli sono che solo i dipendenti di Disaster Tech hanno accesso diretto al database. Quando un utente viene rimosso dall'applicazione, le informazioni vengono archiviate. Gli utenti mantengono il diritto di rimuovere i propri dati personali dal sistema in qualsiasi momento. Tuttavia, la rimozione di tali informazioni impedirebbe anche l'uso dell'applicazione.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati dell'applicazione vengono archiviati in un database PostgreSQL in Azure che viene crittografato in fase di ripristino. Nessun utente ha accesso diretto al database o all'API back-end. Tutte le chiamate API sono protette con un token di accesso di Active Directory.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


