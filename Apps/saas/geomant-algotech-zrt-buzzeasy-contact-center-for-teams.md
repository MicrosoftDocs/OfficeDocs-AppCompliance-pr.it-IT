---
title: Application Information for Buzzeasy Contact Center for Teams by Geomant-Algotech Zrt.
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 11/29/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e conformità disponibili per Buzzeasy Contact Center per Teams, i criteri di gestione dei dati, le informazioni sul catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 10c37808d1ec33fb38927294c104c50a98dda001
ms.sourcegitcommit: 58c50d1704196178455927329748485b40dd7880
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/17/2022
ms.locfileid: "63546894"
---
# <a name="buzzeasy-contact-center-for-teams"></a>Buzzeasy Contact Center per Teams

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: November 23, 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/geomant.buzzeasy_teams_contact_center" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Geomant-Algotech Zrt. a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Buzzeasy Contact Center per Teams |
| ID | geomant.buzzeasy_teams_contact_center |
| Nome società partner | Geomant-Algotech Zrt. |
| Sito Web aziendale | [https://www.buzzeasy.com](https://www.buzzeasy.com) |
| Condizioni per l'uso dell'app | [https://docs.geomant.com/buzzeasy/portal/Buzzeasy_Service_L...](https://docs.geomant.com/buzzeasy/portal/Buzzeasy_Service_Level_Agreement.html) |
| Funzionalità di base dell'app | Soluzione Contact Center per Microsoft Teams |
| Sede centrale dell'azienda | Ungheria |
| Pagina delle informazioni dell'app | [https://www.geomant.com/buzzeasy-contact-centre-for-microso...](https://www.geomant.com/buzzeasy-contact-centre-for-microsoft-teams) |
| Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app? | Iaas |
| Quali provider di cloud di hosting usa l'app? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Geomant-Algotech Zrt. informazioni su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app o l'infrastruttura sottostante elabora i dati relativi a un cliente Microsoft o al dispositivo? | Sì |
| Quali dati vengono elaborati dalla tua app? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| L'app supporta TLS 1.1 o versione successiva? | Sì |
| L'app o l'infrastruttura sottostante archivia i dati dei clienti Microsoft? | Sì |
| Quali dati vengono archiviati nei database? | Microsoft JWT User and refresh Token, MICROSOFT Application ID, App Secret, M365 Email content from Graph API |
| Se l'infastruttura sottostante elabora o archivia i dati dei clienti Microsoft, dove sono archiviati geograficamente? | Irlanda |
| Si dispone di un processo di affiliazione e di eliminazione dei dati stabilito? | Sì |
| Per quanto tempo vengono conservati i dati dopo la chiusura dell'account? | Meno di 90 giorni |
| Si dispone di un processo di gestione dell'accesso ai dati stabilito? | Sì |
| Trasferire i dati dei clienti o i contenuti dei clienti a terze parti o sub-processori? | No |
| Sono stati stipulati contratti di condivisione dei dati con qualsiasi servizio di terze parti con cui si condividono i dati dei clienti Microsoft? |  |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Esegui test di penetrazione annuali nell'app? | Sì |
| L'app dispone di un piano di ripristino di emergenza documentato, inclusa una strategia di backup e ripristino? | Sì |
| L'ambiente usa la protezione antimalware tradizionale o i controlli delle applicazioni? | TraditionalAntiMalware |
| Si dispone di un processo stabilito per l'identificazione e la classificazione dei rischi delle vulnerabilità di sicurezza? | No |
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
| Hai distribuito software di rilevamento e prevenzione delle intrusioni (IDPS) nel perimetro del limite di rete che supporta la tua app? | N/D |
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
| L'app è conforme all'Health Insurance Portability and Accounting Act (HIPAA)? | N/D |
| L'app è conforme a Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | N/D |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 1)? | No |
| Data di certificazione SOC1 più recente |   |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 2)? | No |
| Quale certificazione SOC 2 hai raggiunto? | |
| Data di certificazione SOC2 più recente | |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 3)? | No |
| Data di certificazione SOC3 più recente | |
| Eseguire valutazioni PCI DSS annuali sull'app e sull'ambiente di supporto? | N/D |
| L'app International Organization for Standardization (ISO 27001) è certificata? | Sì |
| L'app è conforme all'International Organization for Standardization (ISO 27018)? | N/D |
| L'app è conforme all'International Organization for Standardization (ISO 27017)? | No |
| L'app è conforme all'International Organization for Standardization (ISO 27002)? | No |
| L'app Federal Risk and Authorization Management Program (FedRAMP) è conforme? | No |
| L'app è conforme al Family Educational Rights and Privacy Act (FERPA)? | N/D |
| L'app è conforme al Children's Online Privacy Protection Act (COPPA)? | N/D |
| L'app è conforme Sarbanes-Oxley Act (SOX)? | N/D |
| L'app è conforme al NIST 800-171? | N/D |
| L'app è stata certificata da Cloud Security Alliance (CSA Star) ? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Hai un GDPR o altri requisiti o obblighi di privacy o protezione dei dati (ad esempio CCPA)? | Sì |
| L'app ha un avviso sulla privacy rivolto all'esterno che descrive come raccoglie, usa, condivide e archivia i dati dei clienti? | Sì |
| URL dell'informativa sulla privacy | https://www.geomant.com/privacy-policy |
| L'app esegue processi decisionali automatizzati, inclusa la profilatura che potrebbe avere un effetto legale o un impatto simile? | No |
| L'app elabora i dati dei clienti per uno scopo secondario non descritto nell'informativa sulla privacy (ad esempio marketing, analisi)? | No |
| Si elaborano categorie speciali di dati sensibili (ad esempio origine razziale o etnica, opinioni politiche, convinzioni religiose o filosofiche, dati genetici o biometrici, dati sanitari) o categorie di dati soggetti alle leggi sulle notifiche di violazione? | No |
| L'app raccoglie o elabora dati da minori (ad esempio, persone di età inferiore ai 16 anni)? | No |
| L'app dispone di funzionalità per eliminare i dati personali di un individuo su richiesta? | Sì |
| L'app dispone di funzionalità per limitare o limitare l'elaborazione dei dati personali di un individuo su richiesta? | Sì |
| L'app offre agli utenti la possibilità di correggere o aggiornare i propri dati personali? | Sì |
| Vengono eseguite revisioni regolari sulla sicurezza e sulla privacy dei dati (ad esempio, valutazioni dell'impatto sulla protezione dei dati o valutazioni dei rischi per la privacy) per identificare i rischi correlati al trattamento dei dati personali per l'app? | Sì |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'applicazione si integra con Microsoft Identity Platform (Azure AD) per single sign-on, accesso API e così via? | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione? | No |
| L'app usa la versione più recente di MSAL (Microsoft Authentication Library) o Microsoft Identity Web per l'autenticazione? | N/D |
| Se l'app non usa una delle librerie precedenti, quali librerie di autenticazione usa? |  |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app supporta la valutazione dell'accesso continuo (CAE) | No |
| L'app archivia credenziali nel codice? | No |
| Le app e i componenti aggiuntivi per Microsoft 365 potrebbero usare API Microsoft aggiuntive al di fuori di Microsoft Graph. L'app o il componente aggiuntivo usa api Microsoft aggiuntive? | No |

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

>|   **Graph autorizzazioni**  | **Tipo autorizzazione** |          **Giustificazione**          | **Azure AD ID app** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Mail.Send | application | Invio di un invito per conto di un utente del servizio. | [1b81b79d-10ff-4614-81cc-5ac3dc64a40c](../azure/1b81b79d-10ff-4614-81cc-5ac3dc64a40c.md) |
>| Presence.Read.All | delegated | Visualizzare lo stato dell'agente/utente per altri agenti, eseguire la sincronizzazione con lo stato dell'agente. | [1b81b79d-10ff-4614-81cc-5ac3dc64a40c](../azure/1b81b79d-10ff-4614-81cc-5ac3dc64a40c.md) |
>| User.Read | delegated | Visualizzare l'elenco degli utenti per gli amministratori per la registrazione. | [1b81b79d-10ff-4614-81cc-5ac3dc64a40c](../azure/1b81b79d-10ff-4614-81cc-5ac3dc64a40c.md) |
>| User.Read.All | delegated | Visualizzare le informazioni AAD utente sulle interfacce di amministrazione/utente | [1b81b79d-10ff-4614-81cc-5ac3dc64a40c](../azure/1b81b79d-10ff-4614-81cc-5ac3dc64a40c.md) |
>| User.ReadBasic.All | delegated | Visualizzare le informazioni AAD utente sulle interfacce di amministrazione/utente | [1b81b79d-10ff-4614-81cc-5ac3dc64a40c](../azure/1b81b79d-10ff-4614-81cc-5ac3dc64a40c.md) |
>| Mail.ReadWrite | application | Consente all'agente di leggere/scrivere una cassetta postale specifica (condivisa) tramite l'interfaccia utente dell'agente. Può essere filtrato in base a una cassetta postale specifica. | [cbc8bfef-8dd2-4714-ab18-18e15566b63e](../azure/cbc8bfef-8dd2-4714-ab18-18e15566b63e.md) |
>| Mail.Send | application | Invio di posta elettronica per conto di una cassetta postale condivisa. | [cbc8bfef-8dd2-4714-ab18-18e15566b63e](../azure/cbc8bfef-8dd2-4714-ab18-18e15566b63e.md) |
>| User.Read | delegated | Accedere e leggere il profilo utente | [cbc8bfef-8dd2-4714-ab18-18e15566b63e](../azure/cbc8bfef-8dd2-4714-ab18-18e15566b63e.md) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

