---
title: Configurare Assets Essentials per Creative Cloud Pro con le soluzioni di gestione del lavoro
description: 'Questa esercitazione introduce un percorso di amministratori per consentire l’integrazione dell’applicazione Assets Essentials con le applicazioni desktop Creative Cloud e con le applicazioni Adobe Workfront. Le applicazioni desktop Creative Cloud includono Adobe Photoshop, Adobe Illustrator, Adobe InDesign e Adobe XD. '
source-git-commit: f4e56fc6bb76eeb2770b18be88b7da1a1829069c
workflow-type: tm+mt
source-wordcount: '900'
ht-degree: 14%

---


# Assets Essentials per Creative Cloud Pro con soluzioni di gestione del lavoro {#creative-cloud-enterprise-user-journeys}

![Preferenza per scegliere il tema scuro o chiaro](assets/cce-next-banner-landing-page.png)

## Introduzione {#introduction}

Creative Cloud Pro for enterprise con le soluzioni di gestione del lavoro integra strumenti creativi, di content e di gestione del lavoro per aumentare la capacità di produrre contenuti creativi e raggiungere rapidamente gli obiettivi aziendali. La soluzione include i seguenti componenti:

* Creative Cloud Pro

* Adobe Workfront

* Nozioni di base su Experience Manager Assets

Questa esercitazione introduce un percorso di amministratori per consentire l’integrazione dell’applicazione Assets Essentials con le applicazioni desktop Creative Cloud e con le applicazioni Adobe Workfront. Le applicazioni desktop Creative Cloud includono Adobe Photoshop, Adobe Illustrator, Adobe InDesign e Adobe XD.

## Tipi di distribuzione {#deployment-types}

Poiché la soluzione è costituita da applicazioni e servizi di Creative Cloud e Adobe Experience Cloud, potrebbero essere implementati in uno o due Admin Console Adobi per la tua azienda.

In caso di distribuzione in due Admin Console, è necessario un ulteriore passaggio di configurazione:

* I servizi e le applicazioni di Creative Cloud (Creative Cloud per enterprise Pro e moduli opzionali) sono gestiti in [Adobe Admin Console per la distribuzione Creative Cloud](https://chl-author-preview.corp.adobe.com/content/help/en/enterprise/admin-guide.html).

* Adobe Workfront e Adobe Experience Manager Assets Essentials sono gestiti in [Soluzioni Adobe Admin Console per Experience Cloud](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html).

Per integrare le applicazioni Creative Cloud e Assets Essentials, gli utenti disponibili in Admin Console per la Creative Cloud devono essere resi disponibili in Admin Console, ad Experience Cloud. Per rendere gli utenti disponibili in Experience Cloud Admin Console, crea una directory per stabilire [trust tra directory](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) tra le due console di amministrazione.

![Utenti Creative Cloud](assets/creative-cloud-users.svg)

Come illustrato nel diagramma, gli utenti delle Creative Cloud vengono automaticamente resi disponibili nell’Admin Console di Experience Cloud in base a una relazione di affidabilità tra le due console. Puoi quindi aggiungere gli utenti ai profili di prodotto Assets Essentials. Di conseguenza, gli utenti Creative Cloud possono accedere all’applicazione Adobe Asset Link che può interagire con l’archivio Assets Essentials. Per ulteriori informazioni, consulta [Integrare Assets Essentials con le applicazioni Creative Cloud](integrate-assets-essentials-creative-cloud.md).

## percorsi della documentazione di Experience Manager {#documentation-journeys}

Un Percorso di documentazione unisce molti argomenti e funzionalità diversi e forse complessi, fornendo una narrazione che aiuta il lettore, che può essere nuovo di Assets Essentials, a comprendere e risolvere un problema aziendale dall&#39;inizio alla fine, assumendo al contempo un argomento preliminare minimo o conoscenze Assets Essentials.

I Percorsi di documentazione sono progettati in base ai principi delle best practice, alla luce delle ultime ricerche di Adobe, della comprovata esperienza nell’implementazione da parte di consulenti di Adobe e del feedback dai progetti dei clienti.

## Prerequisiti

* [Accesso ad Adobe Admin Console per soluzioni di Experience Cloud](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html)

* [Accesso a Adobe Admin Console per l&#39;implementazione di Creative Cloud for enterprise](https://helpx.adobe.com/enterprise/admin-guide.html)

## Amministrare Experience Manager Assets Essentials {#administer-assets-essentials}

![Preferenza per scegliere il tema scuro o chiaro](assets/cce-assets.png)

Adobe Experience Manager Assets Essentials è una nuova edizione leggera di Adobe Experience Manager Assets. Assets Essentials fornisce una gestione unificata delle risorse e una collaborazione con un’interfaccia utente semplificata e coerente. La facilità d’uso consente ai team creativi e di marketing di archiviare, individuare e distribuire risorse digitali.

Adobe Experience Manager Assets Essentials è fornito per Adobe per i suoi clienti. Come parte del provisioning, Assets Essentials viene aggiunto all’organizzazione di un cliente in Adobe Admin Console.

Gli amministratori utilizzano l’Admin Console per gestire le adesioni utente al prodotto Assets Essentials:

* Aggiungere gruppi di utenti

* Aggiungi utenti a gruppi di utenti

* Aggiungere utenti ai profili di prodotto di Assets Essentials

Dopo aver gestito le adesioni utente in Admin Console, gli amministratori possono utilizzare l&#39;applicazione Assets Essentials per:

* Creare una struttura di cartelle per soddisfare al meglio le esigenze dell’organizzazione

* Gestire le autorizzazioni per la struttura delle cartelle

* Impostazione dei moduli di metadati

[![Vedi la Guida](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](adminster-aem-assets-essentials.md)

## Integrare applicazioni Creative Cloud con Experience Manager Assets Essentials {#administer-creative-cloud-applications}

![Preferenza per scegliere il tema scuro o chiaro](assets/cce-creative-cloud.png)

[il pannello in-app Adobe Asset Link](https://www.adobe.com/creativecloud/business/enterprise/adobe-asset-link.html) consente a professionisti del settore creativo di connettersi all’archivio [!DNL Assets Essentials] dall’interno delle app desktop [!DNL Adobe Creative Cloud] supportate. Il pannello è disponibile per [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] e [!DNL Adobe XD]. Semplifica l’accesso alle risorse e velocizza le attività relative ai contenuti.

Questa esercitazione ti guida a integrare [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign]e [!DNL Adobe XD] applicazioni con Experience Manager Assets Essentials.

Obiettivi:

* Creare un trust tra Creative Cloud e Admin Console di Experience Cloud

* Aggiungere utenti Creative Cloud ai profili di prodotto Assets Essentials

* Installare Adobe Asset Link

* Utilizzare Adobe Asset Link

[![Vedi la Guida](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-assets-essentials-creative-cloud.md)

## Integrare Adobe Workfront con Experience Manager Assets Essentials {#administer-adobe-workfront}

![Preferenza per scegliere il tema scuro o chiaro](assets/cce-workfront.png)

[[!DNL Adobe Workfront]](https://www.workfront.com/) è un’applicazione per la gestione dell’intero ciclo di vita del lavoro, tutto in un’unica posizione. Integrazione nativa tra [!DNL Adobe Workfront] e [!DNL Assets Essentials] consente alle organizzazioni di migliorare la velocità dei contenuti e il time-to-market collegando intrinsecamente il lavoro e la gestione delle risorse. Nel contesto di gestione del lavoro, gli utenti possono accedere ai documenti e alle immagini necessari utilizzando la stessa soluzione.

Questa esercitazione ti guida di amministrare Adobe Workfront e quindi integrarlo con Experience Manager Assets Essentials.

Obiettivi:

* Aggiungere utenti ai profili di prodotto Workfront

* Aggiungere utenti ai profili di prodotto di Assets Essentials

* Configurare l’integrazione Experience Manager Assets Essentials

[![Vedi la Guida](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-assets-essentials-workfront.md)


