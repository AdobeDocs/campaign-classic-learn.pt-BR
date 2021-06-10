---
title: Como configurar campanhas de email recorrentes e contínuas
description: Saiba como configurar um delivery recorrente e contínuo e compreender as diferenças entre as duas abordagens.
feature: Workflows
kt: 1560
doc-type: feature video
activity: use
team: TM
role: Business Practitioner
level: Beginner
exl-id: 42f2a7e6-7d88-473b-b913-fe09b7016b28
source-git-commit: 5fb898eca821c5078393003c41032801f8454fd5
workflow-type: tm+mt
source-wordcount: '268'
ht-degree: 67%

---

# Como configurar campanhas de email recorrentes e contínuas

Este tutorial explica como configurar um delivery recorrente e contínuo e as diferenças entre as duas abordagens.

## Rastreamento de entrega recorrente e contínua {#recurring-and-continuous-delivery-tracking}

Os deliveries recorrentes e contínuos diferem na maneira como os dados de contato são gerenciados:

* O **delivery contínuo** permite adicionar novos recipients a um delivery existente, o que evita a criação de um novo delivery cada vez que um novo recipient for adicionado. Você pode atualizar o criativo diretamente no workflow da campanha e ele atualizará o modelo na pasta Recursos do template do delivery.

   Um delivery contínuo criará um ÚNICO delivery. Logs do delivery (broadLog) e logs de rastreamento que fazem referência a um delivery serão adicionados a cada execução.

   ![Delivery contínuo](/help/assets/delivery_continuous.jpg)

* Um **delivery recorrente** criará uma nova instância de delivery toda vez que for executado. Por exemplo, se o workflow estiver programado para ser executado uma vez por semana, o resultado será 52 deliveries em um ano. Também significa que o log abrangente e os logs de rastreamento serão separados por cada instância do delivery.

   ![Delivery recorrente](/help/assets/delivery_recurring.jpg)

## Como configurar uma entrega recorrente {#how-to-set-up-a-recurring-delivery}

Este vídeo explica como configurar um delivery recorrente e uma atividade de scheduler.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## Como configurar uma entrega contínua {#how-to-set-up-a-continuous-delivery}

Este vídeo mostra como configurar um delivery contínuo com um query incremental.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)

## Recursos adicionais

[Criando um delivery recorrente em um workflow de direcionamento](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/use-cases/deliveries/sending-a-birthday-email.html?lang=en#creating-a-recurring-delivery-in-a-targeting-workflow)
