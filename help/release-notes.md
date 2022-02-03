---
title: Note sulla versione
description: Note sulla versione e problemi noti di [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 73d5e66cfb2315f730329b5db9e6e648c1fe017d
workflow-type: tm+mt
source-wordcount: '420'
ht-degree: 1%

---

# Release notes of [!DNL Assets Essentials] {#release-notes}

L&#39;attuale versione di [!DNL Assets Essentials] rilasciato il 27 gennaio 2022. Con questa versione:

* [!DNL Assets Essentials] now enables you to generate a link and share assets with others who do not have access to the [!DNL Assets Essentials] application. You can define: <!-- CQ-4329575 -->

   * Data di scadenza del collegamento

   * Se i destinatari possono scaricare la risorsa dopo aver effettuato l’accesso al collegamento.

   Based on these settings, the recipient of the link can choose to preview the assets or download them.

* Miglioramenti delle prestazioni per [!UICONTROL Create Folder] funzionamento. <!-- CQ-4338818 -->

## Problemi noti {#known-issues}

Elenco dei problemi noti di [!DNL Assets Essentials] l&#39;offerta viene rivista e aggiornata su base continuativa:

* Nessuno

In caso di problemi o richieste di miglioramenti, [fornire feedback](#provide-feedback) alla squadra.

## Versioni precedenti {#past-release}

### Versione 2021.11.0 {#november-2021}

[!DNL Assets Essentials] is released on December 16, 2021, with the following updates:

* Adobe deploys Assets Essentials automatically after completing the provisioning process. The administrators do not need to perform additional steps to deploy Assets Essentials using [!DNL Cloud Manager] user interface. Questa distribuzione automatica sarà disponibile per gli ambienti con provisioning dopo il 6 gennaio 2022.
* Su Adobe Exchange sono disponibili nuove versioni dei plug-in Creative Cloud che funzionano con Assets Essentials - [Adobe Asset Link per Adobe XD v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) e [Adobe Asset Link per Photoshop / InDesign / Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* Vari bug e miglioramenti dei prodotti, inclusi i problemi noti precedenti (le cartelle ora vengono visualizzate correttamente nella struttura di navigazione a sinistra dopo il caricamento<!-- CQ-4337638 -->, il caricamento mediante trascinamento consente all’utente di selezionare la cartella corrente o una sottocartella al momento del rilascio per il caricamento<!-- CQ-4327753 -->).

### Versione 2021.8.0 {#august2021}

[!DNL Assets Essentials] La versione 2021.8.0 è stata rilasciata il 30 agosto 2021 con i seguenti aggiornamenti:

* Integrazioni con [!DNL Adobe Workfront] che consente [!DNL Workfront] gli utenti gestiscono le proprie risorse digitali nel contesto della gestione del proprio lavoro. For more information, see [integrations with other Adobe solutions](/help/integration.md).

### Versione 2021.7.0 {#july2021}

[!DNL Assets Essentials] 2021.7.0 is released on July 29, 2021, with the following updates:

* You can create and manage customized metadata forms to be used for displaying metadata properties to users in the asset detail screen in [!UICONTROL Metadata Forms] option under [!DNL Settings]. Vedi [moduli metadati](metadata.md#metadata-forms).
* Various bug fixes and product improvements, including better performance when uploading a nested folder with many subfolders.

### Versione 2021.6.0 {#june2021}

La prima versione di [!DNL Assets Essentials], reso disponibile il 21 giugno 2021, offre funzionalità di gestione delle risorse leggere. Supporta le seguenti funzioni principali e operazioni CRUD (creazione, lettura, aggiornamento ed eliminazione):

* Carica e aggiungi le risorse, comprese le cartelle nidificate. Visualizzare l&#39;anteprima delle risorse e delle versioni.
* Ricerca full-text, filtri di ricerca sfumati e ricerche salvate per individuare rapidamente le risorse.
* Basic asset management operations like update, delete, download, and manage metadata.
* [!DNL Assets Essentials] è disponibile per [!DNL Adobe Journey Optimizer] per gestire le risorse durante la creazione dei messaggi. For more information, see [integrations with other Adobe solutions](/help/integration.md).
