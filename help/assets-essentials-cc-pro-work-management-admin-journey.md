---
title: Configurare Assets Essentials per Creative Cloud Pro con le soluzioni di gestione del lavoro
description: Questa esercitazione introduce un percorso di amministratori per consentire l’integrazione dell’applicazione Assets Essentials con le applicazioni desktop Creative Cloud e con le applicazioni Adobe Workfront. Le applicazioni desktop Creative Cloud includono Adobe Photoshop, Adobe Illustrator, Adobe InDesign e Adobe XD.
exl-id: a5e9e0c3-35ec-41de-9656-f4f0f88946c7
source-git-commit: 8920080944981fc1a990136af46c9258c5e8627c
workflow-type: ht
source-wordcount: '941'
ht-degree: 100%

---

# Assets Essentials per Creative Cloud Pro con soluzioni di gestione del lavoro {#creative-cloud-enterprise-user-journeys}

![Preferenza per scegliere il tema scuro o chiaro](assets/cce-next-banner-landing-page.png)

## Introduzione {#introduction}

Creative Cloud Pro for enterprise con le soluzioni di gestione del lavoro integra strumenti creativi, di contenuto e di gestione del lavoro per aumentare la capacità di produrre contenuti creativi e raggiungere rapidamente gli obiettivi aziendali. La soluzione include i seguenti componenti:

* Creative Cloud Pro

* Adobe Workfront

* Experience Manager Assets Essentials

Questa esercitazione introduce un percorso di amministratori per consentire l’integrazione dell’applicazione Assets Essentials con le applicazioni desktop Creative Cloud e con le applicazioni Adobe Workfront. Le applicazioni desktop Creative Cloud includono Adobe Photoshop, Adobe Illustrator, Adobe InDesign e Adobe XD.

## Tipi di distribuzione {#deployment-types}

Poiché la soluzione è costituita da applicazioni e servizi di Creative Cloud e Adobe Experience Cloud, potrebbero essere implementati in uno o due Admin Console Adobi per la tua azienda.

In caso di distribuzione in due Admin Console, è necessario un ulteriore passaggio di configurazione:

* I servizi e le applicazioni di Creative Cloud (Creative Cloud for enterprise Pro e moduli opzionali) sono gestiti in [Adobe Admin Console per la distribuzione Creative Cloud](https://helpx.adobe.com/it/enterprise/admin-guide.html).

* Adobe Workfront e Adobe Experience Manager Assets Essentials sono gestiti in [Soluzioni Adobe Admin Console per Experience Cloud](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html?lang=it).

Per integrare le applicazioni Creative Cloud e Assets Essentials, gli utenti disponibili in Admin Console per Creative Cloud devono essere resi disponibili in Admin Console for Experience Cloud. Per rendere gli utenti disponibili in Experience Cloud Admin Console, crea una directory per stabilire [trust tra directory](https://helpx.adobe.com/it/enterprise/using/set-up-identity.html#directory-trusting) tra le due console di amministrazione.

![Utenti Creative Cloud](assets/creative-cloud-users.svg)

Come illustrato nel diagramma, gli utenti di Creative Cloud vengono automaticamente resi disponibili nell’Admin Console di Experience Cloud in base a una relazione di affidabilità tra le due console. Puoi quindi aggiungere gli utenti ai profili di prodotto Assets Essentials. Di conseguenza, gli utenti Creative Cloud possono accedere all’applicazione Adobe Asset Link che può interagire con l’archivio Assets Essentials. Per ulteriori informazioni, consulta [Integrare Assets Essentials con le applicazioni Creative Cloud](integrate-with-creative-cloud.md).

## Percorsi della documentazione di Experience Manager {#documentation-journeys}

Un percorso di documentazione unisce molti argomenti e caratteristiche diversi e forse complicati, fornendo un resoconto che aiuta il lettore, che potrebbe essere un nuovo utente di Assets Essentials, a capire e risolvere un problema di business dall’inizio alla fine, supponendo una conoscenza minima pregressa dell’argomento o di Assets Essentials.

I percorsi di documentazione sono progettati in base ai principi delle best practice, alla luce delle ultime ricerche condotte da Adobe, della comprovata esperienza nell’implementazione da parte di consulenti di Adobe e del feedback raccolto sui progetti dei clienti.

## Prerequisiti

* [Accesso ad Adobe Admin Console per soluzioni di Experience Cloud](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html?lang=it)

* [Accesso a Adobe Admin Console per l’implementazione di Creative Cloud for enterprise](https://helpx.adobe.com/it/enterprise/admin-guide.html)

## Amministrare Experience Manager Assets Essentials {#administer-assets-essentials}

![Preferenza per scegliere il tema scuro o chiaro](assets/cce-assets.png)

Adobe Experience Manager Assets Essentials è una nuova edizione leggera di Adobe Experience Manager Assets. Assets Essentials offre funzioni per la gestione unificata delle risorse e collaborazione con un’interfaccia utente semplificata e coerente. La facilità d’uso consente ai team creativi e di marketing di archiviare, individuare e distribuire risorse digitali.

Adobe Experience Manager Assets Essentials è fornito da Adobe per i suoi clienti. Come parte del provisioning, Assets Essentials viene aggiunto all’organizzazione del cliente in Adobe Admin Console.

Gli amministratori utilizzano l’Admin Console per gestire le adesioni utente al prodotto Assets Essentials:

* Aggiungere gruppi di utenti

* Aggiungere utenti ai gruppi di utenti

* Aggiungere utenti ai profili di prodotto di Assets Essentials

Dopo aver gestito le adesioni utente in Admin Console, gli amministratori possono utilizzare l’applicazione Assets Essentials per:

* Creare una struttura di cartelle per soddisfare al meglio le esigenze dell’organizzazione

* Gestire le autorizzazioni per la struttura delle cartelle

* Impostare moduli di metadati

[![Consulta la Guida](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](deploy-administer.md)

Dopo aver configurato e gestito l’applicazione Assets Essentials, [integra le applicazioni Creative Cloud con l’applicazione Experience Manager Assets Essentials](integrate-with-creative-cloud.md).

## Integrare le applicazioni Creative Cloud con Experience Manager Assets Essentials {#administer-creative-cloud-applications}

![Preferenza per scegliere il tema scuro o chiaro](assets/cce-creative-cloud.png)

[il pannello in-app Adobe Asset Link](https://www.adobe.com/it/creativecloud/business/enterprise/adobe-asset-link.html) consente a professionisti del settore creativo di connettersi all’archivio [!DNL Assets Essentials] dall’interno delle app desktop [!DNL Adobe Creative Cloud] supportate. Il pannello è disponibile per [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] e [!DNL Adobe XD]. Semplifica l’accesso alle risorse e velocizza le attività relative ai contenuti.

Questa esercitazione ti guida a integrarele applicazioni [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign]e [!DNL Adobe XD] con Experience Manager Assets Essentials.

Obiettivi:

* Creare una trust directory tra Creative Cloud e Admin Console di Experience Cloud

* Aggiungere utenti Creative Cloud ai profili di prodotto Assets Essentials

* Installare Adobe Asset Link

* Utilizzare il collegamento Adobe Asset

[![Consulta la Guida](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-with-creative-cloud.md)

Ora che hai integrato le applicazioni Creative Cloud con Assets Essentials, [integra Adobe Workfront con Experience Manager Assets Essentials](integrate-with-workfront.md).

## Integrare Adobe Workfront con Experience Manager Assets Essentials {#administer-adobe-workfront}

![Preferenza per scegliere il tema scuro o chiaro](assets/cce-workfront.png)

[[!DNL Adobe Workfront]](https://www.workfront.com/) è un’applicazione per la gestione dell’intero ciclo di vita del lavoro, tutto in un’unica posizione. L’integrazione nativa tra [!DNL Adobe Workfront] e [!DNL Assets Essentials] consente alle organizzazioni di velocizzare le attività relative ai contenuti e il time-to-market, grazie a un collegamento intrinseco tra il lavoro e la gestione delle risorse. Nel contesto di gestione del lavoro, gli utenti possono accedere ai documenti e alle immagini necessari utilizzando la stessa soluzione.

Questa esercitazione ti guida ad amministrare Adobe Workfront e quindi integrarlo con Experience Manager Assets Essentials.

Obiettivi:

* Aggiungere utenti ai profili di prodotto Workfront

* Aggiungere utenti ai profili di prodotto di Assets Essentials

* Configurare l’integrazione Experience Manager Assets Essentials

[![Consulta la Guida](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-with-workfront.md)
