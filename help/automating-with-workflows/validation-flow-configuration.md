---
title: Configuración de los flujos de trabajo de validación en Adobe Campaign Classic
seo-title: Configuración de los flujos de trabajo de validación en Adobe Campaign Classic
description: Obtenga información sobre cómo configurar diferentes flujos de trabajo de validación de aprobación.
seo-description: En este vídeo se explica cómo configurar y utilizar una plantilla de envío en ACCAdobe Campaign ofrece varias opciones para que los especialistas en marketing revisen y proporcionen contenido de envío, objetivo de campaña, extracción de datos y aprobaciones de presupuesto. Este tutorial explica cómo configurar diferentes flujos de trabajo de validación de aprobación.
uuid: fdeb7aef-95aa-4bc1-9c51-2eb7ce802107
discoiquuid: 29abc57d-c359-472d-817a-0671818894f0
feature: Flujos de trabajo, aprobaciones
topics: Validation
kt: KT-1566
doc-type: feature video
activity: setup
team: TM
role: Profesional empresarial
level: Avanzadas
translation-type: tm+mt
source-git-commit: 8f06f533afc34b4bcf7fcc690c1b9ab5cafcef4a
workflow-type: tm+mt
source-wordcount: '339'
ht-degree: 0%

---


# Configuración de los flujos de trabajo de validación en Adobe Campaign Classic

Adobe Campaign ofrece varias opciones para que los especialistas en marketing revisen y proporcionen contenido de envío, objetivo de campaña, extracción de datos y aprobaciones de presupuesto.

Este tutorial explica cómo configurar diferentes flujos de trabajo de validación de aprobación.

## Requisito previo {#prerequisite}

Antes de activar los pasos de aprobación, el equipo de marketing debe definir revisores individuales:

* La función de revisor de Adobe Campaign dentro de una actividad de aprobación puede ser un solo revisor (Operador) o un grupo de revisores (función de operador).
* Los grupos de revisores y revisores deben estar configurados previamente en Adobe Campaign mediante una función de administrador. Esto permite a los desarrolladores de campañas seleccionar los revisores como aprobadores en una campaña o entrega.

## Configuración de aprobaciones para campañas {#configuring-approvals-for-campaigns}

Si tiene el mismo conjunto de revisores para todas las entregas en el flujo de trabajo de la campaña, aprovecharía las funcionalidades de aprobación de [!DNL Campaign]. Al configurar las aprobaciones y los revisores en el nivel de campaña, las tareas de aprobación y los revisores se dirigen a cada actividad de entrega del flujo de trabajo una vez que se ejecute el flujo de trabajo.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Configuración de aprobaciones para envíos {#configuring-approvals-for-deliveries}

También puede configurar aprobaciones a nivel de envío. Si los pasos y revisores de las aprobaciones de entrega difieren de los pasos y revisores de aprobación de campaña, la configuración de entrega anulará la configuración de campaña.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Configuración de una actividad de aprobación {#configuring-an-approval-activity}

A diferencia de la entrega o las aprobaciones de campaña, la actividad de aprobación permite crear un proceso de aprobación dentro de un flujo de trabajo. De este modo, la lógica de selección de objetivos se puede aprobar antes de iniciar la entrega. También permite la aprobación en varios niveles dentro del flujo de trabajo, si es necesario.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

Para obtener más información, consulte la [Documentación de aprobación](https://docs.adobe.com/help/en/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)
