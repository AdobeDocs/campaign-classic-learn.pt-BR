---
title: Configurar campanhas de email recorrentes e contínuas
description: Saiba como configurar uma entrega recorrente e contínua e compreender as diferenças entre as duas abordagens.
feature: Workflows, Campaigns
jira: KT-1560
doc-type: feature video
activity: use
team: TM
role: User
level: Beginner
exl-id: 42f2a7e6-7d88-473b-b913-fe09b7016b28
TQID: https://experienceleague.adobe.com/JPcr0Ub8i7-L-v9MsR0BKIg0Umc6JuGIX0iBcCAc610
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
feature_v2:
  - id: a075b2c1-7748-4328-b7f6-343aa314616a
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
source-git-commit: ccbe1ae144ce2079b11103b9b8a9344fed56cbd2
workflow-type: tm+mt
source-wordcount: 240
ht-degree: 100%

---

# Configurar campanhas de email recorrentes e contínuas

Este tutorial explica como configurar uma entrega recorrente e contínua e as diferenças entre as duas abordagens.

## Rastreamento de entrega recorrente e contínua {#recurring-and-continuous-delivery-tracking}

As entregas recorrentes e contínuas diferem na maneira como os dados de contato são gerenciados:

* A **entrega contínua** permite adicionar novos destinatários a uma entrega existente, o que evita a criação de uma nova entrega cada vez que um novo destinatário for adicionado. Você pode atualizar o criativo diretamente no fluxo de trabalho da campanha e ele atualizará o modelo na pasta Recursos do template da entrega.

  Uma entrega contínua criará uma ÚNICA entrega. Logs da entrega (broadLog) e logs de rastreamento que fazem referência a uma entrega serão adicionados a cada execução.

  ![Delivery contínuo](/help/assets/delivery_continuous.jpg)

* Uma **entrega recorrente** criará uma nova instância de entrega toda vez que for executada. Por exemplo, se o fluxo de trabalho estiver programado para ser executado uma vez por semana, o resultado será 52 entregas em um ano. Também significa que o log abrangente e os logs de rastreamento serão separados por cada instância da entrega.

  ![Entrega recorrente](/help/assets/delivery_recurring.jpg)

## Como configurar uma entrega recorrente {#how-to-set-up-a-recurring-delivery}

Este vídeo explica como configurar uma entrega recorrente e uma atividade de scheduler.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12&learn=on){transcript=true}

## Como configurar uma entrega contínua {#how-to-set-up-a-continuous-delivery}

Este vídeo mostra como configurar uma entrega contínua com uma consulta incremental.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12&learn=on){transcript=true}
