---
title: Painel de controle do Campaign
seo-title: Painel de controle do Campaign
description: O Painel de controle do Campaign permite que você monitore e gerencie seu armazenamento SFTP por instância e endereços IP de lista de permissões.
seo-description: O Painel de controle do Campaign permite que você monitore e gerencie seu armazenamento SFTP por instância e endereços IP de lista de permissões.
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: 37c36a52fb6fc7a5ccfe5d82dc9a32397b9a7d89
workflow-type: tm+mt
source-wordcount: '441'
ht-degree: 6%

---


# [!UICONTROL Control Panel]

>[!NOTE]
>
>Os termos &quot;[!UICONTROL whitelist]&quot; e &quot;[!UICONTROL blacklist]&quot; foram substituídos pelos termos &quot;[!UICONTROL allow list]&quot; e &quot;[!UICONTROL block list]&quot;na documentação do Adobe Campaign.
>Algumas ocorrências desses termos ainda podem existir na interface do usuário do produto, nomes de opções, código interno, bem como nos vídeos de tutoriais. Eles serão substituídos em versões futuras do Painel de controle do Campaign.

O [!UICONTROL Control Panel] permite que os administradores de Adobe Campaign monitorem os principais ativos e executem tarefas administrativas, como gerenciar o armazenamento SFTP por instância ou endereços [!UICONTROL allow list] IP.

## Acesso [!UICONTROL Control Panel]

Para acessar o Painel de controle do Campaign, acesse a página inicial do Experience Cloud: [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com):

* **[!UICONTROL Experience Cloud Home]** > **[!UICONTROL Quick Access]**

   ou
* **[!UICONTROL Experience Cloud Home]**  > [!UICONTROL Solution picker]: **Campanha** > **[!UICONTROL Control Panel]cartão **

   ou

* Diretamente do URL: [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## Pré-requisitos

Antes de começar, conclua os seguintes pré-requisitos:

### Confirmar [!DNL IMS Org ID]

Você precisa conhecer o seu [!DNL IMS org ID]. O vídeo a seguir descreve onde você pode pesquisar o da sua instância [!DNL IMS org ID].

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Verificação[!DNL IMS Org ID](00:26 min)*

### Direitos do administrador

Os direitos de administrador são necessários para acessar o [!UICONTROL Control Panel].
O vídeo a seguir explica como adicionar um administrador a uma instância de Campanha

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Como adicionar um administrador ao perfil &quot;[!UICONTROL Administrators]&quot; do produto para poder usar[!UICONTROL Control Panel](01:03 min)*

## [!UICONTROL Control Panel] tutoriais

* **Gerenciamento de servidores SFTP**

   *Saiba como monitorar a capacidade do servidor, os endereços IP e[!UICONTROL allow list]adicionar chaves SSH*

   * [Monitorando a capacidade do servidor, permitindo a listagem de endereços IP e a adição de chaves SSH](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [Gerando uma chave SSH](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [Conexão com um servidor SFTP](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[Delegar subdomínios](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *Saiba como delegar totalmente um subdomínio para[!UICONTROL Adobe Campaign]*

* **[Adicionar certificados SSL](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *Saiba como você pode adicionar certificados SSL para proteger seus subdomínios usando o Painel de controle do Campaign.*

* **[Gerenciamento de certificados SSL](/help/acc/monitoring-campaign-classic/control-panel/managing-ssl-certificates.md)**

   *Saiba como você pode visualização o status dos certificados SSL de seus subdomínios, bem como solicitar renovações.*

* **[Adicionar permissões de URL](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *como adicionar alguns URLs externos à lista de URLs autorizados, para que sua instância possa se conectar a eles.*

* **[Lista de permissões de IP para acesso de instância](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *Saiba como configurar novas conexões com suas instâncias por intervalos de endereços[!UICONTROL allow listing]IP.*

* **[Gerenciamento de registros TXT do Google](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *Saiba como adicionar um registro de verificação de[!DNL Google TXT]site a todos os seus subdomínios usados para enviar emails para[!DNL GMAIL]endereços pelo[!UICONTROL Campaign Control Panel].*

* **Gerenciamento de chaves GPG**

   *Saiba como gerar e instalar um par de chaves públicas/privadas em uma instância de Campanha especificada para a criptografia de dados de saída, bem como importar e instalar uma chave pública em uma instância de Campanha para a descriptografia de dados de entrada:*

   * [Geração e instalação de chaves GPG para criptografia de dados](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [Uso de uma chave GPG para criptografar dados](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [Descriptografia de dados](./gpg-key-management/decrypting-data.md)

* **[Resolução de problemas do painel de controle](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *Entenda como solucionar problemas do[!UICONTROL Control Panel]*

## Recursos adicionais

* [Centro de ajuda do Painel de controle do Campaign](https://docs.adobe.com/content/help/pt-BR/control-panel/using/control-panel-home.translate.html)