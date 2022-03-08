---
title: Gestire i metadati
description: Gestire i metadati delle risorse in [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: cfc105d1-41fc-4418-9905-b2a28a348682
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: tm+mt
source-wordcount: '962'
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

Per visualizzare i metadati di una risorsa, cerca la risorsa o la risorsa, seleziona la risorsa e fai clic su **[!UICONTROL Dettagli]** nella barra degli strumenti.

![Visualizzare i metadati di una risorsa](assets/metadata-view1.png)

*Figura: Per visualizzare una risorsa e i relativi metadati, fai clic su **[!UICONTROL Dettagli]**dalla barra degli strumenti o fai doppio clic sulla risorsa.*

I metadati di base come titolo, descrizione e data di caricamento sono disponibili nella sezione [!UICONTROL Base] scheda . La [!UICONTROL Avanzate] La scheda contiene metadati più avanzati, ad esempio il modello della fotocamera, i dettagli dell&#39;obiettivo e i geotag. La [!UICONTROL Tag] contiene tag applicati automaticamente in base al contenuto dell’immagine.

## Aggiornare i metadati {#update-metadata}

Puoi aggiornare manualmente alcuni campi di metadati. I campi includono [!UICONTROL Titolo], [!UICONTROL Descrizione], [!UICONTROL Autore]e [!UICONTROL Parole chiave].

## Tag {#tags}

[!DNL Assets Essentials] utilizza l&#39;intelligenza artificiale fornita da [Adobe Sensei](https://www.adobe.com/it/sensei.html) per applicare automaticamente tag rilevanti a tutte le risorse caricate. Questi tag, giustamente denominati Tag avanzati, consentono di velocizzare i contenuti dei progetti grazie alla possibilità di trovare rapidamente le risorse rilevanti. Gli smart tag sono un esempio di metadati non contenuti nell’immagine.

Gli smart tag vengono applicati in tempo quasi reale e vengono generati in base al contenuto dell’immagine. Quando carichi una risorsa, viene visualizzata l’interfaccia utente [!UICONTROL Elaborazione] sulla miniatura della risorsa per un certo periodo di tempo. Una volta completata l&#39;elaborazione, puoi [visualizzare i metadati](#view-metadata) e gli smart tag.

![Visualizzare tag avanzati di una risorsa](assets/metadata-view-tags.png)

*Figura: Per visualizzare i tag avanzati di una risorsa, fai clic su **[!UICONTROL Dettagli]**dalla barra degli strumenti o fai doppio clic sulla risorsa.*

I tag avanzati contengono anche un punteggio di affidabilità in percentuale. Indica l’affidabilità associata al tag applicato. È possibile moderare gli smart tag applicati automaticamente.

## Aggiungi o aggiorna tag {#manually-tag}

Puoi aggiungere più tag alle risorse, oltre ai tag avanzati che vengono aggiunti automaticamente utilizzando la variabile [!DNL Adobe Sensei] servizio intelligente. Apri una risorsa per l&#39;anteprima, fai clic su [!UICONTROL Tag], e digita le parole chiave desiderate nel [!UICONTROL Parole chiave] campo . Per aggiungere il tag, premere Invio. [!DNL Assets Essentials] indicizza la parola chiave in tempo quasi reale e il tuo team può presto cercare le risorse aggiornate utilizzando le nuove parole chiave.

È inoltre possibile rimuovere i tag dal [!UICONTROL Tag avanzati] sezione aggiunta automaticamente da [!DNL Assets Essentials] a tutte le risorse caricate.

## Moduli metadati {#metadata-forms}

Per impostazione predefinita, Assets Essentials fornisce molti campi di metadati standard. Le organizzazioni hanno esigenze aggiuntive in termini di metadati e necessitano di più campi di metadati per aggiungere metadati specifici per le aziende. I moduli metadati consentono alle aziende di aggiungere campi di metadati personalizzati a una risorsa [!UICONTROL Dettagli] pagina. I metadati specifici per l&#39;azienda migliorano la governance e il rilevamento delle risorse.

Puoi configurare i moduli di metadati per diversi tipi di risorse (diversi tipi MIME). Utilizza lo stesso nome del modulo del tipo MIME del file. Le funzioni di base corrispondono automaticamente al nome del modulo le risorse caricate. Ad esempio, se un modulo metadati è basato sul nome `PDF` o `pdf` esiste, quindi i documenti PDF caricati contengono campi di metadati come definito nel modulo. È possibile creare moduli da zero o riutilizzarli.

>[!IMPORTANT]
>
>Il nuovo modulo metadati per un tipo di file specifico sostituisce completamente il modulo metadati predefinito che [!DNL Assets Essentials] fornisce. Se elimini o rinomini un modulo di metadati, i campi di metadati predefiniti sono nuovamente disponibili per le nuove risorse.

Per creare un modulo di metadati, effettua le seguenti operazioni:

1. Nella barra a sinistra, fai clic su **[!UICONTROL Impostazioni]** > **[!UICONTROL Forms metadati]**.

   ![opzione moduli metadati nella barra laterale sinistra](assets/metadata-forms-sidebar.png)

1. Fai clic su **[!UICONTROL Crea]**, nell’area in alto a destra dell’interfaccia utente.
1. Specifica un nome per il modulo e fai clic su **[!UICONTROL Crea]**.
1. Specifica un nome per la scheda in **[!UICONTROL Impostazioni]** nella barra a destra.
1. Da **[!UICONTROL Componenti]** nella barra a sinistra, trascina i componenti richiesti su una scheda del modulo. Trascina i componenti nella sequenza desiderata.

   ![opzione moduli metadati nella barra laterale sinistra](assets/metadata-form-new.png)

   *Figura: Interfaccia per la creazione di moduli con metadati, con opzioni per l’aggiunta di componenti e opzioni per l’anteprima del modulo.*

1. Per ogni componente, in fornisci un nome nel **[!UICONTROL Impostazioni]** nella barra a destra, fornisci una mappatura con le proprietà supportate.
1. Facoltativamente, per un componente, seleziona **[!UICONTROL Obbligatorio]** per rendere obbligatorio il campo metadati e selezionare **[!UICONTROL Sola lettura]** per rendere il campo non modificabile nella risorsa [!UICONTROL Dettagli] pagina.
1. Facoltativamente, fai clic su **[!UICONTROL Anteprima]** per visualizzare in anteprima il modulo che si sta creando.
1. Facoltativamente, aggiungi più schede e i componenti richiesti in ogni scheda.
1. Fai clic su **[!UICONTROL Salva]** una volta completato il modulo.

Una volta creato il modulo, questo viene applicato automaticamente quando gli utenti caricano una risorsa del tipo MIME corrispondente.

Per riutilizzare un modulo esistente per creare un nuovo modulo, selezionare un modulo di metadati e fare clic su **[!UICONTROL Copia]** dalla barra degli strumenti, fornisci un nome e fai clic su **[!UICONTROL Conferma]**. È possibile modificare un modulo di metadati per modificarlo. Quando si modifica un modulo, questo viene utilizzato per le risorse caricate dopo la modifica. Non vengono modificate le risorse esistenti.

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
