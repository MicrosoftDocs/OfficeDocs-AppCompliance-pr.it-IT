---
title: Informazioni sull'applicazione per StarLeaf di StarLeaf
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per StarLeaf, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b180c5c804831624caedb4404b85ca216549fd2f
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251095"
---
# <a name="starleaf"></a>StarLeaf

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 24, 2020</p>

* <a href="https://teams.microsoft.com/l/app/220b3db0-e3be-40df-8148-f0e0c33a986a" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000185" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da StarLeaf a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | StarLeaf |
| ID | WA200000185 |
| Funzionalità | Bot, estensione per la messaggistica |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | StarLeaf |
| URL del sito Web del partner | [https://www.starleaf.com](https://www.starleaf.com) |
| URL dell'informativa sulla privacy | [https://support.starleaf.com/legal-information/starleaf-pri...](https://support.starleaf.com/legal-information/starleaf-privacy-notice/) |
| URL delle Condizioni per l'utilizzo | [https://support.starleaf.com/legal-information/starleaf-clo...](https://support.starleaf.com/legal-information/starleaf-cloud-services-customer-terms-of-use/) |

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

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni di identificazione dell'utente finale (EUII): l'elenco (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunta. Questa app usa questa funzionalità?

>| **Giustificazione per l'accesso a EUII?**  | **L'EUII è archiviato nei database?** | **Giustificazione per l'archiviazione di EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Il bot accede all'elenco del team per prenotare una riunione per conto dell'utente/host che prenota la riunione tramite il bot. Questo consente a StarLeaf di offrire un'esperienza di partecipazione senza problemi con un solo pulsante per partecipare alle riunioni. | Nome, cognome, indirizzo di posta elettronica. In questo modo il bot StarLeaf può prenotare una riunione per conto dell'utente/host che ha interagito con il bot e invitare gli altri membri del team alla riunione. |  |



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

