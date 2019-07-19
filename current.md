---
title: Notas de la versión de Adobe Experience Cloud
description: Notas de la versión de Experience Cloud de julio de 2019
doc-type: notas de la versión
last-update: Julio de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: c45b9f49e0732e52b01677c0acb8e6b12d155e77

---


# Notas de la versión de Adobe Experience Cloud

Nuevas funciones y correcciones en Adobe Experience Cloud.

>[!NOTE]
>
>Suscríbase a la [actualización de producto prioritaria de Adobe](https://www.adobe.com/subscription/priority-product-update.html) para recibir notificaciones por correo electrónico de las próximas versiones. Recibirá el aviso entre tres y cinco días laborables antes del lanzamiento de la versión. La nueva información publicada tras el lanzamiento se marcará con la fecha de publicación.

**Fecha de la versión: 18 de julio de 2019**

* [Administración y servicios principales de Experience Cloud](#experiencecloud)
* [!DNL Analytics](#analytics) - **(actualizado el 15 de julio)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)

## Servicios principales y administración {#experiencecloud}

Notas de la versión de la interfaz de Experience Cloud, incluidos los servicios principales de [!UICONTROL plataforma] y la administración de productos.

* [Servicio Experience Cloud ID](#ecid)
* [Mobile Services y Mobile SDK](#mobile)
* [Experience Platform Launch](#launch)
* [Boletines de seguridad y avisos](#security)

### Servicio Experience Cloud ID {#ecid}

**Correcciones y actualizaciones**

* `cookieDomain` Actualización de configuración de: La biblioteca asignará automáticamente un dominio de cookie de nivel superior cuando `cookieDomain` no esté establecido en `initConfig`. (CORE-29223)
* Se ha corregido un problema para `getVisitorValue` en `localVisitor`. (CORE-31287)
* Se ha corregido una incoherencia del `MCOPTOUT` valor en el visitante principal frente al iframe secundario visitante del `getVisitorValue` método. (CORE-29719)
* Se ha corregido un problema de vulnerabilidad en jQuery 3.2.1. (CORE-31183)
* Actualización de inclusión: Se ha agregado `optIn.off` para cancelar la suscripción a los eventos.
* Se ha corregido un problema relacionado con la `setTimeout` función. (CORE-30623)

See [Experience Cloud ID Service](https://marketing.adobe.com/resources/help/en_US/mcvid/mcvid-release-notes.html) for cumulative release notes.

### Mobile Services y Mobile SDK {#mobile}

iOS y Android se actualizaron de la siguiente manera:

**iOS**

* Adobe Target: Todas las solicitudes ahora incluyen al cliente y `sessionId` en los parámetros de consulta de URL.
* Adobe Target: Se ha corregido una fuga de memoria.
* Servicio de ID de visitante: Las API `visitorAppendToURL` y `visitorGetUrlVariablesAsync` ya no codifican dos veces sus valores devueltos. La doble codificación provocaba que los valores devueltos de esas API se marcaran con indicadores de ciertas revisiones de seguridad.

**Android**

* Target: Todas las solicitudes ahora incluyen al cliente y el sessionId en los parámetros de consulta de URL.
* Mensajería en la aplicación: Se ha corregido un problema por el que, cuando un mensaje se activaba con una URL de pulsaciones vacías, las aplicaciones de Android se bloqueaban.
* Servicio de ID de visitante: Las API `Visitor.appendToURL` y `Visitor.getUrlVariablesAsync` ya no codifican dos veces sus valores devueltos. La doble codificación provocaba que los valores devueltos de esas API se marcaran con indicadores de ciertas revisiones de seguridad.

Para obtener documentación del producto, consulte [Mobile Services](https://docs.adobe.com/content/help/en/mobile-services/using/home.html).

Para obtener más información sobre los SDK de Mobile, consulte [SDK de Android para soluciones de Experience Cloud 4.x](https://docs.adobe.com/content/help/en/mobile-services/android/overview.html) y [SDK de iOS para soluciones de Experience Cloud 4.x](https://docs.adobe.com/content/help/en/mobile-services/ios/overview.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) (links to product help) for release notes and product documentation.

### Boletines de seguridad y avisos {#security}

See [Security bulletins and advisories](https://helpx.adobe.com/security.html) for important information regarding security vulnerabilities that could affect specific versions of Adobe products.

## [!DNL Analytics] {#analytics}

* [Nuevas funciones y correcciones en Adobe Analytics](#aa-features) **(actualizado el 15 de julio)**
* [Avisos importantes para los administradores de Analytics](#aa-notices)

### Nuevas funciones de la versión [!DNL Analytics] {#aa-features}

Para obtener la documentación del producto, consulte la [Página principal de ayuda de Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

| Componente | Descripción |
| -----------| ---------- |   
| Analysis Workspace: Mejoras de análisis de cohorte | New [Cohort Analysis settings](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/cohort-table/t-cohort.html) have been added: <ul><li>Mostrar sólo porcentaje</li><li>Porcentaje redondeado al más próximo</li><li>Mostrar una fila porcentual promedio</li></ul> |
| Analysis Workspace | En el carril izquierdo, los usuarios tienen la opción de _Mostrar elementos de los últimos 18 meses_. Anteriormente, el período retroactivo era de 6 meses como máximo. Esto facilita la comparación con páginas o campañas del último año, hasta hace 18 meses. |
| Nueva plantilla de Analysis Workspace | We added a new template called ["Magento: Marketing &amp; Commerce"](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/starter-projects.html) to Analysis Workspace. Está diseñada específicamente para los clientes de comercio electrónico de Magento, pero cualquier minorista puede utilizarla para obtener una información sin precedente sobre sus actividades comerciales. |

#### [!DNL Analysis Workspace] correcciones

* Se ha corregido un problema que hacía que se mostraran al revés los caracteres de byte múltiple al desglosar dimensiones. (AN-180112)
* Se ha corregido un problema con los errores de visualización: ahora se muestra una barra de error rojo cuando se produce un error de visualización.(AN-175542)
* Se ha corregido un problema por el que los nombres de dimensiones aparecían en inglés en entornos localizados.(AN-178695)

#### [!DNL Analytics] correcciones

* Se ha corregido un problema que provocaba que el gráfico de líneas en un informe detallado en tiempo real estuviera en blanco. (AN-181690)
* Se ha corregido un problema en el cual, en algunas circunstancias, las partes del historial de fuentes de datos no se mostraban en la interfaz de usuario de la Admin Console. (AN-176219)

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación o actualizada | Descripción |
| -----------| ---------- | ---------- |
| Límites del Generador de reglas de clasificación | Añadidos el 5 de junio de 2019. | These limits are not new, but have been added to the documentation [here](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| Nuevos límites de operadores de segmentos | Añadidos el 31 de mayo de 2019. | A partir del 18 de julio de 2019, los operadores de segmentos "contiene cualquiera de", "no contiene ninguno de", "contiene todo" y "no contiene todos" se limitan a 100 palabras por campo de entrada. El límite se aplicará a todos los segmentos nuevos y modificados después de esta fecha. Los segmentos existentes que excedan el límite seguirán siendo compatibles, pero no se podrán modificar ni guardar hasta que se reduzca el número de palabras del campo de entrada. Estos límites se aplican como parte de un intento continuo por mejorar el rendimiento de la consultas. |
| Próximos cambios de soporte para las **[!UICONTROL clasificaciones numéricas]** y con **[!UICONTROL fecha habilitada]** | Actualizado el 28 de mayo de 2019 | Se ha eliminado de la base de código la posibilidad de importar clasificaciones numéricas 2 y fechas activadas. Este cambio entra en vigor con el lanzamiento de mantenimiento de julio de 2019. Si tiene columnas numéricas o con fecha habilitada en el archivo de importación, esas celdas serán omitidas sin aviso y cualquier otra información de ese archivo se importará como de costumbre. <br/>Las clasificaciones existentes se pueden exportar a través del flujo de trabajo de clasificación estándar y seguirán estando disponibles en los informes. |
| Futuros cambios en los cálculos _Total de informes_ | actualizado el 9 de julio de 2019 | El **18 de junio de 2019**, Adobe Analytics unificará los cálculos _Total de informes_ en todas sus dimensiones y métricas. Por tanto, se cambiarán los totales de algunos informes (Prop o informes de atributos del consumidor) Antes de este cambio, algunos totales de informes no incluían el elemento de línea _Sin especificar_ en el total, independientemente de si el valor _Sin especificar_ aparecía en el informe o no. <br/>A partir del 18 de junio de 2019, el valor _Sin especificar_ aparecerá siempre en el total de los informes, aunque no aparezca en él como un elemento de línea. Además, los segmentos que utilizan la lógica _existe_ o _no existe_ pueden obtener resultados diferentes para algunas dimensiones después de este cambio, específicamente las dimensiones en las que _No especificado_ tiene un nombre especial como el elemento de línea "Escritos o marcadores" para la dimensión Tipo de referente o el elemento de línea "Otro" para la dimensión Tipo de dispositivo. Este cambio afectará a Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder y a la API de informes. |
| Actualización de las descargas de CSV desde [!DNL Analysis Workspace] | 10 de abril de 2019 | A partir del 11 de abril de 2019, se realizarán varios cambios en las **[!UICONTROL descargas de CSV]** (y en **[!UICONTORL Copiar al Portapapeles]**) desde [!DNL Analysis Workspace] para eliminar el formato de los datos exportados.  <ul><li>El separador de miles ya no se incluye. Se seguirá incluyendo el separador decimal y se respetará el formato definido dentro de **[!UICONTROL Componentes &gt; Configuración de informes &gt; Separador de miles]**. Nota: Los valores numéricos que utilizan una coma como separador decimal seguirán citados en el CSV exportado.</li><li>No se mostrarán símbolos de moneda.</li><li>No se mostrarán símbolos de porcentajes. Los porcentajes estarán en formato decimal. Por ejemplo, 75 % estará representado como 0,75.</li><li>El tiempo se mostrará en segundos.</li><li>Las tablas de cohorte muestran solo valores sin procesar; se eliminan los porcentajes.</li><li>Si un número no es válido, se mostrará una celda vacía.</li></ul> |
| Cambio en el comando de Debugger [!DNL Analysis Workspace] | 4 de abril de 2019 | El comando Console para activar el [!DNL Analysis Workspace] Debugger cambia a adobeTools.debug.includeOberonXml el **13 de junio de 2019**. adobe.tools.debug.includeOberonXml dejará de funcionar a partir de esa fecha. |
| Números de versión de los navegadores web | 7 de febrero de 2019 | A partir del 8 de enero de 2019, cambiamos el nivel de truncamiento para los números de versión de navegadores web de 2 a 1. A partir de esa fecha, las versiones solo mostrarán los dos primeros niveles (por ejemplo, _Firefox 64.0.2_ ahora aparece como _Firefox 64.0_). |
| Finalización del servicio de [!DNL Ad Hoc Analysis] | 29 de enero de 2019 | El 6 de agosto de 2018 Adobe anunció su intención de finalizar el servicio de [!DNL Ad Hoc Analysis]. La fecha se hará pública una vez que esté disponible.<br/>Para obtener más información, incluidas las versiones de Java compatibles durante este periodo, visite [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Vínculos [!DNL Analytics] breves de informes | 14 de enero de 2019 | A partir del 17 de enero de 2019, todos los vínculos [!DNL Analytics] breves a informes de que no hayan recibido ninguna visita en el plazo de un año se limpiarán y eliminarán de forma gradual. |
| Finalización de la compatibilidad con TLS 1.0 | Actualizado 10 de enero de 2019 | Desde el 11 de febrero de 2019, los informes de Adobe Analytics no son compatibles con el cifrado TLS (Transport Layer Security) 1.0. Este cambio forma parte de nuestros continuos esfuerzos por mantener los estándares de seguridad más elevados y fomentar la protección de los datos de nuestros clientes. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/> Desde el 20 febrero de 2019, la recopilación de datos de Adobe Analytics no es compatible con TLS 1.0. Este cambio significa que Adobe ya no recopila [!DNL Analytics] datos de de los usuarios finales que utilicen dispositivos antiguos o exploradores web incompatibles con TLS 1.1 o posteriores. No esperamos que esto tenga un impacto significativo en los datos de los clientes ni en los informes. (Si el sitio web ya no ofrece compatibilidad con TLS 1.0, usted no se verá afectado). <br/>A partir del 11 de abril de 2019, la API de informes de Adobe Analytics ya no será compatible con el cifrado TLS 1.0. Los clientes que acceden a la API deben verificar que no se verán afectados. <ul><li>Los clientes de API que utilicen Java 7 con la configuración predeterminada deberán realizar [ modificaciones para que sea compatible con TLS 1.2](https://www.java.com/en/configure_crypto.html). (Consulte _Cambio de la versión de protocolo TLS predeterminada para puntos finales del cliente: de TLS 1.0 a TLS 1.2_). </li><li>Los clientes de API que usen Java 8 no deberían tener problemas, ya que la configuración predeterminada es TLS 1.2.</li><li> Los clientes de API que usen otros módulos deben ponerse en contacto con su proveedor para obtener más información acerca de la compatibilidad con TLS 1.2.</li></ul> |
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

* En la página [!UICONTROL Información general de segmentos], la anchura de la carpeta de almacenamiento de segmentos es ahora flexible. Esto permite distinguir entre segmentos con nombres más largos. (AAM-48400)
* Se ha corregido un problema en [!UICONTROL Modelos algorítmicos], por el cual al mover el control deslizante **Ajustar alcance y precisión** no afectaba al alcance o la precisión del modelo. (AAM-47996)
* Se corrigió un problema en destinos de Analytics en el que se dañaba el botón para descargar un archivo CSV de segmentos que entran en conflicto con los controles de exportación de datos o las normativas de uso compartido de datos de terceros. (AAM-48100)
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
   * Tablas: se ha proporcionado una opción para copiar una fila `entry` o una fila `complete` dentro de una tabla mediante copiar y pegar.
   * Tablas: se ha proporcionado una opción para seleccionar varias celdas en una columna, o para combinarlas o fusionarlas.
   * Tablas: ahora se puede establecer las propiedades de columna de tabla en el modo Autor del editor web.
   * Tablas: ahora se pueden ajustar las proporciones y el tamaño de las columnas en una tabla estándar.
   * Tablas: ahora se pueden seleccionar filas y columnas en la vista Autor.
   * Tablas: se han habilitado estilos y propiedades (alineados, valign) en el editor web para alineación de celdas de tabla.
   * Correcciones de errores en la vista de etiquetas completas, incluidos escenarios para copiar y pegar y arrastrar y soltar contenido.
   * Mostrar títulos de temas en las pestañas Editor.
   * Se han resuelto problemas de rendimiento en el editor web.
* Transferir línea de base al contenido traducido durante la traducción.
* Transferir condición configurada previamente durante el flujo de trabajo de traducción.
* Se ha añadido la capacidad de aplicar etiquetas a todos los dependientes de un mapa desde la línea base.
* Se ha proporcionado un botón para descargar el mapa con todas las dependencias como un zip.
* Las mejoras de la conversión de XHTML a DITA son las siguientes:
   * El nombre del DITAMAP generado ahora es idéntico al nombre del archivo ZIP cargado.
   * Se agregó compatibilidad con elementos y atributos HTML adicionales.
   * Compatibilidad con la ingesta de archivos HTML-ZIP simultánea.
   * La jerarquía de subcarpetas donde se carga el ZIP (*en ruta de entrada según se configura en h2d_io.xml*), se conserva para la salida generada (*en la ruta de salida configurada*).
* Se proporcionaron registros de auditoría para ver quién volvió a la versión y por qué.
* Regeneración del sitio AEM:
   * Deshabilitar la regeneración para los submapas.
   * Flujos de trabajo de generación de publicaciones habilitados para casos de uso de regeneración.
   * Desactive la opción de regeneración para un tema sin pulsar y active la opción para el tema principal donde se aplica el atributo cortado.
* La búsqueda DITA funciona ahora en la lógica AND de la búsqueda de AEM Asset.
* Los resultados no muestran los archivos temporales almacenados en la carpeta de salida de traducción.
* Pestaña de línea base:
   * Mejoras de rendimiento al abrir una línea de base.
   * Selección de temas por fecha para trabajar en la marca de tiempo del cliente.
* API para eliminar etiquetas.

#### Mantenimiento del producto

**AEM 6.2 SP1-CFP20**

AEM 6.2 Service Pack 1– Cumulative Fix Pack 20 (6.2.1.20), publicada el 6 de junio de 2019 es una actualización importante que incluye correcciones claves de cliente publicadas tras la disponibilidad general de AEM 6.2 SP1 en diciembre de 2016.

* [Notas de la versión](https://helpx.adobe.com/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html)
* [Versiones de AEM Forms CFP](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3.3.5**

AEM 6.3.3.5 es una actualización importante publicada el miércoles, 3 de julio de 2019 que incluye correcciones clave del cliente realizadas tras la publicación general de AEM 6.3 en abril de 2017.

* [Notas de la versión](https://helpx.adobe.com/experience-manager/6-3/release-notes/sp3-release-notes.html)
* [Versiones de AEM Forms CFP](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.4.5.0**

AEM 6.4.5.0 es una actualización importante publicada el miércoles, 3 de julio de 2019 que incluye correcciones clave del cliente realizadas tras la publicación general de AEM 6.4 en abril de 2018.

* [Notas de la versión](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
* [Versiones de AEM Forms CFP](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.5.1.0**

AEM 6.5.1.0 es una actualización importante publicada el miércoles, 3 de julio de 2019 que incluye correcciones clave del cliente realizadas tras la publicación general de AEM 6.5 en abril de 2019.

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

Para acceder a las notas de la versión actual, consulte:

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
