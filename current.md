---
title: Últimas notas de la versión
description: Conozca las últimas notas de la versión, las nuevas funciones y la nueva documentación de los  [!DNL Experience Cloud]  productos y servicios. Encuentre ayuda y tutoriales nuevos acerca de [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise] y [!DNL Document Cloud].
doc-type: release notes
last-update: July 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: bd6e90a7cbb0f07b21c65b6486fb65327fce6003
workflow-type: tm+mt
source-wordcount: '5574'
ht-degree: 49%

---

# Notas de la versión de Adobe Experience Cloud, julio de 2022

![Titular](assets/experience-cloud-banner-3.png)

Como con Experience Maker, la ruta hacia el éxito empieza por [Experience League](https://experienceleague.adobe.com/?lang=es#home). Encuentre una amplia biblioteca de documentación de procedimientos, tutoriales autoguiados, vídeos explicativos y cursos para todos los niveles y funciones, una comunidad en línea de compañeros y asistencia técnica especializada cuando la necesite.

>[!NOTE]
>
>Para recibir una notificación mensual por correo electrónico acerca de las actualizaciones realizadas en esta página, suscríbase a la [Actualización de producto prioritario de Adobe](https://www.adobe.com/subscription/priority-product-update.html). Vuelva con frecuencia para mantenerse al tanto de lo que está pasando en Experience League.

Última actualización: **19 de julio de 2022**

* [[!DNL Experience League] Eventos](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud: componentes y administración de la interfaz central](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Streaming Media Analytics]](#sma)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Experience Manager Guides]](#xml-doc)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [Modelos de experiencia digital: tutoriales](#blueprints)

¿Necesita ayuda? Visite [Experience League](https://experienceleague.adobe.com/?lang=es#home) para encontrar la documentación técnica y de los productos, cursos seleccionados por Adobe, tutoriales de vídeo, respuestas rápidas, conocimiento de la comunidad y formación impartida por instructores.

## ![Icono](/assets/experience-league.png) Eventos de [!DNL Experience League] {#events}

Los eventos de Experience League son un buen lugar para aprender, interactuar y obtener respuestas de los expertos en productos de Adobe. Consulte [Eventos](https://experienceleague.adobe.com/events/?lang=es) Experience League para permanecer actualizado para julio de 2022.

Actualizado **17 de julio de 2022**

| Evento | Tipo | Descripción |
| -----------|---------- | ----|
| [Pregunten a los expertos: Datastreams y preparación de datos](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=en) | Experience League LIVE  | En esta final de tres sesiones relativas a la recopilación de datos para Adobe Experience Cloud, nuestros expertos ofrecerán una explicación más profunda de las capacidades avanzadas de recopilación de datos de Adobe, incluidas funciones como la preparación para la recopilación de datos. Al final de esta sesión, los asistentes se sentirán confiados con las últimas y más potentes funciones para recopilar datos de experiencias digitales <br>**Fecha:** 21 de julio a las 9 a.m. PDT - [Detalles](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=en) |

{style=&quot;table-layout:auto&quot;}

Consulte [Eventos](https://experienceleague.adobe.com/events/?lang=en) en Experience League para mantenerse actualizado sobre los próximos eventos y episodios anteriores.

## ![Icono](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] proporciona información detallada, actualizaciones de estado y notificaciones por correo electrónico sobre los productos de Adobe y las interrupciones y sesiones de mantenimiento de los servicios. Puede comprobar el estado en [status.adobe.com](https://status.adobe.com/es).

Para obtener la información más reciente sobre la versión, consulte las [notas de la versión](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=es#status) del Estado del sistema de Adobe.

## ![Icono](/assets/ec_appicon_24.png) Experience Cloud: componentes y administración de la interfaz central {#ecloud}

Los [componentes de la IU central](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=es) de Experience Cloud incluyen las funciones disponibles en la página de inicio y el encabezado de producto persistente. Estas funciones incluyen la configuración del perfil del usuario, las preferencias y la búsqueda. También puede encontrar ayuda sobre la administración de usuarios y productos, los atributos del cliente y las audiencias de Experience Cloud.

### Actualización de aprovisionamiento

Actualizado: **19 de julio de 2022**

>[!IMPORTANT]
>
>Revise el siguiente aviso sobre el aprovisionamiento de Experience Cloud.

Adobe está actualizando su aprovisionamiento para proporcionar a todos los clientes Experience Cloud acceso a las funcionalidades básicas que ayudan a la interoperabilidad entre algunos productos Experience Cloud. Los usuarios tendrán Adobe Experience Platform como un nuevo derecho añadido a sus organizaciones Experience Cloud, con [!UICONTROL Recopilación de datos] como servicio incluido.

Adobe Experience Platform [!UICONTROL Recopilación de datos] incluye [etiquetas](https://experienceleague.adobe.com/docs/tags.html?lang=en) para una administración universal de etiquetas simplificada, y ofrece una infraestructura de datos de flujo fiable, sólida y completa. Las etiquetas simplifican la recopilación de datos de experiencias del cliente y optimizan el envío de experiencias.

Con esta actualización, los administradores pueden ver cambios o adiciones al Admin Console:

1. La tarjeta de producto de Adobe Experience Platform en el Admin Console incluirá:

   * Places
   * Garantía
   * Espacio de nombre de identidad
   * Zonas protegidas
   * Modelo de datos de experiencia
   * Esquemas
   * Corrientes de datos
   * ID de visitante

   Para las organizaciones que actualmente no usan Experience Platform, ahora verá la variable _Adobe Experience Platform_ en el Admin Console, incluidas las funcionalidades mencionadas anteriormente.

   Para organizaciones que actualmente utilizan Experience Platform, _Lugares_ ahora se consolidará en la tarjeta de Experience Platform.

1. La recopilación de datos de Adobe Experience Platform (anteriormente, Launch) y la privacidad seguirán apareciendo como tarjetas de producto independientes de las demás funciones de Experience Platform.

Para obtener más información sobre las nuevas funciones, visite sus páginas respectivas en el Experience League:

* [Recopilación de datos](https://experienceleague.adobe.com/docs/analytics/analyze/reports-analytics/reporting-interface/overview-data-collection.html)
* [Places](https://experienceleague.adobe.com/docs/places/using/home.html?lang=es)
* [Garantía](https://experienceleague.adobe.com/docs/platform-learn/implement-mobile-sdk/app-implementation/assurance.html%3Flang%3Dde)
* [Espacio de nombre de identidad](https://experienceleague.adobe.com/docs/experience-platform/identity/home.html?lang=es)
* [Zonas protegidas](https://experienceleague.adobe.com/docs/experience-platform/sandbox/home.html?lang=es)
* [Modelo de datos de experiencia](https://experienceleague.adobe.com/docs/experience-platform/xdm/home.html?lang=es)
* [Esquemas](https://experienceleague.adobe.com/docs/experience-platform/xdm/schema/composition.html?lang=es)
* [Corrientes de datos](https://experienceleague.adobe.com/docs/experience-platform/edge/datastreams/overview.html?lang=en)
* [ID de visitante](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services.html?lang=en#section_3C9F6DF37C654D939625BB4D485E4354)
* [Privacidad](https://experienceleague.adobe.com/docs/experience-platform/privacy/home.html?lang=es)

Actualización de funciones: **11 de julio de 2022**

| Función | Descripción |
| ------- | ------- |
| Inicio unificado: Widget de acceso rápido | **Navegar más rápido:** ahora puede personalizar aún más su experiencia en casa y decidir qué aplicaciones están al alcance de su mano. Utilice la nueva función de anclaje para seleccionar qué aplicaciones aparecen en primer plano y centradas en su [!UICONTROL Acceso rápido]. <br>**No se pierda nada con el posicionamiento inteligente:** sus nuevas aplicaciones ahora son más fáciles de encontrar. Las aplicaciones recién asignadas muestran un _Nuevo_ distintivo y autoanclaje a [!UICONTROL Acceso rápido]. |

{style=&quot;table-layout:auto&quot;}

**Más recursos de ayuda de [!DNL Experience Cloud Central UI Components] y Administración**

* [Notas de la versión](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=es) para los componentes centrales de la IU de Experience Cloud
* [Administración de usuarios y productos](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) Experience Cloud (administración)
* [Notas de la versión](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=es) del servicio Places
* Documentación del producto para [People: atributos del cliente y biblioteca de audiencias](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=es)
* [Búsqueda unificada de objetos y entidades](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=es)

## ![Icono](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

Información sobre la versión más reciente y la nueva documentación de [!DNL Experience Platform] y el [!UICONTROL SDK móvil]:

Lanzamiento previsto: **27 de julio de 2022**

* [Notas de la versión de Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=es)

### Nuevos tutoriales y cursos de [!DNL Experience Platform] {#tutorials-platform}

Nuevos tutoriales, artículos y cursos de vídeo publicados para [!DNL Experience Platform].

| Publicadas | Nombre | Tipo | Descripción | Aplicación |
| -----------| ---------- | ---------- | ---------- |---------- |
| Julio de 2022 | [Monitorización del reenvío de eventos](https://experienceleague.adobe.com/docs/platform-learn/data-collection/event-forwarding/monitor.html) | Vídeo | Obtenga información sobre cómo monitorizar el reenvío de eventos en la interfaz de recopilación de datos. | Recopilación de datos |
| Julio de 2022 | [Monitorización de la ingesta de datos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/monitoring/monitoring-dashboard.html) | Vídeo | Obtenga información sobre cómo monitorizar y rastrear datos que se incorporan a Adobe Experience Platform mediante el panel de monitorización. | Recopilación de datos |
| Julio de 2022 | [Importación de datos de ejemplo en Adobe Experience Platform](https://experienceleague.adobe.com/docs/platform-learn/tutorials/import-sample-data.html?lang=es) | Artículo | Aprenda a configurar un entorno limitado de Experience Platform con datos de ejemplo. Con una colección de Postman, puede crear grupos de campos, esquemas, conjuntos de datos y luego importar datos de ejemplo en Experience Platform. | Experience Platform |
| Julio de 2022 | [Coincidencia de segmentos que recibe datos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-receiving-data.html) | Vídeo | Con la coincidencia de segmentos, sus socios estratégicos pueden compartir los datos con usted. En este vídeo, aprenda a aprobar y recibir los datos, y dónde puede verlos y agregarlos a sus propios segmentos. | Experience Platform - Segmentos |
| Julio de 2022 | [Pregunte a los expertos: Conexiones de Real-Time CDP](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-06-23-22.html?lang=en) | Experience League LIVE video | En este segundo de tres sesiones de transmisión en directo sobre la recopilación de datos, nuestros expertos favoritos ofrecen un análisis detallado del Adobe RTCDP [!UICONTROL Conexiones], donde los clientes pueden reenviar eventos a destinos que no sean de Adobe mediante un sistema de administración de etiquetas del lado del servidor. | Recopilación de datos |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

Consulte [Notas de la versión y registros de cambios](https://aep-sdks.gitbook.io/docs/release-notes) para conocer los SDK de Adobe Experience Platform Mobile.

## ![Icono](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Versión siguiente: **20 de julio de 2022**

Última actualización: **13 de julio de 2022**

* [Notas de la versión](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=es) de Adobe Analytics
* [Tutoriales y documentación del producto](https://experienceleague.adobe.com/docs/analytics.html?lang=es) de Adobe Analytics

### AppMeasurement {#appm}

Versión: **2.22.4**

* [Notas de la versión de AppMeasurement para JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=es)

### Nuevos tutoriales y cursos de [!DNL Analytics] {#tutorials-analytics}

Nuevos tutoriales, artículos y cursos de vídeo publicados para Adobe Analytics.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Julio de 2022 | [Mejoras de flujo en 2022](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analyzing-customer-journeys/flow-improvements.html) | Vídeo | Obtenga información sobre algunas de las buenas mejoras realizadas en [!UICONTROL Flujo] visualización. Las mejoras incluyen permitirle configurar el inicio o el final de la ruta que le interese, filtrar una columna para incluir o excluir un elemento específico y definir ajustes avanzados preconfigurables. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

Última actualización: **12 de julio de 2022**

* [Notas de la versión](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=es) de Customer Journey Analytics
* [Tutoriales y documentación del producto](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=es) de Customer Journey Analytics

### Nuevos tutoriales y cursos para Customer Journey Analytics {#tutorials-cja}

Nuevos vídeos, tutoriales o cursos publicados para CJA.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Julio de 2022 | [Configurar el panel de elementos siguiente y anterior](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/panels/configure-next-previous-item-panel.html) | Vídeo | Obtenga información sobre cómo configurar el panel de elementos siguiente y anterior en [!DNL Customer Journey Analytics]. Este panel genera tablas y visualizaciones para identificar el elemento siguiente o anterior para un valor de dimensión específico. |
| Julio de 2022 | [Crear una anotación](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/annotations/create-an-annotation.html?lang=en) | Vídeo | Aprenda a crear una anotación en su [!DNL Customer Journey Analytics] proyectos en los que se producen eventos como inicios de campañas, problemas de datos y festivos. Esta función informa a los usuarios de las variaciones métricas en estas fechas o intervalos de fechas. |
| Julio de 2022 | [Crear de un filtro rápido](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/components/filters/create-a-quick-filter.html) | Vídeo | Cree filtros rápidos directamente en sus [!DNL Customer Journey Analytics] proyectos y eluda la complejidad del generador de filtros. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

Última actualización: **23 de marzo de 2022**

* [Notas de la versión](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=es) de [!DNL Streaming Media Analytics]
* [Tutoriales y documentación del producto](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=es) de [!DNL Streaming Media Analytics]

## ![Icono](/assets/audience-manager.png) Audience Manager {#aam}

Correcciones y mejoras en Audience Manager:

| Mejora | Descripción |
| -----------| ---------- |  
| Validador para fuentes de datos de destino pertenecientes a otras empresas | Audience Manager publicó una mejora en el [proceso de incorporación de datos por lotes](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=es). Para evitar la incorporación accidental de archivos y datos en fuentes de datos de destino propiedad de otros socios, Audience Manager ha añadido un requisito de asignación entre el ID del socio (PID) y las fuentes de datos (DPID) propiedad de otros socios. <ul><li>Vea también el campo __DPID_TARGET_DATA_OWNER_ en [Requisitos de tamaño de archivo y nombre de Amazon S3 para archivos de datos entrantes](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=es#name-elements).</li><li>Los consultores y el Servicio de atención al cliente internos de Adobe deberían leer el documento [Administración del acceso de incorporación para datos de segundo nivel](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=es) para obtener información acerca de la nueva mejora de la asignación requerida y cómo solicitar una nueva asignación.</li><li>_No_ es necesario para solicitar una asignación para las relaciones de uso compartido de datos existentes. La asignación _tampoco_ es obligatoria al incorporar datos en fuentes de datos de destino que pertenecen a su PID.</li></ul> |

{style=&quot;table-layout:auto&quot;}

Para obtener recursos de ayuda, consulte [Documentación y tutoriales de Audience Manager](https://experienceleague.adobe.com/docs/audience-manager.html?lang=es) en Experience League.

## ![Icono](/assets/aem.png) Adobe Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Experience Manager. Adobe recomienda a los clientes con implementaciones On-Premise implementar los parches más recientes para garantizar más estabilidad, seguridad y rendimiento.

Adobe recomienda visitar la página [Actualizaciones de versión y hoja de ruta de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=es) para mantenerse al día respecto a la información de la versión.

### Vídeos de actualización de productos

* [Vídeo de información general sobre la versión de junio de 2022](https://video.tv.adobe.com/v/344308/?quality=12) para ver un resumen de la versión 2022.6.

Vídeos de actualización de productos anteriores:

* [Vídeo de información general sobre la versión de mayo de 2022](https://video.tv.adobe.com/v/343321/?quality=12) para obtener un resumen de las funciones añadidas en la versión 2022.5.0 (mayo de 2022).
* [Vídeo de información general sobre la versión de abril de 2022](https://video.tv.adobe.com/v/342612?quality=12)
* [Vídeo de información general sobre la versión de marzo de 2022](https://video.tv.adobe.com/v/341465)
* [Vídeo de información general sobre la versión de enero de 2022](https://video.tv.adobe.com/v/340120)
* [Vídeo de información general sobre la versión de diciembre de 2021](https://video.tv.adobe.com/v/339278)
* [Vídeo de información general sobre la versión de octubre de 2021](https://video.tv.adobe.com/v/338253)
* [Vídeo de información general sobre la versión de septiembre de 2021](https://video.tv.adobe.com/v/337381)

### Experience Manager [!DNL Sites] como [!DNL Cloud Service]

Nuevas funciones de [!DNL Sites]:

* A [nueva interfaz de usuario](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/administering/content-fragments/content-fragments-console.html?lang=en) ya está disponible para administradores de contenido y autores de contenido para administrar de forma eficaz (realizar acciones como publicar, cancelar la publicación, copiar y mover), buscar/filtrar y crear fragmentos de contenido para casos de uso sin encabezado.

* El nuevo [Componente Tabla de contenido](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/components/tableofcontents.html?lang=en) funciona no solo con la variable [!UICONTROL Componentes principales] pero con todos los componentes, procesar automáticamente la tabla de contenido en las páginas de contenido. Y, como se procesa en el lado del servidor y se almacena en caché completamente por parte del Dispatcher, también es eficiente cargar.

### Experience Manager [!DNL Assets] como [!DNL Cloud Service]

Nuevas funciones de [!DNL Assets]:

* Experience Manager [!DNL Assets] utiliza las capacidades de Adobe Sensei AI ahora [distinguir entre colores en una imagen y aplicarlos como etiquetas automáticamente al ingerirlos](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/color-tag-images.html?lang=es). Estas etiquetas permiten una experiencia de búsqueda mejorada, basada en la composición de color de la imagen. Puede configurar el número de colores, dentro de un rango de uno a cuarenta, que están etiquetados en una imagen para que pueda buscar imágenes basadas en esos colores más adelante.

### Experience Manager Forms as a Cloud Service

Nuevas funciones de [!DNL Forms]:

* [Integrar [!UICONTROL Forms adaptable] con Microsoft® Power Automate](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/forms-microsoft-power-automate-integration.html?lang=en): Ahora puede configurar un formulario adaptable para ejecutar un flujo de nube Microsoft® Power Automate en el envío. El formulario adaptativo configurado envía los datos capturados, los archivos adjuntos y el documento de registro al flujo de Power Automate Cloud para su procesamiento. Le ayuda a crear una experiencia de captura de datos personalizada mientras aprovecha el poder de Microsoft® Power Automate para crear lógicas empresariales en torno a los datos capturados y automatizar los flujos de trabajo de los clientes.

**Asistente para crear un formulario adaptable:** Puede utilizar el asistente para usuarios empresariales para crear rápidamente [!UICONTROL Forms adaptable]. El asistente proporciona un desplazamiento rápido por las fichas para seleccionar fácilmente la plantilla preconfigurada, el estilo, los campos y las opciones de envío para crear un formulario adaptativo.

### Experience Manager as a Cloud Service Foundation

Novedades:

Como se mencionó en las notas de la versión de mayo (2022.5.0), se eliminó la opción &quot;Agregar árbol&quot; en la pestaña Distribuir de la pantalla del administrador del agente de replicación. Los paquetes con una jerarquía de contenido de árbol deben replicarse usando Administrar publicación o Flujo de trabajo para publicar árbol de contenido.

### [!DNL Cloud Manager]

Novedades:

* [!DNL Cloud Manager] los usuarios ahora pueden acceder a tutoriales de vídeo útiles desde el [!UICONTROL Bienvenido] en la página de aterrizaje en cualquier momento.

* La ventana emergente del [Restaurar contenido](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/backup.html?lang=en) de la página de detalles de entornos ahora muestra una lista práctica de comandos git que permite al usuario ver los cambios localmente.

### Nuevos cursos y tutoriales para Experience Manager {#tutorials-aem}

Nuevos vídeos, tutoriales y cursos publicados durante el mes pasado.

| Publicadas | Nombre | Tipo | Descripción | Aplicaciones |
| -----------| ---------- | ---------- | ---------- |---------- |
| Julio de 2022 | [Aproveche al máximo la administración de flujos de trabajo empresariales](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/workflow.html?lang=en) | Vídeo | Descubra las ventajas de utilizar flujos de trabajo para la administración de recursos y cómo crearlos rápidamente. | AEM: Administración del flujo de trabajo de experiencia |
| Julio de 2022 | [Ofrecer experiencias sin objetivos con Adobe Experience Manager](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/headless.html?lang=en) | Vídeo | Obtenga información sobre la administración de experiencias sin objetivos mediante el Experience Manager más reciente [!UICONTROL Fragmento de contenido] mejoras y la nueva API de GraphQL para la entrega de contenido sin encabezado. | Experience Manager [!DNL Sites] |
| Julio de 2022 | [Hacer que los metadatos funcionen para su negocio en Adobe Experience Manager Assets](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/metadata.html?lang=en) | Vídeo | Aprenda a sacar el máximo partido a los metadatos en AEM Assets reduciendo la carga de trabajo de etiquetas de recursos y haciendo que sus recursos sean más fáciles de buscar. | Experience Manager [!DNL Assets] |
| Julio de 2022 | [aplicación iOS](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/ios-swiftui-app.html) | Vídeo | Las aplicaciones de ejemplo son una buena manera de explorar las capacidades sin objetivos de Adobe Experience Manager. Esta aplicación de iOS muestra cómo consultar contenido mediante AEM [!UICONTROL API de GraphQL] uso de consultas persistentes. | Experience Manager [!DNL Assets], [!DNL Sites] |
| Julio de 2022 | [Aplicación Android™](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/android-app.html) | Vídeo | Esta aplicación Android™ muestra cómo consultar el contenido mediante la variable [!UICONTROL API de GraphQL] de AEM. | Experience Manager [!DNL Assets], [!DNL Sites] |
| Julio de 2022 | [Configuración de OSGi para Adobe Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/deploying/configuring-osgi.html?lang=en) | Vídeo | Aprenda a configurar OSGI para AEM CS. Por ejemplo, obtenga información sobre la administración de paquetes OSGi y la administración de los ajustes de configuración de los componentes OSGi a través de archivos de configuración que forman parte de un proyecto de código AEM. | AEM as a Cloud Service |
| Julio de 2022 | [Sustituir propiedades del modelo de datos del formulario](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/adaptive-forms/override-fdm-values.html?lang=en) | Vídeo | Obtenga información sobre cómo anular las propiedades del modelo de datos de formulario para facilitar la prueba de un modelo de datos de formulario con diferentes extremos. | AEM [!DNL Forms] |

{style=&quot;table-layout:auto&quot;}

### Información de la versión de Experience Manager

Todas las notas de la versión de Experience Manager se mantienen en las páginas siguientes:

* [Información sobre la versión de Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=es)
* [Notas de la versión de Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/release-notes/current.html?lang=en)
* [Notas de la versión del servicio de conversión automatizada de formularios](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=es)
* [Notas de la versión de Experience Manager 6.5 Service Pack](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=es)
* [Notas de la versión de Experience Manager 6.4 Cumulative Fix Pack](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=es)
* [Notas de la versión de Experience Manager Assets Dynamic Media](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=es)
* [Notas de la versión de Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=es)
* [Notas de la versión de la aplicación de escritorio de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=es)
* [Notas de la versión de Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=es)
* [Notas de la versión de Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=es)
* [Notas de la versión de Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=es)

### Otros recursos de ayuda para Experience Manager

* [Guías de Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=en)
* [Guía del usuario de Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/introduction.html?lang=en)
* [Formación y asistencia de Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=es)
* [Formación y asistencia de Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=es)
* [Formación y asistencia de Experience Manager 6.3](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=es)
* [Formación y asistencia de Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=es#previous-updates)
* [Versiones anteriores de la documentación de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Inicio de la Ayuda de Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=es)
* [Documentación de Experience Manager: Actualizaciones recientes](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=es#aem-as-a-cloud-service)

## ![Icono](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] es una aplicación implementada en AEM. Es una potente solución de administración de contenido de componentes (CCMS) de nivel empresarial que permite la compatibilidad nativa con DITA en Adobe Experience Manager, lo que permite a AEM gestionar la creación y la entrega de contenido basado en DITA.

Obtenga más información sobre [[!DNL Experience Manager Guides]](https://www.adobe.com/es/products/xml-documentation-for-experience-manager/features.html).

### Recursos adicionales

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-guides-learn/videos/overview.html?lang=en): tutoriales sobre Experience League
* [[!DNL Experience Manager Guides] Aprendizaje y asistencia](https://helpx.adobe.com/es/support/xml-documentation-for-experience-manager.html): documentación del producto

## ![Icono](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Consulte los siguientes vínculos para ver las notas de la versión de Adobe Commerce:

* [Notas de la versión de Adobe Commerce y Magento Open Source 2.4.x](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Notas de la versión de Cloud Suite](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### Nuevos tutoriales y documentación de Adobe Commerce {#tutorials-commerce}

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Julio de 2022 | [Guía de introducción a Adobe Commerce](https://experienceleague.adobe.com/docs/commerce-admin/start/guide-overview.html) | Documentación del producto | Una guía dirigida a los comerciantes y a los administradores de sistemas que son nuevos en Adobe Commerce y Magento Open Source. Obtenga información general sobre la plataforma desde su perspectiva e información detallada sobre las funciones básicas que habilitan una tienda funcional. |
| Julio de 2022 | [Guía del usuario del Page Builder](https://experienceleague.adobe.com/docs/commerce-admin/page-builder/guide-overview.html) | Documentación del producto | Obtenga información sobre las funciones de Page Builder , incluido un tutorial de tres partes para la creación de componentes de contenido básicos. Esta guía es para administradores. Supone una comprensión básica de la configuración y funcionalidad principales de Adobe Commerce. |
| Julio de 2022 | [Guía de B2B para Adobe Commerce](https://experienceleague.adobe.com/docs/commerce-admin/b2b/guide-overview.html) | Guía de administración | Obtenga información detallada sobre cómo instalar y habilitar este módulo, incluida la configuración y administración de sus funciones. |
| Julio de 2022 | [B2B para Adobe Commerce: tutoriales](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/b2b/company-accounts.html?lang=en) | Vídeo (múltiple) | Obtenga información sobre [!UICONTROL Compañías] en Adobe Commerce. Puede administrar las cuentas de su empresa y todas las solicitudes de aprobación pendientes aparecerán en la parte superior de la lista. |
| Julio de 2022 | [Uso de la herramienta Parche de Calidad](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/quality-patch-tool.html) | Vídeo | Obtenga información sobre [!UICONTROL Herramienta Parche de Calidad], que es una herramienta de línea de comandos que proporciona parches de calidad para Adobe Commerce y Magento Open Source. |
| Julio de 2022 | [El tablero de herramientas de análisis de todo el sitio](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/site-wide-analysis-tool.html) | Vídeo | Obtenga información sobre la herramienta de análisis de todo el sitio. Esta función es una herramienta de autoservicio proactiva y un repositorio central que incluye información detallada del sistema y recomendaciones para garantizar la seguridad y la operabilidad de la instalación de Adobe Commerce. |
| Julio de 2022 | [Usar servicios de pago](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/payment-services.html) | Vídeo | Aprenda a utilizar [!UICONTROL Servicios de pago] para reducir los gastos operativos, aumente los ingresos. |
| Julio de 2022 | [Administrar estado de pedido](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/orders/order-status.html) | Vídeo | Obtenga información sobre cómo comprobar el estado de un pedido y sus detalles, y cómo cambiar el estado de un pedido si es necesario. |
| Julio de 2022 | [Herramientas de marketing](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/marketing/catalog-price-rules.html?lang=en) | Vídeo (múltiple) | Obtenga información sobre la creación de una regla de precio de catálogo, reglas de precio de carro de compras, reglas de producto relacionadas, búsqueda en vivo y más. |
| Julio de 2022 | [Innovaciones en la personalización de contenido que ofrecen valor empresarial](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/content-perosonalization.html?lang=en) | Vídeo | Vea las presentaciones de Skills Builder y aprenda sobre las innovaciones recientes en la solución Contenido de Adobe que le ayudan a democratizar la creación de contenido, hacer que la entrega omnicanal sea una brisa y escalar la personalización. |
| Julio de 2022 | [Administración de catálogos](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/catalog/seo-url-rewrites.html) | Vídeos | Obtenga información sobre la administración de catálogos en Adobe Commerce. crear una categoría, administrar productos en una categoría, administrar inventario y mucho más. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/target.png) [!DNL Adobe Target] {#target}

Última actualización: **30 de junio de 2022**

* Para obtener información previa al lanzamiento, consulte [Versión preliminar de Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=es)
* Para obtener información actual, consulte [Notas de la versión de Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=es)

### Nuevos cursos y tutoriales de Adobe Target {#tutorials-target}

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Julio de 2022 | [Crear audiencias](https://experienceleague.adobe.com/docs/target-learn/tutorials/audiences/create-audiences.html) | Vídeo | Aprenda a crear y guardar audiencias personalizadas en [!DNL Target] para usar en sus actividades. |
| Julio de 2022 | [Personalización y automatización con Adobe Target](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/data-and-insights/2022/personalize.html?lang=en) | Vídeo | Aprenda los conceptos básicos de la automatización y optimización de las capacidades de Adobe Target mediante [!UICONTROL Segmentación automática] y [!UICONTROL Personalizaciones automáticas]. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign permite entregar, de forma intuitiva y automatizada, mensajes privados a través de canales de marketing en línea y sin conexión. Ahora puede anticipar los deseos de los clientes mediante experiencias basadas en sus hábitos y preferencias.

### Últimas versiones de productos de Campaign

* [Versión de Campaign v7.3](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=es)
* [Versión de Panel de control de Campaign de junio](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=en)
* [tutoriales y cursos](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html?lang=es#tutorials-campaign) en Experience League

### Nuevos tutoriales y cursos [!DNL Campaign] {#tutorials-campaign}

Nuevos vídeos, tutoriales o cursos publicados de Adobe Campaign.

| Publicadas | Nombre | Tipo | Descripción | Aplicaciones |
| -----------| ---------- | ---------- | ---------- |---------- |
| Julio de 2022 | [Panel de control de Campaign para modelos de alojamiento híbridos](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/control-panel-for-hybrid-hosting-models.html) | Vídeo | Obtenga información sobre cómo habilitar el Panel de control de Campaign para los modelos de alojamiento híbridos de Adobe Campaign, acceder al Panel de control de Campaign y desbloquear funciones clave. | Panel de control |
| Julio de 2022 | [Monitorización de las salidas y la latencia](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-throughputs-and-latency.html?lang=es) | Vídeo | Obtenga información sobre cómo monitorizar la entrega mediante mensajes y latencias de mensajes transaccionales de la instancia de campaign. | Panel de control |
| Julio de 2022 | [Monitorización de flujos de trabajo para optimizar el uso de recursos](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-workflows.html?lang=es) | Vídeo | Obtenga información sobre cómo monitorizar el uso temporal del almacenamiento de sus flujos de trabajo y dónde configurar la configuración del flujo de trabajo para evitar problemas de la base de datos o del flujo de trabajo en su instancia. | Panel de control |
| Julio de 2022 | [Desarrollo y personalización de modelos de datos en Adobe Campaign Classic](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/data-models.html?lang=en) | Vídeo (eventos del generador de habilidades) | Únase a esta sesión con nuestro instructor de Campaign para aprender a desarrollar un esquema de datos dentro de un modelo de datos dentro de Campaign Classic. | Campaign Classic v7 |
| Julio de 2022 | [Prácticas recomendadas y estrategias de capacidad de envío que impulsan los resultados](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/deliverability-best-practices.html) | Vídeo | Aprenda a minimizar las incontables horas que se dedican a la planificación y producción de sus campañas de correo electrónico. | Campaign Classic v7 |
| Julio de 2022 | [Reduzca el nivel de su marketing multicanal con Adobe Campaign Classic](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/cross-channel.html?lang=en) | Vídeo | Vea este seminario web en profundidad centrado en los flujos de trabajo, la automatización, la personalización y la medición para los clientes de Adobe Campaign Classic. | Campaign Classic v7 |
| Julio de 2022 | [Consejos para ahorrar tiempo de un profesional!](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/tips.html?lang=en) | Vídeo | Empiece su nuevo año con consejos y trucos de un profesional de Adobe Campaign! Aprenda a ser más eficaz en la creación y el lanzamiento de campañas y a ofrecer experiencias multicanal más significativas y adaptadas. | Campaign Classic v7 |
| Julio de 2022 | [Integraciones de Adobe Campaign con un ecosistema de marketing](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/integrations.html?lang=en) | Vídeo | Obtenga información sobre las integraciones de Adobe Campaign con un ecosistema de marketing. Las soluciones de marketing multicanal como Adobe Campaign no deben permanecer aisladas de otras tecnologías o equipos. No deje que los sistemas dispares impidan una comprensión completa de un cliente y interrumpan las estrategias entre canales. | Campaign Classic v7 |
| Julio de 2022 | [Punto destacado del cliente de Adobe Campaign Standard: Microsoft](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/microsoft.html?lang=en) | Vídeo | Escuche al equipo de marketing de Microsoft® cómo utilizan Adobe Campaign Standard, su arquitectura, sus principios rectores y las prácticas recomendadas. | Campaign Standard |
| Julio de 2022 | [Punto destacado del cliente de Adobe Campaign: Center Parcs](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/center-parcs.html?lang=en) | Vídeo | Escuche a los clientes de Adobe Campaign compartir cómo superan los desafíos, se ajustan a la nueva normalidad, se vuelven más eficientes en la administración de campañas y aportan un valor significativo a través de Adobe Campaign. | Campaign Classic v7 |
| Julio de 2022 | [Adobe Campaign Classic V7 frente a V8](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/classic-v7-vs-v8.html?lang=en) | Vídeo | Conozca las últimas actualizaciones de productos y comprenda las diferencias entre V7 y V8 de nuestros responsables de productos. | Campaign Classic v7, Campaign v8 |
| Julio de 2022 | [Keynote - Tendencias del Recorrido del cliente e innovación en B2B y B2C](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/keynote.html?lang=en) | Vídeo | Obtenga información sobre las últimas tendencias en la administración del Recorrido de clientes entre B2B y B2C. Consulte las innovaciones más recientes en aplicaciones de recorrido clave y Adobe Experience Cloud y Platform en general. | Marketo, Campaign Classic v7, Campaign v8 |
| Julio de 2022 | [Sugerencias y trucos principales para Adobe Campaign Standard](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/tips-and-tricks.html?lang=en) | Vídeo | Conecte la instancia de Adobe Campaign Standard y descubra las prácticas recomendadas sobre segmentación, personalización y fatiga de marketing para obtener un mejor uso de ACS. | Campaign Standard |
| Julio de 2022 | [Equipo, habilidades y diseño organizativo necesarios para admitir el marketing en canales múltiples](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/team-skills-org-design.html) | Vídeo | Aprenda a estar capacitado para interactuar donde quiera, cuando y como desee. Conozca la importancia de tener una organización de marketing que admita la planificación, ejecución y medición. | Campaign Classic v7, Campaign v8, Campaign Standard |

{style=&quot;table-layout:auto&quot;}

### Recursos de ayuda de Campaign

* Adobe Campaign v8: [Documentación](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=es) - [Guías de implementación](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=es)
* Adobe Campaign Standard: [Documentación de Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Vídeos de procedimientos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=es) - [Planificación de versiones](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=es) - [Últimas actualizaciones de la documentación](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=es)
* Adobe Campaign Classic: [Documentación de Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=es) - [Vídeos de procedimientos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=es) - [Actualizaciones más recientes de la documentación](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=es)
* Panel de control de Adobe Campaign: [Documentación](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=en)    - Vídeos prácticos para [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=es) y [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=es)

## ![Icono](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Con Journey Optimizer, puede administrar campañas omnicanal programadas y momentos uno a uno para millones de clientes desde una sola aplicación, y todo el recorrido se optimiza con decisiones y perspectivas inteligentes.

### Últimas versiones de productos de Journey Optimizer

Descubra las funcionalidades, mejoras y correcciones más recientes en las [Notas de la versión de Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=es).

### Nuevos tutoriales y cursos de Journey Optimizer {#tutorials-ajo}

Nuevos vídeos, tutoriales o cursos publicados para Adobe Journey Optimizer.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Julio de 2022 | [Configuración de las reglas de frecuencia de los mensajes](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/channel-configuration/configure-frequency-rules.html) | Vídeo | Obtenga información sobre cómo crear, activar, probar e informar sobre reglas de frecuencia. Obtenga información sobre cómo determinar qué reglas de frecuencia se heredarán para un mensaje. |
| Julio de 2022 | [Configuración, creación y entrega de mensajes SMS](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/configure-author-and-deliver-sms-messages.html) | Vídeo | Obtenga información sobre cómo configurar, crear e incluir mensajes SMS en sus recorridos de cliente. |
| Julio de 2022 | [Compatibilidad con palabras clave entrantes para SMS](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/inbound-keyword-support-for-sms.html) | Vídeo | Comprender cómo funciona la compatibilidad de palabras clave de entrada nativas (inicio, parada, sin interrupciones) para trabajos de SMS. |

{style=&quot;table-layout:auto&quot;}

### Más recursos para [!DNL Journey Optimizer]

* [Documentación de Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=es) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=es)
* [Documentación de gestión de decisiones](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html?lang=es) - [Últimas actualizaciones de la documentación](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=es)

## ![Icono](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Utilice Experience Platform para orquestar el recorrido de un cliente a escala a través de canales de experiencia, anticipando de forma inteligente las necesidades de cada individuo en tiempo real.

### Últimas versiones de productos de [!DNL Journey Orchestration]

Obtenga más información acerca de las funcionalidades, mejoras y correcciones más recientes en las [[!DNL Journey Orchestration] Notas de la versión](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=es).

#### Más recursos para [!DNL Journey Orchestration]

* [Documentación de Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=es) - [Últimas actualizaciones de la documentación](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=es)

## ![Icono](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] es una aplicación completa para la gestión de posibles clientes y para los especialistas en marketing B2B que buscan transformar las experiencias de los clientes al interactuar en todas las fases de los recorridos de compra complejos.

### Actualizaciones centrales de Marketo Engage

Consulte [!DNL Marketo Engage] [programación de versiones](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=es) para obtener la información más reciente sobre el calendario de versiones y las notas de la versión.

### Nuevos tutoriales y cursos de Marketo {#tutorials-marketo}

Nuevos vídeos, tutoriales o cursos publicados para Adobe Marketo.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Julio de 2022 | [Experiencias B2B con Marketo Engage y Adobe Experience Cloud](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-experiences.html?lang=en) | Vídeo | Conozca las integraciones entre Marketo Engage y la aplicación de Adobe Experience Cloud, y qué problemas se solucionarán. | Marketo Engage |
| Julio de 2022 | [Mejor juntos: Adobe Marketo Engage y Real-Time CDP](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-campaigns.html?lang=en) | Vídeo | Aprenda a organizar campañas B2B con Marketo Engage y RT-CDP (edición B2B) y cuáles son los casos de uso y las ventajas más importantes que se desbloquean. | Marketo, Real-time Customer Data Platform |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] es una aplicación de administración de trabajo unificada para compartir ideas, crear contenido, administrar procesos complejos y trabajar de forma óptima.

Consulte la página [[!DNL Workfront] Versiones](https://one.workfront.com/s/product-releases) de para obtener un resumen de la información más reciente de todos los productos.

## ![Icono](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

Notas de la versión para [!DNL Adobe Advertising Cloud].

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
* [Nuevas funciones en  [!DNL Advertising Cloud DSP]](#adcloud-dsp)
* [Nuevas funciones en  [!DNL Advertising Cloud Search]](#adcloud-search)
<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

<!--
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

-->

### Nuevas funciones en [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Última actualización: **14 de julio de 2022**

| Función | Descripción |
| ------- | ----------- |
| Informes personalizados | (versión del 31 de mayo; función beta) Advertising Cloud DSP ahora puede introducir segmentos de origen compuestos de señales autenticadas creadas dentro de una plataforma de datos del cliente (CDP). |
| [!UICONTROL Inventario] | (Versión del 29 de junio) El nuevo [!UICONTROL Inventario] > [!UICONTROL Ofertas] la vista incluye las mismas capacidades de personalización de datos que la [!UICONTROL Campañas] , incluidos filtros adicionales, personalización de columnas y la opción de guardar vistas personalizadas, clasificación de columnas y una vista de visualización de datos (gráfico). Puede abrir un menú de comandos en cada fila haciendo clic en los puntos suspensivos (...) después del nombre de la oferta. |
| [!UICONTROL Inspector de inventario] | (Versión del 29 de junio) El [!UICONTROL Inventario] de la colocación [!UICONTROL Inspector] ahora incluye gráficos de visualización de datos personalizables y métricas de rendimiento ampliadas, como [!UICONTROL Tasa de visualización], [!UICONTROL Clics]y [!UICONTROL CPM de ayer]. |

{style=&quot;table-layout:auto&quot;}

### Nuevas funciones en [!DNL Advertising Cloud Search] {#adcloud-search}

Última actualización: **14 de julio de 2022**

| Función | Descripción |
| ------- | ----------- |
| [!UICONTROL Insights] | (Versión del 11 de junio) El análisis de Impresión compartida perdida ya está disponible como función beta. |
| [!DNL Advanced Campaign Management] | (20 de junio) ([!DNL Google Ads] y [!DNL Microsoft Advertising] campañas) Ahora puede crear variaciones de anuncios de búsqueda interactivas dinámicas utilizando una plantilla de publicidad específica del motor de búsqueda, basada en el contenido de su inventario, desde [!UICONTROL Campañas] > [!UICONTROL Avanzado (ACM)]. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Nuevos tutoriales y cursos publicados para Adobe Document Cloud.

| Publicadas | Nombre | Tipo | Descripción | Aplicación |
| -----------| ---------- | ---------- | ---------- |---------- |
| Julio de 2022 | [Uso de la función de aprobador](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/add-an-approver.html?lang=en) | Vídeo (actualizado) | Obtenga información sobre cómo enviar un documento a través de un proceso de aprobación. | Adobe Sign |
| Julio de 2022 | [Configuración de un formulario web](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/webform.html) | Vídeo (actualizado) | Aprenda a crear un documento que se pueda firmar electrónicamente directamente en el sitio web. | Adobe Sign |
| Julio de 2022 | [Uso de la función de delegado](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/delegate-signature.html?lang=en) | Vídeo (actualizado) | Descripción | Adobe Sign |
| Julio de 2022 | [Firma electrónica de un documento](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/electronically-sign-a-document.html?lang=en) | Vídeo (actualizado) | Aprenda lo fácil que es firmar un documento que se le envíe con Acrobat Sign. | Adobe Sign |
| Julio de 2022 | [Ejecución y puesta en marcha para administradores de Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/up-and-running-admin.html?lang=en) | Vídeo (actualizado) | Conozca las siete áreas clave en las que los administradores deben centrarse para ponerse en marcha rápidamente en Acrobat Sign. | Adobe Sign |
| Julio de 2022 | [Send for Signature en Outlook](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/send-for-signature-with-outlook.html?lang=en#) | Vídeo (actualizado) | Aprenda a optimizar los flujos de trabajo de los documentos enviando un documento para su firma directamente en Microsoft® Outlook. | Adobe Sign |
| Julio de 2022 | [Rellenar e iniciar sesión en Outlook](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/fill-and-sign-doc-microsoft-outlook.html?lang=en) | Vídeo (actualizado) | Aprenda a optimizar los flujos de trabajo de los documentos rellenando y firmando un formulario directamente en Microsoft Outlook. | Adobe Sign |
| Julio de 2022 | [Creación y administración de grupos](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/create-and-manage-groups.html?lang=en) | Vídeo (actualizado) | Obtenga información sobre cómo crear grupos, agregar usuarios a grupos y editar la configuración de grupos. | Adobe Sign |
| Julio de 2022 | [Delegar firma a otra persona](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/delegate-signing.html?lang=en) | Vídeo (actualizado) | Aprenda a delegar la firma de un documento a otra persona. | Adobe Sign |

{style=&quot;table-layout:auto&quot;}

Para obtener ayuda de Document Cloud, consulte:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=es)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=es)
* [Información y asistencia técnica de Document Cloud](https://helpx.adobe.com/es/support/document-cloud.html)

## ![Icono](/assets/creative-cloud-24.png) Adobe Creative Cloud para empresas {#creative-cloud}

Consulte [Tutoriales de Creative Cloud para empresas](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=es) para obtener los más recientes.

## ![Icono](/assets/experience-league.png) Administración de datos del cliente: voces {#voices}

[Voces de administración de datos del cliente](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=es) es su destino como encargado y especialista en prácticas de marketing y técnicas de gestión de datos de clientes. Esta colección de tutoriales es su punto de encuentro para escuchar a sus compañeros, inspirarse y aprender acerca de los desarrollos en MarTech. No se requiere registro, simplemente haga clic y mírelo.

## ![Icono](/assets/experience-league.png) Modelos de experiencia digital {#blueprints}

[Los modelos de experiencia digital](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=es) son implementaciones repetibles para abordar la estrategia y resolver los problemas empresariales establecidos. Cada modelo proporciona una serie de artefactos que explican el principal problema empresarial, las arquitecturas, los pasos de implementación, las consideraciones técnicas y los vínculos a la documentación pertinente.

[Volver arriba](#events)
