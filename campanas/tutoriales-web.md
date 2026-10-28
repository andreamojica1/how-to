# Campañas — tutoriales web (afrus.ai/howto)

Un bloque por tutorial, listo para pegar. Orden: español, inglés, portugués.

## Español

```text
=== TUTORIAL ===
Idioma: es
Título: Qué es una campaña en AFRUS
Slug: que-es-una-campana
Categoría: Campañas
Resumen: Aprende qué es una campaña en AFRUS: el lugar donde agrupas las donaciones y registros de tus widgets bajo un objetivo de recaudación.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-sirve-una-campana, como-vincular-un-widget-con-una-campana, como-vincular-una-pagina-de-agradecimiento-a-una-campana, que-es-el-crowdfunding-widget, que-es-el-componente-donantes, como-usar-el-centro-de-costos-de-una-campana, como-usar-analytics-de-campanas, como-usar-kpi-merge-tags
--- CUERPO (HTML) ---
<p><strong>Una campaña agrupa las donaciones y los registros que entran por uno o varios widgets bajo un mismo objetivo de recaudación.</strong> Tiene un nombre interno, un nombre público, una descripción, una meta en la moneda de tu organización y un estado (activa o inactiva).</p>
<h2>Dónde la encuentras</h2>
<p>En <strong>Fundraising &gt; Campañas</strong>. Desde la lista puedes crear una campaña con "Crear campaña", buscarla por nombre y filtrarla por <strong>Estado</strong>, <strong>Tipo de Campaña</strong> y <strong>Total Recaudado</strong>. Para ver esta sección, tu rol necesita el permiso de ver campañas.</p>
<h2>Cómo crear una campaña</h2>
<ol>
<li><strong>Pulsa "Crear campaña".</strong> En <strong>Fundraising &gt; Campañas</strong>.</li>
<li><strong>Completa los datos.</strong> <strong>Nombre de campaña</strong> (hasta 100 caracteres), <strong>Descripción</strong> (hasta 500), <strong>Nombre público</strong> (hasta 100) y <strong>Meta de recaudación</strong>.</li>
<li><strong>Deja encendido Campaña activa</strong> para poder elegirla ya en tus widgets.</li>
<li><strong>Pulsa "Crear".</strong></li>
</ol>
<h2>Estados</h2>
<ul>
<li><strong>activo:</strong> se puede elegir en el editor de widgets.</li>
<li><strong>inactivo:</strong> la campaña está apagada.</li>
<li><strong>archivado:</strong> la campaña está archivada.</li>
</ul>
<h2>Preguntas frecuentes</h2>
<p><strong>¿La campaña puede tener otra moneda?</strong> No. La meta se guarda siempre en la moneda de tu organización.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Para qué sirve una campaña en AFRUS
Slug: para-que-sirve-una-campana
Categoría: Campañas
Resumen: Aprende para qué sirve una campaña: seguir tu meta, medir la conversión y la rentabilidad, y mostrar tu progreso en tu web.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-una-campana, como-vincular-un-widget-con-una-campana, como-usar-analytics-de-campanas, que-es-el-crowdfunding-widget
--- CUERPO (HTML) ---
<p>Con una campaña puedes:</p>
<ul>
<li><strong>Seguir tu meta.</strong> Ves cuánto lleva recaudado una iniciativa frente a su meta (<strong>Total recaudado</strong>, con barra de progreso).</li>
<li><strong>Medir la conversión de tus widgets.</strong> La <strong>Tasa de conversión</strong> compara donaciones y registros con las veces que se mostraron los widgets de la campaña.</li>
<li><strong>Usar una página de agradecimiento común</strong> para todos los widgets de la campaña que la usen.</li>
<li><strong>Medir la rentabilidad.</strong> Registras los costos y ves ROI, costo por transacción, costo por donante recurrente, Lifetime Value y más en el Dashboard de Analytics.</li>
<li><strong>Mostrar tu campaña en tu web</strong> con el <strong>Crowdfunding widget</strong> (progreso hacia la meta) y el <strong>Componente donantes</strong> (lista de personas que donaron).</li>
<li><strong>Contar el impacto en cifras</strong> con los <strong>KPI Merge Tags</strong>, que insertan cifras calculadas en correos automáticos o landings.</li>
</ul>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Qué hace "Seleccionar por defecto"?</strong> Marca la campaña por defecto de tu organización (solo puede haber una). A ella se asignan las transacciones que llegan de algunas pasarelas sin una campaña conocida, por ejemplo cobros de suscripciones creadas fuera de AFRUS.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo vincular un widget con una campaña
Slug: como-vincular-un-widget-con-una-campana
Categoría: Campañas
Resumen: Aprende a vincular un widget con una o varias campañas para que sus donaciones y registros cuenten en los resultados de la campaña.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-una-campana, como-vincular-una-pagina-de-agradecimiento-a-una-campana, para-que-sirve-una-campana
--- CUERPO (HTML) ---
<p>Al vincular un widget, sus donaciones y registros quedan asociados a la campaña y cuentan en sus resultados.</p>
<h2>Antes de empezar</h2>
<ul><li><strong>La campaña debe estar activa.</strong> El editor de widgets solo muestra campañas activas, por su nombre público.</li></ul>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre el widget.</strong> Entra a <strong>Fundraising &gt; Widgets</strong> y edita el widget. El editor se abre en una pestaña nueva.</li>
<li><strong>Elige la campaña.</strong> En el panel <strong>Renderización</strong>, en <strong>Elige tus campañas</strong>, selecciona una o varias campañas.</li>
<li><strong>Guarda los cambios del widget.</strong></li>
</ol>
<p>Al terminar, el widget aparece en la tabla <strong>Widgets de la campaña</strong> del detalle de la campaña. Si eliges más de una campaña, el donante verá un desplegable <strong>Elige tu campaña</strong> en el formulario, con la primera ya elegida.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Por qué no veo mi campaña en el editor?</strong> Porque está inactiva. Enciende <strong>Campaña activa</strong> en el detalle de la campaña.</p>
<p><strong>¿Se puede deshacer?</strong> Sí. Quita la campaña en <strong>Elige tus campañas</strong> y guarda.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo vincular una página de agradecimiento a una campaña
Slug: como-vincular-una-pagina-de-agradecimiento-a-una-campana
Categoría: Campañas
Resumen: Aprende a elegir una landing o experiencia como página de agradecimiento de tu campaña y a activarla en tus widgets.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-una-campana, como-vincular-un-widget-con-una-campana, para-que-sirve-una-campana
--- CUERPO (HTML) ---
<p>Así todos los widgets de la campaña pueden llevar al donante a la misma página después de donar. Son dos partes: elegir la página en la campaña y activarla en cada widget.</p>
<h2>Antes de empezar</h2>
<ul><li><strong>Ten creada la página</strong> como experiencia en <strong>Fundraising &gt; Experiences AI</strong> o como landing en <strong>Fundraising &gt; Landings</strong>.</li></ul>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre la campaña.</strong> En <strong>Fundraising &gt; Campañas</strong>, menú de tres puntos de la fila, <strong>Editar</strong>.</li>
<li><strong>Ve a la pestaña Página de agradecimiento.</strong></li>
<li><strong>Elige el tipo.</strong> En <strong>Tipo</strong>, elige <strong>Experiences</strong> o <strong>Landings</strong>.</li>
<li><strong>Elige la página</strong> en <strong>Elegir una experiencia</strong> o <strong>Elegir una landing</strong>. Verás una vista previa <strong>Mobile</strong>.</li>
<li><strong>Pulsa "Usar plantilla".</strong> No muestra confirmación: recarga la campaña y revisa que la pestaña muestre la página elegida.</li>
<li><strong>Abre cada widget</strong> en <strong>Fundraising &gt; Widgets</strong>.</li>
<li><strong>Activa la página de la campaña.</strong> En la sección <strong>Avanzado</strong>, apartado <strong>Página de agradecimiento</strong>, marca <strong>Usa la página de agradecimiento de la campaña.</strong> y guarda.</li>
</ol>
<p>Al terminar, después de donar, el donante llega a la página elegida en la campaña a la que se asoció su donación.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Qué pasa si la campaña no tiene página elegida?</strong> Se usa la página de agradecimiento normal del widget. Lo mismo si la página ya no existe.</p>
<p><strong>¿Se puede deshacer?</strong> Sí. Desmarca la casilla en el widget o elige otra página en la campaña.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Qué es el Crowdfunding widget y cómo configurarlo
Slug: que-es-el-crowdfunding-widget
Categoría: Campañas
Resumen: Aprende qué es el Crowdfunding widget y cómo mostrar en tu web el progreso de tu campaña hacia su meta, en vivo.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-una-campana, que-es-el-componente-donantes, para-que-sirve-una-campana
--- CUERPO (HTML) ---
<p><strong>El Crowdfunding widget es un bloque que pegas en cualquier web y que muestra en vivo el progreso de tu campaña hacia una meta:</strong> total alcanzado, meta, barra de avance, número de donaciones y, si pusiste fecha de cierre, cuántos días faltan o <em>"Campaña finalizada"</em>.</p>
<p>En <strong>Tipo de componente</strong> eliges qué medir: <strong>Meta de Recaudación</strong> (suma de donaciones exitosas), <strong>Meta de Suscriptores</strong> (suscripciones activas) o <strong>Meta de Registros</strong> (personas registradas, sin repetir). En <strong>Tipo de meta</strong> eliges <strong>Fija</strong> (escribes la meta, la moneda y la fecha y hora de cierre) o <strong>Dinámica</strong> (usa la meta de la campaña).</p>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre el configurador.</strong> En <strong>Fundraising &gt; Campañas</strong>, menú de tres puntos de la fila, <strong>Crowdfunding widget</strong>.</li>
<li><strong>Configura la meta</strong> en la pestaña <strong>Configuración</strong>.</li>
<li><strong>Ajusta el diseño</strong> en <strong>Estilos</strong>: <strong>Tipografía</strong>, <strong>Tamaño de tipografía</strong> y <strong>Color primario</strong>.</li>
<li><strong>Pulsa "Guardar".</strong> Cada guardado crea una versión nueva, que puedes elegir en <strong>Versiones</strong>.</li>
<li><strong>Pulsa "Copiar código de inserción"</strong> y pégalo en el HTML de tu sitio.</li>
</ol>
<h2>Preguntas frecuentes</h2>
<p><strong>Cambié el diseño y mi web no cambió, ¿por qué?</strong> La tipografía, el tamaño, el color y el idioma van dentro del código. Después de guardar, copia y pega el código de nuevo.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Qué es el Componente donantes y cómo configurarlo
Slug: que-es-el-componente-donantes
Categoría: Campañas
Resumen: Aprende qué es el Componente donantes y cómo mostrar en tu web la lista de personas que donaron a tu campaña.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-una-campana, que-es-el-crowdfunding-widget, para-que-sirve-una-campana
--- CUERPO (HTML) ---
<p><strong>El Componente donantes es un bloque para tu web que muestra la lista de personas que donaron a la campaña.</strong> Por defecto se titula <em>"Personas que también donaron"</em> y muestra nombre, apellido y monto de cada donación exitosa, de la más reciente a la más antigua. Si no hay donaciones, muestra <em>"No hay donantes disponibles"</em>.</p>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre el configurador.</strong> En <strong>Fundraising &gt; Campañas</strong>, menú de tres puntos de la fila, <strong>Componente donantes</strong>.</li>
<li><strong>Personalízalo.</strong> Configura <strong>Título</strong>, <strong>Tipografía</strong>, <strong>Color primario</strong>, el tema <strong>Light</strong> o <strong>Dark</strong> y el interruptor <strong>Activo</strong> / <strong>Inactivo</strong>. La vista previa usa nombres de ejemplo.</li>
<li><strong>Pulsa "Guardar"</strong> (o "Actualizar" si ya existía).</li>
<li><strong>Copia el código de inserción</strong> y pégalo en tu web.</li>
</ol>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Puedo ocultar nombres o montos?</strong> No. El bloque publica nombre, apellido y monto de cada donante; asegúrate de que tu organización puede publicar esa información.</p>
<p><strong>¿Tengo que volver a copiar el código si cambio algo?</strong> Solo si cambias la tipografía o el color. El título, el tema y Activo / Inactivo se aplican sin tocar tu web.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Para qué sirve y cómo se usa el centro de costos de una campaña
Slug: como-usar-el-centro-de-costos-de-una-campana
Categoría: Campañas
Resumen: Aprende a registrar los costos de tu campaña en la pestaña Costos para medir su rentabilidad y activar el Dashboard de Analytics.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-una-campana, como-usar-analytics-de-campanas, como-usar-kpi-merge-tags
--- CUERPO (HTML) ---
<p>El centro de costos es la pestaña <strong>Costos</strong> de la campaña. Sirve para saber cuánto invertiste, para que AFRUS calcule indicadores como Resultado, ROI o costo por transacción, y para activar el Dashboard de Analytics: "Ver Analytics" solo se habilita cuando hay al menos un costo.</p>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre la campaña</strong> y ve a la pestaña <strong>Costos</strong>.</li>
<li><strong>Pulsa "Agregar costo".</strong></li>
<li><strong>Completa los datos.</strong> <strong>Costo</strong> (mayor que 0), <strong>Tipo</strong> (<strong>Publicidad (working media)</strong> o <strong>Costos de apoyo y producción</strong>), <strong>Fecha de gasto</strong>, <strong>Widget</strong> (opcional) y <strong>Nota</strong> (opcional, hasta 1000 caracteres).</li>
<li><strong>Pulsa "Agregar".</strong></li>
</ol>
<p>El costo aparece en <strong>Lista de costos</strong> y suma en el <strong>Total</strong>, que puedes filtrar por fechas. Un costo asignado a un widget cuenta en la analítica de ese widget; uno sin widget, solo en la de la campaña completa.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Puedo registrar decimales?</strong> El valor se guarda sin decimales, así que registra montos redondeados. Los costos van siempre en la moneda de tu organización.</p>
<p><strong>¿Se puede deshacer?</strong> Puedes editar un costo. Eliminarlo pide confirmación y no se puede deshacer.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Analytics de campañas: qué datos obtienes y cómo analizarlos
Slug: como-usar-analytics-de-campanas
Categoría: Campañas
Resumen: Aprende a activar el Analytics de tu campaña, qué indicadores muestra y cómo leerlos para saber si tu campaña es rentable.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-una-campana, como-usar-el-centro-de-costos-de-una-campana, para-que-sirve-una-campana
--- CUERPO (HTML) ---
<h2>Cómo se activa</h2>
<p>Registra al menos un costo en la pestaña <strong>Costos</strong> de la campaña. Hasta entonces, "Ver Analytics" está deshabilitado.</p>
<h2>Paso a paso</h2>
<ol>
<li><strong>Pulsa "Ver Analytics"</strong> en el detalle de la campaña.</li>
<li><strong>Elige el periodo</strong> en la pestaña <strong>Resumen</strong> (por defecto, todo el historial). Las tarjetas se recalculan para ese rango.</li>
<li><strong>Descarga los indicadores</strong> con "Descargar KPIs" si los quieres en CSV.</li>
<li><strong>Abre un widget</strong> en <strong>Rendimiento por Widget</strong> para ver sus indicadores y sus costos.</li>
<li><strong>Mira la evolución</strong> en la pestaña <strong>Tendencias</strong> (por defecto, el mes en curso).</li>
</ol>
<h2>Qué datos obtienes</h2>
<ul>
<li><strong>Rentabilidad:</strong> Ingresos Totales, Costos, Resultado, ROI, Inversión y Punto de Equilibrio.</li>
<li><strong>Costo de adquisición:</strong> CPT (costo por transacción) y CPR (costo por donante recurrente), brutos y netos.</li>
<li><strong>Recurrencia:</strong> MRR y ARR adquiridos, RCR, Tasa de Calidad, Tasa de Abandono, Vida del Donante, Lifetime Value, AMV y Eficiencia de Adquisición.</li>
<li><strong>Tablas Histórico:</strong> rendimiento por widget, UTM Source, UTM Medium, UTM Campaign y URL.</li>
</ul>
<h2>Cómo analizarlos</h2>
<ul>
<li><strong>¿Es rentable?</strong> Mira Resultado y ROI; si hay pérdida, Punto de Equilibrio dice en cuántos meses se recupera.</li>
<li><strong>¿Captas bien?</strong> Si Eficiencia de Adquisición (LTV / CPR) es mayor que 1, cada donante recurrente vale más de lo que cuesta conseguirlo.</li>
<li><strong>¿Dónde invertir?</strong> Las tablas por widget, UTM y URL muestran qué canales traen más ingresos.</li>
</ul>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Los datos son en vivo?</strong> Las tarjetas del Resumen, sí. Las tablas Histórico y la pestaña Tendencias se actualizan una vez al día, así que lo de hoy puede aparecer mañana. Además, las tablas Histórico muestran el total de siempre y no respetan el rango de fechas.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Para qué sirven y cómo se usan los KPI Merge Tags
Slug: como-usar-kpi-merge-tags
Categoría: Campañas
Resumen: Aprende a crear KPI Merge Tags para mostrar cifras de impacto calculadas en tus correos automáticos y en tus landings.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-una-campana, como-usar-el-centro-de-costos-de-una-campana, como-usar-analytics-de-campanas
--- CUERPO (HTML) ---
<p><strong>Los KPI Merge Tags son cifras calculadas con una fórmula que insertas en correos automáticos o landings,</strong> por ejemplo para convertir el monto de una donación en "comidas donadas". Se crean en la pestaña <strong>KPI Merge Tag</strong> de la campaña.</p>
<ul>
<li><strong>KPI Transaccional:</strong> para correos automáticos (<strong>Interacciones &gt; Autoresponders</strong>). Calcula con el <strong>Monto</strong> de la donación que dispara el correo.</li>
<li><strong>KPI Global:</strong> para landings. Calcula con el <strong>Total Recaudado</strong> y la <strong>Cantidad de Donantes</strong> de la campaña.</li>
</ul>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre la pestaña.</strong> En la campaña, <strong>KPI Merge Tag</strong>, apartado <strong>KPI Transaccional</strong> (o <strong>KPI Global</strong>), y pulsa "Agregar KPI Merge Tag" (o "Agregar KPI global").</li>
<li><strong>Ponle nombre.</strong> Escribe <strong>Nombre del KPI</strong>; en <strong>Variable generada</strong> verás la etiqueta. Para KPI Global, usa solo letras sin tilde, números y espacios.</li>
<li><strong>Arma la fórmula</strong> en <strong>Constructor de Fórmula</strong>, alternando "Agregar Variable" y "Agregar Operador". Con "Agregar Variable Multiplicador" creas una constante. La fórmula debe terminar en una variable.</li>
<li><strong>Pulsa "Crear".</strong></li>
<li><strong>Usa la etiqueta.</strong> En un correo automático: <em>{{kpi_88_comidas_donadas}}</em>. En una landing, entre corchetes: <em>[global_kpi_88_comidas_donadas]</em> (88 es el ID de la campaña).</li>
</ol>
<h2>Preguntas frecuentes</h2>
<p><strong>¿En qué orden se calcula la fórmula?</strong> En el KPI Transaccional, la multiplicación y la división van primero. En el KPI Global, las operaciones se aplican de izquierda a derecha.</p>
<p><strong>¿Puedo eliminar un KPI Merge Tag?</strong> No. Puedes editarlo, pero no hay botón para eliminarlo.</p>
=== FIN ===
```

## English

```text
=== TUTORIAL ===
Idioma: en
Título: What a campaign is in AFRUS
Slug: what-is-a-campaign
Categoría: Campaigns
Resumen: Learn what a campaign is in AFRUS: where you group your widgets' donations and registrations under one fundraising goal.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-campaign-for, how-to-link-a-widget-to-a-campaign, how-to-link-a-thank-you-page-to-a-campaign, what-is-the-crowdfunding-widget, what-is-the-donors-component, how-to-use-the-campaign-cost-center, how-to-use-campaign-analytics, how-to-use-kpi-merge-tags
--- CUERPO (HTML) ---
<p><strong>A campaign groups the donations and registrations that come in through one or more widgets under a single fundraising goal.</strong> It has an internal name, a public name, a description, a goal in your organization's currency and a status (active or inactive). Labels are shown as they appear in the Spanish version of the console.</p>
<h2>Where to find it</h2>
<p>In <strong>Fundraising &gt; Campañas</strong>. From the list you can create a campaign with "Crear campaña" (Create campaign), search by name and filter by <strong>Estado</strong> (Status), <strong>Tipo de Campaña</strong> (Campaign type) and <strong>Total Recaudado</strong> (Total raised). Your role needs the permission to view campaigns.</p>
<h2>How to create a campaign</h2>
<ol>
<li><strong>Click "Crear campaña".</strong> In <strong>Fundraising &gt; Campañas</strong>.</li>
<li><strong>Fill in the details.</strong> <strong>Nombre de campaña</strong> (name, up to 100 characters), <strong>Descripción</strong> (up to 500), <strong>Nombre público</strong> (public name, up to 100) and <strong>Meta de recaudación</strong> (fundraising goal).</li>
<li><strong>Leave Campaña activa (Active campaign) on</strong> so you can choose it in your widgets right away.</li>
<li><strong>Click "Crear" (Create).</strong></li>
</ol>
<h2>Statuses</h2>
<ul>
<li><strong>activo</strong> (active): it can be chosen in the widget editor.</li>
<li><strong>inactivo</strong> (inactive): the campaign is off.</li>
<li><strong>archivado</strong> (archived): the campaign is archived.</li>
</ul>
<h2>Frequently asked questions</h2>
<p><strong>Can a campaign have another currency?</strong> No. The goal is always saved in your organization's currency.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: What a campaign is for in AFRUS
Slug: what-is-a-campaign-for
Categoría: Campaigns
Resumen: Learn what a campaign is for: tracking your goal, measuring conversion and return, and showing your progress on your website.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-campaign, how-to-link-a-widget-to-a-campaign, how-to-use-campaign-analytics, what-is-the-crowdfunding-widget
--- CUERPO (HTML) ---
<p>With a campaign you can:</p>
<ul>
<li><strong>Track your goal.</strong> See how much an initiative has raised against its goal (<strong>Total recaudado</strong>, with a progress bar).</li>
<li><strong>Measure your widgets' conversion.</strong> The <strong>Tasa de conversión</strong> (Conversion rate) compares donations and registrations with the number of times the campaign's widgets were shown.</li>
<li><strong>Use a shared thank-you page</strong> for every campaign widget that uses it.</li>
<li><strong>Measure return.</strong> Record costs and see ROI, cost per transaction, cost per recurring donor, Lifetime Value and more in the Analytics dashboard.</li>
<li><strong>Show your campaign on your website</strong> with the <strong>Crowdfunding widget</strong> (progress towards the goal) and the <strong>Componente donantes</strong> (Donors component, list of people who donated).</li>
<li><strong>Tell your impact in numbers</strong> with <strong>KPI Merge Tags</strong>, which insert calculated figures into automated emails or landings.</li>
</ul>
<h2>Frequently asked questions</h2>
<p><strong>What does "Seleccionar por defecto" (Set as default) do?</strong> It marks your organization's default campaign (there can only be one). Transactions that arrive from some payment gateways without a known campaign are assigned to it, for example charges from subscriptions created outside AFRUS.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to link a widget to a campaign
Slug: how-to-link-a-widget-to-a-campaign
Categoría: Campaigns
Resumen: Learn how to link a widget to one or more campaigns so its donations and registrations count in the campaign's results.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-campaign, how-to-link-a-thank-you-page-to-a-campaign, what-is-a-campaign-for
--- CUERPO (HTML) ---
<p>When you link a widget, its donations and registrations are associated with the campaign and count in its results. Labels are shown as they appear in the Spanish version of the console.</p>
<h2>Before you start</h2>
<ul><li><strong>The campaign must be active.</strong> The widget editor only lists active campaigns, by their public name.</li></ul>
<h2>Step by step</h2>
<ol>
<li><strong>Open the widget.</strong> Go to <strong>Fundraising &gt; Widgets</strong> and edit the widget. The editor opens in a new tab.</li>
<li><strong>Choose the campaign.</strong> In the <strong>Renderización</strong> (Rendering) panel, in <strong>Elige tus campañas</strong> (Choose your campaigns), select one or more campaigns.</li>
<li><strong>Save the widget changes.</strong></li>
</ol>
<p>When you finish, the widget appears in the <strong>Widgets de la campaña</strong> (Campaign widgets) table in the campaign detail. If you choose more than one campaign, donors see an <strong>Elige tu campaña</strong> (Choose your campaign) drop-down in the form, with the first one preselected.</p>
<h2>Frequently asked questions</h2>
<p><strong>Why don't I see my campaign in the editor?</strong> Because it is inactive. Turn on <strong>Campaña activa</strong> in the campaign detail.</p>
<p><strong>Can it be undone?</strong> Yes. Remove the campaign in <strong>Elige tus campañas</strong> and save.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to link a thank-you page to a campaign
Slug: how-to-link-a-thank-you-page-to-a-campaign
Categoría: Campaigns
Resumen: Learn how to choose a landing or experience as your campaign's thank-you page and turn it on in your widgets.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-campaign, how-to-link-a-widget-to-a-campaign, what-is-a-campaign-for
--- CUERPO (HTML) ---
<p>This way every widget in the campaign can take the donor to the same page after donating. There are two parts: choosing the page in the campaign and turning it on in each widget. Labels are shown as they appear in the Spanish version of the console.</p>
<h2>Before you start</h2>
<ul><li><strong>Have the page created</strong> as an experience in <strong>Fundraising &gt; Experiences AI</strong> or as a landing in <strong>Fundraising &gt; Landings</strong>.</li></ul>
<h2>Step by step</h2>
<ol>
<li><strong>Open the campaign.</strong> In <strong>Fundraising &gt; Campañas</strong>, row's three-dot menu, <strong>Editar</strong> (Edit).</li>
<li><strong>Go to the Página de agradecimiento (Thank-you page) tab.</strong></li>
<li><strong>Choose the type.</strong> In <strong>Tipo</strong>, choose <strong>Experiences</strong> or <strong>Landings</strong>.</li>
<li><strong>Choose the page</strong> in <strong>Elegir una experiencia</strong> or <strong>Elegir una landing</strong>. You will see a <strong>Mobile</strong> preview.</li>
<li><strong>Click "Usar plantilla" (Use template).</strong> It shows no confirmation: reload the campaign and check the tab shows the chosen page.</li>
<li><strong>Open each widget</strong> in <strong>Fundraising &gt; Widgets</strong>.</li>
<li><strong>Turn on the campaign's page.</strong> In the <strong>Avanzado</strong> (Advanced) section, <strong>Página de agradecimiento</strong> area, tick <strong>Usa la página de agradecimiento de la campaña.</strong> (Use the campaign's thank-you page) and save.</li>
</ol>
<p>When you finish, after donating, the donor lands on the page chosen in the campaign their donation was associated with.</p>
<h2>Frequently asked questions</h2>
<p><strong>What if the campaign has no page chosen?</strong> The widget's normal thank-you page is used. The same happens if the page no longer exists.</p>
<p><strong>Can it be undone?</strong> Yes. Untick the box in the widget or choose another page in the campaign.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: What the Crowdfunding widget is and how to set it up
Slug: what-is-the-crowdfunding-widget
Categoría: Campaigns
Resumen: Learn what the Crowdfunding widget is and how to show your campaign's live progress towards its goal on your website.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-campaign, what-is-the-donors-component, what-is-a-campaign-for
--- CUERPO (HTML) ---
<p><strong>The Crowdfunding widget is a block you paste into any website that shows your campaign's progress towards a goal, live:</strong> total reached, goal, progress bar, number of donations and, if you set an end date, days left or <em>"Campaña finalizada"</em> (Campaign ended). Labels are shown as they appear in the Spanish version of the console.</p>
<p>In <strong>Tipo de componente</strong> (Component type) you choose what to track: <strong>Meta de Recaudación</strong> (sum of successful donations), <strong>Meta de Suscriptores</strong> (active subscriptions) or <strong>Meta de Registros</strong> (registered people, without duplicates). In <strong>Tipo de meta</strong> (Goal type) you choose <strong>Fija</strong> (Fixed: you type the goal, currency and end date and time) or <strong>Dinámica</strong> (Dynamic: it uses the campaign's goal).</p>
<h2>Step by step</h2>
<ol>
<li><strong>Open the configurator.</strong> In <strong>Fundraising &gt; Campañas</strong>, row's three-dot menu, <strong>Crowdfunding widget</strong>.</li>
<li><strong>Set the goal</strong> in the <strong>Configuración</strong> (Settings) tab.</li>
<li><strong>Adjust the design</strong> in <strong>Estilos</strong> (Styles): <strong>Tipografía</strong> (font), <strong>Tamaño de tipografía</strong> (font size) and <strong>Color primario</strong> (primary color).</li>
<li><strong>Click "Guardar" (Save).</strong> Each save creates a new version, which you can choose in <strong>Versiones</strong>.</li>
<li><strong>Click "Copiar código de inserción" (Copy embed code)</strong> and paste it into your site's HTML.</li>
</ol>
<h2>Frequently asked questions</h2>
<p><strong>I changed the design and my website didn't change. Why?</strong> Font, size, color and language are inside the code. After saving, copy and paste the code again.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: What the Donors component is and how to set it up
Slug: what-is-the-donors-component
Categoría: Campaigns
Resumen: Learn what the Donors component is and how to show on your website the list of people who donated to your campaign.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-campaign, what-is-the-crowdfunding-widget, what-is-a-campaign-for
--- CUERPO (HTML) ---
<p><strong>The Componente donantes (Donors component) is a block for your website that shows the list of people who donated to the campaign.</strong> By default it is titled <em>"Personas que también donaron"</em> (People who also donated) and shows the first name, last name and amount of each successful donation, newest first. If there are no donations, it shows <em>"No hay donantes disponibles"</em> (No donors available). Labels are shown as they appear in the Spanish version of the console.</p>
<h2>Step by step</h2>
<ol>
<li><strong>Open the configurator.</strong> In <strong>Fundraising &gt; Campañas</strong>, row's three-dot menu, <strong>Componente donantes</strong>.</li>
<li><strong>Customize it.</strong> Set <strong>Título</strong> (Title), <strong>Tipografía</strong> (Font), <strong>Color primario</strong> (Primary color), the <strong>Light</strong> or <strong>Dark</strong> theme and the <strong>Activo</strong> / <strong>Inactivo</strong> (Active / Inactive) switch. The preview uses sample names.</li>
<li><strong>Click "Guardar" (Save)</strong> (or "Actualizar" — Update — if it already existed).</li>
<li><strong>Copy the embed code</strong> and paste it into your website.</li>
</ol>
<h2>Frequently asked questions</h2>
<p><strong>Can I hide names or amounts?</strong> No. The block publishes each donor's first name, last name and amount; make sure your organization can publish that information.</p>
<p><strong>Do I need to copy the code again if I change something?</strong> Only if you change the font or color. Title, theme and Active / Inactive apply without touching your website.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: What a campaign's cost center is for and how to use it
Slug: how-to-use-the-campaign-cost-center
Categoría: Campaigns
Resumen: Learn how to record your campaign's costs in the Costs tab to measure its return and turn on the Analytics dashboard.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-campaign, how-to-use-campaign-analytics, how-to-use-kpi-merge-tags
--- CUERPO (HTML) ---
<p>The cost center is the campaign's <strong>Costos</strong> (Costs) tab. It tells you how much you invested, lets AFRUS calculate indicators such as Result, ROI or cost per transaction, and turns on the Analytics dashboard: "Ver Analytics" (View Analytics) is only enabled once there is at least one cost. Labels are shown as they appear in the Spanish version of the console.</p>
<h2>Step by step</h2>
<ol>
<li><strong>Open the campaign</strong> and go to the <strong>Costos</strong> tab.</li>
<li><strong>Click "Agregar costo" (Add cost).</strong></li>
<li><strong>Fill in the details.</strong> <strong>Costo</strong> (Cost, greater than 0), <strong>Tipo</strong> (Type: <strong>Publicidad (working media)</strong> or <strong>Costos de apoyo y producción</strong> — support and production costs), <strong>Fecha de gasto</strong> (expense date), <strong>Widget</strong> (optional) and <strong>Nota</strong> (note, optional, up to 1000 characters).</li>
<li><strong>Click "Agregar" (Add).</strong></li>
</ol>
<p>The cost appears in <strong>Lista de costos</strong> (Cost list) and adds to the <strong>Total</strong>, which you can filter by date. A cost assigned to a widget counts in that widget's analytics; one without a widget only counts in the whole campaign's analytics.</p>
<h2>Frequently asked questions</h2>
<p><strong>Can I record decimals?</strong> The value is saved without decimals, so record rounded amounts. Costs are always in your organization's currency.</p>
<p><strong>Can it be undone?</strong> You can edit a cost. Deleting it asks for confirmation and cannot be undone.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: Campaign Analytics: what data you get and how to analyze it
Slug: how-to-use-campaign-analytics
Categoría: Campaigns
Resumen: Learn how to turn on your campaign's Analytics, which indicators it shows and how to read them to know if your campaign pays off.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-campaign, how-to-use-the-campaign-cost-center, what-is-a-campaign-for
--- CUERPO (HTML) ---
<h2>How to turn it on</h2>
<p>Record at least one cost in the campaign's <strong>Costos</strong> (Costs) tab. Until then, "Ver Analytics" (View Analytics) is disabled. Labels are shown as they appear in the Spanish version of the console.</p>
<h2>Step by step</h2>
<ol>
<li><strong>Click "Ver Analytics"</strong> in the campaign detail.</li>
<li><strong>Choose the period</strong> in the <strong>Resumen</strong> (Summary) tab (by default, all history). The cards recalculate for that range.</li>
<li><strong>Download the indicators</strong> with "Descargar KPIs" (Download KPIs) if you want them as CSV.</li>
<li><strong>Open a widget</strong> in <strong>Rendimiento por Widget</strong> (Performance by widget) to see its indicators and costs.</li>
<li><strong>See the trend</strong> in the <strong>Tendencias</strong> (Trends) tab (by default, the current month).</li>
</ol>
<h2>What data you get</h2>
<ul>
<li><strong>Return:</strong> total income, costs, result, ROI, investment and break-even.</li>
<li><strong>Acquisition cost:</strong> CPT (cost per transaction) and CPR (cost per recurring donor), gross and net.</li>
<li><strong>Recurring giving:</strong> acquired MRR and ARR, RCR, quality rate, churn rate, donor lifetime, Lifetime Value, AMV and acquisition efficiency.</li>
<li><strong>Histórico (Historical) tables:</strong> performance by widget, UTM Source, UTM Medium, UTM Campaign and URL.</li>
</ul>
<h2>How to analyze them</h2>
<ul>
<li><strong>Is it profitable?</strong> Look at result and ROI; if there is a loss, break-even tells you in how many months it is recovered.</li>
<li><strong>Are you acquiring well?</strong> If acquisition efficiency (LTV / CPR) is greater than 1, each recurring donor is worth more than it costs to get them.</li>
<li><strong>Where to invest?</strong> The widget, UTM and URL tables show which channels bring in the most income.</li>
</ul>
<h2>Frequently asked questions</h2>
<p><strong>Is the data live?</strong> The Resumen cards are. The Histórico tables and the Tendencias tab update once a day, so today's activity may show tomorrow. The Histórico tables also show the all-time total and ignore the date range.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: What KPI Merge Tags are for and how to use them
Slug: how-to-use-kpi-merge-tags
Categoría: Campaigns
Resumen: Learn how to create KPI Merge Tags to show calculated impact figures in your automated emails and landings.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-campaign, how-to-use-the-campaign-cost-center, how-to-use-campaign-analytics
--- CUERPO (HTML) ---
<p><strong>KPI Merge Tags are figures calculated with a formula that you insert into automated emails or landings,</strong> for example to turn a donation amount into "meals donated". You create them in the campaign's <strong>KPI Merge Tag</strong> tab. Labels are shown as they appear in the Spanish version of the console.</p>
<ul>
<li><strong>KPI Transaccional</strong> (Transactional KPI): for automated emails (<strong>Interacciones &gt; Autoresponders</strong>). It calculates with the <strong>Monto</strong> (Amount) of the donation that triggers the email.</li>
<li><strong>KPI Global:</strong> for landings. It calculates with the campaign's <strong>Total Recaudado</strong> (Total raised) and <strong>Cantidad de Donantes</strong> (Number of donors).</li>
</ul>
<h2>Step by step</h2>
<ol>
<li><strong>Open the tab.</strong> In the campaign, <strong>KPI Merge Tag</strong>, section <strong>KPI Transaccional</strong> (or <strong>KPI Global</strong>), and click "Agregar KPI Merge Tag" (or "Agregar KPI global").</li>
<li><strong>Name it.</strong> Type <strong>Nombre del KPI</strong> (KPI name); <strong>Variable generada</strong> (Generated variable) shows the tag. For a Global KPI, use only unaccented letters, numbers and spaces.</li>
<li><strong>Build the formula</strong> in <strong>Constructor de Fórmula</strong> (Formula builder), alternating "Agregar Variable" (Add variable) and "Agregar Operador" (Add operator). "Agregar Variable Multiplicador" creates a constant. The formula must end with a variable.</li>
<li><strong>Click "Crear" (Create).</strong></li>
<li><strong>Use the tag.</strong> In an automated email: <em>{{kpi_88_comidas_donadas}}</em>. In a landing, in square brackets: <em>[global_kpi_88_comidas_donadas]</em> (88 is the campaign ID).</li>
</ol>
<h2>Frequently asked questions</h2>
<p><strong>In what order is the formula calculated?</strong> In a Transactional KPI, multiplication and division go first. In a Global KPI, operations are applied left to right.</p>
<p><strong>Can I delete a KPI Merge Tag?</strong> No. You can edit it, but there is no button to delete it.</p>
=== FIN ===
```

## Português

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: O que é uma campanha na AFRUS
Slug: o-que-e-uma-campanha
Categoría: Campanhas
Resumen: Aprenda o que é uma campanha na AFRUS: onde você agrupa as doações e cadastros dos seus widgets sob um objetivo de captação.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-serve-uma-campanha, como-vincular-um-widget-a-uma-campanha, como-vincular-uma-pagina-de-agradecimento-a-uma-campanha, o-que-e-o-crowdfunding-widget, o-que-e-o-componente-de-doadores, como-usar-o-centro-de-custos-da-campanha, como-usar-o-analytics-de-campanhas, como-usar-kpi-merge-tags
--- CUERPO (HTML) ---
<p><strong>Uma campanha agrupa as doações e os cadastros que chegam por um ou vários widgets sob um mesmo objetivo de captação.</strong> Ela tem um nome interno, um nome público, uma descrição, uma meta na moeda da sua organização e um status (ativa ou inativa). Os nomes de tela aparecem como na versão em espanhol do console.</p>
<h2>Onde encontrar</h2>
<p>Em <strong>Fundraising &gt; Campañas</strong>. Na lista, você pode criar uma campanha com "Crear campaña" (Criar campanha), buscar pelo nome e filtrar por <strong>Estado</strong> (Status), <strong>Tipo de Campaña</strong> e <strong>Total Recaudado</strong> (Total arrecadado). Seu perfil precisa da permissão de ver campanhas.</p>
<h2>Como criar uma campanha</h2>
<ol>
<li><strong>Clique em "Crear campaña".</strong> Em <strong>Fundraising &gt; Campañas</strong>.</li>
<li><strong>Preencha os dados.</strong> <strong>Nombre de campaña</strong> (nome, até 100 caracteres), <strong>Descripción</strong> (até 500), <strong>Nombre público</strong> (nome público, até 100) e <strong>Meta de recaudación</strong> (meta de captação).</li>
<li><strong>Deixe Campaña activa (Campanha ativa) ligado</strong> para poder escolhê-la já nos seus widgets.</li>
<li><strong>Clique em "Crear" (Criar).</strong></li>
</ol>
<h2>Status</h2>
<ul>
<li><strong>activo</strong> (ativo): pode ser escolhida no editor de widgets.</li>
<li><strong>inactivo</strong> (inativo): a campanha está desligada.</li>
<li><strong>archivado</strong> (arquivado): a campanha está arquivada.</li>
</ul>
<h2>Perguntas frequentes</h2>
<p><strong>A campanha pode ter outra moeda?</strong> Não. A meta é sempre salva na moeda da sua organização.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Para que serve uma campanha na AFRUS
Slug: para-que-serve-uma-campanha
Categoría: Campanhas
Resumen: Aprenda para que serve uma campanha: acompanhar sua meta, medir conversão e retorno e mostrar seu progresso no seu site.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-uma-campanha, como-vincular-um-widget-a-uma-campanha, como-usar-o-analytics-de-campanhas, o-que-e-o-crowdfunding-widget
--- CUERPO (HTML) ---
<p>Com uma campanha você pode:</p>
<ul>
<li><strong>Acompanhar sua meta.</strong> Veja quanto uma iniciativa já arrecadou em relação à meta (<strong>Total recaudado</strong>, com barra de progresso).</li>
<li><strong>Medir a conversão dos seus widgets.</strong> A <strong>Tasa de conversión</strong> (Taxa de conversão) compara doações e cadastros com o número de vezes que os widgets da campanha foram exibidos.</li>
<li><strong>Usar uma página de agradecimento comum</strong> para todos os widgets da campanha que a utilizem.</li>
<li><strong>Medir o retorno.</strong> Registre os custos e veja ROI, custo por transação, custo por doador recorrente, Lifetime Value e mais no painel de Analytics.</li>
<li><strong>Mostrar sua campanha no seu site</strong> com o <strong>Crowdfunding widget</strong> (progresso até a meta) e o <strong>Componente donantes</strong> (Componente de doadores, lista de pessoas que doaram).</li>
<li><strong>Contar o impacto em números</strong> com os <strong>KPI Merge Tags</strong>, que inserem números calculados em e-mails automáticos ou landings.</li>
</ul>
<h2>Perguntas frequentes</h2>
<p><strong>O que faz "Seleccionar por defecto" (Definir como padrão)?</strong> Marca a campanha padrão da sua organização (só pode haver uma). A ela são atribuídas as transações que chegam de alguns gateways de pagamento sem uma campanha conhecida, por exemplo cobranças de assinaturas criadas fora da AFRUS.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como vincular um widget a uma campanha
Slug: como-vincular-um-widget-a-uma-campanha
Categoría: Campanhas
Resumen: Aprenda a vincular um widget a uma ou várias campanhas para que as doações e cadastros dele contem nos resultados da campanha.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-uma-campanha, como-vincular-uma-pagina-de-agradecimento-a-uma-campanha, para-que-serve-uma-campanha
--- CUERPO (HTML) ---
<p>Ao vincular um widget, as doações e os cadastros feitos nele ficam associados à campanha e contam nos resultados dela. Os nomes de tela aparecem como na versão em espanhol do console.</p>
<h2>Antes de começar</h2>
<ul><li><strong>A campanha precisa estar ativa.</strong> O editor de widgets só mostra campanhas ativas, pelo nome público.</li></ul>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra o widget.</strong> Acesse <strong>Fundraising &gt; Widgets</strong> e edite o widget. O editor abre em uma nova aba.</li>
<li><strong>Escolha a campanha.</strong> No painel <strong>Renderización</strong> (Renderização), em <strong>Elige tus campañas</strong> (Escolha suas campanhas), selecione uma ou várias campanhas.</li>
<li><strong>Salve as alterações do widget.</strong></li>
</ol>
<p>Ao terminar, o widget aparece na tabela <strong>Widgets de la campaña</strong> (Widgets da campanha) no detalhe da campanha. Se você escolher mais de uma campanha, o doador verá uma lista suspensa <strong>Elige tu campaña</strong> (Escolha sua campanha) no formulário, com a primeira já selecionada.</p>
<h2>Perguntas frequentes</h2>
<p><strong>Por que não vejo minha campanha no editor?</strong> Porque ela está inativa. Ligue <strong>Campaña activa</strong> no detalhe da campanha.</p>
<p><strong>Dá para desfazer?</strong> Sim. Remova a campanha em <strong>Elige tus campañas</strong> e salve.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como vincular uma página de agradecimento a uma campanha
Slug: como-vincular-uma-pagina-de-agradecimento-a-uma-campanha
Categoría: Campanhas
Resumen: Aprenda a escolher uma landing ou experiência como página de agradecimento da sua campanha e a ativá-la nos seus widgets.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-uma-campanha, como-vincular-um-widget-a-uma-campanha, para-que-serve-uma-campanha
--- CUERPO (HTML) ---
<p>Assim, todos os widgets da campanha podem levar o doador para a mesma página depois da doação. São duas partes: escolher a página na campanha e ativá-la em cada widget. Os nomes de tela aparecem como na versão em espanhol do console.</p>
<h2>Antes de começar</h2>
<ul><li><strong>Tenha a página criada</strong> como experiência em <strong>Fundraising &gt; Experiences AI</strong> ou como landing em <strong>Fundraising &gt; Landings</strong>.</li></ul>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra a campanha.</strong> Em <strong>Fundraising &gt; Campañas</strong>, menu de três pontos da linha, <strong>Editar</strong>.</li>
<li><strong>Vá até a aba Página de agradecimiento (Página de agradecimento).</strong></li>
<li><strong>Escolha o tipo.</strong> Em <strong>Tipo</strong>, escolha <strong>Experiences</strong> ou <strong>Landings</strong>.</li>
<li><strong>Escolha a página</strong> em <strong>Elegir una experiencia</strong> ou <strong>Elegir una landing</strong>. Você verá uma prévia <strong>Mobile</strong>.</li>
<li><strong>Clique em "Usar plantilla" (Usar modelo).</strong> Não aparece confirmação: recarregue a campanha e confira se a aba mostra a página escolhida.</li>
<li><strong>Abra cada widget</strong> em <strong>Fundraising &gt; Widgets</strong>.</li>
<li><strong>Ative a página da campanha.</strong> Na seção <strong>Avanzado</strong> (Avançado), área <strong>Página de agradecimiento</strong>, marque <strong>Usa la página de agradecimiento de la campaña.</strong> (Usa a página de agradecimento da campanha) e salve.</li>
</ol>
<p>Ao terminar, depois de doar, o doador chega à página escolhida na campanha à qual a doação foi associada.</p>
<h2>Perguntas frequentes</h2>
<p><strong>E se a campanha não tiver página escolhida?</strong> É usada a página de agradecimento normal do widget. O mesmo acontece se a página não existir mais.</p>
<p><strong>Dá para desfazer?</strong> Sim. Desmarque a opção no widget ou escolha outra página na campanha.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: O que é o Crowdfunding widget e como configurá-lo
Slug: o-que-e-o-crowdfunding-widget
Categoría: Campanhas
Resumen: Aprenda o que é o Crowdfunding widget e como mostrar no seu site, ao vivo, o progresso da sua campanha até a meta.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-uma-campanha, o-que-e-o-componente-de-doadores, para-que-serve-uma-campanha
--- CUERPO (HTML) ---
<p><strong>O Crowdfunding widget é um bloco que você cola em qualquer site e que mostra ao vivo o progresso da sua campanha até uma meta:</strong> total alcançado, meta, barra de progresso, número de doações e, se você definiu data de encerramento, quantos dias faltam ou <em>"Campaña finalizada"</em> (Campanha encerrada). Os nomes de tela aparecem como na versão em espanhol do console.</p>
<p>Em <strong>Tipo de componente</strong> você escolhe o que medir: <strong>Meta de Recaudación</strong> (soma das doações aprovadas), <strong>Meta de Suscriptores</strong> (assinaturas ativas) ou <strong>Meta de Registros</strong> (pessoas cadastradas, sem repetição). Em <strong>Tipo de meta</strong> você escolhe <strong>Fija</strong> (Fixa: você digita a meta, a moeda e a data e hora de encerramento) ou <strong>Dinámica</strong> (Dinâmica: usa a meta da campanha).</p>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra o configurador.</strong> Em <strong>Fundraising &gt; Campañas</strong>, menu de três pontos da linha, <strong>Crowdfunding widget</strong>.</li>
<li><strong>Configure a meta</strong> na aba <strong>Configuración</strong> (Configuração).</li>
<li><strong>Ajuste o visual</strong> em <strong>Estilos</strong>: <strong>Tipografía</strong> (fonte), <strong>Tamaño de tipografía</strong> (tamanho da fonte) e <strong>Color primario</strong> (cor primária).</li>
<li><strong>Clique em "Guardar" (Salvar).</strong> Cada salvamento cria uma nova versão, que você pode escolher em <strong>Versiones</strong>.</li>
<li><strong>Clique em "Copiar código de inserción" (Copiar código de incorporação)</strong> e cole no HTML do seu site.</li>
</ol>
<h2>Perguntas frequentes</h2>
<p><strong>Mudei o visual e meu site não mudou. Por quê?</strong> Fonte, tamanho, cor e idioma vão dentro do código. Depois de salvar, copie e cole o código de novo.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: O que é o Componente de doadores e como configurá-lo
Slug: o-que-e-o-componente-de-doadores
Categoría: Campanhas
Resumen: Aprenda o que é o Componente de doadores e como mostrar no seu site a lista de pessoas que doaram para a sua campanha.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-uma-campanha, o-que-e-o-crowdfunding-widget, para-que-serve-uma-campanha
--- CUERPO (HTML) ---
<p><strong>O Componente donantes (Componente de doadores) é um bloco para o seu site que mostra a lista de pessoas que doaram para a campanha.</strong> Por padrão, o título é <em>"Personas que también donaron"</em> (Pessoas que também doaram) e ele mostra nome, sobrenome e valor de cada doação aprovada, da mais recente para a mais antiga. Se não houver doações, mostra <em>"No hay donantes disponibles"</em> (Não há doadores disponíveis). Os nomes de tela aparecem como na versão em espanhol do console.</p>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra o configurador.</strong> Em <strong>Fundraising &gt; Campañas</strong>, menu de três pontos da linha, <strong>Componente donantes</strong>.</li>
<li><strong>Personalize.</strong> Configure <strong>Título</strong>, <strong>Tipografía</strong> (fonte), <strong>Color primario</strong> (cor primária), o tema <strong>Light</strong> ou <strong>Dark</strong> e a chave <strong>Activo</strong> / <strong>Inactivo</strong> (Ativo / Inativo). A prévia usa nomes de exemplo.</li>
<li><strong>Clique em "Guardar" (Salvar)</strong> (ou "Actualizar" — Atualizar — se já existia).</li>
<li><strong>Copie o código de incorporação</strong> e cole no seu site.</li>
</ol>
<h2>Perguntas frequentes</h2>
<p><strong>Posso ocultar nomes ou valores?</strong> Não. O bloco publica nome, sobrenome e valor de cada doador; confirme que sua organização pode publicar essas informações.</p>
<p><strong>Preciso copiar o código de novo se mudar algo?</strong> Só se mudar a fonte ou a cor. Título, tema e Ativo / Inativo são aplicados sem mexer no seu site.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Para que serve e como usar o centro de custos da campanha
Slug: como-usar-o-centro-de-custos-da-campanha
Categoría: Campanhas
Resumen: Aprenda a registrar os custos da sua campanha na aba Costos para medir o retorno e ativar o painel de Analytics.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-uma-campanha, como-usar-o-analytics-de-campanhas, como-usar-kpi-merge-tags
--- CUERPO (HTML) ---
<p>O centro de custos é a aba <strong>Costos</strong> (Custos) da campanha. Ele mostra quanto você investiu, permite que a AFRUS calcule indicadores como Resultado, ROI ou custo por transação e ativa o painel de Analytics: "Ver Analytics" só é habilitado quando há pelo menos um custo. Os nomes de tela aparecem como na versão em espanhol do console.</p>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra a campanha</strong> e vá até a aba <strong>Costos</strong>.</li>
<li><strong>Clique em "Agregar costo" (Adicionar custo).</strong></li>
<li><strong>Preencha os dados.</strong> <strong>Costo</strong> (Custo, maior que 0), <strong>Tipo</strong> (<strong>Publicidad (working media)</strong> ou <strong>Costos de apoyo y producción</strong> — custos de apoio e produção), <strong>Fecha de gasto</strong> (data do gasto), <strong>Widget</strong> (opcional) e <strong>Nota</strong> (opcional, até 1000 caracteres).</li>
<li><strong>Clique em "Agregar" (Adicionar).</strong></li>
</ol>
<p>O custo aparece em <strong>Lista de costos</strong> (Lista de custos) e soma no <strong>Total</strong>, que você pode filtrar por datas. Um custo atribuído a um widget conta na análise desse widget; um sem widget, só na da campanha inteira.</p>
<h2>Perguntas frequentes</h2>
<p><strong>Posso registrar centavos?</strong> O valor é salvo sem centavos, então registre valores arredondados. Os custos ficam sempre na moeda da sua organização.</p>
<p><strong>Dá para desfazer?</strong> Você pode editar um custo. Excluí-lo pede confirmação e não pode ser desfeito.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Analytics de campanhas: que dados você obtém e como analisar
Slug: como-usar-o-analytics-de-campanhas
Categoría: Campanhas
Resumen: Aprenda a ativar o Analytics da sua campanha, que indicadores ele mostra e como lê-los para saber se a campanha compensa.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-uma-campanha, como-usar-o-centro-de-custos-da-campanha, para-que-serve-uma-campanha
--- CUERPO (HTML) ---
<h2>Como ativar</h2>
<p>Registre pelo menos um custo na aba <strong>Costos</strong> (Custos) da campanha. Até lá, "Ver Analytics" fica desabilitado. Os nomes de tela aparecem como na versão em espanhol do console.</p>
<h2>Passo a passo</h2>
<ol>
<li><strong>Clique em "Ver Analytics"</strong> no detalhe da campanha.</li>
<li><strong>Escolha o período</strong> na aba <strong>Resumen</strong> (Resumo) — por padrão, todo o histórico. Os cartões são recalculados para esse período.</li>
<li><strong>Baixe os indicadores</strong> com "Descargar KPIs" (Baixar KPIs) se quiser em CSV.</li>
<li><strong>Abra um widget</strong> em <strong>Rendimiento por Widget</strong> (Desempenho por widget) para ver os indicadores e os custos dele.</li>
<li><strong>Veja a evolução</strong> na aba <strong>Tendencias</strong> (Tendências) — por padrão, o mês atual.</li>
</ol>
<h2>Que dados você obtém</h2>
<ul>
<li><strong>Retorno:</strong> receita total, custos, resultado, ROI, investimento e ponto de equilíbrio.</li>
<li><strong>Custo de aquisição:</strong> CPT (custo por transação) e CPR (custo por doador recorrente), brutos e líquidos.</li>
<li><strong>Recorrência:</strong> MRR e ARR adquiridos, RCR, taxa de qualidade, taxa de cancelamento, vida do doador, Lifetime Value, AMV e eficiência de aquisição.</li>
<li><strong>Tabelas Histórico:</strong> desempenho por widget, UTM Source, UTM Medium, UTM Campaign e URL.</li>
</ul>
<h2>Como analisar</h2>
<ul>
<li><strong>É rentável?</strong> Veja resultado e ROI; se houver perda, o ponto de equilíbrio diz em quantos meses ela é recuperada.</li>
<li><strong>Você está captando bem?</strong> Se a eficiência de aquisição (LTV / CPR) for maior que 1, cada doador recorrente vale mais do que custa conquistá-lo.</li>
<li><strong>Onde investir?</strong> As tabelas por widget, UTM e URL mostram quais canais trazem mais receita.</li>
</ul>
<h2>Perguntas frequentes</h2>
<p><strong>Os dados são ao vivo?</strong> Os cartões do Resumen, sim. As tabelas Histórico e a aba Tendencias são atualizadas uma vez por dia, então o que aconteceu hoje pode aparecer amanhã. Além disso, as tabelas Histórico mostram o total de sempre e não respeitam o período escolhido.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Para que servem e como usar os KPI Merge Tags
Slug: como-usar-kpi-merge-tags
Categoría: Campanhas
Resumen: Aprenda a criar KPI Merge Tags para mostrar números de impacto calculados nos seus e-mails automáticos e nas suas landings.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-uma-campanha, como-usar-o-centro-de-custos-da-campanha, como-usar-o-analytics-de-campanhas
--- CUERPO (HTML) ---
<p><strong>Os KPI Merge Tags são números calculados com uma fórmula que você insere em e-mails automáticos ou landings,</strong> por exemplo para transformar o valor de uma doação em "refeições doadas". Eles são criados na aba <strong>KPI Merge Tag</strong> da campanha. Os nomes de tela aparecem como na versão em espanhol do console.</p>
<ul>
<li><strong>KPI Transaccional</strong> (KPI transacional): para e-mails automáticos (<strong>Interacciones &gt; Autoresponders</strong>). Calcula com o <strong>Monto</strong> (Valor) da doação que dispara o e-mail.</li>
<li><strong>KPI Global:</strong> para landings. Calcula com o <strong>Total Recaudado</strong> (Total arrecadado) e a <strong>Cantidad de Donantes</strong> (Quantidade de doadores) da campanha.</li>
</ul>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra a aba.</strong> Na campanha, <strong>KPI Merge Tag</strong>, seção <strong>KPI Transaccional</strong> (ou <strong>KPI Global</strong>), e clique em "Agregar KPI Merge Tag" (ou "Agregar KPI global").</li>
<li><strong>Dê um nome.</strong> Digite <strong>Nombre del KPI</strong> (Nome do KPI); <strong>Variable generada</strong> (Variável gerada) mostra a tag. Para KPI Global, use só letras sem acento, números e espaços.</li>
<li><strong>Monte a fórmula</strong> em <strong>Constructor de Fórmula</strong> (Construtor de fórmula), alternando "Agregar Variable" (Adicionar variável) e "Agregar Operador" (Adicionar operador). "Agregar Variable Multiplicador" cria uma constante. A fórmula deve terminar em uma variável.</li>
<li><strong>Clique em "Crear" (Criar).</strong></li>
<li><strong>Use a tag.</strong> Em um e-mail automático: <em>{{kpi_88_comidas_donadas}}</em>. Em uma landing, entre colchetes: <em>[global_kpi_88_comidas_donadas]</em> (88 é o ID da campanha).</li>
</ol>
<h2>Perguntas frequentes</h2>
<p><strong>Em que ordem a fórmula é calculada?</strong> No KPI Transacional, multiplicação e divisão vêm primeiro. No KPI Global, as operações são aplicadas da esquerda para a direita.</p>
<p><strong>Posso excluir um KPI Merge Tag?</strong> Não. Você pode editá-lo, mas não há botão para excluí-lo.</p>
=== FIN ===
```
