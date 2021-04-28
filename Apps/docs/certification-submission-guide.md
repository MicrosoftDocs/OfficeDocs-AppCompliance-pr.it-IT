---
ms.author: oromalle
title: Guida all'invio della certificazione Microsoft 365
author: orionomalley
description: Visualizzazione granulare della Guida all'invio della certificazione Microsoft 365
keywords: team di certificazione delle app Microsoft 365 security compliance m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 4d0f09b3a1dd6bde7022e93d08a491e2855d90a7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/28/2021
ms.locfileid: "52071365"
---
# <a name="microsoft-365-certification-submission-guide"></a>Guida all'invio della certificazione Microsoft 365

**Contenuto dell'articolo:**
- [Introduzione](#introduction)
- [Prerequisiti](#prerequisites) 
- [Aggiornamenti delle specifiche di certificazione Microsoft 365](#microsoft-365-certification-specification-updates)
- [Ambito di certificazione](#certification-scope)
- [Processo di certificazione](#certification-process)
- [Prove di conformità](#compliance-evidence) 
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

Parte del programma Microsoft 365 App Compliance, la certificazione Microsoft 365 offre alle organizzazioni aziendali la certezza e la sicurezza che i dati e la privacy siano adeguatamente protetti e protetti durante l'integrazione di app/componenti aggiuntivi per sviluppatori di terze parti nella piattaforma Microsoft 365. Le applicazioni e i componenti aggiuntivi che superano la convalida verranno designati **Come certificato Microsoft 365** in tutto l'ecosistema Microsoft 365. 

Partecipando al programma di certificazione Microsoft 365, l'utente accetta queste condizioni supplementari e si conforma a qualsiasi documentazione di accompagnamento applicabile alla partecipazione al programma di certificazione Microsoft 365 con Microsoft Corporation ("Microsoft", "microsoft", "noi" o "nostro"). L'utente rappresenta e garantisce all'utente di avere l'autorità di accettare queste condizioni supplementari di certificazione Microsoft 365 per conto di se stessi, di una società e/o di un'altra entità, a seconda dei casi. Microsoft può modificare, modificare o terminare questi termini supplementari in qualsiasi momento. La partecipazione continua al programma di certificazione Microsoft 365 dopo qualsiasi modifica o modifica significa che l'utente accetta le nuove condizioni supplementari. Se non accetti i nuovi termini supplementari o termini questi termini supplementari, devi smettere di partecipare al programma di certificazione Microsoft 365.

Questo documento è destinato agli ISV (Independent Software Vendor) per fornire informazioni sul processo di certificazione Microsoft 365, sui prerequisiti per avviare il processo e sui dettagli dei controlli di sicurezza specifici che devono essere installati.  Le informazioni generali sul programma conformità app di Microsoft 365 sono [](https://docs.microsoft.com/microsoft-365-app-certification/overview)disponibili nella pagina del programma conformità app di Microsoft 365. 

> [!IMPORTANT]
> Attualmente, la certificazione Microsoft 365 è limitata:
>* Applicazioni di Microsoft Teams (schede, bot e così via) .
>* App/componenti aggiuntivi di Sharepoint
>* Componenti aggiuntivi di Office (Word, Excel, PowerPoint, Outlook, Project, OneNote)

## <a name="prerequisites"></a>Prerequisiti

### <a name="publisher-attestation"></a>Attestazione editore

Prima di essere insignito del processo di certificazione Microsoft 365, è necessario aver completato l'attestazione dell'autore. Tuttavia, è possibile avviare il processo di certificazione Microsoft 365 prima di completare l'attestazione dell'autore.  

### <a name="read-the-microsoft-365-certification-specification"></a>Leggere la specifica di certificazione Microsoft 365

Microsoft consiglia a tutti gli ISV (Independent Software Vendor) di leggere la specifica di certificazione Microsoft 365 nella sua interezza per garantire che tutti i controlli applicabili vengano soddisfatti dall'ambiente nell'ambito e dall'app/componente aggiuntivo. In questo modo si garantisce un processo di valutazione uniforme.

## <a name="microsoft-365-certification-specification-updates"></a>Aggiornamenti delle specifiche di certificazione Microsoft 365 

Gli aggiornamenti alla specifica di certificazione Microsoft 365 sono previsti ogni sei o dodici mesi circa. Questi aggiornamenti potrebbero introdurre nuovi domini di sicurezza di destinazione e/o controlli di sicurezza. Gli aggiornamenti si baseranno sul feedback degli sviluppatori, sulle modifiche al panorama delle minacce e per aumentare la base di sicurezza del programma durante la maturazione. 

Gli ISV che hanno già avviato la valutazione della certificazione Microsoft 365 possono continuare la valutazione con la versione della specifica di certificazione Microsoft 365 valida al momento dell'avvio della valutazione. Tutti i nuovi invii, inclusa la ricertificazione annuale, devono essere valutati rispetto alla versione pubblicata.

> [!NOTE]
> Non è necessario rispettare tutti i controlli contenuti in questa specifica di certificazione Microsoft 365 per ottenere una certificazione. Tuttavia, il superamento delle soglie (che non verranno divulgate) è in atto per ognuno dei domini di sicurezza descritti in questa Specifica di certificazione Microsoft 365. Alcuni controlli verranno classificati come "**Hard Fail**", il che significa che la mancanza di questi controlli di sicurezza comporta una valutazione non riuscita. 

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
|>9 & <25|3|
|>24|4 |

> [!NOTE]
>Se vengono identificate discrepanze tra i dispositivi inclusi nel campione iniziale, le dimensioni del campione possono essere aumentate durante la valutazione. 

## <a name="certification-process"></a>Processo di certificazione

Prima di avviare il processo di certificazione, è necessario aver avviato o completato correttamente l'attestazione dell'autore. Le risposte di attestazione verranno utilizzate a supporto del processo di certificazione Microsoft 365 e procederanno come segue: 

1. Consultare la documentazione relativa all'attestazione dell'autore per garantire l'allineamento con l'ambiente corrente 
2. Richiesta di avanzamento alla certificazione Microsoft 365 tramite posta elettronica <AppCert@microsoft.com> 
3. Gli analisti della certificazione apriranno un dialogo prima di avviare il processo di certificazione Microsoft 365   
4. Inviare [l'invio di documenti iniziale](#initial-document-submission)
5. L'analista di certificazione fornirà un elenco dei controlli per i quali sono necessarie prove, che avvia formalmente il processo di certificazione Di Microsoft 365
6. Inviare prove che dimostrano che tutti i controlli di certificazione Microsoft 365 nell'ambito sono stati soddisfatti entro una finestra di 60 giorni per completare la certificazione Microsoft 365 

> [!IMPORTANT]
> **Intervallo di tempo per l'invio:** Si prevede che in media il processo di valutazione debba richiedere 15 giorni, a condizione che tu sia in grado di rispondere alle richieste di prove in modo appropriato. Microsoft consiglia di verificare che questa guida all'invio della certificazione sia stata letta e di essere certi di poter soddisfare i controlli impostati al suo interno e di fornire prove sufficienti prima di avviare il processo di certificazione. All'avvio del processo di certificazione, è consentito un massimo di 60 giorni per completare la valutazione, altrimenti la prova già raccolta diventa obsoleta. Se, dopo il periodo di tempo di 60 giorni, non viene raggiunta una valutazione corretta, l'invio avrà esito negativo e il processo deve ricominciare. Se viene emesso un errore a causa del mancato rispetto della specifica di certificazione Microsoft 365 o perché viene raggiunto il periodo di tempo di 60 giorni e non vengono fornite prove sufficienti, i risultati non riusciti non saranno resi pubblici da Microsoft. 

## <a name="compliance-evidence"></a>Prove di conformità

Anche se non è obbligatorio, se attualmente si è in conformità con altri framework di sicurezza esterni, è possibile scegliere di utilizzare queste certificazioni per soddisfare alcuni dei controlli di certificazione Microsoft 365. Gli analisti della certificazione esaminino l'ambito e la copertura del controllo di sicurezza di qualsiasi framework di sicurezza esterno supportato per determinare quali controlli possono essere esclusi dalla valutazione della certificazione Microsoft 365, fornendo l'ambito dei framework di sicurezza esterni includono gli ambienti nell'ambito per la valutazione della certificazione Microsoft 365. 

Gli analisti della certificazione tenteranno di allineare i framework di sicurezza esterni esistenti alla specifica di certificazione Microsoft 365. Tuttavia, se la documentazione di supporto non è in grado di garantire che i controlli di certificazione Microsoft 365 sono stati valutati nell'ambito del controllo/valutazione dei framework di sicurezza esterni, sarà necessario fornire ulteriori prove dei controlli in essere. 

Attualmente, i framework di sicurezza esterni che possono essere utilizzati a supporto della valutazione della certificazione Microsoft 365 includono:

*  [ISMS](#isms) / [IEC](#iec) - Specifica IS0/IEC 27001 
*  [PCI DSS](#pci-dss)
*  [SOC 2](#soc-2)

La documentazione deve dimostrare in modo adeguato che l'ambiente nell'ambito della certificazione Microsoft 365 è stato incluso nell'ambito di questi framework di sicurezza esterni. La convalida di questi framework di sicurezza verrà evasa accettando prove di certificazioni valide condotte da società esterne di terze parti affidabili. Queste società affidabili devono essere membri di organismi di accreditamento internazionali per i programmi di conformità pertinenti.Vedere Standard di certificazione e [conformità ISO](https://www.iso.org/certification.html) per ISO 27001 e [QSA (Qualified Security Assessors)](https://www.pcisecuritystandards.org/assessors_and_solutions/qualified_security_assessors) per PCI DSS. 

Nella tabella seguente viene evidenziata la documentazione richiesta dagli analisti della certificazione nell'ambito di questo processo di convalida:

| **Standard** | **Requisiti** |
| ----- | ----- |
| **[ISO 27001](#iso-27001)** | Sarà necessaria una versione pubblica della Dichiarazione di **applicabilità** (SOA) e una copia del certificato ISO 27001 emesso.  Il SOA riepiloga la tua posizione su ognuno dei 114 controlli di sicurezza delle informazioni e verrà usato per identificare se eventuali esclusioni di controlli che non sono in modo soddisfacente nel certificato ISO 27001. Se non è possibile determinare questo problema esaminando la versione pubblica della SOA, l'analista potrebbe avere bisogno di accedere all'intero SOA se ISO 27001 verrà utilizzato per convalidare alcuni dei controlli della specifica di certificazione Microsoft 365.  Oltre a convalidare l'ambito delle attività di valutazione ISO 27001, gli analisti confermeranno anche la validità della società di controllo come descritto in precedenza.|
|**[PCI DSS](#pci-dss)**| È necessario fornire un documento AOC **(Level 1 Attestation of Compliance)** valido che identififii chiaramente l'applicazione e i componenti di sistema nell'ambito.  Un AOC di autovalutazione **non verrà** accettato come prova delle procedure consigliate per la sicurezza. L'AOC verrà utilizzato per determinare quali dei controlli della specifica di certificazione Microsoft 365 sono stati valutati e confermati nell'ambito della valutazione PCI DSS.|
|**[SOC 2](#soc-2)**|Il report **SOC 2 (Tipo I o Tipo II)** deve essere aggiornato (rilasciato negli ultimi 15 mesi e il periodo di tempo dichiarato iniziato negli ultimi 27 mesi) per essere utilizzato come prova di conformità con uno qualsiasi dei controlli di valutazione contenuti nella presente specifica di certificazione Microsoft 365.|


## <a name="microsoft-365-certification"></a>Certificazione Microsoft 365

I framework di sicurezza esterni supportati possono essere usati come prova della riunione di alcuni dei controlli di certificazione Microsoft 365. Prima di poter considerare i framework di sicurezza esterni, gli analisti della certificazione esaminino l'ambito e la copertura di controllo della sicurezza del framework di sicurezza esterno utilizzando la documentazione presentata in precedenza. 

Le appendici seguenti possono essere utilizzate per identificare dove esistono potenziali lacune tra il framework di sicurezza esterno e la specifica di certificazione Microsoft 365 come indicato di seguito: 

|**Framework** | **Considerazioni aggiuntive** |
|-------------- | --------------------|
|ISO 27001| [**Appendice C**](#appendix-c): Raccolta di prove - Delta per ISO 27001.|
|PCI DSS | [**Appendice D**](#appendix-d): Raccolta di prove - Delta per PCI DSS.|
|SOC 2| [**Appendice E**](#appendix-e): Raccolta di prove - Delta per SOC 2.|

> [!NOTE]
> Anche se i suddetti standard/framework di sicurezza esterni possono essere inviati come prova per soddisfare alcuni dei controlli di certificazione Microsoft 365, il passaggio della certificazione Microsoft 365 non significa che si supererà correttamente un controllo rispetto a tali standard/framework. La specifica di certificazione Microsoft 365 è solo un piccolo sottoinsieme di tali standard/framework di sicurezza che consente a Microsoft di ottenere un livello di garanzia in riferimento alla propria posizione di sicurezza.

## <a name="initial-document-submission"></a>Invio documento iniziale

L'invio del documento iniziale aiuterà gli analisti della certificazione a eseguire l'ambito e a determinare quali saranno gli ambiti per la valutazione. Dopo di che sarà necessario inviare la documentazione di supporto e le prove utilizzate per eseguire la valutazione. L'invio iniziale deve includere le informazioni specificate di seguito:

| **Panoramica &nbsp; della documentazione**     |   **Dettagli della documentazione**  |
| -------------------------| -----------------------------|
|**Descrizione app/componente aggiuntivo** | Descrizione dello scopo e della funzionalità dell'app/componente aggiuntivo. Questo dovrebbe fornire all'analista di certificazione una buona comprensione del funzionamento dell'app/componente aggiuntivo e dell'uso previsto.
|**Report test di penetrazione** |Report di test di penetrazione completato negli ultimi 12 mesi. Questo report deve includere l'ambiente che supporta la distribuzione dell'app/aggiunta insieme a qualsiasi altro ambiente che supporti il funzionamento dell'app/componente aggiuntivo. **Nota:** se non fai test di penetrazione annuali, puoi scegliere di farlo attraverso il processo di certificazione.|
|**Diagrammi dell'architettura**|Diagramma dell'architettura logica che rappresenta una panoramica generale dell'infrastruttura di supporto dell'app o del componente aggiuntivo. Deve includere tutti **gli ambienti** di hosting e l'infrastruttura di supporto che supporta l'app/componente aggiuntivo. Questo diagramma DEVE illustrare tutti i diversi componenti di sistema di supporto all'interno dell'ambiente per aiutare gli analisti della certificazione a comprendere i sistemi nell'ambito e a determinare il campionamento. Indicare anche il tipo di ambiente di hosting utilizzato. ISV ospitato, IaaS, PaaS o ibrido. **Nota:** Se viene utilizzato SaaS, indicare i vari servizi SaaS utilizzati per fornire i servizi di supporto all'interno dell'ambiente.|
|**Public Footprint** | Descrizione **dettagliata di** tutti gli indirizzi IP pubblici e gli URL utilizzati dall'infrastruttura di supporto. Deve includere l'intervallo IP instradabile completo allocato all'ambiente, a meno che non sia stata implementata una segmentazione adeguata per suddividere l'intervallo in uso (sarà necessaria una prova adeguata della segmentazione)|
|**Diagrammi del flusso di dati** |Diagrammi di flusso che illustrano in dettaglio quanto segue:
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
|**Conferma di conformità**|Documentazione di supporto per i framework di sicurezza esterni inclusi nell'invio dell'attestazione dell'autore o da considerare quando si esaminano i controlli di certificazione Microsoft 365. Attualmente sono supportati i tre elementi seguenti:|
||&#x2713; attestazione di conformità [PCI DSS](#pci-dss) (AOC).|
||&#x2713; report [SOC 2](#soc-2) tipo I/Type II.|
||&#x2713; [ISMS](#isms)  /  [IEC](#iec) - 1S0/IEC 27001 Statement of Applicability (SoA) e Certificazione.|
|**Dipendenze Web**|Documentazione che elenca tutte le dipendenze usate dall'app o dal componente aggiuntivo con le versioni correnti in esecuzione.|
|**Inventario software**|Un inventario software aggiornato che include tutto il software utilizzato nell'ambiente nell'ambito insieme alle versioni.|
|**Inventario hardware**| Un inventario hardware aggiornato utilizzato dall'infrastruttura di supporto. Verrà usato per facilitare il campionamento durante l'esecuzione della fase di valutazione. Se l'ambiente include PaaS, fornire dettagli sui servizi utilizzati.|

## <a name="evidence-collection-and-assessment-activities"></a>Attività di raccolta e valutazione delle prove

Attraverso solide attività di raccolta e valutazione delle prove, gli analisti della certificazione saranno in grado di valutare la propria posizione di sicurezza per ottenere un livello adeguato di garanzia della sicurezza dei dati e conformità ai controlli delle specifiche di certificazione di Microsoft 365. Gli analisti della certificazione riusciranno a ottenere questo risultato nel modo seguente: 

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

Gli analisti della certificazione esamineranno le prove fornite per determinare se sono stati soddisfatti in modo adeguato i controlli in questa specifica di certificazione Microsoft 365. 

Se possibile e per ridurre il tempo necessario per completare la valutazione, [](#initial-document-submission)una o tutta la documentazione dettagliata nell'invio della documentazione iniziale deve essere fornita   in anticipo.

Gli analisti della certificazione esaminino innanzitutto le prove fornite dall'invio iniziale della documentazione e le informazioni sull'attestazione dell'editore per identificare le righe appropriate di richiesta, le dimensioni di campionamento e la necessità di ottenere ulteriori prove come descritto in precedenza.  Gli analisti della certificazione analizzeranno tutte le informazioni raccolte per trarre conclusioni su come e se si stanno incontrando i controlli all'interno di questa specifica di certificazione Microsoft 365. 

## <a name="app-certification-criteria"></a>Criteri di certificazione app

L'app, l'infrastruttura di supporto e la documentazione di supporto verranno valutati nei domini di sicurezza seguenti:

1. [**Sicurezza applicazioni**](#application-security)
1. [**Sicurezza operativa / Distribuzione sicura**](#operational-security)
1. [**Sicurezza e privacy per la gestione dei dati**](#data-handling-security-and-privacy)
1. [**Revisione facoltativa di External Compliance Framework**](#optional-external-compliance-frameworks-review)

Ognuno di questi domini di sicurezza include controlli chiave specifici che includono uno o più requisiti specifici che verranno valutati nell'ambito del processo di valutazione. Per garantire che la certificazione Microsoft 365 sia inclusiva per gli sviluppatori di tutte le dimensioni, ognuno dei quattro domini di sicurezza viene valutato utilizzando un sistema di punteggio per determinare un punteggio complessivo da ognuno dei domini. I punteggi per ognuno dei controlli di certificazione Microsoft 365 vengono allocati tra 1 (basso) e 3 (alto) in base al rischio percepito che tale controllo non venga soddisfatto. Ognuno dei quattro domini di sicurezza avrà un segno percentuale minimo da considerarsi un pass. Alcuni elementi di questa specifica includono alcuni criteri di errore automatici:

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

**Convalida delle autorizzazioni GraphAPI**

La convalida delle autorizzazioni GraphAPI viene eseguita per convalidare l'app o il componente aggiuntivo non richiede autorizzazioni troppo permissive. Questa operazione viene eseguita controllando manualmente le autorizzazioni richieste. Gli analisti della certificazione interseranno questi controlli rispetto all'invio dell'attestazione dell'autore e valuteranno il livello di accesso richiesto per garantire che vengano soddisfatte le procedure di "privilegio minimo". Se gli analisti della certificazione ritengono che queste procedure di "privilegio minimo" non vengano soddisfatte, gli analisti della certificazione avranno una discussione aperta con l'utente per convalidare la giustificazione aziendale per le autorizzazioni richieste. Eventuali discrepanze rispetto all'invio dell'attestazione dell'autore riscontrate durante questa revisione riceveranno anche un feedback in modo da poter aggiornare l'attestazione dell'autore. 

**Controlli di connettività esterna**

Come parte della valutazione, un analista eseguirà una leggera analisi delle funzionalità delle applicazioni per identificare le connessioni esterne a M365.  Tutte le connessioni non identificate come Microsoft o le connessioni dirette al servizio verranno contrassegnate e discusse durante la valutazione.

**Test di sicurezza delle applicazioni**

Un'adeguata revisione dei rischi associati all'app/componente aggiuntivo e all'ambiente di supporto è essenziale per garantire ai clienti la sicurezza dell'app/componente aggiuntivo. I test di sicurezza delle applicazioni sotto forma di test di penetrazione devono essere eseguiti se l'applicazione dispone di connettività a qualsiasi servizio non pubblicato da Microsoft. Se l'app funziona autonomamente senza connettività a qualsiasi servizio o back-end non Microsoft, non è necessario eseguire test di penetrazione.


### <a name="penetration-testing-scope"></a>Ambito di test di penetrazione

Le attività  di test di penetrazione DEVONO includere l'ambiente che supporta la distribuzione dell'app/componente aggiuntivo (ad esempio, in cui è ospitato il codice dell'app/componente aggiuntivo che in genere sarà la risorsa all'interno del file manifesto) insieme a qualsiasi ambiente aggiuntivo che supporti il funzionamento dell'app/componente aggiuntivo (ad esempio, se l'app/componente aggiuntivo parla con altre applicazioni Web al di fuori di Microsoft 365).  Quando si definisce l'ambito, è necessario fare attenzione per garantire che tutti i sistemi o gli ambienti "connessi" che possono influire sulla sicurezza dell'ambiente nell'ambito siano inclusi anche in tutte le attività di test di penetrazione. 

Se vengono utilizzate tecniche per segmentare gli ambienti nell'ambito da altri ambienti, le attività di test di penetrazione DEVONO convalidare l'efficacia di queste tecniche di segmentazione. Questo deve essere descritto nel report di test di penetrazione. 
 

### <a name="testspecification"></a>Specifica di test 

|Test | Controlli |
|-------|-----------|
|**Test di penetrazione**| I test di  penetrazione delle applicazioni e dell'infrastruttura devono essere eseguiti ogni anno (ogni 12 mesi) e condotti da una società indipendente affidabile. La correzione delle vulnerabilità critiche e  ad alto rischio identificate deve essere completata entro un mese dalla conclusione del test di penetrazione o prima a seconda del processo documentato di applicazione delle patch.Footprint esterno completo (indirizzi IP, URL, endpoint API e così via) DEVE essere incluso nell'ambito dei test di penetrazione e deve essere documentato nel report dei test di penetrazione. Footprint esterno completo (indirizzi IP, URL, endpoint API e così via) **DEVE** essere incluso nell'ambito dei test di penetrazione e deve essere documentato nel report dei test di penetrazione.                                                                                                                                                                           I test di penetrazione delle applicazioni Web DEVONO includere tutte le classi di vulnerabilità; ad esempio, la più attuale OWASP Top 10 o SANS Top 25 CWE.                                                                                                                                                                                Non è necessario rieseguire la verifica delle vulnerabilità identificate da parte della società di test di  penetrazione. La correzione e l'autovalutazione sono tuttavia sufficienti, tuttavia, è necessario fornire prove adeguate per dimostrare una correzione sufficiente durante la valutazione.|

### <a name="application-security-testing-reportreview"></a>Revisione del report di test di sicurezza delle applicazioni

I report dei test di penetrazione verranno esaminati per verificare che non vi siano vulnerabilità che soddisfino i criteri **di errore automatico seguenti:**

* Presenza di un sistema operativo non supportato. 

* Presenza di account amministrativi predefiniti, enumerabili o intuibili.

* Presenza di rischi SQL'iniezione.*

* Presenza di cross-site scripting.*

* Presenza di vulnerabilità di attraversamento della directory (percorso file).*

* Presenza di vulnerabilità HTTP, ad esempio suddivisione delle risposte dell'intestazione, contrabbando di richieste e attacchi Desync.*

* Presenza della divulgazione del codice sorgente [(incluso LFI](#lfi)).*

* Qualsiasi punteggio critico o elevato, come definito dalle linee guida per la gestione delle patch CVSS.

* Qualsiasi vulnerabilità tecnica significativa che può essere facilmente sfruttata per compromettere una grande quantità di EUII o OUI.

*Indipendentemente dalle vulnerabilità CVSS Score

> [!IMPORTANT]
>I report devono essere in grado di garantire che sia possibile dimostrare tutto ciò che è descritto nella sezione Application Security Test Specification.


### <a name="penetration-testing-requirements-and-cost"></a>Requisiti e costi dei test di penetrazione

Per gli ISV che attualmente non esigino in test di penetrazione, i test di penetrazione sono inclusi nella certificazione Microsoft 365. Microsoft organizza e copre il costo di un test di penetrazione per un massimo di 12 giorni di test manuale. I costi dei test di penetrazione vengono calcolati in base al numero di giorni necessari per testare l'ambiente. Tutte le spese che superano i 12 giorni di test saranno di responsabilità dell'ISV. L'ISV sarà anche responsabile della dimostrazione che le vulnerabilità identificate nel test di penetrazione sono state corretti prima del conferimento di una certificazione, ma non è necessario produrre un report pulito.

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

### <a name="test-specification"></a>Specifica di test

|Test | Controlli |
| ------------------------|------------------------------ |
| **Protezione antimalware** | È necessario distribuire meccanismi di protezione antimalware in tutti i sistemi nell'ambito comunemente interessati dal malware. Questi meccanismi di protezione possono includere l'uso di software antivirus o tecniche di controllo delle applicazioni che proteggono dal malware. Se si usa il software antivirus o il controllo delle applicazioni, deve soddisfare i criteri seguenti.                                                                                            L'anti-virus (inclusi anche i prodotti antimalware) DEVE soddisfare le condizioni seguenti: |
||&#x2713; software antivirus è in esecuzione su tutti i componenti di sistema nell'ambito.|
||&#x2713; il software antivirus viene mantenuto aggiornato (entro 30 giorni).|
||&#x2713; le firme antivirus vengono mantenute aggiornate (entro 1 giorno).|
||&#x2713; deve essere configurata l'analisi all'accesso e/o le analisi periodiche con le notifiche.  Se viene utilizzata l'analisi all'accesso, devono essere configurate anche le analisi settimanali, ma se non è configurata l'analisi all'accesso, è necessario configurare l'analisi giornaliera. |
||&#x2713; software antivirus **deve** essere configurato come segue.|
||&emsp;&#x25fc; bloccare il malware sospetto.|
||&emsp;&#x25fc; mettere in quarantena il malware sospetto.|
||&emsp;&#x25fc; fornire un avviso sul malware sospetto.|
||&#x2713; software antivirus **deve** essere configurato per registrare tutte le attività.
||&#x2713; criteri e procedure **devono** essere applicati per promuovere pratiche antimalware forti.|
||oppure|
||I controlli delle applicazioni DEVONO essere configurati in tutti i sistemi nell'ambito in modo da soddisfare le condizioni seguenti:|
||&#x2713; tutte le applicazioni consentite che possono essere eseguite su componenti di sistema nell'ambito devono essere formalmente approvate dall'organizzazione.|
||&#x2713; L'organizzazione DEVE mantenere un elenco completo delle applicazioni approvate con giustificazione aziendale per l'applicazione.|
||&#x2713; specifici meccanismi di controllo delle applicazioni DEVONO essere documentati completamente: ad esempio, le posizioni nella whitelist; firma del codice e così via.|
||&#x2713; controllo dell'applicazione deve essere configurato come documento.|
||&#x2713; processo documentato per le approvazioni delle applicazioni deve essere in atto e controllabile.|
|**Gestione delle patch**|È **necessario** che siano stati documentati criteri e procedure di applicazione delle patch per garantire che l'applicazione delle patch sia eseguita in modo appropriato. Deve essere  in atto un processo affidabile che identifichi, classifica e patch le nuove vulnerabilità della sicurezza in base ai punteggi di classificazione dei rischi consigliati di CVSS V3.1 o alla tassonomia di punteggio equivalente: 
||**Punteggi consigliati per la classificazione dei rischi** (intervallo di punteggio di base CVSS v3.1)|
||&emsp;**Critico**: 9.0 - 10.0.|
||&emsp;**High**: 7.0 - 8.9.|
||&emsp;**Medium**: 4.0 - 6.9.|
||&emsp;**Low**: 0.1 - 3.9.|
||&emsp;**Nessuno**: 0,0 |
|| **IMPORTANTE:** il processo di identificazione delle nuove vulnerabilità deve essere sufficientemente solido da consentire l'identificazione e l'applicazione di patch delle vulnerabilità in linea con la finestra di applicazione delle patch documentata definita. |
|**Patching**|&#x2713; Eventuali problemi critici, di alto  o medio rischio devono essere patchati entro un periodo predeterminato e documentato deciso dall'ISV che rappresenta il periodo minimo di tempo prima che il problema venga **risolto.**  Anche se la finestra di applicazione delle patch è definita dall'ISV, la finestra deve essere entro un intervallo di tempo ragionevole. Ad esempio, tre mesi per applicare una patch a una vulnerabilità critica non sarebbero ragionevoli e pertanto rifiutati all'interno della valutazione della certificazione Microsoft 365.|
||&#x2713; criteri e procedure dettagliate su come viene eseguita l'applicazione di patch **DEVE** essere in vigore e **DEVE** includere tutti i sistemi operativi, le applicazioni e i componenti software applicabili utilizzati nell'ambiente. Sono incluse tutte le dipendenze Web usate all'interno dell'app o del componente aggiuntivo.|
||&#x2713; I componenti software e i sistemi operativi non più supportati dal fornitore **non** devono essere utilizzati nell'ambiente. I criteri  di supporto DEVONO essere applicati per garantire che i componenti software/sistemi operativi non supportati verranno rimossi dall'ambiente e deve essere presente un processo per identificare quando i componenti software vengono applicati.|
|**Analisi delle vulnerabilità**|L'analisi delle vulnerabilità deve includere:|
||&#x2713;'analisi trimestrale delle vulnerabilità esterne eseguita  sul footprint pubblico completo dell'ambiente nell'ambito (URL E indirizzi IP per l'analisi dell'infrastruttura e dell'applicazione Web).|
||&#x2713;'analisi delle vulnerabilità interne con autenticazione trimestrale eseguita su componenti di sistema nell'ambito (non per PaaS).|
||&#x2713; Deve essere in atto un  criterio documentato di correzione delle vulnerabilità per garantire che i componenti di sistema non siano affliti da vulnerabilità note, dettagliando la sequenza temporale per correggere le vulnerabilità in base ai punteggi di classificazione dei rischi consigliati CVSS **** definiti (vedere sopra).|
||&#x2713; le analisi continue devono  essere eseguite fino a quando le vulnerabilità identificate classificate per i rischi non vengono corretti entro la sequenza temporale richiesta, come definito dal criterio di correzione dell'ISV. Anche se la sequenza temporale di correzione è definita dall'ISV, la finestra deve essere entro un intervallo di tempo ragionevole. Ad esempio, tre mesi per correggere una vulnerabilità critica non sarebbero ragionevoli e pertanto rifiutati nell'ambito della valutazione della certificazione Microsoft 365.|
|**Firewall**|L'infrastruttura di supporto avrà un firewall (o equivalente in cui vengono utilizzati i servizi cloud) configurato come segue:|
||&#x2713; **deve** essere installato in tutte le connessioni Internet che espongono gli ambienti nell'ambito.|
||&#x2713; **deve** essere installato tra tutte le dmz (zone demilitarizzate) ed eventuali reti attendibili.|
||&#x2713; Tutti gli accessi **pubblici DEVONO** terminare in una DMZ (Demilitarized Zone). |
||&#x2713; le credenziali amministrative predefinite **DEVONO** essere modificate prima dell'installazione negli ambienti di produzione.|
||&#x2713; Tutto il traffico consentito attraverso firewall nell'ambito (in entrambe le direzioni) **DEVE** passare attraverso un processo di approvazione e tutti i protocolli, i servizi e le porte devono essere documentati con giustificazioni aziendali.|
||&#x2713; le regole firewall devono essere configurate in linea con le regole consentite documentate.|
||&#x2713; crittografia forte, in linea con **l'Appendice B,** **DEVE** essere abilitata su tutte le interfacce amministrative non console del firewall.|
||&#x2713;'autenticazione a più fattori (MFA) **deve** essere abilitata per l'accesso amministrativo del firewall.|
||&#x2713; le revisioni di Firewall **devono** essere eseguite almeno ogni sei mesi.|
||L'analisi della certificazione esamini la base delle regole del firewall per la presenza di flussi di traffico in uscita verso potenziali terze parti per convalidare la condivisione di dati esterni di terze parti.  |
||**Web Application Firewall (WAF)**. Se viene distribuita una misura WAF o equivalente per proteggere dalle minacce e dalle vulnerabilità delle applicazioni Web, verrà fornito ulteriore credito. Se presente, devono essere applicati criteri e **procedure** di supporto insieme alle configurazioni WAF seguenti: |
||&#x2713; WAF DEVE operare in modalità di difesa attiva (bloccando automaticamente gli attacchi identificati) o in modalità di monitoraggio (monitoraggio attivo/analisi degli avvisi).|
||&#x2713; WAF configurato per supportare la ripartizione del carico di lavoro [SSL.](#ssl)|
||&#x2713; WAF deve essere configurato in base al **set** di regole di base [OWASP](#owasp)(3.0 o 3.1) per la protezione dalla maggior parte   delle seguenti:|
||&emsp;&#x25fc; problemi relativi al protocollo e alla codifica.|
||&emsp;&#x25fc; inserimento dell'intestazione, contrabbando delle richieste e suddivisione delle risposte.|
||&emsp;&#x25fc; attacchi di attraversamento di file e percorsi.|
||&emsp;&#x25fc; attacchi RFI (Remote File Inclusion).|
||&emsp;&#x25fc; attacchi di esecuzione di codice remoto.|
||&emsp;&#x25fc; attacchi phP-injection.|
||&emsp;&#x25fc; attacchi di cross-site scripting.|
||&emsp;&#x25fc; SQL attacchi di inserimento di dati.|
||&emsp;&#x25fc; attacchi session-fixation.|
|**Change Control**|I criteri e  le procedure di controllo delle modifiche DEVONO essere implementati per garantire che le modifiche siano implementate in modo da mantenere la sicurezza, la stabilità e l'integrità dell'ambiente. Sono necessari i seguenti criteri **di controllo delle** modifiche:|
||&#x2713; separazione dei compiti: gli ambienti di sviluppo e test **devono** essere separati dagli ambienti di produzione.|
||&#x2713; dati sensibili provenienti da ambienti di produzione **NON DEVONO** essere utilizzati all'interno di ambienti di sviluppo/test.|
||&#x2713; tutte le modifiche DEVONO essere testate in un ambiente di test/sviluppo prima di essere introdotte nell'ambiente di produzione.|
||&#x2713; le richieste di **modifica vengono** generate e **autorizzate PRIMA di** entrare in produzione.|
||&#x2713; Come minimo, le richieste di modifica **DEVONO** includere:|
||&emsp;&#x25fc; Documentazione di impatto.|
||&emsp;&#x25fc; procedure di back-out documentate.|
||&#x2713; Le richieste di **modifica DEVONO** essere contrassegnate come complete, solo dopo **che è** stato eseguito un test delle funzionalità.|
|**Sviluppo/distribuzione di software sicuro**|La sicurezza deve essere all'avanguardia nelle procedure di sviluppo del software per ridurre al minimo il rischio di introdurre vulnerabilità di codifica nell'app o nel componente aggiuntivo, mantenendo in tal modo un ambiente sicuro e proteggendo i dati. Devono essere presenti le **seguenti** procedure di sicurezza per lo sviluppo di software: |
||&#x2713; È necessario disporre di un processo di sviluppo software consolidato e documentato che copre l'intero ciclo di vita dello sviluppo software.|
||&#x2713; tutte le modifiche al codice DEVONO essere esaminate e il processo di autorizzazione deve essere gestito da un utente diverso dallo sviluppatore originale.|
||&#x2713; procedure di codifica sicure e  le tecniche di revisione DEVONO affrontare le [10 principali 10](https://owasp.org/www-project-top-ten) classi di vulnerabilità CWE OWASP o [SANS Top 25.](https://www.sans.org/top25-software-errors)|
||&#x2713; gli **sviluppatori devono sottoporsi** a una formazione di codifica software sicura almeno ogni anno.|
||&#x2713; archivi di codice **devono** essere protetti da MFA.|
||&#x2713; devono essere presenti **controlli** di accesso adeguati per proteggere gli archivi di codice da modifiche di codice dannose.|
||**Nota:** Microsoft ha pubblicato il [Security Development Lifecycle](https://www.microsoft.com/en-us/securityengineering/sdl/) (SDL) seguito da Microsoft per supportare i requisiti di sicurezza e conformità all'interno dei propri prodotti. SDL aiuta gli sviluppatori a creare software più sicuro riducendo il numero e la gravità delle vulnerabilità nel software, riducendo al contempo i costi di sviluppo.|
|**Gestione account**| La gestione degli account dei componenti di sistema nell'ambito, nonché i criteri e le procedure di supporto **devono** soddisfare le condizioni seguenti: |
||&#x2713; le credenziali predefinite (fornitore o ISV) **sono** disabilitate o rimosse in tutti i componenti di sistema nell'ambito.|
||&#x2713; creazione, modifica ed eliminazione dell'account **DEVE** passare attraverso un processo di approvazione stabilito.|
||&#x2713; Gli account che non sono stati utilizzati  per più di 3 mesi devono essere disabilitati o eliminati, pertanto ISV deve disporre di un meccanismo per ottenere questo risultato.|
||&#x2713;criteri password complessa o altre misure di prevenzione adeguate **devono** essere configurate per proteggere le credenziali utente. I criteri password seguenti devono essere utilizzati come linee guida:|
||&emsp;&#x25fc; Lunghezza minima password di otto caratteri|
||&emsp;&#x25fc; soglia di blocco account non superiore a 10 tentativi|
||&emsp;&#x25fc; cronologia delle password di almeno cinque password|
||&emsp;&#x25fc; l'utilizzo di password complesse|
||&#x2713; gli account utente univoci DEVONO essere emessi a ogni utente; non è necessario utilizzare account condivisi.|
||&#x2713; i principi dei privilegi minimi **DEVONO** essere applicati a tutti gli utenti, il meccanismo utilizzato per ottenere questo risultato deve essere documentato (ad esempio, l'uso dei gruppi). |
||&#x2713; protezione avanzata dell'account di servizio appropriato **DEVE** essere documentata ed eseguita, ad esempio, l'accesso interattivo disabilitato, gli accessi limitati a host specifici e così via. |
||&#x2713; le soluzioni di Accesso **remoto DEVONO:** |
||&emsp;&#x25fc; utilizzare MFA (Multi Factor Authentication)|
||&emsp;&#x25fc; utilizzare un profilo di protezione dei dati in transito che soddisfi o superi il profilo di configurazione dei dati in transito, come descritto nell'Appendice A|
||&#x2713; Se la gestione del DNS pubblico si trova all'esterno dell'ambiente nell'ambito, tutti gli account utente in grado di apportare modifiche DNS DEVONO essere configurati per l'utilizzo di MFA.|
||**Nota:** i portali di gestione cloud dovranno inoltre soddisfare i requisiti di gestione degli account applicabili, vedere l'Appendice F per ulteriori dettagli.|
|**Rilevamento e prevenzione delle intrusioni (OPTIONAL)**| Verrà assegnato un credito aggiuntivo in caso di utilizzo di IDPS (Intrusion Detection and Prevention System) nel perimetro degli ambienti di supporto nell'ambito.  Di seguito sono riportati i controlli consigliati: |
||&#x2713; IDPS deve essere distribuito nel perimetro dell'ambiente di supporto |
||&#x2713; le firme IDPS devono essere mantenute correnti entro il giorno precedente |
||&#x2713; IDPS deve essere configurato per l'ispezione TLS |
||&#x2713; IDPS deve essere configurato per TUTTO il traffico in ingresso e in uscita |
||&#x2713; IDPS deve essere configurato per l'avviso |
|**Registrazione eventi** |La copertura della **registrazione DEVE** includere **tutti i** componenti e le applicazioni di sistema nell'ambito, inclusi i meccanismi di protezione antimalware. Devono essere registrati **gli** eventi seguenti:|
||&emsp;&#x25fc; gli utenti accedono ai componenti di sistema e all'applicazione|
||&emsp;&#x25fc; Tutte le azioni eseguite da un utente con privilegi elevati|
||&emsp;&#x25fc; tentativi di accesso logico non validi|
||&emsp;&#x25fc; creazione/modifica di account con privilegi|
||&emsp;&#x25fc; manomissione del registro eventi|
||&emsp;&#x25fc; disabilitazione degli strumenti di sicurezza; ad esempio, antimalware o registrazione eventi|
||&emsp;&#x25fc; registrazione antimalware; ad esempio, aggiornamenti, rilevamento malware, errori di analisi|
||&emsp;&#x25fc; eventi IDPS/WAF (se configurati)|
||I registri **eventi DEVONO** includere le informazioni seguenti:|
||&emsp;&#x25fc; utente |
||&emsp;&#x25fc; Tipo di evento |
||&emsp;&#x25fc; data e ora |
||&emsp;&#x25fc; indicatore esito positivo/negativo|
||&emsp;&#x25fc; Label per identificare il sistema interessato |
||La sincronizzazione **dell'ora** DEVE essere utilizzata in tutti i componenti di sistema nell'ambito per facilitare le indagini forensi.|
||La sincronizzazione **dell'ora DEVE** essere configurata per utilizzare la stessa origine ora primaria (e secondaria se necessario)|
||I sistemi pubblici (sistemi all'interno della RETE PERIMETRALE) **DEVONO** scrivere log in un archivio di registrazione centralizzato interno. L'archivio di registrazione centralizzato non deve essere all'interno della rete perimetrale.|
||Gli audit trail **DEVONO essere** protetti per garantire che i dati del registro non possono essere modificati da un attore di minacce. L'accesso all'archivio di registrazione centralizzato deve essere limitato solo al personale autorizzato.|
||I **registri DEVONO** essere immediatamente disponibili per 30 giorni. I dati **di** registrazione devono essere conservati per un minimo di 90 giorni.|
|**Revisione** |I processi di revisione, nonché i criteri e le procedure di supporto **DEVONO soddisfare** le condizioni seguenti:|
||&#x2713; eseguire revisioni giornaliere dei log o utilizzare la tecnologia di analisi e avviso dei registri automatizzati per esaminare gli eventi di tutti i componenti di sistema nell'ambito per identificare eventuali eventi di sicurezza potenziali.|
||&#x2713; I potenziali eventi di sicurezza **DEVONO** essere immediatamente seguiti.|
|**Avvisi** |I processi di avviso, nonché i criteri e le procedure di supporto **devono soddisfare** le condizioni seguenti: |
||&#x2713; eventi di sicurezza registrati che rappresentano un rischio per la sicurezza dei sistemi, delle operazioni o dei dati deve attivare un avviso immediato, ad esempio (non un elenco esaustivo):|
||&emsp;&#x25fc; creazione/modifica dell'account Privilege|
||&emsp;&#x25fc; di malware|
||&emsp;&#x25fc; Disabilitazione degli strumenti di sicurezza|
||&emsp;&#x25fc; manomissione del registro eventi|
||&emsp;&#x25fc; eventi IDPS/WAF (se configurati) |
||&#x2713; il personale deve essere sempre disponibile (24 ore su 24, 7 giorni su 7) per reagire agli avvisi attivati.|
|**Gestione dei rischi**|È necessario sviluppare e eseguire una metodologia di valutazione dei rischi che includa quanto segue:|
||&#x2713; Processo formalmente definito.|
||&#x2713; eseguito almeno ogni anno.|
||&#x2713; include tutti gli asset all'interno dell'ambiente nell'ambito.|
||&#x2713; identifica le minacce e le vulnerabilità di tutti gli asset inclusi.|
||&#x2713; include l'uso di matrici di impatto e probabilità definite.|
||&#x2713; la creazione di un registro dei rischi e di un piano di trattamento dei rischi corrispondente.|
|**Intervento in caso di incidente**|È necessario un piano accurato **di** risposta agli incidenti **e deve** includere come minimo:|
||&#x2713; La copertura minima dei componenti e delle applicazioni dei sistemi nell'ambito.|
||&#x2713; specifiche procedure di risposta agli incidenti per i modelli di minaccia previsti.|
||&#x2713; processo di comunicazione documentato, garantendo la notifica in tempo reale di tutte le parti interessate chiave e di qualsiasi altro organismo esterno rilevante, ad esempio; marche/acquirenti di pagamenti, enti normativi e autorità di vigilanza ([GDPR)](#gdpr)in linea con i requisiti di segnalazione richiesti.|
||&#x2713; la risposta agli incidenti viene aggiornata in base alle lezioni apprese, ai cambiamenti organizzativi e all'incorporazione degli sviluppi del settore.|
||&#x2713; formazione annuale per i membri del team di risposta agli incidenti.|

## <a name="data-handling-security-and-privacy"></a>Sicurezza e privacy per la gestione dei dati

I dati in transito tra l'utente dell'applicazione, i servizi intermedi e i sistemi ISV devono essere protetti tramite crittografia tramite una connessione TLS che supporta almeno TLS v1.1. *Vedere* [**l'appendice A**](#appendix-a).

Se l'applicazione recupera e archivia i dati M365, sarà necessario implementare uno schema di crittografia dell'archiviazione dei dati che segue la specifica definita [**nell'Appendice B.**](#appendix-a)

### <a name="test-specification"></a>Specifica di test

|Test | Controlli |
| -----------------------|-------------------------------- |
|**Dati in transito**| La trasmissione dei dati sensibili DEVE utilizzare almeno TLS 1.1 con alcune eccezioni descritte nell'Appendice A.|
||La trasmissione dei dati **sensibili DEVE** essere adeguatamente crittografata in base ai profili di crittografia descritti nell'appendice B.|
||La compressione TLS deve essere disabilitata.|
||HSTS (HTTP Strict Transport Security) **DEVE** essere configurato >= 15552000|
|**Dati in pausa**| L'archiviazione dei dati sensibili **DEVE** essere protetta in linea con i profili di crittografia descritti nell'appendice B che riguardano i requisiti minimi di crittografia, algoritmi, dimensioni delle chiavi, hash e autenticazione dei messaggi.|
||Tutti i tipi di dati archiviati DEVONO essere documentati.|
|**Conservazione ed eliminazione dei dati**|L'archiviazione **dei** dati sensibili deve essere mantenuta al minimo implementando criteri, procedure e processi di conservazione e eliminazione dei dati che includono al minimo:|
||&#x2713; documentare e limitare la quantità di archiviazione dei dati e il tempo di conservazione a quello richiesto per i requisiti legali, normativi e/o aziendali.|
||&#x2713; documentare e distribuire i processi per l'eliminazione sicura dei dati sensibili quando non sono più necessari, in linea con i criteri documentati.|
||&#x2713; documentare e distribuire un processo trimestrale per identificare ed eliminare in modo sicuro i dati sensibili archiviati che superano il periodo di conservazione definito.|
|**Gestione accesso ai dati**|La limitazione dell'accesso ai dati a coloro che hanno un motivo aziendale legittimo consente alle organizzazioni di impedire la gestione errata dei dati sensibili tramite inesperienza o malizia. I dati sensibili, ricevuti dall'app/componente aggiuntivo e l'accesso alle chiavi di crittografia, richiedono l'approvazione documentata (elettronica o scritta) per le parti autorizzate a tutti i livelli di accesso e devono includere un elenco di privilegi approvati e verificati che dimostrano che il criterio incorpora i requisiti specificati come segue: |
||&#x2713; Defining access needs and privilege assignments only to roles that specifically require such privileged access. |
||&#x2713; limitare l'accesso ai privilegi minimi necessari per eseguire le responsabilità del processo.|
||&#x2713; che siano stati stipulati accordi di condivisione dei dati con tutte le terze parti che utilizzano dati M365.|
|**GDPR**| Come parte del processo di certificazione Microsoft 365, devi dimostrare l'adesione al GDPR, tramite:|
||&#x2713; una revisione indipendente della conformità al GDPR da parte di una società di controllo esterna esperta. Sarà necessario inviare il report per la revisione o consentire all'analista di visualizzarlo. La relazione dovrebbe fornire dettagli sufficienti non solo per convalidare la valutazione del revisore esterno, ma anche per garantire una sufficiente sicurezza che la revisione esterna abbia confermato la conformità al GDPR.|
||oppure|
||&#x2713; l'invio di ulteriori prove per fornire ulteriore garanzia del tuo impegno per le leggi sulla privacy dei dati, come indicato di seguito:|
||&#x25fc; processo documentato di richiesta di accesso soggetto (SAR) progettato per soddisfare le richieste dei clienti e soddisfare il requisito di trenta giorni del GDPR. È consigliabile che siano stati evasi strumenti di individuazione dei dati adeguati per garantire che un SAR sia soddisfatto entro questi tempi. **Nota:** se questi strumenti non vengono utilizzati, dovrai dimostrare come funziona e dimostrare come i processi sono in grado di garantire l'individuazione di tutte le informazioni dell'oggetto dei dati.|
||&#x25fc;le note sulla privacy devono essere presenti nel sito Web e contenere le informazioni seguenti:
||
||Se non è disponibile un report GDPR indipendente, è necessario verificare quanto segue nell'ambito della valutazione della certificazione M365: |
||&#x2713; processo documentato di richiesta di accesso soggetto (SAR) progettato per soddisfare le richieste dei clienti e soddisfare il requisito di trenta giorni del GDPR.  È consigliabile che siano disponibili strumenti adeguati per l'individuazione dei dati per garantire che una sar sia evasa entro questi tempi, quando questi strumenti non vengono utilizzati, sarà necessario dimostrare come funziona e dimostrare come i processi sono in grado di garantire l'individuazione di tutte le informazioni dell'oggetto dei dati.|
||&#x2713; le note sulla privacy devono essere presenti nel sito Web e contenere le informazioni seguenti:|
||&emsp;&emsp;&#x25a1; contatto delle organizzazioni.|
||&emsp;&emsp;&#x25a1; Tipo di dati personali in fase di elaborazione.|
||&emsp;&emsp;&#x25a1; legge del trattamento dei dati personali (*Articolo 6*).|
||&emsp;&emsp;&#x25a1; Dettagli dei diritti dell'utente:|
||&emsp;&emsp;&#x25a1; diritto di essere informati (*Articoli13 e 14*).
||&emsp;&emsp;&#x25a1; diritto di accesso da parte dell'oggetto dei dati (*Articolo 15*).|
||&emsp;&emsp;&#x25a1; diritto di rettifica (*articolo 16*).|
||&emsp;&emsp;&#x25a1; diritto di cancellazione (*Articolo 17*).|
||&emsp;&emsp;&#x25a1; diritto alla restrizione del trattamento (*articolo 18*).|
||&emsp;&emsp;&#x25a1; diritto alla portabilità dei dati (*Articolo 20*).|
||&emsp;&emsp;&#x25a1; diritto all'oggetto (*Articolo 21*).|
||&emsp;&emsp;&#x25a1; diritti in relazione al contrassegno automatico delle decisioni, inclusa la profilatura (*Articolo 22*).|
||&#x2713; La condivisione delle informazioni con terze parti deve avere accordi in essere per garantire che il trattamento dei dati dell'oggetto dei dati sia in linea con le leggi sulla privacy dei dati.|

## <a name="optional-external-compliance-frameworks-review"></a>Revisione facoltativa dei framework di conformità esterni

Se nell'attestazione dell'autore sono stati inclusi framework di sicurezza esterni, gli analisti della certificazione dovranno verificare la validità di tali framework di conformità della sicurezza nell'ambito della valutazione della certificazione Microsoft 365.
Le evidenze per i seguenti framework di conformità della sicurezza esterna supportati includono:

* [ISMS](#isms) /  [IEC](#iec) - Specifica IS0/IEC 27001</h5>
* [PCI DSS](#pci-dss)
* [SOC 2](#soc-2)

La documentazione identificata nella [sezione Compliance Evidence](#compliance-evidence) verrà usata per eseguire questa revisione.

### <a name="test-specifications"></a>Specifiche di test

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

**Scambio di chiavi**

&emsp;&#x2713; ECDH è consentito. La **chiave DEVE** essere di almeno 256 bit. È necessario utilizzare la curva NIST P-256, P-384 o P-521.

&emsp;&#x2713; ECDH è consentito. La **chiave DEVE** essere di almeno 256 bit. È necessario utilizzare la curva NIST P-256, P-384 o P-521.

## <a name="appendix-c"></a>Appendice C

### <a name="evidence-collection--delta-for-iso-27001"></a>Raccolta di prove - Delta per ISO 27001

Se hai già raggiunto la conformità ISO27001, i seguenti delta (lacune) non interamente coperti da ISO 27001 dovranno essere esaminati come minimo nell'ambito di questa certificazione Microsoft 365.

> [!NOTE]
> Come parte della valutazione della certificazione Microsoft 365, l'analista di certificazione determinerà se uno dei controlli ISO 27001 mappati non è stato incluso nell'ambito della valutazione ISO 27001 e può anche decidere di campionare i controlli che sono stati trovati per fornire ulteriore garanzia. Eventuali requisiti mancanti da ISO 27001 dovranno essere inclusi nelle attività di valutazione della certificazione Microsoft 365.

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
> Nell'ambito della valutazione della certificazione Microsoft 365, l'analista di certificazione determinerà se uno dei controlli PCI DSS mappati non è stato incluso nell'ambito della valutazione PCI DSS e può anche decidere di campionare i controlli che sono stati trovati per fornire ulteriore garanzia. Eventuali requisiti mancanti nel DSS PCI dovranno essere inclusi nelle attività di valutazione della certificazione Microsoft 365.

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
> Come parte della valutazione della certificazione Microsoft 365, l'analista di certificazione determinerà se uno dei controlli SOC 2 mappati non è stato incluso nell'ambito della valutazione SOC 2 e può anche decidere di campionare i controlli che sono stati trovati come inclusi per fornire ulteriore garanzia. Eventuali requisiti mancanti nella valutazione SOC 2 dovranno essere inclusi nell'ambito delle attività di valutazione della certificazione Microsoft 365.

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

Microsoft riconosce che distribuirai applicazioni e archivi il codice di app/componenti aggiuntivi in ambienti di hosting diversi. Le responsabilità generali di alcuni controlli di sicurezza all'interno della certificazione Microsoft 365 dipendono dall'ambiente di hosting utilizzato. L'Appendice F esamina i tipi di distribuzione comuni e ne esegue il mapping con i controlli di sicurezza valutati nell'ambito del processo di valutazione. Sono stati identificati i seguenti tipi di distribuzione di hosting:

|  |  |
|-----|------|
|**ISV ospitato**|I tipi ospitati da ISV possono essere definiti come la posizione in cui sei responsabile dell'infrastruttura usata per supportare l'ambiente app/componenti aggiuntivi. Può trovarsi fisicamente all'interno dei data center o dei data center di terze parti con un servizio di co-posizione. In ultima analisi, si ha la completa proprietà e il controllo amministrativo sull'infrastruttura di supporto e sull'ambiente operativo.|
|**Infrastruttura come servizio (IaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)|Infrastruttura come servizio è un servizio che viene fornito in base al quale l'infrastruttura di supporto fisica viene gestita e gestita per loro conto dal provider di servizi cloud (CSP). In genere, la rete, l'archiviazione, i server fisici e l'infrastruttura di virtualizzazione sono tutti responsabilità del CSP. Il sistema operativo, il middleware, il runtime, i dati e le applicazioni sono le responsabilità dell'utente. Anche le funzionalità di firewall vengono gestite e gestite da terze parti, tuttavia la manutenzione della base di regole del firewall in genere è ancora responsabilità degli utenti.|
|**Platform as a Service/Serverless (PaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)| Con Platform as a Service, viene eseguito il provisioning con una piattaforma gestita che presenta un servizio che può essere utilizzato. Non è necessario eseguire le funzioni sysadmin poiché il sistema operativo e l'infrastruttura di supporto sono gestiti dal provider di servizi di configurazione. Questa operazione viene in genere utilizzata quando le organizzazioni non desiderano presentare un servizio Web e possono invece concentrarsi sulla creazione del codice sorgente dell'applicazione Web e sulla pubblicazione dell'applicazione Web nei servizi Web gestiti dal cloud.  Un altro esempio può essere un servizio di database in cui viene data connettività a un database, tuttavia l'infrastruttura di supporto e l'applicazione di database sono astratte dal consumer.   **Nota: Serverless e PaaS sono simili, quindi ai fini della certificazione Di Microsoft 365 Hosting Deployment Type's Serverless e PasS sono considerati gli stessi**|
|**Hybrid Hosted**|Con il tipo ospitato ibrido, è possibile utilizzare più tipi ospitati per supportare varie parti dell'ambiente di supporto. Questo può essere più il caso in cui app/componenti aggiuntivi vengono utilizzati in più stack M365. Anche se la certificazione Microsoft 365 supporterà la posizione in cui vengono sviluppate app/componenti aggiuntivi in più servizi M365, è necessario valutare l'intero ambiente di supporto (tra app/componenti aggiuntivi) in base a ognuno dei "Mapping di tipi ospitati" applicabili. In alcuni casi, è possibile utilizzare tipi ospitati diversi per un singolo componente aggiuntivo, in cui questa operazione viene eseguita, l'applicabilità dei criteri dovrà comunque seguire i criteri "Mapping di tipi ospitati" tra i vari tipi ospitati.|
|**Hosting condiviso**|L'hosting condiviso è il luogo in cui si ospita l'ambiente all'interno di una piattaforma condivisa da più singoli consumer. La specifica di certificazione Microsoft 365 non è stata scritta per conto di questo a causa dell'adozione del cloud, l'hosting condiviso non è comune. Se si ritiene che sia in uso, contattare Microsoft perché sarà necessario creare ulteriori requisiti per tenere conto dei rischi aggiuntivi in questo tipo di tipo di hosting.|


## <a name="appendix-g"></a>Appendice G

### <a name="microsoft-365-certification-process-workflow"></a>Flusso di lavoro del processo di certificazione Microsoft 365

![Flusso di lavoro](ProcessFlow.jpg)

## <a name="learn-more"></a>Altre informazioni

[Panoramica del programma di conformità delle app di Microsoft 365](~/overview.md)  
[Che cos'è l'attestazione di Microsoft 365 App Publisher?](~/docs/attestation.md)  
[Che cos'è la certificazione Microsoft 365?](~/docs/enterprise-app-certification-guide.md)

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
