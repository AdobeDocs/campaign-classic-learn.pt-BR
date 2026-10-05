---
title: Solução de problemas do Painel de controle
description: O Painel de controle do Campaign permite monitorar e gerenciar o armazenamento SFTP por instância e incluir na lista de permissões endereços IP.
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
  - id: fd6e6e36-54e4-4f1a-96fc-1a750e400d50
    internal-label: Campaign Classic v7
feature_v2:
  - id: ae9127b0-c11d-467b-903d-a84cef43f6ed
    internal-label: Control Panel
source-git-commit: d4d4654e5b2dee85947373b8dcf139754844b316
workflow-type: tm+mt
source-wordcount: '353'
ht-degree: 67%
---

# Resolução de problemas do [!UICONTROL Control Panel]

## Logon e página inicial

### Sintoma: não é possível fazer logon na Experience Cloud

**O que fazer:**
O usuário deve localizar a ID da organização IMS (xxx). O administrador precisa adicionar o usuário ao perfil de produto &quot;Campaign-xxx-Admins&quot; para cada instância que será gerenciada. Ainda que o usuário seja um administrador de todas as instâncias, será necessário adicioná-lo como usuário.

### Sintoma: os links na página inicial da Experience Cloud para acessar o [!UICONTROL Control Panel] não aparecem para um usuário

**Causa:**
Os usuários não verão os links até que sejam adicionados como usuários ao Perfil de Produto _Campaign-xxx-Administrators/Admin_.

**O que fazer:**
O administrador deve adicionar o usuário ao perfil do produto _Campaign-xxx-Admins_ para cada instância que deseje gerenciar. Se o usuário for um administrador de todas as instâncias, será necessário adicioná-lo como &quot;usuário&quot;.

### Sintoma: uma instância não está listada no [!UICONTROL Control Panel]

**Causa:**
O mais provável é que o usuário precise ser adicionado como um Perfil de Produto &quot;usuário&quot; _Campaign-xxx-Administrators/Admin_ para a instância que estiver ausente

**O que fazer:**
O administrador deve adicionar o usuário ao perfil do produto _Campaign-xxx-Admins_ para cada instância que deseje gerenciar. Se o usuário for um administrador de todas as instâncias, será necessário adicioná-lo como &quot;usuário&quot;.

### Vídeos úteis

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12&learn=on){transcript=true}

*Verificar ID da Organização IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12&learn=on){transcript=true}

*Como adicionar um administrador aos administradores do perfil do produto para utilizar o [!UICONTROL Control panel] (01:03 min)*

### Documentação útil

* [Conheça o Painel de controle](https://experienceleague.adobe.com/pt-br/docs/control-panel/using/control-panel-home)
* [Gerenciando permissões para o [!UICONTROL Control Panel]](https://experienceleague.adobe.com/pt-br/docs/control-panel/using/control-panel-home)

## Estabelecer conexão com o servidor SFTP (cliente ou API)

A conexão com servidores SFTP requer:

* [!UICONTROL Allow listing] o endereço IP a partir do qual você está se conectando ao servidor SFTP
* Par de chave privada/pública que precisa ser registrado com o Adobe Campaign
* Se você se conectar diretamente ao servidor SFTP, precisará do software cliente SFTP

### Documentação útil {#helpful-docs}

* [Logon no servidor SFTP](https://experienceleague.adobe.com/pt-br/docs/control-panel/using/control-panel-home)

