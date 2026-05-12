---
title: Connettere AEM Assets a Creative Cloud
description: Scopri come configurare e collegare AEM Assets a Creative Cloud. Connettiti a una licenza Creative Cloud fornita a un’altra organizzazione IMS per utilizzare facilmente le integrazioni Creative Cloud più recenti in AEM Assets, inclusi Express e Creative Cloud Libraries.
exl-id: 3d8d7429-ddf6-44cd-a6e7-ba2afcbaf52b
TQID: https://experienceleague.adobe.com/jNPNmqvjsK-A6LD-Mk02ffYM15aO2zudSfhJrST-gVA
product_v2: id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
feature_v2: id: ae478996-b206-4712-9b0c-dc78a2644453
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554id: f8a45b24-4be7-4f1b-909b-60d06b483a20
source-git-commit: f026b389ce582ece5d2ca8745d291b1ae50d657e
workflow-type: tm+mt
source-wordcount: 287
ht-degree: 100%

---

# Connettere AEM Assets a Creative Cloud  {#cross-org-entitlements}

Experience Manager Assets è in grado di connettersi a una licenza Creative Cloud fornita a un’altra organizzazione IMS per utilizzare facilmente le più recenti integrazioni Creative Cloud in AEM Assets, inclusi Express e Creative Cloud Libraries.

Se per i prodotti Creative Cloud e AEM Assets è stato eseguito il provisioning per organizzazioni IMS separate, è possibile connettersi a un’organizzazione Creative Cloud diversa per eseguire flussi di lavoro integrati tra le due soluzioni.

## Prerequisiti {#prerequisites}

* Diritti di amministratore su Experience Manager Assets

* Diritto attivo a Creative Cloud per lo stesso ID utente utilizzato in Creative Cloud e Experience Manager. I diritti a ID personali e federati con lo stesso indirizzo e-mail vengono trattati come ID utente diversi.

## Connettersi a una nuova organizzazione Creative Cloud {#connect-to-creative-cloud-org}

Per connettersi a una nuova organizzazione Creative Cloud, effettua le seguenti operazioni:

1. Accedi a **[!UICONTROL Impostazioni]** > **[!UICONTROL Creative Cloud]**.

1. Seleziona la nuova organizzazione Creative Cloud utilizzando l’elenco a discesa **[!UICONTROL Seleziona nuovo ID organizzazione Creative Cloud]**. Nell’elenco vengono visualizzate tutte le organizzazioni a cui hai accesso. Seleziona l’organizzazione con diritti attivi per Creative Cloud.

1. Fai clic su **[!UICONTROL Cambia organizzazione]** per passare alla nuova organizzazione.

   ![Diritti per più organizzazioni](assets/cross-org-entitlements.png)

## Limitazioni {#limitations}

* Puoi collegare AEM Assets a un’organizzazione Creative Cloud alla volta. La connessione a più organizzazioni Creative Cloud alla volta non è supportata.

* L’organizzazione Creative Cloud a cui ti connetti in AEM Assets è applicabile a tutti gli utenti all’interno dell’organizzazione.
