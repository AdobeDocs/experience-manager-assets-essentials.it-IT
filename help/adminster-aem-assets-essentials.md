---
title: Amministrare Experience Manager Assets Essentials
description: Configura l’accesso all’applicazione Assets Essentials utilizzando l’Admin Console, quindi gestisci le attività che possono essere eseguite dopo aver effettuato l’accesso all’applicazione Assets Essentials.
source-git-commit: 1f01dd340f79d1c2d9748232c2b1a589ae7f8545
workflow-type: tm+mt
source-wordcount: '1399'
ht-degree: 53%

---


# Amministrare Experience Manager Assets Essentials {#administer-assets-essentials}

![Preferenza per scegliere il tema scuro o chiaro](assets/cce-assets.png)

## Obiettivo

* **Pubblico**: Amministratori Assets Essentials

* **Obiettivo**: Configura l’accesso all’applicazione Assets Essentials utilizzando l’Admin Console, quindi gestisci le attività che possono essere eseguite dopo aver effettuato l’accesso all’applicazione Assets Essentials.

## Panoramica {#overview}


Il provisioning di [!DNL Adobe Experience Manager Assets Essentials] viene eseguito da Adobe per i propri clienti. Come parte del provisioning, [!DNL Assets Essentials] viene aggiunto a un’organizzazione del cliente in [!DNL Adobe Admin Console]. Gli amministratori utilizzano [!DNL Admin Console] per gestire le adesioni utente a [!DNL Assets Essentials] e assegnare agli amministratori dell&#39;applicazione le autorizzazioni e i moduli di metadati in [!DNL Assets Essentials].

Il diagramma di flusso di dati seguente illustra la sequenza di attività che un amministratore deve eseguire per configurare e gestire Assets Essentials:

![Flusso di amministrazione di Assets Essentials](assets/permissions-management-cce-next.svg)

## Accedere all’Admin Console {#access-admin-console}

Dopo il provisioning della soluzione Assets Essentials, l’amministratore riceve un messaggio e-mail da Adobe. L’e-mail contiene un messaggio di benvenuto e un collegamento per iniziare. Inoltre, Adobe avvia il processo di implementazione automatica di Assets Essentials. Il completamento del processo di implementazione richiede un’ora.

Utilizzando il link incluso nel messaggio e-mail, accedi ad [Admin Console](https://adminconsole.adobe.com). Se disponi dell&#39;accesso dell&#39;amministratore a più account organizzazione, seleziona l&#39;organizzazione appropriata o passa ad essa utilizzando la [selettore organizzazione](https://helpx.adobe.com/it/enterprise/using/admin-console.html). Al termine dell’implementazione automatica, la scheda prodotto relativa a [!DNL AEM Assets Essentials] è visibile in [!DNL Admin Console].

![Implementazione di Assets Essentials](assets/admin-console-cards.png)

## Gestione delle attività di Admin Console {#manage-admin-console-tasks}

Esegui le seguenti attività nell’Admin Console:

* [Aggiungere utenti ai profili di prodotto](#add-users-to-product-profiles)

* [Aggiungere gruppi di utenti](#add-user-groups)

* [Aggiungere utenti ai gruppi](#add-users-to-user-groups)

### Aggiungere utenti ai profili di prodotto {#add-users-to-product-profiles}

Aggiungi gli utenti ai profili di prodotto in modo che abbiano accesso all’applicazione Assets Essentials.

Per aggiungere utenti ai profili di prodotto:

1. Accesso [Admin Console](https://adminconsole.adobe.com) per la tua organizzazione, fai clic su **[!UICONTROL Prodotti]** nella barra superiore, fai clic su **[!UICONTROL Nozioni di base su AEM Assets]**, quindi fai clic sull’istanza per [!DNL Assets Essentials]. Il nome dell’istanza potrebbe essere diverso rispetto alla schermata sottostante.
   >[!NOTE]
   >
   >[!DNL Cloud Manager] L’istanza è per uso amministratore speciale solo come controllare lo stato del servizio e ottenere l’accesso ai registri del servizio e non può essere utilizzata per aggiungere utenti al prodotto. Per ulteriori informazioni, consulta [guida per l’amministratore](deploy-administer.md#view-service-status-and-access-logs-view-logs).

   ![Profilo amministratore di Admin Console](assets/assets-essentials-instance.png)

   [!DNL Assets Essentials] dispone di tre profili prodotto che rappresentano il punto di accesso per amministratori, utenti standard e consumer.

   ![Profilo amministratore di Admin Console](assets/admin-console-admin-profile.png)

1. Per aggiungere un utente al prodotto, fai clic su uno dei tre profili di prodotto Assets Essentials, seleziona **[!UICONTROL Aggiungi utente]**, fornisci i dettagli utente e fai clic su **[!UICONTROL Salva]**.

   ![Aggiungi profilo amministratore utenti](assets/add-users-admin-profile.png)

   Quando aggiungi un utente, quest’ultimo riceve un invito e-mail per poter iniziare a utilizzare la soluzione. È possibile disattivare gli inviti e-mail dalle impostazioni del profilo prodotto in [!DNL Admin Console].

1. Per rimuovere un utente da un gruppo, fai clic sul gruppo, seleziona un utente esistente, quindi seleziona **[!UICONTROL Rimuovi utente]**.

   >[!NOTE]
   >
   >Per eseguire attività amministrative nell’applicazione Assets Essentials, devi aggiungere un utente al profilo di prodotto Assets Essentials amministratore nell’Admin Console. Queste attività includono [Crea struttura cartelle](#create-folder-structure), [Gestione delle autorizzazioni per le cartelle](#manage-permissions-for-folders)e [Metadati di installazione Forms](#metadata-forms).

### Aggiungere gruppi di utenti {#add-user-groups}

Crea gruppi di utenti e quindi assegna gli utenti ai gruppi di utenti. Questi gruppi di utenti saranno disponibili nell&#39;applicazione Assets Essentials per impostare le autorizzazioni sulle cartelle.

Puoi aggiungere utenti ai gruppi di utenti (1) e [utenti ai profili di prodotto di Assets Essentials (2)](#add-admin-users). Tuttavia, non è possibile aggiungere gruppi di utenti direttamente ai profili di prodotto di Assets Essentials (3).

![Aggiungere utenti a gruppi e profili di prodotto](assets/user-groups-product-profiles.svg)

Per informazioni su come gestire i gruppi di utenti, consulta `Create user groups` e `Edit user groups` disponibili in [Gestione di gruppi di utenti](https://helpx.adobe.com/it/enterprise/using/user-groups.html).

>[!NOTE]
>
>Se Admin Console è configurata per sfruttare un sistema esterno per la gestione delle assegnazioni di utenti/gruppi, ad esempio i connettori di Azure o Google, lo strumento di sincronizzazione degli utenti o l’API REST di User Management, i gruppi e le assegnazioni utente vengono configurate automaticamente. Per ulteriori informazioni, consulta [Utenti Adobe Admin Console](https://helpx.adobe.com/it/enterprise/using/users.html).


### Aggiungere utenti ai gruppi {#add-users-to-user-groups}

Dopo aver creato i gruppi di utenti, puoi iniziare ad aggiungere gli utenti a tali gruppi.

Per informazioni su come gestire l’aggiunta di utenti ai gruppi di utenti, consulta `Add users to groups` disponibile in [Gestione di gruppi di utenti](https://helpx.adobe.com/it/enterprise/using/user-groups.html#add-users-to-groups).

## Gestione delle attività di amministrazione di Assets Essentials {#manage-assets-essentials-tasks}

Dopo aver eseguito le attività di Admin Console, è ora possibile eseguire le seguenti attività di amministrazione nell&#39;applicazione Assets Essentials:

* [Creare una struttura di cartelle](#create-folder-structure)

* [Gestione delle autorizzazioni per le cartelle](#manage-permissions-for-folders)

* [Metadati di installazione Forms](#metadata-forms)

>[!NOTE]
>
>Per poter gestire queste attività, in particolare gestendo le autorizzazioni, l&#39;utente deve disporre di diritti di amministrazione dell&#39;applicazione, che devono essere aggiunti al [Profilo di prodotto Assets Essentials amministratore](#add-users-to-product-profiles).


### Creare una struttura di cartelle {#create-folder-structure}

Per creare una struttura di cartelle nell’archivio Assets Essentials, puoi utilizzare i seguenti metodi:

* Fai clic sull’opzione **[!UICONTROL Crea cartella]** disponibile nella barra degli strumenti per creare una cartella vuota.

* Fai clic sull’opzione **[!UICONTROL Aggiungi risorse]** disponibile nella barra degli strumenti per [caricare una struttura di cartelle disponibile nel computer locale](add-delete.md).

Crea una struttura di cartelle che sia adatta agli obiettivi aziendali dell’organizzazione. Se carichi nell’archivio Assets Essentials una struttura di cartelle già esistente, sarà necessario sottoporla a una verifica. Per ulteriori informazioni, consulta [Best practice per una gestione efficace delle autorizzazioni](permission-management-best-practices.md).

Quando inizi a pianificare la creazione di una struttura di cartelle nell’archivio Assets Essentials, considera quanto segue:

* Governance futura: le cartelle gestite dagli amministratori e quelle di cui le [autorizzazioni sono delegate ad altri utenti come proprietari](manage-permissions.md##manage-permissions-folders).

* Scalabilità: la struttura di cartelle deve soddisfare le esigenze future della tua organizzazione e deve essere facilmente scalabile.

* Dimensioni: una cartella non deve contenere un numero eccessivo di risorse. Potrebbe diventare difficile da usare e da gestire.

* Intuitività: la struttura di cartelle deve essere facile da sfogliare e intuitiva per gli utenti finali. Gli utenti devono essere in grado di capire facilmente dove caricare una nuova risorsa nella struttura di cartelle.

Sono disponibili vari tipi di strutture di cartelle che puoi utilizzare nella tua organizzazione. Di seguito sono riportati alcuni esempi di tipiche strutture di cartelle:

![Strutture di cartelle tipiche](assets/folder-structure.svg)

### Gestione delle autorizzazioni per le cartelle {#manage-permissions-for-folders}

Assets Essentials consente agli amministratori di gestire i livelli di accesso per le cartelle disponibili nell’archivio. In qualità di amministratore, puoi creare gruppi di utenti e assegnare autorizzazioni a tali gruppi per gestire i livelli di accesso. Puoi anche delegare i privilegi di gestione delle autorizzazioni ai gruppi di utenti a livello di cartella.

>[!VIDEO](https://video.tv.adobe.com/v/341104)

Per ulteriori informazioni, consulta [Gestione delle autorizzazioni per le cartelle](manage-permissions.md).

### Metadati di installazione Forms {#metadata-forms}

Per impostazione predefinita, Assets Essentials fornisce molti campi di metadati standard. Spesso le organizzazioni hanno l’esigenza di aggiungere altri metadati, specifici per l’azienda. I moduli di metadati consentono alle aziende di aggiungere campi di metadati personalizzati alla pagina [!UICONTROL Dettagli] di una risorsa. I metadati specifici per l’azienda migliorano la governance e l’individuazione delle risorse. Puoi creare nuovi moduli o riutilizzare quelli esistenti.

Puoi configurare i moduli di metadati per diversi tipi di risorse (diversi tipi MIME). Utilizza un modulo con lo stesso nome del tipo MIME del file. Le funzioni di base confrontano automaticamente il tipo MIME delle risorse caricate con il nome del modulo e aggiornano i metadati delle risorse caricate in base ai campi del modulo.

Ad esempio, se un modulo metadati è basato sul nome `PDF` o `pdf` esiste, quindi i documenti PDF caricati contengono campi di metadati come definito nel modulo.

Assets Essentials utilizza la seguente sequenza per cercare i nomi dei moduli di metadati esistenti per applicare i campi di metadati alle risorse caricate di un particolare tipo:

sottotipo MIME > tipo MIME > `default` modulo > Modulo predefinito

Ad esempio, se è presente un modulo di metadati denominato `PDF` o `pdf`, i documenti PDF caricati contengono i campi di metadati definiti in tale modulo. Se un modulo di metadati è basato sul nome `PDF` o `pdf` non esiste, Assets Essentials corrisponde se è presente un modulo di metadati con il nome `application`. Se è presente un modulo metadati con il nome `application`, i documenti PDF caricati contengono campi di metadati come definiti nel modulo. Se Assets Essentials non trova ancora un modulo di metadati corrispondente, cerca il `default` modulo metadati per applicare ai documenti PDF caricati i campi metadati definiti nel modulo. Se nessuno di questi passaggi funziona, Assets Essentials applica i campi di metadati definiti nel modulo predefinito a tutti i documenti PDF caricati.

>[!IMPORTANT]
>
>Un nuovo modulo di metadati per un tipo di file specifico sostituisce interamente quello predefinito fornito da [!DNL Assets Essentials]. Se elimini o rinomini un modulo di metadati, i campi di metadati predefiniti diventano di nuovo disponibili per le nuove risorse.

>[!VIDEO](https://video.tv.adobe.com/v/341275)

Per ulteriori informazioni su Forms metadati, consulta [Metadati Forms in Assets Essentials](metadata.md#metadata-forms).

## Novità

Dopo aver configurato e gestito l’applicazione Assets Essentials, [integrare applicazioni Creative Cloud con l&#39;applicazione Experience Manager Assets Essentials](integrate-assets-essentials-creative-cloud.md).

