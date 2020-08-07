---
title: Panel de control de Campaign
seo-title: Panel de control de Campaign
description: El Panel de control de Campaign le permite supervisar y administrar su almacenamiento SFTP por instancia y añadir direcciones IP a la lista de permitidos.
seo-description: El Panel de control de Campaign le permite supervisar y administrar su almacenamiento SFTP por instancia y añadir direcciones IP a la lista de permitidos.
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: ca3b7933927914b9965f6f059293041dd1db1da2
workflow-type: tm+mt
source-wordcount: '419'
ht-degree: 76%

---


# [!UICONTROL Control Panel]

>[!NOTE]
>
>Los términos &quot;[!UICONTROL whitelist]&quot; y &quot;[!UICONTROL blacklist]&quot; se han sustituido por &quot;[!UICONTROL allow list]&quot; y &quot;[!UICONTROL block list]&quot; en la documentación de Adobe Campaign.
>Algunas incidencias de estos términos pueden seguir existiendo en la interfaz de usuario del producto, los nombres de opciones, el código interno y los vídeos de tutoriales. Se reemplazarán en próximas versiones del Panel de control de Campaign.

El [!UICONTROL Control Panel] permite a los administradores de Adobe Campaign supervisar los recursos clave y realizar tareas administrativas, como administrar el almacenamiento SFTP por instancia o por direcciones IP en [!UICONTROL allow list].

## Acceso al [!UICONTROL Control Panel]

Para acceder al Panel de control de Campaign, vaya a la página principal de Experience Cloud: [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com):

* **[!UICONTROL Experience Cloud Home]** > **[!UICONTROL Quick Access]**

   o
* **[!UICONTROL Experience Cloud Home]**  > [!UICONTROL Solution picker]: **Campaign** > Tarjeta de **[!UICONTROL Control Panel]**

   o

* Directamente desde la dirección URL: [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## Requisitos previos

Antes de comenzar, complete los siguientes requisitos previos:

### Confirme [!DNL IMS Org ID]

Tiene que saber su [!DNL IMS org ID]. El siguiente vídeo describe dónde puede buscar la instancia de [!DNL IMS org ID].

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Comprobación de[!DNL IMS Org ID](00:26 min)*

### Derechos de administrador

Se requieren derechos de administrador para acceder al [!UICONTROL Control Panel].
En el siguiente vídeo se explica cómo agregar un administrador a una instancia de Campaign

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Adición de un administrador al perfil del producto &quot;[!UICONTROL Administrators]&quot; para utilizarlo[!UICONTROL Control Panel](01:03 min)*

## [!UICONTROL Control Panel] tutoriales

* **Administración de servidores SFTP**

   *Obtenga información sobre cómo supervisar la capacidad del servidor, las direcciones[!UICONTROL allow list]IP y agregar claves SSH*

   * [Monitorización de la capacidad del servidor, admisión de direcciones IP y adición de claves SSH](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [Generación de una clave SSH](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [Conexión a un servidor SFTP](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[Delegación de subdominios](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *Aprenda a delegar completamente un subdominio a[!UICONTROL Adobe Campaign]*

* **[Adición de certificados SSL](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *Descubra cómo puede agregar certificados SSL para proteger los subdominios mediante Panel de control de Campaign.*

* **[Añadir permisos de URL](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *cómo agregar algunas direcciones URL externas a la lista de direcciones URL autorizadas para que la instancia pueda conectarse a ellas.*

* **[Listado de IP permitidas para acceso a instancias](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *Obtenga información sobre cómo configurar nuevas conexiones a las instancias según los intervalos de direcciones[!UICONTROL allow listing]IP.*

* **[Administración de registros TXT de Google](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *Obtenga información sobre cómo agregar un registro de verificación del[!DNL Google TXT]sitio a todos los subdominios utilizados para enviar correos electrónicos a[!DNL GMAIL]las direcciones a través del[!UICONTROL Campaign Control Panel].*

* **Administración de claves GPG**

   *Obtenga información sobre cómo generar e instalar un par de claves públicas/privadas en una instancia de Campaign específica para el cifrado de datos salientes, así como cómo importar e instalar una clave pública en una instancia de Campaign para el descifrado de datos*

   * [Generación e instalación de claves GPG para el cifrado de datos](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [Uso de una clave GPG para cifrar datos](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [Descifrado de datos](./gpg-key-management/decrypting-data.md)

* **[Localización de averías del panel de control](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *Obtenga información sobre cómo solucionar problemas de la[!UICONTROL Control Panel]*

## Recursos adicionales

* [Centro de ayuda del Panel de control de Campaign](https://docs.adobe.com/content/help/es-ES/control-panel/using/control-panel-home.html)
