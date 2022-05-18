---
title: Integrare Assets Essentials con Adobe Workfront
description: Integra Assets Essentials con l’applicazione Adobe Workfront in modo da poter accedere all’archivio Assets Essentials all’interno dell’applicazione Workfront.
exl-id: 47c2963d-57f0-463e-8d5b-5e5af9928f77
source-git-commit: 507d5de0fad337f5c84dab28bc396dbfa7c5afe1
workflow-type: tm+mt
source-wordcount: '619'
ht-degree: 19%

---

# Integrare Assets Essentials con Adobe Workfront {#integrate-assets-essentials-workfront}

![Preferenza per scegliere il tema scuro o chiaro](assets/cce-workfront.png)

## La storia finora

Dopo [configurazione di Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) e [integrazione delle applicazioni Creative Cloud con Assets Essentials](integrate-assets-essentials-creative-cloud.md), puoi sfruttare per integrare l’applicazione Adobe Workfront con Assets Essentials.

## Obiettivo

* **Pubblico**: Amministratori Adobe Workfront

* **Obiettivo**: Integra Assets Essentials con l’applicazione Adobe Workfront in modo da poter accedere all’archivio Assets Essentials all’interno dell’applicazione Workfront.

## Panoramica

[[!DNL Adobe Workfront]](https://www.workfront.com/) è un’applicazione per la gestione dell’intero ciclo di vita del lavoro, tutto in un’unica posizione. Integrazione nativa tra [!DNL Adobe Workfront] e [!DNL Assets Essentials] consente alle organizzazioni di migliorare la velocità dei contenuti e il time-to-market collegando intrinsecamente il lavoro e la gestione delle risorse. Nel contesto di gestione del lavoro, gli utenti possono accedere ai documenti e alle immagini necessari utilizzando la stessa soluzione.

Esegui le seguenti attività per integrare Workfront con Experience Manager Assets Essentials:

* [Aggiungere utenti ai profili di prodotto Workfront](#add-users-to-product-profiles)

* [Aggiungere utenti ai profili di prodotto di Assets Essentials](#add-workfront-users-assets-essentials-product-profiles)

* [Configurare l&#39;integrazione di Experience Manager Assets Essentials](#configure-assets-essentials-integration)

## Aggiungere utenti ai profili di prodotto Workfront {#add-users-to-product-profiles}

Per aggiungere utenti ai profili di prodotto Workfront:

1. Accesso [Admin Console](https://adminconsole.adobe.com) per la tua organizzazione, fai clic su **[!UICONTROL Prodotti]** nella barra superiore, fai clic su **[!UICONTROL Workfront]**, quindi fai clic sulla prima istanza nell’elenco. Non fare clic sulla seconda e sulla terza istanza dell’elenco.

   ![Profilo amministratore di Admin Console](assets/workfront-instances.png)

   In Admin Console viene visualizzato l’unico profilo di prodotto disponibile.

1. Per aggiungere un utente a un profilo di prodotto, fai clic sul profilo, quindi fai clic su **[!UICONTROL Aggiungi utente]**, fornisci i dettagli utente e fai clic su **[!UICONTROL Salva]**.

   ![Aggiungi profilo amministratore utenti](assets/add-users-workfront.png)

   Quando aggiungi un utente, quest’ultimo riceve un invito e-mail per poter iniziare a utilizzare la soluzione. È possibile disattivare gli inviti e-mail dalle impostazioni del profilo prodotto in [!DNL Admin Console].

1. Per rimuovere un utente da un gruppo, fai clic sul gruppo, seleziona un utente esistente, quindi seleziona **[!UICONTROL Rimuovi utente]**.

Per ulteriori informazioni su come creare utenti e amministratori di sistema in Workfront con Adobe Admin Console, consulta [Gestione degli utenti in Adobe Admin Console](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FAdministration_and_Setup%2FAdd_users%2FCreate_and_manage_users%2Fadmin-console.htm&amp;_LANG=enus).

## Aggiungere utenti ai profili di prodotto di Assets Essentials {#add-workfront-users-assets-essentials-product-profiles}

Assegna gli utenti Workfront a uno dei seguenti profili di prodotto Assets Essentials:

* **[!DNL Assets Essentials]Utenti** accedere all’interfaccia utente completa di Assets Essentials. Questi utenti possono caricare, organizzare, assegnare tag e trovare risorse digitali nell’applicazione Assets Essentials. Inoltre, gli utenti possono accedere all’esperienza di selezione delle risorse incorporate in [!DNL Adobe Workfront] applicazione.
* **[!DNL Assets Essentials]Utenti consumer**: accedere all’esperienza di selezione delle risorse incorporate in [!DNL Adobe Workfront] applicazione.

Per ulteriori informazioni su come assegnare gli utenti ai profili di prodotto Assets Essentials, consulta [Assegnare gli utenti ai profili di prodotto Assets Essentials](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Configurare l&#39;integrazione di Experience Manager Assets Essentials {#configure-assets-essentials-integration}

Dopo aver aggiunto gli utenti ai profili di prodotto Workfront e Assets Essentials tramite l’Admin Console, puoi [configurare l’integrazione di Experience Manager Assets Essentials con Adobe Workfront](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2F_workfront-for-aem-asset-essentials.htm).

Dopo aver configurato l’integrazione, puoi:

* [Collegare risorse e cartelle da Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Flink-to-aem.htm&amp;_LANG=enus)

* [Inviare un documento alle funzioni di base di Experience Manager Assets](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fsend-to-aem.htm&amp;_LANG=enus)

* [Prova di una risorsa collegata per Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fproof-linked-asset-aem.htm)

* [Visualizzare o scaricare una risorsa collegata da Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fview-download-asset.htm)
