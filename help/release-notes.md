---
title: Note sulla versione
description: Note sulla versione e problemi noti di [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 0c849c92562f9102819aaea627f5945030b27a1e
workflow-type: tm+mt
source-wordcount: '380'
ht-degree: 1%

---

# Note sulla versione di [!DNL Assets Essentials] {#release-notes}

L&#39;attuale versione di [!DNL Assets Essentials] rilasciato il 16 dicembre 2021. Con questa versione:

* Adobe distribuisce automaticamente Assets Essentials dopo il completamento del processo di provisioning. Gli amministratori non devono eseguire passaggi aggiuntivi per distribuire Assets Essentials utilizzando [!DNL Cloud Manager] interfaccia utente. Questa distribuzione automatica sarà disponibile per gli ambienti con provisioning dopo il 6 gennaio 2022.
* Su Adobe Exchange sono disponibili nuove versioni dei plug-in Creative Cloud che funzionano con Assets Essentials - [Adobe Asset Link per Adobe XD v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) e [Adobe Asset Link per Photoshop / InDesign / Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* Vari bug e miglioramenti dei prodotti, inclusi i problemi noti precedenti (le cartelle ora vengono visualizzate correttamente nella struttura di navigazione a sinistra dopo il caricamento<!-- CQ-4337638 -->, il caricamento mediante trascinamento consente all’utente di selezionare la cartella corrente o una sottocartella al momento del rilascio per il caricamento<!-- CQ-4327753 -->).

Per ulteriori informazioni sulla soluzione, consulta la sezione [introduzione a [!DNL Assets Essentials]](introduction.md). Per iniziare a utilizzare le funzioni, vedi [introduzione](/help/get-started.md).

## Problemi noti {#known-issues}

Elenco dei problemi noti di [!DNL Assets Essentials] l&#39;offerta viene rivista e aggiornata su base continuativa:

* Le singole risorse non possono essere caricate nella cartella superiore (Risorse), ma solo in una sottocartella del sistema. <!-- CQ-4337638 -->

In caso di problemi o richieste di miglioramenti, [fornire feedback](#provide-feedback) alla squadra.

## Versioni precedenti {#past-release}

### Versione 2021.8.0 {#august2021}

[!DNL Assets Essentials] La versione 2021.8.0 è stata rilasciata il 30 agosto 2021 con i seguenti aggiornamenti:

* Integrazioni con [!DNL Adobe Workfront] che consente [!DNL Workfront] gli utenti gestiscono le proprie risorse digitali nel contesto della gestione del proprio lavoro. Per ulteriori informazioni, consulta [integrazioni con altre soluzioni Adobe](/help/integration.md).

### Versione 2021.7.0 {#july2021}

[!DNL Assets Essentials] 2021.7.0 è rilasciato il 29 luglio 2021 con i seguenti aggiornamenti:

* Puoi creare e gestire moduli di metadati personalizzati da utilizzare per visualizzare le proprietà dei metadati agli utenti nella schermata di dettaglio delle risorse in [!UICONTROL Metadata Forms] opzione sotto [!DNL Settings]. Vedi [moduli metadati](metadata.md#metadata-forms).
* Varie correzioni di bug e miglioramenti al prodotto, tra cui prestazioni migliori durante il caricamento di una cartella nidificata con molte sottocartelle.

### Versione 2021.6.0 {#june2021}

La prima versione di [!DNL Assets Essentials], reso disponibile il 21 giugno 2021, offre funzionalità di gestione delle risorse leggere. Supporta le seguenti funzioni principali e operazioni CRUD (creazione, lettura, aggiornamento ed eliminazione):

* Carica e aggiungi le risorse, comprese le cartelle nidificate. Visualizzare l&#39;anteprima delle risorse e delle versioni.
* Ricerca full-text, filtri di ricerca sfumati e ricerche salvate per individuare rapidamente le risorse.
* Operazioni di base per la gestione delle risorse, come l’aggiornamento, l’eliminazione, il download e la gestione dei metadati.
* [!DNL Assets Essentials] è disponibile per [!DNL Adobe Journey Optimizer] per gestire le risorse durante la creazione dei messaggi. Per ulteriori informazioni, consulta [integrazioni con altre soluzioni Adobe](/help/integration.md).
