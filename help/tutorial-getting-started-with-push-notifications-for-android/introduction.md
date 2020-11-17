---
title: Introdução ao tutorial com notificações por push para Android - Introdução
description: Este tutorial o guiará pelas etapas envolvidas no envio de notificações por push do Adobe Campaign e no recebimento dessas notificações no aplicativo Android.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 217b0ec1b6f5c5e17009f1103d69726aa57dcaa4
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 6%

---


# Introdução ao tutorial com notificações por push para Android - Introdução

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android ]mobile devices.

Este tutorial o guiará pelas etapas envolvidas no envio de [!DNL push] notificações da Adobe Campaign para um [!DNL Android] aplicativo.

## Pré-requisitos

Antes de começar, você precisará atender aos seguintes pré-requisitos

1) Aplicativo móvelEste tutorial não cobre as etapas detalhadas necessárias para configurar o aplicativo móvel. Você precisará de um aplicativo **[!DNL Android]móvel com o[!DNL Campaign SDK]** integrado.

   * Você pode encontrar uma descrição detalhada das etapas necessárias na [integração do SDK de Campanha ao aplicativo](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)móvel.

   * Você também pode usar o SDK Experience Platform Mobile. Para obter mais informações, assista ao vídeo do tutorial [Configurar o Canal Mobile SDK](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html) .

2) Pacote do Canal do aplicativo móvel instalado

   Será necessário ter o pacote de canal do aplicativo móvel instalado em sua instância. O vídeo a seguir explica como verificar se o canal do aplicativo móvel está instalado em sua instância e, se não estiver, como instalá-lo.

   [!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Tutorial

Gostaríamos de enviar uma notificação por push promocional personalizada para os assinantes do aplicativo Neotrip [!DNL Android] para dispositivos móveis. O aplicativo Neotrip está configurado com o SDK de Campanha e verificamos se o canal do aplicativo móvel está ativado em nossa instância de Campanha.

As seguintes etapas de configuração são obrigatórias:

### Etapa 1: Estenda o schema de subscrição do aplicativo para personalizar notificações por push

Como gostaríamos de personalizar a notificação por push, primeiro [estenderemos o schema](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) de subscrição do aplicativo para armazenar os valores de personalização que recebemos do aplicativo quando o usuário se inscreve no serviço.

### Etapa 2: Configure o serviço Android e crie o aplicativo móvel no Campaign

Em seguida, precisaremos [configurar o serviço Android e criar o aplicativo móvel na Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). Nesta etapa, definiremos o aplicativo Neotrip como o público alvo para a notificação por push.

### Etapa 3: Configurar e enviar a notificação por push

Em seguida, estamos prontos para [configurar e enviar a notificação](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)por push.

## Start do tutorial

**[Etapa 1: Estenda a schema da subscrição do aplicativo](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)**
