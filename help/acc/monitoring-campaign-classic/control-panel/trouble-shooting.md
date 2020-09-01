---
title: Panel de control de Campaign de Solución de problemas
description: El panel de control de Campaign le permite monitorizar y administrar su almacenamiento SFTP por instancia y direcciones IP de lista de permitidos.
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
ht-degree: 100%

---


# Solución de problemas [!UICONTROL Control Panel]

## Inicio de sesión y página principal

### Síntoma: no se puede iniciar sesión en Experience Cloud

**Qué hacer:**
el usuario debe localizar su identificador de organización de IMS (xxx). El administrador debe añadir el usuario al Perfil de productos &quot;Campaign-xxx-administradores&quot; para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, es posible que tenga que añadirse como usuario.

### Síntoma: los vínculos de la página principal de Experience Cloud para acceder a [!UICONTROL Control Panel] no aparecen para un usuario.

**Causa:**
los usuarios no verán los vínculos hasta que se añadan como usuarios al Perfil de productos _Campaign-xxx-Administradores/Admin_.

**Qué hacer:**
El administrador debe añadir el usuario al Perfil de productos _Campaign-xxx-administradores_ para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, es posible que tenga que añadirse como &quot;usuario&quot;.

### Síntoma: una instancia no aparece en la lista de [!UICONTROL Control Panel]

**Causa:**
es muy probable que el usuario deba añadirse como &quot;usuario&quot; al Perfil de productos _Campaign-xxx-administradores/admin_ para la instancia que falta.

**Qué hacer:**
El administrador debe añadir el usuario al Perfil de productos _Campaign-xxx-administradores_ para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, es posible que tenga que añadirse como &quot;usuario&quot;.

### Vídeos útiles

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Comprobación del identificador de organización de IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Cómo añadir un administrador a los administradores de perfil de productos para poder utilizarlo[!UICONTROL Control panel] (1:03 min)*

### Documentación útil

* [Descubra el panel de control de Campaign](https://helpx.adobe.com/es/campaign/kb/control-panel-overview.html)
* [Administración de permisos para [!UICONTROL Control Panel]](https://helpx.adobe.com/es/campaign/kb/control-panel-access.html)

## Establecimiento de la conexión con el servidor SFTP (cliente o API)

La conexión a los servidores SFTP requiere lo siguiente:

* [!UICONTROL Allow listing] la dirección IP desde la que se está conectando al servidor SFTP.
* Par de clave pública/privada que debe registrarse con Adobe Campaign.
* Si se conecta directamente al servidor SFTP, también necesitará el software de cliente SFTP.

### Documentación útil

* [Inicio de sesión en el servidor SFTP](https://helpx.adobe.com/es/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)

