---
title: Formati di file supportati
description: Formati di file supportati per i vari casi d'uso di [!DNL Assets Essentials]
role: User,Leader,Administrator,Architect,Developer
contentOwner: AG
source-git-commit: 5bae37e18ac587aaacaa004e5ec02775888d7f9a
workflow-type: tm+mt
source-wordcount: '196'
ht-degree: 26%

---


# Supporto dei formati di file in [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] supporta un&#39;ampia gamma di formati di file e ogni funzionalità supporta diversi tipi di file.

* ![tipo di file immagine ](assets/do-not-localize/image-icon.png) iconaImmagini: GIF, JPG, PNG e TIFF
* ![tipo di file documento ](assets/do-not-localize/document-icon.png) iconaDocumenti: DOCX, PDF, PPTX e XLSX
* ![tipo di file video ](assets/do-not-localize/video-icon.png) iconVideo: MP4

I vari tipi di file supportano diversi livelli di supporto per i casi d’uso e le funzioni come descritto di seguito. Utilizza la legenda per comprendere il livello di supporto.

| Livello di supporto | Descrizione |
|---------------|-------------------------|
| . | Supportata |
| * | Supportato condizionatamente |
| - | Non applicabile |

* Altre attività di gestione delle risorse:

## Aggiungere, caricare e visualizzare le risorse {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| Tipo risorsa | Sfoglia | Copia | Carica | Crea | Elimina | Dettagli | Zoom immagine | Visualizzato di recente |
|---------------|----------|------|----------|----------|----------|----------|------------|-----------------|
| Immagini raster | . |  | . | - | . | . | . | . |
| Cartelle | . |  | . | . | . | . | - | - |
| Video | . |  | . | - | . | * | - | . |
| Librerie CC | . |  | . | . | . | . | - | - |
| PDF | . |  | . | - | . | . | - | . |
| PSD | . |  | . | - | . | * | - | . |
| AI | . |  | . | - | . | * | - | . |
| INDD | . |  | . | - | . | * | - | . |

## Cercare, utilizzare e modificare le risorse {#support-to-search-use-edit}

| Tipo risorsa | Scarica | Inserimento tramite trascinamento | Editor immagini | Ricerca | Tag avanzati | Rinomina | Versioni |
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

| Tipo risorsa | Metadati | Rappresentazioni | Cestino | Copia | Sposta | [!DNL Adobe Asset Link] check-in |
|---------------|----------|------------|----------|----------|----------|----------------------------------|
| Immagini raster | * | . | . | . | . | . |
| Cartelle | * | - | . | . | . | - |
| Video | * | - | . | . | . | - |
| Librerie CC | * | - | - | - | - | - |
| PDF | * | - | . | . | . | - |
| PSD | * | - | . | . | . | - |
| AI | * | - | . | . | . | - |
| INDD | * | - | . | . | . | - |

<!-- TBD: Saving template table separately.
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
