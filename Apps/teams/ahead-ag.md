---
title: Informazioni sull'applicazione per il futuro del gruppo di disponibilità
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 06/10/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per il futuro, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: e1ae7c1fe34e66f970fba4a06205530425ac8594
ms.sourcegitcommit: cede428f2a23bd3060f5506f270b40b327b02769
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 06/29/2022
ms.locfileid: "66549541"
---
# <a name="ahead"></a>Avanti

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 20 maggio 2022</p>

* <a href="https://teams.microsoft.com/l/app/53360535-c93f-497f-b2a1-95bd9aa34283" target="_blank">Visualizzazione in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200004202" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite dal gruppo di disponibilità a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Avanti |
| ID | WA200004202 |
| client Office 365 supportati | Microsoft Teams |
| Nome della società partner | gruppo di disponibilità ahead |
| Sito Web dell'azienda | [https://www.aheadintranet.com](https://www.aheadintranet.com) |
| Condizioni per l'utilizzo dell'app | [https://www.aheadintranet.com/terms-and-conditions](https://www.aheadintranet.com/terms-and-conditions) |
| Funzionalità di base dell'app | App di coinvolgimento dei dipendenti per mantenere i dipendenti informati e coinvolti. |
| Sede centrale dell'azienda | Svizzera |
| Pagina delle informazioni sull'app | |
| Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app? | Paas |
| Quali provider di servizi cloud di hosting usano l'app? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite dal gruppo di disponibilità in anticipo sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app o l'infrastruttura sottostante elabora i dati relativi a un cliente Microsoft o al dispositivo? | Sì |
| Quali dati vengono elaborati dall'app? | Dati rilevanti per il corretto funzionamento del prodotto Intranet futuro. Sono incluse, a titolo esemplifica vole, notizie, storie, informazioni relative alla destinazione del contenuto a gruppi di utenti specifici, alla navigazione e alle notifiche. |
| L'app supporta TLS 1.1 o versione successiva? | Sì |
| L'app o l'infrastruttura sottostante archivia i dati dei clienti Microsoft? | Sì |
| Quali dati vengono archiviati nei database? | Dati rilevanti per il corretto funzionamento del prodotto Intranet futuro. Sono incluse, a titolo esemplifica vole, notizie, storie, informazioni relative alla destinazione del contenuto a gruppi di utenti specifici, alla navigazione e alle notifiche. I dati correlati agli utenti sono copie di sola lettura di Azure AD. Questa operazione è limitata all'ID e al nome dell'utente e alla relativa appartenenza ai gruppi di Azure AD contrassegnati come rilevanti in anticipo. |
| Se l'infrastruttura sottostante elabora o archivia i dati dei clienti Microsoft, dove vengono archiviati geograficamente questi dati? | Paesi Bassi (i) |
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
| Si eseguono test di penetrazione annuali sull'app? | No |
| L'app dispone di un piano di ripristino di emergenza documentato, inclusa una strategia di backup e ripristino? | No |
| L'ambiente usa la protezione antimalware tradizionale o i controlli delle applicazioni? | TraditionalAntiMalware |
| Si dispone di un processo stabilito per l'individuazione e la classificazione dei rischi delle vulnerabilità di sicurezza? | No |
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
| Si dispone di software di rilevamento e prevenzione delle intrusioni (IDPS) distribuito nel perimetro del limite di rete che supporta l'app? | N/D |
| La registrazione eventi è configurata in tutti i componenti di sistema che supportano l'app? | Sì |
| Tutti i log vengono esaminati con cadenza regolare da strumenti umani o automatizzati per rilevare potenziali eventi di sicurezza? | Sì |
| Quando viene rilevato un evento di sicurezza, gli avvisi vengono inviati automaticamente a un dipendente per la valutazione? | Sì |
| È stato stabilito un processo formale di gestione dei rischi per la sicurezza delle informazioni? | No |
| Si dispone di un processo formale di risposta agli eventi imprevisti di sicurezza documentato e stabilito? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app è conforme al Health Insurance Portability and Accounting Act (HIPAA)? | N/D |
| L'app è conforme a Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | N/D |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 1)? | N/D |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 2)? | No |
| L'app è conforme ai controlli dell'organizzazione dei servizi (SOC 3)? | No |
| Si eseguono valutazioni PCI DSS annuali rispetto all'app e al relativo ambiente di supporto? | N/D |
| L'app International Organization for Standardization (ISO 27001) è certificata? | No |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27018)? | N/D |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27017)? | No |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27002)? | No |
| L'app Federal Risk and Authorization Management Program (FedRAMP) è conforme? | No |
| L'app è conforme al Family Educational Rights and Privacy Act (FERPA)? | N/D |
| L'app è conforme al Children's Online Privacy Protection Act (COPPA)? | N/D |
| L'app è conforme a Sarbanes-Oxley Act (SOX)? | N/D |
| L'app è conforme a NIST 800-171? | N/D |
| L'app è stata certificata da Cloud Security Alliance (CSA Star)? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Si dispone di gdpr o altri requisiti o obblighi di privacy o protezione dei dati (ad esempio CCPA)? | Sì |
| L'app ha un'informativa sulla privacy esterna che descrive come raccoglie, usa, condivide e archivia i dati dei clienti? | Sì |
| URL dell'informativa sulla privacy | https://www.aheadintranet.com/data-security |
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
| L'applicazione si integra con Microsoft Identity Platform (Azure AD) per l'accesso Single Sign-On, l'accesso alle API e così via? | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di controllo di integrazione Microsoft Identity Platform? | Sì |
| L'app usa la versione più recente di MSAL (Microsoft Authentication Library) o Microsoft Identity Web per l'autenticazione? | Sì |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | App client |
| L'app supporta la valutazione dell'accesso continuo (CAE) | No |
| L'app archivia le credenziali nel codice? | No |
| Le app e i componenti aggiuntivi per Microsoft 365 potrebbero usare altre API Microsoft all'esterno di Microsoft Graph. L'app o il componente aggiuntivo usa altre API Microsoft? | No |

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

>|   **Autorizzazione Graph**  | **Tipo autorizzazione** |          **Giustificazione**          | **Azure AD App ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Directory.Read.All | Delegato | Notizie di destinazione in base ai gruppi di Active Directory | [53360535-c93f-497f-b2a1-95bd9aa34283](../azure/53360535-c93f-497f-b2a1-95bd9aa34283.md) |
>| Directory.Read.All | Applicazione | Notizie di destinazione in base ai gruppi di Active Directory, per il push | [53360535-c93f-497f-b2a1-95bd9aa34283](../azure/53360535-c93f-497f-b2a1-95bd9aa34283.md) |
>| ExternalItem.Read.All | Delegato | Cercare contenuto da origini di terze parti (ServiceNow) | [53360535-c93f-497f-b2a1-95bd9aa34283](../azure/53360535-c93f-497f-b2a1-95bd9aa34283.md) |
>| Sites.Read.All | Delegato | Cercare contenuti nei siti di SharePoint | [53360535-c93f-497f-b2a1-95bd9aa34283](../azure/53360535-c93f-497f-b2a1-95bd9aa34283.md) |
>| User.Read | Delegato | Leggere il profilo utente | [53360535-c93f-497f-b2a1-95bd9aa34283](../azure/53360535-c93f-497f-b2a1-95bd9aa34283.md) |
>| User.Read | Delegato | Leggere il profilo dell'utente (immagine e così via) | [53360535-c93f-497f-b2a1-95bd9aa34283](../azure/53360535-c93f-497f-b2a1-95bd9aa34283.md) |
>| User.Read.All | Delegato | Leggere il profilo dell'utente | [53360535-c93f-497f-b2a1-95bd9aa34283](../azure/53360535-c93f-497f-b2a1-95bd9aa34283.md) |
>| User.Read.All | Applicazione | Leggere le informazioni sul profilo nella ricerca | [53360535-c93f-497f-b2a1-95bd9aa34283](../azure/53360535-c93f-497f-b2a1-95bd9aa34283.md) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

