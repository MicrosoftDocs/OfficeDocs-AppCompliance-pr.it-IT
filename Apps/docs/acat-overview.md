---
title: Strumento di automazione della conformità delle app per Microsoft 365
author: xu-hong
ms.author: hongxu6
manager: zhshang
description: Panoramica dello strumento di automazione della conformità delle app per Microsoft 365
keywords: Microsoft 365 di automazione della certificazione delle app
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 5e3fbc062c1887a205a7b99a85a292ad9a64f8d0
ms.sourcegitcommit: 0865622c8abffc11115e56d966729e5318d67ab9
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/20/2022
ms.locfileid: "65608809"
---
# <a name="app-compliance-automation-tool-for-microsoft-365"></a>Strumento di automazione della conformità delle app per Microsoft 365
In questo articolo si apprenderà cos'è lo strumento di automazione della conformità delle app per Microsoft 365 (ACAT) e come semplifica la conformità e ottenere la certificazione Microsoft 365.

> [!IMPORTANT]
> ACAT è attualmente disponibile in anteprima privata. Se si vuole partecipare al programma di anteprima privato, iscriversi [qui](https://aka.ms/acat/private/signup).

> [!NOTE]
> Per fornire commenti e suggerimenti all'anteprima privata di ACAT, è possibile iniziare da questo [modulo](https://aka.ms/acat/feedback). Il team del prodotto ACAT ti seguirà il prima possibile una volta ricevuti i tuoi messaggi. 

## <a name="what-is-app-compliance-automation-tool-for-microsoft-365"></a>Che cos'è lo strumento di automazione della conformità delle app per Microsoft 365
App Compliance Automation Tool for Microsoft 365 (ACAT) è un servizio nel portale di Azure che consente di semplificare il percorso di conformità per qualsiasi app che utilizza Microsoft 365 dati dei clienti e viene pubblicata tramite il Centro per i partner. App Compliance Automation Tool for Microsoft 365 è uno strumento di automazione della conformità incentrato sull'applicazione che consente di completare Microsoft 365 certificazione con maggiore facilità e praticità. In Anteprima privata, ACAT è disponibile per le app in esecuzione in Azure.

Con questo strumento, sarà possibile definire rapidamente il limite di conformità per le applicazioni, monitorare automaticamente i risultati della conformità e completare più facilmente il controllo di conformità. Il limite di conformità è l'infrastruttura cloud che supporta il recapito dell'app e di tutti i sistemi back-end con cui l'app può comunicare.

Oltre a offrire un percorso più rapido verso la certificazione Microsoft 365, ACAT può essere utile in vari scenari di conformità per le applicazioni Microsoft 365:

- Procedura dettagliata di visualizzazione e correzione per le responsabilità di certificazione Microsoft 365.
- Report giornalieri automatici che consentono di ottenere continuamente risultati di conformità.
- Procedure consigliate per la sicurezza e la conformità che possono essere usate come indicazioni nella fase iniziale del ciclo di vita dell'applicazione.

## <a name="benefits-of-acat"></a>Vantaggi di ACAT
Percorso di conformità incentrato sulle applicazioni.
- ACAT segnala quotidianamente lo stato di conformità per l'ambiente cloud delle applicazioni, che è possibile integrare con la strategia di conformità dell'infrastruttura cloud corrente.
- Gli sviluppatori possono richiamare ACAT anche durante la fase di sviluppo di app.

Accelera il processo di certificazione Microsoft 365.
- ACAT automatizza completamente alcuni controlli di certificazione Microsoft 365.
- C'è un elenco di automazione in continua crescita che viene attivamente sviluppato da Microsoft.

Integrazione nativa con Microsoft 365 flusso di lavoro di certificazione.
- ACAT è completamente integrato con il Centro per i partner per Microsoft 365 scopo di certificazione.

## <a name="concepts-of-acat"></a>Concetti di ACAT
### <a name="regulatory-compliance-report"></a>Report conformità alle normative 
In ACAT è possibile controllare lo stato di conformità dell'applicazione creando un report di conformità. È possibile definire il limite di conformità per l'applicazione specificando le risorse di Azure che compilano l'applicazione. Creare più report per un'applicazione, in base a diversi ambienti e fasi di sviluppo.

Dopo aver creato il report, ACAT inizierà a raccogliere i dati di conformità in base all'ora di attivazione predefinita e quindi genererà automaticamente i risultati della conformità come report. Nel frattempo, ACAT continuerà a monitorare continuamente le modifiche di conformità per il report di conformità, fino a quando non si sceglie di eliminare il report.

### <a name="microsoft-365-certification-control-results"></a>Microsoft 365 risultati del controllo di certificazione
Nel report conformità alle normative i risultati della conformità sono organizzati in base ai controlli con gli stati corrispondenti contrassegnati da ACAT:
- **Superato**: non ci sono errori per i controlli di certificazione Microsoft 365 completamente automatizzati.
- **Non riuscito**: vengono rilevate responsabilità dei clienti non riuscite per i controlli di certificazione Microsoft 365 completamente automatizzati.
- **Superato - Evidenza aggiuntiva necessaria**: non sono presenti errori per i controlli di certificazione Microsoft 365 *parzialmente automatizzati*.
- **Non riuscita- Evidenza aggiuntiva necessaria**: sono stati rilevati errori nelle responsabilità dei clienti per i controlli di certificazione Microsoft 365 *parzialmente automatizzati*.
- **Controllo manuale**: ACAT non automatizza alcuna responsabilità del cliente per i controlli di certificazione Microsoft 365.

### <a name="customer-responsibility"></a>Responsabilità del cliente
A ogni controllo è associato un set di responsabilità dei clienti che devono essere soddisfatte. Le responsabilità vengono mantenute dall'utente nelle aree seguenti: dati, endpoint, account, gestione degli accessi e così via.

ACAT raccoglie i dati per ogni responsabilità del cliente e restituisce un risultato di valutazione. Fornisce anche un'azione correttiva, che è la nostra guida che consente di allinearsi agli standard di certificazione Microsoft 365.


## <a name="faq"></a>Domande frequenti
### <a name="what-are-manual-controls-and-partially-automated-controls"></a>Cosa sono i controlli manuali e i controlli parzialmente automatizzati?
Ogni controllo di conformità è associato a un set di responsabilità dei clienti, per cui ACAT raccoglie i dati di conformità. Tuttavia, non tutti i controlli per la certificazione Microsoft 365 sono attualmente coperti da ACAT (è in corso uno sforzo per espandere la copertura). Per il controllo parzialmente automatizzato, ACAT automatizza parti delle responsabilità dei clienti. È possibile usare lo stato di conformità per riferimento, ma non per Microsoft 365 controllo di certificazione direttamente. Per i controlli manuali, ACAT attualmente non automatizza le responsabilità dei clienti.

### <a name="i-made-the-suggested-changes-base-on-the-remediation-suggestion-yet-the-control-is-still-failing"></a>Sono state apportate le modifiche suggerite in base al suggerimento di correzione, ma il controllo continua a non riuscire
Dopo aver eseguita un'azione per risolvere l'errore, è necessario attendere che ACAT recuperi i risultati della valutazione aggiornati per aggiornare lo stato del controllo. Le valutazioni vengono eseguite ogni 24 ore all'ora di attivazione pre-impostata.

### <a name="how-is-the-compliance-report-used-in-the-certification-process"></a>Come viene usato il report di conformità nel processo di certificazione?
ACAT è perfettamente integrato con il [Centro](https://partner.microsoft.com/dashboard) per i partner per completare il percorso di certificazione Microsoft 365. Durante la creazione del report di conformità, è possibile modificare la configurazione della certificazione Microsoft 365, ovvero il GUID dell'offerta. È facoltativo durante la creazione ed è possibile configurarlo in un secondo momento quando si avvia la pubblicazione dell'applicazione.

## <a name="learn-more"></a>Ulteriori informazioni

* [Informazioni di base con ACAT](https://aka.ms/acat/getstarted)
* [Altre informazioni sulla certificazione Microsoft 365](https://aka.ms/acat/m365cert)
