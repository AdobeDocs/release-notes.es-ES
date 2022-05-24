---
title: Últimas notas de la versión
description: Conozca las últimas notas de la versión, las nuevas funciones y la nueva documentación de los productos y servicios de  [!DNL Experience Cloud] . Encuentre ayuda y tutoriales nuevos acerca de [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise] y [!DNL Document Cloud].
doc-type: release notes
last-update: May 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: d4aed4b509b13fbc0fc73d11dcb30ac4f2fdbfd7
workflow-type: tm+mt
source-wordcount: '4935'
ht-degree: 50%

---

# Notas de la versión de Adobe Experience Cloud: mayo de 2022

![Titular](assets/experience-cloud-banner-3.png)

Como Experience Maker, la ruta hacia el éxito empieza por [Adobe Experience League](https://experienceleague.adobe.com/?lang=es#home). Encuentre una amplia biblioteca de documentación de procedimientos, tutoriales autoguiados, vídeos explicativos y cursos para todos los niveles y funciones, una comunidad en línea de compañeros y asistencia técnica especializada cuando la necesite.

¿Todo listo para empezar? [Complete un test de cinco minutos y gane](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp).

>[!NOTE]
>
>Para recibir una notificación mensual por correo electrónico acerca de las actualizaciones realizadas en esta página, suscríbase a la [Actualización de producto prioritario de Adobe](https://www.adobe.com/subscription/priority-product-update.html). Vuelva con frecuencia para mantenerse al tanto de lo que está pasando en Experience League.

Última actualización: **24 de mayo de 2022**

* [Eventos de [!DNL Experience League]](#events)
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
* [[!DNL Adobe Campaign]](#ac) (Actualizado) **24 de mayo**)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [Modelos de experiencia digital: tutoriales](#blueprints)

¿Necesita ayuda? Visite [Adobe Experience League](https://experienceleague.adobe.com/?lang=es#home) para encontrar la documentación técnica y de los productos, cursos seleccionados por Adobe, tutoriales de vídeo, respuestas rápidas, conocimiento de la comunidad y formación impartida por instructores.

## ![Icono](/assets/experience-league.png) Eventos de [!DNL Experience League] {#events}

Los eventos de Experience League son un buen lugar para aprender, interactuar y obtener respuestas de los expertos en productos de Adobe.

Actualización: **24 de mayo de 2022**

| Evento | Tipo | Descripción |
| -----------|---------- | ----|
| [Adobe Campaign: serie de seminarios web de éxito de los clientes](https://peer2peerenhancecustomerjourney-ac-may2022.experienceleague.adobeevents.com/) | Peer2Peer: Mejora de los Recorridos del cliente mediante Adobe Campaign. | Únase a esta conversación en directo entre pares con Anja Starun, responsable de operaciones de participación en las marcas Kayo, Binge y Flash de Streamotion. Conozca directamente de ella las estrategias exitosas que su equipo implementó para crear recorridos de cliente individualizados usando Adobe Campaign. <br>**Fecha:** 26 de mayo a las 15.00 horas EST <br>[Detalles e inscripción](https://peer2peerenhancecustomerjourney-ac-may2022.experienceleague.adobeevents.com/) |
| [Notificaciones push con Journey Optimizer: Configurar fácilmente la aplicación móvil para notificaciones push](https://www.youtube.com/watch?v=t36Xjhukmro) | Experience League LIVE  | Obtenga información sobre los casos de uso comunes de las notificaciones push con Adobe Journey Optimizer y descubra los detalles técnicos sobre cómo configurar una aplicación para notificaciones push con tecnología Adobe Experience Platform. <br>**Fecha:** 12 de mayo de 2022 a las 9:30 PDT<br>[Programación y eventos anteriores](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=es) |
| [Comunidad de Adobe Target](https://experienceleaguecommunities.adobe.com/t5/adobe-target-discussions/at-community-q-amp-a-coffee-break-4-27-22-8am-pt-jim-mctiernan/m-p/446940?profile.language=es#M3096) | Sesión de preguntas y respuestas y descanso | Únase a Brent Kostak y Drew Burns, del equipo de productos de Adobe Target, que pueden responder a sus preguntas de Adobe Target sobre audiencias compartidas, Real-Time CDP, datos de origen, flujos de trabajo de personalización de principio a fin y mucho más.<br>Vea los últimos [Seminario web de personalización en tiempo real](https://experienceleaguecommunities.adobe.com:443/t5/adobe-target-discussions/webinar-recording-4-28-22-real-time-personalization-with-adobe/td-p/449012) y remita sus preguntas de seguimiento a los expertos de la [Rodaje de café](https://adobe.ly/3MyiDHa) en la Comunidad de Adobe Target!<br>**Fecha:** 25 de mayo de 2022 a las 8 de la mañana PDT<br>[Detalles y registro](https://adobe.ly/3MyiDHa) |
| [Adobe [!DNL Developers Live]: Comercio](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2022/feb2022/overview.html?lang=en) | Vídeos bajo demanda | _Adobe Developers Live: Comercio 2022_ reúne a desarrolladores y creadores de experiencias con distintos orígenes y un propósito singular para crear experiencias integrales increíbles. Esta conferencia virtual de un día incluye importantes actualizaciones para desarrolladores de comercio y código abierto, sesiones técnicas, oportunidades de redes comunitarias y mucho más. |
| [Marketo Skills Exchange](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=en) | Vídeos bajo demanda | Obtenga información sobre la importancia de la hoja de ruta de Marketo y cómo evitar una planificación deficiente. Obtenga consejos sobre cómo desbloquear el potencial de los campos personalizados de los miembros del programa, los consejos y trucos del Marketo Engage y mucho más en la [!DNL Marketo] Intercambio de habilidades de agosto de 2021, ahora en Experience League. |
| [Adobe Summit 2022](https://business.adobe.com/summit/adobe-summit.html) | Sesiones bajo demanda | Aprenda de los ejecutivos de Adobe, Ryan Reynolds, Rosalind Brewer, CEO de Walgreens Boots Alliance, Inc, John Donahoe, CEO de NIKE, Inc. y Gail J. McGovern, CEO de American Red Cross, mientras comparten cómo las experiencias de los clientes son la moneda de nuestra economía digital.<br>Explora las [sesiones bajo demanda](https://business.adobe.com/summit/2022/sessions.html) del Adobe Summit 2022. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] proporciona información detallada, actualizaciones de estado y notificaciones por correo electrónico sobre los productos de Adobe y las interrupciones y sesiones de mantenimiento de los servicios. Puede comprobar el estado en [status.adobe.com](https://status.adobe.com/es).

Para obtener la información más reciente sobre la versión, consulte las [notas de la versión](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=es#status) del Estado del sistema de Adobe.

## ![Icono](/assets/ec_appicon_24.png) Experience Cloud: componentes y administración de la interfaz central {#ecloud}

Los [componentes de la IU central](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=es) de Experience Cloud incluyen las funciones disponibles en la página de inicio y el encabezado de producto persistente. Estas funciones incluyen la configuración del perfil del usuario, las preferencias y la búsqueda. También puede encontrar ayuda sobre la administración de usuarios y productos, los atributos del cliente y las audiencias de Experience Cloud.

No se ha actualizado.

**Más recursos de ayuda de [!DNL Experience Cloud Central UI Components] y Administración**

* [Notas de la versión](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=es) para los componentes centrales de la IU de Experience Cloud
* [Administración de usuarios y productos](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) Experience Cloud (administración)
* [Notas de la versión](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=es) del servicio Places
* Documentación del producto para [People: atributos del cliente y biblioteca de audiencias](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=es)
* [Búsqueda unificada de objetos y entidades](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=es)

## ![Icono](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

Información sobre la versión más reciente y la nueva documentación de [!DNL Experience Platform] y el [!UICONTROL SDK móvil]:

Fecha de publicación planeada: **25 de mayo de 2022**

* [Notas de la versión de Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=es)

### Nuevos tutoriales y cursos de [!DNL Experience Platform] {#tutorials-platform}

Nuevos tutoriales, artículos y cursos de vídeo publicados para [!DNL Experience Platform].

| Publicadas | Nombre | Tipo | Descripción | Aplicación |
| -----------| ---------- | ---------- | ---------- |---------- |
| Mayo de 2022 | [Perspectivas previas al uso compartido de coincidencias de segmentos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-pre-share-insights.html) | Vídeo | Cuando decida con un socio estratégico con el que compartir datos, es importante saber cómo coinciden sus clientes, de modo que sepa cuán útil será ese uso compartido de datos. La coincidencia de segmentos le permite ver la superposición con posibles socios de datos antes de compartir datos. | [!DNL Real-time Customer Data Platform] |
| Mayo de 2022 | [Configuración de conexión de coincidencia de segmentos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-connection-setup.html?lang=en) | Vídeo | obtenga información sobre cómo configurar la conexión entre usted y un socio para que pueda compartir audiencias. Después de configurar esta función de coincidencia de segmentos, podrá compartir datos de un lado a otro con su socio de datos. | [!DNL Real-time Customer Data Platform] |
| Mayo de 2022 | [Control de datos de coincidencias de segmentos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-data-governance.html?lang=en) | Vídeo | Aprenda a configurar y utilizar controles de control de datos en Real-Time CDP para que pueda limitar qué conjuntos de datos (y, por lo tanto, qué segmentos que utilizan dichos conjuntos de datos) se pueden compartir con socios de datos. | [!DNL Real-time Customer Data Platform] |
| Mayo de 2022 | [Flujo de configuración de coincidencia de segmentos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-configuration-flow.html?lang=en) | Vídeo | Conozca el proceso de configuración de un [!UICONTROL Coincidencia de segmentos] para un recurso compartido de datos. | [!DNL Real-time Customer Data Platform] |
| Mayo de 2022 | [Conexión a destinos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/connecting-to-destinations.html) | Vídeo | Antes de poder enviar datos a los socios de destino desde CDP en tiempo real, primero debe realizar las conexiones con dichos socios. Este vídeo lo acompaña durante ese proceso, que suelen realizar los administradores. | [!DNL Real-time Customer Data Platform] |
| Mayo de 2022 | [Crear esquemas](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html) | Vídeo | Este vídeo muestra cómo crear esquemas en Adobe Experience Platform utilizando la clase XDM Individual Profile y varios grupos de campos. | Experience Platform |
| Mayo de 2022 | [Analizar y visualizar perspectivas omnicanal en Tableau mediante el servicio de consulta](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/analyze-and-visualize.html) | Vídeo | Descubra cómo puede utilizar el servicio de consulta de Adobe Experience Platform con herramientas de visualización de datos externas mediante un ejemplo de análisis de pérdida. | Experience Platform |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

Consulte [Notas de la versión y registros de cambios](https://aep-sdks.gitbook.io/docs/release-notes) para conocer los SDK de Adobe Experience Platform Mobile.

## ![Icono](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Fecha de versión: **18 de mayo de 2022**

* [Notas de la versión](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=es) de Adobe Analytics
* [Tutoriales y documentación del producto](https://experienceleague.adobe.com/docs/analytics.html?lang=es) de Adobe Analytics

### AppMeasurement {#appm}

Versión: **2.22.4**

* [Notas de la versión de AppMeasurement para JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=es)

### Nuevos tutoriales y cursos de [!DNL Analytics] {#tutorials-analytics}

Nuevos tutoriales, artículos y cursos de vídeo publicados para Adobe Analytics.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Mayo de 2022 | [Introducción a Report Builder](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/report-builder/get-started-with-report-builder.html?lang=en) | Vídeo | Conozca los conceptos básicos del uso de Report Builder, incluida la instalación, el inicio de sesión y las solicitudes de datos. |
| Mayo de 2022 | [Navegar por la nueva página de aterrizaje](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/navigating-the-new-landing-page.html?lang=en) | Vídeo | Aprenda a sacar el máximo partido a la nueva página de aterrizaje de Analytics y a sus funciones. |
| Mayo de 2022 | [Paneles e informes del espacio de trabajo de resumen de página siguiente/anterior](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/next-previous-and-page-summary-workspace-panels-reports.html) | Vídeo | Consulte los dos nuevos tipos de panel en Analysis Workspace: Siguiente/Anterior y Resumen de página. Esto iguala Workspace con algunos de los más populares [!UICONTROL Informes y análisis] informes. |
| Mayo de 2022 | [Actualizaciones de la página de aterrizaje de Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/analysis-workspace-landing-page-updates.html?lang=en) | Vídeo | Obtenga información sobre algunas de las buenas mejoras y adiciones a la nueva página de aterrizaje. Hemos tomado los comentarios de sus clientes y hemos intentado incorporar las funciones más destacadas, como el cambio de tamaño de columnas, los nuevos tipos de columnas, los vínculos a informes de bots y en tiempo real, entre otras. |
| Mayo de 2022 | [¿Estás haciendo las preguntas correctas?](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/are-you-asking-the-right-questions.html) | Vídeo | Aprenda cómo es más valioso identificar y recopilar los puntos de datos procesables que registrar cada elemento posible. La identificación eficiente de esos puntos de datos requiere un plan básico y debates creativos con las partes interesadas. |
| Mayo de 2022 | [Uso [!UICONTROL Report Builder] opciones de envío avanzadas para la Power BI](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/report-builder/use-report-builder-advanced-delivery-options-for-power-bi.html?lang=en) | Vídeo | Aprenda a configurar una programación avanzada para enviar un libro de Report Builder a Power BI. |
| Mayo de 2022 | [Programar una solicitud de Report Builder](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/report-builder/schedule-a-report-builder-request.html?lang=en) | Vídeo | Obtenga información sobre cómo configurar una programación básica para un libro de Report Builder. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

Fecha de versión: **18 de mayo de 2022**

* [Notas de la versión](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=es) de Customer Journey Analytics
* [Tutoriales y documentación del producto](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=es) de Customer Journey Analytics

## ![Icono](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

Última actualización: **23 de marzo de 2022**

* [!DNL Streaming Media Analytics][Notas de la versión de ](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=es)
* [Tutoriales y documentación del producto](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=es) de [!DNL Streaming Media Analytics]

<!-- ### New Customer Journey Analytics tutorials and courses {#tutorials-cja}

New video tutorials, articles, and courses published for Customer Journey Analytics.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|April 2022|[Overview of configuring Data Views for Customer Journey Analytics](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/overview-of-configuring-data-views-for-cja.html?lang=en)|Video |Learn about configuring [!UICONTROL Data Views] for Customer Journey Analytics. [!UICONTROL Data Views] are similar to [!UICONTROL Virtual Report Suites] in Adobe Analytics. They allow you to configure the incoming data so that it can be most useful for your reporting and analysis. |
|April 2022|[Connections Details Experience in CJA](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections-details-experience-in-cja.html?lang=en)|Video |Learn how to check the status of your connection’s datasets and of the ingestion process.|
-->

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

### Versiones de productos de Experience Manager

* **Experience Manager as a Cloud Service**

   Observe el [Vídeo de información general sobre la versión de abril de 2022](https://video.tv.adobe.com/v/342612?quality=12) para obtener un resumen de las funciones añadidas en la versión 2022.4.0 (abril de 2022). <!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

   * [Vídeo de información general sobre la versión de marzo de 2022](https://video.tv.adobe.com/v/341465).
   * [Vídeo de información general sobre la versión de enero de 2022](https://video.tv.adobe.com/v/340120).
   * [Vídeo de información general sobre la versión de diciembre de 2021](https://video.tv.adobe.com/v/339278).
   * [Vídeo de información general sobre la versión de octubre de 2021](https://video.tv.adobe.com/v/338253).
   * [Vídeo de información general sobre la versión de septiembre de 2021](https://video.tv.adobe.com/v/337381).

* **Experience Manager Sites as a Cloud Service**

   _Nueva función_

   * Ahora puede definir tipos de datos del modelo de contenido como [traducible](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/content-fragments/content-fragments-models.html?lang=en#properties) uso de una casilla de verificación en el editor de modelos de contenido. Además, las reglas y configuraciones de Experience Manager de traducción se actualizan automáticamente.

   _Nueva función en el canal de prelanzamiento_

   * Publicar fragmentos de experiencias para vista previa : para obtener una vista previa de las experiencias finales que pueden ver los visitantes, puede publicar fragmentos de experiencias independientes en el servicio de vista previa as a Cloud Service del Experience Manager.


* **Experience Manager Assets as a Cloud Service**

   _Nueva función_

   * Ahora puede [ordenar etiquetas](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/organize-assets.html?lang=es#use-tags-to-organize-assets) en la ventana del selector de etiquetas en orden ascendente o descendente, según el nombre de la etiqueta, la fecha de creación o la fecha de modificación.

* **Experience Manager Forms as a Cloud Service**

   _Nuevas funciones_

   * **Comunicaciones: Compatibilidad con las API de manipulación de documentos en el SDK as a Cloud Service de Forms** - [API de manipulación de documentos](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=es) ayuda a combinar, reorganizar y validar documentos de PDF. Ahora puede utilizar las API de Communications - Document Generation en un entorno de desarrollo local con la ayuda del SDK as a Cloud Service de Experience Manager Forms.
   * **Usar XCI personalizado para generar un documento de registro** - Ahora puede [usar un archivo XCI personalizado para establecer varias propiedades de un documento de registro](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/generate-document-of-record-for-non-xfa-based-adaptive-forms.html?lang=en#use-a-custom-xci-file). Anula el XCI principal con los cambios personalizados. Proporciona más control sobre la generación de Documentos de Registro, lo que aumenta la personalización y las oportunidades de personalización.
   * **Utilizar CAPTCHA invisible en forma adaptable** - Puede usar la variable [CAPTCHA invisible para mostrar el desafío CAPTCHA solo si hay actividad sospechosa](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/add-components-to-an-adaptive-form/captcha-adaptive-forms.html?lang=en). Si no se encuentra ninguna actividad sospechosa, no se muestra el desafío CAPTCHA. Ayuda a evaluar la cumplimentación de formularios humanos sin requisitos de casilla de verificación, reducir los esfuerzos de personalización y mejorar la experiencia del usuario final.
   * **Configuraciones del modelo de datos de formulario** - Ahora puede [reutilizar las configuraciones del modelo de datos de formulario en entornos](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/use-form-data-model/create-form-data-models.html?lang=en#runmode-specific-context-aware-config), simplificar las integraciones de datos y reducir los costes de TI.

* **Experience Manager Screens as a Cloud Service**

   _Nueva función_

   * Asignación de canales masivos : los usuarios pueden seleccionar varios canales y asignarlos a varias pantallas al mismo tiempo, en una operación.

* **Experience Manager as a Cloud Service Foundation**

   _**Analizadores de compilaciones SDK**_

   El Experience Manager as a Cloud Service SDK Build Analyzer Maven Plugin detecta problemas en un proyecto maven, incluidas dependencias que faltan. Proporciona a los desarrolladores la oportunidad de descubrir problemas durante el desarrollo local, mucho antes de implementarlos en entornos de nube con Cloud Manager.

   Se ha añadido recientemente un nuevo analizador:

   * content-packages-validation : valida la sintaxis y estructura de contenido bien formadas para los paquetes que se instalan durante la implementación.
   Adobe recomienda actualizar el proyecto de maven con la última versión del analizador o incluir el analizador si aún no lo ha hecho. Consulte la [Documentación de la ](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html?lang=es) para obtener más información.

* **Cloud Manager**

   _Nuevas funciones_

   * La página Entornos tiene una columna para mostrar el Experience Manager Versión del entorno.
   * La ejecución de la canalización ahora muestra los errores de nivel superior de la interfaz de usuario en la pantalla de ejecución.
   * Vuelva a ejecutar el paso de implementación de producción a través de la interfaz de usuario de Cloud Manager.
   * Vuelva a utilizar la compilación de imágenes para volver a ejecutar el paso de implementación de producción.
   * Nueva API para permitir la eliminación de autoservicio de la infraestructura de red.

* **Analizador de prácticas recomendadas**

   _Nuevas funciones_

   * Capacidad para detectar e informar sobre el uso de API de Asset Manager no admitidas. Hay cuatro API que ya no son compatibles con Experience Manager as a Cloud Service. Los clientes deben asegurarse de que ya no utilizan estas API y de que deben utilizar el nuevo método de carga de recursos.
   * Capacidad para detectar el uso de plantillas de fragmento de contenido. Las plantillas de fragmentos de contenido ya no son compatibles con la creación de nuevos fragmentos de contenido en el Experience Manager as a Cloud Service. Los clientes deben crear modelos de fragmento de contenido para reemplazar las plantillas de fragmento de contenido.
   * Capacidad para detectar activos con más de 100 descendientes bajo el nodo de metadatos del recurso en el repositorio. Adobe recomienda quitar los nodos de metadatos que no necesite, de modo que pueda mejorar el rendimiento al cargar carpetas que estén formadas por dichos recursos.
   * Capacidad para detectar e informar sobre el tipo de almacén de datos utilizado.
   * Patrón actualizado para el portal de formularios de Experience Manager.

### Comunidad

* **Seminario web del Experience Manager grabado GEM**

   * [_Integre el marco de AEM y CIF para crear una experiencia de comercio electrónico enriquecida e inmersiva_](https://adobe.ly/3jorz5r).

* Experience Manager as a Cloud Service [Actualización de la versión 2022.4.0](https://adobe.ly/3LO0gOo).

### Nuevos cursos y tutoriales para Experience Manager {#tutorials-aem}

Nuevos vídeos, tutoriales y cursos publicados durante el mes pasado.

| Publicadas | Nombre | Tipo | Descripción | Aplicaciones |
| -----------| ---------- | ---------- | ---------- | ------|
| Mayo de 2022 | [Actualización de la versión 2021.4.0 de AEM as a Cloud Service.](https://experienceleague.adobe.com/docs/experience-manager-release-overview-events/aemcsupdates/2021/2021-4-0.html?lang=en) | Vídeo | Obtenga información del equipo de productos de AEM y obtenga información sobre las funciones y las innovaciones de la última versión de Adobe Experience Manager. | AEM Asset Essentials, Sites, Screens, Forms y Cloud Foundation |
| Mayo de 2022 | [Nube 5 AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-5/cloud5-introduction.html) | Vídeos | Obtenga toda la información útil que necesita sobre AEM as a Cloud Service en vídeos cortos de 5 minutos o menos. Empiece con la temporada 1. | AEM CS |
| Mayo de 2022 | [Obtención de un token de inicio de sesión para integraciones](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-5/cloud5-getting-login-token-integrations.html) | Vídeo | Una guía detallada sobre cómo obtener un token de inicio de sesión para integraciones de Cloud Service y algunos casos de uso para hacerlo. | AEM CS |
| Mayo de 2022 | [Mostrar varios documentos pdf en un carrusel](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/display-pdf-in-carousel.html?lang=en) | Vídeo | Conozca el caso de uso común para mostrar varios documentos de PDF al usuario que rellena el formulario para revisarlo antes de enviarlo. | AEM Forms |
| Mayo de 2022 | [Imágenes con AEM sin encabezado](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/how-to/images.html) | Vídeo | Obtenga información sobre el desarrollo de una experiencia rica y atractiva AEM sin encabezado mediante imágenes y mucho más. | AEM sin encabezado |
| Mayo de 2022 | [Texto enriquecido con AEM sin encabezado](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/how-to/localized-content.html) | Vídeo | Aprenda a utilizar el campo de texto Multi-line , un tipo de datos de fragmentos de contenido que permite a los autores crear contenido de texto enriquecido. | AEM sin encabezado |
| Mayo de 2022 | [Dirección IP de salida dedicada](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/dedicated-egress-ip-address.html?lang=es) | Vídeo | Aprenda a configurar y utilizar la dirección IP de salida dedicada, que permite que las conexiones salientes de AEM se originen desde una IP dedicada. | AEM CS |
| Mayo de 2022 | [Implementación del código](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/deploy-code.html) | Vídeo | Obtenga información sobre cómo implementar su código en Producción mediante canalizaciones de Cloud Manager en AEM as a Cloud Service. | AEM CS, Cloud Manager |
| Mayo de 2022 | [Desactivar la ejecución del flujo de trabajo posterior al procesamiento](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/asset-microservices-configure-and-use.html#disable-post-processing-workflow-execution) | Documentación | Aprenda a crear un modelo de flujo de trabajo vacío en la sección Flujo de trabajo de inicio automático cuando no sea necesario posprocesar. | AEM CS |
| Mayo de 2022 | [Marcas de agua](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/watermarks.html?lang=en) | Vídeo | AEM as a Cloud Service funciones de marca de agua permiten que las representaciones de imágenes personalizadas se marquen con agua con cualquier imagen PNG. | AEM Assets |

{style=&quot;table-layout:auto&quot;}

### Información de la versión de Experience Manager

Todas las notas de la versión de Experience Manager se mantienen en las páginas siguientes:

* [Información sobre la versión de Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=es)
* [Notas de la versión de Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=es)
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

* [Guías de Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=es)
* [Guía del usuario de Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=es)
* [Formación y asistencia de Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=es)
* [Formación y asistencia de Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=es)
* [Formación y asistencia de Experience Manager 6.3](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=es)
* [Formación y asistencia de Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=es#previous-updates)
* [Versiones anteriores de la documentación de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Inicio de la Ayuda de Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=es)
* [Documentación de Experience Manager: Actualizaciones recientes](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=es#aem-as-a-cloud-service)

## ![Icono](/assets/ec_appicon_24.png) Guías de Adobe Experience Manager {#xml-doc}

Guías del Experience Manager (anteriormente, XML Documentation para el Experience Manager) es una aplicación implementada en AEM. Es una potente solución de administración de contenido de componentes (CCMS) de nivel empresarial que permite la compatibilidad nativa con DITA en Adobe Experience Manager, lo que permite a AEM gestionar la creación y la entrega de contenido basado en DITA.

Más información sobre [Guías del Experience Manager](https://www.adobe.com/es/products/xml-documentation-for-experience-manager/features.html).

### Recursos adicionales

* [Guías del Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=es) : tutoriales sobre Experience League
* [Guías del Experience Manager Información y asistencia](https://helpx.adobe.com/es/support/xml-documentation-for-experience-manager.html) - documentación del producto

## ![Icono](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Consulte los siguientes vínculos para ver las notas de la versión de Adobe Commerce:

* [Notas de la versión de Adobe Commerce y Magento Open Source 2.4.x](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Notas de la versión de Cloud Suite](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![Icono](/assets/target.png) [!DNL Adobe Target] {#target}

Última actualización: **9 de mayo de 2022**

* Para obtener información previa al lanzamiento, consulte [Versión preliminar de Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=es)
* Para obtener información actual, consulte [Notas de la versión de Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=es)

## ![Icono](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign permite entregar, de forma intuitiva y automatizada, mensajes privados a través de canales de marketing en línea y sin conexión. Ahora puede anticipar los deseos de los clientes mediante experiencias basadas en sus hábitos y preferencias.

### Últimas versiones de productos de Campaign

**Última versión:** [versión 22.2 del Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/e-release-notes.html) (junio de 2022)

Obtenga más información sobre las últimas funciones, mejoras y correcciones en la [Campaign v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=es), [Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=es)y [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) notas de la versión.

### Recursos de ayuda de Campaign

* Adobe Campaign v8: [Documentación](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [Guías de implementación](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=es)
* Adobe Campaign Standard: [Documentación de Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Vídeos de procedimientos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=es) - [Planificación de versiones](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html) - [Últimas actualizaciones de la documentación](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=es)
* Adobe Campaign Classic: [Documentación de Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Vídeos de procedimientos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=es) - [Actualizaciones más recientes de la documentación](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=es)
* Panel de control de Adobe Campaign: [Documentación](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=es)  - Vídeos prácticos para [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=es) y [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=es)

## ![Icono](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Con Journey Optimizer, puede administrar campañas omnicanal programadas y momentos uno a uno para millones de clientes desde una sola aplicación, y todo el recorrido se optimiza con decisiones y perspectivas inteligentes.

### Últimas versiones de productos de Journey Optimizer

Descubra las funcionalidades, mejoras y correcciones más recientes en las [Notas de la versión de Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=es).

### Tutoriales y cursos de Journey Optimizer {#tutorials-ajo}

Últimos tutoriales de Journey Optimizer:

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Mayo de 2022 | [Crear reglas de decisión](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-rules.html?lang=en) | Vídeo | Aprenda a crear reglas de decisión para la administración de decisiones. Reglas o _reglas de decisión_ son uno de los componentes de bloque de creación requeridos de ofertas personalizadas. |
| Mayo de 2022 | [Creación de ubicaciones](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-placements.html) | Vídeo | Obtenga información sobre cómo crear ubicaciones para la administración de decisiones. Las ubicaciones son uno de los componentes de bloque de creación para las ofertas. Una ubicación es la combinación de tipo de contenido y canal, como una imagen en un correo electrónico o código HTML de un sitio web. |
| Mayo de 2022 | [Crear decisiones](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-decisions.html) | Vídeo | Aprenda a crear decisiones para la administración de decisiones. Una decisión combina las ubicaciones y las colecciones en una sola entidad, para que se pueda tomar la decisión de proporcionar la oferta más relevante al cliente. |
| Mayo de 2022 | [Entrega de ofertas con la API de Decisions Hub](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/deliver-offers-with-the-decisions-api.html) | Vídeo | Obtenga información sobre cómo entregar ofertas con la API de Decisions Hub. |
| Mayo de 2022 | [Creación de ofertas de reserva](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-fallback-offers.html) | Vídeo | Aprenda a crear ofertas de reserva para la administración de decisiones. Las ofertas de reserva son ofertas predeterminadas que se muestran a los clientes que no cumplen los requisitos para ninguna de sus ofertas personalizadas. |
| Mayo de 2022 | [Creación de colecciones](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-collections.html?lang=en) | Vídeo | Aprenda a crear colecciones para la administración de decisiones. Las colecciones se utilizan para administrar ofertas en grupos lógicos y se necesitan para compilar para actividades de administración de decisiones |

{style=&quot;table-layout:auto&quot;}

### Más recursos para [!DNL Journey Optimizer]

* [Documentación de Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=es)
* [Documentación de gestión de decisiones](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html) - [Últimas actualizaciones de la documentación](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=es)

## ![Icono](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Utilice Experience Platform para orquestar el recorrido de un cliente a escala a través de canales de experiencia, anticipando de forma inteligente las necesidades de cada individuo en tiempo real.

### Últimas versiones de productos de [!DNL Journey Orchestration]

Obtenga más información acerca de las funcionalidades, mejoras y correcciones más recientes en las Notas de la versión de [[!DNL Journey Orchestration] ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=es).

#### Más recursos para [!DNL Journey Orchestration]

* [Documentación de Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=es) - [Últimas actualizaciones de la documentación](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=es)

## ![Icono](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] es una aplicación completa para la gestión de posibles clientes y para los especialistas en marketing B2B que buscan transformar las experiencias de los clientes al interactuar en todas las fases de los recorridos de compra complejos.

Eventos de vídeo recientemente publicados en Experience League:

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Mayo de 2022 | [Marketo Skills Exchange](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=en) | Vídeos | Empiece por obtener información sobre la hoja de ruta de Marketo. A continuación, descubra la importancia de pensar en la instancia de Marketo como un producto. Obtenga consejos sobre cómo desbloquear el potencial de los campos personalizados de los miembros del programa, los consejos y trucos del Marketo Engage, etc., en esta página recientemente publicada [Marketo Skills Exchange](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=en) desde agosto de 2021, ahora en Experience League. |

{style=&quot;table-layout:auto&quot;}

### Actualizaciones centrales de Marketo Engage

Consulte [!DNL Marketo Engage] [programación de versiones](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=es) para obtener la información más reciente sobre el calendario de versiones y las notas de la versión.

## ![Icono](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] es una aplicación de administración de trabajo unificada para compartir ideas, crear contenido, administrar procesos complejos y trabajar de forma óptima.

Consulte la página [[!DNL Workfront] Versiones](https://one.workfront.com/s/product-releases) de para obtener un resumen de la información más reciente de todos los productos.

## ![Icono](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

Notas de la versión para [!DNL Adobe Advertising Cloud].

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
<!-- * [New features in [!DNL Advertising Cloud DSP]](#adcloud-dsp) -->
* [Nuevas funciones en  [!DNL Advertising Cloud Search]](#adcloud-search)

<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

<!--
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

-->

<!--
### New features in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Custom Reports | You can now create and manage [!DNL Amazon S3] and different types of FTP delivery locations, called *[!DNL report destinations]*, for your custom reports. Once you configure report destinations, you can set up each of your new custom reports to be delivered to one or more locations of a single destination type, or to email recipients. Updates to your [!DNL Amazon S3] and FTP credentials won't interrupt report delivery.<br><br>Your existing reports are still sent to the specified email recipients. To configure delivery to a different report destination, create a report with the new destination. |
| [!UICONTROL Packages], [!UICONTROL Placements], and [!UICONTROL Ads] views| When you view data for a single day, the trend charts now include hourly data. Hold the cursor over any point to see the data for that hour. |
| [!UICONTROL Placements] | The placement [!UICONTROL Inspector] now includes an [!UICONTROL Inventory] tab, which shows all deals and their associated metrics for the placement. Use the information to make quick adjustments or troubleshoot issues without generating a custom report. |
| [!UICONTROL Ads] | (Users with permission to include Clearcastclock numbers in their ads) DSP no longer shows an error if you use a clock number that's attached to another ad. **Note:**  The best practice is to use a unique clock number for each video ad. Otherwise, the publisher does not approve all the ads. |
| [!UICONTROL Deal IDs] | The [!UICONTROL Deal ID] settings and other places in the user interface reflect new branding for [!DNL Magnite] SSP:<br><ul><li>The SSP [!DNL Tremor] ([!DNL Telaria]) is now [!DNL Magnite CTV].</li><li>In the coming weeks, [!DNL Rubicon] will change to [!DNL Magnite DV+], where [!DNL DV+] stands for display, video, and other formats such as audio.</li></ul> |
| [!DNL Freewheel] programmatically guaranteed deals | You can now find the status of ads for [!DNL Freewheel] programmatically guaranteed deals from the [!UICONTROL Ads] view. Previously, you could check the status only from the [!UICONTROL Deals] view. |
-->

### Nuevas funciones en [!DNL Advertising Cloud Search] {#adcloud-search}

Última actualización: **** 12 de mayo de 2022 para la versión del 14 de mayo

| Función | Descripción |
| ------- | ----------- |
| [!UICONTROL Campañas] | Las siguientes funciones beta están disponibles para todos los anunciantes:<ul><li>([!DNL Microsoft® Advertising] cuentas) Sincronización, visibilidad de solo lectura y compatibilidad con informes (incluidos los datos de visualización) para sus campañas de publicidad nativas existentes en la variable [!DNL Microsoft® Audience Network], incluyendo [!DNL Microsoft® Audience Ads].</li><li>([!DNL Google Ads] y [!DNL Microsoft® Advertising] cuentas) Capacidad de importar [!DNL Google Ads] campañas y estructura de campaña para [!DNL Microsoft® Advertising] from [!UICONTROL Buscar] > [!UICONTROL Herramientas] > [!UICONTROL Importar campañas beta].<br><br>Una vez importadas las campañas, puede comprobar el estado del trabajo de importación, revisar los registros de errores y editar, pausar o eliminar la programación de importación.</li></ul> |
| [!UICONTROL Campañas]<br><br>[!UICONTROL Portfolio] | ([!DNL Microsoft® Advertising] campañas) Ya están disponibles para todos los usuarios las siguientes estrategias de oferta:<ul><li>[!UICONTROL Uso compartido de impresiones de Target]: Puede configurar campañas con esta estrategia y, opcionalmente, establecer un porcentaje de impresión objetivo, una posición de anuncio objetivo y un costo por clic máximo. Precaución: Esta opción aún no es compatible con portafolios híbridos y no se puede agregar a portafolios estándar.</li><li>[!UICONTROL Maximizar clics]: Puede configurar campañas con esta estrategia y, opcionalmente, establecer un costo por clic máximo objetivo. Puede incluir campañas con esta estrategia en portafolios estándar o híbridos. Para utilizar esta estrategia en una cartera híbrida, el objetivo de la cartera debe incluir sólo [!DNL Adobe] propiedades (métricas) y debe habilitar la carga de objetivos de Advertising Cloud Search en [!DNL Microsoft® Ads].</li></ul> |
| Integración con Adobe Analytics | (7 de abril) En la fuente de datos a la que Advertising Cloud envía [!DNL Analytics], datos para [!DNL Google Ads] los anuncios de búsqueda dinámica solo están disponibles hasta el nivel de grupo de anuncios a partir del 7 de mayo de 2022. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Nuevos tutoriales y cursos publicados para Adobe Document Cloud.

| Publicadas | Nombre | Tipo | Descripción | Aplicación |
| -----------| ---------- | ---------- | ---------- |---------- |
| Mayo de 2022 | [Uso compartido de acceso a cuentas](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/advanced-tasks-admins/share-account-access.html) | Vídeo | Obtenga información sobre cómo configurar el acceso de solo vista a transacciones en la cuenta de otro usuario. | [!DNL Acrobat Sign] |
| Mayo de 2022 | [Administración de plantillas de documento](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-managing/edit-a-template.html?lang=en) | Vídeo | Aprenda a editar o eliminar una plantilla de la biblioteca. | [!DNL Acrobat Sign] |
| Mayo de 2022 | [Cree su primer flujo en Microsoft® Power Automate](https://experienceleague.adobe.com/docs/document-services/tutorials/pdfservices/create-workflow-power-automate.html?lang=en) | Artículo | Aprenda a crear su primer flujo en Microsoft® Power Automate mediante el conector de Adobe PDF Services. | Servicios de documento |
| Mayo de 2022 | [Obtención de credenciales para Microsoft® Power Automate](https://experienceleague.adobe.com/docs/document-services/tutorials/pdfservices/getting-credentials-power-automate.html?lang=en) | Artículo | Obtenga información sobre cómo obtener credenciales para empezar a usar o probar los servicios de Adobe PDF. En función de si es un usuario de prueba o un cliente existente, este tutorial explica los pasos adecuados para obtener las credenciales. | Servicios de documento |

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
