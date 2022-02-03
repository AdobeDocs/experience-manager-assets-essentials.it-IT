---
title: Come si condividono i collegamenti per le risorse?
description: Genera un collegamento e condividi risorse con altri utenti che non hanno accesso al [!DNL Assets Essentials] applicazione.
source-git-commit: 886fcc437aea05e1e1ae6d6d1fec945cf5699f24
workflow-type: tm+mt
source-wordcount: '390'
ht-degree: 0%

---


# Share links for assets {#share-links-assets}

[!DNL Assets Essentials] consente di generare un collegamento e condividere risorse con soggetti esterni che non hanno accesso al [!DNL Assets Essentials] applicazione. Puoi definire:

* Data di scadenza del collegamento

* If the recipients are allowed to download the assets (original binaries) after accessing the link.

In base a queste impostazioni, il destinatario del collegamento può scegliere di visualizzare in anteprima le risorse o scaricarle.

## Generate a link for assets {#generate-link-for-assets}

Per generare un collegamento per una risorsa o una cartella contenente risorse:

1. Seleziona le risorse e/o le cartelle contenenti le risorse e fai clic su **[!UICONTROL Share Link]**.

1. Per modificarla, fai clic sull’icona Calendario per definire una data di scadenza del collegamento utilizzando **[!UICONTROL Expiration Date]** campo . You can also specify a date directly in the `yyyy-mm-dd` format. Per impostazione predefinita, la data di scadenza di un collegamento è impostata su 2 settimane dalla data di condivisione.

1. Seleziona **[!UICONTROL Allow download]** per consentire al destinatario del collegamento di scaricare le risorse.

1. Clic **[!UICONTROL Generate Link]**.

1. Fai clic su **[!UICONTROL Copy Link]** per copiare il collegamento. Puoi anche copiare il collegamento dal **[!UICONTROL Share Link]** campo .

   ![Option to crop and straighten](assets/share-asset-link.png)

1. Fai clic su **[!UICONTROL Close]** e condividere il collegamento tramite e-mail o altri strumenti di collaborazione.

## Accedere alle risorse condivise {#access-shared-assets}

Dopo aver condiviso il collegamento pubblico per le risorse, i destinatari possono fare clic sul collegamento per visualizzare in anteprima o scaricare le risorse condivise in un browser web senza dover accedere a [!DNL Assets Essentials].

Fai clic sul collegamento, fai clic sulla cartella per passare alla risorsa, quindi fai clic sulla risorsa per visualizzarla in anteprima. Potete selezionare di visualizzare le risorse condivise in una vista a elenco o a schede.

You can hover the mouse over the shared asset or the shared assets folder to either select the asset or download it.

Puoi anche selezionare più risorse e fare clic su **[!UICONTROL Download]**. [!DNL Assets Essentials] scarica le risorse selezionate come file zip. [!DNL Assets Essentials] creates a sub-folder in the parent zip file, with the same name as that of the asset, for each asset that you select to download.

To download all assets at once, switch to the **[!UICONTROL List view]**, click **[!UICONTROL Select all]** and then click **[!UICONTROL Download]**.

>[!NOTE]
>
>Se non si abilita l&#39;opzione di download mentre [generazione del collegamento](#share-links-assets) per una risorsa e se il destinatario del collegamento seleziona di scaricare la risorsa, [!DNL Assets Essentials] scarica un file zip vuoto.

![Opzione per ritagliare e raddrizzare](assets/preview-shared-assets.png)

