---
title: Amministrare e gestire gli utenti
description: Casi di utilizzo dell’amministrazione, ad esempio distribuzione e gestione degli utenti in [!DNL Assets Essentials].
role: Admin
exl-id: ef91126f-3aee-442b-b242-a6bf4034f3dc
source-git-commit: fb4ca5b3ab85f77cc1013c2d4743530f5d48e96d
workflow-type: tm+mt
source-wordcount: '1129'
ht-degree: 1%

---

# Amministrare [!DNL Assets Essentials] e aggiungere utenti {#administer}

[!DNL Adobe Experience Manager Assets Essentials] è fornito per Adobe per i suoi clienti. Come parte del provisioning, [!DNL Assets Essentials] viene aggiunto all’organizzazione di un cliente in [!DNL Adobe Admin Console]. Gli amministratori utilizzano [!DNL Admin Console] per gestire le adesioni utente a [!DNL Assets Essentials] e assegnare agli amministratori dell&#39;applicazione le autorizzazioni e i moduli di metadati in [!DNL Assets Essentials].

## Distribuzione automatica di Assets Essentials {#automatic-deployment-assets-essentials}

Dopo il provisioning della soluzione Assets Essentials, l’amministratore riceve un’e-mail da Adobe. L’e-mail contiene un messaggio di benvenuto e un collegamento per iniziare. Inoltre, Adobe avvia il processo di distribuzione automatica di Assets Essentials. Il completamento del processo di distribuzione richiede un&#39;ora.

Dal collegamento nell’e-mail, accedi e accedi a [Admin Console](https://adminconsole.adobe.com). Se disponi dell&#39;accesso dell&#39;amministratore a più account organizzazione, seleziona l&#39;organizzazione appropriata o passa a tale organizzazione utilizzando il commutatore nella barra superiore. Una volta completato il processo di distribuzione automatica, la scheda prodotto per [!DNL AEM Assets Essentials] è visibile in [!DNL Admin Console].

![Implementazione di Assets Essentials](assets/assets-essentials-deployment.png)

Dopo la corretta implementazione della soluzione Assets Essentials, gli amministratori devono eseguire le seguenti attività:

* [Impostare gruppi di utenti, struttura delle cartelle e assegnare autorizzazioni](manage-permissions.md) per la soluzione. Segui [best practice](permission-management-best-practices.md) per garantire una configurazione delle autorizzazioni semplice ed efficace.
* [Gestire l’accesso utente](#add-users-to-essentials) dei membri dell&#39;organizzazione [!DNL Assets Essentials].
* Facoltativamente, [visualizzare lo stato e i registri del servizio](#view-logs).

>[!NOTE]
>
>Se è stato eseguito il provisioning di Assets Essentials prima del 06 gennaio 2022, esegui la [passaggi di implementazione in Cloud Manager](#deploy-essentials) prima di gestire l&#39;accesso utente dei membri dell&#39;organizzazione.


## Gestione degli utenti {#add-users-to-essentials}

Un amministratore gestisce a quali utenti è concesso l&#39;accesso [!DNL Assets Essentials]. Gli amministratori utilizzano [!DNL Adobe Admin Console] per aggiungere o rimuovere l’accesso utente. [!DNL Assets Essentials] dispone dei due tipi seguenti di accesso utente disponibili.

* **[!DNL Assets Essentials]Amministratori** avere accesso amministrativo alla domanda. Oltre a tutte le funzionalità degli utenti finali, gli amministratori delle applicazioni di questo gruppo possono gestire le autorizzazioni per qualsiasi cartella e gruppo/utente nell&#39;intero archivio delle applicazioni.
* **[!DNL Assets Essentials]Utenti** accedere all&#39;interfaccia utente completa. Questi utenti possono caricare, organizzare, assegnare tag e trovare risorse digitali.
* **[!DNL Assets Essentials]Utenti consumer**: accedere all’esperienza di selezione delle risorse incorporate in [!DNL Adobe Journey Optimizer] editor di modelli e-mail. Per ulteriori informazioni, consulta [Utilizzo [!DNL Assets Essentials] in [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

In [!DNL Admin Console], questi tre tipi di accesso sono rappresentati da tre [!UICONTROL Profili di prodotto]. Per aggiungere e rimuovere membri dell’organizzazione a uno qualsiasi dei due profili, effettua le seguenti operazioni:

1. Accesso [!DNL Admin Console] per la tua organizzazione, fai clic su **[!UICONTROL Prodotti]** nella barra superiore, fai clic su **[!UICONTROL Nozioni di base su AEM Assets]**, quindi fai clic su [!DNL Assets Essentials] ambiente. [!DNL Assets Essentials] dispone di tre profili di prodotto che rappresentano l’accesso per gli utenti amministratori, regolari e consumer.

   ![Tre profili per tre tipi di utenti](assets/admin-console-admin-profile.png)
   <!-- Need to update screenshot to include 3 profiles -->

   *Figura: Sono disponibili tre profili per aggiungere i tre tipi di utenti.*

1. Per aggiungere un utente a un gruppo, fai clic sul gruppo e seleziona **[!UICONTROL Aggiungi utente]**, fornisci i dettagli utente e fai clic su **[!UICONTROL Salva]**. Quando aggiungi un utente, questo riceve un invito e-mail per iniziare. Puoi disattivare gli inviti e-mail nelle impostazioni del profilo di prodotto in [!DNL Admin Console].

   ![Aggiungi un utente a [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

   *Figura: Aggiungi un utente a [!DNL Assets Essentials] da [!DNL Admin Console].*

1. Per rimuovere un utente da un gruppo, fare clic sul gruppo, selezionare un utente esistente e selezionare **[!UICONTROL Rimuovi utente]**.

>[!TIP]
>
>In [!DNL Admin Console], puoi gestire gli utenti in blocco utilizzando file CSV. Per ulteriori informazioni, consulta [[!DNL Admin Console] documentazione](https://helpx.adobe.com/enterprise/using/accounts.html).

## Visualizza lo stato del servizio e i registri di accesso {#view-logs}

Dopo il provisioning, gli amministratori distribuiscono [!DNL Assets Essentials] una sola volta. Dopo la distribuzione iniziale, Adobe esegue la manutenzione e gli aggiornamenti del servizio. Gli amministratori possono utilizzare [!DNL Cloud Manager] interfaccia utente per controllare lo stato del servizio e scaricare i registri di accesso recenti.

1. Quando gli utenti segnalano dei problemi, controlla lo stato del servizio di [!DNL Assets Essentials] in **[!UICONTROL Panoramica del programma]** interfaccia. Durante il normale funzionamento della soluzione, lo stato è `Running`. Se [!DNL Cloud Manager] visualizza qualsiasi altro stato, crea un ticket di supporto nel [!DNL Admin Console] sezione supporto.

   ![Lo stato di [!DNL Assets Essentials] in [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Figura: Lo stato normale di [!DNL Assets Essentials] in [!DNL Cloud Manager] è `Running`.*

1. Per scaricare i registri di accesso recenti, fai clic su ![icona delle opzioni](assets/do-not-localize/options-ellipses-icon.png), seleziona **[!UICONTROL Download dei registri]** e seguire le istruzioni visualizzate. Puoi controllare le richieste di accesso HTTPS utilizzando i registri.

   ![ Opzione per scaricare i registri di accesso](assets/cloudmanager-download-logs.png)

   *Figura: Opzione per scaricare i registri di accesso.*

## Implementa [!DNL Assets Essentials] {#deploy-essentials}

>[!NOTE]
>
>Esegui questi passaggi solo se è stato eseguito il provisioning di Assets Essentials prima del 6 gennaio 2022.

Dopo il provisioning, [!DNL Assets Essentials] l&#39;adesione viene aggiunta all&#39;organizzazione in [!DNL Admin Console]. Prima che la soluzione sia disponibile per l&#39;utente, un amministratore dell&#39;organizzazione deve distribuirla. L&#39;amministratore esegue una distribuzione una tantum utilizzando [!DNL Cloud Manager] interfaccia utente. Dopo la distribuzione iniziale, Adobe esegue la manutenzione e gli aggiornamenti del servizio. Dopo il provisioning della soluzione, l’amministratore riceve un’e-mail da Adobe. L’e-mail contiene un messaggio di benvenuto e un collegamento per iniziare. Per distribuire, segui questi passaggi:

1. Dal collegamento nell’e-mail, accedi e accedi a [Admin Console](https://adminconsole.adobe.com). Se disponi dell&#39;accesso dell&#39;amministratore a più account organizzazione, seleziona l&#39;organizzazione appropriata o passa a tale organizzazione utilizzando il commutatore nella barra superiore. La scheda prodotto per [!DNL Assets Essentials] è visibile in [!DNL Admin Console].

   ![[!DNL Assets Essentials] ingresso scheda [!DNL Admin Console]](assets/essentials-in-admin-console.png)

   *Figura: [!DNL Assets Essentials] ingresso scheda [!DNL Admin Console].*

   >[!NOTE]
   >
   >Se è possibile visualizzare il **[!UICONTROL Nozioni di base su AEM Assets]** scheda nella sezione prodotti anziché **[!UICONTROL AEM Assets Essentials - Cloud Manager]** la distribuzione di Assets Essentials è già completa. Puoi saltare i passaggi rimanenti.

1. Aggiungi te stesso come amministratore al `AEM Assets Essentials - Cloud Manager` profilo di prodotto nel [!DNL Admin Console]. Puoi aggiungere un altro membro dell’organizzazione oppure più amministratori.

1. Fai clic su ![icona aggiungi](assets/do-not-localize/add-icon.svg) a [!UICONTROL Selezionare i profili di prodotto], quindi seleziona [!UICONTROL Deployment Manager - Assets Essentials] come **[!UICONTROL profilo di prodotto]**. L’utente aggiunto in questo passaggio riceve un’e-mail dall’Adobe con accesso a [!DNL Cloud Manager] e può eseguire la distribuzione.

   ![Aggiungi un amministratore e seleziona un profilo di prodotto in [!DNL Admin Console]](assets/adminconsole-user1.png)

   *Figura: Aggiungi un amministratore e seleziona un profilo di prodotto in [!DNL Admin Console].*

1. Per accedere [!DNL Cloud Manager], fai clic sul collegamento nell’e-mail con accesso a [!DNL Cloud Manager]. In alternativa, puoi accedere a [https://experience.adobe.com/#/cloud-manager/](https://experience.adobe.com/#/cloud-manager/) nel browser.

1. Nell’interfaccia utente di Cloud Manager, fai clic su **[!UICONTROL Aggiungi programma]** dall&#39;angolo in alto a destra.

1. Fornisci un nome a tua scelta e, facoltativamente, carica un&#39;immagine (rappresenta il programma in [!DNL Cloud Manager]), quindi fai clic su **[!UICONTROL Crea]**. [!DNL Cloud Manager] l&#39;impostazione del programma richiede alcuni minuti.

1. Quando il programma è pronto, posiziona il puntatore del mouse sulla tessera e fai clic su ![icona aggiungi ambiente](assets/do-not-localize/add-environment-icon.png).

1. Per aggiungere [!DNL Assets Essentials] servizio alla tua organizzazione, fai clic su **[!UICONTROL Aggiungi ambiente]**, seleziona un nome e un&#39;area di distribuzione e fai clic su **[!UICONTROL Salva]**. Non è possibile modificare l&#39;area di distribuzione in un secondo momento. Prova a trovare una corrispondenza con la regione di distribuzione di [!DNL Assets Essentials] con l&#39;area di distribuzione dell&#39;altra soluzione con cui si intende utilizzare [!DNL Assets Essentials]. L&#39;obiettivo è garantire l&#39;accesso alla rete più rapido possibile alle risorse digitali e la latenza più bassa possibile.

   ![Aggiungi un ambiente in [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

   *Figura: Aggiungi un ambiente in [!DNL Cloud Manager] per iniziare a utilizzare [!DNL Assets Essentials].*

1. Dopo alcuni minuti, quando l’ambiente viene creato correttamente, puoi accedere al [!DNL Admin Console] e aggiungi gli utenti della tua organizzazione a [!DNL Assets Essentials] soluzione. Fai clic su ![icona delle opzioni](assets/do-not-localize/options-ellipses-icon.png) e seleziona la **[!UICONTROL Gestisci accesso]** opzione .

   ![Ambiente pronto in [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Figura: Un ambiente in [!DNL Cloud Manager] pronto all’uso.*

>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] aiuto](https://helpx.adobe.com/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] aiuto](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=it)
>* [Documentazione di Adobe Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html)
>* [Note sulla versione](release-notes.md)
>* [Introduzione all&#39;utilizzo [!DNL Assets Essentials]](get-started.md)

