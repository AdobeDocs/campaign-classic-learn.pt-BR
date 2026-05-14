---
title: Como configurar workflows de validação no Adobe Campaign Classic
description: Saiba como configurar diferentes fluxos de trabalho de validação e aprovação.
feature: Workflows, Approvals
jira: KT-1566
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: 34fbb91d-ae99-497c-872e-55ce2e6ea2aa
TQID: https://experienceleague.adobe.com/KhR76gfI2ZAMjDZDHCm7tOqQcJ5atG23hAwssYh3kcc
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
feature_v2:
  - id: a075b2c1-7748-4328-b7f6-343aa314616a
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
source-git-commit: ccbe1ae144ce2079b11103b9b8a9344fed56cbd2
workflow-type: tm+mt
source-wordcount: 274
ht-degree: 96%

---

# Criar fluxos de trabalho de validação

O Adobe Campaign oferece várias opções para que os profissionais de marketing revisem e forneçam conteúdo de entrega, direcionamento da campanha, extração de dados e aprovações de orçamento.

Este tutorial explica como configurar diferentes fluxos de trabalho de validação de aprovação.

## Pré-requisito {#prerequisite}

Antes de habilitar as etapas de aprovação, a equipe de marketing deve definir revisores individuais:

* A função de revisor do Adobe Campaign em uma atividade de aprovação pode ser um único revisor (Operador) ou um grupo de revisores (função Operador).
* Para permitir que os desenvolvedores de campanha selecionem os revisores como aprovadores em uma campanha ou entrega, os revisores e os grupos de revisores devem ser configurados no Adobe Campaign por um administrador.

## Configuração de aprovações para campanhas  {#configuring-approvals-for-campaigns}

Se você tiver o mesmo conjunto de revisores para todas as entregas no fluxo de trabalho da campanha, aplique a funcionalidade de aprovação da campanha configurando aprovações e revisores no nível da campanha. As tarefas de aprovação e os revisores são encaminhados para cada atividade de entrega do fluxo de trabalho depois que o fluxo de trabalho é executado.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12&learn=on){transcript=true}

## Configuração de aprovações para entregas  {#configuring-approvals-for-deliveries}

Você também pode configurar aprovações em um nível de entrega. Se as etapas de aprovação de entrega e os revisores forem diferentes das etapas de aprovação da campanha e dos revisores, as configurações de entrega substituirão as configurações da campanha.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12&learn=on){transcript=true}

## Configuração de uma atividade de aprovação  {#configuring-an-approval-activity}

Diferentemente das aprovações de entrega ou campanha, a atividade de aprovação permite criar um processo de aprovação em um fluxo de trabalho. Dessa forma, a lógica de seleção de direcionamento pode ser aprovada antes que a entrega seja iniciada. Ela também permite a aprovação em vários níveis no fluxo de trabalho, se necessário.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12&learn=on){transcript=true}

Para obter mais informações, consulte a [Documentação de aprovação](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=pt-BR)
