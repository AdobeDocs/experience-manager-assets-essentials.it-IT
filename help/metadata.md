---
title: Gestire i metadati
description: Gestire i metadati delle risorse in [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: cfc105d1-41fc-4418-9905-b2a28a348682
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: tm+mt
source-wordcount: '962'
ht-degree: 66%

---

# Metadati in [!DNL Assets Essentials] {#metadata}

Con metadati si intendono i dati o la descrizione dei dati. Ad esempio, le immagini come risorsa possono contenere informazioni sulla fotocamera con cui sono state scattate o su eventuale copyright. Queste informazioni sono metadati dell’immagine. I metadati sono fondamentali per una gestione efficiente delle risorse. I metadati raccolgono tutti i dati disponibili per una risorsa, ma non sono necessariamente contenuti in essa.

I metadati consentono di categorizzare ulteriormente le risorse, cosa molto utile con il crescere della quantità di informazioni digitali. Ricorrendo solo ai nomi dei file, alle miniature e alla memoria dell’utente, è possibile gestire alcune centinaia di file. Tuttavia, questo approccio non è scalabile. E diventa praticamente inutile quando aumentano sia il numero di persone coinvolte che il numero di attività gestite.

Con l’aggiunta dei metadati, il valore di una risorsa digitale aumenta, perché la risorsa diventa:

* Più accessibile: i sistemi e gli utenti possono trovarla facilmente.
* Più semplice da gestire: puoi trovare e modificare più facilmente le risorse che hanno uno stesso set di proprietà.
* Completa: la risorsa contiene più informazioni e contesto grazie a un maggior numero di metadati.

Per questi motivi, Assets offre i mezzi giusti per creare, gestire e scambiare metadati per le risorse digitali.

## Visualizzare i metadati {#view-metadata}

Per visualizzare i metadati di una risorsa, cerca la risorsa o la risorsa, seleziona la risorsa e fai clic su **[!UICONTROL Dettagli]** nella barra degli strumenti.

![Visualizzare i metadati di una risorsa](assets/metadata-view1.png)

*Figura: Per visualizzare una risorsa e i relativi metadati, fai clic su **[!UICONTROL Dettagli]**dalla barra degli strumenti o fai doppio clic sulla risorsa.*

I metadati di base come titolo, descrizione e data di caricamento sono disponibili nella sezione [!UICONTROL Base] scheda . La [!UICONTROL Avanzate] La scheda contiene metadati più avanzati, ad esempio il modello della fotocamera, i dettagli dell&#39;obiettivo e i geotag. La [!UICONTROL Tag] contiene tag applicati automaticamente in base al contenuto dell’immagine.

## Aggiornare i metadati {#update-metadata}

Puoi aggiornare manualmente alcuni campi di metadati. I campi includono [!UICONTROL Titolo], [!UICONTROL Descrizione], [!UICONTROL Autore]e [!UICONTROL Parole chiave].

## Tag {#tags}

[!DNL Assets Essentials] utilizza l’intelligenza artificiale fornita da [Adobe Sensei](https://www.adobe.com/it/sensei.html) per applicare automaticamente tag rilevanti a tutte le risorse caricate. Questi tag, o “tag avanzati”, consentono di velocizzare le attività relative ai contenuti dei progetti grazie alla possibilità di trovare rapidamente le risorse rilevanti. I tag avanzati sono un esempio di metadati non contenuti nell’immagine.

I tag avanzati vengono applicati quasi in tempo reale e vengono generati in base al contenuto dell’immagine. Quando carichi una risorsa, viene visualizzata l’interfaccia utente [!UICONTROL Elaborazione] sulla miniatura della risorsa per un certo periodo di tempo. Una volta completata l’elaborazione, puoi [visualizzare i metadati](#view-metadata) e i tag avanzati.

![Visualizzare i tag avanzati di una risorsa](assets/metadata-view-tags.png)

*Figura: Per visualizzare i tag avanzati di una risorsa, fai clic su **[!UICONTROL Dettagli]**dalla barra degli strumenti o fai doppio clic sulla risorsa.*

I tag avanzati contengono anche un punteggio di affidabilità in percentuale. Indica l’affidabilità associata al tag applicato. È possibile moderare i tag avanzati applicati automaticamente.

## Aggiungere o aggiornare i tag {#manually-tag}

Puoi aggiungere più tag alle risorse, oltre ai tag avanzati che vengono aggiunti automaticamente utilizzando servizio intelligente [!DNL Adobe Sensei]. Apri una risorsa per l&#39;anteprima, fai clic su [!UICONTROL Tag], e digita le parole chiave desiderate nel [!UICONTROL Parole chiave] campo . Per aggiungere il tag, premi Invio. [!DNL Assets Essentials] indicizza la parola chiave quasi in tempo reale e dopo poco il tuo team può già cercare le risorse aggiornate utilizzando le nuove parole chiave.

È inoltre possibile rimuovere i tag dal [!UICONTROL Tag avanzati] sezione aggiunta automaticamente da [!DNL Assets Essentials] a tutte le risorse caricate.

## Moduli di metadati {#metadata-forms}

Per impostazione predefinita, Assets Essentials fornisce molti campi di metadati standard. Spesso le organizzazioni hanno l’esigenza di aggiungere altri metadati, specifici per l’azienda. I moduli metadati consentono alle aziende di aggiungere campi di metadati personalizzati a una risorsa [!UICONTROL Dettagli] pagina. I metadati specifici per l’azienda migliorano la governance e l’individuazione delle risorse.

Puoi configurare i moduli di metadati per diversi tipi di risorse (diversi tipi MIME). Utilizza un modulo con lo stesso nome del tipo MIME del file. Essentials abbina automaticamente le risorse caricate al nome del modulo. Ad esempio, se è presente un modulo di metadati denominato `PDF` o `pdf`, i documenti PDF caricati contengono i campi di metadati definiti in tale modulo. Puoi creare nuovi moduli o riutilizzare quelli esistenti.

>[!IMPORTANT]
>
>Un nuovo modulo di metadati per un tipo di file specifico sostituisce interamente quello predefinito fornito da [!DNL Assets Essentials]. Se elimini o rinomini un modulo di metadati, i campi di metadati predefiniti diventano di nuovo disponibili per le nuove risorse.

Per creare un modulo di metadati, effettua le seguenti operazioni:

1. Nella barra a sinistra, fai clic su **[!UICONTROL Impostazioni]** > **[!UICONTROL Forms metadati]**.

   ![opzione Moduli di metadati nella barra laterale a sinistra](assets/metadata-forms-sidebar.png)

1. Fai clic su **[!UICONTROL Crea]**, nell’area in alto a destra dell’interfaccia utente.
1. Specifica un nome per il modulo e fai clic su **[!UICONTROL Crea]**.
1. Specifica un nome per la scheda in **[!UICONTROL Impostazioni]** nella barra a destra.
1. Da **[!UICONTROL Componenti]** nella barra a sinistra, trascina i componenti richiesti su una scheda del modulo. Trascina i componenti nella sequenza desiderata.

   ![opzione oduli di metadati nella barra laterale a sinistra](assets/metadata-form-new.png)

   *Figura: Interfaccia per la creazione di moduli di metadati, con opzioni che consentono di aggiungere componenti e visualizzare l’anteprima del modulo.*

1. Per ogni componente, in fornisci un nome nel **[!UICONTROL Impostazioni]** nella barra a destra, fornisci una mappatura con le proprietà supportate.
1. Facoltativamente, per un componente, seleziona **[!UICONTROL Obbligatorio]** per rendere obbligatorio il campo metadati e selezionare **[!UICONTROL Sola lettura]** per rendere il campo non modificabile nella risorsa [!UICONTROL Dettagli] pagina.
1. Facoltativamente, fai clic su **[!UICONTROL Anteprima]** per visualizzare in anteprima il modulo che si sta creando.
1. Se necessario, aggiungi altre schede e i relativi componenti in ogni scheda.
1. Fai clic su **[!UICONTROL Salva]** una volta completato il modulo.

Dopo aver creato il modulo, quest’ultimo viene applicato automaticamente quando gli utenti caricano una risorsa del tipo MIME corrispondente.

Per riutilizzare un modulo esistente per creare un nuovo modulo, selezionare un modulo di metadati e fare clic su **[!UICONTROL Copia]** dalla barra degli strumenti, fornisci un nome e fai clic su **[!UICONTROL Conferma]**. A questo punto puoi modificare il modulo di metadati. Quando modifichi un modulo, quest’ultimo viene utilizzato per le risorse caricate in seguito alla modifica. L’operazione non modifica le risorse esistenti.

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
