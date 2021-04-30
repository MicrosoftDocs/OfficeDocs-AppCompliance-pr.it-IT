---
title: Application Information for Invoice and Time Tracking - Zoho Invoice by Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Tutte le informazioni di sicurezza e conformità disponibili per La fattura e il monitoraggio del tempo - Zoho Invoice, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 900935b6422b2a9e48ddb0a79c92c0b1f6b4d139
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095863"
---
# <a name="invoice-and-time-tracking---zoho-invoice"></a>Fattura e tracciabilità del tempo - Fattura Zoho

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381067" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Zoho Corporation Private Limited a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Fattura e tracciabilità del tempo - Fattura Zoho |
| ID | WA104381067 |
| Office 365 client supportati | Outlook 2013 o versioni successive su Windows, Outlook 2016 o versione successiva su Mac, Outlook sul Web |
| Nome società partner | Zoho Corporation Private Limited |
| URL del sito Web del partner | [https://www.zoho.com/](https://www.zoho.com/) |
| URL dell'informativa sulla privacy | [https://zoho.com/privacy.html](https://zoho.com/privacy.html) |
| URL delle Condizioni per l'utilizzo | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Zoho Corporation Private Limited su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Contacts.Read | delegated |  |  Consentire agli utenti di sincronizzare i contatti di Office365 con Zoho Invoice. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Mail.Read | delegated |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Mail.Send | delegated |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Export.All | delegated |  | Consentire all'utente di esportare tutte le informazioni correlate all'utente. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | delegated |  | Consentire agli utenti di accedere e leggere il profilo utente. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | delegated |  | Consentire agli utenti di importare gli utenti di Office365 in Zoho. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| e-mail | delegated |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profilo | delegated |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



#### <a name="add-in-data-access"></a>Accesso ai dati del componente aggiuntivo

Elenca le autorizzazioni richieste da questa app per accedere ai dati dell'organizzazione, la giustificazione e lo scopo di questa autorizzazione (per cosa l'app usa queste informazioni?) e se l'app archivia queste informazioni nei relativi database.

>| **Autorizzazione**  | **Descrizione** |
>|:----------------|:----------------|
>| Elemento di lettura | Questo componente aggiuntivo può accedere alle informazioni personali sul messaggio attivo, ad esempio i nomi dei mittenti, i nomi dei destinatari, gli indirizzi di posta elettronica, il corpo del messaggio e le informazioni sugli allegati. Il componente aggiuntivo può inviare questi dati a un servizio di terze parti. Gli altri elementi nella cassetta postale&#8217;non possono essere letti o modificati. |
>| Invia dati | Può inviare dati tramite Internet |

#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Non raccogliamo informazioni personali/informazioni personali in telemetria e log.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati verranno recuperati solo dopo il consenso dell'utente. L'accesso logico ai server viene fornito tramite una rete dedicata isolata &amp; ed è altamente protetto e monitorato. Questa rete è protetta con Firewall, Autenticazione a 2 fattori e Autenticazione Kerberos


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28305' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28305" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

