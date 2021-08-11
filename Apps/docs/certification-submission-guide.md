---
ms.author: oromalle
title: Microsoft 365 Guida all'invio della certificazione
author: orionomalley
description: Microsoft 365 Visualizzazione granulare della Guida all'invio della certificazione
keywords: team di certificazione delle app Microsoft 365 sicurezza m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 31c974a20e17daa0436826432429bd664a9a1f59dee6b351b587ae0b30cc6bac
ms.sourcegitcommit: 717ca5bc90981def8914c4cd1fad992f67be4d5b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/06/2021
ms.locfileid: "54750541"
---
# <a name="microsoft-365-certification-submission-guide"></a>Microsoft 365 Guida all'invio della certificazione

**Contenuto dell'articolo:**
- [Introduzione](#introduction)
- [Prerequisiti](#prerequisites) 
- [Microsoft 365 Aggiornamenti delle specifiche di certificazione](#microsoft-365-certification-specification-updates)
- [Ambito di certificazione](#certification-scope)
- [Processo di certificazione](#certification-process)
- [Invio documento iniziale](#initial-document-submission) 
- [Attività di raccolta e valutazione delle prove](#evidence-collection-and-assessment-activities)
- [Criteri di certificazione](#app-certification-criteria)
- [Sicurezza applicazioni](#application-security)
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

Parte del programma conformità app Microsoft 365, la certificazione Microsoft 365 offre alle organizzazioni aziendali la certezza e la sicurezza che i dati e la privacy siano adeguatamente protetti e protetti durante l'integrazione di app/componenti aggiuntivi per sviluppatori di terze parti nella piattaforma Microsoft 365. Le applicazioni e i componenti aggiuntivi che superano la convalida verranno Microsoft 365 **certificati** in tutto Microsoft 365 ecosistema. 

Partecipando al programma di certificazione Microsoft 365, l'utente accetta queste condizioni supplementari e si conforma a qualsiasi documentazione di accompagnamento applicabile alla partecipazione al programma di certificazione Microsoft 365 con Microsoft Corporation ("Microsoft", "microsoft", "noi" o "nostro"). L'utente rappresenta e garantisce a Microsoft di avere l'autorità di accettare queste condizioni supplementari di certificazione Microsoft 365 per conto di se stessi, di una società e/o di un'altra entità, se applicabile. Microsoft può modificare, modificare o terminare questi termini supplementari in qualsiasi momento. La partecipazione continua al programma di Microsoft 365 dopo qualsiasi modifica o modifica significa che l'utente accetta le nuove condizioni supplementari. Se non accetti i nuovi termini supplementari o termini questi termini supplementari, devi smettere di partecipare al programma di Microsoft 365 Certification.

Questo documento è destinato agli ISV (Independent Software Vendor) per fornire informazioni sul processo di certificazione Microsoft 365, prerequisiti per avviare il processo e dettagli di controlli di sicurezza specifici che devono essere installati.  Informazioni generali sul programma Microsoft 365 conformità app sono disponibili nella pagina Microsoft 365 programma conformità [app](https://docs.microsoft.com/microsoft-365-app-certification/overview). 

> [!IMPORTANT]
> Attualmente, Microsoft 365 certificazione è applicabile a tutti:
>* Microsoft Teams applicazioni (schede, bot e così via) .
>* App/componenti aggiuntivi di Sharepoint
>* Office Componenti aggiuntivi (Word, Excel, PowerPoint, Outlook, Project, OneNote)
>* WebApps

## <a name="prerequisites"></a>Prerequisiti

### <a name="publisher-attestation"></a>Attestazione dell'autore

Prima di essere insignito del Microsoft 365 di certificazione, devi aver completato Publisher attestazione. Tuttavia, è possibile avviare il Microsoft 365 di certificazione prima di completare Publisher attestazione.  

### <a name="read-the-microsoft-365-certification-specification"></a>Leggere la specifica Microsoft 365 di certificazione

Microsoft consiglia a tutti gli ISV (Independent Software Vendor) di leggere questa specifica di certificazione Microsoft 365 nella sua interezza per garantire che tutti i controlli applicabili vengano soddisfatti dall'ambiente nell'ambito e dall'app/componente aggiuntivo. In questo modo si garantisce un processo di valutazione uniforme.

## <a name="microsoft-365-certification-specification-updates"></a>Microsoft 365 Aggiornamenti delle specifiche di certificazione 

Gli aggiornamenti alla specifica Microsoft 365 certificazioni sono previsti circa ogni sei-dodici mesi. Questi aggiornamenti potrebbero introdurre nuovi domini di sicurezza di destinazione e/o controlli di sicurezza. Gli aggiornamenti si baseranno sul feedback degli sviluppatori, sulle modifiche al panorama delle minacce e per aumentare la base di sicurezza del programma durante la maturazione. 

Gli ISV che hanno già avviato la valutazione della certificazione Microsoft 365 possono continuare la valutazione con la versione della specifica di certificazione Microsoft 365 valida al momento dell'avvio della valutazione. Tutti i nuovi invii, inclusa la ricertificazione annuale, devono essere valutati rispetto alla versione pubblicata.

> [!NOTE]
> Non è necessario rispettare tutti i controlli contenuti in questa specifica Microsoft 365 certificazione per ottenere una certificazione. Tuttavia, il superamento delle soglie (che non verranno divulgate) è in atto per ognuno dei domini di sicurezza descritti in questa specifica Microsoft 365 Certification Specification. Alcuni controlli verranno classificati come "**Hard Fail**", il che significa che la mancanza di questi controlli di sicurezza comporta una valutazione non riuscita. 

## <a name="certification-scope"></a>Ambito di certificazione

L'ambiente nell'ambito è l'ambiente che supporta la distribuzione del codice dell'app/componente aggiuntivo e supporta qualsiasi sistema **back-end** con cui l'app o il componente aggiuntivo potrebbe comunicare. Verranno inclusi anche altri ambienti connessi all'ambito, a meno che non sia in atto una segmentazione adeguata e gli ambienti connessi non possono influire sulla sicurezza dell'ambiente nell'ambito. Tutti gli ambienti di ripristino di emergenza dovranno inoltre essere inclusi nell'ambito della valutazione, in quanto tali ambienti sarebbero necessari per soddisfare il servizio in caso di problemi nell'ambiente principale.  Il termine **componenti di sistema nell'ambito** fa riferimento a TUTTI i dispositivi e i sistemi   utilizzati  nell'ambiente nell'ambito. I componenti nell'ambito includono, ma non sono limitati a:
* Le applicazioni Web.
* Server.
* Firewall (o equivalenti).
* Interruttori.
* Servizi di bilanciamento del carico.
* Infrastruttura virtuale.
* Portali di gestione Web provider cloud 

> [!IMPORTANT]
> L'ambiente nell'ambito deve avere una DMZ e l'ambiente di supporto dell'app/componente aggiuntivo deve essere segmentato dai sistemi aziendali interni e dagli ambienti aziendali limitando così l'ambito delle attività di valutazione solo ai sistemi nell'ambito. Gli analisti della certificazione convalidano le tecniche di segmentazione durante la valutazione e rivedono i report di test di penetrazione che dovrebbero includere test per convalidare l'efficacia di qualsiasi tecnica di segmentazione in uso.

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a>Infrastruttura come servizio (IaaS), Piattaforma come servizio (PaaS) e Software as a Service (SaaS) 
Se IaaS e/o PaaS vengono utilizzati per supportare l'infrastruttura della distribuzione del codice dell'applicazione o del componente aggiuntivo in fase di revisione, il provider della piattaforma Cloud sarà responsabile di alcuni dei controlli di sicurezza valutati durante tutto il processo di certificazione. Pertanto, gli analisti della certificazione dovranno disporre di una verifica esterna indipendente delle procedure consigliate per la sicurezza da parte del provider della piattaforma Cloud tramite report di conformità esterni come i report [PCI DSS](bookmark://pci-dss)   Attestation of Compliance (AOC), ISO27001 o [SOC 2](bookmark://soc-2)   Type II. 

L'Appendice F fornisce informazioni dettagliate sui controlli di sicurezza che saranno probabilmente applicabili in base ai tipi di distribuzione seguenti e in base al fatto che l'app/componente aggiuntivo esfiltra o meno i dati M365: 
* ISV ospitato 
* IaaS ospitato 
* PaaS/Serverless Hosted 
* Hybrid Hosted 
* Shared Hosted 

Quando viene distribuito IaaS o PaaS, è necessario fornire la prova dell'ambiente ospitato all'interno di questi tipi di distribuzione.

### <a name="sampling"></a>Campionamento

Le richieste di prove a supporto della valutazione della certificazione devono essere basate su un campione dei componenti di sistema nell'ambito in considerazione dei diversi sistemi operativi, della funzione principale del dispositivo e dei diversi tipi di dispositivi. All'inizio del processo di certificazione verrà selezionato un campione appropriato. La tabella seguente deve essere utilizzata come guida sulle dimensioni del campione:

|Dimensioni della popolazione              | Esempio                  |
|---------------------------- |-------------------------|
|<5|1|
|>5 & <10|2|
|>9 & <25|3 |
|>24|4 |

> [!NOTE]
>Se vengono identificate discrepanze tra i dispositivi inclusi nel campione iniziale, le dimensioni del campione possono essere aumentate durante la valutazione. 

## <a name="certification-process"></a>Processo di certificazione

Prima di avviare il processo di certificazione, dovrai aver completato correttamente l'attestazione Publisher certificato. Le risposte di attestazione verranno utilizzate a supporto del processo Microsoft 365 certificazione e procederanno come segue:

## <a name="certification-process"></a>Processo di certificazione

Prima di iniziare il processo di certificazione, è necessario aver completato la Publisher attestazione. Dopo l'approvazione dell'attestazione dell'editore, riceverai un messaggio di posta elettronica introduttivo che ti invita a partecipare Microsoft 365 certificazione.

### <a name="preparation"></a>Preparazione
1. Passare al Centro per i partner ed esaminare la documentazione [Publisher di attestazione]( https://docs.microsoft.com/microsoft-365-app-certification/docs/attestation) completata. Se necessario, è possibile modificare e aggiornare le risposte. Tuttavia, in questo caso, sarà necessario inviare di nuovo la documentazione di attestazione per l'approvazione. Se l'invio è precedente a tre mesi, ti verrà richiesto di inviare di nuovo l'attestazione Publisher per la revisione e la convalida. 
1. Leggere attentamente la guida Microsoft 365 per l'invio [della certificazione](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide) per comprendere cosa ti sarà richiesto. Assicurati di essere in grado di soddisfare i requisiti [di]( https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#app-certification-criteria) controllo specificati nella Guida all'invio Microsoft 365 certificazione.
1. All'interno del centro per i partner fai clic su "Avvia certificazione". In questo modo verrà visualizzato il portale di invio dei documenti iniziale. Inviare [l'invio del documento iniziale](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#initial-document-submission). Questo ci aiuterà a determinare cosa è nell'ambito della valutazione in base al modo in cui l'app è progettata e gestisce i dati dei clienti. Controlla spesso questa pagina per vedere se l'invio è stato accettato.

>[!NOTE]
>Per tutte le app di Office puoi fare riferimento alla nostra [guida Office Apps User Guide](https://docs.microsoft.com/microsoft-365-app-certification/docs/userguide). Per tutte le WebApp puoi fare riferimento alla nostra [Guida per l'utente dell'app SaaS.](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/saasuserguide)

### <a name="assessment"></a>Valutazione
1. Dopo l'accettazione dell'invio del documento iniziale, il set di controlli di sicurezza necessari per la tua app verrà visualizzato automaticamente nel portale. Verrà quindi richiesto di inviare la prova per ogni controllo dimostrando che il controllo è in atto. Tieni presente che ti verranno dati **60** giorni per inviare tutte le prove. Un analista rivedrà le prove e approverà il controllo o richiederà prove nuove o aggiuntive. Controlla spesso questa pagina per vedere se la tua prova è stata accettata.
### <a name="certification"></a>Certificazione
1. Dopo che l'invio è stato convalidato da un analista, ti verrà notificata la decisione di certificazione. Le app con una certificazione riceveranno un badge nella loro applicazione all'interno **delle pagine AppSource** e **Documenti Microsoft.** Per informazioni sui vantaggi completi della certificazione, [vedere](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide#program-benefits).

## <a name="review-and-re-certification"></a>Revisione e ricertificazione
Nel caso in cui l'applicazione subisca [modifiche](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#significant-changes) significative in qualsiasi momento, ti verrà richiesto di inviarci una notifica.

Sarà inoltre necessario eseguire la ricertificazione su base annuale. Ciò richiederà la riconvalida dei controlli nell'ambito rispetto all'ambiente corrente. Questo processo può iniziare fino a 90 giorni prima della scadenza della certificazione. La certificazione esistente non scadrà durante il periodo di ricertificazione. La nuova certificazione in tutti i programmi scade nell'anniversario di un anno della certificazione Microsoft 365.

Se la certificazione non viene rinnovata prima della data di scadenza, lo stato della certificazione delle app verrà revocato. Tutti i messaggi non consentiti, le icone e il marchio di certificazione associato verranno rimossi dall'app e ti sarà proibito pubblicizzare l'app come Microsoft 365 Certified.


> [!IMPORTANT]
> **Intervallo di tempo per l'invio:** È previsto che in media il processo di valutazione debba richiedere 30 giorni, purché tu sia in grado di controllare spesso lo stato dell'invio e rispondere a commenti e richieste di prove supplementari in modo appropriato. All'avvio del processo di certificazione, è consentito un massimo di 60 giorni per completare la valutazione. Se tutti gli invii non sono stati completati entro il periodo di tempo di 60 giorni, all'invio verrà generato un errore e il processo deve ricominciare. Questi risultati non saranno resi pubblici.


## <a name="initial-document-submission"></a>Invio documento iniziale

L'invio del documento iniziale aiuterà gli analisti della certificazione a eseguire l'ambito e a determinare quali saranno gli ambiti per la valutazione. Dopo di che sarà necessario inviare la documentazione di supporto e le prove utilizzate per eseguire la valutazione. L'invio iniziale deve includere le informazioni specificate di seguito:

| **Panoramica &nbsp; della documentazione**     |   **Dettagli della documentazione**  |
| -------------------------| -----------------------------|
|**Descrizione app/componente aggiuntivo** | Descrizione dello scopo e della funzionalità dell'app/componente aggiuntivo. Questo dovrebbe fornire all'analista di certificazione una buona comprensione del funzionamento dell'app/componente aggiuntivo e dell'uso previsto.
|**Report test di penetrazione** |Report di test di penetrazione completato negli ultimi 12 mesi. Questo report deve includere l'ambiente che supporta la distribuzione dell'app/aggiunta insieme a qualsiasi altro ambiente che supporti il funzionamento dell'app/componente aggiuntivo. **Nota:** se non fai test di penetrazione annuali, puoi scegliere di farlo attraverso il processo di certificazione.|
|**Diagrammi dell'architettura**|Diagramma dell'architettura logica che rappresenta una panoramica generale dell'infrastruttura di supporto dell'app o del componente aggiuntivo. Deve includere tutti **gli ambienti** di hosting e l'infrastruttura di supporto che supporta l'app/componente aggiuntivo. Questo diagramma DEVE illustrare tutti i diversi componenti di sistema di supporto all'interno dell'ambiente per aiutare gli analisti della certificazione a comprendere i sistemi nell'ambito e a determinare il campionamento. Indicare anche il tipo di ambiente di hosting utilizzato. ISV ospitato, IaaS, PaaS o ibrido. **Nota:** Se viene utilizzato SaaS, indicare i vari servizi SaaS utilizzati per fornire i servizi di supporto all'interno dell'ambiente.|
|**Public Footprint** | Descrizione **dettagliata di** tutti gli indirizzi IP pubblici e gli URL utilizzati dall'infrastruttura di supporto. Deve includere l'intervallo IP instradabile completo allocato all'ambiente, a meno che non sia stata implementata una segmentazione adeguata per suddividere l'intervallo in uso (sarà necessaria una prova adeguata della segmentazione)|
|**Diagrammi del flusso di dati** |Flow diagrammi che illustrano in dettaglio quanto segue:
||&#x2713; flussi di dati M365 da e verso l'app /componente aggiuntivo (inclusi [EUII](#euii) e [OII).](#oii)|
||&#x2713; flussi di dati M365 all'interno dell'infrastruttura di supporto (se applicabile)|
||&#x2713; Diagrammi che evidenziano dove e quali dati sono archiviati, come i dati vengono passati a terze parti esterne (inclusi i dettagli di quali terze parti) e come i dati vengono protetti in transito su reti aperte/pubbliche e in pausa.|
|**Dettagli endpoint API**| Elenco completo di tutti gli endpoint API usati dalla tua app. Per comprendere meglio l'ambito dell'ambiente, fornisci i percorsi degli endpoint API all'interno dell'ambiente.                                
|**Autorizzazioni API Microsoft**| Fornire la  documentazione in cui vengono fornite informazioni dettagliate su TUTTE le API Microsoft usate insieme alle autorizzazioni richieste per il funzionamento dell'app/componente aggiuntivo insieme a una giustificazione per le autorizzazioni richieste|
|**Tipi di archiviazione dati** |Archiviazione e gestione dei dati che descrivono:|
||&#x2713; in che misura i clienti M365 Data [EUII](#euii) e [OII](#oii) vengono ricevuti e archiviati|
||&#x2713; Periodo di conservazione dei dati.|
||&#x2713; perché viene acquisito il cliente M365 Data.|
||&#x2713; dove vengono archiviati i dati M365 del cliente (devono essere inclusi nei diagrammi del flusso di dati forniti in precedenza).|
|**Conferma di conformità**|Documentazione di supporto per i framework di sicurezza esterni inclusi nell'invio Publisher attestazione o da considerare quando si esaminano Microsoft 365 controlli di certificazione. Attualmente sono supportati i tre elementi seguenti:|
||&#x2713; attestazione di conformità [PCI DSS](#pci-dss) (AOC).|
||&#x2713; report [SOC 2](#soc-2) tipo I/Type II.|
||&#x2713; [ISMS](#isms)  /  [IEC](#iec) - 1S0/IEC 27001 Statement of Applicability (SoA) e Certificazione.|
|**Dipendenze Web**|Documentazione che elenca tutte le dipendenze usate dall'app o dal componente aggiuntivo con le versioni correnti in esecuzione.|
|**Inventario software**|Un inventario software aggiornato che include tutto il software utilizzato nell'ambiente nell'ambito insieme alle versioni.|
|**Inventario hardware**| Un inventario hardware aggiornato utilizzato dall'infrastruttura di supporto. Verrà usato per facilitare il campionamento durante l'esecuzione della fase di valutazione. Se l'ambiente include PaaS, fornire dettagli sui servizi utilizzati.|

## <a name="evidence-collection-and-assessment-activities"></a>Attività di raccolta e valutazione delle prove

Gli analisti della certificazione dovranno esaminare le prove in tutti i componenti di sistema all'interno del set di campioni definito. I tipi di prove necessari per supportare il processo di valutazione includono uno o tutti gli elementi seguenti:

**Raccolta di prove**

* Documentazione iniziale, evidenziata nella [sezione Invio iniziale documentazione](#initial-document-submission) sopra riportata 
* Documenti dei criteri 
* Elaborare documenti 
* Impostazioni di configurazione del sistema 
* Modificare i ticket 
* Modificare i record di controllo 
* Report di sistema

Verranno utilizzati diversi metodi per raccogliere le prove necessarie per completare il processo di valutazione.  Questa raccolta di prove può essere sotto forma di: 
* Documenti 
* Screenshot 
* Interviste 
* Screenharing 

Le tecniche di raccolta delle prove utilizzate verranno determinate durante il processo di valutazione. 

**Attività di valutazione**

Gli analisti della certificazione esamineranno le prove fornite per determinare se sono stati soddisfatti in modo adeguato i controlli in questa Microsoft 365 Certification Specification. 

Se possibile e per ridurre il tempo necessario per completare la valutazione, [](#initial-document-submission)una o tutta la documentazione dettagliata nell'invio della documentazione iniziale deve essere fornita   in anticipo.

Gli analisti della certificazione esaminino innanzitutto le prove fornite dall'invio iniziale della documentazione e le informazioni sull'attestazione di Publisher per identificare le linee di indagine appropriate, le dimensioni di campionamento e la necessità di ottenere ulteriori prove come descritto in precedenza.  Gli analisti della certificazione analizzeranno tutte le informazioni raccolte per trarre conclusioni su come e se si stanno incontrando i controlli all'interno di Microsoft 365 Certification Specification. 

## <a name="app-certification-criteria"></a>Criteri di certificazione app

L'app, l'infrastruttura di supporto e la documentazione di supporto verranno valutati nei domini di sicurezza seguenti:

1. [**Sicurezza applicazioni**](#application-security)
1. [**Sicurezza operativa / Distribuzione sicura**](#operational-security)
1. [**Sicurezza e privacy per la gestione dei dati**](#data-handling-security-and-privacy)

Ognuno di questi domini di sicurezza include controlli chiave specifici che includono uno o più requisiti specifici che verranno valutati nell'ambito del processo di valutazione. Per garantire che la certificazione Microsoft 365 sia inclusiva per gli sviluppatori di tutte le dimensioni, ogni dominio di sicurezza viene valutato utilizzando un sistema di punteggio per determinare un punteggio complessivo da ognuno dei domini. I punteggi per ognuno dei controlli di certificazione Microsoft 365 vengono allocati tra 1 (basso) e 3 (alto) in base al rischio percepito che tale controllo non venga soddisfatto. Ogni dominio di sicurezza avrà un segno percentuale minimo da considerarsi un pass. Alcuni elementi di questa specifica includono alcuni criteri di errore automatici:

- Autorizzazioni API che non segue il principio dei privilegi minimi (PoLP).  
- Nessun rapporto sui test di penetrazione quando è necessario.
- Nessuna difesa antimalware
- L'autenticazione a più fattori non viene utilizzata per proteggere l'accesso amministrativo.  
- Nessun processo di applicazione di patch.  
- Nessuna informativa sulla privacy [gdpr](#gdpr) adatta.  

## <a name="application-security"></a>Sicurezza applicazioni

Il dominio di sicurezza dell'applicazione si concentra sulle tre aree seguenti: 
* Convalida delle autorizzazioni GraphAPI 
* Controlli di connettività esterna
* Test di sicurezza delle applicazioni 

### <a name="graphapi-permission-validation"></a>Convalida delle autorizzazioni GraphAPI

La convalida delle autorizzazioni GraphAPI viene eseguita per convalidare l'app o il componente aggiuntivo non richiede autorizzazioni troppo permissive. Questa operazione viene eseguita controllando manualmente le autorizzazioni richieste. Gli analisti della certificazione interseranno questi controlli rispetto all'invio di attestazione Publisher e valuteranno il livello di accesso richiesto per garantire che vengano soddisfatte le procedure di "privilegio minimo". Se gli analisti della certificazione ritengono che queste procedure di "privilegio minimo" non vengano soddisfatte, gli analisti della certificazione avranno una discussione aperta con l'utente per convalidare la giustificazione aziendale per le autorizzazioni richieste. Eventuali discrepanze rispetto all'Publisher di attestazione trovata durante questa revisione riceveranno anche un feedback in modo da poter aggiornare Publisher'attestazione. 

### <a name="external-connectivity-checks"></a>Controlli di connettività esterna

Come parte della valutazione, un analista eseguirà una leggera analisi delle funzionalità delle applicazioni per identificare le connessioni esterne a M365.  Tutte le connessioni non identificate come Microsoft o le connessioni dirette al servizio verranno contrassegnate e discusse durante la valutazione.

### <a name="application-security-testing"></a>Test di sicurezza delle applicazioni

Un'adeguata revisione dei rischi associati all'app/componente aggiuntivo e all'ambiente di supporto è essenziale per garantire ai clienti la sicurezza dell'app/componente aggiuntivo. I test di sicurezza delle applicazioni sotto forma di test di penetrazione devono essere eseguiti se l'applicazione dispone di connettività a qualsiasi servizio non pubblicato da Microsoft. Se l'app funziona autonomamente senza connettività a qualsiasi servizio o back-end non Microsoft, non è necessario eseguire test di penetrazione.


**Ambito di test di penetrazione**

Le attività  di test di penetrazione DEVONO includere l'ambiente che supporta la distribuzione dell'app/componente aggiuntivo (ad esempio, in cui è ospitato il codice dell'app/componente aggiuntivo che in genere sarà la risorsa all'interno del file manifesto) insieme a qualsiasi ambiente aggiuntivo che supporti il funzionamento dell'app/componente aggiuntivo (ad esempio, se l'app/componente aggiuntivo parla con altre applicazioni Web al di fuori di Microsoft 365).  Quando si definisce l'ambito, è necessario fare attenzione per garantire che tutti i sistemi o gli ambienti "connessi" che possono influire sulla sicurezza dell'ambiente nell'ambito siano inclusi anche in tutte le attività di test di penetrazione. 

Se vengono utilizzate tecniche per segmentare gli ambienti nell'ambito da altri ambienti, le attività di test di penetrazione DEVONO convalidare l'efficacia di queste tecniche di segmentazione. Questo deve essere descritto nel report di test di penetrazione. 

I report di test di penetrazione verranno esaminati per **** verificare che non vi siano vulnerabilità che soddisfino i criteri di errore automatico seguenti descritti nei controlli seguenti.
 
**Requisiti per i test di penetrazione**

||**Controlli di test di penetrazione**|
| -------------------------|-----------------------------|
|**Criteri generali**| **Controlli**|
|| I test di  penetrazione delle applicazioni e dell'infrastruttura devono essere eseguiti ogni anno (ogni 12 mesi) e condotti da una società indipendente affidabile. |
|| La correzione delle vulnerabilità critiche e  ad alto rischio identificate deve essere completata entro un mese dalla conclusione del test di penetrazione o prima a seconda del processo documentato di applicazione delle patch. |
|| Footprint esterno completo (indirizzi IP, URL, endpoint API e così via) DEVE essere incluso nell'ambito dei test di penetrazione e deve essere documentato nel report dei test di penetrazione. |
|| I test di penetrazione delle applicazioni Web DEVONO includere tutte le classi di vulnerabilità; ad esempio, la più attuale OWASP Top 10 o SANS Top 25 CWE. |
|| Non è necessario rieseguire la verifica delle vulnerabilità identificate da parte della società di test di  penetrazione. La correzione e l'autovalutazione sono tuttavia sufficienti, tuttavia, è necessario fornire prove adeguate per dimostrare una correzione sufficiente durante la valutazione.|
|**Criteri di errore automatico:**|**Controlli**|
|| Presenza di un sistema operativo non supportato. |
|| Presenza di account amministrativi predefiniti, enumerabili o intuibili.|
|| Presenza di rischi SQL'iniezione.|
|| Presenza di cross-site scripting.|
|| Presenza di vulnerabilità di attraversamento della directory (percorso file).|
|| Presenza di vulnerabilità HTTP, ad esempio suddivisione delle risposte dell'intestazione, contrabbando di richieste e attacchi Desync.|
|| Presenza della divulgazione del codice sorgente (incluso [LFI](#lfi)).|
|| Qualsiasi punteggio critico o elevato, come definito dalle linee guida per la gestione delle patch CVSS.|
|| Qualsiasi vulnerabilità tecnica significativa che può essere facilmente sfruttata per compromettere una grande quantità di EUII o OUI.|






> [!IMPORTANT]
>I report devono essere in grado di garantire che sia possibile dimostrare tutto ciò che è descritto nella sezione Application Security Test Specification.


**Requisiti e costi dei test di penetrazione**

Per gli ISV che attualmente non esercitino test di penetrazione, i test di penetrazione sono inclusi nella Microsoft 365 certificazioni. Microsoft organizza e copre il costo di un test di penetrazione per un massimo di 12 giorni di test manuale. I costi dei test di penetrazione vengono calcolati in base al numero di giorni necessari per testare l'ambiente. Tutte le spese che superano i 12 giorni di test saranno di responsabilità dell'ISV. L'ISV sarà anche responsabile della dimostrazione che le vulnerabilità identificate nel test di penetrazione sono state corretti prima del conferimento di una certificazione, ma non è necessario produrre un report pulito.

Una volta organizzato un test di penetrazione, l'ISV è responsabile delle tariffe associate alla riprogrammazione e alle cancellazioni nel modo seguente:

| **Ripianificazione della scala cronologica delle commissioni** | **Proporzionale da pagare** |
|------------------|------------------------|
| La richiesta di ri-pianificazione ha ricevuto più di 30 giorni prima della data di inizio programmata. | 0% da pagare |
| Richiesta di ri-pianificazione ricevuta da 8 a 30 giorni prima della data di inizio pianificata. | 25% da pagare |
| Ri-pianificare la richiesta ricevuta entro 2-7 giorni prima della data di inizio programmata con una data di prenotazione fissa.| 50% da pagare |
| Richiesta di ri-pianificazione ricevuta meno di 2 giorni prima della data di inizio. | 100% da pagare |

| **Scala cronologica della commissione di annullamento** | **Proporzionale da pagare** |
|------------------|------------------------|
| La richiesta di annullamento ha ricevuto più di 30 giorni prima della data di inizio programmata. | 25% da pagare |
| La richiesta di annullamento ha ricevuto da 8 a 30 giorni prima della data di inizio programmata. | 50% da pagare |
| Richiesta di annullamento ricevuta entro 7 giorni prima della data di inizio programmata. | 90% da pagare |

## <a name="operational-security"></a>Sicurezza operativa

Questo dominio misura l'allineamento dell'infrastruttura di supporto e dei processi di distribuzione dell'app con le procedure consigliate per la sicurezza.

### <a name="controls"></a>Controlli

|**Famiglia di controlli**| **Controlli**|
| ------------------------|------------------------------ |
| **Protezione antimalware**|Fornire la documentazione sui criteri che regola le procedure e le procedure antivirus.|
||Fornire prove dimostrabili che il software antivirus è in esecuzione in tutti i componenti di sistema campionati.|
||Fornire prove dimostrabili che le firme antivirus sono aggiornate in tutti gli ambienti (entro 1 giorno).|
||Fornire prove dimostrabili che l'antivirus è configurato per eseguire l'analisi all'accesso o periodica in tutti i componenti di sistema campionati. Nota: se l'analisi all'accesso non è abilitata, è necessario che sia abilitato almeno l'analisi e l'avviso giornalieri.|
||Fornire prove dimostrabili che l'antivirus è configurato per bloccare automaticamente il malware o la quarantena e avvisare tutti i componenti di sistema campionati.|
|**Controlli delle applicazioni:** obbligatori solo se non viene utilizzato il tradizionale antimalware|Fornire prove dimostrabili che le applicazioni vengono approvate prima della distribuzione.|
||Fornire prove dimostrabili dell'esistenza e della manutenzione di un elenco completo delle applicazioni approvate con giustificazione aziendale.|
||Fornire documentazione di supporto in cui viene descritto in dettaglio che il software di controllo delle applicazioni è configurato per soddisfare specifici meccanismi di controllo delle applicazioni. (Esempio: Presentazione consentita: sample1, sample3, firma del codice)|
||Fornire prove dimostrabili che il controllo dell'applicazione è configurato come documentato da tutti i componenti di sistema campionati.|
|**Gestione delle patch - Classificazione dei rischi**| Documentazione sui criteri di fornitura che regola il modo in cui vengono identificate le nuove vulnerabilità di sicurezza e viene assegnato un punteggio di rischio.|
||Fornire prove di come vengono identificate le nuove vulnerabilità della sicurezza.|
||Fornire prove che dimostrano che a tutte le vulnerabilità viene assegnata una classificazione dei rischi una volta identificate.|
|**Patch Managmeent - Applicazione di patch**|Fornire la documentazione dei criteri per l'applicazione di patch ai componenti di sistema nell'ambito che includono un intervallo di tempo minimo adeguato per l'applicazione di patch per vulnerabilità critiche, ad alto e medio rischio; e rimozione delle autorizzazioni di eventuali sistemi operativi e software non supportati.|
||Fornire prove dimostrabili che tutti i componenti di sistema campionati vengono patchati.|
||Fornire prove dimostrabili che i sistemi operativi e i componenti software non supportati non vengono utilizzati nell'ambiente.|
|**Analisi delle vulnerabilità**|Fornire i report di analisi delle vulnerabilità dell'infrastruttura trimestrale e delle applicazioni Web. L'analisi deve essere eseguita in base all'intero footprint pubblico (indirizzi IP e URL) e agli intervalli IP interni.|
||Fornire prove dimostrabili che la correzione delle vulnerabilità identificate durante l'analisi delle vulnerabilità viene patchata in base al periodo di tempo documentato per l'applicazione di patch.|
|**Firewall**|Fornire la documentazione sui criteri che regola le procedure e le procedure di gestione del firewall.|
||Fornire prove dimostrabili che le credenziali amministrative predefinite vengono modificate prima dell'installazione in ambienti di produzione.|
||Fornire prove dimostrabili che i firewall vengono installati sul limite dell'ambiente nell'ambito e installati tra la rete perimetrale (nota anche come DMZ, zona demilitarizzata e subnet schermata) e le reti attendibili interne.|
||Fornire prove dimostrabili che tutti gli accessi pubblici terminano nella zona demilitarizzata (DMZ).|
||Fornire prove dimostrabili che tutto il traffico consentito attraverso il firewall attraversa un processo di approvazione.|
||Fornire prove dimostrabili che la base di regole del firewall è configurata per rilasciare il traffico non definito in modo esplicito.|
||Fornire prove dimostrabili che il firewall supporta solo una crittografia solida in tutte le interfacce amministrative non della console.|
||Fornire prove dimostrabili che si stanno eseguendo revisioni delle regole del firewall almeno ogni 6 mesi.|
|**Web Application Firewall (WAF) (OPTIONAL):** il credito aggiuntivo verrà premiato per soddisfare i controlli seguenti.|Fornire prove dimostrabili che Il Firewall applicazione Web (WAF) è configurato per monitorare, avvisare e bloccare attivamente il traffico dannoso.|
||Fornire prove dimostrabili che waf supporta la ripartizione del carico di lavoro SSL.|
||Fornire prove dimostrabili che waf è protetto da alcune o tutte le seguenti classi di vulnerabilità in base al set di regole di base OWASP (3.0 o 3.1) |
|**Change Control**|Fornire la documentazione dei criteri che regola i processi di controllo delle modifiche.|
||Fornire prove dimostrabili che gli ambienti di sviluppo e test applicano la separazione dei compiti dall'ambiente di produzione.|
||Fornire prove dimostrabili che i dati di produzione sensibili non vengono utilizzati all'interno degli ambienti di sviluppo o test.|
||Fornire prove dimostrabili che le richieste di modifica documentate contengono l'impatto della modifica, i dettagli delle procedure di back-out e dei test da eseguire.|
||Fornire prove dimostrabili che le richieste di modifica sono sottoposte a un processo di autorizzazione e disconnessione.|
|**Sviluppo/distribuzione di software sicuro**| Fornire criteri e procedure che supportano lo sviluppo e la distribuzione di software sicuri, incluse indicazioni sulle procedure consigliate per la codifica sicura rispetto alle classi di vulnerabilità comuni, ad esempio OWASP Top 10 o SANS Top 25 CWE.|
|| Fornire prove dimostrabili che le modifiche al codice vengono sottoposte a un processo di revisione e autorizzazione da parte di un secondo revisore.|
|| Fornire prove dimostrabili che gli sviluppatori vengono sottoposti a una formazione sullo sviluppo di software sicuro ogni anno.|
|| Fornire prove dimostrabili che gli archivi di codice sono protetti con l'autenticazione a più fattori (MFA).|
|| Fornire prove dimostrabili che i controlli di accesso sono in atto per proteggere gli archivi di codice.
|**Gestione account**| Fornire la documentazione relativa ai criteri che regola le procedure e le procedure di gestione degli account.
||Fornire prove dimostrabili che le credenziali predefinite sono disabilitate, rimosse o modificate nei componenti di sistema campionati.|
||Fornire prove dimostrabili che la creazione, la modifica e l'eliminazione degli account attraversano un processo di approvazione stabilito.|
||Fornire prove dimostrabili che è in corso un processo per disabilitare o eliminare gli account non utilizzati entro 3 mesi.|
||Fornire prove dimostrabili che sono in atto criteri password complessa o altre misure di prevenzione adeguate per proteggere le credenziali utente.  Le seguenti informazioni devono essere utilizzate come linea guida minima: lunghezza minima della password di 8 caratteri, soglia di blocco account non superiore a 10 tentativi, cronologia delle password di almeno 5 password, applicazione dell'uso di password complesse|
|**Rilevamento e prevenzione delle intrusioni (OPTIONAL):** Il credito aggiuntivo verrà premiato per soddisfare i controlli seguenti|Fornire prove dimostrabili che i sistemi di rilevamento e prevenzione delle intrusioni (IDPS) vengono distribuiti nel perimetro degli ambienti nell'ambito.|
||Fornire prove dimostrabili che le firme IDPS vengono mantenute correnti (entro 24 ore).|
||Fornire prove dimostrabili che IDPS è configurato per supportare l'ispezione TLS di tutto il traffico Web in ingresso.|
||Fornire una prova dimostrabile che IDPS è configurato per monitorare tutti i flussi di traffico in ingresso.|
||Fornire una prova dimostrabile che IDPS è configurato per monitorare tutti i flussi di traffico in uscita.|
|**Registrazione eventi di sicurezza** |Fornire la documentazione relativa ai criteri per le procedure consigliate che regolano la registrazione degli eventi di sicurezza.|
|| Fornire prove dimostrabili che mostrano che la registrazione degli eventi di sicurezza è impostata in tutti i componenti di sistema campionati per registrare gli eventi seguenti: Accesso utente ai componenti di sistema e all'applicazione, Tutte le azioni intraprese da un utente con privilegi elevati, Tentativi di accesso logico non validi Creazione o modifica di account con privilegi, Manomissione del registro eventi, Disabilitazione degli strumenti di sicurezza (ad esempio, antimalware o registrazione eventi),  Registrazione antimalware (ad esempio aggiornamenti, rilevamento malware ed errori di analisi). Eventi IDPS e WAF, se configurati|
||Fornire prove dimostrabili che gli eventi di sicurezza registrati contengono le informazioni minime seguenti: Utente, Tipo di evento, Data e ora, Indicatori di esito positivo o negativo, Etichetta che identifica il sistema interessato|
||Fornire una prova dimostrabile che tutti i componenti di sistema campionati vengono sincronizzati nel tempo con gli stessi server primari e secondari.|
||Fornire prove dimostrabili quando i sistemi pubblici sono in uso, che i registri eventi di sicurezza vengono inviati a una soluzione di registrazione centralizzata non all'interno della rete perimetrale.|
||Fornire prove dimostrabili per dimostrare che la soluzione di registrazione centralizzata è protetta da manomissioni non autorizzate dei dati di registrazione.|
||Fornire una prova dimostrabile che sono immediatamente disponibili almeno 30 giorni di dati di registrazione degli eventi di sicurezza, con 90 giorni di registri eventi di sicurezza conservati.|
|**Revisione (dati di registro)** |Fornire la documentazione dei criteri che regola le procedure e le procedure di revisione dei registri.|
||Fornire prove dimostrabili che i registri vengono esaminati quotidianamente da strumenti umani o automatizzati per identificare potenziali eventi di sicurezza.|
||Fornire prove dimostrabili che vengono esaminati e corretti potenziali eventi di sicurezza e anomalie.|
|**Avvisi** | Fornire la documentazione relativa ai criteri che regola le procedure e le procedure di avviso degli eventi di sicurezza.|
|| Fornire prove dimostrabili che gli avvisi vengono attivati per il triage immediato per i seguenti tipi di eventi di sicurezza: creazione o modifica di account con privilegi, eventi virus o malware, manomissione del registro eventi, eventi IDPS o WAF
|**Gestione dei rischi**|Fornire prove dimostrabili che è stato stabilito un processo formale di gestione dei rischi per la sicurezza delle informazioni.|
||Fornire prove dimostrabili che una valutazione formale dei rischi avviene ogni anno, almeno.|
||Fornire prove dimostrabili che la valutazione dei rischi per la sicurezza delle informazioni include minacce, vulnerabilità o l'equivalente.|
||Fornire prove dimostrabili che la valutazione dei rischi per la sicurezza delle informazioni include l'impatto, la matrice dei rischi di probabilità o l'equivalente.|
||Fornire prove dimostrabili che la valutazione dei rischi per la sicurezza delle informazioni include un registro dei rischi e un piano di trattamento.|
|**Intervento in caso di incidente**|Fornire il piano di risposta agli incidenti di sicurezza (IRP).|
||Fornire prove dimostrabili che l'IRP per la sicurezza include un processo di comunicazione documentato per garantire una notifica in tempo reale ai principali stakeholder, come marchi di pagamento e acquirenti, enti normativi, autorità di vigilanza, amministratori e clienti.|
||Fornire prove dimostrabili che tutti i membri del team di risposta agli eventi imprevisti hanno completato una formazione annuale o un esercizio top della tabella.|
||Fornire prove dimostrabili per mostrare che l'IRP di sicurezza viene aggiornato in base alle lezioni apprese o alle modifiche dell'organizzazione.|

## <a name="data-handling-security-and-privacy"></a>Sicurezza e privacy per la gestione dei dati

I dati in transito tra l'utente dell'applicazione, i servizi intermedi e i sistemi ISV devono essere protetti tramite crittografia tramite una connessione TLS che supporta almeno TLS v1.1. *Vedere* [**l'appendice A**](#appendix-a).

Se l'applicazione recupera e archivia i dati M365, sarà necessario implementare uno schema di crittografia dell'archiviazione dei dati che segue la specifica definita [**nell'Appendice B.**](#appendix-a)

### <a name="controls"></a>Controlli

|**Famiglia di controlli**| **Controlli** |
| -----------------------|-------------------------------- |
|**Dati in transito**| Fornire prove dimostrabili che la configurazione TLS soddisfa o supera i requisiti di crittografia all'interno dei requisiti di configurazione [del profilo TLS](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#appendix-a)|
||Fornire prove dimostrabili che la compressione TLS è disabilitata in tutti i servizi pubblici che gestiscono le richieste Web.|
||Fornire prove dimostrabili che la sicurezza del trasporto TLS HTTP strict è abilitata e configurata per >= 15552000 in tutti i siti.|
|**Dati in pausa**| Fornire prove dimostrabili che i dati in stato di inquieto sono crittografati in linea con i requisiti del profilo di crittografia, usando algoritmi di crittografia come AES, Blowfish, TDES e le dimensioni delle chiavi di crittografia a 128 bit e a 256 bit.|
||Fornire prove dimostrabili che la funzione hash o l'autenticazione dei messaggi (HMAC-SHA1) viene utilizzata solo per proteggere i dati in stato di inquieto in linea con i requisiti del profilo di crittografia.|
||Fornire un inventario che mostra tutti i dati archiviati, inclusa la posizione di archiviazione e la crittografia utilizzata per proteggere i dati.|
|**Conservazione ed eliminazione dei dati**|Fornire prove dimostrabili che viene formalmente stabilito un periodo di conservazione dei dati approvato e documentato.|
||Fornire prove dimostrabili che i dati conservati corrispondono al periodo di conservazione definito.|
||Fornire prove dimostrabili che sono in atto processi per eliminare in modo sicuro i dati dopo il periodo di conservazione.|
|**Gestione accesso ai dati**|Fornire un elenco di tutti gli utenti con accesso ai dati o alle chiavi di crittografia, inclusa la giustificazione aziendale.|
||Fornire prove dimostrabili che gli utenti campionati che hanno accesso a dati o chiavi di crittografia sono stati formalmente approvati, indicando in dettaglio i privilegi necessari per la loro funzione lavorativa.|
||Fornire prove dimostrabili che gli utenti campionati che hanno accesso ai dati o alle chiavi di crittografia dispongono solo dei privilegi inclusi nell'approvazione.|
||Fornire un elenco di tutte le terze parti con cui vengono condivisi i dati dei clienti.|
||Fornire prove dimostrabili che tutte le terze parti che utilizzano i dati dei clienti hanno stipulato accordi di condivisione.|
|**GDPR** (se applicabile)| Fornire un processo documentato di richiesta di accesso soggetto (SAR) e fornire prove che dimostrano che gli interessati sono in grado di generare le richieste di accesso degli interessati.|
||Fornire prove dimostrabili che sei in grado di identificare tutte le posizioni dei dati degli interessati quando rispondi a un sar.|
||L'utente mantiene un'informativa sulla privacy che deve contenere i dettagli delle società (Nome, Indirizzo e così via).|
||L'utente mantiene un avviso sulla privacy che dovrebbe spiegare i tipi di dati personali in fase di trattamento.|
||L'utente mantiene un'informativa sulla privacy che dovrebbe spiegare la lecita' del trattamento dei dati personali|
||L'utente mantiene un avviso sulla privacy che spiega in dettaglio i diritti dell'oggetto dei dati: Diritto di essere informati, Diritto di accesso da parte dell'utente, Diritto di cancellazione, Diritto alla restrizione del trattamento, Diritto alla portabilità dei dati, Diritto all'oggetto, Diritti in relazione al processo decisionale automatizzato, inclusa la profilatura.|
|| L'utente mantiene un avviso sulla privacy che dovrebbe spiegare per quanto tempo verranno conservati i dati personali.|

## <a name="optional-external-compliance-frameworks-review"></a>Revisione facoltativa dei framework di conformità esterni

Anche se non è obbligatorio, se attualmente si è in conformità con ISO 27001, PCI DSS o SOC2, è possibile scegliere di utilizzare queste certificazioni per soddisfare alcuni dei controlli di certificazione Microsoft 365. Gli analisti della certificazione tenteranno di allineare i framework di sicurezza esterni esistenti alla specifica Microsoft 365 certification. Tuttavia, se la documentazione di supporto non è in grado di garantire che i controlli di certificazione Microsoft 365 sono stati valutati nell'ambito del controllo/valutazione dei framework di sicurezza esterni, sarà necessario fornire ulteriori prove di tali controlli.

La documentazione deve dimostrare in modo adeguato che l'ambiente nell'ambito della certificazione Microsoft 365 è stato incluso nell'ambito di questi framework di sicurezza esterni. La convalida di questi framework di sicurezza verrà evasa accettando prove di certificazioni valide condotte da società esterne di terze parti affidabili. Queste società affidabili devono essere membri di organismi di accreditamento internazionali per i programmi di conformità pertinenti. Vedere Standard di certificazione e conformità ISO per ISO 27001 e QSA (Qualified Security Assessors) per PCI DSS.

Nella tabella seguente vengono evidenziati i framework esterni e la documentazione richiesti dagli analisti della certificazione nell'ambito di questo processo di convalida:

| **Standard** | **Requisiti** |
| ----- | ----- |
| **[ISO 27001](#iso-27001)** | Sarà necessaria una versione pubblica della Dichiarazione di **applicabilità** (SOA) e una copia del certificato ISO 27001 emesso.  Il SOA riepiloga la tua posizione su ognuno dei 114 controlli di sicurezza delle informazioni e verrà usato per identificare se eventuali esclusioni di controlli che non sono in modo soddisfacente nel certificato ISO 27001. Se non è possibile determinare questo problema esaminando la versione pubblica della soa, l'analista potrebbe avere bisogno di accedere all'intero SOA se ISO 27001 verrà utilizzato per convalidare alcuni dei controlli della specifica di certificazione Microsoft 365.  Oltre a convalidare l'ambito delle attività di valutazione ISO 27001, gli analisti confermeranno anche la validità della società di controllo come descritto in precedenza.|
|**[PCI DSS](#pci-dss)**| È necessario fornire un documento AOC **(Level 1 Attestation of Compliance)** valido che identififii chiaramente l'applicazione e i componenti di sistema nell'ambito.  Un AOC di autovalutazione **non verrà** accettato come prova delle procedure consigliate per la sicurezza. L'AOC verrà utilizzato per determinare quali dei controlli Microsoft 365 certification specification sono stati valutati e confermati nell'ambito della valutazione PCI DSS.|
|**[SOC 2](#soc-2)**|Il report **SOC 2 (Tipo I o Tipo II)** deve essere aggiornato (rilasciato entro gli ultimi 15 mesi e il periodo di tempo dichiarato iniziato negli ultimi 27 mesi) per essere utilizzato come prova di conformità con uno qualsiasi dei controlli di valutazione in questa specifica di certificazione Microsoft 365.|

Se nell'attestazione di Publisher sono stati inclusi framework di sicurezza esterni, gli analisti della certificazione dovranno verificare la validità di tali framework di conformità della sicurezza nell'ambito della valutazione della certificazione Microsoft 365.

|**Framework** | **Considerazioni aggiuntive** |
|-------------- | --------------------|
|ISO 27001| [**Appendice C**](#appendix-c): Raccolta di prove - Delta per ISO 27001.|
|PCI DSS | [**Appendice D**](#appendix-d): Raccolta di prove - Delta per PCI DSS.|
|SOC 2| [**Appendice E**](#appendix-e): Raccolta di prove - Delta per SOC 2.|

> [!NOTE]
> Anche se i suddetti standard/framework di sicurezza esterni possono essere inviati come prova per soddisfare alcuni dei controlli di certificazione Microsoft 365, il passaggio della certificazione Microsoft 365 non significa che si supererà correttamente un controllo rispetto a tali standard/framework. La Microsoft 365 Certification Specification è solo un piccolo sottoinsieme di tali standard/framework di sicurezza che consente a Microsoft di ottenere un livello di garanzia in riferimento alla propria posizione di sicurezza.


### <a name="requirements-to-use-external-compliance-frameworks"></a>Requisiti per l'utilizzo di framework di conformità esterni

&#x2713; L'ambiente di supporto app/componenti aggiuntivi E tutti  i processi aziendali di supporto DEVONO essere inclusi nell'ambito di qualsiasi framework di conformità di sicurezza esterno supportato e devono essere chiaramente indicati nella documentazione fornita. 

&#x2713; I framework di conformità  della sicurezza esterna supportati devono essere correnti, ad esempio entro gli ultimi 12 mesi (o entro 15 mesi se la nuova valutazione è attualmente in corso e possono essere fornite prove).

&#x2713; i framework di conformità di sicurezza esterni supportati **DEVONO** essere eseguiti da una società accreditata indipendente.

## <a name="appendix-a"></a>Appendice A

### <a name="tls-profile-configuration-requirements"></a>Requisiti di configurazione del profilo TLS

Tutto il traffico di rete, sia all'interno di una rete virtuale, di un servizio cloud o di un data center, deve essere protetto con un minimo di TLS v1.1 (è consigliato TLS v1.2+ ) o un altro protocollo applicabile. Le eccezioni a questo requisito sono:

* **Reindirizzamento DA HTTP a HTTPS**. L'app può rispondere tramite HTTP per reindirizzare i client a HTTPS, ma la risposta non deve contenere dati sensibili (cookie, intestazioni, contenuto). Non sono consentite altre risposte HTTP oltre ai reindirizzamenti a HTTPS e alla risposta ai probe di integrità. Vedi di seguito.
* **Probe di integrità**. La tua app può rispondere ai probe di integrità su HTTP **solo se** i probe di integrità HTTPS non sono supportati dalla parte che controlla.
* **Accesso al certificato**. L'accesso agli endpoint CRL, OCSP e AIA ai fini della convalida e del controllo della revoca dei certificati è consentito su HTTP.
* **Comunicazioni locali**. La tua app può usare HTTP (o altri protocolli non protetti) per le comunicazioni che non lasciano il sistema operativo, e. g. connessione a un endpoint del server Web esposto in localhost.

La compressione TLS **DEVE** essere disabilitata.

## <a name="appendix-b"></a>Appendice B

### <a name="encryption-profile-configuration-requirements"></a>Requisiti di configurazione del profilo di crittografia

Solo le primitive e i parametri crittografici sono consentiti come segue:

### <a name="symmetric-cryptography"></a>Crittografia simmetrica

**Crittografia**

&emsp;&#x2713; sono consentiti solo AES, BitLocker, Blowfish o TDES. Qualsiasi lunghezza di chiave supportata >=128 è consentita (128, 192 e 256 bit) e può essere utilizzata (sono consigliate chiavi a 256 bit).

&emsp;&#x2713; è consentita solo la modalità CBC. Ogni operazione di crittografia deve usare un vettore di inizializzazione (IV) appena generato casualmente.

&emsp;&#x2713; L'uso di crittografia di flusso, ad esempio RC4, **NON è** consentito.

**Funzioni hash**

&emsp;&#x2713; Tutto il nuovo codice deve usare SHA-256, SHA-384 o SHA-512 (noto collettivamente come SHA-2). L'output può essere troncato a non meno di 128 bit

&emsp;&#x2713; SHA-1 può essere usato solo per motivi di compatibilità.

&emsp;&#x2713; l'utilizzo di MD5, MD4, MD2 e altre funzioni hash NON è consentito, anche per le applicazioni non crittografiche.

**Autenticazione dei messaggi**

&emsp;&#x2713; Tutto il nuovo codice DEVE utilizzare HMAC con una delle funzioni hash approvate. L'output di HMAC può essere troncato a non meno di 128 bit.

&emsp;&#x2713; HMAC-SHA1 può essere utilizzato solo per motivi di compatibilità.

&emsp;&#x2713; chiave HMAC DEVE essere di almeno 128 bit. Sono consigliate chiavi a 256 bit.

### <a name="asymmetric-algorithms"></a>Algoritmi asimmetrici

**Crittografia**

&emsp;&#x2713; RSA è consentito. Key **MUST** be at least 2048 bits and OAEP padding must be used. L'uso della spaziatura interna PKCS è consentito solo per motivi di compatibilità.

**Firme**

&emsp;&#x2713; RSA è consentito. Key **MUST** be at least 2048 bits and PSS padding must be used. L'uso della spaziatura interna PKCS è consentito solo per motivi di compatibilità.

&emsp;&#x2713;ECDSA è consentito. La **chiave DEVE** essere di almeno 256 bit. È necessario utilizzare la curva NIST P-256, P-384 o P-521.

**Chiave Exchange**

&emsp;&#x2713; ECDH è consentito. La **chiave DEVE** essere di almeno 256 bit. È necessario utilizzare la curva NIST P-256, P-384 o P-521.

&emsp;&#x2713; ECDH è consentito. La **chiave DEVE** essere di almeno 256 bit. È necessario utilizzare la curva NIST P-256, P-384 o P-521.

## <a name="appendix-c"></a>Appendice C

### <a name="evidence-collection--delta-for-iso-27001"></a>Raccolta di prove - Delta per ISO 27001

Se hai già raggiunto la conformità ISO27001, i seguenti delta (lacune) non interamente coperti da ISO 27001 dovranno essere esaminati come minimo nell'ambito di questa certificazione Microsoft 365.

> [!NOTE]
> Nell'ambito della valutazione della certificazione Microsoft 365, l'analista di certificazione determinerà se uno dei controlli ISO 27001 mappati non è stato incluso nell'ambito della valutazione ISO 27001 e può anche decidere di campionare i controlli che sono stati trovati per fornire ulteriore garanzia. Tutti i requisiti mancanti da ISO 27001 dovranno essere inclusi nelle attività di valutazione Microsoft 365 certificazione.

**Protezione antimalware - Antivirus**

Se la protezione antimalware è in atto utilizzando il controllo delle applicazioni ed è attestata all'interno di ISO 27001 Report non sono necessarie ulteriori indagini. Se non è presente alcun controllo delle applicazioni, gli analisti della certificazione dovranno identificare e valutare le prove dei meccanismi di controllo delle applicazioni per impedire la detonazione di malware all'interno dell'ambiente. Ciò richiederà di:

* Dimostrare che il software antivirus è in esecuzione in tutti i componenti di sistema campionati.

* Dimostrare che l'antivirus è configurato in tutti i componenti di sistema campionati per bloccare automaticamente il malware, per mettere & avviso o per avvisare.

* Il software antivirus **DEVE essere** configurato per registrare tutte le attività.

**Gestione delle patch - Applicazione di patch**

Poiché i controlli ISO 27001 non valutano in modo specifico questa categoria, sarà necessario:

* I componenti software e i sistemi operativi non più supportati dal fornitore **non** devono essere utilizzati nell'ambiente. I criteri di supporto DEVONO essere applicati per garantire che i componenti software/sistemi operativi non supportati verranno rimossi dall'ambiente e deve essere presente un processo per identificare quando i componenti software vanno a fine vita

**Analisi delle vulnerabilità**  

Poiché i controlli ISO 27001 non valutano in modo specifico questa categoria, sarà necessario:

* Dimostrare che viene eseguita l'analisi trimestrale delle vulnerabilità interne ed esterne.

* Verificare che la documentazione di supporto sia disponibile per la correzione delle vulnerabilità in base alla classificazione dei rischi e in linea con la specifica come segue:
 
 &#x2713; risolvere tutti i problemi di rischio critici e elevati in linea con la classificazione dei rischi per l'analisi interna.
 
 &#x2713; risolvere tutti i problemi di rischio critico, elevato e medio in linea con la classificazione dei rischi per l'analisi esterna.
 
 &#x2713; dimostrare che la correzione viene eseguita in linea con i criteri di correzione delle vulnerabilità documentati.

**Firewall : firewall (o tecnologie equivalenti)**

Poiché i controlli ISO 27001 non valutano in modo specifico questa categoria, sarà necessario:

* Dimostrare che i firewall sono installati sul limite dell'ambiente nell'ambito.

* Dimostrare che i firewall sono installati tra la rete perimetrale e le reti attendibili.

*   Dimostrare che tutti gli accessi pubblici terminano nella DMZ.

*   Dimostrare che le credenziali amministrative predefinite vengono modificate prima dell'installazione nell'ambiente reale.

*   Dimostrare che tutto il traffico consentito attraverso i firewall passa attraverso un processo di autorizzazione che si traduce nella documentazione di tutto il traffico con una giustificazione aziendale.

*   Dimostrare che tutti i firewall sono configurati per rilasciare il traffico non definito in modo esplicito.

*   Dimostrare che i firewall supportano solo la crittografia solida in tutte le interfacce amministrative non della console.

*   Dimostrare che le interfacce amministrative non console del firewall esposte all'autenticazione a più fattori supportano Internet.

*   Dimostrare che le revisioni delle regole del firewall vengono eseguite almeno ogni 6 mesi

**Firewall - Firewall applicazione Web (WAF)**  

Se viene distribuito un waf, verrà fornito ulteriore credito per proteggere dalla miriade di minacce e vulnerabilità dell'applicazione Web a cui l'applicazione può essere esposta. Quando è presente un waf o simile, sarà necessario:

* Dimostrare che waf è configurato in modalità di difesa attiva o monitorare di più con l'avviso.

* Dimostrare che waf è configurato per supportare la ripartizione del carico di lavoro SSL.

* È configurato in base al set di regole di base OWASP (3.0 o 3.1) per la protezione dalla maggior parte dei tipi di attacco seguenti:

&#x2713; problemi relativi al protocollo e alla codifica.

&#x2713; inserimento dell'intestazione, contrabbando delle richieste e suddivisione delle risposte.

&#x2713; attacchi di attraversamento di file e percorsi.

&#x2713; attacchi RFI (Remote File Inclusion).

&#x2713; attacchi di esecuzione di codice remoto.

&#x2713; attacchi phP-injection.

&#x2713; attacchi di cross-site scripting.

&#x2713; SQL attacchi di inserimento di dati.

&#x2713; attacchi session-fixation.

**Change Control**

Poiché i controlli ISO 27001 non valutano in modo specifico alcuni elementi dei processi di richiesta di modifica, sarà necessario:

* Dimostrare che le richieste di modifica hanno i dettagli seguenti:

&#x2713; impatto documentato.

&#x2713; dettagli sui test delle funzionalità da eseguire.

&#x2713; Dettagli di eventuali procedure di back-out.

* Dimostrare che i test delle funzionalità vengono eseguiti dopo il completamento delle modifiche.

* Dimostrare che le richieste di modifica vengono disconnesse dopo l'esecuzione del test delle funzionalità.

**Gestione account**

Poiché i controlli ISO 27001 non valutano in modo specifico alcuni elementi dei processi di gestione degli account, sarà necessario:

*   Dimostrare come &#x2713;vengono implementati per ridurre gli attacchi di riesecuzione (ad esempio, MFA, Kerberos).
*   Illustrare in che modo gli account che non sono stati utilizzati in 3 mesi vengono disabilitati o eliminati.
*   &#x2713; o altre misure di prevenzione adeguate devono essere configurate per proteggere le credenziali utente. I criteri minimi per le password seguenti devono essere utilizzati come linee guida:

&#x2713; Lunghezza minima password di 8 caratteri.

&#x2713; soglia di blocco dell'account non superiore a 10 tentativi.
 
&#x2713; cronologia delle password di almeno cinque password.
 
&#x2713; l'utilizzo di password complesse.
 
*   Dimostrare che l'autenticazione a più fattori è configurata per tutte le soluzioni di accesso remoto.

*   Dimostrare che la crittografia avanzata è configurata in tutte le soluzioni di accesso remoto.

*   Se la gestione del DNS pubblico si trova all'esterno dell'ambiente nell'ambito, tutti gli account utente in grado di apportare modifiche DNS DEVONO essere configurati per l'utilizzo di MFA.

**Rilevamento e prevenzione delle intrusioni (OPTIONAL)**

Poiché i controlli ISO 27001 non valutano in modo specifico alcuni elementi dei processi dei servizi di rilevamento e prevenzione delle intrusioni (IDPS, Intrusion Detection and Prevention Services), sarà necessario:

*   GLI IDPS **devono** essere distribuiti nel perimetro dell'ambiente di supporto.

*   Le firme IDPS **DEVONO** essere mantenute correnti entro il giorno precedente.

*   IDPS **DEVE essere** configurato per l'ispezione TLS.

*   IDPS **DEVE essere** configurato per TUTTO il traffico in ingresso e in uscita.

*   IDPS **DEVE** essere configurato per l'avviso.

**Registrazione eventi**

Poiché i controlli ISO 27001 non valutano in modo specifico alcuni elementi dei processi di registrazione degli eventi di sicurezza, sarà necessario:

* Dimostrare che i sistemi pubblici stanno accedendo a una soluzione di registrazione centralizzata che non è all'interno della rete perimetrale.

* Dimostrare come sia immediatamente disponibile un minimo di 30 giorni di dati di registrazione, con 90 giorni di conservazione.

**Revisione (dati di registrazione)**

Poiché i controlli ISO 27001 non valutano in modo specifico alcuni elementi di questa categoria, sarà necessario:

*   Illustrare come vengono eseguite le revisioni giornaliere dei log e come vengono identificate le eccezioni e le anomalie che mostrano come vengono gestite.

**Avvisi**

Poiché i controlli ISO 27001 non valutano in modo specifico alcuni elementi di questa categoria, sarà necessario:

* Illustrare in che modo gli eventi di sicurezza sono configurati per attivare avvisi per la verifica immediata.

* Dimostrare come il personale è disponibile 24 ore su 24, 7 giorni su 7 per rispondere agli avvisi di sicurezza.

**Gestione dei rischi**

Poiché i controlli ISO 27001 non valutano in modo specifico alcuni elementi dei processi di valutazione dei rischi, sarà necessario:

* Dimostrare che è stato stabilito un processo formale di gestione dei rischi.

**Risposta agli eventi imprevisti**

Poiché i controlli ISO 27001 non valutano in modo specifico alcuni elementi dei criteri e dei processi di risposta agli incidenti, sarà necessario:

*   Dimostrare che il piano o la procedura di risposta agli eventi imprevisti include:

&#x2713; procedure di risposta specifiche per i modelli di minaccia previsti.

&#x2713; funzionalità di gestione degli incidenti allineate a NIST Cybersecurity Framework (identificare, proteggere, rilevare, rispondere, recuperare).
 
&#x2713; L'IRP copre i sistemi nell'ambito.
 
&#x2713; formazione annuale per il team di risposta agli incidenti.

## <a name="appendix-d"></a>Appendice D

### <a name="evidence-collection--deltas-for-pci-dss"></a>Raccolta di prove - Delta per PCI DSS

Se hai già raggiunto la conformità PCI DSS, i seguenti delta (lacune) non interamente coperti da PCI DSS dovranno essere esaminati come minimo nell'ambito di questa certificazione Microsoft 365.

> [!NOTE]
> Come parte della valutazione della certificazione Microsoft 365, l'analista di certificazione determinerà se uno dei controlli PCI DSS mappati non è stato incluso nell'ambito della valutazione PCI DSS e può anche decidere di campionare i controlli che sono stati trovati per fornire ulteriore garanzia. Eventuali requisiti mancanti nel DSS PCI dovranno essere inclusi nelle attività di valutazione Microsoft 365 certificazione.

**Protezione antimalware - Controllo applicazioni**

Se la protezione antimalware è in atto tramite l'uso di antivirus ed è attestata all'interno del rapporto DSS PCI non sono necessarie ulteriori indagini. Se non è presente alcun antivirus, gli analisti della certificazione dovranno identificare e valutare le prove dei meccanismi di controllo delle applicazioni per impedire la detonazione di malware all'interno dell'ambiente. Ciò richiederà di: 

*   Dimostrare come viene eseguita l'approvazione dell'applicazione e verificare che sia stata completata.

*   Dimostrare che esiste un elenco completo delle applicazioni approvate con giustificazione aziendale.

*   Fornire o dimostrare la documentazione di supporto è sul posto per illustrare in dettaglio come il software di controllo delle applicazioni è configurato per soddisfare specifici meccanismi di controllo delle applicazioni (ad esempio, whitelisting, firma del codice e così via).

*   Dimostrare che in tutti i componenti di sistema campionati, il controllo dell'applicazione è configurato come documentato.

**Gestione delle patch - Classificazione dei rischi**

Poiché i controlli PCI DSS non valutano in modo specifico questa categoria, sarà necessario:

* Illustrare come viene eseguita la classificazione dei rischi delle vulnerabilità.

**Analisi delle vulnerabilità**

Poiché i controlli PCI DSS non valutano in modo specifico questa categoria, sarà necessario:

* Dimostrare che la correzione viene eseguita in linea con i criteri di correzione delle vulnerabilità documentati.

**Firewall : firewall (o tecnologie equivalenti)**

Poiché i controlli PCI DSS non valutano in modo specifico questa categoria, sarà necessario:

* Dimostrare che i firewall supportano solo la crittografia solida in tutte le interfacce amministrative non della console.

* Dimostrare che le interfacce amministrative non console del firewall esposte all'autenticazione a più fattori supportano Internet.

Verrà fornito ulteriore credito se viene distribuito un waf (Web Application Firewall) per proteggere dalle miriade di minacce e vulnerabilità dell'applicazione Web a cui l'applicazione può essere esposta. Quando è presente un waf o simile, sarà necessario:

* Dimostrare che waf è configurato in modalità di difesa attiva o monitorare di più con l'avviso.

* Dimostrare che waf è configurato per supportare la ripartizione del carico di lavoro SSL.

* È configurato in base al set di regole di base OWASP (3.0 o 3.1) per la protezione dalla maggior parte dei tipi di attacco seguenti:

&#x2713; problemi relativi al protocollo e alla codifica.

&#x2713; inserimento dell'intestazione, contrabbando delle richieste e suddivisione delle risposte.

&#x2713; attacchi di attraversamento di file e percorsi.

&#x2713; attacchi RFI (Remote File Inclusion).

&#x2713; attacchi di esecuzione di codice remoto.

&#x2713; attacchi phP-injection.

&#x2713; attacchi di cross-site scripting.

&#x2713; SQL attacchi di inserimento di dati.

&#x2713; attacchi session-fixation.

**Change Control**

Poiché i controlli DSS PCI non valutano in modo specifico alcuni elementi dei processi di richiesta di modifica, sarà necessario:

* Dimostrare che le richieste di modifica vengono generate prima di essere effettuate in ambienti di produzione.

* Dimostrare che le modifiche sono autorizzate prima di entrare in produzione.

* Dimostrare che i test delle funzionalità vengono eseguiti dopo il completamento delle modifiche.

* Dimostrare che le richieste di modifica vengono disconnesse dopo l'esecuzione del test delle funzionalità.

**Sviluppo/distribuzione di software sicuro**

Poiché i controlli PCI DSS non accedono in modo specifico ad alcuni elementi di processi di sviluppo e distribuzione software sicuri; ciò richiederà all'utente:

* Gli archivi di codice DEVONO essere protetti da MFA.

*   È necessario disporre di controlli di accesso adeguati per proteggere gli archivi di codice da modifiche di codice dannose.

**Gestione account**

Poiché i controlli PCI DSS non valutano in modo specifico alcuni elementi dei processi di gestione degli account, sarà necessario:

* Illustrare come vengono implementati i meccanismi di autorizzazione per ridurre gli attacchi di riesecuzione (ad esempio, MFA, Kerberos).

* I criteri password complessa o altre misure di prevenzione adeguate devono essere configurati per proteggere le credenziali utente. I criteri minimi per le password seguenti devono essere utilizzati come linee guida: 

&#x2713; Lunghezza minima password di 8 caratteri.

&#x2713; soglia di blocco dell'account non superiore a 10 tentativi.

&#x2713; cronologia delle password di almeno cinque password.

&#x2713; l'utilizzo di password complesse.

* Dimostrare che la crittografia avanzata è configurata in tutte le soluzioni di accesso remoto.

* Se la gestione del DNS pubblico si trova all'esterno dell'ambiente nell'ambito, tutti gli account utente in grado di apportare modifiche DNS DEVONO essere configurati per l'utilizzo di MFA.

**Rilevamento e prevenzione delle intrusioni (OPTIONAL)**

Poiché i controlli PCI DSS non valutano in modo specifico alcuni elementi dei processi dei servizi di rilevamento e prevenzione delle intrusioni (IDPS, Intrusion Detection and Prevention Services), sarà necessario:

* IDPS DEVE essere configurato per l'ispezione TLS.

*   IDPS DEVE essere configurato per TUTTO il traffico in ingresso e in uscita.

**Gestione dei rischi**

Poiché i controlli PCI DSS non valutano in modo specifico alcuni elementi dei processi di valutazione dei rischi, sarà necessario:

* Dimostrare che la valutazione dei rischi include matrici di impatto e probabilità.

**Risposta agli eventi imprevisti**

Poiché i controlli PCI DSS non valutano in modo specifico alcuni elementi dei criteri e dei processi di risposta agli incidenti, questo richiederà allo sviluppatore di:

* Dimostrare che le funzionalità di gestione degli eventi imprevisti sono allineate a NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover).

## <a name="appendix-e"></a>Appendice E

### <a name="evidence-collection---deltas-for-soc-2"></a>Raccolta di prove - Delta per SOC 2

Se hai già raggiunto la conformità SOC 2, i seguenti delta (lacune) non interamente coperti da SOC 2 dovranno essere esaminati nell'ambito di questa certificazione Microsoft 365.

> [!NOTE]
> Come parte della valutazione della certificazione Microsoft 365, l'analista di certificazione determinerà se uno dei controlli SOC 2 mappati non è stato incluso nell'ambito della valutazione SOC 2 e può anche decidere di campionare i controlli che sono stati trovati come inclusi per fornire ulteriore garanzia. Tutti i requisiti mancanti dalla valutazione SOC 2 dovranno essere inclusi nell'ambito delle attività di valutazione Microsoft 365 certificazione.

**Protezione antimalware - Controllo applicazioni**

Se la protezione antimalware è in atto tramite l'uso di antivirus ed è attestata all'interno del report SOC 2, non sono necessarie ulteriori indagini. Se non è presente alcun antivirus, gli analisti della certificazione dovranno identificare e valutare le prove dei meccanismi di controllo delle applicazioni per impedire la detonazione di malware all'interno dell'ambiente. Ciò richiederà di:

* Fornire o dimostrare la documentazione di supporto è sul posto per illustrare in dettaglio come il software di controllo delle applicazioni è configurato per soddisfare specifici meccanismi di controllo delle applicazioni (ad esempio, whitelisting, firma del codice e così via).

* Dimostrare come viene eseguita l'approvazione dell'applicazione e verificare che sia stata completata.

*   Dimostrare che esiste un elenco completo delle applicazioni approvate con giustificazione aziendale.

*   Dimostrare che in tutti i componenti di sistema campionati, il controllo dell'applicazione è configurato come documentato.

**Gestione delle patch - Applicazione di patch**

Poiché i controlli SOC 2 non valutano in modo specifico questa categoria, sarà necessario:

*   Qualsiasi problema basso, medio, alto o critico deve essere patchato nelle normali finestre di attività di applicazione di patch.

*   I componenti software e i sistemi operativi non più supportati dal fornitore non devono essere utilizzati nell'ambiente. I criteri di supporto DEVONO essere applicati per garantire che i componenti software/sistemi operativi non supportati verranno rimossi dall'ambiente e deve essere presente un processo per identificare quando i componenti software vengono applicati.

**Firewall - Firewall**

Poiché i controlli SOC 2 non valutano in modo specifico i controlli delle modifiche agli elenchi di controllo di accesso del firewall, sarà necessario:

* Dimostrare che tutto il traffico consentito attraverso i firewall passa attraverso un processo di autorizzazione che si traduce nella documentazione di tutto il traffico con una giustificazione aziendale.

* Dimostrare che le revisioni delle regole del firewall vengono eseguite almeno ogni sei mesi.

Se viene distribuito un firewall dell'applicazione Web (WAF) o simile, verrà fornito ulteriore credito per proteggere dalla miriade di minacce e vulnerabilità dell'applicazione Web a cui l'applicazione può essere esposta. Quando è presente un waf o simile, sarà necessario:

* Dimostrare che waf è configurato in modalità di difesa attiva o monitorare di più con l'avviso.

* Dimostrare che waf è configurato per supportare la ripartizione del carico di lavoro SSL.

* È configurato in base al set di regole di base OWASP ((3.0 o 3.1) per la protezione dalla maggior parte dei tipi di attacco seguenti:

&emsp;&#x2713; problemi relativi al protocollo e alla codifica.

&emsp;&#x2713; inserimento dell'intestazione, contrabbando delle richieste e suddivisione delle risposte.

&emsp;&#x2713; attacchi di attraversamento di file e percorsi.

&emsp;&#x2713; attacchi RFI (Remote File Inclusion).

&emsp;&#x2713; attacchi di esecuzione di codice remoto.

&emsp;&#x2713; attacchi phP-injection.

&emsp;&#x2713; attacchi di cross-site scripting.

&emsp;&#x2713; SQL attacchi di inserimento di dati.

&emsp;&#x2713; attacchi session-fixation.

**Change Control**

Poiché i controlli SOC 2 non valutano in modo specifico alcuni elementi dei processi di richiesta di modifica, questo richiederà allo sviluppatore di:

* Illustrare in che modo gli ambienti di sviluppo/test sono separati dall'ambiente di produzione che forza la separazione dei compiti.

* Illustrare in che modo i dati in tempo reale non vengono utilizzati all'interno degli ambienti di sviluppo/test.

* Dimostrare che i test delle funzionalità vengono eseguiti dopo il completamento delle modifiche.

* Dimostrare che le richieste di modifica vengono disconnesse dopo l'esecuzione del test delle funzionalità.

**Sviluppo/distribuzione di software sicuro**

Poiché i controlli SOC 2 non accedono in modo specifico ad alcuni elementi di processi di sviluppo e distribuzione software sicuri; ciò richiederà all'utente:

*   È necessario disporre di un processo di sviluppo software consolidato e documentato che copra l'intero ciclo di vita dello sviluppo software.

*   Gli sviluppatori DEVONO sottoporsi a una formazione di codifica software sicura almeno ogni anno.

*   Gli archivi di codice DEVONO essere protetti da MFA.

*   È necessario disporre di controlli di accesso adeguati per proteggere gli archivi di codice da modifiche di codice dannose.

**Gestione account**

Poiché i controlli SOC2 non valutano in modo specifico alcuni elementi dei processi di gestione degli account, sarà necessario:

*   Illustrare come vengono implementati i meccanismi di autorizzazione per ridurre gli attacchi di riesecuzione (ad esempio, MFA, Kerberos).

*   Illustrare in che modo gli account che non sono stati utilizzati in 3 mesi vengono disabilitati o eliminati.

*   I criteri password complessa o altre misure di prevenzione adeguate devono essere configurati per proteggere le credenziali utente. I criteri minimi per le password seguenti devono essere utilizzati come linee guida:

&emsp;&#x2713; Lunghezza minima password di 8 caratteri.

&emsp;&#x2713; soglia di blocco dell'account non superiore a 10 tentativi.

&emsp;&#x2713; cronologia delle password di almeno 5 password.

&emsp;&#x2713; l'utilizzo di password complesse

*   Dimostrare che gli account utente univoci vengono emessi a tutti gli utenti.

*   Se la gestione del DNS pubblico si trova all'esterno dell'ambiente nell'ambito, tutti gli account utente in grado di apportare modifiche DNS DEVONO essere configurati per l'utilizzo di MFA.

**Rilevamento e prevenzione delle intrusioni (OPTIONAL).**

Poiché i controlli SOC 2 non valutano in modo specifico alcuni elementi dei processi dei servizi di rilevamento e prevenzione delle intrusioni (IDPS, Intrusion Detection and Prevention Services), sarà necessario:

*   Le firme IDPS DEVONO essere mantenute correnti entro il giorno precedente

*   IDPS DEVE essere configurato per l'ispezione TLS

*   IDPS DEVE essere configurato per TUTTO il traffico in ingresso e in uscita

**Registrazione eventi**

Poiché i controlli SOC 2 non valutano in modo specifico alcuni elementi dei processi di registrazione degli eventi di sicurezza, sarà necessario:

* Illustrare come, in tutti i componenti di sistema all'interno del set di esempio, il sistema seguente è configurato per registrare gli eventi seguenti

&emsp;&#x2713; Accesso utente ai componenti di sistema e alle applicazioni.

&emsp;&#x2713; Tutte le azioni eseguite da un utente con privilegi elevati.

&emsp;&#x2713; tentativi di accesso logico non validi.

Dimostrare che gli eventi registrati contengono; almeno le informazioni seguenti:

&emsp;&#x2713; Utente.

&emsp;&#x2713; tipo di evento.

&emsp;&#x2713; data e ora.

&emsp;&#x2713; indicatore esito positivo/negativo.

&emsp;&#x2713; Label per identificare il sistema interessato.

*   Dimostrare che tutti i componenti di sistema all'interno del set di esempio sono configurati per l'utilizzo della sincronizzazione dell'ora e che questi sono gli stessi dei server di tempo primario/secondario.

* Dimostrare che i sistemi pubblici stanno accedendo a una soluzione di registrazione centralizzata che non è all'interno della rete perimetrale.

*   Dimostrare che i sistemi pubblici stanno accedendo a una soluzione di registrazione centralizzata che non è all'interno della rete perimetrale.

* Illustrare in che modo la soluzione di registrazione centralizzata è protetta da manomissioni non autorizzate dei dati di registrazione.

* Dimostrare come sia immediatamente disponibile un minimo di 30 giorni di dati di registrazione, con almeno 90 giorni di conservazione.

**Gestione dei rischi**

Poiché i controlli SOC2 non valutano in modo specifico alcuni elementi dei processi di valutazione dei rischi, sarà necessario:

* Dimostrare che una valutazione formale dei rischi viene eseguita almeno ogni anno.

*Risposta agli eventi imprevisti.*

Poiché i controlli SOC2 non valutano in modo specifico alcuni elementi dei criteri e dei processi di risposta agli incidenti, sarà necessario:

* Dimostrare che il piano o la procedura di risposta agli eventi imprevisti include:

&emsp;&#x2713; specifiche procedure di risposta per i modelli di minaccia previsti.

&emsp;&#x2713; processo di comunicazione documentato per garantire una notifica in tempo reale dei principali stakeholder (marchi di pagamento/acquirenti, enti normativi, autorità di vigilanza, amministratori, clienti e così via).

## <a name="appendix-f"></a>Appendice F

### <a name="hosting-deployment-types"></a>Hosting dei tipi di distribuzione

Microsoft riconosce che distribuirai applicazioni e archivi il codice di app/componenti aggiuntivi in ambienti di hosting diversi. Le responsabilità generali di alcuni controlli di sicurezza all'interno del Microsoft 365 dipenderanno dall'ambiente di hosting utilizzato. L'Appendice F esamina i tipi di distribuzione comuni e ne esegue il mapping con i controlli di sicurezza valutati nell'ambito del processo di valutazione. Sono stati identificati i seguenti tipi di distribuzione di hosting:

|Tipi di hosting  |Descrizione  |
|-----|------|
|**ISV ospitato**|I tipi ospitati da ISV possono essere definiti come la posizione in cui sei responsabile dell'infrastruttura usata per supportare l'ambiente app/componenti aggiuntivi. Può trovarsi fisicamente all'interno dei data center o dei data center di terze parti con un servizio di co-posizione. In ultima analisi, si ha la completa proprietà e il controllo amministrativo sull'infrastruttura di supporto e sull'ambiente operativo.|
|**Infrastruttura come servizio (IaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)|Infrastruttura come servizio è un servizio che viene fornito in base al quale l'infrastruttura di supporto fisica viene gestita e gestita per loro conto dal provider di servizi cloud (CSP). In genere, la rete, l'archiviazione, i server fisici e l'infrastruttura di virtualizzazione sono tutti responsabilità del CSP. Il sistema operativo, il middleware, il runtime, i dati e le applicazioni sono le responsabilità dell'utente. Anche le funzionalità di firewall vengono gestite e gestite da terze parti, tuttavia la manutenzione della base di regole del firewall in genere è ancora responsabilità degli utenti.|
|**Platform as a Service/Serverless (PaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)| Con Platform as a Service, viene eseguito il provisioning con una piattaforma gestita che presenta un servizio che può essere utilizzato. Non è necessario eseguire le funzioni sysadmin poiché il sistema operativo e l'infrastruttura di supporto sono gestiti dal provider di servizi di configurazione. Questa operazione viene in genere utilizzata quando le organizzazioni non desiderano presentare un servizio Web e possono invece concentrarsi sulla creazione del codice sorgente dell'applicazione Web e sulla pubblicazione dell'applicazione Web nei servizi Web gestiti dal cloud.  Un altro esempio può essere un servizio di database in cui viene data connettività a un database, tuttavia l'infrastruttura di supporto e l'applicazione di database sono astratte dal consumer.   **Nota: Serverless e PaaS sono simili, quindi ai fini della certificazione Microsoft 365 Il tipo di distribuzione Serverless e PasS del tipo di distribuzione di hosting di Microsoft 365 sono considerati gli stessi**|
|**Hybrid Hosted**|Con il tipo ospitato ibrido, è possibile utilizzare più tipi ospitati per supportare varie parti dell'ambiente di supporto. Questo può essere più il caso in cui app/componenti aggiuntivi vengono utilizzati in più stack M365. Anche se la certificazione Microsoft 365 supporterà la posizione in cui vengono sviluppate app/componenti aggiuntivi in più servizi M365, è necessario valutare l'intero ambiente di supporto (tra app/componenti aggiuntivi) in base a ognuno dei "Mapping di tipi ospitati" applicabili. In alcuni casi, è possibile utilizzare tipi ospitati diversi per un singolo componente aggiuntivo, in cui questa operazione viene eseguita, l'applicabilità dei criteri dovrà comunque seguire i criteri "Mapping di tipi ospitati" tra i vari tipi ospitati.|
|**Hosting condiviso**|L'hosting condiviso è il luogo in cui si ospita l'ambiente all'interno di una piattaforma condivisa da più singoli consumer. La Microsoft 365 di certificazione non è stata scritta per conto di questo a causa dell'adozione del cloud, l'hosting condiviso non è comune. Se si ritiene che sia in uso, contattare Microsoft perché sarà necessario creare ulteriori requisiti per tenere conto dei rischi aggiuntivi in questo tipo di tipo di hosting.|


## <a name="appendix-g"></a>Appendice G

### <a name="microsoft-365-certification-process-workflow"></a>Microsoft 365 Flusso di lavoro processo di certificazione

![Flusso di lavoro](ProcessFlow.jpg)

## <a name="learn-more"></a>Per approfondire

[Microsoft 365 Panoramica del programma di conformità delle app](~/overview.md)  
[Che cos'Microsoft 365'attestazione Publisher app?](~/docs/attestation.md)  
[Che cos'è Microsoft 365 certificazioni?](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a>Glossario

### <a name="aia"></a>AIA

*Authority Information Access è un descrittore della posizione del servizio utilizzato per trovare il certificato dell'autorità di certificazione emittente.

### <a name="crl"></a>CRL

*L'elenco di revoche di certificati consente a un endpoint SSL (Secure Sockets Layer) di verificare che un certificato ricevuto da un host remoto sia valido e attendibile.

### <a name="cvss-score"></a>Punteggio CVSS

*Common Vulnerability Scoring System è uno standard pubblicato che misura la vulnerabilità e calcola un punteggio numerico in base alla gravità.

### <a name="cvss-patch-management-guidelines"></a>Linee guida per la gestione delle patch CVSS

* Critico (9.0 - 10.0)
* Alto (7,0 - 8,9)
* Medio (4,0 - 6,9)
* Basso (0,0 - 3,9)

### <a name="dmz"></a>DMZ

*La zona demilitarizzata è una rete intermedia fisica o logica che interagisce direttamente con reti esterne o non proprietarie mantenendo separata e isolata la rete privata interna dell'host.

### <a name="euii"></a>EUII

*Informazioni identificabili per l'utente finale.*

### <a name="gdpr"></a>GDPR

*Il regolamento generale sulla protezione dei dati è un regolamento per la privacy e la protezione dei dati dell'Unione Europea (UE) per tutti i dati dei cittadini dell'UNIONE, indipendentemente dalla posizione del sito di applicazione.

### <a name="hsts"></a>HSTS

*HTTP Strict Transport Security utilizza un'intestazione di risposta HTTP che indica al Web browser di accedere solo al contenuto tramite HTTPS.  Questo è progettato per proteggere da attacchi di downgrade e dirottamento dei cookie.

### <a name="iec"></a>IEC

*International Electrotechnical Commission.

### <a name="isms"></a>ISMS

*Information Security Management System.

### <a name="isv"></a>ISV

I fornitori di sicurezza indipendenti sono individui e organizzazioni che sviluppano, commercializzazione e vendono software in esecuzione su piattaforme hardware e software di terze parti.

### <a name="iso-27001"></a>ISO 27001

Un framework di specifica del sistema di gestione della sicurezza delle informazioni per tutti i controlli tecnici in un'organizzazione che elabora i criteri e le procedure di gestione dei rischi.

### <a name="lfi"></a>LFI

*Inclusione file locale consente* a un utente malintenzionato di includere file in un server tramite il Web browser.

### <a name="nist"></a>NIST

Il *National Institute of Standards* (NIST), un'agenzia non regolamentare del Dipartimento del Commercio degli Stati Uniti fornisce indicazioni alle organizzazioni del settore privato negli Stati Uniti per valutare e approvare la loro capacità di prevenire, rilevare e rispondere agli attacchi informatici.

### <a name="non-significant-changes"></a>Modifiche non significative

* Correzioni di bug secondarie.
* Miglioramenti secondari delle prestazioni.
* Patch per sistemi operativi/librerie/client e applicazioni server.

### <a name="ocsp"></a>OCSP

*Il protocollo di stato del* certificato online viene utilizzato per controllare lo stato di revoca dei certificati digitali X.509.

### <a name="oii"></a>OII

*Informazioni di identificazione dell'organizzazione*.

### <a name="owasp"></a>OWASP

*Aprire Protezione applicazione Web Project*.

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
* Aggiornamenti principali all'infrastruttura di supporto; ad esempio, l'implementazione di un nuovo firewall, gli aggiornamenti principali ai servizi front-facing e così via.
* Aggiunta di funzionalità e /o estensioni alla tua app.
* Aggiornamenti dell'app che acquisiscono dati sensibili aggiuntivi.
* Modifiche ai flussi di dati o ai modelli di autorizzazione dell'app
* Aggiunta di endpoint API o funzioni degli endpoint API.

### <a name="soc-2"></a>SOC 2

*Service Organization Control 2*, una procedura tecnica di controllo costituita da cinque principi di trust service per garantire che i provider di servizi gestino in modo sicuro i dati e la privacy per i client di un'organizzazione.

### <a name="ssl"></a>SSL

*Secure Sockets Layer*.

### <a name="tls"></a>TLS

*Transport Layer Security*.
