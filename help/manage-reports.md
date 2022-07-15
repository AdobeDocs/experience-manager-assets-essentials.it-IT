---
title: Gestione dei rapporti in Assets Essentials
description: Utilizza le informazioni contenute nei rapporti di Assets Essentials per derivare le metriche di successo chiave per misurare l’adozione di Assets all’interno della tua azienda e da parte dei clienti.
source-git-commit: 511b7904eca972e76f55e574c7c364dd88fb1721
workflow-type: tm+mt
source-wordcount: '515'
ht-degree: 4%

---

# Gestire i rapporti {#manage-reports}

Il reporting delle risorse consente agli amministratori di valutare l’utilità dell’implementazione Adobe Experience Manager Assets Essentials. I rapporti forniscono informazioni utili sul modo in cui gli utenti interagiscono con le risorse disponibili nell’implementazione.

Utilizza le informazioni contenute nei rapporti per derivare le metriche di successo chiave per misurare l’adozione di Assets all’interno della tua azienda e da parte dei clienti.

## Accedere ai rapporti {#access-reports}

Tutti gli utenti assegnati al [Profilo di prodotto Amministratori Assets Essentials](deploy-administer.md) può accedere a statistiche e rapporti live in Assets Essentials.

## Visualizzare le statistiche dal vivo {#view-live-statistics}

Assets Essentials consente di visualizzare i dati di download generati automaticamente per la distribuzione Assets Essentials. Puoi scegliere di visualizzare il numero di download delle risorse effettuati negli ultimi 30 giorni o negli ultimi 12 mesi.

![Opzioni nella barra degli strumenti quando si seleziona una risorsa](assets/asset-reports-live-statistics.png)

Passa a **[!UICONTROL Impostazioni]** > **[!UICONTROL Statistiche live]** per visualizzare i dati di download generati automaticamente.

## Creare un rapporto {#create-report}

Per creare un rapporto:

1. Passa a **[!UICONTROL Impostazioni]** > **[!UICONTROL Rapporti]** e fai clic su **[!UICONTROL Creare un rapporto]**.

1. In [!UICONTROL Configurazione] Specifica un titolo e una descrizione facoltativa per il rapporto.

1. Seleziona il percorso della cartella, che comprende le risorse su cui eseguire il rapporto, utilizzando **[!UICONTROL Seleziona percorso cartella]** campo .

1. Selezionare l&#39;intervallo di date per il report.

1. In [!UICONTROL Colonne] selezionare i nomi delle colonne da visualizzare nel rapporto.

1. Fai clic su **[!UICONTROL Crea]**.

   ![Download del rapporto](assets/download-reports-config.png)

Nella tabella seguente viene illustrato l’utilizzo di tutte le colonne che è possibile aggiungere al rapporto:

<table>
    <tbody>
     <tr>
      <th><strong>Nome colonna</strong></th>
      <th><strong>Descrizione</strong></th>
     </tr>
     <tr>
      <td>Titolo</td>
      <td>Titolo della risorsa.</td>
     </tr>
     <tr>
      <td>Percorso</td>
      <td>Percorso della cartella in cui la risorsa è disponibile in Assets Essentials.</td>
     </tr>
     <tr>
      <td>Tipo</td>
      <td>Il tipo MIME della risorsa.</td>
     </tr>
     <tr>
      <td>Dimensione</td>
      <td>Dimensione della risorsa.</td>
     </tr>
     <tr>
      <td>Scaricato da</td>
      <td>L’ID e-mail dell’utente che ha scaricato la risorsa.</td>
     </tr>
     <tr>
      <td>Data di download</td>
      <td>La data in cui viene eseguita l’azione di download delle risorse.</td>
     </tr>
     <tr>
      <td>Autore</td>
      <td>L’autore della risorsa.</td>
     </tr>
     <tr>
      <td>Data creazione</td>
      <td>La data in cui la risorsa viene caricata in Assets Essentials.</td>
     </tr>
     <tr>
      <td>Data di modifica</td>
      <td>Data dell’ultima modifica apportata alla risorsa.</td>
     </tr>
     <tr>
      <td>Scaduti</td>
      <td>Lo stato di scadenza della risorsa.</td>
     </tr>
     <tr>
      <td>Scaricato per nome utente</td>
      <td>Nome dell’utente che ha scaricato la risorsa.</td>
     </tr>           
    </tbody>
   </table>

## Visualizza l&#39;elenco dei report {#view-report-list}

Dopo [creazione del rapporto](#create-report), puoi visualizzare l’elenco dei rapporti e selezionare se scaricarli in formato CSV o eliminarli.

Per visualizzare l’elenco dei rapporti, passa a **[!UICONTROL Impostazioni]** > **[!UICONTROL Rapporti]**.

Per ogni rapporto puoi visualizzare il titolo, il tipo di rapporto, la descrizione specificata durante la creazione, lo stato del rapporto, l’ID e-mail dell’autore che ha creato il rapporto e la data di creazione del rapporto.

`Completed ` lo stato del rapporto indica che il rapporto è pronto per il download.

![Elenco dei rapporti](assets/list-of-reports.png)


## Scaricare un rapporto CSV {#download-csv-report}

Per scaricare un rapporto in formato CSV:

1. Passa a **[!UICONTROL Impostazioni]** > **[!UICONTROL Rapporti]**.

1. Seleziona un rapporto e fai clic su **[!UICONTROL Scarica CSV]**.

Il rapporto selezionato viene scaricato in formato CSV. Le colonne visualizzate nel rapporto CSV dipendono dalle colonne selezionate mentre [creazione del rapporto](#create-report).

## Eliminare un rapporto {#delete-report}

Per eliminare un rapporto:

1. Passa a **[!UICONTROL Impostazioni]** > **[!UICONTROL Rapporti]**.

1. Seleziona un rapporto e fai clic su **[!UICONTROL Elimina]**.
