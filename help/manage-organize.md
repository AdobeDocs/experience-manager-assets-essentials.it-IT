---
title: Gestire le risorse digitali
description: Sposta, elimina, copia, rinomina, aggiorna e aggiorna le risorse in [!DNL Assets Essentials].
role: User,Leader
contentOwner: AG
exl-id: b01e98b9-0cc2-47c5-9f5b-79b8e6bef39f
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: tm+mt
source-wordcount: '614'
ht-degree: 0%

---

# Gestire le risorse {#manage-assets}

Puoi eseguire facilmente diverse attività di gestione delle risorse digitali (DAM) utilizzando l’interfaccia intuitiva di [!DNL Assets Essentials]. Dopo aver aggiunto le risorse, puoi cercare, scaricare, spostare, copiare, rinominare, eliminare, aggiornare e modificare le risorse.

Utilizzo [!DNL Assets Essentials] per eseguire le seguenti attività di gestione delle risorse. Quando selezioni una risorsa, nella barra degli strumenti nella parte superiore vengono visualizzate le seguenti opzioni:

![Opzioni della barra degli strumenti quando si seleziona una risorsa](assets/toolbar-image-selected.png)

*Figura: Opzioni disponibili nella barra degli strumenti per un’immagine selezionata.*

* ![icona deseleziona](assets/do-not-localize/close-icon.png) Deseleziona la selezione.
* ![icona dettagli](assets/do-not-localize/edit-in-icon.png) Fai clic su per visualizzare l’anteprima di una risorsa e i metadati dettagliati. Quando visualizzi l’anteprima, puoi visualizzare le versioni e modificare un’immagine.
* ![icona di download](assets/do-not-localize/download-icon.png) Scarica la risorsa selezionata nel file system locale.
* ![icona Elimina](assets/do-not-localize/delete-icon.png) Elimina la risorsa o la cartella selezionata.
* ![icona di pagamento](assets/do-not-localize/checkout-icon.png) Paga la risorsa selezionata.
* ![icona copia](assets/do-not-localize/copy-icon.png) Copia il file o la cartella selezionati.
* ![icona Sposta](assets/do-not-localize/move-icon.png) Sposta la risorsa o la cartella selezionata in una posizione diversa nella gerarchia del repository.
* ![icona rinomina](assets/do-not-localize/rename-icon.png) Rinomina la risorsa o la cartella selezionata. In caso contrario, la ridenominazione non riesce e viene visualizzato un avviso. Riprova con un nuovo nome.
* ![icona assegna attività](assets/do-not-localize/review-delegate-icon.png) Assegna attività ad altri utenti per collaborare a una risorsa.

Puoi visualizzare le stesse opzioni sulle miniature delle risorse.

![Opzioni sulla miniatura della risorsa per gestire una risorsa](assets/options-on-thumbnail.png)

[!DNL Assets Essentials] visualizza nella barra degli strumenti solo le opzioni pertinenti in base al tipo di risorsa selezionata.

![Opzioni della barra degli strumenti quando si seleziona una risorsa](assets/toolbar-folder-selected.png)

*Figura: Opzioni disponibili nella barra degli strumenti per una cartella selezionata.*

![Opzioni della barra degli strumenti quando si seleziona una risorsa](assets/toolbar-pdf-selected.png)

*Figura: Opzioni disponibili nella barra degli strumenti per un file PDF selezionato.*

## Scaricare e distribuire le risorse {#download}

È possibile selezionare una o più risorse o cartelle o una combinazione di entrambe e scaricare la selezione nel file system locale. Puoi modificare le risorse e caricarle nuovamente o distribuirle all’esterno [!DNL Assets Essentials]. Inoltre, è possibile [scaricare le rappresentazioni](/help/add-delete.md#renditions) di una risorsa.

## Controllo delle versioni delle risorse {#versions-of-assets}

<!-- 
TBD: query for engineering: How many versions are maintained. What happens when we reach that limit? Are old versions automatically removed? -->

[!DNL Assets Essentials] versioni le risorse quando vengono caricate di nuovo che vengono aggiornate o modificate. Puoi visualizzare la cronologia delle versioni precedenti e ripristinare una versione precedente delle risorse come versione più recente, ripristinata se necessario a una versione precedente. Le versioni delle risorse vengono create nei seguenti scenari:

* Carica una nuova risorsa con lo stesso nome file di una risorsa esistente e nella stessa cartella della risorsa esistente. [!DNL Assets Essentials] richiede di sovrascrivere la risorsa precedente o di salvare la nuova risorsa come versione. Vedi [caricare risorse duplicate](/help/add-delete.md#resolve-upload-fails).

   ![Crea versioni durante il caricamento](assets/uploads-manage-duplicates.png)

   *Figura: Quando carichi una risorsa con lo stesso nome di una risorsa esistente, puoi creare una versione della risorsa.*

* Modifica un’immagine e fai clic su **[!UICONTROL Salva come versione]**. Vedi [modificare le immagini](/help/edit-images.md).

   ![Salvare l’immagine modificata come versione](assets/edit-image2.png)

   *Figura: Salva l’immagine modificata come versione.*

* Apri le versioni di una risorsa esistente. Fai clic su **[!UICONTROL Nuova versione]** e carica una versione più recente della risorsa nell’archivio.

   ![Opzione per caricare una nuova versione di una risorsa dalla cronologia delle versioni](assets/view-asset-versions2.png)

### Visualizzare le versioni di una risorsa {#view-versions}

Quando carichi una copia duplicata o una copia modificata di una risorsa, puoi crearne le versioni. Il controllo delle versioni consente di rivedere le risorse storiche e, se necessario, ripristinare una versione precedente.

Per visualizzare le versioni, apri l’anteprima di una risorsa e fai clic su **[!UICONTROL Versioni]** ![Icona Versioni](assets/do-not-localize/versions-clock-icon.png) dalla barra laterale destra. Per visualizzare in anteprima una versione specifica, selezionala. Per ripristinarlo, fai clic su **[!UICONTROL Rendi più recente]**.

Puoi anche creare versioni dalla timeline delle versioni. Seleziona la versione più recente e fai clic su **[!UICONTROL Nuova versione]** e carica una nuova copia della risorsa dal file system locale.

![Visualizzare le versioni di una risorsa](assets/view-asset-versions1.png)

*Figura: Visualizza le versioni di una risorsa, ripristina una versione precedente o carica un&#39;altra nuova versione.*
