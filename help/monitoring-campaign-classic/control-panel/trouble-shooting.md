---
title: Solução de problemas do Painel de controle do Campaign
description: O Painel de controle do Campaign permite monitorar e gerenciar o armazenamento SFTP por instância e lista de permissões endereços IP de .
feature: Painel de controle do Campaign
kt: 2938
doc-type: article
activity: use
team: PM
source-git-commit: 8910430585bdaa0db076db9c34b34798f649d39c
workflow-type: tm+mt
source-wordcount: '332'
ht-degree: 42%

---


# Resolução de problemas do [!UICONTROL Control Panel]

## Login e página inicial

### Sintoma: Não é possível iniciar sessão no Experience Cloud

**O que fazer:**
O usuário deve localizar a ID organizacional IMS (xxx). O Administrador deve adicionar o usuário ao Perfil de produto &quot;Campaign-xxx-Admins&quot; para cada instância que ele quiser gerenciar. Se o usuário for um administrador de todas as instâncias, ele deverá se adicionar como usuário.

### Sintoma: os links na página inicial da Experience Cloud para acessar o [!UICONTROL Control Panel] não aparecem para um usuário

**Causa:**
Os usuários não verão os links até que sejam adicionados como usuários ao Perfil do produto _Campanha-xxx-Administradores/Admin_.

**O que fazer:**
O Administrador deve adicionar o usuário ao Perfil de produto  _Campaign-xxx-_  Adminspara cada instância que ele quiser gerenciar. Se o usuário for um administrador de todas as instâncias, ele deverá se adicionar como &quot;usuários&quot;.

### Sintoma: uma instância não está listada no [!UICONTROL Control Panel]

**Causa:**
Provavelmente, o usuário deve ser adicionado como um Perfil de Produto &quot;usuário&quot;  _Campaign-xxx-Administrators/_ Adminpara a instância que estiver ausente

**O que fazer:**
O Administrador deve adicionar o usuário ao Perfil de produto  _Campaign-xxx-_  Adminspara cada instância que ele quiser gerenciar. Se o usuário for um administrador de todas as instâncias, ele deverá se adicionar como &quot;usuários&quot;.

### Vídeos úteis

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Verificar IMS Org ID (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Como adicionar um administrador aos administradores do perfil do produto para utilizar o [!UICONTROL Control panel] (01:03 min)*

### Documentação útil

* [Conheça o Painel de controle do Campaign](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=pt-BR)
* [Gerenciamento de permissões para o [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Estabelecer conexão com o servidor SFTP (cliente ou API)

A conexão com servidores SFTP requer:

* [!UICONTROL Allow listing] o endereço IP a partir do qual você está se conectando ao servidor SFTP
* Par de chave privada/pública que deve ser registrado no Adobe Campaign
* Se você se conectar diretamente ao servidor SFTP, precisará de software cliente SFTP

### Documentação útil {#helpful-docs}

* [Fazer logon no servidor SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

