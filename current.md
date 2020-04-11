---
title: Notas de la versión de Adobe Experience Cloud
description: Plantilla para notas de la versión de Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 3e124e820e573047298f878cf8cb2bf2a6b7f7dd

---


# Acceso anticipado - Notas de la versión de Adobe Experience Cloud - Abril de 2020

![Banner](/assets/experience-cloud-banner-3.png)

Nuevas funciones y correcciones en [!DNL Adobe Experience Cloud].

>[!IMPORTANT]
>
>Esta página incluye contenido previo al lanzamiento de la nueva versión y está sujeto a cambios antes de su publicación planificada.

>[!NOTE]
>
>Para recibir notificaciones por correo electrónico sobre próximas versiones, suscríbase a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html). La nueva información publicada tras el lanzamiento se marcará con la fecha de publicación.

**Fecha de publicación: 2020 de abril de**

(Las fechas de lanzamiento específicas de la solución pueden variar).

* [Estado del sistema de Adobe](#status)
* [Servicios principales e interfaz de Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/es-ES/target/using/release-notes/target-release-notes.html) (vínculos a la página de ayuda de la solución)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/es/primetime/user-guide.html) (vínculos a la página de ayuda de la solución)

¿Busca ayuda en casa? Consulte la documentación de [Adobe Experience Cloud](https://docs.adobe.com/content/help/es-ES/experience-cloud/user-guides/home.html).

## ![Icono](/assets/adobe.png) Estado del sistema de Adobe {#status}

[!UICONTROL El estado del sistema de Adobe] proporciona información detallada, actualizaciones de estado y notificaciones por correo electrónico sobre los productos en la nube de Adobe y las interrupciones y sesiones de mantenimiento de los servicios de Adobe. Puede comprobar el estado en [status.adobe.com](https://status.adobe.com/).

**Novedades**

* Con su Adobe ID, puede suscribirse a las notificaciones de eventos con una mayor granularidad, lo que permite llegar hasta la oferta de productos y el nivel de complementos. Además, en nuestra última versión, el proceso de suscripción automática ahora recomienda una selección de productos y servicios en función de los derechos de sus productos. Esto debería agilizar el proceso de suscripción al reducir el número de decisiones o clics necesarios para crear sus suscripciones y, lo que es más importante, enviar notificaciones más relevantes en la bandeja de entrada. Empiece por [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuevas funciones y mejoras disponibles**

| Función | Descripción |
| -----------| ---------- |
| suscripciones personalizadas basadas en derechos | <ul><li>Recomendaciones de suscripción preseleccionadas basadas en las autorizaciones DX del usuario.</li><li>Las suscripciones recomendadas se resaltan en la parte superior de la lista del producto para una visualización rápida.</li><li>Las notificaciones por correo electrónico recibidas son relevantes para las autorizaciones de productos del usuario.</li></ul> |
| Administración más sencilla de Suscripciones | <ul><li>**[!UICONTROL Administrar Suscripciones]** tiene una nueva experiencia de usuario para administrar suscripciones de productos y eventos.</li><li>Nueva opción para vista y edición de suscripciones de productos y eventos por separado.</li><li>La opción **[!UICONTROL Eliminar]** le permite cancelar la suscripción de una suscripción de producto o evento.</li><li>La opción **[!UICONTROL Cancelar suscripción todo]** con un solo clic está disponible para las suscripciones de productos.</li><li>La compatibilidad con UX está disponible para las superficies web, móviles y tabletas y la localización en 19 idiomas.</li></ul> |

## ![Icono](/assets/ec_appicon_24.png) Servicios principales e interfaz de Experience Cloud {#ecloud}

Nuevas funciones y correcciones en la interfaz de Experience Cloud, incluida la administración y los servicios principales (atributos del cliente, audiencias, desencadenadores, cookies, etc.):

* La página [!UICONTROL Fuente] de Experience Cloud estaba en desuso. (EXC-8505)
* La página de inicio de sesión de Experience Cloud se ha actualizado para reflejar nuevos elementos de marca. (EXC-10747)

Para obtener documentación del producto, consulte la página de ayuda de [Experience Cloud](https://docs.adobe.com/content/help/es-ES/core-services/interface/experience-cloud.html).

## ![Icono](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Notas de la versión de [!UICONTROL Experience Platform], [!UICONTROL Experience Platform Launch], [!UICONTROL Identity Service], Journey Orchestration, Mobile Services y boletines de seguridad.

### Organización de recorridos {#journey}

Con Adobe Experience Platform, puede organizar los recorridos individuales de los clientes a escala en distintos canales de experiencia y adaptarse de forma inteligente a las necesidades y recorrido de cada usuario en tiempo real.

* [Documentación](https://docs.adobe.com/content/help/es-ES/journeys/using/journey-orchestration-home.html)
* [Notas de la versión](https://docs.adobe.com/content/help/es-ES/journeys/using/release-notes/release-notes.html)
* [Vídeotutoriales](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services y Mobile SDK {#mobile}

Android 4.18.2 (3 de abril de 2020):

* Mensajería en la aplicación: Por motivos de seguridad, [!UICONTROL WebViews] creada por el SDK ahora establece la propiedad `setAllowFileAccess` igual a _false_.

iOS 4.19.2 (24 de marzo de 2020):

* General: Se corrigieron algunas filtraciones en el [!DNL Target] código.

Unidad 4.19.0 (10 de marzo de 2020):

* Se ha actualizado [!UICONTROL Unity Plugin] para que utilice las versiones 4.19.0 de iOS y 4.18.0 o [!DNL Android].
* Se ha expuesto un nuevo método de adquisición para [!DNL Android] permitir el procesamiento de una URL proporcionada por las API de [!DNL Google Play] Remitente del reenvío.

### Información adicional de la versión de la plataforma de experiencia

* [Notas](https://docs.adobe.com/content/help/es-ES/launch/using/intro/release-notes/current.html)de la versión del Experience Platform Launch.
* [Notas de la versión de la plataforma de experiencia](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Boletines de seguridad y avisos](https://helpx.adobe.com/es/security.html)     (Todos los productos de Adobe)

## ![Icono](/assets/analytics.png) [!DNL Analytics] {#analytics}

Fecha de publicación: **16 de abril de 2020**

* [Nuevas funciones, mejoras y correcciones en Adobe Analytics](#aa-features)
* [Avisos importantes para los administradores de Analytics](#aa-notices)  (Actualizado el 7 de abril de 2020)
* [AppMeasurement](#appm)
* [Nuevos tutoriales de Analytics](#tutorials-analytics)

### Nuevas funciones, mejoras y correcciones en Adobe Analytics {#aa-features}

| Función | Descripción |
| -----------| ---------- |
| [!UICONTROL Análisis]del viaje del cliente: Rellenado [!UICONTROL automatizado de datos] | Esta nueva opción le permite importar todos los datos históricos de una conexión en [!UICONTROL Customer Journey Analytics]. (Documentación a seguir) |
| Compatibilidad de Analytics con [!UICONTROL Experience Edge] | Ahora puede reenviar datos que se han enviado a [!UICONTROL Experience Edge] a Analytics. |
| [!UICONTROL Espacio de trabajo]: Crear automáticamente tablas improvisadas a partir de un estado en blanco | Anteriormente, no se podían soltar componentes directamente en un proyecto en blanco o en un panel en blanco; primero tenía que agregar una tabla improvisada. Ahora puede soltar componentes directamente en un proyecto o panel en blanco, y automáticamente se creará una tabla improvisada en un formato recomendado. Además, se mejoró la forma en que se gestionan los tipos de componentes mixtos (p. ej., dimensiones y métricas) al soltarlos en una tabla improvisada en blanco juntos. |

#### Correcciones de Analytics

* Se ha corregido un problema que hacía que faltaran datos de segmentos de Analytics en el Administrador de Audiencias. (AN-206221)
* Se ha corregido un problema con el procesamiento de fuentes [!UICONTROL de] datos que mostraba fechas incorrectas. (AN-213604)
* Se ha corregido un problema con los archivos de clasificación que no se cargaban correctamente en FTP. (AN-214102)
* Se ha corregido un problema con el método API que `Segments.Get` no devolvía una respuesta completa. (AN-206210)
* Se corrigió un problema en el cual los elementos de línea de tabla se convertían en caracteres especiales en la descarga de [!DNL Workspace] PDF. (AN-196153)
* Se ha corregido un problema con la llamada a la API 1.4 de Adobe Analytics que `visattrcustomeridcustomerattributes` no funcionaba correctamente. (AN-186873)
* Se ha corregido un problema con los datos que aparecían en los informes pero no aparecían en la fuente [!UICONTROL de datos]. (AN-211923)
* Se ha corregido un problema que impedía copiar permisos de Perfil  de producto. (AN-211113)
* Se corrigió un problema en el cual los usuarios con Federated ID no podían iniciar sesión en el Creador de informes. (AN-207750)
* Se ha corregido un problema con los datos de [!UICONTROL AdWords] que no se mostraban en Análisis [!UICONTROL de publicidad]. (AN-213249)
* Se corrigió un problema en el cual los datos de clasificación no se mostraban en la vista de tendencias. (AN-212761)
* Se ha corregido un problema que provocaba un recuento incorrecto de segmentos publicados en el Administrador [!UICONTROL de segmentos]. (AN-213374)

#### Correcciones adicionales de Analytics

AN-212151; AN-214343; AN-215017; AN-115525; AN-123869; AN-101871; AN-152580; AN-160480; AN-199299; AN-209486; AN-212961; AN-211539; AN-213095; AN-212653; AN-211826; AN-206948; AN-208607; AN-204286; AN-214401; AN-212130; AN-211943; AN-212709; AN-212833; AN-211550; AN-212977; AN-213422; AN-213450; AN-214528; AN-213827; AN-214094; AN-214153; AN-214234; AN-214355; AN-214427; AN-214642; AN-214691; AN-214924; AN-215080; AN-215212

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación     o actualizada | Descripción |
| -----------| ---------- | ---------- |
| Cambio en la forma en que se calculan [!UICONTROL las entradas y salidas] en [!UICONTROL Workspace] | 7 de abril de 2020 | En [!UICONTROL Análisis Workspace], a partir de marzo de 2020, hemos cambiado la forma en que el valor _Ninguno_ interactúa con las [!UICONTROL entradas y salidas]. Dado que ahora puede activar y desactivar _Nones_ en el espacio de trabajo [!UICONTROL de]Análisis, se aplica el valor _Ninguno_ después de la entrada o salida, mientras que (para eVars) solía aplicarse antes. Por ejemplo: supongamos que la primera visita individual de una visita no tiene valor para las eVars, pero la segunda visita sí lo tiene. En [!UICONTROL Informes y análisis] se mostrará como _No especificado_ para la entrada, pero en el área de trabajo de [!UICONTROL Análisis] se mostrará como el valor de la segunda visita. |
| Fin de la vida útil de la configuración **[!UICONTROL Nivel de conversión]** | 3 de marzo de 2020 | The non-functioning [Conversion Level](https://docs.adobe.com/content/help/es-ES/analytics/admin/admin-tools/general-acct-settings-admin.html) setting in **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL General Account Settings]** will be removed from the interface on March 12, 2020. |
| Fin de la vida útil de la configuración **[!UICONTROL Archivo de tablero]** | 27 de marzo de 2020 | La configuración **[!UICONTROL Ver archivo]** en **[!UICONTROL Administrar tableros]** de [!UICONTROL Reports &amp; Analytics] dejará de estar disponible a partir de octubre de 2020. |
| Finalización de la compatibilidad con TLS 1.1 | 3 de octubre de 2019 | A partir del 31 de marzo de 2020, Adobe Analytics dejará de ofrecer soporte para TLS 1.1. Este cambio es parte de nuestro trabajo para mantener los estándares de seguridad más altos e impulsar la seguridad de los datos del cliente. |
| Nuevo dominio de Adobe Analytics | 18 de diciembre de 2019 | El 16 de enero de 2020, Adobe Analytics empezará a pasar a un nuevo dominio: `https://experience.adobe.com/analytics.`<br>**Nota:** Este cambio se aplica a todos los usuarios que acceden a Analytics con su Adobe ID o Enterprise ID.<ul><li>Este cambio de dominio puede provocar problemas con las cookies al cargar Analytics en Safari. Al anular la selección _Impedir el seguimiento entre sitios_ en las preferencias de privacidad de [!DNL Safari], se habilitarán las cookies entre dominios (y todas las experiencias entre sitios) y Analytics funcionará en este nuevo dominio de Adobe Experience Cloud. Puede utilizar otros navegadores sin problemas porque esto solo afecta a los usuarios de [!DNL Safari].</li><li>El cambio de dominio puede hacer que [!UICONTROL Activity Map] deje de funcionar para algunos clientes [en casos específicos](https://docs.adobe.com/content/help/es-ES/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fin de vida útil: API heredadas de Analytics | 9 de enero de 2020 | En noviembre de 2020, los siguientes servicios de API heredadas de Analytics llegarán a su fin de vida útil y se cerrarán. Las integraciones actuales creadas con estos servicios dejarán de funcionar. <ul><li>API de Analytics 1.3</li><li>API de Analytics SOAP 1.4</li><li>Autenticación OAuth heredada (OAuth y JWT)</li></ul>Hemos creado las [Preguntas frecuentes del fin de la vida útil de la API heredada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ayudarle a responder a sus preguntas y proporcionar instrucciones sobre cómo proceder. Las integraciones de API que emplean estos servicios pueden migrar a las [API de REST 1.4 de Analytics](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o a las [API de Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Las cuentas heredadas de OAuth pueden migrar a una cuenta de integración de Analytics [Adobe IO](https://console.adobe.io/home?mv=email), que puede utilizarse para acceder tanto a las API de Analytics 1.4 como a las API de Analytics 2.0. |
| Fin de la administración de datos en el centro de datos de San José para Londres y Singapur | Julio de 2020 | Para los clientes de Londres y Singapur, ya no se ofrecerá la administración de datos entre Londres o Singapur y el centro de datos de San José [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, utilice [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Singapur, utilice [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| EOL de Ad Hoc Analysis | 6 de agosto de 2018 | Adobe anunció su intención de finalizar el servicio de Ad Hoc Analysis. La fecha se hará pública una vez que esté disponible. Para obtener más información, consulte [Descubrir Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Consulte [Notas de la versión de AppMeasurement para JavaScript](https://docs.adobe.com/content/help/es-ES/analytics/implementation/appmeasurement-updates.html). La versión 2.20.0 se publicó el jueves, 5 de marzo de 2020.

### Nuevos tutoriales de Analytics {#tutorials-analytics}

| Contenido | Descripción |
| -----------| ---------- |
| [Adobe Labs (Previsualizaciones tecnológicas) con Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | Adobe Labs (Previsualizaciones tecnológicas) le permite interactuar con tecnologías emergentes, descubrir perspectivas valiosas e influir en el desarrollo y las prioridades futuras [!DNL Analytics] de las funciones. |
| [Publicación de Audiencia de Experience Cloud mejorada](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | Se han realizado mejoras en [!UICONTROL Experience Cloud Audiencia Publishing]. Ahora puede publicar audiencias (segmentos) y hacerlas disponibles seis veces más rápido. Esto reduce el tiempo de latencia actual de 48 horas a aproximadamente 8 horas, y posiblemente más rápido, según el tráfico y el tamaño del segmento. |
| [Varios grupos de informes en el área de Análisis](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | Se pueden analizar varios grupos de informes en un solo proyecto de [!UICONTROL Workspace] seleccionando grupos de informes en el nivel de panel. Esto le permite llevar a cabo una análisis de panel en paralelo en diferentes conjuntos de datos. |

Consulte la página de inicio [de la Ayuda de](https://docs.adobe.com/content/help/es-ES/analytics/landing/home.html) Adobe Analytics para obtener documentación del producto.

## ![Icono](/assets/audience-manager.png) Audience Manager {#aam}

Nuevas funciones y correcciones en Adobe Audience Manager:

* Se ha corregido un problema que provocaba que no funcionaran los botones Prueba [!UICONTROL de] Duplicado y Plantilla [!UICONTROL de asignación de] Duplicados en el Laboratorio [!UICONTROL de] Audiencias. (AAM-53388)
* Se ha corregido un problema que provocaba que las Audiencias [!UICONTROL de tasa de] coincidencia [!UICONTROL y de direcciones de] segmentos se mostraran como 0 cuando se configuraba un destino para exportar UUID. Las Audiencias [!UICONTROL Tasa de] coincidencia y Direccionamiento  de segmento ahora se muestran como 100%. (AAM-51615)
* Se ha corregido un problema que hacía que los nombres de características que contienen caracteres especiales se codificaran dos veces en HTML. (AAM-54001)
* Se ha corregido un problema que impedía a algunos usuarios cambiar a otras soluciones de Adobe Experience Cloud desde la interfaz de [!DNL Audience Manager] usuario. (AAM-52917)
* Se ha corregido un problema que impedía a algunos usuarios crear una fuente de datos SHA256 para destinos basados en personas. (AAM-53525)
* Varias mejoras de accesibilidad en la interfaz. (AAM-48986, AAM-49009, AAM-48984, AAM-48939, AAM-48940, AAM-48964, AAM-49032, AAM-49360)

## ![Icono](/assets/aem.png) Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Adobe Experience Manager (AEM). Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

### Autoayuda

* **AEM Newsletter**

   Consulte la newsletter [más reciente de](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html)Adobe Experience Manager.

* **AEM como servicio de nube: configuración del servicio de nube de Dynamic Media**

   Hay una nueva opción disponible al configurar el servicio de nube de Dynamic Media:

   **Publicación** selectiva: al seleccionar esta opción, significa que los recursos se publican automáticamente solo para previsualización segura y se pueden publicar explícitamente en AEM sin publicarlos en DMS7 para envío en el dominio público.

   Consulte [Configuración del servicio](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services)de Dynamic Media Cloud.

* **Medios dinámicos: Imágenes inteligentes**

   El tema completo de la Ayuda de Imágenes inteligentes se ha actualizado con nueva información, incluidos ejemplos de recursos de imagen que ilustran la optimización de imágenes inteligentes añadida.

   Consulte Imágenes [inteligentes](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/imaging-faq.html).

* **Configuración de Dynamic Media: modo Scene7**

   Ahora hay una nueva opción Sincronizar todo el contenido disponible en la página Configuración de Dynamic Media que se encuentra en **[!UICONTROL Herramientas > Servicios]** de nube.

   Consulte [Creación de una configuración](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services)de Dynamic Media.

* **AEM Assets Brand Portal es compatible con AEM Assets como servicio de nube**

   Ahora puede publicar recursos de AEM Assets como un servicio de nube en AEM Assets Brand Portal.

   Consulte [Configuración de AEM Assets con Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) y [Publicación de recursos en Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html).

* **Adobe Asset Link 2.0 publicado**

   Adobe Asset Link 2.0 es compatible con el trabajo con varios entornos de AEM y con AEM como servicio de nube. AEM admite la necesidad de los especialistas en marketing de configurar la ejecución automática del flujo de trabajo de procesamiento de recursos cuando los recursos se cargan en una carpeta mediante Adobe Asset Link.

   See [Adobe Asset Link](https://helpx.adobe.com/es/enterprise/using/adobe-asset-link.html).

### Nuevos tutoriales de Experience Manager

| Contenido | Descripción |
| -----------| ---------- |  
| [Configuración de las herramientas de despachante locales](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | Obtenga información sobre cómo facilitar la configuración, validación y simulación de [!UICONTROL Dispatcher] localmente. |
| [Configuración de herramientas de desarrollo para proyectos de AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | El desarrollo de Adobe Experience Manager (AEM) requiere que se instale y configure un conjunto mínimo de herramientas de desarrollo en el equipo de desarrollo. Estas herramientas admiten el desarrollo y la creación de proyectos AEM. |
| [Configuración de AEM Runtime local](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) se puede ejecutar localmente mediante AEM como Jar [!UICONTROL de]inicio rápido del SDK de Cloud Service. Esto permite a los desarrolladores implementar y probar el código, la configuración y el contenido personalizados antes de comprometerlo con el control de código fuente, e implementarlo en AEM como un entorno de servicio de nube. |
| [Navegación](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | Explore los conceptos básicos para la navegación con Recursos AEM. |
| [Versiones](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | Explore cómo AEM crea y mantiene versiones de recursos. |
| [Integración de AEM - [!DNL Magento] mediante el marco de integración de [!UICONTROL comercio]](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | Este vídeo lo acompaña durante la configuración de la integración entre AEM y [!DNL Magento]. |
| [Introducción a la pila de arquitectura de AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | El arquetipo de proyecto CIF crea un proyecto CIF de Adobe Experience Manager (AEM) mínimo como punto de partida para los proyectos de los clientes que utilizan componentes principales de CIF. |
| [Introducción a OSGi](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | Introducción a OSGi, una arquitectura modular dinámica para aplicaciones Java que constituye la base de Adobe Experience Manager. |
| [Introducción al repositorio de contenido Java (JCR)](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | Introducción al [repositorio de contenido Java (JCR) utilizado por Adobe Experience Manager. |
| [Introducción a Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | Introducción a [!DNL Sling], un marco web de código abierto RESTful que forma parte de la pila de tecnología subyacente de Adobe Experience Manager. |
| [Introducción al nivel de creación y publicación](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | Introducción a los niveles [!UICONTROL Autor] y [!UICONTROL Publicación] como parte de la arquitectura en Adobe Experience Manager. |
| [Introducción a Dispatcher](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | Introducción a las funciones y características del despachante como parte de la arquitectura de AEM. |
| [Introducción al desarrollo de componentes](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | Información general sobre el desarrollo de componentes con sitios de Adobe Experience Manager. Incluye una introducción a [!UICONTROL los cuadros de diálogo], los modelos [!UICONTROL Sling], los scripts HTL y las bibliotecas [!UICONTROL del]cliente. |
| [Arquetipo de AEM Project](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | El proyecto de AEM contiene todo el código y las configuraciones de una implementación. The AEM [!UICONTROL Project Archetype] creates a minimal, best-practices-based Adobe Experience Manager project as a starting point for your own AEM projects. |
| [Explicación de los componentes principales](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | Los componentes  principales de AEM son un conjunto de componentes estándar que se utilizan con Adobe Experience Manager. |
| [Uso de la barra de inicio rápido de AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | Obtenga información sobre cómo instalar y ejecutar una instancia local de Adobe Experience Manager en solo unos minutos con el tarro de inicio rápido de [!UICONTROL AEM]. |

### Recursos de ayuda adicionales

* [AEM como un servicio en la nube](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/landing/home.html)
* [Página de inicio de Learn &amp; Support de AEM 6.5](https://helpx.adobe.com/es/support/experience-manager/6-5.html)
* [Página de inicio de Learn &amp; Support de AEM 6.4](https://helpx.adobe.com/es/support/experience-manager/6-4.html)
* [Página de inicio de Learn &amp; Support de AEM 6.3](https://helpx.adobe.com/es/support/experience-manager/6-3.html)
* [Página de inicio de Learn &amp; Support de AEM 6.2](https://helpx.adobe.com/es/support/experience-manager/6-2.html)
* [Guía del usuario de Cloud Manager](https://helpx.adobe.com/es/experience-manager/cloud-manager/user-guide.html)
* [Versiones anteriores de la documentación de AEM](https://helpx.adobe.com/es/experience-manager/aem-previous-versions.html)
* [Inicio de la Ayuda de Dynamic Media Classic](https://docs.adobe.com/content/help/es-ES/dynamic-media-classic/using/home.html)
* [Notas de la versión de Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notas de la versión de Livefyre](https://docs.adobe.com/content/help/es-ES/livefyre/using/release-notes/c-rn.html)

## ![Icono](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign permite entregar, de forma intuitiva y automatizada, mensajes privados a través de canales de marketing en línea y sin conexión. Ahora puede anticipar los deseos de los clientes mediante experiencias basadas en sus hábitos y preferencias.

### Campaign Standard

* [Adobe Campaign Standard 20.2](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/release-notes/release-notes.html)

### Nuevos tutoriales de Campaign Standard {#tutorials-acs}

| Contenido | Descripción |
| -----------| ---------- |  
| [Sustitución de Perfiles: prueba de mensajes de correo electrónico con perfiles objetivo](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html) | Pruebe los mensajes de correo electrónico con la función Sustitución de Perfil. |

### Recursos de ayuda de Campaña adicionales

* Adobe Campaign Standard: [Documentación](https://helpx.adobe.com/es/support/campaign/standard.html) - [Notas de la versión](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/release-notes/release-notes.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Planificación de lanzamiento](https://helpx.adobe.com/es/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentación](https://helpx.adobe.com/es/support/campaign/classic.html) - [Notas de la versión](https://docs.campaign.adobe.com/doc/AC/es-ES/RN.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Panel de control de Adobe Campaign: [Documentación](https://docs.adobe.com/content/help/es-ES/control-panel/using/control-panel-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/es-ES/control-panel/using/release-notes.html)

<!-- ## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Advertising Cloud release notes. -->

## ![Icono](/assets/magento.png) [!DNL Magento] {#magento}

Para las notas de la versión de Magento, consulte:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Icono](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] es una solución completa para la gestión de clientes potenciales y para los especialistas en marketing B2B que buscan transformar las experiencias de los clientes al interactuar en todas las etapas de los viajes de compra complejos.

### Actualizaciones centrales de Marketo Engage

Consulte [!DNL Marketo] las notas [](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) de la versión para obtener más información.

### Próximas funciones

Las siguientes funciones se lanzarán durante todo el trimestre:

| Función | Descripción |
|------|---------|
| [!DNL Bizible] | <ul><li>Nueva segmentación basada en cuentas</li><li>Almacenamiento de filtros específicos del tablero</li><li>Exportación de tableros Bizible en PDF</li></ul> |
| Conexión de ventas | Actualizaciones y mejoras de la ventana de composición y del centro de comandos |

### Anuncios

**Centro de éxito de Marketo Engage:** lanzamiento en febrero de 2020. El Centro de éxito es un centro de ayuda integrado en el producto que le permite buscar en la Documentación del producto, la Comunidad, las guías de inicio prácticas, el contenido de adopción de acceso y mucho más. Nota: Esta función se lanzará como una versión beta en ANZ y se comercializará en Norteamérica más adelante en el trimestre.

### Degradaciones

* **Parámetro &quot;_method&quot; de la API de recursos:** A partir de septiembre de 2020, los extremos de la API de recursos ya no aceptarán `_method` pasar parámetros de Consulta en un cuerpo POST para evitar las limitaciones de longitud de URI.
* **Degradación de compatibilidad con Internet Explorer:** a partir de la versión del 31 de julio de 2020, la interfaz de usuario de Marketo Engage dejará de ser compatible con Internet Explorer.

Para ver las notas de la versión acumulativas e históricas, consulte [Notas de la versión de Marketo](https://docs.marketo.com/x/CgA6Ag).
