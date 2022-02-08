---
title: Informazioni sull'applicazione per EasyLife 365 di EasyLife 365 AG
ms.author: elmalova
author: elenamalova
ms.date: 02/04/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tutte le informazioni di sicurezza e conformità disponibili per EasyLife 365, i criteri di gestione dei dati, le informazioni del catalogo app Microsoft Cloud App Security e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 489c314ca81a9701d1e8304ca5c278f20f270d97
ms.sourcegitcommit: dd610febc885b7c5766014e7364ed43c4bd942ac
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 02/08/2022
ms.locfileid: "62449449"
---
# <a name="easylife-365"></a>EasyLife 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 5, 2022</p>

* <a href="https://teams.microsoft.com/l/app/93731bac-4d43-480f-9e40-9fc567dfb817" target="_blank">Visualizzazione in Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003697" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da EasyLife 365 AG a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | EasyLife 365 |
| ID | WA200003697 |
| Office 365 client supportati | Microsoft Teams |
| Nome società partner | EasyLife 365 AG |
| Sito Web aziendale | [https://www.easylife365.cloud](https://www.easylife365.cloud) |
| Condizioni per l'uso dell'app | [https://www.easylife365.cloud/terms](https://www.easylife365.cloud/terms) |
| Funzionalità di base dell'app | Semplificare la governance. |
| Sede centrale dell'azienda | Svizzera |
| Pagina delle informazioni dell'app | |
| Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app? | IsvHosted |
| Quali provider di cloud di hosting usa l'app? |  |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite da EasyLife 365 AG sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'app o l'infrastruttura sottostante elabora i dati relativi a un cliente Microsoft o al dispositivo? | Sì |
| Quali dati vengono elaborati dalla tua app? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| L'app supporta TLS 1.1 o versione successiva? | Sì |
| L'app o l'infrastruttura sottostante archivia i dati dei clienti Microsoft? | Sì |
| Quali dati vengono archiviati nei database? | Metadati del gruppo (id, nome) e Informazioni utente (id, posta) nella registrazione per 90 giorni |
| Se l'infastruttura sottostante elabora o archivia i dati dei clienti Microsoft, dove sono archiviati geograficamente? | Paesi Bassi (la) |
| Si dispone di un processo di affiliazione e di eliminazione dei dati stabilito? | Sì |
| Per quanto tempo vengono conservati i dati dopo la chiusura dell'account? | Meno di 90 giorni |
| Si dispone di un processo di gestione dell'accesso ai dati stabilito? | Sì |
| Trasferire i dati dei clienti o i contenuti dei clienti a terze parti o sub-processori? | No |
| Sono stati stipulati contratti di condivisione dei dati con qualsiasi servizio di terze parti con cui si condividono i dati dei clienti Microsoft? |  |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalogo vengono visualizzate di seguito.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Esegui test di penetrazione annuali nell'app? | Sì |
| L'app dispone di un piano di ripristino di emergenza documentato, inclusa una strategia di backup e ripristino? | Sì |
| L'ambiente usa la protezione antimalware tradizionale o i controlli delle applicazioni? | TraditionalAntiMalware, ApplicationControls |
| Si dispone di un processo stabilito per l'identificazione e la classificazione dei rischi delle vulnerabilità di sicurezza? | Sì |
| Si dispone di un criterio che regola il contratto di servizio (SLA) per l'applicazione delle patch? | Sì |
| Si svolgono attività di gestione delle patch in base ai contratti di servizio dei criteri di applicazione delle patch? | Sì |
| L'ambiente include sistemi operativi o software non supportati? | No |
| Esegui l'analisi trimestrale delle vulnerabilità nella tua app e nell'infastruttura che la supporta? | No |
| Nel limite di rete esterno è installato un firewall? | No |
| Si dispone di un processo di gestione delle modifiche stabilito utilizzato per esaminare e approvare le richieste di modifica prima che siano distribuite nell'ambiente di produzione? | Sì |
| Un'altra persona sta esaminando e approvando tutte le richieste di modifica del codice inviate alla produzione dallo sviluppatore originale? | Sì |
| Le procedure di codifica protetta prendono in considerazione le classi di vulnerabilità comuni, ad esempio OWASP Top 10? | Sì |
| Autenticazione a più fattori abilitata per: | DNSManagement, Credential, CodeRepositories |
| Si dispone di un processo stabilito per il provisioning, la modifica e l'eliminazione degli account dei dipendenti? | Sì |
| Hai distribuito software di rilevamento e prevenzione delle intrusioni (IDPS) nel perimetro del limite di rete che supporta la tua app? | N/D |
| La registrazione eventi è impostata su tutti i componenti di sistema che supportano la tua app? | Sì |
| Tutti i log vengono esaminati a cadenza regolare da strumenti umani o automatizzati per rilevare potenziali eventi di sicurezza? | Sì|
| Quando viene rilevato un evento di sicurezza, gli avvisi vengono inviati automaticamente a un dipendente per il triage? | Sì |
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
| L'app è conforme al Family Educational Rights and Privacy Act (FERPA)? | No |
| L'app è conforme al Children's Online Privacy Protection Act (COPPA)? | No |
| L'app è conforme Sarbanes-Oxley Act (SOX)? | No |
| L'app è conforme al NIST 800-171? | No |
| L'app è stata certificata da Cloud Security Alliance (CSA Star) ? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Hai un GDPR o altri requisiti o obblighi di privacy o protezione dei dati (ad esempio CCPA)? | Sì |
| L'app ha un avviso sulla privacy rivolto all'esterno che descrive come raccoglie, usa, condivide e archivia i dati dei clienti? | Sì |
| URL dell'informativa sulla privacy | https://www.easylife365.cloud/web/privacy |
| L'app esegue processi decisionali automatizzati, inclusa la profilatura che potrebbe avere un effetto legale o un impatto simile? | No |
| L'app elabora i dati dei clienti per uno scopo secondario non descritto nell'informativa sulla privacy (ad esempio marketing, analisi)? | No |
| Si elaborano categorie speciali di dati sensibili (ad esempio origine razziale o etnica, opinioni politiche, convinzioni religiose o filosofiche, dati genetici o biometrici, dati sanitari) o categorie di dati soggetti alle leggi sulle notifiche di violazione? | No |
| L'app raccoglie o elabora dati da minori (ad esempio, persone di età inferiore ai 16 anni)? | No |
| L'app dispone di funzionalità per eliminare i dati personali di un individuo su richiesta? | No |
| L'app dispone di funzionalità per limitare o limitare l'elaborazione dei dati personali di un individuo su richiesta? | No |
| L'app offre agli utenti la possibilità di correggere o aggiornare i propri dati personali? | No |
| Vengono eseguite revisioni regolari sulla sicurezza e sulla privacy dei dati (ad esempio, valutazioni dell'impatto sulla protezione dei dati o valutazioni dei rischi per la privacy) per identificare i rischi correlati al trattamento dei dati personali per l'app? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| L'applicazione si integra con Microsoft Identity Platform (Azure AD) per single sign-on, accesso API e così via? | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione? | Sì |
| L'app usa la versione più recente di MSAL (Microsoft Authentication Library) o Microsoft Identity Web per l'autenticazione? | Sì |
| Se l'app non usa una delle librerie precedenti, quali librerie di autenticazione usa? |  |
| L'app supporta i criteri di accesso condizionale? | No |
| L'app supporta la valutazione dell'accesso continuo (CAE) | No |
| L'app archivia credenziali nel codice? | No |
| Le app e i componenti aggiuntivi per Microsoft 365 potrebbero usare API Microsoft aggiuntive al di fuori di Microsoft Graph. L'app o il componente aggiuntivo usa api Microsoft aggiuntive? | Sì |

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

>|   **Graph autorizzazioni**  | **Tipo autorizzazione** |          **Giustificazione**          | **Azure AD'ID app** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Group.Read.All | delegated | Consente di gestire Microsoft 365 gruppi nell'app | [192ba193-b68c-464c-a920-7eaa93b59a12](https://docs.microsoft.com/microsoft-365-app-certification/azure/192ba193-b68c-464c-a920-7eaa93b59a12) |
>| User.Read.All | delegated | Utilizzato per recuperare le informazioni utente nell'applicazione. Usato in Selezione utenti | [192ba193-b68c-464c-a920-7eaa93b59a12](https://docs.microsoft.com/microsoft-365-app-certification/azure/192ba193-b68c-464c-a920-7eaa93b59a12) |
>| ChannelMember.ReadWrite.All | application | Usato per leggere e modificare i membri del canale nell'app back-end | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](https://docs.microsoft.com/microsoft-365-app-certification/azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a) |
>| Directory.ReadWrite.All | entrambi | Usato per verificare se le autorizzazioni dell'app nel tenant per EasyLife 365. Usato per disabilitare/abilitare l'accesso Guest a Microsoft 365 gruppo nel back-end. | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](https://docs.microsoft.com/microsoft-365-app-certification/azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a) |
>| Group.ReadWrite.All | application | Usato per eseguire Microsoft 365 gruppi, verificare i proprietari di un gruppo, archiviare Teams, eliminare gruppi nel servizio back-end | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](https://docs.microsoft.com/microsoft-365-app-certification/azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a) |
>| Mail.Send | application | Consente di inviare le notifiche di posta elettronica agli utenti con qualsiasi cassetta postale nell'ambiente. Questo è configurato dagli amministratori per inviare messaggi di posta da una cassetta postale condivisa o da un utente. Gli amministratori in genere limitano le autorizzazioni di questa app all'ID app | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](https://docs.microsoft.com/microsoft-365-app-certification/azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a) |
>| MailboxSettings.Read | application | Utilizzato per leggere le impostazioni della lingua di una cassetta postale degli utenti prima di inviare notifiche in quella lingua specifica | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](https://docs.microsoft.com/microsoft-365-app-certification/azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a) |
>| Reports.Read.All | application | Usato per verificare l'utilizzo Microsoft 365 gruppi nel back-end | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](https://docs.microsoft.com/microsoft-365-app-certification/azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a) |
>| Sites.Read.All | application | Usato per enumerare i SharePoint online in un tenant | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](https://docs.microsoft.com/microsoft-365-app-certification/azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a) |
>| User.Read.All | application | Usato per cercare utenti e recuperare informazioni di base per inviare notifiche | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](https://docs.microsoft.com/microsoft-365-app-certification/azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a) |
>| User.ReadWrite.All | application | Utilizzato per invitare account guest, modificare i metadati dell'account guest ed eliminare gli account guest, se necessario nell'applicazione back-end | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](https://docs.microsoft.com/microsoft-365-app-certification/azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a) |
>| ChannelMember.ReadWrite.All | delegated | Utilizzato dagli utenti per modificare l'appartenenza al canale di un team | [716a0b19-6f38-4909-a80a-ffaac7957316](https://docs.microsoft.com/microsoft-365-app-certification/azure/716a0b19-6f38-4909-a80a-ffaac7957316) |
>| Group.ReadWrite.All | delegated | Usato da per modificare i metadati per Microsoft 365 gruppi e Teams. Usato per cercare gruppi nell'ambiente | [716a0b19-6f38-4909-a80a-ffaac7957316](https://docs.microsoft.com/microsoft-365-app-certification/azure/716a0b19-6f38-4909-a80a-ffaac7957316) |
>| TeamsActivity.Send | application | Usato per inviare Teams notifiche nel back-end | [716a0b19-6f38-4909-a80a-ffaac7957316](https://docs.microsoft.com/microsoft-365-app-certification/azure/716a0b19-6f38-4909-a80a-ffaac7957316) |
>| TeamsAppInstallation.ReadForUser.All | application | Verifica se l'utente ha installato l'app EasyLife prima di inviare notifiche tramite Teams. | [716a0b19-6f38-4909-a80a-ffaac7957316](https://docs.microsoft.com/microsoft-365-app-certification/azure/716a0b19-6f38-4909-a80a-ffaac7957316) |
>| User.Read.All | delegated | Utilizzato dalle selezione utenti per cercare gli utenti in un'organizzazione; Utilizzato per enumerare gli account guest | [716a0b19-6f38-4909-a80a-ffaac7957316](https://docs.microsoft.com/microsoft-365-app-certification/azure/716a0b19-6f38-4909-a80a-ffaac7957316) |
>| email | delegated | Utilizzato dall'autenticazione SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](https://docs.microsoft.com/microsoft-365-app-certification/azure/716a0b19-6f38-4909-a80a-ffaac7957316) |
>| offline_access | delegated | Utilizzato dall'autenticazione SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](https://docs.microsoft.com/microsoft-365-app-certification/azure/716a0b19-6f38-4909-a80a-ffaac7957316) |
>| openid | delegated | Utilizzato dall'autenticazione SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](https://docs.microsoft.com/microsoft-365-app-certification/azure/716a0b19-6f38-4909-a80a-ffaac7957316) |
>| profile | delegated | Utilizzato dall'autenticazione SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](https://docs.microsoft.com/microsoft-365-app-certification/azure/716a0b19-6f38-4909-a80a-ffaac7957316) |

>Questa applicazione non dispone di API aggiuntive.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

