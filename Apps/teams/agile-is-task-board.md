---
title: Informazioni sull'applicazione per Agile Task Board di Agile-IS
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/08/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e sulla conformità disponibili per Agile Task Board, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: e9b91da0c67ec24ae9484540baaaf8e34ce2d247
ms.sourcegitcommit: ffdee67a99a6f03cc93fe4d99f00e484b9a8a0e5
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/10/2022
ms.locfileid: "64753911"
---
# <a name="agile-task-board"></a>Agile Task Board

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 8 aprile 2022</p>

* <a href="https://teams.microsoft.com/l/app/6021779f-643c-48c0-9f80-8e41ea801be7" target="_blank">Visualizza in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002162" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Agile-IS a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Agile Task Board |
| ID | WA200002162 |
| client Office 365 supportati | Microsoft Teams |
| Nome della società partner | Agile-IS |
| Sito Web dell'azienda | [https://www.agile-is.de](https://www.agile-is.de) |
| Condizioni per l'utilizzo dell'app | [https://www.agile-is.de/en/termsofuse](https://www.agile-is.de/en/termsofuse) |
| Funzionalità di base dell'app | La scheda attività Agile consente a te e al tuo team di ottenere una panoramica migliore del tuo progetto agile. Convertire la scheda fisica in una versione digitale. È possibile eseguire il mapping del processo con funzionalità come colonne per la visualizzazione dello stato, un numero qualsiasi di corsie, la colorazione basata su metadati delle mappe, l'assegnazione di responsabilità, la modifica del trascinamento della selezione e molte altre impostazioni. Tutti i dati rimarranno all'interno del tenant M365. |
| Sede centrale dell'azienda | Germania |
| Pagina delle informazioni sull'app | [https://www.agile-is.de/en/agiletaskboard](https://www.agile-is.de/en/agiletaskboard) |
| Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app? | Paas |
| Quali provider di servizi cloud di hosting usano l'app? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Agile-IS sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app o l'infrastruttura sottostante elabora i dati relativi a un cliente Microsoft o al dispositivo? | No |
| L'app o l'infrastruttura sottostante archivia i dati dei clienti Microsoft? | Sì |
| Quali dati vengono archiviati nei database? | UPN's zur Lizenzverwaltung; Unternehmensdaten zur Rechnungslegung |
| Se l'infrastruttura sottostante elabora o archivia i dati dei clienti Microsoft, dove vengono archiviati geograficamente questi dati? | Germania |
| Si dispone di un processo di noleggio e smaltimento dei dati stabilito? | Sì |
| Per quanto tempo vengono conservati i dati dopo la chiusura dell'account? | Meno di 30 giorni |
| Si dispone di un processo di gestione dell'accesso ai dati stabilito? | Sì |
| Trasferisci i dati dei clienti o il contenuto del cliente a terze parti o sub-responsabili del trattamento? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Di seguito sono riportate le informazioni del catalogo [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Si eseguono test di penetrazione annuali sull'app? | No |
| L'app dispone di un piano di ripristino di emergenza documentato, inclusa una strategia di backup e ripristino? | Sì |
| L'ambiente usa la protezione antimalware tradizionale o i controlli delle applicazioni? | ApplicationControls |
| Si dispone di un processo stabilito per l'individuazione e la classificazione dei rischi delle vulnerabilità di sicurezza? | No |
| Si dispone di un criterio che regola il contratto di servizio (SLA) per l'applicazione di patch? | No |
| Si eseguono attività di gestione delle patch in base ai contratti di servizio dei criteri di applicazione delle patch? | No |
| L'ambiente ha sistemi operativi o software non supportati? | No |
| Si esegue l'analisi trimestrale delle vulnerabilità nell'app e nell'infrastruttura che la supporta? | No |
| È installato un firewall sul limite di rete esterno? | Sì |
| Si dispone di un processo di gestione delle modifiche stabilito usato per esaminare e approvare le richieste di modifica prima che vengano distribuite nell'ambiente di produzione? | Sì |
| Una persona aggiuntiva sta esaminando e approvando tutte le richieste di modifica del codice inviate all'ambiente di produzione dallo sviluppatore originale? | Sì |
| Le procedure di codifica sicura tengono conto delle classi di vulnerabilità comuni, ad esempio OWASP Top 10? | Sì |
| Autenticazione a più fattori abilitata per: | CodeRepositories, Credential, DNSManagement |
| Si dispone di un processo stabilito per il provisioning, la modifica e l'eliminazione degli account dei dipendenti? | Sì |
| Si dispone di software di rilevamento e prevenzione delle intrusioni (IDPS) distribuito nel perimetro del limite di rete che supporta l'app? | N/D |
| La registrazione eventi è configurata in tutti i componenti di sistema che supportano l'app? | Sì |
| Tutti i log vengono esaminati con cadenza regolare da strumenti umani o automatizzati per rilevare potenziali eventi di sicurezza? | Sì |
| Quando viene rilevato un evento di sicurezza, gli avvisi vengono inviati automaticamente a un dipendente per la valutazione? | No |
| È stato stabilito un processo formale di gestione dei rischi per la sicurezza delle informazioni? | No |
| Si dispone di un processo formale di risposta agli eventi imprevisti di sicurezza documentato e stabilito? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app è conforme al Health Insurance Portability and Accounting Act (HIPAA)? | No |
| L'app è conforme a Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | No |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 1)? | No |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 2)? | No |
| L'app è conforme ai controlli dell'organizzazione dei servizi (SOC 3)? | No |
| Si eseguono valutazioni PCI DSS annuali rispetto all'app e al relativo ambiente di supporto? | No |
| L'app International Organization for Standardization (ISO 27001) è certificata? | No |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27018)? | No |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27017)? | No |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27002)? | No |
| L'app Federal Risk and Authorization Management Program (FedRAMP) è conforme? | No |
| L'app è conforme al Family Educational Rights and Privacy Act (FERPA)? | No |
| L'app è conforme al Children's Online Privacy Protection Act (COPPA)? | No |
| L'app è conforme a Sarbanes-Oxley Act (SOX)? | No |
| L'app è conforme a NIST 800-171? | No |
| L'app è stata certificata da Cloud Security Alliance (CSA Star)? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Si dispone di gdpr o altri requisiti o obblighi di privacy o protezione dei dati (ad esempio CCPA)? | Sì |
| L'app ha un'informativa sulla privacy esterna che descrive come raccoglie, usa, condivide e archivia i dati dei clienti? | Sì |
| URL dell'informativa sulla privacy | https://www.agile-is.de/en/telemetry |
| L'app esegue un processo decisionale automatizzato, inclusa la profilatura che potrebbe avere un effetto legale o un impatto simile? | No |
| L'app elabora i dati dei clienti per uno scopo secondario non descritto nell'informativa sulla privacy (ad esempio marketing, analisi)? | No |
| Si elaborano categorie speciali di dati sensibili (ad esempio, origine razziale o etnica, opinione politica, credenze religiose o filosofiche, dati genetici o biometrici, dati sanitari) o categorie di dati soggetti a leggi sulle notifiche di violazione? | No |
| L'app raccoglie o elabora i dati di minori (ad esempio, persone di età inferiore ai 16 anni)? | No |
| L'app ha funzionalità per eliminare i dati personali di un individuo su richiesta? | N/D |
| L'app ha funzionalità per limitare o limitare il trattamento dei dati personali di un individuo su richiesta? | N/D |
| L'app offre agli utenti la possibilità di correggere o aggiornare i propri dati personali? | N/D |
| Vengono eseguite regolari verifiche della sicurezza dei dati e della privacy (ad esempio, valutazioni dell'impatto sulla protezione dei dati o valutazioni dei rischi per la privacy) per identificare i rischi correlati al trattamento dei dati personali per l'app? | N/D |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'applicazione si integra con Microsoft Identity Platform (Azure AD) per l'accesso Single Sign-On, l'accesso API e così via? | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di controllo di integrazione Microsoft Identity Platform? | Sì |
| L'app usa la versione più recente di MSAL (Microsoft Authentication Library) o Microsoft Identity Web per l'autenticazione? | Sì |
| Se l'app non usa una delle librerie precedenti, quale libreria o libreria di autenticazione usa? |  |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app supporta la valutazione dell'accesso continuo (CAE) | Sì |
| L'app archivia le credenziali nel codice? | No |
| Le app e i componenti aggiuntivi per Microsoft 365 potrebbero usare api Microsoft aggiuntive all'esterno di Microsoft Graph. L'app o il componente aggiuntivo usa altre API Microsoft? | Sì |

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

>|   **Autorizzazione Graph**  | **Tipo autorizzazione** |          **Giustificazione**          | **ID app Azure AD** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| AppCatalog.Read.All | Delegato | Consente all'app di eseguire query sulla versione dell'app attualmente installata. Usato per fornire le risorse dell'app corrette. | [ed6cb2ac-21e8-4e9c-a917-6a2d5f03e3a5](../azure/ed6cb2ac-21e8-4e9c-a917-6a2d5f03e3a5.md) |
>| GroupMember.Read.All | Delegato | Leggere i membri del gruppo per assegnare l'attività planner  | [ed6cb2ac-21e8-4e9c-a917-6a2d5f03e3a5](../azure/ed6cb2ac-21e8-4e9c-a917-6a2d5f03e3a5.md) |
>| Tasks.ReadWrite | Delegato | Usare il piano e l'attività di Planner   | [ed6cb2ac-21e8-4e9c-a917-6a2d5f03e3a5](../azure/ed6cb2ac-21e8-4e9c-a917-6a2d5f03e3a5.md) |
>| TeamsActivity.Send | Delegato | Inviare messaggi all'attività dei team | [ed6cb2ac-21e8-4e9c-a917-6a2d5f03e3a5](../azure/ed6cb2ac-21e8-4e9c-a917-6a2d5f03e3a5.md) |
>| TeamsAppInstallation.ReadForTeam | Delegato | Consente all'app di eseguire query sulla versione dell'app attualmente installata. Usato per fornire le risorse dell'app corrette. | [ed6cb2ac-21e8-4e9c-a917-6a2d5f03e3a5](../azure/ed6cb2ac-21e8-4e9c-a917-6a2d5f03e3a5.md) |
>| User.Read | Delegato | Consente all'utente di accedere e leggere informazioni di base sul profilo | [ed6cb2ac-21e8-4e9c-a917-6a2d5f03e3a5](../azure/ed6cb2ac-21e8-4e9c-a917-6a2d5f03e3a5.md) |
>| User.ReadBasic.All | Delegato | Consente all'utente di leggere le informazioni di base del profilo di altri utenti | [ed6cb2ac-21e8-4e9c-a917-6a2d5f03e3a5](../azure/ed6cb2ac-21e8-4e9c-a917-6a2d5f03e3a5.md) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

