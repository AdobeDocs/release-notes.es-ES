---
title: Notas de la versión de Adobe Experience Cloud
description: Notas de la versión de Experience Cloud de junio de 2019
doc-type: notas de la versión
last-update: Junio de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: dbcd180c5fd07abd8a6b8ed9ec47b3b1d996f275

---


# Notas de la versión de Adobe Experience Cloud

Nuevas funciones y correcciones en Adobe Experience Cloud.

>[!NOTE]
>Suscríbase a la [actualización de producto prioritaria de Adobe](https://www.adobe.com/subscription/priority-product-update.html) para recibir notificaciones por correo electrónico de las próximas versiones. Recibirá el aviso entre tres y cinco días laborables antes del lanzamiento de la versión. La nueva información publicada tras el lanzamiento se marcará con la fecha de publicación.

**Fecha de publicación: 13 de junio de 2019**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [[! Campaña DNL]](#ac)
* [Mobile Services](#mobile)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Notas de la versión de Adobe Experience Platform

* Consulte [[! Notas de la versión de DNL Experience]](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) en Adobe. io para obtener las actualizaciones más recientes [!DNL Experience Platform].

### [!DNL Experience Platform Launch]

* Consulte [[! DNL Experience Platform Launch]](https://docs.adobelaunch.com/) para obtener la información más reciente.

## Analytics {#analytics}

Nuevas funciones y correcciones en Adobe Analytics:

* [Nuevas funciones y correcciones en Adobe Analytics](#aa-features)
* [Avisos importantes para los administradores de Analytics](#aa-notices)

Para obtener la documentación del producto, consulte la [Página principal de ayuda de Analytics](https://marketing.adobe.com/resources/help/en_US/reference/).

### Nuevas funciones y correcciones en Adobe Analytics {#aa-features}

| Función | Descripción |
| -----------| ---------- |  
| **Segmentación** | Nuevos modelos de atribución para dimensiones en segmentación:<ul><li>Repetición (predeterminada): Incluye instancias + valores persistentes para la dimensión.</li><li>Instancia: Incluye instancias para la dimensión.</li><li>Instancia no repetida: Incluye instancias únicas (no repetitivas) para la dimensión.</li></ul> [Más](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-build.html) |
| **Segmentación** | Nuevos operadores de segmentos: **[!UICONTROL Es igual a Cualquiera de]** y **[!UICONTROL no es igual a ninguno de]**. [Más...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segment-reference/seg-operators.html) |
| **Depurador** | Ahora, al iniciar sesión con su Adobe ID, tiene la opción de recuperar las visitas posprocesadas en Experience Cloud Debugger. Las visitas posprocesadas son llamadas al servidor después de haber pasado por [!UICONTROL reglas de procesamiento] y reglas de VISTA, lo que permite validar [!UICONTROL reglas de procesamiento] y sus reglas VISTA. **Nota**: Si utiliza A 4 T (complementos), los datos posteriores al procesamiento pueden tardar unos minutos en remontarse. |
| **Analysis Workspace:** | Se han agregado nuevos filtros predeterminados a la búsqueda de carril izquierdo. Más allá de lo que ve hoy (Dimensiones, Métricas, Aprobado, etc.), nuevos filtros como Métricas calculadas, Atributos del cliente, evars, Props, Vídeo, etc. se agregó para facilitar la búsqueda de los componentes que necesita. |
| **Analysis Workspace** | Se ha añadido una advertencia a la visualización de visitas en el orden previsto que se mostrará cuando agregue un segmento como punto de contacto: ciertas combinaciones de contenedores de segmentos no válidos provocarán un diagrama de visitas en el orden previsto no válido, como por ejemplo <ul><li>Uso de un segmento basado en visitantes como punto de contacto dentro de una visualización de visitas en el orden previsto de visitante en contexto</li><li>Uso de un segmento basado en visitantes como punto de contacto dentro de una visualización de visitas en el orden previsto visita-contexto</li><li>Uso de un segmento basado en visitas como punto de contacto dentro de una visualización de visitas en el orden previsto visita-contexto</li></ul> <br> [Más...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/fallout/compare-segments-fallout.html)</br> |
| **Mejoras en la documentación de Analytics** | La documentación de Analytics se ha reorganizado y ahora incluye funciones de colaboración que le permiten mejorar el contenido. Puede registrar problemas con la documentación y sugerir ediciones. El conjunto de documentos se ha trasladado a [un nuevo dominio](https://docs.adobe.com/content/help/en/analytics/landing/home.html). Las redirecciones deberían estar en su sitio. |
| **Nueva guía del usuario de notas técnicas** | La guía del usuario de Notas [técnicas](https://docs.adobe.com/content/help/en/analytics/technotes/home.html) ya está disponible. Actualmente, está orientado a ayudar a los usuarios con herramientas de análisis de terceros, como Google Analytics, a familiarizarse con Adobe Analytics. La guía del usuario de notas técnicas se ampliará durante los próximos meses para incluir contenido adicional. |

**Correcciones de Analysis Workspace**

* Se ha corregido un problema con la información localizada de fecha japonesa en [!DNL Analysis Workspace] las visualizaciones. (AN-180114)
* Se ha corregido un problema que se producía tras copiar y pegar elementos de dimensión. Las búsquedas subsiguientes en el elemento generaban un error. (AN-177394)
* Se ha corregido un problema con la opción de edición que faltaba en los paneles de segmentos en tablas improvisadas. (AN-171703)
* Se ha corregido un problema con **[!UICONTROL Establecer como página]** de aterrizaje que no funcionaba cuando se compartía con un gran conjunto de destinatarios. (AN-163922)
* Se ha corregido un problema que hacía que las cadenas se recortaran verticalmente en informes en tiempo real. (AN-175980)

**Otras correcciones de Analytics**

* Se ha corregido un problema por el que los usuarios administradores no podían habilitar **[!UICONTROL eventos de éxito]**. (AN-176689)
* Se ha corregido un problema que se producía al crear una alerta con la métrica **[!UICONTROL Tasa]** de salida. (AN-177476)

### Avisos importantes para los administradores de Analytics {#aa-notices}

| Aviso | Fecha de incorporación o actualizada | Descripción |
| -----------| ---------- | ---------- |
| Límites del generador de reglas de clasificación | Se agregó el 5 de junio de 2019. | Estos límites no son nuevos, pero se han agregado a la documentación [aquí](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| Nuevos límites de operadores de segmentos | Se agregó el 31 de mayo de 2019. | A partir del 18 de julio de 2019, los operadores de segmentos &quot;contiene cualquiera de&quot;, &quot;no contiene ninguno de&quot;, &quot;contiene todo&quot; y &quot;no contiene todos&quot; se limita a 100 palabras por campo de entrada. El límite se aplicará a todos los segmentos nuevos y modificados después de esta fecha. Los segmentos existentes que excedan el límite seguirán siendo compatibles, pero no se podrán modificar ni guardar hasta que se reduzca el campo de entrada. Estos límites se aplican como parte de un esfuerzo continuo por mejorar el rendimiento de la consulta. |
| Próximos cambios de soporte para las **[!UICONTROL clasificaciones numéricas]** y con **[!UICONTROL fecha habilitada]** | Actualizado 28 de mayo de 2019 | Se ha eliminado de la base de código la posibilidad de importar clasificaciones numéricas 2 y fechas activadas. Este cambio entra en vigor con el lanzamiento de mantenimiento de julio de 2019. Si tiene columnas numéricas o con fecha habilitada en el archivo de importación, esas celdas serán omitidas sin aviso y cualquier otra información de ese archivo se importará como de costumbre. <br/>Las clasificaciones existentes se pueden exportar a través del flujo de trabajo de clasificación estándar y seguirán estando disponibles en los informes. |
| Futuros cambios en los cálculos _Total de informes_ | Actualizado 2 de mayo de 2019 | El **13 de junio de 2019**, Adobe Analytics unificará los cálculos _Total de informes_ en todas sus dimensiones y métricas. Por tanto, se cambiarán los totales de algunos informes (Prop o informes de atributos del consumidor) Antes de este cambio, algunos totales de informes no incluían el elemento de línea _Sin especificar_ en el total, independientemente de si el valor _Sin especificar_ aparecía en el informe o no. <br/>A partir del 13 de junio de 2019, el valor _Sin especificar_ aparecerá siempre en el total de los informes, aunque no aparezca en él como un elemento de línea. Además, los segmentos que utilizan la lógica _existe_ o _no existe_ pueden obtener unos resultados diferentes para algunas dimensiones después de este cambio. Este cambio afectará a Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder y a la API de informes. |
| Actualización de las descargas de CSV desde [!DNL Analysis Workspace] | 10 de abril de 2019 | A partir del 11 de abril de 2019, se realizarán varios cambios en las **[!UICONTROL descargas de CSV]** (y en **[!UICONTORL Copiar al Portapapeles]**) desde [!DNL Analysis Workspace] para eliminar el formato de los datos exportados.  <ul><li>El separador de miles ya no se incluye. Se seguirá incluyendo el separador decimal y se respetará el formato definido dentro de **[!UICONTROL Componentes &gt; Configuración de informes &gt; Separador de miles]**. Nota: Los valores numéricos que utilizan una coma como separador decimal seguirán citados en el CSV exportado.</li><li>No se mostrarán símbolos de moneda.</li><li>No se mostrarán símbolos de porcentajes. Los porcentajes estarán en formato decimal. Por ejemplo, 75 % estará representado como 0,75.</li><li>El tiempo se mostrará en segundos.</li><li>Las tablas de cohorte muestran solo valores sin procesar; se eliminan los porcentajes.</li><li>Si un número no es válido, se mostrará una celda vacía.</li></ul> |
| Cambio en el comando de Debugger [!DNL Analysis Workspace] | 4 de abril de 2019 | El comando Console para activar el [!DNL Analysis Workspace] Debugger cambia a adobeTools.debug.includeOberonXml el **13 de junio de 2019**. adobe.tools.debug.includeOberonXml dejará de funcionar a partir de esa fecha. |
| Números de versión de los navegadores web | 7 de febrero de 2019 | A partir del 8 de enero de 2019, cambiamos el nivel de truncamiento para los números de versión de navegadores web de 2 a 1. A partir de esa fecha, las versiones solo mostrarán los dos primeros niveles (por ejemplo, _Firefox 64.0.2_ ahora aparece como _Firefox 64.0_). |
| Finalización del servicio de [!DNL Ad Hoc Analysis] | 29 de enero de 2019 | El 6 de agosto de 2018 Adobe anunció su intención de finalizar el servicio de [!DNL Ad Hoc Analysis]. La fecha se hará pública una vez que esté disponible.<br/>Para obtener más información, incluidas las versiones de Java compatibles durante este periodo, visite [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Vínculos breves a informes de Analytics | 14 de enero de 2019 | A partir del 17 de enero de 2019, todos los vínculos breves a informes de Analytics que no hayan recibido ninguna visita en el plazo de un año se limpiarán y eliminarán de forma gradual. |
| Finalización de la compatibilidad con TLS 1.0 | Actualizado el 10 de enero de 2019 | Desde el 11 de febrero de 2019, los informes de Adobe Analytics no son compatibles con el cifrado TLS (Transport Layer Security) 1.0. Este cambio forma parte de nuestros continuos esfuerzos por mantener los estándares de seguridad más elevados y fomentar la protección de los datos de nuestros clientes. Si no puede conectarse a los informes de Adobe Analytics después del 11 de febrero de 2019, debe actualizar el navegador a la versión [más reciente](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/> Desde el 20 febrero de 2019, la recopilación de datos de Adobe Analytics no es compatible con TLS 1.0. Este cambio significa que Adobe ya no recopila datos de Analytics de los usuarios finales que utilicen dispositivos antiguos o exploradores web incompatibles con TLS 1.1 o posteriores. No esperamos que esto tenga un impacto significativo en los datos de los clientes ni en los informes. (Si el sitio web ya no ofrece compatibilidad con TLS 1.0, usted no se verá afectado). <br/>A partir del 11 de abril de 2019, la API de informes de Adobe Analytics ya no será compatible con el cifrado TLS 1.0. Los clientes que acceden a la API deben verificar que no se verán afectados. <ul><li>Los clientes de API que utilicen Java 7 con la configuración predeterminada deberán realizar [ modificaciones para que sea compatible con TLS 1.2](https://www.java.com/en/configure_crypto.html). (Consulte _Cambio de la versión de protocolo TLS predeterminada para puntos finales del cliente: de TLS 1.0 a TLS 1.2_). </li><li>Los clientes de API que usen Java 8 no deberían tener problemas, ya que la configuración predeterminada es TLS 1.2.</li><li> Los clientes de API que usen otros módulos deben ponerse en contacto con su proveedor para obtener más información acerca de la compatibilidad con TLS 1.2.</li></ul> |
| Canal de datos: cambio de tamaño de la columna post_product_list | 9 de enero de 2019 | El 7 de febrero de 2019, Adobe aumentó el tamaño de la columna post_product_list de 64 KB a 16 MB. El objetivo de este cambio es garantizar que los valores eVar de comercialización añadidos a post_product_list durante el procesamiento no provoquen la solapación entre los valores de ingresos y el producto. Si tiene procesos que consumen valores de post_product_list, compruebe que dichos procesos puedan gestionar valores de hasta 16 MB de longitud; de lo contrario, el valor se truncará a los 16 KB para evitar fallos producidos por el consumo de datos. |
| Cambios de administración que afectan a los puntos de conexión de [!DNL Analytics Live Stream] inactivos | 20 de diciembre de 2018 | A partir del 1 de febrero de 2019, puede que se deshabiliten los puntos de conexión de [!DNL Live Stream] que no tengan conexiones activas de consumidores durante 90 días. Póngase en contacto con el Servicio de atención al cliente para consultar sobre sus puntos de conexión de [!DNL Live Stream] y, si es necesario, solicitar que los vuelvan a habilitar. Además, asegúrese de que los procesos de consumidores mantengan una conexión persistente, tal como se pretende desde el diseño del servicio, y que se implementen para reconectar cuando se desconecte o interrumpa la conexión. |
| Actualizar el [!DNL Report Builder] de Adobe debido al fin de la compatibilidad con TLS 1.0 | 7 de septiembre de 2018 | Debido al fin de la compatibilidad con TLS 1.0, recomendamos a los usuarios de [!DNL Report Builder] que descarguen ARB v5.6.21 antes de febrero de 2019. Después de esta fecha, las versiones anteriores de dejarán de [!DNL Report Builder] funcionar. |

## Audience Manager {#aam}

**Correcciones, mejoras y casos de finalización del soporte**

* Audience Manager solo cuenta los modelos algorítmicos activos con el límite de uso.
* Se ha resuelto un problema que hacía que el alcance del modelo algorítmico no se mostrara para características que usan el modelo correspondiente.
* Se ha resuelto un problema que provocaba que el contenido de las carpetas de características no se mostrara, y que los nombres de carpetas contenían paréntesis y/o corchetes.
* Se ha resuelto un problema que provocaba que fallara la ordenación de rasgos al seleccionar solo un tipo de características.
* Se ha resuelto un problema que provocaba que el árbol de carpetas de rasgos se contraiga a la vista [!UICONTROL Todas las características] cada vez que creaba o actualizaba una nueva subcarpeta.
* Se ha resuelto un problema que hacía que se necesitara [!DNL VIEW_DATASOURCES] el permiso al intentar eliminar un socio.
* Se ha resuelto un problema que hacía que [!UICONTROL el] cuadro Buscar de [!UICONTROL la] página Segmentos realizara búsquedas en todas las carpetas en lugar de en la seleccionada.
* Se ha resuelto un problema que impedía que la tabla [!UICONTROL Excluir características] se ordenara por los controles del encabezado al crear un nuevo modelo algorítmico.
* Se ha resuelto un problema que provocaba que Audience Manager se bloqueara al ejecutar cualquier informe con fechas de intervalo vacío.

## Experience Manager {#aem}

Funciones nuevas, correcciones y actualizaciones en Adobe Experience Manager (AEM). Adobe recomienda a los clientes con implementaciones locales implementar los parches más recientes para garantizar una mayor estabilidad, seguridad y rendimiento.

### Versiones de productos

**Cloud Manager 2019.5.0**

La versión más reciente de Cloud Manager (2019.5.0) no contiene cambios funcionales significativos aunque ofrece un par de correcciones de errores.

* [Notas de la versión para Cloud Manager 2019.5.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

**Documentación XML para AEM**

Ya está disponible la versión 3.3 para la solución Documentación XML. Consulte las siguientes notas de la versión:

***Funciones de mapa avanzado***
* Agregue referencias de tema mediante la función de arrastrar y soltar desde la vista del repositorio o utilizando la barra horizontal y el catálogo de elementos.
* Añada metadatos sobre un tema ref, fragmento, como título de navegación, formato, ámbito, etc.
* Al hacer clic en el tema ref se debería abrir el tema en el editor (modo de vista previa si no se extrae y se desactiva la edición con el cierre de compra).
* Agregar encabezado de tema y grupo de temas.
* Agregue bookmaps con Frontmatter (temas, prefacio, lista de libros, avisos, etc.) y Backmatter (temas, apéndices, glosario, etc.).
* En el modo Autor, se resaltan los vínculos rotos, se muestran las rutas y se encuentra disponible la Vista de etiquetas completas.
* Capacidad para establecer atributos del nivel de mapa.
* Capacidad para establecer Título/booktitle.
* Compatibilidad con Reltables con la capacidad de agregar encabezados rel, columnas, arrastrar o colocar temas del mapa y del repositorio a la tabla rel, definir vinculación, ámbito y otros parámetros para los vínculos, reordenar los vínculos dentro de la celda.
* Utilidad de barra de herramientas para insertar antes, insertar después e insertar elemento.
* Resalte si se aplica una condición en un tema.
* Capacidad para editar varios mapas a la vez (cada mapa se abre como una ficha en el mismo navegador).
* En el panel Mapa y la vista del repositorio, al pasar el ratón por encima, muestre el título completo del tema y el nombre de archivo.

***Vista de etiquetas completas***

* Inserte nuevas etiquetas entre dos elementos.
* Copiar y pegar etiquetas.
* Arrastre y suelte las etiquetas en las posiciones permitidas y no permitidas dentro de un archivo.
* Expandir y contraer etiquetas.

***Mejoras de búsqueda específica de DITA***

* Se proporciona una herramienta de serialización para reindexar el contenido seleccionado
* Los usuarios pueden utilizar `contains` y `exact match` en su búsqueda. También pueden buscar utilizando los parámetros siguientes. :
   * Metadatos de recursos. Por ejemplo, o `file name``title`cualquier metadato personalizado definido por el cliente.
   * Nombre de atributo DITA y su valor. Por ejemplo, `platform=winOS`.
   * Nombre de elemento DITA y su valor. Por ejemplo, `author = Joe Smith`.
   * Nombre de elemento DITA y su atributo aplicado. Por ejemplo, tabla con el par nombre/valor de atributo spacebase aplicado al mismo.
   * Tema DITA y metadatos de mapa.
   * Tipo de información DITA. Para el examen [ple, mapa, tema, concepto, etc.
   * Ruta de carpeta raíz en la que se encuentra el recurso.
   * Estado del documento.
   * Estado extraído.
   * Intervalo de fechas modificado.
   * Etiquetas CQ.
* Es posible crear consultas complejas combinando uno o más de los parámetros de búsqueda anteriores.

***Revise los cambios de funciones***

* Sugerencias para un revisor:
   * Importe todos los comentarios e incorpore los cambios para revisiones continuas antes de actualizar a la compilación 3.3.
   * Asegúrese de que no hay varias fichas abiertas para el editor.
   * Asegúrese de que la vista Etiquetas completas no está habilitada.
   * No cambie entre el modo Autor y el modo Origen mientras la revisión está en curso.
* Capacidad para especificar la versión de mi contenido que se va a revisar.
* Capacidad para elegir las versiones de los temas seleccionados en base a una línea base, fecha, etiqueta o la versión activa, o especificar las versiones para cada uno de los temas al crear una revisión.
* Capacidad para enviar el mismo tema o mapa para revisarlos varias veces y el autor puede acceder a todas las revisiones en el panel de revisión del editor.
* Como iniciador, puede insertar una versión posterior del contenido para los revisores. Los revisores recibirán una notificación cuando se inserte un nuevo contenido para su revisión.
* Como autor, el usuario podrá ver los comentarios de revisión de todas las versiones de su contenido en el panel de revisión del editor. Los autores podrán filtrar los comentarios por número de versión.
* Como usuario del autor, podrá ver e importar comentarios en una versión anterior del contenido en el editor que se estaba revisando.

***Varios***

* Cree una nueva carpeta, tema o mapa desde la vista Repositorio.
* Ver en la interfaz de usuario de recursos: agregue una opción de menú para carpetas y temas: «Ver en la interfaz de usuario de recursos». Esta opción abre la interfaz de usuario de recursos, donde el usuario puede ver el árbol de contenido a la izquierda y todos los archivos de la vista de lista de la derecha con todos los menús de recursos de la parte superior.
* Ahora, un tablero Revisar está disponible como mosaico en el proyecto DITA que rastrea la revisión en un nivel de revisor y en un nivel de tarea de revisión.
* Se agregó la capacidad de convertir IDML a DITA.
* Proporcionar API para aplicar una etiqueta dada en todas las versiones especificadas en una línea base.
* Habilite un evento después de que se complete la conversión XHTML/DOCX a DITA. Puede utilizar este suceso para agregar atributos especializados al contenido convertido o para cualquier otra lógica personalizada que necesite implementar.
* Se han realizado mejoras en la ficha Rendimiento de línea de base. El usuario debe ejecutar una secuencia de comandos en todas las líneas base existentes primero.
* Se han realizado mejoras en la conversión de XHTML a DITA.
* DITA-OT Offloading for Publishing Optimization.
* Se corrigió la ordenación en la columna Tipo en la vista de lista.
* Capacidad para administrar ahora estilos en cascada en Word a conversión DITA.

### Comunidad

**[Serie de seminarios web de Experience Builder para Experience Builder](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)**

¿Con qué le interesa aprender cómo los procesos devops pueden simplificar las actividades diarias de administración de Adobe Experience Manager en la nube? Cloud Manager proporciona la primera generación de funcionalidad nativa en la nube para Adobe Experience Manager que permite la agilidad en la nube, ya sea que su organización empiece su transformación de devops o busque estrategias para aumentar los procesos de devops existentes.

[En esta serie](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)mensual, puede aprender directamente del equipo de productos de Adobe acerca de cómo empezar y utilizar las funciones de Cloud Manager para simplificar la administración de Adobe Experience Manager en la nube.

Aprenderá lo siguiente:
* Cómo empezar a utilizar Cloud Manager y configurar la canalización de CI/CD
* Funcionamiento de escalado automático y de entrega de servicios transparentes y puede simplificar la administración de entornos de Adobe Experience Manager en la nube
* Cómo utilizar la API de Cloud Manager e integrar los procesos de devops existentes

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

### [!DNL Campaign Classic] Versión de primavera 19.1

| Funcionalidad | Descripción |
| ------------- | ----------- |
| Panel de control | Para aumentar la eficacia de su trabajo como usuario administrador, administre la configuración de los servidores SFTP mediante el monitoreo de almacenamiento, la lista blanca de direcciones IP e instale las claves SSH para cada instancia. Tenga en cuenta que el Panel de control solo está disponible para clientes alojados en AWS desde hoy. [Inicie sesión a través de Experience Cloud](https://experiencecloud.adobe.com/campaign/controlpanel/). <br> Para obtener más información, consulte la documentación [detallada](https://helpx.adobe.com/campaign/kb/control-panel.html) y el vídeo [de procedimientos](https://helpx.adobe.com/campaign/kt/acc/using/acc-control-panel-video-use.html). |
| Pista de auditoría | Como administrador, aumente la productividad monitoreando y administrando los cambios realizados en la instancia de Adobe Campaign Classic. La pista de auditoría registrará acciones realizadas en Esquema de origen, Flujo de trabajo y Opción. Rápidamente puede ver si un elemento se ha creado, modificado o eliminado.<br>Para obtener más información, consulte la documentación [detallada](https://docs.campaign.adobe.com/doc/AC/en/PRO_Production_procedures_Audit_trail.html) y el vídeo [de procedimientos](https://helpx.adobe.com/campaign/kt/acc/using/acc-audit-trail-feature-video-use.html). |
| Gardrail, Robustez y Escalabilidad | Se ha añadido una serie de mejoras [!DNL Campaign Classic]. Las mejoras en la escalabilidad, solidez y escalabilidad se enumeran en [las Notas de la versión de Adobe Campaign Classic](https://docs.campaign.adobe.com/doc/AC/en/RN.html). |
| Mensajería SMS segura (TLS) | SMS protegido ahora es compatible con el conector SMPP genérico ampliado. Esto permite una conexión cifrada al proveedor. <br> Para obtener más información, consulte la [ documentación detallada](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html). |
| Actualización de matriz de compatibilidad | Con esta nueva versión, Adobe Campaign ahora admite los sistemas de base de datos siguientes. Consulte la matriz [de compatibilidad](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html) <ul><li>Oracle 18 c</li><li>MySQL 5.7 (FDA)</li><li>SQL Server 2017</li><li>Teradata 16 (FDA)</li><li>Postgresql 11</li></ul> |

Consulte [las Notas de la versión de] Adobe Campaign Classic] (http://docs.campaign.adobe.com/doc/AC/en/RN.html) para ver correcciones y mejoras.

### [!DNL Campaign Standard] Versión de primavera 19.2

| Funcionalidad | Descripción |
| ------------- | ----------- |
| Panel de control | Para ayudar a aumentar la eficacia de su trabajo como usuario administrador, puede supervisar fácilmente la capacidad y administrar la configuración de las instancias (empezando por la administración de servidores SFTP). <br> Para obtener más información, consulte la documentación [detallada](https://helpx.adobe.com/campaign/kb/control-panel.html) y el vídeo [de procedimientos](https://helpx.adobe.com/campaign/kt/acs/using/acs-control-panel-video-use.html). |
| Notificaciones locales | Los mensajes de notificación local permiten informar a los usuarios cuando los nuevos datos están disponibles en sus aplicaciones móviles, incluso sin tener acceso a Internet o a la aplicación móvil que se ejecuta en primer plano. Las notificaciones locales se activan mediante una aplicación móvil en un momento concreto y según un evento.<br>Para obtener más información, consulte la [ documentación detallada](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type). |
| Mejora del flujo de trabajo: Adición de una carga útil a actividad de señal externa | Inicie un flujo de trabajo con una carga útil cuando las condiciones definidas se cumplan correctamente con otro flujo de trabajo o una llamada de API REST para integrarlos con los sistemas externos. Esto también incluye una nueva actividad de prueba en la que puede ejecutar pruebas en esta funcionalidad. <br>Para obtener más información, consulte la documentación [detallada](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type) y el vídeo [de procedimientos](https://helpx.adobe.com/campaign/kt/acs/using/acs-external-signal-activity-feature-video-use.html). |
| Mejora de páginas de aterrizaje: Google recaptcha | Aproveche Google recaptcha para evitar el correo deseado en las páginas de aterrizaje sin requerir ninguna acción de sus clientes. <br>Para obtener más información, consulte la [ documentación detallada](https://helpx.adobe.com/campaign/standard/channels/using/designing-a-landing-page.html#setting-google-recaptcha). |

Para obtener información del producto, consulte:

* Adobe Campaign Standard: [Documentación](https://helpx.adobe.com/support/campaign/standard.html) - [ Notas de la versión](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ Vídeos de presentación](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Documentación](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de la versión](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos de presentación](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Mobile Services {#mobile}

* TLS 1.0 se ha desactivado en todos los servidores de Adobe. Para dispositivos Android 4. x que conectarse a servicios de Adobe mediante SSL, el SDK forzará ahora TLS 1.1/TLS 1.2 al establecer un protocolo de enlace.

## Advertising Cloud {#adcloud}

Actualización: 5 de junio de 2019, para la versión del 8 de junio

| Producto | Función | Descripción |
| -----------| ---------- | ----------  |
| Buscar campañas, Clasificaciones de etiquetas y Restricciones | Métodos abreviados de teclado | Ahora puede utilizar <b>Mayús + clic</b> para seleccionar varias filas consecutivas y <b>Ctrl + clic</b> para seleccionar varias filas no consecutivas. |
|  | Seleccionar todos vs. Seleccionar todo en la página | En las tablas de datos, al seleccionar la casilla de verificación superior para seleccionar todas las filas, el nuevo valor predeterminado es seleccionar todas las filas de la página (en función de si está viendo 25 filas, 50 filas, 100 filas, 200 filas o Desplazamiento continuo). Aún tiene la opción de seleccionar todas las filas disponibles. |
| Vistas predeterminadas, vistas personalizadas y ajustes personalizados de personalización de columnas | Reorganización de columnas | Los botones Subir y Bajar permiten reordenar las columnas. Puede seguir arrastrando y soltando columnas para reordenarlas, como podía anteriormente. |

## Target Standard/Premium 19.6.1 (25 de junio de 2019) {#target}

Consulte las notas de la versión de Adobe Target para obtener la información más reciente sobre la versión:

[Notas de la versión de Target (versión prelanzamiento)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)

[Notas de la versión de Target (actual)](https://docs.adobe.com/content/help/en/target/using/release-notes/release-notes.html)

## Magento {#magento}

Magento es una plataforma de comercio electrónico que proporciona a los comerciantes en línea un sistema de compras flexible y, a la vez, permite controlar el aspecto, el contenido y la funcionalidad de su tienda en línea. Magento está disponible en una versión de código abierto y una versión de comercio con más funciones.

Magento Commerce forma parte de Adobe Commerce Cloud y ofrece una solución de comercio electrónico con potencia empresarial, adaptabilidad ilimitada y la flexibilidad del código abierto para las experiencias B2C y B2B.

Las notas de la versión de nuestras ediciones de código abierto y comercio se encuentran en la página [Información](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) de la versión.

## Primetime {#primetime}

Adobe Primetime es una plataforma de TV multipantalla que ayuda a las empresas de comunicación a crear y monetizar experiencias de visualización personalizadas y atractivas.

[Notas de la versión de Primetime](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Inicio de la Ayuda de Primetime](http://help.adobe.com/en_US/primetime/)
