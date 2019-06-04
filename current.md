---
title: Notas de la versión de Adobe Experience Cloud
description: Plantilla para notas de la versión de Experience Cloud
doc-type: notas de la versión
last-update: Mayo de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 8517ef177c10b4a0e5228ccbcb9168d0e35577e0

---


# Notas de la versión de Adobe Experience Cloud

Nuevas funciones y correcciones en Adobe Experience Cloud.

>[!NOTE]
>>Suscríbase a la [actualización de producto prioritaria de Adobe](https://www.adobe.com/subscription/priority-product-update.html) para recibir notificaciones por correo electrónico de las próximas versiones. Recibirá el aviso entre tres y cinco días laborables antes del lanzamiento de la versión. La nueva información publicada tras el lanzamiento se marcará con la fecha de publicación.


**Fecha de la versión: Mayo de 2019**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.5.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Notas de la versión de Adobe Experience Platform

Versión 1.0, 15 de mayo de 2019

* Consulte [las notas de la versión de Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) en Adobe. io para obtener las últimas actualizaciones de la plataforma de experiencia.

### Experience Platform Launch

* Consulte [Launch Platform Launch](https://docs.adobelaunch.com/) para obtener la información más reciente.

### Servicio Experience Cloud ID

Publicado **el 13 de mayo de 2019**

* Compatibilidad con el Visitante API 4.3.0
* Compatibilidad con ITP 2.1.
* Se ha corregido un problema con la configuración de secureCookie.

## Analytics {#analytics}

Nuevas funciones y correcciones en Adobe Analytics:

* [Nuevas funciones y correcciones en Adobe Analytics](#aa-features)
* [Avisos importantes para los administradores de Analytics](#aa-notices)

Para obtener la documentación del producto, consulte la [Página principal de ayuda de Analytics](https://marketing.adobe.com/resources/help/en_US/reference/).

### Nuevas funciones y correcciones en Adobe Analytics {#aa-features}

| Función | Descripción |
| -----------| ---------- |  
| [!DNL AppMeasurement Version 2.14.0] <ul><li>Se han corregido problemas con la administración del estado de los parámetros de rastreador cuando hay varias visitas pendientes. (AN -176931, AN -176629, DTM -12758)</li><li>Appmeasurement actualizado para incluir Visitor. js 4.3.0 (AN -180049)</li></ul> |
| [!DNL Analysis Workspace]: Nueva configuración de visualización de flujo para _incluir instancias repetidas_ | La configuración de flujo para _Incluir instancias repetidas_ le proporciona la opción de incluir o excluir instancias repetidas, como las recargas de página. Además, todas las visualizaciones de flujo se basan solamente en instancias. |
| [!DNL Ad Hoc Analysis]: Compatibilidad con Java 11 | Ad Hoc Analysis ahora es compatible con Java 11. Aprenda a ejecutar [Análisis específicos en Java 11](https://marketing.adobe.com/resources/help/en_US/dsc/adhoc-java.html). |
| **Recopilación de datos:** Nueva cookie s_ ecid | Se ha añadido una nueva cookie de servidor individual, s_ecid, en la cual la recopilación de datos almacena el ECID del visitante. |

**Correcciones de Analysis Workspace**

* Se corrigió el problema que afectaba **[!UICONTROL al tiempo empleado en la página]**. [!DNL Analysis Workspace]Los informes del ya no utilizarán el nombre de la página cuando calculen los bloques de tiempo empleado, lo cual permite contar las visitas granulares y en bloque. **[!UICONTROL ]****[!UICONTROL ]** (AN-140479)
* Los problemas de rendimiento de visualización de líneas fijas como parte de un esfuerzo mayor por mejorar [!DNL Analysis Workspace] el rendimiento. (AN-174878)
* Se corrigió un problema con la falta de codificación UTF-8 en los archivos CSV descargados. (AN-178393)
* Se han corregido problemas con el lento [!DNL Analysis Workspace] rendimiento del proyecto. (AN-177710)
* Se corrigieron problemas de muestra de visualización de líneas con intervalos pequeños en la granularidad del eje y. (AN-176467)

**Otras correcciones de Analytics**

* [!DNL Audience Analytics]: Se ha corregido un problema que se producía después de cambiar el nombre de una audiencia [!DNL Audience Manager (AAM)] ; el nombre actualizado no se reflejaba en Audience Analytics. (AN-176237)
* Se ha corregido un problema que impedía que los usuarios guardaran [! Segmentos DNL Analytics en [!DNL Audience Manager]. Esto se originó en las carpetas AAM existentes con nombres que usaban tanto mayúsculas como minúsculas. Ahora ninguna carpeta hace la distinción entre mayúsculas y minúsculas con el fin de que se sincronicen correctamente. (AN-177934)
* Se ha corregido un problema que se producía cuando los usuarios iniciaban sesión a [!DNL Analytics] través de la [!DNL Experience Cloud] sesión y después se agotaba el tiempo de espera de la sesión. Al reanudar la sesión, se redirigía al usuario a una URL defectuosa. (AN-176812)
* Se ha corregido un problema con desplazamientos de zona horaria en [!DNL Data Warehouse] solicitudes. (AN-177585)

### Avisos importantes para los administradores de Analytics {#aa-notices}

| Aviso | Fecha de incorporación  o actualizada | Descripción |
| -----------| ---------- | ---------- |
| Próximos cambios de soporte para **[!UICONTROL clasificaciones numéricas]** y **[!UICONTROL con fecha 2 habilitada]** | Actualizado 28 de mayo de 2019 | La capacidad para importar clasificaciones numéricas 2 y habilitadas por fecha se eliminará del código base. Este cambio tendrá efecto con la versión de mantenimiento de julio de 2019. Si tiene columnas numéricas o con fecha habilitada en el archivo de importación, esas celdas serán omitidas sin aviso y cualquier otra información de ese archivo se importará como de costumbre. <br/>Las clasificaciones existentes se pueden exportar a través del flujo de trabajo de clasificación estándar y seguirán estando disponibles en los informes. |
| Futuros cambios en los cálculos _Total de informes_ | Actualizado 2 de mayo de 2019 | El **13 de junio de 2019**, Adobe Analytics unificará los cálculos _Total de informes_ en todas sus dimensiones y métricas. Por tanto, se cambiarán los totales de algunos informes (Prop o informes de atributos del consumidor) Antes de este cambio, algunos totales de informes no incluían el elemento de línea _Sin especificar_ en el total, independientemente de si el valor _Sin especificar_ aparecía en el informe o no. <br/>A partir del 13 de junio de 2019, el valor _Sin especificar_ aparecerá siempre en el total de los informes, aunque no aparezca en él como un elemento de línea. Además, los segmentos que utilizan la lógica _existe_ o _no existe_ pueden obtener unos resultados diferentes para algunas dimensiones después de este cambio. Este cambio afectará a Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder y a la API de informes. |
| Actualizar a descargas CSV desde [!DNL Analysis Workspace] | 10 de abril de 2019 | A partir del 11 de abril de 2019, se realizaron varios cambios en **[!UICONTROL las descargas]** de CSV (y **[!UICONTORL Copiar al portapapeles]**) para [!DNL Analysis Workspace] eliminar el formato de los datos exportados.  <ul><li>El separador de miles ya no se incluye. Se seguirá incluyendo el separador decimal y se respetará el formato definido dentro de **[!UICONTROL Componentes &gt; Configuración de informes &gt; Separador de miles]**. Nota: Los valores numéricos que utilizan una coma como separador decimal seguirán citados en el CSV exportado.</li><li>No se mostrarán símbolos de moneda.</li><li>No se mostrarán símbolos de porcentajes. Los porcentajes estarán en formato decimal. Por ejemplo, 75 % estará representado como 0,75.</li><li>El tiempo se mostrará en segundos.</li><li>Las tablas de cohorte muestran solo valores sin procesar; se eliminan los porcentajes.</li><li>Si un número no es válido, se mostrará una celda vacía.</li></ul> |
| Próximo cambio al [!DNL Analysis Workspace] depurador, comando | 4 de abril de 2019 | El comando Console to turn on the [!DNL Analysis Workspace] Debugger está cambiando a adobetools. debug. includeoberonxml el 13 de **junio de 2019**. adobe.tools.debug.includeOberonXml dejará de funcionar a partir de esa fecha. |
| Números de versión de los navegadores web | 7 de febrero de 2019 | A partir del 8 de enero de 2019, cambiamos el nivel de truncamiento para los números de versión de navegadores web de 2 a 1. A partir de esa fecha, las versiones solo mostrarán los dos primeros niveles (por ejemplo, _Firefox 64.0.2_ ahora aparece como _Firefox 64.0_). |
| Fin de vida útil para [!DNL Ad Hoc Analysis] | 29 de enero de 2019 | El 6 de agosto de 2018, Adobe anunció la intención de [!DNL Ad Hoc Analysis]caducar. La fecha se hará pública una vez que esté disponible.<br/>Para obtener más información, incluidas las versiones de Java compatibles durante este periodo, visite [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Vínculos breves a informes de Analytics | 14 de enero de 2019 | A partir del 17 de enero de 2019, todos los vínculos breves a informes de Analytics que no hayan recibido ninguna visita en el plazo de un año se limpiarán y eliminarán de forma gradual. |
| Finalización de la compatibilidad con TLS 1.0 | Actualizado el 10 de enero de 2019 | Desde el 11 de febrero de 2019, los informes de Adobe Analytics no son compatibles con el cifrado TLS (Transport Layer Security) 1.0. Este cambio forma parte de nuestros continuos esfuerzos por mantener los estándares de seguridad más elevados y fomentar la protección de los datos de nuestros clientes. Si no puede conectarse a los informes de Adobe Analytics después del 11 de febrero de 2019, debe actualizar el navegador a la versión [más reciente](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/> Desde el 20 febrero de 2019, la recopilación de datos de Adobe Analytics no es compatible con TLS 1.0. Este cambio significa que Adobe ya no recopila datos de Analytics de los usuarios finales que utilicen dispositivos antiguos o exploradores web incompatibles con TLS 1.1 o posteriores. No esperamos que esto tenga un impacto significativo en los datos de los clientes ni en los informes. (Si el sitio web ya no ofrece compatibilidad con TLS 1.0, usted no se verá afectado). <br/>A partir del 11 de abril de 2019, la API de informes de Adobe Analytics ya no será compatible con el cifrado TLS 1.0. Los clientes que acceden a la API deben verificar que no se verán afectados. <ul><li>Los clientes de API que utilicen Java 7 con la configuración predeterminada deberán realizar [ modificaciones para que sea compatible con TLS 1.2](https://www.java.com/en/configure_crypto.html). (Consulte _Cambio de la versión de protocolo TLS predeterminada para puntos finales del cliente: de TLS 1.0 a TLS 1.2_). </li><li>Los clientes de API que utilicen Java 8 no deben verse afectados, ya que la configuración predeterminada es TLS 1.2.</li><li> Los clientes de API que usen otros módulos deben ponerse en contacto con su proveedor para obtener más información acerca de la compatibilidad con TLS 1.2.</li></ul> |
| Canal de datos: cambio de tamaño de la columna post_product_list | 9 de enero de 2019 | El 7 de febrero de 2019, Adobe aumentó el tamaño de la columna post_product_list de 64 KB a 16 MB. Este cambio garantiza que los valores de evar de comercialización agregados a post_ product_ list durante el procesamiento no provoquen truncamiento de los valores de ingresos e ingresos. Si tiene procesos que consumen valores de post_product_list, compruebe que dichos procesos puedan gestionar valores de hasta 16 MB de longitud; de lo contrario, el valor se truncará a los 16 KB para evitar fallos producidos por el consumo de datos. |
| Cambios de administración que afectan [!DNL Analytics Live Stream] los puntos finales inactivos | 20 de diciembre de 2018 | A partir del 1 de febrero de 2019, pueden deshabilitarse [!DNL Live Stream] los puntos finales sin conexiones activas al consumidor durante 90 días. Puede ponerse en contacto con el Servicio de atención al cliente para solicitar información sobre los [!DNL Live Stream] puntos finales y, si es necesario, volver a activarlos. Además, asegúrese de que los procesos de consumidores mantengan una conexión persistente, tal como se pretende desde el diseño del servicio, y que se implementen para reconectar cuando se desconecte o interrumpa la conexión. |
| Actualizar el [!DNL Report Builder] de Adobe debido al fin de la compatibilidad con TLS 1.0 | 7 de septiembre de 2018 | Debido al final de la compatibilidad con TLS 1.0, recomendamos que [!DNL Report Builder] los usuarios descarguen la versión v 5.6.21 anterior a febrero de 2019. Después de esa fecha, las versiones anteriores de [!DNL Report Builder] no funcionarán. |

## Audience Manager {#aam}

| Función | Descripción |
| -----------| ---------- |  
| [Complicación de la dirección IP](https://marketing.adobe.com/resources/help/en_US/aam/ip-obfuscation.html) | Es posible que su empresa desee complicar la dirección IP en muchos países debido a las normativas de privacidad globales. Audience Manager le permite complicar las direcciones IP de los visitantes en forma global o por país. |
| [Personalización de integraciones de socio - Nube de datos de Oracle](https://marketing.adobe.com/resources/help/en_US/aam/custom-partner-integrations.html) | Esta página muestra las integraciones personalizadas entre Audience Manager y los socios de datos. Audience Manager ingesta la cookie y los datos de ID móviles de la nube de datos de Orale para Audience Marketplace a través de archivos de datos entrantes. Las especificaciones de integración personalizadas descritas en esta página solo se refieren a los archivos de datos entrantes que contienen ID de móviles (IDFA y Android Device ID). |

**Correcciones, mejoras y casos de finalización del soporte**

* Hemos añadido dos nuevas columnas a los informes generales de los destinos. Ahora puede ver la Fecha de inicio y la fecha final de una asignación de segmento a un destino. (AAM-44781)

## Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Adobe Experience Manager (AEM). Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

### Versiones de productos

**AEM 6.5**

AEM 6.5, disponible desde el 8 de abril de 2019, es una versión de actualización del código de AEM 6.4. Las actualizaciones más recientes de AEM 6.5 le proporcionan un acceso instantáneo a las atractivas mejoras que impulsan su actividad empresarial todavía más rápidamente.

* [Novedades de Adobe Experience Manager 6.5](https://www.adobe.com/marketing/experience-manager/new.html)
* [Notas de la versión de Adobe Experience Manager 6.5](https://helpx.adobe.com/experience-manager/6-5/release-notes.html)

**Cloud Manager 2019.4.0**

La versión más reciente de Cloud Manager (2019.4.0 publicada el 18 de abril de 2019) añade una interfaz de usuario localizada en francés, alemán y japonés. Además, se han mejorado los pasos de implementación.

* [Notas de la versión para Cloud Manager 2019.4.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### Mantenimiento del producto

**AEM 6.4.4.0**

AEM 6.4 Service Pack 4 (6.4.4.0, publicado el 4 de abril de 2019) es una actualización importante que incluye correcciones claves del cliente realizadas tras la publicación general de AEM 6.4 en abril de 2018.

[Notas de la versión para AEM 6.4 Service Pack](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
[Versiones de AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**Conector AEM S3**

Es posible que las instancias de AEM con versiones anteriores de conector de Datastore S3 no estén disponibles debido a errores de acceso S3 tras el fin de la compatibilidad con la versión de firma 2 del 24 de junio de 2019. Como cliente de AEM, Adobe recomienda verificar la versión del conector de Datastore de S3 que está utilizando. Si es necesario, actualice a una versión reciente.

Consulte [el impacto del desuso de la versión de la firma 2 de AWS para Amazon S3](https://helpx.adobe.com/experience-manager/kb/the-impact-of-aws-signature-version-2-deprecation-for-amazon-s3.html)

### Autoayuda

**Modernización del código de base de AEM Sites**

Aprenda a aprovechar la tecnología más reciente de AEM para modernizar su base de AEM Sites. [Modernizing your Existing Experience Manager Sites Codebase de Adobe Experience Manager](https://expleague.azureedge.net/labs/L761/index.html)

**AEM Editor Text Editor – Información detallada**

Conozca las prácticas recomendadas en las configuraciones y el uso del Rich Text Editor en AEM.

Consulte [la información detallada sobre AEM Rich Text Editor (RTE)](https://helpx.adobe.com/experience-manager/kt/eseminars/gems/AEM-Rich-Text-Editor-RTE-Deep-Dive1.html)

### Recursos adicionales 

* [Página de inicio de Learn &amp; Support de AEM 6.5](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Inicio de Información y asistencia de AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Inicio de Información y asistencia de AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Inicio de Información y asistencia de AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guía del usuario de Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Versiones anteriores de la documentación de AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Notas de la versión de Scene7 Publishing System](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notas de la versión de Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## Campaign {#ac}

Adobe Campaign permite entregar, de forma intuitiva y automatizada, mensajes privados a través de canales de marketing en línea y sin conexión. Ahora puede anticipar los deseos de los clientes mediante experiencias basadas en sus hábitos y preferencias.

* Campaign Classic 18.10.4 - compilación 8983
* Campaign Classic 18.10.5 - compilación 8984

Consulte las [Notas de la versión de Adobe Campaign Classic](http://docs.campaign.adobe.com/doc/AC/en/RN.html) para saber más sobre las correcciones y mejoras.

Para obtener información del producto, consulte:

* Adobe Campaign Standard: [Documentación](https://helpx.adobe.com/support/campaign/standard.html) - [ Notas de la versión](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ Vídeos de presentación](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Documentación](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de la versión](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos de presentación](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Advertising Cloud {#adcloud}

| Función | Descripción |
| -----------| ---------- |  
| Buscar Herramientas | (Anunciantes con cuentas de Google Ads) Advertising Cloud tiene la opción de cargar en Google Ads todos los datos de conversión que registra para las campañas de anuncios de Google Ads que usan el servicio de seguimiento de conversión de Advertising Cloud. Las cargas diarias incluyen el valor de conversión definido mediante el modelo de atribución a nivel de anunciante. Todas las conversiones cargadas tienen el prefijo &quot;Adobe_ACS_&quot; (como &quot;Adobe_ACS_Subscriptions&quot; para la conversión &quot;Suscripciones&quot;). <br/> **Nota:** Las cargas no incluirán datos de conversión subidos a Advertising Cloud desde archivos de fuentes. |
| Buscar campañas | El menú de **Búsqueda** &gt; **Campañas** &gt; **Campañas** es ahora jerárquico, con Campañas debajo de Cuentas; Grupos de publicidad en Campañas; y Palabras clave (con submenú), Publicidades, Grupos de productos (solo vistas en vivo), Colocaciones (con submenú) y Objetivos automáticos en Grupos de publicidad.<br/>En las vistas en vivo, Audiencias y Extensiones se encuentran en el mismo nivel que las Cuentas, con sus propios submenús. |

## Target Standard/Premium 19.5.1 {#target}

Esta versión incluye las funciones, cambios y mejoras siguientes:

(Los números entre paréntesis son para uso interno de Adobe).

### Actualizaciones de funciones

| Función/Mejora | Descripción |
| --- | --- |
| Compositor de experiencias visuales de aplicación de una sola página (SPA VEC) | El SPA VEC incluye las siguientes mejoras para que su trabajo sea más fácil y eficiente:<ul><li>Ahora puede cancelar la carga de un sitio web en el VEC para desbloquear la edición de una actividad. Esta mejora es útil si, por ejemplo, necesita hacer un pequeño cambio en una actividad, revisar su configuración o añadir código personalizado y no quiere esperar a que se cargue el sitio web. (TGT-33872)</li><li>Puede realizar muchas acciones antes de que la página se cargue en VEC o incluso si la página no se carga completamente (por ejemplo, si el código personalizado ya no funciona). Las acciones que no se pueden editar antes de que el sitio web cargue no aparecerán en la IU de Target. (TGT-33851 y TGT-34149)</li></ul> |
| Actividades de personalización automatizada (AP) y actividades de segmentación automática | Puede seleccionar una experiencia para utilizarla como control mientras crea una actividad de PA o de segmentación automática. Esto permite dirigir todo el tráfico de control a una experiencia específica, según el porcentaje de asignación de tráfico configurado en la actividad. A continuación, puede evaluar el rendimiento de los envíos personalizados con respecto a la experiencia de control. (TGT-26572) |
| Las actividades de | Puede utilizar la opción Recomendar elementos adquiridos anteriormente al crear la lógica de elementos visualizados recientemente. (TGT-34030) |

### Mejoras, correcciones y cambios

* Los iconos de la barra de herramientas se muestran correctamente después de cancelar la carga de una página dentro del VEC. Si no se pueden realizar acciones específicas hasta que la página se haya cargado por completo, los iconos de la barra de herramientas asociados se desactivan. (TGT-33811)
* Ahora puede ver y navegar con mayor facilidad mediante carpetas de ofertas en el selector de recursos en lugar de desplazarse por una jerarquía de carpetas plana. (TGT-33725)

Consulte las [Notas de la versión de Adobe Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) para obtener la información más reciente acerca de los siguientes productos:

* Target Standard y Target Premium
* Recommendations Classic


## Magento {#magento}

Magento es una plataforma de comercio electrónico que proporciona a los comerciantes en línea un sistema de compras flexible y, a la vez, permite controlar el aspecto, el contenido y la funcionalidad de su tienda en línea. Magento está disponible en una versión de código abierto y una versión de comercio con más funciones.

Magento Commerce forma parte de Adobe Commerce Cloud y ofrece una solución de comercio electrónico con potencia empresarial, adaptabilidad ilimitada y la flexibilidad del código abierto para las experiencias B2C y B2B.

Las notas de la versión de nuestras ediciones de código abierto y comercio se encuentran en la página [Información](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) de la versión.

## Primetime {#primetime}

Adobe Primetime es una plataforma de TV multipantalla que ayuda a las empresas de comunicación a crear y monetizar experiencias de visualización personalizadas y atractivas.

[Notas de la versión de Primetime](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Inicio de la Ayuda de Primetime](http://help.adobe.com/en_US/primetime/)