---
title: Últimas notas de la versión
description: Conozca las últimas notas de la versión, las nuevas funciones y la nueva documentación de los productos y servicios de Experience Cloud. Encuentre ayuda y tutoriales nuevos sobre Experience Cloud, Creative Cloud para empresas y Document Cloud.
doc-type: release notes
last-update: March 2021
author: mfrei
translation-type: tm+mt
source-git-commit: bb6a42b34458a8f1959d4206f546992f4c8e5747
workflow-type: tm+mt
source-wordcount: '7120'
ht-degree: 31%

---


# Notas de la versión de Adobe Experience Cloud: marzo de 2021

![Banner](/assets/experience-cloud-banner-3.png)

Las soluciones y servicios de Experience Cloud se actualizan mensualmente. Esta página es su ubicación central para encontrar las últimas actualizaciones de la versión, la documentación y los tutoriales de los productos y servicios de [!DNL Experience Cloud]. También puede encontrar nueva documentación para [!DNL Creative Cloud for Enterprise] y [!DNL Document Cloud].

>[!NOTE]
>
>Suscríbase a la [Actualización de producto con prioridad de Adobe](https://www.adobe.com/subscription/priority-product-update.html) mensual para recibir notificaciones por correo electrónico sobre actualizaciones de esta página. Esta página se mantiene durante todo el mes y puede contener contenido que esté sujeto a cambios antes de la fecha de lanzamiento. Consulte regularmente las actualizaciones de la documentación de Adobe Enterprise y Experience League.

Actualización más reciente: **22 de marzo de 2021**

* [Estado del sistema de Adobe](#status) (no actualizado)
* [Componentes, servicios y administración de la interfaz de usuario del Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [Analytics](#analytics) y [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [Document Cloud](#doc-cloud)
* [Creative Cloud Enterprise](#creative-cloud)

¿Necesita ayuda? Visite [Adobe Experience League](https://experienceleague.adobe.com/?lang=es#home) para encontrar la documentación técnica y de los productos, cursos seleccionados por Adobe, tutoriales de vídeo, respuestas rápidas, información de la comunidad y formación impartida por instructores.

## ![Icono](/assets/adobe.png) Estado del sistema de Adobe {#status}

[!UICONTROL El estado del sistema de Adobe] proporciona información detallada, actualizaciones de estado y notificaciones por correo electrónico sobre los productos en la nube de Adobe y las interrupciones y sesiones de mantenimiento de los servicios de Adobe. Puede comprobar el estado en [status.adobe.com](https://status.adobe.com/).

Las actualizaciones más recientes del estado del sistema de Adobe se encuentran en [Estado del sistema de Adobe - 21 de mayo de 2020](https://docs.adobe.com/content/help/es-ES/release-notes/experience-cloud/previous/2020/05212020.html#status).

## ![](/assets/ec_appicon_24.png) IconoComponentes, servicios y administración de la interfaz de usuario de Experience Cloud  {#ecloud}

**Búsqueda unificada:** la búsqueda unificada, que actualmente está disponible para Experience Platform, ahora admite la búsqueda de fuentes y destinos para usuarios Experience Platform. Esta función le permite buscar segmentos, conjuntos de datos, esquemas, fuentes y destinos.

## ![Icono](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Incluye información sobre la actualización de versión de Experience Platform y Experience Platform Launch.

* [Notas de la versión de Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html). (Actualizado el 24 de febrero de 2021)
* [Notas de la versión de Experience Platform Launch](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=es). (Actualizado el 18 de febrero de 2021)

### Tutoriales y cursos de Experience Platform

Nuevos vídeos, tutoriales o cursos publicados para Experience Platform y sus servicios.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Marzo de 2021 | [Panel de monitorización](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/monitoring-dashboard.html) | Vídeo | Obtenga información sobre cómo monitorizar y rastrear datos que se incorporan a Adobe Experience Platform mediante el panel de control de Campaign. Este tablero de monitorización proporciona una vista descendente del procesamiento de datos de origen a través del lago de datos a los niveles de ejecución de Perfil e Identidad en los niveles de origen, flujo de datos y flujo de datos, con avisos procesables de forma oportuna. |
| Marzo de 2021 | [Ingesta de datos mediante conectores de flujo del servidor de servidor](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/streaming-ingestion-source-connector.html) | Vídeo | Este vídeo muestra cómo transmitir datos en tiempo real desde una fuente de almacenamiento en la nube a Platform y utilizar los datos en tiempo real para la participación de los clientes. |
| Marzo de 2021 | [Ingesta de datos para ingenieros de datos](https://video.tv.adobe.com/v/331971?quality=12&learn=on) | Vídeo | Información general del curso Ingesta de datos . |
| 5 de marzo de 2021 | [Ingesta de datos para ingenieros de datos](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.1.dataingestion) | Curso | Cómo importar datos de varias fuentes a Adobe Experience Platform, etc. |
| Marzo de 2021 | [Configuración del destino de Azure Blob](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/configure-the-azure-blob-destination.html?lang=es#destinations) | Vídeo | Aprenda a seguir los pasos necesarios para configurar y configurar un destino de almacenamiento de Azure Blob en [!UICONTROL Plataforma de datos del cliente en tiempo real] (CDP en tiempo real). |
| 5 de marzo de 2021 | [Introducción a Offer decisioning para especialistas en marketing](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1.offerdecisioning) | Curso | Obtenga información sobre el servicio de aplicaciones [!UICONTROL Offer decisioning] creado sobre Adobe Experience Platform. Este curso está diseñado para los especialistas en marketing que deseen aumentar los ingresos, la experiencia del cliente y la lealtad mediante el envío de las mejores ofertas a sus clientes. |
| 5 de marzo de 2021 | [Transmisión de datos mediante API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/streaming-ingestion-http-api.html) | Vídeo | Este vídeo muestra cómo transmitir datos a Adobe Experience Platform en tiempo real mediante el extremo de la API HTTP. |
| 5 de marzo de 2021 | [Supervisión de la ingesta de datos mediante API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/data-monitoring.html?lang=es#data-ingestion) | Vídeo | Aprenda a monitorizar y rastrear los datos que se incorporan en Adobe Experience Platform mediante la IU y la API de Platform. |
| 5 de marzo de 2021 | [Ingesta de datos de bases de datos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-databases.html?lang=en#sources) | Vídeo | En este vídeo se explica cómo realizar una ingesta por lotes de datos desde una fuente de base de datos en el Perfil del cliente en tiempo real y el lago de datos de experiencia de Adobe Experience Platform, de forma sencilla y escalable. |
| 5 de marzo de 2021 | [Ingesta de datos de Amazon S3](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-amazon-s3.html) | Vídeo | Este vídeo muestra cómo incorporar fácilmente por lotes datos de servicios de almacenamiento en la nube en el Perfil del cliente en tiempo real y el lago de datos de Adobe Experience Platform, de una manera fácil y escalable. |
| 5 de marzo de 2021 | [Ingesta de datos de Salesforce CRM](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-salesforce-crm.html) | Vídeo | Este vídeo muestra cómo incorporar fácilmente por lotes datos de fuentes CRM al Perfil del cliente en tiempo real de Adobe Experience Platform y al lago de datos, de una manera fácil y escalable. |
| 5 de marzo de 2021 | [Ingesta de datos de Adobe Analytics](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-adobe-analytics.html) | Vídeo | El conector de origen de Adobe Analytics le permite transmitir fácilmente los datos de Adobe Analytics al Perfil del cliente en tiempo real de Adobe Experience Platform y al lago de datos de experiencia, de una manera fácil y escalable. |
| 5 de marzo de 2021 | [Explicación de los conectores de origen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/overview.html?lang=en#sources) | Vídeo | Este vídeo ofrece información general sobre las fuentes o los conectores de origen en el Experience Platform. |
| 5 de marzo de 2021 | [Consola de IO de Adobe Exportar Detalles de Postman](https://experienceleague.adobe.com/docs/platform-learn/tutorials/apis/postman.html) | Vídeo | Obtenga información sobre cómo autenticar y acceder a las API de Experience Platform. |
| 5 de marzo de 2021 | [Explicación de la ingesta de datos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/understanding-data-ingestion.html#data-ingestion) | Vídeo | Obtenga información sobre las funcionalidades de ingesta de datos de Experience Platform que le permiten unir sus datos en una plataforma abierta y escalable para administrar perfiles de clientes en tiempo real. |

## ![Icono](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Utilice Adobe Experience Platform para orquestar el recorrido de un cliente a escala a través de canales de experiencia, anticipando de forma inteligente las necesidades de cada individuo en tiempo real.

### Últimas versiones de productos

Versión de febrero de 2021: obtenga más información sobre las últimas funciones, mejoras y correcciones en las [Notas de la versión del Journey Orchestration](https://docs.adobe.com/content/help/es-ES/journeys/using/release-notes/release-notes.html).

### Nuevos cursos y tutoriales para Journey Orchestration

Nuevos vídeos, tutoriales y cursos publicados durante el mes pasado.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| 16 de marzo de 2021 | [Actualizar acción de perfil](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/building-a-journey/update-profile-action.html?lang=en#building-a-journey) | Vídeo | Obtenga información sobre cómo actualizar un perfil de Experience Platform existente con información proveniente de un evento, una fuente de datos o el uso de un valor específico. |

### Recursos adicionales para Journey Orchestration

[Documentación](https://docs.adobe.com/content/help/es-ES/journeys/using/journey-orchestration-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/es-ES/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![](/assets/experience_platform_appicon_24.png) IconOffer Decisioning  {#offer-decisioning}

[!UICONTROL Offer ] Decisioninges un servicio de aplicaciones integrado con Adobe Experience Platform. Utilice [!UICONTROL Offer decisioning] para ofrecer la mejor oferta y experiencia a sus clientes en todos los puntos de contacto y en el momento adecuado.

### Últimas versiones de productos

Versión de febrero de 2021: obtenga más información sobre las últimas funciones en las [Notas de la versión del Offer decisioning](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new).

### Más recursos para el Offer decisioning

[Documentación](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=en) :  [Vídeos de presentación](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=en)

## ![Icono](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Fecha de la versión: **25 de marzo de 2021**

* [Nuevas funciones en Adobe Analytics](#aa-features)
* [Nuevas funciones en Customer Journey Analytics](#cust-journey)
* [Correcciones en Adobe Analytics](#aa-fixes)
* [Avisos importantes para los administradores de Analytics](#aa-notices)
* [AppMeasurement](#appm)

### Funciones nuevas en Adobe Analytics {#aa-features}

| Función | [Disponibilidad general](https://docs.adobe.com/content/help/es-ES/analytics/landing/an-releases.html) - Fecha de destino | Descripción |
| ----------- | ---------- | ------- |
| Actualizaciones de la API de reparación de datos | 25 de marzo de 2021 | La API de reparación de datos ahora es compatible con variables estándar como [!UICONTROL Page] y [!UICONTROL IP address], variables móviles y de vídeo, así como propiedades y eVars personalizadas.  Los valores dentro de las variables se pueden eliminar o definir nuevos valores. La API ahora también ofrece filtrado para direcciones URL, cadenas de consulta, signos de, etc. |
| Analysis Workspace: [!UICONTROL Componentes] > [!UICONTROL Preferencias de usuario] | 25 de marzo de 2021 | La página [!UICONTROL Componentes] > [!UICONTROL Preferencias de usuario] permite administrar la configuración de [!UICONTROL Analysis Workspace] y sus componentes relacionados para el usuario. [!UICONTROL Las ] preferencias de usuario se aplican a todos los proyectos y paneles nuevos. <br>**Nota:** Las siguientes opciones de configuración se han trasladado a la página  [!UICONTROL Preferencias de ] usuario:<ul><li>Configuración de informes: Separador de miles (ahora llamado _Formato de número_)</li><li>Configuración de informes: Separador CSV</li><li>Proyectos de Workspace: Ayuda > Habilitar sugerencias</li><li>Proyectos de Workspace: Panel en blanco _Iniciar nuevos proyectos con esta opción de panel_</li></ul> |
| Analysis Workspace: [!UICONTROL Predicción del contenedor inteligente de histograma] | 25 de marzo de 2021 | [!UICONTROL La ] predicción del contenedor inteligente del histograma ayuda con los histogramas de métricas de alta cardinalidad al identificar automáticamente la anchura y el número adecuados de bloques para la propagación de los datos. Para las métricas de baja cardinalidad, la visualización se comporta del mismo modo que antes. |
| [!UICONTROL API de ] registro de uso | 25 de marzo de 2021 | Se trata de una nueva API de Analytics v2.0 que habilita el acceso mediante programación a los mismos datos de registro de uso disponibles en **[!UICONTROL Administración]** > **[!UICONTROL Registro]** > **[!UICONTROL Registro de uso y acceso]**. Encontrará más detalles sobre la autenticación, el esquema y la respuesta de ejemplo disponibles [aquí](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/usage-logs.md). |
| Compatibilidad de paneles de Analytics con intervalos de fechas personalizados | 25 de marzo de 2021 | Los creadores de informes de valoración pueden crear y aplicar intervalos de fechas personalizados a los proyectos de informes de valoración móviles. Los creadores pueden elegir entre espacios de trabajo familiares y preconjuntos de intervalos de fechas móviles, o crear un intervalo de fechas personalizado. |

### Nuevas funciones en Customer Journey Analytics {#cust-journey}

| Función | [Disponibilidad general](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - Fecha de destino | Descripción |
| ----------- | ---------- | ----- |
| Compatibilidad con [!UICONTROL paneles de Adobe Analytics] | 25 de marzo de 2021 | [!UICONTROL Customer Journey Analytics]  (CJA) ahora es compatible con el Generador de informes de valoración de paneles de  [!UICONTROL Adobe Analytics y con el ] Creador de aplicaciones móviles. Esto permite a los ejecutivos y usuarios empresariales ver sus KPI de canales cruzados en función de los datos de CJA, utilizando la misma aplicación que ya están utilizando para Adobe Analytics. |
| Analysis Workspace: **[!UICONTROL Componentes]** > **[!UICONTROL Preferencias de usuario]** | 25 de marzo de 2021 | La página [!UICONTROL Componentes] > [!UICONTROL Preferencias de usuario] permite administrar la configuración de [!UICONTROL Analysis Workspace] y sus componentes relacionados para el usuario. [!UICONTROL Las ] preferencias de usuario se aplican a todos los proyectos y paneles nuevos. <br>**Nota:** Las siguientes opciones de configuración se han trasladado a la página  [!UICONTROL Preferencias de ] usuario:<ul><li>Proyectos de Workspace: Ayuda > Habilitar sugerencias</li><li>Proyectos de Workspace: Panel en blanco _Iniciar nuevos proyectos con esta opción de panel_</li></ul> |
| Analysis Workspace: [!UICONTROL Predicción del contenedor inteligente de histograma] | 25 de marzo de 2021 | [!UICONTROL La ] predicción del contenedor inteligente del histograma ayuda con los histogramas de métricas de alta cardinalidad al identificar automáticamente la anchura y el número adecuados de bloques para la propagación de los datos. Para las métricas de baja cardinalidad, la visualización se comporta del mismo modo que antes. |
| Compatibilidad de paneles de Analytics con el Customer Journey Analytics | 25 de marzo de 2021 | La aplicación de paneles de Analytics ahora es compatible con Customer Journey Analytics. Los usuarios con Customer Journey Analytics pueden mostrar KPI de cualquier dato ingerido en Adobe Experience Platform en la aplicación de paneles de Analytics. Customer Journey Analytics le permite combinar varias fuentes de datos para obtener una vista verdadera y multicanal de la experiencia del cliente. Ahora, con la aplicación de paneles de Analytics, puede obtener una vista completa y actualizada de su empresa, en cualquier momento y en cualquier lugar. |

### Correcciones en Adobe Analytics {#aa-fixes}

* Se ha corregido un problema por el cual, después de editar y guardar el nuevo propietario de un segmento, este nuevo propietario no se reflejaba en la interfaz de usuario del segmento. (AN-234502) AN-250970; (AN-250286)
* Se ha corregido un problema que provocaba que un grupo de informes de aplicación consumiera llamadas primarias al servidor y llamadas primarias al servidor móvil. (AN-244029)
* Se ha corregido un problema con el tiempo de respuesta lento de la interfaz de usuario al abrir proyectos de [!UICONTROL Workspace]. (AN-242553)
* Se ha corregido un problema que impedía iniciar sesión en [!UICONTROL Report Builder] después de actualizar a la versión más reciente. (AN-248825)
* Se ha corregido un problema con los permisos de usuario para usuarios no administradores: Un usuario debe tener un permiso siempre y cuando se añada al menos a uno de sus perfiles en [!UICONTROL Admin Console]. Añadir usuarios a perfiles solo debe añadir a los permisos que tienen y no debe eliminar nada de lo que ya tienen derecho a través de otros perfiles de producto. (AN-242723)
* Se ha corregido un problema de codificación de idioma con [!UICONTROL Fuentes de datos]. (AN-249862)
* Se ha corregido un problema que impedía a los usuarios acceder a proyectos compartidos de [!UICONTROL Workspace]. (AN-247814)
* Se ha corregido un problema por el que [!UICONTROL Alert Previews] no coincidía con el número de [!UICONTROL Alerts] activadas. (AN-249392) (AN-250804)

#### Correcciones adicionales de Adobe Analytics

AN-206099; AN-237460; AN-241803; AN-243735; AN-244081; AN-244615; AN-244687; AN-246832; AN-247227; AN-248237; AN-248478; AN-248852; AN-249115; AN-249140; AN-249216; AN-249275; AN-249538; AN-249963; AN-250034; AN-250270; AN-250320; AN-250338; AN-250377; AN-250378; AN-250557; AN-250609; AN-250614; AN-250615; AN-250885; AN-251088; AN-251137; AN-251190; AN-251192; AN-251193; AN-251301; AN-251496; AN-251545; AN-251734; AN-251735; AN-251744; AN-251816; AN-251982; AN-251972; AN-252051; AN-252073; AN-252105; AN-252409; AN-252640

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación o actualizada | Descripción |
| ----------- | ---------- | ---------- |
| [!UICONTROL Procesamiento]  de VISTA igual a SiteCatalyst = ON | 17 de marzo de 2021 | El 17 de junio de 2021, todos los grupos de informes se actualizarán para que [!UICONTROL Procesamiento de VISTA igual a SiteCatalyst] esté activado. Este cambio afecta a los informes de [!UICONTROL Data Warehouse] al procesar los datos para que coincidan con las reglas de procesamiento. Si tiene alguna pregunta o aclaración, póngase en contacto con el Servicio de atención al cliente de Adobe. |
| Fin de la vida útil de [!UICONTROL Procesamiento completo] [!UICONTROL Fuentes de datos] | 10 de marzo de 2021 | El Adobe planea eliminar [!UICONTROL Procesamiento completo] [!UICONTROL Fuentes de datos] en el futuro. A partir del 25 de marzo de 2021, ya no se podrán crear nuevas importaciones de este tipo. Utilice [Bulk Data Insertion API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) para importar este tipo de datos. [Más información](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html) |
| Opciones de la página de aterrizaje Reports &amp; Analytics | 19 de febrero de 2021 | El 25 de marzo de 2021, se eliminarán las opciones para establecer nuevos paneles de Reports &amp; Analytics u otro contenido como página de aterrizaje de Adobe Analytics. Si anteriormente estableció una página de Reports &amp; Analytics como página de aterrizaje personalizada, seguirá funcionando hasta que se modifique la página de aterrizaje en [!UICONTROL Preferencias del usuario]. |
| Fin de la vida útil de Ad Hoc Analysis | Enero de 2021 | [!UICONTROL Ad Hoc Analysis] llega a su fecha de finalización de servicio el 1 de marzo de 2021. Para obtener más información, consulte [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |
| Fin de la vida útil de tres servicios de API de Analytics | 6 de enero de 2021 | El 30 de abril de 2021, los siguientes servicios de la API heredada de Analytics tienen programado alcanzar la fecha de fin de vida útil y se cerrarán. Todas las integraciones actuales creadas con estos servicios dejarán de funcionar ese día.<ul><li>API de Analytics 1.3</li><li>API de Analytics SOAP 1.4</li><li>Autenticación OAuth heredada (OAuth y JWT)</li></ul>Hemos creado [Preguntas frecuentes del fin de la vida útil de la API heredada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para responder a sus preguntas y proporcionar instrucciones sobre cómo proceder. Las integraciones de API que emplean estos servicios pueden migrar a las [API de REST 1.4 de Analytics](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o a las [API de Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Las cuentas heredadas de OAuth pueden migrar a una cuenta de integración de Analytics [Adobe IO](https://console.adobe.io/home?mv=email#), que puede utilizarse para acceder tanto a las API de Analytics 1.4 como a las API de Analytics 2.0. |
| Fin de la vida útil de Data Connectors de Adobe | 13 de julio de 2020 | Los [!UICONTROL Data Connectors de Adobe] utilizan tecnología antigua que ya no es útil ni compatible. Hay disponible un nuevo estándar en el [Programa de socios de Exchange de Adobe](https://partners.adobe.com/exchangeprogram/experiencecloud). Utilice ese estándar para que se puedan seguir ofreciendo y admitiendo integraciones. La fecha oficial de finalización es el 1 de agosto de 2021. [Más información...](https://docs.adobe.com/content/help/es-ES/analytics/import/dataconnectors/data-connectors-eol.html) |

### AppMeasurement {#appm}

Para obtener las últimas actualizaciones de las versiones de AppMeasurement, consulte las notas de la versión de [AppMeasurement para JavaScript](https://docs.adobe.com/content/help/es-ES/analytics/implementation/appmeasurement-updates.html).

### Recursos de ayuda de Analytics

* [Tutoriales y documentación del producto Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=es-ES)

## ![Icono](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Correcciones y mejoras en Audience Manager.

### Correcciones y mejoras {#aam-fixes-and-improvements}

* Se ha resuelto un problema en el [Informe de estado de integración](https://experienceleague.adobe.com/docs/audience-manager/user-guide/reporting/onboarding-status-report.html?lang=es). Este problema consistía en una discrepancia entre los registros del informe y los del archivo cargados por un socio de integración. (AAM-57415)
* Se ha corregido un problema que provocaba una validación incorrecta de asignación de segmentos duplicados para **[!UICONTROL People-Based Destinations]**. (AAM-56631)
* Se ha corregido un problema que bloqueaba el acceso de algunos usuarios a **[!UICONTROL Informes de audiencia]**. (AAM-57412)
* Se ha parcheado una vulnerabilidad [!UICONTROL Remote Code Execution] que los atacantes podrían usar para acceder a datos confidenciales. (AAM-57495)

### Cursos y tutoriales para Audience Manager {#tutorials-aam}

Nuevos vídeos, tutoriales o cursos publicados para Audience Manager.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| 19 de marzo de 2021 | [Explicación de la administración de datos en tiempo real de CDP para usuarios Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-data-gov-for-aam-users.html) | Vídeo | Obtenga información sobre la funcionalidad de administración de datos en [!UICONTROL Plataforma de datos del cliente en tiempo real]. |
| 19 de marzo de 2021 | [Una historia de dos percepciones: marcas vs. consumidores](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/brands-vs-consumers.html) | Vídeo | En este seminario web, el Adobe revela el nivel de comprensión y preparación de los anunciantes y editores para un futuro sin cookies, el impacto en sus casos de uso y su percepción del ecosistema en general. |
| 5 de marzo de 2021 | [10 consideraciones para la administración responsable de datos del cliente](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/ten-considerations-for-responsible-customer-data-management.html) | Evento | Escuche de Adobe y Scotiabank Digital las consideraciones clave para la administración responsable de datos. |
| 19 de marzo de 2021 | [El futuro de la gestión de datos y el entorno cambiante](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/the-future-of-data-management-and-the-changing-environment.html) | Evento | En este seminario web, vea cómo Adobe y 451 Research piensan en el futuro de la tecnología y los datos para abordar el nuevo entorno de marketing y comenzar a preparar su negocio para el futuro de la gestión de datos. |
| 21 de marzo de 2021 | [Explicación de los esquemas y XDM en CDP en tiempo real para usuarios Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-schemas-xdm-for-aam-users.html?lang=en#other-integrations) | Vídeo | A medida que pase del Audience Manager a la plataforma de datos del cliente en tiempo real (CDP en tiempo real), encontrará algunos conceptos y prácticas nuevos. Los esquemas y XDM entran dentro de esa categoría. Este vídeo explica estos conceptos. |
| 17 de marzo de 2021 | [Explicación de las señales en CDP en tiempo real para usuarios Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-signals-for-aam-users.html) | Vídeo | Este vídeo está diseñado para usuarios Audience Manager que se trasladan a la Plataforma de datos del cliente en tiempo real (CDP en tiempo real) y analiza cómo se utilizan en Platform las señales (pares clave-valor) que utiliza en el Audience Manager para crear características. |
| 12 de marzo de 2021 | [Explicación de los esquemas y XDM en CDP en tiempo real para usuarios Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-schemas-xdm-for-aam-users.html) | Vídeo | A medida que pase del Audience Manager a la plataforma de datos del cliente en tiempo real (CDP en tiempo real), encontrará algunos conceptos y prácticas nuevos. Los esquemas y XDM entran dentro de esa categoría. Este vídeo explica estos conceptos. |
| 12 de marzo de 2021 | [Explicación de la ingesta de datos web en CDP en tiempo real para usuarios Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-web-ingestion-for-aam-users.html) | Vídeo | Conozca los conceptos relativos a la introducción de datos de sitios web en la plataforma de datos del cliente en tiempo real (CDP en tiempo real) e incluya un contacto de alto nivel sobre dónde se adapta el conector de datos del Audience Manager, así como la forma en que los datos pueden moverse del sitio web directamente a través del SDK web a CDP en tiempo real. |
| 3 de marzo de 2021 | [Explicación de los segmentos en CDP en tiempo real para usuarios Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-segments-for-aam-users.html?lang=en#other-integrations) | Vídeo | Conozca las diferencias en la creación de segmentos y segmentos entre CDP en tiempo real y Audience Manager. |
| 3 de marzo de 2021 | [Explicación de los rasgos en CDP en tiempo real para usuarios Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-traits-for-aam-users.html?lang=en#other-integrations) | Vídeo | Conozca las características en Audience Manager y qué equivalente se encuentra en CDP en tiempo real. |
| 3 de marzo de 2021 | [Introducción al curso: Habilidades avanzadas del Audience Manager](https://video.tv.adobe.com/v/331788/?quality=12&learn=on) | Vídeo | Aprenda lo que le espera en el curso Audience Manager de habilidades avanzadas. |
| 3 de marzo de 2021 | [Explicación de la ingesta de datos de origen en CDP en tiempo real para usuarios Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-1pd-ingestion-for-aam-users.html?lang=en#other-integrations) | Vídeo | Obtenga información sobre la ingesta de datos sin conexión de origen en la plataforma de datos del cliente en tiempo real (CDP en tiempo real). Obtenga información sobre algunas de las principales diferencias entre los dos productos con respecto a la ingesta de datos y muestra cómo se puede utilizar el conector de datos del Audience Manager como una brecha de parada hasta que los procesos se hayan trasladado a CDP en tiempo real. |
| 1 de marzo de 2021 | [Comercializar las audiencias que posee ofreciéndoles a un Audience Marketplace](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/audience-marketplace/selling-data/commercialize-owned-audiences-on-marketplace.html?lang=en#audience-marketplace) | Vídeo | Obtenga información sobre cómo configurar los datos como una fuente de datos pública o privada en el Audience Marketplace, lo que lo convierte en un proveedor de datos de segundo o tercer nivel. |
| Marzo de 2021 | [Creación y administración de la activación de datos en el Audience Manager](https://experienceleague.adobe.com/?lang=es&amp;recommended=AudienceManager-U-1-2020.4) | Curso | En este curso, aprenda todo sobre la activación de audiencias, por ejemplo, el envío de datos de audiencia a socios de destino para personalizar la experiencia para los usuarios finales. Conozca los conceptos básicos de los destinos, cómo elegir el destino adecuado y cómo preparar y enviar datos de audiencia a destinos de redes sociales basados en personas, no en cookies. |
| Marzo de 2021 | [Habilidades avanzadas del Audience Manager](https://experienceleague.adobe.com/?lang=es&amp;recommended=AudienceManager-U-1-2020.5) | Curso | Una vez dominados los conceptos básicos de Audience Manager, siga este curso para obtener información sobre cómo llevar la Gestión de público al siguiente nivel. Aprenda a utilizar la IA con modelos algorítmicos, a utilizar las reglas de combinación de perfiles para comprender a sus clientes como personas en lugar de como dispositivos, y otros temas buenos para ampliar el uso del DMP. |

## ![Icono](/assets/aem.png) Adobe Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Experience Manager. Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

>[!NOTE]
>
>Adobe recomienda visitar la página [Actualizaciones de versión y hoja de ruta de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=es) para mantenerse al día con respecto a la información de la versión.

### Versiones de productos

* **AEM 6.5.8.0**
AEM 6.5, Service Pack 8 (6.5.8.0, publicado el 11 de marzo de 2021) es una actualización importante que incluye nuevas funciones, mejoras clave para el cliente, así como mejoras de rendimiento, estabilidad y seguridad, publicada desde el lanzamiento general de AEM 6.5 en abril de 2019.
   * [Notas de la versión](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=es#service-pack)
   * [Características de la versión de AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html?lang=es#forms-updates)

* **AEM 6.4.8.4**
AEM 6.4, Service Pack 8, Cumulative Fix Pack 4 (6.4.8.4 publicado el 25 de febrero de 2021) es una actualización importante que incluye varias correcciones internas y de cliente desde la disponibilidad general de AEM 6.4, Service Pack 8 (6.4.8.0) en marzo de 2020.
   * [Notas de la versión](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=es)
   * [Características de la versión de AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

* **Adobe Experience Manager as a Cloud Service**

   ¿Qué novedades hay en Experience Manager como Cloud Service?

   * **Experience Manager de sitios como Cloud Service**

      * [El componente](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/remote-page.html?lang=en) RemotePage: Se ha agregado compatibilidad con la visualización y edición de SPA externas dentro del Experience Manager mediante .
      * [Edición de un SPA externo en el Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/editing-external-spa.html?lang=en): Se ha añadido la capacidad de cargar una aplicación independiente de una sola página en una instancia de Experience Manager, agregar secciones de contenido editables y habilitar la creación.
   * **Experience Manager Assets as a Cloud Service**

      * Recursos de Experience Manager como Cloud Service tiene derecho a tener una instancia preconfigurada de Brand Portal. El usuario de Cloud Manager puede activar Brand Portal en Recursos de Experience Manager como Cloud Service. Consulte [Activación de Brand Portal mediante Brand Portal](https://experienceleague.corp.adobe.com/docs/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html).
      * Las empresas ahora pueden obtener recursos mediante Brand Portal. La función de abastecimiento de recursos utiliza Brand Portal para ayudar a los clientes a interactuar con los usuarios de la agencia a fin de que obtengan recursos para nuevas campañas de marketing, fotos y proyectos. Consulte [Descripción general de Asset Sourcing](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/brand-portal-asset-sourcing.html?lang=en) en la Guía de Brand Portal.
      * El informe de uso de Brand Portal ahora muestra solamente los usuarios activos. Los usuarios inactivos no se muestran ahora. Los usuarios activos son aquellos cuya cuenta se asigna a un perfil de producto en el Admin Console. Consulte [Trabajar con informes](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/admin-tools/brand-portal-reports.html?lang=en) en la guía de Brand Portal.
      * En Brand Portal, se introduce una nueva configuración de descarga que permite crear carpetas independientes para cada recurso al descargar carpetas, colecciones, etc. Consulte [Descarga de recursos](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/download/brand-portal-download-assets.html?lang=en) en **Descarga de recursos desde Brand Portal** en la Guía de Brand Portal.
   * **Experience Manager de Forms as a Cloud Service**

      AEM Forms ha ayudado a muchas organizaciones a ofrecer buenas experiencias de incorporación e inscripción a lo largo de los años. Estas experiencias han ayudado a las organizaciones a convertir posibles clientes en ventas, a procesar los datos capturados de los clientes, a ofrecer experiencias adaptables basadas en el perfil de audiencia y mucho más. Ahora, AEM Forms está disponible como servicio en la nube.

      Puede utilizar AEM Forms como Cloud Service para crear formularios digitales, conectar formularios a orígenes de datos existentes, integrar formularios con Adobe Sign para agregar firmas electrónicas a formularios, generar documento de registro (DoR) para archivar formularios enviados como archivos PDF. El servicio también puede convertir los PDF forms existentes en formularios digitales. Además de las funciones estándar de AEM Forms, el servicio ofrece varias funciones nativas de la nube, como el escalado automático, el tiempo de inactividad cero para las actualizaciones y el entorno de desarrollo nativo de la nube. Lea [esta publicación de blog](https://blog.adobe.com/en/publish/2021/03/11/experience-manager-forms-as-a-cloud-service.html) para obtener más información sobre las funcionalidades y características de AEM Forms como Cloud Service.

      Póngase en contacto con el representante de su Adobe para realizar una demostración o registrarse en el servicio.


   * **Experience Manager Commerce as a Cloud Service**

      * Administración de experiencia del producto: Enriquezca las páginas del catálogo de productos individualmente con fragmentos de experiencias.
      * Se han ampliado las propiedades de la consola de producto para mostrar los recursos vinculados y los fragmentos de experiencia, incluida la acción para navegar rápidamente al contenido asociado.
      * Sitio de referencia de Venia del CIF publicado - 2021.02.24 que incluye la versión más reciente de los componentes principales del CIF 1.8.0. Consulte [Sitio de referencia de Venia del CIF 2021.02.24](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2021.02.24) para obtener más información.
      * Componentes principales de CIF versión 1.8.0. Consulte [Componentes principales de CIF 1.8.0](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.8.0) para obtener más información.
   * **Cloud Manager**

      * Los clientes con entornos que tienen configuraciones de nombre de dominio personalizado preexistentes para [Listas de permitidos IP](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/ip-allow-lists/check-ip-allow-list-status.html?lang=en#pre-existing-cdn), [certificados SSL](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/manage-ssl-certificates/check-status-ssl-certificate.html?lang=en#pre-existing-cdn) y [nombres de dominio personalizados](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/custom-domain-names/check-domain-name-status.html?lang=en#pre-existing-cdn) ahora ven un mensaje sobre las configuraciones existentes anteriormente. También pueden autoabastecerse mediante la interfaz de usuario.
      * Los usuarios con los permisos necesarios ahora pueden editar un programa, lo que les permite hacer lo siguiente de forma autoservicio:
         * Agregar la solución Sitios a un programa existente con Assets o a la inversa.
         * Elimine Sitios o Recursos de un programa existente con Sitios y Recursos.
         * Agregue el derecho de solución no utilizado a un programa existente o como un programa nuevo.
      * **AEM** actualización push ahora se muestra para las pantallas  *Ejecución de la* canalización y  ** Actividad.
      * Si un entorno está en hibernación, pero también hay una actualización de Experience Manager disponible, el estado **Hibernated** tiene prioridad sobre **Update available**.
      * Los usuarios ahora pueden ver sus funciones de Cloud Manager seleccionando **Ver funciones de Cloud Manager** después de navegar al icono de perfil de usuario (parte superior derecha) del shell unificado.
      * La etiqueta **Application for Approval** se ha vuelto a etiquetar como **Production Approval** para una buena claridad.
      * La etiqueta **Version** se ha vuelto a etiquetar como **Git Tag** en la pantalla de ejecución de la canalización de producción.
      * Las etiquetas que definen el comportamiento cuando métricas importantes no alcanzan el umbral definido se han vuelto a etiquetar para reflejar su verdadero comportamiento: **Cancelar inmediatamente** y **Aprobar inmediatamente**.
      * Las listas de eliminación de clases y métodos se han actualizado en función de la versión `2021.3.4997.20210303T022849Z-210225` del SDK de Experience Manager Cloud Service.
      * La canalización de producción de Cloud Manager ahora incluye la capacidad [Pruebas de IU personalizadas](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/test-results/functional-testing.html?lang=en#custom-ui-testing).




### **Comunidad**

* **Adobe Developers Live 2021 | Lista de sesión completa**

   [](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-2021-complete-session-list/m-p/394595#M27875) Esta es una lista agregada de todas las sesiones de Experience Manager que se producen en  **Adobe Developers Live**.

* **Cumbre Adobe 2021 | Lista de sesiones completa del Experience Manager**

   [](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-complete-aem-session-list/td-p/398344) Esta es una lista agregada de todas las sesiones de Experience Manager que se llevaron a cabo en la Cumbre del  **Adobe 2021**.

### Información de la versión de Experience Manager

Todas las notas de la versión de Experience Manager se mantienen en las páginas siguientes:

* [Actualización de la versión de Experience Manager y del plan de trabajo](https://docs.adobe.com/content/help/es-ES/experience-manager-release-information/aem-release-updates/home.html)
* [Información sobre la versión de Experience Manager como Cloud Service](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/release-notes/home.html)
* [Notas de la versión de Experience Manager Cloud Manager](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Notas de la versión del servicio de conversión automatizada de Forms](https://docs.adobe.com/content/help/es-ES/aem-forms-automated-conversion-service/using/release-notes.html)
* [Notas de la versión de Experience Manager 6.5 Service Pack](https://docs.adobe.com/content/help/es-ES/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Notas de la versión de Experience Manager 6.4 Cumulative Fix Pack](https://docs.adobe.com/content/help/es-ES/experience-manager-64/release-notes/cfp-release-notes.html)
* [Notas de la versión de Experience ManagerAssets Dynamic Media](https://docs.adobe.com/content/help/es-ES/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notas de la versión de Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [Notas de la versión de la aplicación de escritorio de Experience Manager](https://docs.adobe.com/content/help/es-ES/experience-manager-desktop-app/using/release-notes.html)
* [Notas de la versión de Experience Manager Dispatcher](https://docs.adobe.com/content/help/es-ES/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Notas de la versión de Livefyre](https://docs.adobe.com/content/help/es-ES/livefyre/using/release-notes/c-rn.html)

### Cursos y tutoriales de Experience Manager

Nuevos vídeos, tutoriales y cursos publicados durante el mes pasado.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Marzo de 2021 | [Entrega de contenido en el Experience Manager Cloud Service](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/content/feb2021/content-delivery.html#content) | Evento | Adobe Experience Manager as a Cloud Service tiene una potente arquitectura de entrega de contenido preconfigurada. Demostrar cómo sacar el máximo partido a las configuraciones de entrega de contenido optimizado |
| Marzo de 2021 | [Migrar el artículo de ayuda sobre tipos de documentos y Forms a ExL](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/pdf-forms-and-documents.html?lang=en#document-services) | Artículo | Un artículo que explica los diferentes tipos de PDF forms y documentos. |
| Marzo de 2021 | [Implementación de producción con un entorno de publicación de AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/production-deployment.html#graphql) | Tutorial | Configure un entorno local para simular el contenido que se distribuye desde una instancia de Autor a una instancia de Publicación. Genere una compilación de producción de una aplicación React configurada para consumir contenido del entorno AEM Publish utilizando las API de GraphQL. A lo largo del camino, aprenderá a utilizar de forma eficaz las variables de entorno y a actualizar las configuraciones AEM CORS. |
| Marzo de 2021 | [Administración de contenido sin encabezado mediante las API de GraphQL](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.headless) | Curso | Descubra cómo se pueden utilizar las API de GraphQL de AEM y las capacidades sin objetivos para potenciar las experiencias que aparecen en una aplicación externa. |
| Marzo de 2021 | [Lanzamientos: vídeo de funciones](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/page-authoring/launches.html) | Vídeo | Los lanzamientos en AEM Sites proporcionan una forma de crear, crear y revisar el contenido del sitio web para futuras versiones. Durante la creación del lanzamiento, el sitio web de producción puede seguir evolucionando y cambiando día a día como lo haría normalmente. |
| Marzo de 2021 | [Recursos relacionados y no relacionados: Vídeo de funciones](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/relate-unrelate.html?lang=es) | Vídeo | Obtenga información sobre cómo establecer y administrar relaciones entre recursos en AEM. |
| Marzo de 2021 | [Autentificación para AEM como Cloud Service desde una aplicación externa](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.aemcs) | Curso | Descubra cómo una aplicación externa puede utilizar los tokens de acceso de desarrollo local y las credenciales de servicio para autenticarse mediante programación para AEM como Cloud Service a través de HTTP. |
| Marzo de 2021 | [Rellenar y firmar varios formularios en una aplicación hipotecaria](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.7.forms&amp;lang=es-ES) | Curso | Firme un paquete de documentos sin problemas mediante la integración de AEM Forms y Sign. Los datos introducidos en el formulario se pueden utilizar para rellenar previamente formularios posteriores en el paquete. |
| Marzo de 2021 | [Versiones / Deformación de tiempo en AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/page-authoring/timewarp-feature-video-use.html) | Vídeo | Deformación de tiempo es una función de Adobe Experience Manager Sites que proporciona a los autores una forma rápida de revisar el estado de una página en un momento específico en el pasado. |
| Marzo de 2021 | [Foundation - Workflow Management](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/workflow/use-workflow-management.html?lang=en#workflow) | Vídeo | Este vídeo utiliza modelos de flujo de trabajo para mostrar este conjunto de funciones, aunque también son aplicables a AEM lanzadores. |
| Marzo de 2021 | [Bloques de fragmentos de experiencias](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/experience-fragments/building-blocks.html) | Vídeo | Los bloques de creación son una subfunción de los fragmentos de experiencias. Los bloques de creación permiten a los autores de contenido reutilizar componentes en diferentes variaciones de fragmentos de experiencias. |
| Marzo de 2021 | [Editor de flujo de trabajo](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/workflow/use-the-workflow-editor.html?lang=en#workflow) | Vídeo | El flujo de trabajo permite la administración de procesos del negocio en el Experience Manager y se utiliza para el procesamiento automático de contenido, así como para facilitar la gobernanza y el proceso que requieren la toma de decisiones por parte de los humanos. |
| Marzo de 2021 | [Grupos de usuarios cerrados en AEM Assets](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/closed-user-groups.html) | Vídeo | Grupos de usuarios cerrados (CUG) es una función que se utiliza para restringir el acceso al contenido a un grupo selecto de usuarios en un sitio publicado. Este vídeo muestra cómo se pueden utilizar los grupos de usuarios cerrados con Adobe Experience Manager Assets para restringir el acceso a una carpeta específica de recursos. |
| Marzo de 2021 | [Informes ](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/asset-reports.html) | Vídeo | Descubra cómo AEM Assets proporciona un marco de informes a nivel empresarial que se adapta a repositorios grandes a través de una experiencia de usuario intuitiva. |
| Marzo de 2021 | [Etiquetas inteligentes para imágenes con AEM Assets](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/image-smart-tags.html) | Vídeo | Las etiquetas inteligentes para imágenes aumentan AEM capacidades de búsqueda mediante la adición automática e inteligente de etiquetas de metadatos a los recursos de imagen en función del contenido de la imagen. |
| Marzo de 2021 | [Metadatos en cascada, visibilidad](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/cascade-metadata-feature-video-use.html) | Vídeo | Obtenga información sobre las nuevas reglas dinámicas para los requisitos de campo, la visibilidad y las opciones contextuales. El vídeo también detalla los pasos necesarios para que un administrador aplique estas reglas a un esquema de metadatos personalizado. |
| Marzo de 2021 | [Principales proyectos](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/projects/use-project-masters.html?lang=en#delete-project-masters) | Vídeo | La eliminación de un proyecto maestro da como resultado proyectos derivados que no se pueden utilizar. |
| Marzo de 2021 | [Personalización de las propiedades de página](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/developing/page-properties-technical-video-develop.html) | Vídeo | Cree un vídeo técnico sobre cómo ampliar y personalizar mejor las Propiedades de página. |
| Marzo de 2021 | [Traducción de fragmentos de contenido](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-translation-feature-video-use.html) | Vídeo | Descubra cómo se pueden localizar y traducir los fragmentos de contenido con Adobe Experience Manager. Los recursos de medios mixtos asociados a un fragmento de contenido también pueden extraerse y traducirse. |
| Marzo de 2021 | [Fragmentos de experiencias](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/experience-fragments/experience-fragments-feature-video-use.html) | Vídeo | Descubra cómo los fragmentos de experiencias permiten a los autores de contenido reutilizar contenido en varios canales, incluidas las páginas Sitios y sistemas de terceros. |
| Marzo de 2021 | [Aumento de búsqueda de búsqueda mejorada](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/search-and-discovery/search-boost.html) | Vídeo | Obtenga más información sobre el Boost de búsqueda. |

### Otros recursos de ayuda para Experience Manager

* [Guías de Experience Manager como Cloud Service](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/landing/home.html)
* [Formación y asistencia de Experience Manager 6.5](https://helpx.adobe.com/es/support/experience-manager/6-5.html)
* [Formación y asistencia de Experience Manager 6.4](https://helpx.adobe.com/es/support/experience-manager/6-4.html)
* [Formación y asistencia de Experience Manager 6.3](https://helpx.adobe.com/es/support/experience-manager/6-3.html)
* [Formación y asistencia de Experience Manager 6.2](https://helpx.adobe.com/es/support/experience-manager/6-2.html)
* [Guía del usuario de Cloud Manager](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Versiones anteriores de la documentación de Experience Manager](https://helpx.adobe.com/es/experience-manager/aem-previous-versions.html)
* [Inicio de la Ayuda de Dynamic Media Classic](https://docs.adobe.com/content/help/es-ES/dynamic-media-classic/using/home.html)

## ![Icono](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign permite entregar, de forma intuitiva y automatizada, mensajes privados a través de canales de marketing en línea y sin conexión. Ahora puede anticipar los deseos de los clientes mediante experiencias basadas en sus hábitos y preferencias.

### Últimas versiones de productos

Obtenga más información sobre las últimas funciones, mejoras y correcciones publicadas:

* [Notas de la versión de Campaign Standard](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/release-notes/release-notes.html)
* [Notas de la versión de Campaign Classic](https://docs.adobe.com/content/help/es-ES/campaign-classic/using/release-notes/latest-release.html).

>[!IMPORTANT]
>
>Obtenga información sobre las [actualizaciones de configuración necesarias](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/acc-config-updates.html?lang=en) para Adobe Campaign Classic.

### Nuevos cursos y tutoriales de Campaign

Nuevos vídeos, tutoriales y cursos publicados durante el mes pasado.

| Publicadas | Nombre | Solución | Descripción |
| -----------| ---------- | ---------- | ---------- |
| 23 de febrero de 2021 | [Capacidad de entrega: métricas para la capacidad de entrega](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/metrics-overview.html) | Campaign Classic/Estándar | Obtenga información sobre las métricas clave de capacidad de envío que se deben monitorizar y cómo utilizarlas para identificar un problema de reputación. |
| 23 de febrero de 2021 | [Capacidad de entrega: devoluciones](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/bounces.html) | Campaign Classic/Estándar | Obtenga información sobre los distintos tipos de devoluciones. |
| 23 de febrero de 2021 | [Capacidad de entrega: quejas](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/complaints.html) | Campaign Classic/Estándar | Obtenga información sobre las quejas que se registran cuando un usuario indica que un correo electrónico es no deseado o inesperado. |
| 23 de febrero de 2021 | [Capacidad de entrega: trampas de correo no deseado](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/spam-traps.html) | Campaign Classic/Estándar | Obtenga información sobre los distintos tipos de devoluciones. |
| 23 de febrero de 2021 | [Capacidad de entrega: activación de lotes y bloqueo](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/bulking-and-blocking.html) | Campaign Classic/Estándar | Descubra por qué los ISP colocan los mensajes de correo electrónico en carpetas masivas o los bloquean. |
| 23 de febrero de 2021 | [Capacidad de entrega - Proceso de transición - Infraestructura](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/infrastructure.html) | Campaign Classic/Estándar | Aprenda lo que se necesita para construir correctamente una infraestructura de correo electrónico. |
| 23 de febrero de 2021 | [Capacidad de entrega: participación](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/engagement.html) | Campaign Classic/Estándar | Obtenga información sobre los diferentes tipos de participación y por qué la participación importa para la capacidad de envío. |
| 23 de febrero de 2021 | [Capacidad de entrega - Proceso de transición: Criterios de segmentación](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/targeting-criteria.html) | Campaign Classic/Estándar | Aprenda a establecer una reputación positiva desde el principio para crear confianza de forma eficaz antes de rodar en sus audiencias menos comprometidas. |
| 23 de febrero de 2021 | [Capacidad de entrega: proceso de transición: consideraciones específicas del ISP durante el calentamiento de la IP](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/isp-specific-considerations-during-ip-warming.html) | Campaign Classic/Estándar | Obtenga información sobre las diferentes reglas y formas que los proveedores de ISP tienen para ver su tráfico |
| 24 de febrero de 2021 | [Capacidad de entrega: primeras impresiones: introducción](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/introduction.html) | Campaign Classic/Estándar | Aprenda cómo puede configurarse para ejecutar un programa de correo electrónico exitoso haciendo una buena primera impresión en esas áreas. |
| 24 de febrero de 2021 | [Capacidad de entrega - Proceso de transición: Volumen](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/volume.html) | Campaign Classic/Estándar | Comprenda cómo el envío de volumen influye en la capacidad de envío de sus campañas de correo electrónico. |
| 24 de febrero de 2021 | [Capacidad de entrega: primeras impresiones: recopilación de direcciones y crecimiento de listas](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/address-collection-and-list-growth.html) | Campaign Classic/Estándar | Conozca cuáles son las mejores fuentes para las nuevas direcciones de correo electrónico, cómo garantizar una alta calidad de los datos y la alineación con las directrices legales. |
| 25 de febrero de 2021 | [Capacidad de entrega: primeras impresiones: correo electrónico de bienvenida](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/welcome-emails.html) | Campaign Classic/Estándar | Aprenda cuáles deben ser los elementos clave de su estrategia de bienvenida. |
| 25 de febrero de 2021 | [Capacidad de entrega - Proceso de transición: Cambiar plataformas de correo electrónico](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/switching-email-platforms.html) | Campaign Classic/Estándar | Aprenda a realizar la transición sin problemas al cambiar de plataforma de correo electrónico. |
| 26 de febrero de 2021 | [Capacidad de entrega: prácticas recomendadas de contenido para una entrega óptima](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/content-best-practices-for-optimal-delivery.html) | Campaign Classic/Estándar | Sugerencias para optimizar el contenido del correo electrónico para la entrega. |
| 26 de febrero de 2021 | [Capacidad de entrega: permanencia del remitente](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/sender-permanence.html) | Campaign Classic/Estándar | Aprenda por qué es importante establecer un volumen de envío coherente. |
| 26 de febrero de 2021 | [Capacidad de entrega: monitorización continua](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/ongoing-monitoring.html) | Campaign Classic/Estándar | Sepa qué problemas debe tener en cuenta al monitorizar los envíos. |
| 26 de febrero de 2021 | [Capacidad de entrega: ponerla en práctica](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/putting-it-in-practice.html) | Campaign Classic/Estándar | Cuatro pilares clave para el éxito. |
| 10 de marzo de 2021 | [Prácticas recomendadas de entrega para líderes, usuarios empresariales y administradores](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.deliverability) | Campaign Classic | Conozca los términos, conceptos y enfoques clave relativos a la entrega para permitirle garantizar el éxito de su programa de marketing. |

### Recursos de ayuda

* Adobe Campaign Standard: [Centro de ayuda](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/campaign-standard-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Vídeos de procedimientos](https://docs.adobe.com/content/help/es-ES/campaign-standard-learn/tutorials/overview.html) - [Planificación de versiones](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/release-notes/release-planning.html) - [Últimas actualizaciones de la documentación](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Centro de ayuda](https://docs.adobe.com/content/help/es-ES/campaign-classic/using/campaign-classic-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) - [Vídeos de procedimientos ](https://docs.adobe.com/content/help/es-ES/campaign-classic-learn/tutorials/overview.html)- [Últimas actualizaciones de la documentación](https://docs.adobe.com/content/help/es-ES/campaign-classic/using/documentation-updates.html)
* Panel de control de Adobe Campaign: [Documentación](https://docs.adobe.com/content/help/es-ES/control-panel/using/control-panel-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/es-ES/control-panel/using/release-notes.html) - Vídeos prácticos para [Campaign Standard](https://docs.adobe.com/content/help/es-ES/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) y [Campaign Classic](https://docs.adobe.com/content/help/es-ES/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Icono](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Notas de la versión de Adobe Advertising Cloud.

* [Nuevas funciones de Advertising Cloud DSP](#adcloud-dsp)
* [Nuevas funciones en Advertising Cloud Search](#adcloud-search)

### Nuevas funciones de la versión [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Última actualización: **28 de octubre de 2020**

| Función | Descripción |
| -----------| ---------- |
| Nuevo Ayuda | (Versión del 28 de octubre) La ayuda anterior se ha sustituido por páginas actualizadas, que están disponibles en el vínculo Ayuda del menú principal de DSP, y también están disponibles en todo momento en [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=es](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=es-ES). |
| Campañas | (Versión del 28 de octubre) Las vistas beta de Campaign anteriores son ahora las vistas de Campaign predeterminadas para obtener perspectivas más rápidas, flujos de trabajo simplificados y vistas personalizadas. |
| Inventario privado | (Versión del 15 de octubre) Ahora todos los usuarios pueden configurar y editar los detalles del ID de la oferta mediante un nuevo formulario de ID de oferta, que es una versión simplificada del formulario heredado de [!UICONTROL servicio de publicidad inteligente]. Para configurar los detalles del nuevo ID de acuerdo, vaya a **[!UICONTROL Inventario > Ofertas]**, haga clic en **[!UICONTROL Crear]** y, a continuación, haga clic en **[!UICONTROL Deal ID Beta]**. |
| Previsión de ubicación | (Versión del 15 de octubre) En el caso de las ubicaciones con un ritmo de nivel de ubicación, la sección [!UICONTROL Previsión] de la configuración de ubicación incluye una nueva sección [!UICONTROL Máximos estimados], que indica cuánta mayor capacidad está disponible con la configuración de segmentación actual. |

### Nuevas funciones de la versión [!DNL Advertising Cloud Search] {#adcloud-search}

Última actualización: **22 de enero de 2021 para la versión del 23 de enero**

| Función | Descripción |
| -----------| ---------- |
| [!UICONTROL Buscar campañas]<br> Informes | Advertising Cloud Search ya no informa de nuevos datos de posición promedio para campañas publicitarias de Microsoft®. La columna Posición promedio muestra los valores de cero (0) para las fechas que comienzan el 23 de enero. Esto se está preparando para el cese de la utilización de los datos de posición promedio por parte de Microsoft en enero de 2021.<br>Los datos de posición promedio recopilados hasta el 22 de enero aún están disponibles en los informes. |

### Tutoriales y cursos de Ad Cloud

Actualizado el **2 de diciembre de 2020**

## ![Icono](/assets/magento.png) [!DNL Magento] {#magento}

Consulte las [notas de la versión](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html) de Magento Commerce y Open Source para obtener la información más reciente.

## ![Icono](/assets/target.png)[!DNL Target] {#target}

Consulte las [[!DNL Target] notas de la versión](https://docs.adobe.com/content/help/es-ES/target/using/release-notes/target-release-notes.html) para obtener la información más reciente sobre la versión.

## ![Icono](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] es una aplicación completa para la gestión de posibles clientes y para los especialistas en marketing B2B que buscan transformar las experiencias de los clientes al interactuar en todas las fases de los recorridos de compra complejos.

### Actualizaciones centrales de Marketo Engage

Consulte las [notas de la versión](https://docs.marketo.com/display/public/DOCS/Release+Notes) de [!DNL Marketo Engage] para obtener la información más reciente sobre la versión.

### Próximas funciones

Las siguientes funciones se lanzarán durante todo el trimestre:

| Función | Descripción |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>Nueva segmentación basada en cuentas</li><li>Almacenamiento de filtros específicos del tablero</li><li>Exportación de tableros Bizible en PDF</li></ul> |
| Conexión de ventas | Actualizaciones y mejoras de la ventana de composición y del centro de comandos |

### Degradaciones

* **Parámetro de API de Asset &quot;_method&quot;:** a partir de septiembre de 2020, los puntos de conexión de Asset API ya no aceptarán “`_method`” para pasar parámetros de consulta en un cuerpo de POST para omitir las limitaciones de longitud de URI.
* **Degradación de compatibilidad con Internet Explorer:** a partir de la versión del 31 de julio de 2020, la interfaz de usuario de Marketo Engage dejará de ser compatible con Internet Explorer.

## ![Icono](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Nuevos vídeos, tutoriales o cursos publicados para Adobe Document Cloud.

| Publicadas | Nombre | Solución | Descripción |
| -----------| ---------- | ---------- | ---------- |
| 25 de febrero de 2021 | [Primeras impresiones: correo electrónico de bienvenida](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/welcome-emails.html) | Vídeo | Aprenda cuáles deben ser los elementos clave de su estrategia de bienvenida. |
| 25 de febrero de 2021 | [Primeras impresiones: recopilación de direcciones y crecimiento de listas](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/address-collection-and-list-growth.html) | Vídeo | Conozca cuáles son las mejores fuentes para las nuevas direcciones de correo electrónico, cómo garantizar una alta calidad de los datos y la alineación con las directrices legales. |

Para obtener ayuda de Document Cloud, consulte:

* [Centro de aprendizaje de Adobe Acrobat](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html)
* [Centro de aprendizaje de Adobe Sign](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html)
* [Aprendizaje y asistencia sobre Document Cloud](https://helpx.adobe.com/es/support/document-cloud.html)

## ![Icono](/assets/creative-cloud-24.png) Creative Cloud Enterprise {#creative-cloud}

Nuevos tutoriales de Creative Cloud Enterprise.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Marzo de 2021 | [Explicación de las licencias de usuario con nombre](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/nameduserlicensing.html) | Artículo | Obtenga información sobre la importancia de las licencias de usuario con nombre. |
| 5 de marzo de 2021 | [Caducidad del número de serie](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/cceserial.html) | Vídeo | Conozca los pasos necesarios para garantizar que los usuarios finales tengan acceso continuo a sus aplicaciones y servicios de Adobe. |
| Marzo de 2021 | [Implementar y administrar aterrizaje: recurso de soporte](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/overview-deploy.html) | Vídeo | Descubra cómo Creative Cloud para empresas admite implementaciones personalizadas y configuraciones de licencias flexibles, y funciona con otras ofertas empresariales de Adobe. |
| 5 de marzo de 2021 | [Personalización de los colores en una ilustración de Adobe Stock Vector](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/customizecolors.html) | Vídeo | Agregue pollillo a cualquier proyecto con una ilustración de aspecto bueno. Busque el vector perfecto en Adobe Stock y, a continuación, combine los colores con la paleta del proyecto mediante Adobe Illustrator. |
| 5 de marzo de 2021 | [Personalice una plantilla de presentación de Adobe Stock para que tenga un aspecto profesional pero llamativo](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/presentationtemplate.html) | Vídeo | Cree una hermosa presentación estilizada en minutos con imágenes y plantillas de Adobe Stock y algunos efectos especiales fáciles de hacer. |
| 5 de marzo de 2021 | [Personalización de una animación de pantalla de carga con Adobe Stock y XD](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/loadingscreen.html) | Vídeo | Personalice las ilustraciones vectoriales de Adobe Stock para crear una animación escalofriante de la pantalla de carga para una aplicación móvil. |
| 5 de marzo de 2021 | [Crear composiciones de fotos realistas con imágenes de Adobe Stock](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/realisticcomposite.html) | Vídeo | Reúne dos buenas fotos de Adobe Stock para atraer gente a sus publicaciones sociales. |
| 5 de marzo de 2021 | [Cree paneles de humor inspiradores en poco tiempo con Adobe Stock](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/moodboard.html) | Vídeo | Cree un tablero de estados de ánimo de proyecto para retransmitir información, ideas, imágenes y paletas de color a equipos o clientes. |
| 5 de marzo de 2021 | [Cree imágenes de marca coherentes con bellos degradados y recursos de Adobe Stock](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/brandgradients.html) | Vídeo | Incluya animación en los gráficos de su newsletter con vectores editables para Adobe Stock. |
| 5 de marzo de 2021 | [Creación de animaciones para correo electrónico con Adobe Stock y Photoshop](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/animationemail.html) | Vídeo | Habilite sus correos electrónicos con Stop-Action Animation con Adobe Stock y Photoshop. |
| 5 de marzo de 2021 | [Cree una foto turística interactiva con Adobe Stock y XD](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/interactivetourismphoto.html) | Vídeo | Cree rápidamente una foto interactiva dentro del prototipo de su sitio web con Adobe Stock &amp; XD. |
