---
title: Notas de la versión de Adobe Experience Cloud
description: Notas de la versión de Adobe Experience Cloud
doc-type: release notes
last-update: June 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 504a9a00daef04e57c5662d0a4e3e92920b40ccd
workflow-type: tm+mt
source-wordcount: '7037'
ht-degree: 34%

---


# Notas de la versión de Adobe Experience Cloud - Junio de 2020

![Banner](/assets/experience-cloud-banner-3.png)

This page describes new features, fixes, and important notices in [!DNL Adobe Experience Cloud]. También se destacan la nueva documentación, los cursos de formación y los tutoriales de vídeo que le ayudarán a sacar el máximo provecho de los Experience Cloud.

>[!NOTE]
>
>Suscríbase a la [actualización de producto prioritaria de Adobe](https://www.adobe.com/subscription/priority-product-update.html) para recibir notificaciones por correo electrónico de las próximas versiones.

**Fecha de publicación: 18 de junio de 2020**

Las fechas de lanzamiento del producto pueden variar. Vuelva a buscar actualizaciones con frecuencia.

Última actualización: **18 de junio de 2020**

* [Estado del sistema de Adobe](#status)
* [Interfaz de Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Organización de recorridos](#journey-orch)
* [Analytics](#analytics) (y [Customer Journey Analytics](#cust-journey))
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/es-ES/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/es/primetime/user-guide.html) (lleva a la página de ayuda de Primetime)

¿Necesita ayuda? Visite [Adobe Experience League](https://experienceleague.adobe.com/#home) para encontrar documentación técnica y de productos, cursos seleccionados por Adobe, tutoriales en vídeo, respuestas rápidas, información de la comunidad y formación impartida por instructores.

## ![Icono](/assets/adobe.png) Estado del sistema de Adobe {#status}

[!UICONTROL El estado del sistema de Adobe] proporciona información detallada, actualizaciones de estado y notificaciones por correo electrónico sobre los productos en la nube de Adobe y las interrupciones y sesiones de mantenimiento de los servicios de Adobe. Puede comprobar el estado en [status.adobe.com](https://status.adobe.com/).

Publicado: **21 de mayo de 2020**

**Novedades**

* Con su Adobe ID, puede suscribirse a las notificaciones de eventos con una mayor granularidad, lo que permite llegar hasta la oferta de productos y el nivel de complementos. Para ayudarle a configurar su suscripción más rápido, el proceso de suscripción automática ahora recomienda una selección de productos y ofertas según los derechos del producto. Esto debería reducir la cantidad de correos electrónicos que recibe y enviaría notificaciones más pertinentes a su bandeja de entrada. Empiece por [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuevas funciones y mejoras disponibles**

| Función | Descripción |
| -----------| ---------- |
| Mejora de la experiencia del usuario en cuanto a las suscripciones y las notificaciones | <ul><li>Las ubicaciones regionales de [!DNL Marketo Engage] ahora se filtran según la lista de ofertas de productos seleccionadas.</li><li>Las notificaciones de [!DNL Marketo Engage] por correo electrónico son pertinentes la región, la ubicación y las preferencias de entorno del usuario.</li></ul> |
| Confirmación de suscripción de evento | <ul><li>Ahora puede obtener una confirmación por correo electrónico al suscribirse a las actualizaciones de evento único en curso.</li></ul> |
| Mejoras en el uso de la navegación global | <ul><li>Una experiencia de usuario coherente con `Adobe.com` en el menú de navegación de nivel superior.</li></ul> |

## ![Icono](/assets/ec_appicon_24.png) Interfaz de Experience Cloud {#ecloud}

Actualizaciones generales de la interfaz de Experience Cloud.

**Dominio de producto unificado**

Adobe ha estado actualizando el encabezado de la interfaz y el dominio para unificar y mejorar el funcionamiento de las aplicaciones de Experience Cloud. Estas mejoras están diseñadas para mejorar sutilmente su experiencia. Estas mejoras no cambiarán los flujos de trabajo actuales.

Las actualizaciones incluyen:

* Nuevas direcciones URL de la aplicación: `experience.adobe.com/<application name>`:
   * Todos los productos adoptarán en algún momento este patrón de URL. Busque nuevas direcciones URL que entren en vigor durante el mes.
   * Compatibilidad con navegadores: Los exploradores admitidos son [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] y [!DNL Opera] (en sus versiones más recientes). **Nota:** Aunque la interfaz de Experience Cloud admite estos exploradores, es posible que las aplicaciones individuales no admitan todos los exploradores. (Por ejemplo, [Analytics](https://docs.adobe.com/content/help/es-ES/analytics/admin/sys-reqs.html) no es compatible con [!DNL Opera] y [Target](https://docs.adobe.com/help/es-ES/target/using/implement-target/before-implement/supported-browsers.html) no es compatible con [!DNL Safari]).
   * ([!DNL Safari] solo) El cambio de dominio puede causar problemas de cookies en [!DNL Safari]. Al anular la selección _Impedir el seguimiento entre sitios_ en las preferencias de privacidad de [!DNL Safari], se habilitarán las cookies entre dominios (y todas las experiencias entre sitios) y Experience Cloud funcionará en este nuevo dominio.
* Es más fácil cambiar entre las organizaciones o a otra aplicación.
* Ayuda del producto mejorada: [!UICONTROL Experience League] está integrada en el producto, por lo que una búsqueda de ayuda también incluye resultados de foros de la comunidad y contenido de vídeo. Este cambio simplifica el acceso a más contenido y le ayuda a sacar el máximo rendimiento de Experience Cloud. Además, puede hacer clic en **[!UICONTROL Ayuda]** > **[!UICONTROL Comentarios]** para informar sobre problemas o compartir sus ideas con Adobe.

Las siguientes aplicaciones utilizan el nuevo dominio experience.adobe.com:

| Aplicación o servicio | Dominio |
| -----------| ---------- |
| Página de inicio de Experience Cloud | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| Administración de recorridos | `experience.adobe.com/journeys` |
| Adobe Analytics | `experience.adobe.com/analytics` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Panel de control de Adobe Campaign | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Distribución de software | `experience.adobe.com/downloads` |
| Herramienta de administración (beta) | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Board &amp; Collections]**, un filtro heredado en el selector de [!UICONTROL recursos de Experience Cloud] se está retirando del mercado.

## ![Icono](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Release notes for the [!DNL Experience Platform] and application services, including [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], and security bulletins.

Fecha de publicación: **10 de junio de 2020**

[!DNL Adobe Experience Platform] incluye las siguientes nuevas funciones:

* **Área de trabajo de ciencia de datos:** El [!DNL JupyterLab Launcher] ahora incluye un [!DNL Python] ordenador portátil para aprendizaje automático en tiempo real (Alpha).
* **Segmentación:** Se ha agregado un campo de fecha de aniversario para las funciones de fecha, que permite a los usuarios evaluar las fechas sin el año.
* **Fuentes:** Conectores de origen nuevos para [!DNL Apache HDFS] y [!DNL Couchbase].

Para obtener más información sobre estas funciones, consulte las notas de la versión del [Experience Platform](https://docs.adobe.com/content/help/es-ES/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md).

### Información adicional de la versión de Experience Platform

* [Notas de la versión de Experience Platform Launch](https://docs.adobe.com/content/help/es-ES/launch/using/intro/release-notes/current.html)
* [Boletines de seguridad y avisos](https://helpx.adobe.com/es/security.html) (Todos los productos de Adobe)

### Nuevos cursos y tutoriales para Experience Platform {#tutorials-plat}

| Contenido | Tipo de contenido | Descripción |
| -----------| ---------- | ---------- |
| [Introducción al Adobe Experience Platform](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1) | Curso | Descubra cómo Adobe Experience Platform le ayuda a ofrecer la experiencia adecuada al transformar sus datos en sólidos perfiles de clientes en tiempo real y perspectivas basadas en AI que puede activar en cada canal. Este curso de introducción le ofrece una descripción general de las funciones de los Experience Platform, casos de uso, relación con Adobe Experience Cloud, arquitectura básica, interfaz y funciones de proyecto. |
| [Introducción al SDK web y a la red perimetral](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/introduction-to-web-sdk-and-edge-network.html) | Tutorial de vídeo | Información general sobre el SDK de Adobe Experience Platform y Edge Network. Experience Platform Web SDK es una biblioteca JavaScript del lado del cliente que permite a los clientes utilizar una biblioteca JavaScript, un tipo de señalización, un flujo de datos, un destino del lado del servidor para enviar datos a todas las aplicaciones de Adobe y a destinos de terceros. |
| [Demostración del SDK web y la red perimetral](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/demo-of-web-sdk-and-edge-network.html) | Tutorial de vídeo | Observe el SDK web de Adobe Experience Platform y Edge Network en acción, con una sola llamada a Adobe que envía datos a Experience Platform, Analytics, Audience Manager y Destinatario. |
| [Demostración de datos de clientes en tiempo real Platform](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/demo.html) | Tutorial de vídeo | Conozca cómo se utiliza CDP en tiempo real para recopilar datos de múltiples fuentes. Puede combinar esos datos en un único perfil de clientes en tiempo real y activarlos para crear experiencias personalizadas con los clientes. |

## ![Icono](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Con Adobe Experience Platform, puede organizar los recorridos individuales de los clientes a escala en distintos canales de experiencia y adaptarse de forma inteligente a las necesidades y recorrido de cada usuario en tiempo real.

### Última versión

Para obtener las últimas actualizaciones de la versión, consulte las notas de la versión de [Journey Orchestration](https://docs.adobe.com/content/help/es-ES/journeys/using/release-notes/release-notes.html)

### Nuevos cursos y tutoriales para Journey Orchestration {#jo-tutorials}

| Contenido | Tipo de contenido | Descripción |
| -----------| ---------- | ---------- |
| [Introducción a Journey Orchestration para administradores](https://experienceleague.adobe.com/?recommended=JourneyOrchestration-A-1-2020.2) | Curso | Obtenga información sobre cómo configurar y utilizar Journey Orchestration. Este curso abarca los conceptos clave y los pasos de configuración necesarios para permitir la orquestación de un viaje. Obtenga información sobre cómo crear, publicar y cómo informar y analizar los viajes orquestados. |
| [Introducción a Journey Orchestration para usuarios empresariales](https://experienceleague.corp.adobe.com/?recommended=JourneyOrchestration-U-1-2020.1) | Curso | Obtenga información sobre cómo configurar y utilizar Journey Orchestration. Este curso abarca los conceptos clave. Aprenderá a crear, publicar, crear informes y analizar sus travesías orquestadas. |

### Recursos adicionales para el Journey Orchestration

[Documentación](https://docs.adobe.com/content/help/es-ES/journeys/using/journey-orchestration-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/es-ES/journeys/using/release-notes/release-notes.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![Icono](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Fecha de publicación: **18 de junio de 2020**

* [Funciones nuevas en Adobe Analytics](#aa-features)
* [Nuevas funciones en Customer Journey Analytics](#cust-journey)
* [Nuevas funciones de Media Analytics](#media-aa)
* [Correcciones en Adobe Analytics](#aa-fixes)
* [Avisos importantes para los administradores de Analytics](#aa-notices)
* [Nuevos cursos y tutoriales de Adobe Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Funciones nuevas en Adobe Analytics {#aa-features}

| Función | [Disponibilidad general](https://docs.adobe.com/content/help/es-ES/analytics/landing/an-releases.html) - Fecha de destino | Descripción |
| -----------| ---------- |-------|
| IQ de atribución: Atribución algorítmica | 18 de junio de 2020 | El modelo [!UICONTROL Atribución] algorítmica de Analysis Workspace utiliza técnicas estadísticas para determinar dinámicamente la asignación óptima de crédito para la métrica seleccionada. Disponible para los clientes de Adobe Analytics Ultimate. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| IQ de atribución: Ventanas retroactivas personalizadas | 18 de junio de 2020 | Ahora puede configurar cualquier modelo de atribución en IQ [!UICONTROL de] atribución para incluir puntos de contacto de hasta 90 días antes del período de tiempo de sistema de informes. Esto generalmente aumenta la precisión de atribución de eventos que se producen al principio del período de sistema de informes teniendo en cuenta las interacciones que se produjeron en el mes o meses anteriores. Disponible para los clientes de Adobe Analytics Foundation, Select, Prime, Premium, Premium Attribution, Premium Complete y Ultimate. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| Funciones de proyecto para proyectos compartidos de Workspace | 18 de junio de 2020 | Al compartir un proyecto de Workspace, ahora puede colocar destinatarios en una de las tres funciones del proyecto, según la experiencia del proyecto que desee que tengan: Editar, Duplicado y Vista. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Proyectos de Workspace solo de Vista | 18 de junio de 2020 | Los proyectos de Workspace se pueden compartir solo con los usuarios como &quot;vistas posibles&quot;. Cuando un destinatario de Vista abre el proyecto compartido, recibe una experiencia de proyecto más restrictiva, sin carril izquierdo ni interacciones limitadas. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Capacidad para co-editar proyectos de Workspace | 18 de junio de 2020 | Los Destinatarios añadidos a la función &quot;Puede editar&quot; se pueden guardar en un proyecto que se haya compartido con ellos. Esto se extiende tanto a los administradores como a los no administradores. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Panel en blanco actualizado en Workspace | 18 de junio de 2020 | El panel en blanco de Workspace ahora incluye paneles y visualizaciones, lo que le ofrece una forma más fluida de elegir el flujo de trabajo de análisis que mejor se adapte a sus necesidades. |
| Dominios de origen disponibles en RDC de China | 18 de junio de 2020 | Permite a los clientes con un `.cn` dominio solicitar un dominio de origen para utilizarlo dentro de China continental. (Documentación disponible con la compra de la SKU &quot;Optimización del rendimiento de China&quot;). |
| El panel Quick Insights en Espacio de trabajo | 25 de junio de 2020 | Quick Insights proporciona una guía a los no analistas y a los nuevos usuarios de Analysis Workspace para aprender a responder preguntas comerciales de forma rápida y sencilla. [Más información...](https://docs.adobe.com/content/help/es-ES/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| Panel Analytics for Target en Espacio de trabajo | 25 de junio de 2020 | El panel Analytics para Destinatario (A4T) le permite analizar sus actividades y experiencias de Adobe Target, con alza y confianza, en Analysis Workspace. [Más información...](https://docs.adobe.com/content/help/es-ES/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |
| [!UICONTROL Página Acerca de Workspace] | Junio de 18,2020 | La página [!UICONTROL Acerca del espacio de trabajo] proporciona información sobre el entorno de su Analysis Workspace, sobre los administradores de Analytics de Adobe (si necesita asistencia técnica) y una forma de proporcionar comentarios en el producto. Se encuentra en **[!UICONTROL Espacio de trabajo]** > **[!UICONTROL Ayuda]** > **[!UICONTROL Acerca de Espacio de trabajo]**. |

### Nuevas funciones en Customer Journey Analytics {#cust-journey}

| Función | [Disponibilidad general](https://docs.adobe.com/content/help/es-ES/analytics/landing/an-releases.html) - Fecha de destino | Descripción |
| -----------| ---------- |-----|
| Compatibilidad con matrices de objetos | 18 de junio de 2020 | Los clientes de CJA ahora pueden informar sobre dimensiones y métricas que aparecen en matrices de objetos dentro de sus esquemas de conjuntos de datos de Adobe Experience Platform. [Más información...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-usecases/object-arrays.html) |
| IQ de atribución: [!UICONTROL Atribución algorítmica] | 18 de junio de 2020 | El modelo [!UICONTROL Atribución] algorítmica de [!UICONTROL Analysis Workspace] utiliza técnicas estadísticas para determinar dinámicamente la asignación óptima de crédito para la métrica seleccionada. Disponible para los clientes de Adobe Analytics Ultimate. [Más información...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/attribution/algorithmic.html) |
| IQ de atribución: Ventanas retroactivas personalizadas | 18 de junio de 2020 | Ahora puede configurar cualquier modelo de atribución en IQ [!UICONTROL de] atribución para incluir puntos de contacto desde 90 días antes del período de tiempo de sistema de informes. Esto generalmente aumenta la precisión de atribución de eventos que se producen al principio del período de sistema de informes teniendo en cuenta las interacciones que se produjeron en el mes o meses anteriores. [Más información...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/attribution/models.html) |
| Compatibilidad con la detección de [!UICONTROL anomalías] | 18 de junio de 2020 | [!UICONTROL La detección] de anomalías proporciona un método estadístico para determinar cómo ha cambiado una métrica determinada en relación con los datos anteriores. [Más información...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html) |
| Funciones de proyecto para proyectos compartidos [!UICONTROL de Workspace] | 18 de junio de 2020 | Al compartir un proyecto de [!UICONTROL Workspace] , ahora puede colocar destinatarios en una de las tres funciones del proyecto, según la experiencia del proyecto que desee que tengan: Editar, Duplicado y Vista. [Más información...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/share-projects.html) |
| Proyectos de [!UICONTROL Workspace] solo para Vistas | 18 de junio de 2020 | [!UICONTROL Los proyectos de Workspace] se pueden compartir con los usuarios, ya que solo _[!UICONTROL puede realizar la Vista]_. Cuando un destinatario de Vista abre el proyecto compartido, recibe una experiencia de proyecto más restrictiva sin carril izquierdo e interacciones limitadas.[Más información...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/view-only-projects.html) |
| Capacidad para editar proyectos de [!UICONTROL Workspace] en forma conjunta | 18 de junio de 2020 | Los Destinatarios añadidos a la función _[!UICONTROL Puede editar]_pueden guardarse en un proyecto que se haya compartido con ellos.[Más información...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/share-projects.html) |
| El panel Quick Insights en [!UICONTROL Espacio de trabajo] | 25 de junio de 2020 | Quick Insights proporciona una guía a los no analistas y a los nuevos usuarios de [!UICONTROL Analysis Workspace] para aprender a responder preguntas comerciales de forma rápida y sencilla. [Más información...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/panels/quickinsight.html) |
| [!UICONTROL Página Acerca de Workspace] | Junio de 18,2020 | La página [!UICONTROL Acerca del espacio de trabajo] proporciona información sobre el entorno de su Analysis Workspace, sobre los administradores de Analytics de Adobe (si necesita asistencia técnica) y una forma de proporcionar comentarios en el producto. Se encuentra en **[!UICONTROL Espacio de trabajo]** > **[!UICONTROL Ayuda]** > **[!UICONTROL Acerca de Espacio de trabajo]**. |

### Nuevas funciones de [!UICONTROL Media Analytics] {#media-aa}

Fecha de actualización: **18 de junio de 2020**

| Función | [Disponibilidad general](https://docs.adobe.com/content/help/es-ES/analytics/landing/an-releases.html) - Fecha de destino | Descripción |
| -----------| ---------- | ---------- |
| [Dispositivos y plataformas compatibles](https://docs.adobe.com/content/help/en/media-analytics/using/supported-devices.html) | 18 de junio de 2020 | Media Launch Extension con el SDK de AEP ahora admite los siguientes dispositivos OTT:<ul><li>Apple TV (tvOS)</li><li>Fire TV (sistema operativo Fire)</li><li>Android TV</li></ul> |  | [Dispositivos y plataformas compatibles](https://docs.adobe.com/content/help/en/media-analytics/using/supported-devices.html) | 18 de junio de 2020 | Media Launch Extension con el SDK de AEP ahora admite los siguientes dispositivos OTT:<ul><li>Apple TV (tvOS)</li><li>Fire TV (sistema operativo Fire)</li><li>Android TV</li></ul> |
| [Seguimiento de estado del reproductor](https://docs.adobe.com/content/help/es-ES/media-analytics/using/player-state-tracking/player-state-overview.html) | 29 de mayo de 2020 | [!UICONTROL Los clientes de Media Analytics] pueden capturar la interacción del visor durante la reproducción mediante un conjunto estándar de variables de solución para pantalla completa, subtítulos opcionales, silencios, imágenes en imagen y enfoque. También tiene la flexibilidad para crear estados de reproductor personalizados. Las variables de seguimiento de estado del reproductor ahora están disponibles para el sistema de informes en [!UICONTROL Analysis Workspace]. Esta función requiere uno de los siguientes elementos: <ul><li>Media [!DNL JavaScript] SDK 3.0 o superior</li><li>Para usar con el SDK [!DNL Adobe Experience Platform] (AEP):</li><li>[!UICONTROL Extensión de Media Analytics] (para la Web): [!UICONTROL Adobe Media Analytics] (SDK 3.x) para audio y vídeo v1.0 o superior</li><li>[!UICONTROL Extensión de Media Analytics] (para móviles): [!UICONTROL Adobe Media Analytics para audio] y vídeo v2.0 o superior</li><li>[!UICONTROL Colección de medios]</li></ul> |

### Correcciones en Adobe Analytics {#aa-fixes}

* Se ha corregido un problema que provocaba que los segmentos con búsquedas multibyte para determinados grupos de informes no coincidieran con nada. Ahora coincidirán con las cadenas correctas. (AN-220043)
* Se ha corregido un problema con el filtro [!UICONTROL de] elementos en [!UICONTROL Informes y Analytics] , que no funcionaba. (AN-206132)
* Se corrigió el tiempo de respuesta lento en la interfaz [!UICONTROL Proyectos] programados. (AN-214837)
* Se ha corregido un problema con la API de Analytics Sistema de informes 2.0 que producía un error de intervalo de fechas. (AN-215087)
* Fixed a case in which the instance/visit/visitor wasn&#39;t being counted in the denominator for the [!UICONTROL Time Spent] metrics. Esto sucedería cuando una visita individual sin valor para la dimensión (por ejemplo, Pagename) continuaba en el mismo segundo. (AN-211074)
* Se ha corregido un problema que impedía a los usuarios acceder a los proyectos de [!UICONTROL Workspace] que se compartían con ellos. (AN-217561)
* Se ha solucionado el problema por el que el Generador [!UICONTROL de reglas de]clasificación no clasificaba las claves. (AN-221538)
* Se ha corregido un problema con el uso [!UICONTROL de llamadas del] servidor, que no sistema de informes ningún dato de uso. (AN-210452)
* Se han corregido problemas con los segmentos publicados de Adobe Analytics que faltaban datos en el Audience Manager. (AN-220208, AN-220659)
* Se ha corregido un problema con los informes que mostraban datos, pero los registros [!UICONTROL de Fuentes] de datos indicaban &quot;Sin datos de Data warehouse&quot;. (AN-220784, AN-220858)
* Se han corregido problemas que evitaban el inicio de la [!UICONTROL Ad hoc analysis] desde el `experiencecloud.com` dominio. (AN-219680, AN-221629)
* Se han corregido problemas con el uso de la tecla de acceso directo &quot;Ctrl (o Comando) + C&quot;. (AN-221101, AN-221537)
* Se ha corregido un problema con la página de habilitación del [!UICONTROL Activity Map] . (AN-222029, AN-221242)
* Se ha corregido un problema que impedía añadir un punto de contacto en medio de una visualización de [!UICONTROL visitas en el orden previsto] . (AN-221648)

#### Correcciones adicionales de Adobe Analytics

AN-218269; AN-218455; AN-218492; AN-219888; AN-220447; AN-220546; AN-220788; AN-220866; AN-221165; AN-221545; AN-221712; AN-221832; AN-221853; AN-222000; AN-222505; AN-222559

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación o actualizada | Descripción |
| -----------| ---------- | ---------- |
| Migración al dominio de producto unificado | Fecha de entrada en vigor: 28 de mayo de 2020 | La migración a un dominio de producto unificado para Adobe Analytics, que comenzó en enero de 2020, finalizó el 28 de mayo de 2020. While Adobe Analytics works to remove all `omniture.com` domain references from its architecture, it is important to allowlist `omniture.com` as a third-party cookie. Cuando la migración completa de la arquitectura se complete (pronto), le notificaremos mediante las notas de la versión y este paso de lista de permitidos ya no será necesario. [A continuación](https://helpx.adobe.com/es/analytics/kb/adobe-ip-addresses.html) se muestra una lista completa de las direcciones IP y los dominios recomendados que debe permitir.<br>Si su organización bloquea las cookies de terceros, póngase en contacto con el Servicio de atención al cliente para recuperar el acceso a Adobe Analytics. |
| Nueva página de aterrizaje predeterminada de Adobe Analytics | Fecha de entrada en vigor: 18 de junio de 2020 | El 18 de junio de 2020, la página de aterrizaje predeterminada de Adobe Analytics cambiará de [!UICONTROL Informes] a [!UICONTROL Espacio de trabajo]. Este cambio se producirá para todos los usuarios que no hayan establecido previamente una página de aterrizaje personalizada. |
| Lista de permitidos de tecnología de terceros | 12 de marzo de 2020 (fecha de entrada en vigor) | Adobe Analytics ha comenzado a aprovechar las tecnologías de terceros para administrar el despliegue de funciones y la compatibilidad con el producto. Las siguientes direcciones URL deben agregarse a las listas de permisos necesarias para el cortafuegos de red a fin de garantizar el acceso completo a las funciones:<ul><li>Perspectiva: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Improved redundancy for [!UICONTROL Analysis Workspace] availability | 21 de mayo de 2020 | In order to ensure availability of [!UICONTROL Analysis Workspace], we are adding a secondary CDN (Content Delivery Network) for improved redundancy. Las siguientes direcciones URL deben agregarse a cualquier lista de permisiones de firewall de red necesaria:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Cambio en la forma en que se calculan las [!UICONTROL entradas y las salidas] en [!UICONTROL Espacio de trabajo] | 7 de abril de 2020 | En [!UICONTROL Analysis Workspace], a partir de marzo de 2020, hemos cambiado la forma en que el valor _Ninguno_ interactúa con las [!UICONTROL entradas y salidas]. Dado que ahora puede activar y desactivar el valor _Ninguno_ en [!UICONTROL Analysis Workspace], se aplica el valor _Ninguno_ después de la entrada o salida, cuando se solía aplicar antes (para eVars). Por ejemplo, supongamos que una primera visita no tiene valor para eVar, pero la segunda visita sí lo tiene. En [!UICONTROL Reports &amp; Analytics], se mostrará como _Sin especificar_ en la entrada, pero en [!UICONTROL Analysis Workspace], se mostrará como el valor de la segunda visita. |
| Fin de la vida útil de la configuración **[!UICONTROL Archivo de tablero]** | 27 de marzo de 2020 | La configuración **[!UICONTROL Ver archivo]** en **[!UICONTROL Administrar tableros]** de [!UICONTROL Reports &amp; Analytics] dejará de estar disponible a partir de octubre de 2020. |
| Fin de vida útil: API heredadas de Analytics | 9 de enero de 2020 | En noviembre de 2020, los siguientes servicios de API heredadas de Analytics llegarán a su fin de vida útil y se cerrarán. Las integraciones actuales creadas con estos servicios dejarán de funcionar. <ul><li>API de Analytics 1.3</li><li>API de Analytics SOAP 1.4</li><li>Autenticación OAuth heredada (OAuth y JWT)</li></ul>Hemos creado las [Preguntas frecuentes del fin de la vida útil de la API heredada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ayudarle a responder a sus preguntas y proporcionar instrucciones sobre cómo proceder. Las integraciones de API que emplean estos servicios pueden migrar a las [API de REST 1.4 de Analytics](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o a las [API de Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Las cuentas heredadas de OAuth pueden migrar a una cuenta de integración de Analytics [Adobe IO](https://console.adobe.io/home?mv=email), que puede utilizarse para acceder tanto a las API de Analytics 1.4 como a las API de Analytics 2.0. |
| Fin de la administración de datos en el centro de datos de San José para Londres y Singapur | Julio de 2020 | Para los clientes de Londres y Singapur, ya no se ofrecerá la administración de datos entre Londres o Singapur y el centro de datos de San José [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, utilice [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Singapur, utilice [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| EOL de Ad Hoc Analysis | 6 de agosto de 2018 | Adobe anunció su intención de finalizar el servicio de Ad Hoc Analysis. La fecha se hará pública una vez que esté disponible. Para obtener más información, consulte [Descubrir Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### Nuevos cursos y tutoriales de Analytics {#tutorials-analytics}

Nuevos cursos, vídeos de tutorial y artículos en Analytics y Customer Journey Analytics.

| Contenido | Tipo de contenido | Descripción |
| -----------| ---------- | ---------- |
| [Introducción a Customer Journey Analytics para usuarios](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-U-1-2020.1) | Curso | En este curso, aprenderá a utilizar Customer Journey Analytics (CJA) para analizar datos de muchas fuentes de datos diferentes. Aprenderá las diferencias entre Adobe Analytics y Customer Journey Analytics y cómo se gestionan los datos en CJA. Después de realizar este curso, debería poder crear y personalizar visualizaciones entre canales para mejorar la comprensión de sus clientes. |
| [Introducción a Customer Journey Analytics para administradores](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | Curso | Obtenga información sobre cómo configurar y utilizar [!UICONTROL Journey Orchestration]. Este curso abarca los conceptos clave y los pasos de configuración necesarios para permitir la orquestación de un viaje. Aprenderá a crear, publicar y a informar y analizar sus travesías orquestadas. |
| [Introducción a Customer Journey Analytics para ingenieros de datos](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-D-1-2020.1) | Curso | En este curso, conocerá los datos que llegan a Customer Journey Analytics y cómo afectan los informes del analista. Este curso se basa en su conocimiento general del Adobe Experience Platform. |
| [Introducción a Customer Journey Analytics para administradores](https://video.tv.adobe.com/v/34349?captions=spa) | Tutorial de vídeo | Vídeo introductorio a Customer Journey Analytics para administradores. |
| [Implementación guiada de Analytics](https://experienceleague.adobe.com/?recommended=Analytics-D-1-2019.1) | Curso | En este curso, aprenderá a empezar a implementar Adobe Analytics, comprender los conceptos de Analytics, crear un plan e implementar Adobe Analytics con Experience Platform Launch. |
| [Soluciones de Adobe Analytics para líderes](https://experienceleague.adobe.com/?recommended=Analytics-L-1-2020.1) | Curso | En este curso, conozca los aspectos fundamentales de Analytics y cómo el Analysis Workspace puede cambiar su negocio. Conozca cómo puede descubrir perspectivas con Adobe Sensei, escuchar los testimonios de los clientes y observar los puntos destacados de los expertos del sector en la Cumbre 2019. |
| [Introducción a Analysis Workspace](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.1.workspace) | Curso | Obtenga información sobre cómo empezar a usar Analysis Workspace. Cree su primer proyecto, aprenda a definir intervalos de fechas, aplicar segmentos y compartir y colaborar en proyectos. |
| [Generador de cuadros de mando de paneles de Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-scorecard-builder.html) | Tutorial de vídeo | En este vídeo, aprenderá a crear y compartir [!UICONTROL cuadros de mandos] en el [!UICONTROL Analysis Workspace] para que se vean en los paneles Analytics de Adobe (aplicación móvil). |
| [Experiencia en la aplicación de Adobe Analytics paneles](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-in-app-experience.html) | Tutorial de vídeo | En este vídeo, aprenderá a usar paneles de Adobe Analytics (aplicación móvil) para acceder a [!UICONTROL los cuadros de mandos] de vista creados por usted o compartidos con usted. |

#### Recursos de ayuda de Analytics

* [Tutoriales de Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentación del producto de Adobe Analytics](https://docs.adobe.com/content/help/es-ES/analytics/landing/home.html)

## ![Icono](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Nuevas funciones, correcciones, documentación y tutoriales en Audience Manager.

Updated **June 10, 2020**

### Actualizaciones de la interfaz de usuario

Audience Manager está publicando actualizaciones en el dominio y en la barra de encabezado para mejorar su experiencia y unificarse con otras aplicaciones de Experience Cloud.

* Es más fácil cambiar entre las organizaciones o a otra aplicación.
* Se ha mejorado la ayuda del usuario, que incluye artículos destacados y vídeos pertinentes al contexto en el menú Ayuda.
* Posibilidad de dar comentarios sobre tickets de soporte de archivos y Experience Platform.
* Un nuevo patrón de URL más sencillo. Actualice los marcadores a la nueva dirección URL: `experience.adobe.com/audience-manager`.

Estas actualizaciones solo están disponibles para los usuarios que inicien sesión con un Adobe ID. Para cambiar a un inicio de sesión con Adobe ID, consulte [Administrar usuarios y productos de Experience Cloud](https://docs.adobe.com/content/help/es-ES/core-services/interface/manage-users-and-products/admin-getting-started.html).

### Nuevas funciones y correcciones en Adobe Audience Manager

| Función | Descripción |
| -----------| ---------- |  
| [Complemento Audience Manager para IAB TCF v2.0 ](https://docs.adobe.com/content/help/es-ES/audience-manager/user-guide/overview/data-privacy/consent-management/aam-iab-plugin.translate.html) | Continuando con el enfoque de Adobe en Privacidad por diseño, estamos actualizando el complemento Audience Manager para IAB TCF a la versión 2.0 de IAB Transparency &amp; Consent Framework (TCF), a partir del 10 de junio de 2020. Los clientes que hayan implementado el complemento Audience Manager para IAB TCF deben actualizar a la versión 2.0 antes del 15 de agosto de 2020 para poder seguir usando la función. Después del 15 de agosto de 2020, la versión 1.1 dejará de ser compatible. |

**Correcciones**

* Se han actualizado los Términos y condiciones [!UICONTROL del] Audience Marketplace para que reflejen los requisitos legales de determinadas regiones geográficas. (AAM-54518)
* Se corrigió un problema en el cual el acceso a la página [!UICONTROL Características] desde marcadores resultaba en un error 404. (AAM-54768)
* Se corrigió un problema en el cual se agotaba el tiempo de espera de la API de actualización de destino al recuperar los modelos [!UICONTROL algorítmicos]. (AAM-54342)
* Ahora los usuarios pueden ver un indicador de precisión de clasificación de modelo para personas [!UICONTROL inteligentes]. (AAM-54847)
* Se corrigió un problema en el cual al pulsar Intro después de agregar una expresión de rasgo se eliminaba la expresión en lugar de guardarla. (AAM-54210)
* Se corrigió un problema en el cual las llamadas al método GET de la API de [!UICONTROL características] fallaban para los usuarios que no tenían el permiso VISTA_MODELS. (AAM-53104)
* Se corrigió un problema en el cual los usuarios no podían eliminar los modelos [!UICONTROL algorítmicos] que contenían características [!UICONTROL de carpeta]. (AAM-50192)
* Las expresiones de rasgos largos ahora se envuelven en varias líneas. (AAM-54972)
* Se corrigió un problema en el cual los usuarios con permisos de solo lectura podían ver el botón [!UICONTROL Crear nuevo] en las páginas de modelos algorítmicos. (AAM-54889)
* Se ha corregido un problema que provocaba que el indicador de carga de los informes [!UICONTROL General] y [!UICONTROL Tendencia] siguiera girando después de que finalizara la descarga de CSV. (AAM-54571)
* Se corrigió un problema en el cual los usuarios no podían agregar características masivas a los segmentos en el Generador [!UICONTROL de segmentos]. (AAM-55033)
* Varias mejoras de accesibilidad en toda la interfaz de usuario. (AAM-47269, AAM-48966, AAM-48976, AAM-49369, AAM-49023, AAM-49042).

### Nuevos cursos y tutoriales para Audience Manager {#tutorials-aam}

| Contenido | Tipo de contenido | Descripción |
| -----------| ---------- | ---------- |  
| [Introducción al Audience Manager](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.1) | Curso | Este curso le enseña los conceptos básicos del Audience Manager y los problemas que puede resolver con él. Obtenga información sobre casos de uso común y términos y conceptos clave de Audience Manager. |
| [Introducción a la identidad en el Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/introduction-to-identity-in-audience-manager.html) | Tutorial de vídeo | Conozca cómo Adobe Audience Manager administra la identidad, incluidos los perfiles internos y la combinación de perfiles, así como la sincronización de ID con socios. |
| [Explicación y configuración del destino basado en personas de LinkedIn](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-linkedin-pbd.html) | Curso | Este vídeo le guiará por los conceptos y pasos para crear un destino basado en personas en LinkedIn. Se basa en los vídeos y la documentación adicionales relativos a los destinos basados en personas. |
| [Creación de características basadas en reglas](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-rule-based-traits.html) | Tutorial de vídeo | Aprenda a utilizar el Generador [!UICONTROL de] características en la interfaz de Audience Manager para crear una característica basada en reglas, lo que le permite capturar la actividad en tiempo real en perfiles de Audience Manager. |
| [Habilitación del complemento Audience Manager para IAB TCF 2.0](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#enabling-iab-tcf) | Tutorial de vídeo | Obtenga información sobre cómo activar el complemento Audience Manager para IAB TCF. Habilitar este complemento es fácil si utiliza Adobe Experience Platform Launch. |
| [Demostración del complemento Audience Manager para IAB TCF 2.0](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#demo) | Tutorial de vídeo | En este vídeo, vea cómo las cookies y las señalizaciones del servicio de ID de Experience Cloud y las soluciones se ven afectadas por las selecciones de selección de usuarios de IAB. |

## ![Icono](/assets/aem.png) Adobe Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Adobe Experience Manager (AEM). Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

### Actualizaciones de productos

* **AEM 6.5.5.0**

   AEM 6.5, Service Pack 5 (6.5.5.0 publicado el 4 de junio de 2020) es una actualización importante que incluye nuevas funciones, mejoras clave solicitadas por el cliente y mejoras de rendimiento, estabilidad y seguridad, publicadas desde la disponibilidad general de AEM 6.5 en abril de 2019.

   * [Notas de la versión](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
   * [Características de la versión de AEM Forms](https://helpx.adobe.com/es/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.1**

   AEM 6.4, Service Pack 8, Cumulative Fix Pack (6.4.8.1 publicado el 04 de junio de 2020) es una actualización importante que incluye varias correcciones internas y de cliente desde la disponibilidad general de AEM 6.4, Service Pack 8 (6.4.8.0) en marzo de 2020.

   * [Notas de la versión](https://docs.adobe.com/content/help/en/experience-manager-64/release-notes/cfp-release-notes.html)
   * [Características de la versión de AEM Forms](https://helpx.adobe.com/es/aem-forms/kb/aem-forms-releases.html)

### Autoayuda

* **AEM como un servicio en la nube**

   ¿Qué novedades hay en AEM como Cloud Service?

   Entre los aspectos destacados se incluyen:

   * AEM Sites Commerce Integration Framework.
   * Etiquetas inteligentes mejoradas y novedades en la experiencia de formación guiada por la interfaz de usuario.
   * Compatibilidad con Adobe Asset Link para Adobe Xd.
   * AEM Assets Compatibilidad con Dynamic Media 3D.
   * Las nuevas mejoras de autoservicio reducen la dependencia de Adobe para las operaciones de simulación de pruebas.
      * La compatibilidad mejorada con el simulador para pruebas de autoservicio en Cloud Manager permite a los usuarios autorizados eliminar todos los entornos de un simulador para pruebas y recibir créditos.
      * El entorno de la zona de pruebas de hibernación automática &quot;hiberna&quot; automáticamente los entornos limitados después de un período de inactividad. Los clientes pueden activar activamente la &quot;deshibernación&quot;.
   * Herramientas de Transición para admitir la aceleración en la nube

   Con el objetivo de reducir el tiempo y el costo de la transición desde el local al Cloud Service, este mes se lanzaron dos herramientas de transición. Estas herramientas están diseñadas para automatizar algunas de las tareas clave durante el proceso de transición y, por lo tanto, reducir el esfuerzo general. .

   1. [El uso de Content Transfer Tool](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html) (disponible en SD) optimiza la actividad de transferencia de contenido y la hace escalable. Con una interfaz de usuario fácil de usar, la herramienta es de autoservicio para clientes y socios existentes (in situ/AMS) que están realizando la transición a AEM como Cloud Service.
   1. [Herramienta AMS Dispatcher Converter](https://github.com/adobe/aem-cloud-service-dispatcher-converter) (Open-source) para automatizar la conversión de las configuraciones de AMS Dispatcher a configuraciones de Dispatcher Cloud Service.

   [Notas de la versión de AEM como Cloud Service 2020.6.0](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

   Herramientas de Transición:

   https://github.com/adobe/aem-cloud-service-dispatcher-converter

   https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html

* **Componentes principales**

   Core Components 2.9.0 presenta la integración con la capa [de datos del cliente de](https://github.com/adobe/adobe-client-data-layer) Adobe y un nuevo componente de barra de progreso, y ahora está disponible junto con la documentación [de](https://docs.adobe.com/content/help/es-ES/experience-manager-core-components/using/introduction.html) creación, los detalles del [desarrollador y la descarga de proyectos disponibles en GitHub](https://github.com/adobe/aem-core-wcm-components).

* **El paso de AEM as a Cloud Service**

   [Al pasar a AEM como Cloud Service](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/moving/home.html) , se describe el viaje de transición recomendado para un cliente de AEM existente que se desplaza a Cloud Service. El objetivo de esta documentación es proporcionar a los clientes información, orientación y prácticas recomendadas para ayudarles a prepararse para esta transición y hacer que este viaje sea estructurado y predecible.

   Se ha lanzado una de las herramientas de Transición en la nube - Herramienta de transferencia de contenido. [Adobe ha desarrollado la herramienta](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/overview-content-transfer-tool.html) de transferencia de contenido que se puede utilizar para mover el contenido existente de una instancia de AEM de origen (in situ o AMS) a la instancia de destinatario AEM Cloud Service.

   Se ha lanzado una de las herramientas de refactorización de código: AEM Dispatcher Converter. [AEM Dispatcher Converter](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/refactoring-tools/dispatcher-transformation-utility-tools.html) es una herramienta para convertir las configuraciones existentes de AEM Dispatcher a AEM como configuraciones de Dispatcher Cloud Service y está disponible.

* **Accesibilidad y directrices WCAG 2.1**

   Actualizaciones en relación con las Directrices WCAG 2.1:

   * [Adobe Experience Manager as a Cloud Service y las directrices de accesibilidad web](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/web-accessibility.html)
   * [Guía rápida de WCAG 2.1](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/quick-guide-wcag.html)
   * [Crear contenido accesible (Conformidad con WCAG 2.1)](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/fundamentals/accessible-content.html)

* **Newsletters de AEM**

   El newsletter de AEM de Experience League está diseñado para ayudarle a ponerse al día con AEM, de modo que pueda obtener ventajas de inmediato. Esta es la newsletter más reciente:

   * [Volumen 31](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.31.html): Experience Manager ya está disponible como servicio en la nube.
   * [Suscríbase](https://adobeeventsonline.com/AEM/2017/NL/Optin/) a la newsletter de Experience Insider.
   * Archivos de newsletter de Vista en la sección de [Recursos de AEM](https://helpx.adobe.com/es/support/experience-manager/6-5.html) de la página de Aprendizaje y asistencia de Adobe Experience Manager 6.5.

### **Comunidad**

* **Debate de la comunidad de AEM**

   Ahora puede ver todos los anuncios de AEM y las referencias interesantes a blogueros internos y externos en un solo lugar. Consulte la sección [Discusión de la comunidad de AEM.](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

### Nuevos cursos y tutoriales para Experience Manager

| Contenido | Tipo de contenido | Descripción |
| -----------| ---------- | ---------- |
| [Introducción a Adobe Asset Link para usuarios empresariales](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.asset.link) | Curso | En este curso, aprenderá a utilizar las funciones y capacidades de Adobe Asset Link para impulsar su diseño creativo con contenido almacenado en Adobe Experience Manager Assets. El curso abarca todo tipo de temas, desde cómo iniciar un vínculo de recursos de adobe, operaciones básicas de recursos, opciones de búsqueda y exploración, y cómo colaborar eficazmente con otros usuarios. |
| [Introducción a los AEM Assets para usuarios empresariales](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.assets) | Curso | Obtenga información sobre cómo empezar a trabajar con AEM Assets para usuarios empresariales. Explore los conceptos básicos de los AEM Assets, las funciones de colaboración, la búsqueda, organización y descarga de recursos y sus representaciones. |
| [Introducción a los AEM Sites para usuarios empresariales](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites) | Curso | Aprenda a utilizar las funciones y capacidades principales de los AEM Sites para administrar las páginas web de su organización. El curso abarca desde una introducción hasta AEM Sites, conceptos básicos de creación, funciones avanzadas de creación y funciones de administración de páginas. |
| [Estructura del proyecto de AEM](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/implementing/developing/aem-project-content-package-structure.html) | Artículo | Describe los cambios necesarios en los proyectos de Adobe Experience Manager Maven para que sean compatibles con AEM Cloud Service. |
| [Modelos Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#sling-models) | Tutorial de vídeo | Obtenga información sobre la depuración de AEM como inicio rápido local del SDK de un Cloud Service mediante la consola web de modelos Sling. |
| [Componentes de la consola web de AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#components) | Tutorial de vídeo | Obtenga información sobre la depuración de AEM como inicio rápido local del SDK de Cloud Service mediante la consola web Componentes. |
| [Depuración del inicio rápido local del SDK de AEM mediante registros](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Tutorial de vídeo | Obtenga información sobre la depuración de AEM como inicio rápido local del SDK de Cloud Service mediante la consola web Bundles. |
| [Depuración remota de AEM como inicio rápido local del SDK de Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/remote-debugging.html) | Tutorial de vídeo | Obtenga información sobre la depuración remota de Java desde su IDE, lo que le permite avanzar en la ejecución de código en directo en AEM para comprender el flujo exacto de ejecución. |
| [Configuración de etiquetas inteligentes](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/metadata/smart-tags-technical-video-setup.html) | Tutorial de vídeo | Instrucciones paso a paso para integrar Adobe Experience Manager (AEM) con el servicio de contenido inteligente mediante Adobe I/O. |
| [Generación por lotes de documentos](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/interactive-communications/batch-generation-interactive-communications.html) | Artículo | Obtenga información sobre el uso de la API por lotes para producir varias comunicaciones interactivas a partir de una plantilla. |
| [Creación de un documento de canal de impresión en AEM Forms](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/ic-print-channel-tutorial/introduction.html) | Artículo | Conozca los pasos necesarios para crear una comunicación interactiva para el canal de impresión. |
| [Acceso a Adobe Asset Link](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/launch-adobe-asset-link.html) | Tutorial de vídeo | Obtenga información sobre cómo acceder al contenido almacenado en Adobe Experience Manager Assets (AEM Assets) sin salir de las aplicaciones de escritorio de Creative Cloud con las que está más familiarizado. |
| [Información general del panel Vínculo de recursos](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/panel-overview.html) | Tutorial de vídeo | Adobe Asset Link permite a los usuarios creativos examinar, buscar, extraer y registrar recursos almacenados en AEM Assets mediante el panel integrado en la aplicación de InDesign, Photoshop e Illustrator. Obtenga información sobre la interfaz de usuario del panel Adobe Asset Link y sus funciones. |
| [Búsqueda de recursos](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/asset-search.html) | Tutorial de vídeo | Los usuarios creativos pueden buscar recursos almacenados en AEM Assets mediante palabras clave o realizar una búsqueda en una ubicación específica. |
| [Versiones y comentarios de archivos](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/file-versioning-and-comments.html) | Tutorial de vídeo | Con el panel Vínculo de recursos de Adobe, puede acceder a los detalles de los archivos de los recursos de los AEM Assets, como miniaturas, metadatos básicos y versiones, desde el panel. |
| [Cierre de compra](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/check-in-check-out.html) | Tutorial de vídeo | Adobe Asset le permite extraer AEM Assets directamente de la aplicación creativa en la que está trabajando y puede empezar a realizar ediciones inmediatamente. |
| [Representación solo de colocación para AEM Assets](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/for-placement-only.html) | Tutorial de vídeo | Explore cómo crear y utilizar una representación solo para colocación (FPO) para recursos de AEM. |
| [Colocar copia](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/place-copy.html) | Tutorial de vídeo | Aprenda a utilizar recursos de AEM Assets mediante la operación Colocar copia. |
| [Descargar y cargar](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/download-and-upload.html) | Tutorial de vídeo | Obtenga información sobre cómo descargar y cargar archivos de recursos desde y hacia AEM Assets mediante el panel Vínculo de recursos. |
| [Archivos y colecciones](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/files-and-collections.html) | Tutorial de vídeo | Obtenga información sobre cómo acceder rápida y fácilmente a AEM Assets y colecciones desde el panel Vínculo de recursos. |
| [Descargar](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/sharing/download.html) | Tutorial de vídeo | Obtenga información sobre cómo descargar recursos y sus representaciones en su equipo local para usarlos y compartirlos. |

### Recursos adicionales

* [AEM como un servicio en la nube](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/landing/home.html)
* [Página de inicio de Learn &amp; Support de AEM 6.5](https://helpx.adobe.com/es/support/experience-manager/6-5.html)
* [Página de inicio de Learn &amp; Support de AEM 6.4](https://helpx.adobe.com/es/support/experience-manager/6-4.html)
* [Página de inicio de Learn &amp; Support de AEM 6.3](https://helpx.adobe.com/es/support/experience-manager/6-3.html)
* [Página de inicio de Learn &amp; Support de AEM 6.2](https://helpx.adobe.com/es/support/experience-manager/6-2.html)
* [Guía del usuario de Cloud Manager](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Versiones anteriores de la documentación de AEM](https://helpx.adobe.com/es/experience-manager/aem-previous-versions.html)
* [Inicio de la Ayuda de Dynamic Media Classic](https://docs.adobe.com/content/help/es-ES/dynamic-media-classic/using/home.html)
* [Notas de la versión de Dynamic Media](https://docs.adobe.com/content/help/en/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notas de la versión de Livefyre](https://docs.adobe.com/content/help/es-ES/livefyre/using/release-notes/c-rn.html)

## ![Icono](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign permite entregar, de forma intuitiva y automatizada, mensajes privados a través de canales de marketing en línea y sin conexión. Ahora puede anticipar los deseos de los clientes mediante experiencias basadas en sus hábitos y preferencias.

### Nuevas versiones de productos

[La versión](https://docs.adobe.com/content/help/es-ES/campaign-classic/using/release-notes/latest-release.html) de Adobe Campaign Classic 20.2 incluye:

* _Compatibilidad con Emoticon_ - Conector _de sinapsis de_ Azure - _Nuevas regulaciones de privacidad_
* Panel de control de Campaña: [Monitoreo activo del perfil](https://docs.adobe.com/content/help/en/control-panel/using/performance-monitoring/active-profiles-monitoring.html)

### Nuevos cursos y tutoriales de campaña

| Contenido | Tipo de contenido | Descripción |
| -----------| ---------- | ---------- |  
| [Introducción a Adobe Campaign Standard para usuarios empresariales](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | Curso | Obtenga información sobre cómo navegar por la interfaz, trabajar con envíos y crear y administrar datos de destinatario. |
| [Instalación y configuración del cliente de Adobe Campaign](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | Vídeo | Obtenga información sobre cómo descargar e instalar la consola de Adobe Campaign Client, crear y administrar las conexiones a varios entornos y comprobar el acceso a la consola de Adobe Campaign Client |

### Recursos de ayuda

* Adobe Campaign Standard: [Centro de ayuda](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/campaign-standard-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/release-notes/release-notes.html) - [Vídeos de procedimientos](https://docs.adobe.com/content/help/es-ES/campaign-standard-learn/tutorials/overview.html) - [Planificación de versiones](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/release-notes/release-planning.html) - [Últimas actualizaciones de la documentación](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Centro de ayuda](https://docs.adobe.com/content/help/es-ES/campaign-classic/using/campaign-classic-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/es-ES/campaign-classic/using/release-notes/latest-release.html) - [Vídeos de procedimientos ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [Últimas actualizaciones de la documentación](https://docs.adobe.com/content/help/es-ES/campaign-classic/using/documentation-updates.html)
* Panel de control de Adobe Campaign: [Documentación](https://docs.adobe.com/content/help/es-ES/control-panel/using/control-panel-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/es-ES/control-panel/using/release-notes.html) - Vídeos prácticos para [Campaign Standard](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) y [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Icono](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Updated **June 3, 2020**

* [Nuevas funciones de Advertising Cloud DSP](#adcloud-dsp)
* [Nuevas funciones en Advertising Cloud Search](#adcloud-search)

### Nuevas funciones de Advertising Cloud DSP {#adcloud-dsp}

Updated **June 23, 2020**

| Función | Descripción |
| -----------| ---------- |
| Migración de dominios | (Versión del 22 de junio) Advertising Cloud DSP ha migrado de https://www.tubemogul.com a [https://advertising.adobe.com](https://advertising.adobe.com). |
| Integración de Adobe Analytics | (Versión del 18 de junio) DSP ahora puede suprimir opcionalmente la métrica Costo de AMO de los datos que envía a Analytics. Para suprimir la métrica, póngase en contacto con su administrador de cuentas de Adobe. |
| Gráfico de dispositivos basados en personas | (Versión del 22 de junio) Los clientes de autoservicio de DSP ahora pueden aprovechar un gráfico de dispositivos (ya sea Adobe Experience Cloud Device Co-op |
| o LiveRamp) para la determinación de objetivos basada en personas y la administración de frecuencias en cualquier campaña nueva. Esto garantizará que llegue a sus audiencias en todos sus dispositivos propios y puede limitar su exposición a la publicidad. |
| Opción de exclusión de CCPA | (Versión del 22 de junio) Ahora puede comunicar a Advertising Cloud las solicitudes de exclusión de CCPA mediante un nuevo segmento de exclusión de la venta de CCPA, que puede crear desde [!UICONTROL Audiencias > Segmentos]. También puede recuperar informes mensuales de los ID que los clientes han enviado para solicitudes de exclusión de venta de la cuenta a) desde [!UICONTROL Audiencias > Segmentos] o b) mediante la API de tráfico de Advertising Cloud. Para obtener más información, consulte https://docs.adobe.com/content/help/en/advertising-cloud/all/privacy/ad-cloud-ccpa-opt-out-of-sale.html. |
| Comprobación doble de la seguridad auténtica de la marca | (Versión del 22 de junio) Los anunciantes ahora pueden destinatario con una sola oferta previa de ID de segmento DoubleVerify, con filtros exhaustivos de seguridad de marca para imitar sus reglas de bloqueo posteriores a la oferta con DoubleVerify. Ahora puede hacerlo en la sección de segmentación Calidad de los medios de la configuración del anunciante en [!UICONTROL Configuración > Anunciante]. Para obtener más información sobre el servicio, póngase en contacto con programmaticsales@doubleverify.com. Se aplican tarifas adicionales para esta función. |
| Optimización de CPA/ROAS | (Versión del 20 de mayo) Los administradores de Campañas ya no necesitan limitar las nuevas colocaciones dentro de los paquetes para evitar una sobreasignación del presupuesto. Las colocaciones ahora reciben una asignación de presupuesto dinámica en función de su rendimiento de CPM o CPA/ROAS. |
| [!UICONTROL Página principal de Campaña] | (Versión del 3 de junio) Hay disponibles nuevas métricas de ritmo a nivel de campaña basadas en el presupuesto de campaña proporcionado y el tiempo transcurrido. |
| [!UICONTROL Ubicaciones] | (Versión del 22 de junio) Se eliminaron los filtros Diversidad del sitio y Tamaño del reproductor para simplificar la configuración de la ubicación. |
| Previsión de ubicación | (Versión del 3 de junio) Para las colocaciones de vídeo y CTV con optimización de nivel de colocación, la configuración de colocación ahora incluye previsiones para varias longitudes de publicidad (15 segundos y 30 segundos). También incluyen previsiones para el inventario VAST y VPAID. |
| [!UICONTROL Inventario] | (Versión beta del 22 de junio) Un nuevo formulario de ID de oferta le permite configurar rápidamente una operación privada que ya ha negociado. |
|  | (Versión beta del 22 de junio) Ya está disponible la versión previa interactiva para el inventario VAST. Puede configurar una sola publicidad y colocación interactiva previa, reduciendo el número de publicidades y colocaciones. |
| Objetivo de Audiencia ACTV | (Versión del 18 de junio) Las lentes de Audiencia permiten a los usuarios crear y aplicar lecturas de audiencia secundarias a sus flujos de trabajo de planificación, pedidos y sistema de informes. Esto les permite (1) obtener perspectivas rápidas en audiencias secundarias, (2) tener flexibilidad para realizar transacciones en audiencias preferidas y (3) medir la ejecución de una campaña a través del &quot;objetivo&quot; de múltiples audiencias. |

### Nuevas funciones en [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Función | Descripción |
| -----------| ---------- |
| [!UICONTROL Campañas] | Microsoft Advertising (anteriormente Bing Ads) está desaprobando las métricas de posición promedio después del 30 de septiembre de 2020. Como preparación para esto, a partir del 11 de julio, se ignorarán las restricciones basadas en posiciones y también se ignorarán las condiciones basadas en posiciones en cualquier tipo de restricción. |
| [!UICONTROL Información sobre los anuncios] | (Versión del 13 de junio) Se han eliminado las siguientes perspectivas:<br/><br/><ul><li>Rendimiento del Destinatario de Audiencia (la versión más reciente)</li><li>Rendimiento histórico (la versión más reciente)</li><li>Tipo de coincidencia (la versión más reciente)</li><li>Auditoría de configuración (la versión más reciente)</li><li>Anuncio previo de portafolios (heredado)</li></ul><br/>Las perspectivas restantes son versiones heredadas y la etiqueta _Legacy_ se ha eliminado de los nombres. Además, se eliminaron los modos de edición/Live. |

## ![Icono](/assets/magento.png) [!DNL Magento] {#magento}

Para las notas de la versión de Magento, consulte:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Icono](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] es una aplicación completa para la gestión de clientes potenciales y para los especialistas en marketing B2B que buscan transformar las experiencias de los clientes al interactuar en todas las etapas de los viajes de compra complejos.

### Actualizaciones centrales de Marketo Engage

Consulte las [!DNL Marketo][notas de la versión](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) para obtener la información más reciente sobre la versión.

### Próximas funciones

Las siguientes funciones se lanzarán durante todo el trimestre:

| Función | Descripción |
|------|---------|
| [!DNL Bizible] | <ul><li>Nueva segmentación basada en cuentas</li><li>Almacenamiento de filtros específicos del tablero</li><li>Exportación de tableros Bizible en PDF</li></ul> |
| Conexión de ventas | Actualizaciones y mejoras de la ventana de composición y del centro de comandos |

### Anuncios

**Centro de éxito de Marketo Engage:** lanzamiento en febrero de 2020. El Centro de éxito es un centro de ayuda integrado en el producto que le permite buscar en la Documentación del producto, la Comunidad, las guías de inicio prácticas, el contenido de adopción de acceso y mucho más. Nota: Esta función se lanzará como una versión beta en ANZ y se comercializará en Norteamérica más adelante en el trimestre.

### Degradaciones

* **Parámetro de API de Asset &quot;_method&quot;:** `_method` a partir de septiembre de 2020, los puntos de conexión de Asset API ya no aceptarán &quot;_method&quot; para pasar parámetros de consulta en un cuerpo de POST para omitir las limitaciones de longitud de URI.
* **Degradación de compatibilidad con Internet Explorer:** a partir de la versión del 31 de julio de 2020, la interfaz de usuario de Marketo Engage dejará de ser compatible con Internet Explorer.

Para ver las notas de la versión acumulativas e históricas, consulte [Notas de la versión de Marketo](https://docs.marketo.com/x/CgA6Ag).
