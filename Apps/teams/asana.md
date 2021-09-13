---
title: Informazioni sull'applicazione per Asana di Asana
ms.author: elmalova
author: elenamalova
ms.date: 11/02/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Asana, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 14ec3eee9b8ae673565ef91a017019d23d524619
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/12/2021
ms.locfileid: "59279949"
---
# <a name="asana"></a>Asana

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 2, 2020</p>

* <a href="https://teams.microsoft.com/l/app/f0e33e18-08fc-4511-a2a7-c6bdff367263" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001727" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Asana a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Asana |
| ID | WA200001727 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Asana |
| URL del sito Web del partner | [https://asana.com](https://asana.com) |
| URL dell'informativa sulla privacy | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://asana.com/terms#terms-of-service](https://asana.com/terms#terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Asana su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>Questa applicazione non utilizza Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti i file OII non servizi Microsoft vengono trasferiti a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Il componente aggiuntivo trasferisce le informazioni di posta elettronica di base (mittente, destinatario, oggetto, corpo) e gli allegati ad Asana quando richiesto dall'utente. |  | Posta elettronica : legge la posta elettronica attualmente aperta quando viene visualizzata in un riquadro attività. - Legge gli allegati di posta elettronica attualmente aperti da caricare nelle attività di Asana. - In questo modo gli utenti possono eseguire rapidamente attività in Asana con le informazioni dei messaggi di posta elettronica. |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>Non è possibile accedere all'UEII.


#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>L'applicazione registra solo le informazioni relative ai dati asana. L'unica volta che registriamo qualsiasi elemento correlato Outlook informazioni utente è quando l'utente allega esplicitamente un messaggio di posta elettronica o carica un allegato ad Asana e anche in questo caso non registriamo il contenuto. I log a breve termine sono presenti nei server che possono includere alcuni dati utente, ma sono effimeri e limitati a periodi inferiori a 72 ore.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Enterprise clienti hanno garantito la crittografia a riposo usando AES-256. I dati vengono archiviati in Amazon Web Services e AWS gestisce le chiavi di crittografia utilizzando il sistema di gestione delle chiavi. Abbiamo 2FA per tutti gli amministratori. L'accesso viene fornito in base al principio dei privilegi minimi.
Gli amministratori dell'organizzazione Asana hanno la possibilità di configurare saml, SCIM, account di servizio e di avere una visualizzazione generale dei dati inseriti nello strumento. Gli amministratori possono richiedere un'esportazione completa dell'organizzazione dalla Console di amministrazione e controllare in base alle esigenze.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

