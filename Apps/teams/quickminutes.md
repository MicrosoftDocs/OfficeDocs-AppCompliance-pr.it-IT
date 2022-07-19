---
title: Informazioni sull'applicazione per QuickMinutes di QuickMinutes
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 07/18/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per QuickMinutes, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 462cbb7aa74e6a1f4718554efdfc0e482a832b44
ms.sourcegitcommit: 21d1c42a8e6d9f94b9c8f279bbe37f649ebd4e10
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 07/19/2022
ms.locfileid: "66852714"
---
# <a name="quickminutes"></a>QuickMinutes

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 9 giugno 2022</p>

* <a href="https://teams.microsoft.com/l/app/5f60fe53-d441-4320-8c26-13fdaee9b58a" target="_blank">Visualizzazione in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200004414" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da QuickMinutes a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | QuickMinutes |
| ID | WA200004414 |
| client Office 365 supportati | Microsoft Teams |
| Nome della società partner | QuickMinutes |
| Sito Web dell'azienda | [https://quickminutes.com](https://quickminutes.com) |
| Condizioni per l'utilizzo dell'app | [https://quickminutes.com/privacy#/terms_of_service](https://quickminutes.com/privacy#/terms_of_service) |
| Funzionalità di base dell'app | Semplifica i flussi di lavoro online delle riunioni con il nostro assistente digitale intelligente. |
| Sede centrale dell'azienda | Irlanda |
| Pagina delle informazioni sull'app | [https://support.quickminutes.com/portal/en-gb/kb/articles/m...](https://support.quickminutes.com/portal/en-gb/kb/articles/microsoft-teams-integration-22-4-2020-1) |
| Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app? | Iaas |
| Quali provider di servizi cloud di hosting usano l'app? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da QuickMinutes su come questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app o l'infrastruttura sottostante elabora i dati relativi a un cliente Microsoft o al dispositivo? | Sì |
| Quali dati vengono elaborati dall'app? | I dati del profilo utente vengono usati per popolare le informazioni degli utenti nel database QuickMinutes quando l'utente registra un nuovo account con QuickMinutes usando Microsoft SSO. QuickMinutes esegue il pull dei dati del calendario degli utenti per visualizzare gli eventi nell'interfaccia utente di QuickMinutes. Queste informazioni non vengono archiviati nel database QuickMinutes, ma solo da API Graph e visualizzate all'utente.  |
| L'app supporta TLS 1.1 o versione successiva? | Sì |
| L'app o l'infrastruttura sottostante archivia i dati dei clienti Microsoft? | Sì |
| Quali dati vengono archiviati nei database? | Informazioni sul profilo utente, ad esempio Nome, Cognome, Email e immagine del profilo. Archiviamo anche i token di accesso e aggiornamento ms degli utenti. |
| Se l'infrastruttura sottostante elabora o archivia i dati dei clienti Microsoft, dove vengono archiviati geograficamente questi dati? | Irlanda |
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
| L'app dispone di un piano di ripristino di emergenza documentato, inclusa una strategia di backup e ripristino? | Sì |
| L'ambiente usa la protezione antimalware tradizionale o i controlli delle applicazioni? | TraditionalAntiMalware, ApplicationControls |
| Si dispone di un processo stabilito per l'individuazione e la classificazione dei rischi delle vulnerabilità di sicurezza? | No |
| Si dispone di un criterio che regola il contratto di servizio (SLA) per l'applicazione di patch? | Sì |
| Si eseguono attività di gestione delle patch in base ai contratti di servizio dei criteri di applicazione delle patch? | Sì |
| L'ambiente ha sistemi operativi o software non supportati? | No |
| Si esegue l'analisi trimestrale delle vulnerabilità nell'app e nell'infrastruttura che la supporta? | No |
| È installato un firewall sul limite di rete esterno? | Sì |
| Si dispone di un processo di gestione delle modifiche stabilito usato per esaminare e approvare le richieste di modifica prima che vengano distribuite nell'ambiente di produzione? | Sì |
| Una persona aggiuntiva sta esaminando e approvando tutte le richieste di modifica del codice inviate all'ambiente di produzione dallo sviluppatore originale? | Sì |
| Le procedure di codifica sicura tengono conto delle classi di vulnerabilità comuni, ad esempio OWASP Top 10? | Sì |
| Autenticazione a più fattori abilitata per: | DNSManagement, Credential, CodeRepositories |
| Si dispone di un processo stabilito per il provisioning, la modifica e l'eliminazione degli account dei dipendenti? | Sì |
| Si dispone di software di rilevamento e prevenzione delle intrusioni (IDPS) distribuito nel perimetro del limite di rete che supporta l'app? | Sì |
| La registrazione eventi è configurata in tutti i componenti di sistema che supportano l'app? | Sì |
| Tutti i log vengono esaminati con cadenza regolare da strumenti umani o automatizzati per rilevare potenziali eventi di sicurezza? | No |
| Quando viene rilevato un evento di sicurezza, gli avvisi vengono inviati automaticamente a un dipendente per la valutazione? | No |
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
| L'app è conforme al Family Educational Rights and Privacy Act (FERPA)? | No |
| L'app è conforme al Children's Online Privacy Protection Act (COPPA)? | No |
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
| URL dell'informativa sulla privacy | https://quickminutes.com/privacy#/privacy_policy |
| L'app esegue un processo decisionale automatizzato, inclusa la profilatura che potrebbe avere un effetto legale o un impatto simile? | No |
| L'app elabora i dati dei clienti per uno scopo secondario non descritto nell'informativa sulla privacy (ad esempio marketing, analisi)? | No |
| Si elaborano categorie speciali di dati sensibili (ad esempio, origine razziale o etnica, opinione politica, credenze religiose o filosofiche, dati genetici o biometrici, dati sanitari) o categorie di dati soggetti a leggi sulle notifiche di violazione? | No |
| L'app raccoglie o elabora i dati di minori (ad esempio, persone di età inferiore ai 16 anni)? | No |
| L'app ha funzionalità per eliminare i dati personali di un individuo su richiesta? | Sì |
| L'app ha funzionalità per limitare o limitare il trattamento dei dati personali di un individuo su richiesta? | No |
| L'app offre agli utenti la possibilità di correggere o aggiornare i propri dati personali? | Sì |
| Vengono eseguite regolari verifiche della sicurezza dei dati e della privacy (ad esempio, valutazioni dell'impatto sulla protezione dei dati o valutazioni dei rischi per la privacy) per identificare i rischi correlati al trattamento dei dati personali per l'app? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'applicazione si integra con Microsoft Identity Platform (Azure AD) per l'accesso Single Sign-On, l'accesso alle API e così via? | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di controllo di integrazione Microsoft Identity Platform? | Sì |
| L'app usa la versione più recente di MSAL (Microsoft Authentication Library) o Microsoft Identity Web per l'autenticazione? | N/D |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app supporta la valutazione dell'accesso continuo (CAE) | No |
| L'app archivia le credenziali nel codice? | No |
| Le app e i componenti aggiuntivi per Microsoft 365 potrebbero usare altre API Microsoft all'esterno di Microsoft Graph. L'app o il componente aggiuntivo usa altre API Microsoft? | No |

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

>|   **Autorizzazione Graph**  | **Tipo autorizzazione** |          **Giustificazione**          | **Azure AD App ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegato | L'ambito del calendario viene usato da QuickMinutes per leggere/scrivere riunioni QuickMinutes nell'utente Calendario Microsoft | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |
>| People.Read | Delegato | L'ambito delle persone viene usato da QuickMinutes per elencare i contatti degli utenti Microsoft quando aggiungono utenti all'organizzazione o al gruppo QuickMinutes | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |
>| email | Delegato | L'ambito di posta elettronica viene usato per concedere a QuickMinutes l'accesso all'indirizzo di posta elettronica principale dell'utente sotto forma di attestazione di posta elettronica. | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |
>| openid | Delegato | L'ambito openid viene usato da QuickMinutes nell'endpoint del token Microsoft Identity Platform per acquisire i token ID. In questo modo QuickMinutes può usare i token per accedere alla API Graph per conto degli utenti | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |
>| profile | Delegato | L'ambito del profilo viene usato da QuickMinutes per accedere al profilo degli utenti quando li registriamo tramite Microsoft SSO e creiamo il loro account QuickMinutes. | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

