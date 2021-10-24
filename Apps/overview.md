---
title: Programma di conformità delle app di Microsoft 365
author: LGerrard
ms.author: Legerrar
description: Introduzione e panoramica del programma
keywords: microsoft 365 app m365 Attestazione autore certificazione
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: e36bee4289de320d264a8a5e55c7bc20a4ea803b
ms.sourcegitcommit: cab3c02db1b748f3502714d89bd9b65408fd9f54
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 10/22/2021
ms.locfileid: "60545768"
---
# <a name="microsoft-365-app-compliance-program"></a>Programma di conformità delle app di Microsoft 365

Il Programma di conformità delle app Microsoft 365 è un approccio in due passaggi alla sicurezza e alla conformità delle app e include la Verifica dell’autore e la Certificazione Microsoft 365. Ogni livello si basa sul successivo, offrendo un programma a più livelli per dare agli utenti la sicurezza di cui hanno bisogno durante l'uso delle app nell'ecosistema Microsoft 365.  

La nostra missione è offrire ai clienti Microsoft un modo per considerare completamente attendibili le applicazioni che eseguono le loro organizzazioni.

![Approccio Livello 2 alla conformità delle app](media/Microsoft365AppComplianceBanner.png)

## <a name="publisher-verification"></a>Verifica dell'autore

La [verifica dell'autore](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview) consente agli amministratori e agli utenti di comprendere l'autenticità degli sviluppatori delle app che si integrano con Microsoft Identity Platform. Quando un'app è contrassegnata come verificata dall'autore, significa che l'autore ha verificato la propria identità attraverso un account Microsoft Partner Network che ha completato il processo di verifica, e ha associato tale account alla registrazione dell'applicazione.
La verifica dell’autore si applica alle app che soddisfano le seguenti condizioni:  
- Uso di OAuth 2.0 e OpenID Connect per far accedere gli utenti e richiedere l'accesso ai dati usando API lato servizio come Microsoft Graph. 
- Registrata in Azure AD come multi-tenant.  

> [!IMPORTANT]
> La verifica dell'autore non impedisce a uno sviluppatore di app di avviare o completare l'attestazione di autore o la certificazione Microsoft 365. Se non si applica all'app, la verifica può essere ignorata e l'attestazione può essere avviata.

## <a name="microsoft-365-certification"></a>Certificazione Microsoft 365
Il processo di Certificazione Microsoft 365 prevede due fasi: **Attestazione** e **Certificazione**.
1.  **Attestazione** comporta il completamento di un questionario sugli sicurezza, la gestione dei dati e gli attributi di conformità di un'app che sono più importanti per i clienti. Tutte le informazioni vengono quindi pubblicate in un unico posto e in un formato coerente e di facile lettura. L'obiettivo è accelerare il processo di adozione delle app assicurando al contempo ai clienti che le app che usano nei loro tenant soddisfino gli standard dell'organizzazione.
1.  **Certificazione** comporta un controllo accurato di un'app rispetto a un set di controlli derivati da framework standard leader di settore. Agli ISV verrà chiesto di fornire prove per dimostrare che stanno rispettando ogni controllo prima di ottenere una certificazione. L'obiettivo è offrire ai clienti la garanzia di poter considerare attendibile l'app per cui le app che hanno ricevuto una certificazione Microsoft 365 hanno solide procedure di sicurezza e conformità per proteggere la sicurezza dei dati e la privacy.


La Certificazione Microsoft 365 si applica alle WebApp e a tutte le app che si integrano con i prodotti Microsoft seguenti:
-   Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- SharePoint
- Project
- OneNote

### <a name="get-started"></a>Introduzione
- [Come completare la Verifica dell’autore](https://docs.microsoft.com/en-us/azure/active-directory/develop/mark-app-as-publisher-verified)
- [Come completare la Certificazione Microsoft 365](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification)

