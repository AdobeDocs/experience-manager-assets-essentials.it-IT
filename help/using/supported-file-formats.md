---
title: Formati di file supportati
description: Formati di file supportati per i vari casi d’uso di [!DNL Assets Essentials]
role: User,Leader,Admin,Developer
contentOwner: AG
exl-id: bc44e98d-446e-41ff-b5b4-9dc324834630
source-git-commit: b3c726122425c9a89a5d6c0ac35b652d20d8e0b9
workflow-type: tm+mt
source-wordcount: '372'
ht-degree: 100%

---

# Supporto dei formati di file in [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] supporta un’ampia gamma di formati di file e ogni funzionalità supporta diversi tipi di file.

* ![icona per file immagine](assets/image-icon.svg) Immagini: JPG, PNG, GIF, TIFF e altri
* ![icona creative cloudtype](assets/creative-cloud-files.svg) File Creative Cloud: PSD, PSB, IA e INDD
* ![icona per file da fotocamera](assets/camera-icon.svg) File Camera Raw: CR2/CR3, NEF, SRW/SRF e altri
* ![icona per file documento](assets/document-icon.svg) Documenti: DOCX, PDF, PPTX e XLSX
* ![icona per file video](assets/video-icon.svg) Video: MP4

[!DNL Assets Essentials] supporta qualsiasi formato di file binario con servizi di base quali archiviazione, caricamento, copia, spostamento, eliminazione e aggiunta di metadati.

[!DNL Assets Essentials] supporta anche i file Camera Raw di una vasta gamma di produttori di fotocamere, tra cui Canon (CR2/CR3), Nikon (NEF), Sony (SRW/SRF), Fujifilm (RAF), Olympus (ORF) e altri, grazie ad Adobe Camera Raw.

I vari tipi di file sono supportati per diversi casi d’uso e funzioni, come riepilogato di seguito. La legenda seguente indica i diversi livelli di supporto.

| Livello di supporto | Descrizione |
|-------------------|-------------------------|
| ✓ | Funzione supportata |
| ✓ ‡ | Funzione supportata a determinate condizioni |
| − | Non applicabile |

## Aggiungere, caricare e visualizzare le risorse {#support-to-upload-view}

<!-- 
TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| Tipo risorsa | [Sfogliare](/help/using/navigate-view.md) | Copiare | [Caricare](/help/using/add-delete.md) | Creare | [Eliminare](/help/using/add-delete.md#delete-assets) | Dettagli | Zoom immagine | [Visualizzato di recente](/help/using/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| Immagini raster | ✓ | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| File non elaborati | ✓ | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| Cartelle | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | − | − |
| Video MP4 | ✓ | ✓ | ✓ | − | ✓ | ✓ ‡ | − | ✓ |
| PDF | ✓ | ✓ | ✓ | − | ✓ | ✓ | − | ✓ |
| PSD, IA, PSB e INDD | ✓ | ✓ | ✓ | − | ✓ | ✓ ‡ | − | ✓ |
| Altri file binari | ✓ | ✓ | ✓ | − | ✓ | ✓ | − | ✓ |

<!-- 
Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## Cercare, utilizzare e modificare le risorse {#support-to-search-use-edit}

| Tipo risorsa | [Download](/help/using/manage-organize.md#download) | Inserimento tramite trascinamento | [Editor immagine](/help/using/edit-images.md) | [Ricerca](/help/using/search.md) | [Tag avanzati](/help/using/metadata.md#tags) | [Rinomina](/help/using/manage-organize.md) | [Versioni](/help/using/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| Immagini raster | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| File non elaborati | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| Cartelle | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |
| Video | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| CC Libraries | − | − | − | − | − | ✓ | ✓ |
| PDF | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| PSD e PSB | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| AI e INDD | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |
| Altri file binari | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |


## Rivedere le risorse e collaborare {#support-to-review-collaborate}

| Tipo risorsa | Annotazioni | Commenti | Creazione di attività e revisione |
|---------------|----------|----------|-------------------------|
| Immagini raster | ✓ | ✓ | ✓ |
| File non elaborati | ✓ | ✓ | ✓ |
| Cartelle | − | − | − |
| Video | − | ✓ | ✓ |
| CC Libraries | − | − | − |
| PDF | − | ✓ | ✓ |
| PSD, PSB, IA e INDD | − | ✓ | ✓ |
| Altri file binari | − | ✓ | ✓ |
| DOC | − | ✓ | ✓ |
| DOCX | − | ✓ | ✓ |
| PPT | − | ✓ | ✓ |
| PPTX | − | ✓ | ✓ |
| XLS | − | ✓ | ✓ |
| XLSX | − | ✓ | ✓ |
| TXT | − | ✓ | ✓ |
| RTF | − | ✓ | ✓ |

## Altre attività di gestione risorse {#support-to-manage-assets}

| Tipo risorsa | [Metadati](/help/using/metadata.md) | [Rappresentazioni](/help/using/add-delete.md#renditions) | [Eliminare](/help/using/add-delete.md#delete-assets) | Copiare | Spostare |
|---------------|-------------------|------------|----------|----------|----------|
| Immagini raster | ✓ | ✓ | ✓ | ✓ | ✓ |
| File non elaborati | ✓ | ✓ | ✓ | ✓ | ✓ |
| Cartelle | ✓ | − | ✓ | ✓ | ✓ |
| Video | ✓ | − | ✓ | ✓ | ✓ |
| CC Libraries | ✓ | − | − | − | − |
| PDF | ✓ | − | ✓ | ✓ | ✓ |
| AI e INDD | ✓ | − | ✓ | ✓ | ✓ |
| PSD e PSB | ✓ | ✓ | ✓ | ✓ | ✓ |
| Altri file binari | ✓ | − | ✓ | ✓ | ✓ |

Gli utenti di [!DNL Adobe Asset Link] possono caricare e consegnare (caricare una nuova versione) i file nell’archivio di [!DNL Assets Essentials] dalle applicazioni desktop [!DNL Adobe Creative Cloud] supportate.

<!-- 
TBD: Saving the template table separately for later use.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD, PSB           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->

## Passaggi successivi {#next-steps}

* Fornisci feedback sui prodotti utilizzando l’opzione [!UICONTROL Feedback] disponibile nell’interfaccia utente di Assets Essentials

* Fornisci feedback alla documentazione utilizzando [!UICONTROL Modifica questa pagina] ![modifica la pagina](assets/do-not-localize/edit-page.png) o [!UICONTROL Segnala un problema] ![crea un problema GitHub](assets/do-not-localize/github-issue.png) disponibile sulla barra laterale destra

* Contatta il [Servizio clienti](https://experienceleague.adobe.com/it?support-solution=General#support)
