---
title: Amministrare e gestire gli utenti
description: Casi di utilizzo relativi all’amministrazione, tra cui implementazione e gestione degli utenti in [!DNL Assets Essentials].
role: Admin
exl-id: ef91126f-3aee-442b-b242-a6bf4034f3dc
source-git-commit: 59f6165fd7576736ff75369c2805c15ce3ae9af0
workflow-type: ht
source-wordcount: '1201'
ht-degree: 100%

---

# Amministrare [!DNL Assets Essentials] e aggiungere utenti {#administer}

Il provisioning di [!DNL Adobe Experience Manager Assets Essentials] viene eseguito da Adobe per i propri clienti. Come parte del provisioning, [!DNL Assets Essentials] viene aggiunto a un’organizzazione del cliente in [!DNL Adobe Admin Console]. Gli amministratori potranno utilizzare [!DNL Admin Console] per gestire i diritti utente alla soluzione [!DNL Assets Essentials] e assegnare gli amministratori dell’applicazione per configurare le autorizzazioni e i moduli di metadati in [!DNL Assets Essentials].

Per gestire un’esperienza basata su percorsi con Assets Essentials, fai clic su questo [collegamento](adminster-aem-assets-essentials.md).

## Implementazione automatica di Assets Essentials {#automatic-deployment-assets-essentials}

Dopo il provisioning della soluzione Assets Essentials, l’amministratore riceve un messaggio e-mail da Adobe. L’e-mail contiene un messaggio di benvenuto e un collegamento per iniziare. Inoltre, Adobe avvia il processo di implementazione automatica di Assets Essentials. Il completamento del processo di implementazione richiede un’ora.

Utilizzando il link incluso nel messaggio e-mail, accedi ad [Admin Console](https://adminconsole.adobe.com). Se puoi accedere come amministratore a più account, seleziona l’organizzazione appropriata o passa a tale organizzazione utilizzando il selettore nella barra superiore. Al termine dell’implementazione automatica, la scheda prodotto relativa a [!DNL AEM Assets Essentials] è visibile in [!DNL Admin Console].

![Implementazione di Assets Essentials](assets/assets-essentials-deployment.png)

Dopo aver completato l’implementazione della soluzione Assets Essentials, gli amministratori devono eseguire le seguenti attività:

* [Imposta i gruppi utenti, la struttura delle cartelle e assegna le autorizzazioni](manage-permissions.md) per la soluzione. Segui le [best practice](permission-management-best-practices.md) per garantire una configurazione delle autorizzazioni semplice ed efficace.
* [Gestire l’accesso degli utenti](#add-users-to-essentials) membri dell’organizzazione a [!DNL Assets Essentials].
* In alternativa, [visualizzare lo stato e i registri del servizio](#view-logs).

>[!NOTE]
>
>Se il provisioning di Assets Essentials è stato eseguito prima del 6 gennaio 2022, esegui i [passaggi di implementazione in Cloud Manager](#deploy-essentials) prima di gestire l’accesso degli utenti membri dell’organizzazione.


## Gestione degli utenti {#add-users-to-essentials}

Un amministratore gestisce gli utenti che possono accedere a [!DNL Assets Essentials]. Gli amministratori utilizzano [!DNL Adobe Admin Console] per aggiungere o rimuovere l’accesso utente. [!DNL Assets Essentials] dispone dei seguenti due tipi di accesso utente.

* **[!DNL Assets Essentials] - amministratori**: dispongono di accesso amministrativo all’applicazione. Oltre a tutte le capacità degli utenti finali, gli amministratori dell’applicazione di questo gruppo possono gestire le autorizzazioni per qualsiasi cartella e gruppo o utente nell’intero archivio dell’applicazione.
* **[!DNL Assets Essentials] - utenti**: hanno accesso all’interfaccia utente completa. Possono caricare, organizzare, assegnare tag e trovare risorse digitali.
* **[!DNL Assets Essentials] - utenti consumer**: hanno accesso all’esperienza di selezione delle risorse incorporata nell’editor di modelli e-mail di [!DNL Adobe Journey Optimizer]. Per ulteriori informazioni, consulta [Utilizzo [!DNL Assets Essentials] in [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html?lang=it).

In [!DNL Admin Console], questi tre tipi di accesso sono rappresentati da tre [!UICONTROL Profili prodotto]. Per aggiungere o rimuovere membri dell’organizzazione in uno dei due profili, segui questi passaggi:

1. Accedi a [!DNL Admin Console] per la tua organizzazione, fai clic su **[!UICONTROL Prodotti]** nella barra superiore, quindi su **[!UICONTROL AEM Assets Essentials]**, infine sull’ambiente [!DNL Assets Essentials]. [!DNL Assets Essentials] dispone di tre profili prodotto che rappresentano l’accesso per gli amministratori, gli utenti standard e consumer.

   ![Tre profili per tre tipi di utenti](assets/admin-console-admin-profile.png)
   <!-- Need to update screenshot to include 3 profiles -->

   *Figura: per aggiungere i tre tipi di utenti, sono disponibili tre profili.*

1. Per aggiungere un utente a un gruppo, fai clic sul gruppo e seleziona **[!UICONTROL Aggiungi utente]**, specifica i dettagli utente, quindi fai clic su **[!UICONTROL Salva]**. Quando aggiungi un utente, quest’ultimo riceve un invito e-mail per poter iniziare a utilizzare la soluzione. È possibile disattivare gli inviti e-mail dalle impostazioni del profilo prodotto in [!DNL Admin Console].

   ![Aggiungere un utente a [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

   *Figura: Aggiungere un utente a [!DNL Assets Essentials] da [!DNL Admin Console].*

1. Per rimuovere un utente da un gruppo, fai clic sul gruppo, seleziona un utente esistente, quindi seleziona **[!UICONTROL Rimuovi utente]**.

>[!TIP]
>
>In [!DNL Admin Console], puoi gestire gli utenti in blocco utilizzando file CSV. Per ulteriori informazioni, consulta la [[!DNL Admin Console] documentazione](https://helpx.adobe.com/it/enterprise/using/accounts.html).

## Visualizzare lo stato del servizio e i registri di accesso {#view-logs}

Dopo il provisioning, gli amministratori implementano [!DNL Assets Essentials] una sola volta. Dopo l’implementazione iniziale, Adobe esegue la manutenzione e gli aggiornamenti del servizio. Gli amministratori possono utilizzare l’interfaccia utente di [!DNL Cloud Manager] per controllare lo stato del servizio e scaricare i registri di accesso recenti.

1. Quando gli utenti segnalano dei problemi, controlla lo stato del servizio di [!DNL Assets Essentials] nell’interfaccia **[!UICONTROL Panoramica programma]**. Durante il normale funzionamento della soluzione, lo stato è `Running`. Se [!DNL Cloud Manager] mostra un altro stato, crea un ticket di supporto nella sezione supporto di [!DNL Admin Console].

   ![Stato di [!DNL Assets Essentials] in [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Figura: Lo stato normale di [!DNL Assets Essentials] in [!DNL Cloud Manager] è `Running`.*

1. Per scaricare i registri di accesso recenti, fai clic sull’![icona delle opzioni](assets/do-not-localize/options-ellipses-icon.png), seleziona **[!UICONTROL Scarica registri]** e segui le istruzioni visualizzate. Puoi controllare le richieste di accesso HTTPS utilizzando i registri.

   ![ Opzione per scaricare i registri di accesso](assets/cloudmanager-download-logs.png)

   *Figura: Opzione per scaricare i registri di accesso.*

## Implementare [!DNL Assets Essentials] {#deploy-essentials}

>[!NOTE]
>
>Esegui questi passaggi solo se è stato eseguito il provisioning di Assets Essentials prima del 6 gennaio 2022.

Dopo il provisioning, [!DNL Assets Essentials] diventa disponibile per l’organizzazione in [!DNL Admin Console]. Prima che la soluzione sia disponibile per l’utente, un amministratore dell’organizzazione deve implementarla. L’amministratore esegue un’implementazione una tantum mediante l’interfaccia utente di [!DNL Cloud Manager]. Dopo l’implementazione iniziale, Adobe esegue la manutenzione e gli aggiornamenti del servizio. Dopo il provisioning della soluzione, l’amministratore riceve un’e-mail da Adobe. L’e-mail contiene un messaggio di benvenuto e un collegamento per iniziare. Per eseguire l’implementazione, effettua le seguenti operazioni:

1. Dal collegamento nell’e-mail, accedi ad [Admin Console](https://adminconsole.adobe.com). Se puoi accedere come amministratore a più account, seleziona l’organizzazione appropriata o passa a tale organizzazione utilizzando il selettore nella barra superiore. La scheda prodotto di [!DNL Assets Essentials] è visibile in [!DNL Admin Console].

   Scheda di ![[!DNL Assets Essentials] in [!DNL Admin Console]](assets/essentials-in-admin-console.png)

   *Figura: Scheda di [!DNL Assets Essentials] in [!DNL Admin Console].*

   >[!NOTE]
   >
   >Se nella sezione prodotti trovi la scheda **[!UICONTROL AEM Assets Essentials]** anziché la scheda **[!UICONTROL AEM Assets Essentials - Cloud Manager]**, l’implementazione di Assets Essentials è già stata completata. Puoi saltare i passaggi rimanenti.

1. Aggiungi te stesso/a come amministratore al profilo del prodotto `AEM Assets Essentials - Cloud Manager` in [!DNL Admin Console]. Al tuo posto, puoi aggiungere un altro membro dell’organizzazione oppure più amministratori.

1. Fai clic sull’![icona Aggiungi](assets/do-not-localize/add-icon.svg) per [!UICONTROL selezionare i profili di prodotto], quindi seleziona [!UICONTROL Deployment Manager - Assets Essentials] come **[!UICONTROL profilo di prodotto]**. L’utente aggiunto in questo passaggio riceve un’e-mail da Adobe con accesso a [!DNL Cloud Manager] e può eseguire l’implementazione.

   ![Aggiungere un amministratore e selezionare un profilo di prodotto in [!DNL Admin Console]](assets/adminconsole-user1.png)

   *Figura: Aggiungere un amministratore e selezionare un profilo di prodotto in [!DNL Admin Console].*

1. Per accedere a [!DNL Cloud Manager], fai clic sul collegamento nell’e-mail per l’accesso a [!DNL Cloud Manager]. In alternativa, puoi accedere a [https://experience.adobe.com/#/cloud-manager/](https://experience.adobe.com/#/cloud-manager/) nel browser.

1. Nell’interfaccia utente di Cloud Manager, fai clic su **[!UICONTROL Aggiungi programma]** in alto a destra.

1. Specifica un nome a tua scelta e, facoltativamente, carica un’immagine (che rappresenterà il programma in [!DNL Cloud Manager]), quindi fai clic su **[!UICONTROL Crea]**. [!DNL Cloud Manager] richiede qualche minuto per impostare il programma.

1. Quando il programma è pronto, passa il puntatore sulla sezione e fai clic sull’![icona Aggiungi ambiente](assets/do-not-localize/add-environment-icon.png).

1. Per aggiungere il servizio [!DNL Assets Essentials] alla tua organizzazione, fai clic su **[!UICONTROL Aggiungi ambiente]**, seleziona un nome e un’area di implementazione, quindi fai clic su **[!UICONTROL Salva]**. Non sarà possibile modificare l’area di implementazione in un secondo momento. Prova a impostare l’area di implementazione di [!DNL Assets Essentials] sulla stessa area di implementazione dell’altra soluzione con cui intendi utilizzare [!DNL Assets Essentials]. In tal modo l’accesso in rete alle risorse digitali sarà quanto più rapido possibile e con latenza minima.

   ![Aggiungere un ambiente in [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

   *Figura: Aggiungere un ambiente in [!DNL Cloud Manager] per iniziare a utilizzare [!DNL Assets Essentials].*

1. Dopo alcuni minuti, una volta creato l’ambiente, puoi accedere ad [!DNL Admin Console] e aggiungere utenti della tua organizzazione alla soluzione [!DNL Assets Essentials]. Fai clic sull’![icona Opzioni](assets/do-not-localize/options-ellipses-icon.png) e seleziona **[!UICONTROL Gestione accesso]**.

   ![Ambiente pronto in [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Figura: Ambiente in [!DNL Cloud Manager] pronto all’uso.*

## Passaggi successivi {#next-steps}

* [Guarda un video per distribuire Assets Essentials](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/provisioning.html?lang=it)

* Fornisci feedback sui prodotti utilizzando l’opzione [!UICONTROL Feedback] disponibile nell’interfaccia utente di Assets Essentials

* Fornisci feedback alla documentazione utilizzando [!UICONTROL Modifica questa pagina] ![modifica la pagina](assets/do-not-localize/edit-page.png) o [!UICONTROL Segnala un problema] ![crea un problema GitHub](assets/do-not-localize/github-issue.png) disponibile sulla barra laterale destra

* Contatta il [Servizio clienti](https://experienceleague.adobe.com/?support-solution=General&amp;lang=it#support)



>[!MORELIKETHIS]
>
>* Aiuto di [[!DNL Admin Console] ](https://helpx.adobe.com/it/enterprise/using/admin-console.html)
>* Aiuto di [[!DNL Cloud Manager] ](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=it)
>* [Documentazione di Adobe Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=it)
>* [Note sulla versione](release-notes.md)
>* [Iniziare a utilizzare [!DNL Assets Essentials]](get-started.md)

