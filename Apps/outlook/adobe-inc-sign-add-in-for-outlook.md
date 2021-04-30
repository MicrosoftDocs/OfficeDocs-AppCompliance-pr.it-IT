---
title: Application Information for Adobe Sign Add-In for Outlook by Adobe Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Tutte le informazioni di sicurezza e conformità disponibili per Adobe Sign Add-In per Outlook, i criteri di gestione dei dati, le informazioni sul catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5ae63ddb614784164870b24508e0782bce49dd48
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096015"
---
# <a name="adobe-sign-add-in-for-outlook"></a>Adobe Sign Add-In per Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381158" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Adobe Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Adobe Sign Add-In per Outlook |
| ID | WA104381158 |
| Office 365 client supportati | Outlook 2013 o versioni successive su Windows, Outlook 2016 o versione successiva su Mac, Outlook sul Web |
| Nome società partner | Adobe Inc. |
| URL del sito Web del partner | [https://www.adobe.com/](https://www.adobe.com/) |
| URL dell'informativa sulla privacy | [https://www.adobe.com/privacy/policy.html](https://www.adobe.com/privacy/policy.html) |
| URL delle Condizioni per l'utilizzo | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Adobe Inc. Su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | application | Abbiamo bisogno di dati dal messaggio di posta elettronica per estrarre il report di Adobe Sign History e Audit Trail di ogni transazione. https://helpx.adobe.com/sign/using/audit-reports-transaction-history.html | Per popolare il documento allegato, i messaggi di posta elettronica del mittente e del destinatario e il contenuto del messaggio dai messaggi di posta elettronica a Adobe Sign da inviare per la firma. Ciò consente di risparmiare tempo all'utente per digitare di nuovo i campi in Adobe Sign. Dopo la firma di un contratto, componi automaticamente un nuovo messaggio di posta elettronica per l'utente per inviare un messaggio di posta elettronica per informare i destinatari che la transazione è stata eseguita. |  |
>| People.Read | delegated |  | Per riempire automaticamente l'indirizzo di posta elettronica nell'esperienza invia per la firma, digitando alcune lettere iniziali, non è necessario che gli utenti di &quot; &quot; digitare l'intero messaggio di posta elettronica. |  |
>| User.Read | delegated |  | Per leggere il profilo dell'utente e associare il proprio profilo (fondamentalmente, la posta elettronica) al database in modo che possa usare Adobe Sign. |  |
>| offline_access | delegated |  | Per aggiornare il token di accesso, quando quello corrente è scaduto. Ad esempio, quando l'utente è in una finestra di invio per la firma e lo lascia inattivo per troppo tempo, è necessario aggiornare un nuovo token quando l'utente &quot; &quot; è attivo. |  |
>| openid | delegated | Email è l'identificatore univoco per gli utenti in Adobe Sign. Archiviamo l'ID di posta elettronica in modo da poter mappare tutte le attività dell'utente al suo record Adobe Sign.  | Per accedere all'utente per garantire il consenso per l'autorizzazione all'uso dell'app Adobe Sign. |  |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



#### <a name="add-in-data-access"></a>Accesso ai dati del componente aggiuntivo

Elenca le autorizzazioni richieste da questa app per accedere ai dati dell'organizzazione, la giustificazione e lo scopo di questa autorizzazione (per cosa l'app usa queste informazioni?) e se l'app archivia queste informazioni nei relativi database.

>| **Autorizzazione**  | **Descrizione** |
>|:----------------|:----------------|
>| ReadWrite Mailbox | Questo componente aggiuntivo può leggere o modificare il contenuto di qualsiasi elemento nella cassetta postale e creare nuovi elementi. Può accedere alle informazioni personali, ad esempio il corpo, l'oggetto, il mittente, i destinatari o gli allegati, in qualsiasi messaggio o elemento del calendario. Può inviare questi dati a un servizio di terze parti. |
>| Invia dati | Può inviare dati tramite Internet |

#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Nessuna. Non registriamo alcuna unità EUII o OII nella telemetria o nei log. Il processo è il nostro controllo di sicurezza che convalida che non stiamo facendo questo.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>Non abbiamo alcuna interazione dell'amministratore del cliente nel nostro sistema per l Microsoft Teams appalto.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

