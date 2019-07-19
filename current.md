---
title: Notas de la versión de Adobe Experience Cloud
description: Notas de la versión de Experience Cloud de julio de 2019
doc-type: notas de la versión
last-update: Julio de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 50a8aaf58413337e4aa0478e5505f8ea9d8edd36

---


# Notas de la versión de Adobe Experience Cloud

Nuevas funciones y correcciones en Adobe Experience Cloud.

>[!NOTE]
>
>Suscríbase a la [actualización de producto prioritaria de Adobe](https://www.adobe.com/subscription/priority-product-update.html) para recibir notificaciones por correo electrónico de las próximas versiones. Recibirá el aviso entre tres y cinco días laborables antes del lanzamiento de la versión. La nueva información publicada tras el lanzamiento se marcará con la fecha de publicación.

**Fecha de la versión: 18 de julio de 2019**

* [Administración y servicios principales de Experience Cloud](#experiencecloud)
* [!DNL Analytics](#analytics)**(Actualizado el 15 de julio)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)

## Core services and administration {#experiencecloud}

Notas de la versión de la interfaz de Experience Cloud, incluidos los servicios principales de [!UICONTROL plataforma] y la administración de productos.

* [Servicio Experience Cloud ID](#ecid)
* [Mobile Services y Mobile SDK](#mobile)
* [Experience Platform Launch](#launch)
* [Boletines de seguridad y consejos](#security)

### Servicio Experience Cloud ID {#ecid}

**Correcciones y actualizaciones**

* `cookieDomain` actualización de configuración: La biblioteca asignará automáticamente un dominio de cookie de nivel superior cuando `cookieDomain` no esté `initConfig` establecido. (CORE-29223)
* Fixed an issue for `getVisitorValue` in `localVisitor`. (CORE-31287)
* Fixed an inconsistency of `MCOPTOUT` value in parent visitor versus iframe child visitor from `getVisitorValue` method. (CORE-29719)
* Se ha corregido un problema de vulnerabilidad en jquery 3.2.1. (CORE-31183)
* Opt-in update: added `optIn.off` to unsubscribe from events.
* Fixed an issue related to `setTimeout` function. (CORE-30623)

See [Experience Cloud ID Service](https://marketing.adobe.com/resources/help/en_US/mcvid/mcvid-release-notes.html) for cumulative release notes.

### Mobile Services y Mobile SDK {#mobile}

iOS y Android se actualizaron de la siguiente manera:

**iOS**

* Adobe Target: All requests now include the client and the `sessionId` in the URL query parameters.
* Adobe Target: Se ha corregido una fuga de memoria.
* Visitor ID Service: The `visitorAppendToURL` and `visitorGetUrlVariablesAsync` APIs no longer double-encode their return values. La doble codificación estaba ocasionando que los valores devueltos de esas API se marcaran con indicadores de ciertas revisiones de seguridad.

**Android**

* Target: Todas las solicitudes ahora incluyen el cliente y el sessionid en los parámetros de consulta de URL.
* Mensajería en la aplicación: Se ha corregido un problema por el que, cuando un mensaje se activaba con una URL de pulsaciones vacías, las aplicaciones de Android se bloqueaban.
* Visitor ID Service: The `Visitor.appendToURL` and `Visitor.getUrlVariablesAsync` APIs no longer double-encode their return values. La doble codificación estaba ocasionando que los valores devueltos de esas API se marcaran con indicadores de ciertas revisiones de seguridad.

Para obtener documentación del producto, consulte [Mobile Services](https://docs.adobe.com/content/help/en/mobile-services/using/home.html).

Para obtener más información sobre los SDK de Mobile, consulte [SDK de Android para soluciones de Experience Cloud 4.x](https://docs.adobe.com/content/help/en/mobile-services/android/overview.html) y [SDK de iOS para soluciones de Experience Cloud 4.x](https://docs.adobe.com/content/help/en/mobile-services/ios/overview.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) (links to product help) for release notes and product documentation.

### Security bulletins and advisories {#security}

See [Security bulletins and advisories](https://helpx.adobe.com/security.html) for important information regarding security vulnerabilities that could affect specific versions of Adobe products.

## [!DNL Analytics] {#analytics}

* [Nuevas funciones y correcciones en Adobe Analytics](#aa-features) **(Actualización: 15 de julio)**
* [Avisos importantes para los administradores de Analytics](#aa-notices)

### Nuevas funciones de la versión [!DNL Analytics] {#aa-features}

Para obtener la documentación del producto, consulte la [Página principal de ayuda de Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

| Componente | Descripción |
| -----------| ---------- |   
| Analysis Workspace: mejoras de Análisis de cohorte | New [Cohort Analysis settings](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/cohort-table/t-cohort.html) have been added: <ul><li>Mostrar sólo porcentaje</li><li>Porcentaje redondeado al más próximo</li><li>Mostrar una fila porcentual promedio</li></ul> |
| Analysis Workspace | In the left rail, users now have the option to _Show items from last 18 months_. Anteriormente, el período retroactivo era de 6 meses como máximo. Esto facilita la comparación con páginas o campañas del último año, hasta hace 18 meses. |
| Nueva plantilla de Analysis Workspace | We added a new template called ["Magento: Marketing &amp; Commerce"](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/starter-projects.html) to Analysis Workspace. Está diseñada específicamente para los clientes de comercio electrónico de Magento, pero cualquier minorista puede utilizarlo para obtener perspectivas únicas sobre sus actividades comerciales. |

#### [!DNL Analysis Workspace] correcciones

* Se ha corregido un problema que hacía que se mostraran al revés los caracteres de byte múltiple al desglosar dimensiones. (AN-180112)
* Se ha corregido un problema con los errores de visualización: ahora se muestra una barra de error rojo cuando se produce un error de visualización.(AN-175542)
* Se ha corregido un problema por el que los nombres de dimensiones aparecían como inglés en entornos localizados.(AN-178695)

#### [!DNL Analytics] correcciones

* Se ha corregido un problema que provocaba que el gráfico de líneas en un informe detallado en tiempo real estuviera en blanco. (AN-181690)
* Se corrigió un problema en el cual, en algunas circunstancias, las partes del historial de fuentes de datos no se mostraban en la interfaz de usuario de la Consola de administración. (AN-176219)

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación  o actualizada | Descripción |
| -----------| ---------- | ---------- |
| Límites del Generador de reglas de clasificación | Añadidos el 5 de junio de 2019. | These limits are not new, but have been added to the documentation [here](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| Nuevos límites de operadores de segmentos | Añadidos el 31 de mayo de 2019. | A partir del 18 de julio de 2019, los operadores de segmentos "contiene cualquiera de", "no contiene ninguno de", "contiene todo" y "no contiene todos" se limitan a 100 palabras por campo de entrada. El límite se aplicará a todos los segmentos nuevos y modificados después de esta fecha. Los segmentos existentes que excedan el límite seguirán siendo compatibles, pero no se podrán modificar ni guardar hasta que se reduzca el número de palabras del campo de entrada. Estos límites se aplican como parte de un intento continuo por mejorar el rendimiento de la consultas. |
| Próximos cambios de soporte para las **[!UICONTROL clasificaciones numéricas]** y con **[!UICONTROL fecha habilitada]** | Actualizado el 28 de mayo de 2019 | Se ha eliminado de la base de código la posibilidad de importar clasificaciones numéricas 2 y fechas activadas. Este cambio entra en vigor con el lanzamiento de mantenimiento de julio de 2019. Si tiene columnas numéricas o con fecha habilitada en el archivo de importación, esas celdas serán omitidas sin aviso y cualquier otra información de ese archivo se importará como de costumbre. <br/>Las clasificaciones existentes se pueden exportar a través del flujo de trabajo de clasificación estándar y seguirán estando disponibles en los informes. |
| Futuros cambios en los cálculos _Total de informes_ | actualizado el 9 de julio de 2019 | El **18 de junio de 2019**, Adobe Analytics unificará los cálculos _Total de informes_ en todas sus dimensiones y métricas. Por tanto, se cambiarán los totales de algunos informes (Prop o informes de atributos del consumidor) Antes de este cambio, algunos totales de informes no incluían el elemento de línea _Sin especificar_ en el total, independientemente de si el valor _Sin especificar_ aparecía en el informe o no. <br/>A partir del 18 de junio de 2019, el valor _Sin especificar_ aparecerá siempre en el total de los informes, aunque no aparezca en él como un elemento de línea. Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change, specifically dimensions where _Unspecified_ has a special name such as the "Typed/Bookmarked" line item for Referrer Type dimension or the "Other" line item for the Device Type dimension. Este cambio afectará a Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder y a la API de informes. |
| Actualización de las descargas de CSV desde [!DNL Analysis Workspace] | 10 de abril de 2019 | A partir del 11 de abril de 2019, se realizarán varios cambios en las **[!UICONTROL descargas de CSV]** (y en **[!UICONTORL Copiar al Portapapeles]**) desde [!DNL Analysis Workspace] para eliminar el formato de los datos exportados.  <ul><li>El separador de miles ya no se incluye. Se seguirá incluyendo el separador decimal y se respetará el formato definido dentro de **[!UICONTROL Componentes &gt; Configuración de informes &gt; Separador de miles]**. Nota: Los valores numéricos que utilizan una coma como separador decimal seguirán citados en el CSV exportado.</li><li>No se mostrarán símbolos de moneda.</li><li>No se mostrarán símbolos de porcentajes. Los porcentajes estarán en formato decimal. Por ejemplo, 75 % estará representado como 0,75.</li><li>El tiempo se mostrará en segundos.</li><li>Las tablas de cohorte muestran solo valores sin procesar; se eliminan los porcentajes.</li><li>Si un número no es válido, se mostrará una celda vacía.</li></ul> |
| Cambio en el comando de Debugger [!DNL Analysis Workspace] | 4 de abril de 2019 | El comando Console para activar el [!DNL Analysis Workspace] Debugger cambia a adobeTools.debug.includeOberonXml el **13 de junio de 2019**. adobe.tools.debug.includeOberonXml dejará de funcionar a partir de esa fecha. |
| Números de versión de los navegadores web | 7 de febrero de 2019 | A partir del 8 de enero de 2019, cambiamos el nivel de truncamiento para los números de versión de navegadores web de 2 a 1. A partir de esa fecha, las versiones solo mostrarán los dos primeros niveles (por ejemplo, _Firefox 64.0.2_ ahora aparece como _Firefox 64.0_). |
| Finalización del servicio de [!DNL Ad Hoc Analysis] | 29 de enero de 2019 | El 6 de agosto de 2018 Adobe anunció su intención de finalizar el servicio de [!DNL Ad Hoc Analysis]. La fecha se hará pública una vez que esté disponible.<br/>Para obtener más información, incluidas las versiones de Java compatibles durante este periodo, visite [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Short [!DNL Analytics] report links | 14 de enero de 2019 | Any short [!DNL Analytics] report links that have not been visited within one year will be cleaned up and deleted starting on Thursday, January 17, 2019, on a rolling schedule. |
| Finalización de la compatibilidad con TLS 1.0 | Actualizado 10 de enero de 2019 | Desde el 11 de febrero de 2019, los informes de Adobe Analytics no son compatibles con el cifrado TLS (Transport Layer Security) 1.0. Este cambio forma parte de nuestros continuos esfuerzos por mantener los estándares de seguridad más elevados y fomentar la protección de los datos de nuestros clientes. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/>[!DNL Analytics] Desde el 20 febrero de 2019, la recopilación de datos de Adobe no es compatible con TLS 1.0. Este cambio significa que Adobe ya no recopila datos de Analytics de los usuarios finales que utilicen dispositivos antiguos o exploradores web incompatibles con TLS 1.1 o posteriores. No esperamos que esto tenga un impacto significativo en los datos de los clientes ni en los informes. (Si el sitio web ya no ofrece compatibilidad con TLS 1.0, usted no se verá afectado). <br/>A partir del 11 de abril de 2019, la API de informes de Adobe Analytics ya no será compatible con el cifrado TLS 1.0. Los clientes que acceden a la API deben verificar que no se verán afectados. <ul><li>Los clientes de API que utilicen Java 7 con la configuración predeterminada deberán realizar [ modificaciones para que sea compatible con TLS 1.2](https://www.java.com/en/configure_crypto.html). (Consulte _Cambio de la versión de protocolo TLS predeterminada para puntos finales del cliente: de TLS 1.0 a TLS 1.2_). </li><li>Los clientes de API que usen Java 8 no deberían tener problemas, ya que la configuración predeterminada es TLS 1.2.</li><li> Los clientes de API que usen otros módulos deben ponerse en contacto con su proveedor para obtener más información acerca de la compatibilidad con TLS 1.2.</li></ul> |
| Canal de datos: cambio de tamaño de la columna post_product_list | 9 de enero de 2019 | El 7 de febrero de 2019, Adobe aumentó el tamaño de la columna post_product_list de 64 KB a 16 MB. El objetivo de este cambio es garantizar que los valores eVar de comercialización añadidos a post_product_list durante el procesamiento no provoquen la solapación entre los valores de ingresos y el producto. Si tiene procesos que consumen valores de post_product_list, compruebe que dichos procesos puedan gestionar valores de hasta 16 MB de longitud; de lo contrario, el valor se truncará a los 16 KB para evitar fallos producidos por el consumo de datos. |
| Cambios de administración que afectan a los puntos de conexión de [!DNL Analytics Live Stream] inactivos | 20 de diciembre de 2018 | A partir del 1 de febrero de 2019, puede que se deshabiliten los puntos de conexión de [!DNL Live Stream] que no tengan conexiones activas de consumidores durante 90 días. Póngase en contacto con el Servicio de atención al cliente para consultar sobre sus puntos de conexión de [!DNL Live Stream] y, si es necesario, solicitar que los vuelvan a habilitar. Además, asegúrese de que los procesos de consumidores mantengan una conexión persistente, tal como se pretende desde el diseño del servicio, y que se implementen para reconectar cuando se desconecte o interrumpa la conexión. |
| Actualizar el [!DNL Report Builder] de Adobe debido al fin de la compatibilidad con TLS 1.0 | 7 de septiembre de 2018 | Debido al fin de la compatibilidad con TLS 1.0, recomendamos a los usuarios de [!DNL Report Builder] que descarguen ARB v5.6.21 antes de febrero de 2019. Después de esta fecha, las versiones anteriores de dejarán de [!DNL Report Builder] funcionar. |

### AppMeasurement {#appm}

Publicado el 15 de julio de 2019:

**Appmeasurement para JavaScript 2.15.0**

* Se ha agregado el seguimiento de alcance de desplazamiento de Activity Map a la extensión Mapa de actividades (AN -172949)
* Se agregó DIL 9.2 a appmeasurement. (AN-182472)

Consulte el [Historial de versiones de AppMeasurement](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html) para ver el historial de versiones de AppMeasurement en las plataformas siguientes:

* JavaScript
* iOS
* Android
* Flash-Flex
* OSX
* Windows Phone, XBOX, Silverlight y .NET
* [!DNL BlackBerry]
* Java
* PHP
* Symbian

### Data Workbench {#aa-dwb}

* Updated the help definition for [log (X, B)](https://marketing.adobe.com/resources/help/en_US/insight/client/c_syntx_mtrc_exp.html) metric syntax documentation. (AN-180527)

Vea las [Notas de la versión del Data Workbench](https://marketing.adobe.com/resources/help/en_US/insight/whatsnew/) para obtener la información más reciente.

## Audience Manager {#aam}

**Correcciones y mejoras**

* On the [!UICONTROL Segments Overview] page, the width of the segment storage folder is now flexible. Esto permite distinguir entre segmentos con nombres más largos. (AAM-48400)
* Fixed an issue in [!UICONTROL Algorithmic Models], where moving the **Adjust Reach &amp; Accuracy** slider did not affect the model's reach or accuracy. (AAM-47996)
* Se corrigió un problema en destinos de Analytics en el que se dañaba el botón para descargar un archivo. csv de segmentos que entran en conflicto con los controles de exportación de datos o las normativas de uso compartido de datos de terceros. (AAM-48100)
* Se corrigió un problema en el cual los clientes veían errores aleatorios de "Acceso denegado" al iniciar sesión en la interfaz de usuario de Audience Manager. (AAM-47632)

## Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Adobe Experience Manager (AEM). Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

### Versiones de productos

Información sobre nuevas funciones para los productos siguientes:

#### Cloud Manager 2019.6.0

The latest Cloud Manager release (2019.6.0) contains a new [Product Update Wizard](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/product-update-wizard/overview-productupdate-wizard.html) to help customers successfully run an AEM update.

* [Notas de la versión para Cloud Manager 2019.6.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

#### Documentación XML 3.4

La solución Documentación XML 3.4 ya está disponible.

***Notas de la versión***

* Se ha añadido la compatibilidad con AEM 6.5.
* Cambios del editor:
   * Vista previa del nivel de mapa.
   * Tables - provided an option to copy an `entry` or a `complete` row within a table using copy and paste.
   * Tablas: se ha proporcionado una opción para seleccionar varias celdas en una columna, o para combinarlas o combinarlas.
   * Tablas: permite establecer las propiedades de columna de tabla en el modo Autor del editor web.
   * Tablas: permite ajustar las proporciones y el tamaño de las columnas en una tabla estándar.
   * Tablas: Selección de filas y columnas en la vista Autor.
   * Tablas: estilos y propiedades habilitados (alineados, valign) en el editor web para alineación de celdas de tabla.
   * Correcciones de errores en la vista de etiquetas completas, incluyendo escenarios para copiar y pegar y arrastrar y soltar contenido.
   * Mostrar títulos de temas en las fichas Editor.
   * Se han resuelto problemas de rendimiento en el editor web.
* Transferir línea de base al contenido traducido durante la traducción.
* Ajuste preestablecido de condición de transferencia durante el flujo de trabajo de traducción.
* Se ha añadido la capacidad de aplicar etiquetas a todos los dependientes de un mapa desde la línea base.
* Se ha proporcionado un botón para descargar el mapa con todas las dependencias como un zip.
* XHTML to DITA conversion improvements to the following:
   * El nombre del DITAMAP generado ahora es idéntico al nombre del archivo zip cargado.
   * Se agregó compatibilidad con elementos y atributos HTML adicionales.
   * Compatibilidad con la ingesta de archivos HTML-zip simultánea.
   * The sub-folder hierarchy where the zip is uploaded (*under input path as configured in h2d_io.xml*), is retained for the generated output (*under the configured output path*).
* Se proporcionaron registros de auditoría para ver quién volvió a la versión y por qué.
* Regeneración del sitio AEM:
   * Deshabilitar la regeneración para los submapas.
   * Flujos de trabajo de generación de publicaciones habilitados para casos de uso de regeneración.
   * Desactive la opción de regeneración para un tema sin pulsar y active la opción para el tema principal donde se aplica el atributo chunked.
* La búsqueda DITA funciona ahora en la lógica AND de la búsqueda de recursos AEM.
* Los resultados no muestran los archivos temporales almacenados en la carpeta de salida de traducción.
* Ficha Línea base:
   * Mejoras de rendimiento al abrir una línea de base.
   * Elección de temas por fecha para trabajar en la marca de tiempo del cliente.
* API para eliminar etiquetas.

#### Mantenimiento del producto

**AEM 6.2 SP1-CFP20**

AEM 6.2 Service Pack 1: Cumulative Fix Pack 20 (6.2.1.20), publicado el 6 de junio de 2019, es una actualización importante que incluye correcciones clave de cliente publicadas tras la disponibilidad general de AEM 6.2 SP 1 diciembre de 2016.

* [Notas de la versión](https://helpx.adobe.com/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html)
* [Versiones de AEM Forms CFP](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3.3.5**

AEM 6.3.3.5, publicado el 3 de julio de 2019, es una actualización importante que incluye correcciones clave de cliente publicadas tras la disponibilidad general de AEM 6.3 en abril de 2017.

* [Notas de la versión](https://helpx.adobe.com/experience-manager/6-3/release-notes/sp3-release-notes.html)
* [Versiones de AEM Forms CFP](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.4.5.0**

AEM 6.4.5.0, publicado el 3 de julio de 2019, es una actualización importante que incluye correcciones clave de cliente publicadas tras la disponibilidad general de AEM 6.4 en abril de 2018.

* [Notas de la versión](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
* [Versiones de AEM Forms CFP](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.5.1.0**

AEM 6.5.1.0, publicado el 3 de julio de 2019, es una actualización importante que incluye correcciones clave de cliente publicadas tras la disponibilidad general de AEM 6.5 en abril de 2019.

* [Notas de la versión](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
* [Versiones de AEM Forms CFP](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Autoayuda

**Actualización de invalidación de caché de AEM**

An important AEM patch for the AEM 6.5 clientlibs cache invalidation is available by way of the [AEM 6.5.1.0 update](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html) or this [KB article](https://helpx.adobe.com/experience-manager/kb/avoid-crx-quickstart-deletion-in-aem-6-5.html).

### Recursos adicionales

* [Página de inicio de Learn &amp; Support de AEM 6.5](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Inicio de Información y asistencia de AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Inicio de Información y asistencia de AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Inicio de Información y asistencia de AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guía del usuario de Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Versiones anteriores de la documentación de AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Notas de la versión de Scene7 Publishing System](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notas de la versión de Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign permite entregar, de forma intuitiva y automatizada, mensajes privados a través de canales de marketing en línea y sin conexión. Ahora puede anticipar los deseos de los clientes mediante experiencias basadas en sus hábitos y preferencias.

Para ver las notas de revisión, consulte:

* Adobe Campaign Classic [19.1.2](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – build 9029
* Adobe Campaign Standard [19.2.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-3---june-2019)
* Adobe Campaign Standard [19.2.4](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-4---june-2019)
* Adobe Campaign Standard [19.2.7](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-7---july-2019)

Para obtener información del producto, consulte:

* Adobe Campaign Standard: [Documentación](https://helpx.adobe.com/support/campaign/standard.html) - [ Notas de la versión](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ Vídeos de presentación](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Documentación](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de la versión](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos de presentación](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## [!DNL Target] {#target}

See [Target release notes (pre-release)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) for the latest release infomration about Target.

## Magento {#magento}

Para obtener información sobre las notas de la versión de Magento Commerce y Magento Open Source, consulte:

* [Notas de la versión de Magento Open Source 2.3.2](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2OpenSource.html)
* [Notas de la versión de Magento Commerce 2.3.2](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2Commerce.html)
