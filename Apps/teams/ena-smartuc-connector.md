---
title: Informazioni sull'applicazione per ENA SmartUC Connector di ENA
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/11/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni sulla sicurezza e sulla conformità disponibili per ENA SmartUC Connector, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 3f2f49283d559d7d1392339969884fb50ba2a777
ms.sourcegitcommit: 5e2cd59a54fc018a6df761b00c18e3ba592d9dba
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/15/2022
ms.locfileid: "64876403"
---
# <a name="ena-smartuc-connector"></a>Connettore ENA SmartUC

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 11 marzo 2022</p>

* <a href="https://teams.microsoft.com/l/app/029cfd5a-4413-499d-bda6-a2a0a3f5e70e" target="_blank">Visualizza in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003354" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da ENA a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Connettore ENA SmartUC |
| ID | WA200003354 |
| client Office 365 supportati | Microsoft Teams |
| Nome della società partner | ENA |
| Sito Web dell'azienda | [https://www.ena.com](https://www.ena.com) |
| Condizioni per l'utilizzo dell'app | [https://www.ena.com/legal/aup/](https://www.ena.com/legal/aup/) |
| Funzionalità di base dell'app | L'app connette il set di prodotti ENA SmartUC all'app Teams, consentendo agli utenti finali di effettuare chiamate telefoniche supportate da ENA SmartUC dall'interno Teams. |
| Sede centrale dell'azienda | Stati Uniti d'America |
| Pagina delle informazioni sull'app | |
| Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app? | Ibrido |
| Quali provider di servizi cloud di hosting usano l'app? | Altre, Le parti del servizio gestite da Metaswitch sono ospitate in Azure. È anche necessario includere dettagli sul modo in cui è ospitata la propria infrastruttura (ad esempio, i server EAS). |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da ENA su come questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app o l'infrastruttura sottostante elabora i dati relativi a un cliente Microsoft o al dispositivo? | Sì |
| Quali dati vengono elaborati dall'app? | I seguenti EUII/OII possono essere trasferiti all'API JSON CommPortal tramite il proxy MCT: indirizzo IP, chiamata del numero di telefono dell'utente, Password, token di autenticazione CommPortal, ID sessione CommPortal, numero di telefono di Callee quando si effettua una chiamata, Domini di indirizzi di posta elettronica. |
| L'app supporta TLS 1.1 o versione successiva? | Sì |
| L'app o l'infrastruttura sottostante archivia i dati dei clienti Microsoft? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Di seguito sono riportate le informazioni del catalogo [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Si eseguono test di penetrazione annuali sull'app? | No |
| L'app dispone di un piano di ripristino di emergenza documentato, inclusa una strategia di backup e ripristino? | No |
| L'ambiente usa la protezione antimalware tradizionale o i controlli delle applicazioni? | TraditionalAntiMalware |
| Si dispone di un processo stabilito per l'individuazione e la classificazione dei rischi delle vulnerabilità di sicurezza? | Sì |
| Si dispone di un criterio che regola il contratto di servizio (SLA) per l'applicazione di patch? | Sì |
| Si eseguono attività di gestione delle patch in base ai contratti di servizio dei criteri di applicazione delle patch? | Sì |
| L'ambiente ha sistemi operativi o software non supportati? | No |
| Si esegue l'analisi trimestrale delle vulnerabilità nell'app e nell'infrastruttura che la supporta? | Sì |
| È installato un firewall sul limite di rete esterno? | Sì |
| Si dispone di un processo di gestione delle modifiche stabilito usato per esaminare e approvare le richieste di modifica prima che vengano distribuite nell'ambiente di produzione? | Sì |
| Una persona aggiuntiva sta esaminando e approvando tutte le richieste di modifica del codice inviate all'ambiente di produzione dallo sviluppatore originale? | Sì |
| Le procedure di codifica sicura tengono conto delle classi di vulnerabilità comuni, ad esempio OWASP Top 10? | No |
| Autenticazione a più fattori abilitata per: | CodeRepositories, DNSManagement |
| Si dispone di un processo stabilito per il provisioning, la modifica e l'eliminazione degli account dei dipendenti? | Sì |
| Si dispone di software di rilevamento e prevenzione delle intrusioni (IDPS) distribuito nel perimetro del limite di rete che supporta l'app? | No |
| La registrazione eventi è configurata in tutti i componenti di sistema che supportano l'app? | Sì |
| Tutti i log vengono esaminati con cadenza regolare da strumenti umani o automatizzati per rilevare potenziali eventi di sicurezza? | No |
| Quando viene rilevato un evento di sicurezza, gli avvisi vengono inviati automaticamente a un dipendente per la valutazione? | No |
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
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 2)? | No |
| L'app è conforme ai controlli dell'organizzazione dei servizi (SOC 3)? | No |
| Si eseguono valutazioni PCI DSS annuali rispetto all'app e al relativo ambiente di supporto? | No |
| L'app International Organization for Standardization (ISO 27001) è certificata? | No |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27018)? | No |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27017)? | No |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27002)? | No |
| L'app Federal Risk and Authorization Management Program (FedRAMP) è conforme? | No |
| L'app è conforme al Family Educational Rights and Privacy Act (FERPA)? | N/D |
| L'app è conforme al Children's Online Privacy Protection Act (COPPA)? | N/D |
| L'app è conforme a Sarbanes-Oxley Act (SOX)? | No |
| L'app è conforme a NIST 800-171? | No |
| L'app è stata certificata da Cloud Security Alliance (CSA Star)? | No |

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
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di controllo di integrazione Microsoft Identity Platform? | No |
| L'app usa la versione più recente di MSAL (Microsoft Authentication Library) o Microsoft Identity Web per l'autenticazione? | Sì |
| Se l'app non usa una delle librerie precedenti, quale libreria o libreria di autenticazione usa? |  |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app supporta la valutazione dell'accesso continuo (CAE) | No |
| L'app archivia le credenziali nel codice? | Sì |
| Le app e i componenti aggiuntivi per Microsoft 365 potrebbero usare api Microsoft aggiuntive all'esterno di Microsoft Graph. L'app o il componente aggiuntivo usa altre API Microsoft? | Sì |

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

>|   **Autorizzazione Graph**  | **Tipo autorizzazione** |          **Giustificazione**          | **ID app Azure AD** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| ChannelMember.Read.All | Delegato | ID utente e nomi visualizzati dei membri del canale/chat corrente. L'app usa questa opzione per presentare all'utente un elenco di membri del canale/chat da chiamare. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| Chat.ReadBasic | Delegato | ID utente e nomi visualizzati dei membri della chat corrente. L'app usa questa opzione per presentare all'utente un elenco di membri della chat da chiamare. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| People.Read.All | Delegato | ID utente e nomi visualizzati dei membri del team corrente. L'app usa questa opzione per presentare all'utente un elenco di membri del team da chiamare. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| User.Read.All | Delegato | Numero di telefono aziendale e cellulare degli utenti. Ciò è necessario in modo che sia possibile avviare le chiamate telefoniche a questi numeri. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| offline_access | Delegato | Token di autorizzazione per l'utente, che autorizza l'app ad accedere agli altri endpoint API Graph elencati per loro conto. Queste autorizzazioni di accesso sono necessarie per il funzionamento delle applicazioni di Microsoft Identity Platform. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| openid | Delegato | Token di autorizzazione per l'utente, che autorizza l'app ad accedere agli altri endpoint API Graph elencati per loro conto. Queste autorizzazioni di accesso sono necessarie per il funzionamento delle applicazioni di Microsoft Identity Platform. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |
>| profile | Delegato | Token di autorizzazione per l'utente, che autorizza l'app ad accedere agli altri endpoint API Graph elencati per loro conto. Queste autorizzazioni di accesso sono necessarie per il funzionamento delle applicazioni di Microsoft Identity Platform. | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](../azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e.md) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

