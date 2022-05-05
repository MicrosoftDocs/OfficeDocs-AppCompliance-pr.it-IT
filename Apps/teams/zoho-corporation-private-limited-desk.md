---
title: Informazioni sull'applicazione per Zoho Desk di Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/19/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Zoho Desk, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 6386c25acea352558965af02c99a49cd79baff6b
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/05/2022
ms.locfileid: "65227998"
---
# <a name="zoho-desk"></a>Zoho Desk

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 20 ottobre 2021</p>

* [Visualizza in Teams store](https://teams.microsoft.com/l/app/091ec948-c0ee-4d56-aa9e-51c3d8316a9c)
* [Visualizzazione in AppSource](https://appsource.microsoft.com/product/office/WA104382044)

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Zoho Corporation Private Limited a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Zoho Desk |
| ID | WA104382044 |
| client Office 365 supportati | Microsoft Teams |
| Nome della società partner | Zoho Corporation Private Limited |
| Sito Web dell'azienda | [https://www.zoho.com](https://www.zoho.com) |
| Condizioni per l'utilizzo dell'app | [https://www.zoho.com/terms.html](https://www.zoho.com/terms.html) |
| Funzionalità di base dell'app | Zoho Desk è un software di help desk basato sul Web che offre la possibilità di gestire in modo efficiente le attività di supporto clienti. Zoho Desk consente di assegnare, tenere traccia e configurare facilmente gli avvisi sui ticket dell'help desk. È possibile personalizzare Zoho Desk per la propria azienda e garantire soddisfazione nell'esperienza di supporto clienti. |
| Sede centrale dell'azienda | Stati Uniti d'America |
| Pagina delle informazioni sull'app | [https://www.zoho.com/desk/help/](https://www.zoho.com/desk/help/) |
| Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app? | IsvHosted |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Zoho Corporation Private Limited su come questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elencare le [autorizzazioni di Microsoft Graph](/graph/permissions-reference) necessarie per questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (delegata/applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **ID app Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.Read | Delegato |  | Leggere i file utente. |  |
>| Files.Read.All | Delegato |  | Leggere tutti i file a cui l'utente può accedere. |  |
>| User.Read | Delegato |  | Accedere e leggere il profilo utente. |  |
>| User.ReadBasic.All | Delegato |  | Leggere tutti i profili di base degli utenti. |  |
>| email | Delegato |  | Visualizzare l'indirizzo di posta elettronica dell'utente. |  |
>| offline_access | Delegato |  | Mantenere l'accesso ai dati a cui è stato concesso l'accesso. |  |
>| profile | Delegato |  | Visualizzare il profilo di base dell'utente. |  |


#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con un servizio non Microsoft, elencare il servizio non Microsoft usato dall'app, i dati trasferiti e includere una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono usati servizi Microsoft.

#### <a name="data-access-via-bots"></a>Accesso ai dati tramite bot

Se questa app contiene un bot o un'estensione di messaggistica, può accedere alle informazioni identificabili dell'utente finale (EUII): il roster (nome, cognome, nome visualizzato, indirizzo di posta elettronica) di qualsiasi membro del team in un team o chat a cui viene aggiunto. Questa app usa questa funzionalità?

>Non è possibile accedere all'identità dell'identità dell'utente.


#### <a name="telemetry-data"></a>Dati di telemetria

Nei dati di telemetria o nei log dell'applicazione vengono visualizzate informazioni personali dell'organizzazione o informazioni personali dell'utente finale( EUII) ? In caso affermativo, descrivere quali dati vengono archiviati e quali sono i criteri di conservazione e rimozione?

>No

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio l'eliminazione, la conservazione, il controllo, l'archiviazione, i criteri degli utenti finali e così via.

>1)C'è un'opzione nell'interfaccia utente per eliminare le entità, gli amministratori e gli agenti all'interno del desk Zoho con opzioni di eliminazione possono eseguire questa operazione. 2) Sono disponibili anche opzioni per l'esportazione tramite le quali l'amministratore può esportare e ottenere per il proprio scopo.  3) Manteniamo il controllo nel back-end, quando il cliente richiede queste informazioni possono essere fornite.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app o l'infrastruttura sottostante elabora i dati relativi a un cliente Microsoft o al dispositivo? | Sì |
| Quali dati vengono elaborati dall'app? | Dati del profilo, Webhook conversazione personale. |
| L'app supporta TLS 1.1 o versione successiva? | Sì |
| L'app o l'infrastruttura sottostante archivia i dati dei clienti Microsoft? | Sì |
| Quali dati vengono archiviati nei database? | ID utente, nome utente, indirizzo di posta elettronica |
| Se l'infrastruttura sottostante elabora o archivia i dati dei clienti Microsoft, dove vengono archiviati geograficamente questi dati? | Stati Uniti d'America, Irlanda, Paesi Bassi (i), Cina, Giappone, India, Australia |
| Si dispone di un processo di noleggio e smaltimento dei dati stabilito? | Sì |
| Per quanto tempo vengono conservati i dati dopo la chiusura dell'account? | Meno di 90 giorni |
| Si dispone di un processo di gestione dell'accesso ai dati stabilito? | Sì |
| Trasferisci i dati dei clienti o il contenuto del cliente a terze parti o sub-responsabili del trattamento? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Di seguito sono riportate le informazioni del catalogo [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security).

<iframe height='1020' title='informazioni Microsoft Cloud App Security' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28308' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28308" target="_blank">Visualizza in una nuova</a> 
| **schedaInformazioni** | **sulle** |
|:----------------|:-------------|
| informazioni Eseguire test di penetrazione annuali nell'app? | Sì |
| L'app ha un piano di ripristino di emergenza documentato, inclusa una strategia di backup e ripristino? | Sì |
| L'ambiente usa la protezione antimalware tradizionale o i controlli delle applicazioni? | TraditionalAntiMalware, ApplicationControls |
| Si dispone di un processo stabilito per identificare e classificare i rischi delle vulnerabilità di sicurezza? | Sì |
| Si dispone di un criterio che regola il contratto di servizio (SLA) per l'applicazione di patch? | Sì |
| Si eseguono attività di gestione delle patch in base ai contratti di servizio dei criteri di applicazione delle patch? | Sì |
| L'ambiente ha sistemi operativi o software non supportati? | No |
| Eseguire l'analisi trimestrale delle vulnerabilità nell'app e nell'infrastruttura che la supporta? | Sì |
| Si dispone di un firewall installato nel limite di rete esterno? | Sì |
| Si dispone di un processo di gestione delle modifiche stabilito usato per esaminare e approvare le richieste di modifica prima che vengano distribuite nell'ambiente di produzione? | Sì |
| : un'altra persona esamina e approva tutte le richieste di modifica del codice inviate all'ambiente di produzione dallo sviluppatore originale? | Sì |
| Le procedure di codifica sicura tengono conto delle classi di vulnerabilità comuni, ad esempio OWASP Top 10? | Sì |
| Autenticazione a più fattori (MFA) abilitata per: | CodeRepositories, DNSManagement, Credential |
| Si dispone di un processo stabilito per il provisioning, la modifica e l'eliminazione degli account dei dipendenti? | Sì |
| Si dispone di software di rilevamento e prevenzione delle intrusioni (IDPS) distribuito nel perimetro del limite di rete che supporta l'app? | Sì |
| La registrazione eventi è configurata in tutti i componenti di sistema che supportano l'app? | Sì |
| Tutti i log vengono esaminati a cadenza regolare da strumenti umani o automatizzati per rilevare potenziali eventi di sicurezza? | Sì |
| Quando viene rilevato un evento di sicurezza, gli avvisi vengono inviati automaticamente a un dipendente per la valutazione? | Sì |
| È stato stabilito un processo formale di gestione dei rischi per la sicurezza delle informazioni? | Sì |
| Si dispone di un processo formale di risposta agli eventi imprevisti di sicurezza documentato e stabilito? | Sì |
| Segnala le violazioni dei dati di app o servizi alle autorità di vigilanza e alle persone interessate dalla violazione entro 72 ore dal rilevamento? | Sì |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app è conforme al Health Insurance Portability and Accounting Act (HIPAA)? | Sì |
| L'app è conforme a Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | No |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 1)? | No |
| L'app è conforme ai controlli dell'organizzazione del servizio (SOC 2)? | Sì |
| Quale certificazione SOC 2 hai ottenuto? | type2 |
| Data di certificazione SOC2 più recente | 2021-11-30 |
| L'app è conforme ai controlli dell'organizzazione dei servizi (SOC 3)? | No |
| Si eseguono valutazioni PCI DSS annuali rispetto all'app e al relativo ambiente di supporto? | No |
| L'app International Organization for Standardization (ISO 27001) è certificata? | Sì |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27018)? | Sì |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27017)? | Sì |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27002)? | No |
| L'app Federal Risk and Authorization Management Program (FedRAMP) è conforme? | No |
| L'app è conforme al Family Educational Rights and Privacy Act (FERPA)? | No |
| L'app è conforme al Children's Online Privacy Protection Act (COPPA)? | No |
| L'app è conforme a Sarbanes-Oxley Act (SOX)? | No |
| L'app è conforme a NIST 800-171? | No |
| L'app è stata certificata da Cloud Security Alliance (CSA Star)? | Sì |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Si dispone di gdpr o altri requisiti o obblighi di privacy o protezione dei dati (ad esempio CCPA)? | Sì |
| L'app ha un'informativa sulla privacy esterna che descrive come raccoglie, usa, condivide e archivia i dati dei clienti? | Sì |
| URL dell'informativa sulla privacy | https://www.zoho.com/terms.html |
| L'app esegue un processo decisionale automatizzato, inclusa la profilatura che potrebbe avere un effetto legale o un impatto simile? | No |
| L'app elabora i dati dei clienti per uno scopo secondario non descritto nell'informativa sulla privacy (ad esempio marketing, analisi)? | No |
| Si elaborano categorie speciali di dati sensibili (ad esempio, origine razziale o etnica, opinione politica, credenze religiose o filosofiche, dati genetici o biometrici, dati sanitari) o categorie di dati soggetti a leggi sulle notifiche di violazione? | No |
| L'app raccoglie o elabora i dati di minori (ad esempio, persone di età inferiore ai 16 anni)? | No |
| L'app ha funzionalità per eliminare i dati personali di un individuo su richiesta? | Sì |
| L'app ha funzionalità per limitare o limitare il trattamento dei dati personali di un individuo su richiesta? | Sì |
| L'app offre agli utenti la possibilità di correggere o aggiornare i propri dati personali? | Sì |
| Vengono eseguite regolari verifiche della sicurezza dei dati e della privacy (ad esempio, valutazioni dell'impatto sulla protezione dei dati o valutazioni dei rischi per la privacy) per identificare i rischi correlati al trattamento dei dati personali per l'app? | Sì |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'applicazione si integra con Microsoft Identity Platform (Azure AD) per l'accesso Single Sign-On, l'accesso API e così via? | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco di controllo di integrazione Microsoft Identity Platform? | Sì |
| L'app usa la versione più recente di MSAL (Microsoft Authentication Library) o Microsoft Identity Web per l'autenticazione? | Sì |
| Se l'app non usa una delle librerie precedenti, quale libreria o libreria di autenticazione usa? |  |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Multi-Factor Authentication, Richiesta di dispositivi gestiti dall'organizzazione per applicazioni specifiche, Blocco di comportamenti di accesso rischiosi, Limitazione dell'accesso concesso a persone diverse dai ruoli amministrativi  |
| L'app supporta la valutazione dell'accesso continuo (CAE) | Sì |
| L'app archivia le credenziali nel codice? | No |
| Le app e i componenti aggiuntivi per Microsoft 365 potrebbero usare api Microsoft aggiuntive all'esterno di Microsoft Graph. L'app o il componente aggiuntivo usa altre API Microsoft? | No |

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

>|   **Autorizzazione Graph**  | **Tipo autorizzazione** |          **Giustificazione**          | **ID app Azure AD** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Contacts.Read | Delegato | Leggere i contatti utente | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| Files.Read | Delegato | Leggere i file utente | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| Files.Read.All | Delegato | Leggere tutti i file a cui l'utente può accedere | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| Files.Read.Selected | Delegato | Leggere i file selezionati dall'utente | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| User.Read | Delegato | Accedere e leggere il profilo utente | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| User.ReadBasic.All | Delegato | Leggere tutti i profili di base degli utenti | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| email | Delegato | Visualizzare l'indirizzo di posta elettronica degli utenti | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| offline_access | Delegato | Mantenimento dell'accesso ai dati a cui è stato concesso l'accesso | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| profile | Delegato | Visualizzare il profilo di base degli utenti | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

