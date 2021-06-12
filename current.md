---
title: Últimas notas de la versión
description: Conozca las últimas notas de la versión, las nuevas funciones y la nueva documentación de los productos y servicios de Experience Cloud. Encuentre ayuda y tutoriales nuevos sobre Experience Cloud, Creative Cloud para empresas y Document Cloud.
doc-type: release notes
last-update: June 2021
author: mfrei
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 8adc3fe8f3f4b174d1c41cc7c3162d38a984d661
workflow-type: tm+mt
source-wordcount: '5062'
ht-degree: 51%

---

# Notas de la versión de Adobe Experience Cloud: junio de 2021

![Banner](assets/experience-cloud-banner-3.png)

Las aplicaciones y servicios de Experience Cloud se actualizan mensualmente. Esta página es la ubicación central para buscar las últimas actualizaciones de la versión, documentación y tutoriales para [!DNL Experience Cloud] y [!DNL Experience Platform]. También puede encontrar nueva documentación para [!DNL Creative Cloud for Enterprise] y [!DNL Document Cloud].

>[!NOTE]
>
>Suscríbase a la [Actualización de producto con prioridad de Adobe](https://www.adobe.com/subscription/priority-product-update.html) mensual para recibir notificaciones por correo electrónico sobre actualizaciones de esta página. Esta página se mantiene durante todo el mes, por lo que debe consultar regularmente las actualizaciones de la documentación de Experience League y del producto empresarial de Adobe.

Última actualización: **11 de junio de 2021**

* [Componentes de la interfaz central de Experience Cloud](#ecloud)
* [Estado del sistema de Adobe](#status)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [[!DNL Analytics]](#analytics) y [Customer Journey Analytics](#cust-journey) 
* [[!DNL Audience Manager]](#aam)
* [[!DNL Experience Manager]](#aem)
* [[!DNL Campaign]](#ac)
* [[!DNL Advertising]](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Workfront]](#workfront)
* [Document Cloud](#doc-cloud)
* [Creative Cloud Enterprise](#creative-cloud)

¿Necesita ayuda? Visite [Adobe Experience League](https://experienceleague.adobe.com/?lang=es#home) para encontrar la documentación técnica y de los productos, cursos seleccionados por Adobe, tutoriales de vídeo, respuestas rápidas, información de la comunidad y formación impartida por instructores.

## ![](/assets/ec_appicon_24.png) Icono Componentes de la interfaz de usuario de Experience Cloud Central {#ecloud}

Los componentes de interfaz central de Experience Cloud incluyen actualizaciones a las que se puede acceder desde el encabezado unificado del producto, como las preferencias de autoayuda, búsqueda y cuenta de usuario. Las actualizaciones de People, Places (Ubicación) y la administración de productos se encuentran aquí.

| Función | Fecha | Descripción |
| ------- | ------- | ------- |
| Compatibilidad con inicio de sesión único para Federated ID de Adobe | 17 de junio de 2021 | Si utiliza Federated ID, puede iniciar sesión en el Experience Cloud sin tener que introducir una dirección de correo electrónico o contraseña. Para utilizar esta función, añada **#/sso:@domain** a la dirección URL del Experience Cloud. <br><br>Por ejemplo, suponga que es el propietario del dominio  **adobecustomer.** command y que desea iniciar sesión en Adobe Analytics. La dirección URL sería: **https://experience.adobe.com/#/sso:@adobecustomer.com/analytics**. |
| Búsqueda en Experience League | 1 de junio de 2021 | Se ha mejorado la búsqueda de documentación de Experience League. Vaya a [Experience League](https://experienceleague.adobe.com/docs/?lang=en) y utilice el campo **[!UICONTROL Search]** para localizar tutoriales, documentación, cursos y más. |

{style=&quot;table-layout:auto&quot;}

**Más recursos de ayuda**

* Ayuda de administración para [Componentes de interfaz central](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) y administración de usuarios
* Ayuda y notas de la versión de [Places - Location Service](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=en)
* Ayuda de [People - Atributos del cliente y Biblioteca de audiencias](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)
Para obtener documentación del producto sobre estas funciones, consulte [Componentes de la interfaz central del Experience Cloud](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en).

## ![Icono](/assets/adobe.png) Estado del sistema de Adobe {#status}

[!UICONTROL El estado del sistema de Adobe] proporciona información detallada, actualizaciones de estado y notificaciones por correo electrónico sobre los productos en la nube de Adobe y las interrupciones y sesiones de mantenimiento de los servicios de Adobe. Puede comprobar el estado en [status.adobe.com](https://status.adobe.com/).

Las actualizaciones más recientes del estado del sistema de Adobe se encuentran en [Estado del sistema de Adobe - 21 de mayo de 2020](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=es).

## ![Icono](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Incluye información sobre la actualización de la versión y nueva documentación para el Experience Platform y el Experience Platform Launch.

* **26 de mayo de 2021:** [Notas de la versión del Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=es)
* **17 de mayo de 2021:** [Notas de la versión de recopilación de datos de Experience Platform](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=es)  (anteriormente, Experience Platform Launch)

### Tutoriales y cursos de Experience Platform {#tutorials-platform}

Nuevos vídeos, tutoriales o cursos publicados para Experience Platform y sus servicios.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Junio de 2021 | [Preparar datos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/prepare-data.html) | Vídeo | Aprenda a limpiar, preparar y combinar datos de varios conjuntos de datos para crear un conjunto de datos mediante las funciones Crear tabla AS (CTAS) y Activar SQL para informes y tableros. |
| Junio de 2021 | [Copiar esquemas entre entornos limitados](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/copy-schemas-between-sandboxes.html) | Vídeo | Obtenga información sobre cómo copiar un esquema de un simulador de pruebas a otro en Adobe Experience Platform mediante la [!UICONTROL Export/Import Schema API]. Cree y pruebe los esquemas en entornos limitados de desarrollo y, a continuación, cópielos en producción. |
| Junio de 2021 | [Actualizar esquemas](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/update-schemas.html) | Vídeo | Conozca los aspectos básicos que debe tener en cuenta al actualizar esquemas existentes en Adobe Experience Platform. |
| Junio de 2021 | [Componentes básicos del esquema](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schema-building-blocks.html) | Vídeo | Obtenga información sobre los elementos clave del bloque de creación de los esquemas del Modelo de datos de experiencia (XDM), incluidos los campos, los tipos de datos, los grupos de campos de esquema, las clases y el comportamiento. |
| Junio de 2021 | [Crear clases](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-classes.html) | Vídeo | Aprenda a crear clases en Adobe Experience Platform para utilizarlas en esquemas del Modelo de datos de experiencia (XDM). |
| Junio de 2021 | [Configuración de relaciones entre esquemas](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/configure-relationships-between-schemas.html) | Vídeo | Aprenda a configurar una relación entre dos esquemas en Adobe Experience Platform. Las relaciones permiten utilizar un conjunto de datos como una tabla de búsqueda para otro. |
| Junio de 2021 | [Crear tipos de datos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-data-types.html) | Vídeo | Aprenda a crear sus propios tipos de datos en Adobe Experience Platform para utilizarlos en esquemas del Modelo de datos de experiencia (XDM). |
| Junio de 2021 | [Convertir el modelo de datos en un modelo de datos de experiencia](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/convert-your-data-model-to-xdm.html) | Vídeo | Descubra cómo los arquitectos de datos pueden tomar su modelo de datos transaccionales existente y convertirlo en un modelo de datos de experiencia. Este vídeo muestra la diferencia en los enfoques de modelado mediante diagramas de relación entre entidades. |
| Junio de 2021 | [Planificar el modelo de datos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/plan-your-data-model.html) | Vídeo | Aprenda qué hacer antes de empezar a crear los esquemas en Adobe Experience Platform. Registre sus casos de uso empresarial, comprenda su licencia de Platform, conozca las protecciones del producto e identifique qué datos se van a introducir antes de finalizar su modelo de datos. |
| Junio de 2021 | [Tableau](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/psql-client-tableau.html) | Vídeo | Obtenga información sobre cómo conectarse a [!UICONTROL Query Service] desde varias aplicaciones cliente de escritorio que admite el protocolo `PostgreSQL` y cómo utilizar las herramientas y controladores `PostgreSQL` para conectar y escribir consultas. |
| Junio de 2021 | [Funciones definidas por Adobe](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/adobe-defined-functions.html) | Vídeo | Aprenda a utilizar funciones definidas por Adobe en Adobe Experience Platform [!UICONTROL Query Service] para realizar tareas comunes relacionadas con el negocio en los datos de Experience Event. |
| Junio de 2021 | [Exploración de datos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/explore-data.html) | Vídeo | Obtenga información sobre cómo validar datos ingestados, obtener una vista previa de datos y explorar propiedades estadísticas y analíticas de datos mediante funciones SQL. |
| Junio de 2021 | [Información general del servicio de consultas](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/understanding-query-service.html) | Vídeo | Obtenga información sobre el servicio de consulta en Adobe Experience Platform y cómo ayuda a comprender el comportamiento de los clientes y generar perspectivas impactantes. |
| Junio de 2021 | [Información general sobre la interfaz de usuario del servicio de consulta](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-ui.html) | Vídeo | Obtenga información sobre cómo escribir y ejecutar consultas, ver consultas ejecutadas anteriormente y acceder a consultas guardadas por otros usuarios dentro de su organización de IMS en Adobe Experience Platform Query Service. |
| Junio de 2021 | [API de consulta](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-api.html) | Vídeo | Obtenga información sobre cómo escribir y ejecutar consultas, crear consultas de programación y crear una plantilla de consulta utilizando Adobe Experience Platform [!UICONTROL Query Service API]. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Utilice el Experience Platform para organizar el recorrido de un cliente a escala en todos los canales de experiencia, anticipando de forma inteligente las necesidades de cada individuo en tiempo real.

* Actualizado en junio de 2021: [notas de la versión del Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=es)

**Recursos adicionales para Journey Orchestration**

[Documentación](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=en) - [Vídeos de presentación](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=es)

## ![Icono](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer Decisioning] es un servicio de aplicaciones integrado en Adobe Experience Platform. Utilice [!UICONTROL Offer decisioning] para ofrecer la mejor oferta y experiencia a sus clientes en todos los puntos de contacto y en el momento adecuado.

* Actualizado en abril de 2021: [notas de la versión del Offer decisioning](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=es#new)

**Más recursos para Offer decisioning**

[Documentación](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new) - [Vídeos de presentación](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=es)

## ![Icono](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Fecha de publicación: **17 de junio de 2021**

* [Funciones nuevas en Adobe Analytics](#aa-features)
* [Nuevas funciones en Customer Journey Analytics](#cust-journey)
* [Correcciones en Adobe Analytics](#aa-fixes)
* [Avisos importantes para los administradores de Analytics](#aa-notices)
* [Nuevos cursos y tutoriales de Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Funciones nuevas en Adobe Analytics {#aa-features}

| Función | [Disponibilidad general](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=es) - Fecha de destino | Descripción |
| ----------- | ---------- | ------- |
| N/D | N/D |

{style=&quot;table-layout:auto&quot;}

### Nuevas funciones en Customer Journey Analytics {#cust-journey}

| Función | [Disponibilidad general](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=en) - Fecha de destino | Descripción |
| ----------- | ---------- | ----- |
| N/D | N/D |

{style=&quot;table-layout:auto&quot;}

### Correcciones en Adobe Analytics {#aa-fixes}

* Se ha corregido un problema con la moneda incorrecta que se mostraba en el informe Ingresos en tiempo real . (AN-254649)
* Se ha actualizado la documentación sobre la [distinción entre mayúsculas y minúsculas del eVar en los informes](https://experienceleague.adobe.com/docs/analytics/components/dimensions/evar.html). (AN-246438)
* Se ha actualizado la documentación para explicar mejor [Implementación de fuentes de datos](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/create-feed.html) y [aquí](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/df-faq.html#BucketOwnerFullControl). (AN-219485)
* Se han corregido problemas con algunos datos que no se enviaban en el informe de Data Warehouse (AN-259951; AN-259712; AN-260107; (AN-259953)

#### Correcciones adicionales en Adobe Analytics o CJA

AN-246344; AN-250035; AN-250354; AN-252482; AN-254661; AN-254965; AN-255424; AN-256515; AN-257232; AN-257572; AN-257893; AN-258393; AN-259203; AN-259513; AN-259614; AN-259665; AN-259931; AN-260074; AN-260085; AN-260147; AN-260190; AN-260198; AN-260290; AN-260306 (CJA); AN-260508; AN-260625; AN-260793; AN-260861; AN-260938; AN-260945; AN-261149; AN-261317

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación  o actualizada | Descripción |
| ----------- | ---------- | ---------- |
| Los agentes de usuario del explorador reflejan versiones incorrectas del sistema operativo para Mac OS | 19 de mayo de 2021 | Actualmente, todos los exploradores principales informan incorrectamente a los usuarios de macOSX 11 y versiones posteriores de que están utilizando macOS 10, tal como se ha registrado en la cadena del agente de usuario del explorador. Esto afecta a los informes de Adobe Analytics, ya que utiliza el agente de usuario para determinar la información del dispositivo, como el sistema operativo. Aparentemente, esta inexactitud sirve para evitar problemas de compatibilidad en algunos sitios web. Consulte este [ticket de Bugzilla](https://bugs.webkit.org/show_bug.cgi?id=213622&amp;utm_source=convertkit&amp;utm_medium=email&amp;utm_campaign=User+Agent+strings%2C+new+BigQuery+features%2C+custom+Google+Tag+Manager+loader...+%E2%80%93+Simmer+Newsletter+%2311%20-%205873454) como referencia. No está claro cuándo o si se solucionará este problema.<br>Algunos exploradores registraron inicialmente macOS 11 correctamente, por lo que es posible que haya tráfico que coincida con este valor. Sin embargo, debido a la inexactitud de los informes, no resulta útil filtrar por sistema operativo macOS 11.<br>Esto es significativo porque, a partir de Safari en macOS 11, Apple actualizó las limitaciones de caducidad de las cookies de ITP para aplicarlas a implementaciones CNAME (consulte la [publicación del blog de WebKit](https://webkit.org/blog/11338/cname-cloaking-and-bounce-tracking-defense/)).<br>Antes de esta actualización, estas limitaciones se aplicaban únicamente a las cookies del lado del cliente configuradas mediante JavaScript. Esta inexactitud dificulta la evaluación de la cantidad de tráfico que está usando macOS 11 y, por lo tanto, se ve afectado por el cambio de ITP. Puede obtener más información acerca de las cookies y Adobe Analytics [aquí](https://experienceleague.adobe.com/docs/analytics/technotes/cookies/cookies.html?lang=es#cookies). |
| Fin de la vida útil de tres servicios de API de Analytics | 19 de mayo de 2021 | El 18 de agosto de 2021, los siguientes servicios de API heredadas de Analytics llegaron a su fecha de finalización y se cerraron. Todas las integraciones actuales creadas con estos servicios dejaron de funcionar ese día.<ul><li>API de Analytics 1.3</li><li>API de Analytics SOAP 1.4</li><li>Autenticación OAuth heredada (OAuth y JWT)</li></ul>Adobe pone a su disposición [Preguntas frecuentes del fin de la vida útil de la API heredada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para responder a sus preguntas y proporcionar instrucciones sobre cómo proceder. Las integraciones de API que emplean estos servicios pueden migrar a las [API de REST 1.4 de Analytics](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o a las [API de Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Las cuentas heredadas de OAuth pueden migrar a una cuenta de integración de Analytics [Adobe I/O](https://console.adobe.io/home?mv=email#), que puede utilizarse para acceder tanto a las API de Analytics 1.4 como a las API de Analytics 2.0. |
| Actualizaciones de región ISO 2021 | 13 de mayo de 2021 | Adobe realizará actualizaciones de la zona ISO 2021 el 21 de mayo de 2021. Es de esperar que solo se produzcan actualizaciones menores después de este lanzamiento. |
| Fin de la vida útil de las fuentes de datos de procesamiento completo | 12 de abril de 2021 | Adobe tiene planificado dejar de utilizar el procesamiento completo de fuentes de datos el 31 de julio de 2021. A partir del 25 de marzo de 2021, ya no se podrán crear nuevas importaciones de este tipo. Utilice la [API de inserción de datos masiva](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) para importar este tipo de datos. |
| Actualización de inicio de sesión en [!UICONTROL Report Builder] | 9 de abril de 2021 | El 14 de enero de 2021, las actualizaciones de inicio de sesión de [!UICONTROL Report Builder] eliminaron las dependencias de tecnologías heredadas y alinearon el proceso de inicio de sesión con Experience Cloud. Experience Cloud utiliza su Enterprise ID (correo electrónico y contraseña). Para garantizar el acceso ininterrumpido a [!UICONTROL Report Builder], actualice el complemento [!UICONTROL Report Builder] a la versión 5.6.47 o posterior antes del 22 de julio de 2021. La versión 5.6.47 y posteriores de Report Builder solo admitirán el inicio de sesión de Experience Cloud y no el inicio de sesión único. |
| Cambios en la dirección IP de la fuente de datos y de Data Warehouse | 6 de abril de 2021 | A partir del 17 de junio, el sistema de entrega de Data Feeds y Data Warehouse será reubicado en los centros de datos de Adobe y, por lo tanto, puede haber cambios en las direcciones IP externas que usted ve. Adobe le recomienda que confirme que todos los bloques CIDR de IP del centro de datos donde se originan los informes y las fuentes estén presentes en cualquier cortafuegos de cualquier sistema de destino que usted administra. [Esta es una lista completa de rangos de direcciones IP que deben colocarse en las listas de permitidos del cortafuegos](https://experienceleague.adobe.com/docs/analytics/technotes/ip-addresses.html?lang=es#data-collection-and-ftp-ip-address-blocks). |
| Aviso de los próximos cambios en el menú de Analytics | 24 de marzo de 2021 | El 22 de abril de 2021, actualizaremos los menús desplegables de **[!UICONTROL Componentes]**, **[!UICONTROL Herramientas]** y **[!UICONTROL Administradores]** para lograr algunas mejoras en el rendimiento. Todas estas páginas seguirán estando disponibles en los vínculos **[!UICONTROL Todos los componentes]**, **[!UICONTROL Todas las herramientas]** y **[!UICONTROL Todos los administradores]**. Simplemente se eliminarán del menú desplegable. Estos son los elementos de menú que se eliminarán del menú desplegable y se colocarán en su página de vínculo respectiva:<br><br> [!UICONTROL Componentes]<ul><li>[!UICONTROL Marcadores]</li><li>[!UICONTROL Tableros]</li><li>[!UICONTROL Objetivos]</li><li>[!UICONTROL Eventos de calendario]</li><li>[!UICONTROL Informes programados]</li><li>[!UICONTROL Configuración de informes]</li></ul>Herramientas de <ul><li>[!UICONTROL Recommendations Classic]</li><li>[!UICONTROL Search&amp;Promote]</li></ul>[!UICONTROL Administrador]<ul><li>[!UICONTROL Administración de usuarios]</li><li>[!UICONTROL Importador de clasificaciones]</li><li>[!UICONTROL Clasificación del Generador de reglas]</li><li>[!UICONTROL Fuentes de datos]</li><li>[!UICONTROL Data Connectors]</li><li>[!UICONTROL Configuración de la empresa]</li><li>[!UICONTROL Registros]</li><li>[!UICONTROL Dynamic Tag Management]</li><li>[!UICONTROL Administrador de códigos]</li><li>[!UICONTROL Excluir por dirección IP]</li><li>[!UICONTROL Administración del tráfico]</li></ul> |
| Procesamiento de VISTA igual a SiteCatalyst ON | 17 de marzo de 2021 | El 17 de junio de 2021, todos los grupos de informes se actualizarán para que [!UICONTROL Procesamiento de VISTA igual a SiteCatalyst] esté ACTIVADO. Este cambio afecta a los informes de Data Warehouse al procesar los datos para que coincidan con las reglas de procesamiento. Si tiene alguna pregunta o aclaración, póngase en contacto con el Servicio de atención al cliente. |
| Opciones de la página de aterrizaje Reports &amp; Analytics | 19 de febrero de 2021 | El 25 de marzo de 2021, se eliminaron las opciones para establecer nuevos paneles de Reports &amp; Analytics u otro contenido como página de aterrizaje de Adobe Analytics. Si anteriormente estableció una página de Reports &amp; Analytics como página de aterrizaje personalizada, seguirá funcionando hasta que se modifique la página de aterrizaje en [!UICONTROL Preferencias del usuario]. |
| Fin de la vida útil de Data Connectors de Adobe | 13 de julio de 2020 | Los [!UICONTROL Data Connectors de Adobe] utilizan tecnología antigua que ya no es útil ni compatible. Hay disponible un nuevo estándar en el [Programa de socios de Exchange de Adobe](https://partners.adobe.com/exchangeprogram/experiencecloud). Utilice ese estándar para que se puedan seguir ofreciendo y admitiendo integraciones. La fecha oficial de finalización es el 1 de agosto de 2021. [Más información...](https://experienceleague.adobe.com/docs/analytics/import/dataconnectors/data-connectors-eol.html?lang=es) |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

Para obtener las últimas actualizaciones de las versiones de AppMeasurement, consulte las notas de la versión de [AppMeasurement para JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=es).

### Nuevos cursos y tutoriales de Analytics {#tutorials-analytics}

Nuevos cursos, tutoriales y artículos en [!DNL Analytics] y [!UICONTROL Customer Journey Analytics].

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Junio de 2021 | [Introducción a Customer Journey Analytics para administradores](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | Curso | Obtenga información sobre cómo configurar, configurar y administrar el Customer Journey Analytics. Aprenda algunos conceptos básicos para darle una base y, a continuación, avance en más pasos de configuración. A continuación, el curso se limita con algunas recomendaciones sobre la migración de métricas calculadas y segmentos de Adobe Analytics a Customer Journey Analytics. |
| Junio de 2021 | [Configuración de informes internos de búsqueda del sitio](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/configure-internal-site-search-reports.html?lang=en) | Vídeo | Cree y configure tablas improvisadas en Analysis Workspace para analizar la funcionalidad de búsqueda interna del sitio. |
| Junio de 2021 | [Asignación de variables de SDK web a Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/map-web-sdk-variables-into-adobe-analytics.html?lang=en) | Vídeo | Obtenga información sobre cómo asignar variables de análisis desde el SDK web a Adobe Analytics mediante reglas de procesamiento. |
| Junio de 2021 | [Implementación de variables de búsqueda interna mediante SDK web](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-web-sdk.html?lang=en) | Vídeo | Aprenda a utilizar el SDK web para implementar variables de Adobe Analytics en un caso de uso de seguimiento de términos de búsqueda interna. Consulte el flujo de datos de la página a Experience Edge y, a continuación, a Adobe Analytics. |
| Junio de 2021 | [Implementación de variables de búsqueda interna mediante AppMeasurement](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-appmeasurement.html?lang=en) | Vídeo | En este vídeo, aprenda los pasos para implementar variables de búsqueda interna del sitio para Adobe Analytics mediante la recopilación/Launch de datos del Experience Platform, incluido el término de búsqueda, el número de resultados y otros. |
| Junio de 2021 | [Definición de los requisitos comerciales de búsqueda interna del sitio](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/defining-your-internal-site-search-business-requirements.html?lang=en) | Vídeo | Al decidir si realizar el seguimiento de la búsqueda interna en el sitio, es importante decidir primero qué aspectos de la búsqueda desea rastrear y qué acciones se pueden tomar del análisis de los resultados. Este vídeo muestra la documentación de los requisitos comerciales. |

{style=&quot;table-layout:auto&quot;}

### Recursos de ayuda de Analytics

* [Tutoriales y documentación del producto Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=es)

## ![Icono](/assets/audience-manager.png) Audience Manager {#aam}

Correcciones y mejoras en Audience Manager.

### Correcciones y mejoras {#aam-fixes-and-improvements}

* Se ha publicado una mejora en el [Informe de uso de actividades](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/administration/activity-usage-reporting.html?lang=en) que ahora le permite revisar los datos anteriores a un año. (AAM-58268)
* Adobe proporciona a los clientes Audience Manager claves de acceso de los usuarios para los bloques de Amazon S3 de Audience Manager. Por motivos de seguridad, las claves ahora se desactivan automáticamente tras 100 días de inactividad. Para obtener más información, consulte la pregunta de la parte inferior de la página en las [Preguntas frecuentes sobre la recopilación de datos y la integración del producto](https://experienceleague.adobe.com/docs/audience-manager/user-guide/faqs/faq-data-collection.html?lang=en).

## ![Icono](/assets/aem.png) Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Experience Manager (AEM). Adobe recomienda a los clientes con implementaciones On-Premise implementar los parches más recientes para garantizar más estabilidad, seguridad y rendimiento.

>[!NOTE]
>
>Adobe recomienda visitar la página [Actualizaciones de versión y hoja de ruta de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=es) para mantenerse al día respecto a la información de la versión.

### AEM actualizaciones de productos

* **Experience Manager 6.5.9.0**

   AEM 6.5, Service Pack 9.0 (6.5.9.0, publicado el 27 de mayo de 2021) es una actualización importante que incluye nuevas funciones, mejoras clave solicitadas por el cliente, rendimiento mejorado, estabilidad y seguridad, publicada desde el lanzamiento general de AEM 6.5 en abril de 2019.

   * [Notas de la versión](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=es)
   * [Características de la versión de AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html?lang=en)

### AEM versiones de productos

* **Experience Manager as a Cloud Service**

   Nuevas funciones de Experience Manager como Cloud Service:

   * **Adobe Experience Manager as a Cloud Service Foundation**

      * [Canal](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/prerelease.html?lang=en) previo al lanzamiento: Previsualice las próximas funciones un mes antes de que se activen en la producción.
      * [Desaprobación de API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/deprecated-apis.html?lang=en): Una lista de las API obsoletas más recientes.
      * [Complemento Maven de Experience Manager as a Cloud Service SDK Build Analyzer](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html?lang=en): Actualice sus proyectos maven a la versión más reciente, que incluye una comprobación de API Java™ obsoleta y otras mejoras.
   * **Experience Manager Sites as a Cloud Service**

      * **Puntos finales de GraphQL:** ahora es posible habilitar la API de Experience Manager GraphQL para configuraciones de sitios de Experience Manager individuales y crear extremos personalizados de GraphQL para esas configuraciones mediante la nueva interfaz de usuario de la consola de GraphQL. La interfaz de usuario también permite administrar los extremos de GraphQL.
      * **Modelos de contenido, tipo de datos mejorado de fecha y hora:**  ahora es posible configurar el tipo de fecha de fecha y hora para permitir la creación solo de información de fecha, hora o fecha y hora.
      * **Modelos de contenido, tipo de datos Etiquetas mejorado:** ahora es posible configurar el tipo de datos Etiquetas para permitir la creación de etiquetas únicas o múltiples.
      * **Modelos de contenido, nuevo tipo de datos de marcador de posición de pestañas:**  el nuevo tipo de datos de marcador de posición de pestañas permite agrupar tipos de datos en secciones que se procesan en pestañas en el editor de fragmentos de contenido.
   * **Experience Manager Assets as a Cloud Service**

      Ahora puede verificar el contenido en un nuevo [nivel de vista previa](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/fundamentals/previewing-content.html?lang=en) para simular el aspecto y la presentación finales de la experiencia como lo haría en el nivel de publicación. Esta nueva funcionalidad está habilitada por el asistente de publicación administrada de sitios de Experience Manager, que le permite elegir un destino de publicación entre [!UICONTROL Publicar] o [!UICONTROL Vista previa]. A continuación, se puede acceder a las experiencias en [!UICONTROL Preview] a través de una dirección URL dedicada. Después de la validación en [!UICONTROL Preview], el contenido se puede publicar de [!UICONTROL Author] a [!UICONTROL Publish] como de costumbre. La activación del servicio [!UICONTROL Preview] en Experience Manager como entorno de Cloud Service se está implementando gradualmente en las próximas semanas.

   * **Experience Manager de recursos como Cloud Service**

      Nuevas funciones del canal de prelanzamiento:

      * Los esquemas de metadatos se pueden aplicar directamente a las propiedades de la carpeta.
      * La herramienta [!UICONTROL Asset Bulk Ingestor] permite agregar metadatos durante una ingesta masiva.
      * La mejora de la experiencia del usuario muestra el número de recursos presentes en una carpeta. Para más de 1000 recursos en una carpeta, Recursos de Experience Manager muestra más de 1000.

      Nuevas funciones en [!UICONTROL Dynamic Media]:

      * La proporción de píxeles de dispositivos de imágenes inteligentes (DPR) y la optimización del ancho de banda de la red le permiten ofrecer imágenes de la mejor calidad de forma eficaz, en dispositivos con pantallas de alta resolución y ancho de banda de red restringido. Consulte [preguntas frecuentes sobre imágenes inteligentes](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/dynamicmedia/imaging-faq.html?lang=en).




### **Comunidad AEM**

* [One-Stop-Shop de todos los blogs Experience Manager](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

* [Directrices para enviar una nueva idea de Experience Manager](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/guidelines-for-submitting-a-new-experience-manager-aem-idea/td-p/382376)

* [La Cumbre Adobe 2021 se pasa por alto con Dan Levy](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-sneaks-with-dan-levy/td-p/405865): Una vez al año, cada empleado de Adobe, desde ingenieros y científicos de datos hasta diseñadores de experiencia de usuario y gestores de productos, tiene la oportunidad de compartir ideas innovadoras para desarrollar la manera en que las marcas interactúan con sus clientes. Únete a nosotros para Adobe Sneaks, donde compartimos los siete proyectos principales, pulsando las últimas tecnologías en áreas como IA y aplicaciones de código bajo.

### Información de la versión de Experience Manager

Todas las notas de la versión de Experience Manager se mantienen en las páginas siguientes:

* [Información sobre la versión de Experience Manager como Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=en)
* [Notas de la versión de Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=es)
* [Notas de la versión del servicio de conversión automatizada de Forms](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=en)
* [Notas de la versión de Experience Manager 6.5 Service Pack](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en)
* [Notas de la versión de Experience Manager 6.4 Cumulative Fix Pack](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=es)
* [Notas de la versión de Experience Manager Assets Dynamic Media](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=es)
* [Notas de la versión de Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=es)
* [Notas de la versión de la aplicación de escritorio de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=en)
* [Notas de la versión de Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=es)
* [Notas de la versión de Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=es)

### Nuevos cursos y tutoriales para Experience Manager  {#tutorials-aem}

Nuevos vídeos, tutoriales y cursos publicados durante el mes pasado.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Junio de 2021 | [Implementar los métodos de la interfaz](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/implement-interface.html?lang=en) | Artículo | Obtenga información sobre cómo implementar los métodos de interfaz para crear archivos PDF mediante la API de REST de Document Cloud. |
| Junio de 2021 | [Crear interfaz de servicio](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-interface.html) | Artículo | Defina los métodos en la interfaz que desee exponer. |
| Junio de 2021 | [Crear configuración OSGi personalizada](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-doc-cloud-configuration.html?lang=en) | Artículo | Obtenga información sobre la configuración personalizada de OSGi para poder capturar los detalles del proyecto de Adobe I/O. |
| Junio de 2021 | [Crear analizador de contenido](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/get-content-analyzer.html?lang=en) | Artículo | Aprenda a crear la parte JSON que contiene la información sobre los parámetros de entrada en la llamada Crear REST de PDF. |
| Junio de 2021 | [Crear paso de proceso personalizado](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/custom-process-step.html?lang=en) | Artículo | Vea el código completo del paso de proceso personalizado que convierte y reemplaza los archivos nativos con los PDF convertidos. Este paso personalizado busca todos los archivos adjuntos bajo el nombre de la carpeta, que se proporciona como un argumento de proceso en el flujo de trabajo. Este paso de proceso personalizado utiliza los métodos del `DocumentCloudSDKService` personalizado para crear archivos PDF. |
| Junio de 2021 | [Consultas persistentes de GraphQL](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/video-series/graphql-persisted-queries.html?lang=en) | Vídeo | Obtenga información sobre cómo habilitar, crear, actualizar y ejecutar consultas persistentes en Experience Manager. |
| Junio de 2021 | [Creación del primer servlet en AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-servlet.html?lang=en) | Artículo | Cree su primer servlet sling para poder combinar datos con una plantilla de formulario. |
| Junio de 2021 | [Creación de su primer servicio OSGi con formularios de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-osgi-service.html?lang=en) | Artículo | Cree su primer servicio OSGi con AEM Forms para que pueda generar PDF combinando datos con plantillas. |

{style=&quot;table-layout:auto&quot;}

### Otros recursos de ayuda para Experience Manager

* [Guías de Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=en)
* [Formación y asistencia de Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=es)
* [Formación y asistencia de Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=es)
* [Formación y asistencia de Experience Manager 6.3](https://helpx.adobe.com/es/support/experience-manager/6-3.html)
* [Formación y asistencia de Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=es#previous-updates)
* [Versiones anteriores de la documentación de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Guía del usuario de Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=es)
* [Inicio de la Ayuda de Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=es)
* [Documentación de Experience Manager: Actualizaciones recientes](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=es#aem-as-a-cloud-service)

## ![Icono](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign permite entregar, de forma intuitiva y automatizada, mensajes privados a través de canales de marketing en línea y sin conexión. Ahora puede anticipar los deseos de los clientes mediante experiencias basadas en sus hábitos y preferencias.

### Últimas versiones de productos

Conozca las últimas funciones, mejoras y correcciones publicadas:

* **Nuevo Adobe Campaign v8**  con mejoras significativas en infraestructura, seguridad, capacidad de envío y supervisión. Al utilizar [!DNL Snowflake], una tecnología de base de datos en la nube, Adobe Campaign mejora considerablemente su escala y velocidad, con la capacidad de administrar una cantidad más significativa de perfiles de clientes, así como tasas de envío y transacciones por hora mucho más altas. Obtenga más información en la [documentación de Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html).

* **Versión** de Adobe Campaign Classic v7 21.1.3: Obtenga más información en las notas de la versión de  [Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html).

* **Versión** de Adobe Campaign Standard 21.2: Obtenga más información en las Notas de la versión del  [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html).

### Nuevos cursos y tutoriales de [!UICONTROL Campaign]{#tutorials-campaign}

| Publicadas | Nombre | Solución | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Junio de 2021 | [Integración de Campaign Standard con Analytics para optimizar el marketing por correo electrónico](https://experienceleague.adobe.com/?lang=es#dashboard/learning) | Campaign Standard | (Curso) Aprenda a integrar Campaign Standard con Adobe Analytics y a optimizar sus estrategias de marketing por correo electrónico con datos en tiempo real. Este curso muestra cómo crear un informe de Campaign Standard en Adobe Analytics. A continuación, aprenda a utilizar los Triggers de Experience Cloud y Platform Launch para configurar los mensajes transaccionales y de marketing en función de la actividad del cliente. |
| Junio de 2021 | [Tutoriales de Adobe Campaign V8](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/overview.html) | Campaign V8 | Esta guía del usuario contiene vídeos y tutoriales sobre las numerosas funciones y funcionalidades de Adobe Campaign V8. |
| Junio de 2021 | [Creación y diseño de entregas de correo electrónico](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/content-creation/email/create-and-design-email-deliveries.html) | Campaña V8 | (Vídeo) Conozca el proceso de creación de una entrega por correo electrónico y aprenda a diseñar y personalizar el contenido del correo electrónico. |
| Junio de 2021 | [Diseño de correos electrónicos para la entrega](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/email/design-emails-for-deliverability.html) | Campaña V8 | (Vídeo) Aprenda a aplicar las prácticas recomendadas de envío a los envíos de correo electrónico. |
| Junio de 2021 | [Administrar la fatiga mediante reglas de tipología](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/typology-rules-for-fatigue-management.html) | Campaña V8 | (Vídeo) Aprenda a implementar la administración de la fatiga mediante la aplicación de reglas de tipología. |
| Junio de 2021 | [Configuración de la gestión de la fatiga mediante filtros](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/fatigue-management-using-filters.html) | Campaign Standard | (Vídeo) Aprenda a implementar la administración de la fatiga en Adobe Campaign mediante filtros. |

{style=&quot;table-layout:auto&quot;}

### Recursos de ayuda de Campaign

* Adobe Campaign Standard: [Centro de ayuda](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=en) - [Vídeos de procedimientos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=es) - [Planificación de versiones](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=es) - [Últimas actualizaciones de la documentación](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=es)
* Adobe Campaign Classic: [Centro de ayuda](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=en) - [Vídeos de procedimientos ](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=es)- [Últimas actualizaciones de la documentación](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=es)
* Panel de control de Adobe Campaign: [Documentación](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en) - [Notas de la versión](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en)  - Vídeos prácticos para [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=es) y [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=es)

## ![Icono](/assets/advertising-cloud.png) Publicidad {#adcloud}

Notas de la versión para [!DNL Adobe Advertising].

* [Nuevas funciones de Advertising DSP](#adcloud-dsp)
* [Nuevas funciones en Advertising Search](#adcloud-search)

### Nuevas funciones de la versión [!DNL Advertising DSP] {#adcloud-dsp}

Última actualización: **10 de junio de 2021 para la versión del 16 de junio**

| Función | Descripción |
| -----------| ---------- |
| Administración de campañas | (Versión del 16 de junio) La previsión está disponible para las ubicaciones de visualización estándar con un ritmo y presupuestos de nivel de ubicación. |

{style=&quot;table-layout:auto&quot;}

### Nuevas funciones de la versión [!DNL Advertising Search] {#adcloud-search}

Última actualización: **19 de mayo de 2021, para la versión del 18 de mayo**

| Función | Descripción |
| -----------| ---------- |
| [!UICONTROL Centro de notificaciones beta] | El [!UICONTROL Centro de notificaciones beta] está disponible para todos los usuarios. Puede utilizarlo para suscribirse a notificaciones por correo electrónico y web acerca de errores de autenticación de cuenta, alertas personalizadas activadas y finalización de [!UICONTROL Advertising Insights] que genere.<br>Puede ver las notificaciones desde estas ubicaciones:<ul><li>El panel [!UICONTROL Notificaciones], que se abre desde el vínculo Notificaciones en la parte superior derecha de cualquier página.</li><li>El [!UICONTROL Centro de notificaciones] en [!UICONTROL Insights e informes > Centro de notificaciones beta].</li></ul><br><b>Nota:</b> Debido a las mejoras en el modo de almacenamiento de las notificaciones, se borraron todas las notificaciones existentes. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/magento.png) [!DNL Magento] {#magento}

Consulte las [notas de la versión](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html) de Magento Commerce y Open Source para obtener la información más reciente.

## ![Icono](/assets/target.png)[!DNL Target] {#target}

Consulte las [[!DNL Target] notas de la versión](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=es) para obtener la información más reciente sobre la versión.

## ![Icono](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] es una aplicación completa para la gestión de posibles clientes y para los especialistas en marketing B2B que buscan transformar las experiencias de los clientes al interactuar en todas las fases de los recorridos de compra complejos.

### Actualizaciones centrales de Marketo Engage

Consulte [!DNL Marketo Engage] [programación de versiones](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=en) para obtener la información más reciente sobre el calendario de versiones y las notas de versiones.

## ![Icono](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] es una aplicación de administración de trabajo unificada para compartir ideas, crear contenido, administrar procesos complejos y hacer su mejor trabajo.

Consulte la página [[!DNL Workfront] releases](https://one.workfront.com/s/product-releases) para obtener un resumen de la información más reciente de todos los productos.

## ![Icono](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Nuevos vídeos, tutoriales o cursos publicados para Adobe Document Cloud.

### Cursos y tutoriales para Document Cloud {#tutorials-doc-cloud}

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Junio de 2021 | [Adobe Acrobat para Google Drive](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/acrobatandgoogle.html) | Vídeo | Obtenga acceso a las herramientas PDF que ahorran tiempo y a los flujos de trabajo de firma electrónica directamente dentro de la aplicación de Google Drive. |

{style=&quot;table-layout:auto&quot;}

Para obtener ayuda de Document Cloud, consulte:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=es)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=es)
* [Aprendizaje y asistencia sobre Document Cloud](https://helpx.adobe.com/es/support/document-cloud.html)

## ![Icono](/assets/creative-cloud-24.png) Creative Cloud Enterprise {#creative-cloud}

| Publicadas | Nombre | Tipo | Descripción |
| ----------| --------- | --------- | --------- |
| Junio de 2021 | [Pruebe la mano en el Fresco en el iPad (y en el iPhone)](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/frescoworkshop.html) | Vídeo | Explore todo un mundo nuevo de dibujo digital y pintura con Adobe Fresca en este taller práctico de 15 minutos. Aprenda rápidamente a trabajar con capas y máscaras de recorte para ajustar la pintura y las texturas a una forma base. |
| Junio de 2021 | [Descodificación de la sopa de alfabetos de formatos gráficos](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/alphabetsoup.html) | Vídeo | Los archivos PG, PNG, SVG, GIF y EPS se utilizan normalmente en el diseño, algunos para páginas web, otros para presentaciones, publicaciones y proyectos creativos. Pero... ¿qué quieren decir, y cuál deberías escoger? Averigüe en este taller práctico de 15 minutos. |

{style=&quot;table-layout:auto&quot;}

Consulte [Tutoriales de Creative Cloud para empresas](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=es) para conocer los tutoriales más recientes.
