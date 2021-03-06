---
title: Gestire le raccolte
description: Una raccolta è un insieme di risorse in Experience Manager Assets Essentials. Puoi utilizzare le raccolte per condividere le risorse tra i vari utenti.
exl-id: 33c889f5-c989-4772-9591-db62f50e5c80
source-git-commit: 096906eded35dc0a8c231534204bfc672c2430b7
workflow-type: tm+mt
source-wordcount: '686'
ht-degree: 75%

---

# Gestire le raccolte {#manage-collections}

Una raccolta è un insieme di risorse in Experience Manager Assets Essentials. Puoi utilizzare le raccolte per condividere le risorse tra i vari utenti.

A differenza delle cartelle, una raccolta può includere risorse da posizioni diverse.

<!--
You can share collections with various users that are assigned different levels of privileges, including viewing, editing, and so on.
-->

Puoi condividere più raccolte con un utente. Ogni raccolta contiene riferimenti alle risorse. L’integrità dei riferimenti alle risorse viene mantenuta tra le varie raccolte.

![Raccolte](assets/collections.png)

Per gestire e utilizzare le raccolte, puoi eseguire le seguenti attività:

* [Creare una raccolta](#create-collection)

* [Aggiungere risorse a una raccolta](#add-assets-to-collection)

* [Rimuovere risorse da una raccolta](#remove-assets-from-collection)

* [Visualizzare e modificare i metadati di una raccolta](#view-edit-collection-metadata)

* [Scaricare una raccolta](#download-collection)

* [Eliminare una raccolta](#delete-collection)

## Creare una raccolta {#create-collection}

Per creare una raccolta:

1. Fai clic su **[!UICONTROL Raccolte]** nella barra a sinistra, quindi fai clic su **[!UICONTROL Crea raccolta]**.

1. Specifica un titolo e una descrizione facoltativa per la raccolta.

1. Seleziona se devi creare una raccolta privata o pubblica. È disponibile una raccolta pubblica per visualizzare e modificare tutti gli utenti. Tuttavia, una raccolta privata è disponibile per il creatore e gli utenti con privilegi di amministratore.

1. Fai clic su **[!UICONTROL Crea]** per creare la raccolta.

![Creare la raccolta](assets/create-collection.png)

<!--
   
   for viewing and editing only to users with the appropriate [permissions](#manage-collection-access).

-->

## Aggiungere risorse a una raccolta {#add-assets-to-collection}

Per aggiungere risorse a una raccolta:

1. Fai clic su **[!UICONTROL Risorse]** nella barra a sinistra e seleziona le risorse.

1. Fai clic su **[!UICONTROL Aggiungi alla raccolta]**.

1. Nella finestra di dialogo [!UICONTROL Raccolte] seleziona le raccolte a cui aggiungere le risorse selezionate.

1. Fai clic su **[!UICONTROL Aggiungi]** per aggiungere la risorsa alle raccolte selezionate.

Per aggiungere risorse a una raccolta, puoi anche fare clic su **[!UICONTROL Raccolte]** nella barra a sinistra, poi clic sulla raccolta a cui aggiungere le risorse, quindi **[!UICONTROL Aggiungi alla raccolta]**, seleziona le risorse e fai clic su **[!UICONTROL Seleziona]**.

## Creare una raccolta avanzata {#create-smart-collection}

Salva i risultati della ricerca come Raccolta avanzata per aggiornare dinamicamente il contenuto della raccolta. Se nell’archivio Assets Essentials sono state aggiunte risorse che soddisfano i criteri di ricerca definiti durante la creazione della Raccolta avanzata, i contenuti di questa vengono aggiornati automaticamente.

Per creare una raccolta avanzata:

1. Fai clic su **[!UICONTROL Filtro]** e [definire i criteri di ricerca](search.md##refine-search-results).

1. Fai clic su **[!UICONTROL Salva con nome]** quindi seleziona **[!UICONTROL Raccolta avanzata]**.

1. Sulla [!UICONTROL Creare una raccolta avanzata] Specifica un titolo e una descrizione per la Raccolta avanzata.

1. Seleziona **[!UICONTROL Raccolta pubblica]** se hai bisogno di tutti gli utenti per accedere alla raccolta. Seleziona **[!UICONTROL Raccolta privata]** se hai bisogno di un gruppo limitato di utenti per accedere alla raccolta.

1. Fai clic su **[!UICONTROL Crea]** per creare la Raccolta avanzata.

![Creare una raccolta avanzata](assets/create-smart-collection.png)


## Rimuovere risorse da una raccolta {#remove-assets-from-collection}

Per rimuovere le risorse da una raccolta:

1. Fai clic su **[!UICONTROL Raccolte]** nella barra a sinistra per visualizzare l’elenco delle raccolte.

1. Fai clic sulla raccolta e seleziona le risorse da rimuovere.

1. Fate clic su **[!UICONTROL Rimuovi]**.

<!--

## Manage access to a Private collection {#manage-collection-access}

The permission management for collections function in the same manner as folders in [!DNL Assets Essentials]. Administrators can manage the access levels for collections available in the repository. As an administrator, you can create user groups and assign permissions to those groups to manage access levels. You can also delegate the permission management privileges to user groups at the collection-level.

For more information, see [Manage permissions for folders and collections](manage-permissions.md).

-->

<!--

## Search a collection {#search-collections}

Click **[!UICONTROL Collections]** in the left rail and use the Search box to specify a text as the criteria to search for a collection. [!DNL Assets Essentials] uses the specified text to search collection names, metadata including tags defined for a collection and returns appropriate results.

>[!NOTE]
>
>Assets Essentials performs search in collections available at the root level. It does not perform search in assets and folders available in collections.

-->

## Visualizzare e modificare i metadati di una raccolta {#view-edit-collection-metadata}

I metadati di una raccolta includono dati sulla raccolta, come titolo e descrizione.

Per visualizzare e modificare i metadati di una raccolta:

1. Fai clic su **[!UICONTROL Raccolte]** nella barra a sinistra, seleziona una raccolta e fai clic su **[!UICONTROL Dettagli]**.
1. Visualizza i metadati della raccolta utilizzando la scheda **[!UICONTROL Base]**.
1. Se necessario, modifica i campi di metadati. Puoi modificare i campi [!UICONTROL Titolo], [!UICONTROL Descrizione] e [!UICONTROL Autore].

![Metadati di una raccolta](assets/collection-metadata.png)

## Condividere collegamenti per le raccolte {#share-collection-links}

[!DNL Assets Essentials] consente di generare un collegamento e di condividere raccolte e risorse al loro interno con le parti interessate che non hanno accesso all’applicazione [!DNL Assets Essentials]. Puoi definire una data di scadenza del collegamento e condividerlo con altri utilizzando il metodo di comunicazione preferito, ad esempio e-mail o servizi di messaggistica. I destinatari del collegamento possono visualizzare in anteprima le risorse e scaricarle.

![Condividere il collegamento per le risorse](assets/share-link-collections.png)

Per ulteriori informazioni su come condividere i collegamenti di raccolte con soggetti esterni, consulta [Condividere collegamenti alle risorse](share-links-for-assets.md).

## Scaricare una raccolta {#download-collection}

Per scaricare una raccolta:

1. Fai clic su **[!UICONTROL Raccolte]** nella barra a sinistra.

1. Seleziona la raccolta da scaricare e fai clic su **[!UICONTROL Scarica]**.

1. Nella finestra di dialogo [!UICONTROL Scarica risorsa] fai clic su **[!UICONTROL OK]**.

Gli elementi della raccolta selezionati vengono scaricati come file .ZIP sul computer locale.

## Eliminare una raccolta {#delete-collection}

Per eliminare una raccolta:

1. Fai clic su **[!UICONTROL Raccolte]** nella barra a sinistra.

1. Seleziona la raccolta da eliminare.

1. Fai clic su **[!UICONTROL Elimina]**.

## Passaggi successivi {#next-steps}

* Fornisci feedback sui prodotti utilizzando l’opzione [!UICONTROL Feedback] disponibile nell’interfaccia utente di Assets Essentials

* Fornisci feedback alla documentazione utilizzando [!UICONTROL Modifica questa pagina] ![modifica la pagina](assets/do-not-localize/edit-page.png) o [!UICONTROL Segnala un problema] ![crea un problema GitHub](assets/do-not-localize/github-issue.png) disponibile sulla barra laterale destra

* Contatta il [Servizio clienti](https://experienceleague.adobe.com/?support-solution=General&amp;lang=it#support)
