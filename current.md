---
title: Notas de la versión de Adobe Experience Cloud
description: Plantilla para notas de la versión de Experience Cloud
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 8a895d104abd20910aa37ec2ec3b6eeaccd8c461

---


# REVISIÓN INTERNA - Notas de la versión de Adobe Experience Cloud - Enero de 2020

Nuevas funciones y correcciones en Adobe Experience Cloud.

> [!NOTE] Para recibir notificaciones por correo electrónico sobre próximas versiones, suscríbase a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html). La nueva información publicada tras el lanzamiento se marcará con la fecha de publicación.

**Fecha de versión: Enero de 2020**

* [Interfaz de Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (vínculos a la ayuda de la solución)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (vínculos a la ayuda de la solución)
* [!DNL Advertising Cloud](#adcloud) (actualizado el 8/11)

¿Busca ayuda en casa? Consulte la documentación de [Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Status.adobe.com

Con su Adobe ID, puede suscribirse a las notificaciones de eventos de estado, en función de sus preferencias de productos, región y evento.

| Función | Descripción |
| -----------| ---------- |
| Suscripción a notificaciones de correo electrónico en tiempo real | <ul><li>Compatibilidad con Experience Cloud, Creative Cloud, Document Cloud, AEP y Adobe Services</li><li>Compatibilidad con las preferencias de región y tipo de evento</li><li>Compatibilidad de UX con superficies web, móviles y tabletas</li></ul> |
| Gestión de preferencias de notificaciones | <ul><li>Editar y guardar las preferencias de notificación en cualquier momento</li><li>Cancelar la suscripción a las notificaciones en cualquier momento</li><li>Elemento</li></ul> |
| Envío de correo electrónico personalizado y más rápido | <ul><li>Las notificaciones de eventos se envían en cuanto se abren, actualicen o cierren los CSO y CMR</li><li>Recibir solo las notificaciones de eventos relevantes que coincidan con las preferencias configuradas</li><li>Se han recibido notificaciones localizadas basadas en el idioma configurado en las preferencias de la cuenta</li></ul> |
| Notificaciones personalizadas en el producto | Los eventos que coinciden con las preferencias de notificación y las autorizaciones del producto aparecen en el panel Anuncio. |

## Interfaz de Experience Cloud {#ecloud}

Notas de la versión de la interfaz de Experience Cloud y la administración de productos.

* Elemento
* Elemento

Para obtener documentación del producto, consulte [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Notas de la versión de Experience Platform, Experience Platform Launch, servicios de identidad y boletines de seguridad.

* [Notas de la versión de Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Boletines de seguridad y avisos](https://helpx.adobe.com/security.html) (Todos los productos de Adobe)

### Experience Platform Launch {#launch}

Consulte [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) para ver notas de la versión y documentación del producto.

## [!DNL Analytics] {#analytics}

Nuevas funciones y correcciones en Adobe Analytics:

* [Nuevas funciones, mejoras y correcciones en Adobe Analytics](#aa-features)
* [Avisos importantes para los administradores de Analytics](#aa-notices) (**Actualización: 18 de diciembre de 2019**)
* [AppMeasurement](#appm)

Para obtener documentación del producto, consulte la sección [Ayuda de Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nuevas funciones, mejoras y correcciones en Adobe Analytics {#aa-features}

| Función | Descripción |
| -----------| ---------- | 
|  |  |

#### Correcciones

* Se ha corregido un problema que hacía que se mostrara
* Se ha corregido un problema que hacía que se mostrara

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación o actualizada | Descripción |
| -----------| ---------- | ---------- |
| Nuevo dominio de Adobe Analytics | 18 de diciembre de 2019 | El 16 de enero de 2020, Adobe Analytics pasará al nuevo dominio: https://experience.adobe.com/analytics. Este cambio puede provocar problemas con las cookies al cargar Analytics en Safari. Al desmarcar &quot;Impedir el seguimiento entre sitios&quot; en las preferencias de privacidad de Safari, se habilitarán las cookies entre dominios (y todas las experiencias entre sitios) y Analytics podrá funcionar en este nuevo dominio de Adobe Experience Cloud. Los usuarios pueden utilizar otros navegadores sin problemas, ya que esto solo afecta a los usuarios de Safari. |
| Fecha de fin de uso de la opción **[!UICONTROL Ver archivo]** | 30 de octubre de 2019 | Anuncio de la fecha de finalización en enero de 2020 de la opción **[!UICONTROL Ver archivo]**en el Administrador de paneles (**[!UICONTROL  Componentes > Paneles]**). |
| Fecha de fin de uso de la opción **[!UICONTROL Aplicar restricciones de inicio de sesión con IP]** | 30 de octubre de 2019 | Anuncio de la fecha de finalización en enero de 2020 de la creación de listas de IP de inicio de sesión admitidas (**[!UICONTROL Aplicar restricciones de inicio de sesión con IP]**) en el menú**[!UICONTROL  Administración > Configuración de la compañía > Seguridad]**. |
| Se ha actualizado la administración del atributo SameSite en las cookies | 15 de octubre de 2019 | En agosto de 2019, Adobe anunció que añadía la configuración de cookie SameSite a todas las cookies establecidas por Analytics. Se aplica una actualización lógica donde:<ul><li>Todas las cookies de terceros que no están basadas en Webkit tienen el atributo SameSite establecido en `none`.</li><li>Todas las demás cookies no tienen el atributo SameSite establecido.</li></ul> |
| Finalización de la compatibilidad con TLS 1.1 | 3 de octubre de 2019 | A partir del 31 de marzo de 2020, Adobe Analytics dejará de ofrecer soporte para TLS 1.1. Este cambio es parte de nuestro trabajo para mantener los estándares de seguridad más altos e impulsar la seguridad de los datos del cliente. |
| Fin de la administración de datos en el centro de datos de San José para Londres y Singapur | Julio de 2020 | Para los clientes de Londres y Singapur, ya no se ofrecerá la administración de datos entre Londres o Singapur y el centro de datos de San José [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, utilice [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Singapur, utilice [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| Actualización de los totales de la tabla de forma libre de Analysis Workspace | 12 de septiembre de 2019 | En octubre de 2019, las filas totales de la tabla de forma libre empezarán a contabilizar los [filtros de informe](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) aplicados. Hasta la fecha, los totales solo se han contabilizado para la segmentación. Con este cambio, se actualizarán las visualizaciones dependientes (por ejemplo, las visualizaciones de [!UICONTROL Número de resumen] vinculadas), así como los datos CSV y PDF exportados. |
| Próximos cambios en el campo `createDate` para los usuarios de Analytics | 30 de agosto de 2019 | En octubre o noviembre de 2019, el campo `createDate` de los usuarios de Analytics se actualizará de la hora del Pacífico de EE. UU. a un valor de fecha y hora con formato correcto respecto a la información de zona horaria. (AN-183468) |
| Compatibilidad con desplazamientos históricos de zona horaria | 8 de agosto de 2019 | Analytics ahora gestiona automáticamente los desplazamientos de zona horaria para las visitas con marca de hora. Después de este cambio el 8 de agosto, los sistemas que cargan los datos para el procesamiento histórico ya no necesitarán ajustar los desplazamientos de zona horaria antes de enviar los datos. |
| Límites del Generador de reglas de clasificación | Añadidos el 5 de junio de 2019 | Estos límites no son nuevos, pero se han agregado a la documentación [aquí](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Nuevos límites de operadores de segmentos | Añadidos el 31 de mayo de 2019 | A partir del 18 de julio de 2019, los operadores de segmentos _contiene cualquiera de_, _no contiene ninguno de_, _contiene todo_ y _no contiene todos_ se limitan a 100 palabras por campo de entrada. El límite se aplicará a todos los segmentos nuevos y modificados después de esta fecha. Los segmentos existentes que excedan el límite seguirán siendo compatibles, pero no se podrán modificar ni guardar hasta que se reduzca el número de palabras del campo de entrada. Estos límites se aplican como parte de un intento continuo por mejorar el rendimiento de la consultas. |
| Próximos cambios de soporte para las **[!UICONTROL clasificaciones numéricas 2]**y con**[!UICONTROL  fecha habilitada]** | Actualizado el 28 de mayo de 2019 | Se ha eliminado de la base de código la posibilidad de importar clasificaciones numéricas 2 y fechas activadas. Este cambio entra en vigor con el lanzamiento de mantenimiento de julio de 2019. Si tiene columnas numéricas o con fecha habilitada en el archivo de importación, esas celdas serán omitidas sin aviso y cualquier otra información de ese archivo se importará como de costumbre. <br/>Las clasificaciones existentes se pueden exportar a través del flujo de trabajo de clasificación estándar y seguirán estando disponibles en los informes. |
| Cambio a los cálculos _Total de informes_ | Actualizado el 9 de julio de 2019 | El **18 de junio de 2019**, Adobe Analytics unificará los cálculos _Total de informes_ en todas sus dimensiones y métricas. Por tanto, se cambiarán los totales de algunos informes (Prop o informes de atributos del consumidor). Antes de este cambio, algunos totales de informes no incluían el elemento de línea _Sin especificar_ en el total, independientemente de si el valor _Sin especificar_ aparecía en el informe o no. <br/>A partir del 18 de junio de 2019, el valor _Sin especificar_ aparecerá siempre en el total de los informes, aunque no aparezca en él como un elemento de línea. Además, los segmentos que utilizan la lógica _existe_ o _no existe_ pueden obtener resultados diferentes para algunas dimensiones después de este cambio, específicamente las dimensiones en las que _No especificado_ tiene un nombre especial como el elemento de línea &quot;Escritos o marcadores&quot; para la dimensión Tipo de referente o el elemento de línea &quot;Otro&quot; para la dimensión Tipo de dispositivo. Este cambio afectará a Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder y a la API de informes.<br>**Nota **: Este cálculo _del total_del informe ahora se denomina _Total_general. Consulte &quot;Espacio de trabajo de análisis: Actualizar a totales de tabla improvisada&quot; arriba. |
| Actualización de las descargas de CSV desde Analysis Workspace | 10 de abril de 2019 | A partir del 11 de abril de 2019, se realizarán varios cambios en las **[!UICONTROL descargas de CSV]**(y en**[!UICONTORL  Copiar al Portapapeles]**) desde Analysis Workspace para eliminar el formato de los datos exportados.  <ul><li>El separador de miles ya no se incluye. Se seguirá incluyendo el separador decimal y se respetará el formato definido dentro de **[!UICONTROL Componentes > Configuración de informes > Separador de miles]**. Nota: Los valores numéricos que utilizan una coma como separador decimal seguirán citados en el CSV exportado.</li><li>No se mostrarán símbolos de moneda.</li><li>No se mostrarán símbolos de porcentajes. Los porcentajes estarán en formato decimal. Por ejemplo, 75 % estará representado como 0,75.</li><li>El tiempo se mostrará en segundos.</li><li>Las tablas de cohorte muestran solo valores sin procesar; se eliminan los porcentajes.</li><li>Si un número no es válido, se mostrará una celda vacía.</li></ul> |
| Cambio en el comando de Debugger de Analysis Workspace | 4 de abril de 2019 | El comando Console para activar el Analysis Workspace Debugger cambia a adobeTools.debug.includeOberonXml el **13 de junio de 2019**. adobe.tools.debug.includeOberonXml dejará de funcionar a partir de esa fecha. |
| Números de versión de los navegadores web | 7 de febrero de 2019 | A partir del 8 de enero de 2019, cambiamos el nivel de truncamiento para los números de versión de navegadores web de 2 a 1. A partir de esa fecha, las versiones solo mostrarán los dos primeros niveles (por ejemplo, _Firefox 64.0.2_ ahora aparece como _Firefox 64.0_). |
| Finalización del servicio de [!DNL Ad Hoc Analysis] | 29 de enero de 2019 | El 6 de agosto de 2018 Adobe anunció su intención de finalizar el servicio de [!DNL Ad Hoc Analysis]. La fecha se hará pública una vez que esté disponible.<br/>Para obtener más información, incluidas las versiones de Java compatibles durante este período, visite [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Vínculos [!DNL Analytics] breves de informes | 14 de enero de 2019 | A partir del 17 de enero de 2019, todos los vínculos [!DNL Analytics] breves a informes de que no hayan recibido ninguna visita en el plazo de un año se limpiarán y eliminarán de forma gradual. |
| Canal de datos: cambio de tamaño de la columna post_product_list | 9 de enero de 2019 | El 7 de febrero de 2019, Adobe aumentó el tamaño de la columna post_product_list de 64 KB a 16 MB. El objetivo de este cambio es garantizar que los valores eVar de comercialización añadidos a post_product_list durante el procesamiento no provoquen la solapación entre los valores de ingresos y el producto. Si tiene procesos que consumen valores de post_product_list, compruebe que dichos procesos puedan gestionar valores de hasta 16 MB de longitud; de lo contrario, el valor se truncará a los 16 KB para evitar fallos producidos por el consumo de datos. |
| Cambios de administración que afectan a los puntos de conexión de [!DNL Analytics Live Stream] inactivos | 20 de diciembre de 2018 | A partir del 1 de febrero de 2019, puede que se deshabiliten los puntos de conexión de [!DNL Live Stream] que no tengan conexiones activas de consumidores durante 90 días. Póngase en contacto con el Servicio de atención al cliente para consultar sobre sus puntos de conexión de [!DNL Live Stream] y, si es necesario, solicitar que los vuelvan a habilitar. Además, asegúrese de que los procesos de consumidores mantengan una conexión persistente, tal como se pretende desde el diseño del servicio, y que se implementen para reconectar cuando se desconecte o interrumpa la conexión. |
| Actualizar el [!DNL Report Builder] de Adobe debido al fin de la compatibilidad con TLS 1.0 | 7 de septiembre de 2018 | Debido al fin de la compatibilidad con TLS 1.0, recomendamos a los usuarios de [!DNL Report Builder] que descarguen la versión v5.6.21 antes de febrero de 2019. Después de esta fecha, las versiones anteriores de dejarán de [!DNL Report Builder] funcionar. |

### [!DNL AppMeasurement] {#appm}

Consulte [Notas de la versión de AppMeasurement para JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

### Nuevas funciones y correcciones en Audience Manager {#aam-new-features}

| Función | Descripción |
|--- |----|
|  |  |

### Mejoras {#aam-enhancements}

Para obtener más información, póngase en contacto con su asesor de Audience Manager o con el Servicio de atención al cliente.

### Correcciones y mejoras {#aam-fixes-and-improvements}

* Se ha corregido un problema que hacía que se mostrara
* Se ha corregido un problema que hacía que se mostrara

## Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Adobe Experience Manager (AEM). Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

### Versiones de productos

### Autoayuda

* **Actualizaciones de la documentación de AEM**

   Obtenga información sobre cambios y actualizaciones importantes de la documentación de Adobe Experience Manager en los últimos tres meses.

   Consulte la [Documentación de AEM: Actualizaciones de documentación recientes](https://helpx.adobe.com/experience-manager/documentation-updates.html).

### Recursos adicionales

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

### Recursos de documentación

* Adobe Campaign Standard: [Documentación](https://helpx.adobe.com/support/campaign/standard.html) - [Notas de la versión](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Planificación de lanzamiento](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentación](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de la versión](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

| Ver | Función |
|------|---------|
|  |  |
