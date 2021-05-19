---
title: Informazioni sull'applicazione di Asana per Outlook di Asana
ms.author: elmalova
author: elenamalova
ms.date: 11/02/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per Asana per Outlook, i suoi criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza /conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cd3d403d7b25c1ad5dda60dff8d93c18dfe59c30
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553747"
---
# <a name="asana-for-outlook"></a>Asana per Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 2 novembre 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381833" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Asana a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | Asana per Outlook |
| ID | WA104381833 |
| Office 365 client supportati | Outlook 2016 o più tardi Windows, Outlook 2016 o più tardi su Mac, Outlook sul Web |
| Nome della società partner | Asana |
| URL del sito Web partner | [https://asana.com/](https://asana.com/) |
| URL dell'Informativa sulla privacy | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| URL delle Condizioni d'uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da Asana su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>Questa applicazione non utilizza Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft non sono trasferiti** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Il componente aggiuntivo trasferisce le informazioni di base sull'e-mail (mittente, recipiente, oggetto, corpo) e gli allegati ad Asana quando richiesto dall'utente. |  | Posta elettronica: legge la posta elettronica attualmente aperta quando viene visualizzata in un riquadro attività. - Legge gli allegati di posta elettronica attualmente aperti da caricare nelle attività di Asana. - Ciò offre agli utenti la possibilità di effettuare rapidamente attività ad Asana con informazioni dalle e-mail. |



#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>La nostra applicazione registra solo le informazioni relative ai dati Asana. L'unica volta che registriamo tutto ciò che riguarda le informazioni dell'utente Outlook è quando l'utente allega esplicitamente un'e-mail o carica un allegato ad Asana, e anche allora non registriamo il contenuto. I registri a breve termine esistono sui server che possono includere alcuni dati utente, ma sono effimeri e limitati a periodi inferiori a 72 ore.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>Enterprise clienti hanno garantito la crittografia a riposo utilizzando AES-256. I dati vengono archiviati su Amazon Web Services e AWS gestisce le chiavi di crittografia utilizzando il proprio sistema di gestione delle chiavi. Abbiamo 2FA per tutti gli amministratori. L'accesso è dato in base al principio del privilegio minimo.
Gli amministratori dell'organizzazione Asana hanno la possibilità di configurare SAML, SCIM, account di servizio e di avere una visualizzazione generale dei dati che vengono messi nello strumento. Gli amministratori possono richiedere un'esportazione organizzativa completa dall'interno della console di amministrazione e controllare in base alle esigenze.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

