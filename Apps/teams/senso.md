---
title: Informazioni sull'applicazione per Senso by Senso
ms.author: elmalova
author: elenamalova
ms.date: 08/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Senso, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a44620633f9eee6c5d5e18997a58158a16c5e801
ms.sourcegitcommit: 7ef4a79aa28ac4dcce067b1f6f8693eeec6335e9
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/13/2021
ms.locfileid: "58245310"
---
# <a name="senso"></a>Senso

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 2, 2021</p>

* <a href="https://teams.microsoft.com/l/app/3973b9d4-b50e-472d-8145-8967e01379b4" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002571" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Senso a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Senso |
| ID | WA200002571 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Senso |
| URL del sito Web del partner | [https://www.senso.cloud](https://www.senso.cloud) |
| URL della pagina Teams informazioni sull'applicazione | [https://www.senso.cloud/safeguarding-microsoft-teams/](https://www.senso.cloud/safeguarding-microsoft-teams/) |
| URL dell'informativa sulla privacy | [https://www.senso.cloud/privacy](https://www.senso.cloud/privacy) |
| URL delle Condizioni per l'utilizzo | [https://www.senso.cloud/eula](https://www.senso.cloud/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Senso su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | application | Leggere i nomi e le descrizioni dei canali per identificare il punto in cui è stata contrassegnata una violazione.   | Quando si verifica una violazione, vengono registrati il nome del mittente (Da), i nomi dei destinatari (A), il nome del canale, la data, l'ora e i messaggi provenienti da tale canale di chat per fornire contesto a una violazione.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMember.Read.All | application | Leggere l'elenco dei membri e i messaggi di chat di tutti i canali. | Quando si verifica una violazione, vengono registrati il nome del mittente (Da), i nomi dei destinatari (A), il nome del canale, la data, l'ora e i messaggi provenienti da tale canale di chat per fornire contesto a una violazione.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMessage.Read.All | application | Leggere tutti i messaggi del canale | Quando si verifica una violazione, vengono registrati il nome del mittente (Da), i nomi dei destinatari (A), il nome del canale, la data, l'ora e i messaggi provenienti da tale canale di chat per fornire contesto a una violazione.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Chat.Read.All | application | Leggere tutti i messaggi di chat | Quando si verifica una violazione, vengono registrati il nome del mittente (Da), i nomi dei destinatari (A), il nome del canale, la data, l'ora e i messaggi provenienti da tale canale di chat per fornire contesto a una violazione.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Directory.Read.All | application | Lettura dei dati della directory | Quando si verifica una violazione, vengono registrati il nome del mittente (Da), i nomi dei destinatari (A), il nome del canale, la data, l'ora e i messaggi provenienti da tale canale di chat per fornire contesto a una violazione.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Files.Read.All | application | Leggere i file in tutte le raccolte siti | Quando si verifica una violazione, vengono registrati il nome del mittente (Da), i nomi dei destinatari (A), il nome del canale, la data, l'ora e i messaggi provenienti da tale canale di chat per fornire contesto a una violazione.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read | delegated | Accedere e leggere il profilo utente | Usato per l'accesso Single #A0 | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read.All | application | Leggere i profili completi di tutti gli utenti | Quando si verifica una violazione, vengono registrati il nome del mittente (Da), i nomi dei destinatari (A), il nome del canale, la data, l'ora e i messaggi provenienti da tale canale di chat per fornire contesto a una violazione.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione per il motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Senso.cloud utilizza i sottoprocessori seguenti per le prestazioni del servizio: https://www.senso.cloud/privacy-policy/ Sezione 5. Divulgazioni dei dati personali. | I tipi di dati condivisi con account di terze parti e provider di terze parti sono definiti nella sezione 5, colonna a destra della tabella ( https://www.senso.cloud/privacy-policy/) . | La base lecita per l'elaborazione di ognuno di essi si basa sulle prestazioni di un contratto con l'utente o necessaria per i nostri interessi legittimi (per l'esecuzione della nostra attività, l'archiviazione dei dati, la fornitura di servizi di amministrazione e IT, la sicurezza di rete, per evitare frodi e violazioni dei dati. Ad esempio, l'indirizzo di posta elettronica aziendale, l'indirizzo di posta elettronica è necessario per inviare le notifiche di contatto di fatturazione al cliente o se si paga con carta di credito, le informazioni sono necessarie per aumentare i ticket di supporto quando si accede al supporto tecnico. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Senso.cloud utilizza i sottoprocessori seguenti per le prestazioni del servizio: https://www.senso.cloud/privacy-policy/ Sezione 5. Divulgazioni dei dati personali. | I tipi di dati condivisi con account di terze parti e provider di terze parti sono definiti nella sezione 5, colonna a destra della tabella ( https://www.senso.cloud/privacy-policy/) . | La base lecita per l'elaborazione di ognuno di essi si basa sulle prestazioni di un contratto con l'utente o necessaria per i nostri interessi legittimi (per l'esecuzione della nostra attività, l'archiviazione dei dati, la fornitura di servizi di amministrazione e IT, la sicurezza di rete, per evitare frodi e violazioni dei dati. Ad esempio, l'indirizzo di posta elettronica aziendale, l'indirizzo di posta elettronica è necessario per inviare le notifiche di contatto di fatturazione al cliente o se si paga con carta di credito, le informazioni sono necessarie per aumentare i ticket di supporto quando si accede al supporto tecnico. |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Senso monitora i messaggi di chat in base alle librerie di rilevamento delle minacce di immagine e parole chiave.  Se si verifica una corrispondenza, registriamo le informazioni seguenti in base al trigger di violazione; Ora e data, ID sito, frase/immagine, gravità, Da, A, Nome canale, Stato e attivazione della raccolta per la revisione da parte dell'utente finale.  Manterremo le informazioni personali solo per tutto il tempo necessario per soddisfare gli scopi per i quali sono state raccolte, anche ai fini del soddisfacimento di eventuali requisiti legali, operativi, contabili o di reporting

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Accesso limitato agli sviluppatori senior, ip bloccati, autenticazione a 2 fattori e audit trail.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da Senso su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione dei dati?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Autorizzazioni di accesso basato sui ruoli |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/><br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
