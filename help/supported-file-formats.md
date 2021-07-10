---
title: Formati di file supportati
description: Formati di file supportati per i vari casi d'uso di [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: c63e9ab1054398dc055643f0dca6631bae881047
workflow-type: tm+mt
source-wordcount: '206'
ht-degree: 24%

---


# Supporto dei formati di file in [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] supporta un&#39;ampia gamma di formati di file e ogni funzionalità supporta diversi tipi di file.

* ![tipo di file immagine ](assets/do-not-localize/image-icon.png) iconaImmagini: GIF, JPG, PNG e TIFF
* ![tipo di file documento ](assets/do-not-localize/document-icon.png) iconaDocumenti: DOCX, PDF, PPTX e XLSX
* ![tipo di file video ](assets/do-not-localize/video-icon.png) iconVideo: MP4

I vari tipi di file supportano diversi livelli di supporto per i casi d’uso e le funzioni come descritto di seguito. Utilizza la legenda per comprendere il livello di supporto.

| Livello di supporto | Descrizione |
|-------------------|-------------------------|
| . | Supportata |
| guscio | Supportato condizionatamente |
| - | Non applicabile |

## Aggiungere, caricare e visualizzare le risorse {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| Tipo risorsa | [Sfoglia](/help/navigate-view.md) | Copia | [Carica](/help/add-delete.md) | Crea | [Elimina](/help/add-delete.md#delete-assets) | Dettagli | Zoom immagine | [Visualizzato di recente](/help/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| Immagini raster | . | . | . | - | . | . | . | . |
| Cartelle | . | . | . | . | . | . | - | - |
| Video MP4 | . | . | . | - | . | guscio | - | . |
| PDF | . | . | . | - | . | . | - | . |
| PSD, AI e INDD | . | . | . | - | . | guscio | - | . |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## Cercare, utilizzare e modificare le risorse {#support-to-search-use-edit}

| Tipo risorsa | [Scarica](/help/manage-organize.md#download) | Inserimento tramite trascinamento | [Editor immagini](/help/edit-images.md) | [Ricerca](/help/search.md) | [Tag avanzati](/help/metadata.md#tags) | [Rinomina](/help/manage-organize.md) | [Versioni](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| Immagini raster | . | . | . | . | . | . | . |
| Cartelle | . | . | - | . | - | . | - |
| Video | . | . | - | . | . | . | - |
| Librerie CC | - | - | - | - | - | . | - |
| PDF | . | . | - | . | . | . | - |
| PSD | . | . | - | . | . | . | - |
| AI | . | . | - | . | . | . | - |
| INDD | . | . | - | . | . | . | - |

## Esaminare le risorse e collaborare {#support-to-review-collaborate}

| Tipo risorsa | Annota | Commento | Creazione di attività e revisione |
|---------------|----------|----------|-------------------------|
| Immagini raster | . | . | . |
| Cartelle | - | - | - |
| Video | - | . | . |
| Librerie CC | - | - | - |
| PDF | - | . | . |
| PSD | - | . | . |
| AI | - | . | . |
| INDD | - | . | . |

## Altre attività di gestione delle risorse {#support-to-manage-assets}

| Tipo risorsa | [Metadati](/help/metadata.md) | [Rappresentazioni](/help/add-delete.md#renditions) | [Cestino](/help/add-delete.md#delete-assets) | Copia | Sposta |
|---------------|-------------------|------------|----------|----------|----------|
| Immagini raster | . | . | . | . | . |
| Cartelle | . | - | . | . | . |
| Video | . | - | . | . | . |
| Librerie CC | . | - | - | - | - |
| PDF | . | - | . | . | . |
| PSD | . | - | . | . | . |
| AI | . | - | . | . | . |
| INDD | . | - | . | . | . |

Gli utenti di [!DNL Adobe Asset Link] possono archiviare le immagini raster nell&#39;archivio [!DNL Assets Essentials] dalle applicazioni [!DNL Adobe Creative Cloud] desktop supportate.

<!-- TBD: Saving the template table separately for later use.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->
