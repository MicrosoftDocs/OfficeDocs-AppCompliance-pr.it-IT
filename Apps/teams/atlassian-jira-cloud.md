---
title: Application Information for Jira Cloud by Atlassian
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Jira Cloud, i criteri di gestione dei dati, le informazioni del catalogo app di Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 6f20ca178d988c5f89b03bd1da5b3100d5c552ef
ms.sourcegitcommit: e61daaadc2921e59735e8952fe81e5a416b55fbf
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 01/28/2022
ms.locfileid: "62256722"
---
# <a name="jira-cloud"></a>Jira Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 11, 2021</p>

* <a href="https://teams.microsoft.com/l/app/aa183fd9-7104-46c4-af9f-9ee9b81d717e" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002140" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Atlassian a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Jira Cloud |
| ID | WA200002140 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | Atlassian |
| Sito Web aziendale | [https://www.atlassian.com](https://www.atlassian.com) |
| Condizioni per l'uso dell'app | [https://www.atlassian.com/licensing/marketplace/termsofuse](https://www.atlassian.com/licensing/marketplace/termsofuse) |
| Funzionalità di base dell'app | Consente al team di tenere traccia, aggiornare e gestire i progetti da Microsoft Teams. |
| Sede centrale dell'azienda | Australia |
| Pagina delle informazioni dell'app | |
| Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app? | Paas |
| Quali provider di cloud di hosting usa l'app? | Aws |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Atlassian su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app o l'infrastruttura sottostante elabora i dati relativi a un cliente Microsoft o al dispositivo? | Sì |
| Quali dati vengono elaborati dalla tua app? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| L'app supporta TLS 1.1 o versione successiva? | Sì |
| L'app o l'infrastruttura sottostante archivia i dati dei clienti Microsoft? | Sì |
| Quali dati vengono archiviati nei database? | ID tenant e ID utente |
| Se l'infastruttura sottostante elabora o archivia i dati dei clienti Microsoft, dove sono archiviati geograficamente? | Stati Uniti d'America |
| Si dispone di un processo di affiliazione e di eliminazione dei dati stabilito? | Sì |
| Per quanto tempo vengono conservati i dati dopo la chiusura dell'account? | Non conservato |
| Si dispone di un processo di gestione dell'accesso ai dati stabilito? | Sì |
| Trasferire i dati dei clienti o i contenuti dei clienti a terze parti o sub-processori? | No |
| Sono stati stipulati contratti di condivisione dei dati con qualsiasi servizio di terze parti con cui si condividono i dati dei clienti Microsoft? |  |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Esegui test di penetrazione annuali nell'app? | No |
| L'app dispone di un piano di ripristino di emergenza documentato, inclusa una strategia di backup e ripristino? | No |
| L'ambiente usa la protezione antimalware tradizionale o i controlli delle applicazioni? | TraditionalAntiMalware, ApplicationControls |
| Si dispone di un processo stabilito per l'identificazione e la classificazione dei rischi delle vulnerabilità di sicurezza? | Sì |
| Si dispone di un criterio che regola il contratto di servizio (SLA) per l'applicazione delle patch? | Sì |
| Si svolgono attività di gestione delle patch in base ai contratti di servizio dei criteri di applicazione delle patch? | Sì |
| L'ambiente include sistemi operativi o software non supportati? | No |
| Esegui l'analisi trimestrale delle vulnerabilità nella tua app e nell'infastruttura che la supporta? | Sì |
| Nel limite di rete esterno è installato un firewall? | Sì |
| Si dispone di un processo di gestione delle modifiche stabilito utilizzato per esaminare e approvare le richieste di modifica prima che siano distribuite nell'ambiente di produzione? | Sì |
| Un'altra persona sta esaminando e approvando tutte le richieste di modifica del codice inviate alla produzione dallo sviluppatore originale? | Sì |
| Le procedure di codifica protetta prendono in considerazione le classi di vulnerabilità comuni, ad esempio OWASP Top 10? | Sì |
| Autenticazione a più fattori abilitata per: | CodeRepositories, DNSManagement, Credential |
| Si dispone di un processo stabilito per il provisioning, la modifica e l'eliminazione degli account dei dipendenti? | Sì |
| Hai distribuito software di rilevamento e prevenzione delle intrusioni (IDPS) nel perimetro del limite di rete che supporta la tua app? | Sì |
| La registrazione eventi è impostata su tutti i componenti di sistema che supportano la tua app? | Sì |
| Tutti i log vengono esaminati a cadenza regolare da strumenti umani o automatizzati per rilevare potenziali eventi di sicurezza? | Sì|
| Quando viene rilevato un evento di sicurezza, gli avvisi vengono inviati automaticamente a un dipendente per il triage? | Sì |
| È stato stabilito un processo formale di gestione dei rischi per la sicurezza delle informazioni? | Sì |
| Si dispone di un processo formale di risposta agli incidenti di sicurezza documentato e stabilito? |  |
| Segnalare violazioni dei dati di app o servizi alle autorità di vigilanza e agli utenti interessati dalla violazione entro 72 ore dal rilevamento?| |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app è conforme all'Health Insurance Portability and Accounting Act (HIPAA)? | No |
| L'app è conforme a Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | No |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 1)? | No |
| Data di certificazione SOC1 più recente |   |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 2)? | Sì |
| Quale certificazione SOC 2 hai raggiunto? |  type2 |
| Data di certificazione SOC2 più recente |  2020-10-31 |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 3)? | Sì |
| Data di certificazione SOC3 più recente |  2020-10-31 |
| Eseguire valutazioni PCI DSS annuali sull'app e sull'ambiente di supporto? | No |
| L'app International Organization for Standardization (ISO 27001) è certificata? | Sì |
| L'app è conforme all'International Organization for Standardization (ISO 27018)? | Sì |
| L'app è conforme all'International Organization for Standardization (ISO 27017)? | No |
| L'app è conforme all'International Organization for Standardization (ISO 27002)? | No |
| L'app Federal Risk and Authorization Management Program (FedRAMP) è conforme? | No |
| L'app è conforme al Family Educational Rights and Privacy Act (FERPA)? | No |
| L'app è conforme al Children's Online Privacy Protection Act (COPPA)? | No |
| L'app è conforme Sarbanes-Oxley Act (SOX)? | Sì |
| L'app è conforme al NIST 800-171? | No |
| L'app è stata certificata da Cloud Security Alliance (CSA Star) ? | Sì |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Hai un GDPR o altri requisiti o obblighi di privacy o protezione dei dati (ad esempio CCPA)? | No |
| L'app ha un avviso sulla privacy rivolto all'esterno che descrive come raccoglie, usa, condivide e archivia i dati dei clienti? | No |
| L'app esegue processi decisionali automatizzati, inclusa la profilatura che potrebbe avere un effetto legale o un impatto simile? | No |
| L'app elabora i dati dei clienti per uno scopo secondario non descritto nell'informativa sulla privacy (ad esempio marketing, analisi)? | No |
| Si elaborano categorie speciali di dati sensibili (ad esempio origine razziale o etnica, opinioni politiche, convinzioni religiose o filosofiche, dati genetici o biometrici, dati sanitari) o categorie di dati soggetti alle leggi sulle notifiche di violazione? | No |
| L'app raccoglie o elabora dati da minori (ad esempio, persone di età inferiore ai 16 anni)? | No |
| L'app dispone di funzionalità per eliminare i dati personali di un individuo su richiesta? |  |
| L'app dispone di funzionalità per limitare o limitare l'elaborazione dei dati personali di un individuo su richiesta? |  |
| L'app offre agli utenti la possibilità di correggere o aggiornare i propri dati personali? |  |
| Vengono eseguite revisioni regolari sulla sicurezza e sulla privacy dei dati (ad esempio, valutazioni dell'impatto sulla protezione dei dati o valutazioni dei rischi per la privacy) per identificare i rischi correlati al trattamento dei dati personali per l'app? |  |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'applicazione si integra con Microsoft Identity Platform (Azure AD) per single sign-on, accesso API e così via? | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione? | Sì |
| L'app usa la versione più recente di MSAL (Microsoft Authentication Library) o Microsoft Identity Web per l'autenticazione? | No |
| Se l'app non usa una delle librerie precedenti, quali librerie di autenticazione usa? |  |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app supporta la valutazione dell'accesso continuo (CAE) | No |
| L'app archivia credenziali nel codice? | No |
| Le app e i componenti aggiuntivi per Microsoft 365 potrebbero usare API Microsoft aggiuntive al di fuori di Microsoft Graph. L'app o il componente aggiuntivo usa api Microsoft aggiuntive? | No |

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

>|   **Graph autorizzazioni**  | **Tipo autorizzazione** |          **Giustificazione**          | **Azure AD'ID app** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| offline_access | delegated | Fornire l'accesso alle risorse per conto dell'utente per un lungo periodo di tempo per garantire la migliore esperienza utente. | [512b84d2-5840-45d6-8d01-5f073836d039](https://docs.microsoft.com/microsoft-365-app-certification/azure/512b84d2-5840-45d6-8d01-5f073836d039) |
>| openid | delegated | Ottenere il nome, il cognome, il nome utente preferito e l'ID oggetto dell'utente. | [512b84d2-5840-45d6-8d01-5f073836d039](https://docs.microsoft.com/microsoft-365-app-certification/azure/512b84d2-5840-45d6-8d01-5f073836d039) |
>| profile | delegated | Ottenere il nome, il cognome, il nome utente preferito e l'ID oggetto dell'utente. | [512b84d2-5840-45d6-8d01-5f073836d039](https://docs.microsoft.com/microsoft-365-app-certification/azure/512b84d2-5840-45d6-8d01-5f073836d039) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

