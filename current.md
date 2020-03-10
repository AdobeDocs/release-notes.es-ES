---
title: Notas de la versión de Adobe Experience Cloud
description: Plantilla para notas de la versión de Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: b58151e366ba9aef341a8bd6742d6275d5cd8b30

---


# Acceso anticipado - Notas de la versión de Adobe Experience Cloud - Marzo de 2020

Nuevas funciones y correcciones en Adobe Experience Cloud.

>[!IMPORTANT]
>Esta página incluye contenido previo al lanzamiento de la nueva versión y está sujeta a cambios antes de su publicación planificada.

>[!NOTE]
>Para recibir notificaciones por correo electrónico sobre próximas versiones, suscríbase a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html). La nueva información publicada tras el lanzamiento se marcará con la fecha de publicación.

**Fecha de la versión: Marzo de 2020**

(Las fechas específicas de lanzamiento del producto pueden variar)

* [Estado del sistema de Adobe](#status)
* [Servicios principales e interfaz de Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Orquestación de viajes](#journey)
* [Mobile Services y Mobile SDK](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (vínculos a la ayuda de la solución)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (vínculos a la ayuda de la solución)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [Nueva documentación y tutoriales](#selfhelp)

¿Busca ayuda en casa? Consulte la documentación de [Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Estado del sistema de Adobe {#status}

[!UICONTROL El estado del sistema de Adobe] proporciona información detallada, actualizaciones de estado y notificaciones por correo electrónico sobre los productos en la nube de Adobe y las interrupciones y sesiones de mantenimiento de los servicios de Adobe. Puede comprobar el estado en [status.adobe.com](https://status.adobe.com/).

**Novedades**

* Con su Adobe ID, puede suscribirse a las notificaciones de eventos con más granularidad, hasta la oferta de productos y el nivel de complemento. Busque esta nueva funcionalidad en los productos de Experience Cloud, donde el proceso de suscripción automática muestra subofertas para los productos y servicios a los que desea suscribirse. Esta mejora debería reducir significativamente el volumen de notificaciones que recibe y hacer que las notificaciones sean más relevantes para los productos y las funciones que utiliza.  Empiece por [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuevas funciones y mejoras disponibles**

| Función | Descripción |
| -----------| ---------- |
| Autosuscripción personalizada personalizada por subofertas de producto | <ul><li>Suscripción automática por oferta de productos o complementos para productos de Experience Cloud.</li><li>Las notificaciones de eventos recibidas son relevantes para las preferencias de productos y ofertas de productos.</li></ul> |
| Experiencia personalizada basada en las preferencias del usuario | <ul><li>En las notificaciones por correo electrónico se utiliza la preferencia de zona horaria basada en la configuración del explorador.</li><li>Confirmación de correo electrónico enviada al suscribirse/cancelar la suscripción con todas las preferencias seleccionadas.</li></ul> |
| Mejor entrega de mensajes de eventos | <ul><li>El historial de eventos se ordena según las actualizaciones de eventos cronológicos.</li><li>Marca de hora de la resolución de eventos agregada a los problemas cerrados Mayor/Menor.</li></ul> |

## Servicios principales e interfaz de Experience Cloud {#ecloud}

Nuevas funciones y correcciones en la interfaz de Experience Cloud, incluida la administración y los servicios principales (atributos del cliente, audiencias, desencadenadores, cookies, etc.).

| Función | Fecha de la versión | Descripción |
| ----|----|---- |
| Herramienta de administración: ver detalles del usuario | 26 de febrero de 2020 | Los administradores pueden ver una lista de los usuarios de Experience Cloud que pueden ordenar y filtrar, y sus detalles en la nueva herramienta de administración. Los detalles del usuario incluyen el acceso al producto, las funciones y la información a la que accedió por última vez. Consulte la ayuda de la [herramienta de administración de Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) para obtener más información. |

### Dominio de producto unificado

Adobe está actualizando el encabezado de la interfaz y el dominio para unificar y mejorar el funcionamiento de las aplicaciones de Experience Cloud. Estas mejoras están diseñadas para mejorar sutilmente su experiencia. Estas mejoras no cambiarán los flujos de trabajo actuales.

Las actualizaciones incluyen:

* Nuevas URL de la solución: `experience.adobe.com/<application name>`:
   * Todos los productos adoptarán en algún momento este patrón de URL. Busque nuevas direcciones URL que entren en vigor durante el mes.
   * Compatibilidad con navegadores: Los exploradores admitidos son [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] y [!DNL Opera] (en sus versiones más recientes). **Nota:** Aunque la interfaz de Experience Cloud admite estos exploradores, es posible que las soluciones individuales no los admitan a todos. (Por ejemplo, [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) no es compatible con [!DNL Opera] y [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) no es compatible con [!DNL Safari]).
   * ([!DNL Safari] solo) El cambio de dominio puede causar problemas de cookies en [!DNL Safari]. Al anular la selección _Impedir el seguimiento entre sitios_ en las preferencias de privacidad de [!DNL Safari], se habilitarán las cookies entre dominios (y todas las experiencias entre sitios) y Experience Cloud funcionará en este nuevo dominio.
* Es más fácil cambiar entre las organizaciones o a otra aplicación.
* Ayuda del producto mejorada: [!UICONTROL Experience League] está integrada en el producto, por lo que una búsqueda de ayuda también incluye resultados de foros de la comunidad y contenido de vídeo. Este cambio simplifica el acceso a más contenido y le ayuda a sacar el máximo rendimiento de Experience Cloud. Además, puede hacer clic en **[!UICONTROL Ayuda]** > **[!UICONTROL Comentarios]** para informar sobre problemas o compartir sus ideas con Adobe.
* Notificaciones mejoradas: El menú desplegable [!UICONTROL Notificaciones] ahora tiene dos pestañas, una para sus propias notificaciones de productos y otra para los anuncios de productos globales.

**Nota:** La página [!UICONTROL Fuente] quedó obsoleta en enero de 2020. Busque un aviso de obsolescencia del producto.

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) help.

## Experience Platform {#platform}

Release notes for the [!UICONTROL Experience Platform,] [!UICONTROL Experience Platform Launch,] [!UICONTROL Identity Service,] and security bulletins.

* [Notas de la versión de Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Boletines de seguridad y avisos](https://helpx.adobe.com/security.html)   (Todos los productos de Adobe)

### Experience Platform Launch {#launch}

Consulte [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) para ver notas de la versión y documentación del producto.

## Orquestación de viajes {#journey}

Con Adobe Experience Platform, organice viajes individuales de clientes a escala en distintos canales de experiencia anticipando de forma inteligente las necesidades de cada individuo en tiempo real, dondequiera que su viaje lo lleve.

Se ha publicado la versión del primer trimestre. [Más información](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#q1-release---march-2020)

### Recursos adicionales

[Documentación](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html) : [Notas](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) de la versión: vídeos [de procedimientos](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## Mobile Services y Mobile SDK {#mobile}

**iOS v4.19.1**

* General: se ha resuelto un posible bloqueo cuando se incluyen enumeraciones de [!UICONTROL Swift] en los datos de contexto para las llamadas de seguimiento.
* [!DNL Target] - [!DNL Target] El ID de sesión ahora se agregará como parámetro de datos de contexto `a.target.sessionId` en la visita interna de [!UICONTROL Analytics para Target] enviada a Adobe Analytics.

**Android v4.18.1**

* [!DNL Target] - [!DNL Target] El ID de sesión ahora se agregará como parámetro de datos de contexto &quot;a.target.sessionId&quot; en la visita interna de [!UICONTROL Analytics para Target] enviada a Adobe Analytics.

## [!DNL Analytics] {#analytics}

Fecha de la versión: **12 de marzo de 2020**

Nuevas funciones y correcciones en Adobe Analytics:

* [Nuevas funciones, mejoras y correcciones en Adobe Analytics](#aa-features)
* [Avisos importantes para los administradores de Analytics](#aa-notices)
* [AppMeasurement](#appm)

Para obtener documentación del producto, consulte la sección [Ayuda de Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nuevas funciones, mejoras y correcciones en Adobe Analytics {#aa-features}

* **Varios grupos de informes en[!UICONTROL Analysis Workspace ]**: Ahora puede incluir datos de varios grupos de informes en un único proyecto de[!UICONTROL Analysis Workspace]para verlo en paralelo. Esta función se implementará para todos los clientes durante varias semanas.[Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Optimización** de audiencias de Experience Cloud: Esta función le permite publicar segmentos en Experience Cloud en un plazo de 8 horas (en lugar del tiempo de procesamiento de 48 horas anterior). [Más información...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **Analysis Workspace: plantilla** de tutorial de formación: Esta nueva plantilla estándar le guía por la terminología común y por los pasos para crear su primer análisis en Workspace. Está disponible como plantilla estándar en el modo [!UICONTROL Nuevo proyecto] y reemplaza el proyecto de muestra que existe actualmente para los usuarios nuevos que no tienen otros proyectos en su lista.

#### Correcciones

* Se ha corregido un problema en [!UICONTROL Informes y análisis] que impedía descargar `.xls` informes. Este problema afectaba a los clientes que usaban monedas distintas del dólar estadounidense y el euro. (AN-206541, AN-204008)
* La implementación de un nuevo shell solucionó varios problemas con los clientes relacionados con el cambio de organizaciones de Experience Cloud.(AN-200844, AN-186920)
* Se corrigió un problema en el cual al realizar un desglose en el elemento de línea _No especificado_ (o en algunos otros elementos de línea de informes) sin incluir _No especificado (Ninguno)_ en los filtros de búsqueda del desglose, no se obtendrían resultados en el desglose.
* Se corrigió un problema que se producía al usar una dimensión clasificada, el total de la métrica de entrada o salida no coincidía con el total del elemento de línea de un desglose.
* Se corrigió un problema en el cual los modelos de primer toque y último toque en IQ de atribución no calculaban correctamente el crédito para algunos elementos de línea en algunas dimensiones predeterminadas.
* Se corrigió un problema en el cual el desglose de una dimensión de fecha por otra dimensión de fecha devolvía resultados incorrectos.
* Se corrigió un problema en el cual a veces las métricas de entrada o salida se contaban incorrectamente al aplicarse a &quot;No especificado&quot; en un informe de dimensión clasificado.

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación   o actualizada | Descripción |
| -----------| ---------- | ---------- |
| Configuración EOL de nivel **[!UICONTROL de]** conversión | 3 de marzo de 2020 | El ajuste de Nivel [de](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) conversión que no funciona en Herramientas **[!UICONTROL de]administración > Grupos[!UICONTROL de]informes > Configuración[!UICONTROL de cuenta]** general se eliminará de la interfaz de usuario el 12 de marzo de 2020. |
| EOL del archivo de **[!UICONTROL tableros]** | 3 de marzo de 2020 | La configuración **[!UICONTROL Ver archivo]** en **[!UICONTROL Administrar tableros]** en [!UICONTROL Informes y análisis] ya no estará disponible a partir del 12 de marzo de 2020. |
| Finalización de la compatibilidad con TLS 1.1 | 3 de octubre de 2019 | A partir del 31 de marzo de 2020, Adobe Analytics dejará de ofrecer soporte para TLS 1.1. Este cambio es parte de nuestro trabajo para mantener los estándares de seguridad más altos e impulsar la seguridad de los datos del cliente. |
| Nuevo dominio de Adobe Analytics | 18 de diciembre de 2019 | El 16 de enero de 2020, Adobe Analytics empezará a pasar a un nuevo dominio: `https://experience.adobe.com/analytics.`<br>**Nota:** Este cambio se aplica a todos los usuarios que acceden a Analytics con su Adobe ID o Enterprise ID.<ul><li>Este cambio de dominio puede provocar problemas con las cookies al cargar Analytics en Safari. Al anular la selección _Impedir el seguimiento entre sitios_ en las preferencias de privacidad de , se habilitarán las cookies entre dominios (y todas las experiencias entre sitios) y Analytics funcionará en este nuevo dominio de Adobe Experience Cloud. [!DNL Safari] You can use other browsers without issue because this affects only [!DNL Safari] users.</li><li>El cambio de dominio puede hacer que [!UICONTROL Activity Map] deje de funcionar para algunos clientes [en casos específicos](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fin de vida útil: API heredadas de Analytics | 9 de enero de 2020 | En noviembre de 2020, los siguientes servicios de API heredadas de Analytics llegarán a su fin de vida útil y se cerrarán. Las integraciones actuales creadas con estos servicios dejarán de funcionar. <ul><li>API de Analytics 1.3</li><li>API de Analytics SOAP 1.4</li><li>Autenticación OAuth heredada (OAuth y JWT)</li></ul>Hemos creado las [Preguntas frecuentes del fin de la vida útil de la API heredada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ayudarle a responder a sus preguntas y proporcionar instrucciones sobre cómo proceder. Las integraciones de API que emplean estos servicios pueden migrar a las [API de REST 1.4 de Analytics](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o a las [API de Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Las cuentas heredadas de OAuth pueden migrar a una cuenta de integración de Analytics [Adobe IO](https://console.adobe.io/home?mv=email), que puede utilizarse para acceder tanto a las API de Analytics 1.4 como a las API de Analytics 2.0. |
| Fin de la administración de datos en el centro de datos de San José para Londres y Singapur | Julio de 2020 | For customers in London and Singapore, we will no longer support brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |

### [!DNL AppMeasurement] {#appm}

Consulte [Notas de la versión de AppMeasurement para JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). La versión 2.20.0 se publicó el 5 de marzo de 2020.

## Audience Manager {#aam}

Nuevas funciones y actualizaciones de Audience Manager:

### Fixes and improvements {#aam-fixes-and-improvements}

* Se corrigió un error en el cual los clientes no podían actualizar el nombre del segmento debido a que faltaba un permiso RBAC [!UICONTROL VIEW_ALL_DESTINATIONS]. No se debe necesitar el permiso [!UICONTROL VIEW_ALL_DESTINATIONS] para actualizar un segmento. Para obtener más información sobre los permisos de RBAC, consulte [Administración (controles RBAC)](https://docs.adobe.com/help/en/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions). (AAM-52760)
* Se ha corregido un error en el Explorador [de](https://docs.adobe.com/help/en/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html) datos por el que algunos clientes no podían ver el contenido en la sección de información básica ni en los operadores del creador de expresiones al crear características basadas en señales del Explorador [!UICONTROL de] datos. (AAM-53130)
* Se corrigió un error en el cual algunos clientes no podían cargar la interfaz de [!UICONTROL Audience Marketplace] . (AAM-52070)
* Se ha corregido un error en la API [!UICONTROL de] segmentos por el que, debido a algunos segmentos sin descripción, la interfaz se bloqueaba cuando los usuarios intentaban acceder a esos segmentos y los usuarios tenían que desplazarse fuera de esa página. (AAM-53071)
* Varias mejoras de accesibilidad en toda la interfaz. (AAM-48952, AAM-48969, AAM-48979, AAM-48993, AAM-49048, AAM-49057, AAM-49058,AAM-493 92)

## Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Adobe Experience Manager (AEM). Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

### Actualizaciones de productos

* **AEM 6.5.4.0** AEM 6.5, Service Pack 4.0 (6.5.4.0 publicado el 5 de marzo de 2020) es una actualización importante que incluye nuevas funciones, mejoras clave para el cliente, rendimiento mejorado, estabilidad y seguridad, publicadas desde la disponibilidad general de AEM 6.5 en abril de 2019.
   * [Novedades de Adobe Experience Manager 6.5, Service Pack 4](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
   * [Notas de la versión](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Entregables de la versión de AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

   AEM 6.4, Service Pack 8.0 (6.4.8.0 publicado el 5 de marzo de 2020) es una actualización importante que incluye correcciones clave de cliente realizadas tras la disponibilidad general de AEM 6.4 en abril de 2018.
   * [Notas de la versión](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versiones de AEM Forms CFP](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 8 (6.3.3.8 publicado el 5 de marzo de 2019) es una actualización importante que incluye correcciones clave de cliente realizadas tras la disponibilidad general de AEM 6.3 en abril de 2017.
   * [Notas de la versión](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versiones de AEM Forms CFP](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal**

   AEM Assets Brand Portal 6.4, Service Pack 6 (6.4.6 publicado el 5 de marzo de 2020) cambia la forma en que AEM Assets se configura con [!UICONTROL Brand Portal.] Además, la versión incluye otras mejoras y correcciones de errores.
   * [Notas de la versión](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### Autoayuda

* **AEM como servicio de nube: permisos basados en funciones**

   Cloud Manager tiene funciones preconfiguradas con los permisos adecuados. Cada una de las funciones tiene permisos específicos, tareas preconfiguradas o permisos asociados a cada función. El tema de la Ayuda de permisos [basados en](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html) roles identifica las funciones disponibles y las funciones que pueden ejecutarlas.

* **AEM como servicio de nube: despachante**

   Las secciones de invalidación [de caché de Dispatcher y CDN](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn) y Dispatcher [](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation) Explícit se actualizaron para aclarar las opciones disponibles y cómo funcionan.

* **Configuración de AEM Assets con Brand Portal**

   Recursos AEM ahora se configura con [!UICONTROL Brand Portal] a través de Adobe I/O, que obtiene un testigo IMS para la autorización del inquilino de Brand Portal. Anteriormente, se configuraba en la interfaz clásica mediante la puerta de enlace OAuth [!UICONTROL heredada.]
Consulte [Configuración de AEM Assets con Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html).

* **AEM como servicio de nube: recorte inteligente en Dynamic Media**

   Hay una nueva opción disponible en AEM como servicio de nube cuando se trabaja con Smart Crop en el componente Dynamic Media:

   **Activar coincidencia** de proporción: seleccione esta opción para permitir que Dynamic Media elija una representación de recorte inteligente que mejor se ajuste a la proporción de aspecto de la imagen original.
Consulte [Al trabajar con recorte](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop)inteligente.

### Comunidad

* **Seminarios web de AEM Skill Builder**

   * Sitios AEM: a partir del 17 de marzo de 2020, aprenderá los componentes básicos de la creación de contenido y los conceptos y operaciones fundamentales de los sitios AEM. [Regístrese ahora](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register).
   * Recursos AEM: a partir del 19 de marzo de 2020, perfeccione su experiencia en la gestión de activos digitales, además de conocer los conceptos básicos del portal de marcas, los medios [!UICONTROL dinámicos,] [!UICONTROL Asset Link,] etc. [Regístrese ahora](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register).

### Recursos adicionales

* [AEM como un servicio en la nube](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [Página de inicio de Learn &amp; Support de AEM 6.5](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Página de inicio de Learn &amp; Support de AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Página de inicio de Learn &amp; Support de AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Página de inicio de Learn &amp; Support de AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guía del usuario de Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Versiones anteriores de la documentación de AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Inicio de la Ayuda de Dynamic Media Classic](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Notas de la versión de Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notas de la versión de Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign permite entregar, de forma intuitiva y automatizada, mensajes privados a través de canales de marketing en línea y sin conexión. Ahora puede anticipar los deseos de los clientes mediante experiencias basadas en sus hábitos y preferencias.

### Campaign Classic

* [Actualización de Campaign Classic 19.1.4](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Recursos adicionales

* Adobe Campaign Standard: [Documentación](https://helpx.adobe.com/support/campaign/standard.html) - [Notas de la versión](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Planificación de lanzamiento](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentación](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de la versión](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Panel de control de Adobe Campaign: [Documentación](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Actualizado el 10 de febrero de 2020, para la versión del 8 de febrero:

| Ver | Función |
|------|---------|
| [!UICONTROL Portafolios] | You can now add [!DNL Yahoo!] Japan Display Network (YDN) campaigns to portfolios to optimize the campaign budgets and ad group-level bids. La misma oferta se aplica a todos los anuncios de un grupo de anuncios. Los datos de las campañas de la red de visualización de Japón se incluyen en las simulaciones del portafolio. |
| [!UICONTROL Buscar] > [!UICONTROL Hojas de edición masiva] | Ahora puede crear, editar y eliminar anuncios de búsqueda interactivos (RSA) de Google mediante hojas de edición en bloque. Antes, la compatibilidad solo estaba disponible a través de la interfaz de administración de campañas estándar en **[!UICONTROL Buscar]** > **[!UICONTROL Campañas]** |
| [!UICONTROL Búsqueda] > [!UICONTROL Campañas, Informes] | Las métricas de prominencia de Google Ads `Impr. (Abs. Top) %` y `Impr. (Top) %` ahora están disponibles en todos los informes básicos y en las vistas de administración de campañas a nivel de entidad, excepto en los informes de grupos de productos de compras, en los informes de uso compartido de [!UICONTROL impresiones diarias de campaña] y de [!UICONTROL uso compartido de impresiones diarias de palabras clave], y en las vistas de etiquetas y restricciones. |

## [!DNL Magento] {#magento}

Para las notas de la versión de Magento, consulte:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] es una solución completa para la gestión de clientes potenciales y para los especialistas en marketing B2B que buscan transformar las experiencias de los clientes al interactuar en todas las etapas de los viajes de compra complejos.

### Actualizaciones centrales de Marketo Engage

Fecha de publicación: 21 de febrero de 2020

* **Microsoft Dynamics _Cambio de propietario en Microsoft_ Acción de flujo**: cambie un cliente potencial o un contacto directamente desde Marketo Engage.
* **Mejoras en las llamadas API:**
   * API de User Management
   * API de esquemas de objetos personalizados
   * API de reglas de redireccionamiento de páginas de aterrizaje
* **Almacenamiento en caché del descriptor de formulario:** mejoras en las páginas de aterrizaje y en los formularios.

Consulte las [!DNL Marketo] notas de la versión de [febrero de 2020](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) para obtener más información.

### Próximas funciones

Las siguientes funciones se lanzarán durante todo el trimestre:

| Función | Descripción |
|------|---------|
| [!DNL Bizible] | <ul><li>Nueva segmentación basada en cuentas</li><li>Almacenamiento de filtros específicos del tablero</li><li>Exportación de tableros Bizible en PDF</li></ul> |
| Conexión de ventas | Actualizaciones y mejoras de la ventana de composición y del centro de comandos |

### Anuncios

**Centro de éxito de Marketo Engage:** lanzamiento en febrero de 2020. El Centro de éxito es un centro de ayuda integrado en el producto que le permite buscar en la Documentación del producto, la Comunidad, las guías de inicio prácticas, el contenido de adopción de acceso y mucho más. Nota: Esta función se lanzará como una versión beta en ANZ y se comercializará en Norteamérica más adelante en el trimestre.

### Degradaciones

* **Parámetro &quot;_method&quot; de Asset API:** a partir de septiembre de 2020, los puntos de conexión de Asset API ya no aceptarán &quot;_method&quot; para pasar parámetros de consulta en un cuerpo de POST para omitir las limitaciones de longitud de URI.
* **Degradación de compatibilidad con Internet Explorer:** a partir de la versión del 31 de julio de 2020, la interfaz de usuario de Marketo Engage dejará de ser compatible con Internet Explorer.

Para ver las notas de la versión acumulativas e históricas, consulte [Notas de la versión de Marketo](https://docs.marketo.com/x/CgA6Ag).

## Nueva documentación y tutoriales {#selfhelp}

Artículos y vídeos de autoayuda nuevos y recientes. <!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

| Solución | Contenido | Descripción |
|----------| -----------| ---------- |  
| [!UICONTROL AEM Commerce] | Vídeo: [Creación de varias categorías y páginas de producto](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md) | Obtenga información sobre cómo crear un proyecto CIF de Adobe Experience Manager (AEM) mínimo como punto de partida para proyectos de clientes que utilizan componentes principales de CIF. Aplique un tema y estilo CSS a los componentes e inspeccione un nuevo proyecto de AEM CIF, generado por el arquetipo. Además, descubra cómo se organizan CSS y JavaScript utilizados por los componentes principales de CIF. |
| [!UICONTROL Formularios de AEM] | Artículo: [Autenticar con AEM Author mediante OKTA](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | Obtenga información sobre cómo configurar la aplicación en el portal OKTA y sobre la configuración que suele utilizar para registrar una nueva aplicación. |
| [!UICONTROL AEM Commerce] | Tutorial: [Personalización de los componentes principales de CIF](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md) | Revise varios puntos de extensión diferentes proporcionados por los componentes principales de CIF y AEM en general. Los componentes principales de CIF proporcionan un conjunto estándar de componentes de comercio que se pueden utilizar para acelerar un proyecto que integra las soluciones Adobe Experience Manager (AEM) y Magento. |
| [!DNL Adobe Campaign] - Destinos de audiencia | Video - [Create an audience...](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | Cree una audiencia en Campaign Standard mediante el Generador [!UICONTROL de segmentos de la plataforma de]experiencias de Adobe. Puede acceder a esta función directamente desde Adobe Campaign Standard mediante los módulos [!UICONTROL Audiencias] . |
| [!DNL Adobe Campaign] - Destinos de audiencia | Vídeo: [Activación de audiencias de la plataforma Adobe Experience en un flujo de trabajo de marketing](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | Obtenga información sobre cómo activar la Audiencia [!UICONTROL de consulta de servicios de] datos en un flujo de trabajo mediante la actividad [!UICONTROL Leer audiencia] . |
| [!DNL Adobe Campaign] | Tutorial: Notificación [push con Android](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) | Envíe notificaciones push personalizadas y segmentadas a dispositivos móviles iOS y Android. Este tutorial le guiará por los pasos necesarios para enviar notificaciones push desde Adobe Campaign y recibir estas notificaciones en su aplicación de Android. |
| [!DNL Adobe Campaign] | Vídeo: [Crear una notificación push](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | Cree una notificación push en Adobe Campaign Standard. Puede enviar notificaciones push personalizadas y segmentadas a dispositivos móviles iOS y Android. |
| [!DNL Adobe Campaign] - Conector de datos AEP | Vídeo: [Comprobar el estado de un trabajo de inserción de datos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) | Obtenga información sobre cómo comprobar el estado de un trabajo de inserción de datos y si los datos se han ingerido de Adobe Campaign Standard a Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Conector de datos AEP | Vídeo: [Modificación de la asignación de datos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) | Obtenga información sobre cómo comprobar el estado y modificar la asignación de datos. |
| [!DNL Adobe Campaign] - Conector de datos AEP | Vídeo: [Mapa de eventos de experiencia](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | Obtenga información sobre cómo asignar eventos de experiencia en Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Conector de datos AEP | Vídeo: [Asignar recursos personalizados](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) | Obtenga información sobre cómo asignar distintos tipos de datos entre Adobe Campaign Standard y Adobe Experience Platform. |
| [!DNL Adobe Campaign] - Conector de datos AEP | Vídeo: [Comprender el conector de datos de la plataforma Adobe Experience](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) | Obtenga información sobre cómo hacer que los datos estén disponibles en Adobe Experience Platform asignando datos XTK (datos ingestados en Campaign) a datos del modelo de datos de experiencia (XDM) en la plataforma Adobe Experience. |
| [!DNL Adobe Campaign] - Conector de datos AEP | Vídeo: [Asignar datos de tabla de inicio](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html) | Obtenga información sobre cómo asignar los datos iniciales y los perfiles de prueba con Adobe Experience Platform. |
| [!DNL Adobe Campaign]- Destinos de audiencia | Vídeo: [Cambiar la dimensión de segmentación de una entrega para una audiencia de plataforma](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html) | Descubra cómo cambiar la dimensión de segmentación de una entrega para una audiencia de plataforma fuera de la tabla de perfil principal en Adobe Campaign Standard. |
| [!DNL Adobe Campaign] | Video - [Gran administración de datos en Snowflake](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Aproveche el conector Snowflake de Adobe Campaign Classic. |
| [!DNL Adobe Campaign] - Destinos de audiencia | Artículo - Destinos [de audiencia (BETA) - Información general](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) | Descubra cómo aprovechar los datos de perfil centralizados y consolidados de la plataforma Adobe Experience Platform para campañas de marketing en Adobe Campaign Standard. |
| [!DNL Adobe Target] - SDK móvil | Tutorial: [Personalización de las experiencias de la aplicación con Adobe Target](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) | Implemente Adobe Target en su propia aplicación de Android. Valide la configuración del SDK de Mobile Services e implemente [!DNL Target] solicitudes como la recuperación previa de contenido, el bloqueo de solicitudes y más. |
| Adobe Analytics | Vídeo: Supersesión de [Adobe Summit 2019](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) | Vea clips seleccionados de la &quot;súper sesión&quot; de alta tecnología en Summit 2019. |
| Adobe Analytics | Vídeo: [Introducción a las métricas calculadas en el análisis de viajes del cliente](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) | Conozca los aspectos básicos de la creación de métricas  calculadas en el análisis de viajes del [!UICONTROL cliente]. |
| Adobe Analytics | Vídeo: Supersesión de [Adobe Summit 2019](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html) | Vea clips seleccionados de la sesión de viajes y hospitalidad en la Cumbre 2019. |
| Adobe Analytics | Vídeo: Supersesión de [Adobe Summit 2019](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) | Consulte los clips seleccionados de la sesión de venta al por menor en la Cumbre 2019. |
| Adobe Analytics | Vídeo: Caso de uso [del cliente: El grupo de énfasis invierte en la experiencia del cliente para impulsar las ventas](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) | Vea cómo el grupo Accent utiliza Adobe Experience Cloud para crear experiencias digitales sin problemas. |
| Adobe Analytics | Vídeo: Caso de uso [del cliente: ServiceNow obtiene las perspectivas correctas para conectarse con posibles clientes](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) | Descubra cómo [!DNL ServiceNow] obtiene datos procesables de sus canales de mercadotecnia y aumenta el retorno de la inversión en la publicidad de búsqueda paga con Adobe Advertising Cloud y Adobe Analytics. |
| Adobe Analytics | Vídeo: [Adobe Analytics: es más que datos que inteligencia del cliente](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html) | Obtenga información sobre la mercadotecnia basada en datos y cómo llevar la madurez de los análisis desde los datos hasta las perspectivas y la acción. |
| Adobe Analytics | Vídeo: [Adobe Sensei y Adobe Analytics: versión ampliada](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html) | Vea las funciones clave de Adobe Analytics con tecnología de Adobe [!DNL Sensei,] como, por ejemplo, Detección de [!UICONTROL anomalías,] Análisis de [!UICONTROL contribución,] Alertas [!UICONTROL inteligentes,] [!UICONTROL Clúster,] IQ de  [!UICONTROL clúster,Modelado de propensión.] |
| Adobe Analytics | Vídeo: [Cómo puede Adobe Analysis Workspace cambiar su negocio](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | Descubra cómo puede realizar análisis específicos, análisis flexibles, análisis de cohorte y análisis de visitas en el orden previsto mediante [!UICONTROL Analysis Workspace]. También puede compartir el entorno de trabajo de análisis con todos los miembros de su empresa, y su función de arrastrar y soltar permite a todos analizar los datos fácilmente y obtener perspectivas rápidamente. |
| Adobe Analytics | Vídeo: Caso de uso [del cliente: El Home Depot innova través de la administración de la experiencia del cliente](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) | Descubra cómo [!DNL Home Depot] utiliza las soluciones de Adobe para crear la lealtad de la marca y la satisfacción del cliente con una experiencia de compra personalizada y personalizada. |
| Adobe Analytics | Presentación: [Explicación del análisis de viajes del cliente](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html) | Descubra cómo [!UICONTROL Customer Journey Analytics]de Adobe, un servicio de aplicaciones integrado en [!DNL Adobe Experience Platform], incorpora [!UICONTROL Analysis Workspace] en la plataforma de experiencias. Esta función permite el análisis multicanal en cualquiera de los conjuntos [!DNL Adobe Experience Platform] de datos. |
| Adobe Analytics | Vídeo: Atribución [entre canales en CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html) | Descubra cómo puede utilizar las visualizaciones para mostrar la atribución (dar crédito) a través de los canales en [!UICONTROL Customer Journey Analytics]. |
| Adobe Analytics | Artículo: Sugerencias [al cliente para continuar su viaje de aprendizaje de Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) | Conozca a tres clientes de Adobe que tienen consejos y trucos para obtener el máximo valor de Adobe Analytics. |
| Adobe Analytics | Vídeo: [Creación de visualizaciones multicanal en CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html) | Descubra cómo [!UICONTROL Customer Journey Analytics] le permite crear visualizaciones que incluyen datos de varios conjuntos de datos en varios canales, incluida la combinación de datos por visitante. |
| Adobe Analytics | Vídeo: [Mover las métricas calculadas de Adobe Analytics a los análisis de viajes del cliente](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) | Encontrará sugerencias para volver a crear las métricas [!UICONTROLC] calculadas de Analytics en Análisis de viajes [!UICONTROL del cliente]. |
