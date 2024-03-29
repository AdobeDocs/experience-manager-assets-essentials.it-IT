---
title: Cercare e individuare le risorse in [!DNL Assets Essentials]
description: Cerca e individua le risorse in [!DNL Assets Essentials].
role: User
exl-id: be9597a3-056c-436c-a09e-15a03567c85a
source-git-commit: 92cfe963d37df919b8bc29c49da7c8e9bd62638e
workflow-type: tm+mt
source-wordcount: '1524'
ht-degree: 85%

---

# Cercare risorse in [!DNL Assets Essentials] {#search-assets}

>[!CONTEXTUALHELP]
>id="assets_search"
>title="Cerca risorse"
>abstract="Per cercare le risorse, puoi specificare una parola chiave nella barra di ricerca o filtrare le risorse in base al loro stato, al tipo di file, al tipo MIME, alla dimensione e alle date di creazione, modifica e scadenza. Oltre ai filtri standard, puoi anche applicare filtri personalizzati. Puoi salvare i risultati filtrati come Ricerca salvata o Raccolta avanzata."
>additional-url="https://experienceleague.adobe.com/docs/experience-manager-assets-essentials/help/manage-collections.html?lang=it#manage-smart-collection" text="Creare Raccolte avanzate"

[!DNL Assets Essentials] fornisce una funzione di ricerca efficace e attiva per impostazione predefinita. Si tratta di una ricerca full-text completa. La potente funzionalità di ricerca consente di trovare rapidamente la risorsa appropriata e velocizza le attività relative ai contenuti. [!DNL Assets Essentials] consente di effettuare ricerche full-text, anche nei metadati, quali tag avanzati, titolo, data di creazione e copyright.

Per cercare le risorse, effettua le operazioni seguenti:

* Fai clic nella casella di ricerca nella parte superiore della pagina. Per impostazione predefinita, la ricerca viene eseguita all’interno della cartella attuale. Effettua una delle operazioni seguenti:

  ![casella di ricerca](assets/search-box.png)

   * Cerca utilizzando una parola chiave e, se necessario, cambia la cartella. Premi Invio.

   * Per iniziare a lavorare su una risorsa visualizzata di recente, fai clic nella casella di ricerca e seleziona una delle risorse visualizzate di recente che vengono proposte.

## Filtrare i risultati della ricerca {#refine-search-results}

Puoi filtrare i risultati della ricerca in base ai seguenti parametri.

![Filtri di ricerca](assets/filters1.png)

*Figura: Filtrare le risorse trovate in base a vari parametri.*

* Stato risorsa: filtra i risultati della ricerca in base allo stato delle risorse, scegliendo tra `Approved`, `Rejected` o `No Status`.

* Tipo file: filtra i risultati della ricerca in base ai tipi di file supportati come `Images`, `Documents` e `Videos`.
* Tipo MIME: filtra uno o più formati di file supportati. <!-- TBD:  [supported file formats](/help/using/supported-file-formats.md). -->
* Dimensioni immagine: fornisci una o più dimensioni minima e massima per filtrare le immagini. Le dimensioni vengono fornite in pixel e non corrispondono alle dimensioni del file delle immagini.
* Data di creazione: la data di creazione della risorsa, specificata nei metadati. Il formato di data standard è `yyyy-mm-dd`.
* Data di modifica: data dell’ultima modifica delle risorse. Il formato di data standard è `yyyy-mm-dd`.

* Data di scadenza: filtra i risultati della ricerca in base allo stato `Expired` delle risorse. Inoltre, è possibile specificare un intervallo di date di scadenza per le risorse per filtrare ulteriormente i risultati della ricerca.

* Filtri personalizzati: [aggiungi filtri personalizzati](#custom-filters) all’interfaccia utente di Assets Essentials. Per perfezionare i risultati della ricerca, applica i filtri personalizzati in aggiunta a quelli standard.

Puoi ordinare le risorse trovate in ordine crescente o decrescente per `Name`, `Relevance`, `Size`, `Modified` e `Created`. Per impostazione predefinita, le risorse trovate sono ordinate per `Relevance`.

## Gestire i filtri personalizzati {#custom-filters}

**Autorizzazioni richieste:** `Can Edit`, `Owner` o Amministratore.

Assets Essentials consente inoltre di aggiungere filtri personalizzati all’interfaccia utente. Puoi applicare i filtri personalizzati in aggiunta ai [filtri standard](#refine-search-results), per perfezionare i risultati della ricerca.

Assets Essentials fornisce i seguenti filtri personalizzati:

<table>
    <tbody>
     <tr>
      <th><strong>Nome filtro personalizzato</strong></th>
      <th><strong>Descrizione</strong></th>
     </tr>
     <tr>
      <td>Titolo</td>
      <td>Filtra le risorse utilizzando il titolo della risorsa. Il titolo specificato nei criteri di ricerca con distinzione tra maiuscole e minuscole deve corrispondere esattamente al titolo della risorsa da visualizzare nei risultati.</td>
     </tr>
     <tr>
      <td>Nome</td>
      <td>Filtra le risorse utilizzando il nome del file della risorsa. Il nome specificato nei criteri di ricerca con distinzione tra maiuscole e minuscole deve corrispondere esattamente al nome file della risorsa da visualizzare nei risultati.</td>
     </tr>
     <tr>
      <td>Dimensione risorsa</td>
      <td>Filtra le risorse definendo un intervallo di dimensioni, in byte, nei criteri di ricerca per visualizzare la risorsa nei risultati.</td>
     </tr>
     <tr>
      <td>Tag previsti</td>
      <td>Filtra le risorse utilizzando i tag avanzati della risorsa. Il nome del tag avanzato specificato nei criteri di ricerca con distinzione tra maiuscole e minuscole deve corrispondere esattamente al nome di quello della risorsa da visualizzare nei risultati. Non è possibile specificare più tag avanzati nei criteri di ricerca.</td>
     </tr>    
    </tbody>
   </table>

<!--
   You can use a wildcard operator (*) to enable Assets Essentials to display assets in the results that partially match the search criteria. For example, if you define <b>ma*</b> as the search criteria, Assets Essentials displays assets with title, such as, market, marketing, man, manchester, and so on in the results.

   You can use a wildcard operator (*) to enable Assets Essentials to display assets in the results that partially match the search criteria.

   You can use a wildcard operator (*) to enable Assets Essentials to display assets in the results that partially match the search criteria. You can specify multiple smart tags separated by a comma in the search criteria.

   -->

### Aggiungere filtri personalizzati {#add-custom-filters}

Per aggiungere filtri personalizzati:

1. Fai clic su **[!UICONTROL Filtri]**.

1. Nella sezione **[!UICONTROL Filtri personalizzati]**, fai clic su **[!UICONTROL Modifica]** o **[!UICONTROL Aggiungere filtri]**.

   ![Aggiungere filtri personalizzati](assets/add-custom-filters.png)

1. Nella finestra di dialogo **[!UICONTROL Gestione filtri personalizzati]** seleziona i filtri da aggiungere all’elenco di filtri esistente. Seleziona **[!UICONTROL Filtri personalizzati]** per selezionare tutti i filtri.

1. Fai clic su **[!UICONTROL Conferma]** per aggiungere i filtri all’interfaccia utente.

### Rimuovere i filtri personalizzati {#remove-custom-filters}

Per rimuovere i filtri personalizzati:

1. Fai clic su **[!UICONTROL Filtri]**.

1. Nella sezione **[!UICONTROL Filtri personalizzati]**, fai clic su **[!UICONTROL Modifica]**.

1. Nella finestra di dialogo **[!UICONTROL Gestione filtri personalizzati]** deseleziona i filtri da rimuovere dall’elenco di filtri esistente.

1. Fai clic su **[!UICONTROL Conferma]** per rimuovere i filtri dall’interfaccia utente.

## Cercare risorse tramite [!DNL Adobe Firefly] {#search-firefly}

Puoi cercare una risorsa non disponibile in nessuna cartella di risorse utilizzando [!DNL Adobe Firefly] funzione di ricerca risorse in [!DNL Experience Manager Assets]. Questo consente di generare in modo efficiente in tempo reale le risorse che non sono memorizzate nelle cartelle di risorse.

### Prima di iniziare

È necessario disporre di un [!DNL Adobe Express] abbonamento.

### Generare risorse

Per generare nuove risorse tramite [!DNL Adobe Firefly]:

1. Accedi a [!DNL AEM Assets] Workspace.
1. Immetti il nome della risorsa nella barra di ricerca nella parte superiore della pagina.<br>
Ad esempio, puoi cercare una risorsa utilizzando la parola chiave `Bugatti Type 57`. Durante la ricerca della risorsa, non viene trovato alcun risultato, perché la risorsa non è presente in nessuna cartella di risorse.
1. Digita il nome della risorsa nella barra di ricerca al centro della pagina e fai clic su **[!UICONTROL Genera]**.
   ![Integrazione del Firefly](firefly-integration.jpg)
   *Figura: Nessun risultato trovato per Bugatti Type 57 nella cartella delle risorse.*<br>
Le nuove risorse sono state generate correttamente.
   ![Integrazione del Firefly](assets/bugatti-type-57.jpg)
   *Figura: Risorse di riferimento cercate tramite [!DNL Adobe Firefly] funzione di ricerca risorse.* <br>
Puoi caricare queste risorse nella cartella preferita per accedervi facilmente.

### Caricare le risorse

Per caricare la risorsa generata nell’archivio delle risorse:

1. Clic **[!UICONTROL Carica]**.
1. Seleziona la cartella di risorse in cui devi caricare la risorsa e fai clic su **[!UICONTROL Seleziona cartella]**.
   ![Carica risorsa](assets/upload-asset-firefly.jpg)
   *Figura: Selezionare la cartella in cui caricare la risorsa.*

## Ricerche salvate {#saved-search}

La funzionalità di ricerca di [!DNL Assets Essentials] è semplice. Nella casella di ricerca, puoi sia digitare una parola chiave e premere Invio per visualizzare i risultati, sia cercare rapidamente con un solo clic, richiamando parole chiave già utilizzate di recente.

Puoi anche filtrare i risultati della ricerca in base a criteri specifici, secondo i metadati e il tipo di risorse. [!DNL Assets Essentials] consente di salvare i parametri dei filtri utilizzati di frequente, per migliorare l’esperienza di ricerca. Puoi quindi selezionare una ricerca salvata per eseguirla di nuovo applicandone il filtro con un solo clic.

Per salvare una ricerca, cerca le risorse, applica uno o più filtri e fai clic su **[!UICONTROL Salva come]** > **[!UICONTROL Ricerca salvata]** nel pannello [!UICONTROL Filtri.] Puoi anche fare clic su **[!UICONTROL Salva come]** e selezionare **[!UICONTROL Raccolta avanzata]** per salvare i risultati come Raccolta avanzata. Per ulteriori dettagli, consulta [Creare una raccolta avanzata](manage-collections.md#create-a-smart-collection).

![Crea raccolta avanzata](assets/create-smart-collection.png)

<!-- TBD: Search behavior. Full-text search. Ranking and rank boosts. Hidden assets.
Report poor UX that users can only save a filtered search and not a simple search.
.
Are other supported files fully indexed and support full-text search? Eg. audio/videos files can at best have metadata indexed.
Anything about ranking of assets displayed in search results?

What about temporarily hiding an asset (suspending search on it) from the search results? If an asset is undergoing review collaboration, should it be used by others? Should it be hidden in search?

When userA is searching and userB add an asset that matches search results, will the asset display in search as soon as userA refreshes the page? Assuming indexing is near real-time. May not be so for bulk uploads.
-->

## Utilizzare i risultati della ricerca {#work-with-search-results}

Puoi selezionare le risorse da visualizzare nei risultati della ricerca ed effettuare le seguenti operazioni:

* **Trova immagine simile**: trova una risorsa di immagine simile nell’interfaccia utente di Assets in base ai metadati e ai tag avanzati.

* **Dettagli**: visualizza e modifica le proprietà della risorsa.

* **Scarica**: scarica una risorsa.

* **Aggiungi a raccolta**: aggiungi la risorsa selezionata a una raccolta.

* **Fissa in Accesso rapido**: [fissa una risorsa](my-workspace.md) per un accesso più rapido quando necessario in un secondo momento. Tutti gli elementi fissati vengono visualizzati nella sezione **Accesso rapido** dell’area di lavoro personale.

* **Apri in Adobe Express**: modifica un’immagine nell’Adobe Express integrato dalla schermata Experience Manager Assets.

* **Modifica**: modifica l’immagine utilizzando Adobe Express.

* **Condividi collegamento**: [condividi collegamenti](share-links-for-assets.md) per una risorsa con altri utenti in modo che possano accedervi e scaricarla.

* **Elimina**: elimina una risorsa.

* **Copia**: copia una risorsa in un percorso cartella diverso.

* **Sposta**: sposta una risorsa in un percorso cartella diverso.

* **Rinomina**: rinomina una risorsa.

* **Copia in librerie**: aggiungi una risorsa alla libreria.

* **Assegna attività**: assegna attività agli utenti per una risorsa.

* **Osserva**: [monitora le operazioni](manage-notifications.md) eseguite su una risorsa.

## Configurazione della pagina Home Cerca prima {#configuring-search-first-homepage}

Assets Essentials consente di selezionare la pagina di destinazione predefinita per la tua organizzazione. Quando si utilizza la pagina Home Cerca prima, è possibile personalizzare il marchio della pagina configurando le immagini dello sfondo e del logo in base al proprio marchio.

Per configurare la pagina Home Cerca prima, esegui i passaggi seguenti:

1. Passa a **[!UICONTROL Impostazioni]** > **[!UICONTROL Impostazioni generali]**.
1. Seleziona **[!UICONTROL Cerca prima]**. Viene aperta la configurazione correlata Cerca prima. È possibile impostare l’[allineamento](#setting-alignment-search-bar) o [impostare l’immagine di sfondo e il logo](#setting-background-image-and-logo) della pagina Home.

### Impostazione dell’allineamento della barra di ricerca {#setting-alignment-search-bar}

[!DNL Assets Essentials] consente di modificare l’allineamento della barra di ricerca. È possibile fare in modo che la barra di ricerca venga visualizzata al centro o in alto. Seleziona l’allineamento appropriato e fai clic su **[!UICONTROL Salva]**.

![Allineamento nella pagina Home Cerca prima](assets/search-first-alignment.png)

### Impostazione dell’immagine di sfondo e del logo nella pagina Home {#setting-background-image-and-logo}

Puoi aggiungere il logo del tuo brand e l’immagine di sfondo alla pagina Home Cerca prima. Esegui i passaggi seguenti:

1. Accedi alla sezione **[!UICONTROL Immagine di sfondo e logo]** nella **[!UICONTROL pagina Home]**.
1. Fai clic su **[!UICONTROL Sostituisci]** per sfogliare le immagini dall’archivio risorse esistente.
1. Fai clic su **[!UICONTROL Salva]**. Visualizza l’[anteprima](#preview-configured-homepage) delle modifiche per esaminarle.

### Visualizzare l’anteprima della pagina Home configurata {#preview-configured-homepage}

È possibile visualizzare un’anteprima per controllare il layout e la formattazione della pagina Home Cerca prima. Utilizzando **[!UICONTROL Anteprima]**, è possibile correggere il layout o apportare modifiche in base alle necessità. Per visualizzare in anteprima la pagina Home configurata, esegui i passaggi seguenti:

1. Fai clic su **[!UICONTROL Impostazioni generali]** e seleziona **[!UICONTROL Cerca prima]**.
1. Accedi a **[!UICONTROL Personalizza la pagina Home Cerca prima]** e fai clic su **[!UICONTROL Anteprima]**. Attiva o disattiva **[!UICONTROL Tema scuro]** per visualizzare l’anteprima della pagina Home con tema scuro o chiaro.
1. Fai clic su **[!UICONTROL Chiudi]** per chiudere la schermata di anteprima.

   ![Anteprima della pagina Home Cerca prima](assets/search-first-preview.gif)

## Passaggi successivi {#next-steps}

* [Guarda un video per cercare le risorse in Assets Essentials](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/basics/using.html?lang=it)

* Fornisci feedback sui prodotti utilizzando l’opzione [!UICONTROL Feedback] disponibile nell’interfaccia utente di Assets Essentials

* Fornisci feedback alla documentazione utilizzando [!UICONTROL Modifica questa pagina] ![modifica la pagina](assets/do-not-localize/edit-page.png) o [!UICONTROL Segnala un problema] ![crea un problema GitHub](assets/do-not-localize/github-issue.png) disponibile sulla barra laterale destra

* Contatta il [Servizio clienti](https://experienceleague.adobe.com/?support-solution=General&amp;lang=it#support)
