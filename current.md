---
title: Últimas notas de la versión
description: Conozca las últimas notas de la versión, las nuevas funciones y la nueva documentación de los productos y servicios de  [!DNL Experience Cloud] . Encuentre ayuda y tutoriales nuevos acerca de [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise] y [!DNL Document Cloud].
doc-type: release notes
last-update: February 2022
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: e9a119ac8351d6431039b1e0387db1d4875a91bb
workflow-type: tm+mt
source-wordcount: '4933'
ht-degree: 49%

---

# Notas de la versión de Adobe Experience Cloud: febrero de 2022

![Banner](assets/experience-cloud-banner-3.png)

Como Experience Maker, la ruta hacia el éxito empieza por [Adobe Experience League](https://experienceleague.adobe.com/?lang=en#home). Encuentre una amplia biblioteca de documentación de procedimientos, tutoriales autoguiados, vídeos explicativos y cursos para todos los niveles y funciones, una comunidad en línea de compañeros y asistencia técnica especializada cuando la necesite.

¿Listo para empezar? [Haga un test de 5 minutos y gane](https://exploreadobe.com/experience-league-quiz/)!

>[!NOTE]
>
>Para recibir una notificación mensual por correo electrónico acerca de las actualizaciones realizadas en esta página, suscríbase a la [Actualización de producto prioritario de Adobe](https://www.adobe.com/subscription/priority-product-update.html). Vuelva con frecuencia para mantenerse al tanto de lo que está pasando en Experience League.

**Febrero de 2022**

Última actualización: **11 de febrero de 2022**

* [Los eventos de [!DNL Experience League]](#events)
* [[!UICONTROL Estado del sistema] de Adobe](#status)
* [[!DNL Experience Cloud Central Interface Components] &amp; Administración](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Target]](#target) (Actualización: **3 de febrero de 2022**)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [Modelos de experiencia digital: tutoriales](#blueprints)

¿Necesita ayuda? Visite [Adobe Experience League](https://experienceleague.adobe.com/?lang=es#home) para encontrar la documentación técnica y de los productos, cursos seleccionados por Adobe, tutoriales de vídeo, respuestas rápidas, conocimiento de la comunidad y formación impartida por instructores.

## ![Icono](/assets/experience-league.png) Los eventos de [!DNL Experience League] {#events}

Los eventos de Experience League son un buen lugar para obtener respuestas de los expertos en productos de Adobe. Tres tipos de eventos incluyen:

| Tipo de evento | Descripción |
| -----------|---------- |
| [Experience League LIVE ](#exl-live) | Un programa de transmisión en vivo producido por el equipo del Experience League y alojado en YouTube. Es una oportunidad para conectar con expertos en productos de Adobe y aprender consejos, trucos y estrategias útiles que puede poner en práctica con las aplicaciones de Adobe Experience Cloud.<br> Desplácese hacia abajo para obtener más información sobre los próximos eventos y ver los eventos anteriores alojados en [Experience League Activo](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=es). |
| [Pausas para café de preguntas y respuestas de la comunidad ](#coffee) | Pase una hora con un invitado especial y envíe sus preguntas en las comunidades de Experience League! Obtenga respuestas de expertos en productos en Adobe Tome un café y charle con los responsables de productos de las comunidades de Experience League.<br>Desplácese hacia abajo para leer lo que vamos a cubrir. ¡No olvides registrarte antes de que sea demasiado tarde! |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=es) | Eventos de vídeo a petición disponibles en el Experience League. |

{style=&quot;table-layout:auto&quot;}

### Experience League LIVE {#exl-live}

| Fecha del evento | Fecha | Nombre del evento | Formato | Descripción |
| -----------| ---------- | ---------- | ---------- |---------- |
| 3 de febrero de 2022 | Bajo demanda | [Presentación de todas las nuevas demostraciones de referencia en AEM](https://www.youtube.com/watch?v=FEREXV826NQ) | Evento de vídeo en directo | Aprenda la forma más rápida de aprovisionar, mostrar y explorar las características de AEM as a Cloud Service. |

{style=&quot;table-layout:auto&quot;}

### Coffee breaks de preguntas y respuestas de la comunidad {#coffee}

| Nombre del evento | Fecha | Aplicaciones | Formato | Descripción |
| -----------| ---------- | ---------- | ---------- |---------- |
| Comunidad de Adobe Target;pausa para café | 23 de febrero de 2022 @ 8am PST | Adobe Target, Experience Platform, RTCDP | Preguntas y respuestas del foro | [Regístrese ahora](http://atcommunityqacoffeebreak.splashthat.com/?utm_source=in-product&amp;utm_medium=gainsight&amp;utm_campaign=coffee_talk_AT&amp;utm_content=220223)! Únase a nosotros en la Comunidad de Adobe Target de 8 a.m. a 9 a.m. PT para obtener respuestas de expertos de Vishal Chordia, Director de Productos Senior. Responderá a todas sus preguntas relacionadas con Adobe Experience Platform (AEP), Personalización basada en audiencias, Real-time Customer Data Platform (RTCDP) con Target y Adobe Target general |

{style=&quot;table-layout:auto&quot;}

### Adobe Developers Live {#dev-live}

| Evento | Fecha y hora | Tipo | Descripción |
| -----------| ---------- | ---------- |---------- |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=en) | Bajo demanda | Vídeo | [!DNL Developers Live] muestra los últimos avances tecnológicos y herramientas para desarrolladores que permiten el diseño, los flujos de trabajo de creación de contenido, los servicios de documentos y la administración de experiencias del cliente en todas las industrias. Vea la dirección principal, obtenga información acerca de las API de Analytics, la capa de datos del cliente, los proyectos de código abierto de Adobe I/O y mucho más. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] proporciona información detallada, actualizaciones de estado y notificaciones por correo electrónico sobre los productos de Adobe y las interrupciones y sesiones de mantenimiento de los servicios. Puede comprobar el estado en [status.adobe.com](https://status.adobe.com/es).

Fecha de la versión: **16 de noviembre de 2021**

**Novedades**

* El estado de Adobe ahora informa de incidentes a nivel de producto. Las páginas de Status Cloud y Product tienen un nuevo aspecto y filtros mejorados basados en los informes de incidentes a nivel de producto. Esto facilita la comprensión del impacto de su producto en [status.adobe.com](https://status.adobe.com/) y en sus notificaciones por correo electrónico. Si no está suscrito, utilice este vínculo para configurar sus preferencias de suscripción personalizadas [https://status.adobe.com/proactive-notifications/manage](https://status.adobe.com/proactive-notifications/manage)

* La página de inicio de Estado ahora está personalizada con eventos filtrados según sus autorizaciones y suscripciones a productos. Consulte en **status.adobe.com** > **[!UICONTROL Mis eventos]** pestaña .

**Nuevas funciones y mejoras disponibles**

| Función | Descripción |
| ------- | -------|
| Informes a nivel de producto de incidentes | <ul><li>Cada producto tiene un banner en [!UICONTROL Estado] que incluye las últimas actualizaciones, el historial y los atributos de impacto del producto</li><li>Los correos electrónicos ahora siguen el mismo formato de los informes de impacto a nivel de producto en lugar de los informes a nivel de incidente</li></ul> |
| Vista personalizada de la variable [!UICONTROL Estado] página principal | <ul><li>Presentación de una nueva vista, **[!UICONTROL Mis eventos]** en el [!UICONTROL Información general] página. Esta vista filtra eventos en función de sus derechos y suscripciones</li><li>Los derechos pueden ser para organizaciones o personas. Las suscripciones pueden ser para productos o eventos</li></ul> |
| Experiencia del usuario mejorada | <ul><li>Las páginas de nube tienen un resumen de la disponibilidad de todos los productos y una capacidad de filtrar por producto, región, fechas y tipos de eventos</li><li>Las páginas de producto contienen un resumen de la disponibilidad de todas las funcionalidades y una vista detallada de los eventos y el historial</li><li>Los filtros mejorados están disponibles por capacidad, centros/entornos de datos (cuando corresponda), región, fecha, tipo de evento y estado de incidente/mantenimiento</li></ul> |
| Suscripciones mejoradas con actualización de ofertas de productos | <ul><li>Las ofertas de Adobe Analytics se actualizan a una vista fácil de usar (existente [!DNL Analytics] las suscripciones se migran a nuevas ofertas)</li><li>Ofertas granulares para [!DNL Customer Journey Analytics]</li></ul> |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] y Administración {#ecloud}

| Función | Descripción |
| ------- |-------|
| **[!UICONTROL Recientes]** (accesos directos) añadidos a [Experience Cloud](https://experience.adobe.com/home) landing | Puede acceder a los accesos directos a su actividad de Journey Optimizer y Experience Platform más reciente en la nueva **[!UICONTROL Recientes]** encabezado. Esta actualización también incluye mejoras generales de diseño y capacidad de respuesta en la página de aterrizaje. |
| **[!UICONTROL Sandboxes]** se ha movido a la barra de encabezado | El indicador Sandboxes ahora está integrado en el encabezado para todas las aplicaciones de interfaz de Experience Platform. Consulte [Sandboxes](https://experienceleague.adobe.com/docs/experience-platform/sandbox/ui/user-guide.html?lang=es) en Experience Platform para obtener más información. |

{style=&quot;table-layout:auto&quot;}

**Más recursos de ayuda de [!DNL Experience Cloud Central UI Components] y Administración**

* [Notas de la versión](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=en) para los componentes de la interfaz de usuario de Experience Cloud Central
* [Administración de usuarios y productos](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=es) Experience Cloud (administración)
* Servicio de Places [notas de la versión](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=es)
* Documentación del producto para [People: Atributos del cliente y biblioteca de audiencias](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)

## ![Icono](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Información de la versión más reciente y nueva documentación para Experience Platform y [!UICONTROL SDK móvil]:

Fecha de la versión: **26 de enero de 2022**

* [Notas de la versión de Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=es)

### Nuevos tutoriales y cursos de Experience Platform {#tutorials-platform}

Nuevos vídeos, tutoriales o cursos publicados para Experience Platform.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Febrero de 2022 | [Implementación de Adobe Experience Cloud con SDK web](https://experienceleague.adobe.com/docs/platform-learn/implement-web-sdk/overview.html) | Tutorial de varias páginas | Obtenga información sobre cómo implementar aplicaciones de Experience Cloud mediante el SDK web de Adobe Experience Platform. Este tutorial muestra cómo implementar el SDK web de Platform mediante un sitio web de venta minorista de muestra denominado _Luma_. La variable [Luma](https://luma.enablementadobe.com/content/luma/us/en.html) El sitio tiene una capa de datos y una funcionalidad enriquecidas que le permiten crear una implementación realista. ¡Empieza ahora! |
| Febrero de 2022 | [Personalización de próxima visita con CDP en tiempo real y Adobe Target](https://experienceleague.adobe.com/docs/platform-learn/tutorials/experience-cloud/next-hit-personalization.html) | Vídeo | Obtenga información sobre cómo personalizar en la siguiente visita individual con [!UICONTROL Real-time Customer Data Platform] y Adobe Target. El destino de Adobe Target en CDP en tiempo real le permite utilizar segmentos de Experience Platform en Adobe Target para la personalización de la misma página y de la página siguiente con control y compatibilidad con la privacidad. |

{style=&quot;table-layout:auto&quot;}

### SDK de Adobe Mobile

Consulte [Notas de la versión y registros de cambios](https://aep-sdks.gitbook.io/docs/release-notes) para conocer los SDK de Adobe Experience Platform Mobile.

## ![Icono](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Fecha de publicación: **16 de febrero de 2022**

* Adobe Analytics [notas de la versión](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=en) (**nueva ubicación**)
* Adobe Analytics [documentación y tutoriales del producto](https://experienceleague.adobe.com/docs/analytics.html?lang=es)

### [!DNL Customer Journey Analytics] {#cja}

Fecha de publicación: **16 de febrero de 2022**

* Customer Journey Analytics [notas de la versión](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=en)  (**nueva ubicación**)
* Customer Journey Analytics [documentación y tutoriales del producto](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=en)

### AppMeasurement {#appm}

Versión: **2,22,4**

* [Notas de la versión de AppMeasurement para JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=en)

### Nuevos tutoriales y cursos de Analytics {#tutorials-analytics}

Nuevos vídeos, tutoriales o cursos publicados de Adobe Analytics.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Febrero de 2022 | [Manipulación de datos entrantes con reglas de procesamiento](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/manipulating-incoming-data-with-processing-rules.html?lang=es) | Vídeo | Obtenga información general sobre las reglas de procesamiento en Adobe Analytics y conozca para qué se utilizan. Conozca algunas sugerencias, ejemplos e incluso una advertencia. |
| Febrero de 2022 | [Configuración de variables de lista](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configuring-list-variables.html?lang=es) | Vídeo | Cuando debe colocar más de un valor en un eVar (una variable de conversión) al mismo tiempo, ¿qué va a hacer? Enumere variables al rescate! Descubra cómo y por qué configurar y utilizar variables de lista en Adobe Analytics. |
| Febrero de 2022 | [Configurar clasificaciones de tráfico](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-traffic-classifications.html?lang=en) | Vídeo | Obtenga información sobre cómo configurar clasificaciones para variables de tráfico, a las que se suele llamar _props_ y también para _pagename_, etc. |
| Febrero de 2022 | [Configurar clasificaciones de conversión](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-conversion-classifications.html?lang=en) | Vídeo | Obtenga información sobre la configuración de clasificaciones para variables de conversión, también conocidas como _eVars_. Esta configuración también se aplica a productos y variables de lista. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/audience-manager.png) Audience Manager {#aam}

Correcciones y mejoras en Audience Manager.

* Se ha resuelto un problema que hacía que todas las llamadas a la API devolvieran un `Undocumented` al realizarse a través de la interfaz Swagger. (AAM-59190)
* Se ha resuelto un problema que hacía que se asignaran funciones de usuario incorrectas a socios en algunas situaciones. (AAM-59451)
* Se ha resuelto un problema que hacía que la API necesitara encabezados de autenticación que distinguían entre mayúsculas y minúsculas. (AAM-58528)

Para obtener recursos de autoayuda, consulte [documentación y tutoriales del Audience Manager](https://experienceleague.adobe.com/docs/audience-manager.html?lang=en) en Experience League

## ![Icono](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe recomienda visitar la página [Actualizaciones de versión y hoja de ruta de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=es) para mantenerse al día respecto a la información de la versión.

### Versiones de productos de Experience Manager

* **Experience Manager as a Cloud Service**

   Observe el [Vídeo de información general sobre la versión de enero de 2022](https://video.tv.adobe.com/v/340120) para obtener un resumen de las funciones añadidas en la versión 2022.1.0 (enero de 2022).

   * Vídeo de presentación de las nuevas funciones de la [](https://video.tv.adobe.com/v/339278)versión de diciembre de 2021.
   * [Vídeo de información general de las nuevas funciones de la versión de octubre de 2021](https://video.tv.adobe.com/v/338253).
   * [Vídeo de las nuevas funciones de la versión de septiembre de 2021](https://video.tv.adobe.com/v/337381).

   * **Experience Manager Assets as a Cloud Service**

      _Nuevas funciones de Experience Manager Assets_

      * Dynamic Media: Ahora puede utilizar la interfaz Experience Manager - Dynamic Media para configurar [Configuración general](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-general-settings.html) y [Configuración de publicación](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-publish-settings.html) en lugar de tener que pasar por la aplicación de escritorio de Dynamic Media Classic.
      * Dynamic Media ahora admite la ingesta, previsualización, reproducción y publicación de vídeos MXF. Todavía no se admite la anotación ni el vídeo de ventas para vídeos MXF.
      * Después de configurar una conexión entre las implementaciones remotas de DAM y Sites, los recursos en DAM remoto están disponibles en la implementación de Sites. Ahora puede [actualizar, eliminar, cambiar el nombre y mover operaciones](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/use-assets-across-connected-assets-instances.html?lang=es) en recursos o carpetas DAM remotos. Las actualizaciones, con algún retraso, están disponibles automáticamente en la implementación de Sites.

      _Nuevas funciones en el canal de prelanzamiento de Experience Manager Assets_

      * Dynamic Media ahora proporciona la flexibilidad para permitirle [configurar una cuenta de alias de compañía](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-alias-account.html?lang=en) en la interfaz de usuario, de modo que se actualicen las URL de Dynamic Media y el código de incrustación de visor predeterminados. Esta acción influye positivamente en SEO para reflejar las actualizaciones realizadas en el contexto de su negocio, como el cambio de marca.
      * Ahora puede utilizar la interfaz de usuario de Experience Manager Assets para:

         * Configure la detección de recursos duplicados en un repositorio.
         * Configure la adición de marcas de agua digitales a las imágenes.
      * Los administradores ahora pueden configurar el servicio de correo electrónico para las descargas grandes. Permite a los usuarios [activar notificaciones por correo electrónico para descargas grandes](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/download-assets-from-aem.html?lang=en#enable-email-notifications-for-large-downloads) de la interfaz de Experience Manager Assets. El usuario recibe una notificación por correo electrónico que contiene el vínculo de descarga de la carpeta zip archivada al finalizar el proceso de descarga.
      * La variable [Administrar publicación](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en) se mejora con una interfaz de usuario mejorada. Los usuarios pueden publicar o cancelar la publicación del contenido desde y hacia el destino seleccionado, y [Añadir contenido](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#add-content) a la lista de publicaciones desde el repositorio de DAM. También pueden [Incluir configuración de carpeta](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#include-folder-settings) para publicar contenido de las carpetas seleccionadas y aplicar filtros, y [programar publicación](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#publish-assets-later) a una fecha u hora posterior.

      _Corrección de errores_

      * Los recursos sin procesar sin representación original se envían a Asset compute para su procesamiento mientras se migran los recursos de Experience Manager On-Premise a Cloud Services.
   * **Experience Manager Forms as a Cloud Service**

      _Novedades en Forms_

      * **Experience Manager Forms as a Cloud Service - Comunicaciones** — [API de comunicación](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=es) le ayuda a combinar una plantilla y los datos XML para generar documentos de impresión en distintos formatos. El servicio permite generar documentos en modos sincrónico y por lotes. Las API le ayudan a crear aplicaciones que le permitan lo siguiente:

         * Generar documentos rellenando archivos de plantilla con datos XML.
         * Genere formularios en varios formatos, incluidas las secuencias de impresión de PDF no interactivas.
         * Genere PDF de impresión a partir de PDF de formularios XFA.
         * Genere documentos de PDF, PostScript, PCL y ZPL de forma masiva combinando varios conjuntos de datos con plantillas de origen.
      * **Fuentes personalizadas para documentos de registro y PDF creados con API de comunicaciones** ahora puede utilizar fuentes aprobadas por la marca en documentos de PDF generados mediante API de comunicaciones para cumplir con los requisitos de la organización.

      _Novedades en el canal de prelanzamiento de Forms_

      * [API del ensamblador](https://developer.adobe.com/experience-manager-forms-cloud-service-developer-reference/references/assembler-sync/) — las API del ensamblador para combinar, reorganizar, aumentar y obtener información sobre documentos del PDF.
   * **Cloud Manager**

      _Fecha de la versión_

      La fecha de la versión de Cloud Manager en Experience Manager as a Cloud Service 2022.01.0 es el 20 de enero de 2022.
La próxima versión está prevista para el 10 de febrero de 2022.

      _Nuevas funciones_

      * Cloud Manager [evita la reconstrucción de la base de código cuando detecta que se utiliza la misma confirmación git](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/create-application-project/setting-up-project.html?lang=en#build-artifact-reuse) en varias ejecuciones de canalización de pila completa.
      * El acceso al registro de entorno del Experience Manager ahora requiere la variable **[!UICONTROL Administrador de implementación]** perfil de producto. Los usuarios sin este perfil ven un botón deshabilitado en la interfaz de usuario.
      * La interfaz de usuario no permite la configuración de canalización de front-end para un programa en el que Sites no esté habilitado como solución.
      * Al generar una contraseña de git, se muestra la fecha de caducidad.








### Comunidad

* **Seminario web del Experience Manager GEM: _Creación de sitios más rápida con Experience Manager sin encabezado y App Builder_**

   **Fecha**: Miércoles, 23 de marzo de 2022
   **Tiempo**: 8:00 A.M. (PST), 5:00 (CET) o 9:00 (IST)
   **Altavoz**: Duy Nguyen, ingeniero de desarrollo de software de Adobe
   [Regístrese para unirse al seminario web en https://adobe.ly/3oCkEsh](https://adobe.ly/3oCkEsh)
   [Preguntas frecuentes sobre el seminario web](https://adobe.ly/3LkSWdm)

* Reproduzca el seminario web del Experience Manager GEM de enero de 2022: [_Experience Manager as a Cloud Service para el examen de 2021 y las perspectivas de 2022_](https://adobe.ly/3rqbSOz)

### Nuevos cursos y tutoriales para Experience Manager {#tutorials-aem}

Nuevos vídeos, tutoriales y cursos publicados durante el mes pasado.

| Publicadas | Nombre | Tipo | Descripción | Aplicación |
| ------| ------| ----- | -----| ----|
| Febrero de 2022 | [Crear credenciales de servicio](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/service-credentials.html) | Vídeo | Obtenga información sobre cómo crear credenciales de servicio para garantizar la autenticación segura para sus integraciones con AEM as a Cloud Service. | AEM Forms CS |
| Febrero de 2022 | [Creación de un token web JSON (JWT)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-jwt.html) | Artículo | Obtenga información sobre los tokens web JSON, un método abierto y estándar del sector RFC 7519 para representar reclamaciones de forma segura entre dos partes. `JWT.io` las bibliotecas se utilizan en este ejemplo para generar el JWT. | AEM Forms CS |
| Febrero de 2022 | [Intercambiar JWT por token de acceso](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-access-token.html) | Artículo | El JWT creado en la variable [Creación de un token web JSON (JWT)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-jwt.html) se intercambia con las API de Adobe IMS por un token de acceso, que se puede utilizar para acceder a AEM as a Cloud Service. Obtenga información sobre cómo solicitar un token de acceso para enviar una solicitud de POST que contenga JWT, client_id, client_secret al servicio de autenticación IMS. | AEM Forms CS |
| Febrero de 2022 | [Incrustación de fuentes en pdf generado](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/intellij-set-up.html?lang=en#add-the-fonts-module) | Artículo | Obtenga información sobre cómo instalar [!DNL IntelliJ] edición comunitaria. | AEM Forms CS |
| Febrero de 2022 | [Realizar la llamada del POST](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/merge-data-with-template.html) | Vídeo | Obtenga información sobre cómo realizar una llamada de POST HTTP al extremo con los parámetros necesarios. La plantilla y los archivos de datos se proporcionan como archivos de recursos. | Forms CS |
| Febrero de 2022 | [Migración desde arquetipo de AEM antiguo](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/updating-project-archetype.html?lang=en) | Vídeo | Desc. | Forms CS |
| Febrero de 2022 | [Externalización del almacenamiento de datos de flujo de trabajo en AEM Forms CS](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/create-aem-workflow/externalize-workflow.html?lang=en) | Vídeo | Obtenga información sobre cómo almacenar los datos del flujo de trabajo en el almacenamiento de Azure. AEM Forms CS tiene la nueva capacidad de almacenar los datos de flujo de trabajo, como variables, archivos adjuntos, etc., en una cuenta de almacenamiento externa. | AEM Forms CS |
| Febrero de 2022 | [Integración de Adobe Analytics con la automatización de la configuración del Experience Cloud](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/integrations/adobe-analytics-exc-setup-automation.html) | Vídeo | Descubra cómo la automatización de la configuración de Experience Cloud proporciona una forma sencilla y automatizada de integrar e instrumentar Experience Manager Sites con Experience Platform Launch y Adobe Analytics. | AEM Sites |
| Febrero de 2022 | [Recommendations de producto](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/authoring/product-recommendations.html) | Vídeo | Aprenda a insertar dinámicamente estas recomendaciones de productos en una tienda de Adobe Experience Manager (AEM). Adobe Commerce cuenta con un motor de recomendaciones equipado con Adobe Sensei. | AEM y Adobe Commerce |

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

## ![Icono](/assets/ec_appicon_24.png) Documentación XML para Adobe Experience Manager {#xml-doc}

La documentación de XML para Adobe Experience Manager es una aplicación implementada en AEM. Es una potente solución de administración de contenido de componentes (CCMS) de nivel empresarial que permite la compatibilidad nativa con DITA en Adobe Experience Manager, lo que permite a AEM gestionar la creación y la entrega de contenido basado en DITA.

Más información acerca [Documentación de XML para AEM](https://www.adobe.com/es/products/xml-documentation-for-experience-manager/features.html).

### Nuevos tutoriales sobre la documentación de XML para Adobe Experience Manager {#tutorials-xml-doc}

Nuevos vídeos, tutoriales o cursos publicados para la documentación de XML de Adobe Experience Manager.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Enero de 2022 | [Versiones de documentación de XML](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/tutorials/release-info/latest-release-info.html?lang=es) | Vídeo | Obtenga información sobre la documentación de XML para Adobe Experience Manager, una potente solución de administración de contenido de componentes (CCMS) con categoría empresarial. Permite la compatibilidad nativa con DITA en Adobe Experience Manager, lo que permite a AEM gestionar la creación y la entrega de contenido basado en DITA. |
| Enero de 2022 | [Generación de resultados con documentación de XML para AEM](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/output-generation/overview.html?lang=es) | Vídeos y artículos | Obtenga información sobre el tablero de mapas, informes, publicación con líneas de base y condiciones, etc. |

{style=&quot;table-layout:auto&quot;}

### Recursos adicionales

* [Documentación XML para Adobe Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=es) : tutoriales sobre Experience League
* [Documentación XML para obtener información y asistencia de Adobe Experience Manager](https://helpx.adobe.com/support/xml-documentation-for-experience-manager.html) - documentación del producto

## ![Icono](/assets/magento.png) [!DNL Adobe Commerce] {#magento}

Consulte los siguientes vínculos para ver las notas de la versión de Adobe Commerce:

* [Adobe Commerce y Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite para Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### Nuevos tutoriales de Adobe Commerce {#tutorials-commerce}

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Febrero de 2022 | [Actualizar Adobe Commerce/Magento Open Source](https://experienceleague.adobe.com/docs/commerce-operations/upgrade-guide/overview.html) | Guía del usuario | Obtenga toda la ayuda necesaria para continuar con el proceso de actualización. |
| Febrero de 2022 | [Taller de actualización de Adobe Commerce 2.4](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/upgrade-workshop.html?lang=en) | Vídeo | Conozca los pasos y las prácticas recomendadas a seguir al prepararse para la próxima actualización a la versión 2.4.4 o superior. |
| Febrero de 2022 | [Uso de la herramienta de compatibilidad de actualización en PhpStorm](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/uct-phpstorm.html?lang=en) | Vídeo | Aprenda a utilizar la variable `PhpStorm` plugin |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/target.png) [!DNL Adobe Target] {#target}

Última actualización: **1 de febrero de 2022**

* Para obtener información previa al lanzamiento, consulte [Versión preliminar de Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=es)
* Para obtener información actual, consulte [Notas de la versión de Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=en)

## ![Icono](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign permite entregar, de forma intuitiva y automatizada, mensajes privados a través de canales de marketing en línea y sin conexión. Ahora puede anticipar los deseos de los clientes mediante experiencias basadas en sus hábitos y preferencias.

### Últimas versiones de productos de Campaign

Conozca las últimas funciones, mejoras y correcciones publicadas:

* (Nuevo!) [Versión de Campaign Standard 2.1](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=es)
* [Campaign v8.2.10](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=es)
* [Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=es)

### Nuevos tutoriales y cursos [!DNL Campaign] {#tutorials-campaign}

Nuevos vídeos, tutoriales o cursos publicados de Adobe Campaign.

| Publicadas | Nombre | Tipo | Descripción | Versión |
| ------| ----- | -----| ------ | --- |
| Febrero de 2022 | [Aspectos básicos de la administración de datos con flujos de trabajo de Adobe Campaign](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/data-management-fundamentals.html?lang=en) | Vídeo | Descubra cuáles son las dimensiones de segmentación y las tablas de trabajo, y cómo administra Adobe Campaign los datos en diferentes fuentes de datos. | Campaign v8 |
| Febrero de 2022 | [Cambiar la fuente de datos](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/change-data-source.html?lang=en) | Vídeo | Aprenda a cambiar la fuente de datos de una tabla de trabajo de flujo de trabajo mediante la actividad Cambiar fuente de datos para administrar datos de forma flexible en diferentes fuentes de datos, como FDA, FFDA y la base de datos local. | Campaign v8 |

{style=&quot;table-layout:auto&quot;}

### Recursos de ayuda de Campaign

* Adobe Campaign v8: [Documentación](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=es) - [Guías de implementación](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=es)
* Adobe Campaign Standard: [Documentación de Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Vídeos de procedimientos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=es) - [Planificación de versiones](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=es) - [Últimas actualizaciones de la documentación](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=es)
* Adobe Campaign Classic: [Documentación de Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Vídeos de procedimientos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=es) - [Actualizaciones más recientes de la documentación](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=es)
* Panel de control de Adobe Campaign: [Documentación](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=es) - Vídeos prácticos para [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=es) y [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=es)

## ![Icono](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Con Journey Optimizer, puede administrar campañas omnicanal programadas y momentos uno a uno para millones de clientes desde una sola aplicación, y todo el recorrido se optimiza con decisiones y perspectivas inteligentes.

### Últimas versiones de productos de Journey Optimizer

Descubra las funcionalidades, mejoras y correcciones más recientes en las [Notas de la versión de Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=es).

### Más recursos para [!DNL Journey Optimizer]

* [Documentación de Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=es)
* [Documentación de gestión de decisiones](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html) - [Notas de la versión](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=es) - [Últimas actualizaciones de la documentación](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=es)

## ![Icono](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Utilice Experience Platform para orquestar el recorrido de un cliente a escala a través de canales de experiencia, anticipando de forma inteligente las necesidades de cada individuo en tiempo real.

### Últimas versiones de productos de [!DNL Journey Orchestration]

Obtenga más información acerca de las funcionalidades, mejoras y correcciones más recientes en las Notas de la versión de [[!DNL Journey Orchestration] ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=es).

#### Más recursos para [!DNL Journey Orchestration]

* [Documentación de Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=es) - [Últimas actualizaciones de la documentación](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=es)

## ![Icono](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] es una aplicación completa para la gestión de posibles clientes y para los especialistas en marketing B2B que buscan transformar las experiencias de los clientes al interactuar en todas las fases de los recorridos de compra complejos.

### Actualizaciones centrales de Marketo Engage

Consulte [!DNL Marketo Engage] [programación de versiones](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=es) para obtener la información más reciente sobre el calendario de versiones y las notas de la versión.

## ![Icono](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] es una aplicación de administración de trabajo unificada para compartir ideas, crear contenido, administrar procesos complejos y trabajar de forma óptima.

Consulte la página [[!DNL Workfront] Versiones](https://one.workfront.com/s/product-releases) de para obtener un resumen de la información más reciente de todos los productos.

## ![Icono](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

Notas de la versión para [!DNL Adobe Advertising Cloud].

* [Nuevas funciones en  [!DNL Advertising Cloud]](#adcloud-all)
* [Nuevas funciones en  [!DNL Advertising Cloud DSP]](#adcloud-dsp)
* [Nuevas funciones en  [!DNL Advertising Cloud Search]](#adcloud-search)
* [Nuevos tutoriales de  [!DNL Advertising Cloud] ](#tutorials-ad-cloud)

### Nuevas funciones en [!DNL Advertising Cloud] {#adcloud-all}

Última actualización: **27 de octubre de 2021**

| Función | Descripción |
| ------- | ----------- |
| Analytics para Advertising Cloud | Si su organización desea dejar de utilizar el Adobe Analytics heredado `visitorAPI.js` biblioteca a la biblioteca de Adobe Experience Platform (`alloy.js`) para la recopilación de datos, debe realizar cambios para habilitar la vinculación de ID. Consulte [Uso del  [!DNL Last Event Service]  de la biblioteca JavaScript con el  [!DNL Web SDK] de Adobe Experience Platform](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html?lang=es). |

{style=&quot;table-layout:auto&quot;}

### Nuevas funciones en [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Última actualización: **27 de octubre de 2021**

| Función | Descripción |
| ------- | ----------- |
| Informes personalizados | Ahora puede crear y administrar [!DNL Amazon S3] y diferentes tipos de ubicaciones de entrega por FTP, denominadas *[!DNL report destinations]*, para sus informes personalizados. Una vez configurados los destinos de los informes, puede ajustar cada uno de los nuevos informes personalizados para que se envíen a una o más ubicaciones de un solo tipo de destino o a destinatarios de correo electrónico. Las actualizaciones de las credenciales de [!DNL Amazon S3] y FTP no interrumpen la entrega de informes.<br><br>Los informes existentes se seguirán enviando a los destinatarios de correo electrónico especificados. Para configurar la entrega a un destino de informe diferente, cree un nuevo informe con el nuevo destino. |
| Vistas de [!UICONTROL Paquetes], [!UICONTROL Ubicaciones] y [!UICONTROL Anuncios] | Cuando se ven datos de un solo día, los gráficos de tendencias ahora incluyen datos por hora. Mantenga el cursor sobre cualquier punto para ver los datos de esa hora. |
| [!UICONTROL Ubicaciones] | La ubicación [!UICONTROL Inspector] ahora incluye una pestaña de [!UICONTROL inventario], que muestra todas las ofertas y sus métricas asociadas para la ubicación. Utilice la información para realizar ajustes rápidos o solucionar problemas sin generar un informe personalizado. |
| [!UICONTROL Anuncios] | (Usuarios con permiso para incluir números de Clearcastwatch en sus anuncios) DSP ya no muestra un error si utiliza un número de reloj adjunto a otro anuncio. **Nota:** La práctica recomendada es utilizar un número de reloj único para cada anuncio de vídeo. De lo contrario, el editor no aprueba todas las publicidades. |
| [!UICONTROL ID de acuerdo] | Los ajustes de [!UICONTROL ID de acuerdo] y otros lugares de la interfaz de usuario reflejan la nueva promoción de la marca para el SSP de [!DNL Magnite]:<br><ul><li>El SSP “[!DNL Tremor]” ([!DNL Telaria]) es ahora “[!DNL Magnite CTV]”.</li><li>En las próximas semanas, [!DNL Rubicon] cambiará a [!DNL Magnite DV+], donde [!DNL DV+] significa pantalla, vídeo y otros formatos, como audio.</li></ul> |
| [!DNL Freewheel] ofertas garantizadas mediante programación | Ahora puede encontrar el estado de las publicidades para [!DNL Freewheel] ofertas programáticas garantizadas de la vista [!UICONTROL Anuncios]. Anteriormente, solo se podía comprobar el estado desde la vista [!UICONTROL Ofertas]. |

{style=&quot;table-layout:auto&quot;}

### Nuevas funciones en [!DNL Advertising Cloud Search] {#adcloud-search}

Última actualización: **4 de febrero de 2022**

| Función | Descripción |
| ------- | ----------- |
| [!UICONTROL Hojas de edición en bloque], [!UICONTROL Centro de notificaciones] | (Versión del 22 de enero) Todas las notificaciones por correo electrónico para hojas de edición masiva, que Advertising Cloud Search envía cuando se completa o falla una operación de hoja de edición masiva, ahora son gestionadas por [!UICONTROL Centro de notificaciones].<br><br>[!UICONTROL Hojas de edición en bloque] es un nuevo tipo de notificación, con sus propias preferencias de notificación, en [!UICONTROL Centro de notificaciones]. Las notificaciones por correo electrónico y las notificaciones web están habilitadas de forma predeterminada, pero también puede cambiar la configuración de las notificaciones.<br><br>El formato y el contenido de las notificaciones por correo electrónico utilizan la variable [!UICONTROL Centro de notificaciones] e incluye un vínculo de descarga directa para el archivo de hoja de edición masiva o el archivo de error asociado. |

{style=&quot;table-layout:auto&quot;}

### Nuevos tutoriales de Advertising Cloud {#tutorials-ad-cloud}

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Enero de 2022 | [Tutoriales de Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/dsp/intro.html?lang=es) | Vídeos | Hay disponibles cinco nuevos tutoriales de vídeo sobre Advertising Cloud DSP. |

## ![Icono](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Nuevos vídeos, tutoriales o cursos publicados para Adobe Document Cloud.

### Nuevos cursos y tutoriales para Document Cloud {#tutorials-doc-cloud}

Nuevos vídeos, tutoriales o cursos publicados para Adobe Document Cloud.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Febrero de 2022 | [Trabajo con campos de formulario](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/workforms.html?lang=en) | Vídeo | Aprenda a añadir varios tipos de campos de formulario, definir propiedades de campo de formulario y agregar seguridad para crear formularios profesionales de alta calidad. |
| Febrero de 2022 | [Optimize PDF para SEO (Optimización del motor de búsqueda)](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/optimizeseo.html) | Vídeo | Aprenda a optimizar un PDF para mejorar la capacidad de detección y la clasificación de los motores de búsqueda en la web. |

{style=&quot;table-layout:auto&quot;}

Para obtener ayuda de Document Cloud, consulte:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=es)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=es)
* [Información y asistencia técnica de Adobe Document Cloud](https://helpx.adobe.com/support/document-cloud.html)

## ![Icono](/assets/creative-cloud-24.png) Adobe Creative Cloud para empresas {#creative-cloud}

Consulte [Tutoriales de Creative Cloud para empresas](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=es) para obtener los más recientes.

## Modelos de experiencia digital: tutoriales {#blueprints}

[Modelos de experiencia digital](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=en) son implementaciones repetibles que le permiten abordar la estrategia y resolver rápidamente los problemas del negocio establecidos. Cada modelo proporciona una serie de artefactos que explican el problema comercial de alto valor, las arquitecturas, los pasos de implementación, las consideraciones técnicas y los vínculos a la documentación relevante.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Febrero de 2022 | [Recorridos del cliente](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/overview.html?lang=en) | Vídeo | Los Recorridos del cliente permiten a las marcas interactuar de forma proactiva con sus clientes y comunicarse con ellos a través de canales como correo electrónico, SMS y alertas móviles. |
| Febrero de 2022 | [Modelo de Campaign v7](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/campaign-v7/campaign-v7.html?lang=en) | Vídeo | Adobe Campaign v7 es una herramienta de campaña diseñada para canales de marketing tradicionales, como correo electrónico y correo postal. Proporciona sólidas capacidades de ETL y administración de datos para ayudar a diseñar y depurar la campaña perfecta. |

{style=&quot;table-layout:auto&quot;}
