---
title: Painel de controle do Campaign de solução de problemas
description: O Painel de controle do Campaign permite que você monitore e gerencie seu armazenamento SFTP por instância e endereços IP de lista de permissões.
feature: Control Panel
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
translation-type: tm+mt
source-git-commit: b2820c65a88d25f9b7a4ed5005cd5083463e000a
workflow-type: tm+mt
source-wordcount: '339'
ht-degree: 1%

---


# Resolução de problemas [!UICONTROL Control Panel]

## Login e página inicial

### Sintoma: Não é possível fazer login no Experience Cloud

**O que fazer:**
O usuário precisa localizar a ID organizacional IMS (xxx). O administrador precisa adicionar o usuário ao Perfil de produto &quot;Campanha-xxx-Admins&quot; para cada instância que ele deseja gerenciar. Se o usuário for um administrador de todas as instâncias, ainda será necessário adicioná-lo como usuários.

### Sintoma: Os links na página inicial do Experience Cloud para acesso [!UICONTROL Control Panel] não aparecem para um usuário

**Causa:**
Os usuários não verão os links até que sejam adicionados como usuários ao Perfil de produto &quot;Campanha-xxx-Administradores/Admin&quot;

**O que fazer:**
O administrador precisa adicionar o usuário ao Perfil de produto &quot;Campanha-xxx-Admins&quot; para cada instância que ele deseja gerenciar. Se o usuário for um administrador de todas as instâncias, talvez ainda seja necessário adicioná-lo como &quot;usuários&quot;.

### Sintoma: Uma Instância não está listada no [!UICONTROL Control Panel]

**Causa:**
O usuário mais provável precisa ser adicionado como um Perfil de produto &quot;usuário&quot; &quot;Campanha-xxx-Administradores/Administrador&quot; para a instância que está ausente

**O que fazer:**
O administrador precisa adicionar o usuário ao Perfil de produto &quot;Campanha-xxx-Admins&quot; para cada instância que ele deseja gerenciar. Se o usuário for um administrador de todas as instâncias, talvez ainda seja necessário adicioná-lo como &quot;usuários&quot;.

### Vídeos úteis

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Verificar ID de Org IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Como adicionar um administrador aos administradores do perfil do produto para poder usar[!UICONTROL Control panel](01:03 min)*

### Documentação útil

* [Descubra o Painel de controle do Campaign](https://helpx.adobe.com/campaign/kb/control-panel-overview.html)
* [Gerenciamento de permissões para o [!UICONTROL Control Panel]](https://helpx.adobe.com/campaign/kb/control-panel-access.html)

## Estabelecendo conexão com o servidor SFTP (cliente ou API)

A conexão com servidores SFTP requer:

* [!UICONTROL Allow listing] o endereço IP do qual você está se conectando ao servidor SFTP
* Par de chave privada/pública que precisa ser registrado com Adobe Campaign
* Se você se conectar diretamente ao servidor SFTP, também precisará do software cliente SFTP

### Documentação útil

* [Fazer logon no servidor SFTP](https://helpx.adobe.com/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)

