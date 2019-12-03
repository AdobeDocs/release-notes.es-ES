---
title: Notas de la versión de Adobe Experience Cloud
description: Plantilla para notas de la versión de Experience Cloud
doc-type: release notes
last-update: November 2019
author: mfrei
translation-type: tm+mt
source-git-commit: ba99a07c966a56306daa151606f4503586cb898a

---


# Notas de la versión de Adobe Experience Cloud, noviembre de 2019

Nuevas funciones y correcciones en Adobe Experience Cloud.

> [!NOTE] Para recibir notificaciones por correo electrónico sobre próximas versiones, suscríbase a [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html). La nueva información publicada tras el lanzamiento se marcará con la fecha de publicación.

**Fecha de la versión: 31 de octubre de 2019**

* [Interfaz de Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (vínculos a la ayuda de la solución)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (vínculos a la ayuda de la solución)
* [!DNL Advertising Cloud](#adcloud) (actualizado el 8/11)

¿Busca ayuda en casa? Consulte la documentación [de](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html)Adobe Experience Cloud.

## Interfaz de Experience Cloud {#ecloud}

Notas de la versión de la interfaz de Experience Cloud y la administración de productos.

* La página Fuente quedará obsoleta en diciembre de 2019. Busque un aviso de obsolescencia del producto. (MCUI-10039)
* Se ha actualizado el vínculo [Más información](https://www.adobe.com/marketing/campaign.html) para Adobe Campaign en el selector de aplicaciones. (MCUI-10034)
* Se ha mejorado la estabilidad y la capacidad de respuesta de la plataforma principal de la interfaz de Experience Cloud. (MCUI-6822)
* Se han eliminado las vulnerabilidades de seguridad en la interfaz de usuario de Experience Cloud. (MCUI-9942)
* Se ha corregido un problema crítico de los Atributos del cliente que bloqueaba la validación de esquemas para algunos clientes. (MCUI-10024, MCUI-6479)
* Se ha mejorado la Biblioteca de audiencias para eliminar dimensiones que no se admiten en la creación de audiencias en tiempo real. (MCUI-10046)

Para obtener documentación del producto, consulte [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Notas de la versión de Experience Platform, Experience Platform Launch, servicios de identidad y boletines de seguridad.

* [Experience Platform Launch](#launch)
* [Boletines de seguridad y avisos](https://helpx.adobe.com/security.html) (Todos los productos de Adobe)

### Experience Platform Launch {#launch}

Consulte [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) para ver notas de la versión y documentación del producto.

## [!DNL Analytics] {#analytics}

Nuevas funciones y correcciones en Adobe Analytics:

* [Nuevas funciones, mejoras y correcciones en Adobe Analytics](#aa-features)
* [Avisos importantes para los administradores de Analytics](#aa-notices)
* [AppMeasurement](#appm)

Para obtener documentación del producto, consulte la sección [Ayuda de Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nuevas funciones, mejoras y correcciones en Adobe Analytics {#aa-features}

| Función | Descripción |
| -----------| ---------- | 
| Análisis de Recorrido del cliente | A partir del 21 de noviembre de 2019, el [Análisis de recorrido del cliente](https://www.adobe.com/analytics/customer-journey-analytics.html) estará disponible como complemento de Adobe Analytics.<br><br/>El Ánalisis del recorrido del cliente permite obtener los datos de clientes desde cualquier canal que elija, tanto en línea como sin conexión, e importarlos en Adobe Experience Platform y, a continuación, analizarlos del mismo modo que lo haría con los datos digitales actuales con Analysis Workspace. El Análisis del Recorrido del cliente permite controlar cómo conectar los datos en línea y sin conexión en Analysis Workspace en cualquier ID de cliente común, lo que permite realizar procesos de atribución, segmentación, flujo, abandonos, etc. en todo el conjunto de datos de clientes de Adobe Analytics.<br><br/>Los clientes de Analytics Select, Prime y Ultimate pueden adquirir este producto adicional. Póngase en contacto con el equipo de su cuenta de Adobe para obtener más información. |
| API de Servicio de privacidad: CCPA | La Ley de Privacidad del Consumidor de California (CCPA) mejora los derechos de privacidad y la protección del consumidor para los residentes de California, Estados Unidos. Esta ley entrará en vigor el 1 de enero de 2020.<br><br/>La CCPA otorga nuevos derechos de privacidad de datos a los residentes de California, como el derecho a acceder y eliminar sus datos personales, a saber si sus datos personales se venden o revelan (y a quién) y a rechazar la venta de sus datos personales.<br><br/>En previsión de la CCPA, el Servicio de privacidad aceptará las solicitudes de exclusión de la venta de datos personales.<br><br/>El Servicio de privacidad, anteriormente Servicio de RGPD, conserva todas las funciones anteriores, ahora ampliadas para ser compatibles con la CCPA.<br/><br/>[CCPA en Analytics](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[Información general sobre el Servicio de privacidad](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| Informes de privacidad: Admin Console de Analytics | Al habilitar Informes de privacidad para Analytics, se agrega un conjunto de variables reservadas a un grupo de informes.  Las variables están diseñadas para ayudar en la recopilación de datos de consentimiento del consumidor en el nivel de visita individual.<br><br/>Nuevas dimensiones:<br/><ul><li>Exclusión en la administración de consentimiento</li><li>Inclusión en la administración de consentimiento</li><li>[Variables de administración de consentimiento](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| Análisis de audio y vídeo: Compatibilidad con privacidad | Se han agregado dos nuevas variables a la API de recopilación de medios:<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>Son variables opcionales que se pueden utilizar para recoger el estado del consentimiento del consumidor en el momento de la visita.<br/><br/>[Documentación de la API de recopilación de medios](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>Las nuevas variables de datos de contexto de la Administración de consentimiento de Analytics se han agregado al formulario de Federated Analytics. Estas variables ya están disponibles para su uso al marcar las visitas de exclusión de uso compartido o de venta de visitas para la federación.<br/><br/>[Descargar formulario federado](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |

#### Correcciones

* Se ha corregido un problema que provocaba un error al intentar eliminar intervalos de fechas que eran propiedad de “Usuario desconocido”. (AN-185540)

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporació o actualizada | Descripción |
| -----------| ---------- | ---------- |
| Fecha de fin de uso de la opción **[!UICONTROL Ver archivo]** | 30 de octubre de 2019 | Anuncio de la fecha de finalización en enero de 2020 de la opción **[!UICONTROL Ver archivo]** en el Administrador de paneles (**[!UICONTROL Componentes &gt; Paneles]**). |
| Fecha de fin de uso de la opción **[!UICONTROL Aplicar restricciones de inicio de sesión con IP]** | 30 de octubre de 2019 | Anuncio de la fecha de finalización en enero de 2020 de la creación de listas de IP de inicio de sesión admitidas (**[!UICONTROL Aplicar restricciones de inicio de sesión con IP]**) en el menú **[!UICONTROL Administración &gt; Configuración de la compañía &gt; Seguridad]**. |
| Se ha actualizado la administración del atributo SameSite en las cookies | 15 de octubre de 2019 | En agosto de 2019, Adobe anunció que añadía la configuración de cookie SameSite a todas las cookies establecidas por Analytics. Se aplica una actualización lógica donde:<ul><li>Todas las cookies de terceros que no están basadas en Webkit tienen el atributo SameSite establecido en `none`.</li><li>Todas las demás cookies no tienen el atributo SameSite establecido.</li></ul> |
| Finalización de la compatibilidad con TLS 1.1 | 3 de octubre de 2019 | A partir del 31 de marzo de 2020, Adobe Analytics dejará de ofrecer soporte para TLS 1.1. Este cambio es parte de nuestro trabajo para mantener los estándares de seguridad más altos e impulsar la seguridad de los datos del cliente. |
| Fin de la administración de datos en el centro de datos de San José para Londres y Singapur | Julio de 2020 | Para los clientes de Londres y Singapur, ya no se ofrecerá la administración de datos entre Londres o Singapur y el centro de datos de San José [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>Para Londres, utilice [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Para Singapur, utilice [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| Actualización de los totales de la tabla de forma libre de Analysis Workspace | 12 de septiembre de 2019 | En octubre de 2019, las filas totales de la tabla de forma libre empezarán a contabilizar los [filtros de informe](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) aplicados. Hasta la fecha, los totales solo se han contabilizado para la segmentación. Con este cambio, se actualizarán las visualizaciones dependientes (por ejemplo, las visualizaciones de [!UICONTROL Número de resumen] vinculadas), así como los datos CSV y PDF exportados. |
| Próximos cambios en el campo `createDate` para los usuarios de Analytics | 30 de agosto de 2019 | En octubre o noviembre de 2019, el campo `createDate` de los usuarios de Analytics se actualizará de la hora del Pacífico de EE. UU. a un valor de fecha y hora con formato correcto respecto a la información de zona horaria. (AN-183468) |
| Compatibilidad con desplazamientos históricos de zona horaria | 8 de agosto de 2019 | Analytics ahora gestiona automáticamente los desplazamientos de zona horaria para las visitas con marca de hora. Después de este cambio el 8 de agosto, los sistemas que cargan los datos para el procesamiento histórico ya no necesitarán ajustar los desplazamientos de zona horaria antes de enviar los datos. |
| Límites del Generador de reglas de clasificación | Añadidos el 5 de junio de 2019 | Estos límites no son nuevos, pero se han agregado a la documentación [aquí](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Nuevos límites de operadores de segmentos | Añadidos el 31 de mayo de 2019 | A partir del 18 de julio de 2019, los operadores de segmentos _contiene cualquiera de_, _no contiene ninguno de_, _contiene todo_ y _no contiene todos_ se limitan a 100 palabras por campo de entrada. El límite se aplicará a todos los segmentos nuevos y modificados después de esta fecha. Los segmentos existentes que excedan el límite seguirán siendo compatibles, pero no se podrán modificar ni guardar hasta que se reduzca el número de palabras del campo de entrada. Estos límites se aplican como parte de un intento continuo por mejorar el rendimiento de la consultas. |
| Próximos cambios de soporte para las **[!UICONTROL clasificaciones numéricas 2]** y con **[!UICONTROL fecha habilitada]** | Actualizado el 28 de mayo de 2019 | Se ha eliminado de la base de código la posibilidad de importar clasificaciones numéricas 2 y fechas activadas. Este cambio entra en vigor con el lanzamiento de mantenimiento de julio de 2019. Si tiene columnas numéricas o con fecha habilitada en el archivo de importación, esas celdas serán omitidas sin aviso y cualquier otra información de ese archivo se importará como de costumbre. <br/>Las clasificaciones existentes se pueden exportar a través del flujo de trabajo de clasificación estándar y seguirán estando disponibles en los informes. |
| Cambio a los cálculos _Total de informes_ | Actualizado el 9 de julio de 2019 | El **18 de junio de 2019**, Adobe Analytics unificará los cálculos _Total de informes_ en todas sus dimensiones y métricas. Por tanto, se cambiarán los totales de algunos informes (Prop o informes de atributos del consumidor). Antes de este cambio, algunos totales de informes no incluían el elemento de línea _Sin especificar_ en el total, independientemente de si el valor _Sin especificar_ aparecía en el informe o no. <br/>A partir del 18 de junio de 2019, el valor _Sin especificar_ aparecerá siempre en el total de los informes, aunque no aparezca en él como un elemento de línea. Además, los segmentos que utilizan la lógica _existe_ o _no existe_ pueden obtener resultados diferentes para algunas dimensiones después de este cambio, específicamente las dimensiones en las que _No especificado_ tiene un nombre especial como el elemento de línea "Escritos o marcadores" para la dimensión Tipo de referente o el elemento de línea "Otro" para la dimensión Tipo de dispositivo. Este cambio afectará a Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder y a la API de informes. |
| Actualización de las descargas de CSV desde Analysis Workspace | 10 de abril de 2019 | A partir del 11 de abril de 2019, se realizarán varios cambios en las **[!UICONTROL descargas de CSV]** (y en **[!UICONTORL Copiar al Portapapeles]**) desde Analysis Workspace para eliminar el formato de los datos exportados.  <ul><li>El separador de miles ya no se incluye. Se seguirá incluyendo el separador decimal y se respetará el formato definido dentro de **[!UICONTROL Componentes &gt; Configuración de informes &gt; Separador de miles]**. Nota: Los valores numéricos que utilizan una coma como separador decimal seguirán citados en el CSV exportado.</li><li>No se mostrarán símbolos de moneda.</li><li>No se mostrarán símbolos de porcentajes. Los porcentajes estarán en formato decimal. Por ejemplo, 75 % estará representado como 0,75.</li><li>El tiempo se mostrará en segundos.</li><li>Las tablas de cohorte muestran solo valores sin procesar; se eliminan los porcentajes.</li><li>Si un número no es válido, se mostrará una celda vacía.</li></ul> |
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
| [Mejoras en las reglas de combinación de perfiles](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rules-overview.html) | Hemos lanzado una serie de mejoras para las [!UICONTROL reglas de combinación de perfiles]: <ul><li>La evaluación de segmentos ahora se puede hacer en lote, para hasta 100 dispositivos.</li><li>Hemos mejorado la precisión de los informes para los grupos de rasgos y segmentos.</li><li>Hemos mejorado la precisión de los archivos por lotes generados mediante ID entre dispositivos.</li><li>Hemos actualizado la documentación con ejemplos prácticos más detallados para cada regla. Consulte [Ejemplos prácticos generales de reglas de combinación de perfiles](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rule-targeting-options.html), [Ejemplos prácticos de gráficos de dispositivos externos](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/external-graph-use-cases.html) y [Ejemplos prácticos de gráficos de dispositivos de vínculos de perfiles](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/profile-link-use-case.html).</li></ul> |
| [Recomendaciones inteligentes para datos de Audience Marketplace, con tecnología de Adobe Sensei](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/segments/trait-recommendations.html) | Con Recomendaciones de características, cuando crea o edita un segmento en el [Generador de segmentos](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/segments/segment-builder.html), ahora obtiene recomendaciones sobre características adicionales que puede incluir, desde fuentes de datos de [!UICONTROL Audience Marketplace] a las que no está suscrito. Añada las características recomendadas al segmento para aumentar la audiencia objetivo. <br>  Además, hemos rediseñado la página [!UICONTROL Marketplace] para facilitar la búsqueda de características similares y el filtrado de fuentes de datos. |
| [Herramientas de administración masiva](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | Hemos publicado una nueva versión de la hoja de cálculo de Administración masiva que funciona en los sistemas operativos MacOS y Microsoft Windows y que admite el inicio de sesión en Experience Cloud. |
| [HTTP Strict-Transport-Security](https://docs.adobe.com/help/en/audience-manager/user-guide/overview/data-security-and-privacy/data-security.html#hsts) | Se ha agregado la compatibilidad con [!DNL HTTP Strict-Transport-Security], una política de seguridad web que protege contra el secuestro de cookies y ataques de reducción de categoría de protocolos. |

### Mejoras {#aam-enhancements}

A partir de noviembre de 2019, Audience Manager también será compatible con el envío de ID de Roku, ID de Amazon Fire TV e ID de Xbox/Microsoft a destinos de Google Ad Manager y DV360, además de la cookie compatible anteriormente, las ID de dispositivo de IDFA y GAID. No es necesario cambiar nada en las integraciones de Google existentes.

En Audience Manager, los ID de Roku, ID de Amazon Fire TV e ID de Xbox/Microsoft se denominan ID de dispositivo globales. Puede obtener más información sobre estos ID y sobre las fuentes de datos a las que están asociados en la documentación de producto de Audience Manager:

* [ID de dispositivo globales](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/ids-in-aam.html#global-device-ids)
* [Fuentes de datos globales](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html)

La ingesta de datos para las fuentes de datos Roku, Amazon Fire TV y Xbox/Microsoft funciona de la misma manera que para IDFA y GAID: se genera un ID de Audience Manager automáticamente y se vincula al DAID al ingerir datos tecleados de ellos. Los nuevos ID se envían automáticamente a los destinos de Google nuevos y existentes configurados en su cuenta.

Para obtener más información, póngase en contacto con su asesor de Audience Manager o con el Servicio de atención al cliente.

### Correcciones y mejoras {#aam-fixes-and-improvements}

* Se ha corregido un error en Audience Marketplace, donde la interfaz de usuario devolvía el Error 409 cuando los clientes enviaban el uso mensual del segmento. (AAM-50825)
* Se ha corregido un error en Señales derivadas, en el que durante un corto tiempo los clientes no podían crear nuevas señales derivadas. (AAM-50968)
* Se ha corregido un error en Destinos basados en personas, en los que los clientes no podían cambiar el nombre de un destino. (AAM-51025)
* Se ha corregido un error en el cual algunos usuarios tenían cuentas duplicadas para iniciar sesión en la interfaz de usuario de Audience Manager. Debido a los permisos asociados a las cuentas duplicadas, estos usuarios no podían acceder a algunas partes de la interfaz de usuario y realizar operaciones. (AAM-50818)
* Se sigue mejorando la accesibilidad de la interfaz de usuario de Audience Manager. (AAM-48932, AAM-48997, AAM-49043, AAM-49054, AAM-49371, AAM-49375, AAM-51313)

## Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Adobe Experience Manager (AEM). Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

### Versiones de productos

* **Brand Portal 6.4.5**

   Adobe Experience Manager Assets Brand Portal 6.4.5 es una compilación de funcionalidades centrada en proporcionar a los usuarios de Brand Portal (agencias o equipos externos) la capacidad de cargar contenido en Brand Portal y publicar en AEM Assets, sin necesidad de acceder al entorno de creación. Esta funcionalidad se denomina [Asset Sourcing en Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/using-asset-sourcing/brand-portal-overiew-using-asset-sourcing.html) y mejora las experiencias de los clientes al proporcionar un mecanismo bidireccional para que los usuarios contribuyan y compartan recursos con otros usuarios de Brand Portal distribuidos globalmente.

   Consulte [Novedades de AEM Assets Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/whats-new.html).

   Consulte las [Notas de la versión](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html).

* **Servicio de Conversión automatizada de AEM Forms**

   El servicio de conversión automatizada de formularios ayuda a acelerar la digitalización y modernización de las experiencias de recopilación de datos mediante la conversión automatizada de formularios PDF a formularios adaptables. El servicio, con la tecnología Adobe Sensei, convierte automáticamente los formularios PDF en formularios adaptables basados en HTML5, fáciles de usar en el dispositivo. A la vez que aprovecha las inversiones actuales en formularios PDF y XFA, el servicio también aplica validaciones, estilo y presentación adecuados a los campos de formulario adaptables durante la conversión.

   Consulte [Servicio de Conversión automatizada de Adobe Experience Manager Forms](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html).

* **Cloud Manager 2019.10.0**

   Ya están disponibles las notas generales de la versión de Cloud Manager 2019.10.0. En las notas también se enumeran las actualizaciones de los pasos de implementación y la gestión de versiones del proyecto.

   Consulte las [notas de la versión de Cloud Manager 2019.10.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html).

### Autoayuda

* **Activity map**

   Debido a los cambios de seguridad dentro de la API de Adobe Analytics, ya no es posible utilizar la versión de Activity Map incluida en AEM. Consulte [Configuración de la conexión a Adobe Analytics](https://helpx.adobe.com/experience-manager/6-5/sites/administering/using/adobeanalytics-connect.html#ConfiguringtheConnectiontoAdobeAnalytics).

   Ahora debe utilizar el [complemento del explorador de Activity Map](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/getting-started/get-started-users/activitymap-install.html) para Chrome, Firefox o Internet Explorer proporcionado por Adobe Analytics.

* **Guía de recomendaciones para proyectos de AEM Screens**

   La nueva _Guía de recomendaciones para proyectos de AEM Screens_ incluye información y recomendaciones prácticas para imaginar, diseñar y añadir experiencias personalizadas para los clientes en su implementación de sistemas de firma digital. También indica cómo crear un impacto positivo en su empresa mediante las recomendaciones, todo mientras implementa un proyecto de publicidad dinámica en AEM Screens.

   Consulte la [Guía de recomendaciones para proyectos de AEM Screens](https://docs.adobe.com/content/help/en/experience-manager-screens/using/about-guide.html).

* **Administración de experiencias indirectas**

   Las funcionalidades del [Procesador de contenido remoto](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#main-pars_header_450130848) que se utilizan en el servidor para la representación de aplicaciones de una sola página ya están documentadas.

* **SPA y procesamiento en el servidor**

   Puede ampliar y personalizar el servicio de representación de contenido remoto que las SPA dirigidas por AEM utilizan para el procesamiento en el servidor, para así satisfacer sus necesidades.

   Consulte [SPA y procesamiento en el servidor](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#RemoteContentRenderer).

* **Arquetipo de AEM Project**

   AEM Project crea un proyecto de Adobe Experience Manager mínimo basado en las recomendaciones como punto de partida para sus propios proyectos de AEM. Las propiedades que se deben proporcionar al utilizar este arquetipo permiten especificar los nombres de todas las partes de este proyecto, así como controlar determinadas funciones opcionales.

   Consulte [Arquetipo de AEM Project](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html).

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

Versión actualizada el 8 de noviembre de 2019.

| Ver | Función |
|------|---------|
| Seguimiento de conversión | La etiqueta de asignación de conversión basada en JavaScript de Advertising Cloud ahora admite el seguimiento de clics de acceso de Mozilla Firefox versión 69 y posteriores, que bloquea las cookies de terceros de forma predeterminada. La misma etiqueta ya incluye compatibilidad con Apple Safari.<br><br/>Si utiliza el seguimiento de conversión de Advertising Cloud y aún no ha implementado la etiqueta de asignación de conversión de Advertising Cloud, implemente el siguiente código en todas las páginas de aterrizaje:<br></br>`<script src="//www.everestjs.net/static/amo-conversion-mapper.js"></script>`<br></br>Nota: Esta etiqueta admite etiquetas de seguimiento de conversión JavaScript v2 y v3 de Advertising Cloud, no la etiqueta de seguimiento de imágenes. |
| Portafolios | Cuando se habilita la opción de portafolio “Habilitar % del objetivo de gasto máximo de campaña”, ahora nunca se supera el objetivo de gasto máximo. Anteriormente, Advertising Cloud superaba el objetivo de gasto máximo cuando era óptimo. |
| Buscar audiencias | La biblioteca de audiencias en Buscar &gt; Audiencias &gt; Biblioteca ahora incluye automáticamente una columna “Tamaño de audiencia”, que se rellena diariamente con Bing Ads y Google Ads. Opcionalmente, puede utilizar la columna como filtro de datos. |
| Integración con Adobe Analytics | Ahora, Analytics incluye la dimensión "Tipo de aterrizaje (AMO ID)" para las campañas de DSP de Advertising Cloud.  Utilice esta dimensión para segmentar las métricas de Analytics en función de cómo llegaron los visitantes al sitio. Los valores incluyen "Pulsaciones" y "Visualizaciones".<br><br/>**Nota:** Los datos de las visualizaciones que se produjeron antes del 31 de octubre de 2019 se muestran como datos de las pulsaciones. De manera que no se recomienda utilizar esta dimensión con datos previos a mediados de noviembre de 2019. |
