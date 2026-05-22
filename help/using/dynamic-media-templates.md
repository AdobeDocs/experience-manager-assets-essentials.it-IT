---
title: Come gestire i modelli di Dynamic Media
description: Scopri come creare modelli Dynamic Media utilizzando l’editor modelli WYSIWYG, includendo più immagini e livelli di testo per creare rapidamente banner e volantini da utilizzare nelle applicazioni a valle.
hide: true
hidefromtoc: true
role: User
exl-id: 07de648e-4ae2-4524-8e05-3cf10bb6006d
source-git-commit: 4c176db86c9f3219f2cb63edda71435a2aa76850
workflow-type: tm+mt
source-wordcount: '3000'
ht-degree: 99%

---

# Modelli Dynamic Media{#dynamic-media-templates}

| [Best practice per la ricerca](https://experienceleague.adobe.com/it/docs/experience-manager-cloud-service/content/assets/best-practices/search-best-practices) | [Best practice per i metadati](https://experienceleague.adobe.com/it/docs/experience-manager-cloud-service/content/assets/best-practices/metadata-best-practices) | [Content Hub](https://experienceleague.adobe.com/it/docs/experience-manager-cloud-service/content/assets/content-hub/product-overview) | [Documentazione di AEM Assets per sviluppatori](https://developer.adobe.com/experience-cloud/experience-manager-apis/) |
| ------------- | --------------------------- |---------|-----|

>[!CONTEXTUALHELP]
>id="assets_dm_templates"
>title="Gestire i modelli Dynamic Media"
>abstract="Crea e personalizza banner di immagini e testo all’istante, con un’interfaccia WYSIWYG di facile utilizzo e incorpora l’URL di Dynamic Media in qualsiasi applicazione di prime o terze parti, per promuovere esperienze altamente coinvolgenti. Provalo."
>additional-url="https://images-tv.adobe.com/mpcv3/4477/b74738ca-888c-4a37-9a9e-14fabd68ee45_1738206841.854x480at800_h264.mp4" text="Guarda il video"

Crea modelli Dynamic Media utilizzando l’editor modelli WYSIWYG, includendo più immagini e livelli di testo per creare rapidamente banner e volantini da utilizzare nelle applicazioni a valle. Inoltre, puoi aggiungere parametri ai livelli immagine e testo inclusi nel modello e utilizzare gli [URL Dynamic Media](https://experienceleague.adobe.com/it/docs/commerce-admin/content-design/wysiwyg/storage/catalog-urls-dynamic-media) per aggiornare i valori di tali livelli in tempo reale.

Ecco alcune delle funzioni principali:

* **Editor modelli WYSIWYG di Dynamic Media:** per creare banner personalizzabili con livelli immagine e testo.
* **Parametrizzazione dei livelli:** per definire coppie chiave-valore dinamiche per i livelli per abilitare gli aggiornamenti in tempo reale.
* **Supporto URL Dynamic Media:** utilizza gli URL di Dynamic Media per i modelli, integrando valori personalizzati da applicazioni di prima parte o di terze parti.
* **Controllo visibilità livelli:** per nascondere o mostrare dinamicamente i livelli in base alle esigenze.
* **Ridimensionamento testo avanzato:** per regolare automaticamente le dimensioni del testo e adattarla alle aree designate.

Alcuni dei vantaggi principali dei modelli di Dynamic Media includono:

* **Ottimizzazione 1:1 Personalizzazione:** adatta il contenuto ai segnali dei clienti in tempo reale.
* **Riduzione delle attività manuali:** automatizza e accelera la creazione e la gestione dei contenuti.
* **Garanzia di esperienze omnicanale coerenti:** per mantenere la coerenza del brand su tutti i canali.
* **Riutilizzo efficace dei contenuti:** evita contenuti usa e getta e sfrutta la scalabilità di modelli dinamici basati su parametri.
* **Riduzione dei rischi:** aggiorna prezzi, sconti e collegamenti in tempo reale.
* **Ottimizzazione del coinvolgimento dei clienti:** crea esperienze interattive e contestualmente rilevanti.

>[!NOTE]
>
>I clienti con abbonamenti allo SKU Sicurezza avanzata non possono utilizzare alcuna funzionalità di Dynamic Media, inclusi i modelli di Dynamic Media, in questo programma di servizi cloud.

## Prima di iniziare{#prerequisites-for-dynamic-media-wysiwyg-template}

Per creare un modello di Dynamic Media, è necessario disporre di:

1. Accesso a Dynamic Media.
1. [Sincronizzazione delle immagini disponibili nell’istanza di AEM Assets con Dynamic Media per poterle utilizzare per la creazione del modello](https://experienceleague.adobe.com/it/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm).
1. Nell’interfaccia utente touch, è stato verificato quanto segue:
   * Nella pagina **[!UICONTROL Modifica configurazione Dynamic Media]**, la **[!UICONTROL Modalità di sincronizzazione elementi Dynamic Media]** impostata su **[!UICONTROL Opzione disabilitata per impostazione predefinita]** non è applicata a tutte le cartelle di AEM (**[!UICONTROL Sincronizza tutti i contenuti]** è deselezionata). Per ulteriori informazioni, consulta [Configurazione dei servizi cloud di Dynamic Media](https://experienceleague.adobe.com/it/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm).
   * **[!UICONTROL La modalità di sincronizzazione elementi di Dynamic Media]** è impostata su **[!UICONTROL Abilita per le sottocartelle]** per la cartella o sottocartella di destinazione in cui verrà salvato il modello dopo la creazione. Per ulteriori informazioni, consulta [Configurazione dei servizi cloud di Dynamic Media](https://experienceleague.adobe.com/it/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm).

## Creare un modello WYSIWYG di Dynamic Media{#how-to-create-dynamic-media-wysiwyg-template}

Per creare un modulo DM, segui questi passaggi:

1. [Creare un’area di lavoro vuota](#create-a-canvas)
1. [Aggiungere immagini all’area di lavoro](#add-images-to-the-canvas)
1. [Aggiungere livelli di testo all’area di lavoro](#add-text-to-the-canvas)
1. [Modificare o eliminare un livello](#edit-or-delete-a-layer)
1. [Parametrizzare i livelli](#parameterise-a-layer)

### Creare un’area di lavoro vuota{#create-a-canvas}

Per creare un’area di lavoro vuota, esegui i passaggi seguenti:

1. Passa ad Assets Essentials e fai clic su **[!UICONTROL Risorse Dynamic Media]** disponibile nel pannello a sinistra.

   ![Modelli Dynamic Media](/help/using/assets/DM-Assets1.png)

1. Fai clic su **[!UICONTROL Crea modello]** per salvare il modello in Risorse Dynamic Media oppure passa a una cartella e fai clic su **[!UICONTROL Crea modello]** per salvare il modello in tale cartella. Viene visualizzata la finestra di dialogo **[!UICONTROL Nuovo modello]**.
   ![come creare modelli dinamici personalizzabili in tempo reale](/help/using/assets/new-template.png)
Per [creare una cartella](/help/using/add-delete.md) in **[!UICONTROL Risorse Dynamic Media]**, crea una cartella in **[!UICONTROL Risorse]**. La struttura di cartelle in **[!UICONTROL Risorse]** viene replicata in **[!UICONTROL Risorse Dynamic Media]**.
1. Specifica un nome modello, definisci la larghezza e l’altezza dell’area di lavoro e fai clic su **[!UICONTROL Crea]**. Viene visualizzata un’area di lavoro vuota con opzioni di menu su entrambi i lati da utilizzare per la creazione del modello. Passa il puntatore del mouse sulle opzioni di menu per visualizzarne la descrizione comando.
   ![modello personalizzabile in tempo reale](/help/using/assets/blank-canvas-page.png)

>[!NOTE]
>
> L’intervallo consentito di larghezza e altezza è compreso tra 50 e 5000.

**Opzioni di menu nel riquadro a destra:** utilizza queste opzioni per aggiungere all’area di lavoro le immagini e i livelli di testo necessari.

* ![Modelli DM](/help/using/assets/add-image.svg): fai clic per aggiungere immagini all’area di lavoro.
* ![modelli personalizzabili](/help/using/assets/add-text.svg): fai clic per aggiungere testi all’area di lavoro.
* ![modelli personalizzabili](/help/using/assets/show-layers-list.svg): fai clic per visualizzare l’elenco di tutti i livelli, immagine e testo, nell’area di lavoro. Ogni immagine e testo aggiunto all’area di lavoro viene rappresentato come un livello separato.

**Opzioni di menu nel riquadro a sinistra:** utilizza queste opzioni per le azioni comuni dell’editor come indicato di seguito.

* ![Modelli DM](/help/using/assets/layer-selector.svg): seleziona un livello.
* ![crea un modello immediatamente personalizzabile](/help/using/assets/undo.svg): fai clic per annullare l’ultima azione oppure premi **Ctrl** + **Z** (Windows) o **Cmd** + **Z** (Mac).
* ![modello per creare rapidamente i banner](/help/using/assets/redo.svg): fai clic per ripetere l’ultima azione oppure premi **Ctrl** + **Y** (Windows) o **Cmd** + **Y** (Mac).
* ![modello per creare rapidamente i volantini](/help/using/assets/zoomin.svg): fai clic per ingrandire l’area di lavoro oppure premi **Ctrl** + **+** (Windows) o Cmd + **+** (Mac).
* ![modello per creare rapidamente i banner](/help/using/assets/ZoomOut-1.svg): fai clic per ridurre l’area di lavoro oppure premi **Ctrl** + **-** (Windows) o **Cmd** + **-** (Mac).
* Premi **Backspace** o **elimina** per eliminare il livello selezionato se non stai modificando testo o proprietà.

Fai clic su ![modello per creare rapidamente i volantini](/help/using/assets/show-layers-list.svg) **>** altre opzioni (![](/help/using/assets/three-dots.svg)) sul livello dell’area di lavoro per modificare le dimensioni dell’area di lavoro in qualsiasi momento durante la creazione del modello.
![](/help/using/assets/edit-canvas1.png)

>[!NOTE]
>
> I modelli consentono un massimo di 20 livelli, inclusa l’area di lavoro.

### Aggiungere immagini all’area di lavoro{#add-images-to-the-canvas}

Per aggiungere immagini all’area di lavoro, esegui i passaggi seguenti:

1. Fai clic su ![crea un banner in pochi secondi](/help/using/assets/add-image.svg) per visualizzare il pannello [Selettore risorse](https://experienceleague.adobe.com/it/docs/experience-manager-cloud-service/content/assets/manage/asset-selector/overview-asset-selector). Il pannello mostra le immagini dell’istanza di AEM Assets che sono sincronizzate con Dynamic Media.
1. Sfoglia il pannello o usa le parole chiave nella barra di ricerca per trovare un’immagine specifica.
1. Trascina un’immagine nell’area di lavoro per utilizzarla. Consulta il [**[!UICONTROL pannello Proprietà]**](#reposition-resize-delete-a-layer) per ridimensionare o riposizionare un livello nell’area di lavoro.
   ![crea un banner in pochi secondi](/help/using/assets/add-image-to-canvas.png)

### Aggiungere livelli di testo all’area di lavoro{#add-text-to-the-canvas}

Per aggiungere livelli di testo all’area di lavoro, effettua le seguenti operazioni:

1. Fai clic su ![creazione rapida di nuovi banner](/help/using/assets/add-text.svg) per aggiungere un livello di testo all’area di lavoro e aprire il pannello Proprietà.
1. Seleziona il livello e fai clic sul testo per aggiornarlo.
1. Abilita **[!UICONTROL Ridimensionamento testo avanzato]** nel pannello Proprietà per regolare automaticamente la lunghezza del testo e la dimensione del font in modo che si adattino in modo ottimale all’area designata.
   ![Migliori banner personalizzabili](/help/using/assets/add-text-layer.png)

Consulta il [**[!UICONTROL pannello Proprietà]**](#reposition-resize-delete-a-layer) per riposizionare, ridimensionare, ruotare o eliminare il livello. Formatta il testo con il font, le dimensioni, il colore, lo stile e l’allineamento desiderati (nel livello) modificandone i valori nei rispettivi campi nella sezione **[!UICONTROL Testo]** del pannello.

>[!NOTE]
>
> Per utilizzare un tipo di font diverso da quello predefinito della famiglia di font Adobe Sans F2, è necessario caricare e pubblicare il file del font in AEM Assets e Dynamic Media. Se nell’istanza sono presenti font obsoleti, assicurati di eseguire una [rielaborazione](/help/using/reprocessing.md) per poterli visualizzare nell’editor Modelli.

### Modificare o eliminare un livello {#edit-or-delete-a-layer}

Per modificare o eliminare un livello dell’area di lavoro, esegui la procedura seguente:

1. Fai clic su ![modelli con supporto per aggiornamenti dinamici](/help/using/assets/show-layers-list.svg) e seleziona il livello nell’area di lavoro o nell’elenco Livelli.
1. Fai clic su **altre opzioni** (![modelli con supporto per aggiornamenti in tempo reale](/help/using/assets/three-dots.svg)) per modificare o eliminare il livello.
1. Fai clic su **[!UICONTROL Elimina]** per eliminare il livello.
1. Fai clic su **[!UICONTROL Modifica]** per modificare il livello utilizzando il [**[!UICONTROL pannello Proprietà]**](#reposition-resize-delete-a-layer).
   ![Creazione rapida di banner](/help/using/assets/edit-delete-layer.png)

### Pannello Proprietà{#properties-panel}

Per passare al pannello delle proprietà di un livello:

1. Fai clic su ![creazione rapida dei contenuti](/help/using/assets/show-layers-list.svg).
1. Seleziona il livello dall’elenco.

In questo pannello viene visualizzata la posizione del punto centrale del livello sul piano dell’area di lavoro (valori X e Y), le dimensioni del livello (larghezza e altezza) e le opzioni di formattazione del testo.

![Creazione rapida dei contenuti](/help/using/assets/properties-panel.png)

Dal pannello delle proprietà di un livello, seleziona un altro livello nell’area di lavoro per passare al relativo pannello delle proprietà.


#### Riposizionare, ridimensionare, ruotare o eliminare un livello{#reposition-resize-delete-a-layer}

Per modificare un livello testo o immagine, consulta le seguenti azioni di modifica dei livelli:

* **Riposizionare il livello:** trascina il livello per spostarlo in qualsiasi punto dell’area di lavoro. Questa azione aggiorna i valori X e Y nel pannello delle proprietà.
* **Ridimensionare il livello:** seleziona il livello e trascina le relative maniglie di ridimensionamento. Questa azione aggiorna i valori W (larghezza) e H (altezza) nel pannello delle proprietà.
* **Ruotare il livello:** trascina la maniglia quadrata posizionata verticalmente sopra il livello per ruotarlo intorno al centro. Questa azione aggiorna i valori degli angoli nel pannello delle proprietà.
* **Eliminare il livello:** premi **Backspace** o **Canc** e quindi fai clic su **[!UICONTROL Conferma]** per eliminare il livello selezionato.

#### Opzioni di formattazione del testo{#text-formatting-options-on-properties-panel}

Formatta il testo con il font, le dimensioni, il colore, lo stile e l’allineamento desiderati (nel livello) modificandone i valori nei rispettivi campi nella sezione **[!UICONTROL Testo]** del pannello.

**[!UICONTROL Ridimensionamento testo avanzato]** Accertati di includere **[!UICONTROL Ridimensionamento testo avanzato]** ([Adattamento del testo](https://experienceleague.adobe.com/it/docs/dynamic-media-developer-resources/image-serving-api/image-serving-api/http-protocol-reference/text-formatting/r-copy-fitting)) per adattarlo in modo ottimale a qualsiasi testo nell’area designata, modificandone in modo intelligente la dimensione e la lunghezza del font. Questa funzionalità impedisce l’overflow del testo o riduce al minimo gli spazi in eccesso nella parte inferiore.
![Creazione di contenuti in poco tempo](/help/using/assets/smart-text-resize.png)

### Parametrizzare i livelli {#parameterise-a-layer}

Dopo aver creato un modello con più livelli di immagini e testi, imposta i parametri dei livelli selezionati. Quando un livello o una sua proprietà vengono parametrizzati, viene loro assegnata una coppia chiave-valore (definita anche parametro). Includendo questo parametro nell’URL del modello, puoi aggiornare posizione, dimensioni o contenuto del livello in tempo reale, ottenendo una personalizzazione immediata.

Per parametrizzare un livello:

1. fai clic su ![creazione immediata di contenuti](/help/using/assets/show-layers-list.svg), seleziona un livello e fai clic su **[!UICONTROL Parametri]**. Viene visualizzato il pannello **[!UICONTROL Parametri]**.
1. Attiva **[!UICONTROL Includi parametro]** per parametrizzare una proprietà. Consulta [questa sezione](#parameterisation-options-or-allowed-parameters) per conoscere il comportamento della proprietà dopo la parametrizzazione.
1. **Facoltativo:** rinominare il nome del parametro. Il nome di un parametro è seguito da un suffisso. Per un livello selezionato, tutte le relative proprietà con parametri condividono lo stesso nome di livello seguito da un suffisso variabile. Rinomina il livello seguendo una convenzione di denominazione semantica: in questo modo, quando includerai il parametro nell’URL, il suo nome spiegherà chiaramente il contenuto o la funzione del livello stesso.
1. Fai clic su **[!UICONTROL Salva]**.
   ![Creazione immediata di contenuti](/help/using/assets/parameterise-a-layer.png)
Per passare dal pannello Parametri di un’immagine al livello testo, seleziona il livello nell’area di lavoro e fai clic su **[!UICONTROL Parametri]**.

#### Opzione del pannello Parametri {#parameterisation-options-or-allowed-parameters}

Le proprietà con parametri possono essere incluse come parametri URL nell’URL del modello per modificare il modello in tempo reale utilizzando l’URL.

**Parametri immagine:**

**X:** includi questo parametro per spostare il livello orizzontalmente lungo la sua linea centrale, parallelamente all’asse delle X del piano del modello, modificando il valore del parametro nell’URL.
**Y:** includi questo parametro per spostare il livello verticalmente lungo la linea centrale, parallelamente all’asse delle Y del piano del modello, modificando il valore del parametro nell’URL.
**Larghezza:** includi questo parametro per regolare la larghezza del livello modificando il valore del parametro nell’URL.
**Altezza:** includi questo parametro per regolare l’altezza del livello modificando il valore del parametro nell’URL.
**Nascondi:** includi questo parametro per nascondere o mostrare il livello nel modello utilizzando 0 (mostra) e 1 (nascondi).
**Origine:** includi questo parametro per sostituire l’immagine del livello con una nuova immagine modificando il percorso dell’immagine nel valore del parametro nell’URL.

**Parametri di formattazione del testo:**

Includi i parametri seguenti per modificare il testo, il font, il colore e la dimensione direttamente dall’URL, aggiornandone i relativi valori.

**Testo:** includi questo parametro per aggiornare il testo dall’URL.
**Famiglia font:** includi questo parametro per aggiornare il font del testo dall’URL.
**Dimensione del font:** includi questo parametro per aggiornare la dimensione del font del testo dall’URL.
**Colore testo:** includi questo parametro per aggiornare il colore del font del testo dall’URL.

### Raggruppare i livelli per controllarne contemporaneamente la visibilità{#group-layers}

Un altro modo per mantenere flessibili i modelli consiste nell’utilizzare un singolo nome di parametro per controllare più livelli. Questa strategia è utile per il parametro di visibilità (nascondi o mostra livelli), per aggiornare la progettazione o gli elementi grafici da un singolo modello.

Segui questi passaggi per assegnare lo stesso nome ai parametri di visibilità (![creazione rapida di contenuti](/help/using/assets/Visibility-icon.svg)) di più livelli, consentendo di nasconderli o visualizzarli contemporaneamente.

1. Passa al [**[!UICONTROL pannello Proprietà]**](#parameterise-a-layer) di un livello.
1. Attiva/disattiva il parametro **[!UICONTROL Nascondi]** se non è già stato impostato in precedenza come parametro.
1. **Facoltativo:** rinominare il parametro Nascondi.
1. Copia il nome del parametro Nascondi.
1. Passa al pannello Parametri degli altri livelli selezionandoli dall’area di lavoro e, se non sono parametrizzati, attiva/disattiva il parametro **[!UICONTROL Nascondi]**.
1. Sostituisci il nome del **[!UICONTROL parametro Nascondi]** con il nome copiato.
1. Fai clic su **[!UICONTROL Salva]** per raggruppare i livelli.
1. Esegui i passaggi 3 e 4 nella sezione [**[!UICONTROL Anteprima e pubblicazione]**](#preview-and-publish-template-and-copy-template-deliver-url) per visualizzare le modifiche.

## Anteprima e pubblicazione del modello per copiare l’URL di consegna{#preview-and-publish-template-and-copy-template-deliver-url}

Per visualizzare in anteprima e pubblicare il modello e copiare l’URL di consegna, effettua le seguenti operazioni:

1. Nella pagina dell’area di lavoro, fai clic su **[!UICONTROL Anteprima]**. Inoltre, puoi passare ad **[!UICONTROL Assets Essentials]** **>** **[!UICONTROL Dynamic Media Assets]** **>** trova e seleziona il modello **>** fai clic su **[!UICONTROL Modifica modello]** **>** fai clic su **[!UICONTROL Anteprima]**. Nella pagina di anteprima vengono visualizzati il modello, i relativi parametri (livelli e proprietà con parametri), lo stato di pubblicazione e l’opzione **[!UICONTROL Pubblica]**.
1. Seleziona i parametri dal pannello **[!UICONTROL Parametri modello]** per modificarne i valori e aggiornare immediatamente contenuto, dimensioni, posizione o formattazione del testo del relativo livello nell’anteprima. Ad esempio:
   1. Seleziona un livello di testo e modificane il testo oppure
   1. Seleziona un livello immagine, fai clic su ![creazione di contenuti in tempo reale](/help/using/assets/add-image.svg), seleziona un’immagine dal selettore risorse, quindi fai clic su **[!UICONTROL Aggiorna]**.

   Il modello viene aggiornato immediatamente, visualizzando il testo modificato e sostituendo l’immagine precedente con quella nuova. Inoltre, il valore del parametro immagine riflette il nuovo percorso immagine. Analogamente, è possibile ridimensionare un livello regolandone i valori e le modifiche vengono applicate al modello in tempo reale.
1. Seleziona dall’elenco il parametro Nascondi per i [livelli raggruppati](#group-layers) al fine di mostrarli o nasconderli nel modello.
1. **Facoltativo:** modifica il valore del parametro **[!UICONTROL Nascondi]** tra 0 e 1 e fai clic su **[!UICONTROL Aggiorna]** per visualizzare le modifiche. I livelli con lo stesso parametro Nascondi vengono nascosti o visualizzati insieme. Allo stesso modo, puoi controllare la visibilità dei livelli dall’URL.

   ![creazione di contenuti in tempo reale](/help/using/assets/dm-templates-publish-status.png)
Puoi anche attivare/disattivare l’opzione **[!UICONTROL Includi tutti i parametri]** per modificare tutti i valori dei parametri visualizzati e visualizzare gli aggiornamenti nell’anteprima del modello.
   <br>
1. Per pubblicare il modello nella pagina di anteprima, fai clic su **[!UICONTROL Pubblica]** e conferma la pubblicazione. Viene visualizzato il messaggio Pubblicazione completata e lo stato di pubblicazione viene aggiornato a Pubblicato.

>[!NOTE]
>
>La pubblicazione del modello richiede prima la pubblicazione delle immagini del modello.

### Copiare l’URL di consegna

I parametri selezionati nella pagina **[!UICONTROL Anteprima]** diventano i parametri dell’URL nell’URL del modello.

Per copiare l’URL del modello pubblicato visualizzato nell’anteprima:

1. Fai clic su **[!UICONTROL Copia URL]**. Viene visualizzata la finestra di dialogo **[!UICONTROL Copia URL]**. Seleziona e copia l’URL visualizzato. Il primo parametro nell’URL inizia dopo un punto interrogativo **(?)** e una coppia chiave-valore inizia con **$** e termina con **&amp;**. La chiave e il valore sono separati dal segno uguale **(=)**, con la chiave a sinistra e il valore a destra.
1. Incolla questo URL nella scheda del browser e visualizza il modello live. Personalizza il modello in tempo reale aggiornando il valore del parametro richiesto (valore della chiave) nell’URL direttamente come mostrato nel [passaggio 2](#preview-and-publish-template-and-copy-template-deliver-url) della sezione **Anteprima e pubblicazione**.
1. Usa questo URL per gestire rapidamente il merchandising dei tuoi prodotti o servizi. Puoi condividere questo URL con i tuoi clienti o integrarlo nel tuo sito web o in qualsiasi applicazione di terze parti per visualizzare il banner e aggiornarlo in tempo reale, così da riflettere le offerte in corso.

Scopri come creare un modello di Dynamic Media in questo video, passo dopo passo.
>[!VIDEO](https://video.tv.adobe.com/v/3443281)

## Aggiornamenti in tempo reale al modello dall’URL{#update-the-template-from-the-url}

Modificare i parametri direttamente nell’URL può essere un grattacapo. Per semplificare:

1. Copia l’URL e incollalo in un blocco note.
1. Utilizza Cmd+F (Mac) o Ctrl+F (Windows) per trovare e modificare i valori dei parametri. Ad esempio:
   * Sostituisci i percorsi immagine per i livelli immagine.
   * Regola le dimensioni e le posizioni dei livelli (se [parametrizzate](#parameterise-a-layer)).
   * Modifica testo, font, colore, dimensione o allineamento per i livelli di testo.
   * Modifica i valori di visibilità compresi tra 0 e 1.

Incolla questo URL aggiornato nel browser per visualizzare le modifiche.

## Modificare il modello{#edit-the-template}

Modifica il modello seguendo questi passaggi:

1. In Assets Essentials, fai clic su **[!UICONTROL Dynamic Media Assets]**.
2. Vai alla posizione del modello.
3. Seleziona il modello.
4. Fai clic su **[!UICONTROL Modifica modello]**. Nell’area di lavoro del modello vengono visualizzati il modello e l’elenco di tutti i relativi livelli nel pannello Livelli. Inizia a modificare il modello in base alle tue esigenze.

## Aspetti importanti da prendere in considerazione {#important-points-to-note}

* Dopo aver creato un modello con livelli immagine parametrizzati per gli aggiornamenti dinamici, accertati che le immagini destinate agli aggiornamenti futuri condividano le stesse dimensioni delle immagini parametrizzate. In questo modo le immagini si adatteranno perfettamente ai livelli, senza fuoriuscire o lasciare spazi vuoti. Attualmente, il modello non supporta il ridimensionamento automatico delle immagini all’interno dei livelli.
* Non è disponibile alcun supporto per sottostringhe in un livello di testo. L’utente non può applicare proprietà di font diverse alla sottostringa di un livello di testo.
* Al momento il supporto di più società Dynamic Media non è disponibile con i modelli di Dynamic Media.
* In caso di copia o spostamento, il selettore della destinazione mostra tutte le cartelle (comprese le cartelle sincronizzate con elementi non appartenenti a Dynamic Media). Inoltre, al momento non mostra le risorse dei modelli di Dynamic Media (si tratta di limitazioni del selettore della destinazione).
* Qualsiasi operazione di aggiornamento di una cartella (ad esempio, Pubblica o Elimina) da Assets influisce sui modelli Dynamic Media disponibili all’interno di tale cartella.
* Il cestino non funziona per i modelli di Dynamic Media. Se una risorsa viene spostata nel cestino e quindi ripristinata, viene ripristinata in AEM ma non in Dynamic Media. Lo stesso vale per i modelli di Dynamic Media.

## Consulta anche

1. Esplora [Dynamic Media e le sue funzionalità](https://experienceleague.adobe.com/it/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media)
1. Esplora [Dynamic Media con funzionalità OpenAPI](https://experienceleague.adobe.com/it/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/dynamic-media-open-apis-overview)
