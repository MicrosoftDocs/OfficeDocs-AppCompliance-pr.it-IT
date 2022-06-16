---
title: Application Information for Solo di Teladoc, Inc.
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 06/15/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Solo, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 5b00791610112ea615e763c0504a88334195a0ae
ms.sourcegitcommit: fd81f2f5b4f627e3d1cabdff7e2caf40fafbe35c
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 06/16/2022
ms.locfileid: "66118000"
---
# <a name="solo"></a>Solo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 15 giugno 2022</p>

* <a href="https://teams.microsoft.com/l/app/c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e" target="_blank">Visualizza in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003826" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Teladoc, Inc. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Solo |
| ID | WA200003826 |
| client Office 365 supportati | Microsoft Teams |
| Nome della società partner | Teladoc, Inc. |
| Sito Web dell'azienda | [https://www.teladochealth.com/platform/](https://www.teladochealth.com/platform/) |
| Condizioni per l'utilizzo dell'app | [https://www.teladochealth.com/terms-and-conditions/](https://www.teladochealth.com/terms-and-conditions/) |
| Funzionalità di base dell'app | Piattaforma di assistenza virtuale con servizi configurabili e flussi di lavoro dei pazienti. |
| Sede centrale dell'azienda | Stati Uniti d'America |
| Pagina delle informazioni sull'app | [https://teladochealth.com/platform/](https://teladochealth.com/platform/) |
| Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app? | Iaas |
| Quali provider di servizi cloud di hosting usano l'app? | Azure, Aws |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Teladoc, Inc. Su come questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app o l'infrastruttura sottostante elabora i dati relativi a un cliente Microsoft o al dispositivo? | Sì |
| Quali dati vengono elaborati dall'app? | ID oggetto dell'utente e DELL'ID tenant del tenant |
| L'app supporta TLS 1.1 o versione successiva? | Sì |
| L'app o l'infrastruttura sottostante archivia i dati dei clienti Microsoft? | Sì |
| Quali dati vengono archiviati nei database? | ID oggetto dell'utente e DELL'ID tenant del tenant |
| Se l'infrastruttura sottostante elabora o archivia i dati dei clienti Microsoft, dove vengono archiviati geograficamente questi dati? | Stati Uniti d'America |
| Si dispone di un processo di noleggio e smaltimento dei dati stabilito? | Sì |
| Per quanto tempo vengono conservati i dati dopo la chiusura dell'account? | Meno di 90 giorni |
| Si dispone di un processo di gestione dell'accesso ai dati stabilito? | Sì |
| Trasferisci i dati dei clienti o il contenuto del cliente a terze parti o sub-responsabili del trattamento? | No |

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
| Autenticazione a più fattori abilitata per: | CodeRepositories, Credential, DNSManagement |
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
| L'app è conforme al Health Insurance Portability and Accounting Act (HIPAA)? | Sì |
| L'app è conforme a Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | Sì |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 1)? | N/D |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 2)? | No |
| L'app è conforme ai controlli dell'organizzazione dei servizi (SOC 3)? | No |
| Si eseguono valutazioni PCI DSS annuali rispetto all'app e al relativo ambiente di supporto? | Sì |
| L'app International Organization for Standardization (ISO 27001) è certificata? | Sì |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27018)? | N/D |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27017)? | No |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27002)? | No |
| L'app Federal Risk and Authorization Management Program (FedRAMP) è conforme? | No |
| L'app è conforme al Family Educational Rights and Privacy Act (FERPA)? | N/D |
| L'app è conforme al Children's Online Privacy Protection Act (COPPA)? | N/D |
| L'app è conforme a Sarbanes-Oxley Act (SOX)? | Sì |
| L'app è conforme a NIST 800-171? | N/D |
| L'app è stata certificata da Cloud Security Alliance (CSA Star)? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Si dispone di gdpr o altri requisiti o obblighi di privacy o protezione dei dati (ad esempio CCPA)? | Sì |
| L'app ha un'informativa sulla privacy esterna che descrive come raccoglie, usa, condivide e archivia i dati dei clienti? | No |
| L'app esegue un processo decisionale automatizzato, inclusa la profilatura che potrebbe avere un effetto legale o un impatto simile? | No |
| L'app elabora i dati dei clienti per uno scopo secondario non descritto nell'informativa sulla privacy (ad esempio marketing, analisi)? | No |
| Si elaborano categorie speciali di dati sensibili (ad esempio, origine razziale o etnica, opinione politica, credenze religiose o filosofiche, dati genetici o biometrici, dati sanitari) o categorie di dati soggetti a leggi sulle notifiche di violazione? | Sì |
| L'app raccoglie o elabora i dati di minori (ad esempio, persone di età inferiore ai 16 anni)? | Sì |
| Il consenso viene ottenuto da un genitore o da un tutore legale? | Sì |
| L'app ha funzionalità per eliminare i dati personali di un individuo su richiesta? | No |
| L'app ha funzionalità per limitare o limitare il trattamento dei dati personali di un individuo su richiesta? | No |
| L'app offre agli utenti la possibilità di correggere o aggiornare i propri dati personali? | No |
| Vengono eseguite regolari verifiche della sicurezza dei dati e della privacy (ad esempio, valutazioni dell'impatto sulla protezione dei dati o valutazioni dei rischi per la privacy) per identificare i rischi correlati al trattamento dei dati personali per l'app? | Sì |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'applicazione si integra con Microsoft Identity Platform (Azure AD) per l'accesso Single Sign-On, l'accesso alle API e così via? | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di controllo di integrazione Microsoft Identity Platform? | Sì |
| L'app usa la versione più recente di MSAL (Microsoft Authentication Library) o Microsoft Identity Web per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app supporta la valutazione dell'accesso continuo (CAE) | No |
| L'app archivia le credenziali nel codice? | No |
| Le app e i componenti aggiuntivi per Microsoft 365 potrebbero usare api Microsoft aggiuntive all'esterno di Microsoft Graph. L'app o il componente aggiuntivo usa altre API Microsoft? | No |

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

>|   **Autorizzazione Graph**  | **Tipo autorizzazione** |          **Giustificazione**          | **Azure AD App ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| AppCatalog.Read.All | Delegato | Per ottenere l'ID dell'app del catalogo per l'app sidepanel e installarlo negli appuntamenti di telehealth pianificati | [c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e](../azure/c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e.md) |
>| CallRecords.Read.All | Applicazione | Per garantire la qualità delle chiamate relative agli appuntamenti di telehealth | [c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e](../azure/c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e.md) |
>| OnlineMeetings.ReadWrite | Delegato | Installare host sidePanel e unire il paziente nell'app personalizzata per appuntamenti | [c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e](../azure/c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e.md) |
>| TeamsActivity.Send | Applicazione | Segnalazione della fine della sessione per l'appuntamento telehealth. | [c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e](../azure/c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e.md) |
>| User.Read | Delegato | Accesso Single Sign-On dell'app da Teams | [c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e](../azure/c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e.md) |
>| email | Delegato | Accesso Single Sign-On dell'app da Teams | [c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e](../azure/c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e.md) |
>| offline_access | Delegato | Accesso Single Sign-On dell'app da Teams | [c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e](../azure/c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e.md) |
>| openid | Delegato | Accesso Single Sign-On dell'app da Teams | [c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e](../azure/c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e.md) |
>| profile | Delegato | oid e tid vengono usati per eseguire il mapping tra un account Solo e Teams account, in modo che un medico in Teams possa visualizzare gli appuntamenti di telehealth | [c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e](../azure/c626ce8b-6d15-4c07-bfb1-a5fd0bc3c20e.md) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

