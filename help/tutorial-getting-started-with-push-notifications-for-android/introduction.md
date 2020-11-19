---
title: 'Introducción a las notificaciones push para Android: Introducción'
description: Este tutorial le guiará por los pasos necesarios para enviar notificaciones push desde Adobe Campaign y recibir estas notificaciones en su aplicación de Android.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 016f47e131df9c3a25b9131da372efaedf6cd5ad
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 8%

---


# Introducción a las notificaciones push para Android: Introducción

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android] mobile devices. Este tutorial le guiará por los pasos necesarios para enviar [!DNL push] notificaciones de Adobe Campaign a una [!DNL Android] aplicación.

## Requisitos previos

Antes de empezar, deberá tener lo siguiente:

1) **Aplicación Android Mobile**

   Este tutorial no cubre los pasos detallados necesarios para configurar la aplicación móvil. Necesitará tener una aplicación **[!DNL Android]móvil con la [!DNL Campaign SDK] integrada**.

   Puede encontrar una descripción detallada de los pasos necesarios en la documentación del producto:

   [Integración del SDK de Campaign en la aplicación móvil](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)

   También puede utilizar el SDK de Experience Platform Mobile. Para obtener más información, vea el vídeo del tutorial:

   [Configuración del Canal push mediante el SDK de Experience Platform Mobile](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html)

2) **[!DNL Mobile App channel]paquete instalado**

   El [!DNL Mobile App channel] paquete debe estar instalado en su [!DNL Campaign] instancia. En el siguiente vídeo se explica cómo comprobar si la [!DNL Mobile App channel] instalación está instalada en la instancia y, en caso contrario, cómo instalarla.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Información general del tutorial

Nos gustaría enviar una notificación promocional personalizada [!DNL push] a los suscriptores de la aplicación [!DNL Neotrip] móvil [!DNL Android] . La [!DNL Neotrip] aplicación está configurada con el [!DNL Campaign SDK] y nos hemos asegurado de que el [!DNL Mobile App channel] se active en nuestra [!DNL Campaign] instancia.

Se requieren los siguientes pasos de configuración:

### Paso 1: Ampliar el esquema de suscripción de la aplicación para personalizar [!DNL push] las notificaciones

Como nos gustaría personalizar la [!DNL push] notificación, primero [ampliaremos el esquema](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) de suscripción de la aplicación para poder almacenar los valores de personalización que recibimos de la aplicación cuando el usuario se suscriba al servicio.

### Paso 2: Configure el servicio de Android y cree la aplicación móvil en Campaña

A continuación, tendremos que [configurar el servicio de Android y crear la aplicación móvil en Campaña](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). En este paso definiremos la [!DNL Neotrip] aplicación como el destinatario para la notificación push.

### Paso 3: Configurar y enviar la notificación push

A continuación, estamos listos para [configurar y enviar la notificación](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)push.

## Inicio del tutorial

Paso 1: [Ampliación del esquema de suscripción de la aplicación](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
