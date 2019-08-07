---
title: Notas de la versión de Adobe Experience Cloud
description: Plantilla para notas de la versión de Experience Cloud
doc-type: notas de la versión
last-update: Agosto de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 6e1d9c4b083968fe1632d1309900058c90206fe1

---


# Acceso anticipado: notas de la versión de Adobe Experience Cloud

Nuevas funciones y correcciones en Adobe Experience Cloud.

>[!IMPORTANT]
>
>Esta página incluye contenido previo al lanzamiento de la nueva versión y está sujeta a cambios antes de su publicación planificada.

>[!NOTE]
>
>Suscríbase a la [actualización de producto prioritaria de Adobe](https://www.adobe.com/subscription/priority-product-update.html) para recibir notificaciones por correo electrónico de las próximas versiones. Recibirá el aviso entre tres y cinco días laborables antes del lanzamiento de la versión. La nueva información publicada tras el lanzamiento se marcará con la fecha de publicación.

**Fecha de la versión: Agosto de 2019**

* [Plataforma y administración de experiencias](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (vínculos a la ayuda de solución)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (vínculos a la ayuda de solución)

## [!UICONTROL Plataforma] y administración de experiencias {#platform}

Notas de la versión de la plataforma [!UICONTROL de experiencia], la interfaz de Experience Cloud, la administración de productos, Launch Platform Launch, Identity Service y los boletines de seguridad.

* [Interfaz de Experience Cloud](#core-services)
* [Experience Platform Launch](#launch)
* [Boletines de seguridad y avisos](https://helpx.adobe.com/security.html) (Todos los productos de Adobe)

### Interfaz de Experience Cloud {#core-services}

* Se ha corregido un problema crítico en el inicio de sesión de Experience Cloud que llevaba a la sesión de sesión de algunos usuarios. (MCUI-6908)
* Se ha actualizado el inicio de sesión de Experience Cloud para mejorar el rendimiento y reducir la latencia. (MCUI -6854, MCUI -6869, MCUI -6883)
* Interfaz actualizada de forma estática. (MCUI -6861, MCUI -6911, MCUI -6862)
* Se ha corregido un problema con [!UICONTROL los activadores] de Experience Cloud que provocaba una interpretación incorrecta de _la cláusula "Me gusta"_ en la definición [!UICONTROL de Activador] . (MCUI-6611)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Nuevas funciones y correcciones en Adobe Analytics:

* [Nuevas funciones, mejoras y correcciones en Adobe Analytics](#aa-features)
* [Avisos importantes para los administradores de Analytics](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### New features, enhancements, and fixes in Adobe Analytics {#aa-features}

| Función | Descripción |
| -----------| ---------- |  
| Compatibilidad con la configuración de cookies samesite | La [configuración](https://web.dev/samesite-cookies-explained) de la cookie samesite será agregada a todos los conjuntos de cookies por Analytics. Este cambio le permite cumplir con los cambios de Chrome que requieren el campo de cookie samesite. Las cookies de Analytics estarán `none`predeterminadas. Si ha utilizado exclusivamente un dominio de origen (p. ej. stats.domain.com), puede hacer que Adobe clientcare lo establezca `lax` en dominios de recopilación de origen. |
| Espacio de trabajo: Aumento del límite de elementos para el filtro desplegable de 50 a 200 | Aumentamos el límite de elementos que se pueden colocar en un filtro desplegable de 50 a 200. Esta mejora permite una variedad de casos de uso, como agregar todos los países (195) a un filtro, o todos los estados y provincias de EE. UU. (52). |
| Impresiones de actividad de A 4 T y conversiones de actividad habilitadas para IQ de atribución | Hemos habilitado dos métricas de Analytics para Target (A 4 T) para IQ de Atribución: Impresiones de actividad y Conversión de actividades. En Analysis Workspace hasta la fecha, estas métricas se han incrementado en comparación con Informes y análisis. Con este cambio, los usuarios ahora pueden aplicar un modelo de atribución «mismo toque», que hará que Analysis Workspace esté en línea con Informes y análisis. |

#### Correcciones

* Se ha corregido un problema con el texto que se mostraba en los informes en tiempo real en el modo de pantalla completa. (AN-183168)

### Avisos importantes para los administradores de [!DNL Analytics] {#aa-notices}

| Aviso | Fecha de incorporación o actualizada | Descripción |
| -----------| ---------- | ---------- |
| Compatibilidad con desplazamientos históricos de zona horaria | 8 de agosto de 2019 | Analytics ahora gestiona automáticamente los desplazamientos de zona horaria para las visitas con marca de hora. Siguiendo este cambio el 8 de agosto, los sistemas que se cargan en los datos del procesamiento histórico ya no deberán ajustarse en los desplazamientos de zona horaria antes de enviar los datos. |
| Límites del Generador de reglas de clasificación | Añadidos el 5 de junio de 2019 | Estos límites no son nuevos, pero se han agregado a la documentación [aquí](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Nuevos límites de operadores de segmentos | Añadidos el 31 de mayo de 2019 | Starting July 18, 2019, the segment operators _contains any of_, _does not contain any of_, _contains all of_ and _does not contain all_ of will be limited to 100 words per input field. El límite se aplicará a todos los segmentos nuevos y modificados después de esta fecha. Los segmentos existentes que excedan el límite seguirán siendo compatibles, pero no se podrán modificar ni guardar hasta que se reduzca el número de palabras del campo de entrada. Estos límites se aplican como parte de un intento continuo por mejorar el rendimiento de la consultas. |
| Próximos cambios de soporte para las **[!UICONTROL clasificaciones numéricas 2]** y con **[!UICONTROL fecha habilitada]** | Actualizado el 28 de mayo de 2019 | Se ha eliminado de la base de código la posibilidad de importar clasificaciones numéricas 2 y fechas activadas. Este cambio entra en vigor con el lanzamiento de mantenimiento de julio de 2019. Si tiene columnas numéricas o con fecha habilitada en el archivo de importación, esas celdas serán omitidas sin aviso y cualquier otra información de ese archivo se importará como de costumbre. <br/>Las clasificaciones existentes se pueden exportar a través del flujo de trabajo de clasificación estándar y seguirán estando disponibles en los informes. |
| Futuros cambios en los cálculos _Total de informes_ | actualizado el 9 de julio de 2019 | El **18 de junio de 2019**, Adobe Analytics unificará los cálculos _Total de informes_ en todas sus dimensiones y métricas. Por tanto, se cambiarán los totales de algunos informes (Prop o informes de atributos del consumidor). Antes de este cambio, algunos totales de informes no incluían el elemento de línea _Sin especificar_ en el total, independientemente de si el valor _Sin especificar_ aparecía en el informe o no. <br/>A partir del 18 de junio de 2019, el valor _Sin especificar_ aparecerá siempre en el total de los informes, aunque no aparezca en él como un elemento de línea. Además, los segmentos que utilizan la lógica _existe_ o _no existe_ pueden obtener resultados diferentes para algunas dimensiones después de este cambio, específicamente las dimensiones en las que _No especificado_ tiene un nombre especial como el elemento de línea "Escritos o marcadores" para la dimensión Tipo de referente o el elemento de línea "Otro" para la dimensión Tipo de dispositivo. Este cambio afectará a Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder y a la API de informes. |
| Actualización de las descargas de CSV desde [!DNL Analysis Workspace] | 10 de abril de 2019 | A partir del 11 de abril de 2019, se realizarán varios cambios en las **[!UICONTROL descargas de CSV]** (y en **[!UICONTORL Copiar al Portapapeles]**) desde [!DNL Analysis Workspace] para eliminar el formato de los datos exportados.  <ul><li>El separador de miles ya no se incluye. Se seguirá incluyendo el separador decimal y se respetará el formato definido dentro de **[!UICONTROL Componentes &gt; Configuración de informes &gt; Separador de miles]**. Nota: Los valores numéricos que utilizan una coma como separador decimal seguirán citados en el CSV exportado.</li><li>No se mostrarán símbolos de moneda.</li><li>No se mostrarán símbolos de porcentajes. Los porcentajes estarán en formato decimal. Por ejemplo, 75 % estará representado como 0,75.</li><li>El tiempo se mostrará en segundos.</li><li>Las tablas de cohorte muestran solo valores sin procesar; se eliminan los porcentajes.</li><li>Si un número no es válido, se mostrará una celda vacía.</li></ul> |
| Cambio en el comando de Debugger[!DNL Analysis Workspace] | 4 de abril de 2019 | El comando Console para activar el [!DNL Analysis Workspace] Debugger cambia a adobeTools.debug.includeOberonXml el **13 de junio de 2019**. adobe.tools.debug.includeOberonXml dejará de funcionar a partir de esa fecha. |
| Números de versión de los navegadores web | 7 de febrero de 2019 | A partir del 8 de enero de 2019, cambiamos el nivel de truncamiento para los números de versión de navegadores web de 2 a 1. A partir de esa fecha, las versiones solo mostrarán los dos primeros niveles (por ejemplo, _Firefox 64.0.2_ ahora aparece como _Firefox 64.0_). |
| Finalización del servicio de [!DNL Ad Hoc Analysis] | 29 de enero de 2019 | El 6 de agosto de 2018 Adobe anunció su intención de finalizar el servicio de [!DNL Ad Hoc Analysis]. La fecha se hará pública una vez que esté disponible.<br/>Para obtener más información, incluidas las versiones de Java compatibles durante este periodo, visite [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Vínculos [!DNL Analytics] breves de informes | 14 de enero de 2019 | A partir del 17 de enero de 2019, todos los vínculos [!DNL Analytics] breves a informes de que no hayan recibido ninguna visita en el plazo de un año se limpiarán y eliminarán de forma gradual. |
| Finalización de la compatibilidad con TLS 1.0 | Actualizado 10 de enero de 2019 | Desde el 11 de febrero de 2019, los informes de Adobe Analytics no son compatibles con el cifrado TLS (Transport Layer Security) 1.0. Este cambio forma parte de nuestros continuos esfuerzos por mantener los estándares de seguridad más elevados y fomentar la protección de los datos de nuestros clientes. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/server-side-forwarding/ssf-requirements.html).<br/> Desde el 20 febrero de 2019, la recopilación de datos de Adobe Analytics no es compatible con TLS 1.0. Este cambio significa que Adobe ya no recopila [!DNL Analytics] datos de los usuarios finales que utilicen dispositivos antiguos o exploradores web incompatibles con TLS 1.1 o posteriores. No esperamos que esto tenga un impacto significativo en los datos de los clientes ni en los informes. (Si el sitio web ya no ofrece compatibilidad con TLS 1.0, usted no se verá afectado). <br/>A partir del 11 de abril de 2019, la API de informes de Adobe Analytics ya no será compatible con el cifrado TLS 1.0. Los clientes que acceden a la API deben verificar que no se verán afectados. <ul><li>Los clientes de API que utilicen Java 7 con la configuración predeterminada deberán realizar [ modificaciones para que sea compatible con TLS 1.2](https://www.java.com/en/configure_crypto.html). (Consulte _Cambio de la versión de protocolo TLS predeterminada para puntos finales del cliente: de TLS 1.0 a TLS 1.2_.) </li><li>Los clientes de API que usen Java 8 no deberían tener problemas, ya que la configuración predeterminada es TLS 1.2.</li><li> Los clientes de API que usen otros módulos deben ponerse en contacto con su proveedor para obtener más información acerca de la compatibilidad con TLS 1.2.</li></ul> |
| Canal de datos: cambio de tamaño de la columna post_product_list | 9 de enero de 2019 | El 7 de febrero de 2019, Adobe aumentó el tamaño de la columna post_product_list de 64 KB a 16 MB. El objetivo de este cambio es garantizar que los valores eVar de comercialización añadidos a post_product_list durante el procesamiento no provoquen la solapación entre los valores de ingresos y el producto. Si tiene procesos que consumen valores de post_product_list, compruebe que dichos procesos puedan gestionar valores de hasta 16 MB de longitud; de lo contrario, el valor se truncará a los 16 KB para evitar fallos producidos por el consumo de datos. |
| Cambios de administración que afectan a los puntos de conexión de [!DNL Analytics Live Stream] inactivos | 20 de diciembre de 2018 | A partir del 1 de febrero de 2019, puede que se deshabiliten los puntos de conexión de [!DNL Live Stream] que no tengan conexiones activas de consumidores durante 90 días. Póngase en contacto con el Servicio de atención al cliente para consultar sobre sus puntos de conexión de [!DNL Live Stream] y, si es necesario, solicitar que los vuelvan a habilitar. Además, asegúrese de que los procesos de consumidores mantengan una conexión persistente, tal como se pretende desde el diseño del servicio, y que se implementen para reconectar cuando se desconecte o interrumpa la conexión. |
| Actualizar el [!DNL Report Builder] de Adobe debido al fin de la compatibilidad con TLS 1.0 | 7 de septiembre de 2018 | Debido al fin de la compatibilidad con TLS 1.0, recomendamos a los usuarios de [!DNL Report Builder] que descarguen ARB v5.6.21 antes de febrero de 2019. Después de esta fecha, las versiones anteriores de dejarán de [!DNL Report Builder] funcionar. |

### AppMeasurement {#appm}

[!UICONTROL Versiones de appmeasurement] 2.16.0 el 8 de agosto de 2019.

| Función | Descripción |
| -----------| ---------- |
| `sendBeacon` compatibilidad con vínculos de salida | Se ha implementado `sendBeacon` la compatibilidad en [!UICONTROL appmeasurement] para vínculos de salida. Esto mejorará el seguimiento del vínculo de salida y probablemente dará como resultado un incremento del tráfico. |
| Valores ECID/fid | Los valores ECID/fid ahora se almacenan en caché en la primera visita, aunque cambie la configuración optin. |
| DIL 9.3 | Módulo de gestión de público actualizado a DIL 9.3 |
| Seguimiento de alcance de desplazamiento | Conmutador expuesto en s. activitymap. trackscrollreach para activar o desactivar el seguimiento de alcance de desplazamiento. |
| Servicio de ID de visitante 4.4.0 | Appmeasurement actualizado para utilizar el servicio de ID de visitante 4.4.0. |

#### Correcciones

* Se ha corregido un error en la cola de appmeasurement que se producía antes de que isreadytotrack fuese verdadero.

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

## Audience Manager {#aam}

**Correcciones y mejoras**

* La ficha Administración ahora solo aparece en cuentas de usuario con privilegios administrativos (AAM -48557).
* La API de lista de usuarios ahora devuelve detalles completos del usuario (AAM -48662).
* Ahora puede cambiar el tamaño de la lista de carpetas de características (AAM -48800).
* Varias optimizaciones de accesibilidad de la interfaz de usuario (AAM -48865, AAM -48933).
* Carga de optimizaciones para las páginas de administración de datos y administración (AAM -48514).

## [!DNL Campaign] {#ac}

Adobe Campaign permite entregar, de forma intuitiva y automatizada, mensajes privados a través de canales de marketing en línea y sin conexión. Ahora puede anticipar los deseos de los clientes mediante experiencias basadas en sus hábitos y preferencias.

### Adobe Campaign Standard

[Versión de Campaign Standard 19.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

| Función | Descripción |
| -----------| ---------- |  
| Actividad de API externa (beta pública) | Para una personalización más profunda, la actividad de API externa permite introducir datos de sistemas externos en un flujo de trabajo mediante una llamada de API REST. Los puntos finales de REST pueden ser un sistema de administración de clientes, un tiempo de ejecución de Adobe I/O o un punto final de Adobe Experience Cloud REST (por ejemplo, plataforma de datos, Target, Analytics, campaña). Esta capacidad está actualmente en versión beta pública. Para obtener más información, consulte la documentación [detallada](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) y el vídeo [de procedimientos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html). |
| Informe sobre el segmento de flujo de trabajo | Esta función permite a los especialistas en marketing desglosar el rendimiento de entrega por código de segmento. Cuando crea un flujo de trabajo y utiliza una actividad de segmentación para asignar segmentos a la población de envíos, estos segmentos ahora pueden entrar en la misma entrega. Esto le permite mostrar las estadísticas de aperturas/clics en función de varios segmentos dentro de una entrega única. Para obtener más información, consulte la documentación [detallada](https://docs.adobe.com/content/help/en/campaign-standard/using/reporting/customizing-reports/creating-a-report-workflow-segment.html) y el vídeo [de procedimientos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/reporting/report-on-workflow-segments.html). |

### Adobe Campaign Classic

[Actualización de Campaign Classic 19.1.3](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - compilación 9031

### Panel de control de Adobe Campaign

[Las nuevas funcionalidades del Panel de control](https://helpx.adobe.com/campaign/kb/control-panel-instance-settings.html) incluyen la capacidad de agregar URL que Campaign Classic conecta con para transferencias de datos o archivos.

Tenga en cuenta que [!UICONTROL el Panel de control] está disponible para los clientes de Adobe Campaign Classic y Adobe Campaign Standard alojados en AWS. No se requiere ninguna actualización para el Panel de control.

### Recursos adicionales

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)