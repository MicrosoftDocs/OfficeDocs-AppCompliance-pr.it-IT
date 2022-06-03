---
title: Informazioni sull'applicazione per Adobe Acrobat di Adobe
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/09/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Adobe Acrobat, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: c87e0fadffed9b801f57668eae3d63285dd6a716
ms.sourcegitcommit: 4ceff6ef6aa0bae1075da646773b852970bb4049
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 06/03/2022
ms.locfileid: "65874276"
---
# <a name="adobe-acrobat"></a>Adobe Acrobat Reader

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 6 marzo 2022</p>

* <a href="https://teams.microsoft.com/l/app/10aea93d-20cf-44c2-b4a5-284c5ef2e6a5" target="_blank">Visualizza in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002564" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Adobe a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Adobe Acrobat Reader |
| ID | WA200002564 |
| client Office 365 supportati | Microsoft Teams |
| Nome della società partner | Adobe |
| Sito Web dell'azienda | [https://www.adobe.com](https://www.adobe.com) |
| Condizioni per l'utilizzo dell'app | [https://www.adobe.com/legal/terms.html](https://www.adobe.com/legal/terms.html) |
| Funzionalità di base dell'app | Con Adobe Acrobat per Microsoft Teams, i creatori del formato di file PDF offrono un modo per collaborare con tutti i partecipanti al canale e raccogliere feedback in un unico &#8211; PDF senza dover mai lasciare l'ambiente Teams. Ricevere notifiche sulle attività quando altri utenti interviene sui documenti. I revisori possono visualizzare e commentare l'uno sull'altro&#8217;feedback, in modo da&#8217;dedicare meno tempo alla gestione dei conflitti |
| Sede centrale dell'azienda | Stati Uniti d'America |
| Pagina delle informazioni sull'app | [https://helpx.adobe.com/document-cloud/help/microsoft-teams...](https://helpx.adobe.com/document-cloud/help/microsoft-teams.html) |
| Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app? | Paas |
| Quali provider di servizi cloud di hosting usano l'app? | Azure, Aws |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Adobe sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app o l'infrastruttura sottostante elabora i dati relativi a un cliente Microsoft o al dispositivo? | Sì |
| Quali dati vengono elaborati dall'app? | UserInfo, risorsa OAuth, Risorsa utente,  |
| L'app supporta TLS 1.1 o versione successiva? | Sì |
| L'app o l'infrastruttura sottostante archivia i dati dei clienti Microsoft? | Sì |
| Quali dati vengono archiviati nei database? | tenant_id, upn_hash, profile_and_token_info, oauth_state, ims_login_changed_at, preference_data, updated_at, created_at, expires_at |
| Se l'infrastruttura sottostante elabora o archivia i dati dei clienti Microsoft, dove vengono archiviati geograficamente questi dati? | Stati Uniti d'America |
| Si dispone di un processo di noleggio e smaltimento dei dati stabilito? | Sì |
| Per quanto tempo vengono conservati i dati dopo la chiusura dell'account? | Meno di 30 giorni |
| Si dispone di un processo di gestione dell'accesso ai dati stabilito? | Sì |
| Trasferisci i dati dei clienti o il contenuto del cliente a terze parti o sub-responsabili del trattamento? | Sì |
| Sono in vigore contratti di condivisione dei dati con qualsiasi servizio di terze parti con cui si condividono i dati dei clienti Microsoft? | Sì |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Di seguito sono riportate le informazioni del catalogo [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Si eseguono test di penetrazione annuali sull'app? | Sì |
| L'app dispone di un piano di ripristino di emergenza documentato, inclusa una strategia di backup e ripristino? | Sì |
| L'ambiente usa la protezione antimalware tradizionale o i controlli delle applicazioni? | ApplicationControls, TraditionalAntiMalware |
| Si dispone di un processo stabilito per l'individuazione e la classificazione dei rischi delle vulnerabilità di sicurezza? | Sì |
| Si dispone di un criterio che regola il contratto di servizio (SLA) per l'applicazione di patch? | Sì |
| Si eseguono attività di gestione delle patch in base ai contratti di servizio dei criteri di applicazione delle patch? | Sì |
| L'ambiente ha sistemi operativi o software non supportati? | No |
| Si esegue l'analisi trimestrale delle vulnerabilità nell'app e nell'infrastruttura che la supporta? | Sì |
| È installato un firewall sul limite di rete esterno? | Sì |
| Si dispone di un processo di gestione delle modifiche stabilito usato per esaminare e approvare le richieste di modifica prima che vengano distribuite nell'ambiente di produzione? | Sì |
| Una persona aggiuntiva sta esaminando e approvando tutte le richieste di modifica del codice inviate all'ambiente di produzione dallo sviluppatore originale? | Sì |
| Le procedure di codifica sicura tengono conto delle classi di vulnerabilità comuni, ad esempio OWASP Top 10? | Sì |
| Autenticazione a più fattori abilitata per: | CodeRepositories, DNSManagement, Credential |
| Si dispone di un processo stabilito per il provisioning, la modifica e l'eliminazione degli account dei dipendenti? | Sì |
| Si dispone di software di rilevamento e prevenzione delle intrusioni (IDPS) distribuito nel perimetro del limite di rete che supporta l'app? | Sì |
| La registrazione eventi è configurata in tutti i componenti di sistema che supportano l'app? | Sì |
| Tutti i log vengono esaminati con cadenza regolare da strumenti umani o automatizzati per rilevare potenziali eventi di sicurezza? | Sì |
| Quando viene rilevato un evento di sicurezza, gli avvisi vengono inviati automaticamente a un dipendente per la valutazione? | Sì |
| È stato stabilito un processo formale di gestione dei rischi per la sicurezza delle informazioni? | Sì |
| Si dispone di un processo formale di risposta agli eventi imprevisti di sicurezza documentato e stabilito? | Sì |
| Si segnalano violazioni dei dati di app o servizi alle autorità di vigilanza e alle persone interessate dalla violazione entro 72 ore dal rilevamento? | Sì |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app è conforme al Health Insurance Portability and Accounting Act (HIPAA)? | No |
| L'app è conforme a Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | No |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 1)? | No |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 2)? | Sì |
| Quale certificazione SOC 2 hai ottenuto? | type2 |
| Data di certificazione SOC2 più recente | 2021-11-22 |
| L'app è conforme ai controlli dell'organizzazione dei servizi (SOC 3)? | No |
| Si eseguono valutazioni PCI DSS annuali rispetto all'app e al relativo ambiente di supporto? | No |
| L'app International Organization for Standardization (ISO 27001) è certificata? | Sì |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27018)? | No |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27017)? | No |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27002)? | No |
| L'app Federal Risk and Authorization Management Program (FedRAMP) è conforme? | Sì |
| L'app è conforme al Family Educational Rights and Privacy Act (FERPA)? | Sì |
| L'app è conforme al Children's Online Privacy Protection Act (COPPA)? | Sì |
| L'app è conforme a Sarbanes-Oxley Act (SOX)? | No |
| L'app è conforme a NIST 800-171? | Sì |
| L'app è stata certificata da Cloud Security Alliance (CSA Star)? | Sì |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Si dispone di gdpr o altri requisiti o obblighi di privacy o protezione dei dati (ad esempio CCPA)? | Sì |
| L'app ha un'informativa sulla privacy esterna che descrive come raccoglie, usa, condivide e archivia i dati dei clienti? | Sì |
| URL dell'informativa sulla privacy | https://business.adobe.com/privacy/general-data-protection-regulation.html |
| L'app esegue un processo decisionale automatizzato, inclusa la profilatura che potrebbe avere un effetto legale o un impatto simile? | No |
| L'app elabora i dati dei clienti per uno scopo secondario non descritto nell'informativa sulla privacy (ad esempio marketing, analisi)? | No |
| Si elaborano categorie speciali di dati sensibili (ad esempio, origine razziale o etnica, opinione politica, credenze religiose o filosofiche, dati genetici o biometrici, dati sanitari) o categorie di dati soggetti a leggi sulle notifiche di violazione? | No |
| L'app raccoglie o elabora i dati di minori (ad esempio, persone di età inferiore ai 16 anni)? | No |
| L'app ha funzionalità per eliminare i dati personali di un individuo su richiesta? | No |
| L'app ha funzionalità per limitare o limitare il trattamento dei dati personali di un individuo su richiesta? | No |
| L'app offre agli utenti la possibilità di correggere o aggiornare i propri dati personali? | Sì |
| Vengono eseguite regolari verifiche della sicurezza dei dati e della privacy (ad esempio, valutazioni dell'impatto sulla protezione dei dati o valutazioni dei rischi per la privacy) per identificare i rischi correlati al trattamento dei dati personali per l'app? | Sì |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'applicazione si integra con Microsoft Identity Platform (Azure AD) per l'accesso Single Sign-On, l'accesso alle API e così via? | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di controllo di integrazione Microsoft Identity Platform? | Sì |
| L'app usa la versione più recente di MSAL (Microsoft Authentication Library) o Microsoft Identity Web per l'autenticazione? | No |
| Se l'app non usa una delle librerie precedenti, quale libreria o libreria di autenticazione usa? | Non si usano librerie di autenticazione, viene usato direttamente il protocollo OAuth 2.0 |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app supporta la valutazione dell'accesso continuo (CAE) | No |
| L'app archivia le credenziali nel codice? | No |
| Le app e i componenti aggiuntivi per Microsoft 365 potrebbero usare api Microsoft aggiuntive all'esterno di Microsoft Graph. L'app o il componente aggiuntivo usa altre API Microsoft? | No |

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

>|   **Autorizzazione Graph**  | **Tipo autorizzazione** |          **Giustificazione**          | **Azure AD App ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Files.ReadWrite.All | Delegato | Per poter elencare e esplorare i file e le cartelle recenti, OneDrive e Teams dei canali dell'utente. Gli utenti possono accedere a questi file, usarli per eseguire operazioni su di essi e salvare i file nella loro archiviazione. | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| Team.ReadBasic.All | Delegato | Leggere i nomi e le descrizioni dei team | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| User.Read | Delegato | Accedere e leggere il profilo utente | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| email | Delegato | Visualizzare l'indirizzo di posta elettronica degli utenti | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| offline_access | Delegato | mantenere l'accesso ai dati a cui sono stati assegnati | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| openid | Delegato | Accedere agli utenti | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| profile | Delegato | visualizzare il profilo di base degli utenti | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

