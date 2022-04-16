---
title: Informazioni sull'applicazione per Jira Cloud di Atlassian
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 10/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Jira Cloud, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: bcba0e0913aab92a5808c0316443696de0767b54
ms.sourcegitcommit: 5e2cd59a54fc018a6df761b00c18e3ba592d9dba
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/15/2022
ms.locfileid: "64880990"
---
# <a name="jira-cloud"></a>Jira Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 11 agosto 2021</p>

* <a href="https://teams.microsoft.com/l/app/aa183fd9-7104-46c4-af9f-9ee9b81d717e" target="_blank">Visualizza in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002140" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Atlassian a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Jira Cloud |
| ID | WA200002140 |
| client Office 365 supportati | Microsoft Teams |
| Nome della società partner | Atlassian |
| Sito Web dell'azienda | [https://www.atlassian.com](https://www.atlassian.com) |
| Condizioni per l'utilizzo dell'app | [https://www.atlassian.com/licensing/marketplace/termsofuse](https://www.atlassian.com/licensing/marketplace/termsofuse) |
| Funzionalità di base dell'app | Consente al team di tenere traccia, aggiornare e gestire i progetti da Microsoft Teams. |
| Sede centrale dell'azienda | Australia |
| Pagina delle informazioni sull'app | |
| Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app? | Paas |
| Quali provider di servizi cloud di hosting usano l'app? | Aws |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Atlassian sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app o l'infrastruttura sottostante elabora i dati relativi a un cliente Microsoft o al dispositivo? | Sì |
| Quali dati vengono elaborati dall'app? | Dati profilo utente, informazioni sul tenant |
| L'app supporta TLS 1.1 o versione successiva? | Sì |
| L'app o l'infrastruttura sottostante archivia i dati dei clienti Microsoft? | Sì |
| Quali dati vengono archiviati nei database? | ID tenant e ID utente |
| Se l'infrastruttura sottostante elabora o archivia i dati dei clienti Microsoft, dove vengono archiviati geograficamente questi dati? | Stati Uniti d'America |
| Si dispone di un processo di noleggio e smaltimento dei dati stabilito? | Sì |
| Per quanto tempo vengono conservati i dati dopo la chiusura dell'account? | Non conservato |
| Si dispone di un processo di gestione dell'accesso ai dati stabilito? | Sì |
| Trasferisci i dati dei clienti o il contenuto del cliente a terze parti o sub-responsabili del trattamento? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Di seguito sono riportate le informazioni del catalogo [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Si eseguono test di penetrazione annuali sull'app? | No |
| L'app dispone di un piano di ripristino di emergenza documentato, inclusa una strategia di backup e ripristino? | No |
| L'ambiente usa la protezione antimalware tradizionale o i controlli delle applicazioni? | TraditionalAntiMalware, ApplicationControls |
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
| Data di certificazione SOC2 più recente | 2020-10-31 |
| L'app è conforme ai controlli dell'organizzazione dei servizi (SOC 3)? | Sì |
| Data di certificazione SOC3 più recente | 2020-10-31 |
| Si eseguono valutazioni PCI DSS annuali rispetto all'app e al relativo ambiente di supporto? | No |
| L'app International Organization for Standardization (ISO 27001) è certificata? | Sì |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27018)? | Sì |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27017)? | No |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27002)? | No |
| L'app Federal Risk and Authorization Management Program (FedRAMP) è conforme? | No |
| L'app è conforme al Family Educational Rights and Privacy Act (FERPA)? | No |
| L'app è conforme al Children's Online Privacy Protection Act (COPPA)? | No |
| L'app è conforme a Sarbanes-Oxley Act (SOX)? | Sì |
| L'app è conforme a NIST 800-171? | No |
| L'app è stata certificata da Cloud Security Alliance (CSA Star)? | Sì |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Si dispone di gdpr o altri requisiti o obblighi di privacy o protezione dei dati (ad esempio CCPA)? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'applicazione si integra con Microsoft Identity Platform (Azure AD) per l'accesso Single Sign-On, l'accesso API e così via? | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di controllo di integrazione Microsoft Identity Platform? | Sì |
| L'app usa la versione più recente di MSAL (Microsoft Authentication Library) o Microsoft Identity Web per l'autenticazione? | No |
| Se l'app non usa una delle librerie precedenti, quale libreria o libreria di autenticazione usa? |  |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app supporta la valutazione dell'accesso continuo (CAE) | No |
| L'app archivia le credenziali nel codice? | No |
| Le app e i componenti aggiuntivi per Microsoft 365 potrebbero usare api Microsoft aggiuntive all'esterno di Microsoft Graph. L'app o il componente aggiuntivo usa altre API Microsoft? | No |

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

>|   **Autorizzazione Graph**  | **Tipo autorizzazione** |          **Giustificazione**          | **ID app Azure AD** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| offline_access | Delegato | Fornire l'accesso alle risorse per conto dell'utente per un periodo di tempo prolungato per garantire la migliore esperienza utente. | [512b84d2-5840-45d6-8d01-5f073836d039](../azure/512b84d2-5840-45d6-8d01-5f073836d039.md) |
>| openid | Delegato | Ottenere il nome, il cognome, il nome utente preferito e l'ID oggetto specificati dell'utente. | [512b84d2-5840-45d6-8d01-5f073836d039](../azure/512b84d2-5840-45d6-8d01-5f073836d039.md) |
>| profile | Delegato | Ottenere il nome, il cognome, il nome utente preferito e l'ID oggetto specificati dell'utente. | [512b84d2-5840-45d6-8d01-5f073836d039](../azure/512b84d2-5840-45d6-8d01-5f073836d039.md) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

