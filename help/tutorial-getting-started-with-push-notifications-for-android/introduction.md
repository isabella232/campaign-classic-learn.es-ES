---
title: Tutorial Getting Started with push notifications for Android - Introduction (Introducción a las notificaciones push en Android)
description: Este tutorial le guiará por los pasos necesarios para enviar notificaciones push desde Adobe Campaign y recibir estas notificaciones en su aplicación de Android.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 412fe93f45be1e98343b4e63cbd7dd9285444e46
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 6%

---


# Tutorial Getting Started with push notifications for Android - Introduction (Introducción a las notificaciones push en Android)

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android ]mobile devices.

Este tutorial le guiará por los pasos necesarios para enviar [!DNL push] notificaciones de Adobe Campaign a una [!DNL Android] aplicación.

## Requisitos previos

Antes de empezar, deberá cumplir los siguientes requisitos previos

1) Aplicación móvilEste tutorial no cubre los pasos detallados necesarios para configurar la aplicación móvil. Tendrá que tener una aplicación **[!DNL Android]móvil con la[!DNL Campaign SDK]** integración.

   * Puede encontrar una descripción detallada de los pasos necesarios en el SDK para la [integración de Campañas en la aplicación](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)móvil.

   * También puede utilizar el SDK de Experience Platform Mobile. Para obtener más información, vea el vídeo del tutorial [Configurar el Canal push con el SDK](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html) de Experience Platform Mobile.

2) Paquete de Canal de aplicaciones móviles instalado

   Deberá tener instalado el paquete de canal de la aplicación móvil en su instancia. En el siguiente vídeo se explica cómo comprobar si el canal de aplicaciones móviles está instalado en la instancia y, en caso contrario, cómo instalarlo.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Tutorial

Nos gustaría enviar una notificación push promocional personalizada a los suscriptores de la aplicación móvil Neotrip [!DNL Android] . La aplicación Neotrip está configurada con el SDK de Campaña y nos hemos asegurado de que el canal de aplicaciones móviles esté activado en nuestra instancia de Campaña.

Se requieren los siguientes pasos de configuración:

### Paso 1: Ampliar el esquema de suscripción de la aplicación para personalizar las notificaciones push

Como nos gustaría personalizar la notificación push, primero [ampliaremos el esquema](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) de suscripción de la aplicación para poder almacenar los valores de personalización que recibimos de la aplicación cuando el usuario se suscribe al servicio.

### Paso 2: Configure el servicio de Android y cree la aplicación de aplicaciones móviles en Campaña

A continuación, tendremos que [configurar el servicio de Android y crear la aplicación de aplicaciones móviles en Campaña](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). En este paso definiremos la aplicación Neotrip como el destinatario para la notificación push.

### Paso 3: Configurar y enviar la notificación push

A continuación, estamos listos para [configurar y enviar la notificación](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)push.

## Inicio del tutorial

**[Paso 1: Ampliación del esquema de suscripción de la aplicación](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)**
