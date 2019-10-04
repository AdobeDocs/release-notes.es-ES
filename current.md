---
title: Notas de la versión de Adobe Experience Cloud
description: Plantilla para notas de la versión de Experience Cloud
doc-type: notas de la versión
last-update: de octubre de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 04228df4d9a7279fe2c8627aeb0bb7492d34327e

---


# Early Access - Experience Cloud Release Notes - October 2019

Nuevas funciones y correcciones en Adobe Experience Cloud.

>[!IMPORTANT]
>
>Esta página incluye contenido previo al lanzamiento de la nueva versión y está sujeta a cambios antes de su publicación planificada.
>
>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. La nueva información publicada tras el lanzamiento se marcará con la fecha de publicación.

## Fecha de la versión: 10 de octubre de 2019

<!-- * [Experience Cloud interface](#ecloud) -->
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (links to solution help)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (links to solution help)

<!-- ## Experience Cloud interface {#ecloud}

Release notes for Experience Cloud interface and product administration.

* Fixed a security vulnerability to include recommended HTTP headers. (MCUI-9942)
* Fixed an issue in switching between Analytics login companies. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html). -->

## Experience Platform {#platform}

Notas de la versión de Experience Platform, Experience Platform Launch, servicios de identidad y boletines de seguridad.

* [Experience Platform Launch](#launch)
* [Boletines de seguridad y avisos](https://helpx.adobe.com/security.html) (All Adobe products)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Nuevas funciones y correcciones en Adobe Analytics:

* [Nuevas funciones, mejoras y correcciones en Adobe Analytics](#aa-features)
* [Avisos importantes para los administradores de Analytics](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nuevas funciones, mejoras y correcciones en Adobe Analytics {#aa-features}

| Función | Descripción |
| -----------| ---------- |  
| API de Privacy Service: CCPA | La Ley de Privacidad del Consumidor de California (CCPA, por sus siglas en inglés) mejora los derechos de privacidad y la protección del consumidor para los residentes de California, Estados Unidos. This Act is set to become effective on January 1, 2020.<br/>La CCPA otorga nuevos derechos de privacidad de datos a los residentes de California, como el derecho a acceder y eliminar sus datos personales, a saber si sus datos personales se venden o revelan (y a quién) y a rechazar la venta de sus datos personales.<br/>En previsión de la CCPA, el Servicio de Privacidad apoyará las solicitudes de exclusión de la venta de datos personales.<br/>The Privacy Service was formerly called the GDPR Service and retains all the previous functionality, now extended to support CCPA.<br/>CCPA in Analytics: Privacy Service Overview`[Link to new CCPA page in Analytics]()`<br/>[](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| Privacy Reporting: Analytics Admin Console | Al habilitar Informes de privacidad para Analytics, se agrega un conjunto de variables reservadas a un grupo de informes.  Las variables están diseñadas para ayudar en la recopilación de datos de consentimiento del consumidor a nivel de visita individual.<br/>Nuevas dimensiones:<br/><ul><li>Desactivación de la administración de consentimiento</li><li>Inclusión en la administración de consentimiento</li><li>Variables de administración de consentimiento: `[Link to new Consent Variables page in Analytics]()`</li></ul> |
| Análisis de audio y vídeo: Compatibilidad con privacidad | Se han agregado dos nuevas variables a la API de Media Collection:<br/><ul><li>analytics.optOutServerSideForwarding</li><li> analytics.optOutShare</li></ul>Son variables opcionales que se pueden utilizar para capturar el estado del consentimiento del consumidor en el momento de la visita.<br/>[Documentación de la API de Media CollectionLas nuevas variables de datos de contexto de la Administración de](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/>consentimiento de Analytics se han agregado al formulario de Federated Analytics. Estas variables ya están disponibles para su uso al marcar las visitas de exclusión de compartir o venta para federación.<br/>[Descargar formulario federado](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |
| Espacio de trabajo de análisis: Actualizar a totales de tabla improvisada | Las tablas improvisadas ahora incluyen dos totales, un total **[!UICONTROL de]** tabla y un total **** general. La fila total de la tabla cuenta los filtros [de](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) informe aplicados. Anteriormente, solo la segmentación afectaba a los totales. [Obtenga](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/workspace-totals.html)<br/>más información Además, se han agregado las opciones **[!UICONTROL Mostrar totales]** y **[!UICONTROL Mostrar total]** general a Configuración **[!UICONTROL de]** columna.<br/>Con este cambio a totales improvisados, se actualizarán las visualizaciones dependientes (por ejemplo, visualizaciones de números **[!UICONTROL de]** resumen vinculadas), así como los datos CSV y PDF exportados. |
| Espacio de trabajo de análisis: Opción para eliminar no especificado/ninguno | Se ha agregado la capacidad de eliminar fácilmente "No especificado (Ninguno)" como opción para informar los filtros. |
| Espacio de trabajo de análisis: Desaprobación de los componentes de granularidad púrpura | Los componentes de tiempo de granularidad púrpura (Minuto, Hora, Día, Semana, Mes, Trimestre, Año) han quedado obsoletos. Los componentes de tiempo púrpura siempre se han comportado exactamente como sus equivalentes de dimensión naranja, por lo que este cambio simplificará la experiencia. **No es necesario realizar ninguna acción** si ya ha utilizado uno de los componentes de tiempo púrpura.<br/>Con este cambio, también se ha cambiado el nombre de la sección púrpura **[!UICONTROL Hora]** a Intervalos **[!UICONTROL de fechas]**. |

#### Correcciones

* Analysis Workspace: Fixed an issue that resulted in incorrect search results when searching for dimension items in the left rail. (AN-185065)
* Fixed issues with being unable to delete or unpublish shared segments in Adobe Audience Manager (AAM). The fix is to not delete the segment if AAM is unresponsive. (AN-185882, AN-185883 y AN-184607)
* Fixed a timeout issue with being unable to load segments in Ad Hoc Analysis. (AN-184654)
* Fixed an issue that occurred when the report suite you last used was subsequently hidden or you no longer had permissions to access this report suite. In this case, you could no longer log in through Experience Cloud. (AN-181777)
* Fixed a timeout issue in segments that made it difficult to create a VRS based on a segment. (AN-179684)

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación o actualizada | Descripción |
| -----------| ---------- | ---------- |
| Finalización de la compatibilidad con TLS 1.1 | 3 de octubre de 2019 | By March 31, 2020, Adobe Analytics will remove support for TLS 1.1. This change is part of our ongoing efforts to maintain the highest security standards and promote the safety of customer data. |
| San Jose FTP Broker Ending for London and Singapore | Julio de 2020 | For customers in London and Singapore, we will no longer be supporting brokering of data between London or Singapore and the San Jose data center ftp.omniture.com.[](ftp://ftp.omniture.com/)<br/>For London use ftp3.omniture.comFor Singapore use ftp4.omniture.com[](ftp://ftp3.omniture.com/)<br/>[](ftp://ftp4.omniture.com/) |
| Actualización de los totales de la tabla de forma libre de Analysis Workspace | 12 de septiembre de 2019 | En octubre de 2019, las filas totales de la tabla improvisada empezarán a contabilizar los filtros [de](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) informe aplicados. Hasta la fecha, los totales solo se han contabilizado para la segmentación. Con este cambio, se actualizarán las visualizaciones dependientes (por ejemplo, las visualizaciones de [!UICONTROL Número de resumen] vinculadas), así como los datos CSV y PDF exportados. |
| Próximos cambios en el campo `createDate` para los usuarios de Analytics | 30 de agosto de 2019 | En octubre o noviembre de 2019, el campo `createDate` de los usuarios de Analytics se actualizará de la hora del Pacífico de EE. UU. a un valor de fecha y hora con formato correcto respecto a la información de zona horaria. (AN-183468) |
| Compatibilidad con desplazamientos históricos de zona horaria | 8 de agosto de 2019 | Analytics ahora gestiona automáticamente los desplazamientos de zona horaria para las visitas con marca de hora. Después de este cambio el 8 de agosto, los sistemas que cargan los datos para el procesamiento histórico ya no necesitarán ajustar los desplazamientos de zona horaria antes de enviar los datos. |
| Límites del Generador de reglas de clasificación | Añadidos el 5 de junio de 2019 | These limits are not new, but have been added to the documentation here.[](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html) |
| Nuevos límites de operadores de segmentos | Añadidos el 31 de mayo de 2019 | A partir del 18 de julio de 2019, los operadores de segmentos _contiene cualquiera de_, _no contiene ninguno de_, _contiene todo_ y _no contiene todos_ se limitan a 100 palabras por campo de entrada. El límite se aplicará a todos los segmentos nuevos y modificados después de esta fecha. Los segmentos existentes que excedan el límite seguirán siendo compatibles, pero no se podrán modificar ni guardar hasta que se reduzca el número de palabras del campo de entrada. Estos límites se aplican como parte de un intento continuo por mejorar el rendimiento de la consultas. |
| Próximos cambios de soporte para las **[!UICONTROL clasificaciones numéricas 2]** y con **[!UICONTROL fecha habilitada]** | Actualizado el 28 de mayo de 2019 | Se ha eliminado de la base de código la posibilidad de importar clasificaciones numéricas 2 y fechas activadas. Este cambio entra en vigor con el lanzamiento de mantenimiento de julio de 2019. Si tiene columnas numéricas o con fecha habilitada en el archivo de importación, esas celdas serán omitidas sin aviso y cualquier otra información de ese archivo se importará como de costumbre. <br/>Las clasificaciones existentes se pueden exportar a través del flujo de trabajo de clasificación estándar y seguirán estando disponibles en los informes. |
| Cambio a los cálculos _Total de informes_ | actualizado el 9 de julio de 2019 | El **18 de junio de 2019**, Adobe Analytics unificará los cálculos _Total de informes_ en todas sus dimensiones y métricas. Por tanto, se cambiarán los totales de algunos informes (Prop o informes de atributos del consumidor). Antes de este cambio, algunos totales de informes no incluían el elemento de línea _Sin especificar_ en el total, independientemente de si el valor _Sin especificar_ aparecía en el informe o no. <br/>A partir del 18 de junio de 2019, el valor _Sin especificar_ aparecerá siempre en el total de los informes, aunque no aparezca en él como un elemento de línea. Además, los segmentos que utilizan la lógica _existe_ o _no existe_ pueden obtener resultados diferentes para algunas dimensiones después de este cambio, específicamente las dimensiones en las que _No especificado_ tiene un nombre especial como el elemento de línea "Escritos o marcadores" para la dimensión Tipo de referente o el elemento de línea "Otro" para la dimensión Tipo de dispositivo. Este cambio afectará a Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder y a la API de informes. |
| Actualización de las descargas de CSV desde Analysis Workspace | 10 de abril de 2019 | A partir del 11 de abril de 2019, se realizarán varios cambios en las **[!UICONTROL descargas de CSV]** (y en **[!UICONTORL Copiar al Portapapeles]**) desde Analysis Workspace para eliminar el formato de los datos exportados.  <ul><li>El separador de miles ya no se incluye. Se seguirá incluyendo el separador decimal y se respetará el formato definido dentro de **[!UICONTROL Componentes &gt; Configuración de informes &gt; Separador de miles]**. Nota: Los valores numéricos que utilizan una coma como separador decimal seguirán citados en el CSV exportado.</li><li>No se mostrarán símbolos de moneda.</li><li>No se mostrarán símbolos de porcentajes. Los porcentajes estarán en formato decimal. Por ejemplo, 75 % estará representado como 0,75.</li><li>El tiempo se mostrará en segundos.</li><li>Las tablas de cohorte muestran solo valores sin procesar; se eliminan los porcentajes.</li><li>Si un número no es válido, se mostrará una celda vacía.</li></ul> |
| Cambio en el comando de Debugger de Analysis Workspace | 4 de abril de 2019 | El comando Console para activar el Analysis Workspace Debugger cambia a adobeTools.debug.includeOberonXml el **13 de junio de 2019**. adobe.tools.debug.includeOberonXml dejará de funcionar a partir de esa fecha. |
| Números de versión de los navegadores web | 7 de febrero de 2019 | A partir del 8 de enero de 2019, cambiamos el nivel de truncamiento para los números de versión de navegadores web de 2 a 1. A partir de esa fecha, las versiones solo mostrarán los dos primeros niveles (por ejemplo, _Firefox 64.0.2_ ahora aparece como _Firefox 64.0_). |
| Finalización del servicio de [!DNL Ad Hoc Analysis] | 29 de enero de 2019 | El 6 de agosto de 2018 Adobe anunció su intención de finalizar el servicio de [!DNL Ad Hoc Analysis]. La fecha se hará pública una vez que esté disponible.<br/>Para obtener más información, incluidas las versiones de Java compatibles durante este período, visite [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Vínculos [!DNL Analytics] breves de informes | 14 de enero de 2019 | A partir del 17 de enero de 2019, todos los vínculos [!DNL Analytics] breves a informes de que no hayan recibido ninguna visita en el plazo de un año se limpiarán y eliminarán de forma gradual. |
| Canal de datos: cambio de tamaño de la columna post_product_list | 9 de enero de 2019 | El 7 de febrero de 2019, Adobe aumentó el tamaño de la columna post_product_list de 64 KB a 16 MB. El objetivo de este cambio es garantizar que los valores eVar de comercialización añadidos a post_product_list durante el procesamiento no provoquen la solapación entre los valores de ingresos y el producto. Si tiene procesos que consumen valores de post_product_list, compruebe que dichos procesos puedan gestionar valores de hasta 16 MB de longitud; de lo contrario, el valor se truncará a los 16 KB para evitar fallos producidos por el consumo de datos. |
| Cambios de administración que afectan a los puntos de conexión de [!DNL Analytics Live Stream] inactivos | 20 de diciembre de 2018 | A partir del 1 de febrero de 2019, puede que se deshabiliten los puntos de conexión de [!DNL Live Stream] que no tengan conexiones activas de consumidores durante 90 días. Póngase en contacto con el Servicio de atención al cliente para consultar sobre sus puntos de conexión de [!DNL Live Stream] y, si es necesario, solicitar que los vuelvan a habilitar. Además, asegúrese de que los procesos de consumidores mantengan una conexión persistente, tal como se pretende desde el diseño del servicio, y que se implementen para reconectar cuando se desconecte o interrumpa la conexión. |
| Actualizar el [!DNL Report Builder] de Adobe debido al fin de la compatibilidad con TLS 1.0 | 7 de septiembre de 2018 | Debido al fin de la compatibilidad con TLS 1.0, recomendamos a los usuarios de [!DNL Report Builder] que descarguen la versión v5.6.21 antes de febrero de 2019. Después de esta fecha, las versiones anteriores de dejarán de [!DNL Report Builder] funcionar. |

### [!DNL AppMeasurement] {#appm}

Consulte [Notas](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html)de la versión de AppMeasurement para JavaScript.

## Audience Manager {#aam}

Nuevas funciones y correcciones en Audience Manager.

**Correcciones y mejoras**

* A todas las cuentas de cliente creadas después del 1 de julio de 2019 se les asignará automáticamente una [!DNL Tableau] licencia que les permitirá acceder a sus informes. Si su cuenta se creó antes del 1 de julio de 2019 y aún no tiene acceso a sus [!DNL Tableau] informes, póngase en contacto con el Servicio de atención al cliente.
* We've removed incorrectly generated activity trait memberships for visitor profiles that did not have an ID synchronization with the trait data source (AAM-45371).
* We've removed invalid global device IDs from global data sources. See Global Data Sources to learn what valid device IDs should look like to be accepted by Audience Manager (AAM-41259).[](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html)
* Se ha corregido un error que hacía que la página Segmentos dejara de responder al intentar eliminar un segmento protegido (AAM-49881).
* Al editar destinos para Audiencias personalizadas de Twitter, el selector de [!UICONTROL cuentas] ahora solo está activo si el destino no tiene una [!DNL Twitter Ads] cuenta asignada (AAM-49975).
* Se ha corregido un error que impedía a los usuarios desactivar las fuentes de datos de [!UICONTROL Audience Marketplace] cuando las suscripciones estaban desactivadas (AAM-49640).
* Se han aplicado varias mejoras relacionadas con la accesibilidad de la interfaz de usuario de Audience Manager.

## Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Adobe Experience Manager (AEM). Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

### Mantenimiento del producto

* **AEM 6.3.3.6**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 6 (6.3.3.6 publicado el 25 de septiembre de 2019) es una actualización importante que incluye correcciones clave de cliente realizadas tras la disponibilidad general de AEM 6.3 en abril de 2017.
   * [Notas de la versión](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [Versiones de AEM Forms CFP](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.6.0**

   AEM 6.4, Service Pack 6.0 (6.4.6.0 publicado el 19 de septiembre de 2019) es una actualización importante que incluye correcciones clave de cliente realizadas tras la disponibilidad general de AEM 6.4 en abril de 2018.
   * [Notas de la versión](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [Versiones de AEM Forms CFP](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.5.2.0** AEM 6.5, Service Pack 2.0 (6.5.2.0 publicado el 19 de septiembre de 2019) es una actualización importante que incluye correcciones clave de cliente realizadas tras la disponibilidad general de AEM 6.5 en abril de 2019.
   * [Notas de la versión](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Versiones de AEM Forms CFP](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Autoayuda

* **Scene7: Flujo de trabajo de reprocesamiento de recursos**

   Ahora puede volver a procesar los recursos en una carpeta que ya tenga un perfil de procesamiento existente que haya cambiado posteriormente.
Consulte [Reprocesamiento de recursos en una carpeta después de editar su perfil](https://helpx.adobe.com/experience-manager/6-5/assets/using/processing-profiles.html#Reprocessingassetsinafolderafteryouhaveediteditsprocessingprofile)de procesamiento.

* **Integración de visores de medios dinámicos con Adobe Analytics y Adobe Launch**

   La extensión de visores de medios dinámicos para Adobe Launch, junto con la versión de visores de medios dinámicos 5.13, permite a los clientes de Dynamic Media, Adobe Analytics y Adobe Launch usar eventos y datos específicos para los visores de medios dinámicos en su configuración de Adobe Launch.
Consulte [Integración de visores de medios dinámicos con Adobe Analytics y Adobe Launch](https://helpx.adobe.com/experience-manager/6-5/assets/using/launch.html).

* **Aplicación de escritorio AEM**

   La aplicación de escritorio AEM 2.0 ya está disponible para usuarios creativos, especialistas en marketing y de línea de negocios para trabajar con Recursos AEM.
Consulte las notas de la versión de la aplicación de escritorio de [AEM.](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Componentes principales**
   * Obtenga información sobre las funciones de localización de los componentes principales y cómo funcionan con las plantillas de AEM.
      [Consulte el ejemplo](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/get-started/localization.html).
   * Componentes principales 2.6.0 presenta un componente de fragmento de experiencia. El componente ya está disponible junto con la documentación [de](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) creación y los detalles del [desarrollador, así como la descarga del proyecto en GitHub](https://github.com/adobe/aem-core-wcm-components).

* **AEM Assets**
   * Nueva documentación para la funcionalidad de búsqueda visual/de similitudes.
Consulte [Buscar imágenes](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html#visualsearch)similares.
   * La funcionalidad Recursos conectados ahora utiliza documentos disponibles en la implementación remota de DAM, además de formatos de archivo de imágenes.
Consulte [Uso de recursos conectados para compartir recursos DAM en sitios](https://helpx.adobe.com/experience-manager/6-5/assets/using/use-assets-across-connected-assets-instances.html)AEM.
   * Nuevo contenido sobre búsqueda y descubrimiento de recursos. El tema _Buscar recursos en AEM_ es una solución única para obtener información sobre cómo usar, configurar, solucionar problemas, limitaciones y sugerencias.
Consulte [Buscar recursos en AEM](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html).

### Recursos adicionales

* [Página de inicio de Learn &amp; Support de AEM 6.5](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Página de inicio de Learn &amp; Support de AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Página de inicio de Learn &amp; Support de AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Página de inicio de Learn &amp; Support de AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guía del usuario de Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Older Versions of AEM Documentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Inicio de la Ayuda de Dynamic Media Classic](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Notas de la versión de Dynamic Media ](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notas de la versión de Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign permite entregar, de forma intuitiva y automatizada, mensajes privados a través de canales de marketing en línea y sin conexión. Ahora puede anticipar los deseos de los clientes mediante experiencias basadas en sus hábitos y preferencias.

<!-- ### Adobe Campaign Classic

* [Campaign Classic 19.1.4 update](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) – build 9032
* [Campaign Classic 19.1.5 update](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9033) – build 9033

### Adobe Campaign [!UICONTROL Control Panel]

Text

### Additional resources -->

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
