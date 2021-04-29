---
title: Programma di conformità delle app di Microsoft 365
author: LGerrard
ms.author: Legerrar
description: Introduzione e panoramica del programma
keywords: microsoft 365 app m365 Attestazione autore certificazione
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: 199c8f82a894566a918c30e529cefdfb8c259a48
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 04/28/2021
ms.locfileid: "52071766"
---
# <a name="microsoft-365-app-compliance-program"></a>Programma di conformità delle app di Microsoft 365

Il programma di conformità delle app di Microsoft 365 è un approccio a tre livelli per la sicurezza e la conformità delle app. Ogni livello si basa sul successivo, offrendo un programma a più livelli per dare agli utenti la sicurezza di cui hanno bisogno durante l'uso delle app nell'ecosistema Microsoft 365. Al momento, tutti i livelli del programma sono volontari e vengono completati a discrezione dagli sviluppatori dell'app. 

La nostra missione: i clienti Microsoft hanno completa fiducia nelle applicazioni che eseguono nelle loro organizzazioni.
  ![Approccio a 3 livelli alla conformità delle app](media/Microsoft-App-Compliance-Overview.png) 

## <a name="publisher-verification"></a>Verifica dell'autore

La [verifica dell'autore](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview) consente agli amministratori e agli utenti di comprendere l'autenticità degli sviluppatori delle app che si integrano con Microsoft Identity Platform. Quando un'app è contrassegnata come verificata dall'autore, significa che l'autore ha verificato la propria identità attraverso un account Microsoft Partner Network che ha completato il processo di verifica, e ha associato tale account alla registrazione dell'applicazione.
La verifica dell’autore si applica alle app che soddisfano le seguenti condizioni:  
- Uso di OAuth 2.0 e OpenID Connect per far accedere gli utenti e richiedere l'accesso ai dati usando API lato servizio come Microsoft Graph. 
- Registrata in Azure AD come multi-tenant.  

> [!IMPORTANT]
> La verifica dell'autore non impedisce a uno sviluppatore di app di avviare o completare l'attestazione di autore o la certificazione Microsoft 365. Se non si applica all'app, la verifica può essere ignorata e l'attestazione può essere avviata.

## <a name="publisher-attestation"></a>Attestazione dell'autore

L'[attestazione dell’autore](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide) consente agli sviluppatori di condividere informazioni generali, sulla gestione dei dati e sulla sicurezza e sulla conformità del servizio dell'app. In questo modo si riduce l'esigenza da parte degli amministratori IT di lavorare direttamente con gli autori delle app. Tutte le informazioni necessarie per prendere una decisione basata su informazioni aggiornate possono essere trovate per tutte le app che hanno completato l'attestazione dell'editore in un unico posto e in un formato coerente. L'obiettivo è semplificare e accelerare il processo di adozione delle app assicurando al contempo ai clienti che le app che usano nei loro tenant soddisfino gli standard dell'organizzazione.

L’attestazione dell’autore si applica alle app che si integrano con queste piattaforme Microsoft:
-   Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- SharePoint
- Project
- OneNote

> [!IMPORTANT]
> Microsoft non convalida le informazioni fornite. Lo sviluppatore è l'unico responsabile della veridicità, dell'accuratezza, dell'integrità della documentazione di attestazione e dei dati sulle prestazioni dell'app. 

## <a name="microsoft-365-certification"></a>Certificazione Microsoft 365
La [certificazione Microsoft 365](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide) offre alle organizzazioni assicurazione e riservatezza sulla sicurezza e protezione dei dati e della privacy quando si usano le app di Microsoft Teams. La certificazione conferma che una soluzione app è compatibile con le tecnologie Microsoft, è conforme alle procedure consigliate per la sicurezza delle app cloud e viene supportata da Microsoft.Durante questo processo, gli sviluppatori di app lavorano con un valutatore di terze parti per convalidare gli standard di sicurezza e conformità dell'organizzazione. La certificazione Microsoft 365 si applica alle app che si integrano con queste piattaforme Microsoft:

-   Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- SharePoint
- Project
- OneNote
