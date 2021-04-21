---
title: Solução de problemas do Painel de controle do Campaign
description: O Painel de controle do Campaign permite monitorar e gerenciar o armazenamento SFTP por instância e endereços IP de lista de permissões.
feature: Painel de controle do Campaign
kt: 2938
doc-type: article
activity: use
team: PM
role: Administrator
level: Experienced
original-url: https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/administrating/control-panel-acc/trouble-shooting.html
exl-id: 016e8b77-20df-4ca5-b5e7-fe2f3e7ba7a3
translation-type: tm+mt
source-git-commit: 137d1e0c36d038f3fb8a4742bafef6fbac96f41d
workflow-type: tm+mt
source-wordcount: '341'
ht-degree: 100%

---

# Resolução de problemas do [!UICONTROL Control Panel]

## Login e página inicial

### Sintoma: não é possível fazer login na Experience Cloud

**O que fazer:**
O usuário precisa localizar a ID organizacional IMS (xxx). O administrador precisa adicionar o usuário ao perfil de produto &quot;Campaign-xxx-Admins&quot; para cada instância que será gerenciada. Ainda que o usuário seja um administrador de todas as instâncias, será necessário adicioná-lo como usuário.

### Sintoma: os links na página inicial da Experience Cloud para acessar o [!UICONTROL Control Panel] não aparecem para um usuário

**Causa:**
Os usuários não verão os links até que sejam adicionados como usuários ao Perfil do produto _Campanha-xxx-Administradores/Admin_.

**O que fazer:**
O administrador precisa adicionar o usuário ao perfil do produto _Campaign-xxx-Admins_ para cada instância que deseja gerenciar. Se o usuário for um administrador de todas as instâncias, talvez ainda seja necessário adicioná-lo como &quot;usuário&quot;.

### Sintoma: uma instância não está listada no [!UICONTROL Control Panel]

**Causa:**
O mais provável é que o usuário precise ser adicionado como um Perfil de produto “usuário” _Campaign-xxx-Administrators/Admin_ para a instância que estiver ausente

**O que fazer:**
O administrador precisa adicionar o usuário ao perfil do produto _Campaign-xxx-Admins_ para cada instância que deseja gerenciar. Ainda que o usuário seja um administrador de todas as instâncias, pode ser necessário adicioná-lo como &quot;usuário&quot;.

### Vídeos úteis

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Verificar IMS Org ID (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Como adicionar um administrador aos administradores do perfil do produto para utilizar o [!UICONTROL Control panel] (01:03 min)*

### Documentação útil

* [Conheça o Painel de controle do Campaign](https://helpx.adobe.com/br/campaign/kb/control-panel-overview.html)
* [Gerenciamento de permissões para o [!UICONTROL Control Panel]](https://helpx.adobe.com/br/campaign/kb/control-panel-access.html)

## Estabelecer conexão com o servidor SFTP (cliente ou API)

A conexão com servidores SFTP requer:

* [!UICONTROL Allow listing] o endereço IP a partir do qual você está se conectando ao servidor SFTP
* Par de chave privada/pública que precisa ser registrado com o Adobe Campaign
* Se você se conectar diretamente ao servidor SFTP, também precisará do software cliente SFTP

### Documentação útil {#helpful-docs}

* [Fazer logon no servidor SFTP](https://helpx.adobe.com/br/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)
