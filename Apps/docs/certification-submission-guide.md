---
ms.author: oromalle
title: Guida all'invio della certificazione Microsoft 365
author: orionomalley
manager: tonybal
description: La certificazione Microsoft 365 garantisce alle organizzazioni aziendali la sicurezza e la protezione dei dati e della privacy.
keywords: Team di certificazione delle app Conformità alla sicurezza di Microsoft 365 m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: a3bb30be81163b3de45b5a93b6b9b426858b0f97
ms.sourcegitcommit: cede428f2a23bd3060f5506f270b40b327b02769
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 06/29/2022
ms.locfileid: "66545175"
---
# <a name="microsoft-365-certification-submission-guide"></a>Guida all'invio della certificazione Microsoft 365

**Contenuto dell'articolo:**
- [Introduzione](#introduction)
- [Prerequisiti](#prerequisites) 
- [Specifica della certificazione Microsoft 365 Aggiornamenti](#microsoft-365-certification-specification-updates)
- [Ambito di certificazione](#certification-scope)
- [Processo di certificazione](#certification-process)
- [Invio iniziale del documento](#initial-document-submission) 
- [Attività di raccolta e valutazione delle prove](#evidence-collection-and-assessment-activities)
- [Criteri di certificazione](#app-certification-criteria)
- [Sicurezza delle applicazioni](#application-security)
- [Sicurezza operativa](#operational-security) 
- [Sicurezza e privacy per la gestione dei dati](#data-handling-security-and-privacy)
- [Revisione facoltativa dei framework di conformità esterni](#optional-external-compliance-frameworks-review)
- [Appendice A](#appendix-a)
- [Appendice B](#appendix-b) 
- [Appendice C](#appendix-c) 
- [Appendice D](#appendix-d) 
- [Appendice E](#appendix-e) 
- [Appendice F](#appendix-f) 
- [Appendice G ](#appendix-g)
- [Altre informazioni](#learn-more) 
- [Glossario](#glossary) 


## <a name="introduction"></a>Introduzione

Parte del programma Microsoft 365 App Compliance, la certificazione Microsoft 365 garantisce e garantisce alle organizzazioni aziendali che i dati e la privacy sono adeguatamente protetti e protetti quando si integrano app/componenti aggiuntivi per sviluppatori di terze parti nella piattaforma Microsoft 365. Le applicazioni e i componenti aggiuntivi che superano la convalida saranno designati **Microsoft 365 Certified** in tutto l'ecosistema di Microsoft 365. 

Partecipando al programma di certificazione Microsoft 365, l'utente accetta queste condizioni supplementari e si conforma a qualsiasi documentazione associata che si applica alla partecipazione al programma di certificazione Microsoft 365 con Microsoft Corporation ("Microsoft", "noi", "microsoft" o "nostro"). L'utente dichiara e garantisce di avere l'autorità di accettare le condizioni supplementari per la certificazione Microsoft 365 per conto proprio, di una società e/o di un'altra entità, a seconda dei casi. Possiamo modificare, modificare o terminare questi termini supplementari in qualsiasi momento. La partecipazione continua al programma di certificazione Microsoft 365 dopo qualsiasi modifica o modifica significa che accetti le nuove condizioni supplementari. Se non si accettano le nuove condizioni supplementari o se terminiamo queste condizioni supplementari, è necessario interrompere la partecipazione al programma di certificazione Microsoft 365.

Questo documento è destinato agli ISV (fornitori di software indipendenti) per fornire informazioni sul processo di certificazione di Microsoft 365, sui prerequisiti per avviare il processo e sui dettagli dei controlli di sicurezza specifici che devono essere presenti.  Informazioni generali sul programma Microsoft 365 App Compliance sono disponibili nella [pagina](../overview.md) Del programma Conformità app di Microsoft 365. 

> [!IMPORTANT]
> Attualmente, la certificazione Microsoft 365 è applicabile a tutti:
>* Applicazioni di Microsoft Teams (schede, bot e così via).
>* App/componenti aggiuntivi di SharePoint
>* Componenti aggiuntivi di Office (Word, Excel, PowerPoint, Outlook, Project, OneNote)
>* Webapps

## <a name="prerequisites"></a>Prerequisiti

### <a name="publisher-attestation"></a>Attestazione dell'autore

Prima di ricevere il processo di certificazione Microsoft 365, è necessario aver completato l'attestazione dell'editore. Tuttavia, è possibile avviare il processo di certificazione di Microsoft 365 prima di completare l'attestazione del server di pubblicazione.  

### <a name="read-the-microsoft-365-certification-specification"></a>Leggere la specifica di certificazione Microsoft 365

Microsoft consiglia a tutti gli ISV (fornitore di software indipendente) di leggere la specifica di certificazione microsoft 365 nella sua interezza per garantire che tutti i controlli applicabili siano soddisfatti dall'ambiente nell'ambito e dall'app/componente aggiuntivo. In questo modo sarà possibile garantire un processo di valutazione senza problemi.

## <a name="microsoft-365-certification-specification-updates"></a>Specifica della certificazione Microsoft 365 Aggiornamenti 

Aggiornamenti alla specifica di certificazione Microsoft 365 sono previsti circa ogni sei-dodici mesi. Questi aggiornamenti potrebbero introdurre nuovi domini di sicurezza di destinazione e/o controlli di sicurezza. Aggiornamenti si baserà sul feedback degli sviluppatori, sulle modifiche al panorama delle minacce e sull'aumento della baseline di sicurezza del programma man mano che matura. 

Gli ISV che hanno già avviato la valutazione della certificazione Microsoft 365 possono continuare la valutazione con la versione della specifica di certificazione di Microsoft 365 valida all'avvio della valutazione. Tutti i nuovi invii, inclusa la ricertificazione annuale, dovranno essere valutati in base alla versione pubblicata.

> [!NOTE]
> Non è necessario rispettare tutti i controlli all'interno di questa specifica di certificazione di Microsoft 365 per ottenere una certificazione. Tuttavia, per ognuno dei domini di sicurezza descritti in questa specifica di certificazione di Microsoft 365 vengono applicate soglie che non verranno divulgate. Alcuni controlli verranno classificato come "**Hard Fail**", il che significa che la mancanza di questi controlli di sicurezza comporterà una valutazione non riuscita. 

## <a name="certification-scope"></a>Ambito di certificazione

**L'ambiente nell'ambito** è l'ambiente che supporta il recapito del codice app/componente aggiuntivo e supporta tutti i sistemi back-end con cui l'app/componente aggiuntivo potrebbe comunicare. Eventuali altri ambienti connessi a verranno inclusi anche nell'ambito, a meno che non sia presente una segmentazione adeguata E gli ambienti connessi a non possono influire sulla sicurezza dell'ambiente nell'ambito. Tutti gli ambienti di ripristino di emergenza dovranno anche essere inclusi nell'ambito della valutazione, in quanto questi ambienti sarebbero necessari per soddisfare il servizio nel caso in cui si verificasse qualcosa nell'ambiente primario.  Il termine componenti   **di sistema nell'ambito** fa riferimento a **TUTTI i** dispositivi e i sistemi usati nell'ambiente nell'ambito. I componenti nell'ambito includono, ma non sono limitati a:
* Applicazioni Web.
* Server.
* Firewall (o equivalenti).
* Interruttori.
* Servizi di bilanciamento del carico.
* Infrastruttura virtuale.
* Portali di gestione Web del provider di servizi cloud 

> [!IMPORTANT]
> L'ambiente nell'ambito deve avere una rete perimetrale e l'ambiente di supporto dell'app/componente aggiuntivo deve essere segmentato dai sistemi aziendali interni e dagli ambienti aziendali, limitando così l'ambito delle attività di valutazione solo ai sistemi nell'ambito. Gli analisti di certificazione convalideranno le tecniche di segmentazione durante la valutazione insieme alla revisione dei report sui test di penetrazione che avrebbero dovuto includere test per convalidare l'efficacia di qualsiasi tecnica di segmentazione in uso.

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a>Infrastruttura distribuita come servizio (IaaS), Piattaforma distribuita come servizio (PaaS) e Software as a Service (SaaS) 
Quando si usa IaaS e/o PaaS per supportare l'infrastruttura dell'applicazione o il recapito del codice del componente aggiuntivo in esame, il provider della piattaforma cloud sarà responsabile di alcuni dei controlli di sicurezza valutati durante il processo di certificazione. Di conseguenza, gli analisti di certificazione dovranno essere forniti con la verifica esterna indipendente delle procedure consigliate per la sicurezza da parte del provider della piattaforma cloud tramite report di conformità esterni, ad esempio report [PCI DSS] Attestazione di conformità (AOC), ISO27001 o [SOC 2] Report di tipo II. 

L'appendice F fornisce informazioni dettagliate sui controlli di sicurezza che probabilmente saranno applicabili in base ai tipi di distribuzione seguenti e in base al fatto che l'app/componente aggiuntivo esfiltra o meno i dati M365: 
* ISV ospitato 
* IaaS ospitato 
* PaaS/Serverless ospitato 
* Ibrido ospitato 
* Shared Hosted 

Dove viene distribuito IaaS o PaaS, sarà necessario fornire la prova dell'ambiente ospitato all'interno di questi tipi di distribuzione.

### <a name="sampling"></a>Campionamento

Le richieste di prove a supporto della valutazione della certificazione devono essere basate su un campione dei componenti del sistema nell'ambito in considerazione dei diversi sistemi operativi, della funzione primaria del dispositivo e dei diversi tipi di dispositivo. All'inizio del processo di certificazione verrà selezionato un campione appropriato. La tabella seguente deve essere usata come guida sulle dimensioni del campione:

|Dimensioni popolazione              | Esempio                  |
|---------------------------- |-------------------------|
|<5|1|
|>5 & <10|2|
|>9 & <25|3|
|>24|4 |

> [!NOTE]
>Se vengono identificate discrepanze tra i dispositivi inclusi nel campione iniziale, le dimensioni del campione possono essere aumentate durante la valutazione. 

## <a name="certification-process"></a>Processo di certificazione

Prima di avviare il processo di certificazione, sarà necessario aver completato correttamente l'attestazione del server di pubblicazione. Al termine, il processo di certificazione Microsoft 365 procederà come segue:

### <a name="preparation"></a>Preparazione
1. Passare al Centro per i partner ed esaminare la documentazione di [attestazione del server di pubblicazione](../docs/attestation.md) completata. Se necessario, è possibile modificare e aggiornare le risposte; in tal caso, tuttavia, sarà necessario inviare nuovamente la documentazione di attestazione per l'approvazione. Se l'invio ha più di tre mesi, sarà necessario inviare di nuovo l'attestazione del server di pubblicazione per la revisione e la convalida. 
1. Leggere attentamente la [Guida all'invio della certificazione Microsoft 365](../docs/certification-submission-guide.md) per comprendere cosa verrà richiesto dall'utente. Assicurarsi di essere in grado di soddisfare i [requisiti di controllo](../docs/certification-submission-guide.md#app-certification-criteria) specificati nella Guida all'invio della certificazione di Microsoft 365.
1. Nel Centro per i partner fare clic su "Avvia certificazione". Verrà visualizzato il portale di invio di documenti iniziale. Inviare [l'invio iniziale del documento](../docs/certification-submission-guide.md#initial-document-submission). Questo ci aiuterà a determinare cosa è nell'ambito della valutazione in base al modo in cui l'app viene progettata e gestisce i dati dei clienti. Controlla spesso questa pagina per verificare se l'invio è stato accettato.

>[!NOTE]
>Per tutte le app di Office, è possibile fare riferimento [alla Guida per l'utente di Office Apps](../docs/userguide.md). Per tutte le app Web, è possibile fare riferimento alla [guida per l'utente dell'app SaaS](../docs/saasuserguide.md).

### <a name="assessment"></a>Valutazione
1. Dopo l'accettazione dell'invio iniziale del documento, il set di controlli di sicurezza necessari per l'app verrà visualizzato automaticamente nel portale. Sarà quindi necessario inviare prove per ogni controllo che dimostri che il controllo è presente. Tieni presente che ti verranno concessi **60 giorni** per inviare tutte le prove. Un analista esaminerà le prove e approverà il controllo o richiederà prove nuove o aggiuntive.An analyst will review your evidence and either approve the control or request new or additional evidence. Controllare spesso questa pagina per verificare se le prove sono state accettate.
### <a name="certification"></a>Certificazione
1. Dopo che l'invio è stato convalidato da un analista, si riceverà una notifica della decisione di certificazione. Le app con certificazione riceveranno un badge nell'applicazione all'interno di **AppSource** e **nelle pagine della documentazione Microsoft** . È possibile leggere i vantaggi completi della certificazione [qui](../docs/enterprise-app-certification-guide.md#program-benefits).

## <a name="review-and-re-certification"></a>Revisione e ricertificazione
Nel caso in cui l'applicazione subisca [modifiche significative](../docs/certification-submission-guide.md#significant-changes) in qualsiasi momento, sarà necessario inviarci una notifica.

Sarà inoltre necessario eseguire la ricertificazione su base annuale. Ciò richiederà la riconvalida dei controlli nell'ambito rispetto all'ambiente corrente. Questo processo può iniziare fino a 90 giorni prima della scadenza della certificazione. La certificazione esistente non scadrà durante il periodo di certificazione. La certificazione di tutti i programmi scade in occasione dell'anniversario di un anno della certificazione Microsoft 365.

Se la certificazione non viene rinnovata prima della data di scadenza, lo stato di certificazione delle app verrà revocato. Tutti i tag, le icone e il marchio di certificazione associato verranno rimossi dall'app e non sarà consentito pubblicizzare l'app come Microsoft 365 Certified.


> [!IMPORTANT]
> **Intervallo di tempo per l'invio:** Si prevede che in media il processo di valutazione richieda 30 giorni, a condizione che tu sia in grado di controllare frequentemente lo stato dell'invio e rispondere ai commenti e alle richieste di prove supplementari in modo tempestivo. All'avvio del processo di certificazione, è consentito completare la valutazione per un massimo di 60 giorni. Se tutti gli invii non sono stati completati entro il periodo di tempo di 60 giorni, all'invio verrà generato un errore e il processo deve ricominciare. Questi risultati non saranno resi pubblici.


## <a name="initial-document-submission"></a>Invio iniziale del documento


L'invio di documenti iniziale consentirà agli analisti di certificazione di eseguire l'ambito e determinare quali saranno gli ambiti per la valutazione. Dopodiché sarà necessario inviare la documentazione di supporto e le prove usate per eseguire la valutazione. L'invio iniziale deve includere le informazioni specificate di seguito. Per altre informazioni, vedere la [Guida alla sottomissione del documento](../docs/initialdocumentsubguide.md) iniziale.

| **Panoramica della documentazione&nbsp;**     |   **Dettagli della documentazione**  |
| -------------------------| -----------------------------|
|**Descrizione app/componente aggiuntivo** | Descrizione dello scopo e della funzionalità dell'app/componente aggiuntivo. Questo dovrebbe fornire all'analista della certificazione una buona comprensione del funzionamento dell'app/componente aggiuntivo e di ciò che viene usato
|**Report test di penetrazione** |Report di test di penetrazione completato negli ultimi 12 mesi. Questo report deve includere l'ambiente che supporta la distribuzione dell'app/aggiunta insieme a qualsiasi altro ambiente che supporti il funzionamento dell'app/componente aggiuntivo. **Nota:** se non si eseguono test di penetrazione annuali, è possibile scegliere di eseguirli tramite il processo di certificazione.|
|**Diagrammi di architettura**|Diagramma dell'architettura logica che rappresenta una panoramica generale dell'infrastruttura di supporto dell'app/componente aggiuntivo. Deve includere **tutti gli** ambienti di hosting e l'infrastruttura di supporto che supporta l'app/componente aggiuntivo. Questo diagramma DEVE descrivere tutti i diversi componenti di sistema di supporto all'interno dell'ambiente per aiutare gli analisti di certificazione a comprendere i sistemi nell'ambito e a determinare il campionamento. Indicare anche il tipo di ambiente di hosting usato. ISV Ospitato, IaaS, PaaS o Ibrido. **Nota:** Dove viene usato SaaS, indicare i vari servizi SaaS usati per fornire i servizi di supporto all'interno dell'ambiente.|
|**Footprint pubblico** | Dettagli su **tutti gli** URL e gli indirizzi IP pubblici usati dall'infrastruttura di supporto. Questo deve includere l'intervallo IP instradabile completo allocato all'ambiente a meno che non sia stata implementata una segmentazione adeguata per dividere l'intervallo in uso (saranno necessarie prove adeguate di segmentazione)|
|**Diagrammi del flusso di dati** |Diagrammi di flusso che illustrano in dettaglio quanto segue:
||&#x2713; flussi di dati M365 da e verso l'app/componente aggiuntivo (inclusi [EUII](#euii) e [OII](#oii) ).|
||&#x2713; flussi di dati M365 all'interno dell'infrastruttura di supporto (se applicabile)|
||&#x2713; Diagrammi che evidenziano dove e quali dati vengono archiviati, come vengono passati i dati a terze parti esterne (inclusi i dettagli di quali terze parti) e come i dati vengono protetti in transito su reti aperte/pubbliche e inattivi.|
|**Dettagli endpoint API**| Elenco completo di tutti gli endpoint API usati dall'app. Per comprendere l'ambito dell'ambiente, specificare i percorsi degli endpoint API all'interno dell'ambiente.                                
|**Autorizzazioni api Microsoft**| Fornire la documentazione che illustra **in dettaglio TUTTE le** API Microsoft usate insieme alle autorizzazioni richieste per il funzionamento dell'app/componente aggiuntivo insieme a una giustificazione per le autorizzazioni richieste|
|**Tipi di archiviazione dati** |Archiviazione dei dati e gestione dei documenti che descrivono:|
||&#x2713; In che misura i clienti ricevono e archiviano i dati M365 [EUII](#euii) e [OII](#oii)|
||&#x2713; Periodo di conservazione dei dati.|
||&#x2713; Perché vengono acquisiti i dati M365 del cliente.|
||&#x2713; in cui vengono archiviati i dati M365 del cliente (devono essere inclusi nei diagrammi del flusso di dati forniti in precedenza).|
|**Conferma della conformità**|Documentazione di supporto per i framework di sicurezza esterni inclusi nell'invio dell'attestazione del server di pubblicazione o da considerare quando si esaminano i controlli di certificazione di Microsoft 365. Attualmente sono supportati i tre elementi seguenti:|
||&#x2713; [ATCO (PCI DSS](#pci-dss) Attestation of Compliance).|
||&#x2713; report [SOC 2](#soc-2) di tipo I/Type II.|
||&#x2713; ISMS IEC - 1S0/IEC 27001 Statement of Applicability (SoA) and Certification.&#x2713; [ISMS](#isms) / [IEC](#iec) - 1S0/IEC 27001 Statement of Applicability (SoA) and Certification.|
|**Dipendenze Web**|Documentazione che elenca tutte le dipendenze usate dall'app/componente aggiuntivo con le versioni correnti in esecuzione.|
|**Inventario software**|Un inventario software aggiornato che include tutto il software usato nell'ambiente nell'ambito insieme alle versioni.|
|**Inventario hardware**| Inventario hardware aggiornato usato dall'infrastruttura di supporto. Verrà usato per facilitare il campionamento durante l'esecuzione della fase di valutazione. Se l'ambiente include PaaS, specificare i dettagli dei servizi utilizzati.|

## <a name="evidence-collection-and-assessment-activities"></a>Attività di raccolta e valutazione delle prove

Gli analisti di certificazione dovranno esaminare le prove in tutti i componenti di sistema all'interno del set di esempi definito. I tipi di prove necessari per supportare il processo di valutazione includono uno o tutti i seguenti:

**Raccolta di prove**

* Documentazione iniziale, evidenziata nella sezione [Invio iniziale della documentazione](#initial-document-submission) precedente 
* Documenti dei criteri 
* Elaborare i documenti 
* Impostazioni di configurazione del sistema 
* Modificare i ticket 
* Modificare i record di controllo 
* Report di sistema

Verranno usati vari metodi per raccogliere le prove necessarie per completare il processo di valutazione.  Questa raccolta di prove può essere sotto forma di: 
* Documenti 
* Screenshot 
* Interviste 
* Screenharing 

Le tecniche di raccolta delle prove usate verranno determinate durante il processo di valutazione. Per esempi concreti del tipo di prova richiesto nell'invio, vedere la [Guida all'evidenza di esempio](../docs/certification-sample-evidence-guide.md).

**Attività di valutazione**

Gli analisti di certificazione esamineranno le prove fornite per determinare se sono stati soddisfatti i controlli in modo adeguato all'interno di questa specifica di certificazione di Microsoft 365. 

Se possibile e per ridurre la quantità di tempo necessaria per completare la valutazione, è necessario fornire in anticipo una o tutta la documentazione dettagliata nell'invio   [iniziale della documentazione](#initial-document-submission).

Gli analisti della certificazione esamineranno prima di tutto le prove fornite dall'invio della documentazione iniziale e le informazioni sull'attestazione dell'editore per identificare le linee di indagine appropriate, le dimensioni del campionamento e la necessità di ottenere ulteriori prove come descritto in precedenza.  Gli analisti di certificazione analizzeranno tutte le informazioni raccolte per trarre conclusioni su come e se si soddisfano i controlli all'interno di questa specifica di certificazione di Microsoft 365. 

## <a name="app-certification-criteria"></a>Criteri di certificazione dell'app

L'app, l'infrastruttura di supporto e la documentazione di supporto verranno valutati nei domini di sicurezza seguenti:

1. [**Sicurezza delle applicazioni**](#application-security)
1. [**Sicurezza operativa/distribuzione sicura**](#operational-security)
1. [**Sicurezza e privacy per la gestione dei dati**](#data-handling-security-and-privacy)

Ognuno di questi domini di sicurezza include controlli chiave specifici che includono uno o più requisiti specifici che verranno valutati come parte del processo di valutazione. Per garantire che la certificazione Microsoft 365 sia inclusiva per gli sviluppatori di tutte le dimensioni, ogni dominio di sicurezza viene valutato usando un sistema di assegnazione dei punteggi per determinare un punteggio complessivo da ognuno dei domini. I punteggi per ognuno dei controlli di certificazione microsoft 365 vengono allocati tra 1 (basso) e 3 (alto) in base al rischio percepito che tale controllo non venga soddisfatto. Ognuno dei domini di sicurezza avrà un punteggio percentuale minimo da considerare come pass. Alcuni elementi di questa specifica includono alcuni criteri di errore automatici:

- Autorizzazioni API che non seguono il principio dei privilegi minimi (PoLP).  
- Nessun report di test di penetrazione quando è necessario.
- Nessuna difesa antimalware
- L'autenticazione a più fattori non viene usata per proteggere l'accesso amministrativo.  
- Nessun processo di applicazione di patch.  
- Nessuna informativa sulla privacy [gdpr](#gdpr) appropriata.  

## <a name="application-security"></a>Sicurezza delle applicazioni

Il dominio di sicurezza dell'applicazione è incentrato sulle tre aree seguenti: 
* Convalida delle autorizzazioni GraphAPI 
* Controlli di connettività esterni
* Test di sicurezza delle applicazioni 

### <a name="graphapi-permission-validation"></a>Convalida delle autorizzazioni GraphAPI

La convalida delle autorizzazioni GraphAPI viene eseguita per convalidare l'app/componente aggiuntivo non richiede autorizzazioni eccessivamente permissive. Questa operazione viene eseguita controllando manualmente le autorizzazioni richieste. Gli analisti di certificazione faranno riferimento a questi controlli rispetto all'invio dell'attestazione del server di pubblicazione e valuteranno il livello di accesso richiesto per garantire che vengano soddisfatte le procedure con privilegi minimi. Se gli analisti di certificazione ritengono che queste procedure con privilegi minimi non siano soddisfatte, gli analisti di certificazione avranno una discussione aperta con l'utente per convalidare la giustificazione aziendale per le autorizzazioni richieste. Eventuali discrepanze rispetto all'invio dell'attestazione dell'editore trovate durante questa recensione riceveranno anche commenti e suggerimenti in modo che l'attestazione dell'editore possa essere aggiornata. 

### <a name="external-connectivity-checks"></a>Controlli di connettività esterni

Nell'ambito della valutazione, un analista eseguirà una leggera analisi delle funzionalità delle applicazioni per identificare le connessioni al di fuori di M365.  Tutte le connessioni non identificate come Microsoft o le connessioni dirette al servizio verranno contrassegnate e discusse durante la valutazione.

### <a name="application-security-testing"></a>Test di sicurezza delle applicazioni

Una revisione adeguata dei rischi associati all'app/componente aggiuntivo e all'ambiente di supporto è essenziale per garantire ai clienti la sicurezza dell'app/componente aggiuntivo. I test di sicurezza delle applicazioni sotto forma di test di penetrazione DEVONO essere eseguiti se l'applicazione ha connettività a qualsiasi servizio non pubblicato da Microsoft. Se l'app funziona autonomamente senza connettività a servizi o back-end non Microsoft, non è necessario eseguire il test di penetrazione.


**Ambito test di penetrazione**

Le attività di test di penetrazione **DEVONO** essere eseguite nell'ambiente di produzione live che supporta la distribuzione dell'app/componente aggiuntivo (ad esempio, in cui è ospitato il codice app/componente aggiuntivo che in genere sarà la risorsa all'interno del file manifesto) insieme a qualsiasi ambiente aggiuntivo che supporta il funzionamento dell'app/componente aggiuntivo (ad esempio, se l'app/componente aggiuntivo comunica con altre applicazioni Web esterne a Microsoft 365).  Quando si definisce l'ambito, è necessario prestare attenzione a garantire che tutti i sistemi o gli ambienti "connessi a" che possono influire sulla sicurezza dell'ambiente nell'ambito siano inclusi anche nelle attività di test di penetrazione DI TUTTI. 

Quando vengono usate tecniche per segmentare gli ambienti nell'ambito da altri ambienti, le attività di test di penetrazione DEVONO convalidare l'efficacia di tali tecniche di segmentazione. Questa operazione deve essere dettagliata all'interno del report di test di penetrazione. 

I report sui test di penetrazione verranno esaminati per verificare che non siano presenti vulnerabilità che soddisfano i **criteri di errore automatici** seguenti descritti nei controlli seguenti.
 
**Requisiti per i test di penetrazione**


|**Tipo di criteri**|**Controlli test di penetrazione**|
| -------------------------|-----------------------------|
|**Criteri generali**| **Controlli**|
|| I test di penetrazione dell'applicazione e dell'infrastruttura **DEVONO** essere eseguiti ogni anno (ogni 12 mesi) e condotti da una società indipendente affidabile. |
|| La correzione delle vulnerabilità critiche e ad alto rischio identificate **DEVE** essere completata entro un mese dalla conclusione dei test di penetrazione o prima a seconda del processo di applicazione di patch documentato. |
|| Footprint esterno completo (indirizzi IP, URL, endpoint API e così via) DEVE essere incluso nell'ambito dei test di penetrazione e deve essere documentato nel report di test di penetrazione. |
|| I test di penetrazione delle applicazioni Web DEVONO includere tutte le classi di vulnerabilità; Ad esempio, il più recente OWASP Top 10 o SANS Top 25 CWE. |
|| Non è necessario un nuovo test delle vulnerabilità identificate dalla società di test di penetrazione: la correzione e l'auto-revisione sono tuttavia sufficienti, tuttavia, è necessario fornire prove adeguate per dimostrare che durante la valutazione **deve** essere fornita una correzione sufficiente.|
|**Criteri di errore automatico:**|**Controlli**|
|| Presenza di un sistema operativo non supportato. |
|| Presenza di account amministrativi predefiniti, enumerabili o indovinabili.|
|| Presenza di rischi di inserimento SQL.|
|| Presenza di script tra siti.|
|| Presenza di vulnerabilità di attraversamento della directory (percorso file).|
|| Presenza di vulnerabilità HTTP, ad esempio divisione della risposta dell'intestazione, traffico di richieste e attacchi Desync.|
|| Presenza di divulgazione del codice sorgente (inclusa [LFI](#lfi)).|
|| Qualsiasi punteggio critico o elevato come definito dalle linee guida per la gestione delle patch cvss.|
|| Qualsiasi vulnerabilità tecnica significativa che può essere facilmente sfruttata per compromettere una grande quantità di EUII o OUI.|






> [!IMPORTANT]
>I report devono essere in grado di fornire una garanzia sufficiente che sia possibile dimostrare tutti gli elementi descritti nella sezione Specifica del test di sicurezza dell'applicazione.


**Requisiti e regole di test di penetrazione gratuiti**

- Per gli ISV che attualmente non si impegnano in test di penetrazione, i test di penetrazione possono essere condotti gratuitamente con la certificazione Microsoft 365. Microsoft organizzerà e coprirà il costo di un test di penetrazione per un massimo di 12 giorni di test manuali. I costi dei test di penetrazione vengono calcolati in base al numero di giorni necessari per testare l'ambiente. Tutte le spese che superano i 12 giorni di test saranno responsabilità dell'ISV. 
- Gli ISV dovranno presentare prove e ricevere l'approvazione per il 50% dei controlli nell'ambito prima che venga eseguito il test di penetrazione. Per iniziare, è sufficiente compilare l'invio iniziale del documento e scegliere di includere i test di penetrazione come parte della valutazione. Sarai contattato per definire l'ambito e pianificare il test di penetrazione dopo aver completato il 50% dei controlli.
- Il report emesso al termine del test penna verrà fornito all'ISV dopo aver completato la certificazione. Questo report insieme alla certificazione Microsoft 365 può essere usato per mostrare ai potenziali clienti che l'ambiente è sicuro.
- Gli ISV saranno anche responsabili di dimostrare che le vulnerabilità identificate nel test di penetrazione sono state risolte prima dell'assegnazione di una certificazione, ma non devono produrre un report pulito.

Una volta organizzato un test di penetrazione, l'ISV è responsabile delle tariffe associate alla riprogrammazione e all'annullamento come segue:

| **Riprogrammazione della scala cronologica delle commissioni** | **Percentuale pagabile** |
|------------------|------------------------|
| Ri-pianificare richiesta ricevuta più di 30 giorni prima della data di inizio pianificata. | 0% pagabile |
| Ri-pianificare richiesta ricevuta da 8 a 30 giorni prima della data di inizio pianificata. | 25% pagabile |
| Re-pianificare richiesta ricevuta entro 2-7 giorni prima della data di inizio pianificata con una data di ri-prenotazione aziendale.| 50% pagabile |
| Ri-pianificare richiesta ricevuta meno di 2 giorni prima della data di inizio. | 100% pagabile |

| **Scala cronologica della tariffa di annullamento** | **Percentuale pagabile** |
|------------------|------------------------|
| Richiesta di annullamento ricevuta più di 30 giorni prima della data di inizio pianificata. | 25% pagabile |
| Richiesta di annullamento ricevuta da 8 a 30 giorni prima della data di inizio pianificata. | 50% pagabile |
| Richiesta di annullamento ricevuta entro 7 giorni prima della data di inizio pianificata. | 90% pagabile |

## <a name="operational-security"></a>Sicurezza operativa

Questo dominio misura l'allineamento dei processi di distribuzione e infrastruttura di supporto dell'app con le procedure consigliate per la sicurezza.

### <a name="controls"></a>Controlli

|**Famiglia di controlli**| **Controlli**|
| ------------------------|------------------------------ |
| **Protezione da malware - Antivirus**|Fornire la documentazione dei criteri che regola le procedure e le procedure antivirus.|
||Fornire prove dimostrabili che il software antivirus è in esecuzione in tutti i componenti di sistema campionati.|
||Fornire prove dimostrabili che le firme antivirus sono aggiornate in tutti gli ambienti (entro 1 giorno).|
||Fornire prove dimostrabili che l'antivirus è configurato per eseguire analisi di accesso o analisi periodica in tutti i componenti del sistema campionati. Nota: se l'analisi all'accesso non è abilitata, è necessario abilitare almeno l'analisi giornaliera e l'avviso.|
||Fornire prove dimostrabili che l'antivirus è configurato per bloccare automaticamente malware o quarantena e avvisi in tutti i componenti di sistema campionati.|
|**Controlli applicazione**: obbligatorio SOLO se non viene usato l'antimalware tradizionale|Fornire prove dimostrabili che le applicazioni vengono approvate prima della distribuzione.|
||Fornire prove dimostrabili che esiste e viene mantenuto un elenco completo di applicazioni approvate con giustificazione aziendale.|
||Fornire la documentazione di supporto che illustra in dettaglio che il software di controllo dell'applicazione è configurato per soddisfare meccanismi di controllo dell'applicazione specifici. (Esempio: Elenco consentito: sample1, sample3, firma del codice)|
||Fornire prove dimostrabili che il controllo dell'applicazione è configurato come documentato da tutti i componenti di sistema campionati.|
|**Gestione delle patch - Classificazione dei rischi**| Documentazione dei criteri di fornitura che regola il modo in cui vengono identificate le nuove vulnerabilità di sicurezza e viene assegnato un punteggio di rischio.|
||Fornire la prova di come vengono identificate nuove vulnerabilità di sicurezza.|
||Fornire prove che dimostrino che a tutte le vulnerabilità viene assegnata una classificazione dei rischi una volta identificata.|
|**Gestione delle patch - Applicazione di patch**|Fornire la documentazione dei criteri per l'applicazione di patch ai componenti di sistema nell'ambito che include un intervallo di tempo di applicazione di patch minimo adatto per vulnerabilità critiche, ad alto e medio rischio; e la disattivazione di qualsiasi sistema operativo e software non supportato.|
||Fornire prove dimostrabili che vengono applicate patch a tutti i componenti del sistema campionati.|
||Fornire prove dimostrabili che tutti i sistemi operativi e i componenti software non supportati non vengono usati all'interno dell'ambiente.|
|**Analisi delle vulnerabilità**|Fornire i report trimestrali sull'analisi delle vulnerabilità dell'infrastruttura e dell'applicazione Web. L'analisi deve essere eseguita in base all'intero footprint pubblico (INDIRIZZI IP e URL) e agli intervalli IP interni.|
||Fornire prove dimostrabili che la correzione delle vulnerabilità identificate durante l'analisi delle vulnerabilità viene applicata a patch in linea con l'intervallo di tempo di applicazione delle patch documentato.|
|**Firewall**|Fornire la documentazione dei criteri che regola le procedure e le procedure di gestione del firewall.|
||Fornire prove dimostrabili che tutte le credenziali amministrative predefinite vengono modificate prima dell'installazione in ambienti di produzione.|
||Fornire prove dimostrabili che i firewall sono installati sul limite dell'ambiente nell'ambito e installati tra la rete perimetrale (nota anche come rete perimetrale, zona demilitarizzata e subnet schermata) e le reti attendibili interne.|
||Fornire prove dimostrabili che tutti gli accessi pubblici terminano nella zona demilitarizzata (DMZ).|
||Fornire prove dimostrabili che tutto il traffico consentito attraverso il firewall passa attraverso un processo di approvazione.|
||Fornire prove dimostrabili che la base di regole del firewall è configurata per eliminare il traffico non definito in modo esplicito.|
||Fornire prove dimostrabili che il firewall supporta solo crittografia avanzata in tutte le interfacce amministrative non della console.|
||Fornire prove dimostrabili che si eseguono revisioni delle regole del firewall almeno ogni 6 mesi.|
|**Web application firewall (WAF) (FACOLTATIVO):** il credito aggiuntivo verrà ricompensato per aver soddisfatto i controlli seguenti.|Fornire prove dimostrabili che il Web application firewall (WAF) è configurato per monitorare, avvisare e bloccare attivamente il traffico dannoso.|
||Fornire prove dimostrabili che waf supporta l'offload SSL.|
||Fornire prove dimostrabili che il WAF è protetto da alcune o tutte le classi di vulnerabilità seguenti in base al set di regole di base di OWASP (3.0 o 3.1) |
|**Controllo delle modifiche**|Fornire la documentazione dei criteri che regola i processi di controllo delle modifiche.|
||Fornire prove dimostrabili che gli ambienti di sviluppo e test applicano la separazione dei compiti dall'ambiente di produzione.|
||Fornire prove dimostrabili che i dati di produzione sensibili non vengono usati negli ambienti di sviluppo o di test.|
||Fornire prove dimostrabili che le richieste di modifica documentate contengono l'impatto della modifica, i dettagli delle procedure di back-out e dei test da eseguire.|
||Fornire prove dimostrabili che le richieste di modifica vengono sottoposte a un processo di autorizzazione e di conclusione.|
|**Sviluppo/distribuzione di software sicuro**| Fornire criteri e procedure che supportano lo sviluppo e la distribuzione di software sicuri, incluse indicazioni sulle procedure consigliate per la codifica sicura per classi di vulnerabilità comuni, ad esempio OWASP Top 10 o SANS Top 25 CWE.|
|| Fornire prove dimostrabili che le modifiche al codice vengono sottoposte a un processo di revisione e autorizzazione da parte di un secondo revisore.|
|| Fornire prove dimostrabili che gli sviluppatori vengono sottoposti a training di sviluppo software sicuro ogni anno.|
|| Fornire prove dimostrabili che i repository di codice sono protetti con l'autenticazione a più fattori (MFA).|
|| Fornire prove dimostrabili che i controlli di accesso sono in atto per proteggere i repository di codice.
|**Gestione account**| Fornire la documentazione dei criteri che regola le procedure e le procedure di gestione degli account.
||Fornire prove dimostrabili che le credenziali predefinite vengono disabilitate, rimosse o modificate nei componenti di sistema campionati.|
||Fornire prove dimostrabili che la creazione, la modifica e l'eliminazione dell'account passano attraverso un processo di approvazione stabilito.|
||Fornire prove dimostrabili che è in atto un processo per disabilitare o eliminare gli account non usati entro 3 mesi.|
||Fornire prove dimostrabili che sono presenti criteri password complesse o altre mitigazioni appropriate per proteggere le credenziali utente.  Come linea guida minima è consigliabile usare quanto segue: lunghezza minima della password di 8 caratteri, soglia di blocco dell'account non superiore a 10 tentativi, cronologia delle password di un minimo di 5 password, imposizione dell'uso di password complesse|
||Fornire prove dimostrabili che gli account utente univoci vengono rilasciati a tutti gli utenti.|
||Fornire prove dimostrabili che i principi dei privilegi minimi vengono seguiti all'interno dell'ambiente.|
||Fornire prove dimostrabili che è in atto un processo per proteggere o rafforzare gli account del servizio e che il processo viene seguito.|
||Fornire prove dimostrabili che L'autenticazione a più fattori è configurata per tutte le connessioni di accesso remoto e tutte le interfacce amministrative non console.|
||Fornire prove dimostrabili che la crittografia avanzata è configurata per tutte le connessioni di accesso remoto e tutte le interfacce amministrative non console, incluso l'accesso a qualsiasi repository di codice e interfacce di gestione cloud.|
||Fornire prove dimostrabili dell'uso dell'autenticazione a più fattori per proteggere il portale di amministrazione usato per gestire e gestire tutti i record DNS (Public Domain Name Service).|
|**Rilevamento e prevenzione delle intrusioni (FACOLTATIVO):** Il credito aggiuntivo verrà ricompensato per aver soddisfatto i controlli seguenti|Fornire prove dimostrabili che i sistemi di rilevamento e prevenzione delle intrusioni (IDPS) vengono distribuiti nel perimetro degli ambienti nell'ambito.|
||Fornire prove dimostrabili che le firme IDPS vengono mantenute aggiornate (entro 24 ore).|
||Fornire prove dimostrabili che IDPS è configurato per supportare l'ispezione TLS di tutto il traffico Web in ingresso.|
||Fornire prove dimostrabili che IDPS è configurato per monitorare tutti i flussi di traffico in ingresso.|
||Fornire prove dimostrabili che IDPS è configurato per monitorare tutti i flussi di traffico in uscita.|
|**Registrazione eventi di sicurezza** |Fornire la documentazione dei criteri per le procedure consigliate e le procedure che regolano la registrazione degli eventi di sicurezza.|
|| Fornire prove dimostrabili che mostrano che la registrazione degli eventi di sicurezza è configurata in tutti i componenti di sistema campionati per registrare gli eventi seguenti: Accesso utente ai componenti di sistema e all'applicazione, Tutte le azioni eseguite da un utente con privilegi elevati, Tentativi di accesso logico non validi Creazione o modifica dell'account con privilegi, Manomissione del log eventi, Disabilitazione di strumenti di sicurezza (ad esempio antimalware o registrazione eventi),  Registrazione antimalware (ad esempio aggiornamenti, rilevamento di malware e errori di analisi)., eventi IDPS e WAF, se configurati|
||Fornire prove dimostrabili che gli eventi di sicurezza registrati contengono le informazioni minime seguenti: Utente, Tipo di evento, Data e ora, Indicatori di esito positivo o negativo, Etichetta che identifica il sistema interessato|
||Fornire prove dimostrabili che tutti i componenti di sistema campionati sono sincronizzati nel tempo con gli stessi server primari e secondari.|
||Fornire prove dimostrabili quando i sistemi pubblici sono in uso che i log eventi di sicurezza vengono inviati a una soluzione di registrazione centralizzata non all'interno della rete perimetrale.|
||Fornire prove dimostrabili per dimostrare che la soluzione di registrazione centralizzata è protetta da manomissioni non autorizzate dei dati di registrazione.|
||Fornire prove dimostrabili che un minimo di 30 giorni di dati di registrazione eventi di sicurezza è immediatamente disponibile, con 90 giorni di log eventi di sicurezza conservati.|
|**Revisione (dati di log)** |Fornire la documentazione dei criteri che regola le procedure e le procedure di revisione dei log.|
||Fornire prove dimostrabili che i log vengono esaminati quotidianamente da strumenti umani o automatizzati per identificare potenziali eventi di sicurezza.|
||Fornire prove dimostrabili che i potenziali eventi di sicurezza e anomalie vengono analizzati e corretti.|
|**Avvisi** | Fornire la documentazione dei criteri che regola le procedure e le procedure di avviso degli eventi di sicurezza.|
|| Fornire prove dimostrabili che vengono attivati avvisi per valutare immediatamente i tipi di eventi di sicurezza seguenti: creazione o modifica di account con privilegi, eventi di virus o malware, manomissioni del registro eventi, eventi IDPS o WAF|
||Fornire prove dimostrabili che dimostrano che il personale è sempre disponibile, tutto il giorno, per rispondere agli avvisi di sicurezza.|
|**Gestione dei rischi**|Fornire prove dimostrabili dell'esistenza di un processo formale di gestione dei rischi per la sicurezza delle informazioni.|
||Fornire prove dimostrabili che una valutazione formale dei rischi viene eseguita ogni anno, almeno.|
||Fornire prove dimostrabili che la valutazione dei rischi per la sicurezza delle informazioni include minacce, vulnerabilità o equivalenti.|
||Fornire prove dimostrabili che la valutazione del rischio di sicurezza delle informazioni include l'impatto, la matrice di rischio di probabilità o l'equivalente.|
||Fornire prove dimostrabili che la valutazione dei rischi per la sicurezza delle informazioni include un registro dei rischi e un piano di trattamento.|
|**Risposta a un incidente**|Specificare il piano di risposta agli eventi imprevisti (IRP) di sicurezza.|
||Fornire prove dimostrabili che l'IRP di sicurezza include un processo di comunicazione documentato per garantire una notifica tempestiva alle principali parti interessate, ad esempio marchi di pagamento e acquirenti, organismi di regolamentazione, autorità di vigilanza, amministratori e clienti.|
||Fornire prove dimostrabili che tutti i membri del team di risposta agli eventi imprevisti hanno completato la formazione annuale o un esercizio di tabella superiore.|
||Fornire prove dimostrabili per mostrare che l'IRP di sicurezza viene aggiornato in base alle lezioni apprese o alle modifiche dell'organizzazione.|

## <a name="data-handling-security-and-privacy"></a>Sicurezza e privacy per la gestione dei dati

I dati in transito tra l'utente dell'applicazione, i servizi intermedi e i sistemi ISV devono essere protetti dalla crittografia tramite una connessione TLS che supporta almeno TLS v1.1. *Vedere* [**l'appendice A**](#appendix-a).

Dove l'applicazione recupera e archivia i dati M365, sarà necessario implementare uno schema di crittografia dell'archiviazione dati che segue la specifica definita [**nell'appendice B**](#appendix-a).

### <a name="controls"></a>Controlli

|**Famiglia di controlli**| **Controlli** |
| -----------------------|-------------------------------- |
|**Dati in transito**| Fornire prove dimostrabili che la configurazione TLS soddisfa o supera i requisiti di crittografia all'interno dei [requisiti di configurazione del profilo TLS](../docs/certification-submission-guide.md#appendix-a)|
||Fornire prove dimostrabili che la compressione TLS è disabilitata in tutti i servizi pubblici che gestiscono le richieste Web.|
||Fornire prove dimostrabili che la sicurezza del trasporto http TLS strict è abilitata e configurata per >= 15552000 in tutti i siti.|
|**Dati inattivi**| Fornire prove dimostrabili che i dati inattivi sono crittografati in linea con i requisiti del profilo di crittografia, usando algoritmi di crittografia come AES, Blowfish, TDES e dimensioni delle chiavi di crittografia a 128 bit e a 256 bit.|
||Fornire prove dimostrabili che la funzione hash o l'autenticazione dei messaggi (HMAC-SHA1) viene usata solo per proteggere i dati inattivi in linea con i requisiti del profilo di crittografia.|
||Fornire un inventario che mostri tutti i dati archiviati, inclusi il percorso di archiviazione e la crittografia usati per proteggere i dati.|
|**Conservazione ed eliminazione dei dati**|Fornire prove dimostrabili che un periodo di conservazione dei dati approvato e documentato è formalmente stabilito.|
||Fornire prove dimostrabili che i dati conservati corrispondono al periodo di conservazione definito.|
||Fornire prove dimostrabili che i processi sono in atto per eliminare in modo sicuro i dati dopo il periodo di conservazione.|
|**Gestione accesso ai dati**|Fornire un elenco di tutti gli utenti con accesso ai dati o alle chiavi di crittografia, inclusa la giustificazione aziendale.|
||Fornire prove dimostrabili che gli utenti campionati che hanno accesso ai dati o alle chiavi di crittografia sono stati formalmente approvati, specificando i privilegi necessari per la funzione di processo.|
||Fornire prove dimostrabili che gli utenti campionati che hanno accesso ai dati o alle chiavi di crittografia hanno solo i privilegi inclusi nell'approvazione.|
||Specificare un elenco di tutte le terze parti con cui vengono condivisi i dati dei clienti.|
||Fornire prove dimostrabili che tutti i terzi che utilizzano i dati dei clienti hanno contratti di condivisione.|
|**GDPR** (se applicabile)| Fornire un processo di richiesta di accesso soggetto (SAR) documentato e fornire prove che dimostrino che gli interessati sono in grado di generare RICHIESTE SA.|
||Fornire prove dimostrabili che è possibile identificare tutte le posizioni dei dati degli interessati quando si risponde a un SAR.|
||Si mantiene un'informativa sulla privacy che deve contenere i dettagli delle società (Nome, Indirizzo e così via).|
||Si mantiene un'informativa sulla privacy che dovrebbe spiegare i tipi di dati personali elaborati.|
||Si mantiene un'informativa sulla privacy che dovrebbe spiegare la liceità del trattamento dei dati personali|
||L'utente mantiene un'informativa sulla privacy che spiega in dettaglio i diritti dell'interessato: Diritto di essere informato, Diritto di accesso da parte dell'interessato, Diritto alla cancellazione, Diritto alla restrizione del trattamento, Diritto alla portabilità dei dati, Diritto all'oggetto, Diritti in relazione al processo decisionale automatizzato, inclusa la profilatura.|
|| Si mantiene un'informativa sulla privacy che dovrebbe spiegare per quanto tempo verranno conservati i dati personali.|

## <a name="optional-external-compliance-frameworks-review"></a>Revisione facoltativa dei framework di conformità esterni

Anche se non è obbligatorio, se attualmente si è in conformità con ISO 27001, PCI DSS o SOC2, è possibile scegliere di usare queste certificazioni per soddisfare alcuni dei controlli di certificazione di Microsoft 365. Gli analisti della certificazione tenteranno di allineare i framework di sicurezza esterni esistenti alla specifica della certificazione Microsoft 365. Tuttavia, se la documentazione di supporto non è in grado di garantire che i controlli di certificazione di Microsoft 365 siano stati valutati come parte del controllo/valutazione dei framework di sicurezza esterni, sarà necessario fornire prove aggiuntive dei controlli in vigore.

La documentazione deve dimostrare adeguatamente che l'ambiente nell'ambito per la certificazione Microsoft 365 è stato incluso nell'ambito di questi framework di sicurezza esterni. La convalida di questi framework di sicurezza verrà soddisfatta accettando prove di certificazioni valide condotte da società esterne di terze parti affidabili. Queste società affidabili devono essere membri di organismi di accreditamento internazionali per i programmi di conformità pertinenti. Vedere Standard di conformità e certificazione ISO per ISO 27001 e Valutatori di sicurezza qualificati (QSA) per PCI DSS.

La tabella seguente evidenzia i framework esterni e la documentazione richiesti dagli analisti di certificazione come parte di questo processo di convalida:

| **Standard** | **Requisiti** |
| ----- | ----- |
| **[ISO 27001](#iso-27001)** | Sarà necessaria una versione pubblica **dell'Istruzione di applicabilità** (SOA) e una copia del certificato ISO 27001 emesso.  Il SOA riepiloga la posizione in ognuno dei 114 controlli di sicurezza delle informazioni e verrà usato per identificare se eventuali esclusioni di controlli non descritti in modo soddisfacente nel certificato ISO 27001. Se non è possibile determinare questo problema esaminando la versione pubblica del SOA, l'analista potrebbe dover accedere all'intero SOA se iso 27001 verrà usato per convalidare alcuni dei controlli della specifica di certificazione di Microsoft 365.  Oltre a convalidare l'ambito delle attività di valutazione ISO 27001, gli analisti confermeranno anche la validità della società di controllo come descritto in precedenza.|
|**[PCI DSS](#pci-dss)**| È necessario fornire un documento di **attestazione di conformità** (AOC) di livello 1 valido che identifica chiaramente i componenti dell'applicazione e del sistema nell'ambito.  Un AOC di autovalutazione **non verrà** accettato come prova di soddisfare le procedure consigliate per la sicurezza. L'AOC verrà usato per determinare quali controlli della specifica di certificazione di Microsoft 365 sono stati valutati e confermati nell'ambito della valutazione PCI DSS.|
|**[SOC 2](#soc-2)**|Il report **SOC 2 (Tipo I o Tipo II)** deve essere corrente (emesso negli ultimi 15 mesi e il periodo di tempo dichiarato iniziato negli ultimi 27 mesi) da usare come prova di conformità con uno dei controlli di valutazione all'interno della specifica di certificazione microsoft 365.|

Se i framework di sicurezza esterni sono stati inclusi nell'attestazione del server di pubblicazione, gli analisti di certificazione dovranno verificare la validità di tali framework di conformità alla sicurezza nell'ambito della valutazione della certificazione di Microsoft 365.

|**Framework** | **Considerazioni aggiuntive** |
|-------------- | --------------------|
|ISO 27001| [**Appendice C**](#appendix-c): Raccolta di prove - Delta per ISO 27001.|
|PCI DSS | [**Appendice D**](#appendix-d): Raccolta di prove - Delta per PCI DSS.|
|SOC 2| [**Appendice E**](#appendix-e): Raccolta di prove - Delta per SOC 2.|

> [!NOTE]
> Anche se gli standard/framework di sicurezza esterni indicati sopra possono essere inviati come prova per soddisfare alcuni dei controlli di certificazione Microsoft 365, il superamento della certificazione Microsoft 365 non significa che si supererà correttamente un controllo rispetto a tali standard/framework. La specifica di certificazione Microsoft 365 è solo un piccolo sottoinsieme di tali standard/framework di sicurezza che consente a Microsoft di ottenere un livello di garanzia in riferimento al comportamento di sicurezza.


### <a name="requirements-to-use-external-compliance-frameworks"></a>Requisiti per l'uso di framework di conformità esterni

&#x2713; L'ambiente di supporto dell'app/componente aggiuntivo **E** tutti i processi aziendali di supporto **DEVONO** essere inclusi nell'ambito di eventuali framework di conformità della sicurezza esterni supportati e devono essere indicati chiaramente nella documentazione fornita.

&#x2713; Framework di conformità della sicurezza esterni supportati **DEVONO** essere aggiornati, ovvero entro 12 mesi (o entro 15 mesi se la rivalutazione è attualmente in corso e possono essere fornite prove).

&#x2713; I framework di conformità della sicurezza esterni supportati **DEVONO** essere eseguiti da una società accreditata indipendente.

## <a name="appendix-a"></a>Appendice A

### <a name="tls-profile-configuration-requirements"></a>Requisiti di configurazione del profilo TLS

Tutto il traffico di rete, all'interno di una rete virtuale, di un servizio cloud o di un data center, deve essere protetto con un minimo di TLS v1.1 (È consigliabile usare TLS v1.2+ ) o un altro protocollo applicabile. Le eccezioni a questo requisito sono:

* **Reindirizzamento da HTTP a HTTPS**. L'app può rispondere tramite HTTP per reindirizzare i client a HTTPS, ma la risposta non deve contenere dati sensibili (cookie, intestazioni, contenuto). Non sono consentite altre risposte HTTP oltre ai reindirizzamenti a HTTPS e alla risposta ai probe di integrità. Vedere di seguito.
* **Probe di integrità**. L'app può rispondere ai probe di integrità tramite HTTP **solo se** i probe di integrità HTTPS non sono supportati dall'entità di controllo.
* **Accesso ai certificati**. L'accesso agli endpoint CRL, OCSP e AIA ai fini della convalida del certificato e del controllo delle revoche è consentito tramite HTTP.
* **Comunicazioni locali**. L'app può usare HTTP (o altri protocolli non protetti) per le comunicazioni che non lasciano il sistema operativo, e. g. connessione a un endpoint del server Web esposto in localhost.

La compressione TLS **DEVE** essere disabilitata.

## <a name="appendix-b"></a>Appendice B

### <a name="encryption-profile-configuration-requirements"></a>Requisiti di configurazione del profilo di crittografia

Solo le primitive e i parametri di crittografia sono consentiti come indicato di seguito:

### <a name="symmetric-cryptography"></a>Crittografia simmetrica

**Crittografia**

&emsp;&#x2713; sono consentiti solo AES, BitLocker, Blowfish o TDES. È consentita una qualsiasi delle lunghezze di chiave supportate >=128 (128, 192 e 256 bit) e può essere usata (sono consigliate chiavi a 256 bit).

&emsp;&#x2713; è consentita solo la modalità CBC. Ogni operazione di crittografia deve usare un vettore di inizializzazione (IV) generato in modo casuale.

&emsp;&#x2713; L'uso di crittografie a flusso, ad esempio RC4, **NON è** consentito.

**Funzioni hash**

&emsp;&#x2713; Tutto il nuovo codice deve usare SHA-256, SHA-384 o SHA-512 (collettivamente noto come SHA-2). L'output può essere troncato a non meno di 128 bit

&emsp;&#x2713; SHA-1 può essere usato solo per motivi di compatibilità.

&emsp;&#x2713; L'uso di MD5, MD4, MD2 e altre funzioni hash NON è consentito, anche per applicazioni non crittografiche.

**Autenticazione dei messaggi**

&emsp;&#x2713; Tutto il nuovo codice DEVE usare HMAC con una delle funzioni hash approvate. L'output di HMAC può essere troncato a non meno di 128 bit.

&emsp;&#x2713; HMAC-SHA1 può essere usato solo per motivi di compatibilità.

&emsp;&#x2713; chiave HMAC DEVE essere di almeno 128 bit. Sono consigliate chiavi a 256 bit.

### <a name="asymmetric-algorithms"></a>Algoritmi asimmetrici

**Crittografia**

&emsp;&#x2713; RSA è consentito. La chiave **DEVE** essere di almeno 2048 bit e deve essere usata la spaziatura interna OAEP. L'uso della spaziatura interna PKCS è consentito solo per motivi di compatibilità.

**Firme**

&emsp;&#x2713; RSA è consentito. La chiave **DEVE** essere di almeno 2048 bit e deve essere usata la spaziatura interna PSS. L'uso della spaziatura interna PKCS è consentito solo per motivi di compatibilità.

&emsp;&#x2713;ECDSA è consentito. La chiave **DEVE** essere di almeno 256 bit. È necessario usare la curva NIST P-256, P-384 o P-521.

**Scambio di chiavi**

&emsp;&#x2713; ECDH è consentito. La chiave **DEVE** essere di almeno 256 bit. È necessario usare la curva NIST P-256, P-384 o P-521.

&emsp;&#x2713; ECDH è consentito. La chiave **DEVE** essere di almeno 256 bit. È necessario usare la curva NIST P-256, P-384 o P-521.

## <a name="appendix-c"></a>Appendice C

### <a name="evidence-collection--delta-for-iso-27001"></a>Raccolta di prove - Delta per ISO 27001

Se hai già raggiunto la conformità ISO27001, i seguenti delta (gap) non interamente coperti da ISO 27001 dovranno essere esaminati come parte della certificazione Microsoft 365.

> [!NOTE]
> Nell'ambito della valutazione della certificazione Microsoft 365, l'analista della certificazione determinerà se uno dei controlli ISO 27001 mappati non è stato incluso nell'ambito della valutazione ISO 27001 e può anche decidere di eseguire controlli di esempio che sono stati trovati da includere per fornire ulteriori garanzie. Eventuali requisiti mancanti nell'ISO 27001 dovranno essere inclusi nelle attività di valutazione della certificazione Microsoft 365.

**Protezione da malware - Antivirus**

Se la protezione da malware è in atto usando il controllo dell'applicazione e viene attestata all'interno di ISO 27001 Report non sono necessarie ulteriori indagini. Se non è presente alcun controllo delle applicazioni, gli analisti di certificazione dovranno identificare e valutare le prove dei meccanismi di controllo delle applicazioni per prevenire la detonazione del malware all'interno dell'ambiente. In questo modo sarà necessario:

* Dimostrare che il software antivirus è in esecuzione in tutti i componenti di sistema campionati.

* Dimostrare che l'antivirus è configurato in tutti i componenti del sistema campionati per bloccare automaticamente il malware, mettere in quarantena & avviso o per avvisare.

* Il software antivirus **DEVE** essere configurato per registrare tutte le attività.

**Gestione delle patch - Applicazione di patch**

Poiché gli audit ISO 27001 non valutano in modo specifico questa categoria, è necessario:

* I componenti software e i sistemi operativi non più supportati dal fornitore NON **DEVONO** essere usati nell'ambiente. I criteri di supporto DEVONO essere applicati per garantire che i componenti software o i sistemi operativi non supportati vengano rimossi dall'ambiente e che sia necessario un processo per identificare quando i componenti software vanno alla fine del ciclo di vita

**Analisi delle vulnerabilità**  

Poiché gli audit ISO 27001 non valutano in modo specifico questa categoria, è necessario:

* Dimostrare che viene eseguita l'analisi trimestrale delle vulnerabilità interna ed esterna.

* Verificare che la documentazione di supporto sia disponibile per la correzione delle vulnerabilità in base alla classificazione dei rischi e in linea con la specifica come indicato di seguito:
 
 &#x2713; Correggere tutti i problemi di rischio critici e elevati in linea con la classificazione dei rischi per l'analisi interna.
 
 &#x2713; correggere tutti i problemi di rischio critico, elevato e medio in linea con la classificazione dei rischi per l'analisi esterna.
 
 &#x2713; Dimostrare che la correzione viene eseguita in linea con i criteri di correzione della vulnerabilità documentati.

**Firewall - Firewall (o tecnologie equivalenti)**

Poiché gli audit ISO 27001 non valutano in modo specifico questa categoria, è necessario:

* Dimostrare che i firewall sono installati sul limite dell'ambiente nell'ambito.

* Dimostrare che i firewall sono installati tra la rete perimetrale e le reti attendibili.

*   Dimostrare che tutti gli accessi pubblici terminano nella rete perimetrale.

*   Dimostrare che le credenziali amministrative predefinite vengono modificate prima dell'installazione nell'ambiente attivo.

*   Dimostrare che tutto il traffico consentito attraverso i firewall passa attraverso un processo di autorizzazione che comporta la documentazione di tutto il traffico con una giustificazione aziendale.

*   Dimostrare che tutti i firewall sono configurati per eliminare il traffico non definito in modo esplicito.

*   Dimostrare che i firewall supportano solo la crittografia avanzata in tutte le interfacce amministrative non console.

*   Dimostrare che le interfacce amministrative non console del firewall esposte a Internet supportano l'autenticazione a più fattori.

*   Dimostrare che le verifiche delle regole del firewall vengono eseguite almeno ogni 6 mesi

**Firewall - Web Application Firewall (WAF)**  

Verrà fornito un credito aggiuntivo se viene distribuito un WAF per proteggere dalla miriade di minacce e vulnerabilità delle applicazioni Web a cui l'applicazione può essere esposta. Quando è presente un WAF o simile, è necessario:

* Dimostrare che waf è configurato in modalità di difesa attiva o il monitoraggio più con avvisi.

* Dimostrare che waf è configurato per supportare l'offload SSL.

* È configurato in base al set di regole di base OWASP (3.0 o 3.1) per la protezione dalla maggior parte dei tipi di attacco seguenti:

&#x2713; protocollo e problemi di codifica.

&#x2713; inserimento di intestazione, traffico di richieste e suddivisione delle risposte.

&#x2713; attacchi di attraversamento di file e percorsi.

&#x2713; attacchi RFI (Remote File Inclusion).

&#x2713; attacchi di esecuzione remota del codice.

&#x2713; attacchi PHP injection.

&#x2713; attacchi di scripting tra siti.

&#x2713; attacchi SQL injection.

&#x2713; attacchi di correzione della sessione.

**Controllo delle modifiche**

Poiché i controlli ISO 27001 non valutano in modo specifico alcuni elementi dei processi di richiesta di modifica, è necessario:

* Dimostrare che le richieste di modifica hanno i dettagli seguenti:

&#x2713; impatto documentato.

&#x2713; Informazioni dettagliate sui test delle funzionalità da eseguire.

&#x2713; Dettagli di tutte le procedure di back-out.

* Dimostrare che il test delle funzionalità viene eseguito dopo il completamento delle modifiche.

* Dimostrare che le richieste di modifica vengono firmate dopo il test delle funzionalità.

**Gestione account**

Poiché i controlli ISO 27001 non valutano in modo specifico alcuni elementi dei processi di gestione degli account, è necessario:

*   Illustrare come vengono implementati &#x2713;per attenuare gli attacchi di riproduzione (ad esempio MFA, Kerberos).
*   Dimostrare in che modo gli account che non sono stati usati in 3 mesi vengono disabilitati o eliminati.
*   &#x2713; o altre mitigazioni appropriate devono essere configurate per proteggere le credenziali utente. I criteri password minimi seguenti devono essere usati come linee guida:

&#x2713; Lunghezza minima della password di 8 caratteri.

&#x2713; soglia di blocco dell'account non superiore a 10 tentativi.
 
&#x2713; cronologia password di almeno cinque password.
 
&#x2713; Imposizione dell'uso di password complesse.
 
*   Dimostrare che L'autenticazione a più fattori è configurata per tutte le soluzioni di accesso remoto.

*   Dimostrare che la crittografia avanzata è configurata in tutte le soluzioni di accesso remoto.

*   Se la gestione di DNS pubblico non rientra nell'ambiente nell'ambito, tutti gli account utente in grado di apportare modifiche dns devono essere configurati per l'uso dell'autenticazione a più fattori.

**Rilevamento e prevenzione delle intrusioni (FACOLTATIVO)**

Poiché i controlli ISO 27001 non valutano in modo specifico alcuni elementi dei processi idps (Intrusion Detection and Prevention Services), è necessario:

*   IDPS **DEVE** essere distribuito nel perimetro dell'ambiente di supporto.

*   Le firme IDPS **DEVONO** essere mantenute aggiornate entro l'ultimo giorno.

*   IDPS **DEVE** essere configurato per l'ispezione TLS.

*   IDPS **DEVE** essere configurato per TUTTO il traffico in ingresso e in uscita.

*   IDPS **DEVE** essere configurato per l'avviso.

**Registrazione eventi**

Poiché i controlli ISO 27001 non valutano in modo specifico alcuni elementi dei processi di registrazione degli eventi di sicurezza, è necessario:

* Dimostrare che i sistemi pubblici stanno effettuando la registrazione in una soluzione di registrazione centralizzata che non si trova all'interno della rete perimetrale.

* Dimostrare come sia immediatamente disponibile un valore minimo di 30 giorni di dati di registrazione, con 90 giorni di conservazione.

**Revisione (registrazione dei dati)**

Poiché gli audit ISO 27001 non valutano in modo specifico alcuni elementi di questa categoria, è necessario:

*   Dimostrare come vengono condotte le verifiche giornaliere dei log e come vengono identificate eccezioni e anomalie che mostrano come vengono gestite.

**Avvisi**

Poiché gli audit ISO 27001 non valutano in modo specifico alcuni elementi di questa categoria, è necessario:

* Dimostrare in che modo gli eventi di sicurezza sono configurati per attivare avvisi per la valutazione immediata.

* Dimostrare come il personale è disponibile 24 ore su 24, 7 giorni su 7, per rispondere agli avvisi di sicurezza.

**Gestione dei rischi**

Poiché gli audit ISO 27001 non valutano in modo specifico alcuni elementi dei processi di valutazione dei rischi, è necessario:

* Dimostrare che è stato stabilito un processo formale di gestione dei rischi.

**Risposta agli eventi imprevisti**

Poiché i controlli ISO 27001 non valutano in modo specifico alcuni elementi dei processi e dei criteri di risposta agli eventi imprevisti, è necessario:

*   Dimostrare che il piano o la procedura di risposta agli eventi imprevisti include:

&#x2713; procedure di risposta specifiche per i modelli di minaccia previsti.

&#x2713; funzionalità di gestione degli eventi imprevisti allineate a NIST Cybersecurity Framework (Identificare, proteggere, rilevare, rispondere, recuperare).
 
&#x2713; L'IRP copre i sistemi nell'ambito.
 
&#x2713; formazione annuale per il team di risposta agli eventi imprevisti.

## <a name="appendix-d"></a>Appendice D

### <a name="evidence-collection--deltas-for-pci-dss"></a>Raccolta di prove - Delta per PCI DSS

Se hai già raggiunto la conformità PCI DSS, i seguenti differenziali (gap) non interamente coperti da PCI DSS dovranno, almeno, essere esaminati come parte della certificazione Microsoft 365.

> [!NOTE]
> Nell'ambito della valutazione della certificazione Microsoft 365, l'analista della certificazione determinerà se uno dei controlli PCI DSS mappati non è stato incluso nell'ambito della valutazione PCI DSS e può anche decidere di campionare i controlli che sono stati trovati da includere per fornire ulteriore garanzia. Eventuali requisiti mancanti nel PCI DSS dovranno essere inclusi nelle attività di valutazione della certificazione Microsoft 365.

**Protezione da malware - Controllo delle applicazioni**

Se la protezione da malware è in atto tramite l'uso di anti-virus ed è attestata all'interno del rapporto PCI DSS non è necessaria alcuna ulteriore indagine. Se non è presente alcun antivirus, gli analisti di certificazione dovranno identificare e valutare le prove dei meccanismi di controllo delle applicazioni per prevenire la detonazione del malware all'interno dell'ambiente. In questo modo sarà necessario: 

*   Dimostrare come viene eseguita l'approvazione dell'applicazione e verificare che sia stata completata.

*   Dimostrare che esiste un elenco completo di applicazioni approvate con giustificazione aziendale.

*   È disponibile una documentazione di supporto che illustra in dettaglio come il software di controllo dell'applicazione è configurato per soddisfare meccanismi di controllo dell'applicazione specifici (ad esempio, l'elenco di autorizzazioni, la firma del codice e così via).

*   Dimostrare che in tutti i componenti del sistema campionati il controllo dell'applicazione è configurato come documentato.

**Gestione delle patch - Classificazione dei rischi**

Poiché i controlli PCI DSS non valutano in modo specifico questa categoria, è necessario:

* Dimostrare come viene condotta la classificazione dei rischi delle vulnerabilità.

**Analisi delle vulnerabilità**

Poiché i controlli PCI DSS non valutano in modo specifico questa categoria, è necessario:

* Dimostrare che la correzione viene eseguita in linea con i criteri di correzione delle vulnerabilità documentati.

**Firewall - Firewall (o tecnologie equivalenti)**

Poiché i controlli PCI DSS non valutano in modo specifico questa categoria, è necessario:

* Dimostrare che i firewall supportano solo la crittografia avanzata in tutte le interfacce amministrative non console.

* Dimostrare che le interfacce amministrative non console del firewall esposte a Internet supportano l'autenticazione a più fattori.

Verrà fornito un credito aggiuntivo se un Web application firewall (WAF) viene distribuito per proteggere dalla miriade di minacce e vulnerabilità dell'applicazione Web a cui l'applicazione può essere esposta. Quando è presente un WAF o simile, è necessario:

* Dimostrare che waf è configurato in modalità di difesa attiva o il monitoraggio più con avvisi.

* Dimostrare che waf è configurato per supportare l'offload SSL.

* È configurato in base al set di regole di base OWASP (3.0 o 3.1) per la protezione dalla maggior parte dei tipi di attacco seguenti:

&#x2713; protocollo e problemi di codifica.

&#x2713; inserimento di intestazione, traffico di richieste e suddivisione delle risposte.

&#x2713; attacchi di attraversamento di file e percorsi.

&#x2713; attacchi RFI (Remote File Inclusion).

&#x2713; attacchi di esecuzione remota del codice.

&#x2713; attacchi PHP injection.

&#x2713; attacchi di scripting tra siti.

&#x2713; attacchi SQL injection.

&#x2713; attacchi di correzione della sessione.

**Controllo delle modifiche**

Poiché i controlli PCI DSS non valutano in modo specifico alcuni elementi dei processi di richiesta di modifica, è necessario:

* Dimostrare che le richieste di modifica vengono generate prima di essere effettuate negli ambienti di produzione.

* Dimostrare che le modifiche sono autorizzate prima di passare all'ambiente di produzione.

* Dimostrare che il test delle funzionalità viene eseguito dopo il completamento delle modifiche.

* Dimostrare che le richieste di modifica vengono firmate dopo il test delle funzionalità.

**Sviluppo/distribuzione di software sicuro**

Poiché i controlli PCI DSS non accedono in modo specifico ad alcuni elementi dei processi di sviluppo e distribuzione software sicuri; Questa operazione richiede:

* I repository di codice DEVONO essere protetti da MFA.

*   Devono essere applicati controlli di accesso adeguati per proteggere i repository di codice da modifiche di codice dannose.

**Gestione account**

Poiché i controlli PCI DSS non valutano in modo specifico alcuni elementi dei processi di gestione degli account, è necessario:

* Dimostrare come vengono implementati i meccanismi di autorizzazione per attenuare gli attacchi di riproduzione (ad esempio MFA, Kerberos).

* È necessario configurare criteri password complesse o altre mitigazioni appropriate per proteggere le credenziali utente. I criteri password minimi seguenti devono essere usati come linee guida: 

&#x2713; Lunghezza minima della password di 8 caratteri.

&#x2713; soglia di blocco dell'account non superiore a 10 tentativi.

&#x2713; cronologia password di almeno cinque password.

&#x2713; Imposizione dell'uso di password complesse.

* Dimostrare che la crittografia avanzata è configurata in tutte le soluzioni di accesso remoto.

* Se la gestione di DNS pubblico non rientra nell'ambiente nell'ambito, tutti gli account utente in grado di apportare modifiche dns devono essere configurati per l'uso dell'autenticazione a più fattori.

**Rilevamento e prevenzione delle intrusioni (FACOLTATIVO)**

Poiché i controlli PCI DSS non valutano in modo specifico alcuni elementi dei processi idps (Intrusion Detection and Prevention Services), è necessario:

* IDPS DEVE essere configurato per l'ispezione TLS.

*   IDPS DEVE essere configurato per TUTTO il traffico in ingresso e in uscita.

**Gestione dei rischi**

Poiché i controlli PCI DSS non valutano in modo specifico alcuni elementi dei processi di valutazione dei rischi, è necessario:

* Dimostrare che la valutazione del rischio include matrici di impatto e probabilità.

**Risposta agli eventi imprevisti**

Poiché i controlli PCI DSS non valutano in modo specifico alcuni elementi dei processi e dei criteri di risposta agli eventi imprevisti, lo sviluppatore dovrà:

* Illustrare le funzionalità di gestione degli eventi imprevisti allineate a NIST Cybersecurity Framework (Identificare, proteggere, rilevare, rispondere, ripristinare).

## <a name="appendix-e"></a>Appendice E

### <a name="evidence-collection---deltas-for-soc-2"></a>Raccolta di prove - Delta per SOC 2

Se hai già raggiunto la conformità SOC 2, i seguenti delta (gap) non completamente coperti da SOC 2 dovranno essere esaminati come parte della certificazione Microsoft 365.

> [!NOTE]
> Come parte della valutazione della certificazione Microsoft 365, l'analista della certificazione determinerà se uno dei controlli SOC 2 mappati non è stato incluso nell'ambito della valutazione SOC 2 e può anche decidere di campionare i controlli che sono stati trovati per essere inclusi per fornire ulteriore garanzia. Eventuali requisiti mancanti nella valutazione SOC 2 dovranno essere inclusi nell'ambito delle attività di valutazione della certificazione Microsoft 365.

**Protezione da malware - Controllo delle applicazioni**

Se la protezione da malware è in atto tramite l'uso di anti-virus ed è attestata all'interno del report SOC 2 non è necessaria alcuna ulteriore indagine. Se non è presente alcun antivirus, gli analisti di certificazione dovranno identificare e valutare le prove dei meccanismi di controllo delle applicazioni per prevenire la detonazione del malware all'interno dell'ambiente. In questo modo sarà necessario:

* È disponibile una documentazione di supporto che illustra in dettaglio come il software di controllo dell'applicazione è configurato per soddisfare meccanismi di controllo dell'applicazione specifici (ad esempio, l'elenco di autorizzazioni, la firma del codice e così via).

* Dimostrare come viene eseguita l'approvazione dell'applicazione e verificare che sia stata completata.

*   Dimostrare che esiste un elenco completo di applicazioni approvate con giustificazione aziendale.

*   Dimostrare che in tutti i componenti del sistema campionati il controllo dell'applicazione è configurato come documentato.

**Gestione delle patch - Applicazione di patch**

Poiché i controlli SOC 2 non valutano in modo specifico questa categoria, è necessario:

*   Qualsiasi problema basso, medio, alto o critico deve essere patchato all'interno delle normali finestre delle attività di applicazione di patch.

*   I componenti software e i sistemi operativi non più supportati dal fornitore NON DEVONO essere usati nell'ambiente. I criteri di supporto DEVONO essere applicati per garantire che i componenti software o i sistemi operativi non supportati vengano rimossi dall'ambiente e che sia necessario un processo per identificare quando i componenti software terminano il ciclo di vita.

**Firewall - Firewall**

Poiché i controlli SOC 2 non valutano in modo specifico i controlli delle modifiche negli elenchi di controllo di accesso del firewall, è necessario:

* Dimostrare che tutto il traffico consentito attraverso i firewall passa attraverso un processo di autorizzazione che comporta la documentazione di tutto il traffico con una giustificazione aziendale.

* Dimostrare che le verifiche delle regole del firewall vengono eseguite almeno ogni sei mesi.

Verrà fornito credito aggiuntivo se viene distribuito un Web application firewall (WAF) o simile per proteggere dalla miriade di minacce e vulnerabilità dell'applicazione Web a cui l'applicazione può essere esposta. Quando è presente un WAF o simile, è necessario:

* Dimostrare che waf è configurato in modalità di difesa attiva o il monitoraggio più con avvisi.

* Dimostrare che waf è configurato per supportare l'offload SSL.

* È configurato in base al set di regole di base OWASP ((3.0 o 3.1) per la protezione dalla maggior parte dei tipi di attacco seguenti:

&emsp;&#x2713; protocollo e problemi di codifica.

&emsp;&#x2713; iniezione di intestazione, traffico di richieste e divisione delle risposte.

&emsp;&#x2713; attacchi di attraversamento di file e percorsi.

&emsp;&#x2713; attacchi RFI (Remote File Inclusion).

&emsp;&#x2713; attacchi di esecuzione remota del codice.

&emsp;&#x2713; attacchi php injection.

&emsp;&#x2713; attacchi di scripting tra siti.

&emsp;&#x2713; attacchi SQL injection.

&emsp;&#x2713; attacchi di correzione della sessione.

**Controllo delle modifiche**

Poiché i controlli SOC 2 non valutano in modo specifico alcuni elementi dei processi di richiesta di modifica, lo sviluppatore dovrà:

* Dimostrare in che modo gli ambienti di sviluppo/test sono separati dall'ambiente di produzione che applica la separazione dei compiti.

* Dimostrare in che modo i dati in tempo reale non vengono usati negli ambienti di sviluppo/test.

* Dimostrare che il test delle funzionalità viene eseguito dopo il completamento delle modifiche.

* Dimostrare che le richieste di modifica vengono firmate dopo il test delle funzionalità.

**Sviluppo/distribuzione di software sicuro**

Poiché i controlli SOC 2 non accedono in modo specifico ad alcuni elementi dei processi di sviluppo e distribuzione software sicuri; Questa operazione richiede:

*   È NECESSARIO disporre di un processo di sviluppo software stabilito e documentato che copre l'intero ciclo di vita dello sviluppo software.

*   Gli sviluppatori DEVONO sottoporsi al training sicuro del codice software almeno ogni anno.

*   I repository di codice DEVONO essere protetti da MFA.

*   Devono essere applicati controlli di accesso adeguati per proteggere i repository di codice da modifiche di codice dannose.

**Gestione account**

Poiché i controlli SOC2 non valutano in modo specifico alcuni elementi dei processi di gestione degli account, è necessario:

*   Dimostrare come vengono implementati i meccanismi di autorizzazione per attenuare gli attacchi di riproduzione (ad esempio MFA, Kerberos).

*   Dimostrare in che modo gli account che non sono stati usati in 3 mesi vengono disabilitati o eliminati.

*   È necessario configurare criteri password complesse o altre mitigazioni appropriate per proteggere le credenziali utente. I criteri password minimi seguenti devono essere usati come linee guida:

&emsp;&#x2713; Lunghezza minima della password di 8 caratteri.

&emsp;&#x2713; soglia di blocco dell'account non superiore a 10 tentativi.

&emsp;&#x2713; cronologia password di almeno 5 password.

&emsp;&#x2713; Imposizione dell'uso di password complesse

*   Dimostrare che gli account utente univoci vengono rilasciati a tutti gli utenti.

*   Se la gestione di DNS pubblico non rientra nell'ambiente nell'ambito, tutti gli account utente in grado di apportare modifiche dns devono essere configurati per l'uso dell'autenticazione a più fattori.

**Rilevamento e prevenzione delle intrusioni (FACOLTATIVO).**

Poiché i controlli SOC 2 non valutano in modo specifico alcuni elementi dei processi idps (Intrusion Detection and Prevention Services), è necessario:

*   Le firme IDPS DEVONO essere mantenute aggiornate, entro l'ultimo giorno

*   IDPS DEVE essere configurato per l'ispezione TLS

*   IDPS DEVE essere configurato per TUTTO il traffico in ingresso e in uscita

**Registrazione eventi**

Poiché i controlli SOC 2 non valutano in modo specifico alcuni elementi dei processi di registrazione degli eventi di sicurezza, è necessario:

* Dimostrare come, in tutti i componenti di sistema all'interno del set di esempio, il sistema seguente sia configurato per registrare gli eventi seguenti

&emsp;&#x2713; Accesso utente ai componenti di sistema e alle applicazioni.

&emsp;&#x2713; Tutte le azioni eseguite da un utente con privilegi elevati.

&emsp;&#x2713; tentativi di accesso logico non validi.

Dimostrare che gli eventi registrati contengono; come minimo, le informazioni seguenti:

&emsp;&#x2713; utente.

&emsp;&#x2713; tipo di evento.

&emsp;&#x2713; data e ora.

&emsp;&#x2713; indicatore esito positivo/negativo.

&emsp;&#x2713; Etichetta per identificare il sistema interessato.

*   Dimostrare che tutti i componenti di sistema all'interno del set di esempi sono configurati per usare la sincronizzazione dell'ora e che sono uguali ai server ora primari/secondari.

* Dimostrare che i sistemi pubblici stanno effettuando la registrazione in una soluzione di registrazione centralizzata che non si trova all'interno della rete perimetrale.

*   Dimostrare che i sistemi pubblici stanno effettuando la registrazione in una soluzione di registrazione centralizzata che non si trova all'interno della rete perimetrale.

* Dimostrare in che modo la soluzione di registrazione centralizzata è protetta da manomissioni non autorizzate dei dati di registrazione.

* Dimostrare come sia immediatamente disponibile un valore minimo di 30 giorni di dati di registrazione, con 90 giorni o più conservati.

**Gestione dei rischi**

Poiché i controlli SOC2 non valutano in modo specifico alcuni elementi dei processi di valutazione dei rischi, è necessario:

* Dimostrare che una valutazione formale del rischio viene condotta almeno ogni anno.

*Risposta agli eventi imprevisti.*

Poiché i controlli SOC2 non valutano in modo specifico alcuni elementi dei processi e dei criteri di risposta agli eventi imprevisti, è necessario:

* Dimostrare che il piano o la procedura di risposta agli eventi imprevisti include:

&emsp;&#x2713; procedure di risposta specifiche per i modelli di minaccia previsti.

&emsp;&#x2713; processo di comunicazione documentato per garantire una notifica tempestiva delle principali parti interessate (marchi/acquirenti di pagamenti, organismi di regolamentazione, autorità di vigilanza, amministratori, clienti e così via).

## <a name="appendix-f"></a>Appendice F

### <a name="hosting-deployment-types"></a>Hosting dei tipi di distribuzione

Microsoft riconosce che si distribuiranno applicazioni e si archivierà il codice app/componente aggiuntivo all'interno di ambienti di hosting diversi. Le responsabilità complessive di alcuni controlli di sicurezza all'interno della certificazione Microsoft 365 dipenderanno dall'ambiente di hosting usato. L'appendice F esamina i tipi di distribuzione comuni e ne esegue il mapping rispetto ai controlli di sicurezza valutati come parte del processo di valutazione. Sono stati identificati i tipi di distribuzione di hosting seguenti:

|Tipi di hosting  |Descrizione  |
|-----|------|
|**ISV ospitato**|I tipi ospitati ISV possono essere definiti come la posizione in cui si è responsabili dell'infrastruttura usata per supportare l'ambiente app/componente aggiuntivo. Può trovarsi fisicamente all'interno di data center o data center di terze parti con un servizio di co-localizzazione. In definitiva, si dispone della proprietà completa e del controllo amministrativo sull'infrastruttura di supporto e sull'ambiente operativo.|
|**Infrastruttura distribuita come servizio (IaaS)** (https://azure.microsoft.com/overview/what-is-iaas/)|L'infrastruttura distribuita come servizio è un servizio fornito in base al quale l'infrastruttura di supporto fisico viene gestita e gestita per loro conto dal provider di servizi cloud (CSP). In genere, la rete, l'archiviazione, i server fisici e l'infrastruttura di virtualizzazione sono tutte responsabilità del CSP. Il sistema operativo, il middleware, il runtime, i dati e le applicazioni sono responsabilità dell'utente. Anche le funzionalità di firewalling vengono gestite e gestite da terze parti, tuttavia la manutenzione della base di regole del firewall in genere rimane di responsabilità dei consumatori.|
|**Piattaforma distribuita come servizio/serverless (PaaS)** (https://azure.microsoft.com/overview/what-is-paas/)| Con Platform as a Service viene effettuato il provisioning con una piattaforma gestita che presenta un servizio che può essere utilizzato. Non è necessario eseguire funzioni sysadmin perché il sistema operativo e l'infrastruttura di supporto sono gestiti dal CSP. Questo viene in genere usato quando le organizzazioni non vogliono preoccuparsi di presentare un servizio Web e possono invece concentrarsi sulla creazione del codice sorgente dell'applicazione Web e sulla pubblicazione dell'applicazione Web nei servizi Web gestiti dal cloud.  Un altro esempio può essere un servizio di database in cui viene fornita la connettività a un database, tuttavia l'infrastruttura di supporto e l'applicazione di database vengono astratte dal consumer.   **Nota: Serverless e PaaS sono simili, quindi ai fini della certificazione Microsoft 365 Hosting Deployment Type serverless e PasS sono considerati gli stessi**|
|**Ibrido ospitato**|Con il tipo ospitato ibrido, è possibile usare più tipi ospitati per supportare varie parti dell'ambiente di supporto. Questo può essere più il caso in cui le app/componenti aggiuntivi vengono usate in più stack M365. Sebbene la certificazione Microsoft 365 supporti la distribuzione di app/componenti aggiuntivi in più servizi M365, una valutazione dell'intero ambiente di supporto (tra app/componenti aggiuntivi) deve essere valutata in linea con ognuno dei "mapping dei tipi ospitati" applicabili. In alcuni casi, è possibile utilizzare tipi ospitati diversi per un singolo componente aggiuntivo, in cui questa operazione viene eseguita, l'applicabilità dei criteri dovrà comunque seguire i criteri "Mapping di tipi ospitati" tra i vari tipi ospitati.|
|**Hosting condiviso**|L'hosting condiviso è la posizione in cui si ospita l'ambiente all'interno di una piattaforma condivisa da più singoli consumer. La specifica di certificazione Microsoft 365 non è stata scritta per tenere conto di questo problema a causa dell'adozione del cloud, l'hosting condiviso non è comune. Se si ritiene che sia in uso, contattare Microsoft perché sarà necessario creare requisiti aggiuntivi per tenere conto dei rischi aggiuntivi in questo tipo di tipo di hosting.|


## <a name="appendix-g"></a>Appendice G

## <a name="learn-more"></a>Ulteriori informazioni

[Panoramica del programma di conformità delle app di Microsoft 365](~/overview.md)  
[Che cos'è l'attestazione di Microsoft 365 App Publisher?](~/docs/attestation.md)  
[Che cos'è la certificazione Microsoft 365?](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a>Glossario

### <a name="aia"></a>AIA

*Authority Information Access è un descrittore di posizione del servizio usato per trovare il certificato dell'autorità di certificazione emittente.

### <a name="crl"></a>CRL

*L'elenco di revoche di certificati consente a un endpoint SSL (Secure Sockets Layer) di verificare che un certificato ricevuto da un host remoto sia valido e attendibile.

### <a name="cvss-score"></a>Punteggio CVSS

*Common Vulnerability Scoring System è uno standard pubblicato che misura la vulnerabilità e calcola un punteggio numerico in base alla relativa gravità.

### <a name="cvss-patch-management-guidelines"></a>Linee guida per la gestione delle patch cvss

* Critico (9.0 - 10.0)
* Alto (7,0 - 8,9)
* Medio (4.0 - 6.9)
* Basso (0,0 - 3,9)

### <a name="dmz"></a>DMZ

*La zona demilitarizzata è una rete intermedia fisica o logica che interagisce direttamente con reti esterne o non proprietarie mantenendo la rete privata interna dell'host separata e isolata.

### <a name="euii"></a>EUII

*Informazioni personali dell'utente finale*.

### <a name="gdpr"></a>GDPR

*Il regolamento generale sulla protezione dei dati è un regolamento sulla privacy e sulla protezione dei dati dell'Unione europea (UE) per tutti i dati dei cittadini dell'UE, indipendentemente dalla posizione in cui si trova il sito dell'applicazione.

### <a name="hsts"></a>HSTS

*HTTP Strict Transport Security usa un'intestazione di risposta HTTP che indica al Web browser di accedere solo al contenuto tramite HTTPS.  Questo è progettato per proteggere da attacchi di downgrade e cookie hijacking.

### <a name="iec"></a>IEC

*International Electrotechnical Commission.

### <a name="isms"></a>ISMI

*Sistema di gestione della sicurezza delle informazioni.

### <a name="isv"></a>ISV

I fornitori indipendenti di sicurezza sono individui e organizzazioni che sviluppano, commercializzano e vendono software che viene eseguito su piattaforme software e hardware di terze parti.

### <a name="iso-27001"></a>ISO 27001

Un framework di specifica del sistema di gestione della sicurezza delle informazioni per tutti i controlli tecnici in un'organizzazione elabora criteri e procedure di gestione dei rischi.

### <a name="lfi"></a>LFI

*L'inclusione di file locali* consente a un utente malintenzionato di includere file in un server tramite il Web browser.

### <a name="nist"></a>NIST

Il *National Institute of Standards* (NIST), un'agenzia non normativa del Dipartimento del Commercio degli Stati Uniti, fornisce indicazioni per le organizzazioni del settore privato negli Stati Uniti per valutare e approvare la loro capacità di prevenire, rilevare e rispondere agli attacchi informatici.

### <a name="non-significant-changes"></a>Modifiche non significative

* Correzioni di bug minori.
* Miglioramenti delle prestazioni minori.
* Sistemi operativi/librerie/patch dell'applicazione client e server.

### <a name="ocsp"></a>OCSP

*Online Certificate Status Protocol* viene usato per controllare lo stato di revoca dei certificati digitali X.509.

### <a name="oii"></a>OII

*Informazioni identificabili sull'organizzazione*.

### <a name="owasp"></a>OWASP

*Aprire Progetto di sicurezza dell'applicazione Web*.

### <a name="pci-dss"></a>PCI DSS

*Payment Card Industry Data Security Standard*, un'organizzazione che mantiene gli standard per la sicurezza dei dati dei titolari di carte in tutto il mondo.

### <a name="pen-testing"></a>Test della penna

*Il test di penetrazione* è un metodo per testare un'app Web simulando attacchi dannosi per individuare vulnerabilità di sicurezza che un utente malintenzionato potrebbe sfruttare.

### <a name="saml"></a>SAML

*Security Assertion Markup Language* è uno standard aperto per lo scambio di dati di autenticazione e autorizzazione tra l'utente, il provider di identità e il provider di servizi.

### <a name="sensitive-data"></a>Dati sensibili

* Dati di controllo di accesso.
* Contenuto del cliente.
* Informazioni sull'identità dell'utente finale.
* Dati di supporto.
* Dati personali pubblici.
* Informazioni pseudonime dell'utente finale.

### <a name="significant-changes"></a>Modifiche significative

* Rilocazione dell'ambiente di hosting.
* Aggiornamenti principali all'infrastruttura di supporto; ad esempio l'implementazione di un nuovo firewall, gli aggiornamenti principali ai servizi front-facing e così via.
* Aggiunta di funzionalità e /o estensioni all'app.
* Aggiornamenti all'app che acquisisce dati sensibili aggiuntivi.
* Modifiche ai flussi di dati o ai modelli di autorizzazione dell'app
* Aggiunta di endpoint API o funzioni dell'endpoint API.

### <a name="soc-2"></a>SOC 2

*Service Organization Control 2*, una procedura di controllo tecnico costituita da cinque principi del servizio trust per garantire che i provider di servizi gestivano in modo sicuro i dati e la privacy per i client di un'organizzazione.

### <a name="ssl"></a>SSL

*Secure Sockets Layer*.

### <a name="tls"></a>TLS

*Transport Layer Security*.
