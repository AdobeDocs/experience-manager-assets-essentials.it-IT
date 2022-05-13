---
title: Integrare Assets Essentials con le applicazioni Creative Cloud
description: Integra Assets Essentials con le applicazioni Creative Cloud in modo da poter usare il pannello in-app di collegamento delle risorse di Adobe per la connessione [!DNL Assets Essentials] dall’interno del supportato [!DNL Adobe Creative Cloud] applicazioni desktop.
source-git-commit: f4e56fc6bb76eeb2770b18be88b7da1a1829069c
workflow-type: tm+mt
source-wordcount: '854'
ht-degree: 6%

---


# Integrare Assets Essentials con le applicazioni Creative Cloud {#integrate-assets-essentials-creative-cloud-applications}

![Preferenza per scegliere il tema scuro o chiaro](assets/cce-creative-cloud.png)

## La storia finora

Dopo [configurazione di Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) in questa esercitazione puoi sfruttare l’esperienza per integrare le applicazioni Creative Cloud con Assets Essentials.

## Obiettivo

* **Pubblico**: Amministratori di Creative Cloud

* **Obiettivo**: Integra Assets Essentials con le applicazioni Creative Cloud in modo che i tuoi utenti creativi possano usare il pannello in-app di collegamento delle risorse di Adobe per connettersi a [!DNL Assets Essentials] dall’interno del supportato [!DNL Adobe Creative Cloud] applicazioni desktop.

## Panoramica

[il pannello in-app Adobe Asset Link](https://www.adobe.com/creativecloud/business/enterprise/adobe-asset-link.html) consente a professionisti del settore creativo di connettersi all’archivio [!DNL Assets Essentials] dall’interno delle app desktop [!DNL Adobe Creative Cloud] supportate. Il pannello è disponibile per [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] e [!DNL Adobe XD]. Semplifica l’accesso alle risorse, il che a sua volta aiuta ad aumentare la velocità dei contenuti.

Gli utenti delle applicazioni Creative Cloud possono utilizzare il pannello in-app Adobe Asset Link solo quando si integrano le applicazioni Creative Cloud con l’archivio Experience Manager Assets Essentials.

Esegui le seguenti attività per integrare Assets Essentials con le applicazioni Creative Cloud:

* [Creare un trust tra Creative Cloud e Admin Console Experience Cloud](#directory-trusting-cc-assets-essentials-consoles)

* [Aggiungere utenti Creative Cloud ai profili di prodotto Assets Essentials](#add-cc-users-assets-essentials-product-profiles)

* [Installare Adobe Asset Link](#install-asset-link)

* [Utilizzare Adobe Asset Link](#use-asset-link)

## Creare un trust tra Creative Cloud e Admin Console di Experience Cloud {#directory-trusting-cc-assets-essentials-consoles}

Se la tua Creative Cloud viene distribuita in una Admin Console di Adobe separata da quella con Assets Essentials (soluzione di Experience Cloud), devi aggiungere una relazione di trust tra le due console.

Per integrare le applicazioni Creative Cloud e Assets Essentials, gli utenti disponibili in Admin Console per la Creative Cloud devono essere resi disponibili in Admin Console, ad Experience Cloud. Se Creative Cloud e Assets Essentials vengono distribuiti in Admin Console separati, per abilitarlo è necessaria una relazione di trust tra loro.

Nell’Admin Console di Experience Cloud, fai clic su **[!UICONTROL Impostazioni]** e utilizza **[!UICONTROL Directory]** scheda per creare una directory da stabilire [trust tra directory](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) tra i due Admin Console.

## Aggiungere utenti Creative Cloud ai profili di prodotto Assets Essentials {#add-cc-users-assets-essentials-product-profiles}

Dopo aver stabilito l&#39;affidabilità della directory tra l&#39;Admin Console per Creative Cloud e Admin Console, ad Experience Cloud, assegna gli utenti della Creative Cloud al **[!DNL Assets Essentials]Utenti** profilo di prodotto [!DNL Assets Essentials] scheda prodotto nell’Admin Console di Experience Cloud. Consente agli utenti di Creative Cloud di accedere ad Assets Essentials dal pannello dei plug-in di Asset Link per l’Adobe; inoltre, consentirà loro di accedere all’interfaccia utente Web di Assets Essentials completa per caricare, organizzare, assegnare tag e trovare risorse digitali tramite un browser web.

Altri profili di prodotto Assets Essentials - **[!DNL Assets Essentials]Amministratori** e **[!DNL Assets Essentials]Utenti consumer** - vengono utilizzati per diverse adesioni utente (amministratori di applicazioni e utenti che accedono ad Assets Essentials tramite integrazioni Experience Cloud).

Per ulteriori informazioni su come assegnare gli utenti ai profili di prodotto Assets Essentials, consulta [Assegnare gli utenti ai profili di prodotto Assets Essentials](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Installare Adobe Asset Link {#install-asset-link}

[!DNL Adobe Asset Link] il plug-in può essere installato e reso disponibile agli utenti creativi in due modi:

* Gli utenti creativi possono installare il plug-in dal loro [!DNL Creative Cloud Desktop] applicazione
* L’amministratore di Creative Cloud può aggiungere il plug-in Asset Link a un pacchetto Creative Cloud in Admin Console

La scelta dipende dai criteri IT dell&#39;organizzazione.

**Installazione tramite [!DNL Creative Cloud Desktop] applicazione** è descritto [qui](https://helpx.adobe.com/creative-cloud/kb/installingextensionsandaddons.html). Sono disponibili due plug-in in hosting su [Adobe Exchange](https://exchange.adobe.com/) marketplace, a seconda dell’applicazione Creative Cloud:

* Per [!DNL Adobe Photoshop], [!DNL Adobe Illustrator]e [!DNL Adobe InDesign]: [Adobe Asset Link CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* Per [!DNL Adobe XD]: [Adobe Asset Link](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**Installazione con un pacchetto Creative Cloud** viene eseguito dall’amministratore di Creative Cloud in Admin Console, includendo il plug-in Asset Link al momento della creazione di un pacchetto di distribuzione, che può essere successivamente distribuito ai computer utente. Nella schermata Scegli plug-in gestita, cerca **Adobe Asset Link** in **Plug-in aziendali consigliati** sezione . Per ulteriori informazioni, consulta [creare pacchetti di app tramite l’Admin Console](https://helpx.adobe.com/enterprise/using/package-apps-admin-console.html).

## Utilizzare Adobe Asset Link {#use-asset-link}

Gli utenti creativi possono ora utilizzare Adobe Asset Link con Photoshop, Illustrator, InDesign o XD. Per aprire il pannello in InDesign o Illustrator, passa a Windows > Estensioni > Adobe Asset Link. In Photoshop, vai a Finestra > Estensioni (legacy) > Adobe Asset Link.

Per informazioni su come impostare Adobe Asset Link per Adobe XD, fai clic su [qui](https://helpx.adobe.com/it/enterprise/using/adobe-asset-link-for-xd.html).

>[!NOTE]
>
>Quando si lavora su hardware Apple Silicon / M1, Adobe Photoshop deve essere avviato utilizzando la modalità di compatibilità Rosetta per garantire che gli utenti creativi abbiano accesso al pannello Adobe Asset Link, in quanto viene creato utilizzando la tecnologia di estensione CEP. Per ulteriori informazioni, consulta [Silicon di Photoshop per Apple](https://helpx.adobe.com/photoshop/kb/photoshop-for-apple-silicon.html).


Utilizza Adobe Asset Link per lavorare con e modificare le risorse memorizzate nell’archivio Assets Essentials. Puoi eseguire varie attività, ad esempio:

* Cercare e sfogliare le risorse

* Caricare le risorse

* Ordinare e filtrare le risorse

* Inserire, scaricare e trascinare una risorsa

* Estrarre e archiviare una risorsa

* Visualizzare la cronologia delle versioni e i dettagli dei file

Per istruzioni su come eseguire queste attività, consulta [Gestire le risorse tramite Adobe Asset Link](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html).

## Novità

Ora che hai integrato le applicazioni Creative Cloud con Assets Essentials, [integrare Adobe Workfront con Experience Manager Assets Essentials](integrate-assets-essentials-workfront.md).
