---
ms.author: oromalle
title: Certificazione Microsoft 365 - Guida all'invio iniziale del documento
author: orionomalley
manager: tonybal
description: L'invio iniziale del documento fa parte della fase di pre-valutazione della certificazione.
keywords: Team di certificazione delle app Microsoft 365 conformità alla sicurezza m365 invio iniziale del documento
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 23c3cf7a64025bb7269adb35175e8d87bc64224e
ms.sourcegitcommit: ec1d4f7013722fe672830e3664b0fb8b0f33bd37
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/12/2022
ms.locfileid: "64784505"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365 Ceritification - Guida iniziale all'invio di documenti

L'invio iniziale del documento fa parte della fase di pre-valutazione della certificazione. Le informazioni fornite forniranno agli analisti di certificazione il background necessario per identificare quali controlli e componenti di sistema saranno inclusi nell'ambito della valutazione. Questo documento è destinato a servire solo come esempio di ciò che ci si aspetta dall'invio iniziale del documento. La documentazione fornita varia a seconda del modo in cui la soluzione viene progettata, implementata e gestita.

## <a name="what-is-the-hosting-environment-or-service-model-used-to-run-your-app"></a>Qual è l'ambiente di hosting o il modello di servizio usato per eseguire l'app?
- L'infrastruttura distribuita come servizio (IaaS) è un modello di servizio cloud in cui il provider di servizi cloud ospita i componenti dell'infrastruttura, ma gli ISV sono comunque responsabili della distribuzione e della gestione dei componenti singolarmente, ad esempio Macchine virtuali/sistemi operativi, archivi dati e componenti di rete. Di seguito sono riportati esempi di macchine virtuali di Azure e Archiviazione dischi di Azure.
- Platform as a Service (PaaS) è un modello di servizio cloud in cui i componenti dell'infrastruttura vengono gestiti dal provider di servizi cloud. Gli ISV sono responsabili solo della distribuzione di applicazioni e servizi personalizzati. Ne sono esempi app Azure Servizi, Funzioni di Azure e Rete CDN di Azure.
- ISV Ospitato in questo contesto significa che non viene usato alcun provider di servizi cloud. L'ISV gestisce fisicamente i propri server, dischi, rete in modo indipendente in locale.
- Ibrido in questo contesto significa che viene usato uno dei modelli precedenti. Ad esempio, alcuni ISV possono scegliere di usare una combinazione di servizi IaaS e servizi PaaS per supportare l'app oppure possono avere alcuni componenti ospitati ISV locali e esternalizzare altri a un provider di servizi cloud. Se si usa uno di più modelli di servizio, selezionare ibrido.

## <a name="penetration-test-report"></a>Report test di penetrazione

Includere il report di test di penetrazione completo con le date che rilevano che è stato completato negli ultimi 12 mesi. 
-   Questo report deve essere prodotto da test di penetrazione manuali, non può essere l'output di uno strumento di analisi/test automatizzato.
-   Questo report deve includere l'ambiente che supporta la distribuzione dell'app/aggiunta insieme a qualsiasi altro ambiente che supporti il funzionamento dell'app o dei componenti aggiuntivi.


## <a name="system-component-inventory"></a>Inventario componenti di sistema

Un inventroy aggiornato di tutti i componenti di sistema utilizzati dall'infrastruttura di supporto. Verrà usato per facilitare il campionamento durante l'esecuzione della fase di valutazione. Se l'ambiente include PaaS, sarebbe utile fornire dettagli su tutti i servizi PaaS usati.

**Nota:** IaaS/PaaS non avrebbe alcun hardware sotto il controllo ISV.  In questo caso, specificare un elenco o uno screenshot di tutte le risorse viruali.

**Esempio:**

|Nome asset|Tipo di asset|Descrizione|Produttore|Modello|
|---|---|---|---|---|
|D212|Computer Windows|Macchina virtuale|N/D|N/D|
|LT101|Portatili|Workstation|Microsoft|Superficie 3|
|C2938|Opzione|Opzione|N/D|N/D|
|LXM2|Computer Linux|Computer di test|N/D|N/D|


## <a name="software-inventory"></a>Inventario software

Un inventario aggiornato di tutti gli asset software, incluso tutto il software usato nell'ambiente nell'ambito, insieme alle versioni.

**Esempio:**

|Software|Publisher|Versione|Scopo|
|---|---|---|---|
|Server Windows|Microsoft 2016 |Build 14393|Sistema operativo server per l'ambiente di produzione|
|Linux Ubuntu|N/D|16.04 (Xenial)|Sistema operativo server in uso all'interno della rete perimetrale.|
|Esxi|Vmware|6.5.0 (build 13004031)|Usato per supportare i server virtuali.|
|Mysql (Windows)|N/D|8.0.2.1|Server di database per archiviare la cronologia chat.|
|Tomcat|Apache|7.0.92|Portale clienti.|
|IIS|Microsoft|10.0|Supporta le API.|


## <a name="third-party-dependencies"></a>Dipendenze di terze parti

Documentazione che elenca tutte le dipendenze usate dall'app/componente aggiuntivo con le versioni correnti in esecuzione.

**Esempio:**

|Dipendenze Web|Versione corrente in uso|
|----|----|
|Jquery|3.5.1|
|Reagire|16.13.1|
|Bootstrap|4.5.2|
|Express|4.17.1|
|Angular|10.0.14|
|AngularJS|1.8.0|


## <a name="public-ip-addresses"></a>Indirizzi IP pubblici

Dettagli su tutti gli URL e gli indirizzi IP pubblici usati dall'infrastruttura di supporto. Ciò deve includere l'intervallo IP instradabile completo allocato all'ambiente, a meno che non sia stata implementata una segmentazione adeguata per dividere l'intervallo in uso (sarà necessaria un'adeguata prova di segmentazione).

**Esempio:**

|URL|Indirizzo IP|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|40.113.200.201|
|https://customerapi.contoso.com|40.113.200.202|
|https://bot.contoso.com|40.113.200.202|
|N/D (Jump Server)|40.113.200.200|


## <a name="resource-endpoints"></a>Endpoint risorsa

Api Name Endpoint Address Contoso Customer API https://customerapi.contoso.com Contoso servizio Bot https://bot.contoso.com Contoso Files APIhttps://filesapi.contoso.com

Elenco completo di tutti gli endpoint API usati dall'app, inclusi gli endpoint delle risorse sviluppati internamente ed esterni. Per comprendere l'ambito dell'ambiente, specificare i percorsi degli endpoint API all'interno dell'ambiente.

**Esempio:**

|Nome API|  Indirizzo endpoint|
|-|-|
|API del cliente Contoso|  https://customerapi.contoso.com|
|Contoso servizio Bot|   https://bot.contoso.com|
|API File Contoso| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>Diagramma dell'architettura

Diagramma dell'architettura logica che rappresenta una panoramica generale dell'infrastruttura di supporto dell'app/componente aggiuntivo. Deve includere tutti gli ambienti di hosting e l'infrastruttura di supporto che supporta l'app/componente aggiuntivo. Questo diagramma DEVE descrivere tutti i diversi componenti di sistema di supporto all'interno dell'ambiente per aiutare gli analisti di certificazione a comprendere i sistemi nell'ambito e a determinare il campionamento. Indicare anche il tipo di ambiente di hosting usato. ISV Ospitato, IaaS, PaaS o Ibrido. Dove viene usato PaaS, indicare i vari servizi PaaS usati per fornire i servizi di supporto all'interno dell'ambiente.

![Diagramma dell'architettura](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>Diagramma Flusso di dati

Flow diagrammi che illustrano in dettaglio quanto segue:
-   Flussi di dati da e verso l'app/componente aggiuntivo (inclusi i dati dei clienti).
-   Flussi di dati all'interno dell'infrastruttura di supporto (se applicabile)
-   Diagrammi che evidenziano dove e quali dati vengono archiviati, come vengono passati i dati a terze parti esterne (inclusi i dettagli di quali terze parti) e come i dati vengono protetti in transito su reti aperte/pubbliche e inattivi.

![Diagramma Flusso di dati](../media/Dataflowdiagram.png)



