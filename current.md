---
title: Notas de la versión para Experience Cloud y Experience Platform
description: Obtenga información sobre las últimas notas de la versión, las nuevas funciones y la nueva documentación para Experience Cloud y Experience Platform. Encuentre ayuda y tutoriales nuevos sobre Creative Cloud para empresas y Document Cloud.
doc-type: release notes
last-update: February 2021
author: mfrei
translation-type: tm+mt
source-git-commit: c7220fd5298c74ac555ba9d1799194d794b81271
workflow-type: tm+mt
source-wordcount: '6403'
ht-degree: 32%

---


# Notas de la versión de Adobe Experience Cloud: febrero de 2021

![Banner](/assets/experience-cloud-banner-3.png)

Las soluciones y servicios de Experience Cloud se actualizan mensualmente. Esta página es la ubicación central para buscar las últimas actualizaciones de la versión, documentación y tutoriales para [!DNL Experience Cloud] y Experience Platform. También puede encontrar nueva documentación para [!DNL Creative Cloud for Enterprise] y [!DNL Document Cloud].

>[!IMPORTANT]
>
>Esta página contiene contenido de evaluación y está sujeta a cambios antes de las fechas de lanzamiento.

>[!NOTE]
>
>Suscríbase a la [Actualización de producto con prioridad de Adobe](https://www.adobe.com/subscription/priority-product-update.html) mensual para recibir notificaciones por correo electrónico sobre actualizaciones de esta página. Esta página se mantiene a lo largo del mes, por lo que debe consultar regularmente las actualizaciones de los productos empresariales de Adobe y de la documentación de Experience League.

Última actualización: **12 de febrero de 2021**

* [Estado del sistema de Adobe](#status)
* [Administración y servicios de Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [](#analytics) **AnalyticsActualización: 19 de febrero de 2021**
* [Customer Journey Analytics](#cust-journey)`
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

No se ha actualizado este mes.

Consulte [Estado del sistema de Adobe - 21 de mayo de 2020](https://docs.adobe.com/content/help/es-ES/release-notes/experience-cloud/previous/2020/05212020.html#status) para obtener la información más reciente sobre la versión.

## ![Icono](/assets/ec_appicon_24.png) Administración y servicios del Experience Cloud {#ecloud}

La documentación de [Servicios y administración de Experience Cloud](https://docs.adobe.com/content/help/es-ES/core-services/interface/experience-cloud.html) incluye servicios de Activación de Atributos de cliente, Biblioteca de audiencias ([!UICONTROL Personas]), administración de usuarios, y productos y cookies de Experience Cloud.

**4 de febrero de 2021**

* **Actualización de inicio de sesión:** Una actualización al Experience Cloud elimina la pantalla de inicio de sesión del Experience Cloud inicial. A partir del 4 de febrero, se le redirigirá directamente desde `https://experience.adobe.com/login` a la pantalla de inicio de sesión de Adobe.

## ![Icono](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Incluye información sobre la actualización de versión de Experience Platform y Experience Platform Launch.

* [Notas de la versión de Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=es). (27 de enero de 2021)
* [Notas de la versión de Experience Platform Launch](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=es). (13 de enero de 2021)

### Tutoriales y cursos para Experience Platform

Nuevos vídeos, tutoriales o cursos publicados para Experience Platform y sus servicios.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| 10 de febrero de 2021 | [Configuración del destino de blob de Azure](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/configure-the-azure-blob-destination.html?lang=en#destinations) | Vídeo | Conozca cómo seguir los pasos necesarios para configurar y configurar un destino de Almacenamiento de blob de Azure en la plataforma de datos del cliente en tiempo real (CDP en tiempo real). |
| 4 de febrero de 2021 | [Vista de gráficos de identidad](https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/view-identity-graphs.html) | Vídeo | Cómo utilizar la función de visor de gráficos de identidad para buscar, explorar y filtrar gráficos de identidad para la validación y la depuración. |
| 3 de febrero de 2021 | [Introducción a la ingesta de datos por lotes](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/batch-ingestion-overview.html) | Vídeo | Información general sobre la ingestión de datos por lotes en Adobe Experience Platform. Obtenga información sobre cómo ingerir datos por lotes mediante la API. |
| 3 de febrero de 2021 | [Activar datos en aplicaciones que no son de Adobe](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/activate-data-to-non-adobe-applications.html) | Vídeo | Descubra cómo el CDP en tiempo real de Adobe le ayuda a crear estrategias de personalización verdaderas con sus audiencias. Además, descubra cómo se pliega en sus aplicaciones existentes de sistemas ecológicos y no Adobes de Microsoft, Google y Facebook. |
| 21 de enero de 2021 | [Introducción al curso para iniciarse en los servicios inteligentes para especialistas en mercadotecnia](https://video.tv.adobe.com/v/330805?quality=12&learn=on) | Vídeo | Introducción al curso Introducción a los servicios inteligentes para especialistas en marketing. |
| 13 de enero de 2021 | [Introducción a Introducción a Offer decisioning para especialistas en mercadotecnia](https://video.tv.adobe.com/v/330520?quality=12&learn=on) | Vídeo | Introducción al curso Introducción a Offers decisioning para especialistas en marketing. |
| 31 de enero de 2021 | [Entrene, puntee y produzca modelos con la plantilla del generador de fórmulas](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-science-workspace/train-score-and-productize-models.html) | Vídeo | Obtenga información sobre cómo utilizar la plantilla actualizada del creador de fórmulas para crear una fórmula con el esquema de ventas minoristas y los conjuntos de datos. |
| 31 de enero de 2021 | [Carga de datos en portátiles JupyterLab](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-science-workspace/load-data-in-jupyterlab-notebooks.html) | Vídeo | Obtenga información sobre JupyterLab en el área de trabajo de ciencias de datos. |
| 12 de enero de 2021 | [Crear directivas de combinación](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/create-merge-policies.html) | Vídeo | Obtenga información sobre cómo crear políticas de combinación en Adobe Experience Platform. |

## ![Icono](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Utilice Adobe Experience Platform para orquestar el recorrido de un cliente a escala a través de canales de experiencia, anticipando de forma inteligente las necesidades de cada individuo en tiempo real.

### Últimas versiones de productos

Obtenga más información sobre las últimas funciones, mejoras y correcciones en las [Notas de revisión de Journey Orchestration](https://docs.adobe.com/content/help/es-ES/journeys/using/release-notes/release-notes.html).

### Nuevos cursos y tutoriales para Journey Orchestration

Nuevos vídeos, tutoriales y cursos publicados durante el mes pasado.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| 22 de enero de 2021 | [Cambio a otro recorrido](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/building-a-journey/jumping-to-another-journey.html) | Vídeo | Aprenda a mover a las personas de un recorrido a otro. |

### Más recursos para Journey Orchestration

[Documentación](https://docs.adobe.com/content/help/es-ES/journeys/using/journey-orchestration-home.html) - [Notas de la versión](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [Vídeos de presentación](https://docs.adobe.com/content/help/es-ES/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![Icono](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Fecha de publicación: **18 de febrero de 2021**

* [Nuevas funciones en Adobe Analytics](#aa-features)
* [Nuevas funciones en Customer Journey Analytics](#cust-journey)
* [Correcciones en Adobe Analytics](#aa-fixes)
* [Avisos importantes para los administradores de Analytics](#aa-notices) **Actualizado el 19 de febrero de 2021**
* [Cursos y tutoriales sobre Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Funciones nuevas en Adobe Analytics {#aa-features}

| Función | [Disponibilidad general](https://docs.adobe.com/content/help/es-ES/analytics/landing/an-releases.html) - Fecha de destino | Descripción |
| ----------- | ---------- | ------- |
| Analysis Workspace: selección de componentes | 4 de febrero de 2021 | El componente de zona desplegable/zona de colocación que se encuentra en [!UICONTROL Quick Insights] se ha agregado a todas las zonas de colocación de [!UICONTROL Workspace]. Esta mejora le permite elegir de una lista desplegable de componentes compatibles o continuar utilizando el espacio como zona de colocación. |
| Selección de idioma de paneles de Analytics | 14 de enero de 2021 | Vaya a **[!UICONTROL Configuración]** > **[!UICONTROL Preferencias]** > **[!UICONTROL Idioma]** para seleccionar un idioma en el panel de Analytics. |

### Nuevas funciones en Customer Journey Analytics {#cust-journey}

| Función | [Disponibilidad general](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - Fecha de destino | Descripción |
| ----------- | ---------- | ----- |
| Analysis Workspace: selección de componentes | 4 de febrero de 2021 | El componente de zona desplegable/zona de colocación que se encuentra en [!UICONTROL Quick Insights] se ha agregado a todas las zonas de colocación de [!UICONTROL Workspace]. Esta mejora le permite elegir de una lista desplegable de componentes compatibles o continuar utilizando el espacio como zona de colocación. |
| API de CJA | 18 de febrero de 2021 | Las API de CJA ya están disponibles. Estas API permiten editar componentes mediante programación y recuperar informes. Consulte la [documentación de la API de CJA](https://adobe.io/cja-apis/docs) para obtener más información. |

### Correcciones en Adobe Analytics {#aa-fixes}

* Se ha corregido un problema que provocaba un aumento del tiempo de espera de la puerta de enlace de la API de Adobe Analytics 2.0 a 300 segundos (5 minutos). (AN-232335)
* Se han corregido problemas de rendimiento con Workspace, API 2.0 y Adobe Report Builder sistema de informes (AN-245644, AN-244504, AN-243060)
* Se ha corregido un problema que provocaba un error al hacer clic en **Añadir** en Analytics [!UICONTROL Fuente de datos]. (AN-243171)
* Se corrigieron problemas con las clasificaciones que no clasificaban datos. (AN-243823, AN-247049 y AN-244114)
* Se ha corregido un problema con los proyectos programados: los clientes solo podían ver los proyectos que poseían, pero no todos los proyectos programados (AN-246955)
* Se ha corregido un problema con el panel A4T en [!UICONTROL Workspace] que provocaba que los proyectos no se abrieran. (AN-246881)
* Se ha corregido un problema con [!UICONTROL Workspace] que provocaba un error relacionado con A4T [!UICONTROL Métricas calculadas]. (AN-247082)
* Se ha corregido un problema con las solicitudes de API de Data Warehouse que no devolvían datos. (AN-236931)
* Se corrigió un problema en el cual el acceso a un grupo de informes virtuales solo era posible junto con el acceso al grupo de informes principal. (AN-247042)
* Se ha corregido un problema que provocaba un error al convertir proyectos de [!UICONTROL Ad Hoc Analysis] a [!UICONTROL Workspace]. (AN-221215)
* Se ha corregido un problema con el número incorrecto de proyectos filtrados que se mostraban en el [!UICONTROL Administrador de proyectos de Workspace]. (AN-244934)

#### Correcciones adicionales de Adobe Analytics

AN-224987; AN-229009; AN-239750; AN-239765; AN-241620; AN-242996; AN-243577; AN-243774; AN-244509; AN-244746; AN-244763; AN-244868; AN-244960; AN-245016; AN-245097; AN-245727; AN-246141; AN-246283; AN-246340; AN-246532; AN-246669; AN-246744; 246763; AN-246892; AN-246898; AN-246961; AN-247643; AN-247048; AN-247134; AN-247758; AN-247774; AN-248179; AN-248226; AN-248297; AN-248300; AN-248303; AN-248376; AN-248495; AN-248647

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación o actualizada | Descripción |
| ----------- | ---------- | ---------- |
| Opciones de página de aterrizaje de Informes y análisis | 19 de febrero de 2021 | El 25 de marzo de 2021, se eliminarán las opciones para establecer nuevos paneles de Informes y análisis u otro contenido a medida que se elimine su página de aterrizaje de Adobe Analytics. Si anteriormente estableció una página de Informes y análisis como página de aterrizaje personalizada, seguirá funcionando hasta que se modifique la página de aterrizaje en [!UICONTROL Preferencias del usuario]. A partir del 25 de marzo de 2021, ya no podrá definir nuevas páginas de aterrizaje personalizadas de Informes y análisis. |
| EOL de Ad Hoc Analysis | Ene. 2021 | [!UICONTROL Los ] análisis específicos alcanzan su fecha de finalización el 1 de marzo de 2021. Para obtener más información, consulte [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |
| Fin de la vida útil de tres servicios de API de Analytics | 6 de enero de 2021 | El 30 de abril de 2021, los siguientes servicios de la API heredada de Analytics tienen programado alcanzar la fecha de fin de vida útil y se cerrarán. Todas las integraciones actuales creadas con estos servicios dejarán de funcionar ese día.<ul><li>API de Analytics 1.3</li><li>API de Analytics SOAP 1.4</li><li>Autenticación OAuth heredada (OAuth y JWT)</li></ul>Hemos creado [Preguntas frecuentes del fin de la vida útil de la API heredada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para responder a sus preguntas y proporcionar instrucciones sobre cómo proceder. Las integraciones de API que emplean estos servicios pueden migrar a las [API de REST 1.4 de Analytics](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o a las [API de Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Las cuentas heredadas de OAuth pueden migrar a una cuenta de integración de Analytics [Adobe IO](https://console.adobe.io/home?mv=email#), que puede utilizarse para acceder tanto a las API de Analytics 1.4 como a las API de Analytics 2.0. |
| Fin de la vida útil de Data Connectors de Adobe | 13 de julio de 2020 | Los [!UICONTROL Data Connectors de Adobe] utilizan tecnología antigua que ya no es útil ni compatible. Hay disponible un nuevo estándar en el [Programa de Asociados de Negocios de Exchange de Adobe](https://partners.adobe.com/exchangeprogram/experiencecloud). Puede utilizar ese estándar para que cualquier integración siga siendo ofrecida y admitida. La fecha oficial de finalización es el 1 de agosto de 2021. [Más información...](https://docs.adobe.com/content/help/es-ES/analytics/import/dataconnectors/data-connectors-eol.html) |
| Añadir el encabezado HSTS a todas las solicitudes de HTTPS entrantes | 29 de septiembre de 2020 | El 29 de septiembre de 2020, Adobe comenzó a agregar el encabezado HSTS a todas las solicitudes entrantes que utilicen HTTPS. Este encabezado indica al explorador o al cliente que realice todas las solicitudes futuras en HTTPS, lo que se considera una práctica recomendada de seguridad. En este punto, Adobe no aplicará esto a las solicitudes entrantes que utilicen HTTP. |
| Cambio en la configuración de cookies del [!UICONTROL servicio de Experience Cloud ID] | 22 de septiembre de 2020 | Una actualización de la configuración de privacidad de la versión 80 de Chrome afectó la capacidad de Adobe Analytics para rastrear a algunos usuarios que ven páginas AMP de Google. Específicamente, evita el seguimiento entre dominios de los usuarios que ven páginas AMP alojadas en Google. Esto podría causar un aumento en la cantidad de visitantes únicos. Esta corrección permite a los usuarios solucionar este problema cambiando la configuración de sus cookies de ECID.<br>Actualmente, Analytics establece cookies ECID del [!UICONTROL servicio de Experience Cloud ID] con la configuración `SameSite = Lax` que, antes de la versión 80 de Chrome, permitía el seguimiento entre dominios. Ya no es así. Este cambio permite a los usuarios actualizar la configuración SameSite para las cookies ECID a `None`.<br>Este cambio permite compartir la cookie de Analytics en más situaciones, pero las cookies de Analytics no contienen información confidencial. Además, al elegir esta configuración, las cookies deben configurarse en `Secure` para que los datos solo puedan pasarse a través de conexiones HTTPS. Si desea realizar este cambio, un usuario de asistencia técnica puede abrir un ticket con el Servicio de atención al cliente. |

### AppMeasurement {#appm}

Para obtener las últimas actualizaciones de las versiones de AppMeasurement, consulte las [notas de la versión de AppMeasurement para JavaScript](https://docs.adobe.com/content/help/es-ES/analytics/implementation/appmeasurement-updates.html).

### Nuevos cursos y tutoriales de Analytics {#tutorials-analytics}

Nuevos cursos, tutoriales y artículos en [!DNL Analytics] y [!UICONTROL Customer Journey Analytics].

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| 8 de febrero de 2021 | [Añadir líneas de tendencia a visualizaciones de línea](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/adding-trendlines-to-line-visualizations.html?lang=en) | Vídeo | En Configuración de visualización, puede añadir una regresión o mover la línea de tendencia media a la serie de líneas. Esta función ayuda a mostrar un patrón más claro en los datos. |
| 8 de febrero de 2021 | [Añadir complementos de implementación en Platform launch](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/implementation/via-adobe-launch/adding-implementation-plug-ins-in-launch.html?lang=en#implementation) | Vídeo | Los complementos de implementación son fragmentos de código JavaScript que puede agregar a su implementación de Analytics para rastrear datos adicionales personalizados. En este vídeo, aprenda cómo y dónde agregar el código en Platform launch. |
| 6 de enero de 2021 | [Panel de visualizadores simultáneos de medios en Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/media-concurrent-viewers-panel-in-analysis-workspace.html?lang=en#analysis-workspace) | Vídeo | Comprender dónde se produjo el pico de concurrencia o dónde se produjeron los descensos. Obtenga una valiosa perspectiva de la calidad del contenido y la participación del visor, y ayude a solucionar problemas o a planificar el volumen y la escala. |

### Recursos de ayuda de Analytics

* [Tutoriales y documentación del producto Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=es)

## ![Icono](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Nuevas funciones, correcciones, documentación y tutoriales en Audience Manager.

| Función | Fecha de incorporación o actualizada | Descripción |
|----|----|----|
| [Migración de usuarios Audience Manager a Admin Console](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/administration/admin-console-migration.html) | 1 de febrero de 2021 | La administración de cuentas de usuario de Audience Manager se está trasladando al Adobe Admin Console para disfrutar de una experiencia más optimizada en las soluciones de Adobe. <br>Siga los pasos descritos en este artículo para facilitar la migración de usuarios. Todos los administradores de Audience Manager deben realizar el inicio de migrar sus cuentas de usuario a Adobe Admin Console lo antes posible. |

### Correcciones y mejoras {#aam-fixes-and-improvements}

* Se ha corregido un problema en el [Informe de estado de integración](https://experienceleague.adobe.com/docs/audience-manager/user-guide/reporting/onboarding-status-report.html). En este problema, había una discrepancia entre los registros del informe y los del archivo cargados por un socio de integración. (AAM-57415)
* Se ha corregido un problema con la clonación de **[!UICONTROL Modelo]** en la función **[!UICONTROL Audiencias predictivas]**. (AAM-56775)
* Se corrigió un problema con la duplicación de características y segmentos en el cual se duplicaban las características o segmentos incorrectos. (AAM-57351)
* Se corrigió un problema en el cual la casilla de verificación **[!UICONTROL Seleccionar todo]** en **[!UICONTROL Modelos > Excluir características]** no se podía hacer clic para los usuarios. (AAM-57366)
* Se corrigió un problema en **[!UICONTROL Generador de segmentos]** en el cual la casilla de verificación **[!UICONTROL Seleccionar todo]** no seleccionaba todas las características. (AAM-55640)

### Cursos y tutoriales para Audience Manager {#tutorials-aam}

Nuevos vídeos, tutoriales o cursos publicados para Audience Manager.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| 5 de febrero de 2021 | [Pasos para la ingesta de datos basados en archivos](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/integrating-offline-data/steps-for-ingesting-file-based-data.html?lang=en#integrating-offline-data) | Vídeo | Conozca los pasos que debe seguir a medida que incorpore datos sin conexión en Audience Manager, incluidos los requisitos de nombre de archivo para el archivo de datos. |
| 5 de febrero de 2021 | [Formato e ingesta de datos basados en archivos](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/integrating-offline-data/formatting-and-ingesting-file-based-data.html?lang=en#integrating-offline-data) | Vídeo | Al llevar los datos de origen al Audience Manager para comprender mejor y realizar un destinatario de sus clientes, existen ciertos requisitos de formato para los datos. Conozca algunas de las opciones principales y dónde obtener más información. |
| 5 de febrero de 2021 | [Creación de una fuente de datos entre dispositivos y autenticación](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/setup-and-admin/data-sources/creating-a-cross-device-data-source-and-authenticating.html?lang=en#setup-and-admin) | Vídeo | Obtenga información sobre cómo crear una fuente de datos entre dispositivos para almacenar los datos y los ID de CRM al llevar los datos de CRM de origen al Audience Manager. Este vídeo muestra cómo hacerlo y configurar el método `setCustomerIDs()` en Experience Platform Launch para inicios de sesión. |
| 3 de febrero de 2021 | [Introducción al curso - Creación y administración de Activación de datos en Audience Manager](https://video.tv.adobe.com/v/331001) | Vídeo | Los segmentos de audiencia no valen nada a menos que haga algo con ellos. Este curso le enseña a utilizar audiencias para personalizar la experiencia del usuario. Este vídeo de introducción le lleva a empezar en su ruta. |
| 28 de enero de 2021 | [Creación y administración de características](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.3) | Curso | Conozca las características de la creación y organización de características desde el [!UICONTROL Generador de características] del producto a la herramienta [!UICONTROL Administración masiva]. También aprenda a utilizar la herramienta [!UICONTROL Data Explorer] para descubrir señales importantes que llegan al Audience Manager y crear características para ellas. |
| 22 de enero de 2021 | [Uso de informes Audience Optimization para comprender el rendimiento de los medios](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/reports/using-audience-optimization-reports-to-understand-media-performance.html?lang=en#reports) | Vídeo | Conozca cómo utilizar los informes de Audience Optimization para mejorar sus campañas, para saber dónde invertir sus dólares de mercadotecnia y dónde dejar de invertir. También aprenda a determinar el límite de frecuencia óptimo y a encontrar otras joyas en estos informes. |
| 15 de enero de 2021 | [Comprender las Audiencias relacionadas con los informes de superposición](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/reports/understand-related-audiences-with-overlap-reports.html?lang=en#reports) | Vídeo | Los informes de superposición le permiten ver cómo las audiencias de rasgos y segmentos se superponen entre sí (el mismo visitante en varios rasgos o segmentos), para que sepa dónde puede actuar con los datos a fin de aumentar la conversión o centrarse en ampliar el alcance. |
| 12 de enero de 2021 | [Uso de etiquetas de exportación de datos para controlar el flujo de datos](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/data-activation/destinations-basics/using-data-export-labels-to-control-data-flow.html?lang=en#data-activation) | Vídeo | Las etiquetas de exportación de datos le proporcionan un mecanismo en Audience Manager para controlar el flujo de diferentes tipos y fuentes de datos, de modo que pueda satisfacer sus requisitos de privacidad. Conozca cómo y dónde establecer los controles de exportación de datos y las etiquetas de exportación de datos para trabajar en conjunto con este fin. |
| 22 de enero de 2021 | [Importar segmentos de Adobe Analytics en Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/import-aa-segments-into-aam.html?lang=en#build-and-manage-audiences) | Vídeo | Además de reenviar datos en tiempo real de Adobe Analytics a Audience Manager, también puede importar segmentos que incluyan datos posteriores al procesamiento de Analytics a Audience Manager mediante el Experience Cloud. |

## ![Icono](/assets/aem.png) Adobe Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Experience Manager. Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

>[!NOTE]
>
>Adobe recomienda visitar la página [actualizaciones de la versión del Experience Manager y roadmap](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=es) para mantenerse al día con la información de la versión.

### Versiones de productos

* **Experience Manager as a Cloud Service**

   Nuevas funciones en Experience Manager como Cloud Service

   * **Experience Manager Assets as a Cloud Service**

      * **Servicio de Gestor de contenido sin cabeza**

         * [Envío](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/graphql-api-content-fragments.html) de la API de GraphQL para fragmentos de contenido: Capacidad de consulta de fragmentos de contenido mediante la sintaxis de GraphQL y esquemas basados en modelos de fragmentos de contenido para su salida en formato JSON.
         * [Compatibilidad de autenticación para solicitudes](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/graphql-authentication-content-fragments.html) de API de GraphQL: Capacidad para autenticar solicitudes de API de GraphQL con tokenes de acceso para API de servidor.
         * [Componente](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/remote-page.html) RemotePage: Se añadió la compatibilidad con la visualización y edición de SPA externos en AEM uso.
         * [Edición de un SPA externo en AEM](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/editing-external-spa.html): Se ha añadido la capacidad de cargar una aplicación independiente de una sola página en una instancia de AEM, añadir secciones de contenido editables y activar la creación.
         * Salida JSON mejorada de la API de GraphQL, incluida la capacidad de generar texto enriquecido en formato JSON y configuraciones regionales.
         * Compatibilidad con la anidación de modelos de fragmento de contenido para permitir la creación de estructuras de fragmento de contenido anidadas mediante tipos de datos de referencia de fragmento de contenido dedicados o referencias de fragmento de contenido en línea en campos de texto multilínea.
         * Hay más reglas de validación disponibles en los tipos de datos del modelo de fragmento de contenido, incluidos &quot;único&quot;, &quot;obligatorio&quot; y &quot;traducible&quot;.
         * Posibilidad de etiquetar modelos de fragmento de contenido y permitir la creación de fragmentos de contenido en una carpeta con directivas por etiquetas o rutas.
         * Mejoras de uso en el editor de fragmentos de contenido, incluida la acción de publicación y la visualización del modelo en el que se basa un fragmento.
         * Posibilidad de previsualización de salida JSON directamente en el editor de fragmentos de contenido.
      * **Aplicaciones Web progresivas (PWA)**

         * [Una versión de aplicación web progresiva (PWA) de un ](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/features/enable-pwa.html?lang=en) sitecan ahora se habilita en el nivel de proyecto mediante una configuración simple.
   * **Recursos Experience Manager como Cloud Service**

      * Experience Manager como Cloud Service amplía la funcionalidad Etiquetas inteligentes para admitir la identificación de palabras clave y entidades en recursos basados en texto. El texto se identifica, se indexa y se pone a disposición como metadatos para mejorar la experiencia de búsqueda sin necesidad de ninguna configuración. Consulte [Etiquetas inteligentes](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/manage/smart-tags.html).
      * Ahora se admite el formato de archivo MXF. Consulte [formatos de archivo admitidos](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/file-format-support.html#video-formats).
   * **Experience Manager Commerce as a Cloud Service**

      * **Novedades?**

         * Administración de experiencia del producto: Nueva ficha de propiedades &quot;Comercio&quot; para Recursos y Fragmentos de experiencia. Esta ficha le permite vincular productos/categorías a Recursos y Fragmentos de experiencia. La ficha también muestra datos en tiempo real de productos o categorías vinculados y un vínculo para mostrar detalles en la consola de productos.
         * Sitio de referencia de CIF Venia publicado - 2021.02.02 que incluye la versión más reciente de componentes principales de CIF v1.7.0. Consulte [CIF Venia Reference Site](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2021.02.02) para obtener más detalles.
         * Componentes principales de CIF v1.7.0. Consulte [Componentes principales de CIF](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.7.0) para obtener más detalles.
      * **SDK Build Analyzers**

         El Experience Manager como Cloud Service SDK Build Analyzer Maven detecta problemas en un proyecto determinado, incluidas las dependencias que faltan. Ofrece a los desarrolladores la oportunidad de encontrar problemas durante el desarrollo local, mucho antes de implementarlos en Cloud entornos con Cloud Manager.

         Se han agregado dos nuevos analizadores para esta versión:

         * analizador de informes
         * bundle-nativecode

         Para obtener más información, consulte la documentación [aquí](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html#developing).
   * **Herramientas de Transición de nube**

      * **Novedades de la herramienta de transferencia de contenido**

         * Nueva capacidad e interfaz de usuario agregada a la herramienta de transferencia de contenido: herramienta de asignación de usuarios. Esta función asigna automáticamente los usuarios y grupos existentes a sus ID de sistema de Identity Management de Adobe como parte de la actividad de migración de contenido.
Consulte [Uso de la herramienta de asignación de usuarios](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-user-mapping-tool.html).
         * La herramienta de transferencia de contenido ahora migra todos los grupos y usuarios a los que se hace referencia en el conjunto de migración, incluidos los elementos secundarios.
         * Los usuarios pueden seleccionar determinadas rutas en `/etc` al crear conjuntos de migración.







### **Comunidad**

* **Adobe Developers Live 2021 | lista de sesión completa**

   Por solicitud popular, [here](https://adobe.ly/3cldljt) es una lista agregada de todas las sesiones de Experience Manager que se producen en Adobe Developers Live. Toda la grabación y las preguntas y respuestas de cada sesión se publican en sus respectivos subprocesos contextuales.

* **Lista del contenido más reciente de Adobe Experience Manager en Experience League | Enero de 2021**

   La fuente oficial del contenido técnico de la Experiencia Digital producido por el Adobe. Consulte la lista completa [aquí](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/377452#M27156).

### Información de la versión de Experience Manager

Todas las notas de la versión de Experience Manager se mantienen en las páginas siguientes:

* [Actualización de la versión de Experience Manager y del plan de trabajo](https://docs.adobe.com/content/help/es-ES/experience-manager-release-information/aem-release-updates/home.html)
* [Experience Manager como información de versión de Cloud Service](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/release-notes/home.html)
* [Notas de la versión de Experience Manager Cloud Manager](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Notas de la versión del servicio de conversión automatizada de Forms](https://docs.adobe.com/content/help/es-ES/aem-forms-automated-conversion-service/using/release-notes.html)
* [Notas de la versión de Experience Manager 6.5 Service Pack](https://docs.adobe.com/content/help/es-ES/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Notas de la versión de Experience Manager 6.4 Cumulative Fix Pack](https://docs.adobe.com/content/help/es-ES/experience-manager-64/release-notes/cfp-release-notes.html)
* [Experience ManagerAssets Notas de la versión de Dynamic Media](https://docs.adobe.com/content/help/es-ES/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Notas de la versión de Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=es)
* [Notas de la versión de la aplicación de escritorio de Experience Manager](https://docs.adobe.com/content/help/es-ES/experience-manager-desktop-app/using/release-notes.html)
* [Notas de la versión de Experience Manager Dispatcher](https://docs.adobe.com/content/help/es-ES/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Notas de la versión de Livefyre](https://docs.adobe.com/content/help/es-ES/livefyre/using/release-notes/c-rn.html)

### Tutoriales y cursos para Experience Manager

Nuevos vídeos, tutoriales y cursos publicados durante el mes pasado.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| 11 de febrero de 2021 | [Autentificación para AEM como Cloud Service desde una aplicación externa](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.aemcs) | Curso | Obtenga información sobre cómo una aplicación externa puede utilizar [!UICONTROL Tokenes de acceso de desarrollo local] y [!UICONTROL Credenciales de servicio] para autenticarse mediante programación en Experience Manager como Cloud Service sobre HTTP. |
| 11 de febrero de 2021 | [Relacionar y desrelacionar recursos](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/relate-unrelate.html) | Vídeo | Obtenga información sobre cómo establecer y administrar relaciones entre recursos en Experience Manager. |
| 8 de febrero de 2021 | [Tutorial de AEM Sites - WKND](https://docs.adobe.com/content/help/en/experience-manager-learn/getting-started-wknd-tutorial-develop/overview.html) | Tutorial | Bienvenido a un tutorial de varias partes diseñado para desarrolladores nuevos en Experience Manager. Este tutorial explora la implementación de un sitio Experience Manager para un estilo de vida ficticio de la marca WKND. |
| 1 de febrero de 2021 | [Creación de su primer paquete OSGi](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/create-your-first-osgi-bundle.html?lang=en) | Artículo | Obtenga información sobre cómo crear su primer paquete OSGi usando muevos y eclipses. |
| 1 de febrero de 2021 | [Publicar recursos](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/publish.html) | Vídeo | Obtenga información sobre cómo publicar recursos y sus representaciones de Experience Manager Author en AEM Publish. |
| 4 de febrero de 2021 | [Desarrollo local](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/local-development-environment.html) | Vídeo | Obtenga información sobre cómo descargar y configurar un entorno de desarrollo local con el Experience Manager como Cloud Service SDK. |
| 4 de febrero de 2021 | [Estructura del proyecto](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/project-structure.html) | Vídeo | Explore las prácticas recomendadas para estructurar un proyecto Maven Experience Manager para AEM como Cloud Service. |
| 4 de febrero de 2021 | [Migrar configuraciones de Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/dispatcher-configuration.html) | Vídeo | Información general sobre las diferencias en las configuraciones de Dispatcher, y sugerencias y trucos para migrar Dispatcher de Adobe Managed Services (AMS) a Experience Manager como Cloud Service. |
| 2 de febrero de 2021 | [Introducción al SDK de AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/aem-sdk.html) | Vídeo | Uso y configuración del SDK para Experience Manager como Cloud Service. |
| 2 de febrero de 2021 | [¿Qué es AEM Cloud Service?](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/what-is-aem-as-a-cloud-service.html) | Vídeo | Explore qué es el Experience Manager como Cloud Service y en qué se diferencia de otras versiones de Adobe Experience Manager. |
| 2 de febrero de 2021 | [Función del Administrador de nube](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/cloud-manager.html) | Vídeo | Explore el propósito de [!UICONTROL Cloud Manager] y cómo funciona con Experience Manager como Cloud Service. |
| 2 de febrero de 2021 | [Evolución de AEM como Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/evolution.html) | Vídeo | Explore el historial de Experience Manager y las diferencias entre Experience Manager local, AEM de servicios gestionados de Adobe y Experience Manager como Cloud Service. |
| 2 de febrero de 2021 | [Arquitectura de AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/introduction/architecture.html) | Vídeo | Explore la arquitectura subyacente y las piezas importantes de Experience Manager como Cloud Service. Haga un profundo análisis en Cloud Manager y las API. |
| 2 de febrero de 2021 | [Uso de las API de Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/cloud-manager-apis.html) | Vídeo | Explore cómo se pueden usar las API de Cloud Manager para ampliarse e integrarse con otros sistemas. |
| 2 de febrero de 2021 | [Analizar los resultados de la prueba](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/analyze-test-results.html) | Vídeo | Explore los errores de compilación del código y si este código sigue las prácticas recomendadas para Experience Manager como Cloud Service |
| 2 de febrero de 2021 | [Configurar tuberías](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/configure-pipelines.html) | Vídeo | Explore los diferentes tipos de tuberías en Cloud Manager y cómo configurarlas para un proyecto exitoso. |
| 2 de febrero de 2021 | [Administrar configuraciones de despachante](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/dispatcher-configurations.html) | Vídeo | Use prácticas recomendadas y ejemplos para explorar cómo funciona el distribuidor con Experience Manager como Cloud Service y Cloud Manager. |
| 2 de febrero de 2021 | [Integraciones continuas y Administrador de nube](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/continuous-integration.html) | Vídeo | Conozca las prácticas recomendadas y la integración continua mediante Adobe Cloud Manager. |
| 2 de febrero de 2021 | [Combinación de proyectos AEM para la implementación mediante Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/merge-projects.html) | Vídeo | Explore cómo se pueden combinar varios proyectos en un único proyecto para su implementación en Experience Manager como Cloud Service mediante Cloud Manager. |
| 2 de febrero de 2021 | [Implementación de proyectos de Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/devops/deploy-code.html) | Vídeo | Integre el repositorio git del administrador de nube con un repositorio git externo e implemente un proyecto en Experience Manager como Cloud Service. |
| 2 de febrero de 2021 | [Publicación de contenido](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/basics/content-publishing.html) | Vídeo | Explore cómo funciona la publicación de contenido en Experience Manager como Cloud Service, incluidos los conceptos de distribución de contenido y la canalización de Adobes. |
| 2 de febrero de 2021 | [Autenticación basada en tokens - Credenciales de servicio](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/service-credentials.html?lang=en#authentication) | Vídeo | Obtenga información sobre la autenticación basada en tokens para integraciones con Experience Manager como Cloud Service. |
| 2 de febrero de 2021 | [Firmar varios Forms](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/sign-multiple-documents/introduction.html?lang=en#sign-multiple-documents) | Tutorial | Tanto si solicita una hipoteca como si abre una nueva cuenta bancaria, deberá rellenar y firmar varios formularios. La integración entre Forms Experience Manager y Adobe Sign facilita la cumplimentación y firma de varios formularios. |
| 28 de enero de 2021 | [Autenticación basada en tokens: Token de acceso de desarrollo local](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/local-development-access-token.html?lang=en#authentication) | Vídeo | Descubra cómo la consola de desarrolladores de Experience Manager permite a los desarrolladores generar tokenes de acceso temporales que se pueden usar para acceder a Experience Manager mediante programación. |
| 28 de enero de 2021 | [Autenticación basada en tokens para AEM como Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/overview.html?lang=en#authentication) | Vídeo | Descubra cómo una aplicación externa puede autenticarse mediante programación e interactuar con Experience Manager como Cloud Service mediante HTTP mediante tokenes de acceso. |
| 24 de enero de 2021 | [Crear el formulario principal para el déclencheur del proceso](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/sign-multiple-documents/create-initial-form.html) | Artículo | El formulario inicial (formulario de refinanciación) se utiliza para firmar varios formularios activando el flujo de trabajo [!UICONTROL Firmar varios AEM de Forms]. |
| 8 de enero de 2021 | [Ejecución de la canalización de producción de CD/CI de Adobe Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-production-pipeline.html) | Vídeo | La configuración de la tubería de producción CI/CD define el déclencheur que inicia la canalización, los parámetros que controlan la implementación de producción y los parámetros de prueba de rendimiento. |
| 8 de enero de 2021 | [Actividad de Adobe Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/activity.html) | Vídeo | Cloud Manager ofrece una vista consolidada en la actividad de un Programa, enumerando todas las ejecuciones de la canalización de CD/CI, tanto de producción como de no producción. Esta función permite a los usuarios realizar la vista de cualquier oleoducto en curso y revisar implementaciones anteriores. |
| 8 de enero de 2021 | [Canalizaciones de no producción de CD/CI de Adobe Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-non-production-pipeline.html) | Vídeo | Las tuberías de CI/CD que no son de producción se dividen en dos categorías, tuberías de calidad de código y tuberías de implementación. La calidad del código canaliza todo el código de una rama Git para crearlo y evaluarlo con el análisis de calidad del código del Administrador de nube. |
| 8 de enero de 2021 | [Configuración de la canalización de producción de CD/CI de Adobe Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/cicd-production-pipeline.html) | Vídeo | La configuración de la tubería de producción CI/CD define el déclencheur que inicia la canalización, parámetros que controlan la implementación de producción y parámetros de prueba de rendimiento. |
| 8 de enero de 2021 | [Entornos de Adobe Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/environments.html) | Vídeo | Los Entornos de Cloud Manager están compuestos por los servicios de Experience Manager Author, Experience Manager Publish y Dispatcher. Diferentes entornos admiten funciones y pueden participar utilizando diferentes canalizaciones de CD/CI. Los entornos de Cloud Manager suelen tener un entorno de producción, un entorno de fase y un entorno de desarrollo. |
| 8 de enero de 2021 | [Información general de GraphQL sin encabezado](https://internal.adobedemo.com/content/demo-hub/en/demos/internal/aem-headless-graphql.html) | Demostración | Las API de GraphQL de Experience Manager exponen el contenido de los fragmentos de contenido de Experience Manager a las aplicaciones de flujo descendente. Las API de GraphQL se pueden usar en casos de uso híbrido y sin encabezado. |
| 8 de enero de 2021 | [Programas de Adobe Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-manager/programs.html) | Vídeo | Los Programas de Cloud Manager representan conjuntos de entornos de Experience Manager que admiten conjuntos lógicos de iniciativas empresariales, que normalmente corresponden a un acuerdo de nivel de servicio (SLA) adquirido. |
| 8 de enero de 2021 | [Autenticación basada en tokens](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/overview.html?lang=en#authentication) | Vídeo | Los Programas de Cloud Manager representan conjuntos de entornos de Experience Manager que admiten conjuntos lógicos de iniciativas empresariales, que normalmente corresponden a un acuerdo de nivel de servicio (SLA) adquirido. |
| 8 de enero de 2021 | [Importación masiva](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html) | Vídeo | La herramienta Importación masiva en Experience Manager como Cloud Service permite a los administradores importar recursos de forma masiva desde el almacenamiento en la nube (Almacenamiento de blob de Azure o Amazon S3) de forma segura y eficaz. |

### Otros recursos de ayuda para Experience Manager

* [Experience Manager como guía de Cloud Service](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-service/landing/home.html)
* [Página de inicio de aprendizaje y asistencia de Experience Manager 6.5](https://helpx.adobe.com/es/support/experience-manager/6-5.html)
* [Página de inicio de aprendizaje y asistencia de Experience Manager 6.4](https://helpx.adobe.com/es/support/experience-manager/6-4.html)
* [Página de inicio de aprendizaje y asistencia de Experience Manager 6.3](https://helpx.adobe.com/es/support/experience-manager/6-3.html)
* [Página de inicio de aprendizaje y asistencia de Experience Manager 6.2](https://helpx.adobe.com/es/support/experience-manager/6-2.html)
* [Guía del usuario de Cloud Manager](https://docs.adobe.com/content/help/es-ES/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Versiones anteriores de la documentación del Experience Manager](https://helpx.adobe.com/es/experience-manager/aem-previous-versions.html)
* [Inicio de la Ayuda de Dynamic Media Classic](https://docs.adobe.com/content/help/es-ES/dynamic-media-classic/using/home.html)

## ![Icono](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign permite entregar, de forma intuitiva y automatizada, mensajes privados a través de canales de marketing en línea y sin conexión. Ahora puede anticipar los deseos de los clientes mediante experiencias basadas en sus hábitos y preferencias.

### Últimas versiones de productos

Obtenga más información sobre las últimas funciones, mejoras y correcciones publicadas:

* [Notas de la versión de Campaign Standard](https://docs.adobe.com/content/help/es-ES/campaign-standard/using/release-notes/release-notes.html)
* [Notas de la versión de Campaign Classic](https://docs.adobe.com/content/help/es-ES/campaign-classic/using/release-notes/latest-release.html)

### Nuevos cursos y tutoriales de Campaign

Nuevos vídeos, tutoriales y cursos publicados durante el mes pasado.

| Publicadas | Nombre | Solución | Descripción |
| -----------| ---------- | ---------- | ---------- |
| 5 de febrero de 2021 | [Introducción a Adobe Campaign Classic para usuarios empresariales](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.classic) | Campaign Classic | Después de completar este curso, comprenderá los conceptos de Adobe Campaign Classic y sabrá cómo crear su primera campaña de marketing. |
| 1 de febrero de 2021 | [Introducción a los canales múltiples y a los canales cruzados](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/orchestration/introduction-to-cross-and-multi-channel-campaigns.html) | Campaign Classic | Comprender la diferencia entre la campaña de varios canales y de varios canales y cuáles son los casos de uso de campañas de varios canales y de canales cruzados. |
| 1 de febrero de 2021 | [Crear un Envío SMS](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/sms-channel/create-a-sms-delivery.html) | Campaign Classic | Aprenda a crear un envío SMS. |
| 1 de febrero de 2021 | [Crear campañas entre canales](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/orchestration/cross-channel-campaigns.html) | Campaign Classic | Aprenda a crear y ejecutar una campaña entre canales. |
| 29 de enero de 2021 | [Usar Grupos de control](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/use-control-groups.html) | Campaign Classic | Comprender el concepto de grupos de control y aprender a usar un grupo de control para su envío. |
| 28 de enero de 2021 | [Envío y validación de pruebas](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/send-and-validate-proofs.html) | Campaign Classic | Obtenga información sobre cómo enviar y validar una prueba. |
| 28 de enero de 2021 | [Diseñar correos electrónicos para la entrega](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/design-emails-for-deliverability.html) | Campaign Classic | Conozca cómo aplicar las optimizaciones de la entrega. |
| 28 de enero de 2021 | [Crear y diseñar envíos de correo electrónico](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/create-and-design-email-deliveries.html) | Campaign Classic | Conozca el proceso de creación de un envío de correo electrónico y aprenda a diseñar y personalizar el contenido del correo electrónico. |
| 27 de enero de 2021 | [Crear campañas activadas por evento](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/getting-started/create-event-triggered-campaigns.html) | Campaign Classic | Aprenda a crear una campaña desencadenada por eventos y a comprender sus usos. |

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

Última actualización: **23 de febrero de 2021, para la versión del 20 de febrero**

| Función | Descripción |
| -----------| ---------- |
| Todas | Herramientas > &quot;Etiquetas de conversión de adwords&quot; ahora es &quot;Etiquetas de conversión de Google Ads.&quot; |
| Todas | En abril, las siguientes funciones y vistas quedarán en desuso:<br><ul><li>Optimización > Tarjetas de Portfolio</li><li>Optimización > Reglas de oferta</li><li>Perspectivas e informes > Panel</li><li>Campañas:  Compatibilidad pendiente y programada para ediciones masivas</li></ul> |

### Tutoriales y cursos de Advertising Cloud

Actualizado: **23 de febrero de 2021**

| Tutorial | Descripción |
| -----------| ---------- |
| [Introducción a Workspace y Sistema de informes](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-analysis-workspace-a4adc.html) | Descubra cómo puede utilizar los datos de Advertising Cloud para crear informes visuales en Adobe Analytics Analysis Workspace. |

## ![Icono](/assets/magento.png) [!DNL Magento] {#magento}

Consulte Magento Commerce y Open Source [notas de la versión](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html) para obtener la información más reciente sobre la versión.

## ![Icono](/assets/target.png)[!DNL Target] {#target}

Consulte las [[!DNL Target] notas de la versión](https://docs.adobe.com/content/help/es-ES/target/using/release-notes/target-release-notes.html) para obtener la información más reciente sobre la versión.

## ![Icono](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] es una aplicación completa para la administración de posibles clientes y los especialistas en mercadotecnia B2B que buscan transformar las experiencias de los clientes al involucrarse en todas las etapas de recorridos de compra complejos.

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

### Tutoriales de Acrobat

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| 8 de febrero de 2021 | [Aterrizaje de Información general de Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html) | Centro de aprendizaje | Bienvenido a Adobe Acrobat Learning Hub. Encontrará una amplia gama de experiencias de aprendizaje centradas en Adobe Acrobat. Nuestros tutoriales, seminarios web y casos de uso están diseñados para ofrecer rápidamente a los usuarios principiantes y avanzados la máxima velocidad en Adobe Acrobat. |

### Tutoriales de Adobe Sign

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| 8 de febrero de 2021 | [Información general de aterrizaje: recurso de soporte](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html) | Centro de aprendizaje | Bienvenido a Adobe Sign Learning Hub. Encontrará una amplia gama de experiencias de aprendizaje centradas en Adobe Sign. Nuestros tutoriales, seminarios web y casos de uso están diseñados para ofrecer rápidamente a los principiantes y administradores la máxima velocidad en Adobe Sign. |

Para obtener ayuda de Document Cloud, consulte:

* [Centro de aprendizaje de Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=es)
* [Centro de aprendizaje de Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=es)
* [Aprendizaje y asistencia sobre Document Cloud](https://helpx.adobe.com/es/support/document-cloud.html)

## ![](/assets/creative-cloud-24.png) IconoCreative Cloud Enterprise  {#creative-cloud}

Nuevos tutoriales para Creative Cloud Enterprise.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| 3 de febrero de 2021 | [Creación de párrafos con Photoshop](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/cinemagraphps.html?lang=en#cceoverview) | Vídeo | Aprenda a crear una fotografía viva combinando vídeos de Adobe Stock con técnicas inteligentes de enmascaramiento en Photoshop. |
| 3 de febrero de 2021 | [Crear composiciones únicas con Adobe Stock y Photoshop para iPad](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/compositepsipad.html?lang=en) | Vídeo | Aprenda a utilizar una de sus aplicaciones Creative Cloud favoritas de una forma completamente nueva, con una interfaz táctil rediseñada. |
| 3 de febrero de 2021 | [Personalice y marque un modelo 3D con Dimension y Adobe Stock](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/3ddimensionstock.html?lang=en) | Vídeo | Personalice y marque un modelo 3D en Dimension usando materiales, propiedades ambientales, iluminación y fotografía, para crear imágenes fotorealistas para cualquier proyecto de diseño. |
| 2 de febrero de 2021 | [Familiarícese con Componentes en Adobe XD](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/xdoverview/components.html) | Vídeo | Aprenda a utilizar Componentes para ofrecerle una flexibilidad sin precedentes para aplicar velocidad y coherencia al flujo de trabajo de diseño. |
| 2 de febrero de 2021 | [Consejos y técnicas para dominar la iluminación 3D en CGI](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/mastering3dlighting.html?lang=en) | Artículo | Obtenga información sobre la iluminación 3D y cómo crear diferentes condiciones de luz que pueden alterar por completo una escena generada por ordenador y el aspecto que tienen los objetos en ella. |
| 2 de febrero de 2021 | [Creación de fotografía virtual fotorrealista con procesamiento y composición 3D](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/photorealistic.html?lang=en#3doverview) | Artículo | Aprenda a crear fotografía virtual fotorrealista con maquetación y composición 3D. |
| 29 de enero de 2021 | [Guías de referencia rápida de CCE](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/overview-ref.html) | Guías de referencia rápida | Obtenga acceso a guías de referencia rápidas que le ayudarán a aprender las nuevas funciones de Creative Cloud. |
