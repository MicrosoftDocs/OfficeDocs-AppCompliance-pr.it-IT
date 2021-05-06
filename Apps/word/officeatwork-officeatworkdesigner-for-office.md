---
title: Application Information for officeatwork | Designer per Office da ufficio
ms.author: elmalova
author: elenamalova
ms.date: 12/08/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Tutte le informazioni sulla sicurezza e la conformità disponibili per i servizi | Designer per Office, i criteri di gestione dei dati, le Microsoft Cloud App Security del catalogo app e le informazioni sulla sicurezza/conformità nel Registro di sistema CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 2ae2bec5482709812203a101eac2781d15424daa
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251555"
---
# <a name="officeatwork--designer-for-office"></a>officeatwork | Progettazione per Office

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Last updated by the developer on: December 8, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380518" target="_blank">Visualizzazione in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informazioni generali

Informazioni fornite da officeatwork a Microsoft:

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Nome app | officeatwork - Designer per Office |
| ID | WA104380518 |
| Office 365 client supportati | Word 2016 o versioni successive su Mac, Word sul web, Word 2016 o versioni successive su Windows, Word su iPad |
| Nome società partner | officeatwork |
| URL del sito Web del partner | [https://links.officeatwork.com/officeatwork-home](https://links.officeatwork.com/officeatwork-home) |
| URL dell'informativa sulla privacy | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| URL delle Condizioni per l'utilizzo | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Modalità di gestione dei dati da parte dell'app

Queste informazioni sono state fornite dall'ufficio sul modo in cui questa app raccoglie e archivia i dati dell'organizzazione e il controllo che l'organizzazione avrà sui dati raccolti dall'app.

#### <a name="data-access-using-microsoft-graph"></a>Accesso ai dati tramite Microsoft Graph

Elenca tutte [le autorizzazioni Graph Microsoft richieste](https://docs.microsoft.com/graph/permissions-reference) da questa app.

>| **Autorizzazione**  | **Tipo di autorizzazione (Delegata/Applicazione)** | **I dati vengono raccolti? Giustificazione per la raccolta?** | **I dati vengono archiviati? Giustificazione per l'archiviazione?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Contacts.Read | delegated | Non vengono archiviati dati. | Contatti: per abilitare la lettura di tutti i contatti dell'utente connesso. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| Files.Read | delegated | Non vengono archiviati dati. | OneDrive - File (contenuto): per consentire la lettura dei file dell'utente connesso. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| Files.Read.All | delegated | Non vengono archiviati dati. | Teams - File (contenuto): per consentire la lettura di tutti i file dell'utente connesso. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| Group.Read.All | delegated | Non vengono archiviati dati. | Office 365 Utenti - Limita al gruppo: per abilitare la lettura di tutti i gruppi dell'utente connesso. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| Sites.Read.All | delegated | Non vengono archiviati dati. | SharePoint Online: per abilitare la lettura dei dati da SharePoint Online. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| User.Read | delegated | Non vengono archiviati dati. | Sing-In: per consentire all'app officeatwork di leggere le proprietà di base dell'utente. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| User.Read.All | delegated | Non vengono archiviati dati. | Office 365 Utenti - Tutte le proprietà: per consentire la lettura di tutte le proprietà di tutti gli utenti. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| User.ReadBasic.All | delegated | Non vengono archiviati dati. | Office 365 Utenti - Proprietà di base: per consentire la lettura delle proprietà di base di tutti gli utenti | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| offline_access | delegated | Non vengono archiviati dati. | Sing-In: per abilitare l'accesso automatico tramite i token di aggiornamento, come senza, gli utenti dovrebbero eseguire manualmente l'accesso ogni volta che avviano l'app officeatwork. Questo ambito è obbligatorio solo per le applicazioni host non abilitate per SSO. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| openid | delegated | Non vengono archiviati dati. | Sing-In: per consentire agli utenti di accedere all'app officeatwork con l'organizzazione e/o l'account Microsoft | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| profilo | delegated | Non vengono archiviati dati. | Sing-In: per mostrare l'utente connesso nell'app officeatwork. Ciò consente di assicurare/confermare all'utente quale account è stato usato per accedere all'app officeatwork. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |

#### <a name="data-access-using-other-microsoft-apis"></a>Accesso ai dati con altre API Microsoft

Le app e i componenti aggiuntivi Microsoft 365 possono usare API Microsoft aggiuntive diverse da Microsoft Graph per raccogliere o elaborare informazioni identificabili dall'organizzazione. Elenca tutte le API Microsoft diverse da Microsoft Graph questa app usa.

>| **API** |  **L'OII viene raccolto?** |  **Che cos'è OII raccolto?** | **Giustificazione per la raccolta OII?** | **L'OII è archiviato?** | **Giustificazione per l'archiviazione OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API REST di SharePoint | No |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Non servizi Microsoft usato

Se l'app trasferisce o condivide i dati dell'organizzazione con servizi non Microsoft, elenca il servizio non Microsoft utilizzato dall'app, i dati trasferiti e include una giustificazione del motivo per cui l'app deve trasferire queste informazioni.

>Non vengono servizi Microsoft non vengono utilizzati.



#### <a name="add-in-data-access"></a>Accesso ai dati del componente aggiuntivo

Elenca le autorizzazioni richieste da questa app per accedere ai dati dell'organizzazione, la giustificazione e lo scopo di questa autorizzazione (per cosa l'app usa queste informazioni?) e se l'app archivia queste informazioni nei relativi database.

>| **Autorizzazione**  | **Descrizione** |
>|:----------------|:----------------|
>| ReadWrite Document | Può leggere e apportare modifiche al documento |
>| Invia dati | Può inviare dati tramite Internet |

#### <a name="telemetry-data"></a>Dati di telemetria

Le informazioni di identificazione dell'organizzazione (OII) o dell'utente finale (EUII) vengono visualizzate nei registri o nei dati di telemetria dell'applicazione? In caso affermativa, descrivere quali dati sono archiviati e quali sono i criteri di conservazione e rimozione?

>Sì, gli eventi includono oid e tenantId e vengono inviati ad Azure AppInsights. Gli eventi vengono eliminati automaticamente dopo 90 giorni. Se un cliente desidera eliminare questi dati, può usare il collegamento fornito nell'informativa sulla privacy per avviare l'eliminazione di tali dati.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controlli dell'organizzazione per i dati archiviati dal partner

Descrivere in che modo gli amministratori dell'organizzazione possono controllare le informazioni nei sistemi partner? ad esempio eliminazione, conservazione, controllo, archiviazione, criteri per gli utenti finali e così via.

>I dati delle impostazioni delle applicazioni (flag di funzionalità, nome visualizzato dell'organizzazione, tenantId, elenco di oid degli amministratori) vengono archiviati in un'istanza del database di Azure Cosmos (un file per tenant). I file DB sono crittografati e l'accesso è limitato ai tecnici e al personale di supporto tecnico selezionati. Il cliente può accedere e modificare i dati delle impostazioni dell'app officeatwork usando l'app Web dell'interfaccia di amministrazione.

#### <a name="human-review-of-organizational-information"></a>Revisione umana delle informazioni organizzative

Gli utenti sono coinvolti nella revisione o nell'analisi di dati OII (Organizational Identifiable Information) raccolti o archiviati da questa app?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Le informazioni del [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) vengono visualizzate di seguito.

<iframe height='1020' title='Microsoft Cloud App Security Informazioni' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35749' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35749" target="_blank">Visualizzazione in una nuova scheda</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informazioni sull'identità

Queste informazioni sono state fornite dall'ufficio sul modo in cui questa app gestisce l'autenticazione, l'autorizzazione, le procedure consigliate per la registrazione delle applicazioni e altri criteri di identità.

| **Informazioni** | **Risposta** |
|:----------------|:-------------|
| Eseguire l'integrazione con Microsoft Identify Platform (Azure AD)?  | Sì |
| Sono state esaminate e rispettate tutte le procedure consigliate applicabili descritte nell'elenco Microsoft Identity Platform di integrazione?  | Sì |
| L'app usa MSAL (Microsoft Authentication Library) per l'autenticazione? | No |
| L'app supporta i criteri di accesso condizionale? | Sì |
| Elencare i tipi di criteri supportati | Impostazioni predefinite per la sicurezza |
| L'app richiede autorizzazioni con privilegi minimi per lo scenario? | Sì |
| Le autorizzazioni registrate in modo statico dell'app riflettono in modo accurato le autorizzazioni richieste dall'app in modo dinamico e incrementale? | No |
| L'app supporta la multi-tenancy? | Sì |
| L'app dispone di un client riservato? | Sì |
| Sei il proprietario di tutti gli URI (Unified Resource Identifier) di reindirizzamento registrati per la tua app? | Sì |
| Per la tua app, cosa evita di usare? | - URI di reindirizzamento con caratteri jolly,<br/>- OAuth2 Implicit Flow, a meno che non sia necessario per una spa<br/>- Flusso roPC (Resource Owner Password Credential) |
| L'app espone qualsiasi API Web? | No |
| La tua app usa le API di anteprima? | No |
| L'app usa API deprecate? | No |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
