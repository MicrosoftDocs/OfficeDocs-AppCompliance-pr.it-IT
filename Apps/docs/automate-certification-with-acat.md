---
title: Automatizzare la certificazione Microsoft 365 con lo strumento di automazione della conformità delle app per Microsoft 365
description: Uso dello strumento di automazione della conformità delle app per Microsoft 365 (ACAT) per automatizzare la certificazione Microsoft 365.
author: yjin81
ms.author: yajin1
manager: zhshang
ms.service: certification
ms.topic: how-to
ms.date: 04/13/2022
ms.custom: template-how-to
ms.openlocfilehash: 6a18e64f3b75f6d197c9867830d0a061ce298584
ms.sourcegitcommit: 0865622c8abffc11115e56d966729e5318d67ab9
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/20/2022
ms.locfileid: "65608791"
---
# <a name="automate-microsoft-365-certification-with-app-compliance-automation-tool-for-microsoft-365"></a>Automatizzare la certificazione Microsoft 365 con lo strumento di automazione della conformità delle app per Microsoft 365

App Compliance Automation Tool for Microsoft 365 (ACAT) collabora con il programma di conformità delle app Microsoft 365 per soddisfare alcuni dei controlli necessari per la certificazione Microsoft 365. Questo articolo consente di iniziare a usare ACAT e usare le valutazioni di conformità con la certificazione Microsoft 365.

> [!IMPORTANT]
> ACAT è attualmente disponibile in anteprima privata. Se si vuole partecipare al programma di anteprima privato, iscriversi [qui](https://aka.ms/acat/private/signup).

> [!NOTE]
> Per fornire commenti e suggerimenti all'anteprima privata di ACAT, è possibile iniziare da questo [modulo](https://aka.ms/acat/feedback). Il team del prodotto ACAT ti seguirà il prima possibile una volta ricevuti i tuoi messaggi. 

## <a name="create-your-first-compliance-report-to-onboard-acat"></a>Creare il primo report di conformità per l'onboarding di ACAT

ACAT consente di concentrarsi sulla conformità dell'applicazione o dell'ambiente specifico di un'applicazione , ad esempio produzione, gestione temporanea e così via. Consente di creare un report di **conformità** in cui è possibile definire il limite di conformità in base all'infrastruttura cloud dell'applicazione o all'ambiente specifico di un'applicazione.

> [!IMPORTANT]
> Poiché ACAT è in anteprima privata, non è possibile cercarlo direttamente in portale di Azure. Iscriversi al [programma di anteprima privata ACAT](https://aka.ms/acat/private/signup) e ottenere l'accesso dal team di supporto.

- Cercare e avviare ***App Compliance Automation Tool per Microsoft 365*** in portale di Azure.
- Passare a ***Report*** da a sinistra.

:::image type="complex" source="../media/ACAT/getstarted-create-report-inline.png" lightbox="../media/ACAT/getstarted-create-report.png" alt-text="Creare un report di conformità":::
   Passare a Report per creare un nuovo report di conformità :::image-end:::

- Selezionare ***Crea nuovo report*** per iniziare a creare il primo report di conformità con la configurazione corretta. 
    - **Informazioni generali**
        - **Nome report**: il nome del report di conformità è obbligatorio e non può essere duplicato all'interno del tenant. Potrebbe essere la combinazione di numeri, alfabeti e caratteri di sottolineatura. È consigliabile usare un nome significativo con il report di conformità, ad esempio, che indica l'applicazione o l'ambiente specifico.
        - **Tempo di attivazione**: ACAT genererà le valutazioni di conformità per il report di conformità su base giornaliera. Questa configurazione viene usata per specificare quando deve essere attivata la generazione. 
        - **Selezionare la sottoscrizione**: in anteprima privata, ACAT consente di definire l'ambito del report di conformità scegliendo le risorse di Azure in una sottoscrizione specifica. È possibile scegliere la sottoscrizione appropriata in base all'infrastruttura cloud. Se la sottoscrizione per l'applicazione non è presente nell'elenco, è necessario richiedere l'autorizzazione all'amministratore. 
        - **Selezionare le risorse**: dopo aver specificato la sottoscrizione, selezionare le risorse appropriate in base all'infrastruttura cloud. Come impostazione predefinita, tutte le risorse verranno selezionate automaticamente. È anche possibile eseguire ricerche nelle risorse in base ai filtri (ad esempio, gruppo di risorse, tag e così via) e quindi selezionare le risorse. 
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-basic-inline.png" lightbox="../media/ACAT/getstarted-report-config-basic.png" alt-text="Configurazione di base":::
       Configurazione di base per il report di conformità :::image-end:::

    - **Microsoft 365 certificazione**: la configurazione della certificazione Microsoft 365 è facoltativa durante la creazione.  Può essere configurato in un secondo momento dopo aver iniziato a pubblicare l'app.
        - **GUID offerta**: il GUID dell'offerta è l'identificatore univoco per l'offerta del marketplace in [Microsoft Partner Network](https://partner.microsoft.com/dashboard). Selezionare *Altre informazioni* per ottenere un'istruzione dettagliata su come ottenere l'identificatore univoco.
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-m365-inline.png" lightbox="../media/ACAT/getstarted-report-config-m365.png" alt-text="configurazione della certificazione Microsoft 365":::
       Configurazione della certificazione Microsoft 365:::image-end:::

Dopo aver confermato la configurazione e creato il report di conformità, ACAT raccoglierà automaticamente i dati correlati alla conformità dalle origini seguenti. 

- Abilitare il [Microsoft Defender per il cloud](https://azure.microsoft.com/services/defender-for-cloud/) (livello gratuito) per la sottoscrizione. 
- Abilitare alcuni criteri personalizzati per la sottoscrizione. 

> [!NOTE]
> Se la creazione ha esito positivo, ACAT inizierà a raccogliere e generare le valutazioni di conformità per il report di conformità a partire dal giorno seguente. 

## <a name="audit-the-compliance-assessments-with-your-compliance-report"></a>Controllare le valutazioni di conformità con il report di conformità

Con ACAT è possibile apprendere lo stato di run-time del report di conformità e controllare facilmente le valutazioni di conformità. 

- Passare a ***Report*** da a sinistra. È possibile ottenere un breve riepilogo dei report di conformità esistenti.
    - **Stato di runtime: lo** stato di runtime indica se ACAT gestisce ancora correttamente il report di conformità nell'ultima generazione. Esistono tre stati per lo stato di runtime. 
        - **Attivo**: il report di conformità viene eseguito in modo continuo e corretto. 
        - **Non riuscito**: ACAT non è riuscito a generare le valutazioni di conformità per questo report di conformità per l'ultima generazione. Questo stato può verificarsi per diversi motivi, ad esempio la configurazione non corretta nella sottoscrizione per bloccare i dati di conformità indirizzati ad ACAT, si è verificato un errore di sistema o un'interruzione con ACAT e così via. 
        - **Disabilitato**: questo report di conformità viene disabilitato (sospeso) manualmente. Questa funzionalità non è abilitata nell'anteprima privata. 
    - **Ora ultimo trigger** e **Ora di attivazione successiva**: ACAT genererà quotidianamente le valutazioni di conformità per il report di conformità. *L'ora dell'ultimo trigger* indica quando è stata attivata l'ultima generazione e *l'ora del trigger Successivo* indica l'ora del trigger per la generazione successiva. 
    - **Microsoft 365 certificazione**: comprendere lo stato del report di conformità per i controlli di certificazione Microsoft 365. I tre stati per lo stato di conformità della certificazione Microsoft 365 includono:
        - **Superato**: non ci sono errori per i controlli di certificazione Microsoft 365 completamente automatizzati.
        - **Non riuscito**: vengono rilevate responsabilità dei clienti non riuscite per i controlli di certificazione Microsoft 365 completamente automatizzati.
        - **Manuale**: questo stato include due tipi di controlli: il *controllo manuale automatizzato parziale* che è parzialmente automatizzato da ACAT e richiede comunque un impegno manuale per raccogliere le prove di conformità e il *controllo manuale* che richiede l'impegno manuale completo per raccogliere le prove di conformità. ACAT automatizza parti delle responsabilità dei clienti per il controllo parzialmente automatizzato. È possibile usare lo stato di conformità per riferimento, ma non per Microsoft 365 controllo di certificazione direttamente.
    
    :::image type="complex" source="../media/ACAT/getstarted-report-list-inline.png" lightbox="../media/ACAT/getstarted-report-list.png" alt-text="Elenco di report di conformità":::
       Elenco del report di conformità esistente.
    :::image-end:::

Oltre a conoscere il riepilogo generale dei report di conformità esistenti, è anche possibile controllare i dettagli della valutazione della conformità con il team in ACAT. Ottenere i dettagli della valutazione della conformità per il report di conformità specifico facendo clic sul nome del report. ACAT mostrerà i dettagli come indicato di seguito.

- **Impostazioni**: è possibile modificare la configurazione del report di conformità con *Impostazioni*. Nell'anteprima privata è possibile modificare la configurazione relativa alla certificazione Microsoft 365. 
- **Scarica report**: ACAT consente di scaricare le valutazioni del report di conformità come file CSV in un formato che può essere condiviso con i partner per la collaborazione.
    - **Inventario dell'infrastruttura cloud**: questo file contiene i dettagli delle risorse di questo report di conformità. Può essere usato per descrivere l'inventario cloud dell'applicazione. 
    - **Microsoft 365 valutazione della conformità della certificazione**: questo file include le valutazioni di conformità del report di conformità dal punto di vista del controllo di certificazione Microsoft 365. 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-toolbar-inline.png" lightbox="../media/ACAT/getstarted-report-detail-toolbar.png" alt-text="Barra degli strumenti del report di conformità":::
    Barra degli strumenti per il report di conformità.
:::image-end:::

- **Informazioni di base**: questa sezione indica lo stato e la configurazione del report di conformità. 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-essential-inline.png" lightbox="../media/ACAT/getstarted-report-detail-essential.png" alt-text="Informazioni di base sul report di conformità":::
    Informazioni di base per il report di conformità.
:::image-end:::

- **Risultati valutazione**
    - Lo stato di conformità del controllo di certificazione Microsoft 365 è classificato in cinque categorie. 
        - **Superato**: non ci sono errori per i controlli di certificazione Microsoft 365 completamente automatizzati.
        - **Non riuscito**: vengono rilevate responsabilità dei clienti non riuscite per i controlli di certificazione Microsoft 365 completamente automatizzati.
        - **Superato - Evidenza aggiuntiva necessaria**: non sono presenti errori per i controlli di certificazione Microsoft 365 parzialmente automatizzati. È comunque necessario raccogliere prove aggiuntive per i controlli manualmente.
        - **Non riuscito - Evidenza aggiuntiva necessaria**: sono stati rilevati errori nelle responsabilità dei clienti per i controlli di certificazione Microsoft 365 parzialmente automatizzati.
        - **Controllo manuale**: ACAT non automatizza alcuna responsabilità del cliente per i controlli di certificazione Microsoft 365. 
    - Le valutazioni di conformità sono organizzate in base Microsoft 365 famiglia e controllo del controllo della certificazione. 
        - Per altre informazioni sui dettagli del controllo di conformità e su come raccogliere prove di conformità per il controllo manuale, fare clic sul nome del controllo. 
        - Quando si espande il controllo completamente automatizzato e il controllo parzialmente automatizzato, è possibile ottenere altri dettagli sulla conformità della responsabilità del cliente di tale controllo. 
        - Per ogni responsabilità del cliente, è anche possibile individuare lo stato di conformità delle risorse correlate e i passaggi di correzione per la risorsa non riuscita facendo clic sul pulsante di azione. 
            - **Risorse non integre**: è necessario completare i passaggi di correzione per correggere le risorse non integre. 
            - **Risorse non applicabili**: è necessario completare il motivo N/D per configurare le risorse e quindi ACAT potrebbe raccogliere le valutazioni di conformità per le risorse.

:::image type="complex" source="../media/ACAT/getstarted-report-detail-assessment-inline.png" lightbox="../media/ACAT/getstarted-report-detail-assessment.png" alt-text="Valutazioni del report di conformità":::
    Valutazioni di conformità per il report di conformità.
:::image-end:::

## <a name="use-your-first-compliance-report-with-microsoft-r365-certification-audit"></a>Usare il primo report di conformità con il controllo di certificazione Microsoft r365

Prima di usare il report di conformità con Microsoft 365 certificazione, è necessario configurare il GUID dell'offerta per associare il report di conformità all'offerta del marketplace. Esistono due opzioni: 

- Durante il processo di creazione del report di conformità, configurare il GUID dell'offerta nella scheda *di certificazione Microsoft 365*. 
- Se il report di conformità è già stato creato, passare alla *Impostazioni* di questo report di conformità per configurare il GUID dell'offerta.

Dopo aver configurato il GUID dell'offerta, passare a [Microsoft Partner Network](https://partner.microsoft.com/dashboard) per avviare la conformità dell'app. La *documentazione iniziale* è la prima fase della certificazione Microsoft 365. In questa fase, se si sceglie *Sì* per stabilire se si usa ACAT, è possibile scegliere il report di conformità appropriato per questo controllo. La certificazione Microsoft 365 invierà automaticamente le valutazioni di conformità dei controlli completamente automatizzati al revisore, risparmiando tempo e impegno. 

## <a name="get-high-level-overview-of-your-compliance-reports"></a>Panoramica generale dei report di conformità 

La ***panoramica*** offre una migliore comprensione dello stato generale dei report di conformità. 

- **Stato run-time del report di conformità**: questa panoramica fornisce la statistica dello stato di runtime per i report di conformità.
    - **Attivo**: il report di conformità viene eseguito in modo continuo e corretto. 
    - **Non riuscito**: ACAT non è riuscito a generare le valutazioni di conformità per questo report di conformità nell'ultima generazione. Questo stato può verificarsi per diversi motivi, ad esempio la configurazione non corretta nella sottoscrizione per bloccare i dati di conformità indirizzati ad ACAT, si è verificato un errore di sistema o un'interruzione con ACAT e così via. 
    - **Disabilitato**: questo report di conformità viene disabilitato (sospeso) manualmente. Questa funzionalità non è abilitata nell'anteprima privata. 

:::image type="complex" source="../media/ACAT/getstarted-overview-runtime-inline.png" lightbox="../media/ACAT/getstarted-overview-runtime.png" alt-text="Panoramica dello stato di runtime":::
    Panoramica dello stato di runtime del report di conformità.
:::image-end:::

- **Report di conformità alle normative attive**: questa panoramica fornisce la statistica dei risultati di conformità per ogni report *di conformità attivo* .
    - **Superato**: non ci sono errori per i controlli di certificazione Microsoft 365 completamente automatizzati.
    - **Non riuscito**: vengono rilevate responsabilità dei clienti non riuscite per i controlli di certificazione Microsoft 365 completamente automatizzati.
    - **Manuale**: questo stato include due tipi di controlli: il *controllo manuale automatizzato parziale* che è parzialmente automatizzato da ACAT e richiede comunque un impegno manuale per raccogliere le prove di conformità e il *controllo manuale* che richiede l'impegno manuale completo per raccogliere le prove di conformità. ACAT automatizza parti delle responsabilità dei clienti per il controllo parzialmente automatizzato. È possibile usare lo stato di conformità per riferimento, ma non per Microsoft 365 controllo di certificazione direttamente.

:::image type="complex" source="../media/ACAT/getstarted-overview-compliance-inline.png" lightbox="../media/ACAT/getstarted-overview-compliance.png" alt-text="Panoramica dello stato di conformità":::
    Panoramica dello stato di conformità per i report di conformità attivi.
:::image-end:::

## <a name="troubleshooting"></a>Risoluzione dei problemi 

### <a name="why-is-the-compliance-report-created-failed-due-to-authorization-error"></a>Perché il report di conformità creato non è riuscito a causa di un errore di autorizzazione? 

Quando si crea un report di conformità, ACAT configura l'ambiente con la sottoscrizione per raccogliere automaticamente i dati di conformità e questa azione richiede l'autorizzazione specifica della sottoscrizione. È possibile controllare l'autorizzazione della sottoscrizione come indicato di seguito. 

- Cercare e avviare le **sottoscrizioni** in [portale di Azure](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D).
- Passare alla sottoscrizione che si vuole usare per creare il report di conformità. 
- Passare al **controllo di accesso (IAM)** a sinistra. 
- Selezionare **Visualizza accesso personale** per controllare l'autorizzazione.
    - Se l'organizzazione usa [ruoli predefiniti di Azure](/azure/role-based-access-control/built-in-roles), le assegnazioni di ruolo devono includere almeno uno dei ruoli seguenti:
        - [Collaboratore ai criteri di risorse](/azure/role-based-access-control/built-in-roles#resource-policy-contributor) e [Amministrazione di sicurezza](/azure/role-based-access-control/built-in-roles#security-admin)
        - Altre assegnazioni di ruolo con autorizzazioni più elevate, ad esempio [Proprietario](/azure/role-based-access-control/built-in-roles#owner) e così via

### <a name="how-to-report-an-acat-issue-or-warning"></a>Come segnalare un problema o un avviso ACAT? 

Quando si verifica un problema in ACAT e si vuole contattare il [programma di anteprima privato ACAT](mailto:acatprivatepreview@microsoft.com) per assistenza, è necessario il supporto per raccogliere le prove per comprendere meglio lo scenario.

- Ottenere i dettagli dell'errore o dell'avviso ACAT
    - Passare a **Notifiche** nella parte superiore di [portale di Azure](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D).
    - Selezionare **Altri eventi nel log attività** 
    
    :::image type="complex" source="../media/ACAT/getstarted-troubleshoot-activitylog.png" alt-text="Notifiche ACAT":::
        Passare al log attività per controllare le notifiche ACAT.
    :::image-end:::
    
    - Modificare l'intervallo **di tempo** correttamente per filtrare l'errore o l'avviso ACAT nel log attività. 
    - Trovare l'errore o l'avviso ACAT, selezionare per ottenere i dettagli e salvare i dettagli come file.
    
- Controllare se la sottoscrizione è configurata correttamente da ACAT. 
    - Cercare e avviare le **sottoscrizioni** in [portale di Azure](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D).
    - Passare alla sottoscrizione che si vuole usare per creare il report di conformità. 
    - Selezionare **Provider di risorse** per verificare se lo stato di questi provider è *Registrato*.
        - Microsoft.Security
        - Microsoft.ResourceGraph
    - Indietro per [portale di Azure](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D) e avviare **Resource Graph Explorer**.
    - Selezionare **Nuova query**
    - Eseguire questa query per controllare l'assegnazione dei criteri e scaricare il risultato come CSV. 

    ```kusto
    resourcecontainers
    | where type == "microsoft.resources/subscriptions/resourcegroups"
    | where name contains "acat"
    ```

    - Eseguire questa query per controllare l'automazione e scaricare il risultato come CSV.

    ```kusto
    resources
    | where type == "microsoft.security/automations"
    | where name contains "acat"
    ```

    - Eseguire questa query per controllare la valutazione e scaricare il risultato come CSV. È necessario sostituire il segnaposto ***your-subscriptionId*** con la sottoscrizione specifica su cui si vuole eseguire una query.

    ```kusto
    SecurityResources
      | where type == 'microsoft.security/assessments'
      | where subscriptionId == "your-subscriptionId"
      | extend metadata=properties.metadata,
      status=properties.status,
      links=properties.links,
      displayName=properties.displayName,
      resourceDetails=properties.resourceDetails,
      description=properties.metadata.description
      | project type, id, name, description, metadata, status, resourceDetails, links, displayName
    ```