---
title: Caricare risorse nell’archivio
description: Caricare le risorse in [!DNL Assets Essentials], visualizza gli stati di caricamento e risolvi i problemi di caricamento.
role: User
exl-id: a85a4455-4456-48af-aee9-f05300677605
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: tm+mt
source-wordcount: '747'
ht-degree: 0%

---

# Caricare le risorse {#add-assets}

Per aggiungere nuove risorse con cui lavorare, carica alcune risorse dal file system locale. <!-- TBD: Many of the [common file formats are supported](/help/supported-file-formats.md). -->

Puoi utilizzare i seguenti metodi per caricare una o più risorse o una cartella contenente risorse:

* Trascina risorse o cartelle nell’interfaccia utente e segui le istruzioni visualizzate.
* Fai clic su **[!UICONTROL Aggiungere risorse]** dalla barra degli strumenti e aggiungi alcuni file alla finestra di dialogo di caricamento.

<!-- TBD: Update this GIF
![Asset and nested folder upload demo](assets/do-not-localize/upload-assets.gif) -->

Puoi utilizzare uno qualsiasi di questi metodi per caricare le risorse dopo aver creato una cartella. Per creare una cartella vuota, fai clic su **[!UICONTROL Crea cartella]** dalla barra degli strumenti. Quando [!DNL Assets Essentials] offre una potente funzionalità di ricerca full-text, e puoi anche utilizzare le cartelle per organizzare meglio le risorse.

Dopo aver selezionato i file, viene visualizzata una finestra di dialogo di conferma per aggiungere altri file o rimuovere i file già selezionati. Per aggiungere altri file a una selezione, fai clic su **[!UICONTROL Sfoglia]** e seleziona **[!UICONTROL Sfoglia file]** o **[!UICONTROL Sfoglia cartelle]**. Aggiungi più file o cartelle dalla stessa cartella o da una cartella diversa.

Una volta messi in coda tutti i file, fai clic su **[!UICONTROL Carica]**.

![Caricare file e cartelle](assets/upload-browse-files-folders.png)

*Figura: Prima di caricare le risorse selezionate, potete aggiungere o rimuovere le risorse dalla coda.*

>[!CAUTION]
>
>Utilizza risorse prive di spazio vuoto nei nomi dei file. Le risposte ai commenti non funzionano per tali risorse.

## Visualizza stato e avanzamento del caricamento {#upload-progress}

Quando si caricano più risorse o cartelle nidificate in [!DNL Assets Essentials], alcune risorse possono non essere caricate per vari motivi, come la duplicazione delle risorse e problemi di rete.

Per tenere traccia dell’avanzamento del caricamento, fai clic su **[!UICONTROL Avanzamento caricamento]** nella barra degli strumenti. Un pannello mostra l’avanzamento del caricamento di tutte le risorse.

Per visualizzare un sottoinsieme di risorse in base all’avanzamento o allo stato del caricamento, utilizza il filtro nella **[!UICONTROL Avanzamento caricamento]** barra laterale. I vari filtri consentono di visualizzare tutte le risorse, i caricamenti completati, i caricamenti in corso, le risorse in coda da caricare, i caricamenti in pausa, le risorse duplicate e le risorse non caricate.

![Filtra l’avanzamento del caricamento in base allo stato del caricamento](assets/filter-upload-progress.png)

*Figura: Filtra le risorse che hai tentato di caricare in base al loro stato di caricamento o all’avanzamento del caricamento.*

Immediatamente dopo il caricamento delle risorse, [!DNL Assets Essentials] elabora le risorse per generare miniature ed elaborare metadati. Per molte risorse, l’elaborazione richiede un po’ di tempo. Se non visualizzi una miniatura e vedi un messaggio di elaborazione sulla miniatura del segnaposto, controlla nuovamente la cartella dopo alcuni minuti. Durante l&#39;elaborazione, tra l&#39;altro, [!DNL Assets Essentials] genera le rappresentazioni, aggiunge tag avanzati e indicizza i dettagli della risorsa per la ricerca.

![Le risorse sono processi al momento del caricamento e la tessera visualizza l’elaborazione](assets/upload-processing.png)

*Figura: Le risorse caricate mostrano l’elaborazione sulla tessera che vengono elaborate.*

## Rendering delle risorse {#renditions}

[!DNL Assets Essentials] elabora le risorse caricate in tempo quasi reale e per molti tipi di file supportati genera rappresentazioni. Creati per le immagini, i rendering sono versioni ridimensionate dell&#39;immagine caricata. Puoi scaricare non solo la risorsa, ma anche le rappresentazioni per utilizzare una versione appropriata. Puoi visualizzare tutte le rappresentazioni di una risorsa quando [visualizzare in anteprima una risorsa](/help/navigate-view.md#preview-assets).

![Rappresentazioni](assets/renditions-view-download.png)

*Figura: Visualizza e scarica le rappresentazioni.*

## Gestire i caricamenti non riusciti {#resolve-upload-fails}

Se il caricamento di una risorsa supportata non riesce per qualche motivo, fai clic su **[!UICONTROL Riprova]** dal [!UICONTROL Avanzamento caricamento] riquadro.

![Riprova un caricamento non riuscito](assets/upload-retry.png)

*Figura: Riprova se il caricamento di un file supportato non riesce per qualche motivo.*

Se tenti di caricare risorse duplicate, queste non vengono caricate finché non confermi esplicitamente il caricamento. Inizialmente, le risorse duplicate vengono contrassegnate come caricamenti non riusciti. Per risolvere il problema, puoi semplicemente creare una versione, eliminare e sostituire le risorse esistenti o creare una copia duplicata rinominando la risorsa. Puoi risolvere tali errori una risorsa alla volta o farlo in blocco per tutti i duplicati non riusciti in una sola volta.

![Gestire le risorse duplicate una alla volta](assets/uploads-manage-duplicates.png)

*Figura: Per le risorse duplicate che non possono essere caricate per impostazione predefinita, risolvi il problema una risorsa alla volta.*

![Gestire tutti i caricamenti in blocco non riusciti](assets/upload-progress-manage-failed-uploads.png)

*Figura: Per le risorse duplicate che non possono essere caricate per impostazione predefinita, risolvi i problemi per tutte le risorse alla volta.*

>[!TIP]
>
>Puoi caricare le risorse nell’archivio DAM direttamente da [!DNL Creative Cloud] applicazioni desktop. Scopri come [[!DNL Assets Essentials] si integra con [!DNL Adobe Asset Link]](/help/integration.md).

## Eliminare risorse o cartelle {#delete-assets}

Gli utenti possono eliminare singole risorse o cartelle che non sono più necessarie. Per eliminare una risorsa o una cartella, effettua una delle seguenti operazioni:

* Utilizza l’opzione disponibile sulla miniatura di una risorsa o di una cartella.

   ![Opzioni sulla miniatura della risorsa per gestire una risorsa](assets/options-on-thumbnail.png)

   *Figura: Le azioni per file e cartelle sono disponibili nel riquadro della risorsa o della cartella.*

* Seleziona una risorsa o una cartella e fai clic su **[!UICONTROL Elimina]** ![icona Elimina](assets/do-not-localize/delete-icon.png) nella barra degli strumenti.
