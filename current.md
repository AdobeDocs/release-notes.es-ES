---
title: Notas de la versión de Adobe Experience Cloud
description: Plantilla para notas de la versión de Experience Cloud
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: b41cdd18c7e3251218bf41aee62979e5f79a4c2a
workflow-type: tm+mt
source-wordcount: '4722'
ht-degree: 39%

---


# Acceso anticipado - Notas de la versión de Adobe Experience Cloud - Mayo de 2020

![Banner](/assets/experience-cloud-banner-3.png)

Esta página proporciona nuevas funciones, correcciones y avisos importantes en [!DNL Adobe Experience Cloud]. Las fechas de lanzamiento de la solución pueden variar. Vuelva con frecuencia para ver las últimas actualizaciones.

>[!IMPORTANT]
>
>Esta página contiene contenido previo al lanzamiento y está sujeta a cambios antes del 21 de mayo de 2020. La nueva información publicada posteriormente se anotará con la fecha añadida.

>[!NOTE]
>
>Para recibir notificaciones por correo electrónico sobre próximas versiones, suscríbase a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html). 

**Fecha de lanzamiento: mayo de 2020**

Última actualización: **15 de mayo de 2020**

* [Estado del sistema de Adobe](#status)
* [Interfaz de Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/es-ES/target/using/release-notes/target-release-notes.html) (lleva a la página de ayuda de Target)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/es/primetime/user-guide.html) (lleva a la página de ayuda de Primetime)

¿Necesita ayuda? Visite [[!DNL Adobe Experience League]](https://experienceleague.adobe.com/#home) para encontrar cursos seleccionados por Adobe, documentación técnica, respuestas rápidas, perspectiva de la comunidad y formación dirigida por instructores.

## ![Icono](/assets/adobe.png) Estado del sistema de Adobe {#status}

[!UICONTROL El estado del sistema de Adobe] proporciona información detallada, actualizaciones de estado y notificaciones por correo electrónico sobre los productos en la nube de Adobe y las interrupciones y sesiones de mantenimiento de los servicios de Adobe. Puede comprobar el estado en [status.adobe.com](https://status.adobe.com/).

**Novedades**

* Con su Adobe ID, puede suscribirse a las notificaciones de eventos con una mayor granularidad, lo que permite llegar hasta la oferta de productos y el nivel de complementos. Para ayudarle a configurar su suscripción más rápido, el proceso de suscripción automática ahora recomienda una selección de productos y ofertas en función de los derechos del producto. Esto debería reducir el número de correos electrónicos que recibe y enviar notificaciones más relevantes en la bandeja de entrada. Empiece por [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuevas funciones y mejoras disponibles**

| Función | Descripción |
| -----------| ---------- |
| Mejora de la experiencia del usuario en cuanto a las suscripciones y las notificaciones | <ul><li>[!DNL Marketo Engage] las ubicaciones regionales ahora se filtran según la lista de ofertas de productos seleccionadas.</li><li>[!DNL Marketo Engage] las notificaciones por correo electrónico son relevantes para la región, la ubicación y las preferencias de entorno del usuario.</li></ul> |
| Confirmación de suscripción de Evento | <ul><li>Ahora puede obtener una confirmación por correo electrónico al suscribirse a las actualizaciones de evento único en curso.</li></ul> |
| Mejoras en el uso de la navegación global | <ul><li>Una experiencia de usuario coherente con `Adobe.com` el menú de navegación de nivel superior.</li></ul> |

## ![Icono](/assets/ec_appicon_24.png) Interfaz de Experience Cloud {#ecloud}

Actualizaciones generales en la interfaz de Experience Cloud.

**Dominio de producto unificado**

Adobe ha estado actualizando el encabezado de interfaz y dominio para unificar y mejorar su experiencia en todas las aplicaciones de Experience Cloud. Estas mejoras están diseñadas para mejorar sutilmente su experiencia. Estas mejoras no cambian los flujos de trabajo actuales.

Las actualizaciones incluyen:

* Nuevas direcciones URL de la aplicación: `experience.adobe.com/<application name>`:
   * Todos los productos adoptarán en algún momento este patrón de URL. Busque nuevas direcciones URL que entren en vigor durante el mes.
   * Compatibilidad con navegadores: Los exploradores admitidos son [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] y [!DNL Opera] (en sus versiones más recientes). **Nota:** Aunque la interfaz de Experience Cloud admite estos exploradores, es posible que las aplicaciones individuales no los admitan a todos. (Por ejemplo, [Analytics](https://docs.adobe.com/content/help/es-ES/analytics/admin/sys-reqs.html) no es compatible con [!DNL Opera] y [Target](https://docs.adobe.com/help/es-ES/target/using/implement-target/before-implement/supported-browsers.html) no es compatible con [!DNL Safari]).
   * ([!DNL Safari] solo) El cambio de dominio puede causar problemas de cookies en [!DNL Safari]. Al anular la selección _Impedir el seguimiento entre sitios_ en las preferencias de privacidad de [!DNL Safari], se habilitarán las cookies entre dominios (y todas las experiencias entre sitios) y Experience Cloud funcionará en este nuevo dominio.
* Es más fácil cambiar entre las organizaciones o a otra aplicación.
* Ayuda del producto mejorada: [!UICONTROL Experience League] está integrada en el producto, por lo que una búsqueda de ayuda también incluye resultados de foros de la comunidad y contenido de vídeo. Este cambio simplifica el acceso a más contenido y le ayuda a sacar el máximo rendimiento de Experience Cloud. Además, puede hacer clic en **[!UICONTROL Ayuda]** > **[!UICONTROL Comentarios]** para informar sobre problemas o compartir sus ideas con Adobe.

Las siguientes aplicaciones utilizan el nuevo dominio experience.adobe.com:

| Aplicación o servicio | Dominio |
| -----------| ---------- |
| página de inicio de Experience Cloud | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch  | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| Administración de viajes | `experience.adobe.com/journeys` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Panel de control de Adobe Campaign | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Servicio de lugares | `experience.adobe.com/places` |
| Distribución de software | `experience.adobe.com/downloads` |
| Herramienta de administración (beta) | `experience.adobe.com/admin` |

## ![Icono](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Notas de la versión de [!DNL Experience Platform,] incluyendo [!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration], [!UICONTROL ofertas], [!UICONTROL usuarios], [!UICONTROL Places], [!UICONTROL Mobile Services], y boletines de seguridad.

### Mejoras en la interfaz

Updated: **May 15, 2020**

[!DNL Adobe Experience Platform] está publicando actualizaciones en el dominio y en la barra de encabezado para mejorar su experiencia y unificarse con otras aplicaciones de Experience Cloud. Las actualizaciones incluyen:

* Es más fácil cambiar entre las organizaciones o a otra aplicación.
* Se ha mejorado la ayuda del usuario, que incluye artículos destacados y documentación relevante para el contexto en el menú Ayuda.
* Posibilidad de proporcionar comentarios sobre la plataforma de experiencias y tickets de compatibilidad con archivos.

See [Experience Platform release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md) for more information.

### Atributos del cliente: nueva documentación

Updated: **May 15, 2020**

* [Compatibilidad con Atributos del cliente para CCPA](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/ccpa.html) (California Consumer Privacy Act)
* [Compatibilidad de atributos del cliente con el RGPD](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/gdpr.html) (Reglamento general de protección de datos)

### Organización de recorridos {#journey}

Con Adobe Experience Platform, puede organizar los recorridos individuales de los clientes a escala en distintos canales de experiencia y adaptarse de forma inteligente a las necesidades y recorrido de cada usuario en tiempo real.

* [Documentación](https://docs.adobe.com/content/help/es-ES/journeys/using/journey-orchestration-home.html)
* [Notas de la versión](https://docs.adobe.com/content/help/es-ES/journeys/using/release-notes/release-notes.html)
* [Vídeotutoriales](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Información adicional de la versión de Experience Platform

* [Notas de la versión de Experience Platform Launch](https://docs.adobe.com/content/help/es-ES/launch/using/intro/release-notes/current.html)
* [Notas de la versión de Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Boletines de seguridad y avisos](https://helpx.adobe.com/es/security.html) (Todos los productos de Adobe)

## ![Icono](/assets/analytics.png) [!DNL Analytics] {#analytics}

* [Nuevas funciones en el análisis de viajes del cliente](#cust-journey)
* [Funciones nuevas en Adobe Analytics](#aa-features)
* [Avisos importantes para los administradores de Analytics](#aa-notices)
* [AppMeasurement](#appm)
* [Nuevos tutoriales de Analytics](#tutorials-analytics)

### Nuevas funciones en el análisis de viajes del cliente {#cust-journey}

| Función | Descripción |
| -----------| ---------- |
| [!UICONTROL Análisis]del viaje del cliente: Disponibilidad global | Hace que [!UICONTROL Customer Journey Analytics] esté disponible para los clientes de EMEA y APAC. |
| [!UICONTROL Análisis]del viaje del cliente: Compatibilidad con los Simuladores para pruebas de la plataforma de [!UICONTROL Adobe Experience] | Permite seleccionar entornos limitados [!UICONTROL específicos de la plataforma de] Adobe Experience para crear conexiones de CJA. [Más información...](https://docs.adobe.com/content/help/es-ES/analytics-platform/using/cja-connections/create-connection.translate.html) |

### Funciones nuevas en Adobe Analytics {#aa-features}

<!-- Bulk Ingest: Enables you to ingest batches of Analytics data. Useful for server-side and offline data. Learn more...
First-Party Domains Available in China RDC: Enables customers with a cn domain to request a 1st-party domain for use inside of Mainland China. Learn more... -->

| Función | Descripción |
| -----------| ---------- |
| Compatibilidad de Analytics con la plataforma de [!UICONTROL Adobe Experience Platform Edge Network] | Le permite utilizar una sola etiqueta para enviar datos a varias soluciones de Adobe, como Adobe Analytics, Adobe Destinatario, Adobe Audiencia Manager, Adobe Experience Platform Data Lake, Unified Perfil y el servicio Experience Cloud ID. [Más información...](https://docs.adobe.com/content/help/es-ES/experience-platform/edge/home.html) |
| [!UICONTROL paneles de Adobe Analytics] | [!UICONTROL paneles] de Adobe Analytics es una aplicación móvil que permite a los usuarios acceder a las perspectivas desde Adobe Analytics en cualquier momento y lugar. Esta aplicación está dirigida a los ejecutivos que buscan acceso directo a métricas clave. Permite acceder a cuadros de mandos interactivos y depurados y estará disponible para los sistemas operativos iOS y Android. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/mobapp/home.html) |
| [!UICONTROL Workspace][!UICONTROL : Crear automáticamente tablas improvisadas a partir de un estado en blanco] | Previously, you could not drop components directly into a blank project or blank panel; you had to add a [!UICONTROL Freeform Table] first. You can now drop components directly into a blank project or panel, and a [!UICONTROL Freeform Table] is automatically built for you in a recommended format. Además, se han realizado mejoras en la forma en que se gestionan los tipos de componentes mixtos (como dimensiones y métricas) cuando se colocan juntos en una tabla improvisada en blanco. |

#### Correcciones de Adobe Analytics

* Fixed an issue that caused missing [!DNL Analytics] segment data in Audience Manager. (AN-206221)
* Se ha corregido un problema con el procesamiento de [!UICONTROL fuentes de datos] que mostraba fechas incorrectas. (AN-213604)
* Se ha corregido un problema con los archivos de clasificación que no se cargaban correctamente en el FTP. (AN-214102)
* Se ha corregido un problema con el método de API `Segments.Get`, que no devolvía una respuesta completa. (AN-206210)
* Se ha corregido un problema en el cual los elementos de línea de tabla se convertían en caracteres especiales en la descarga de PDF de [!DNL Workspace]. (AN-196153)
* Se ha corregido un problema con la llamada a la API 1.4 de Adobe Analytics `visattrcustomeridcustomerattributes`, que no funcionaba correctamente. (AN-186873)
* Se ha corregido un problema con los datos que aparecían en los informes pero no aparecían en la [!UICONTROL fuente de datos]. (AN-211923)
* Se ha corregido un problema que impedía copiar permisos de [!UICONTROL Perfil de producto]. (AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to [!UICONTROL Report Builder]. (AN-207750)
* Se ha corregido un problema con los datos de [!UICONTROL AdWords] que no se mostraban en [!UICONTROL Advertising Analytics]. (AN-213249)
* Se corrigió un problema en el cual los datos de clasificación no se mostraban en la vista de tendencias. (AN-212761)
* Se ha corregido un problema que provocaba un recuento incorrecto de segmentos publicados en el [!UICONTROL Administrador de segmentos]. (AN-213374)
* Se ha corregido un problema con **[!UICONTROL Mostrar tendencia ascendente como...]** en el Editor [!UICONTROL de métricas] calculadas: no funcionaba al aplicar filtros. (AN-214223)
* Se han corregido varios problemas con Importación y exportación de [!UICONTROL clasificaciones] . (AN-213488, AN-215309, AN-216345, AN-215307 y AN-216671)
* Se han corregido varios problemas con el Generador [!UICONTROL de reglas]de clasificación. (AN-213826, AN-213550 y AN-213095)
* Se corrigieron problemas con el procesamiento [!UICONTROL de fuentes] de datos. (AN-218083, AN-213604, AN-214102, AN-215485, AN-215339, AN-212911 y AN-217551, (AN-217947, AN-219018, AN-214691 y AN-218401)
* Se han corregido problemas de conectividad de FTP. (AN-115525)
* Se corrigieron varios problemas [!DNL Analytics] de fuentes [!UICONTROL de datos] . (AN-176769, AN-160480, AN-211923, AN-204286, AN-212977, AN-214528, AN-215080, (AN-217784, AN-219093, AN-218817, AN-217798, AN-218267 y AN-218382)
* Se corrigieron problemas con las solicitudes [!UICONTROL del almacén] de datos. (AN-181836)
* Se corrigieron problemas en proyectos de [!UICONTROL Workspace] descargados en PDF, en los que los valores se convertían en caracteres especiales. (AN-196153)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions in [!UICONTROL Admin Console]. (AN-211113)
* Se corrigió un problema en el cual los formatos de tiempo en las métricas calculadas se desglosaban para los valores negativos. (AN-210900)
* Se ha corregido un problema que impedía a los usuarios cambiar el modelo [!UICONTROL de] atribución en las métricas de fila estáticas. (AN-207872)
* Se ha corregido un problema que provocaba que el creador de informes  programados se quedara en cola. (AN-215317)
* Se corrigió el conector [!UICONTROL de datos de]ExactTarget. (AN-210794)
* Se corrigieron problemas de latencia en la API [!UICONTROL de ingestión]masiva. (AN-210165)
* Se ha corregido un problema que impedía a los usuarios iniciar sesión en el Creador [!UICONTROL de] informes con un Federated ID. (AN-207750)
* Se ha corregido un problema en [!UICONTROL Advertising Analytics] que impedía que se mostraran [!DNL Google AdWords] los datos. (AN-213249)
* Se ha corregido un problema que impedía que se mostraran eventos [!UICONTROL de Workspace] [!UICONTROL Project Viewed] en los registros. (AN-214134)
* Se ha corregido un problema que se producía al cambiar el intervalo de fechas en [!UICONTROL Workspace] y seleccionar **[!UICONTROL Aplicar a todos los paneles]**. La fecha no cambió en algunos paneles. (AN-214944)
* Se ha corregido un problema que impedía crear o editar alertas. (AN-215920)
* Se ha corregido un problema por el que todos los intervalos de fechas dinámicos en [!UICONTROL Workspace] mostraban fechas incorrectas debido a que el primer día de la semana cambiaba esporádicamente a un domingo de lunes. (AN-218835)

#### Correcciones adicionales de Adobe Analytics

AN-101871, AN-115525; AN-123869; AN-152580; AN-160480; AN-178128; AN-186907; AN-199299; AN-201342; AN-201397; AN-204286; AN-204518; AN-206045; AN-206948; AN-208607; AN-209486; AN-210743; AN-211550; AN-211539; AN-211826; AN-211943; AN-212130; AN-212151; AN-212653; AN-212673; AN-212709; AN-212833; AN-212961; AN-212977; AN-213095; AN-213422; AN-213450; AN-213490; AN-213752; AN-213827; AN-214094; AN-214153; AN-214214; AN-214234; AN-214253;  AN-214255; AN-214343; AN-214355; AN-214401; AN-214427; AN-214528; AN-214642; AN-214691; AN-214772; AN-214793; AN-214924; AN-215017; AN-215080; AN-215212; AN-215312; AN-215377; AN-215402; AN-215545; AN-215905; AN-215963; AN-216447; AN-216676; AN-216880; AN-216999; AN-217245; AN-218450; AN-218899; AN-219487; AN-219677

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación o actualizada | Descripción |
| -----------| ---------- | ---------- |
| Cambio en la forma en que se calculan las [!UICONTROL entradas y las salidas] en [!UICONTROL Workspace] | 7 de abril de 2020 | En [!UICONTROL Analysis Workspace], a partir de marzo de 2020, hemos cambiado la forma en que el valor _Ninguno_ interactúa con las [!UICONTROL entradas y salidas]. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before entry or exit. Por ejemplo, supongamos que la primera visita individual de una visita no tiene valor para las eVars, pero la segunda sí. In [!UICONTROL Reports &amp; Analytics] the first hit will show as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit. |
| Fin de la vida útil de la configuración **[!UICONTROL Nivel de conversión]** | 3 de marzo de 2020 | La configuración [Nivel de conversión](https://docs.adobe.com/content/help/es-ES/analytics/admin/admin-tools/general-acct-settings-admin.html) de **[!UICONTROL Herramientas de administración]** > **[!UICONTROL Grupos de informes]** > **[!UICONTROL Configuración general de cuenta]** se eliminó de la interfaz de usuario el 12 de marzo de 2020. |
| Fin de la vida útil de la configuración **[!UICONTROL Archivo de tablero]** | 27 de marzo de 2020 | La configuración **[!UICONTROL Ver archivo]** en **[!UICONTROL Administrar tableros]** de [!UICONTROL Reports &amp; Analytics] dejará de estar disponible a partir de octubre de 2020. |
| Finalización de la compatibilidad con TLS 1.1 | 3 de octubre de 2019 | A partir del 31 de marzo de 2020, Adobe Analytics dejará de ofrecer soporte para TLS 1.1. Este cambio es parte de nuestro trabajo para mantener los estándares de seguridad más altos e impulsar la seguridad de los datos del cliente. |
| Nuevo dominio de Adobe Analytics | 18 de diciembre de 2019 | El 16 de enero de 2020, Adobe Analytics empezará a pasar a un nuevo dominio: `https://experience.adobe.com/analytics.`<br>**Nota:** Este cambio se aplica a todos los usuarios que acceden a Analytics con su Adobe ID o Enterprise ID.<ul><li>Este cambio de dominio puede provocar problemas con las cookies al cargar Analytics en Safari. Al anular la selección _Impedir el seguimiento entre sitios_ en las preferencias de privacidad de [!DNL Safari], se habilitarán las cookies entre dominios (y todas las experiencias entre sitios) y Analytics funcionará en este nuevo dominio de Adobe Experience Cloud. Puede utilizar otros navegadores sin problemas porque esto solo afecta a los usuarios de [!DNL Safari].</li><li>El cambio de dominio puede hacer que [!UICONTROL Activity Map] deje de funcionar para algunos clientes [en casos específicos](https://docs.adobe.com/content/help/es-ES/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fin de vida útil: API heredadas de Analytics | 9 de enero de 2020 | En noviembre de 2020, los siguientes servicios de API heredadas de Analytics llegarán a su fin de vida útil y se cerrarán. Las integraciones actuales creadas con estos servicios dejarán de funcionar. <ul><li>API de Analytics 1.3</li><li>API de Analytics SOAP 1.4</li><li>Autenticación OAuth heredada (OAuth y JWT)</li></ul>Hemos creado las [Preguntas frecuentes del fin de la vida útil de la API heredada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ayudarle a responder a sus preguntas y proporcionar instrucciones sobre cómo proceder. Las integraciones de API que emplean estos servicios pueden migrar a las [API de REST 1.4 de Analytics](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o a las [API de Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Las cuentas heredadas de OAuth pueden migrar a una cuenta de integración de Analytics [Adobe IO](https://console.adobe.io/home?mv=email), que puede utilizarse para acceder tanto a las API de Analytics 1.4 como a las API de Analytics 2.0. |
| Fin de la administración de datos en el centro de datos de San José para Londres y Singapur | Julio de 2020 | Para los clientes de Londres y Singapur, ya no se ofrecerá la administración de datos entre Londres o Singapur y el centro de datos de San José [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, utilice [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Singapur, utilice [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| EOL de Ad Hoc Analysis | 6 de agosto de 2018 | Adobe anunció su intención de finalizar el servicio de Ad Hoc Analysis. La fecha se hará pública una vez que esté disponible. Para obtener más información, consulte [Descubrir Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Consulte [Notas de la versión de AppMeasurement para JavaScript](https://docs.adobe.com/content/help/es-ES/analytics/implementation/appmeasurement-updates.html). La versión 2.20.0 se publicó 5 de marzo de 2020.

### Nuevos tutoriales de Analytics {#tutorials-analytics}

| Contenido | Descripción |
| -----------| ---------- |
| [Plantilla de tutorial de formación en Espacio de trabajo de Análisis](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | El Tutorial de formación de [!UICONTROL Análisis Workspace] le guía a través de la terminología común y de los pasos para crear su primer proyecto en [!UICONTROL Workspace]. |
| [Añadir comparaciones de meses y años anteriores con tendencias](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | Aprenda a aplicar intervalos de fechas personalizados para crear comparaciones de tendencias mensuales y anuales para cualquier métrica en [!UICONTROL Análisis Workspace]. |
| [Extensión de modo oscuro para área de trabajo de Análisis](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | Active la extensión oscura de Reader Chrome para oscurecer el espacio de trabajo de Análisis. |
| [Extensión de cuentagotas de color para definir paletas personalizadas](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | Aprenda a utilizar la extensión ColorPick EyeDropper Chrome para encontrar fácilmente los valores hexadecimales que necesita para una paleta de colores personalizada en sus proyectos de [!UICONTROL Workspace] . |

#### Recursos de ayuda de Analytics

* [Tutoriales de Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentación del producto de Adobe Analytics](https://docs.adobe.com/content/help/es-ES/analytics/landing/home.html)

## ![Icono](/assets/audience-manager.png) Audience Manager {#aam}

Nuevas funciones, correcciones, documentación y tutoriales en el Administrador de Audiencias.

### Actualizaciones de la interfaz de usuario

Audiencia Manager está publicando actualizaciones en el dominio y en la barra de encabezado para mejorar su experiencia y unificarse con otras aplicaciones de Experience Cloud.

* Es más fácil cambiar entre las organizaciones o a otra aplicación.
* Se ha mejorado la ayuda del usuario, que incluye artículos destacados y vídeos relacionados con el contexto en el menú Ayuda.
* Posibilidad de proporcionar comentarios sobre la plataforma de experiencias y tickets de compatibilidad con archivos.
* Un nuevo patrón de URL más sencillo. Actualice los marcadores a la nueva dirección URL: `experience.adobe.com/audience-manager`.

Estas actualizaciones solo están disponibles para los usuarios que inicien sesión con un Adobe ID. Para cambiar a un inicio de sesión con Adobe ID, consulte [Administrar usuarios y productos](https://docs.adobe.com/content/help/es-ES/core-services/interface/manage-users-and-products/admin-getting-started.html)de Experience Cloud.

### Nuevas funciones y correcciones en Adobe Audience Manager

| Función | Descripción |
| -----------| ---------- |  
| [Herramientas de administración masiva (BAAAM)](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | Hemos cargado una nueva hoja de cálculo de herramientas de administración masiva que: <br><br><ul><li>Permite la lista de subcarpetas en la jerarquía de características (AAM-51528)</li><li>Recupera las métricas cuando se le solicitan características asociadas a ID de CRM (ID de varios dispositivos) (AAM-52135)</li><li>Corrige un problema de codificación de idioma para los caracteres coreanos (AAM-AAM-54006)</li></ul> |

**Correcciones**

* Se corrigió un problema en el cual los informes de tendencias agotaban el tiempo de espera de las carpetas con un gran número de características. (AAM-54457)
* Se corrigió un problema en el cual los clientes no podían ver el generador [!UICONTROL de] Expresiones en el flujo de trabajo de creación/edición de características. (AAM-54255)
* Se corrigió un problema en el cual los mensajes de error en la interfaz de usuario se mostraban solo durante un corto tiempo, y desaparecían antes de que los clientes tuvieran la oportunidad de leerlos. Esto ocurría, por ejemplo, al intentar eliminar un segmento asignado a un destino. (AAM-54031)
* Se corrigió un problema en el cual los clientes que ya no usaban [!UICONTROL Audiencia Marketplace] recibían correos electrónicos de facturación mensuales. (AAM-54602)
* Se corrigió un problema en el cual los clientes que hacían clic en ciertas características desde otras ubicaciones en la interfaz de usuario veían vínculos rotos en lugar de las características. (AAM-54768)
* Se corrigió un problema en el cual, en el modo de edición de expresión de rasgos, al presionar ENTRAR se actualizaba la página y se perdía la expresión de rasgos. (AAM-54210)
* Varias mejoras de accesibilidad en toda la interfaz de usuario. (AAM-47781, AAM-49075, AAM-49360, AAM-49361, AAM-49376, AAM-50432, AAM-52550, AAM-54660).

### Nuevos tutoriales del Administrador de Audiencias {#tutorials-aam}

| Contenido | Descripción |
| -----------| ---------- |  
| [Explicación de los términos y conceptos básicos en el Administrador de Audiencias](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | En este vídeo se explican algunos de los términos y conceptos básicos que le permiten empezar a trabajar en el Administrador de Audiencias, como las señales, las características, los segmentos, etc. |
| [Explicación del flujo de datos en el Administrador de Audiencias](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | Este vídeo le ayuda a comprender el Administrador de Audiencias de Adobe describiendo el flujo de datos dentro, a través y fuera de la aplicación. |
| [Administrador de Audiencias: información general de un DMP](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | Comprenda los principales desafíos con la personalización entre canales y cómo el administrador de Audiencias de Adobe impulsa el viaje del cliente. Además, conozca qué tipos de datos se pueden incorporar en el Administrador de Audiencias e identifique a los socios de ecosistema de tecnología de publicidad integrados con el Administrador de Audiencias. |
| [Casos de uso del Administrador de Audiencias](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | En este vídeo identificamos cuatro casos de uso comunes del Administrador de Audiencias y describimos las optimizaciones asociadas a ellos. |
| [Explicación de las métricas entre dispositivos en el Administrador de Audiencias](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | En este vídeo analizamos la diferencia entre los perfiles de dispositivos y los perfiles entre dispositivos, y mostramos dónde coinciden los números de la interfaz de usuario con estos distintos tipos de perfiles. |
| [Explicación de las Audiencias predictivas en el Administrador de Audiencias](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | En este vídeo analizamos cuáles son las Audiencias predictivas del administrador de Audiencias, presentamos detalles sobre cómo funcionan y señalamos casos de uso. |
| [Configurar e informar sobre Audiencias predictivas en el Administrador de Audiencias](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | En este vídeo se muestra la configuración de Audiencias predictivas en la interfaz del Administrador de Audiencias. También vemos los informes que muestran los resultados del modelo. |

## ![Icono](/assets/aem.png) Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Adobe Experience Manager (AEM). Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

### Actualizaciones de productos

* **AEM como un servicio en la nube**

   * Mejoras y correcciones en el procesamiento de recursos. El cuadro de diálogo de reprocesamiento de recursos proporciona al usuario más control, permite seleccionar un perfil de procesamiento específico y permite activar el flujo de trabajo posterior al procesamiento.
   * Mejoras en el rendimiento de la ingesta de recursos de Dynamic Media.

### Autoayuda

* **Servicio de conversión automatizada de formularios - versión AFC-2020.03.1**

   Hay una nueva opción disponible al instalar el conector más reciente:

   **[!UICONTROL Detección automática de secciones]** lógicas: puede utilizar la opción [!UICONTROL Detectar automáticamente secciones] lógicas para soltar paneles de nivel de página (paneles basados en números de página) y crear únicamente paneles lógicos. También agrupa los campos que no pertenecen a ninguna sección con secciones lógicas anteriores y los campos de una sección lógica que se distribuyen en dos páginas adyacentes en una sola sección lógica. Por ejemplo: si algunos campos de una sección lógica se encuentran al final de la página uno y algunos están en el inicio de la página dos, todos esos campos se agrupan en una sola sección lógica.

* **Formatos de imagen no admitidos en Dynamic Media**

   Información sobre los subtipos de formatos de archivo de imagen rasterizada que no se admiten en los medios [!UICONTROL dinámicos].

   Consulte Formatos de imagen rasterizada [no admitidos en Dynamic Media](https://docs.adobe.com/content/help/en/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media).

* **Fragmentos de contenido**

   Información sobre la compatibilidad con fragmentos [de contenido en la API](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html)HTTP de Recursos AEM, junto con la [personalización y ampliación de fragmentos](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html)de contenido y la configuración de fragmentos [de contenido para la representación](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html).

* **Comunidad de AEM Experience League**

   Conéctese con la comunidad [de la Liga de experiencias de](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community)AEM: Haga preguntas a los compañeros de aprendizaje y a los expertos en AEM, examine los hilos y comparta sus consejos y experiencia.

* **Boletines de AEM**

   El boletín informativo de AEM de la [!UICONTROL Experience League] está diseñado para ayudarle a ponerse al día con AEM, de modo que pueda obtener inicios para obtener valor de inmediato. Esta es la newsletter más reciente:

   * [Volumen 30](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html): Experience Manager ya está disponible como servicio en la nube.
   * [Suscríbase](https://adobeeventsonline.com/AEM/2017/NL/Optin/) a la newsletter de Experience Insider.
   * Archivos de newsletter de Vista en la sección Recursos [de](https://helpx.adobe.com/es/support/experience-manager/6-5.html) AEM de la página de información y asistencia de Adobe Experience Manager 6.5.

### Nuevos tutoriales de Experience Manager

| Contenido | Descripción |
| -----------| ---------- |  
| [Configuración de AEM Runtime local](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) can be run locally using the [!UICONTROL AEM as a Cloud Service] SDK&#39;s [!UICONTROL Quickstart Jar]. This allows developers to deploy to, and test custom code, configuration, and content prior to committing it to source control, and deploying it to a [!UICONTROL AEM as a Cloud Service] environment. |
| [Introducción a Recursos AEM](https://video.tv.adobe.com/v/33624?captions=spa) | Vídeo de introducción sobre cómo empezar a utilizar Recursos AEM para usuarios empresariales. |
| [esquemas de carpetas de metadatos](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | Los esquemas de carpeta de metadatos permiten a los usuarios gestionar y revisar los metadatos asociados a las propias carpetas de recursos, en lugar de hacerlo directamente en los recursos. |
| [Etiquetado](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | Las etiquetas son una herramienta integral para administrar recursos en la jerarquía de carpetas de los recursos. El establecimiento de una taxonomía de etiquetado es fundamental para que los usuarios puedan descubrir y organizar los recursos en AEM. |
| [Perfiles de metadatos](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | Los perfiles de metadatos permiten la aplicación automática de metadatos predeterminados a los recursos de las carpetas de recursos. Esto ayuda a reducir la carga que supone la administración de metadatos para los usuarios de AEM y aumenta la coherencia de los metadatos. |
| [esquemas de metadatos](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | Los esquemas de metadatos definen la interfaz que expone los metadatos de los recursos en AEM. En este vídeo se analiza la combinación de métodos utilizados para aplicar recursos. |

### Recursos adicionales

* [Notas de la versión de AEM as a Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [Documentación de AEM como servicio de nube](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/landing/home.html)
* [Página de inicio de Learn &amp; Support de AEM 6.5](https://helpx.adobe.com/es/support/experience-manager/6-5.html)
* [Página de inicio de Learn &amp; Support de AEM 6.4](https://helpx.adobe.com/es/support/experience-manager/6-4.html)
* [Página de inicio de Learn &amp; Support de AEM 6.3](https://helpx.adobe.com/es/support/experience-manager/6-3.html)
* [Página de inicio de Learn &amp; Support de AEM 6.2](https://helpx.adobe.com/es/support/experience-manager/6-2.html)
* [Guía del usuario de Cloud Manager](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Notas de la versión de AEM Cloud Manager](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Versiones anteriores de la documentación de AEM](https://helpx.adobe.com/es/experience-manager/aem-previous-versions.html)
* [Inicio de la Ayuda de Dynamic Media Classic](https://docs.adobe.com/content/help/es-ES/dynamic-media-classic/using/home.html)
* [Notas de la versión de Dynamic Media](https://docs.adobe.com/content/help/es-ES/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notas de la versión de Livefyre](https://docs.adobe.com/content/help/es-ES/livefyre/using/release-notes/c-rn.html)

## ![Icono](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign permite entregar, de forma intuitiva y automatizada, mensajes privados a través de canales de marketing en línea y sin conexión. Ahora puede anticipar los deseos de los clientes mediante experiencias basadas en sus hábitos y preferencias.

### Campaign Standard

Versión del Panel de control:

| Función | Descripción |
| -----------| ---------- |  
| Gestión de claves GPG | Instale y/o genere claves GPG en una instancia de marketing, para cifrar los datos enviados desde la Campaña y descifrar los datos entrantes. |
| Administración de certificados para subdominios CNAME | El Panel de control ahora le permite renovar los certificados SSL de sus subdominios delegados con el método CNAME. |

* [Adobe Campaign Standard 20.3](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/es-ES/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Nuevos tutoriales de Campaign Standard {#tutorials-acs}

| Contenido | Descripción |
| -----------| ---------- |  
| [Panel de control - Administración de registros TXT de Google](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | Obtenga información sobre cómo agregar registros de verificación del sitio TXT de Google a todos los subdominios utilizados para enviar correos electrónicos a direcciones GMAIL con el Panel de control de Campaña. |
| [Configurar y ejecutar un flujo de trabajo con la actividad de API externa](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | Obtenga información sobre cómo llamar a un extremo de API REST externo mediante la actividad de API externa. |
| (ACS) Tutorial sobre [introducción a las notificaciones push para Android](https://jira.corp.adobe.com/browse/KT-3846) | Este tutorial explica los pasos necesarios para configurar las notificaciones push con ACS y la aplicación Android. |

### New Campaign Classic tutorials {#tutorials-acc}

| Contenido | Descripción |
| -----------| ---------- |  
| [Gran gestión de datos sobre el copo de nieve](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Conozca cómo aprovechar el conector Snowflake en Adobe Campaign Classic. |
| [Panel de control - Administración de registros TXT de Google](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | Obtenga información sobre cómo agregar registros de verificación del sitio TXT de Google a todos los subdominios utilizados para enviar correos electrónicos a direcciones GMAIL con el Panel de control de Campaña. |

### Recursos de ayuda adicionales de Campaign

* Adobe Campaign Standard: [Documentación](https://helpx.adobe.com/es/support/campaign/standard.html) - [Notas de la versión](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/release-notes/release-notes.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Planificación de lanzamiento](https://helpx.adobe.com/es/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentación](https://helpx.adobe.com/es/support/campaign/classic.html) - [Notas de la versión](https://docs.adobe.com/content/help/es-ES/campaign-classic/using/release-notes/latest-release.translate.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Panel de control de Adobe Campaign: [Documentación](https://docs.adobe.com/content/help/es-ES/control-panel/using/control-panel-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/es-ES/control-panel/using/release-notes.html)

## ![Icono](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Nuevas funciones de Advertising Cloud DSP](#adcloud-dsp)
* [Nuevas funciones en Advertising Cloud Search](#adcloud-search)

### Nuevas funciones de Advertising Cloud DSP {#adcloud-dsp}

| Función | Descripción |
| -----------| ---------- |
| [!UICONTROL Campañas Classic] y [!UICONTROL Campañas Beta] | La configuración de medición de IAS para fraude y seguridad de marca, que puede configurar de forma opcional para cada campaña, ahora incluye opciones para medir en el inventario VAST y VPAID. |
| [!UICONTROL Campañas beta] | Se mejoraron las visualizaciones de datos y los tiempos de carga de las páginas. |
|  | En todas las páginas, ahora puede descargar informes de Excel basados en los filtros y vistas actuales. |
|  | (En la versión del 22 de mayo) Las nuevas métricas incluyen métricas de todo el tiempo, Envío de intervalo actual, OTS de fecha específica. |
| [!UICONTROL Listas negras] | El sistema de pronóstico ahora utiliza automáticamente la lista negra a nivel de anunciante o cuenta. Los usuarios ya no necesitan pegar la lista negra en la configuración de colocación. |
| [!UICONTROL Ofertas de inventario] | (Beta cerrada) Un nuevo formulario simplificado le permite configurar, editar y solucionar rápidamente las ofertas de la plataforma de suministro (SSP) que no están disponibles en la bandeja de entrada del ID de oferta. |
|  | Al aceptar un paquete de ofertas garantizadas mediante programación en la Bandeja de entrada de ID de acuerdo, ahora se le advierte de que debe crear una colocación predeterminada para cada ID de acuerdo. |

### Nuevas funciones en [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Función | Descripción |
| -----------| ---------- |
| [!UICONTROL Campañas] | (Cuentas de Google Ads; (servicio beta) A partir de finales de mayo, Advertising Cloud Search podrá sincronizar datos para sus campañas de visualización de Google Gmail y sus campañas de compras Google Smart con las conversiones de Google para seguimiento y sistema de informes. El servicio también le permitirá editar la configuración de la campaña y la configuración del grupo de publicidad para sus campañas existentes desde las vistas de Campañas y grupos de publicidad. El servicio será opcional. Una vez que el servicio esté disponible en general, se aplicará una tarifa adicional.<br>Para obtener más información sobre el servicio, incluido el programa beta y el ámbito futuro, póngase en contacto con su administrador de cuentas de Adobe. |

## ![Icono](/assets/magento.png) [!DNL Magento] {#magento}

Para las notas de la versión de Magento, consulte:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Icono](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] es una aplicación completa para la gestión de clientes potenciales y para los especialistas en marketing B2B que buscan transformar las experiencias de los clientes al interactuar en todas las etapas de los viajes de compra complejos.

### Actualizaciones centrales de Marketo Engage

Consulte las notas [!DNL Marketo] de la [versión](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) para obtener la información más reciente sobre la versión.

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