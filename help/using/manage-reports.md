---
title: Gestire i rapporti in Assets Essentials
description: Accedi ai dati nella sezione dei rapporti di Assets Essentials per valutare l’utilizzo di prodotti e funzionalità e ottenere informazioni approfondite sulle metriche di successo chiave.
exl-id: c7155459-05d9-4a95-a91f-a1fa6ae9d9a4
source-git-commit: 810bb62cd5eb664e36a6ea267050dd025828e900
workflow-type: tm+mt
source-wordcount: '1226'
ht-degree: 97%

---

# Gestire i rapporti {#manage-reports}

La funzionalità di reporting sulle risorse offre agli amministratori visibilità sulle attività dell’ambiente Adobe Experience Manager Assets Essentials. Questi dati forniscono informazioni utili su come gli utenti interagiscono con i contenuti e il prodotto. Tutti gli utenti possono accedere alla dashboard Insight e quelli assegnati al profilo di prodotto Amministratori possono creare rapporti definiti dall’utente.

## Accedere ai rapporti {#access-reports}

Tutti gli utenti assegnati al [profilo di prodotto per amministratori di Assets Essentials](deploy-administer.md) possono accedere alla dashboard Insight e creare rapporti definiti dagli utenti in Assets Essentials.

Per accedere ai rapporti, passa a **[!UICONTROL Rapporti]** in **[!UICONTROL Impostazioni]**.

![Rapporti](assets/reports.png)
<!--
In the **[!UICONTROL Reports]** screen, various components are shown in the tabular format which includes the following:

* **Title**: Title of the report
* **Type**: Determines whether the report is uploaded or downloaded to the repository
* **Description**: Provide details of the report that was given during uploading/downloading the report
* **Status**: Determines whether the report is completed, under progress, or deleted.
* **Author**: Provides email of the author who has uploaded/downloaded the report.
* **Created**: Gives information of the date when the report was generated.
-->

## Creare un rapporto {#create-report}

L’ambiente AEM Assets Essentials offre funzionalità di reporting complete tramite la dashboard Rapporti. Questa funzionalità consente agli utenti di generare e scaricare rapporti CSV che descrivono nel dettaglio i caricamenti e i download delle risorse entro intervalli di tempo specifici, che vanno da una tantum a intervalli giornalieri, settimanali, mensili o annuali.

**Per creare un rapporto:**

1. Passa a **Rapporti** e fai clic su **Crea rapporto** (in alto a destra). La finestra di dialogo **crea rapporto** mostra i campi seguenti:
   ![create-report](/help/using/assets/executed-reports1.svg)

   **Nella scheda Configurazione:**

   1. **Tipo di report:** Seleziona un tipo di report tra [!UICONTROL Carica] o [!UICONTROL Scarica].
   1. **Titolo:** aggiungi un titolo al rapporto.
   1. **Descrizione**: specifica una descrizione facoltativa per il rapporto.
   1. **Seleziona il percorso della cartella:** seleziona un percorso della cartella per generare il rapporto delle risorse caricate e scaricate all’interno di quella cartella specifica. Ad esempio, se hai bisogno del rapporto sulle risorse caricate in una cartella, specifica il percorso di tale cartella.
   1. **Seleziona intervallo date:** seleziona l’intervallo di date per visualizzare l’attività di caricamento o download nella cartella.
   <br>

   >[!NOTE]
   >
   > Assets Essentials converte tutti i fusi orari locali nel Tempo coordinato universale (UTC).

   **Nella scheda Colonne:** seleziona i nomi delle colonne da visualizzare nel rapporto. Nella tabella seguente viene illustrato l’utilizzo di tutte le colonne:

   <table>
    <tbody>
     <tr>
      <th><strong>Nome colonna</strong></th>
      <th><strong>Descrizione</strong></th>
      <th><strong>Tipo di rapporto</strong></th>
     </tr>
     <tr>
      <td>Titolo</td>
      <td>Titolo della risorsa.</td>
      <td>Caricamento e download</td>
     </tr>
     <tr>
      <td>Percorso</td>
      <td>Percorso della cartella in cui la risorsa è disponibile in Assets Essentials.</td>
      <td>Caricamento e download</td>
     </tr>
     <tr>
      <td>Tipo MIME</td>
      <td>Tipo MIME della risorsa.</td>
      <td>Caricamento e download</td>
     </tr>
     <tr>
      <td>Dimensione</td>
      <td>Dimensione della risorsa in byte.</td>
      <td>Caricamento e download</td>
     </tr>
     <tr>
      <td>Scaricato da</td>
      <td>ID e-mail dell’utente che ha scaricato la risorsa.</td>
      <td>Download</td>
     </tr>
     <tr>
      <td>Data di download</td>
      <td>Data in cui è stata eseguita l’azione di download della risorsa.</td>
      <td>Download</td>
     </tr>
     <tr>
      <td>Autore</td>
      <td>Autore della risorsa.</td>
      <td>Caricamento e download</td>
     </tr>
     <tr>
      <td>Data creazione</td>
      <td>La data in cui la risorsa è stata caricata in Assets Essentials.</td>
      <td>Caricamento e download</td>
     </tr>
     <tr>
      <td>Data di modifica</td>
      <td>Data dell’ultima modifica apportata alla risorsa.</td>
      <td>Caricamento e download</td>
     </tr>
     <tr>
      <td>Scaduta</td>
      <td>Stato di scadenza della risorsa.</td>
      <td>Caricamento e download</td>
     </tr>
     <tr>
      <td>Scaricato da nome utente</td>
      <td>Nome dell’utente che ha scaricato la risorsa.</td>
      <td>Download</td>
     </tr>              
    </tbody>
   </table>



## Visualizzare e scaricare il rapporto esistente {#View-and-download-existing-report}

I rapporti esistenti vengono visualizzati nella scheda **Rapporti eseguiti**. Fai clic su **Rapporti** e seleziona **Rapporti eseguiti** per visualizzare tutti i rapporti creati con lo stato **Completati**, indicando che sono pronti per il download. Per scaricare il rapporto in formato CSV o eliminarlo, seleziona la riga del rapporto e seleziona **Scarica CSV** o **Elimina**.
![visualizzare e scaricare i rapporti esistenti](/help/using/assets/view-download-existing-report.png)

## Pianificare un rapporto {#schedule-report}

Nell’interfaccia utente di AEM Essentials, **Pianifica rapporto** imposta una generazione automatica di rapporti in intervalli futuri specifici, ad esempio giornalieri, settimanali, mensili o annuali. Questa funzione consente di semplificare le esigenze di reporting ricorrenti e assicura aggiornamenti tempestivi dei dati. Mentre **Crea rapporto** genera rapporti per le date passate. I rapporti completati sono elencati in **Rapporti eseguiti** e i rapporti futuri si trovano in **Rapporti pianificati**.

Per pianificare un rapporto, effettua le seguenti operazioni:

1. Fai clic su Rapporti nel riquadro a sinistra e quindi su Crea rapporto (in alto a destra).
1. Nella finestra di dialogo del rapporto vengono visualizzate le informazioni riportate di seguito:
   1. **Tipo di rapporto:** seleziona tra il tipo di caricamento e quello di download.
   1. **Titolo:** aggiungi un titolo al rapporto.
   1. **Descrizione**: aggiungi una descrizione facoltativa al rapporto.
   1. **Seleziona il percorso della cartella:** seleziona il percorso di una cartella per generare un rapporto per le risorse che verranno caricate o scaricate in futuro da tale cartella specifica.
   1. Attiva/disattiva **Pianifica rapporto:** attiva/disattiva la pianificazione del rapporto per un momento successivo o per la sua occorrenza ripetuta.
      ![pianifica rapporto](/help/using/assets/schedule-reports1.svg)

   1. **Scegli la frequenza:** specifica l’intervallo di generazione del rapporto (ad esempio giornaliero, settimanale, mensile, annuale o una volta) e imposta la data e l’ora di esecuzione del rapporto insieme alla data di fine per la ricorrenza. Per un rapporto una tantum, seleziona l’intervallo di date per il rapporto sul tipo di attività selezionato nell’ambiente AEM. Ad esempio, se hai bisogno di un rapporto sulle risorse scaricate dal 10 al 29 (date future) di un mese specifico, seleziona queste date nel campo **Seleziona intervallo date**.

   >[!NOTE]
   >
   > Assets Essentials converte tutti i fusi orari locali nel Tempo coordinato universale (UTC).

## Visualizzare rapporti pianificati {#view-scheduled-reports}

I rapporti pianificati vengono visualizzati nella scheda **Rapporti pianificati** in modo ben organizzato. Tutti i rapporti completati per ogni rapporto pianificato vengono memorizzati in una singola cartella di rapporto. Fai clic su ![espandi comprimi](/help/using/assets/expand-icon1.svg) per visualizzare i rapporti completati. Ad esempio, se hai pianificato un rapporto giornaliero, tutti i rapporti completati sono raggruppati in un’unica cartella. Questa organizzazione semplifica sia la navigazione che la reperibilità dei rapporti. Per visualizzare i rapporti pianificati, fai clic su **Rapporti** e quindi su **Rapporti pianificati**. Vengono visualizzati tutti i rapporti pianificati con il relativo stato in corso o completato. I rapporti completati sono pronti per il download.
![rapporti pianificati](/help/using/assets/scheduled-reports-tab.png)

## Modificare e annullare i rapporti pianificati {#edit-cancel-scheduled-reports}

1. Passa alla scheda **Rapporti pianificati**.
1. Seleziona la riga del rapporto.
1. Fai clic su **Modifica**.
1. Fai clic su **Annulla pianificazione** e quindi fai clic su **Conferma** per annullare il rapporto pianificato. Per i rapporti annullati, la fase di esecuzione successiva diventa vuota e lo stato viene visualizzato come annullato.
   ![modificare e annullare rapporti pianificati](/help/using/assets/cancel-edit-scheduled-reports.png)

### Riprendi pianificazione {#resume-schedule}

Per riprendere la pianificazione annullata, seleziona la riga del rapporto e fai clic su **Riprendi pianificazione**. Quando viene ripresa, le voci di runtime successive vengono nuovamente visualizzate e lo stato è su In corso.
![riprendi pianificazione](/help/using/assets/resume-schedule.png)

>[!NOTE]
>
> Se si riprende un rapporto annullato prima della data di fine pianificata, vengono generati automaticamente i rapporti dalla data di annullamento alla data di ripresa.

## Visualizzare gli insight {#view-live-statistics}

>[!CONTEXTUALHELP]
>id="assets_reports"
>title="Rapporti"
>abstract="La dashboard Insights consente di visualizzare le metriche degli eventi in tempo reale per l’ambiente Experience Manager Assets negli ultimi 30 giorni o 12 mesi. L’elenco degli eventi include il numero di download, caricamenti, ricerche principali e così via."

Assets Essentials consente di visualizzare in tempo reale i dati del tuo ambiente Assets Essentials, con la dashboard Insight. Puoi visualizzare le metriche degli eventi in tempo reale negli ultimi 30 giorni o negli ultimi 12 mesi.

<!--![Toolbar options when you select an asset](assets/assets-essentials-live-statistics.png)-->

Fai clic su **[!UICONTROL Insight]** nel riquadro di navigazione a sinistra per visualizzare i seguenti grafici generati automaticamente:

* **Download**: numero di risorse scaricate dall’ambiente Assets Essentials negli ultimi 30 giorni o 12 mesi rappresentato da un grafico a linee.
  ![download](/help/using/assets/insights-downloads2341.svg)

* **Caricamenti**: numero di risorse caricate nell’ambiente Assets Essentials negli ultimi 30 giorni o 12 mesi rappresentato da un grafico a linee.
  ![caricamenti](/help/using/assets/insights-uplods2.svg)

<!--* **Asset Count by Size**: The division of count of assets based on their range of various sizes from 0 MB to 100 GB.-->

* **Utilizzo archiviazione**: utilizzo dell’archiviazione, in byte, per l’ambiente di Assets Essentials rappresentato da un grafico a barre.
  ![utilizzo archiviazione](/help/using/assets/insights-storage-usage1.svg)
  <!--* **Delivery**: The graph depicts the count of assets as the delivery dates.-->

<!--* **Asset Count by Asset Type**: Represents count of various MIME types of the available assets. For example, application/zip, image/png, video/mp4, application/postscripte.-->

* **Ricerche principali**: visualizza i termini più cercati e il numero di volte in cui tali termini sono stati cercati nell’ambiente Assets Essentials negli ultimi 30 giorni o 12 mesi rappresentato in formato tabulare.
  ![utilizzo archiviazione](/help/using/assets/insights-top-search.svg)

  <!--
   ![Insights](assets/insights1.png)
   ![Insights](assets/insights2.png)
   -->

* **Conteggio risorse per dimensione:** suddivide il numero totale delle risorse nell’ambiente Assets Essentials in intervalli di dimensioni diversi, evidenziando il conteggio e la percentuale delle risorse in ciascun intervallo di dimensioni, rappresentate utilizzando un grafico ad anello.
  ![insights-assets-count-by-size](/help/using/assets/insights-assets-count-by-size.svg)

* **Conteggio risorse per tipo di risorsa:** suddivide il numero totale delle risorse nell’ambiente Assets Essentials, evidenziando il conteggio e la percentuale delle risorse in base ai relativi tipi di file, rappresentati da un grafico ad anello.
  ![insights-assets-count-by-size](/help/using/assets/insights-assest-count-by-asset-type1.svg)

