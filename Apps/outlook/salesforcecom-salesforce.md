---
title: Informazioni sull'applicazione per Salesforce per salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Salesforce, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 749e4cf95c8eefb650f6fd0f8ceb59721d7efcc8
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413528"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da salesforce.com a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Salesforce |
| ID | WA104379334 |
| Office 365 client supportati | Outlook 2013 o versioni successive Windows, Outlook 2016 o versioni successive su Mac, Outlook sul web |
| Nome società partner | salesforce.com |
| URL del sito Web del partner | [https://www.salesforce.com](https://www.salesforce.com) |
| URL dell'informativa sulla privacy | [https://www.salesforce.com/company/privacy/](https://www.salesforce.com/company/privacy/) |
| URL delle Condizioni per l'utilizzo | [https://www.salesforce.com/content/dam/web/en_us/www/docume...](https://www.salesforce.com/content/dam/web/en_us/www/documents/legal/Agreements/software-order-form-supplements/Salesforce_Outlook_TOU_Order_Form_Addendum.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da salesforce.com su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft necessarie](https://docs.microsoft.com/graph/permissions-reference) per questa app.

>Questa applicazione non utilizza Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API JavaScript per Office | Sì | Il componente aggiuntivo utilizza le funzioni di Office.js ed EWS per copiare il contenuto e gli allegati di un messaggio di posta elettronica che un utente Outlook ha deciso di accedere a Salesforce. Funzionalità simili vengono utilizzate sul lato calendario per registrare gli appuntamenti in Salesforce. | Il componente aggiuntivo utilizza le funzioni di Office.js ed EWS per copiare il contenuto e gli allegati di un messaggio di posta elettronica che un utente Outlook ha deciso di accedere a Salesforce. Funzionalità simili vengono utilizzate sul lato calendario per registrare gli appuntamenti in Salesforce. | Il componente aggiuntivo usa funzioni come getUserIdentityTokenAsync per ottenere l'identità utente corrente di Outlook, GetItem (.js ed EWS) per ottenere e impostare AdditionalProperties e il contenuto del messaggio di posta elettronica corrente durante il salvataggio nei record di Salesforce, GetAttachment (EWS) per recuperare gli allegati da Exchange e aggiungere alla posta elettronica di Salesforce associata, UpdateItem (.js), GetFolder (.js) per ottenere la cartella delle bozze,  CreateItem (.js), che viene utilizzato per creare una bozza di messaggio. | Il componente aggiuntivo usa funzioni come getUserIdentityTokenAsync per ottenere l'identità utente corrente di Outlook, GetItem (.js ed EWS) per ottenere e impostare AdditionalProperties e il contenuto del messaggio di posta elettronica corrente durante il salvataggio nei record di Salesforce, GetAttachment (EWS) per recuperare gli allegati da Exchange e aggiungere alla posta elettronica di Salesforce associata, UpdateItem (.js), GetFolder (.js) per ottenere la cartella delle bozze,  CreateItem (.js), che viene utilizzato per creare una bozza di messaggio. |
>| Servizi Web Exchange (EWS) | Sì | Il componente aggiuntivo utilizza le funzioni di Office.js ed EWS per copiare il contenuto e gli allegati di un messaggio di posta elettronica che un utente Outlook ha deciso di accedere a Salesforce. Funzionalità simili vengono utilizzate sul lato calendario per registrare gli appuntamenti in Salesforce. | Il componente aggiuntivo utilizza le funzioni di Office.js ed EWS per copiare il contenuto e gli allegati di un messaggio di posta elettronica che un utente Outlook ha deciso di accedere a Salesforce. Funzionalità simili vengono utilizzate sul lato calendario per registrare gli appuntamenti in Salesforce. | Il componente aggiuntivo usa funzioni come getUserIdentityTokenAsync per ottenere l'identità utente corrente di Outlook, GetItem (.js ed EWS) per ottenere e impostare AdditionalProperties e il contenuto del messaggio di posta elettronica corrente durante il salvataggio nei record di Salesforce, GetAttachment (EWS) per recuperare gli allegati da Exchange e aggiungere alla posta elettronica di Salesforce associata, UpdateItem (.js), GetFolder (.js) per ottenere la cartella delle bozze,  CreateItem (.js), che viene utilizzato per creare una bozza di messaggio. | Il componente aggiuntivo usa funzioni come getUserIdentityTokenAsync per ottenere l'identità utente corrente di Outlook, GetItem (.js ed EWS) per ottenere e impostare AdditionalProperties e il contenuto del messaggio di posta elettronica corrente durante il salvataggio nei record di Salesforce, GetAttachment (EWS) per recuperare gli allegati da Exchange e aggiungere alla posta elettronica di Salesforce associata, UpdateItem (.js), GetFolder (.js) per ottenere la cartella delle bozze,  CreateItem (.js), che viene utilizzato per creare una bozza di messaggio. |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzate.



#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>L'archiviazione salesforce è descritta nella Guida alla sicurezza all'indirizzo https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite da salesforce.com su come questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

