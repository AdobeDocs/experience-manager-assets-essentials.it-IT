---
title: Gestire i metadati
description: Gestire i metadati delle risorse in [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: a176769247bcafcc0497f2480cdec86c5753f218
workflow-type: tm+mt
source-wordcount: '931'
ht-degree: 0%

---


# Metadati in [!DNL Assets Essentials] {#metadata}

Metadati significa dati o descrizione dei dati. Ad esempio, le immagini come risorsa possono contenere informazioni sulla fotocamera su cui è stato fatto clic o informazioni sul copyright. Queste informazioni sono metadati dell&#39;immagine. I metadati sono fondamentali per una gestione efficiente delle risorse. I metadati sono la raccolta di tutti i dati disponibili per una risorsa, ma potrebbero non essere necessariamente contenuti in essa.

I metadati consentono di categorizzare ulteriormente le risorse ed è utile man mano che la quantità di informazioni digitali cresce. È possibile gestire poche centinaia di file in base solo ai nomi dei file, alle miniature e alla memoria. Tuttavia, questo approccio non è scalabile. Non è sufficiente quando il numero di persone coinvolte e il numero di attività gestite aumentano.

Con l’aggiunta dei metadati, il valore di una risorsa digitale aumenta, perché la risorsa diventa,

* Più accessibile: i sistemi e gli utenti possono trovarlo facilmente.
* Gestione più semplice: puoi trovare più facilmente le risorse con lo stesso set di proprietà e applicarvi le modifiche necessarie.
* Completo : la risorsa contiene ulteriori informazioni e contenuti con più metadati.

Per questi motivi, Assets offre i mezzi giusti per creare, gestire e scambiare metadati per le risorse digitali.

## Visualizzare i metadati {#view-metadata}

Per visualizzare i metadati di una risorsa, cerca la risorsa o la risorsa, seleziona la risorsa e fai clic su **[!UICONTROL Details]** nella barra degli strumenti.

![Visualizzare i metadati di una risorsa](assets/metadata-view1.png)

*Figura: Per visualizzare una risorsa e i relativi metadati, fai clic su **[!UICONTROL Details]**nella barra degli strumenti o fai doppio clic sulla risorsa.*

I metadati di base come titolo, descrizione e data di caricamento sono disponibili nella scheda [!UICONTROL Basic] . La scheda [!UICONTROL Advanced] contiene metadati più avanzati, ad esempio il modello di fotocamera, i dettagli dell&#39;obiettivo e i geotag. La scheda [!UICONTROL Tags] contiene tag applicati automaticamente in base al contenuto dell’immagine.

## Aggiornare i metadati {#update-metadata}

Puoi aggiornare manualmente alcuni campi di metadati. I campi includono [!UICONTROL Title], [!UICONTROL Description], [!UICONTROL Author] e [!UICONTROL Keywords].

## Tag {#tags}

[!DNL Assets Essentials] utilizza l’intelligenza artificiale fornita da  [Adobe ](https://www.adobe.com/it/sensei.html) Senseito per applicare automaticamente tag rilevanti a tutte le risorse caricate. Questi tag, giustamente denominati Tag avanzati, consentono di velocizzare i contenuti dei progetti grazie alla possibilità di trovare rapidamente le risorse rilevanti. Gli smart tag sono un esempio di metadati non contenuti nell’immagine.

Gli smart tag vengono applicati in tempo quasi reale e vengono generati in base al contenuto dell’immagine. Quando carichi una risorsa, per un certo periodo di tempo l’interfaccia utente visualizza [!UICONTROL Processing] sulla miniatura della risorsa. Una volta completata l&#39;elaborazione, è possibile [visualizzare i metadati](#view-metadata) e gli smart tag.

![Visualizzare tag avanzati di una risorsa](assets/metadata-view-tags.png)

*Figura: Per visualizzare i tag avanzati di una risorsa, fai clic su **[!UICONTROL Details]**nella barra degli strumenti o fai doppio clic sulla risorsa.*

I tag avanzati contengono anche un punteggio di affidabilità in percentuale. Indica l’affidabilità associata al tag applicato. È possibile moderare gli smart tag applicati automaticamente.

## Aggiungi o aggiorna tag {#manually-tag}

Puoi aggiungere più tag alle risorse, oltre ai tag avanzati che vengono aggiunti automaticamente utilizzando il servizio [!DNL Adobe Sensei] avanzato . Apri una risorsa per l’anteprima, fai clic su [!UICONTROL Tags] e digita le parole chiave desiderate nel campo [!UICONTROL Keywords] . Per aggiungere il tag, premere Invio. [!DNL Assets Essentials] indicizza la parola chiave in tempo quasi reale e il tuo team può presto cercare le risorse aggiornate utilizzando le nuove parole chiave.

Puoi anche rimuovere i tag dalla sezione [!UICONTROL Smart Tags] che vengono aggiunti automaticamente da [!DNL Assets Essentials] a tutte le risorse caricate.

## Moduli metadati {#metadata-forms}

Per impostazione predefinita, Assets Essentials fornisce molti campi di metadati standard. Le organizzazioni hanno esigenze aggiuntive in termini di metadati e necessitano di più campi di metadati per aggiungere metadati specifici per le aziende. I moduli metadati consentono alle aziende di aggiungere campi di metadati personalizzati alla pagina [!UICONTROL Details] di una risorsa. I metadati specifici per l&#39;azienda migliorano la governance e il rilevamento delle risorse.

Puoi configurare i moduli di metadati per diversi tipi di risorse (diversi tipi MIME). Utilizza lo stesso nome del modulo del tipo MIME del file. Le funzioni di base corrispondono automaticamente al nome del modulo le risorse caricate. Ad esempio, se esiste un modulo di metadati con il nome `PDF` o `pdf`, i documenti PDF caricati contengono campi di metadati come definito nel modulo. È possibile creare moduli da zero o riutilizzarli.

>[!IMPORTANT]
>
>Il nuovo modulo metadati per un tipo di file specifico sostituisce completamente il modulo metadati predefinito fornito da [!DNL Assets Essentials]. Se elimini o rinomini un modulo di metadati, i campi di metadati predefiniti sono nuovamente disponibili per le nuove risorse.

Per creare un modulo di metadati, effettua le seguenti operazioni:

1. Nella barra a sinistra, fai clic su **[!UICONTROL Settings]** > **[!UICONTROL Metadata Forms]**.

   ![opzione moduli metadati nella barra laterale sinistra](assets/metadata-forms-sidebar.png)

1. Fai clic su **[!UICONTROL Create]** nell’area in alto a destra dell’interfaccia utente.
1. Specifica un nome per il modulo e fai clic su **[!UICONTROL Create]**.
1. Immetti un nome per la scheda in **[!UICONTROL Settings]** nella barra a destra.
1. Dalla barra a sinistra **[!UICONTROL Components]** disponibile, trascina i componenti richiesti su una scheda del modulo. Trascina i componenti nella sequenza desiderata.

   ![opzione moduli metadati nella barra laterale sinistra](assets/metadata-form-new.png)

   *Figura: Interfaccia per la creazione di moduli con metadati, con opzioni per l’aggiunta di componenti e opzioni per l’anteprima del modulo.*

1. Per ogni componente, nella , fornisci un nome nella barra **[!UICONTROL Settings]** a destra, fornisci una mappatura con le proprietà supportate.
1. Facoltativamente, per un componente, seleziona **[!UICONTROL Required]** per rendere obbligatorio il campo di metadati e seleziona **[!UICONTROL Read-Only]** per rendere il campo non modificabile nella pagina della risorsa [!UICONTROL Details].
1. Facoltativamente, fare clic su **[!UICONTROL Preview]** per visualizzare in anteprima il modulo che si sta creando.
1. Facoltativamente, aggiungi più schede e i componenti richiesti in ogni scheda.
1. Una volta completato il modulo, fare clic su **[!UICONTROL Save]**.

Una volta creato il modulo, questo viene applicato automaticamente quando gli utenti caricano una risorsa del tipo MIME corrispondente.

Per riutilizzare un modulo esistente per creare un nuovo modulo, selezionare un modulo di metadati, fare clic su **[!UICONTROL Copy]** nella barra degli strumenti, specificare un nome e fare clic su **[!UICONTROL Confirm]**. È possibile modificare un modulo di metadati per modificarlo. Quando si modifica un modulo, questo viene utilizzato per le risorse caricate dopo la modifica. Non vengono modificate le risorse esistenti.

<!-- TBD: Cannot create a form using the second option. Documenting only the first option for now.
To reuse an existing form to create a new form, do one of these:

* Select a metadata form and click **[!UICONTROL Copy]** from the toolbar, provide a name, and click **[!UICONTROL Confirm]**.

* Click **[!UICONTROL Create]**, select **[!UICONTROL Use existing form structure as template]** option, and select an existing form. 
-->

<!-- TBD: Queries for PM and engg.

Can we edit the existing metadata in any form?

How to moderate smart tags?

Allow or deny list for smart tags?

What about Tags displayed just above Smart Tags in the UI?

Is there a detailed metadata tab. Where do the other details of an asset go?

How can one search based strictly on the metadata. Similar to AEM Assets GQL queries.
-->

<!-- TBD: Link to related articles if any.

>[!MORELIKETHIS]
>
>* [Search assets](search.md).
-->
