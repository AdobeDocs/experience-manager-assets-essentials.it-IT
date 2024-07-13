---
title: Integrare Assets Essentials con le applicazioni Creative Cloud
description: Integra Assets Essentials con le applicazioni Creative Cloud in modo da poter usare il pannello in-app Adobe Asset Link per la connessione all’archivio  [!DNL Assets Essentials]  direttamente dalle applicazioni desktop  [!DNL Adobe Creative Cloud]  supportate.
exl-id: 817bc955-0074-435e-83a8-3fd5f7f2505a
source-git-commit: 65200f73a954e4ebf4fbd6dc3a819acc6e0beda4
workflow-type: tm+mt
source-wordcount: '719'
ht-degree: 100%

---

# Integrare Assets Essentials con le applicazioni Creative Cloud {#integrate-assets-essentials-creative-cloud-applications}

Il [pannello in-app Adobe Asset Link](https://www.adobe.com/it/creativecloud/business/enterprise/adobe-asset-link.html) consente ai professionisti del settore creativo di connettersi all’archivio [!DNL Assets Essentials] direttamente dall app desktop [!DNL Adobe Creative Cloud] supportate. Il pannello è disponibile per [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] e [!DNL Adobe XD]. Semplifica l’accesso alle risorse, il che a sua volta contribuisce a velocizzare la preparazione dei contenuti.

Gli utenti delle applicazioni Creative Cloud possono utilizzare il pannello in-app Adobe Asset Link solo dopo che avrai integrato le applicazioni Creative Cloud con l’archivio Experience Manager Assets Essentials.

Per integrare Assets Essentials con le applicazioni Creative Cloud, esegui le seguenti attività:

* [Creare una relazione di directory affidabili tra Creative Cloud e Admin Console Experience Cloud](#directory-trusting-cc-assets-essentials-consoles)

* [Aggiungere utenti Creative Cloud ai profili di prodotto Assets Essentials](#add-cc-users-assets-essentials-product-profiles)

* [Installare Adobe Asset Link](#install-asset-link)

* [Utilizzare il collegamento Adobe Asset](#use-asset-link)

## Creare una trust directory tra Creative Cloud e Admin Console di Experience Cloud {#directory-trusting-cc-assets-essentials-consoles}

Se Creative Cloud viene implementato in un’istanza di Adobe Admin Console diversa da quella con Assets Essentials (soluzione Experience Cloud), devi aggiungere una relazione di affidabilità tra le due console.

Per integrare le applicazioni Creative Cloud e Assets Essentials, gli utenti disponibili in Admin Console per Creative Cloud devono essere resi disponibili in Admin Console for Experience Cloud. Se Creative Cloud e Assets Essentials sono implementati in istanze diverse di Admin Console, è necessario impostare una relazione di affidabilità tra loro.

In Admin Console di Experience Cloud, fai clic su **[!UICONTROL Impostazioni]** e utilizza la scheda **[!UICONTROL Directory]** per creare una directory al fine di stabilire [directory affidabili](https://helpx.adobe.com/it/enterprise/using/set-up-identity.html#directory-trusting) tra le due istanze di Admin Console.

## Aggiungere utenti Creative Cloud ai profili di prodotto Assets Essentials {#add-cc-users-assets-essentials-product-profiles}

Dopo aver impostato l’affidabilità della directory tra Admin Console per Creative Cloud e Admin Console per Experience Cloud, assegna gli utenti Creative Cloud al profilo di prodotto per Utenti di **[!DNL Assets Essentials]** nella scheda del prodotto [!DNL Assets Essentials] in Admin Console per Experience Cloud. Gli utenti di Creative Cloud potranno così accedere ad Assets Essentials dal pannello del plug-in Adobe Asset Link. Inoltre, potranno accedere all’interfaccia utente web completa di Assets Essentials per caricare, organizzare, assegnare tag e trovare risorse digitali tramite un browser web.

Altri profili di prodotto Assets Essentials, Amministratori di **[!DNL Assets Essentials]** e Utenti consumer di **[!DNL Assets Essentials]**, vengono utilizzati per diverse autorizzazioni utente (amministratori di applicazioni e utenti che accedono ad Assets Essentials tramite integrazioni Experience Cloud).

Per ulteriori informazioni su come assegnare gli utenti ai profili di prodotto Assets Essentials, consulta [Assegnare gli utenti ai profili di prodotto Assets Essentials](deploy-administer.md#add-users-to-product-profiles).

## Installare Adobe Asset Link {#install-asset-link}

Il plug-in [!DNL Adobe Asset Link] può essere installato e reso disponibile agli utenti creativi in due modi:

* Gli utenti creativi possono installare il plug-in dalla loro applicazione [!DNL Creative Cloud Desktop]
* L’amministratore di Creative Cloud può aggiungere il plug-in Asset Link a un pacchetto Creative Cloud in Admin Console

La scelta dipende dai criteri IT dell’organizzazione.

L’**installazione tramite un’applicazione [!DNL Creative Cloud Desktop]** è descritta [qui](https://helpx.adobe.com/it/creative-cloud/kb/installingextensionsandaddons.html). Sono disponibili due plug-in in hosting sul marketplace [Adobe Exchange](https://exchange.adobe.com/), a seconda dell’applicazione Creative Cloud:

* Per [!DNL Adobe Photoshop], [!DNL Adobe Illustrator] e [!DNL Adobe InDesign]: [Adobe Asset Link CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* Per [!DNL Adobe XD]: [Adobe Asset Link](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

L’**installazione con un pacchetto Creative Cloud** viene eseguita dall’amministratore di Creative Cloud in Admin Console, includendo il plug-in Asset Link al momento della creazione di un pacchetto di distribuzione, che può essere successivamente distribuito ai computer degli utenti. Nella schermata gestita per la scelta del plug-in, cerca **Adobe Asset Link** nella sezione dei **plug-in aziendali consigliati**. Per ulteriori informazioni, consulta la sezione su come [creare pacchetti di app tramite Admin Console](https://helpx.adobe.com/it/enterprise/using/package-apps-admin-console.html).

## Utilizzare il collegamento Adobe Asset {#use-asset-link}

Gli utenti creativi possono ora utilizzare Adobe Asset Link con Photoshop, Illustrator, InDesign o XD. Per aprire il pannello in InDesign o Illustrator, passa a Finestre > Estensioni > Adobe Asset Link. In Photoshop, vai a Finestra > Estensioni (legacy) > Adobe Asset Link.

Per informazioni su come impostare Adobe Asset Link per Adobe XD, fai clic [qui](https://helpx.adobe.com/it/enterprise/using/adobe-asset-link-for-xd.html).

>[!NOTE]
>
>Quando si lavora su hardware con chip Apple M1, Adobe Photoshop deve essere avviato utilizzando la modalità di compatibilità Rosetta affinché gli utenti creativi possano accedere al pannello Adobe Asset Link, in quanto viene creato utilizzando la tecnologia per estensioni CEP. Per ulteriori informazioni, consulta [Photoshop for Apple Silicon](https://helpx.adobe.com/it/photoshop/kb/photoshop-for-apple-silicon.html).


Utilizza Adobe Asset Link per modificare e lavorare con le risorse memorizzate nell’archivio Assets Essentials. Puoi eseguire varie attività, ad esempio:

* Cercare e sfogliare le risorse

* Caricare le risorse

* Ordinare e filtrare le risorse

* Inserire, scaricare e trascinare una risorsa

* Ritirare e consegnare una risorsa

* Visualizzare la cronologia delle versioni e i dettagli dei file

Per istruzioni su come eseguire queste attività, consulta [Gestire le risorse tramite Adobe Asset Link](https://helpx.adobe.com/it/enterprise/using/manage-assets-using-adobe-asset-link.html).
