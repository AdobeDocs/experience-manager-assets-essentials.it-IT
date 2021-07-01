---
title: Distribuzione e gestione degli utenti
description: Casi di utilizzo dell'amministrazione, ad esempio la distribuzione e la gestione degli utenti in [!DNL Assets Essentials].
role: Administrator
source-git-commit: e54cdf9b8ecb5d9ddc5b90a3ca82549c61b35074
workflow-type: tm+mt
source-wordcount: '769'
ht-degree: 2%

---


# Distribuire [!DNL Assets Essentials] e aggiungere utenti {#administer}

[!DNL Adobe Experience Manager Assets Essentials] è fornito per Adobe per i suoi clienti. Come parte del provisioning, [!DNL Assets Essentials] viene aggiunto all&#39;organizzazione di un cliente (organizzazione Adobe). Il cliente ha anche accesso a [!DNL Experience Manager Cloud Manager] come strumento di distribuzione e a [!DNL Admin Console] come strumento di gestione degli utenti.

Gli amministratori eseguono le seguenti attività:

* [ [!DNL Assets Essentials]](#deploy-essentials) Implementazione per la loro organizzazione.
* [Gestisci l&#39;](#add-users-to-essentials) accesso utente dei membri dell&#39;organizzazione a  [!DNL Assets Essentials].
* Facoltativamente, [visualizza lo stato del servizio e registra](#view-logs).

## Implementa [!DNL Assets Essentials] {#deploy-essentials}

Dopo il provisioning, l’adesione [!DNL Assets Essentials] viene aggiunta all’organizzazione Adobe e l’amministratore di un’organizzazione la distribuisce. Gli amministratori dell&#39;organizzazione eseguono una distribuzione una tantum utilizzando l&#39;interfaccia utente [!DNL Cloud Manager]. Dopo la distribuzione iniziale, Adobe esegue la manutenzione e gli aggiornamenti del servizio. Per distribuire, segui questi passaggi:

1. Assicurati che l’amministratore riceva un’e-mail dall’Adobe. L’e-mail contiene un messaggio di benvenuto e un collegamento per iniziare.

1. Dal collegamento nell&#39;e-mail, accedi e accedi a [Admin Console](https://adminconsole.adobe.com). Se disponi dell&#39;accesso dell&#39;amministratore a più account organizzazione, seleziona l&#39;organizzazione appropriata o passa a tale organizzazione utilizzando il commutatore nella barra superiore. La scheda prodotto per [!DNL Assets Essentials] è visibile in [!DNL Admin Console].

   ![[!DNL Assets Essentials] ingresso scheda  [!DNL Admin Console]](assets/essentials-in-admin-console.png)

1. Aggiungi te stesso come amministratore al prodotto `AEM Assets Essentials - Cloud Manager` in [!DNL Cloud Manager]. Puoi aggiungere un altro membro dell’organizzazione oppure più amministratori.

1. Fai clic su ![aggiungi icona](assets/do-not-localize/add-icon.svg) a [!UICONTROL Select product profiles], quindi seleziona [!UICONTROL Deployment Manager - Assets Essentials] come **[!UICONTROL product profile]**. L’utente aggiunto in questo passaggio riceve un’e-mail dall’Adobe con accesso a [!DNL Cloud Manager] e può eseguire la distribuzione.

   ![Aggiungi un amministratore e seleziona un profilo di prodotto in  [!DNL Admin Console]](assets/adminconsole-user1.png)

1. Per accedere a [!DNL Cloud Manager], fai clic sul collegamento nell’e-mail con accesso a [!DNL Cloud Manager]. In alternativa, accedi a `https://experience.adobe.com/#/cloud-manager/` nel browser.

1. Nell’interfaccia utente di Cloud Manager, fai clic su **[!UICONTROL Add Program]** nell’angolo in alto a destra.

1. Specifica un nome a tua scelta e, facoltativamente, carica un&#39;immagine (che rappresenta il programma in [!DNL Cloud Manager]), quindi fai clic su **[!UICONTROL Create]**. [!DNL Cloud Manager] l&#39;impostazione del programma richiede alcuni minuti.

1. Quando il programma è pronto, posiziona il puntatore del mouse sul riquadro e fai clic su ![aggiungi l&#39;icona dell&#39;ambiente](assets/do-not-localize/add-environment-icon.png).

1. Per aggiungere il servizio [!DNL Assets Essentials] all&#39;organizzazione, fare clic su **[!UICONTROL Add Environment]**, selezionare un nome e un&#39;area di distribuzione, quindi fare clic su **[!UICONTROL Save]**. Non è possibile modificare l&#39;area di distribuzione in un secondo momento. Prova a far corrispondere l’area di distribuzione di [!DNL Assets Essentials] con l’area di distribuzione dell’altra soluzione con cui intendi utilizzare [!DNL Assets Essentials]. L&#39;obiettivo è garantire l&#39;accesso alla rete più rapido possibile alle risorse digitali e la latenza più bassa possibile.

   ![Aggiungi un ambiente in  [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

1. Quando l’ambiente viene creato correttamente, puoi accedere alla soluzione [!DNL Admin Console] e aggiungere gli utenti dell’organizzazione alla soluzione [!DNL Assets Essentials]. Fare clic sull&#39;icona ![opzioni](assets/do-not-localize/options-ellipses-icon.png) e selezionare l&#39;opzione **[!UICONTROL Manage Access]**.

   ![Ambiente pronto in  [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

## Gestione degli utenti {#add-users-to-essentials}

Un amministratore gestisce a quali utenti è consentito l&#39;accesso a [!DNL Assets Essentials]. Gli amministratori utilizzano [!DNL Adobe Admin Console] per aggiungere o rimuovere l’accesso utente. [!DNL Assets Essentials] dispone dei due tipi seguenti di accesso utente disponibili.

* **[!DNL Assets Essentials]** Accesso utente all’interfaccia utente completa. Questi utenti possono caricare, organizzare, assegnare tag e trovare risorse digitali.
* **[!DNL Assets Essentials]Utenti** consumer: accedere all’esperienza di selezione delle risorse incorporate nell’editor dei modelli di  [!DNL Adobe Journey Optimizer] e-mail. Per ulteriori informazioni, consulta [Utilizzare [!DNL Assets Essentials] in [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

In [!DNL Admin Console], questi due tipi di accesso sono rappresentati da due [!UICONTROL Product Profiles]. Per aggiungere e rimuovere membri dell’organizzazione a uno qualsiasi dei due profili, effettua le seguenti operazioni:

1. Accedi a [!DNL Admin Console] per la tua organizzazione, fai clic su **[!UICONTROL Products]** nella barra superiore, fai clic su **[!UICONTROL AEM Assets Essentials]**, quindi fai clic su [!DNL Assets Essentials] ambiente. [!DNL Assets Essentials] dispone di due profili di prodotto che rappresentano l’accesso per utenti regolari e consumer.

   ![Due profili per due tipi di utenti](assets/adminconsole-user-types.png)

1. Per aggiungere un utente a un gruppo, fare clic sul gruppo, selezionare **[!UICONTROL Add User]**, fornire i dettagli utente e fare clic su **[!UICONTROL Save]**. Quando aggiungi un utente, questo riceve un invito e-mail per iniziare. Puoi disattivare gli inviti e-mail nelle impostazioni del profilo di prodotto in [!DNL Admin Console].

   ![Aggiungi un utente a  [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

1. Per rimuovere un utente da un gruppo, fare clic sul gruppo, selezionare un utente esistente e selezionare **[!UICONTROL Remove User]**.

>[!TIP]
>
>In [!DNL Admin Console] puoi gestire gli utenti in blocco utilizzando file CSV. Per ulteriori informazioni, consulta [[!DNL Admin Console] documentazione](https://helpx.adobe.com/enterprise/using/accounts.html).

## Visualizza lo stato del servizio e i registri di accesso {#view-logs}

Dopo il provisioning, gli amministratori distribuiscono [!DNL Assets Essentials] una sola volta. Dopo la distribuzione iniziale, Adobe esegue la manutenzione e gli aggiornamenti del servizio. Gli amministratori possono utilizzare l’ interfaccia utente [!DNL Cloud Manager] per controllare lo stato del servizio e scaricare i registri di accesso recenti.

1. Quando gli utenti segnalano dei problemi, controlla lo stato del servizio di [!DNL Assets Essentials] nell&#39;interfaccia di **[!UICONTROL Program Overview]**. Durante il normale funzionamento della soluzione, lo stato è `Running`. Se [!DNL Cloud Manager] visualizza qualsiasi altro stato, crea un ticket di supporto nella sezione relativa al supporto [!DNL Admin Console].

   ![Stato in esecuzione di  [!DNL Assets Essentials] in  [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

1. Per scaricare i registri di accesso recenti, fai clic sull&#39;icona ![opzioni](assets/do-not-localize/options-ellipses-icon.png), seleziona **[!UICONTROL Download Logs]** e segui le istruzioni sullo schermo. Puoi controllare le richieste di accesso HTTPS utilizzando i registri.

   ![Opzione dei registri di download](assets/cloudmanager-download-logs.png)

>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] aiuto](https://helpx.adobe.com/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] aiuto](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=it)
>* [Documentazione di Adobe Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html)
>* [Note sulla versione](release-notes.md)
* [Introduzione a [!DNL Assets Essentials]](get-started.md)

