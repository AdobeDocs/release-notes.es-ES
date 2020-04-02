---
title: Notas de la versión de Adobe Experience Cloud
description: Plantilla para notas de la versión de Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: ht
source-git-commit: abf763ddf0ed4ae9d8df5b7dcef4e664db4cf682

---


# Notas de la versión de Adobe Experience Cloud: marzo de 2020

![Banner](/assets/experience-cloud-banner-3.png)

Nuevas funciones y correcciones en [!DNL Adobe Experience Cloud].

>[!IMPORTANT]
>Esta página incluye contenido previo al lanzamiento de la nueva versión y está sujeto a cambios antes de su publicación planificada.

>[!NOTE]
>Para recibir notificaciones por correo electrónico sobre próximas versiones, suscríbase a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html). La nueva información publicada tras el lanzamiento se marcará con la fecha de publicación.

**Fecha de la versión: Marzo de 2020**

Actualización más reciente: 11 de marzo de 2020

* [Estado del sistema de Adobe](#status)
* [Servicios principales e interfaz de Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) - Fecha de la versión: **12 de marzo de 2020**  (Contenido actualizado el 27 de marzo de 2020)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/es-ES/target/using/release-notes/target-release-notes.html) (vínculos a la ayuda de la solución)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/es/primetime/user-guide.html) (vínculos a la ayuda de la solución)
* [Nueva documentación y tutoriales](#selfhelp)

¿Busca ayuda en casa? Consulte la documentación de [Adobe Experience Cloud](https://docs.adobe.com/content/help/es-ES/experience-cloud/user-guides/home.html).

(Las fechas específicas de lanzamiento del producto pueden variar.)

## ![Icono](/assets/adobe.png) Estado del sistema de Adobe {#status}

[!UICONTROL El estado del sistema de Adobe] proporciona información detallada, actualizaciones de estado y notificaciones por correo electrónico sobre los productos en la nube de Adobe y las interrupciones y sesiones de mantenimiento de los servicios de Adobe. Puede comprobar el estado en [status.adobe.com](https://status.adobe.com/).

**Novedades**

* Con su Adobe ID, puede suscribirse a las notificaciones de eventos con una mayor granularidad, lo que permite llegar hasta la oferta de productos y el nivel de complementos. Busque esta nueva funcionalidad en los productos de Experience Cloud, donde el proceso de suscripción automática muestra subofertas de suscripción para los productos y servicios que le pueden interesar. Esta mejora debería reducir significativamente el volumen de notificaciones que recibe y hacer que las notificaciones sean más relevantes para los productos y las funciones que utiliza.  Empiece por [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuevas funciones y mejoras disponibles**

| Función | Descripción |
| -----------| ---------- |
| Autosuscripción personalizada por subofertas de producto | <ul><li>Autosuscripción por oferta de productos o complementos para productos de Experience Cloud.</li><li>Las notificaciones de eventos recibidas son relevantes de acuerdo con las preferencias y ofertas de productos.</li></ul> |
| Experiencia personalizada basada en las preferencias del usuario | <ul><li>En las notificaciones por correo electrónico se utiliza la preferencia de zona horaria basada en la configuración del explorador.</li><li>Confirmación de correo electrónico enviada al suscribirse/cancelar la suscripción con todas las preferencias seleccionadas.</li></ul> |
| Mejor entrega de mensajes de eventos | <ul><li>El historial de eventos se ordena según las actualizaciones de eventos cronológicos.</li><li>Marca de hora de la resolución de eventos agregada a los problemas cerrados de mayor y menor gravedad.</li></ul> |

## ![Icono](/assets/experience-cloud.png) Servicios principales e interfaz de Experience Cloud {#ecloud}

Nuevas funciones y correcciones en la interfaz de Experience Cloud, incluida la administración y los servicios principales (atributos del cliente, audiencias, desencadenadores, cookies, etc.).

| Función | Fecha de la versión | Descripción |
| ----|----|---- |
| Herramienta de administración: ver detalles del usuario | 26 de febrero de 2020 | Los administradores pueden ver una lista de los usuarios de Experience Cloud que pueden ordenar y filtrar, y sus detalles en la nueva herramienta de administración. Los detalles del usuario incluyen el acceso al producto, las funciones y la información a la que accedió por última vez. Consulte la ayuda de la [herramienta de administración de Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) para obtener más información. |

### Dominio de producto unificado

Adobe está actualizando el encabezado de la interfaz y el dominio para unificar y mejorar el funcionamiento de las aplicaciones de Experience Cloud. Estas mejoras están diseñadas para mejorar sutilmente su experiencia. Estas mejoras no cambiarán los flujos de trabajo actuales.

Las actualizaciones incluyen:

* Nuevas URL de la solución: `experience.adobe.com/<application name>`:
   * Todos los productos adoptarán en algún momento este patrón de URL. Busque nuevas direcciones URL que entren en vigor durante el mes.
   * Compatibilidad con navegadores: Los exploradores admitidos son [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] y [!DNL Opera] (en sus versiones más recientes). **Nota:** Aunque la interfaz de Experience Cloud admite estos exploradores, es posible que las soluciones individuales no los admitan a todos. (Por ejemplo, [Analytics](https://docs.adobe.com/content/help/es-ES/analytics/admin/sys-reqs.html) no es compatible con [!DNL Opera] y [Target](https://docs.adobe.com/help/es-ES/target/using/implement-target/before-implement/supported-browsers.html) no es compatible con [!DNL Safari]).
   * ([!DNL Safari] solo) El cambio de dominio puede causar problemas de cookies en [!DNL Safari]. Al anular la selección _Impedir el seguimiento entre sitios_ en las preferencias de privacidad de [!DNL Safari], se habilitarán las cookies entre dominios (y todas las experiencias entre sitios) y Experience Cloud funcionará en este nuevo dominio.
* Es más fácil cambiar entre las organizaciones o a otra aplicación.
* Ayuda del producto mejorada: [!UICONTROL Experience League] está integrada en el producto, por lo que una búsqueda de ayuda también incluye resultados de foros de la comunidad y contenido de vídeo. Este cambio simplifica el acceso a más contenido y le ayuda a sacar el máximo rendimiento de Experience Cloud. Además, puede hacer clic en **[!UICONTROL Ayuda]** > **[!UICONTROL Comentarios]** para informar sobre problemas o compartir sus ideas con Adobe.
* Notificaciones mejoradas: El menú desplegable [!UICONTROL Notificaciones] ahora tiene dos pestañas, una para sus propias notificaciones de productos y otra para los anuncios de productos globales.

**Nota:** La página [!UICONTROL Fuente] dejó de usarse en enero de 2020. Busque un aviso de obsolescencia del producto.

Para obtener documentación del producto, consulte la página de ayuda de [Experience Cloud](https://docs.adobe.com/content/help/es-ES/core-services/interface/experience-cloud.html).

## ![Icono](/assets/platform.png) Experience Platform {#platform}

Notas de la versión de [!UICONTROL Experience Platform], [!UICONTROL Experience Platform Launch], [!UICONTROL Identity Service], Journey Orchestration, Mobile Services y boletines de seguridad.

* [Notas de la versión de Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Organización de recorridos](#journey)
* [Mobile Services y Mobile SDK](#mobile)
* [Boletines de seguridad y avisos](https://helpx.adobe.com/es/security.html)     (Todos los productos de Adobe)

### Experience Platform Launch {#launch}

Consulte [Experience Platform Launch](https://docs.adobe.com/content/help/es-ES/launch/using/intro/release-notes/current.html) para ver notas de la versión y documentación del producto.

### Organización de recorridos {#journey}

Con Adobe Experience Platform, puede organizar los recorridos individuales de los clientes a escala en distintos canales de experiencia y adaptarse de forma inteligente a las necesidades y recorrido de cada usuario en tiempo real.

Se ha publicado la versión del primer trimestre. [Más información](https://docs.adobe.com/content/help/es-ES/journeys/using/release-notes/release-notes.html#q1-release---march-2020)

#### Recursos adicionales     para Journey Orchestration

[Documentación](https://docs.adobe.com/content/help/es-ES/journeys/using/journey-orchestration-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/es-ES/journeys/using/release-notes/release-notes.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services y Mobile SDK {#mobile}

**iOS v4.19.1**

* General: Se ha resuelto un posible bloqueo cuando se incluyen enumeraciones de [!UICONTROL Swift] en los datos de contexto para las llamadas de seguimiento.
* [!DNL Target]: El ID de sesión de [!DNL Target] ahora se agregará como parámetro de datos de contexto `a.target.sessionId` en la visita interna de [!UICONTROL Analytics-for-Target] enviada a Adobe Analytics.

**Android v4.18.1**

* [!DNL Target]: El ID de sesión de [!DNL Target] ahora se agregará como parámetro de datos de contexto “a.target.sessionId” en la visita interna de [!UICONTROL Analytics-for-Target] enviada a Adobe Analytics.

## ![Icono](/assets/analytics.png) [!DNL Analytics] {#analytics}

Fecha de la versión: **12 de marzo de 2020**

Nuevas funciones y correcciones en Adobe Analytics:

* [Nuevas funciones, mejoras y correcciones en Adobe Analytics](#aa-features)
* [Avisos importantes para los administradores de Analytics](#aa-notices)  (Contenido actualizado el 27 de marzo de 2020)
* [AppMeasurement](#appm)

Para obtener documentación del producto, consulte la sección [Ayuda de Adobe Analytics](https://docs.adobe.com/content/help/es-ES/analytics/landing/home.html).

### Nuevas funciones, mejoras y correcciones en Adobe Analytics {#aa-features}

* **Varios grupos de informes en [!UICONTROL Analysis Workspace ]**: Ahora puede incluir datos de varios grupos de informes en un único proyecto de [!UICONTROL Analysis Workspace] para verlo en dos paneles en paralelo. [Más información...](https://docs.adobe.com/content/help/es-ES/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Audience Optimization de Experience Cloud**: Esta funcionalidad permite publicar segmentos en Experience Cloud en un plazo de 8 horas (en lugar del tiempo de procesamiento de 48 horas anterior). [Más información...](https://docs.adobe.com/content/help/es-ES/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **Analysis Workspace: Plantilla de tutorial de formación**: Esta nueva plantilla estándar le guía por la terminología común y por los pasos para crear su primer análisis en Workspace. Está disponible como plantilla estándar en el modo [!UICONTROL Nuevo proyecto] y reemplaza el proyecto de muestra actual para los usuarios nuevos que no tienen otros proyectos en su lista.

#### Correcciones

* Se ha corregido un problema en [!UICONTROL Reports &amp; Analytics] que impedía descargar informes en formato `.xls`. Este problema afectaba a los clientes que usaban monedas distintas del dólar estadounidense y el euro. (AN-206541, AN-204008)
* El despliegue de un nuevo shell solucionó varios problemas con los clientes relacionados con el cambio de organizaciones de Experience Cloud. (AN-200844, AN-186920)
* Se corrigió un problema en el cual, al realizar un desglose en el elemento de línea _No especificado_ (o en algunos otros elementos de línea de informes) sin incluir _No especificado (Ninguno)_ en los filtros de búsqueda del desglose, no se obtenían resultados en el desglose.
* Se corrigió un problema que se producía al usar una dimensión clasificada, en el que el total de la métrica de entrada o salida no coincidía con el total del elemento de línea de un desglose.
* Se corrigió un problema en el cual los modelos de primer y último contacto en Attribution IQ no calculaban correctamente el crédito para algunos elementos de línea en algunas dimensiones predeterminadas.
* Se corrigió un problema en el cual el desglose de una dimensión de fecha por otra dimensión de fecha devolvía resultados incorrectos.
* Se corrigió un problema en el que, en algunas ocasiones, las métricas de entrada o salida se contaban incorrectamente al aplicarse con el valor “No especificado” en un informe de dimensión clasificado.

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación     o actualizada | Descripción |
| -----------| ---------- | ---------- |
| Fin de la vida útil de la configuración **[!UICONTROL Nivel de conversión]** | 3 de marzo de 2020 | La configuración [Nivel de conversión](https://docs.adobe.com/content/help/es-ES/analytics/admin/admin-tools/general-acct-settings-admin.html) de **[!UICONTROL Herramientas de administración] > [!UICONTROL Grupos de informes] > [!UICONTROL Configuración general de cuenta]** se eliminará de la interfaz de usuario el 12 de marzo de 2020. |
| Fin de la vida útil de la configuración **[!UICONTROL Archivo de tablero]** | 27 de marzo de 2020 | La configuración **[!UICONTROL Ver archivo]** en **[!UICONTROL Administrar tableros]** de [!UICONTROL Reports &amp; Analytics] dejará de estar disponible a partir de octubre de 2020. |
| Finalización de la compatibilidad con TLS 1.1 | 3 de octubre de 2019 | A partir del 31 de marzo de 2020, Adobe Analytics dejará de ofrecer soporte para TLS 1.1. Este cambio es parte de nuestro trabajo para mantener los estándares de seguridad más altos e impulsar la seguridad de los datos del cliente. |
| Nuevo dominio de Adobe Analytics | 18 de diciembre de 2019 | El 16 de enero de 2020, Adobe Analytics empezará a pasar a un nuevo dominio: `https://experience.adobe.com/analytics.`<br>**Nota:** Este cambio se aplica a todos los usuarios que acceden a Analytics con su Adobe ID o Enterprise ID.<ul><li>Este cambio de dominio puede provocar problemas con las cookies al cargar Analytics en Safari. Al anular la selección _Impedir el seguimiento entre sitios_ en las preferencias de privacidad de [!DNL Safari], se habilitarán las cookies entre dominios (y todas las experiencias entre sitios) y Analytics funcionará en este nuevo dominio de Adobe Experience Cloud. Puede utilizar otros navegadores sin problemas porque esto solo afecta a los usuarios de [!DNL Safari].</li><li>El cambio de dominio puede hacer que [!UICONTROL Activity Map] deje de funcionar para algunos clientes [en casos específicos](https://docs.adobe.com/content/help/es-ES/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fin de vida útil: API heredadas de Analytics | 9 de enero de 2020 | En noviembre de 2020, los siguientes servicios de API heredadas de Analytics llegarán a su fin de vida útil y se cerrarán. Las integraciones actuales creadas con estos servicios dejarán de funcionar. <ul><li>API de Analytics 1.3</li><li>API de Analytics SOAP 1.4</li><li>Autenticación OAuth heredada (OAuth y JWT)</li></ul>Hemos creado las [Preguntas frecuentes del fin de la vida útil de la API heredada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ayudarle a responder a sus preguntas y proporcionar instrucciones sobre cómo proceder. Las integraciones de API que emplean estos servicios pueden migrar a las [API de REST 1.4 de Analytics](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o a las [API de Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Las cuentas heredadas de OAuth pueden migrar a una cuenta de integración de Analytics [Adobe IO](https://console.adobe.io/home?mv=email), que puede utilizarse para acceder tanto a las API de Analytics 1.4 como a las API de Analytics 2.0. |
| Fin de la administración de datos en el centro de datos de San José para Londres y Singapur | Julio de 2020 | Para los clientes de Londres y Singapur, ya no se ofrecerá la administración de datos entre Londres o Singapur y el centro de datos de San José [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, utilice [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Singapur, utilice [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| EOL de Ad Hoc Analysis | 6 de agosto de 2018 | Adobe anunció su intención de finalizar el servicio de Ad Hoc Analysis. La fecha se hará pública una vez que esté disponible. Para obtener más información, consulte [Descubrir Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Consulte [Notas de la versión de AppMeasurement para JavaScript](https://docs.adobe.com/content/help/es-ES/analytics/implementation/appmeasurement-updates.html). La versión 2.20.0 se publicó el jueves, 5 de marzo de 2020.

## ![Icono](/assets/audience-manager.png) Audience Manager {#aam}

Nuevas funcionalidades y actualizaciones de Audience Manager:

| Función | Descripción |
| -----------| ---------- |
| [Hoja de cálculo de herramientas de administración masiva](https://docs.adobe.com/help/es-ES/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | Hay una nueva versión de la hoja de cálculo disponible que corrige un problema que sufrían algunos clientes al crear modelos algorítmicos en el sistema operativo Windows de 64 bits. Descargue la versión más reciente [aquí](https://docs.adobe.com/help/es-ES/audience-manager/user-guide/reference/bulk-management-tools/assets/BAAAM_V2_20200311.xlsm). |

### Correcciones y mejoras {#aam-fixes-and-improvements}

* Se corrigió un error en el cual los clientes no podían actualizar el nombre del segmento debido a que faltaba un permiso RBAC [!UICONTROL VIEW_ALL_DESTINATIONS]. No se debe necesitar el permiso [!UICONTROL VIEW_ALL_DESTINATIONS] para actualizar un segmento. Para obtener más información sobre los permisos de RBAC, consulte [Administración (controles RBAC)](https://docs.adobe.com/help/es-ES/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions). (AAM-52760)
* Se ha corregido un error en el [Explorador de datos](https://docs.adobe.com/help/es-ES/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html) por el que algunos clientes no podían ver el contenido en la sección de información básica ni en los operadores del creador de expresiones al diseñar características basadas en señales del [!UICONTROL Explorador de datos]. (AAM-53130)
* Se corrigió un error en el cual algunos clientes no podían cargar la interfaz de [!UICONTROL Audience Marketplace]. (AAM-52070)
* Se ha corregido un error en la [!UICONTROL API de segmentos] por el que, debido a algunos segmentos sin descripción, la interfaz se bloqueaba cuando los usuarios intentaban acceder a esos segmentos y los usuarios tenían que desplazarse fuera de esa página. (AAM-53071)
* Varias mejoras de accesibilidad en toda la interfaz de usuario. (AAM-48952, AAM-48969, AAM-48979, AAM-48993, AAM-49048, AAM-49057, AAM-49058, AAM-49392)

## ![Icono](/assets/aem.png) Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Adobe Experience Manager (AEM). Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

### Actualizaciones de productos

* **AEM 6.5.4.0**
AEM 6.5, Service Pack 4.0 (6.5.4.0, publicado el 5 de marzo de 2020) es una actualización importante que incluye nuevas funciones, mejoras clave para el cliente, así como mejoras de rendimiento, estabilidad y seguridad, publicada desde el lanzamiento general de AEM 6.5 en abril de 2019.
   * [Novedades de Adobe Experience Manager 6.5, Service Pack 4](https://docs.adobe.com/content/help/es-ES/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
   * [Notas de la versión](https://helpx.adobe.com/es/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Características de la versión de AEM Forms](https://helpx.adobe.com/es/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

   AEM 6.4 Service Pack 8.0 (6.4.8.0, publicado el jueves, 5 de marzo de 2020) es una actualización importante que incluye correcciones claves del cliente realizadas tras la publicación general de AEM 6.4 en abril de 2018.
   * [Notas de la versión](https://helpx.adobe.com/es/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versiones de AEM Forms CFP](https://helpx.adobe.com/es/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

   AEM 6.3 Service Pack 3, Cumulative Fix Pack 8 (6.3.3.8 publicada el martes, 5 de marzo de 2019) es una actualización importante que incluye correcciones claves de cliente publicadas tras el lanzamiento general de AEM 6.3 en abril de 2017.
   * [Notas de la versión](https://helpx.adobe.com/es/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versiones de AEM Forms CFP](https://helpx.adobe.com/es/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal**

   AEM Assets Brand Portal 6.4, Service Pack 6 (6.4.6, publicado el 5 de marzo de 2020) cambia la forma en que AEM Assets se configura con [!UICONTROL Brand Portal.] Además, la versión incluye otras mejoras y correcciones de errores.
   * [Notas de la versión](https://docs.adobe.com/content/help/es-ES/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### Autoayuda

* **AEM as a Cloud Service: Permisos basados en funciones**

   Cloud Manager tiene funciones preconfiguradas con los permisos adecuados. Cada una de las funciones tiene permisos específicos, tareas preconfiguradas o permisos asociados a cada función. El tema de la página de ayuda que trata los [Permisos basados en funciones](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html) identifica las capacidades disponibles y las funciones que pueden ejecutarlas.

* **AEM as a Cloud Service: Dispatcher**

   Las secciones de [Dispatcher y CDN](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn) e [invalidación de caché explícita de Dispatcher](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation) se actualizaron para aclarar las opciones disponibles y cómo funcionan.

* **Configuración de AEM Assets con Brand Portal**

   AEM Assets ahora se configura con [!UICONTROL Brand Portal] a través de Adobe I/O, que obtiene un testigo IMS para la autorización del inquilino de Brand Portal. Anteriormente, se configuraba en la interfaz clásica mediante la [!UICONTROL puerta de enlace OAuth heredada.]
Consulte [Configuración de AEM Assets con Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html).

* **AEM as a Cloud Service: Recorte inteligente en Dynamic Media**

   Hay una nueva opción disponible en AEM as a Cloud Service cuando se trabaja con Recorte inteligente en Dynamic Media:

   **Activar coincidencia de relación de aspecto**: Seleccione esta opción para permitir que Dynamic Media elija un tipo de recorte inteligente que se adapte a la relación de aspecto de la imagen original.
Consulte [Trabajar con el Recorte inteligente](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop).

### Comunidad

* **Seminarios web de AEM Skills Builder**

   * AEM Sites: a partir del 17 de marzo de 2020, descubrirá los componentes básicos de la creación de contenido y los conceptos y operaciones fundamentales de AEM Sites. [Regístrese ahora](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register).
   * AEM Assets: A partir del 19 de marzo de 2020, perfeccione su experiencia en la administración de activos digitales, además de conocer los conceptos básicos de Brand Portal, [!UICONTROL Dynamic Media], [!UICONTROL Asset Link], y mucho más. [Regístrese ahora](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register).

### Recursos adicionales

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

### Campaign Classic

* [Actualización de Campaign Classic 19.1.4](https://docs.adobe.com/content/help/es-ES/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Recursos adicionales

* Adobe Campaign Standard: [Documentación](https://helpx.adobe.com/es/support/campaign/standard.html) - [Notas de la versión](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/release-notes/release-notes.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Planificación de lanzamiento](https://helpx.adobe.com/es/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentación](https://helpx.adobe.com/es/support/campaign/classic.html) - [Notas de la versión](https://docs.campaign.adobe.com/doc/AC/es-ES/RN.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Panel de control de Adobe Campaign: [Documentación](https://docs.adobe.com/content/help/es-ES/control-panel/using/control-panel-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/es-ES/control-panel/using/release-notes.html)

## ![Icono](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Actualizado el 20 de marzo de 2020 para la versión del 21 de marzo:

| Ver | Función |
|------|---------|
| [!UICONTROL Portafolios] | Para obtener instrucciones sobre cómo administrar sus portafolios para tener en cuenta los cambios de tráfico resultantes de la COVID-19, póngase en contacto con su administrador de cuentas. |
| Campañas publicitarias de Google y Microsoft | En portafolios optimizados con la opción “Optimizar automáticamente los valores de ajuste de oferta”, Advertising Cloud ya no optimiza automáticamente la configuración de ajuste de oferta para campañas mediante la estrategia de oferta de coste por clic (eCPC) mejorada. El motor de búsqueda optimiza todos los ajustes de oferta en el momento de la subasta. Advertising Cloud sigue optimizando las ofertas de base y, cuando la opción “Ajustar automáticamente los límites presupuestarios de la campaña” está activada, el presupuesto de la campaña. |
| [!UICONTROL Alertas beta] | (Función beta) Ahora puede crear plantillas de alerta para identificar cuándo cualquier portafolio cumple condiciones específicas, como métricas de rendimiento, durante un período especificado y luego generar una alerta. Puede crear alertas a nivel de portafolio desde **[!UICONTROL Información e informes]** > **[!UICONTROL Alertas (Beta)]**, pero no desde **[!UICONTROL Optimización]** > **[!UICONTROL (Portafolio)]**. **Nota:** Ya no están disponibles las alertas creadas a partir de la versión anterior de Alertas beta, que se reemplazó en enero. |
| [!UICONTROL Administración] > [!UICONTROL Propiedades de la transacción] | La nueva columna “ID de propiedad” muestra el ID de propiedad exclusivo de cada propiedad de transacción. Puede buscar cualquier cadena contenida en los valores de columna. |

## ![Icono](/assets/magento.png) [!DNL Magento] {#magento}

Para las notas de la versión de Magento, consulte:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Icono](/assets/marketo.png) [!DNL Marketo] {#marketo}

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

## ![Icono](/assets/experience-cloud.png) Nueva documentación y tutoriales {#selfhelp}

Artículos y vídeos informativos nuevos y recientes. <!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

| Solución | Contenido | Descripción |
|----------| -----------| ---------- |  
| [!UICONTROL AEM Commerce] | Vídeo: [Creación de varias categorías y páginas de producto](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md) | Descubra cómo crear un proyecto CIF de Adobe Experience Manager (AEM) básico como punto de partida para proyectos de clientes que utilizan componentes principales de CIF. Aplique un tema y estilo CSS a los componentes e inspeccione un nuevo proyecto de AEM CIF, generado por el arquetipo. Además, descubra cómo se organizan CSS y JavaScript utilizados por los componentes principales de CIF. |
| [!UICONTROL AEM Forms] | Artículo: [Autenticar con AEM Author mediante OKTA](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | Obtenga información sobre cómo configurar la aplicación en el portal OKTA y sobre la configuración que suele utilizar para registrar una nueva aplicación. |
| [!UICONTROL AEM Commerce] | Tutorial: [Personalización de los componentes principales de CIF](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md) | Consulte varios puntos de extensión diferentes proporcionados por los componentes principales de CIF y AEM en general. Los componentes principales de CIF proporcionan un conjunto estándar de componentes comerciales que se pueden utilizar para acelerar un proyecto que integra las soluciones de Adobe Experience Manager (AEM) y Magento. |
| [!DNL Adobe Campaign]: Destinos de audiencia | Vídeo: [Crear una audiencia...](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | Cree una audiencia en Campaign Standard mediante el [!UICONTROL Generador de segmentos de Adobe Experience Platform]. Puede acceder a esta funcionalidad directamente desde Adobe Campaign Standard mediante los módulos [!UICONTROL Audiencias]. |
| [!DNL Adobe Campaign]: Destinos de audiencia | Vídeo: [Activación de audiencias de Adobe Experience Platform en un flujo de trabajo de marketing](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | Obtenga información sobre cómo activar la [!UICONTROL Audiencia de consulta de servicios de datos] en un flujo de trabajo mediante la actividad [!UICONTROL Leer audiencia]. |
| [!DNL Adobe Campaign] | Tutorial: [Notificaciones push con Android](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) | Envíe notificaciones push personalizadas y segmentadas a dispositivos móviles iOS y Android. Este tutorial le guiará por los pasos necesarios para enviar notificaciones push desde Adobe Campaign y recibir estas notificaciones en su aplicación de Android. |
| [!DNL Adobe Campaign] | Vídeo: [Crear una notificación push](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | Cree una notificación push en Adobe Campaign Standard. Puede enviar notificaciones push personalizadas y segmentadas a dispositivos móviles iOS y Android. |
| [!DNL Adobe Campaign]: Conector de datos AEP | Vídeo: [Comprobar el estado de un trabajo de inserción de datos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) | Obtenga información sobre cómo comprobar el estado de un trabajo de inserción de datos y si los datos de Adobe Campaign Standard se han incorporado correctamente en Adobe Experience Platform. |
| [!DNL Adobe Campaign]: Conector de datos AEP | Vídeo: [Modificación de la asignación de datos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) | Obtenga información sobre cómo comprobar el estado y modificar la asignación de datos. |
| [!DNL Adobe Campaign]: Conector de datos AEP | Vídeo: [Asignación de eventos de experiencia](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | Obtenga información sobre cómo asignar eventos de experiencia en Adobe Experience Platform. |
| [!DNL Adobe Campaign]: Conector de datos AEP | Vídeo: [Asignar recursos personalizados](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) | Obtenga información sobre cómo asignar distintos tipos de datos entre Adobe Campaign Standard y Adobe Experience Platform. |
| [!DNL Adobe Campaign]: Conector de datos AEP | Vídeo: [Comprender el conector de datos de Adobe Experience Platform](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) | Obtenga información sobre cómo hacer que los datos estén disponibles en Adobe Experience Platform asignando datos XTK (datos incorporados en Campaign) a datos del modelo de datos de experiencia (XDM) en Adobe Experience Platform. |
| [!DNL Adobe Campaign]: Conector de datos AEP | Vídeo: [Asignar datos de tabla de inicio](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html) | Obtenga información sobre cómo asignar los datos iniciales y los perfiles de prueba con Adobe Experience Platform. |
| [!DNL Adobe Campaign]: Destinos de audiencia | Vídeo: [Cambiar la dimensión de segmentación de una entrega para una audiencia de otra plataforma](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html) | Descubra cómo cambiar la dimensión de segmentación de una entrega para una audiencia de otra plataforma fuera de la tabla de perfil principal en Adobe Campaign Standard. |
| [!DNL Adobe Campaign] | Vídeo: [Administración de datos en gran cantidad en Snowflake](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Saque el máximo partido al conector Snowflake de Adobe Campaign Classic. |
| [!DNL Adobe Campaign]: Destinos de audiencia | Artículo: [Destinos de audiencia (BETA), información general](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) | Descubra cómo aprovechar los datos de perfil centralizados y consolidados de Adobe Experience Platform para campañas de marketing en Adobe Campaign Standard. |
| [!DNL Adobe Target] - SDK móvil | Tutorial: [Personalización de las experiencias de la aplicación con Adobe Target](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) | Implemente Adobe Target en su propia aplicación de Android. Valide la configuración del SDK de Mobile Services e implemente solicitudes de [!DNL Target] como la recuperación previa de contenido, el bloqueo de solicitudes y mucho más. |
| Adobe Analytics | Vídeo: [Supersesión de Adobe Summit 2019](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) | Disfrute de los clips de la supersesión de Summit 2019. |
| Adobe Analytics | Vídeo: [Introducción a las métricas calculadas en Customer Journey Analytics](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) | Conozca los aspectos básicos de la creación de [!UICONTROL métricas calculadas] en [!UICONTROL Customer Journey Analytics]. |
| Adobe Analytics | Vídeo: [Supersesión de Adobe Summit 2019](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html) | Vea clips seleccionados de la sesión de viajes y hospitalidad de Summit 2019. |
| Adobe Analytics | Vídeo: [Supersesión de Adobe Summit 2019](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) | Consulte los clips seleccionados de la sesión de venta al por menor de Summit 2019. |
| Adobe Analytics | Vídeo: [Caso real de cliente: Accent Group invierte en la experiencia de sus clientes para mejorar las ventas](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) | Descubra cómo Accent Group utiliza Adobe Experience Cloud para crear experiencias digitales sin problemas. |
| Adobe Analytics | Vídeo: [Caso real de cliente: ServiceNow obtiene la información correcta y necesaria para conectarse con posibles clientes](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) | Descubra cómo [!DNL ServiceNow] obtiene datos procesables de sus canales de marketing y aumenta el retorno de la inversión en la publicidad de búsqueda de pago con Adobe Advertising Cloud y Adobe Analytics. |
| Adobe Analytics | Vídeo: [Adobe Analytics: Más que simples datos, conocimiento del cliente](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html) | Obtenga información sobre el marketing basada en datos y cómo aplicar la madurez de los análisis desde los datos hasta los conocimientos y la acción. |
| Adobe Analytics | Vídeo: [Adobe Sensei y Adobe Analytics: Versión ampliada](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html) | Vea las funciones principales de Adobe Analytics con tecnología de Adobe [!DNL Sensei,] como, por ejemplo, [!UICONTROL Detección de anomalías], [!UICONTROL Análisis de contribución], [!UICONTROL Alertas inteligentes], [!UICONTROL Clúster], [!UICONTROL IQ de segmento] y [!UICONTROL Modelado de propensión]. |
| Adobe Analytics | Vídeo: [Adobe Analysis Workspace y la revolución de su negocio](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | Descubra cómo puede realizar análisis ad hoc, análisis flexibles, análisis de cohorte y análisis de abandonos mediante [!UICONTROL Analysis Workspace]. También puede compartir el entorno de trabajo de análisis con todos los miembros de su empresa. Además, su función de arrastrar y soltar permite a todos analizar los datos fácilmente y obtener información rápidamente. |
| Adobe Analytics | Vídeo: [Caso real de cliente: The Home Depot innova través de la administración de experiencias del cliente](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) | Descubra cómo [!DNL Home Depot] utiliza las soluciones de Adobe para mejorar la lealtad de marca y la satisfacción del cliente gracias a una experiencia de compra personalizada. |
| Adobe Analytics | Presentación: [Explicación de Customer Journey Analytics](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html) | Descubra cómo Adobe [!UICONTROL Customer Journey Analytics], un servicio de aplicaciones integrado en [!DNL Adobe Experience Platform], incorpora [!UICONTROL Analysis Workspace] en Experience Platform. Esta funcionalidad permite el análisis multicanal en cualquiera de los conjuntos de datos de [!DNL Adobe Experience Platform]. |
| Adobe Analytics | Vídeo: [Atribución en canales múltiples en CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html) | Descubra cómo puede utilizar las visualizaciones para mostrar la atribución (dar crédito) a través de los canales en [!UICONTROL Customer Journey Analytics]. |
| Adobe Analytics | Artículo: [Sugerencias al cliente para continuar con su aprendizaje de Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) | Conozca a tres clientes de Adobe que tienen consejos y trucos para obtener el máximo valor de Adobe Analytics. |
| Adobe Analytics | Vídeo: [Creación de visualizaciones multicanal en CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html) | Descubra cómo [!UICONTROL Customer Journey Analytics] permite crear visualizaciones que incluyen datos de varios conjuntos de datos en diferentes canales, incluida la combinación de datos por visitante. |
| Adobe Analytics | Vídeo: [Mover las métricas calculadas de Adobe Analytics a Customer Journey Analytics](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) | Encontrará sugerencias para volver a crear las [!UICONTROLCmétricas calculadas] de Analytics en [!UICONTROL Customer Journey Analytics]. |
