---
title: Introdução ao tutorial
description: Este tutorial o guiará pelas etapas envolvidas no envio de notificações por push do Adobe Campaign e no recebimento dessas notificações no aplicativo Android.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 9b26dfd30e60c3e12c52e4318a853498af186b4a
workflow-type: tm+mt
source-wordcount: '353'
ht-degree: 9%

---


# Introdução ao tutorial

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android] mobile devices. Este tutorial o guiará pelas etapas envolvidas no envio de [!DNL push] notificações da Adobe Campaign para um [!DNL Android] aplicativo.

## Pré-requisitos

Antes de começar, você precisará ter o seguinte:

1) **Aplicativo Android Mobile**

   Este tutorial não cobre as etapas detalhadas necessárias para configurar o aplicativo móvel. Será necessário ter um aplicativo **[!DNL Android]móvel com o [!DNL Campaign SDK] integrado**.

   Você pode encontrar uma descrição detalhada das etapas necessárias na documentação do produto:

   [Integração do SDK do Campaign no aplicativo móvel](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)

   Você também pode usar o SDK Experience Platform Mobile. Para obter mais informações, assista ao vídeo do tutorial:

   [Configure o Canal Push usando o SDK Experience Platform Mobile](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html)

2) **[!DNL Mobile App channel]pacote instalado**

   O [!DNL Mobile App channel] pacote precisa ser instalado na sua [!DNL Campaign] instância. O vídeo a seguir explica como verificar se o [!DNL Mobile App channel] está instalado na sua instância e, se não estiver, como instalá-lo.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Visão geral do tutorial

Gostaríamos de enviar uma [!DNL push] notificação promocional personalizada aos assinantes do aplicativo [!DNL Neotrip][!DNL Android] móvel. O [!DNL Neotrip] aplicativo está configurado com o [!DNL Campaign SDK] e verificamos se o [!DNL Mobile App channel] está ativado em nossa [!DNL Campaign] instância.

As seguintes etapas de configuração são obrigatórias:

### Etapa 1: Estenda o schema de subscrição do aplicativo para personalizar [!DNL push] notificações

Como gostaríamos de personalizar a [!DNL push] notificação, primeiro [estenderemos o schema](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) de subscrição do aplicativo para armazenar os valores de personalização que recebemos do aplicativo quando o usuário se inscreve no serviço.

### Etapa 2: Configure o serviço Android e crie o aplicativo móvel no Campaign

Em seguida, precisaremos [configurar o serviço Android e criar o aplicativo móvel no Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). Nesta etapa, definiremos o [!DNL Neotrip] aplicativo como o público alvo para a notificação por push.

### Etapa 3: Configurar e enviar a notificação por push

Em seguida, estamos prontos para [configurar e enviar a notificação](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)por push.

## Start do tutorial

Etapa 1: [Estenda a schema da subscrição do aplicativo](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
