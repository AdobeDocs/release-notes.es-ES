---
title: Notas de la versión de Adobe Experience Cloud
description: Plantilla para notas de la versión de Experience Cloud
doc-type: release notes
last-update: February 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 9ed727b23cbc90965f44c4bb914728bbc2394d6b

---


# Notas de la versión de Adobe Experience Cloud - Marzo de 2020

Nuevas funciones y correcciones en Adobe Experience Cloud.

>[!NOTE]
>Para recibir notificaciones por correo electrónico sobre próximas versiones, suscríbase a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html). La nueva información publicada tras el lanzamiento se marcará con la fecha de publicación.

**Fecha de la versión: Marzo de 2020**

(Las fechas específicas de lanzamiento del producto pueden variar)

* [Estado del sistema de Adobe](#status)
* [Servicios principales e interfaz de Experience Cloud](#ecloud)  (Actualización: **26 de febrero de 2020**)
* [Experience Platform](#platform)
* [Mobile Services y Mobile SDK](#mobile)
* [!DNL Analytics](#analytics) (Actualización: 21 de febrero de 2020)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (vínculos a la ayuda de la solución)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (vínculos a la ayuda de la solución)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)

¿Busca ayuda en casa? Consulte la documentación de [Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Estado del sistema de Adobe {#status}

[!UICONTROL El estado del sistema de Adobe] proporciona información detallada, actualizaciones de estado y notificaciones por correo electrónico sobre los productos en la nube de Adobe y las interrupciones y sesiones de mantenimiento de los servicios de Adobe. Puede comprobar el estado en [status.adobe.com](https://status.adobe.com/).

**Novedades**

* Con su Adobe ID, puede suscribirse a las notificaciones de eventos en función de sus preferencias de productos, regiones e idiomas. A los usuarios que configuran sus preferencias de suscripción se les notifican los eventos de mantenimiento e incidencias del producto relevantes en cuanto se abran, actualicen o cierren. Empiece por [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuevas funciones y mejoras disponibles**

| Función | Descripción |
| -----------| ---------- |
| Notificaciones rápidas de los eventos del producto | <ul><li>Reciba información con 30 días de antelación sobre el mantenimiento del servicio. Esta función proporciona más tiempo de espera para evaluar el impacto potencial en sus operaciones comerciales, lo que le permite implementar un plan de mitigación si es necesario.</li><li>Las notificaciones avanzadas están disponibles en las plataformas web, móviles y tabletas y mediante notificaciones por correo electrónico.</li></ul> |
| Personalice su experiencia según el idioma preferido | <ul><li>Elija un idioma preferido para las notificaciones por correo electrónico. La función de suscripción automática ya está disponible en diecinueve idiomas.</li></ul> |
| Mejora de la experiencia del usuario en cuanto a las suscripciones y las notificaciones | <ul><li>Especifique las preferencias de región y evento en un solo clic para todos los productos a los que desee suscribirse.</li><li>Reciba una notificación cuando se promocionen _problemas potenciales_ a _menores_ o _mayores_.</li><li>La página del explorador se vuelve a cargar automáticamente cuando se actualiza cualquier producto o evento.</li></ul> |

## Servicios principales e interfaz de Experience Cloud {#ecloud}

Actualización de la versión: **26 de febrero de 2016**

Nuevas funciones y correcciones en la interfaz de Experience Cloud, incluida la administración y los servicios principales (atributos del cliente, audiencias, desencadenadores, cookies, etc.).

| Función | Descripción |
| -----------| ---------- |
| Herramienta de administración: ver detalles del usuario | Los administradores pueden ver una lista de los usuarios de Experience Cloud que pueden ordenar y filtrar, y sus detalles en la nueva herramienta de administración. Los detalles del usuario incluyen el acceso al producto, las funciones y la información a la que accedió por última vez. Consulte la ayuda de la [herramienta de administración de Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) para obtener más información. |

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

**Nota:** La página [!UICONTROL Fuente] dejará de usarse en enero de 2020. Busque un aviso de obsolescencia del producto.

Para obtener documentación del producto, consulte [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Notas de la versión de Experience Platform, Experience Platform Launch, servicios de identidad y boletines de seguridad.

* [Notas de la versión de Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Boletines de seguridad y avisos](https://helpx.adobe.com/security.html)  (Todos los productos de Adobe)

### Experience Platform Launch {#launch}

Consulte [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) para ver notas de la versión y documentación del producto.

## Mobile Services y Mobile SDK {#mobile}

Contenido móvil.

## [!DNL Analytics] {#analytics}

Nuevas funciones y correcciones en Adobe Analytics:

* [Nuevas funciones, mejoras y correcciones en Adobe Analytics](#aa-features)
* [Avisos importantes para los administradores de Analytics](#aa-notices)
* [AppMeasurement](#appm) (actualización: 21 de febrero de 2020)

Para obtener documentación del producto, consulte la sección [Ayuda de Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nuevas funciones, mejoras y correcciones en Adobe Analytics {#aa-features}

* **Varios grupos de informes en Analysis Workspace**: Ahora puede incluir datos de varios grupos de informes en un único proyecto de Analysis Workspace para verlo en paralelo. A partir del 12 de marzo de 2020, la función se lanzará a todos los clientes durante varias semanas. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Optimización** de audiencias de Experience Cloud: Esta función le permite publicar segmentos en Experience Cloud en un plazo de 8 horas (en lugar del tiempo de procesamiento de 48 horas anterior). [Más información...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)

#### Correcciones

* Se ha corregido un problema en Informes y análisis que impedía a los clientes descargar informes .xls.(AN-206541, AN-204008)
* La implementación de un nuevo shell solucionó varios problemas con los clientes relacionados con el cambio de organizaciones de Experience Cloud.(AN-200844, AN-186920)

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación  o actualizada | Descripción |
| -----------| ---------- | ---------- |
| EOL del ajuste &quot;Nivel de conversión&quot; | 3 de marzo de 2020 | La configuración de Nivel [de](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) conversión que no funciona en Herramientas de administración > Grupos de informes > Configuración general de cuenta se eliminará de la interfaz de usuario el 12 de marzo de 2020. |
| EOL del archivo de tableros | 3 de marzo de 2020 | La opción &quot;Ver archivo&quot; en Administrar tableros en Informes y análisis ya no estará disponible a partir del 12 de marzo de 2020. |
| Nuevo dominio de Adobe Analytics | 18 de diciembre de 2019 | El 16 de enero de 2020, Adobe Analytics empezará a pasar a un nuevo dominio: `https://experience.adobe.com/analytics.`<br>**Nota:** Este cambio se aplica a todos los usuarios que acceden a Analytics con su Adobe ID o Enterprise ID.<ul><li>Este cambio de dominio puede provocar problemas con las cookies al cargar Analytics en Safari. Al anular la selección _Impedir el seguimiento entre sitios_ en las preferencias de privacidad de Safari, se habilitarán las cookies entre dominios (y todas las experiencias entre sitios) y Analytics funcionará en este nuevo dominio de Adobe Experience Cloud. Puede utilizar otros navegadores sin problemas porque esto solo afecta a los usuarios de Safari.</li><li>El cambio de dominio puede hacer que [!UICONTROL Activity Map] deje de funcionar para algunos clientes [en casos específicos](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fin de vida útil: API heredadas de Analytics | 9 de enero de 2020 | En noviembre de 2020, los siguientes servicios de API heredadas de Analytics llegarán a su fin de vida útil y se cerrarán. Las integraciones actuales creadas con estos servicios dejarán de funcionar. <ul><li>API de Analytics 1.3</li><li>API de Analytics SOAP 1.4</li><li>Autenticación OAuth heredada (OAuth y JWT)</li></ul>Hemos creado las [Preguntas frecuentes del fin de la vida útil de la API heredada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ayudarle a responder a sus preguntas y proporcionar instrucciones sobre cómo proceder. Las integraciones de API que emplean estos servicios pueden migrar a las [API de REST 1.4 de Analytics](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o a las [API de Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Las cuentas heredadas de OAuth pueden migrar a una cuenta de integración de Analytics [Adobe IO](https://console.adobe.io/home?mv=email), que puede utilizarse para acceder tanto a las API de Analytics 1.4 como a las API de Analytics 2.0. |
| Fecha de fin de uso de la opción **[!UICONTROL Ver archivo]** | 30 de octubre de 2019 | Anuncio de la fecha de finalización en enero de 2020 de la opción **[!UICONTROL Ver archivo]** en el Administrador de paneles (**[!UICONTROL Componentes > Paneles]**). |
| Fecha de fin de uso de la opción **[!UICONTROL Aplicar restricciones de inicio de sesión con IP]** | 30 de octubre de 2019 | Anuncio de la fecha de finalización en enero de 2020 de la creación de listas de IP de inicio de sesión admitidas (**[!UICONTROL Aplicar restricciones de inicio de sesión con IP]**) en el menú **[!UICONTROL Administración > Configuración de la compañía > Seguridad]**. |
| Finalización de la compatibilidad con TLS 1.1 | 3 de octubre de 2019 | A partir del 31 de marzo de 2020, Adobe Analytics dejará de ofrecer soporte para TLS 1.1. Este cambio es parte de nuestro trabajo para mantener los estándares de seguridad más altos e impulsar la seguridad de los datos del cliente. |
| Fin de la administración de datos en el centro de datos de San José para Londres y Singapur | Julio de 2020 | Para los clientes de Londres y Singapur, ya no se ofrecerá la administración de datos entre Londres o Singapur y el centro de datos de San José [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, utilice [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Singapur, utilice [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Próximos cambios en el campo `createDate` para los usuarios de Analytics | 30 de agosto de 2019 | En octubre o noviembre de 2019, el campo `createDate` de los usuarios de Analytics se actualizó de la hora del Pacífico de EE. UU. a un valor de fecha y hora con formato correcto respecto a la información de zona horaria.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

Consulte [Notas de la versión de AppMeasurement para JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). La versión 2.19.0 se publicó el 21 de febrero de 2020.

## Audience Manager {#aam}

Correcciones y funciones agregadas a Audience Manager.

### Nuevas funciones y correcciones en Audience Manager {#aam-features}

| Función | Descripción |
|----|----|
|  |  |
|  |  |

### Correcciones y mejoras {#aam-fixes-and-improvements}

Correcciones para AAM.

## Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Adobe Experience Manager (AEM). Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

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

### Recursos adicionales

* Adobe Campaign Standard: [Documentación](https://helpx.adobe.com/support/campaign/standard.html) - [Notas de la versión](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Planificación de lanzamiento](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentación](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de la versión](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Panel de control de Adobe Campaign: [Documentación](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Actualizado el 10 de febrero de 2020, para la versión del 8 de febrero

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

**** Centro de éxito de participación en marketing: Lanzamiento en febrero de 2020. El Centro de éxito es un centro de ayuda integrado en el producto que le permite buscar en la Documentación del producto, la Comunidad, las guías de inicio prácticas, el contenido de adopción de acceso y mucho más. Nota: Esta función se lanzará como una versión beta en ANZ y se comercializará en Norteamérica más adelante en el trimestre.

### Degradaciones

* **Parámetro &quot;_method&quot; de Asset API:** a partir de septiembre de 2020, los puntos de conexión de Asset API ya no aceptarán &quot;_method&quot; para pasar parámetros de consulta en un cuerpo de POST para omitir las limitaciones de longitud de URI.
* **Degradación de compatibilidad con Internet Explorer:** a partir de la versión del 31 de julio de 2020, la interfaz de usuario de Marketo Engage dejará de ser compatible con Internet Explorer.

Para ver las notas de la versión acumulativas e históricas, consulte [Notas de la versión de Marketo](https://docs.marketo.com/x/CgA6Ag).