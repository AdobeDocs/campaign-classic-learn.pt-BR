---
title: Adicionar certificados SSL
description: Saiba como adicionar certificados SSL para proteger seus subdomínios.
feature: Painel de controle do Campaign
kt: 4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Administrator
level: Experienced
original-url: https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/administrating/control-panel-acc/adding-ssl-certificates.html
exl-id: 9ba485fb-be26-4f3c-a9de-844fecaec20d
translation-type: tm+mt
source-git-commit: 137d1e0c36d038f3fb8a4742bafef6fbac96f41d
workflow-type: tm+mt
source-wordcount: '212'
ht-degree: 93%

---

# Adicionar certificados SSL

O Adobe Campaign [!UICONTROL Control Panel] permite adicionar certificados SSL para proteger seus subdomínios.

## Acesso ao gerenciamento de subdomínio do Painel de controle do Campaign

Para acessar o gerenciamento de subdomínio no Painel de controle do Campaign, acesse:

* [Experience Cloud Home](https://experience.adobe.com/#/home) > Solution picker: **[!DNL Campaign]** > **[!UICONTROL Control Panel]** card > **[!UICONTROL Subdomains & Certificates]** card

   ou
* Diretamente do URL: [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## Etapas para adicionar certificados SSL

A adição de certificados SSL requer três etapas:

### 1. Gerar solicitações de assinatura de certificado

A solicitação de assinatura de certificado (CSR) é necessária para a aquisição de um certificado SSL. Deve ser gerado para a instância e os subdomínios que você pretende proteger.

O vídeo abaixo descreve como gerar uma solicitação de assinatura de certificado no Painel de controle do Campaign.

>[!VIDEO](https://video.tv.adobe.com/v/31317?quality=12)

*Gerar solicitações de assinatura de certificado (02:36 min)*

### 2. Adquirir o certificado SSL

Após obter o CSR, será necessário comprar o certificado SSL de uma autoridade de certificação aprovada pela organização.

### 3. Instalar os certificados SSL

Após obter o certificado SSL, será necessário instalá-lo para os subdomínios que você pretende proteger.

O vídeo abaixo explica como instalar certificados SSL em [!UICONTROL Control Panel].

>[!VIDEO](https://video.tv.adobe.com/v/31166?quality=12)

*Instalar certificados SSL (01:25 min)*

## Recursos adicionais

* [Delegação total de subdomínio (vídeo)](./subdomain-delegation.md)
* [Subdomínios e certificados (documentação)](https://docs.adobe.com/content/help/pt-BR/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html)
