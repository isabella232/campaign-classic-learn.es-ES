---
title: Cómo configurar flujos de trabajo de validación en Adobe Campaign Classic
seo-title: Cómo configurar flujos de trabajo de validación en Adobe Campaign Classic
description: Adobe Campaign oferta varias opciones para que los especialistas en mercadotecnia revisen y proporcionen contenido de envío, destinatarios de campaña, extracción de datos y aprobaciones presupuestarias. Este tutorial explica cómo configurar diferentes flujos de trabajo de validación de aprobación.
seo-description: Este vídeo explica cómo configurar y utilizar una Plantilla de envíos en la Campaña de ACCAdobe oferta varias opciones para que los especialistas en mercadotecnia revisen y proporcionen contenido de envío, destinatarios de campaña, extracción de datos y aprobaciones presupuestarias. Este tutorial explica cómo configurar diferentes flujos de trabajo de validación de aprobación.
uuid: fdeb7aef-95aa-4bc1-9c51-2eb7ce802107
discoiquuid: 29abc57d-c359-472d-817a-0671818894f0
feature: Workflow
topics: Validation
kt: KT-1566
doc-type: feature video
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 838c617ca163a09fcb57b7b4706433e98869bc3d
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# Cómo configurar flujos de trabajo de validación en Adobe Campaign Classic

Adobe Campaign oferta varias opciones para que los especialistas en mercadotecnia revisen y proporcionen contenido de envío, destinatarios de campaña, extracción de datos y aprobaciones presupuestarias.

Este tutorial explica cómo configurar diferentes flujos de trabajo de validación de aprobación.

## Requisito previo {#prerequisite}

Antes de habilitar los pasos de aprobación, el equipo de mercadotecnia debe definir revisores individuales:

* La función de revisor de Adobe Campaign dentro de una actividad de aprobación puede ser un solo revisor (Operador) o un grupo de revisores (Función de operador).
* Un rol de administrador debe configurar previamente los grupos de revisores y revisores en Adobe Campaign. Esto permite a los desarrolladores de campañas seleccionar a los revisores como aprobadores en una campaña o un envío.

## Configuración de aprobaciones para campañas {#configuring-approvals-for-campaigns}

Si tiene el mismo conjunto de revisores para todos los envíos del flujo de trabajo de campaña, aprovecharía las funcionalidades de aprobación [!DNL Campaign]. Al configurar aprobaciones y revisores en el nivel de campaña, las tareas de aprobación y los revisores se insertarán en cada actividad de envío del flujo de trabajo una vez que se ejecute el flujo de trabajo.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Configuración de aprobaciones para envíos {#configuring-approvals-for-deliveries}

También puede configurar aprobaciones a nivel de envío. Si los pasos y los revisores de aprobaciones de envío difieren de los pasos y los revisores de aprobación de campaña, la configuración de envío anulará la configuración de campaña.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Configuración de una actividad de aprobación {#configuring-an-approval-activity}

A diferencia de las aprobaciones de envío o campaña, la actividad de aprobación permite crear un proceso de aprobación dentro de un flujo de trabajo. De este modo, la lógica de selección de objetivos se puede aprobar antes de iniciar el envío. También permite la aprobación en varios niveles dentro del flujo de trabajo, si es necesario.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

Para obtener más información, consulte la [Documentación de aprobación](https://docs.adobe.com/help/en/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)
