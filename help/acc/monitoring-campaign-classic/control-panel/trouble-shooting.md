---
title: Panel de control de Campaign de grabación de problemas
description: El Panel de control de Campaign le permite supervisar y administrar su almacenamiento SFTP por instancia y direcciones IP de lista de permitidos.
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


# Solución de problemas [!UICONTROL Control Panel]

## Inicio de sesión y página principal

### Síntoma: No se puede iniciar sesión en el Experience Cloud

**Qué hacer:**
El usuario debe localizar su identificador de organización de IMS (xxx). El administrador debe agregar el usuario al Perfil de productos &quot;Campaña-xxx-administradores&quot; para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, es posible que tenga que agregarse como usuario.

### Síntoma: Los vínculos de la página principal del Experience Cloud para acceder [!UICONTROL Control Panel] no aparecen para un usuario

**Causa:**
Los usuarios no verán los vínculos hasta que se agreguen como usuarios a la _Campaña de Perfil de productos: xxx-Administradores/Administradores_.

**Qué hacer:**
El administrador debe agregar el usuario a la _Campaña Product Perfil-xxx-Admins_ para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, es posible que tenga que agregarse como &quot;usuarios&quot;.

### Síntoma: Una instancia no aparece en la lista de [!UICONTROL Control Panel]

**Causa:**
Es muy probable que el usuario deba agregarse como &quot;usuario&quot; _Campaña de Perfil de productos: xxx-administradores/administradores_ para la instancia que falta

**Qué hacer:**
El administrador debe agregar el usuario a la _Campaña Product Perfil-xxx-Admins_ para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, es posible que tenga que agregarse como &quot;usuarios&quot;.

### Vídeos útiles

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Comprobación del identificador de organización de IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Cómo agregar un administrador a los administradores de perfil de productos para poder utilizarlo[!UICONTROL Control panel](01:03 min)*

### Documentación útil

* [Descubra el Panel de control de Campaign](https://helpx.adobe.com/campaign/kb/control-panel-overview.html)
* [Administración de permisos para [!UICONTROL Control Panel]](https://helpx.adobe.com/campaign/kb/control-panel-access.html)

## Establecimiento de la conexión con el servidor SFTP (cliente o API)

La conexión a los servidores SFTP requiere:

* [!UICONTROL Allow listing] la dirección IP desde la que se conecta al servidor SFTP
* Par de clave pública/privada que debe registrarse con Adobe Campaign
* Si se conecta directamente al servidor SFTP, también necesitará el software de cliente SFTP

### Documentación útil

* [Inicio de sesión en el servidor SFTP](https://helpx.adobe.com/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)

