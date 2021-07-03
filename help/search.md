---
title: Cercare e individuare le risorse in [!DNL Assets Essentials]
description: Cerca e scopri le risorse in [!DNL Assets Essentials].
role: User
source-git-commit: 5bae37e18ac587aaacaa004e5ec02775888d7f9a
workflow-type: tm+mt
source-wordcount: '386'
ht-degree: 1%

---


# Cercare risorse in [!DNL Assets Essentials] {#search-assets}

[!DNL Assets Essentials] fornisce una ricerca efficace, che funziona solo per impostazione predefinita. La ricerca è completa in quanto è ricerca full-text. La potente funzionalità di ricerca consente di scoprire rapidamente la risorsa appropriata e di migliorare la velocità dei contenuti. [!DNL Assets Essentials] consente di effettuare ricerche full-text e anche tramite i metadati, quali smart tag, titolo, data di creazione e copyright.

Per cercare le risorse,

* Fai clic nella casella di ricerca nella parte superiore della pagina. Per impostazione predefinita, esegue la ricerca all’interno della cartella attualmente in navigazione. Effettua una delle operazioni seguenti:

   ![casella di ricerca](assets/search-box.png)

   * Cerca utilizzando una parola chiave e facoltativamente cambia la cartella. Premere Invio.

   * Inizia a lavorare con una risorsa visualizzata di recente, ricercandola direttamente. Fai clic nella casella di ricerca e seleziona una risorsa visualizzata di recente dai suggerimenti.

## Filtrare i risultati della ricerca {#refine-search-results}

Puoi filtrare i risultati della ricerca in base ai seguenti parametri.

![Filtri di ricerca](assets/filters1.png)

*Figura: Filtrare le risorse ricercate in base a vari parametri.*

* Tipo di file: Filtra i risultati della ricerca in base ai tipi di file supportati: `Images`, `Documents` e `Videos`.
* Tipo MIME: Filtrare uno o più formati di file supportati. <!-- TBD:  [supported file formats](/help/supported-file-formats.md). -->
* Dimensione immagine: Fornisci una delle dimensioni minima e massima per filtrare le immagini. Le dimensioni vengono fornite in pixel e non corrispondono alle dimensioni del file delle immagini.
* Crea data: La data di creazione della risorsa, come specificato nei metadati. Il formato della data standard utilizzato è `yyyy-mm-dd`.
* Data di modifica: Data dell’ultima modifica delle risorse. Il formato della data standard utilizzato è `yyyy-mm-dd`.

Puoi ordinare le risorse ricercate in ordine crescente o decrescente di `Name`, `Relevancy`, `Size`, `Modified` e `Created`.

## Ricerche salvate {#saved-search}

La funzionalità di ricerca è abbastanza semplice da utilizzare in [!DNL Assets Essentials]. Dall&#39;interno della casella di ricerca, non solo è possibile digitare una parola chiave e premere ritorno per visualizzare i risultati, è anche possibile cercare rapidamente di nuovo le parole chiave ricercate di recente in un solo clic.

Puoi anche filtrare i risultati della ricerca in base a criteri specifici, in base ai metadati e al tipo di risorse. Per i filtri utilizzati di frequente, per migliorare l’esperienza di ricerca, [!DNL Assets Essentials] consente di salvare i parametri di ricerca. Puoi quindi selezionare la ricerca salvata per eseguire la ricerca e applicare il filtro con un solo clic.

Per creare una ricerca salvata, cerca alcune risorse, applica uno o più filtri e fai clic su [!UICONTROL Save Search] nel pannello [!UICONTROL Filters] .

![Ricerca salvata dal pannello Filtri](assets/saved-search.png)

<!-- TBD: Search behavior. Full-text search. Ranking and rank boosts. Hidden assets.
Report poor UX that users can only save a filtered search and not a simple search.
.
Are other supported files fully indexed and support full-text search? Eg. audio/videos files can at best have metadata indexed.
Anything about ranking of assets displayed in search results?

What about temporarily hiding an asset (suspending search on it) from the search results? If an asset is undergoing review collaboration, should it be used by others? Should it be hidden in search?

When userA is searching and userB add an asset that matches search results, will the asset display in search as soon as userA refreshes the page? Assuming indexing is near real-time. May not be so for bulk uploads.
-->
