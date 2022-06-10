---
title: Informazioni sull'applicazione per Confluence Cloud di Atlassian
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 06/09/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Confluence Cloud, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 1534755072b148cfd57e4eb479f69f328c7b92ac
ms.sourcegitcommit: 6e1bedf47a32902e15f956a9492d8f5ec44a9650
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 06/09/2022
ms.locfileid: "65982160"
---
# <a name="confluence-cloud"></a>Confluence Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 9 giugno 2022</p>

* <a href="https://teams.microsoft.com/l/app/30bb610c-6321-40fe-a047-056e7d0dac96" target="_blank">Visualizza in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003113" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Atlassian a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Confluence Cloud |
| ID | WA200003113 |
| client Office 365 supportati | Microsoft Teams |
| Nome della società partner | Atlassian |
| Sito Web dell'azienda | [https://www.atlassian.com](https://www.atlassian.com) |
| Condizioni per l'utilizzo dell'app | [https://www.atlassian.com/licensing/marketplace/termsofuse](https://www.atlassian.com/licensing/marketplace/termsofuse) |
| Funzionalità di base dell'app | Prendere facilmente appunti sulle riunioni, condividere pagine e rimanere aggiornati con Confluence Cloud per Teams.  |
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
>| Calendars.Read | Delegato | - Leggiamo l'elenco dei membri della chat in una riunione, quindi conosciamo l'elenco degli invitati alla riunione. - Gli utenti vengono letti&#8217; nomi e indirizzi di posta elettronica visualizzati in modo condizionale nell'app per le riunioni. Ad esempio, visualizzare il nome dell'utente corrente che prende note sulla riunione. - L'app legge l'utente&#8217;'evento del calendario in cui l'app è stata aggiunta a una riunione in modo da avere informazioni di base sulla riunione, ad esempio il titolo della riunione.     | [4aa38041-66a2-41a4-ac97-55bc828a9803](../azure/4aa38041-66a2-41a4-ac97-55bc828a9803.md) |
>| Chat.ReadBasic | Delegato | - Leggiamo l'elenco dei membri della chat in una riunione, quindi conosciamo l'elenco degli invitati alla riunione. - Gli utenti vengono letti&#8217; nomi e indirizzi di posta elettronica visualizzati in modo condizionale nell'app per le riunioni. Ad esempio, visualizzare il nome dell'utente corrente che prende note sulla riunione. - L'app legge l'utente&#8217;'evento del calendario in cui l'app è stata aggiunta a una riunione in modo da avere informazioni di base sulla riunione, ad esempio il titolo della riunione. | [4aa38041-66a2-41a4-ac97-55bc828a9803](../azure/4aa38041-66a2-41a4-ac97-55bc828a9803.md) |
>| User.ReadBasic.All | Delegato | - Leggiamo l'elenco dei membri della chat in una riunione, quindi conosciamo l'elenco degli invitati alla riunione. - Gli utenti vengono letti&#8217; nomi e indirizzi di posta elettronica visualizzati in modo condizionale nell'app per le riunioni. Ad esempio, visualizzare il nome dell'utente corrente che prende note sulla riunione. - L'app legge l'utente&#8217;'evento del calendario in cui l'app è stata aggiunta a una riunione in modo da avere informazioni di base sulla riunione, ad esempio il titolo della riunione. | [4aa38041-66a2-41a4-ac97-55bc828a9803](../azure/4aa38041-66a2-41a4-ac97-55bc828a9803.md) |
>| email | Delegato | - Leggiamo l'elenco dei membri della chat in una riunione, quindi conosciamo l'elenco degli invitati alla riunione. - Gli utenti vengono letti&#8217; nomi e indirizzi di posta elettronica visualizzati in modo condizionale nell'app per le riunioni. Ad esempio, visualizzare il nome dell'utente corrente che prende note sulla riunione. - L'app legge l'utente&#8217;'evento del calendario in cui l'app è stata aggiunta a una riunione in modo da avere informazioni di base sulla riunione, ad esempio il titolo della riunione.  | [4aa38041-66a2-41a4-ac97-55bc828a9803](../azure/4aa38041-66a2-41a4-ac97-55bc828a9803.md) |
>| offline_access | Delegato | - Leggiamo l'elenco dei membri della chat in una riunione, quindi conosciamo l'elenco degli invitati alla riunione. - Gli utenti vengono letti&#8217; nomi e indirizzi di posta elettronica visualizzati in modo condizionale nell'app per le riunioni. Ad esempio, visualizzare il nome dell'utente corrente che prende note sulla riunione. - L'app legge l'utente&#8217;'evento del calendario in cui l'app è stata aggiunta a una riunione in modo da avere informazioni di base sulla riunione, ad esempio il titolo della riunione. | [4aa38041-66a2-41a4-ac97-55bc828a9803](../azure/4aa38041-66a2-41a4-ac97-55bc828a9803.md) |
>| openid | Delegato | - Leggiamo l'elenco dei membri della chat in una riunione, quindi conosciamo l'elenco degli invitati alla riunione. - Gli utenti vengono letti&#8217; nomi e indirizzi di posta elettronica visualizzati in modo condizionale nell'app per le riunioni. Ad esempio, visualizzare il nome dell'utente corrente che prende note sulla riunione. - L'app legge l'utente&#8217;'evento del calendario in cui l'app è stata aggiunta a una riunione in modo da avere informazioni di base sulla riunione, ad esempio il titolo della riunione. | [4aa38041-66a2-41a4-ac97-55bc828a9803](../azure/4aa38041-66a2-41a4-ac97-55bc828a9803.md) |
>| profile | Delegato | - Leggiamo l'elenco dei membri della chat in una riunione, quindi conosciamo l'elenco degli invitati alla riunione. - Gli utenti vengono letti&#8217; nomi e indirizzi di posta elettronica visualizzati in modo condizionale nell'app per le riunioni. Ad esempio, visualizzare il nome dell'utente corrente che prende note sulla riunione. - L'app legge l'utente&#8217;'evento del calendario in cui l'app è stata aggiunta a una riunione in modo da avere informazioni di base sulla riunione, ad esempio il titolo della riunione. | [4aa38041-66a2-41a4-ac97-55bc828a9803](../azure/4aa38041-66a2-41a4-ac97-55bc828a9803.md) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

