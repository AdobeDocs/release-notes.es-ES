---
title: Notas de la versión de Adobe Experience Cloud
description: Plantilla para notas de la versión de Experience Cloud
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: be2f2b5ad468ad63bfcb2fdd67d063203ac08654
workflow-type: tm+mt
source-wordcount: '5030'
ht-degree: 79%

---


# Notas de la versión de Adobe Experience Cloud: mayo de 2020

![Banner](/assets/experience-cloud-banner-3.png)

Esta página proporciona nuevas funciones, correcciones y avisos importantes en [!DNL Adobe Experience Cloud]. Las fechas de lanzamiento de la solución pueden variar. Vuelva con frecuencia para ver las últimas actualizaciones.

>[!NOTE]
>
>Para recibir notificaciones por correo electrónico sobre próximas versiones, suscríbase a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html).

**Fecha de lanzamiento: mayo de 2020**

Última actualización: **4 de junio de 2020**

* [Estado del sistema de Adobe](#status)
* [Interfaz de Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (**actualizado el 4 de junio de 2020**)
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

Fecha de versión: **21 de mayo de 2020**

**Novedades**

* Con su Adobe ID, puede suscribirse a las notificaciones de eventos con una mayor granularidad, lo que permite llegar hasta la oferta de productos y el nivel de complementos. Para ayudarle a configurar su suscripción más rápido, el proceso de suscripción automática ahora recomienda una selección de productos y ofertas según los derechos del producto. Esto debería reducir la cantidad de correos electrónicos que recibe y enviaría notificaciones más pertinentes a su bandeja de entrada. Empiece por [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuevas funciones y mejoras disponibles**

| Función | Descripción |
| -----------| ---------- |
| Mejora de la experiencia del usuario en cuanto a las suscripciones y las notificaciones | <ul><li>Las ubicaciones regionales de [!DNL Marketo Engage] ahora se filtran según la lista de ofertas de productos seleccionadas.</li><li>Las notificaciones de [!DNL Marketo Engage] por correo electrónico son pertinentes la región, la ubicación y las preferencias de entorno del usuario.</li></ul> |
| Confirmación de suscripción de evento | <ul><li>Ahora puede obtener una confirmación por correo electrónico al suscribirse a las actualizaciones de evento único en curso.</li></ul> |
| Mejoras en el uso de la navegación global | <ul><li>Una experiencia de usuario coherente con `Adobe.com` en el menú de navegación de nivel superior.</li></ul> |

## ![Icono](/assets/ec_appicon_24.png) Interfaz de Experience Cloud {#ecloud}

Actualizaciones generales en la interfaz de Experience Cloud.

**Dominio de producto unificado**

Adobe ha estado actualizando el encabezado de la interfaz y el dominio para unificar y mejorar el funcionamiento de las aplicaciones de Experience Cloud. Estas mejoras están diseñadas para mejorar sutilmente su experiencia. Estas mejoras no cambiarán los flujos de trabajo actuales.

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
| Página de inicio de Experience Cloud | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| Administración de recorridos | `experience.adobe.com/journeys` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Panel de control de Adobe Campaign | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Servicio de Places | `experience.adobe.com/places` |
| Distribución de software | `experience.adobe.com/downloads` |
| Herramienta de administración (beta) | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Board &amp; Collections]**, un filtro heredado en el selector de [!UICONTROL recursos de Experience Cloud] se está retirando del mercado.

## ![Icono](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Notas de la versión de [!DNL Experience Platform,] incluyendo [!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration], [!UICONTROL ofertas], [!UICONTROL usuarios], [!UICONTROL Places], [!UICONTROL Mobile Services], y boletines de seguridad.

### Mejoras en la interfaz

Actualización: **15 de mayo de 2020**

[!DNL Adobe Experience Platform] está publicando actualizaciones en el dominio y en la barra de encabezado para mejorar su experiencia y unificarse con otras aplicaciones de Experience Cloud. Las actualizaciones incluyen:

* Es más fácil cambiar entre las organizaciones o a otra aplicación.
* Se ha mejorado la ayuda del usuario, que incluye artículos destacados y documentación pertinente al contexto en el menú Ayuda.
* Posibilidad de proporcionar comentarios sobre Experience Platform y los tickets de compatibilidad con archivos.

Consulte las [Notas de la versión de Experience Platform](https://docs.adobe.com/content/help/es-ES/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md) para obtener más información.

### Atributos del cliente: documentación nueva

Actualización: **15 de mayo de 2020**

* [Compatibilidad con Atributos del cliente para CCPA](https://docs.adobe.com/content/help/es-ES/core-services/interface/customer-attributes/ccpa.html) (Ley de Privacidad del Consumidor de California)
* [Compatibilidad de atributos del cliente con el RGPD](https://docs.adobe.com/content/help/es-ES/core-services/interface/customer-attributes/gdpr.html) (Reglamento General de Protección de Datos)

### Organización de recorridos {#journey}

Con Adobe Experience Platform, puede organizar los recorridos individuales de los clientes a escala en distintos canales de experiencia y adaptarse de forma inteligente a las necesidades y recorrido de cada usuario en tiempo real.

* [Documentación](https://docs.adobe.com/content/help/es-ES/journeys/using/journey-orchestration-home.html)
* [Notas de la versión](https://docs.adobe.com/content/help/es-ES/journeys/using/release-notes/release-notes.html)
* [Vídeotutoriales](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Información adicional de la versión de Experience Platform

* [Notas de la versión de Experience Platform Launch](https://docs.adobe.com/content/help/es-ES/launch/using/intro/release-notes/current.html)
* [Notas de la versión de Experience Platform](https://docs.adobe.com/content/help/es-ES/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md)
* [Boletines de seguridad y avisos](https://helpx.adobe.com/es/security.html) (Todos los productos de Adobe)

## ![Icono](/assets/analytics.png) [!DNL Analytics] {#analytics}

Updated **June, 2020**

* [Funciones nuevas en Adobe Analytics](#aa-features)
* [Nuevas funciones en Customer Journey Analytics](#cust-journey)
* [Nuevas funciones de Media Analytics](#media-aa)
* [Correcciones de Adobe Analytics](#aa-fixes)
* [Avisos importantes para los administradores de Analytics](#aa-notices)
* [AppMeasurement](#appm)
* [Nuevos tutoriales de Analytics](#tutorials-analytics)

### Funciones nuevas en Adobe Analytics {#aa-features}

| Función | [Disponibilidad](https://docs.adobe.com/content/help/es-ES/analytics/landing/an-releases.html)general: fecha de Destinatario | Descripción |
| -----------| ---------- |-------|
| IQ de atribución: Atribución algorítmica | 18 de junio de 2020 | El modelo [!UICONTROL Atribución] algorítmica de Espacio de trabajo de Análisis utiliza técnicas estadísticas para determinar dinámicamente la asignación óptima de crédito para la métrica seleccionada. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| IQ de atribución: Ventanas retroactivas personalizadas | 18 de junio de 2020 | Ahora puede configurar cualquier modelo de atribución en IQ [!UICONTROL de] atribución para incluir puntos de contacto de hasta 90 días antes del período de tiempo de sistema de informes. Esto generalmente aumenta la precisión de atribución de eventos que se producen al principio del período de sistema de informes teniendo en cuenta las interacciones que se produjeron en el mes o meses anteriores. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| Funciones de proyecto para proyectos compartidos de Workspace | 18 de junio de 2020 | Al compartir un proyecto de Workspace, ahora puede colocar destinatarios en una de las tres funciones del proyecto, según la experiencia del proyecto que desee que tengan: Editar, Duplicado y Vista. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Proyectos de Workspace solo de Vista | 18 de junio de 2020 | Los proyectos de Workspace se pueden compartir solo con los usuarios como &quot;vistas posibles&quot;. Cuando un destinatario de Vista abre el proyecto compartido, recibe una experiencia de proyecto más restrictiva, sin carril izquierdo ni interacciones limitadas. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Capacidad para co-editar proyectos de Workspace | 18 de junio de 2020 | Los Destinatarios añadidos a la función &quot;Puede editar&quot; se pueden guardar en un proyecto que se haya compartido con ellos. Esto se extiende tanto a los administradores como a los no administradores. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Panel en blanco actualizado en Workspace | 18 de junio de 2020 | El panel en blanco de Workspace ahora incluye paneles y visualizaciones, lo que le ofrece una forma más fluida de elegir el flujo de trabajo de análisis que mejor se adapte a sus necesidades. |
| Dominios de origen disponibles en RDC de China | 18 de junio de 2020 | Permite a los clientes con un `.cn` dominio solicitar un dominio de origen para utilizarlo dentro de China continental. (Documentación disponible con la compra de la SKU &quot;Optimización del rendimiento de China&quot;). |
| Panel de perspectivas rápidas en Workspace | 25 de junio de 2020 | Quick Insights proporciona consejos a los no analistas y a los nuevos usuarios de Análisis Workspace para aprender a responder preguntas comerciales de forma rápida y sencilla. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| Panel Análisis para Destinatario en Workspace | 25 de junio de 2020 | El panel Análisis para Destinatario (A4T) permite analizar las actividades y experiencias de Adobe Destinatario en el área de trabajo de Análisis. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |

### Nuevas funciones en Customer Journey Analytics {#cust-journey}

| Función | [Disponibilidad](https://docs.adobe.com/content/help/es-ES/analytics/landing/an-releases.html)general: fecha de Destinatario | Descripción |
| -----------| ---------- |-----|
| Compatibilidad con la detección de anomalías | 18 de junio de 2020 | La detección de anomalías proporciona un método estadístico para determinar cómo ha cambiado una métrica determinada en relación con los datos anteriores. [Más información...](https://docs.adobe.com/content/help/es-ES/analytics/analyze/analysis-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html) |
| Funciones de proyecto para proyectos compartidos de Workspace | 18 de junio de 2020 | Al compartir un proyecto de Workspace, ahora puede colocar destinatarios en una de las tres funciones del proyecto, según la experiencia del proyecto que desee que tengan: Editar, Duplicado y Vista. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Proyectos de Workspace solo de Vista | 18 de junio de 2020 | Los proyectos de Workspace se pueden compartir solo con los usuarios como &quot;vistas posibles&quot;. Cuando un destinatario de Vista abre el proyecto compartido, recibe una experiencia de proyecto más restrictiva, sin carril izquierdo ni interacciones limitadas. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Capacidad para co-editar proyectos de Workspace | 18 de junio de 2020 | Los Destinatarios añadidos a la función &quot;Puede editar&quot; se pueden guardar en un proyecto que se haya compartido con ellos. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |

### Nuevas funciones de [!UICONTROL Media Analytics] {#media-aa}

Fecha de actualización: **29 de mayo de 2020**

**Seguimiento del estado del reproductor:** Los clientes de [!UICONTROL Media Analytics] pueden capturar la interacción del visor durante la reproducción mediante un conjunto estándar de variables de solución para la pantalla completa, los subtítulos opcionales, el silencio, la imagen en imagen y el enfoque. También tiene la flexibilidad para crear estados de reproductor personalizados. Las variables de seguimiento de estado del reproductor ahora están disponibles para el sistema de informes en [!UICONTROL Analysis Workspace]. Esta función requiere uno de los siguientes elementos:

* Media [!DNL JavaScript] SDK 3.0 o superior
* Para usar con el SDK [!DNL Adobe Experience Platform] (AEP):
   * [!UICONTROL Extensión de Media Analytics] (para la Web): [!UICONTROL Adobe Media Analytics] (SDK 3.x) para audio y vídeo v1.0 o superior
   * [!UICONTROL Extensión de Media Analytics] (para móviles): [!UICONTROL Adobe Media Analytics para audio] y vídeo v2.0 o superior
* [!UICONTROL Colección de medios]

Consulte [Acerca del seguimiento del estado del reproductor](https://docs.adobe.com/content/help/es-ES/media-analytics/using/player-state-tracking/player-state-overview.html).

### Adobe Analytics Fixes {#aa-fixes}

* Se ha corregido un problema que provocaba que los segmentos con búsquedas multibyte para determinados grupos de informes no coincidieran con nada. Ahora coincidirán con las cadenas correctas. AN-220043
* Se ha corregido un problema con el filtro de elementos en Informes y análisis, que no funcionaba. AN-206132
* Se corrigió el tiempo de respuesta lento en la interfaz de usuario de Proyectos programados. AN-214837
* Se ha corregido un problema con la API de Sistema de informes de Analytics 2.0 que provocaba un error de intervalo de fechas. AN-215087
* Se corrigió un caso en el cual la instancia/visita/visitante no se contaba en el denominador de las métricas de tiempo empleado. Esto sucedería cuando una visita individual sin valor para la dimensión (por ejemplo, Pagename) continuaba en el mismo segundo. AN-211074
* Se ha corregido un problema que impedía a los usuarios acceder a los proyectos de Workspace que se compartían con ellos. AN-217561
* Se ha solucionado el problema por el que el Generador de reglas de clasificación no clasificaba las claves. AN-221538
* Se corrigió un problema con el uso de llamadas al servidor que no sistema de informes ningún dato de uso. AN-210452
* Se han solucionado problemas con segmentos publicados de Adobe Analytics que faltaban datos en AAM. AN-220208, AN-220659
* Se ha corregido un problema con los informes que mostraban datos, pero los registros de fuentes de datos indicaban &quot;Sin datos del almacén de datos&quot;. AN-220784, AN-220858
* Se han corregido problemas que evitaban que se iniciara la Análisis ad hoc desde el `experiencecloud.com` dominio. AN-219680, AN-221629
* Se han corregido problemas con el uso de la tecla de acceso directo &quot;Ctrl (o Comando) + C&quot;. AN-221101, AN-221537
* Se ha corregido un problema con la página de habilitación de Mapa de Actividad. AN-222029, AN-221242
* Se ha corregido un problema que impedía añadir un punto de contacto en medio de una visualización de visitas en el orden previsto. AN-221648

#### Correcciones adicionales de Adobe Analytics

AN-218269; AN-218455; AN-218492; AN-219888; AN-220447; AN-220546; AN-220788; AN-220866; AN-221165; AN-221545; AN-221712; AN-221832; AN-221853; AN-222000; AN-222505; AN-222559

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación o actualizada | Descripción |
| -----------| ---------- | ---------- |
| Migración al dominio de producto unificado | Fecha de entrada en vigor: 28 de mayo de 2020 | La migración a un dominio de producto unificado para Adobe Analytics, que comenzó en enero de 2020, finalizó el 28 de mayo de 2020. While Adobe Analytics works to remove all `omniture.com` domain references from its architecture, it is important to allowlist `omniture.com` as a third-party cookie. En breve, cuando la migración completa de la arquitectura se complete, le notificaremos mediante las notas de la versión. A partir de entonces, ya no será necesario incluir el dominio en la lista de admitidos. [A continuación](https://helpx.adobe.com/es/analytics/kb/adobe-ip-addresses.html) se muestra una lista completa de las direcciones IP y los dominios recomendados que debe permitir.<br>Si su organización bloquea las cookies de terceros, póngase en contacto con el Servicio de atención al cliente para recuperar el acceso a Adobe Analytics. |
Si su organización bloquea las cookies de terceros, póngase en contacto con el Servicio de atención al cliente para recuperar el acceso a Adobe Analytics.
|Nueva página de aterrizaje predeterminada de Adobe Analytics|Fecha de entrada en vigor: 18 de junio de 2020|El 18 de junio de 2020, la página de aterrizaje predeterminada para Adobe Analytics cambiará de Informes a Espacio de trabajo. Este cambio se producirá para todos los usuarios que no hayan establecido previamente una página de aterrizaje personalizada.|
|Lista de permitidos de tecnología de terceros|12 de marzo de 2020 (fecha de entrada en vigor)|Adobe Analytics ha comenzado a aprovechar las tecnologías de terceros para la administración de la implementación de funciones y la compatibilidad con el producto. Las siguientes direcciones URL deben agregarse a las listas de permisos necesarias para el cortafuegos de red a fin de garantizar el acceso completo a las funciones:<ul><li>Perspectiva: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul>|
|Redundancia mejorada para la disponibilidad del espacio de trabajo de Análisis|21 de mayo de 2020|Para garantizar la disponibilidad del espacio de trabajo de Análisis, agregamos un CDN secundario (Red de Envío de contenido) para una redundancia mejorada. Las siguientes direcciones URL deben agregarse a las listas blancas necesarias de cortafuegos de red:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul>|
|Cambio en la forma en que se calculan las [!UICONTROL entradas y salidas] en el [!UICONTROL espacio de trabajo]|7 de abril de 2020|En el espacio de trabajo [!UICONTROL de]Análisis, a partir de marzo de 2020, hemos cambiado la forma en que el valor _Ninguno_ interactúa con las [!UICONTROL entradas y salidas]. Dado que ahora puede activar y desactivar el valor _Ninguno_ en [!UICONTROL Analysis Workspace], se aplica el valor _Ninguno_ después de la entrada o salida, cuando se solía aplicar antes (para eVars). Por ejemplo, supongamos que una primera visita no tiene valor para eVar, pero la segunda visita sí lo tiene. En [!UICONTROL Reports &amp; Analytics], se mostrará como _Sin especificar_ en la entrada, pero en [!UICONTROL Analysis Workspace], se mostrará como el valor de la segunda visita.|
|EOL of **[!UICONTROL Dashboard Archive]**|March 27, 2020|The **[!UICONTROL View Archive]** setting under **[!UICONTROL Manage Dashboards]** in [!UICONTROL Reports &amp; Analytics] will no longer be available as of October, 2020.|
|Fin de vida - API heredadas de Analytics|9 de enero de 2020|En noviembre de 2020, los siguientes servicios de API heredadas de Analytics llegarán a su fin de vida útil y se cerrarán. Las integraciones actuales creadas con estos servicios dejarán de funcionar. <ul><li>API de Analytics 1.3</li><li>API de Analytics SOAP 1.4</li><li>Autenticación OAuth heredada (OAuth y JWT)</li></ul>Hemos creado las [Preguntas frecuentes del fin de la vida útil de la API heredada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ayudarle a responder a sus preguntas y proporcionar instrucciones sobre cómo proceder. Las integraciones de API que emplean estos servicios pueden migrar a las [API de REST 1.4 de Analytics](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o a las [API de Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Las cuentas heredadas de OAuth pueden migrar a una cuenta de integración de Analytics [Adobe IO](https://console.adobe.io/home?mv=email), que puede utilizarse para acceder tanto a las API de Analytics 1.4 como a las API de Analytics 2.0.|
|San Jose FTP Broker End for London y Singapore|Julio de 2020|Para los clientes en Londres y Singapur, ya no admitiremos la intermediación de datos entre Londres o Singapur y el centro de datos de San José [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, utilice [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Singapur, utilice [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul>|
|EOL de Análisis ad hoc|6 de agosto de 2018|Adobe anunció la intención de una Análisis ad hoc al final de su vida útil. La fecha se hará pública una vez que esté disponible. Para obtener más información, consulte [Descubrir Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/).|

### [!DNL AppMeasurement] {#appm}

Consulte [Notas de la versión de AppMeasurement para JavaScript](https://docs.adobe.com/content/help/es-ES/analytics/implementation/appmeasurement-updates.html). La versión 2.20.0 se publicó 5 de marzo de 2020.

### Nuevos tutoriales de Analytics {#tutorials-analytics}

| Contenido | Descripción |
| -----------| ---------- |
| [Plantilla de tutorial de formación en Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | El tutorial de formación de [!UICONTROL Analysis Workspace] le guía a través de la terminología común y los pasos para crear su primer proyecto en [!UICONTROL Workspace]. |
| [Incorporación de comparaciones de meses y años anteriores con tendencias](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | Aprenda a aplicar intervalos de fechas personalizados para crear comparaciones de tendencias mensuales y anuales para cualquier métrica en [!UICONTROL Analysis Workspace]. |
| [Extensión de modo oscuro para Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | Active la extensión oscura de Reader Chrome para oscurecer Analysis Workspace. |
| [Extensión de cuentagotas de color para definir paletas personalizadas](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | Aprenda a utilizar la extensión ColorPick EyeDropper Chrome para encontrar fácilmente los valores hexadecimales que necesita para una paleta de colores personalizada en sus proyectos de [!UICONTROL Workspace]. |

#### Recursos de ayuda de Analytics

* [Tutoriales de Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Documentación del producto de Adobe Analytics](https://docs.adobe.com/content/help/es-ES/analytics/landing/home.html)

## ![Icono](/assets/audience-manager.png) Audience Manager {#aam}

Nuevas funciones, correcciones, documentación y tutoriales en Audience Manager.

### Actualizaciones de la interfaz de usuario

Audience Manager está publicando actualizaciones en el dominio y en la barra de encabezado para mejorar su experiencia y unificarse con otras aplicaciones de Experience Cloud.

* Es más fácil cambiar entre las organizaciones o a otra aplicación.
* Se ha mejorado la ayuda del usuario, que incluye artículos destacados y vídeos pertinentes al contexto en el menú Ayuda.
* Posibilidad de proporcionar comentarios sobre Experience Platform y los tickets de compatibilidad con archivos.
* Un nuevo patrón de URL más sencillo. Actualice los marcadores a la nueva dirección URL: `experience.adobe.com/audience-manager`.

Estas actualizaciones solo están disponibles para los usuarios que inicien sesión con un Adobe ID. Para cambiar a un inicio de sesión con Adobe ID, consulte [Administrar usuarios y productos de Experience Cloud](https://docs.adobe.com/content/help/es-ES/core-services/interface/manage-users-and-products/admin-getting-started.html).

### Nuevas funciones y correcciones en Adobe Audience Manager

| Función | Descripción |
| -----------| ---------- |  
| [Hoja de cálculo de herramientas de administración masiva (BAAAM)](https://docs.adobe.com/content/help/es-ES/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | Hemos cargado una nueva hoja de cálculo de herramientas de administración masiva que: <br><br><ul><li>Permite la lista de subcarpetas en la jerarquía de características (AAM-51528)</li><li>Recupera las métricas cuando se le solicitan características asociadas a ID de CRM (ID de varios dispositivos) (AAM-52135)</li><li>Corrige un problema de codificación de idioma para los caracteres coreanos (AAM-AAM-54006)</li></ul> |

**Correcciones**

* Se ha corregido un problema en el que los informes de tendencias agotaban el tiempo de espera de las carpetas con una gran cantidad de características. (AAM-54457)
* Se ha corregido un problema en el que los clientes no podían ver el [!UICONTROL generador de expresiones] en el flujo de trabajo de creación/edición de características. (AAM-54255)
* Se ha corregido un problema en el que los mensajes de error en la interfaz de usuario se mostraban solo durante un breve periodo, y desaparecían antes de que los clientes tuvieran la oportunidad de leerlos. Esto ocurría, por ejemplo, al intentar eliminar un segmento asignado a un destino. (AAM-54031)
* Se ha corregido un problema en el que los clientes que ya no usaban [!UICONTROL Audience Marketplace] recibían correos electrónicos de facturación mensuales. (AAM-54602)
* Se ha corregido un problema en el que los clientes que hacían clic en ciertas características desde otras ubicaciones en la interfaz de usuario veían vínculos rotos en lugar de características. (AAM-54768)
* Se ha corregido un problema en el que, en el modo de edición de expresión de características, se actualizaba la página y se perdía la expresión de características al presionar INTRO. (AAM-54210)
* Varias mejoras de accesibilidad en toda la interfaz de usuario. (AAM-47781, AAM-49075, AAM-49360, AAM-49361, AAM-49376, AAM-50432, AAM-52550, AAM-54660).

### Nuevos tutoriales del Audience Manager {#tutorials-aam}

| Contenido | Descripción |
| -----------| ---------- |  
| [Explicación de los términos y conceptos básicos de Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | En este vídeo, se explican algunos de los términos y conceptos básicos que le permiten empezar a trabajar en el Audience Manager, como las señales, las características, los segmentos, etc. |
| [Explicación del flujo de datos en el Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | Este vídeo le ayuda a comprender el Adobe Audience Manager, ya que describe el flujo de datos dentro y fuera de la aplicación, y a través de esta. |
| [Audience Manager: información general de un DMP](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | Comprenda los principales desafíos con la personalización entre canales y cómo Adobe Audience Manager impulsa el recorrido del cliente. Además, sepa qué tipos de datos se pueden incorporar en el Audience Manager e identifique a los socios de ecosistema de tecnología de publicidad integrados con el Audience Manager. |
| [Casos de uso de Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | En este vídeo identificamos cuatro casos de uso comunes del Audience Manager y describimos las prácticas recomendadas asociadas a ellos. |
| [Explicación de las métricas entre dispositivos en el Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | En este vídeo, analizamos la diferencia entre los perfiles de cada dispositivo y los perfiles entre dispositivos, y mostramos dónde coinciden los números de la interfaz de usuario con estos distintos tipos de perfiles. |
| [Explicación de las audiencias predictivas en Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | En este vídeo, analizamos cuáles son las audiencias predictivas del Audience Manager, presentamos detalles sobre cómo funcionan y señalamos casos de uso. |
| [Configurar e informar sobre Audiencias predictivas en Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | En este vídeo, se muestra la configuración de Audiencias predictivas en la interfaz del Audience Manager. También vemos los informes que muestran los resultados del modelo. |

## ![Icono](/assets/aem.png) Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Adobe Experience Manager (AEM). Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

### Actualizaciones de productos

* **AEM como un servicio en la nube**

   * Mejoras y correcciones en el procesamiento de recursos. El cuadro de diálogo de reprocesamiento de recursos proporciona al usuario más control, permite seleccionar un perfil de procesamiento específico y activar el flujo de trabajo posterior al procesamiento.
   * Mejoras en el rendimiento del ingreso de recursos de Dynamic Media.

### Autoayuda

* **Servicio de conversión automatizada de Forms: versión AFC-2020.03.1**

   Hay una nueva opción disponible al instalar el conector más reciente:

   **[!UICONTROL Detección automática de secciones lógicas]**: puede utilizar la opción [!UICONTROL Detectar secciones lógicas automáticamente] para soltar paneles de nivel de página (paneles basados en números de página) y crear paneles lógicos únicamente. También agrupa los campos que no pertenecen a ninguna sección con la sección lógica anterior, y los campos de una sección lógica se distribuyen en dos páginas adyacentes en una sola sección lógica. Por ejemplo, si algunos campos de una sección lógica están al final de la página uno y otros, al principio de la página dos, todos esos campos se agrupan en una sola sección lógica.

* **Formatos de imagen no compatibles en Dynamic Media**

   Información sobre los subtipos de formatos de archivo de imagen de trama que no se admiten en [!UICONTROL Dynamic Media].

   Consulte [Formatos de imagen de trama no admitidos en Dynamic Media](https://docs.adobe.com/content/help/es-ES/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media).

* **Fragmentos de contenido**

   Información sobre la [compatibilidad con fragmentos de contenido en la API HTTP de AEM Assets](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html), junto con la [personalización y ampliación de fragmentos de contenido](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html) y la [configuración de fragmentos de contenido para la representación](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html).

* **Comunidad de AEM Experience League**

   Conéctese con [AEM Experience League Community](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community): haga preguntas a los compañeros de aprendizaje y a los expertos en AEM, examine los hilos y comparta sus consejos y experiencia.

* **Newsletters de AEM**

   El newsletter de AEM de [!UICONTROL Experience League] está diseñado para ayudarle a ponerse al día con AEM, de modo que pueda obtener ventajas de inmediato. Esta es la newsletter más reciente:

   * [Volumen 30](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html): Experience Manager ya está disponible como servicio en la nube.
   * [Suscríbase](https://adobeeventsonline.com/AEM/2017/NL/Optin/) a la newsletter de Experience Insider.
   * Archivos de newsletter de Vista en la sección de [Recursos de AEM](https://helpx.adobe.com/es/support/experience-manager/6-5.html) de la página de Aprendizaje y asistencia de Adobe Experience Manager 6.5.

### Nuevos tutoriales de Experience Manager

| Contenido | Descripción |
| -----------| ---------- |  
| [Configuración del tiempo de ejecución de AEM local](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) se puede ejecutar localmente mediante el [!UICONTROL Jar de inicio rápido] del SDK de [!UICONTROL AEM as a Cloud Service]. Esto permite a los desarrolladores implementar y probar el código, la configuración y el contenido personalizados antes de comprometerlo con el control de código fuente e implementarlo en el entorno de [!UICONTROL AEM as a Cloud Service]. |
| [Introducción a AEM Assets](https://video.tv.adobe.com/v/33624?captions=spa) | Vídeo de introducción sobre cómo empezar a usar AEM Assets para usuarios empresariales. |
| [Esquemas de carpetas de metadatos](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | Los esquemas de carpeta de metadatos permiten a los usuarios administrar y revisar los metadatos asociados a las propias carpetas de recursos, en lugar de hacerlo directamente en los recursos. |
| [Etiquetado](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | Las etiquetas son una herramienta integral para administrar recursos en la jerarquía de carpetas de los recursos. El establecimiento de una taxonomía de etiquetado es fundamental para que los usuarios puedan descubrir y organizar los recursos en AEM. |
| [Perfiles de metadatos](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | Los perfiles de metadatos permiten la aplicación automática de metadatos predeterminados para los recursos de las carpetas de recursos. Esto ayuda a reducir la carga que supone la administración de metadatos para los usuarios de AEM y aumenta la coherencia de los metadatos. |
| [Esquemas de metadatos](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | Los esquemas de metadatos definen la interfaz que expone los metadatos de los recursos en AEM. En este vídeo se analiza la combinación de métodos utilizados para aplicar recursos. |

### Recursos adicionales

* [Notas de la versión de AEM as a Cloud Service](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [Documentación de AEM as a Cloud Service](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/landing/home.html)
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

* [Versión de Adobe Campaign Standard 20.3](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/es-ES/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/es-ES/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Panel de control de Campaign

| Función | Descripción |
| -----------| ---------- |  
| Administración de claves GPG | Instale o genere claves GPG en una instancia de marketing para cifrar los datos enviados desde Campaign y descifrar los datos entrantes. |
| Administración de certificados para subdominios CNAME | El panel de control ahora le permite renovar los certificados SSL de sus subdominios delegados con el método CNAME. |

### Nuevos tutoriales de Campaign

* Nuevos tutoriales de Campaign Standard

| Contenido | Descripción |
| -----------| ---------- |  
| [Panel de control: administración de registros TXT de Google](https://docs.adobe.com/content/help/es-ES/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | Obtenga información sobre cómo agregar registros de verificación del sitio TXT de Google a todos los subdominios utilizados para enviar correos electrónicos a direcciones de GMAIL con el panel de control de Campaign. |
| [Configurar y ejecutar un flujo de trabajo con la actividad de API externa](https://docs.adobe.com/content/help/es-ES/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | Obtenga información sobre cómo llamar a un extremo externo de API REST mediante la actividad de API externa. |
| [Tutorial sobre introducción a las notificaciones push para Android](https://docs.adobe.com/content/help/es-ES/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | Este tutorial explica los pasos necesarios para configurar las notificaciones push con Campaign Standard y la aplicación Android. |

* Nuevos tutoriales de Campaign Classic

| Contenido | Descripción |
| -----------| ---------- |  
| [Administración de datos en cantidad en Snowflake](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Sepa aprovechar el conector Snowflake en Adobe Campaign Classic. |
| [Panel de control: administración de registros TXT de Google](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | Obtenga información sobre cómo agregar registros de verificación del sitio TXT de Google a todos los subdominios utilizados para enviar correos electrónicos a direcciones de GMAIL con el panel de control de Campaign. |

### Recursos de ayuda de Campaign

* Adobe Campaign Standard: [Centro de ayuda](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/campaign-standard-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/release-notes/release-notes.html) - [Vídeos de procedimientos](https://docs.adobe.com/content/help/es-ES/campaign-standard-learn/tutorials/overview.html) - [Planificación de versiones](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/release-notes/release-planning.html) - [Últimas actualizaciones de la documentación](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Centro](https://docs.adobe.com/content/help/es-ES/campaign-classic/using/campaign-classic-home.html) de ayuda - [Notas de la versión](https://docs.adobe.com/content/help/es-ES/campaign-classic/using/release-notes/latest-release.html) - [Vídeos de procedimientos ](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [Últimas actualizaciones de la documentación](https://docs.adobe.com/content/help/es-ES/campaign-classic/using/documentation-updates.html)
* Panel de control de Adobe Campaign: [Documentación](https://docs.adobe.com/content/help/es-ES/control-panel/using/control-panel-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/es-ES/control-panel/using/release-notes.html)

## ![Icono](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Nuevas funciones de Advertising Cloud DSP](#adcloud-dsp)
* [Nuevas funciones en Advertising Cloud Search](#adcloud-search)

### Nuevas funciones de Advertising Cloud DSP {#adcloud-dsp}

| Función | Descripción |
| -----------| ---------- |
| [!UICONTROL Campaign Classic] y [!UICONTROL campañas beta] | La configuración de medición de IAS para fraude y seguridad de marca, que puede configurar de forma opcional para cada campaña, ahora incluye opciones para medir en el inventario VAST y VPAID. |
| [!UICONTROL Campañas beta] | Se mejoraron las visualizaciones de datos y los tiempos de carga de las páginas. |
|  | En todas las páginas, ahora puede descargar informes de Excel basados en los filtros y vistas actuales. |
|  | (En la versión del 22 de mayo) Las nuevas métricas incluyen métricas permanentes, Envío de intervalo actual, OTS de fecha específica. |
| [!UICONTROL Listas negras] | El sistema de pronóstico ahora utiliza automáticamente la lista negra a nivel del anunciante o de la cuenta. Los usuarios ya no necesitan pegar la lista negra en la configuración de colocación. |
| [!UICONTROL Ofertas de inventario] | (Beta cerrada) Un nuevo formulario simplificado le permite configurar, editar y solucionar rápidamente las ofertas de la plataforma de suministro (SSP) que no están disponibles en la bandeja de entrada del Deal ID. |
|  | Al aceptar un paquete de ofertas garantizadas mediante programación en la Bandeja de entrada de Deal ID, ahora se le advierte de que debe crear una colocación predeterminada para cada ID de acuerdo. |

### Nuevas funciones en [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Función | Descripción |
| -----------| ---------- |
| [!UICONTROL Campañas] | (Cuentas de Google Ads; servicio beta) Desde finales de mayo, Advertising Cloud Search podrá sincronizar datos para sus campañas de visualización de Google Gmail y sus campañas Google Smart Shopping con las conversiones de Google para el seguimiento y el sistema de informes. El servicio también le permitirá editar la configuración de la campaña y del grupo de publicidad para sus campañas existentes desde las vistas de campañas y grupos de publicidad. El servicio será opcional. Una vez que el servicio esté disponible en general, se aplicará una tarifa adicional.<br>Para obtener más información sobre el servicio, incluido el programa beta y el ámbito futuro, póngase en contacto con el administrador de cuentas de Adobe. |

## ![Icono](/assets/magento.png) [!DNL Magento] {#magento}

Para las notas de la versión de Magento, consulte:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Icono](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] es una aplicación completa para la gestión de clientes potenciales y para los especialistas en marketing B2B que buscan transformar las experiencias de los clientes al interactuar en todas las etapas de los viajes de compra complejos.

### Actualizaciones centrales de Marketo Engage

Consulte las [!DNL Marketo][notas de la versión](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) para obtener la información más reciente sobre la versión.

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
