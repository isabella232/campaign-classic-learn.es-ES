---
title: Cómo configurar campañas de correo electrónico recurrentes y continuas
description: Este tutorial explica cómo configurar un envío recurrente y continuo y las diferencias entre los dos enfoques en Adobe Campaign Classic (ACC).
feature: workflows
topics: channel activities
kt: 1560
doc-type: feature video
activity: use
team: TM
translation-type: tm+mt
source-git-commit: d1799d978a9a29f69d637178439fe770ffd4b281
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 3%

---


# Cómo configurar campañas de correo electrónico recurrentes y continuas

Este tutorial explica cómo configurar un envío recurrente y continuo y las diferencias entre los dos enfoques.

## Seguimiento recurrente y continuo de Envíos {#recurring-and-continuous-delivery-tracking}

Los envíos recurrentes y continuos difieren en la forma en que se administran los datos de contacto:

* The **continuous delivery** lets you add new recipients to an existing delivery and avoids you having to create a new delivery each time a new recipient is added. Puede actualizar el elemento creativo directamente en el flujo de trabajo de campaña y lo hará en la carpeta Recurso de Plantilla de envíos.

   Un envío continuo creará un envío ÚNICO y registros de envío (wideLog) y registros de seguimiento que hacen referencia a que se agrega un envío cada vez que se ejecuta.

![Envío continuo](/help/acc/assets/delivery_continuous.jpg)

* Un envío **** recurrente creará una nueva instancia de envío cada vez que se ejecute. Por ejemplo, si el flujo de trabajo está programado para ejecutarse una vez a la semana, el resultado sería de 52 Envíos al cabo de un año. Esto también significa que el registro y los registros de seguimiento generales se separarán por cada instancia de envío.

![Envío recurrente](/help/acc/assets/delivery_recurring.jpg)

## Cómo configurar un envío recurrente {#how-to-set-up-a-recurring-delivery}

En este vídeo se explica cómo configurar un envío recurrente y una actividad de Planificador.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## Cómo configurar un envío continuo {#how-to-set-up-a-continuous-delivery}

Este vídeo muestra cómo configurar un envío continuo con una consulta incremental.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)

## Recursos adicionales

[Creación de un envío recurrente en un flujo de trabajo de objetivos](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/use-cases/sending-a-birthday-email.html#creating-a-recurring-delivery-in-a-targeting-workflow)