---
title: Como configurar fluxos de trabalho de validação no Adobe Campaign Classic
seo-title: Como configurar fluxos de trabalho de validação no Adobe Campaign Classic
description: Saiba como configurar diferentes fluxos de trabalho de validação de aprovação.
seo-description: Este vídeo explica como configurar e usar um template do delivery no ACCAadobe Campaign oferece várias opções para que os profissionais de marketing revisem e forneçam conteúdo do delivery, direcionamento da campanha, extração de dados e aprovações de orçamento. Este tutorial explica como configurar diferentes workflows de validação de aprovação.
uuid: fdeb7aef-95aa-4bc1-9c51-2eb7ce802107
discoiquuid: 29abc57d-c359-472d-817a-0671818894f0
feature: Fluxos de trabalho, Aprovações
kt: KT-1566
doc-type: feature video
activity: setup
team: TM
role: Business Practitioner
level: Experienced
exl-id: 34fbb91d-ae99-497c-872e-55ce2e6ea2aa
source-git-commit: 3757eaf573dab5139bad084b664475c6a7de4b02
workflow-type: tm+mt
source-wordcount: '335'
ht-degree: 0%

---

# Como configurar fluxos de trabalho de validação no Adobe Campaign Classic

O Adobe Campaign oferece várias opções para que os profissionais de marketing revisem e forneçam conteúdo de entrega, direcionamento da campanha, extração de dados e aprovações de orçamento.

Este tutorial explica como configurar diferentes workflows de validação de aprovação.

## Pré-requisito {#prerequisite}

Antes de ativar as etapas de aprovação, a equipe de marketing deve definir revisores individuais:

* A função de revisor da Adobe Campaign em uma atividade de aprovação pode ser um único revisor (Operador) ou um grupo de revisores (função Operador).
* Os revisores e os grupos de revisores devem ser configurados anteriormente no Adobe Campaign por uma função de Administrador. Isso permite que os desenvolvedores de campanha selecionem os revisores como aprovadores em uma campanha ou delivery.

## Configuração de aprovações para campanhas {#configuring-approvals-for-campaigns}

Se você tiver o mesmo conjunto de revisores para todos os deliveries no workflow da campanha, você aproveitaria as funcionalidades de aprovação [!DNL Campaign]. Ao configurar aprovações e revisores no nível da campanha, as tarefas de aprovação e os revisores serão encaminhados para cada atividade de delivery do seu workflow, uma vez que o workflow for executado.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Configuração de aprovações para deliveries {#configuring-approvals-for-deliveries}

Você também pode configurar aprovações em um nível de delivery. Se as etapas de aprovação de delivery e os revisores forem diferentes das etapas de aprovação da campanha e dos revisores, as configurações de delivery substituirão as configurações da campanha.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Configurar uma atividade de aprovação {#configuring-an-approval-activity}

Diferente das aprovações de delivery ou campanha, a atividade de aprovação permite criar um processo de aprovação em um workflow. Dessa forma, a lógica de seleção de target pode ser aprovada antes que o delivery seja iniciado. Ela também permite a aprovação em vários níveis no fluxo de trabalho, se necessário.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

Para obter mais informações, consulte a [Documentação de aprovação](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)
