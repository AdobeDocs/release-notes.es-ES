---
title: Últimas notas de la versión
description: Obtenga información sobre las últimas notas de la versión, las nuevas funciones y la nueva documentación de los productos y servicios de  [!DNL Experience Cloud] . Busque nueva ayuda y tutoriales sobre [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud].
doc-type: release notes
last-update: October 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: bc6e1a293674c9554cb5c4bb18e3e39bb8c38213
workflow-type: tm+mt
source-wordcount: '5537'
ht-degree: 38%

---

# Notas de la versión de Adobe Experience Cloud: Octubre de 2021

![Banner](assets/experience-cloud-banner-3.png)

Las aplicaciones y servicios de [!DNL Experience Cloud] se actualizan mensualmente. Esta página es la ubicación central para buscar las últimas actualizaciones de la versión, documentación y tutoriales para [!DNL Experience Cloud] y [!DNL Experience Platform]. También puede encontrar nueva documentación para [!DNL Creative Cloud for enterprise] y [!DNL Document Cloud].

>[!NOTE]
>
>Suscríbase a la [Actualización de producto con prioridad de Adobe](https://www.adobe.com/subscription/priority-product-update.html) mensual para recibir notificaciones por correo electrónico sobre actualizaciones de esta página. Esta página se mantiene durante todo el mes, por lo que debe consultar regularmente las actualizaciones de la documentación de Experience League y del producto empresarial de Adobe.

Última actualización: **7 de octubre de 2021**

* [[!DNL Experience League] Eventos en directo](#events)
* [[!DNL Experience Cloud Central Interface Components] &amp; Administración](#ecloud)
* [Estado del sistema de [!UICONTROL Adobe]](#status)
* [[!DNL Adobe Analytics]](#analytics) y [Customer Journey Analytics](#cust-journey)  **Actualizado el 7 de octubre de 2021**
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

¿Necesita ayuda? Visite [Adobe Experience League](https://experienceleague.adobe.com/?lang=es#home) para encontrar la documentación técnica y de los productos, cursos seleccionados por Adobe, tutoriales de vídeo, respuestas rápidas, información de la comunidad y formación impartida por instructores.

## ![Icono](/assets/experience-league.png) de [!DNL Experience League] Eventos en directo {#events}

[!DNL Experience League] Los eventos en directo son debates con expertos e invitados especiales de Adobe que son fundamentales para presentar la tecnología de Adobe. Consulte la siguiente programación y únase a nosotros en directo o vea los eventos grabados anteriormente.

| Fecha del evento | Fecha | Nombre del evento | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |---------- |
| 21 de octubre de 2021 | 12.00 horas (EST) | [¿Quién hizo clic en eso? Informes avanzados sobre clics en vínculos con Adobe Analytics](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) | Evento de vídeo en directo | La creación de informes sobre la interacción del usuario con su propiedad web o móvil es una parte fundamental del recorrido de su cliente. Con Adobe Analytics puede comprender el quién, qué, por qué y dónde de cada clic en la aplicación. Conozca a los expertos de Adobe Analytics sus principales sugerencias para usar clasificaciones de Activity Map y atribuciones personalizadas para comprender mejor la participación del usuario. |
| 23 de septiembre de 2021 | On Demand | [Sugerencias de los expertos para que sus campañas de días festivos se destaquen](https://www.youtube.com/watch?v=bsU1lAv0xes) | Evento de vídeo en directo | Al igual que nunca es demasiado pronto para comenzar sus compras de días festivos, tampoco lo es para empezar a planificar una campaña de marketing de días festivos con gran éxito. Con Adobe Campaign, puede diseñar, planificar y ejecutar campañas que hagan realidad todos los deseos de los días festivos de su organización.<br>Pero, ¿conoce todos los consejos para ejecutar campañas que terminen el año con un golpe? Únete a Sandra para una discusión en vivo con tres expertos en Adobe que tienen muchos conocimientos colectivos para hacer justamente eso. |
| 26 de agosto de 2021 | On Demand | [Haga que el siguiente segmento de audiencia sea más inteligente que nunca](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-02.html?lang=es) | Grabación de eventos | El éxito de las buenas campañas de marketing depende de la segmentación precisa de la audiencia. Con el nuevo [!UICONTROL Generador de segmentos] de Adobe Experience Platform, puede generar su siguiente segmento de audiencia utilizando los datos de perfil y el comportamiento del usuario basado en el tiempo en todos los canales. Es la mejor manera de garantizar que sus mensajes lleguen a las personas que más necesitan escucharlos. |
| 29 de julio de 2021 | On Demand | [Mis tres consejos favoritos para la implementación de Adobe Analytics](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-01.html?lang=es) | Grabación de eventos | Lo ha visto en el escenario en Summit. Ha oído que comparte consejos de los expertos en Adobe Insider Tours. Puede que incluso haya tenido la ventaja de trabajar con él en su propia implementación de Adobe Analytics. Eric Matisoff le trae sus tres consejos favoritos de implementación de Adobe Analytics a este exclusivo debate de Experience League en vivo. |

{style=&quot;table-layout:auto&quot;}

Para ver más vídeos, visite [Adobe Experience League Channel](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) en YouTube.

## ![Icono](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] y Administración {#ecloud}

| Función | Descripción |
| ------- | ------- |
| Búsqueda unificada | La búsqueda unificada sigue agregando tipos de objetos al índice de búsqueda. En esta actualización, la búsqueda global ahora busca entre el contenido del Experience League y los siguientes tipos de objetos de Journey Optimizer: <ul><li>Conjuntos de datos</li><li>Destinos</li><li>Consultas</li><li>Esquemas</li><li>Segmentos</li><li>Fuentes</li><li>Ofertas</li><li>Componentes</li><li>Mensajes</li><li>Recorridos</li></ul> |
| Consentimiento de datos de uso del producto | Tras un inicio de sesión inicial, se le pedirá que envíe preferencias sobre cómo puede proporcionar Adobe contenido útil y personalizado, como tutoriales, guías, sugerencias rápidas, recomendaciones, vídeos de aprendizaje y mucho más, en función de los datos de uso del producto del Experience Cloud. Esta solicitud también incluye una actualización de sus preferencias para la recopilación y uso de estos datos en <https://experience.adobe.com/preferences>. |
| Navegación [!UICONTROL Déclencheur] del Experience Cloud | [Los ](https://experienceleague.adobe.com/docs/core-services/interface/services/activation/triggers.html?lang=en) activadores de Experience Cloud están disponibles para la navegación directa desde el conmutador de aplicaciones en el encabezado para los usuarios aprovisionados. |
| **Aviso:** Actualización de navegación planificada por la interfaz | En noviembre de 2021, la función de navegación _[!UICONTROL Ir a Launch / Recopilación de datos]_ se eliminará de <https://experience.adobe.com/implement>. |

{style=&quot;table-layout:auto&quot;}

**Más recursos de ayuda de [!DNL Experience Cloud Central UI Components] y Administración**

* Ayuda de administración para [Componentes de interfaz central](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=es) y administración de usuarios
* Ayuda y notas de la versión de [Places: Servicio de ubicación](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=es)
* Ayuda de [People: Atributos de cliente y biblioteca de audiencias](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)

## ![Icono](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] proporciona información detallada, actualizaciones de estado y notificaciones por correo electrónico sobre los productos de Adobe y las interrupciones y sesiones de mantenimiento de los servicios. Puede comprobar el estado en [status.adobe.com](https://status.adobe.com/es).

(Busque la información de la versión más reciente de [!DNL Adobe System Status] en las notas de la versión del [21 de mayo de 2020](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=es)).

## ![Icono](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Fecha de la versión: **7 de octubre de 2021**

* [Funciones nuevas en Adobe Analytics](#aa-features)
* [Nuevas funciones en Customer Journey Analytics](#cust-journey)    **Actualizado el 7 de octubre de 2021**
* [Correcciones en Adobe Analytics](#aa-fixes)
* [Avisos importantes para los administradores de Analytics](#aa-notices)
* [Cursos y tutoriales de Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Funciones nuevas en Adobe Analytics {#aa-features}

| Función | Descripción | [Disponibilidad general](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=es) - Fecha de destino |
| ----------- | ---------- | ------- |
| Visualizaciones para paneles de Analytics | Analytics [!UICONTROL Tableros] presenta tres nuevas visualizaciones para ofrecer a los ejecutivos y a los responsables de la toma de decisiones una mejor comprensión rápida de sus datos. Los nuevos gráficos de barras [!UICONTROL Doughnut], [!UICONTROL Line] y [!UICONTROL Horizontal] facilitan la visualización de datos para elementos de dimensión individuales, sin tener que abrir una vista de detalles. [Más información](https://experienceleague.adobe.com/docs/analytics/analyze/mobapp/create-scorecard.html?lang=en#apply-visualizations) | 7 de octubre de 2021 |
| [!UICONTROL Tiempo invertido en la reproducción de contenido] | La reproducción de medios de transmisión de Adobe [!UICONTROL Tiempo empleado] proporciona una valiosa perspectiva de la participación del visor y permite a las organizaciones de medios obtener perspectivas más detalladas y detalladas con la participación minuto a minuto del usuario mediante análisis avanzado del tiempo empleado con funciones de partición de día. Puede observar la cantidad de tiempo que pasa viendo las emisiones de contenido en un momento específico. La duración de la reproducción se puede dividir en distintas granularidades, incluidas las nuevas granularidades de 5 minutos, 15 minutos y 30 minutos. [Más información](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=en) | 18 de octubre de 2021 |
| [!UICONTROL Generador de segmentos] rápido | Permite a los usuarios empresariales aplicar rápidamente segmentos básicos en un flujo de trabajo de proyecto simplificado y en línea. No es necesario ir al [!UICONTROL Generador de segmentos]. [Más información](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=en) | 21 de octubre de 2021 |
| Mejoras en la búsqueda en el carril izquierdo de Analysis Workspace | La búsqueda en el carril izquierdo 1) prioriza las coincidencias exactas por encima de las coincidencias generales, además de seguir teniendo en cuenta la actualización y relevancia de los componentes. 2) Resalta los caracteres coincidentes para que los resultados de búsqueda sean más comprensibles. 3) Es más fácil encontrar clasificaciones relacionadas con una dimensión. 4) Por último, admite la búsqueda de comodines (`*`) para encontrar más fácilmente los componentes específicos que necesita. Nota: La búsqueda de comodines aún no funciona en el nivel de elemento de dimensión. | 21 de octubre de 2021 |
| Tema oscuro de Analysis Workspace | El tema oscuro está disponible como opción de visualización. | 21 de octubre de 2021 |

{style=&quot;table-layout:auto&quot;}

### Nuevas funciones en Customer Journey Analytics {#cust-journey}

| Función | Descripción | [Disponibilidad general](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - Fecha de destino |
| ----------- | ---------- | ----- |
| Ventana móvil para la retención de datos [!UICONTROL Connection] | **Nota: Póngase en contacto con el Servicio de atención al cliente o con el administrador de cuentas de Adobe para implementar esta configuración. Todavía no está disponible a través de la interfaz de usuario de CJA.**<p>Le permite definir una configuración de retención de datos de CJA como una ventana móvil en meses (3 meses, 6 meses, etc.), a nivel de [!UICONTROL conexión] (no a un [!UICONTROL conjunto de datos]). La retención de datos se basa en marcas de hora de conjuntos de datos de evento y se aplica solo a conjuntos de datos de evento. No existe ninguna configuración de retención de datos para conjuntos de datos de búsqueda o perfil, ya que no hay marcas de tiempo aplicables. La principal ventaja es que solo almacena o genera informes sobre datos que son aplicables y útiles, y elimina los datos más antiguos que ya no son útiles. Le ayuda a mantenerse por debajo de los límites del contrato y reduce el riesgo de costes adicionales. | 7 de octubre de 2021 |
| asistencia al Report Builder | Report Builder es un complemento [!DNL Excel] de Microsoft® que le permite crear, editar y actualizar fácilmente informes personalizados con datos de Customer Journey Analytics. Con Report Builder y Excel, puede utilizar la sencilla pero flexible IU de arrastrar y soltar para crear fácilmente solicitudes de datos complejas. Con Report Builder para Customer Journey Analytics, puede:<ul><li>Hacer referencia a celdas de hojas de cálculo existentes para obtener el orden de fila, el intervalo de fechas o el filtro perfecto</li><li>Crear fechas personalizadas usando calendario, referencias de celda o matemáticas de fecha</li><li>Diseñe las tablas y visualizaciones con herramientas de formato de Excel conocidas</li><li>Disponible para Excel en macOS, Microsoft 365 para la Web y Microsoft Windows</li></ul>[Más información](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-reportbuilder/report-buider-overview.html#) | 7 de octubre de 2021 |
| Visualizaciones para paneles de Analytics | Analytics [!UICONTROL Tableros] presenta tres nuevas visualizaciones para que los ejecutivos y los responsables de la toma de decisiones puedan comprender mejor sus datos a simple vista. Los nuevos gráficos de anillos, líneas y barras horizontales facilitan la visualización de datos para elementos de dimensión individuales, sin tener que abrir una vista de detalles. [Más información](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dashboards/create-scorecard.html?lang=en#apply-visualizations) | 7 de octubre de 2021 |
| API de registros de auditoría del Customer Journey Analytics | El extremo de la API [Audit Log](https://adobe.io/cja-apis/docs/endpoints/auditlogs/) permite solicitar datos de registro de auditoría desde el Adobe. Es una parte importante del cumplimiento de la seguridad y para auditar datos o acciones del usuario. | 7 de octubre de 2021 |
| [!UICONTROL Generador de filtros] rápido | Permite a los usuarios empresariales aplicar rápidamente segmentos básicos en un flujo de trabajo de proyecto simplificado y en línea. No es necesario ir al [!UICONTROL Generador de filtros]. [Más información](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html?lang=en) | 21 de octubre de 2021 |
| Mejoras en la búsqueda en el carril izquierdo de Analysis Workspace | La búsqueda en el carril izquierdo 1) prioriza las coincidencias exactas por encima de las coincidencias generales, además de seguir teniendo en cuenta la actualización y relevancia de los componentes. 2) Resalta los caracteres coincidentes para que los resultados de búsqueda sean más comprensibles. 3) Es más fácil encontrar clasificaciones relacionadas con una dimensión. 4) Por último, admite la búsqueda de comodines (`*`) para encontrar más fácilmente los componentes específicos que necesita. Nota: La búsqueda de comodines aún no funciona en el nivel de elemento de dimensión. | 21 de octubre de 2021 |
| Tema oscuro de Analysis Workspace | El tema oscuro está disponible como opción de visualización. | 21 de octubre de 2021 |

{style=&quot;table-layout:auto&quot;}

### Correcciones en Adobe Analytics y CJA {#aa-fixes}

* Se ha corregido un error de informe programado en Customer Journey Analytics. (AN-271721)
* Se han corregido problemas con [!UICONTROL Buscar componentes] en [!UICONTROL Workspace] que no producían coincidencias exactas. (AN-253937; AN-271707)

#### Correcciones adicionales en Adobe Analytics

AN-256136; AN-265420; AN-268455; AN-269768; AN-270276; AN-270287; AN-271601; AN-271969; AN-272056; AN-272111; AN-272457

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación o actualizada | Descripción |
| ----------- | ---------- | ---------- |
| Fin de la vida útil de tres servicios de API de Analytics | 16 de septiembre de 2021 | El **20 de octubre de 2021**, los siguientes servicios de API heredadas de Analytics alcanzan su fecha de finalización y se cierran. Todas las integraciones actuales creadas con estos servicios dejaron de funcionar ese día.<ul><li>API de Analytics 1.3</li><li>API de Analytics SOAP 1.4</li><li>Autenticación OAuth heredada (OAuth y JWT)</li></ul>Adobe pone a su disposición [Preguntas frecuentes del fin de la vida útil de la API heredada](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) para responder a sus preguntas y proporcionar instrucciones sobre cómo proceder. Las integraciones de API que emplean estos servicios pueden migrar a las [API de REST 1.4 de Analytics](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) o a las [API de Analytics 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Las cuentas heredadas de OAuth pueden migrar a una cuenta de integración de Analytics [Adobe I/O](https://developer.adobe.com/console), que puede utilizarse para acceder tanto a las API de Analytics 1.4 como a las API de Analytics 2.0. |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

Para obtener las últimas actualizaciones de las versiones de AppMeasurement (2.22.2), consulte las [notas de la versión de AppMeasurement para JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=es).

### Cursos y tutoriales de Analytics {#tutorials-analytics}

Últimos cursos, tutoriales y artículos en [!DNL Analytics] y [!UICONTROL Customer Journey Analytics].

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Octubre de 2021 | [Uso de visualizaciones para contar sus historias de datos](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations) | Curso | ¿Quién quiere analizar la tabla tras la tabla solo para intentar extraer perspectivas de los datos? ¡No tú! En este curso, aprenda los conceptos básicos sobre las visualizaciones, incluido cómo agregarlas a un proyecto, introducir datos en ellas y lo que cada visualización puede mostrarle. Obtenga información sobre cómo configurar las opciones para obtener los datos exactos que necesita. Además, obtenga algunos consejos y casos de uso para ayudarle a hacer que las visualizaciones sean prácticas para su análisis normal. |

{style=&quot;table-layout:auto&quot;}

### Recursos de ayuda de Analytics

* [Tutoriales y documentación del producto Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=es)

## ![Icono](/assets/audience-manager.png) Audience Manager {#aam}

Nuevas funciones de Audience Manager: actualizadas el **14 de septiembre de 2021**.

| Función | Descripción |
| ------- | ------- |
| Consentimiento de recopilación de datos de ID de móviles | Se ha agregado compatibilidad con el consentimiento de recopilación de datos de ID de móviles Para beneficiarse de esta actualización, los clientes deben actualizar a [AEP Mobile SDK iOS Core 2.8.0](https://aep-sdks.gitbook.io/docs/foundation-extensions/mobile-core/mobile-core-release-notes#november-4-2020) o posterior. |

## ![Icono](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Incluye información sobre la actualización de la versión y nueva documentación para el Experience Platform y [!UICONTROL Mobile SDK].

**29 de septiembre de 2021**

| Función | Descripción |
| ------- | ------- |
| [[!UICONTROL Zona de aterrizaje de datos]](https://experienceleague.adobe.com/docs/experience-platform/sources/connectors/cloud-storage/data-landing-zone.html) | [!UICONTROL La ] zona de aterrizaje de datos es un  [!DNL Platform]almacén  [!UICONTROL Azure Blob ] aprovisionado que permite un almacenamiento seguro y temporal por simulador de pruebas para introducir archivos en el Experience Platform. |
| Compatibilidad de fuentes de transmisión para [preparación de datos](https://www.adobe.com/go/monitor-streaming-dataflows-en) | Las fuentes de transmisión ahora admiten la preparación de datos, lo que le permite proporcionar un esquema de origen JSON para asignar datos de origen no compatibles con XDM a un esquema XDM de destino. |
| [Credenciales que no caducan](https://experienceleague.adobe.com/docs/experience-platform/query/ui/credentials.html) | Las credenciales no caducadas para los usuarios de [!UICONTROL Query Service] permiten conexiones más permanentes con clientes externos en lugar de renovar las credenciales cada 24 horas. |
| [[!UICONTROL SDK de destino]](https://www.adobe.com/go/destination-sdk-overview-en) | Utilice [!UICONTROL Destination SDK] para integrarse con [!DNL Platform] y contribuir al catálogo de destinos en constante crecimiento. El acceso a esta función solo está disponible para los clientes de Activación de Experience Platform. |

Consulte las [Notas de la versión de Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=es) para todos los detalles.

### Tutoriales y cursos de Experience Platform {#tutorials-platform}

Últimos vídeos, tutoriales o cursos publicados para Experience Platform y servicios.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Octubre de 2021 | [[!DNL Platform] Administración](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin) | Curso | Obtenga información sobre las actividades de administración para Experience Platform, incluida la administración de permisos y entornos limitados. |

{style=&quot;table-layout:auto&quot;}

### SDK de Adobe Mobile

Consulte [Notas de la versión y registros de cambios](https://aep-sdks.gitbook.io/docs/release-notes) para conocer los SDK de Adobe Experience Platform Mobile.

## ![Icono](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

Descubra las funcionalidades, mejoras y correcciones más recientes en las [Notas de la versión de Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=es).

### Tutoriales y cursos de Journey Optimizer {#tutorials-ajo}

Últimos tutoriales de Journey Optimizer:

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Octubre de 2021 | [Configuración y administración de información  [!DNL Journey Optimizer] de datos para ingenieros de datos](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2) | Curso | Obtenga información sobre cómo configurar y administrar los datos necesarios para la administración de recorridos en Journey Optimizer. |
| Octubre de 2021 | [Introducción  [!DNL Journey Optimizer] a Administradores y administradores de Recorrido](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1) | Curso | Aprenda todo lo que necesita saber para crear su primer recorrido. |
| Octubre de 2021 | [ [!DNL Journey Optimizer] Configuración para administradores de Recorrido](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1) | Curso | Comprenda la arquitectura [!DNL Journey Optimizer] y los puntos de integración. Aprenda a configurar [!DNL Journey Optimizer]. |

{style=&quot;table-layout:auto&quot;}

### Más recursos para [!DNL Journey Optimizer]

[Centro de ayuda](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=es)

## ![Icono](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

Utilice Experience Platform para orquestar el recorrido de un cliente a escala a través de canales de experiencia, anticipando de forma inteligente las necesidades de cada individuo en tiempo real.

### Últimas [!DNL Journey Orchestration] versiones del producto

Descubra las funcionalidades, mejoras y correcciones más recientes en las [[!DNL Journey Orchestration] Notas de la versión de ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=es).

#### Más recursos para [!DNL Journey Orchestration]

[Centro de ayuda](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Vídeos de procedimientos](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=es) - [Últimas actualizaciones de la documentación](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=es)

## ![Icono](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer ] Decisioninges un servicio integrado con Adobe Experience Platform. Utilice [!UICONTROL Offer decisioning] para ofrecer la mejor oferta y experiencia a sus clientes en todos los puntos de contacto y en el momento adecuado.

### Últimas versiones del producto de Offer decisioning

Obtenga más información sobre las últimas funciones, mejoras y correcciones en las [Notas de la versión del Offer decisioning](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html).

#### Más recursos para [!UICONTROL Offer decisioning]

[Centro de ayuda](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Vídeos de procedimientos](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=es) - [Últimas actualizaciones de la documentación](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

## ![Icono](/assets/aem.png) Experience Manager {#aem}

Adobe recomienda visitar la página [Actualizaciones de versión y hoja de ruta de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=es) para mantenerse al día respecto a la información de la versión.

### Comunidad

* [Desarrolladores de Adobe en vivo](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)  | 4-5 de octubre de 2021, 7:00 PDT

   Adobe Developers Live reúne a desarrolladores de Adobe y creadores de experiencias con diversos orígenes y un propósito singular para crear experiencias integrales increíbles. Esta conferencia de dos días incluye importantes actualizaciones para desarrolladores, sesiones técnicas y oportunidades de trabajo en red de la comunidad.

   Los equipos de producto de Adobe de Adobe Experience Cloud, Document Cloud y Creative Cloud muestran los últimos avances tecnológicos y herramientas para desarrolladores que permiten el diseño, los flujos de trabajo de creación de contenido, los servicios de documentos y la administración de experiencias de clientes en todas las industrias.

   El Adobe tiene planeadas 20 sesiones de Experience Manager. ¡Difundan la palabra!

   * [Lista de sesiones completa](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041#M120517)
   * [Registro gratuito: inicie sesión en RSVP](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [Comunidad en directo de desarrolladores de Adobe](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-october-4-5/td-p/422127)

### Nuevos cursos y tutoriales para Experience Manager {#tutorials-aem}

Nuevos vídeos, tutoriales y cursos publicados durante el mes pasado.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Octubre de 2021 | [Introducción a la documentación XML](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.xmldocs) | Curso | Obtenga información sobre cómo crear, organizar, crear y publicar contenido con la documentación XML para Adobe Experience Manager. |
| Octubre de 2021 | [Administración de flujos de trabajo creativos  [!DNL Workfront] mediante y Assets Essentials](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.2.assets.essentials) | Curso | Descubra cómo Adobe [!DNL Workfront] y Experience Manager. |
| Octubre de 2021 | [Introducción a AEM Assets Essentials](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.assets.essentials) | Curso | Descubra cómo AEM Assets Essentials puede optimizar la administración de recursos para su organización. |
| Octubre de 2021 | [[!UICONTROL Herramienta de transferencia de contenido]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/content-transfer-tool.html?lang=en) | Vídeo | Descubra cómo [!UICONTROL Content Transfer Tool] le ayuda a migrar contenido a AEM as a Cloud Service desde AEM 6.3+. |
| Octubre de 2021 | [[!UICONTROL Servicio de importación masiva]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/bulk-import-service.html?lang=en) | Vídeo | Descubra cómo se puede utilizar AEM as a Cloud Services [!UICONTROL Bulk Import Service] para importar recursos de fuentes no AEM. |
| Octubre de 2021 | [Comunicaciones (servicio de salida)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/communications.html?lang=en) | Vídeo | Descubra cómo AEM Forms as a Cloud Service admite el caso de uso de comunicación. |
| Octubre de 2021 | [Inscripción digital](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/digital-enrollment.html?lang=en) | Vídeo | Obtenga información sobre cómo AEM Forms as a Cloud Service admite el caso de uso de inscripción digital. |
| Octubre de 2021 | [Uso de herramientas de  [!UICONTROL Cloud Acceleration ] Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/using.html) | Vídeo | Una explicación detallada del uso de las herramientas [!UICONTROL Cloud Acceleration Manager]. |
| Octubre de 2021 | [Navegación por el Administrador de aceleración de  [!UICONTROL Cloud]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/navigating.html) | Vídeo | Explore la experiencia de navegación de [!UICONTROL Cloud Acceleration Manager] para obtener información as a Cloud Service para el Experience Manager. |
| Octubre de 2021 | [Herramienta de Migración del flujo de trabajo de recursos](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/asset-workflow-migration-tool.html) | Vídeo | Descubra cómo la herramienta [!UICONTROL Asset Workflow Migration] ayuda a migrar los flujos de trabajo de AEM Assets existentes a AEM as a Cloud Service. |
| Octubre de 2021 | [[!UICONTROL Conversor de índices]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/index-converter.html) | Vídeo | Descubra cómo el [!UICONTROL Conversor de índices] convierte automáticamente las definiciones de índices de AEM existentes para que sean compatibles con AEM as a Cloud Service. |
| Octubre de 2021 | [[!UICONTROL Dispatcher Converter]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/dispatcher-converter.html) | Vídeo | Descubra cómo el [!UICONTROL Dispatcher Converter] actualiza automáticamente las configuraciones existentes de AEM Dispatcher para que sean compatibles con AEM as a Cloud Service. |
| Octubre de 2021 | [[!UICONTROL Modernizador del repositorio de código]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-repository-modernizer.html) | Vídeo | Descubra cómo el [!UICONTROL Modernizador del repositorio principal] actualiza automáticamente los proyectos existentes de AEM Maven para que sean compatibles con AEM as a Cloud Service. |
| Octubre de 2021 | [[!UICONTROL Herramientas de refactorización de código]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-refactoring-tools.html) | Vídeo | Descubra cómo las [!UICONTROL Herramientas de refactorización de código] de AEM ayudan a automatizar la conversión de proyectos de AEM existentes para que sean compatibles con AEM as a Cloud Service. |
| Octubre de 2021 | [[!UICONTROL Herramienta de transferencia de contenido]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/content-transfer-tool.html) | Vídeo | Descubra cómo la [!UICONTROL herramienta de transferencia de contenido] le permite mover contenido de forma eficaz de AEM 6.5 a AEM as a Cloud Service. |
| Octubre de 2021 | [Fases de implementación de  [!UICONTROL Cloud Acceleration Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/implementation-phase.html) | Vídeo | Revise y comprenda las principales fases de implementación o vaya a AEM as a Cloud Service mediante [!UICONTROL Cloud Acceleration Manager]. |
| Octubre de 2021 | [Analizador de prácticas  [!UICONTROL recomendadas y preparación]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/readiness-and-best-practice-analyzer.html) | Vídeo | Descubra cómo [!UICONTROL Best Practice Analyzer] puede ayudarle a prepararse para pasar de AEM on-premim o Adobe Managed Services a Experience Manager as a Cloud Service. |
| Octubre de 2021 | [Introducción a Cloud Acceleration Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/introduction.html) | Vídeo | Descubra cómo [!UICONTROL Cloud Acceleration Manager] puede ayudarle a pasar rápida y fácilmente al Experience Manager as a Cloud Service. |
| Octubre de 2021 | [AEM Forms as a Cloud Service: paso a AEM CS](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/introduction.html?lang=en) | Vídeo | Obtenga información sobre los casos de uso y las funciones compatibles con AEM Forms as a Cloud Service. |
| Octubre de 2021 | [Solución de problemas AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/troubleshooting.html?lang=en) | Vídeo | Obtenga información sobre cómo solucionar problemas y depurar el SDK de AEM, AEM as a Cloud Service y, el proceso de compilación e implementación. |
| Octubre de 2021 | [AEM  [!UICONTROL microservicios de recursos] : migración a AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/asset-compute-microservices.html?lang=en) | Vídeo | Descubra cómo los microservicios de asset compute de AEM Assets as a Cloud Service le permiten generar de forma automática y eficaz cualquier representación para sus recursos, sustituyendo esta función del flujo de trabajo AEM tradicional. |
| Octubre de 2021 | [Búsqueda e indexación](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/search-and-indexing.html?lang=en) | Vídeo | Obtenga información sobre los índices de búsqueda as a Cloud Service AEM, cómo convertir AEM 6 definiciones de índice para que sean compatibles con AEM as a Cloud Service y cómo implementar índices para AEM as a Cloud Service. |
| Octubre de 2021 | [[!UICONTROL Dispatcher]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/dispatcher.html?lang=en) | Vídeo | Obtenga información sobre AEM [!UICONTROL Dispatcher] para AEM as a Cloud Service, centrándose en los cambios más importantes de [!UICONTROL Dispatcher] para AEM 6, la herramienta de conversión [!UICONTROL Dispatcher] y cómo utilizar el SDK de herramientas de Dispatcher. |
| Octubre de 2021 | [[!UICONTROL Cloud Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/cloud-manager.html?lang=en) | Vídeo | Obtenga información sobre Cloud Manager para AEM as a Cloud Service y sus diferencias con Cloud Manager para AEM en los servicios de administración de Adobe (AMS). |
| Octubre de 2021 | [Introducción a AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/onboarding.html?lang=en) | Vídeo | Obtenga información sobre la incorporación a AEM as a Cloud Service desde la fase de contrato hasta la configuración de entornos mediante [!UICONTROL Cloud Manager]. |
| Octubre de 2021 | [Modernización del repositorio](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/repository-modernization.html?lang=en) | Vídeo | Obtenga información sobre la modernización del repositorio, el contenido mutable e inmutable, la estructura del paquete y la herramienta CLI del modernizador del repositorio. |
| Octubre de 2021 | [[!UICONTROL Herramientas de modernización de AEM]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-modernization-tools.html?lang=en) | Vídeo | Conozca cómo se utilizan AEM [!UICONTROL Herramientas de modernización] para actualizar un proyecto y contenido de AEM existentes para que sean compatibles con AEM as a Cloud Service. |
| Octubre de 2021 | [Herramientas de modernización de AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/introduction.html?lang=en) | Vídeo | Aprenda a pensar de forma diferente en AEM implementaciones as a Cloud Service. |
| Octubre de 2021 | [Analizador de prácticas recomendadas y Cloud Acceleration Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/bpa-and-cam.html?lang=en) | Vídeo | Descubra cómo Best Practice Analyzer (BPA) y Cloud Acceleration Manager (CAM) proporcionan una guía personalizada para migrar a AEM as a Cloud Service. |
| Octubre de 2021 | [Mantenimiento del historial de versiones](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/versions.html) | Vídeo | Descubra cómo Adobe Workfront y el Experience Manager [!UICONTROL Assets Essentials] le ayudan a mantener versiones de documentos [!DNL Workfront] y recursos de Assets Essentials. |
| Octubre de 2021 | [Envío de documentos y vinculación de recursos](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/link-send.html?lang=en) | Vídeo | Obtenga información sobre cómo enviar documentos de Workfront a Assets Essentials y vincular recursos de Assets Essentials a Workfront. |
| Octubre de 2021 | [Configuración de la integración](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html?lang=en) | Vídeo | Obtenga información sobre cómo configurar la integración de Adobe Workfront y Assets Essentials. |
| Octubre de 2021 | [¿Qué es una firma digital?](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | Vídeo | Obtenga información sobre las firmas digitales basadas en certificados, que cumplen con las normas legales más estrictas del mundo y proporcionan el máximo nivel de seguridad de la identidad de un firmante. |
| Octubre de 2021 | [Generador de segmentos en Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-builder-overview.html?lang=en#) | Vídeo | Corte y fragmente sus datos con segmentación en Adobe Analytics. Este vídeo le guía por el [!UICONTROL Generador de segmentos] y le ofrece una descripción general básica. |
| Octubre de 2021 | [Asignación de metadatos](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html?lang=en) | Vídeo | Obtenga información sobre cómo configurar la asignación de metadatos entre los campos de Workfront y las propiedades de Assets Essentials, y configurar Assets Essentials para que muestre los valores asignados. |

{style=&quot;table-layout:auto&quot;}

### Información de la versión de Experience Manager {#aem-links}

Las notas de la versión y otros vínculos de información de la versión para Experience Manager están aquí:

* [[!DNL Experience Manager as a Cloud Service]  Notas de la versión](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?lang=es)
* [[!DNL Experience Manager as a Cloud Service] Información de la versión](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=es)
* [[!DNL Experience Manager Cloud Manager]  Notas de la versión](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=es)
* [Notas de la versión del servicio de conversión automatizada de formularios](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=es)
* [Notas de la versión de Experience Manager 6.5 Service Pack](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=es)
* [Notas de la versión de Experience Manager 6.4 Cumulative Fix Pack](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=es)
* [[!DNL Experience Manager Assets Dynamic Media]  Notas de la versión](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=es)
* [[!DNL Experience Manager Brand Portal]  Notas de la versión](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=es)
* [Notas de la versión de la aplicación de escritorio de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=es)
* [[!DNL Experience Manager Dispatcher]  Notas de la versión](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=es)
* [Notas de la versión de Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=es)
* [Notas de la versión de Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=es)

### Otros recursos de ayuda para Experience Manager

* [[!DNL Experience Manager as a Cloud Service] Guías](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=es)
* [Formación y asistencia de Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=es)
* [Formación y asistencia de Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=es)
* [Formación y asistencia de Experience Manager 6.3](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=es)
* [Formación y asistencia de Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=es#previous-updates)
* [Versiones anteriores de la documentación de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [[!DNL Cloud Manager] Guía de usuario](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=es)
* [[!DNL Dynamic Media Classic] Página inicial de Ayuda](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=es)
* [Documentación de Experience Manager: actualizaciones recientes](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=es#aem-as-a-cloud-service)

## ![Icono](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign permite entregar, de forma intuitiva y automatizada, mensajes privados a través de canales de marketing en línea y sin conexión. Ahora puede anticipar los deseos de los clientes mediante experiencias basadas en sus hábitos y preferencias.

### Últimas versiones de productos de Campaign

Conozca las últimas funciones, mejoras y correcciones publicadas:

* [Notas de la versión v8 de Campaign](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=es)
* [Notas de la versión de Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=es)
* [Notas de la versión de Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=es)

### Nuevos cursos y tutoriales de [!UICONTROL Campaign] {#tutorials-campaign}

Últimos tutoriales y cursos para Adobe Campaign.

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Octubre de 2021 | [Creación de campañas avanzadas con Adobe Campaign V8 para usuarios empresariales](https://experienceleague.adobe.com/?recommended=Campaign-U-1.2021.1.v8) | Curso | Obtenga información sobre cómo configurar y ejecutar campañas de marketing avanzadas mediante Adobe Campaign V8. Obtenga información sobre los requisitos previos, cree y configure campañas avanzadas, envíos y administre suscripciones. |
| Octubre de 2021 | [Uso de API SOAP en flujos de trabajo - Introducción](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=en) | Tutorial | Obtenga información sobre cómo utilizar la API de Adobe Campaign Soap y cree un flujo de trabajo de envío avanzado basado en los datos recibidos mediante la API. |
| Octubre de 2021 | [Crear eventos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/create-events.html?lang=en) | Tutorial | Obtenga información sobre cómo configurar un evento, especifique el extremo de flujo continuo y la carga útil para un evento. |
| Octubre de 2021 | [Configuración de fuentes de datos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/configure-data-sources.html?lang=en) | Tutorial | Comprenda qué es una fuente de datos y aprenda a configurar fuentes de datos externas y de Experience Platform. |
| Octubre de 2021 | [Caso de uso: mensajes de fragmentación](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/use-case-burst-message.html?lang=en) | Tutorial | Comprenda los casos de uso aplicables para la mensajería de ráfaga. Obtenga información sobre cómo configurar un recorrido para los mensajes de ráfaga y las prácticas recomendadas que se deben aplicar. |

{style=&quot;table-layout:auto&quot;}

### Recursos de ayuda de Campaign

* Adobe Campaign v8: [Centro de ayuda](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=es) - [Guías de implementación](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=es)
* Adobe Campaign Standard: [Documentación de Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Vídeos de procedimientos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=es) - [Planificación de versiones](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=es) - [Últimas actualizaciones de la documentación](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=es)
* Adobe Campaign Classic: [documentación de Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Vídeos de procedimientos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=es) - [Actualizaciones más recientes de la documentación](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=es)
* Panel de control de Adobe Campaign: [Documentación](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=es) - [Notas de la versión](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=es) - Vídeos prácticos para [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=es) y [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=es)

## ![Icono](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Notas de la versión para [!DNL Adobe Advertising Cloud].

* [Nuevas funciones en  [!DNL Advertising Cloud DSP]](#adcloud-dsp)
* [Nuevas funciones en  [!DNL Advertising Cloud Search]](#adcloud-search)

### Nuevas funciones en [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Última actualización: **28 de septiembre de 2021**

| Función | Descripción |
| ------- | ----------- |
| Vistas de administración de campañas | Ahora hay disponible una columna &quot;[!UICONTROL Creation date]&quot; en conjuntos de columnas personalizados para las vistas [!UICONTROL Campaigns], [!UICONTROL Packages], [!UICONTROL Placements] y [!UICONTROL Ads]. También puede filtrar las vistas [!UICONTROL Ubicaciones] y [!UICONTROL Publicidades] por [!UICONTROL Fecha de creación]. |
| Ofertas garantizadas mediante programación | (Versión del 8 de septiembre) Ahora puede editar la [!UICONTROL Oferta máxima] para la ubicación predeterminada de una oferta garantizada mediante programación (PG). Sin embargo, como las ofertas PG siempre tienen un CPM fijo, solo los clientes internacionales deben editar la [!UICONTROL Oferta máxima] para tener en cuenta las tarifas de cambio de moneda. |
|  | (Versión del 8 de septiembre) Los usuarios con el permiso &quot;[!DNL FreeWheel Programmatic Guaranteed]&quot; ahora pueden enviar una publicidad a [!DNL FreeWheel Programmatic Creative API] desde la vista [!UICONTROL Anuncios] o la vista [!UICONTROL Colocaciones]. Aún puede enviar una publicidad desde la vista [!UICONTROL Ofertas]. |

{style=&quot;table-layout:auto&quot;}

### Nuevas funciones en [!DNL Advertising Cloud Search] {#adcloud-search}

Última actualización: **28 de septiembre de 2021**

| Función | Descripción |
| ------- | ----------- |
| Información sobre los anuncios | Hay perspectivas adicionales disponibles en el modo beta. |

{style=&quot;table-layout:auto&quot;}

## ![Icono](/assets/magento.png) [!DNL Commerce] (Magento) {#magento}

Consulte los siguientes vínculos para ver las notas de la versión de Adobe Commerce:

* [Adobe Commerce y Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite para Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![Icono](/assets/target.png) [!DNL Target] {#target}

**Última actualización: 3 de agosto de 2021**

Consulte las [[!DNL Target] notas de la versión](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=es) para obtener la información más reciente sobre la versión.

## ![Icono](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] es una aplicación completa para la gestión de posibles clientes y para los especialistas en marketing B2B que buscan transformar las experiencias de los clientes al interactuar en todas las fases de los recorridos de compra complejos.

### Actualizaciones centrales de Marketo Engage

Consulte [!DNL Marketo Engage] [programación de versiones](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=es) para obtener la información más reciente sobre el calendario de versiones y las notas de la versión.

## ![Icono](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] es una aplicación de administración de trabajo unificada para compartir ideas, crear contenido, administrar procesos complejos y trabajar de forma óptima.

Consulte la página [[!DNL Workfront] Versiones](https://one.workfront.com/s/product-releases) de para obtener un resumen de la información más reciente de todos los productos.

## ![Icono](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Nuevos vídeos, tutoriales o cursos publicados para Adobe Document Cloud.

### Cursos y tutoriales para Document Cloud {#tutorials-doc-cloud}

| Publicadas | Nombre | Tipo | Descripción |
| -----------| ---------- | ---------- | ---------- |
| Octubre de 2021 | [¿Qué es una firma digital?](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | Vídeo | Aprenda a utilizar ID digitales de todo el mundo con Adobe Sign. |
| Octubre de 2021 | [Introducción a Adobe Sign para nuevos remitentes](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/new-sender.html) | Vídeo | Si es nuevo en utilizar Adobe Sign, este tutorial es un bueno lugar para empezar. Este tutorial completo se centra en todos los conceptos básicos para ayudarle a poner en marcha Adobe Sign rápidamente. |
| Octubre de 2021 | [Cargar comentarios del PDF en InDesign](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/indesign.html) | Vídeo | En este tutorial de vídeo de 60 segundos, aprenda a cargar los comentarios del PDF de nuevo en el InDesign después de una revisión compartida de Acrobat. Este flujo de trabajo digital le ayuda a completar las revisiones en tiempo de registro. |
| Octubre de 2021 | [Obtención de un ID digital de [!DNL Intesi Group]  (cualificado)](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-qualified.html) | Vídeo | Obtenga información sobre cómo obtener un certificado de firma digital cualificado del grupo [!DNL Intesi]. Una vez registrada y verificada la identidad, [!DNL Intesi] Group le envía un ID digital que se utiliza para aplicar una firma de nube de Adobe Sign. |
| Octubre de 2021 | [Firma mediante [!DNL Intesi Group]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-sign.html) | Vídeo | Aprenda a utilizar su ID digital del grupo Intesi para autenticar su identidad y autorizar una firma digital remota (firma en la nube) en un documento. |
| Octubre de 2021 | [Obtención de un ID digital desde [!DNL Intesi Group]  (avanzado)](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-advanced.html) | Vídeo | Obtenga información sobre cómo obtener un certificado de firma digital avanzado de Intesi Group. Una vez registrado y verificado su identidad, el Grupo Intesi le envía un ID digital que se utiliza para aplicar una firma de nube de Adobe Sign. |
| Octubre de 2021 | [Firma mediante [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-sign.html) | Vídeo | Aprenda a utilizar su [!DNL Digidentity] ID digital para autenticar su identidad y autorizar una firma digital remota (firma en la nube) en un documento. |
| Octubre de 2021 | [Obtener un ID digital de [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-reg.html) | Vídeo | Obtenga información sobre cómo obtener un certificado de firma digital de [!DNL Digidentity]. Una vez registrada y verificada la identidad, [!DNL Digidentity] le envía un ID digital que se utiliza para aplicar una firma de nube de Adobe Sign. |
| Octubre de 2021 | [Detectar diferencias entre dos PDF](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/compare.html) | Vídeo | Nunca cometa el error de trabajar con la versión incorrecta de un archivo. Detectar rápida y correctamente las diferencias entre dos archivos PDF para mejorar los flujos de trabajo de revisión de documentos. |
| Octubre de 2021 | [Crear contenido PDF al examinar con Microsoft® Edge](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/edge.html) | Vídeo | Aprenda a archivar páginas web para el PDF sobre la marcha con la extensión Adobe Acrobat para Microsoft® Edge. Esta herramienta sólo para Windows es inestimable para proyectos de investigación y visualización sin conexión de información basada en web. |
| Octubre de 2021 | [Conversión de mensajes de correo electrónico y archivos adjuntos en PDF en Outlook](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/outlook.html) | Vídeo | Aprenda a archivar mensajes de correo electrónico y archivos adjuntos en PDF en Outlook para sus proyectos. Aprenda a proporcionar información de una manera más profesional y segura mediante la conversión automática de archivos adjuntos al PDF. Esta herramienta solo está disponible para Windows. |

{style=&quot;table-layout:auto&quot;}

Para obtener ayuda de Document Cloud, consulte:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=es)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=es)
* [Información y asistencia técnica de Adobe Document Cloud](https://helpx.adobe.com/es/support/document-cloud.html)

## ![Icono](/assets/creative-cloud-24.png) Creative Cloud para empresas {#creative-cloud}

Consulte [Creative Cloud para tutoriales empresariales](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=es) para conocer los tutoriales más recientes.
