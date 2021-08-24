---
title: Panel de control de Campaign de Solución de problemas
description: El Panel de control de Campaign le permite monitorizar y administrar su almacenamiento SFTP por instancia y lista de permitidos de direcciones IP.
feature: Panel de control de Campaign
kt: 2938
doc-type: article
activity: use
team: PM
source-git-commit: 8910430585bdaa0db076db9c34b34798f649d39c
workflow-type: tm+mt
source-wordcount: '332'
ht-degree: 42%

---


# Solución de problemas [!UICONTROL Control Panel]

## Inicio de sesión y página principal

### Síntoma: No se puede iniciar sesión en el Experience Cloud

**Qué hacer:**
El usuario debe localizar su ID de organización de IMS (xxx). El administrador debe agregar el usuario al Perfil de producto &quot;Campaign-xxx-administradores&quot; para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, debe añadirse como usuario.

### Síntoma: los vínculos de la página principal de Experience Cloud para acceder a [!UICONTROL Control Panel] no aparecen para un usuario.

**Causa:**
los usuarios no verán los vínculos hasta que se añadan como usuarios al Perfil de productos _Campaign-xxx-Administradores/Admin_.

**Qué hacer:**
El administrador debe agregar el usuario al Perfil de productos  _Campaign-xxx-_  Administradores para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, debe añadirse como &quot;usuario&quot;.

### Síntoma: una instancia no aparece en la lista de [!UICONTROL Control Panel]

**Causa:**
es muy probable que el usuario deba agregarse como un perfil de producto de &quot;usuario&quot;  _Campaign-xxx-Administradores/_ Admin para la instancia que falta

**Qué hacer:**
El administrador debe agregar el usuario al Perfil de productos  _Campaign-xxx-_  Administradores para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, debe añadirse como &quot;usuario&quot;.

### Vídeos útiles

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Comprobación del identificador de organización de IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Cómo añadir un administrador a los administradores de perfil de productos para poder utilizarlo [!UICONTROL Control panel] (1:03 min)*

### Documentación útil

* [Descubra el panel de control de Campaign](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=es)
* [Administración de permisos para [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Establecimiento de la conexión con el servidor SFTP (cliente o API)

La conexión a los servidores SFTP requiere lo siguiente:

* [!UICONTROL Allow listing] la dirección IP desde la que se está conectando al servidor SFTP.
* Par de clave pública/privada que debe registrarse con Adobe Campaign
* Si se conecta directamente al servidor SFTP, necesitará el software de cliente SFTP

### Documentación útil {#helpful-docs}

* [Inicio de sesión en el servidor SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

