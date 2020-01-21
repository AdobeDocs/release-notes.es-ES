---
title: Notas de la versión de Adobe Experience Cloud
description: Plantilla para notas de la versión de Experience Cloud
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: tm+mt
source-git-commit: f2d6f3489e183db682d62766d13be958cad5692b

---


# Notas de la versión de Adobe Experience Cloud - Enero de 2020

Nuevas funciones y correcciones en Adobe Experience Cloud.

>[!NOTE]
>Para recibir notificaciones por correo electrónico sobre próximas versiones, suscríbase a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html). La nueva información publicada tras el lanzamiento se marcará con la fecha de publicación.

**Fecha de la versión: 16 de enero de 2020**

* [Estado del sistema de Adobe ](#status)
* [Servicios principales e interfaz de Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services y Mobile SDK](#mobile)
* [!DNL Analytics](#analytics) (**Actualización: 21 de enero de 2020**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (vínculos a la ayuda de la solución)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (vínculos a la ayuda de la solución)
* [!DNL Advertising Cloud](#adcloud)

¿Busca ayuda en casa? Consulte la documentación de [Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Estado del sistema de Adobe {#status}

[!UICONTROL El estado del sistema de Adobe] proporciona información detallada, actualizaciones de estado y notificaciones por correo electrónico sobre los productos en la nube de Adobe y las interrupciones y sesiones de mantenimiento de los servicios de Adobe. Puede comprobar el estado en [status.adobe.com](https://status.adobe.com/).

**Novedades**

* Con su Adobe ID, puede suscribirse a las notificaciones de eventos en función de sus preferencias de productos, regiones y eventos. A los usuarios que configuran sus preferencias de suscripción solo se les notifican los eventos de mantenimiento e incidencias del producto relevantes en cuanto se abran, actualicen o cierren. Empiece por [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nuevas funciones y mejoras disponibles**

| Función | Descripción |
| -----------| ---------- |
| Suscribirse a las notificaciones proactivas por correo electrónico | <ul><li>Compatibilidad con Experience Cloud, Creative Cloud, Document Cloud, Adobe Experience Platform y Adobe Services</li><li>Compatibilidad con las preferencias de región y tipo de evento</li></ul> |
| Administrar las preferencias de notificación | <ul><li>Editar y guardar las preferencias de notificaciones en cualquier momento</li><li>Cancelar la suscripción a las notificaciones en cualquier momento</li></ul> |
| Envío de correo electrónico personalizado y más rápido | <ul><li>Las notificaciones de eventos se envían en cuanto se abren, actualizan o cierran los eventos</li><li>Recibir solo las notificaciones de eventos relevantes que coincidan con las preferencias configuradas</li><li>Recibir notificaciones localizadas basadas en el idioma configurado en las preferencias de la cuenta</li></ul> |
| Obtener notificaciones personalizadas en el producto | <ul><li>Los eventos que coinciden con las preferencias de notificación y las autorizaciones del producto aparecen en el panel Anuncios</li></ul> |

## Servicios principales e interfaz de Experience Cloud{#ecloud}

Nuevas funciones y correcciones en la interfaz de Experience Cloud, incluida la administración y los servicios principales (atributos del cliente, audiencias, desencadenadores, cookies, etc.).

### Dominio de producto unificado

Adobe está actualizando el encabezado de la interfaz y el dominio para unificar y mejorar el funcionamiento de las aplicaciones de Experience Cloud. Estas mejoras están diseñadas para mejorar sutilmente su experiencia. Estas mejoras no cambiarán los flujos de trabajo actuales.

Las actualizaciones incluyen:

* Nuevas direcciones URL de la solución: `experience.adobe.com/<application name>`:
   * Todos los productos finalmente adoptarán este patrón de URL. Busque nuevas direcciones URL que entren en vigor durante el mes.
   * Compatibilidad con navegadores:Los exploradores admitidos son [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari]y [!DNL Opera] (versiones más recientes). **** Nota: Aunque la interfaz de Experience Cloud admite estos exploradores, es posible que las soluciones individuales no admitan todos los exploradores. (Por ejemplo, [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) no es compatible [!DNL Opera]y [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) no lo es [!DNL Safari]).
   * ([!DNL Safari] solo) El cambio de dominio puede causar problemas de cookies en [!DNL Safari]. Unchecking _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain.
* Es más fácil cambiar entre las organizaciones o a otra aplicación.
* Ayuda del producto mejorada: [!UICONTROL Experience League] está integrada en el producto, por lo que una búsqueda de ayuda también incluye resultados de foros de la comunidad y contenido de vídeo. Este cambio simplifica el acceso a más contenido y le ayuda a sacar el máximo rendimiento de Experience Cloud. Además, puede hacer clic en **[!UICONTROL Ayuda]**>**[!UICONTROL  Comentarios]** para informar sobre problemas o compartir sus ideas con Adobe.
* Notificaciones mejoradas: El menú desplegable [!UICONTROL Notificaciones] ahora tiene dos pestañas, una para sus propias notificaciones de productos y otra para los anuncios de productos globales.

**Nota:** La página [!UICONTROL Fuente] dejará de usarse en enero de 2020. Busque un aviso de obsolescencia del producto.

Para obtener documentación del producto, consulte [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

### Cookies de Experience Cloud

Adobe está ajustando la configuración de las cookies `same-site` para prepararse para los cambios que Chrome realizará en Chrome 80 (que se lanzará en febrero de 2020).

No es necesario realizar cambios a menos que utilice un CNAME para la recopilación de datos de origen, sino que utilice ese CNAME en varios dominios (dominios de terceros prácticos) y no utilice el servicio de ID de Experience Cloud (visitante). Con la versión Chrome 80, Chrome proporciona automáticamente a las cookies de ID de visitante de Analytics un valor SameSite de `Lax,`, lo que impide que se use en los demás dominios. Si desea seguir utilizando su CNAME en todos sus dominios, debe ponerse en contacto con el Servicio de atención al cliente de Adobe y solicitar que cambien el valor SameSite de su CNAME a `None.`

Tenga en cuenta que Adobe recomienda utilizar un CNAME independiente para cada uno de los dominios, tanto si utiliza el servicio de Experience Cloud ID como si no.

[Más…](https://medium.com/adobetech/adobe-experience-cloud-cookie-updates-for-google-chrome-19ad67cf1598)

## Experience Platform {#platform}

Notas de la versión de Experience Platform, Experience Platform Launch, servicios de identidad y boletines de seguridad.

* [Notas de la versión de Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Boletines de seguridad y avisos](https://helpx.adobe.com/security.html) (Todos los productos de Adobe)

### Experience Platform Launch {#launch}

Consulte [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) para ver notas de la versión y documentación del producto.

## Mobile Services y Mobile SDK{#mobile}

16 de enero de 2020: Versión 4.18.0

* Adquisición: Se ha agregado una nueva API, `Analytics.processGooglePlayInstallReferrerUrl(final String url)`, para admitir las API de referente de instalación de [!DNL Google Play].

Para obtener más información sobre la instalación de las API de referente, consulte [¿Sigue usando InstallBoradcast? Cambie a la API de referente de Play antes del 1 de marzo de 2020](https://android-developers.googleblog.com/2019/11/still-using-installbroadcast-switch-to.html).

## [!DNL Analytics] {#analytics}

Nuevas funciones y correcciones en Adobe Analytics:

* [Nuevas funciones, mejoras y correcciones en Adobe Analytics](#aa-features)     (Actualización: 21 de enero de 2020)
* [Avisos importantes para los administradores de Analytics](#aa-notices)
* [AppMeasurement](#appm)

Para obtener documentación del producto, consulte la sección [Ayuda de Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nuevas funciones, mejoras y correcciones en Adobe Analytics {#aa-features}

| Función | Descripción |
| -----------| ---------- |
| Analysis Workspace: mejoras en la interfaz de usuario | El 16 de enero de 2020, Analysis Workspace empezará a experimentar mejoras en la interfaz de usuario que abarcarán varios meses. El objetivo de estos cambios es hacer que la aplicación sea más accesible para nuestros usuarios, así como ofrecer una experiencia más coherente en Adobe Experience Cloud. |
| Analysis Workspace: Creador de tablas de forma libre | Con el Creador de tablas de forma libre, puede arrastrar y soltar varias dimensiones, desgloses, métricas y segmentos para crear tablas que respondan a preguntas comerciales más complejas. Los datos no se actualizarán inmediatamente. En su lugar, las actualizaciones se producen después de hacer clic en **[!UICONTROL Generar]**, lo que le ahorra tiempo una vez que sepa qué tabla desea crear. Además, esta función ofrece:<ul><li>**Vista previa**: Puede obtener una vista previa del formato de una tabla antes de dedicar su tiempo a procesar datos reales.</li><li>**Configuración de desglose y filas flexibles**: Puede definir los niveles de fila y desglose para cada fila de dimensión. Anteriormente, Workspace imponía valores predeterminados que no se podían cambiar hasta que se devolvían los datos.</li><li>**Desglose por posición**: Puede definir filas de dimensión para que siempre _se desglosen por posición_ en lugar de _por elemento específico_ (valor predeterminado).</li><li>**Ordenación manual de filas estáticas**: Puede ordenar manualmente las filas estáticas para que las filas de la tabla se muestren exactamente como las necesita. Anteriormente, las filas estáticas solo se podían ordenar por una columna de métrica o alfabéticamente.</li></ul>[Más información...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/freeform-table.html). |
| Nueva dimensión de [!UICONTROL Estado identificado] para el análisis entre dispositivos (CDA) | Se está agregando una nueva dimensión denominada [!UICONTROL Estado identificado] a los grupos de informes virtuales CDA. La dimensión tiene dos valores posibles, _Identificado_ y _No identificado_. _Identificado_ significa que la persona ha sido identificada por el gráfico del dispositivo. _No identificado_ significa que la persona no ha sido identificada por el gráfico del dispositivo.<br>Esto significa que los usuarios de CDA ahora pueden crear métricas calculadas, como [!UICONTROL Cobertura del gráfico de dispositivo], que describe cuántas personas dentro del grupo de informes virtuales reconoce el gráfico del dispositivo. Esta métrica es útil para solucionar problemas con las tasas de compresión de CDA. Si se identifican pocas personas, el nivel de conexión será bajo. |
| Compatibilidad con VRS en la API de Data Warehouse | Los grupos de informes virtuales ahora se pueden usar mediante la API de Data Warehouse. Anteriormente, solo estaban disponibles mediante la interfaz de usuario de Data Warehouse. Al utilizar la API de Data Warehouse, ahora puede ver y consultar los grupos de informes virtuales, pero solo si los segmentos aplicados a un grupo de informes virtuales son compatibles con Data Warehouse. |
| API de Servicio de privacidad: CCPA | La Ley de Privacidad del Consumidor de California (CCPA) mejora los derechos de privacidad y la protección del consumidor para los residentes de California, Estados Unidos. Esta ley entró en vigor el 1 de enero de 2020.<br><br/>La CCPA otorga nuevos derechos de privacidad de datos a los residentes de California, como el derecho a acceder y eliminar sus datos personales, a saber si sus datos personales se venden o revelan (y a quién) y a rechazar la venta de sus datos personales.<br><br/>El servicio de privacidad acepta solicitudes de exclusión de la venta de datos personales.<br><br/>El Servicio de privacidad, anteriormente conocido como Servicio de RGPD, conserva todas las funciones anteriores, ahora ampliadas para ser compatibles con la CCPA.<br/><br/>[CCPA en Analytics](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[Información general sobre el Servicio de privacidad](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |

#### Correcciones

* Se ha corregido un problema con las notificaciones de alerta que no se enviaban a los números de teléfono correspondientes en Egipto. (AN-197079)
* Se han corregido varios problemas con el [!DNL DFA Data Connector]. (AN-193281, AN-193075, AN-193484 y AN-193737)
* [!UICONTROL Reports &amp; Analytics]: Se ha corregido un problema con el informe Canal de conversión de productos que se cortaba y mostraba números que no eran claros. (AN-186901)
* Se ha corregido un problema que impedía a los usuarios cambiar grupos de informes en proyectos de Workspace basados en grupos de informes con la nueva arquitectura de clasificaciones. (AN-199076)
* Se ha corregido un problema que impedía que la función [!UICONTROL Acumulativa] de [!UICONTROL Métricas calculadas] funcionara correctamente. (AN-184257)

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación o actualizada | Descripción |
| -----------| ---------- | ---------- |
| Nuevo dominio de Adobe Analytics | 18 de diciembre de 2019 | El 16 de enero de 2020, Adobe Analytics empezará a pasar a un nuevo dominio. `https://experience.adobe.com/analytics.`<br>**Nota **: Este cambio se aplica a todos los usuarios que acceden a Analytics con su Adobe ID o Enterprise ID.<ul><li>Este cambio de dominio puede provocar problemas con las cookies al cargar Analytics en Safari. Al desmarcar _Impedir el seguimiento entre sitios_ en las preferencias de privacidad de Safari, se habilitarán las cookies entre dominios (y todas las experiencias entre sitios) y Analytics podrá funcionar en este nuevo dominio de Adobe Experience Cloud. Puede utilizar otros navegadores sin problemas porque esto solo afecta a los usuarios de Safari.</li><li>El cambio de dominio puede hacer que [!UICONTROL Activity Map] deje de funcionar para algunos clientes [en casos específicos](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Fin de vida útil: API heredadas de Analytics | 9 de enero de 2020 | En noviembre de 2020, los siguientes servicios de API heredadas de Analytics llegarán a su fin de vida útil y se cerrarán. Las integraciones actuales creadas con estos servicios dejarán de funcionar. <ul><li>API de Analytics 1.3</li><li>API de Analytics SOAP 1.4</li><li>Autenticación OAuth heredada (OAuth y JWT)</li></ul>Hemos creado las [Preguntas frecuentes del fin de la vida útil de la API heredada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para ayudarle a responder a sus preguntas y proporcionar instrucciones sobre cómo proceder. Las integraciones de API que emplean estos servicios pueden migrar a las [API de REST 1.4 de Analytics](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o a las [API de Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Las cuentas heredadas de OAuth pueden migrar a una cuenta de integración de Analytics [Adobe IO](https://console.adobe.io/home?mv=email), que puede utilizarse para acceder tanto a las API de Analytics 1.4 como a las API de Analytics 2.0. |
| Fecha de fin de uso de la opción **[!UICONTROL Ver archivo]** | 30 de octubre de 2019 | Anuncio de la fecha de finalización en enero de 2020 de la opción **[!UICONTROL Ver archivo]** en el Administrador de paneles (**[!UICONTROL  Componentes > Paneles]**). |
| Fecha de fin de uso de la opción **[!UICONTROL Aplicar restricciones de inicio de sesión con IP]** | 30 de octubre de 2019 | Anuncio de la fecha de finalización en enero de 2020 de la creación de listas de IP de inicio de sesión admitidas (**[!UICONTROL Aplicar restricciones de inicio de sesión con IP]**) en el menú **[!UICONTROL  Administración > Configuración de la compañía > Seguridad]**. |
| Finalización de la compatibilidad con TLS 1.1 | 3 de octubre de 2019 | A partir del 31 de marzo de 2020, Adobe Analytics dejará de ofrecer soporte para TLS 1.1. Este cambio es parte de nuestro trabajo para mantener los estándares de seguridad más altos e impulsar la seguridad de los datos del cliente. |
| Fin de la administración de datos en el centro de datos de San José para Londres y Singapur | Julio de 2020 | Para los clientes de Londres y Singapur, ya no se ofrecerá la administración de datos entre Londres o Singapur y el centro de datos de San José [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, utilice [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Singapur, utilice [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Próximos cambios en el campo `createDate` para los usuarios de Analytics | 30 de agosto de 2019 | En octubre o noviembre de 2019, el campo `createDate` de los usuarios de Analytics se actualizó de la hora del Pacífico de EE. UU. a un valor de fecha y hora con formato correcto respecto a la información de zona horaria.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

Consulte [Notas de la versión de AppMeasurement para JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Correcciones y funciones agregadas a Audience Manager.

### Nuevas funciones y correcciones en Audience Manager {#aam-features}

| Función | Descripción |
| -----------| ---------- |
| [Revisión general de la documentación de privacidad y soporte de la Ley de privacidad del consumidor de California (CCPA)](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html) | La [Ley de privacidad del consumidor de California (CCPA)](https://www.caprivacy.org/about), que entró en vigor el 1 de enero de 2020, otorga a los residentes de California nuevos derechos con respecto a su información personal e impone responsabilidades de protección de datos a ciertas entidades que realizan negocios en California. <br><br> Audience Manager ayuda a cumplir con sus obligaciones en virtud de las normativas de privacidad, a través de herramientas de privacidad como [Adobe Experience Platform Privacy Service](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html) para solicitudes de acceso y eliminación de datos. <br><br> Hemos actualizado el proceso actual de [administración de exclusión](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#opt-out-requests) para añadir la exclusión de cualquier ID declarado (por ejemplo, ID de CRM). En caso de exclusión por ID declarado, el ID declarado y el último dispositivo vinculado se excluirán de la recopilación de datos de Audience Manager. Las solicitudes de exclusión ahora también envían solicitudes de anulación de la segmentación a [socios de destino](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#aam-partners-with-unsegmentation) que admiten esta función, tanto en lote como en tiempo real. <br><br> Además, hemos rediseñado nuestra documentación sobre [seguridad de datos](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-security.html), [privacidad de datos](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html) y [administración de datos](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-governance.html) para facilitarle la búsqueda de la información necesaria para cumplir con las regulaciones mencionadas. |

### Correcciones y mejoras {#aam-fixes-and-improvements}

* Se corrigió un problema en el flujo de trabajo [!UICONTROL Crear destino] en el cual, al seleccionar **[!UICONTROL Plataformas integradas]**como[!UICONTROL Categoría], desaparecía la sección[!UICONTROL Información básica]y el flujo de trabajo era imposible de completar. (AAM-52397, AAM-52414)
* La página [!UICONTROL Crear/editar] destinos no se cargaba en los navegadores Apple Safari y Mozilla Firefox. Este error se corrigió. (AAM-51784)

## Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Adobe Experience Manager (AEM). Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

### Mantenimiento del producto

* **AEM 6.5.3.0**
AEM 6.5, Service Pack 3.0 (6.5.3.0 publicado el 12 de diciembre de 2019) es una actualización importante que incluye correcciones claves del cliente realizadas tras el lanzamiento general de AEM 6.5 en abril de 2019.
   * [Notas de la versión](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Versiones de AEM Forms CFP](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.7.0**

   AEM 6.4 Service Pack 7.0 (6.4.7.0 publicada el 12 de diciembre de 2019) es una actualización importante que incluye correcciones claves de cliente publicadas tras el lanzamiento general de AEM 6.4 en abril de 2018.
   * [Notas de la versión](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versiones de AEM Forms CFP](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.7**

   AEM 6.3 Service Pack 3, Cumulative Fix Pack 7 (6.3.3.7 publicada el 12 de diciembre de 2019) es una actualización importante que incluye correcciones claves de cliente publicadas tras el lanzamiento general de AEM 6.3 en abril de 2017.
   * [Notas de la versión](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versiones de AEM Forms CFP](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Desktop App 2.0.1.1**

   AEM Desktop App 2.0.1.1 proporciona una actualización para el inicio de sesión único con Okta y permite especificar la ubicación de los archivos temporales en Preferencias. La compatibilidad con AEM 6.3.x ya no se utiliza en Desktop App 2.x con esta versión.
   * [Notas de la versión](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Adobe Asset Link 1.1 finaliza la compatibilidad con AEM 6.3.x**

   La compatibilidad con AEM 6.3.x ha quedado obsoleta en Adobe Asset Link desde abril de 2019. Adobe Asset Link 1.1 no es compatible con AEM 6.3.x desde el 13 de enero de 2020.
   * [Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html)

### Versiones de productos

* **NUEVO:AEM como servicio de nube**

   [Adobe Experience Manager](https://www.adobe.com/marketing/experience-manager.html) (AEM) ya está disponible como servicio de nube.

   * [Introducción](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/overview/introduction.html)
   * [Información de versión](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/home.html)
   * [Documentación](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)

* **Servicio automatizado de conversión de formularios**

   El Servicio de conversión automatizada de formularios, el servicio para convertir automáticamente formularios PDF a formularios HTML preparados para dispositivos móviles, se publicó el 12 de diciembre de 2019.

   * [Introducción](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)
   * [Configurar el servicio](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/configure-service.html)
   * [Convertir formularios PDF en formularios adaptables](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/convert-existing-forms-to-adaptive-forms.html)

### Autoayuda

* **Vista previa de recursos 3D**

   AEM 6.5 admite la carga, la entrega y la previsualización interactiva de recursos 3D como parte del proceso de creación. El visor 3D interactivo está disponible en la página de detalles de recursos de AEM. El visor incluye, entre otras cosas, una colección de controles de cámara interactivos que le permiten orbitar, aplicar zoom y recorrer el recurso 3D.
Consulte [Previsualización de recursos 3D](https://docs.adobe.com/content/help/en/experience-manager-65/assets/using/previewing-3d-assets.html).

* **Componentes principales**

   La versión 2.8.0 de Componentes principales ya está disponible junto con la [documentación de creación](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) y los [detalles del desarrollador y la descarga del proyecto disponibles en GitHub](https://github.com/adobe/aem-core-wcm-components).

* **Arquetipo de AEM Project**

   El [módulo ui.frontend ](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/uifrontend.html)del [Arquetipo de proyecto de AEM](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html) es una herramienta útil y flexible para facilitar el desarrollo del front-end de su proyecto de AEM.

### Recursos adicionales

* [AEM como servicio de nube](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
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

### Campaign Classic 19.2

| Funcionalidad | Descripción |
| ------------- | ----------- |
| Ley de privacidad del consumidor de California (CCPA) | La CCPA es la nueva ley de privacidad del Estado de California que armoniza y moderniza los requisitos de protección de datos y que entró en vigencia el 1 de enero de 2020. La CCPA se aplica a los clientes de Adobe Campaign que tienen datos de los sujetos de datos que residen en California. <br> Además de las funciones de privacidad ya disponibles (incluida la administración de consentimiento, la configuración de retención de datos y las funciones de usuario), Adobe Campaign le ayuda prepararse para la CCPA: <ul><li>_Derecho de acceso_ y _derecho de eliminación_: estamos aprovechando las funcionalidades agregadas para el RGPD. [Más información](https://helpx.adobe.com/campaign/kb/acc-privacy.html#righttoaccess) </li><li>Puede rastrear si un consumidor se ha excluido de la venta de Información personal. Para ello, debe ampliar la tabla [!UICONTROL Perfiles] y agregar un campo **[!UICONTROL Opción de exclusión para la CCPA]**.[Más información](https://helpx.adobe.com/campaign/kb/acc-privacy.html#ccpa)</li></ul> Consulte el [videotutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html). |
| Seguimiento de flujos de trabajo en vivo | Ahora puede supervisar el estado de ejecución de todos los flujos de trabajo de la instancia mediante vistas predefinidas. <br> Para obtener más información, consulte [Filtrado de flujos de trabajo según su estado](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/monitoring-workflows/monitoring-workflow-execution.html#filtering-workflows-status). |
| Contenido interactivo con AMP | Adobe Campaign permite probar el nuevo formato interactivo [AMP para correo electrónico](https://amp.dev/about/email/), que permite a los especialistas en marketing incluir componentes de AMP dentro de los mensajes para mejorar la experiencia de correo electrónico con contenido enriquecido, dinámico, interactivo y que se puede procesar directamente en el mensaje. <br> Esta funcionalidad se presenta como una versión beta pública. <br> Para obtener más información, consulte la [documentación detallada](https://docs.adobe.com/content/help/en/campaign-classic/using/sending-messages/sending-emails/defining-interactive-content.html) y el [videotutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/sending-messages/email-channel/defining-interactive-email-content-with-amp.html). |
| Mensajería SMS segura (TLS) | Ahora se admiten mensajes SMS seguros a través del conector genérico SMPP extendido. Esto permite establecer una conexión cifrada al proveedor. <br> **Advertencia**: Esta función requiere un certificado actualizado en todos los servidores. Los certificados no válidos, revocados o caducados generarán errores que afectarán a las capacidades generales de envío de mensajes SMS. <br> Para obtener más información, consulte la [documentación detallada](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html). |

Consulte las [Notas de la versión de Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) para saber más sobre las correcciones y mejoras.

### Campaign Standard 19.4

| Funcionalidad | Descripción |
| ------------- | ----------- |
| Ley de privacidad del consumidor de California (CCPA) | La CCPA es la nueva ley de privacidad del Estado de California que armoniza y moderniza los requisitos de protección de datos y que entró en vigencia el 1 de enero de 2020. La CCPA se aplica a los clientes de Adobe Campaign que tienen datos de los sujetos de datos que residen en California. <br> Además de las funciones de privacidad ya disponibles en Adobe Campaign (incluida la administración de consentimiento, la configuración de retención de datos y las funciones de usuario), aprovechamos esta oportunidad para incluir funciones adicionales que le ayudarán a prepararse para la CCPA: <ul><li> Derecho de acceso y derecho de eliminación: estamos aprovechando las funcionalidades agregadas para el RGPD. [Más información](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#righttoaccess) </li><li> Al crear una solicitud de privacidad, se ha agregado el tipo de regulación (RGPD o CCPA) en el servicio principal de privacidad. Este método es el que debe utilizar para todas las solicitudes de acceso y eliminación. El uso de la API de Campaign y la interfaz para acceder y eliminar solicitudes está en desuso. Consulte el artículo [Funciones obsoletas y eliminadas](https://helpx.adobe.com/campaign/kb/acs-deprecated-and-removed-features.html). </li><li> Se ha agregado un campo de **exclusión de CCPA** al recurso Perfiles para permitir a los usuarios de Adobe Campaign realizar un seguimiento sobre si un cliente ha decidido excluirse de la venta de Información personal. [Más información](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#ccpa) </li></ul> Consulte el [videotutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html). |
| Integración de Microsoft Dynamics 365 (GA) | Ya está disponible la integración entre Adobe Campaign Standard y Microsoft Dynamics 365. Podrá transferir los registros de contacto y de entidad personalizada de Dynamics 365 a Campaign y recuperar los datos de eventos de correo electrónico de Campaign en Dynamics 365 para mejorar la alineación de ventas y marketing. <br> Consulte la [documentación detallada](https://helpx.adobe.com/campaign/kb/acs-ms-dynamics.html) para configurar esta integración y consulte el [videotutorial](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/integrating/microsoft-dynamics365-connector/introduction.html). |

Consulte las [Notas de la versión de Adobe Campaign Standard](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) para saber más sobre las correcciones y mejoras.

### Panel de control de Adobe Campaign

Hemos agregado nuevas funciones para que los usuarios administradores deleguen subdominios y renueven certificados SSL desde el Panel de control.

Para obtener más información, consulte estas páginas:

* Configuración de un nuevo subdominio: [Más información](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)
* Renovación del certificado SSL de un subdominio: [Más información](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html)

>[!CAUTION]
>
>Estas funciones estarán disponibles en versión beta a finales de enero y estarán sujetas a frecuentes actualizaciones y modificaciones sin previo aviso.

### Recursos adicionales

* Adobe Campaign Standard: [Documentación](https://helpx.adobe.com/support/campaign/standard.html) - [Notas de la versión](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Planificación de lanzamiento](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentación](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de la versión](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Panel de control de Adobe Campaign: [Documentación](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Actualizado para la versión del 11 de enero de 2020

| Ver | Función |
|------|---------|
| Seguimiento de conversión | Todas las cookies de Advertising Cloud se han actualizado para cumplir con los nuevos requisitos de control de cookies de Google Chrome 80, que se lanzarán el 4 de febrero. Los cambios se implementaron desde los servidores de Adobe utilizando las cookies existentes, sin ningún efecto en las métricas de los visitantes. No se requieren actualizaciones del anunciante. |
| Perspectivas > Alertas beta, Buscar > Campañas | (Función beta solo para cuentas de búsqueda) Una nueva versión beta de alertas permite crear plantillas de alerta para identificar cuándo cualquier campaña de búsqueda, grupo de publicidad, palabra clave o publicidad cumple determinadas condiciones (como métricas de rendimiento) durante un período especificado y, después, generar una alerta. Las alertas están disponibles para un solo anunciante. |
| Informes | Los datos de la publicidad sobre catálogos ahora se incluyen en los informes Clasificación de etiquetas, Valor de etiqueta, Regla de oferta y Restricción. |
