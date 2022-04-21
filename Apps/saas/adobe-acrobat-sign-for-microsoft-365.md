---
title: Informazioni sull'applicazione per Adobe Acrobat Sign for Microsoft 365 di Adobe
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/20/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per Adobe Acrobat Sign for Microsoft 365, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 9b87349c5829954b6c2f421590406110d32d85fe
ms.sourcegitcommit: 9dbbec778006471c0193a7fd39e2f81e7d441275
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/21/2022
ms.locfileid: "65014316"
---
# <a name="adobe-acrobat-sign-for-microsoft-365"></a>Adobe Acrobat Sign for Microsoft 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Ultimo aggiornamento da parte dello sviluppatore: 11 aprile 2022</p>

* <a href="https://appsource.microsoft.com/product/web-apps/adobe.adobe_sign_msft_saas_offer" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da Adobe a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | Adobe Acrobat Sign for Microsoft 365 |
| ID | adobe.adobe_sign_msft_saas_offer |
| Nome della società partner | Adobe |
| Sito Web dell'azienda | [https://acrobat.adobe.com/us/en/sign.html](https://acrobat.adobe.com/us/en/sign.html) |
| Condizioni per l'utilizzo dell'app | [https://www.adobe.com/legal/licenses-terms.html](https://www.adobe.com/legal/licenses-terms.html) |
| Funzionalità di base dell'app | Mantieni veloci i flussi di lavoro di firma dei documenti quando aggiungi Adobe Sign a Office-Outlook-Team. Da questi prodotti è possibile inviare e firmare documenti per firme elettroniche e approvazioni legalmente vincolanti &#8212; tutti con la soluzione di firma elettronica preferita di Microsoft. |
| Sede centrale dell'azienda | Stati Uniti d'America |
| Pagina delle informazioni sull'app | [https://helpx.adobe.com/sign/using/microsoft-teams-integrat...](https://helpx.adobe.com/sign/using/microsoft-teams-integration-user-guide.html) |
| Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app? | Ibrido |
| Quali provider di servizi cloud di hosting usano l'app? | Aws, Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da Adobe sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app o l'infrastruttura sottostante elabora i dati relativi a un cliente Microsoft o al dispositivo? | Sì |
| Quali dati vengono elaborati dall'app? | Per aggiornare il token di accesso, quando quello corrente è scaduto. Ad esempio, quando l'utente è in una &quot;finestra invia per la firma&quot; e lo lascia inattivo per troppo tempo, è necessario aggiornare un nuovo token quando l'utente è attivo. |
| L'app supporta TLS 1.1 o versione successiva? | Sì |
| L'app o l'infrastruttura sottostante archivia i dati dei clienti Microsoft? | Sì |
| Quali dati vengono archiviati nei database? | Per aggiornare il token di accesso, quando quello corrente è scaduto. Ad esempio, quando l'utente è in una &quot;finestra invia per la firma&quot; e lo lascia inattivo per troppo tempo, è necessario aggiornare un nuovo token quando l'utente è attivo. |
| Se l'infrastruttura sottostante elabora o archivia i dati dei clienti Microsoft, dove vengono archiviati geograficamente questi dati? | Stati Uniti d'America |
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
| Si eseguono test di penetrazione annuali sull'app? | Sì |
| L'app dispone di un piano di ripristino di emergenza documentato, inclusa una strategia di backup e ripristino? | Sì |
| L'ambiente usa la protezione antimalware tradizionale o i controlli delle applicazioni? | ApplicationControls, TraditionalAntiMalware |
| Si dispone di un processo stabilito per l'individuazione e la classificazione dei rischi delle vulnerabilità di sicurezza? | Sì |
| Si dispone di un criterio che regola il contratto di servizio (SLA) per l'applicazione di patch? | Sì |
| Si eseguono attività di gestione delle patch in base ai contratti di servizio dei criteri di applicazione delle patch? | Sì |
| L'ambiente ha sistemi operativi o software non supportati? | No |
| Si esegue l'analisi trimestrale delle vulnerabilità nell'app e nell'infrastruttura che la supporta? | Sì |
| È installato un firewall sul limite di rete esterno? | Sì |
| Si dispone di un processo di gestione delle modifiche stabilito usato per esaminare e approvare le richieste di modifica prima che vengano distribuite nell'ambiente di produzione? | Sì |
| Una persona aggiuntiva sta esaminando e approvando tutte le richieste di modifica del codice inviate all'ambiente di produzione dallo sviluppatore originale? | Sì |
| Le procedure di codifica sicura tengono conto delle classi di vulnerabilità comuni, ad esempio OWASP Top 10? | Sì |
| Autenticazione a più fattori abilitata per: | CodeRepositories, Credential, DNSManagement |
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
| Data di certificazione SOC2 più recente | 2020-11-24 |
| L'app è conforme ai controlli dell'organizzazione dei servizi (SOC 3)? | No |
| Si eseguono valutazioni PCI DSS annuali rispetto all'app e al relativo ambiente di supporto? | Sì |
| L'app International Organization for Standardization (ISO 27001) è certificata? | Sì |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27018)? | No |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27017)? | No |
| L'app è conforme all'Organizzazione internazionale per la standardizzazione (ISO 27002)? | No |
| L'app Federal Risk and Authorization Management Program (FedRAMP) è conforme? | Sì |
| L'app è conforme al Family Educational Rights and Privacy Act (FERPA)? | Sì |
| L'app è conforme al Children's Online Privacy Protection Act (COPPA)? | Sì |
| L'app è conforme a Sarbanes-Oxley Act (SOX)? | N/D |
| L'app è conforme a NIST 800-171? | N/D |
| L'app è stata certificata da Cloud Security Alliance (CSA Star)? | Sì |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Si dispone di gdpr o altri requisiti o obblighi di privacy o protezione dei dati (ad esempio CCPA)? | Sì |
| L'app ha un'informativa sulla privacy esterna che descrive come raccoglie, usa, condivide e archivia i dati dei clienti? | Sì |
| URL dell'informativa sulla privacy | https://helpx.adobe.com/sign/help/adobesign_gdpr_compliance.html |
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
| L'app usa la versione più recente di MSAL (Microsoft Authentication Library) o Microsoft Identity Web per l'autenticazione? | No |
| Se l'app non usa una delle librerie precedenti, quale libreria o libreria di autenticazione usa? | adal (con piano per passare a MSAL) |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app supporta la valutazione dell'accesso continuo (CAE) | No |
| L'app archivia le credenziali nel codice? | No |
| Le app e i componenti aggiuntivi per Microsoft 365 potrebbero usare api Microsoft aggiuntive all'esterno di Microsoft Graph. L'app o il componente aggiuntivo usa altre API Microsoft? | Sì |

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

>|   **Autorizzazione Graph**  | **Tipo autorizzazione** |          **Giustificazione**          | **ID app Azure AD** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Mail.ReadWrite | Delegato | Per popolare il documento allegato, i messaggi di posta elettronica del mittente e del destinatario e il contenuto del messaggio dai messaggi di posta elettronica ad Adobe sign to send for signature.To populate the attached document, sender and receiver emails, and message content from emails to Adobe sign to send for signature. Ciò consente di risparmiare tempo all'utente per digitare nuovamente i campi in Adobe Sign. Dopo la firma di un contratto, viene creato automaticamente un nuovo messaggio di posta elettronica per consentire all'utente di inviare un messaggio di posta elettronica per informare i destinatari che la transazione è stata eseguita. Adobe Sign salverà gli allegati come file temporanei, che ha una scadenza di 24 ore. | [ea36b867-ca67-45fd-a61b-d2be86273167](../azure/ea36b867-ca67-45fd-a61b-d2be86273167.md) |
>| People.Read | Delegato | Per compilare automaticamente l'indirizzo di posta elettronica nell'esperienza Invia per la &quot;firma&quot; , digitando alcune lettere iniziali, non è necessario che gli utenti digitino tutti i messaggi di posta elettronica. Adobe Sign archivierà solo i destinatari e-mail e displayName nei contratti. | [ea36b867-ca67-45fd-a61b-d2be86273167](../azure/ea36b867-ca67-45fd-a61b-d2be86273167.md) |
>| User.Read | Delegato | Per leggere il profilo dell'utente e associare il profilo (in pratica, la posta elettronica e userId) al database in modo che possano usare Adobe Sign. Per leggere il profilo dell'utente e associare il profilo (in pratica, la posta elettronica e userId) al database in modo che possano usare Adobe Sign. | [ea36b867-ca67-45fd-a61b-d2be86273167](../azure/ea36b867-ca67-45fd-a61b-d2be86273167.md) |
>| offline_access | Delegato | Per aggiornare il token di accesso, quando quello corrente è scaduto. Ad esempio, quando l'utente è in una &quot;finestra invia per la firma&quot; e lo lascia inattivo per troppo tempo, è necessario aggiornare un nuovo token quando l'utente è attivo. Per aggiornare il token di accesso, quando quello corrente è scaduto. Ad esempio, quando l'utente è in una &quot;finestra invia per la firma&quot; e lo lascia inattivo per troppo tempo, è necessario aggiornare un nuovo token quando l'utente è attivo. | [ea36b867-ca67-45fd-a61b-d2be86273167](../azure/ea36b867-ca67-45fd-a61b-d2be86273167.md) |
>| openid | Delegato | Email e UserId. Per accedere all'utente per assicurarsi il consenso per l'autorizzazione all'uso dell'app Adobe Sign. La posta elettronica è l'identificatore univoco per gli utenti in Adobe Sign. Archiviamo l'ID e-mail in modo da poter eseguire il mapping di tutte le attività di tale utente al suo record Adobe Sign. | [ea36b867-ca67-45fd-a61b-d2be86273167](../azure/ea36b867-ca67-45fd-a61b-d2be86273167.md) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

