---
title: Note sulla versione
description: Note sulla versione e problemi noti di [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: f273e1e3c8a290e0beee0423da00c63013062c43
workflow-type: tm+mt
source-wordcount: '1117'
ht-degree: 80%

---

# Note sulla versione di [!DNL Assets Essentials] {#release-notes}

L&#39;attuale versione di [!DNL Assets Essentials] rilasciato il 14 luglio 2022.

Questa versione offre le seguenti funzionalità:

**Raccolte avanzate**

Salva i risultati della ricerca come Raccolta avanzata per aggiornare dinamicamente il contenuto della raccolta. Se sono presenti risorse aggiunte all’archivio Assets Essentials che soddisfano i criteri di ricerca definiti durante la [creazione di Smart Collection](manage-collections.md#create-smart-collection), il contenuto della Raccolta avanzata viene aggiornato automaticamente.

**Notifiche**

Le notifiche Assets Essentials consentono di: [monitorare le operazioni eseguite sulle risorse o cartelle disponibili nell’archivio](manage-notifications.md). Devi selezionare e abbonarti al contenuto per il quale ti vengono inviate le notifiche. Puoi anche configurare le categorie per le quali vengono inviate le notifiche.

**Generazione rapporti**

Il reporting delle risorse consente agli amministratori di valutare l’attività dell’utente in Adobe Experience Manager Assets Essentials. Il dashboard di rapporti e statistiche live fornisce informazioni utili sul modo in cui gli utenti interagiscono con le risorse disponibili nella distribuzione. [Utilizzare le informazioni nei rapporti](manage-reports.md) per derivare le metriche di successo chiave per misurare l’adozione di Assets all’interno dell’azienda e da parte dei clienti.

Visualizza i rapporti di download delle risorse e il modulo del dashboard delle statistiche live per vedere quali risorse vengono scaricate e la frequenza dei download.

**Miglioramenti in base al feedback ricevuto dai clienti**

Miglioramenti e correzioni di bug in base al feedback ricevuto dai clienti.


## Problemi noti {#known-issues}

L’elenco dei problemi noti di [!DNL Assets Essentials] viene regolarmente rivisto e aggiornato:

<!--

* Assets Essentials does not support creating Private collections.

-->


* Assets Essentials non supporta la modifica di una raccolta avanzata.

* Le raccolte private sono disponibili per il creatore e gli utenti con privilegi di amministratore. In qualità di amministratore, non puoi delegare le autorizzazioni per accedere alla raccolta ad altri utenti.

In caso di problemi o richieste di miglioramenti, ti invitiamo a [fornire un feedback](#provide-feedback) al team.

## Versioni precedenti {#past-release}

### 2022.5.0 {#may-2022}

L’attuale versione di [!DNL Assets Essentials] è stata rilasciata il 16 giugno 2022.

Questa versione offre le seguenti funzionalità:

**Miglioramenti allo stato delle risorse**

* Assets Essentials ora consente di [impostare una data di scadenza per una risorsa](manage-organize.md#set-asset-status). Inoltre, è possibile [filtrare le risorse](search.md#refine-search-results) in base allo stato `Expired` delle risorse e a un intervallo di date di scadenza.

* Ora puoi visualizzare l’indicatore di stato per tutte le risorse disponibili nel Cestino. Di conseguenza, potrai decidere se ripristinare una risorsa in base al suo stato.

**Miglioramenti ai filtri di ricerca**

* Assets Essentials ora consente di [filtrare le risorse](search.md#refine-search-results) in base allo stato `No Status` delle risorse.

<!--

* Assets Essentials now supports [using a wildcard operator (*) while using custom filters](search.md#custom-filters) to enable Assets Essentials to display assets in the results that partially match the search criteria.

-->

**Miglioramenti alle raccolte**

<!--

* Assets Essentials now enables you to [create Private collections](manage-collections.md#create-collection).

-->

* Assets Essentials ora supporta il [download di una raccolta](manage-collections.md).

* È ora possibile modificare il campo metadati Descrizione di una raccolta.

**Miglioramenti alla documentazione**

* È disponibile una nuova versione della [documentazione Panoramica di Assets Essentials](introduction.md).

**Miglioramenti in base al feedback ricevuto dai clienti**

* Miglioramenti e correzioni di bug in base al feedback ricevuto dai clienti.

### 2022.4.0 {#april-2022}

L’attuale versione di [!DNL Assets Essentials] è stata rilasciata il 12 maggio 2022. Questa versione offre le seguenti funzionalità:

* [!DNL Assets Essentials] ora supporta la [creazione di raccolte](manage-collections.md). Una raccolta è un insieme di risorse in Experience Manager Assets Essentials. Puoi utilizzare le raccolte per condividere le risorse tra i vari utenti. A differenza delle cartelle, una raccolta può includere risorse da posizioni diverse.

* Assets Essentials ora consente anche di [aggiungere filtri personalizzati](search.md#custom-filters) all’interfaccia utente. Puoi applicare i filtri personalizzati in aggiunta ai filtri standard, per perfezionare i risultati della ricerca.

* Assets Essentials ora consente di [impostare lo stato](manage-organize.md#set-asset-status) delle risorse disponibili nell’archivio. Imposta lo stato di una risorsa per gestire meglio il consumo a valle di risorse digitali.

* Miglioramenti e correzioni di bug in base al feedback ricevuto dai clienti.

#### Modalità di navigazione in incognito in Chrome {#incognito-mode}

Con questa versione stiamo ottimizzando le prestazioni della distribuzione dell’interfaccia utente e specifiche funzionalità di Assets Essentials (aggiunta di commenti alle risorse e modifica delle immagini) che dipendono dall’archiviazione locale del browser e dall’attivazione di cookie di terze parti. Per impostazione predefinita, la modalità di navigazione in incognito nel browser web Chrome blocca i cookie di terze, e gli utenti hanno alcune opzioni per continuare ad accedere a tutte le funzionalità:

* Utilizzare i profili Chrome invece della modalità di navigazione in incognito, se l&#39;utente ha bisogno di sessioni browser separate

* Disattivare `Block third-party cookies` nella schermata della modalità in incognito in Chrome

### 2022.2.0 {#march-2022}

[!DNL Assets Essentials] è stato rilasciato il 9 marzo 2022, con i seguenti aggiornamenti:

* [!DNL Assets Essentials] ora consente di [generare un collegamento e condividere le risorse con le parti interessate](share-links-for-assets.md), che non hanno accesso all’applicazione [!DNL Assets Essentials]. Puoi definire una data di scadenza del collegamento e condividerlo con altri utilizzando il metodo di comunicazione preferito, ad esempio e-mail o servizi di messaggistica. I destinatari del collegamento possono visualizzare in anteprima le risorse e scaricarle.

* [!DNL Assets Essentials] ora comprende [un profilo di prodotto amministratore](deploy-administer.md#add-users-to-essentials) su Admin Console, oltre ai profili di prodotto standard e consumer esistenti. Un amministratore può ora assegnare altri utenti al profilo di prodotto dell’amministratore.

* Assets Essentials consente ora agli amministratori di [gestire i livelli di accesso per le cartelle disponibili nell’archivio](manage-permissions.md). In qualità di amministratore, puoi creare gruppi di utenti e assegnare autorizzazioni a tali gruppi per gestire i livelli di accesso. Puoi anche delegare i privilegi di gestione delle autorizzazioni ai gruppi di utenti a livello di cartella.

* Miglioramenti e correzioni di bug in base al feedback ricevuto dai clienti.

Inoltre, l’estensione [!DNL Adobe Asset Link] per Creative Cloud (Photoshop, Illustrator e InDesign) ha rilasciato una [nuova versione 3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html), con miglioramenti delle prestazioni del tempo di avvio del pannello e nella velocità di download.


### Versione 2022.1.0 {#january-2022}

[!DNL Assets Essentials] è stato rilasciato il 3 febbraio 2022, con i seguenti aggiornamenti:

* Miglioramenti delle prestazioni per l’operazione [!UICONTROL Crea cartella]. <!-- CQ-4338818 -->

### Versione 2021.11.0 {#november-2021}

[!DNL Assets Essentials] è stato rilasciato il 16 dicembre 2021, con i seguenti aggiornamenti:

* Al termine del processo di provisioning, Adobe implementa automaticamente Assets Essentials. Gli amministratori non devono eseguire alcun passaggio aggiuntivo per implementare Assets Essentials tramite l’interfaccia utente di [!DNL Cloud Manager]. L’implementazione automatica sarà disponibile per gli ambienti per i quali è stato eseguito il provisioning dopo il 6 gennaio 2022.
* In Adobe Exchange sono disponibili nuove versioni dei plug-in Creative Cloud che funzionano con Assets Essentials: [Adobe Asset Link per Adobe XD v. 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) e [Adobe Asset Link for Photoshop/InDesign/Illustrator v. 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* Vari bug e miglioramenti dei prodotti, tra cui problemi noti precedenti (dopo il caricamento, le cartelle ora vengono visualizzate correttamente nella struttura di spostamento a sinistra<!-- CQ-4337638 -->; il caricamento mediante trascinamento della selezione consente di selezionare la cartella corrente o una sottocartella al momento del rilascio per il caricamento<!-- CQ-4327753 -->).

### Versione 2021.8.0 {#august2021}

[!DNL Assets Essentials] 2021.8.0 è stato rilasciato il 30 agosto 2021 con i seguenti aggiornamenti:

* Integrazioni con [!DNL Adobe Workfront] che consentono agli utenti di [!DNL Workfront] di gestire le proprie risorse digitali nel contesto di gestione del proprio lavoro. Per ulteriori informazioni, consulta [Integrazioni con altre soluzioni Adobe](/help/integration.md).

### Versione 2021.7.0 {#july2021}

[!DNL Assets Essentials] 2021.7.0 è stato rilasciato il 29 luglio 2021 con i seguenti aggiornamenti:

* Puoi creare e gestire moduli di metadati personalizzati da utilizzare per consentire agli utenti di visualizzare le proprietà dei metadati nella schermata dei dettagli delle risorse dall’opzione [!UICONTROL Moduli metadati] in [!DNL Settings]. Consulta [Moduli di metadati](metadata.md#metadata-forms).
* Varie correzioni di bug e miglioramenti al prodotto, incluse migliori prestazioni durante il caricamento di cartelle nidificate contenenti numerose sottocartelle.

### Versione 2021.6.0 {#june2021}

La prima versione di [!DNL Assets Essentials], rilasciata il 21 giugno 2021, offre funzionalità leggere per la gestione delle risorse. Supporta le seguenti funzioni principali e operazioni CRUD (Create, Read, Update, Delete: crea, leggi, aggiorna, elimina):

* Caricare e aggiungere risorse, incluse cartelle nidificate. Visualizzare l’anteprima di risorse e versioni.
* Ricerca full-text, filtri di ricerca mirata, e ricerche salvate per individuare rapidamente le risorse.
* Operazioni di base per la gestione delle risorse, come aggiornamento, eliminazione, download e gestione dei metadati.
* [!DNL Assets Essentials] è disponibile per gli utenti di [!DNL Adobe Journey Optimizer] per la gestione delle risorse durante la creazione dei messaggi. Per ulteriori informazioni, consulta [Integrazioni con altre soluzioni Adobe](/help/integration.md).
