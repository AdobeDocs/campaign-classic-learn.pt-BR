---
title: Como configurar workflows de validação no Adobe Campaign Classic
seo-title: Como configurar workflows de validação no Adobe Campaign Classic
description: A Adobe Campaign oferta várias opções para que os comerciantes revisem e forneçam conteúdo de delivery, público alvo de campanhas, extração de dados e aprovações de orçamento. Este tutorial explica como configurar diferentes workflows de validação de aprovação.
seo-description: Este vídeo explica como configurar e usar um template do delivery na Campanha ACCAdobe ofertas várias opções para que os profissionais de marketing revisem e forneçam conteúdo de delivery, público alvo de campanhas, extração de dados e aprovações de orçamento. Este tutorial explica como configurar diferentes workflows de validação de aprovação.
uuid: fdeb7aef-95aa-4bc1-9c51-2eb7ce802107
discoiquuid: 29abc57d-c359-472d-817a-0671818894f0
feature: Workflow
topics: Validation
kt: KT-1566
doc-type: feature video
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 838c617ca163a09fcb57b7b4706433e98869bc3d
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# Como configurar workflows de validação no Adobe Campaign Classic

A Adobe Campaign oferta várias opções para que os comerciantes revisem e forneçam conteúdo de delivery, público alvo de campanhas, extração de dados e aprovações de orçamento.

Este tutorial explica como configurar diferentes workflows de validação de aprovação.

## Pré-requisito {#prerequisite}

Antes de habilitar as etapas de aprovação, a equipe de marketing deve definir revisores individuais:

* A função de revisor do Adobe Campaign em uma atividade de aprovação pode ser um único revisor (Operador) ou um grupo de revisores (função Operador).
* Os revisores e os grupos de revisores devem ser configurados anteriormente no Adobe Campaign por uma função de Administrador. Isso permite que os desenvolvedores de campanhas selecionem os revisores como aprovadores em uma campanha ou delivery.

## Configurar aprovações para campanha {#configuring-approvals-for-campaigns}

Se você tiver o mesmo conjunto de revisores para todos os delivery no fluxo de trabalho da campanha, você aproveitaria as funcionalidades de aprovação [!DNL Campaign]. Ao configurar aprovações e revisores no nível de campanha, as tarefas de aprovação e os revisores serão encaminhados para cada atividade de delivery do fluxo de trabalho depois que o fluxo de trabalho for executado.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Configurar aprovações para delivery {#configuring-approvals-for-deliveries}

Você também pode configurar aprovações em nível de delivery. Se as etapas de aprovação de delivery e os revisores forem diferentes das etapas de aprovação de campanhas e dos revisores, as configurações de delivery substituirão as configurações de campanha.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Configurar uma atividade de aprovação {#configuring-an-approval-activity}

Diferentemente das aprovações de delivery ou campanhas, a atividade de aprovação permite criar um processo de aprovação em um fluxo de trabalho. Dessa forma, a lógica de seleção de definição de metas pode ser aprovada antes que o delivery seja iniciado. Também permite aprovação em vários níveis dentro do fluxo de trabalho, se necessário.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

Para obter mais informações, consulte a [Documentação de aprovação](https://docs.adobe.com/help/en/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)
