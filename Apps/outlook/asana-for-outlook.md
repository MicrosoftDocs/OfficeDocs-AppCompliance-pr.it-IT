---
title: Informazioni sull'applicazione per Asana per Outlook da Asana
ms.author: elmalova
author: elenamalova
ms.date: 11/02/2020
ms.topic: article
ms.service: attestation
description: Tutte le informazioni di sicurezza e conformità disponibili per Asana per Outlook, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a166966dd5dfac55a13df3dded07bd056f3ab2ee
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095967"
---
# <a name="asana-for-outlook"></a>Asana per Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 2, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381833" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Asana a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Asana per Outlook |
| ID | WA104381833 |
| Office 365 client supportati | Outlook 2016 o versioni successive Windows, Outlook 2016 o versioni successive su Mac, Outlook sul Web |
| Nome società partner | Asana |
| URL del sito Web del partner | [https://asana.com/](https://asana.com/) |
| URL dell'informativa sulla privacy | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

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

>| **Tutte le informazioni non servizi Microsoft OII vengono trasferite a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento di OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Il componente aggiuntivo trasferisce le informazioni di posta elettronica di base (mittente, destinatario, oggetto, corpo) e gli allegati ad Asana quando richiesto dall'utente. |  | Posta elettronica : legge la posta elettronica attualmente aperta quando viene visualizzata in un riquadro attività. - Legge gli allegati di posta elettronica attualmente aperti da caricare nelle attività di Asana. - In questo modo gli utenti possono eseguire rapidamente attività in Asana con le informazioni dei messaggi di posta elettronica. |



#### <a name="add-in-data-access"></a>Accesso ai dati del componente aggiuntivo

Elenca le autorizzazioni richieste da questa app per accedere ai dati dell'organizzazione, la giustificazione e lo scopo di questa autorizzazione (per cosa l'app usa queste informazioni?) e se l'app archivia queste informazioni nei relativi database.

>| **Autorizzazione**  | **Descrizione** |
>|:----------------|:----------------|
>| Elemento ReadWrite | Questo componente aggiuntivo può accedere e modificare le informazioni personali nel messaggio attivo, ad esempio il corpo, l'oggetto, il mittente, i destinatari e le informazioni sugli allegati. Può inviare questi dati a un servizio di terze parti. Gli altri elementi nella cassetta postale&#8217;non possono essere letti o modificati. |
>| Invia dati | Può inviare dati tramite Internet |

#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>L'applicazione registra solo le informazioni relative ai dati asana. L'unica volta che registriamo qualsiasi elemento correlato Outlook informazioni utente è quando l'utente allega esplicitamente un messaggio di posta elettronica o carica un allegato ad Asana e anche in questo caso non registriamo il contenuto. I log a breve termine sono presenti nei server che possono includere alcuni dati utente, ma sono effimeri e limitati a periodi inferiori a 72 ore.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Enterprise clienti hanno garantito la crittografia a riposo usando AES-256. I dati vengono archiviati in Amazon Web Services e AWS gestisce le chiavi di crittografia utilizzando il sistema di gestione delle chiavi. Abbiamo 2FA per tutti gli amministratori. L'accesso viene fornito in base al principio dei privilegi minimi.
Gli amministratori dell'organizzazione Di Asana hanno la possibilità di configurare saml, SCIM, account di servizio e di avere una visualizzazione generale dei dati inseriti nello strumento. Gli amministratori possono richiedere un'esportazione completa dell'organizzazione dalla Console di amministrazione e controllare in base alle esigenze.

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

