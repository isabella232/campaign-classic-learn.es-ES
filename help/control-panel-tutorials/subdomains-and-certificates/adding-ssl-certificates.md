---
title: Añadir certificados SSL
description: Aprenda a añadir certificados SSL para proteger los subdominios.
feature: Panel de control de Campaign
kt: 4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Administrator
level: Experienced
original-url: https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/administrating/control-panel-acc/adding-ssl-certificates.html
exl-id: 9ba485fb-be26-4f3c-a9de-844fecaec20d
source-git-commit: 3757eaf573dab5139bad084b664475c6a7de4b02
workflow-type: tm+mt
source-wordcount: '212'
ht-degree: 89%

---

# Añadir certificados SSL

Adobe Campaign [!UICONTROL Control Panel] le permite añadir certificados SSL para proteger sus subdominios.

## Acceso a la administración del subdominio con el panel de control de Campaign

Para acceder a la administración de subdominios en panel de control de Campaign, vaya a:

* [Página de inicio de Experience Cloud](https://experience.adobe.com/#/home) > Selector de soluciones: **[!DNL Campaign]** > **[!UICONTROL Control Panel]** tarjeta > **[!UICONTROL Subdomains & Certificates]** tarjeta

   o
* Directamente desde la dirección URL: [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## Pasos para añadir los certificados SSL

Para añadir los certificados SSL se requieren tres pasos:

### 1. Generar solicitudes de firma de certificado.

Se requiere la solicitud de firma de certificado (CSR) para la compra de un certificado SSL. Es necesario que se genere para la instancia y los subdominios que planea proteger.

En el siguiente vídeo se describe cómo generar una solicitud de firma de certificado en el panel de control de Campaign.

>[!VIDEO](https://video.tv.adobe.com/v/31317?quality=12)

*Generar solicitudes de firma de certificado (2:36 min)*

### 2. Comprar certificados SSL

Después de obtener el CSR, deberá adquirir el certificado SSL de una autoridad certificadora aprobada por su organización.

### 3. Instalar certificados SSL

Una vez que haya obtenido el certificado SSL, deberá instalarlo para los subdominios que planea proteger.

El siguiente vídeo explica cómo instalar los certificados SSL en [!UICONTROL Control Panel].

>[!VIDEO](https://video.tv.adobe.com/v/31166?quality=12)

*Instalar certificados SSL (1:25 min)*

## Recursos adicionales

* [Delegación de subdominios completa (vídeo)](./subdomain-delegation.md)
* [Renovación del certificado SSL de un subdominio (documentación)](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html)