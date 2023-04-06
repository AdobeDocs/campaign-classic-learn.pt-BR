---
title: Introdução a notificações por push para Android – Introdução
description: Este tutorial guiará você pelas etapas envolvidas no envio de notificações por push do Adobe Campaign e no recebimento dessas notificações no aplicativo Android.
feature: Push
kt: 6438
doc-type: article
activity: setup
team: TM
role: Admin, Developer
level: Experienced
recommendations: noDisplay
exl-id: 291c2e3a-c126-439d-9753-06a4091bbda0
source-git-commit: 13f7ab2dd41216a603a22f181dc4d06302c5918a
workflow-type: ht
source-wordcount: '365'
ht-degree: 100%

---

# Introdução a notificações por push para Android – Introdução

O Adobe Campaign permite enviar notificações [!DNL push] personalizadas e segmentadas para [!DNL iOS] e dispositivos móveis [!DNL Android]. Este tutorial guiará você pelas etapas relativas ao envio de notificações [!DNL push] do Adobe Campaign para um aplicativo [!DNL Android].

## Pré-requisitos

Antes de começar, você precisará ter o seguinte:

1) **Aplicativo para dispositivos móveis Android**

   Este tutorial não apresenta as etapas detalhadas necessárias para configurar o aplicativo para dispositivos móveis. Você precisará ter um aplicativo para dispositivos móveis **[!DNL Android]com o [!DNL Campaign SDK] integrado**.

   Você pode encontrar uma descrição detalhada das etapas necessárias na documentação do produto:

   [Integração do SDK do Campaign no aplicativo para dispositivos móveis](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=pt-BR)

   Você também pode usar o SDK móvel da Experience Platform. Para obter mais informações, assista ao tutorial em vídeo:

   [Configurar o canal por push usando o SDK móvel da Experience Platform](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html?lang=pt-BR)

2) Pacote **[!DNL Mobile App channel]instalado**

   O pacote [!DNL Mobile App channel] precisa ser instalado na instância [!DNL Campaign]. O vídeo a seguir explica como verificar se o [!DNL Mobile App channel] está instalado em sua instância e como instalá-lo, caso ele ainda não esteja instalado.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12&learn=on)

## Visão geral do tutorial

Gostaríamos de enviar uma notificação promocional personalizada do [!DNL push] aos assinantes do aplicativo para dispositivos móveis [!DNL Neotrip] [!DNL Android]. O aplicativo [!DNL Neotrip] está configurado com [!DNL Campaign SDK] e verificamos que [!DNL Mobile App channel] está ativado em nossa instância [!DNL Campaign].

As seguintes etapas de configuração são obrigatórias:

### Etapa 1: estenda o esquema de assinatura do aplicativo para personalizar notificações do [!DNL push]

Como queremos personalizar a notificação do [!DNL push], primeiro vamos [estender o esquema de assinatura do aplicativo](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) para poder armazenar os valores de personalização que recebemos do aplicativo quando o usuário assina o serviço.

### Passo 2: configure o serviço Android e crie o aplicativo para dispositivos móveis no Campaign

Em seguida, precisaremos [configurar o serviço Android e criar o aplicativo para dispositivos móveis no Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). Nesta etapa, vamos definir o aplicativo [!DNL Neotrip] como público alvo para a notificação por push.

### Etapa 3: configure e envie a notificação por push

Agora podemos [configurar e enviar a notificação por push](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md).

## Iniciar o tutorial

Etapa 1: [estenda o esquema de assinatura do aplicativo](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
