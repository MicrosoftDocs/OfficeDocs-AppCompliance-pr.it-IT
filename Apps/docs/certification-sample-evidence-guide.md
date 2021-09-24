---
title: Microsoft 365 Certificazione - Guida alle prove di esempio
author: OrionOmalley
ms.author: oromalle
description: Microsoft 365 Panoramica della guida di esempio per l'invio di prove di certificazione
keywords: attestazione della certificazione dell'app Microsoft 365 appaltatori di certificazioneEvidenze di esempio per l'invio di prove
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: d246f1437a60dd3b55d51e22cb5701b4cb9f46bf
ms.sourcegitcommit: 1e461d44be2da90b41fdcb60b35a6a180d52c9d6
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/23/2021
ms.locfileid: "59497139"
---
# <a name="microsoft-365-certification---sample-evidence-guide"></a>Microsoft 365 Certificazione - Guida alle prove di esempio

## <a name="overview"></a>Panoramica

Queste linee guida sono state create per fornire agli ISV assistenza sul livello di dettaglio necessario per i controlli Microsoft 365 certificazione. Fornisce inoltre indicazioni su come strutturare l'invio di prove, insieme ad esempi dei tipi di prove che potrebbero essere potenzialmente utilizzate per soddisfare i controlli di certificazione. Gli esempi condivisi in questo documento non rappresentano l'unica prova che può essere utilizzata per fornire la garanzia che i controlli vengono soddisfatti, ma agiscono solo come linee guida per il tipo di informazioni che possono aiutare gli analisti della certificazione a fornire le prove necessarie per aiutarli con questa affermazione. Nota: - Le interfacce, gli screenshot e la documentazione effettivi usati per soddisfare i requisiti variano a seconda dell'utilizzo del prodotto, della configurazione del sistema e dei processi interni. Inoltre, tenere presente che se è necessaria la documentazione relativa ai criteri o alle procedure, l'ISV sarà necessario per inviare i documenti EFFETTIVI e non gli screenshot, come illustrato in alcuni esempi. È consigliabile seguire queste linee guida per evitare che la valutazione sia ritardata a causa di prove insufficienti. 

Nella certificazione sono disponibili due sezioni che richiedono invii:
1. Invio documento iniziale: un piccolo set di documenti di alto livello necessari per l'ambito della valutazione.
1. L'invio di prove: il set completo di prove necessarie per la valutazione della certificazione 


## <a name="initial-document-submission-guide"></a>Guida all'invio di documenti iniziale

## <a name="evidence-submission-sample-evidence-guide"></a>Guida alle prove di esempio per l'invio di prove

### <a name="structure"></a>Struttura 

Questo è direttamente correlato alle categorie fornite nella Guida agli invii di Microsoft 365 online. Si noti che è meglio utilizzare questa guida direttamente insieme al foglio di calcolo dell'elenco di controllo di certificazione Microsoft 365 fornito per evitare malintesi a cui si riferisce ogni gruppo di controllo in questa guida. Le indicazioni fornite in questo documento sono dettagliate come segue:
- Dominio di sicurezza: i tre domini di sicurezza in cui sono raggruppati tutti i controlli: sicurezza delle applicazioni, sicurezza operativa e sicurezza dei dati e privacy.
- Controlli: = Descrizione attività di valutazione - Questi controlli e il numero associato (n.) vengono presi direttamente dall'elenco Microsoft 365 di certificazione.  
- Intento: = l'intento del motivo per cui il controllo di sicurezza è incluso nel programma e il rischio specifico che è destinato a mitigare.  L'auspicio è che queste informazioni forniranno agli ISV il ragionamento dietro il controllo per comprendere meglio i tipi di prove che devono essere raccolte e a quali ISV devono prestare attenzione e avere consapevolezza e comprensione per produrre le loro prove.
- Linee guida sull'evidenza di esempio: = Fornite per guidare le attività di raccolta delle prove nel foglio di calcolo elenco di controllo di certificazione Microsoft 365, ciò consente agli ISV di visualizzare chiaramente esempi del tipo di prova che possono essere utilizzati dall'analista di certificazione che lo utilizzerà per certificazione sicura che un controllo è in atto e mantenuto, ma non è affatto esaustivo.
- Esempio di prova: = In questa sezione vengono fornite schermate di esempio e immagini di potenziali prove acquisite su ognuno dei controlli nel foglio di calcolo dell'elenco di controllo di certificazione di Microsoft 365, in particolare per i domini di sicurezza e sicurezza dei dati operativi e della privacy (schede all'interno del foglio di calcolo). Si noti che qualsiasi informazione con frecce e caselle rosse all'interno degli esempi consente di comprendere meglio i requisiti necessari per soddisfare qualsiasi controllo.

### <a name="security-domain-application-security"></a>Dominio di sicurezza: sicurezza dell'applicazione

Il dominio Application Security è incentrato sulla garanzia di poter produrre un report di test di penetrazione emesso negli ultimi 12 mesi che mostra che la tua app non presenta vulnerabilità in sospeso. L'unico invio necessario è un report pulito di una società indipendente affidabile. 


### <a name="security-domain-operational-security--secure-development"></a>Dominio di sicurezza: Sicurezza operativa / Sviluppo protetto

Il dominio di sicurezza "Sicurezza operativa/sviluppo sicuro" è progettato per garantire che gli ISV implementino una serie avanzata di tecniche di mitigazione della sicurezza contro una miriade di minacce affrontate dagli operatori delle minacce.  Questo è progettato per proteggere l'ambiente operativo e i processi di sviluppo software per creare ambienti sicuri.

#### <a name="malware-protection---anti-virus"></a>Protezione antimalware - Anti-Virus

**Controllo 1:** Fornire i criteri e le procedure documentati che promuovono le procedure consigliate anti-virus.
- Intento: lo scopo di questo controllo è valutare la comprensione da parte di un ISV dei problemi che devono affrontare quando si considera la minaccia dei virus informatici. Stabilendo e utilizzando le procedure consigliate del settore nello sviluppo di criteri e processi antivirus, un ISV fornisce una risorsa personalizzata per la capacità dell'organizzazione di mitigare i rischi che il malware deve affrontare, elencando le procedure consigliate per il rilevamento e l'eliminazione di virus e fornisce la prova che i criteri documentati forniscono indicazioni sulla sicurezza consigliate per l'organizzazione e i dipendenti. Documentando un criterio e una procedura di distribuzione delle decenzie antimalware da parte dell'ISV, si garantisce l'implementazione e la manutenzione coerenti di questa tecnologia per ridurre il rischio di malware per l'ambiente.

- Linee guida sull'evidenza di esempio: fornire una copia dei criteri antivirus/antimalware in cui sono dettagliati i processi e le procedure implementati all'interno dell'infrastruttura per promuovere le procedure consigliate per antivirus/malware.
Esempio di prova

- Esempio di prova:

![Immagine](../media/AMWExample1.png) App/supporti/AMWExample1.png
