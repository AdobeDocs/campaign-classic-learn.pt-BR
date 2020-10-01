---
title: Painel de controle do Campaign
seo-title: Painel de controle do Campaign
description: O Painel de controle do Campaign permite monitorar e gerenciar o armazenamento SFTP por instância e endereços IP de lista de permissões.
seo-description: O Painel de controle do Campaign permite monitorar e gerenciar o armazenamento SFTP por instância e endereços IP de lista de permissões.
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: 838c617ca163a09fcb57b7b4706433e98869bc3d
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---


# [!UICONTROL Control Panel]

>[!NOTE]
>
>Os termos &quot;[!UICONTROL whitelist]&quot; e &quot;[!UICONTROL blacklist]&quot; foram substituídos pelos termos &quot;[!UICONTROL allow list]&quot; e &quot;[!UICONTROL block list]&quot;na documentação do Adobe Campaign.
>Algumas ocorrências desses termos ainda podem existir na interface do usuário do produto, nomes de opções e código interno, bem como nos vídeos de tutoriais. Eles serão substituídos em versões futuras do Painel de controle do Campaign.

O [!UICONTROL Control Panel] permite que os administradores do Adobe Campaign monitorem os principais ativos e executem tarefas administrativas, como gerenciar o armazenamento SFTP por instância ou endereços IP do [!UICONTROL allow list].

## Acesso ao [!UICONTROL Control Panel]

Para acessar o Painel de controle do Campaign, vá até a página inicial da Experience Cloud: [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com):

* **[!UICONTROL Experience Cloud Home]** > **[!UICONTROL Quick Access]**

   ou
* **[!UICONTROL Experience Cloud Home]**  > [!UICONTROL Solution picker]: **Campaign** > **[!UICONTROL Control Panel]card**

   ou

* Diretamente pelo URL: [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## Pré-requisitos

Antes de começar, conclua os seguintes pré-requisitos:

### Confirmar o [!DNL IMS Org ID]

Você precisa conhecer o seu [!DNL IMS org ID]. O vídeo a seguir descreve onde você pode pesquisar o [!DNL IMS org ID] da sua instância.

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Verificação[!DNL IMS Org ID](00:26 min)*

### Direitos do administrador

Os direitos de administrador são necessários para acessar o [!UICONTROL Control Panel].
O vídeo a seguir explica como adicionar um administrador a uma instância do Campaign

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Como adicionar um administrador ao perfil &quot;[!UICONTROL Administrators]&quot; do produto para usar[!UICONTROL Control Panel](01:03 min)*

## [!UICONTROL Control Panel] tutoriais

* **Gerenciar servidores SFTP**

   *Saiba como monitorar a capacidade do servidor, endereços IP[!UICONTROL allow list]e adicionar chaves SSH*

   * [Monitorar a capacidade do servidor, permitindo a listagem de endereços IP e a adição de chaves SSH](/help/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [Gerar uma chave SSH](/help/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [Conectar um servidor SFTP](/help/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[Delegar subdomínios](/help/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *Saiba como delegar totalmente um subdomínio para[!UICONTROL Adobe Campaign]*

* **[Adicionar certificados SSL](/help/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *Saiba como adicionar certificados SSL para proteger seus subdomínios usando o Painel de controle do Campaign.*

* **[Adicionar permissões de URL](/help/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *como adicionar URLs externos à lista de URLs autorizados para que sua instância possa se conectar a eles.*

* **[Adicionar endereços IP ao lista de permissões](/help/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *Saiba como configurar novas conexões com suas instâncias por intervalos de endereços de IP do[!UICONTROL allow listing].*

* **[Gerenciamento de registros TXT do Google](/help/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *Saiba como adicionar um registro de verificação de site[!DNL Google TXT]a todos os subdomínios usados para enviar emails para endereços[!DNL GMAIL]pelo[!UICONTROL Campaign Control Panel].*

* **Gerenciamento de chaves GPG**

   *Saiba como gerar e instalar um par de chaves públicas/privadas em uma instância do Campaign especificada para criptografar dados de saída, bem como importar e instalar uma chave pública em uma instância do Campaign para descriptografar dados de entrada:*

   * [Gerar e instalar chaves GPG para criptografia de dados](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [Usar uma chave GPG para criptografar dados](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [Descriptografar dados](./gpg-key-management/decrypting-data.md)

* **[Solução de problemas do Painel de controle do Campaign](/help/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *Saiba como solucionar problemas do[!UICONTROL Control Panel]*

## Recursos adicionais

* [Centro de ajuda do Painel de controle do Campaign](https://docs.adobe.com/content/help/pt-BR/control-panel/using/control-panel-home.translate.html)