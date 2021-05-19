---
title: Informazioni sull'applicazione per StarLeaf di StarLeaf
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni disponibili sulla sicurezza e la conformità per StarLeaf, le sue politiche di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza / conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9dc0761fa00e94d97f3d29b4ac85e1d607498288
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553837"
---
# <a name="starleaf"></a>StarLeaf

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 24 agosto 2020</p>

* <a href="https://teams.microsoft.com/l/app/220b3db0-e3be-40df-8148-f0e0c33a986a" target="_blank">Visualizza nel Teams negozio</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000185" target="_blank">Visualizza in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da StarLeaf a Microsoft:

| **Informazioni** | **risposta** |
|:----------------|:-------------|
| Nome dell'app | StarLeaf |
| ID | WA200000185 |
| Office 365 client supportati | Microsoft Teams |
| Nome della società partner | StarLeaf |
| URL del sito Web partner | [https://www.starleaf.com](https://www.starleaf.com) |
| URL dell'Informativa sulla privacy | [https://support.starleaf.com/legal-information/starleaf-pri...](https://support.starleaf.com/legal-information/starleaf-privacy-notice/) |
| URL delle Condizioni d'uso | [https://support.starleaf.com/legal-information/starleaf-clo...](https://support.starleaf.com/legal-information/starleaf-cloud-services-customer-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Come l'app gestisce i dati

Queste informazioni sono state fornite da StarLeaf su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per raccoglierlo?** | **I dati vengono archiviati? Giustificazione per conservarlo?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | applicazione | Viene archiviato l'iCalUId delle riunioni, l'ora/data della riunione, gli indirizzi di posta elettronica dei partecipanti e una proprietà estesa a valore singolo che leggiamo e scriviamo nella riunione utilizzando l'interfaccia delle proprietà personalizzate di Office.js. ICalUId viene utilizzato per correlare la riunione nel calendario di Outlook di un utente&#8217;con la riunione video sul servizio. L'ora/data e i partecipanti vengono utilizzati per fornire una riunione video al momento giusto alle persone giuste sul nostro servizio. SVEP sono abituati con il nostro componente aggiuntivo O365 per fornire agli utenti un'interfaccia per impostare dettagli sulla riunione video sul nostro servizio come la registrazione. | utilizzato per iscriversi alle notifiche webhook per tenere traccia delle modifiche degli utenti agli eventi nei loro calendari e aggiornare il nostro servizio per mantenerlo coerente. Viene anche utilizzato per creare eventi nel proprio calendario quando un utente interagisce con la nostra app Teams e pianifica una riunione sul nostro servizio. | 6e86b349-768F-4953-AC2E-FB03F92DB4BE |
>| User.Read | applicazione | archiviamo il token di aggiornamento oauth per poter accedere. Archiviamo l'ID profilo degli utenti per poter confrontare con i futuri tentativi OAuth di quell'utente e assicurarci&#8217;memorizzare i loro dettagli due volte.  | consentire agli utenti di accedere all'app e consente alla nostra app di ottenere l&#8217;invoro e-mail dell'utente per correlare il loro login con un account sul nostro servizio.  | 6e86b349-768F-4953-AC2E-FB03F92DB4BE |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft utilizzati

Se l'app trasferisce o condivide dati dell'organizzazione con un servizio non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, quali dati vengono trasferiti e includi una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>| **Tutti gli OII non servizi Microsoft non sono trasferiti** |  **Quale OII viene trasferito?** | **Giustificazione per il trasferimento dell'OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| In caso di problemi di supporto tecnico, i dati organizzativi possono essere trasferiti a SalesForce per la gestione dei casi. Se l'utente utilizza la funzione di accesso al sistema di accesso PSTN, la chiamata scorrerà attraverso Twilio, Plivo o Voxbone |  | N/D |

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo e-mail) di qualsiasi membro del team o della chat a cui è aggiunta. Questa app utilizza questa funzionalità?

>| **Giustificazione per l'accesso all'I EUII?**  | **L'III è memorizzato in database?** | **Giustificazione per la conservazione dell'III?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Il bot accede all'elenco del team per prenotare una riunione per conto dell'utente/organizzatore che prenota la riunione tramite il bot. Ciò consente a StarLeaf di offrire un'esperienza di partecipazione senza soluzione di continuità con un pulsante per partecipare alle riunioni. | Nome, cognome, indirizzo email. Ciò consente al bot StarLeaf di prenotare una riunione per conto dell'utente/host che ha interagito con il bot e di invitare gli altri membri del team alla riunione. |  |


#### <a name="telemetry-data"></a>Dati di telemetria

Nella telemetria o nei registri dell'applicazione vengono visualizzate informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII)? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì. I registri includono nomi utente, indirizzi IP, record di dettagli chiamata, informazioni sulla qualità della connessione (perdita di pacchetti, velocità in bit), tipo di dispositivo, stato delle chiamate. Le informazioni sono disponibili per il team di supporto tecnico e gli sviluppatori senior per la diagnosi dei problemi di servizio. I dati vengono resi anonimi dopo 90 giorni. I controlli per proteggere questi dati vengono controllati con la nostra certificazione ISO/IEC 27001.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le proprie informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, politica dell'utente finale, ecc.

>I dati vengono memorizzati sui server di log di StarLeaf&#8217;nel data center in cui si trova l&#8217;articolare e sottoposti a backup in uno o più data center all'interno della stessa giurisdizione. L'accesso ai dati è tramite un singolo account utente utilizzando password per utente che sono controllate in modo sicuro. Gli account utente&#8217;servizio di StarLeaf vengono controllati automaticamente in base ai sistemi HR e ai gruppi aziendali di Active Directory per avvisare il team di sicurezza e conformità se vengono rilevate anomalie.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli esseri umani sono coinvolti nella revisione o nell'analisi di dati di informazioni di identificazione dell'organizzazione (OII) raccolti o archiviati da questa app?

>Sì

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Di seguito sono [riportate Microsoft Cloud App Security informazioni](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) dal catalogo di Microsoft Cloud App Security.

<iframe height='1020' title='Microsoft Cloud App Security informazione' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">Visualizzare in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

