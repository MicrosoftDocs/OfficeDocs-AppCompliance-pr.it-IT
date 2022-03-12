---
title: Informazioni sull'applicazione per il connettore ENA SmartUC da ENA
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/11/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per ENA SmartUC Connector, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: d2095a16fc5f3d9a0e28f8cf782ae292c330a947
ms.sourcegitcommit: 62e60dfc73f78900307418e60318353faf8d9a57
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/12/2022
ms.locfileid: "63459793"
---
# <a name="ena-smartuc-connector"></a>Connettore ENA SmartUC

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: March 11, 2022</p>

* <a href="https://teams.microsoft.com/l/app/029cfd5a-4413-499d-bda6-a2a0a3f5e70e" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003354" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da ENA a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | Connettore ENA SmartUC |
| ID | WA200003354 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | ENA |
| Sito Web aziendale | [https://www.ena.com](https://www.ena.com) |
| Condizioni per l'uso dell'app | [https://www.ena.com/legal/aup/](https://www.ena.com/legal/aup/) |
| Funzionalità di base dell'app | L'app connette il set di prodotti ENA SmartUC all'app Teams, consentendo agli utenti finali di effettuare chiamate telefoniche supportate da ENA SmartUC dall'Teams. |
| Sede centrale dell'azienda | Stati Uniti d'America |
| Pagina delle informazioni dell'app | |
| Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app? | Ibrido |
| Quali provider di cloud di hosting usa l'app? | In altri, le parti del servizio gestito da Metaswitch sono ospitate in Azure. È inoltre necessario includere informazioni dettagliate su come è ospitata la propria infrastruttura (ad esempio, i server EAS). |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da ENA su come questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app o l'infrastruttura sottostante elabora i dati relativi a un cliente Microsoft o al dispositivo? | Sì |
| Quali dati vengono elaborati dalla tua app? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| L'app supporta TLS 1.1 o versione successiva? | Sì |
| L'app o l'infrastruttura sottostante archivia i dati dei clienti Microsoft? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Esegui test di penetrazione annuali nell'app? | No |
| L'app dispone di un piano di ripristino di emergenza documentato, inclusa una strategia di backup e ripristino? | No |
| L'ambiente usa la protezione antimalware tradizionale o i controlli delle applicazioni? | TraditionalAntiMalware |
| Si dispone di un processo stabilito per l'identificazione e la classificazione dei rischi delle vulnerabilità di sicurezza? | Sì |
| Si dispone di un criterio che regola il contratto di servizio (SLA) per l'applicazione delle patch? | Sì |
| Si svolgono attività di gestione delle patch in base ai contratti di servizio dei criteri di applicazione delle patch? | Sì |
| L'ambiente include sistemi operativi o software non supportati? | No |
| Esegui l'analisi trimestrale delle vulnerabilità nella tua app e nell'infastruttura che la supporta? | Sì |
| Nel limite di rete esterno è installato un firewall? | Sì |
| Si dispone di un processo di gestione delle modifiche stabilito utilizzato per esaminare e approvare le richieste di modifica prima che siano distribuite nell'ambiente di produzione? | Sì |
| Un'altra persona sta esaminando e approvando tutte le richieste di modifica del codice inviate alla produzione dallo sviluppatore originale? | Sì |
| Le procedure di codifica protetta prendono in considerazione le classi di vulnerabilità comuni, ad esempio OWASP Top 10? | No |
| Autenticazione a più fattori abilitata per: | CodeRepositories, DNSManagement |
| Si dispone di un processo stabilito per il provisioning, la modifica e l'eliminazione degli account dei dipendenti? | Sì |
| Hai distribuito software di rilevamento e prevenzione delle intrusioni (IDPS) nel perimetro del limite di rete che supporta la tua app? | No |
| La registrazione eventi è impostata su tutti i componenti di sistema che supportano la tua app? | Sì |
| Tutti i log vengono esaminati a cadenza regolare da strumenti umani o automatizzati per rilevare potenziali eventi di sicurezza? | No|
| Quando viene rilevato un evento di sicurezza, gli avvisi vengono inviati automaticamente a un dipendente per il triage? | No |
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
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 2)? | No |
| Quale certificazione SOC 2 hai raggiunto? | |
| Data di certificazione SOC2 più recente | |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 3)? | No |
| Data di certificazione SOC3 più recente | |
| Eseguire valutazioni PCI DSS annuali sull'app e sull'ambiente di supporto? | No |
| L'app International Organization for Standardization (ISO 27001) è certificata? | No |
| L'app è conforme all'International Organization for Standardization (ISO 27018)? | No |
| L'app è conforme all'International Organization for Standardization (ISO 27017)? | No |
| L'app è conforme all'International Organization for Standardization (ISO 27002)? | No |
| L'app Federal Risk and Authorization Management Program (FedRAMP) è conforme? | No |
| L'app è conforme al Family Educational Rights and Privacy Act (FERPA)? | N/D |
| L'app è conforme al Children's Online Privacy Protection Act (COPPA)? | N/D |
| L'app è conforme Sarbanes-Oxley Act (SOX)? | No |
| L'app è conforme al NIST 800-171? | No |
| L'app è stata certificata da Cloud Security Alliance (CSA Star) ? | No |

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
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di Microsoft Identity Platform di integrazione? | No |
| L'app usa la versione più recente di MSAL (Microsoft Authentication Library) o Microsoft Identity Web per l'autenticazione? | Sì |
| Se l'app non usa una delle librerie precedenti, quali librerie di autenticazione usa? |  |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app supporta la valutazione dell'accesso continuo (CAE) | No |
| L'app archivia credenziali nel codice? | Sì |
| Le app e i componenti aggiuntivi per Microsoft 365 potrebbero usare API Microsoft aggiuntive al di fuori di Microsoft Graph. L'app o il componente aggiuntivo usa api Microsoft aggiuntive? | Sì |

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

>|   **Graph autorizzazioni**  | **Tipo autorizzazione** |          **Giustificazione**          | **Azure AD ID app** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| ChannelMember.Read.All | delegated | ID utente e nomi visualizzati dei membri del canale/chat corrente. L'app lo usa per presentare all'utente un elenco di membri di canale/chat da chiamare. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| Chat.ReadBasic | delegated | ID utente e nomi visualizzati dei membri della chat corrente. L'app lo usa per presentare all'utente un elenco di membri della chat da chiamare. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| People.Read.All | delegated | ID utente e nomi visualizzati dei membri del team corrente. L'app lo usa per presentare all'utente un elenco di membri del team da chiamare. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| User.Read.All | delegated | Numeri di telefono dell'azienda e del cellulare degli utenti. Questa operazione è necessaria per poter inizializzare le chiamate telefoniche a questi numeri. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| offline_access | delegated | Un token di autorizzazione per l'utente, che autorizza l'app ad accedere agli altri endpoint dell Graph API elencati per loro conto. Queste autorizzazioni di accesso sono necessarie per il funzionamento delle applicazioni della piattaforma Microsoft Identity. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| openid | delegated | Un token di autorizzazione per l'utente, che autorizza l'app ad accedere agli altri endpoint dell Graph API elencati per loro conto. Queste autorizzazioni di accesso sono necessarie per il funzionamento delle applicazioni della piattaforma Microsoft Identity. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| profile | delegated | Un token di autorizzazione per l'utente, che autorizza l'app ad accedere agli altri endpoint dell Graph API elencati per loro conto. Queste autorizzazioni di accesso sono necessarie per il funzionamento delle applicazioni della piattaforma Microsoft Identity. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

