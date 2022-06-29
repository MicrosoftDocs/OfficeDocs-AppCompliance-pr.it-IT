---
title: Informazioni sull'applicazione per EasyLife 365 di EasyLife 365 AG
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 06/27/2022
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni di sicurezza e conformità disponibili per EasyLife 365, i criteri di gestione dei dati, le informazioni sul catalogo delle app Microsoft Cloud App Security e le informazioni di sicurezza/conformità nel registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust-certification
ms.openlocfilehash: a50f566f963504e4c87d5b7a261373446afe6432
ms.sourcegitcommit: c06f3d478e1b4f66c02e2855ffac6de2f350208a
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 06/29/2022
ms.locfileid: "66249329"
---
# <a name="easylife-365"></a>EasyLife 365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Ultimo aggiornamento da parte dello sviluppatore: 23 marzo 2022</p>

* <a href="https://teams.microsoft.com/l/app/93731bac-4d43-480f-9e40-9fc567dfb817" target="_blank">Visualizzazione in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003697" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da EasyLife 365 AG a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome dell'app | EasyLife 365 |
| ID | WA200003697 |
| client Office 365 supportati | Microsoft Teams |
| Nome della società partner | EasyLife 365 AG |
| Sito Web dell'azienda | [https://www.easylife365.cloud](https://www.easylife365.cloud) |
| Condizioni per l'utilizzo dell'app | [https://www.easylife365.cloud/terms](https://www.easylife365.cloud/terms) |
| Funzionalità di base dell'app | Semplificare la governance. |
| Sede centrale dell'azienda | Svizzera |
| Pagina delle informazioni sull'app | [https://www.easylife365.cloud/governance/features](https://www.easylife365.cloud/governance/features) |
| Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app? | Paas |
| Quali provider di servizi cloud di hosting usano l'app? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da EasyLife 365 AG su come questa app raccoglie e archivia i dati dell'organizzazione e sul controllo che l'organizzazione avrà sui dati raccolti dall'app.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app o l'infrastruttura sottostante elabora i dati relativi a un cliente Microsoft o al dispositivo? | Sì |
| Quali dati vengono elaborati dall'app? | Metadati del gruppo (id, nome, numero di proprietari, informazioni sulla scadenza); Informazioni utente (id, userprincipalname, mail, preferredlanguage, userType) |
| L'app supporta TLS 1.1 o versione successiva? | Sì |
| L'app o l'infrastruttura sottostante archivia i dati dei clienti Microsoft? | Sì |
| Quali dati vengono archiviati nei database? | Metadati del gruppo (ID, nome) e Informazioni utente (ID, posta) nella registrazione per 90 giorni |
| Se l'infrastruttura sottostante elabora o archivia i dati dei clienti Microsoft, dove vengono archiviati geograficamente questi dati? | Paesi Bassi (i) |
| Si dispone di un processo di noleggio e smaltimento dei dati stabilito? | Sì |
| Per quanto tempo vengono conservati i dati dopo la chiusura dell'account? | Meno di 90 giorni |
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
| L'ambiente usa la protezione antimalware tradizionale o i controlli delle applicazioni? | TraditionalAntiMalware, ApplicationControls |
| Si dispone di un processo stabilito per l'individuazione e la classificazione dei rischi delle vulnerabilità di sicurezza? | Sì |
| Si dispone di un criterio che regola il contratto di servizio (SLA) per l'applicazione di patch? | Sì |
| Si eseguono attività di gestione delle patch in base ai contratti di servizio dei criteri di applicazione delle patch? | Sì |
| L'ambiente ha sistemi operativi o software non supportati? | No |
| Si esegue l'analisi trimestrale delle vulnerabilità nell'app e nell'infrastruttura che la supporta? | No |
| È installato un firewall sul limite di rete esterno? | No |
| Si dispone di un processo di gestione delle modifiche stabilito usato per esaminare e approvare le richieste di modifica prima che vengano distribuite nell'ambiente di produzione? | Sì |
| Una persona aggiuntiva sta esaminando e approvando tutte le richieste di modifica del codice inviate all'ambiente di produzione dallo sviluppatore originale? | Sì |
| Le procedure di codifica sicura tengono conto delle classi di vulnerabilità comuni, ad esempio OWASP Top 10? | Sì |
| Autenticazione a più fattori abilitata per: | DNSManagement, Credential, CodeRepositories |
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
| URL dell'informativa sulla privacy | https://www.easylife365.cloud/web/privacy |
| L'app esegue un processo decisionale automatizzato, inclusa la profilatura che potrebbe avere un effetto legale o un impatto simile? | No |
| L'app elabora i dati dei clienti per uno scopo secondario non descritto nell'informativa sulla privacy (ad esempio marketing, analisi)? | No |
| Si elaborano categorie speciali di dati sensibili (ad esempio, origine razziale o etnica, opinione politica, credenze religiose o filosofiche, dati genetici o biometrici, dati sanitari) o categorie di dati soggetti a leggi sulle notifiche di violazione? | No |
| L'app raccoglie o elabora i dati di minori (ad esempio, persone di età inferiore ai 16 anni)? | No |
| L'app ha funzionalità per eliminare i dati personali di un individuo su richiesta? | No |
| L'app ha funzionalità per limitare o limitare il trattamento dei dati personali di un individuo su richiesta? | No |
| L'app offre agli utenti la possibilità di correggere o aggiornare i propri dati personali? | No |
| Vengono eseguite regolari verifiche della sicurezza dei dati e della privacy (ad esempio, valutazioni dell'impatto sulla protezione dei dati o valutazioni dei rischi per la privacy) per identificare i rischi correlati al trattamento dei dati personali per l'app? | No |

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
| Le app e i componenti aggiuntivi per Microsoft 365 potrebbero usare altre API Microsoft all'esterno di Microsoft Graph. L'app o il componente aggiuntivo usa altre API Microsoft? | Sì |

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

>|   **Autorizzazione Graph**  | **Tipo autorizzazione** |          **Giustificazione**          | **Azure AD App ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Group.Read.All | Delegato | Consente di leggere Gruppi o Teams | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| Group.ReadWrite.All | Delegato | Consente di gestire i metadati di gruppi o teams | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| GroupMember.Read.All | Delegato | Legge i membri di un gruppo | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| User.Read.All | Delegato | Consente di recuperare i metadati dell'account guest | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| User.ReadBasic.All | Delegato | Consente di cercare membri o account guest in un'organizzazione | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| Channel.Create | Applicazione | Crea canali per un team | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Channel.ReadBasic.All | Applicazione | Legge i canali di un team esistente | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Directory.Read.All | Applicazione | Ottenere i modelli correnti di impostazione dell'account di gruppo e guest | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Directory.ReadWrite.All | Applicazione | Applicare le impostazioni dell'account guest per il gruppo o il team | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Create | Applicazione | Crea un gruppo | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Read.All | entrambi | Legge le informazioni sul gruppo e recupera gli alias del gruppo | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.ReadWrite.All | Applicazione | Modifica i metadati del gruppo nel back-end | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| GroupMember.Read.All | Applicazione | Recupera le appartenenze a gruppi o team nel back-end | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| GroupMember.ReadWrite.All | Applicazione | Consente di aggiungere o rimuovere membri da un gruppo o un team | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| IdentityRiskyUser.ReadWrite.All | Applicazione | Consente di modificare gli account guest e i relativi metadati | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Mail.Send | Applicazione | Invia messaggi di posta elettronica tramite una cassetta postale condivisa | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| MailboxSettings.Read | Applicazione | Recupera le impostazioni della lingua preferita di un utente | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Reports.Read.All | Applicazione | Recupera i dati di utilizzo di Gruppi e Teams | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Team.ReadBasic.All | Applicazione | Recuperare informazioni di base sul team | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamSettings.ReadWrite.All | Applicazione | Consente di archiviare e annullare l'archiviazione di un team | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Teams.Create | Applicazione | Crea un team | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamsTab.Read.All | Applicazione | Recupera le schede da un team creato | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamsTab.ReadWrite.All | Applicazione | Consente di creare o manipualte schede di un team creato | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Invite.All | Applicazione | Invita un utente al tenant | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Read | Delegato | Ottiene informazioni utente e informazioni sull'organizzazione | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Read.All | entrambi | Recupera informazioni su guest e utente | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Read.All | Delegato | Leggere tutti i gruppi dell'utente | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| Group.ReadWrite.All | Delegato | Modificare i metadati del gruppo dell'utente e modificare gruppi e team | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| GroupMember.Read.All | Delegato | Consente a un proprietario del gruppo di leggere l'appartenenza a un gruppo o a un team | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| GroupMember.ReadWrite.All | Delegato | Consente al proprietario del gruppo di modificare l'appartenenza a un gruppo o a un team | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamSettings.ReadWrite.All | Delegato | Consente di archiviare o annullare l'archiviazione di un team | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamsActivity.Send | Applicazione | Usato per inviare notifiche di Teams nel back-end | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamsAppInstallation.ReadForUser.All | Applicazione | Verificare se l'app EasyLife è installata per l'utente prima di inviare notifiche tramite Teams. | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.Read | Delegato | Legge i dati dell'organizzazione e le informazioni sull'utente | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.Read.All | Delegato | Consente di cercare altri membri o account guest in una directory | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.ReadBasic.All | Delegato | Mostra le foto dell'utente | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| email | Delegato | Usato dall'autenticazione SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| offline_access | Delegato | Usato dall'autenticazione SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| openid | Delegato | Usato dall'autenticazione SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| profile | Delegato | Usato dall'autenticazione SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="certification"

### <a name="certification-information"></a>Informazioni sulla certificazione

| **Controllo** | **Risultato della certificazione Microsoft 365** |
|:------------|:---------------------------------------|
| [**SICUREZZA DELL'APPLICAZIONE**](../docs/certification-submission-guide.md#application-security) | **PASSARE** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Test di penetrazione | Nell'ambito |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Verifica della valutazione della vulnerabilità (DAST/SAST/Penetration Test) | Nell'ambito |
| [**SICUREZZA OPERATIVA**](../docs/certification-submission-guide.md#operational-security) | **PASSARE** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Protezione da malware - Antivirus | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Protezione da malware - Controllo delle applicazioni | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gestione delle patch - Classificazione dei rischi | Nell'ambito |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gestione delle patch - Applicazione di patch | Nell'ambito |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Analisi delle vulnerabilità | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Firewall - Firewall (o tecnologie equivalenti) | Nell'ambito |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Firewall - Web Application Firewall (WAF) (facoltativo) | Nell'ambito |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Controllo delle modifiche | Nell'ambito |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Sviluppo/distribuzione di software sicuro | Nell'ambito |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gestione account | Nell'ambito |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Rilevamento e prevenzione delle intrusioni (facoltativo) | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Registrazione eventi di sicurezza | Nell'ambito |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Revisione (registrazione dei dati) | Nell'ambito |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Avviso eventi di sicurezza | Nell'ambito |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gestione dei rischi per la sicurezza delle informazioni | Nell'ambito |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Risposta agli eventi imprevisti | Nell'ambito |
| [**PRIVACY DI SICUREZZA PER LA GESTIONE &amp; DEI DATI**](../docs/certification-submission-guide.md#data-handling-security-and-privacy) | **PASSARE** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dati in transito | Nell'ambito |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dati inattivi | Nell'ambito |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Conservazione e eliminazione dei dati | Nell'ambito |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gestione accesso ai dati | Nell'ambito |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;GDPR | Nell'ambito |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
