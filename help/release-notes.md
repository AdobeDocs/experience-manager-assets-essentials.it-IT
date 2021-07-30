---
title: Note sulla versione
description: Note sulla versione e problemi noti di [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: fd95cf87ae8e5449471cd580405b228c32ede264
workflow-type: tm+mt
source-wordcount: '275'
ht-degree: 1%

---


# Note sulla versione di [!DNL Assets Essentials] {#release-notes}

La versione corrente è la prima versione pubblica di [!DNL Assets Essentials] resa disponibile il 21 giugno 2021. [!DNL Assets Essentials] offre funzionalità di gestione delle risorse leggere e la sua prima versione supporta le seguenti funzioni principali e operazioni CRUD (creazione, lettura, aggiornamento ed eliminazione):

* Carica e aggiungi le risorse, comprese le cartelle nidificate. Visualizzare l&#39;anteprima delle risorse e delle versioni.
* Ricerca full-text, filtri di ricerca sfumati e ricerche salvate per individuare rapidamente le risorse.
* Operazioni di base per la gestione delle risorse, come l’aggiornamento, l’eliminazione, il download e la gestione dei metadati.
* Integrazione con [[!DNL Adobe Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

Attualmente, [!DNL Assets Essentials] è disponibile per i clienti [[!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer.html).

Per ulteriori informazioni sulla soluzione, consulta l’ [introduzione a [!DNL Assets Essentials]](introduction.md). Per iniziare a utilizzare le funzioni, consulta [guida introduttiva](/help/get-started.md).

## Versione corrente {#release-notes-current}

La versione corrente di Assets Essentials è 2021.7.0, rilasciata il 29 luglio 2021, con i seguenti aggiornamenti:

* Puoi creare e gestire moduli di metadati personalizzati da utilizzare per la visualizzazione delle proprietà dei metadati agli utenti nella schermata di dettaglio delle risorse in [!UICONTROL Metadata Forms] opzione in [!DNL Settings].
* Varie correzioni di bug e miglioramenti al prodotto, tra cui prestazioni migliori durante il caricamento di una cartella nidificata con molte sottocartelle.

## Problemi noti {#known-issues}

L’elenco dei problemi noti relativi all’offerta [!DNL Assets Essentials] viene aggiornato e rivisto su base continuativa:

* Per caricare una cartella o risorse, quando trascini gli elementi in una cartella contenente sottocartelle nell’archivio, il caricamento viene eseguito automaticamente in una delle sottocartelle. La soluzione consiste nel fare clic su [!DNL Upload assets] opzione e trascinare nella finestra di dialogo. <!-- CQ-4327753 -->
* Dopo il caricamento della cartella, a volte le nuove cartelle potrebbero essere visualizzate in modo errato nella barra a sinistra anziché nella visualizzazione ad albero. La soluzione consiste nell&#39;aggiornare il browser. <!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

In caso di problemi o richieste di miglioramenti, [fornisci un feedback](#provide-feedback) al team.
