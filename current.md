---
title: Notas de la versión de Adobe Experience Cloud
description: Plantilla para notas de la versión de Experience Cloud
doc-type: release notes
last-update: February 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 0a9f95d1d9a2bba69cecada0d0c39f70e507c995

---


# Acceso anticipado - Notas de la versión de Adobe Experience Cloud - Febrero de 2020

Nuevas funciones y correcciones en Adobe Experience Cloud.

>[!IMPORTANT]
>Esta página incluye contenido previo al lanzamiento de la nueva versión y está sujeta a cambios antes de su publicación planificada.

>[!NOTE]
>Para recibir notificaciones por correo electrónico sobre próximas versiones, suscríbase a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html). La nueva información publicada tras el lanzamiento se marcará con la fecha de publicación.

**Fecha de publicación: 20 de febrero de 2020**

(Las fechas específicas de lanzamiento del producto pueden variar)

Última actualización: 10 de febrero de 2020

* [Estado del sistema de Adobe](#status)
* [Servicios principales e interfaz de Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services y Mobile SDK](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (vínculos a la ayuda de la solución)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (vínculos a la ayuda de la solución)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)

¿Busca ayuda en casa? Consulte la documentación de [Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Estado del sistema de Adobe {#status}

[!UICONTROL El estado del sistema de Adobe] proporciona información detallada, actualizaciones de estado y notificaciones por correo electrónico sobre los productos en la nube de Adobe y las interrupciones y sesiones de mantenimiento de los servicios de Adobe. Puede comprobar el estado en [status.adobe.com](https://status.adobe.com/).

**Novedades**

* Con su Adobe ID, puede suscribirse a las notificaciones de eventos en función de sus preferencias de producto, región, evento e idioma. Los usuarios que configuran sus preferencias de suscripción reciben una notificación de los eventos de mantenimiento e incidencia del producto relevantes en cuanto se abren, actualicen o cierren. Empiece por [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuevas funciones y mejoras disponibles**

| Función | Descripción |
| -----------| ---------- |
| Conocimiento más rápido de los eventos del producto | <ul><li>Reciba información con 30 días de anticipación sobre el mantenimiento del servicio. Esta función proporciona más tiempo de espera para evaluar el impacto potencial en sus operaciones comerciales, lo que le permite implementar un plan de mitigación si es necesario.</li><li>Las notificaciones avanzadas están disponibles en las superficies web, móviles y tabletas y mediante notificaciones por correo electrónico.</li></ul> |
| Personalice su experiencia según el idioma preferido | <ul><li>Elija un idioma preferido para las notificaciones por correo electrónico. La función de suscripción automática ya está disponible en diecinueve idiomas.</li></ul> |
| Mejora de la experiencia del usuario en cuanto a la suscripción y la notificación | <ul><li>Especifique las preferencias de región y evento en un solo clic para todos los productos a los que desee suscribirse.</li><li>Reciba una notificación cuando se _promocionen problemas potenciales_ a _menores_ o _mayores_ .</li><li>La página del explorador se actualiza automáticamente cuando se actualiza cualquier producto o evento.</li></ul> |

## Servicios principales e interfaz de Experience Cloud {#ecloud}

Nuevas funciones y correcciones en la interfaz de Experience Cloud, incluida la administración y los servicios principales (atributos del cliente, audiencias, desencadenadores, cookies, etc.).

**Correcciones**

* **** Atributos del cliente: La interfaz de usuario de Atributos del cliente ahora muestra estados adicionales de perfiles sincronizados en Target. (MCUI-10231)
* **** Desencadenadores del servicio principal: Debido a la falta de uso, se ha eliminado la puntuación de tendencia &quot;Probabilidad de retorno en 30 días&quot; al crear un activador de tipo Abandono. (MCUI-10056)

### Dominio de producto unificado

Adobe está actualizando el encabezado de la interfaz y el dominio para unificar y mejorar el funcionamiento de las aplicaciones de Experience Cloud. Estas mejoras están diseñadas para mejorar sutilmente su experiencia. Estas mejoras no cambiarán los flujos de trabajo actuales.

Las actualizaciones incluyen:

* Nuevas URL de la solución: `experience.adobe.com/<application name>`:
   * Todos los productos adoptarán en algún momento este patrón de URL. Busque nuevas direcciones URL que entren en vigor durante el mes.
   * Browser support: Supported browsers include [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari], and [!DNL Opera] (latest versions). **Nota:** Aunque la interfaz de Experience Cloud admite estos exploradores, es posible que las soluciones individuales no los admitan a todos. (Por ejemplo, [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) no es compatible con [!DNL Opera] y [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) no es compatible con [!DNL Safari]).
   * ([!DNL Safari] solo) El cambio de dominio puede causar problemas de cookies en [!DNL Safari]. Deselecting _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain.
* Es más fácil cambiar entre las organizaciones o a otra aplicación.
* Ayuda del producto mejorada: [!UICONTROL Experience League] está integrada en el producto, por lo que una búsqueda de ayuda también incluye resultados de foros de la comunidad y contenido de vídeo. Este cambio simplifica el acceso a más contenido y le ayuda a sacar el máximo rendimiento de Experience Cloud. Además, puede hacer clic en **[!UICONTROL Ayuda]** > **[!UICONTROL Comentarios]** para informar sobre problemas o compartir sus ideas con Adobe.
* Notificaciones mejoradas: El menú desplegable [!UICONTROL Notificaciones] ahora tiene dos pestañas, una para sus propias notificaciones de productos y otra para los anuncios de productos globales.

**Nota:** La página [!UICONTROL Fuente] dejará de usarse en enero de 2020. Busque un aviso de obsolescencia del producto.

Para obtener documentación del producto, consulte [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Notas de la versión de Experience Platform, Experience Platform Launch, servicios de identidad y boletines de seguridad.

* [Notas de la versión de Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Boletines de seguridad y avisos](https://helpx.adobe.com/security.html) (Todos los productos de Adobe)

### Experience Platform Launch {#launch}

Consulte [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) para ver notas de la versión y documentación del producto.

## Mobile Services y Mobile SDK {#mobile}

**4 de febrero de 2020: Versión 4.19.0**

En esta versión se realizó la siguiente actualización:

**** Ciclo de vida: Se ha agregado una nueva API `pauseCollectingLifecycleData`para mitigar los datos de duración de sesión anormales que se notificaban desde algunos dispositivos iOS antiguos.

## [!DNL Analytics] {#analytics}

Nuevas funciones y correcciones en Adobe Analytics:

* [Nuevas funciones, mejoras y correcciones en Adobe Analytics](#aa-features) (Actualizado el 21 de enero de 2020)
* [Avisos importantes para los administradores de Analytics](#aa-notices)
* [AppMeasurement](#appm)

Para obtener documentación del producto, consulte la sección [Ayuda de Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nuevas funciones, mejoras y correcciones en Adobe Analytics {#aa-features}

<!--* **Support for multiple report suites in Workspace:** You can now bring in data from multiple report suites into a single project to view side by side. Beginning on Feb 20, 2020, the feature will roll out to all customers over the course of several weeks. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)-->
* **Nueva plantilla de** espacio de trabajo para organizaciones que utilizan Análisis entre dispositivos:Esta plantilla muestra la eficacia del CDA para unir visitas y le enseña las métricas y dimensiones exclusivas del CDA. Se requiere un grupo de informes que utilice CDA. Consulte [Configuración de análisis](https://docs.adobe.com/content/help/en/analytics/components/cda/cda-setup.html) entre dispositivos para obtener más información.
* **** La latencia de vinculación de CDA para organizaciones que utilizan Private Graph se reduce a un día: La funcionalidad de Private Graph se ha mejorado para reducir la latencia de generación de gráficos de un proceso semanal por lotes a un gráfico diario actualizado, lo que permite a los clientes de CDA acceder a vínculos y gráficos de identidad más actualizados.
* **** Labs (Previsualizaciones de tecnología): Esta nueva función de Analytics le permite probar nuevos prototipos de funciones en producción y proporcionar información valiosa a Adobe. [Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/tech-previews/overview.html)
* **Nuevas teclas de acceso directo en Workspace:**<ul><li>Contraer/Expandir todos los paneles: `alt + m`</li><li>Panel Contraer/Expandir activo: `alt + ctrl + m`</li><li>Buscar carril izquierdo: `ctrl + /`</li><li>Mover al panel siguiente: `alt + Right Key`</li><li>Mover al panel anterior: `alt + Left Key`</li></ul>[Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/fa-shortcut-keys.html)
* **Otras mejoras de Workspace:**<ul><li>Cuando se coloca un panel o una visualización en [!UICONTROL Workspace], el carril izquierdo cambia automáticamente a componentes para lograr un flujo de trabajo más fluido.</li><li>Ahora se pueden realizar acciones en los componentes de plantilla (por ejemplo, etiquetados, marcados como favoritos y aprobados).</li><li>Las listas filtradas de métricas y segmentos ofrecen el `+` botón para agregar un nuevo componente si no encuentra lo que necesita.</li></ul>
* El depurador **de** Workspace se ha agregado al menú Ayuda, lo que le permite habilitarlo para depurar solicitudes de Workspace. [Más información...](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/reporting-tricks.md)
* **** Navegador Microsoft Edge basado en cromo: Esta versión incluye cambios para reconocer el explorador Microsoft Edge basado en Chrome (versión 79 y posterior) con fines de generación de informes.

#### Correcciones

* Se ha corregido un problema con la interfaz de usuario del segmento que indicaba que las dimensiones del canal [!UICONTROL de] marketing eran compatibles con el almacén [!UICONTROL de datos], cuando en realidad no lo eran. En el futuro, el Generador [!UICONTROL de] segmentos ya no mostrará estas dimensiones como compatibles con el Almacén [!UICONTROL de datos] . (AN-202297)
* Se ha corregido un problema con el nombre de un segmento publicado que se actualizaba en Analytics y que no se actualizaba en Audience Manager en un plazo de 24 horas. (AN-199974)

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación o actualizada | Descripción |
| -----------| ---------- | ---------- |
| Nuevo dominio de Adobe Analytics | 18 de diciembre de 2019 | `https://experience.adobe.com/analytics.`<br>** El 16 de enero de 2020, Adobe Analytics comenzó a pasar a un nuevo dominio. **Nota: Este cambio se aplica a todos los usuarios que acceden a Analytics con su Adobe ID o Enterprise ID.<ul><li>Este cambio de dominio puede provocar problemas con las cookies al cargar Analytics en Safari. Deselecting _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. Puede utilizar otros navegadores sin problemas porque esto solo afecta a los usuarios de Safari.</li><li>El cambio de dominio puede hacer que [!UICONTROL Activity Map] deje de funcionar para algunos clientes [en casos específicos](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fin de vida útil: API heredadas de Analytics | 9 de enero de 2020 | En noviembre de 2020, los siguientes servicios de API heredadas de Analytics llegarán a su fin de vida útil y se cerrarán. Las integraciones actuales creadas con estos servicios dejarán de funcionar. <ul><li>API de Analytics 1.3</li><li>API de Analytics SOAP 1.4</li><li>Autenticación OAuth heredada (OAuth y JWT)</li></ul>Hemos creado las [Preguntas frecuentes del fin de la vida útil de la API heredada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ayudarle a responder a sus preguntas y proporcionar instrucciones sobre cómo proceder. Las integraciones de API que emplean estos servicios pueden migrar a las [API de REST 1.4 de Analytics](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o a las [API de Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Las cuentas heredadas de OAuth pueden migrar a una cuenta de integración de Analytics [Adobe IO](https://console.adobe.io/home?mv=email), que puede utilizarse para acceder tanto a las API de Analytics 1.4 como a las API de Analytics 2.0. |
| Fecha de fin de uso de la opción **[!UICONTROL Ver archivo]** | 30 de octubre de 2019 | Anuncio de la fecha de finalización en enero de 2020 de la opción **[!UICONTROL Ver archivo]** en el Administrador de paneles (**[!UICONTROL Componentes > Paneles]**). |
| Fecha de fin de uso de la opción **[!UICONTROL Aplicar restricciones de inicio de sesión con IP]** | 30 de octubre de 2019 | Anuncio de la fecha de finalización en enero de 2020 de la creación de listas de IP de inicio de sesión admitidas (**[!UICONTROL Aplicar restricciones de inicio de sesión con IP]**) en el menú **[!UICONTROL Administración > Configuración de la compañía > Seguridad]**. |
| Finalización de la compatibilidad con TLS 1.1 | 3 de octubre de 2019 | A partir del 31 de marzo de 2020, Adobe Analytics dejará de ofrecer soporte para TLS 1.1. Este cambio es parte de nuestro trabajo para mantener los estándares de seguridad más altos e impulsar la seguridad de los datos del cliente. |
| Fin de la administración de datos en el centro de datos de San José para Londres y Singapur | Julio de 2020 | Para los clientes de Londres y Singapur, ya no se ofrecerá la administración de datos entre Londres o Singapur y el centro de datos de San José [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, utilice [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Singapur, utilice [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Próximos cambios en el campo `createDate` para los usuarios de Analytics | 30 de agosto de 2019 | En octubre o noviembre de 2019, el campo `createDate` de los usuarios de Analytics se actualizó de la hora del Pacífico de EE. UU. a un valor de fecha y hora con formato correcto respecto a la información de zona horaria.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

Consulte [Notas de la versión de AppMeasurement para JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). La versión 2.18.0 se publicó el 13 de febrero de 2020.

## Audience Manager {#aam}

Correcciones y funciones agregadas a Audience Manager.

### Nuevas funciones y correcciones en Audience Manager {#aam-features}

| Función | Descripción |
|----|----|
| [Informes de uso de actividades](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/administration/activity-usage-reporting.html) | El informe [!UICONTROL Uso de] actividades le ayuda a ver y rastrear el uso de la actividad de su instancia de Audience Manager, lo que le ofrece una idea clara de cómo se compara el uso de la actividad con el compromiso contractual. |

<!-- ### Fixes and Improvements {#aam-fixes-and-improvements}

* Fixes
* Fixes -->

## Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Adobe Experience Manager (AEM). Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

### Versiones de productos

* **Cloud Manager 2020.2.0**

   Cloud Manager 2020.2.0 simplifica la administración de autoservicio de los entornos limitados de Adobe Experience Manager como un servicio de nube.

   Consulte las [Notas de la versión](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html).

### Autoayuda

* **Tutoriales para AEM como servicio de nube**

   Empiece rápidamente con los [tutoriales de AEM como un servicio](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/overview.html)de nube.

* **API interactiva por lotes de comunicaciones de AEM Forms**

   La comunicación interactiva de la API por lotes de AEM Forms permite a los clientes producir varias comunicaciones interactivas, de forma automática o bajo demanda. Los clientes pueden generar salidas de impresión y Web de forma simultánea.
Consulte [Generación de varias comunicaciones interactivas mediante la API](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/generate-multiple-interactive-communication-using-batch-api.html)por lotes.

* **Plataformas compatibles con AEM Forms en JEE**

   Se ha añadido compatibilidad con Oracle 19c para AEM Forms en clientes JEE.
Consulte Plataformas [admitidas para AEM Forms en JEE](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/jee-installation/aem-forms-jee-supported-platforms.html).

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

### Campaign Classic 19.2.3

Consulte las [Notas de la versión de Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) para saber más sobre las correcciones y mejoras.

### Campaign Standard 20.1

Consulte las [Notas de la versión de Adobe Campaign Standard](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) para saber más sobre las correcciones y mejoras.

### Recursos adicionales

* Adobe Campaign Standard: [Documentación](https://helpx.adobe.com/support/campaign/standard.html) - [Notas de la versión](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Planificación de lanzamiento](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentación](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de la versión](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Panel de control de Adobe Campaign: [Documentación](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Actualizado el 10 de febrero de 2020, para la versión del 8 de febrero

| Ver | Función |
|------|---------|
| Portafolios | Ahora puede agregar Yahoo! Campañas de Japan Display Network (YDN) en portafolios para optimizar los presupuestos de campaña y las ofertas de nivel de grupo de anuncios. La misma oferta se aplica a todos los anuncios de un grupo de anuncios. Los datos de las campañas YDN se incluyen en las simulaciones del portafolio. |
| Buscar > Hojas de edición en bloque | Ahora puede crear, editar y eliminar anuncios de búsqueda interactivos (RSA) de Google mediante hojas de edición en bloque. Previously, support was available only through the standard campaign management interface at **[!UICONTROL Search]** > **[!UICONTROL Campaigns]** |
| Búsqueda > Campañas, Informes | The Google Ads prominence metrics `Impr. (Abs. Top) %` and `Impr. (Top) %` are now available in all basic reports and entity-level campaign management views except for those for shopping product groups, in the [!UICONTROL Campaign Daily Impression Share] and [!UICONTROL Keyword Daily Impression Share] reports, and in the labels and constraints views. |

## [!DNL Magento] {#magento}

Para ver las notas de la versión de Magento, consulte:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)
