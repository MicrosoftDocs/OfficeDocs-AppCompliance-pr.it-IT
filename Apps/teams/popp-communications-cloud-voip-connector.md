---
title: Informazioni sull'applicazione per popp Cloud VoIP Connector by POPP Communications
ms.author: elmalova
author: elenamalova
ms.date: 10/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per il connettore VoIP cloud POPP, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c13790c3baa08d584343e9d504251e3920204b22
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/18/2021
ms.locfileid: "60438725"
---
# <a name="popp-cloud-voip-connector"></a>Connettore VoIP cloud POPP

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 20, 2021</p>

* <a href="https://teams.microsoft.com/l/app/b8e57f6b-31cf-468e-9e99-81f0395cb1f9" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003306" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da POPP Communications a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Connettore VoIP cloud POPP |
| ID | WA200003306 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Comunicazioni POPP |
| URL del sito Web del partner | [https://popp.com](https://popp.com) |
| URL dell'informativa sulla privacy | [https://popp.com/terms/privacy-policy/](https://popp.com/terms/privacy-policy/) |
| URL delle Condizioni per l'utilizzo | [https://popp.com/pvnterms/](https://popp.com/pvnterms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da POPP Communications su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.Read.All | delegated | ID utente e nomi visualizzati dei membri del canale corrente. L'app usa questa opzione per presentare all'utente un elenco di membri del canale da chiamare. | Metaswitch non archivia questi dati. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| Chat.Read | delegated |  Quali dati vengono raccolti o utilizzati? Aggiungere la giustificazione per la raccolta o l'utilizzo dei dati. ID utente e nomi visualizzati dei membri della chat corrente. L'app lo usa per presentare all'utente un elenco di membri della chat da chiamare. | Metaswitch non archivia questi dati. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| TeamMember.Read.All | delegated | ID utente e nomi visualizzati dei membri del team corrente. L'app lo usa per presentare all'utente un elenco di membri del team da chiamare. | Metaswitch non archivia questi dati. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| User.Read.All | delegated |  Quali dati vengono raccolti o utilizzati? Aggiungere la giustificazione per la raccolta o l'utilizzo dei dati. Numeri di telefono dell'azienda e del cellulare degli utenti. Questa operazione è necessaria per poter inizializzare le chiamate telefoniche a questi numeri. |   Metaswitch non archivia questi dati | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| openid | delegated | Un token di autorizzazione per l'utente, che autorizza l'app ad accedere agli altri endpoint api Graph elencati per loro conto. | Metaswitch non archivia questi dati. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Microsoft Identity Platform | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Reti metaswitch e comunicazioni POPP | L'interfaccia OII seguente viene trasferita al server MCT Hosted Bot: Azure AD tenant ID team ID Canale/ID chat Vengono trasferiti anche i contenuti dei messaggi, che potrebbero includere OII Il seguente OII può essere trasferito all'API JSON CommPortal: Telefono numero di utenti in un gruppo aziendale I domini di indirizzi di posta elettronica Indirizzi IP degli utenti | Aggiungere una giustificazione per il motivo per cui è necessario trasferire OII L'app&#8217;scopo principale è facilitare le chiamate telefoniche. Se un utente tenta di effettuare una chiamata telefonica, queste informazioni devono essere fornite per accedere al proprio account CommPortal e correlare la chiamata all'utente corretto.  L'interfaccia OII trasferita al server MCT Hosted Bot è incorporata nell'API Bot Framework che viene usata per l'integrazione con Teams e non può essere evitata. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| L'app&#8217;scopo principale è facilitare le chiamate telefoniche. Se un utente tenta di effettuare una chiamata telefonica, è necessario fornire l'interfaccia EUII per tutte le parti della chiamata per stabilire la chiamata tra gli utenti di telefonia corretti. | No |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessun OII o EUII viene visualizzato nella telemetria o nei log delle applicazioni.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Metaswitch e POPP non archiviano i dati per un periodo di tempo superiore all'immediata necessità di caricare le pagine Web MCT da CommPortal Web. I dati non vengono conservati e vengono rimossi immediatamente.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da POPP Communications su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione?  | No |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Criteri di accesso condizionale nella misura in cui tale supporto viene fornito automaticamente dalla libreria MSAL utilizzata per l'autenticazione.  |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | Sì |
| L'app supporta la multi-tenancy? | No |
| L'app dispone di un client riservato? | No |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/><br/> |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
