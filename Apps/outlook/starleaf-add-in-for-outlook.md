---
title: Informazioni sull'applicazione per il componente aggiuntivo StarLeaf per Outlook da StarLeaf
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
description: Tutte le informazioni di sicurezza e conformità disponibili per il componente aggiuntivo StarLeaf per Outlook, i criteri di gestione dei dati, le informazioni sul catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ac1b9b979d9b6f8706e77baf22a73a784950eeaa
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095879"
---
# <a name="starleaf-add-in-for-outlook"></a>Componente aggiuntivo StarLeaf per Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381343" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da StarLeaf a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Componente aggiuntivo StarLeaf per Outlook |
| ID | WA104381343 |
| Office 365 client supportati | Outlook 2013 o versioni successive su Windows, Outlook 2016 o versione successiva su Mac, Outlook sul Web |
| Nome società partner | StarLeaf |
| URL del sito Web del partner | [https://www.starleaf.com/](https://www.starleaf.com/) |
| URL dell'informativa sulla privacy | [https://www.starleaf.com/privacy-policy](https://www.starleaf.com/privacy-policy) |
| URL delle Condizioni per l'utilizzo | [https://support.starleaf.com/legal-information/end-user-lic...](https://support.starleaf.com/legal-information/end-user-license-agreement-for-starleaf-applications) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da StarLeaf su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | application | archiviamo l'iCalUId delle riunioni, l'ora/data della riunione, gli indirizzi di posta elettronica dei partecipanti e una proprietà estesa a valore singolo che leggiamo e scriviamo sulla riunione utilizzando l'interfaccia delle proprietà personalizzate di Office.js. L'iCalUId viene utilizzato per correlare la riunione in un calendario&#8217;outlook dell'utente con la riunione video nel servizio. L'ora/data e i partecipanti vengono utilizzati per fornire una riunione video al momento giusto alle persone giuste nel nostro servizio. SVEP viene usato con il componente aggiuntivo di O365 per fornire un'interfaccia per gli utenti per impostare i dettagli sulla riunione video nel servizio, ad esempio la registrazione. | usato per sottoscrivere le notifiche webhook per tenere traccia delle modifiche degli utenti agli eventi nei propri calendari e aggiornare il servizio per mantenerlo coerente. Viene usato anche per creare eventi nel calendario quando un utente interagisce con l'app Teams e pianifica una riunione nel servizio. | 6e86b349-768f-4953-ac2e-fb03f92db4be |
>| User.Read | application | archiviamo il token di aggiornamento oauth per poter eseguire l'accesso. Archiviamo l'ID del profilo degli utenti per essere in grado di confrontare i futuri tentativi OAuth da parte di tale utente e garantire che non&#8217;archiviare i dettagli due volte.  | consentire agli utenti di accedere all'app e consente all'app di ottenere l&#8217;'indirizzo di posta elettronica dell'utente per correlare l'accesso con un account nel servizio.  | 6e86b349-768f-4953-ac2e-fb03f92db4be |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutte le informazioni non servizi Microsoft OII vengono trasferite a** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento di OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| In caso di problemi di supporto tecnico, i dati organizzativi possono essere trasferiti a SalesForce per la gestione dei casi. Se l'utente utilizza la funzionalità di accesso remoto PSTN, la chiamata scorrerà attraverso Twilio, Plivo o Voxbone |  | N/D |



#### <a name="add-in-data-access"></a>Accesso ai dati del componente aggiuntivo

Elenca le autorizzazioni richieste da questa app per accedere ai dati dell'organizzazione, la giustificazione e lo scopo di questa autorizzazione (per cosa l'app usa queste informazioni?) e se l'app archivia queste informazioni nei relativi database.

>| **Autorizzazione**  | **Descrizione** |
>|:----------------|:----------------|
>| Elemento ReadWrite | Questo componente aggiuntivo può accedere e modificare le informazioni personali nel messaggio attivo, ad esempio il corpo, l'oggetto, il mittente, i destinatari e le informazioni sugli allegati. Può inviare questi dati a un servizio di terze parti. Gli altri elementi nella cassetta postale&#8217;non possono essere letti o modificati. |
>| Invia dati | Può inviare dati tramite Internet |

#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì. I registri includono nomi utente, indirizzi IP, record di dettagli chiamata, informazioni sulla qualità della connessione (perdita di pacchetti, velocità in bit), tipo di dispositivo, stato delle chiamate. Le informazioni sono disponibili per il team di supporto tecnico e gli sviluppatori senior per la diagnosi dei problemi del servizio. I dati vengono anonimi dopo 90 giorni. I controlli per proteggere questi dati vengono controllati in base alla certificazione ISO/IEC 27001.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati vengono archiviati nei server di log di StarLeaf&#8217;nel data center in cui si trova l'account dell'utente&#8217;ed è stato eseguito il backup in uno o più data center nella stessa giurisdizione. L'accesso ai dati è tramite un singolo account utente che utilizza password per utente, che vengono controllate in base alla forza. Gli account utente di&#8217;StarLeaf vengono controllati automaticamente rispetto ai sistemi HR e ai gruppi di Active Directory aziendali per avvisare il team di sicurezza e conformità in caso di anomalie.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

