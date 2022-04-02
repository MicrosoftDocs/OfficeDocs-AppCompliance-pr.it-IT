---
ms.author: oromalle
title: Microsoft 365 - Guida all'invio di documenti iniziale
author: orionomalley
manager: tonybal
description: Microsoft 365 granulare della Guida all'invio della certificazione
keywords: team di certificazione delle app Microsoft 365 sicurezza conformità m365 invio documento iniziale
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 66afcbd482ee1269ce21e2af6fdeea5026b294ee
ms.sourcegitcommit: b7ef94cf5fb12f6730a8688834ceee4f8fe8e0da
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/25/2022
ms.locfileid: "64463279"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365 Ceritification - Guida all'invio di documenti iniziale

L'invio del documento iniziale fa parte della fase di prevalutazione della certificazione. Le informazioni fornite offriranno agli analisti di certificazione le informazioni necessarie per identificare i controlli e i componenti di sistema che saranno nell'ambito della valutazione. Questo documento ha lo scopo di fungere solo da esempio di ciò che è previsto per l'invio iniziale del documento. La documentazione fornita varia a seconda di come la soluzione viene progettata, implementata e gestita.

## <a name="what-is-the-hosting-environment-or-service-model-used-to-run-your-app"></a>Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app?
- Infrastructure as a Service (IaaS) è un modello di servizio cloud in cui il provider di servizi cloud ospita i componenti dell'infrastruttura, ma gli ISV sono ancora responsabili della distribuzione e della gestione dei componenti singolarmente, ad esempio macchine virtuali/sistemi operativi, archivi dati e componenti di rete. Esempi di questo tipo sono Azure Virtual Machine e Azure Disk Archiviazione.
- Platform as a Service (PaaS) è un modello di servizio cloud in cui i componenti dell'infrastruttura vengono gestiti dal provider di servizi cloud. Gli ISV sono responsabili solo della distribuzione delle proprie applicazioni e servizi. Esempi sono Azure App Services, Azure Functions e Rete CDN di Azure.
- ISV Ospitato in questo contesto significa che non viene utilizzato alcun provider di servizi cloud. L'ISV gestisce fisicamente i propri server, dischi, rete in modo indipendente in locale.
- Ibrido in questo contesto significa che viene utilizzato uno dei modelli precedenti. Ad esempio, alcuni ISV possono scegliere di usare una combinazione di servizi IaaS e servizi PaaS per supportare l'app oppure potrebbero avere alcuni componenti ospitati da ISV locali e esternalizzare altri a un provider di servizi cloud. Se si utilizza uno di più modelli di servizio, selezionare ibrido.

## <a name="penetration-test-report"></a>Report test di penetrazione

Includi il report completo dei test di penetrazione con le date che segnalano che è stato completato negli ultimi 12 mesi. 
-   Questo report deve essere prodotto da test di penetrazione manuali, non può essere l'output di uno strumento di analisi/test automatizzato.
-   Questo report deve includere l'ambiente che supporta la distribuzione dell'app/aggiunta insieme a qualsiasi ambiente aggiuntivo che supporti il funzionamento dell'app o dei componenti aggiuntivi.


## <a name="system-component-inventory"></a>Inventario componenti di sistema

Un'inventaroy aggiornata di tutti i componenti di sistema utilizzati dall'infrastruttura di supporto. Verrà usato per facilitare il campionamento durante l'esecuzione della fase di valutazione. Se l'ambiente include PaaS, sarebbe utile fornire dettagli su tutti i servizi PaaS utilizzati.

**Nota:** IaaS/PaaS non dispone di hardware sotto il controllo isv.  In questo caso, fornire un elenco o uno screenshot di tutte le risorse viruali.

**Esempio:**

|Nome risorsa|    Tipo di risorsa| Descrizione|    Produttore|   Modello|
|-|-|-|-|-|
|D212|  Windows Computer|   Macchina virtuale|    N/D| N/D|
|LT101| Portatili| Workstation|    Microsoft|  Surface 3|
|C2938| Opzione| Opzione|N/D|N/D|     
|LXM2|  Linux Machine|  Computer di test|N/D|N/D|       


## <a name="software-inventory"></a>Inventario software

Un inventario aggiornato di tutti gli asset software, incluso tutto il software utilizzato nell'ambiente nell'ambito insieme alle versioni.

**Esempio:**

|Software|  Publisher|  Versione|     Finalità|
|-|-|-|-|
|Server Windows|    Microsoft 2016 | Build 14393| Sistema operativo server per l'ambiente di produzione|.
|Linux Ubuntu|  N/D|    16.04 (Xenial)| Sistema operativo server in uso all'interno della rete perimetrale.|
|ESXi|  VMWare| 6.5.0 (Build 13004031)| Utilizzato per supportare i server virtuali.|
|Mysql (Windows)|   N/D|    8.0.2.1|    Server di database per archiviare la cronologia delle chat.|
|Tomcat|        Apache| 7.0.92| Portale clienti.|
|IIS|   Microsoft|  10.0|   Supporta le API.|


## <a name="third-party-dependencies"></a>Dipendenze di terze parti

Documentazione che elenca tutte le dipendenze usate dall'app o dal componente aggiuntivo con le versioni correnti in esecuzione.

**Esempio:**

|Dipendenze Web|  Versione corrente in uso|
|-|-|
|JQuery|    3.5.1|
|Reagire| 16.13.1|
|Bootstrap| 4.5.2|
|Express|   4.17.1|
|Angular|   10.0.14|
|AngularJS| 1.8.0|


## <a name="public-ip-addresses"></a>Indirizzi IP pubblici

Descrizione dettagliata di tutti gli indirizzi IP pubblici e gli URL utilizzati dall'infrastruttura di supporto. Deve includere l'intervallo IP instradabile completo allocato all'ambiente, a meno che non sia stata implementata una segmentazione adeguata per suddividere l'intervallo in uso (sarà necessaria una prova adeguata della segmentazione).

**Esempio:**

|URL|  Indirizzo IP|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|  40.113.200.201|
|https://customerapi.contoso.com|   40.113.200.202|
|https://bot.contoso.com|   40.113.200.202|
|N/D (Jump Server)| 40.113.200.200|


## <a name="resource-endpoints"></a>Endpoint risorsa

API Name    Endpoint Address Contoso Customer API    https://customerapi.contoso.com Contoso Bot Service https://bot.contoso.com Contoso Files API   https://filesapi.contoso.com

Elenco completo di tutti gli endpoint API usati dalla tua app, inclusi gli endpoint delle risorse esterne e sviluppati internamente. Per comprendere meglio l'ambito dell'ambiente, fornire i percorsi degli endpoint API all'interno dell'ambiente.

**Esempio:**

|Nome API|  Endpoint Address|
|-|-|
|API del cliente Contoso|  https://customerapi.contoso.com|
|Contoso Bot Service|   https://bot.contoso.com|
|Contoso Files API| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>Diagramma architettonico

Diagramma dell'architettura logica che rappresenta una panoramica generale dell'infrastruttura di supporto dell'app o del componente aggiuntivo. Deve includere tutti gli ambienti di hosting e l'infrastruttura di supporto che supporta l'app/componente aggiuntivo. Questo diagramma DEVE illustrare tutti i diversi componenti di sistema di supporto all'interno dell'ambiente per aiutare gli analisti della certificazione a comprendere i sistemi nell'ambito e a determinare il campionamento. Indicare anche il tipo di ambiente di hosting utilizzato. ISV ospitato, IaaS, PaaS o ibrido. Se viene utilizzato PaaS, indicare i vari servizi PaaS utilizzati per fornire i servizi di supporto all'interno dell'ambiente.

![Diagramma architettonico](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>Diagramma Flow dati

Flow diagrammi che illustrano in dettaglio quanto segue:
-   I dati fluisce da e verso l'app/componente aggiuntivo (inclusi i dati dei clienti).
-   Flussi di dati all'interno dell'infrastruttura di supporto (se applicabile)
-   Diagrammi che evidenziano dove e quali dati vengono archiviati, come i dati vengono passati a terze parti esterne (inclusi i dettagli di quali terze parti) e come i dati sono protetti in transito su reti aperte/pubbliche e in pausa.

![Diagramma Flow dati](../media/Dataflowdiagram.png)



