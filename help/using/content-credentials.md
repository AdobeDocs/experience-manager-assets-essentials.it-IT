---
title: Integrazione con Content Credentials
description: Content Credentials, integrato in AEM Assets e incluso nell’interfaccia utente di AEM Assets Essentials, può offrire un contesto nella cronologia di una risorsa, compreso come è stata creata e chi è stato coinvolto nella sua creazione. Come un’etichetta nutrizionale per i contenuti digitali, Content Credentials può contribuire ad aumentare la trasparenza e a creare fiducia nei confronti del pubblico.
role: User
exl-id: 703f74a6-24d4-4181-8174-9ff4a90ee7aa
TQID: https://experienceleague.adobe.com/witCqgAh8EKfD-hdn8efjZ-M4sypX44KB2ELs3ECInI
product_v2:
  - id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
feature_v2:
  - id: ec4263d9-bf7c-44c7-b3f1-3e664861c8f2
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
topic_v2:
  - id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
source-git-commit: f026b389ce582ece5d2ca8745d291b1ae50d657e
workflow-type: tm+mt
source-wordcount: 474
ht-degree: 13%

---

# Content Credentials {#content-credentials}

I brand sono sempre più attenti alla trasparenza dei contenuti, la divulgazione circa l’utilizzo dell’intelligenza artificiale e la prevenzione rispetto alla manomissione delle risorse. Content Authenticity Initiative (CAI) di Adobe crea strumenti conformi allo standard tecnico [Coalition for Content Provenance and Authenticity](https://c2pa.org/specifications/specifications/1.1/specs/C2PA_Specification.html#_trust_model) (C2PA). Content Credentials, un nuovo tipo di metadati crittografati e in grado di evidenziare eventuali manomissioni, consente agli utenti di comprendere la provenienza dei contenuti e di garantire l’integrità delle risorse del brand. Possono includere un’ampia gamma di dati di provenienza che offrono informazioni sulla cronologia di una risorsa digitale.

Queste informazioni includono:

* **Emittente o firmatario:** informazioni sull&#39;entità o sulla società che ha emesso la firma digitale per certificare la risorsa.
* **Data problema:** la data in cui il Content Credential è stato applicato alla risorsa.
* **Credito e utilizzo:** informazioni sul produttore della risorsa, tra cui nome, handle per social media o altre informazioni relative all&#39;identità.
* **Processo:** record di eventuali modifiche apportate alla risorsa.
* **Dettagli dispositivo:** informazioni sull&#39;app o sul dispositivo utilizzato per creare o modificare la risorsa.
* **Strumento di intelligenza artificiale utilizzato:** se è stata utilizzata l&#39;intelligenza artificiale generativa per modificare o creare la risorsa, è possibile includere il nome del modello utilizzato.
* **Altre informazioni importanti:** potrebbero essere inclusi anche dati aggiuntivi per offrire più contesto sulla cronologia di una risorsa.

Per una visualizzazione completa, [Verifica](https://contentcredentials.org/verify) può offrire un insight più completo nella cronologia delle risorse.

Adobe Experience Manager Assets ora supporta Content Credentials, consentendo agli utenti di visualizzare Content Credentials direttamente nell’interfaccia utente di Assets Essentials di AEM. Esaminando i dettagli della risorsa, qualsiasi immagine con Content Credentials (ad esempio quelle create con i servizi GenAI) mostra i dettagli del manifesto in un pannello dedicato. Se la risorsa viene scaricata, pubblicata o condivisa, le credenziali rimangono intatte insieme alla risorsa.

![risorse](/help/using/assets/content-credentials.png)

## Accedere a Content Credentials {#access-content-credentials}

1. Vai all&#39;interfaccia utente di Assets Essentials e fai clic su **Assets** nel riquadro a sinistra.
1. Passa a una cartella e seleziona la risorsa desiderata.
1. Fai clic su **Dettagli** e seleziona `Cr pin` dal riquadro più a destra. Nella scheda Content Credentials sono visualizzate le seguenti informazioni sulla risorsa.
   1. **Immagine generata:** Data e ora di applicazione di Content Credentials.
   1. **Riepilogo contenuto:** indica se la risorsa è generata parzialmente o completamente da IA o come è stata modificata.
      ![riepilogo contenuti](/help/using/assets/content-credentials1.png)
   1. **Processo:** descrive l&#39;applicazione, il dispositivo e lo strumento di intelligenza artificiale (ad esempio Adobe Firefly) utilizzati per generare la risorsa, nonché le modifiche apportate successivamente.
      ![processo](/help/using/assets/CR-Process.png)
   1. **Informazioni su questo Content Credentials:** Nome dell&#39;emittente insieme alla data e all&#39;ora di emissione.
      ![emittente](/help/using/assets/CR-issuer.png)
