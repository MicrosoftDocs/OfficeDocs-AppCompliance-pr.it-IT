---
title: Informazioni sull'applicazione per la registrazione della conformità Luware per Microsoft Teams da Luware AG
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 12/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per La registrazione della conformità Luware per Microsoft Teams, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: a935073cd26f7f8842467eb6dd866217e706fc59
ms.sourcegitcommit: 5e2cd59a54fc018a6df761b00c18e3ba592d9dba
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/15/2022
ms.locfileid: "64881433"
---
# <a name="luware-compliance-recording-for-microsoft-teams"></a>Registrazione della conformità Luware per Microsoft Teams

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 21 ottobre 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/luwareagzurich.recording_azure_marketplace" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Luware AG a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Registrazione della conformità Luware per Microsoft Teams |
| ID | luwareagzurich.recording_azure_marketplace |
| Nome della società partner | Gruppo di disponibilità Luware |
| Sito Web dell'azienda | [https://luware.com](https://luware.com) |
| Condizioni per l'utilizzo dell'app | [https://luware.com/en/agreements/saas/](https://luware.com/en/agreements/saas/) |
| Funzionalità di base dell'app | Soluzione cloud che consente di acquisire, archiviare, analizzare e recuperare tutte le modalità di comunicazione. |
| Sede centrale dell'azienda | Svizzera |
| Pagina delle informazioni sull'app | [https://luware.com/en/solution/microsoft-teams-recording/](https://luware.com/en/solution/microsoft-teams-recording/) |
| Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app? | Paas |
| Quali provider di servizi cloud di hosting usano l'app? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Luware AG su come questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app o l'infrastruttura sottostante elabora i dati relativi a un cliente Microsoft o al dispositivo? | Sì |
| Quali dati vengono elaborati dall'app? | Informazioni sul chiamante/chiamato (numeri di telefono, upn, durata, indirizzo di posta elettronica &amp; e così via), Dettagli chiamata, metadati,  |
| L'app supporta TLS 1.1 o versione successiva? | Sì |
| L'app o l'infrastruttura sottostante archivia i dati dei clienti Microsoft? | Sì |
| Quali dati vengono archiviati nei database? | ID oggetto di Azure, UPN, indirizzo di posta elettronica &amp; im, nome visualizzato, nome, cognome, posizione (facoltativo), reparto (facoltativo) |
| Se l'infrastruttura sottostante elabora o archivia i dati dei clienti Microsoft, dove vengono archiviati geograficamente questi dati? | Svizzera |
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
| L'ambiente usa la protezione antimalware tradizionale o i controlli delle applicazioni? | TraditionalAntiMalware |
| Si dispone di un processo stabilito per l'individuazione e la classificazione dei rischi delle vulnerabilità di sicurezza? | Sì |
| Si dispone di un criterio che regola il contratto di servizio (SLA) per l'applicazione di patch? | Sì |
| Si eseguono attività di gestione delle patch in base ai contratti di servizio dei criteri di applicazione delle patch? | Sì |
| L'ambiente ha sistemi operativi o software non supportati? | No |
| Si esegue l'analisi trimestrale delle vulnerabilità nell'app e nell'infrastruttura che la supporta? | No |
| È installato un firewall sul limite di rete esterno? | Sì |
| Si dispone di un processo di gestione delle modifiche stabilito usato per esaminare e approvare le richieste di modifica prima che vengano distribuite nell'ambiente di produzione? | Sì |
| Una persona aggiuntiva sta esaminando e approvando tutte le richieste di modifica del codice inviate all'ambiente di produzione dallo sviluppatore originale? | Sì |
| Le procedure di codifica sicura tengono conto delle classi di vulnerabilità comuni, ad esempio OWASP Top 10? | No |
| Autenticazione a più fattori abilitata per: | Credential |
| Si dispone di un processo stabilito per il provisioning, la modifica e l'eliminazione degli account dei dipendenti? | Sì |
| Si dispone di software di rilevamento e prevenzione delle intrusioni (IDPS) distribuito nel perimetro del limite di rete che supporta l'app? | N/D |
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
| L'app è conforme al Health Insurance Portability and Accounting Act (HIPAA)? | N/D |
| L'app è conforme a Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | N/D |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 1)? | N/D |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 2)? | No |
| L'app è conforme ai controlli dell'organizzazione dei servizi (SOC 3)? | No |
| Si eseguono valutazioni PCI DSS annuali rispetto all'app e al relativo ambiente di supporto? | N/D |
| L'app International Organization for Standardization (ISO 27001) è certificata? | Sì |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27018)? | No |
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
| URL dell'informativa sulla privacy | https://luware.com/en/privacy-policy/ |
| L'app esegue un processo decisionale automatizzato, inclusa la profilatura che potrebbe avere un effetto legale o un impatto simile? | No |
| L'app elabora i dati dei clienti per uno scopo secondario non descritto nell'informativa sulla privacy (ad esempio marketing, analisi)? | No |
| Si elaborano categorie speciali di dati sensibili (ad esempio, origine razziale o etnica, opinione politica, credenze religiose o filosofiche, dati genetici o biometrici, dati sanitari) o categorie di dati soggetti a leggi sulle notifiche di violazione? | No |
| L'app raccoglie o elabora i dati di minori (ad esempio, persone di età inferiore ai 16 anni)? | No |
| L'app ha funzionalità per eliminare i dati personali di un individuo su richiesta? | Sì |
| L'app ha funzionalità per limitare o limitare il trattamento dei dati personali di un individuo su richiesta? | No |
| L'app offre agli utenti la possibilità di correggere o aggiornare i propri dati personali? | No |
| Vengono eseguite regolari verifiche della sicurezza dei dati e della privacy (ad esempio, valutazioni dell'impatto sulla protezione dei dati o valutazioni dei rischi per la privacy) per identificare i rischi correlati al trattamento dei dati personali per l'app? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'applicazione si integra con Microsoft Identity Platform (Azure AD) per l'accesso Single Sign-On, l'accesso API e così via? | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di controllo di integrazione Microsoft Identity Platform? | Sì |
| L'app usa la versione più recente di MSAL (Microsoft Authentication Library) o Microsoft Identity Web per l'autenticazione? | Sì |
| Se l'app non usa una delle librerie precedenti, quale libreria o libreria di autenticazione usa? | Oauth 2.0 |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app supporta la valutazione dell'accesso continuo (CAE) | No |
| L'app archivia le credenziali nel codice? | No |
| Le app e i componenti aggiuntivi per Microsoft 365 potrebbero usare api Microsoft aggiuntive all'esterno di Microsoft Graph. L'app o il componente aggiuntivo usa altre API Microsoft? | No |

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

>|   **Autorizzazione Graph**  | **Tipo autorizzazione** |          **Giustificazione**          | **ID app Azure AD** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Calls.AccessMedia.All | Applicazione | registrazione Teams | [5e5d72e0-2df7-4ca7-be58-81dc28d3bdad](../azure/5e5d72e0-2df7-4ca7-be58-81dc28d3bdad.md) |
>| Calls.Initiate.All | Applicazione | registrazione Teams | [5e5d72e0-2df7-4ca7-be58-81dc28d3bdad](../azure/5e5d72e0-2df7-4ca7-be58-81dc28d3bdad.md) |
>| Calls.InitiateGroupCall.All | Applicazione | registrazione Teams | [5e5d72e0-2df7-4ca7-be58-81dc28d3bdad](../azure/5e5d72e0-2df7-4ca7-be58-81dc28d3bdad.md) |
>| Calls.JoinGroupCall.All | Applicazione | registrazione Teams | [5e5d72e0-2df7-4ca7-be58-81dc28d3bdad](../azure/5e5d72e0-2df7-4ca7-be58-81dc28d3bdad.md) |
>| Calls.JoinGroupCallasGuest.All | Applicazione | registrazione Teams | [5e5d72e0-2df7-4ca7-be58-81dc28d3bdad](../azure/5e5d72e0-2df7-4ca7-be58-81dc28d3bdad.md) |
>| Group.Read.All | Applicazione | registrazione Teams | [5e5d72e0-2df7-4ca7-be58-81dc28d3bdad](../azure/5e5d72e0-2df7-4ca7-be58-81dc28d3bdad.md) |
>| GroupMember.Read.All | Applicazione | registrazione Teams | [5e5d72e0-2df7-4ca7-be58-81dc28d3bdad](../azure/5e5d72e0-2df7-4ca7-be58-81dc28d3bdad.md) |
>| OnlineMeetings.Read.All | Applicazione | registrazione Teams | [5e5d72e0-2df7-4ca7-be58-81dc28d3bdad](../azure/5e5d72e0-2df7-4ca7-be58-81dc28d3bdad.md) |
>| OnlineMeetings.ReadWrite.All | Applicazione | registrazione Teams | [5e5d72e0-2df7-4ca7-be58-81dc28d3bdad](../azure/5e5d72e0-2df7-4ca7-be58-81dc28d3bdad.md) |
>| User.Read | Delegato | Single Sign-On | [5e5d72e0-2df7-4ca7-be58-81dc28d3bdad](../azure/5e5d72e0-2df7-4ca7-be58-81dc28d3bdad.md) |
>| User.Read.All | Applicazione | registrazione Teams | [5e5d72e0-2df7-4ca7-be58-81dc28d3bdad](../azure/5e5d72e0-2df7-4ca7-be58-81dc28d3bdad.md) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

