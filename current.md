---
title: Últimas notas de la versión
description: Conozca las últimas notas de la versión, las nuevas funciones y la nueva documentación de los productos y servicios de  [!DNL Experience Cloud] . Encuentre ayuda y tutoriales nuevos acerca de [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise] y [!DNL Document Cloud].
doc-type: release notes
last-update: March 2022
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: bbdac176cdaed65d6312a1274551d8da517764c6
workflow-type: tm+mt
source-wordcount: '5956'
ht-degree: 92%

---

# Notas de la versión de Adobe Experience Cloud: marzo de 2022

![Titular](assets/experience-cloud-banner-3.png)

Como Experience Maker, la ruta hacia el éxito empieza por [Adobe Experience League](https://experienceleague.adobe.com/?lang=es#home). Encuentre una amplia biblioteca de documentación de procedimientos, tutoriales autoguiados, vídeos explicativos y cursos para todos los niveles y funciones, una comunidad en línea de compañeros y asistencia técnica especializada cuando la necesite.

¿Todo listo para empezar? [Complete un test de cinco minutos y gane](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp).

>[!NOTE]
>
>Para recibir una notificación mensual por correo electrónico acerca de las actualizaciones realizadas en esta página, suscríbase a la [Actualización de producto prioritario de Adobe](https://www.adobe.com/subscription/priority-product-update.html). Vuelva con frecuencia para mantenerse al tanto de lo que está pasando en Experience League.

Última actualización: **7 de abril de 2022**

* [[!DNL Experience League] events](#events) (**5 de abril** - AEM relanzamiento de Gems)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud: componentes y administración de la interfaz central](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
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

¿Necesita ayuda? Visite [Adobe Experience League](https://experienceleague.adobe.com/?lang=es#home) para encontrar la documentación técnica y de los productos, cursos seleccionados por Adobe, tutoriales de vídeo, respuestas rápidas, conocimiento de la comunidad y formación impartida por instructores.

## ![Icono](/assets/experience-league.png) Eventos de [!DNL Experience League] {#events}

Los eventos de Experience League son un buen lugar para aprender, interactuar y obtener respuestas de los expertos en productos de Adobe.

Actualizado **5 de abril de 2022**

| Evento | Tipo | Descripción |
| -----------|---------- | ----|
| [GEMs de AEM](https://experienceleague.adobe.com/docs/experience-manager-gems-events/gems/overview.html?lang=en) | Seminario web de Adobe Live | AEM actualizaciones de Gems para 2022 están disponibles! AEM Gems es nuestra serie de seminarios web de conocimientos técnicos sobre Adobe Experience Manager, impartidos por expertos en Adobe. <br>Para conocer las últimas Gems de AEM, consulte [Adobe Experience Manager as a Cloud Service: 2021 Review y 2022 Outlook](https://experienceleague.adobe.com/docs/experience-manager-gems-events/gems/gems2022/aemcloudservice-2021-review-and-outlook.html?lang=en) y [Creación de sitios más rápida con AEM sin encabezado y App Builder](https://experienceleague.adobe.com/docs/experience-manager-gems-events/gems/gems2022/build-sites-faster-with-headless-and-appbuilder.html?lang=en).<br>Visite estas notas de la versión con frecuencia o suscríbase al [Actualización de producto prioritario de Adobe](https://www.adobe.com/subscription/priority-product-update.html) para mantenerse al tanto de AEM Gems y otros eventos Experience League. |
| [Creadores de experiencia: el intercambio de habilidades para Adobe Workfront](https://events.bizzabo.com/385867?promo=CustomerM&amp;tr=true) | Seminario web de Adobe Live | Estamos encantados de anunciar la primera edición de _Experience Makers: The Skills Exchange for Adobe Workfront_. <br>Este evento de aprendizaje digital gratuito de tres horas se centra exclusivamente en Workfront. Puede hacer preguntas a expertos y compañeros que conozcan mejor la gestión del trabajo. Tanto si es nuevo en Workfront como si es un experto, puede ser útil para todos.<br>**Fecha:** Miércoles, 13 de abril a las 9:00 a.m. - 12:00 PDT [Detalles e inscripción](https://events.bizzabo.com/385867?promo=CustomerM&amp;tr=true): Adobe recomienda registrarse incluso si no puede asistir, de modo que se garantice el acceso a las grabaciones a petición. |
| [Adobe Workfront System Admin Essentials: Diseño de una experiencia de usuario ideal](https://webinars.on24.com/adobe_workfront/AdminEssentialsUserExp?partnerref=field) | Seminario web de Adobe Live | Únase a Mary Ann Erickson, directora de éxitos del cliente en Adobe Workfront, y Steve Enos, analista de operaciones creativas en Liberty Mutual Insurance para averiguar cómo diseñar una experiencia de usuario ideal. <br>**Fecha:** Miércoles, 27 de abril. Tiempo: 8:00am PDT / 4:00pm Reino Unido. <br>[Detalles e inscripción](https://webinars.on24.com/adobe_workfront/AdminEssentialsUserExp?partnerref=field) |
| [Experience League LIVE](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=es) | Vídeo en directo y bajo demanda | Un programa de streaming en directo producido por el equipo Experience League. Es una oportunidad para conectar con expertos en productos de Adobe y conocer consejos, trucos y estrategias útiles que puede poner en práctica con las aplicaciones de Adobe Experience Cloud.<br> [Detalles y eventos anteriores](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) |
| [Adobe Analytics: contar historias impactantes con datos](https://engage.adobe.com/adobe-analytics-telling-impactful-stories.html?s_rtid=7015Y0%5b%E2%80%A6%5d15Y000003A5SbQAK&amp;sfid=&amp;acctid=&amp;ecp=&amp;sdid=JCNCWJFP&amp;mv=display) | Seminario web de Adobe Live | La narración con datos está bien ejecutada cuando es un equilibrio entre arte y ciencia. Así que, ¿por qué utilizar demasiado la ingeniería? La campeona de Adobe Analytics, Amy Ard, ha creado tres partes que tienen como objetivo guiar la narración de sus datos sin que se resienta la creatividad:<ul><li>Identificación de la oportunidad o problema</li><li>Explicación a través de los datos</li><li>Ofrecimiento de una solución</li></ul>**Fecha:** jueves, 31 de marzo. [Detalles y registro](https://engage.adobe.com/adobe-analytics-telling-impactful-stories.html?s_rtid=7015Y0%5b…%5d15Y000003A5SbQAK&amp;sfid=&amp;acctid=&amp;ecp=&amp;sdid=JCNCWJFP&amp;mv=display) |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=es) | Vídeo | [!DNL Developers Live] muestra los últimos avances tecnológicos y herramientas para desarrolladores que permiten el diseño, los flujos de trabajo de creación de contenido, los servicios de documentos y la administración de experiencias del cliente en todas las industrias. Vea la dirección principal, obtenga información acerca de las API de Analytics, la capa de datos del cliente, los proyectos de código abierto de Adobe Developer y mucho más. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] proporciona información detallada, actualizaciones de estado y notificaciones por correo electrónico sobre los productos de Adobe y las interrupciones y sesiones de mantenimiento de los servicios. Puede comprobar el estado en [status.adobe.com](https://status.adobe.com/es).

Para obtener la información más reciente sobre la versión, consulte las [notas de la versión](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=es#status) del Estado del sistema de Adobe.

## ![Icono](/assets/ec_appicon_24.png) Experience Cloud: componentes y administración de la interfaz central {#ecloud}

Los [componentes de la IU central](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=es) de Experience Cloud incluyen las funciones disponibles en la página de inicio y el encabezado de producto persistente. Estas funciones incluyen la configuración del perfil del usuario, las preferencias y la búsqueda. También puede encontrar ayuda sobre la administración de usuarios y productos, los atributos del cliente y las audiencias de Experience Cloud.

| Función | Descripción |
| ------- |-------|
| Acceda a _[!UICONTROL Recientes]_ entre Experience Platform y Journey Optimizer mediante la [!UICONTROL Búsqueda unificada] | Puede acceder a los objetos a los que ha accedido recientemente desde todas las páginas de Experience Platform y Journey Optimizer a través del campo [!UICONTROL Búsqueda unificada].<br>Consulte [Búsqueda unificada de objetos y entidades](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=es) para obtener más información. |

{style=&quot;table-layout:auto&quot;}

**Más recursos de ayuda de [!DNL Experience Cloud Central UI Components] y Administración**

* [Notas de la versión](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=es) para los componentes centrales de la IU de Experience Cloud
* [Administración de usuarios y productos](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) Experience Cloud (administración)
* [Notas de la versión](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=es) del servicio Places
* Documentación del producto para [People: atributos del cliente y biblioteca de audiencias](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=es)
* [Búsqueda unificada de objetos y entidades](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=en)

## ![Icono](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Información sobre la última versión y la nueva documentación de Experience Platform y el [!UICONTROL SDK móvil]:

Fecha de la versión: **7 de marzo de 2022**

* [Notas de la versión de Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=es)

### Nuevos tutoriales y cursos de Experience Platform {#tutorials-platform}

Nuevos vídeos, tutoriales o cursos publicados para Experience Platform.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Marzo de 2022 | [Tutorial de implementación de Adobe Experience Cloud en aplicaciones móviles](https://experienceleague.adobe.com/docs/platform-learn/implement-mobile-sdk/overview.html?lang=es) | Curso | Obtenga información sobre cómo implementar aplicaciones de Adobe Experience Cloud en su aplicación móvil mediante el SDK móvil de Adobe Experience Platform. |
| Marzo de 2022 | [Generación de ID de dispositivos de origen](https://experienceleague.adobe.com/docs/platform-learn/data-collection/edge-network/generate-first-party-device-ids.html?lang=es) | Vídeo | Obtenga información acerca de la generación de ID de dispositivos de origen y cómo funcionan. |
| Marzo de 2022 | [Configuración de flujos de datos](https://experienceleague.adobe.com/docs/platform-learn/data-collection/edge-network/configure-datastreams.html?lang=es) | Vídeo | Obtenga información sobre cómo crear y configurar flujos de datos para implementaciones de SDK web y móvil. |

{style=&quot;table-layout:auto&quot;}

### SDK de Adobe Mobile

Consulte [Notas de la versión y registros de cambios](https://aep-sdks.gitbook.io/docs/release-notes) para conocer los SDK de Adobe Experience Platform Mobile.

## ![Icono](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Fecha de la versión: **23 de marzo de 2022**

* [Notas de la versión](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=es) de Adobe Analytics (**nueva ubicación**)
* [Tutoriales y documentación del producto](https://experienceleague.adobe.com/docs/analytics.html?lang=es) de Adobe Analytics

### AppMeasurement {#appm}

Versión: **2.22.4**

* [Notas de la versión de AppMeasurement para JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=es)

### Nuevos tutoriales y cursos de Analytics {#tutorials-analytics}

Nuevos vídeos, tutoriales o cursos publicados de Adobe Analytics.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Marzo de 2022 | [Sugerencias y trucos para simplificar la formación de usuarios y dedicarle menos tiempo](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/simplify-training-users.html?lang=es) | Vídeo y artículo | Aprenda lo esencial para el éxito que puede ser una organización de Adobe Analytics bien formada para su negocio. |
| Marzo de 2022 | [Creación de una comunidad empoderada](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/empowered-community.html?lang=es) | Vídeo y artículo | Conozca el valor de una comunidad de Analytics empoderada y cómo crear y apoyar una. |
| Marzo de 2022 | [Creación de reglas de procesamiento para los canales de marketing](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/create-marketing-channel-processing-rules.html?lang=es) | Vídeo | Obtenga información sobre cómo configurar [!UICONTROL reglas de procesamiento] para los [!UICONTROL canales de marketing]. |
| Marzo de 2022 | [Configuración de canales de marketing en el grupo de informes](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/set-up-marketing-channels.html?lang=es) | Vídeo | En este vídeo, aprenderá a configurar la creación de informes de canales de marketing en su grupo de informes de Analytics. |
| Marzo de 2022 | [Transición a Adobe Analytics desde Google Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/intro-to-analytics/transitioning-from-other-platforms/transition-from-google-analytics.html?lang=es) | Vídeo | Una guía completa para la transición a [!DNL Adobe Analytics] desde [!DNL Google Analytics]. |
| Marzo de 2022 | [Configuración de variables de jerarquía](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-hierarchy-variables.html?lang=es) | Vídeo | Aprenda cómo y cuándo establecer y configurar variables de jerarquía para el sitio. Esta función se puede usar para mostrar una vista jerárquica de las páginas del sitio y cuánto tráfico llega a cada nodo. |
| Marzo de 2022 | [Depuración y uso compartido en Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/curation-and-sharing-in-analysis-workspace.html?lang=es) | Vídeo | Aprenda a trabajar con la depuración y el uso compartido de proyectos en Analysis Workspace. |
| Marzo de 2022 | [Vínculo directo a un proyecto en Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/direct-link-to-a-project.html?lang=es) | Vídeo | Aprenda a democratizar mejor el análisis mediante la creación de vínculos abreviados que llevan a sus compañeros directamente a sus proyectos de Analysis Workspace. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

Fecha de la versión: **23 de marzo de 2022**

* [Notas de la versión](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=es) de Customer Journey Analytics (**nueva ubicación**)
* [Tutoriales y documentación del producto](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=es) de Customer Journey Analytics

## ![Icono](/assets/audience-manager.png) Audience Manager {#aam}

Correcciones y mejoras en Audience Manager:

| Mejora | Descripción |
| -----------| ---------- |  
| Validador para fuentes de datos de destino pertenecientes a otras empresas | Audience Manager publicó una mejora en el [proceso de incorporación de datos por lotes](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=es). Para evitar la incorporación accidental de archivos y datos en fuentes de datos de destino propiedad de otros socios, Audience Manager ha añadido un requisito de asignación entre el ID del socio (PID) y las fuentes de datos (DPID) propiedad de otros socios. <ul><li>Vea también el campo __DPID_TARGET_DATA_OWNER_ en [Requisitos de tamaño de archivo y nombre de Amazon S3 para archivos de datos entrantes](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=es#name-elements).</li><li>Los consultores y el Servicio de atención al cliente internos de Adobe deberían leer el documento [Administración del acceso de incorporación para datos de segundo nivel](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=es) para obtener información acerca de la nueva mejora de la asignación requerida y cómo solicitar una nueva asignación.</li><li>_No_ es necesario para solicitar una asignación para las relaciones de uso compartido de datos existentes. La asignación _tampoco_ es obligatoria al incorporar datos en fuentes de datos de destino que pertenecen a su PID.</li></ul> |

{style=&quot;table-layout:auto&quot;}

Para obtener recursos de ayuda, consulte [Documentación y tutoriales de Audience Manager](https://experienceleague.adobe.com/docs/audience-manager.html?lang=es) en Experience League.

## ![Icono](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe recomienda visitar la página [Actualizaciones de versión y hoja de ruta de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=es) para estar al día respecto a la información de la versión.

### Actualizaciones de producto de Experience Manager

* **Paquete de servicio 12 de Experience Manager 6.5 (6.5.12.0)**

   Adobe Experience Manager 6.5.12.0 incluye nuevas funciones, mejoras clave solicitadas por los clientes y otras de rendimiento, estabilidad y seguridad, que se han publicado desde la puesta a disposición de la versión 6.5 en abril de 2019. El paquete de servicio está instalado en Adobe Experience Manager 6.5.

   Consulte las [Notas de la versión](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=es).

### Versiones de productos de Experience Manager

* **Experience Manager as a Cloud Service**

   Vea el [vídeo de información general sobre la versión de marzo de 2022](https://video.tv.adobe.com/v/341465) para obtener un resumen de las funciones añadidas en la versión 2022.3.0 (marzo de 2022). <!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

   * Vídeo de las nuevas funciones de la [versión de enero de 2022](https://video.tv.adobe.com/v/340120).
   * Vídeo de las nuevas funciones de la [versión de diciembre de 2021](https://video.tv.adobe.com/v/339278).
   * Vídeo de las nuevas funciones de la [versión de octubre de 2021](https://video.tv.adobe.com/v/338253).
   * Vídeo de las nuevas funciones de la [versión de septiembre de 2021](https://video.tv.adobe.com/v/337381).

   * **Experience Manager Assets as a Cloud Service**

      _Nuevas funciones en Experience Manager Assets_

      * Dynamic Media: ahora puede utilizar la interfaz de Dynamic Media de Experience Manager para configurar la [Configuración general](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-general-settings.html?lang=es) y la [Configuración de publicación](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-publish-settings.html?lang=es) en lugar de tener que pasar por la aplicación de escritorio de Dynamic Media Classic.
      * Dynamic Media ahora admite la ingesta, previsualización, reproducción y publicación de vídeos MXF. Todavía no se admite la anotación ni el vídeo de ventas para vídeos MXF.
      * Después de configurar una conexión entre las implementaciones remotas de DAM y Sites, los recursos en DAM remoto están disponibles en la implementación de Sites. Ahora puede [actualizar, eliminar, cambiar el nombre y mover operaciones](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/use-assets-across-connected-assets-instances.html?lang=es) en recursos o carpetas DAM remotos. Las actualizaciones, con algún retraso, están disponibles automáticamente en la implementación de Sites.

      _Nuevas funciones en el canal de prelanzamiento de Experience Manager Assets_

      * Dynamic Media ahora proporciona la flexibilidad para permitirle [configurar una cuenta de alias de compañía](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-alias-account.html?lang=es) en la interfaz de usuario, de modo que se actualicen las URL de Dynamic Media y el código de incrustación de visualizador de forma predeterminada. Esta acción influye positivamente en el SEO para reflejar las actualizaciones realizadas en el contexto de su negocio, como el cambio de marca.
      * Ahora puede utilizar la interfaz de usuario de Experience Manager Assets para lo siguiente:

         * Configurar la detección de recursos duplicados en un repositorio.
         * Configurar la adición de marcas de agua digitales a las imágenes.
      * Los administradores ahora pueden configurar el servicio de correo electrónico para las descargas grandes. Permite a los usuarios [activar las notificaciones por correo electrónico para descargas grandes](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/download-assets-from-aem.html?lang=es#enable-email-notifications-for-large-downloads) desde la interfaz de Experience Manager Assets. El usuario recibe una notificación por correo electrónico que contiene el vínculo de descarga de la carpeta zip archivada al finalizar el proceso de descarga.
      * La función [Administrar publicación](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=es) se ha potenciado con una interfaz de usuario mejorada. Los usuarios pueden publicar o cancelar la publicación del contenido desde y hacia el destino seleccionado, y [Añadir contenido](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=es#add-content) a la lista de publicaciones desde el repositorio de DAM. También pueden [Incluir configuración de carpeta](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=es#include-folder-settings) para publicar contenido de las carpetas seleccionadas y aplicar filtros, y [programar la publicación](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=es#publish-assets-later) a una fecha u hora posterior.

      _Corrección de errores_

      * Los recursos sin procesar sin representación original se envían a Asset Compute para su procesamiento mientras se migran los recursos de Experience Manager On-Premise a los servicios en la nube.
   * **Experience Manager Forms as a Cloud Service**

      _Novedades en Forms_

      * **Experience Manager Forms as a Cloud Service, comunicaciones**: [las API de comunicación](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=es) le ayudan a combinar una plantilla y datos de XML para generar documentos de impresión en varios formatos. El servicio le permite generar documentos en modos sincrónico y por lotes. Las API le ayudan a crear aplicaciones que le permiten hacer lo siguiente:

         * Generar documentos rellenando archivos de plantilla con datos XML.
         * Generar formularios en varios formatos, incluidas las secuencias de impresión de PDF no interactivas.
         * Generar PDF de impresión a partir de PDF de formularios XFA.
         * Generar documentos de PDF, PostScript, PCL y ZPL por lotes combinando varios conjuntos de datos con plantillas de origen.
      * **Fuentes personalizadas para documentos de registro y PDF creados con API de comunicaciones**: ahora puede utilizar fuentes aprobadas por la marca en documentos de PDF generados mediante las API de comunicaciones para cumplir con los requisitos de la organización.

      _Novedades en el canal de prelanzamiento de Forms_

      * [API del ensamblador](https://developer.adobe.com/experience-manager-forms-cloud-service-developer-reference/references/assembler-sync/): las API del ensamblador para combinar, reorganizar, aumentar y obtener información acerca de documentos del PDF.
   * **Cloud Manager**

      _Fecha de la versión_

      La fecha de lanzamiento de Cloud Manager en Experience Manager as a Cloud Service 2022.01.0 es el 20 de enero de 2022.
La próxima versión está planificada para el 31 de marzo de 2022.

      _Nuevas funciones_

      * Cloud Manager [evita la reconstrucción de la base de código cuando detecta que se utiliza el mismo compromiso git](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/create-application-project/setting-up-project.html?lang=es#build-artifact-reuse) en varias ejecuciones de canalización de full-stack.
      * El acceso al registro de entorno de Experience Manager ahora requiere el perfil de producto **[!UICONTROL Administrador de implementación]**. Los usuarios sin este perfil ven un botón deshabilitado en la interfaz de usuario.
      * La interfaz de usuario no permite la configuración de canalización de front-end para un programa en el que Sites no esté habilitado como solución.
      * Al generar una contraseña de git, se muestra la fecha de caducidad.








### Comunidad

* **Seminario web del Experience Manager GEMS: _creación de sitios más rápida con Experience Manager sin encabezado y App Builder_**

   * ¿Se perdió el discurso de apertura de Adobe Summit 2022? Vea [Hacer personal la economía digital](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2022-opening-keynote-make-the-digital-economy/td-p/444612).
   * Adobe Summit 2022 | [Lista completa de sesiones de Experience Manager](https://adobe.ly/3rti6gF).
   * GEMs de Experience Manager | Seminario web | Miércoles, 23 de marzo de 2022
      * Tema: *Creación de sitios más rápida con Experience Manager sin encabezado y App Builder*
      * [Regístrese aquí](https://adobe.ly/3oCkEsh)
      * [Para preguntas y respuestas](https://adobe.ly/3LkSWdm)

### Nuevos cursos y tutoriales para Experience Manager {#tutorials-aem}

Nuevos vídeos, tutoriales y cursos publicados durante el mes pasado.

| Publicadas | Nombre | Tipo | Descripción | Aplicaciones |
| -----------| ---------- | ---------- | ---------- | ------|
| Marzo de 2022 | [Empiece a desarrollar con AEM sin encabezado](https://experienceleague.adobe.com/landing/experience-manager/headless/developer.html?lang=es) | Curso | Cree una página de aterrizaje de AEM sin encabezado que reúna todo el contenido de AEM sin encabezado en ExL. | AEM sin encabezado |
| Marzo de 2022 | [Creación de su primer sitio web en Adobe Experience Manager as a Cloud Service](https://experienceleague.adobe.com/?lang=es#dashboard/learning) | Curso | Genere rápidamente un nuevo sitio web en Experience Manager mediante una plantilla de sitio predefinida. | AEM Sites |
| Marzo de 2022 | [Extracción del nodo del XML de datos enviado](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/custom-workflow-steps/extract-xml-node.html?lang=es) | Vídeo | Aprenda este paso de proceso personalizado para crear un documento XML al extraer el nodo de otro documento XML. Utilice este proceso cuando desee combinar los datos enviados con la plantilla XDP para generar un PDF. | AEM Forms |
| Marzo de 2022 | [Escritura del documento en el sistema de archivos](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/custom-workflow-steps/write-payload-document.html?lang=es) | Vídeo | Obtenga información sobre cómo escribir los documentos generados en el flujo de trabajo en el sistema de archivos. | AEM Forms |
| Marzo de 2022 | [Funciones personalizadas](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/adaptive-forms/custom-functions-aem-forms.html?lang=es) | Vídeo | AEM Forms 6.5 ha introducido la capacidad de definir las funciones de JavaScript que se pueden utilizar para estipular reglas comerciales complejas mediante el editor de reglas. | AEM Forms |
| Marzo de 2022 | [Serie de expertos sobre el conector mejorado de Workfront para Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/overview.html?lang=es) | Vídeo | Únase a los expertos de Workfront y Experience Manager Assets de Adobe en esta serie de vídeos de cuatro partes, mientras muestran y analizan los detalles del conector mejorado de Workfront para Experience Manager. | AEM Assets, Workfront |
| Marzo de 2022 | [Listas desplegables en cascada](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/some-useful-integrations/geonames-org.html?lang=es) | Vídeo | Un tutorial con recursos de muestra para crear un formulario con una lista desplegable en cascada. | AEM Forms |
| Marzo de 2022 | [Configuración inicial](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/setup.html?lang=es) | Vídeo | Obtenga información sobre cómo establecer y configurar el conector mejorado de Workfront para Experience Manager, que permite desbloquear la potencia combinada de AEM Assets y Workfront. | AEM Assets, Workfront |
| Marzo de 2022 | [Asignación de metadatos y formularios personalizados de Workfront](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/custom-forms.html?lang=es) | Vídeo | Obtenga información sobre cómo configurar Workfront y AEM Assets para administrar y sincronizar metadatos de recursos mediante formularios personalizados de Workfront y esquemas de metadatos de AEM. | AEM Assets, Workfront |
| Marzo de 2022 | [Etiquetas de AEM, carpetas vinculadas a proyectos y metadatos de carpetas](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/aem-tags-project-linked-folders-and-folder-metadata.html?lang=es) | Vídeo | Obtenga información sobre cómo dirigir el uso de etiquetas de AEM en recursos a través de datos de Workfront, configurar y utilizar carpetas vinculadas a proyectos y datos de Workfront para esquemas de metadatos de carpetas de recursos de AEM. | AEM Assets, Workfront |
| Marzo de 2022 | [Configuración y flujos de trabajo avanzados](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/advanced-settings-and-workflows.html?lang=es) | Vídeo | Obtenga información acerca de la configuración avanzada de Workfront para el conector mejorado de AEM y cómo configurar los flujos de trabajo avanzados y los iniciadores en AEM para administrar la sincronización de datos entre AEM y Workfront. | AEM Assets, Workfront |
| Marzo de 2022 | [Creación y configuración de una cuenta de Dynamics](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/formscs-dynamics-crm/create-dynamics-account.html?lang=es) | Vídeo | Conozca los pasos para registrar Microsoft® Dynamics con Azure Active Directory. | AEM CS |
| Marzo de 2022 | [Uso compartido de vínculos públicos](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/basics/link-sharing.html?lang=es) | Vídeo | Descubra cómo el vínculo de uso compartido de Assets Essentials permite a los usuarios compartir recursos con partes interesadas internas y externas, al mismo tiempo que minimiza el riesgo de enviar recursos o información incorrectos. | AEM Assets |

{style=&quot;table-layout:auto&quot;}

### Información de la versión de Experience Manager

Todas las notas de la versión de Experience Manager se mantienen en las páginas siguientes:

* [Información sobre la versión de Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=es)
* [Notas de la versión de Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=es)
* [Notas de la versión del servicio de conversión automatizada de formularios](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=es)
* [Notas de la versión de Experience Manager 6.5 Service Pack](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=en)
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

Más información acerca de la [Documentación de XML para AEM](https://www.adobe.com/es/products/xml-documentation-for-experience-manager/features.html).

### Nuevos tutoriales para [!DNL XML Documentation for Adobe Experience Manager] {#tutorials-xml-doc}

Nuevos vídeos, tutoriales o cursos publicados para [!DNL XML Documentation for Adobe Experience Manager].

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Marzo de 2022 | [Generación de resultados con documentación de XML](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2022.2.xmldocs&amp;lang=es) | Curso | Obtenga información sobre cómo generar resultados mediante [!DNL XML Documentation for Adobe Experience Manager]. Obtenga información acerca de las distintas funciones disponibles para la generación de resultados, incluidos informes, líneas de base, condiciones, resolución de problemas, publicación por lotes y activación. |

{style=&quot;table-layout:auto&quot;}

### Recursos adicionales

* [Documentación XML para Adobe Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=es): tutoriales sobre Experience League
* [Documentación XML para obtener información y asistencia de Adobe Experience Manager](https://helpx.adobe.com/es/support/xml-documentation-for-experience-manager.html): documentación del producto

## ![Icono](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Consulte los siguientes vínculos para ver las notas de la versión de Adobe Commerce:

* [Adobe Commerce y Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite para Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### Nuevos recursos de Adobe Commerce {#new-commerce}

Nueva documentación y tutoriales para Adobe Commerce en Experience League.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Marzo de 2022 | [Guía de servicios de pago](https://experienceleague.adobe.com/docs/commerce-merchant-services/payment-services/guide-overview.html?lang=es) | Guía | Una guía dirigida a los administradores de Adobe Commerce y Magento Open Source. Incluye información detallada acerca de la instalación e incorporación de los servicios de pago, así como la configuración y administración de los servicios. Supone una comprensión básica de la configuración y funcionalidad principales de Commerce. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/target.png) [!DNL Adobe Target] {#target}

Última actualización: **21 de marzo de 2022**

* Para obtener información previa al lanzamiento, consulte [Versión preliminar de Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=es)
* Para obtener información actual, consulte [Notas de la versión de Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=es)

## ![Icono](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign permite entregar, de forma intuitiva y automatizada, mensajes privados a través de canales de marketing en línea y sin conexión. Ahora puede anticipar los deseos de los clientes mediante experiencias basadas en sus hábitos y preferencias.

### Últimas versiones de productos de Campaign

Conozca las últimas funciones, mejoras y correcciones publicadas:

* [Campaign Classic versión 7.2.2](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=es)

### Nuevos tutoriales y cursos de [!DNL Campaign] {#tutorials-campaign}

Nuevos tutoriales y cursos publicados para Adobe Campaign.

| Publicadas | Nombre | Tipo | Descripción | Aplicaciones |
| ------| ----- | -----| ------ | --- |
| Marzo de 2022 | [Integración con Experience Manager: información general](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/overview.html?lang=en) | Vídeo | Conecte Adobe Campaign con Adobe Experience Manager para poder administrar las plantillas de entrega de correo electrónico, los recursos y los formularios en Experience Manager. | AEM, Campaign versión 8 |
| Marzo de 2022 | [Configuración de Campaign para la integración de Experience Manager](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/configure-campaign-for-aem-integration.html?lang=es) | Vídeo | Aprenda a configurar la integración entre Experience Manager y Campaign, incluida la configuración importante que se debe buscar y los posibles problemas que se deben evitar. | AEM, Campaign versión 8 |
| Marzo de 2022 | [Aprobación y publicación de una página de Experience Manager en Campaign](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/create-a-campaign-delivery-with-content-from-experience-manager/approve-and-publish-aem-content-to-campaign.html?lang=es) | Vídeo | Aprenda a crear una newsletter en Experience Manager y a aprobarla y publicarla en Campaign. | AEM, Campaign versión 8 |
| Marzo de 2022 | [Sincronización y envío de una entrega de correo electrónico de Experience Manager en Campaign](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/create-a-campaign-delivery-with-content-from-experience-manager/synchronize-and-send-an-aem-delivery-in-campaign.html?lang=es) | Vídeo | Obtenga información sobre cómo probar y enviar un correo electrónico desde Adobe Campaign mediante una newsletter creada en Experience Manager. | AEM, Campaign versión 8 |
| Marzo de 2022 | [Integración con Adobe Target](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/connect/target-integration.html?lang=es) | Vídeo | Aprenda a personalizar una entrega con contenido dinámico servido desde Adobe Target. | Adobe Target, Campaign v8 |

{style=&quot;table-layout:auto&quot;}

### Recursos de ayuda de Campaign

* Adobe Campaign v8: [Documentación](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=es) - [Guías de implementación](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=es)
* Adobe Campaign Standard: [Documentación de Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=es) - [Vídeos de procedimientos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=es) - [Planificación de versiones](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=es) - [Últimas actualizaciones de la documentación](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=es)
* Adobe Campaign Classic: [Documentación de Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Vídeos de procedimientos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=es) - [Actualizaciones más recientes de la documentación](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=es)
* Panel de control de Adobe Campaign: [Documentación](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=es) - Vídeos prácticos para [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=es) y [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=es)

## ![Icono](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Con Journey Optimizer, puede administrar campañas omnicanal programadas y momentos uno a uno para millones de clientes desde una sola aplicación, y todo el recorrido se optimiza con decisiones y perspectivas inteligentes.

### Últimas versiones de productos de Journey Optimizer

Descubra las funcionalidades, mejoras y correcciones más recientes en las [Notas de la versión de Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=es).

### Tutoriales y cursos de Journey Optimizer {#tutorials-ajo}

Últimos tutoriales de Journey Optimizer:

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Marzo de 2022 | [Uso y administración de expresiones guardadas en la biblioteca de personalización](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/personalize-content/use-and-manage-saved-expressions-in-personalization-library.html?lang=es) | Vídeo | Obtenga información sobre cómo utilizar elementos de la biblioteca de personalización guardados en un mensaje y cómo crear y administrar los elementos de esta biblioteca. |

### Más recursos para [!DNL Journey Optimizer]

* [Documentación de Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=es)
* [Documentación de gestión de decisiones](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=es) - [Últimas actualizaciones de la documentación](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=es)

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

### Nuevos tutoriales y cursos de Marketo {#tutorials-marketo}

Nuevos tutoriales y cursos publicados para Adobe Marketo.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Marzo de 2022 | [Creación y administración de cuadros de diálogo personalizados](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/dialogue-management.html?lang=es) | Vídeo | Obtenga información sobre cómo crear y administrar un _[!UICONTROL Diálogo]_. El diseño de conversaciones dirigidas y personalizadas es la clave para crear una buena experiencia de conversación para cada visitante web. |
| Marzo de 2022 | [Configuración e instalación de un bot de chat](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/setup.html?lang=es) | Vídeo | Una guía para ayudarle a instalar un bot de chat de JavaScript en su sitio web o página de aterrizaje, así como personalizar su aspecto para que coincida con su marca. |
| Marzo de 2022 | [Posibilidad de reservar reuniones con su equipo de ventas](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/meeting-booking.html?lang=es) | Vídeo | Use [!UICONTROL Dynamic Chat] para acelerar la conexión con las ventas para los posibles clientes de la cuenta de destino. |
| Marzo de 2022 | [Activación de la integración de Marketo con [!UICONTROL Dynamic Chat]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/marketo-integration.html?lang=es) | Vídeo | [!UICONTROL Dynamic Chat] está integrado de forma nativa en Marketo Engage, lo que le permite utilizar el contexto de las conversaciones con el bot de chat para redireccionar o puntuar a sus posibles clientes. |
| Marzo de 2022 | [Administración de usuarios de [!UICONTROL Dynamic Chat]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/user-management.html?lang=es) | Vídeo | Administre a sus usuarios de [!UICONTROL Dynamic Chat] a través de Adobe Admin Console. |
| Marzo de 2022 | [Recorrido del producto [!UICONTROL Dynamic Chat]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/product-tour.html?lang=es) | Vídeo | [!UICONTROL Dynamic Chat] es una nueva solución de bots de chat creada para marketing y ventas. Está integrado de forma nativa con Marketo Engage, lo que le permite utilizar Dynamic Chat como un nuevo canal en su marketing multicanal. Es fácil de usar y configurar. |

## ![Icono](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] es una aplicación de administración de trabajo unificada para compartir ideas, crear contenido, administrar procesos complejos y trabajar de forma óptima.

Consulte la página [[!DNL Workfront] Versiones](https://one.workfront.com/s/product-releases) de para obtener un resumen de la información más reciente de todos los productos.

## ![Icono](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

Notas de la versión para [!DNL Adobe Advertising Cloud].

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
<!-- * [New features in [!DNL Advertising Cloud DSP]](#adcloud-dsp) -->
* [Nuevas funciones en  [!DNL Advertising Cloud Search]](#adcloud-search)
* [Nuevos tutoriales de  [!DNL Advertising Cloud] ](#tutorials-ad-cloud)

<!-- 
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

{style="table-layout:auto"}
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

<!--
{style="table-layout:auto"}
-->

### Nuevas funciones de [!DNL Advertising Cloud Search] {#adcloud-search}

Última actualización: **7 de abril de 2022**

| Función | Descripción |
| ------- | ----------- |
| [!UICONTROL Campañas]<br><br>[!UICONTROL Información sobre los anuncios] | (7 de abril) [!DNL Google Ads] cuentas) Advertising Cloud Search está realizando la transición de todas las llamadas API del heredado [!DNL Google AdWords API] a la última [!DNL Google Ads API]. Migración al nuevo [!DNL Google Ads API] garantizará la continuidad con las capacidades existentes y permitirá el acceso a [!DNL Google’s] última versión [!DNL Ads] características.<br><br>Algunas funciones aún no se han actualizado a la nueva API y no están disponibles temporalmente:<ul><li>Extensiones de ubicación:<ul>Las extensiones de ubicación no están visibles en la variable [!UICONTROL Extensiones] vista.</li><li>No se puede crear una extensión.</li><li>Los filtros en las ubicaciones no funcionan.</li></li></ul><li>[!UICONTROL Información sobre los anuncios]: La variable [!UICONTROL Porcentaje de impresiones perdidas] y [!UICONTROL Consulta beta de coincidencia cruzada] los análisis no estarán disponibles a partir del 11 de abril.</li></ul>Prevemos la restauración de las capacidades de extensión de ubicación para finales de abril. Una vez que determinemos cuándo se verá afectado [!UICONTROL Información sobre los anuncios] también se pueden restaurar los módulos, se enviará una actualización con la fecha estimada. |
| [!UICONTROL Portafolios] | (Versión del 12 de marzo) De forma predeterminada, la optimización híbrida está disponible en el nivel de campaña. Ahora, de forma opcional, puede habilitar la optimización híbrida en el nivel de grupo de anuncios, para el cual la capacidad de optimización establece los objetivos de CPA o ROAS [!DNL Google] en el nivel de grupo de anuncios para un control más preciso del rendimiento.<br>Con cualquier portafolios, debe dejar un período de aprendizaje antes de lanzarlo, para garantizar que tenga suficiente cobertura de modelo. Del mismo modo, si cambia un portafolio híbrido de optimización de nivel de campaña al nivel de grupo de anuncios, establezca el portafolios en el estado activo durante unas dos semanas. Esto garantiza que la capacidad de optimización tenga tiempo para conocer los grupos de anuncios incluidos y generar objetivos.<br>Para admitir la optimización en el nivel de grupo de anuncios, las simulaciones personalizadas ahora pueden incluir resultados por grupo de anuncios. Ejecute una simulación personalizada con resultados de nivel de grupo de anuncios antes de iniciar un portafolios híbrido con optimización de nivel de grupo de anuncios. |
| [!UICONTROL Portafolios] <br> [!UICONTROL Campañas] | (Coincide con la versión 12; Función beta para [!DNL Microsoft® Advertising] campañas): Ahora puede configurar campañas de búsqueda para que utilicen la variable [!UICONTROL Maximizar conversiones] estrategia de oferta y, opcionalmente, establezca un coste máximo por clic.<br>Si ya participa en la optimización beta híbrida para otras estrategias de oferta automática, tendrá acceso directo a la estrategia [!UICONTROL Maximizar conversiones] y puede incluir campañas con la estrategia [!UICONTROL Maximizar conversiones] en portafolios híbridos. Para utilizar esta estrategia en un portafolios híbrido, debe habilitar la carga de los objetivos de Advertising Cloud Search en [!DNL Microsoft® Ads]. Si aún no participa en la versión beta y desea unirse, póngase en contacto con su administrador de cuentas de [!DNL Adobe]. |
| [!UICONTROL Audiencias]<br><br> de Campaign y [!UICONTROL Hojas de edición por lotes] de Campaign | (Versión del 12 de marzo); [!DNL Microsoft® Advertising] campañas): ahora puede usar cualquiera de sus [!DNL Microsoft® Advertising] audiencias, excepto para audiencias de mercado como objetivos de nivel de campaña o [!UICONTROL adgroup]objetivos de nivel superior. Anteriormente, solo podía utilizarlas como objetivos de nivel de [!UICONTROL grupo de anuncios]. |
| [!UICONTROL Audiencias] de Campaign | (Versión del 12 de marzo); Función beta para [!DNL Microsoft® Advertising] cuentas elegibles para [!UICONTROL Coincidencia de cliente]) Ahora puede crear y administrar audiencias de coincidencia de clientes cargando archivos CSV con direcciones de correo electrónico. Los datos deben tener un cifrado hash con el algoritmo SHA-256. |

{style=&quot;table-layout:auto&quot;}

### Nuevos tutoriales de Advertising Cloud {#tutorials-ad-cloud}

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Marzo de 2022 | [Creación de una ubicación de visualización estándar](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/dsp/placement-create.html?lang=es) | Vídeo | Aprenda a crear una ubicación de visualización estándar para una campaña de Advertising Cloud DSP. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Nuevos tutoriales y cursos publicados para Adobe Document Cloud.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Marzo de 2022 | [Herramientas y comandos personalizados](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/custom.html?lang=es) | Vídeo | Aprenda a mejorar la productividad del flujo de trabajo del documento mediante el uso de comandos y herramientas personalizados. A continuación, comparta sus nuevos comandos y herramientas con sus compañeros para mejorar la eficiencia organizativa. |
| Marzo de 2022 | [Adición de marcadores e hipervínculos](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/bookmarks.html?lang=es) | Vídeo | Aprenda a añadir marcadores e hipervínculos para mejorar la navegación y la interacción con los archivos PDF. |
| Marzo de 2022 | [Optimización de documentos escaneados](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/optimizescan.html?lang=es) | Vídeo | Tanto si el documento proviene de una cámara o un escáner, aprenderá a mejorar el resultado en Acrobat para obtener una mejor experiencia de visualización y búsqueda en PDF. |
| Marzo de 2022 | [Conversión de Word a PDF, incluidos los campos de formulario](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/wordform.html?lang=es) | Vídeo | En este tutorial de vídeo de 60 segundos, aprenderá a convertir archivos y formularios de Word a PDF y a generar automáticamente campos de formulario. |
| Marzo de 2022 | [Campos de formulario avanzados](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/advancedforms.html?lang=es) | Vídeo | En este tutorial práctico, aprenderá a configurar cálculos, crear un botón de envío por correo electrónico y actualizar rápidamente las páginas del formulario sin volver a crear todos los campos de formulario existentes. |
| Marzo de 2022 | [Creación de archivos PDF más eficientes en un abrir y cerrar de ojos](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/optimize.html?lang=es) | Vídeo | En este tutorial de vídeo de 60 segundos, aprenderá a utilizar la herramienta Optimizar PDF para reducir significativamente el tamaño de los archivos PDF. |
| Marzo de 2022 | [Reconocimiento de texto en un archivo PDF digitalizado](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/textrecognition.html?lang=es) | Vídeo | En este tutorial de vídeo de 60 segundos, aprenda a convertir un PDF digitalizado para que pueda buscar texto en él. |
| Marzo de 2022 | [Permita que Acrobat le ayude a hacer PDF accesibles](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/accessible.html?lang=es) | Vídeo | En este tutorial de vídeo de 60 segundos, aprenderá a comprobar si un PDF es accesible. |
| Marzo de 2022 | [Exportación de PDF a Word desde el teléfono](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/exportwordphone.html?lang=es) | Vídeo | En este tutorial de vídeo de 60 segundos, aprenderá a convertir un archivo PDF en un documento de Microsoft® Word totalmente editable con la aplicación móvil de Acrobat. |
| Marzo de 2022 | [Protección de los archivos PDF con una contraseña](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/protect.html?lang=es) | Vídeo | En este tutorial de vídeo de 60 segundos, aprenderá a proteger un PDF para que se pida una contraseña antes de abrirlo o editarlo. |

{style=&quot;table-layout:auto&quot;}

Para obtener ayuda de Document Cloud, consulte:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=es)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=es)
* [Información y asistencia técnica de Document Cloud](https://helpx.adobe.com/es/support/document-cloud.html)

## ![Icono](/assets/creative-cloud-24.png) Adobe Creative Cloud para empresas {#creative-cloud}

Consulte [Tutoriales de Creative Cloud para empresas](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=es) para obtener los más recientes.

## ![Icono](/assets/experience-league.png) Administración de datos del cliente: voces {#voices}

[Voces de administración de datos del cliente](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=en) es su destino como encargado y especialista en prácticas de marketing y técnicas de gestión de datos de clientes. Esta colección de tutoriales es su punto de encuentro para escuchar a sus compañeros, inspirarse y aprender acerca de los desarrollos en MarTech. No se requiere registro, simplemente haga clic y mírelo.

## ![Icono](/assets/experience-league.png) Modelos de experiencia digital {#blueprints}

[Los modelos de experiencia digital](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=es) son implementaciones repetibles para abordar la estrategia y resolver los problemas empresariales establecidos. Cada modelo proporciona una serie de artefactos que explican el principal problema empresarial, las arquitecturas, los pasos de implementación, las consideraciones técnicas y los vínculos a la documentación pertinente.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Febrero de 2022 | [Recorridos del cliente](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/overview.html?lang=es) | Vídeo | Los Recorridos del cliente permiten a las marcas interactuar de forma proactiva con sus clientes y comunicarse con ellos a través de canales como correo electrónico, SMS y alertas móviles. |
| Febrero de 2022 | [Modelo de Campaign v7](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/campaign-v7/campaign-v7.html?lang=es) | Vídeo | Adobe Campaign v7 es una herramienta de campaña diseñada para canales de marketing tradicionales, como correo electrónico y correo directo. Proporciona sólidas capacidades de ETL y administración de datos para ayudar a diseñar y depurar la campaña perfecta. |

{style=&quot;table-layout:auto&quot;}
