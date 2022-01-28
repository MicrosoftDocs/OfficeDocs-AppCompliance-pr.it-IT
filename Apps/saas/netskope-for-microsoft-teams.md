---
title: Informazioni sull'applicazione per Netskope per Microsoft Teams da Netskope
ms.author: elmalova
author: elenamalova
ms.date: 10/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Netskope per Microsoft Teams, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: c4c65c048423c0f0e7bc1c1b396dd832cbebf341
ms.sourcegitcommit: e61daaadc2921e59735e8952fe81e5a416b55fbf
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 01/28/2022
ms.locfileid: "62254003"
---
# <a name="netskope-for-microsoft-teams"></a>Netskope per Microsoft Teams

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 27, 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/netskope.netskope_teams" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Netskope a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Netskope per Microsoft Teams |
| ID | netskope.netskope_teams |
| Nome società partner | Netskope |
| Sito Web aziendale | [https://www.netskope.com](https://www.netskope.com) |
| Condizioni per l'uso dell'app | [https://www.netskope.com/subscription-terms/](https://www.netskope.com/subscription-terms/) |
| Funzionalità di base dell'app | Netskope ha l'unica soluzione&#8217;settore che dispone di CASB, SWG next-gen, isolamento remoto dei browser, firewall cloud, sicurezza cloud pubblica e accesso privato senza attendibilità in un'unica piattaforma: Netskope Security Cloud.  Oltre a queste funzionalità modulari, Netskope offre anche microservizi di sicurezza aggiuntivi che possono essere aggiunti per ottimizzare ulteriormente la posizione di sicurezza dei clienti, ad esempio le funzionalità avanzate di prevenzione della perdita dei dati, crittografia e protezione dalle minacce. |
| Sede centrale dell'azienda | Stati Uniti d'America |
| Pagina delle informazioni dell'app | |
| Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app? | IsvHosted |
| Quali provider di cloud di hosting usa l'app? |  |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Netskope su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app o l'infrastruttura sottostante elabora i dati relativi a un cliente Microsoft o al dispositivo? | Sì |
| Quali dati vengono elaborati dalla tua app? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| L'app supporta TLS 1.1 o versione successiva? | Sì |
| L'app o l'infrastruttura sottostante archivia i dati dei clienti Microsoft? | Sì |
| Quali dati vengono archiviati nei database? | Informazioni utente |
| Se l'infastruttura sottostante elabora o archivia i dati dei clienti Microsoft, dove sono archiviati geograficamente? | Stati Uniti d'America |
| Si dispone di un processo di affiliazione e di eliminazione dei dati stabilito? | Sì |
| Per quanto tempo vengono conservati i dati dopo la chiusura dell'account? | Non conservato |
| Si dispone di un processo di gestione dell'accesso ai dati stabilito? | Sì |
| Trasferire i dati dei clienti o i contenuti dei clienti a terze parti o sub-processori? | Sì |
| Sono stati stipulati contratti di condivisione dei dati con qualsiasi servizio di terze parti con cui si condividono i dati dei clienti Microsoft? | Sì |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalogo vengono visualizzate di seguito.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Esegui test di penetrazione annuali nell'app? | Sì |
| L'app dispone di un piano di ripristino di emergenza documentato, inclusa una strategia di backup e ripristino? | Sì |
| L'ambiente usa la protezione antimalware tradizionale o i controlli delle applicazioni? | ApplicationControls |
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
| L'app è conforme all'Health Insurance Portability and Accounting Act (HIPAA)? | Sì |
| L'app è conforme a Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | No |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 1)? | No |
| Data di certificazione SOC1 più recente |   |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 2)? | Sì |
| Quale certificazione SOC 2 hai raggiunto? |  type2 |
| Data di certificazione SOC2 più recente |  2021-10-21 |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 3)? | No |
| Data di certificazione SOC3 più recente | |
| Eseguire valutazioni PCI DSS annuali sull'app e sull'ambiente di supporto? | N/D |
| L'app International Organization for Standardization (ISO 27001) è certificata? | Sì |
| L'app è conforme all'International Organization for Standardization (ISO 27018)? | Sì |
| L'app è conforme all'International Organization for Standardization (ISO 27017)? | Sì |
| L'app è conforme all'International Organization for Standardization (ISO 27002)? | No |
| L'app Federal Risk and Authorization Management Program (FedRAMP) è conforme? | Sì |
| L'app è conforme al Family Educational Rights and Privacy Act (FERPA)? | N/D |
| L'app è conforme al Children's Online Privacy Protection Act (COPPA)? | N/D |
| L'app è conforme Sarbanes-Oxley Act (SOX)? | No |
| L'app è conforme al NIST 800-171? | Sì |
| L'app è stata certificata da Cloud Security Alliance (CSA Star) ? | Sì |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Hai un GDPR o altri requisiti o obblighi di privacy o protezione dei dati (ad esempio CCPA)? | Sì |
| L'app ha un avviso sulla privacy rivolto all'esterno che descrive come raccoglie, usa, condivide e archivia i dati dei clienti? | Sì |
| URL dell'informativa sulla privacy | https://www.netskope.com/privacy-policy |
| L'app esegue processi decisionali automatizzati, inclusa la profilatura che potrebbe avere un effetto legale o un impatto simile? | Sì |
| I singoli utenti hanno la possibilità di osare l'elaborazione? | Sì |
| L'app elabora i dati dei clienti per uno scopo secondario non descritto nell'informativa sulla privacy (ad esempio marketing, analisi)? | No |
| Si elaborano categorie speciali di dati sensibili (ad esempio origine razziale o etnica, opinioni politiche, convinzioni religiose o filosofiche, dati genetici o biometrici, dati sanitari) o categorie di dati soggetti alle leggi sulle notifiche di violazione? | No |
| L'app raccoglie o elabora dati da minori (ad esempio, persone di età inferiore ai 16 anni)? | No |
| L'app dispone di funzionalità per eliminare i dati personali di un individuo su richiesta? | Sì |
| L'app dispone di funzionalità per limitare o limitare l'elaborazione dei dati personali di un individuo su richiesta? | Sì |
| L'app offre agli utenti la possibilità di correggere o aggiornare i propri dati personali? | No |
| Vengono eseguite revisioni regolari sulla sicurezza e sulla privacy dei dati (ad esempio, valutazioni dell'impatto sulla protezione dei dati o valutazioni dei rischi per la privacy) per identificare i rischi correlati al trattamento dei dati personali per l'app? | Sì |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'applicazione si integra con Microsoft Identity Platform (Azure AD) per single sign-on, accesso API e così via? | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione? | Sì |
| L'app usa la versione più recente di MSAL (Microsoft Authentication Library) o Microsoft Identity Web per l'autenticazione? | N/D |
| Se l'app non usa una delle librerie precedenti, quali librerie di autenticazione usa? |  |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app supporta la valutazione dell'accesso continuo (CAE) | Sì |
| L'app archivia credenziali nel codice? | No |
| Le app e i componenti aggiuntivi per Microsoft 365 potrebbero usare API Microsoft aggiuntive al di fuori di Microsoft Graph. L'app o il componente aggiuntivo usa api Microsoft aggiuntive? | No |

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

>|   **Graph autorizzazioni**  | **Tipo autorizzazione** |          **Giustificazione**          | **Azure AD'ID app** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| ChannelMessage.Read.All | application | DLP su messaggi e post del canale | [9b5751f4-eb23-43ad-ad90-da7afb9300ae](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b5751f4-eb23-43ad-ad90-da7afb9300ae) |
>| ChannelMessage.UpdatePolicyViolation.All | application | DLP su messaggi e post del canale | [9b5751f4-eb23-43ad-ad90-da7afb9300ae](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b5751f4-eb23-43ad-ad90-da7afb9300ae) |
>| Chat.Read.All | application | DLP nelle chat canale/DM | [9b5751f4-eb23-43ad-ad90-da7afb9300ae](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b5751f4-eb23-43ad-ad90-da7afb9300ae) |
>| Chat.ReadBasic.All | application | DLP nelle chat canale/DM | [9b5751f4-eb23-43ad-ad90-da7afb9300ae](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b5751f4-eb23-43ad-ad90-da7afb9300ae) |
>| Chat.ReadWrite | application | DLP nelle chat canale/DM | [9b5751f4-eb23-43ad-ad90-da7afb9300ae](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b5751f4-eb23-43ad-ad90-da7afb9300ae) |
>| Chat.UpdatePolicyViolation.All | application | DLP su messaggi e post del canale | [9b5751f4-eb23-43ad-ad90-da7afb9300ae](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b5751f4-eb23-43ad-ad90-da7afb9300ae) |
>| Directory.Read.All | application | Identificazione e visibilità dell'appartenenza degli utenti | [9b5751f4-eb23-43ad-ad90-da7afb9300ae](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b5751f4-eb23-43ad-ad90-da7afb9300ae) |
>| Files.Read.All | application | DLP sui file pubblicati in MSTeams | [9b5751f4-eb23-43ad-ad90-da7afb9300ae](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b5751f4-eb23-43ad-ad90-da7afb9300ae) |
>| Files.ReadWrite.All | application | DLP sui file pubblicati in MSTeams | [9b5751f4-eb23-43ad-ad90-da7afb9300ae](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b5751f4-eb23-43ad-ad90-da7afb9300ae) |
>| Group.Read.All | application | Identificazione e visibilità del gruppo | [9b5751f4-eb23-43ad-ad90-da7afb9300ae](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b5751f4-eb23-43ad-ad90-da7afb9300ae) |
>| GroupMember.Read.All | application | Identificazione e visibilità del gruppo | [9b5751f4-eb23-43ad-ad90-da7afb9300ae](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b5751f4-eb23-43ad-ad90-da7afb9300ae) |
>| Reports.Read.All | application | Creazione di report e visibilità | [9b5751f4-eb23-43ad-ad90-da7afb9300ae](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b5751f4-eb23-43ad-ad90-da7afb9300ae) |
>| Sites.Read.All | application | Prevenzione della perdita dei SharePoint del team | [9b5751f4-eb23-43ad-ad90-da7afb9300ae](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b5751f4-eb23-43ad-ad90-da7afb9300ae) |
>| TeamsActivity.Read | application | Criteri basati sull'attività utente | [9b5751f4-eb23-43ad-ad90-da7afb9300ae](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b5751f4-eb23-43ad-ad90-da7afb9300ae) |
>| User.Read.All | application | Identificazione e visibilità dell'utente | [9b5751f4-eb23-43ad-ad90-da7afb9300ae](https://docs.microsoft.com/microsoft-365-app-certification/azure/9b5751f4-eb23-43ad-ad90-da7afb9300ae) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

