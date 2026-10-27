# Widgets — tutoriales web (afrus.ai/howto)
Un bloque por tutorial, listo para pegar. Orden: español, inglés, portugués.

## Español

```text
=== TUTORIAL ===
Idioma: es
Título: Qué es un widget
Slug: que-es-un-widget
Categoría: Widgets
Resumen: Aprende qué es un widget de AFRUS: un formulario de donación, registro o pago que se arma por bloques y se inserta en tu sitio web.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-sirve-un-widget, tipos-de-widgets-en-afrus, como-cambiar-los-estilos-del-widget, como-agregar-un-nuevo-pais-a-un-widget, snippets-obligatorios-y-sugeridos, como-configurar-los-metodos-de-pago-del-widget, como-configurar-el-snippet-donacion, scape-recurrent-donacion-unica-como-enlace, cards-de-conversion-unica-a-recurrente, cover-your-cost, como-configurar-una-pagina-de-agradecimiento-en-el-widget, opciones-avanzadas-del-widget, como-insertar-un-widget-en-tu-sitio-web
--- CUERPO (HTML) ---
<p><strong>Un widget es un formulario de AFRUS (de donación, de registro, de pago, etc.) que se arma por bloques llamados snippets y se inserta en cualquier sitio web o landing con un pequeño código.</strong></p>
<p>Cada widget tiene un <strong>Objetivo</strong> (por ejemplo, donación o registro), uno o varios países con su idioma y moneda, y una lista de snippets: información personal, montos, medio de pago, términos y condiciones, botón, etc.</p>
<h2>Dónde lo encuentras</h2>
<p>En <strong>Fundraising &gt; Widgets</strong> verás la pantalla <strong>Gestión de Widgets</strong>, con el botón "Nuevo widget", filtros (<strong>Campaña</strong>, <strong>Objetivo</strong>, <strong>Estado</strong>, <strong>Por defecto</strong>, <strong>Etiqueta</strong>) y una tabla con <strong>Estado</strong>, <strong>Nombre</strong>, <strong>Fecha</strong>, <strong>Objetivo</strong>, <strong>Recaudado</strong>, <strong>Transacciones</strong>, <strong>Suscripciones</strong>, <strong>Vistas</strong> y <strong>Registros</strong>.</p>
<h2>Preguntas frecuentes</h2>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Para qué sirve un widget
Slug: para-que-sirve-un-widget
Categoría: Widgets
Resumen: Aprende para qué sirve un widget: recibir donaciones, captar registros, cobrar pagos y medir resultados desde tu propio sitio web.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-un-widget, tipos-de-widgets-en-afrus, como-cambiar-los-estilos-del-widget, como-agregar-un-nuevo-pais-a-un-widget
--- CUERPO (HTML) ---
<p>Un widget es un formulario de AFRUS que insertas en tu sitio o landing. Esto es lo que te permite hacer:</p>
<ul>
<li><strong>Recibir donaciones desde tu sitio.</strong> Únicas, mensuales o anuales, sin que el donante salga de tu página.</li>
<li><strong>Captar registros (leads), vender productos o tickets y cobrar pagos.</strong> Cada uso tiene su propio tipo de widget.</li>
<li><strong>Hablarle a cada visitante en su idioma y su moneda.</strong> El widget muestra el país desde donde navega la persona, si lo configuraste.</li>
<li><strong>Medir el rendimiento.</strong> El <strong>Dashboard de Widget</strong> muestra vistas, conversiones e ingresos de cada formulario.</li>
<li><strong>Enviar las conversiones a Google y a Meta.</strong> Con Google Tag Manager, GA4, Pixel y Conversions API.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Qué tipos de widgets existen y para qué se usa cada uno
Slug: tipos-de-widgets-en-afrus
Categoría: Widgets
Resumen: Aprende qué tipos de widget (objetivos) ofrece AFRUS, para qué sirve cada uno y cómo crear el que necesitas.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-un-widget, para-que-sirve-un-widget, como-cambiar-los-estilos-del-widget, como-agregar-un-nuevo-pais-a-un-widget
--- CUERPO (HTML) ---
<p>El tipo de widget es su <strong>Objetivo</strong>. Se elige al crearlo y define qué snippets se agregan solos. Los objetivos que ves son los que AFRUS tiene habilitados para tu organización.</p>
<ul>
<li><strong>Transacción:</strong> donaciones únicas, mensuales o anuales.</li>
<li><strong>Registros / Registro:</strong> captar datos de personas (leads), sin pago.</li>
<li><strong>Ofrece Misas / Regala Misas:</strong> formularios de misas e intenciones.</li>
<li><strong>Pagos:</strong> cobrar un pago con valor fijo o con mínimo y máximo.</li>
<li><strong>Producto:</strong> vender productos o tickets de rifa con precio y stock.</li>
<li><strong>Sign up:</strong> registro de una organización con plan de precios.</li>
</ul>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre el editor.</strong> En <strong>Fundraising &gt; Widgets</strong>, haz clic en "Nuevo widget". Se abre en una pestaña nueva; ahí haz clic en "Nuevo formulario".</li>
<li><strong>Elige el objetivo.</strong> Escribe el <strong>Nombre del formulario</strong> (máximo 50 caracteres), elige el <strong>Objetivo</strong> y haz clic en "Crear".</li>
<li><strong>Vincula una campaña.</strong> En <strong>Renderización</strong>, elige al menos una en <strong>Elige tus campañas</strong>. Es obligatorio.</li>
<li><strong>Elige cómo se muestra.</strong> En <strong>Mecanismo de renderización</strong>, elige <strong>Estandar</strong> (incrustado en la página) o <strong>Popup</strong> (se abre desde un botón; completa <strong>Texto del botón Pop up</strong>).</li>
<li><strong>Configura y activa.</strong> Configura los snippets, haz clic en "Guardar Widget" y activa el interruptor <strong>Estado</strong>.</li>
</ol>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Por qué no puedo guardar?</strong> "Guardar Widget" muestra un botón rojo <strong>Errores</strong> con el motivo, por ejemplo que falta una campaña o los términos y condiciones.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo cambiar los estilos del widget
Slug: como-cambiar-los-estilos-del-widget
Categoría: Widgets
Resumen: Aprende a cambiar la forma de los campos, los colores, la tipografía, el encabezado y el pie de tu widget de AFRUS.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-un-widget, tipos-de-widgets-en-afrus, como-agregar-un-nuevo-pais-a-un-widget, para-que-sirve-un-widget
--- CUERPO (HTML) ---
<p>El editor del widget se abre en una pestaña nueva. Para abrirlo, en <strong>Fundraising &gt; Widgets</strong> haz clic en "Editar" en la fila del widget.</p><h2>Paso a paso</h2>
<ol>
<li><strong>Abre el panel Estilo.</strong> En la pestaña <strong>Editar</strong> del editor, abre <strong>Estilo</strong>.</li>
<li><strong>Elige la forma de los campos.</strong> En <strong>Seleccione un estilo para el formulario</strong>: <strong>Cuadrado</strong>, <strong>Cuadrado redondeado</strong>, <strong>Redondeado</strong> o <strong>Línea</strong>.</li>
<li><strong>Ajusta colores y tipografía.</strong> En <strong>Estilo del formulario</strong> cambia la <strong>Familia tipográfica</strong>, los colores principal, de botones, de fondo, de texto y de error, la caja, el borde y la sombra.</li>
<li><strong>Ajusta encabezado y pie.</strong> En <strong>Encabezado</strong> cambia el color de fondo; en <strong>Pie de página</strong>, alineación, colores y tipografía. "REINICIAR" vuelve a los valores de fábrica.</li>
<li><strong>Revisa y guarda.</strong> Mira el resultado con "Vista previa" y haz clic en "Guardar Widget".</li>
</ol>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Puedo tener estilos distintos por país?</strong> No. Los estilos son del widget completo.</p>
<p><strong>¿Dónde cambio el ancho?</strong> En la pestaña <strong>Instalar</strong> del editor.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo agregar un nuevo país a un widget y para qué
Slug: como-agregar-un-nuevo-pais-a-un-widget
Categoría: Widgets
Resumen: Aprende a agregar un país a tu widget para mostrar a cada visitante su idioma, su moneda y sus propios montos y pasarelas.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-un-widget, como-cambiar-los-estilos-del-widget, snippets-obligatorios-y-sugeridos, tipos-de-widgets-en-afrus
--- CUERPO (HTML) ---
<p>Cada país del widget tiene su propio <strong>Idioma</strong>, su propia <strong>Moneda</strong> y sus propios snippets (montos, pasarelas, campos). Quien abre el widget ve el país desde donde navega, si está configurado; si no, ve el país por defecto (con estrella).</p>
<p>El editor del widget se abre en una pestaña nueva. Para abrirlo, en <strong>Fundraising &gt; Widgets</strong> haz clic en "Editar" en la fila del widget.</p><h2>Paso a paso</h2>
<ol>
<li><strong>Agrega el país.</strong> En la columna central, haz clic en <strong>Nuevo país</strong>.</li>
<li><strong>Completa idioma y moneda.</strong> Elige <strong>Seleccione un país</strong>, el <strong>Idioma</strong> (Español, English, Portugues, Italian o Deutsch) y revisa la <strong>Moneda</strong>. En widgets de <strong>Pagos</strong>, elige también el formato decimal.</li>
<li><strong>Agrega un pie de página (opcional).</strong> Hasta 250 caracteres.</li>
<li><strong>Guarda.</strong> Haz clic en "Guardar". Verás <em>"¡País añadido satisfactoriamente!"</em></li>
<li><strong>Configura sus snippets.</strong> El país empieza solo con los snippets obligatorios. Configura montos y medio de pago y haz clic en "Guardar Widget".</li>
</ol>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Se copian los montos de otro país?</strong> No. Los montos y las pasarelas no se copian entre países.</p>
<p><strong>¿Puedo cambiar la moneda después?</strong> Sí, pero se borra la configuración del snippet <strong>Medio de pago</strong> de ese país y hay que rehacerla.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cuáles son los snippets obligatorios y sugeridos de un widget
Slug: snippets-obligatorios-y-sugeridos
Categoría: Widgets
Resumen: Aprende qué snippets son obligatorios en cada widget, cuáles son opcionales y cómo agregarlos y ordenarlos.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-un-widget, como-agregar-un-nuevo-pais-a-un-widget, como-configurar-los-metodos-de-pago-del-widget, como-cambiar-los-estilos-del-widget
--- CUERPO (HTML) ---
<p>En el editor, los snippets son <strong>obligatorios</strong> u <strong>opcionales</strong>. AFRUS no marca snippets como "sugeridos": cuáles conviene usar depende de tu formulario.</p>
<h2>Obligatorios</h2>
<ul>
<li><strong>Información personal:</strong> siempre va primero.</li>
<li><strong>Términos y condiciones:</strong> sin él, con texto y URL, ningún widget se puede guardar. En <strong>Registro</strong> hay que agregarlo a mano.</li>
<li><strong>Medio de pago</strong> y <strong>Botón</strong>: fijos al final.</li>
<li><strong>Según el objetivo:</strong> Donación, Tipos de Misas, Pago Genérico, Producto, o Sign up con Dirección de registro y Modelo de precios.</li>
<li><strong>Los que exige la pasarela:</strong> se agregan solos al guardar Medio de pago, con el aviso <em>"¡IMPORTANTE! Este snippet es requerido por la pasarela de pago"</em>.</li>
</ul>
<h2>Opcionales</h2>
<p>Imagen, Texto, Separador, Campo personalizado, Campo predeterminado, Dirección o Dirección Fija, Documento, Ofrecer única a recurrente, ID de la campaña de Salesforce y, en misas, Imagen con texto, Intención y Regala intención. Algunos solo aparecen si AFRUS los habilitó para tu organización.</p>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre el editor del widget.</strong> En <strong>Fundraising &gt; Widgets</strong>, haz clic en "Editar".</li>
<li><strong>Agrega el snippet.</strong> Haz clic en "Agregar" y elígelo.</li>
<li><strong>Configúralo.</strong> Complétalo en <strong>Configuración del snippet</strong> y guárdalo con <strong>Guardar Snippet</strong>.</li>
<li><strong>Ordénalo.</strong> Arrástralo a su posición.</li>
</ol>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo configurar los métodos de pago en tu widget
Slug: como-configurar-los-metodos-de-pago-del-widget
Categoría: Widgets
Resumen: Aprende a elegir periodicidades, pasarelas y métodos de pago en tu widget, y en qué orden se le muestran al donante.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-un-widget, snippets-obligatorios-y-sugeridos, como-configurar-el-snippet-donacion, como-agregar-un-nuevo-pais-a-un-widget
--- CUERPO (HTML) ---
<h2>Antes de empezar</h2>
<ul><li><strong>Conecta la pasarela</strong> en <strong>Ajustes de Organización &gt; Pasarelas de pago</strong>. En el widget solo aparecen las pasarelas conectadas que aceptan la moneda del país.</li></ul>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre el snippet Medio de pago.</strong> En el editor del widget, elige el país y haz clic en <strong>Medio de pago</strong>.</li>
<li><strong>Elige las periodicidades.</strong> En <strong>Seleccionar periodicidades</strong>, marca <strong>Única</strong>, <strong>Mensual</strong> y/o <strong>Anual</strong>.</li>
<li><strong>Elige las pasarelas.</strong> En <strong>Selecionar pasarelas de pago</strong>.</li>
<li><strong>Empata método y periodicidad.</strong> En <strong>Empatar periodicidad y método de pago</strong>, marca en qué periodicidades se ofrece cada método.</li>
<li><strong>Ordena los métodos.</strong> Arrástralos y marca el preseleccionado con "set default".</li>
<li><strong>Guarda.</strong> <strong>Guardar Snippet</strong> y luego "Guardar Widget".</li>
</ol>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Puedo ofrecer Pix o boleto como mensual?</strong> No. Pix, boleto y efectivo solo se ofrecen como <strong>Única</strong>, salvo Pix con Infopago, que también admite mensual.</p>
<p><strong>¿Qué pasa si cambio la moneda del país?</strong> Se borra esta configuración y hay que rehacerla.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo configurar el snippet Donación de tu widget
Slug: como-configurar-el-snippet-donacion
Categoría: Widgets
Resumen: Aprende a configurar montos sugeridos, monto libre, imágenes y frecuencias única y mensual en el snippet Donación.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-un-widget, como-configurar-los-metodos-de-pago-del-widget, scape-recurrent-donacion-unica-como-enlace, snippets-obligatorios-y-sugeridos
--- CUERPO (HTML) ---
<h2>Antes de empezar</h2>
<ul><li><strong>Configura primero Medio de pago.</strong> Las frecuencias del snippet Donación salen de las periodicidades marcadas ahí.</li></ul>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre el snippet Donación.</strong> En el editor del widget, elige el país y haz clic en <strong>Donación</strong>.</li>
<li><strong>Elige las opciones.</strong> <strong>Quiero campo de monto</strong> (monto libre), <strong>No quiero sugerir cantidades.</strong>, <strong>Quiero escribir una frase de solicitud para cada cantidad</strong> y <strong>Quiero poner una imagen y descripción por cada cantidad</strong>.</li>
<li><strong>Configura los montos.</strong> Haz clic en "Configurar frecuencias". En cada pestaña agrega hasta 4 montos, marca con estrella el predeterminado (obligatorio) y, si quieres, un <strong>Mínimo</strong>. Si hay varias frecuencias, elige la preseleccionada con <strong>Seleccionar frecuencia por defecto</strong>.</li>
<li><strong>Agrega imágenes (opcional).</strong> Una por monto, con "Subir imagen" o desde <strong>Galería</strong>: jpg, webp o png, recomendado 150 × 150 píxeles y hasta 1 MB.</li>
<li><strong>Guarda.</strong> "Guardar" en la ventana y luego <strong>Guardar Snippet</strong>.</li>
<li><strong>Ordena las frecuencias (opcional).</strong> En <strong>Orden de las frecuencias</strong>.</li>
</ol>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Cuántos montos puedo sugerir?</strong> Hasta 4 por frecuencia.</p>
<p><strong>¿Los montos son iguales en todos los países?</strong> No. Cada país tiene su propio snippet Donación.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Scape recurrent: muestra la donación única solo como enlace
Slug: scape-recurrent-donacion-unica-como-enlace
Categoría: Widgets
Resumen: Aprende a mostrar solo la donación mensual en tu widget y dejar la donación única como un enlace debajo del botón de pago.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-un-widget, como-configurar-el-snippet-donacion, cards-de-conversion-unica-a-recurrente, como-configurar-los-metodos-de-pago-del-widget
--- CUERPO (HTML) ---
<p>Con esta opción, el formulario muestra solo la donación mensual y deja la única como un enlace. Así impulsas la recurrencia sin quitarle al donante la opción de dar una sola vez.</p>
<h2>Antes de empezar</h2>
<ul><li><strong>En el snippet Donación</strong>, <strong>Mensual</strong> debe estar activa con al menos un monto, y <strong>Única</strong> también debe estar activa.</li></ul>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre el snippet Donación</strong> en el editor del widget.</li>
<li><strong>Activa la opción.</strong> Marca <strong>Mostrar la donación única solo como enlace debajo del botón de pago</strong>.</li>
<li><strong>Guarda.</strong> <strong>Guardar Snippet</strong> y luego "Guardar Widget".</li>
</ol>
<p>El donante verá solo la frecuencia mensual y, debajo del botón de pago, el enlace <em>"Hacer donación única"</em>.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Por qué no aparece el enlace?</strong> Solo aparece si la frecuencia Única tiene montos o si está activo <strong>Quiero campo de monto</strong>.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cards de conversión: de donación única a recurrente
Slug: cards-de-conversion-unica-a-recurrente
Categoría: Widgets
Resumen: Aprende a configurar la tarjeta que invita a quien dona una vez a convertirse en donante mensual, dentro del formulario y después de pagar.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-un-widget, scape-recurrent-donacion-unica-como-enlace, cover-your-cost, como-configurar-el-snippet-donacion
--- CUERPO (HTML) ---
<h2>Antes de empezar</h2>
<ul>
<li><strong>AFRUS debe habilitar</strong> el snippet <strong>Ofrecer única a recurrente</strong> para tu organización. Solo existe en widgets de objetivo <strong>Transacción</strong>.</li>
<li><strong>La frecuencia mensual</strong> debe estar habilitada en el snippet <strong>Donación</strong> con al menos un monto.</li>
</ul>
<h2>Paso a paso</h2>
<ol>
<li><strong>Agrega el snippet.</strong> En el editor del widget, "Agregar" y elige <strong>Ofrecer única a recurrente</strong>. Se coloca solo después de Donación.</li>
<li><strong>Actívalo.</strong> Activa <strong>Habilitar</strong>.</li>
<li><strong>Personaliza la tarjeta (opcional).</strong> <strong>Título</strong>, <strong>Subtítulo</strong> y colores.</li>
<li><strong>Define las tasas.</strong> <strong>Tasa 1 (%)</strong> y <strong>Tasa 2 (%)</strong>, enteros de 1 a 99 (vienen en 50 y 25): los porcentajes del monto único que se proponen como mensual.</li>
<li><strong>Guarda.</strong> <strong>Guardar Snippet</strong> y luego "Guardar Widget".</li>
</ol>
<h2>Qué ve el donante</h2>
<ul>
<li><strong>Durante el formulario:</strong> la tarjeta <em>"Conviértete en donante mensual"</em> con dos montos mensuales y la opción de mantener su donación única.</li>
<li><strong>Después de pagar</strong> (donación única con tarjeta en una pasarela gestionada por AFRUS): <em>"Conviértelo en un regalo mensual"</em>. Si acepta, se crea además una suscripción mensual; la donación ya cobrada no cambia.</li>
</ul>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Funciona con PayPal o Pix?</strong> Solo la oferta dentro del formulario. La oferta después del pago requiere tarjeta en una pasarela gestionada por AFRUS.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cover your cost: que el donante cubra los costos
Slug: cover-your-cost
Categoría: Widgets
Resumen: Aprende a activar Cover Your Cost para que el donante pueda cubrir la comisión y tu organización reciba el monto completo.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-un-widget, cards-de-conversion-unica-a-recurrente, como-configurar-una-pagina-de-agradecimiento-en-el-widget, scape-recurrent-donacion-unica-como-enlace
--- CUERPO (HTML) ---
<p>Con <strong>Cover Your Cost</strong>, el donante puede cubrir la comisión de la pasarela, para que tu organización reciba el monto completo de la donación.</p>
<h2>Antes de empezar</h2>
<ul>
<li><strong>AFRUS debe activarlo</strong> para tu organización; no se activa desde la consola.</li>
<li><strong>Se configura por pasarela</strong>, no dentro del widget.</li>
</ul>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre la pasarela.</strong> En <strong>Ajustes de Organización &gt; Pasarelas de pago</strong>.</li>
<li><strong>Activa la opción.</strong> En <strong>Cover Your Cost</strong>, activa <strong>Activar Cover Your Cost</strong>.</li>
<li><strong>Define la comisión.</strong> <strong>Comisión de pasarela (%)</strong>, mínimo 0.01. Sumada a la <strong>Comisión AFRUS (%)</strong> debe ser menor a 80 %.</li>
<li><strong>Elige si viene preseleccionada.</strong> Con <strong>Preseleccionar la opción para el donante</strong>.</li>
<li><strong>Guarda la pasarela.</strong> Repite en cada pasarela que deba ofrecerlo.</li>
</ol>
<p>En el último paso del widget, el donante verá <em>"Cubrir el 100% los costos de donación"</em> con la donación base, el costo aproximado y el total.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Por qué el total es un poco más que la suma de los porcentajes?</strong> Porque se calcula para que, después de las comisiones, tu organización reciba al menos el monto base, redondeado hacia arriba.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo configurar una página de agradecimiento en tu widget
Slug: como-configurar-una-pagina-de-agradecimiento-en-el-widget
Categoría: Widgets
Resumen: Aprende a redirigir al donante, después de donar, a la página de agradecimiento de tu campaña o a la URL que elijas.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-un-widget, cover-your-cost, opciones-avanzadas-del-widget, cards-de-conversion-unica-a-recurrente
--- CUERPO (HTML) ---
<p>El editor del widget se abre en una pestaña nueva. Para abrirlo, en <strong>Fundraising &gt; Widgets</strong> haz clic en "Editar" en la fila del widget.</p><h2>Paso a paso</h2>
<ol>
<li><strong>Abre el panel.</strong> En la pestaña <strong>Editar</strong>, abre el panel <strong>Avanzado</strong> y, dentro, <strong>Página de agradecimiento</strong>.</li>
<li><strong>Opción A: la de la campaña.</strong> Marca <strong>Usa la página de agradecimiento de la campaña.</strong></li>
<li><strong>Opción B: tus URL.</strong> Haz clic en "Configurar", activa <strong>Habilitar página de agradecimiento</strong> y usa una <strong>Página de agradecimiento general</strong> o una <strong>Página de agradecimiento personalizada</strong>, con URL para transacción exitosa y pendiente de confirmación, en únicas y recurrentes.</li>
<li><strong>Guarda.</strong> "Guardar" y luego "Guardar Widget".</li>
</ol>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Qué formato deben tener las URL?</strong> Deben empezar con http:// o https:// y tener menos de 255 caracteres.</p>
<p><strong>¿Y si la donación es rechazada?</strong> No se redirige a ninguna página personalizada.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Opciones avanzadas del widget: captcha, analytics, Face to Face y más
Slug: opciones-avanzadas-del-widget
Categoría: Widgets
Resumen: Aprende a configurar Recaptcha, Google Tag Manager, protocolo de medición GA4, Facebook CAPI y Face to Face en tu widget.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-un-widget, como-configurar-una-pagina-de-agradecimiento-en-el-widget, como-insertar-un-widget-en-tu-sitio-web, cover-your-cost
--- CUERPO (HTML) ---
<p>El editor del widget se abre en una pestaña nueva. Para abrirlo, en <strong>Fundraising &gt; Widgets</strong> haz clic en "Editar" en la fila del widget.</p><p>Todas estas opciones están en el panel <strong>Avanzado</strong> y se guardan con "Guardar Widget".</p>
<h2>Paso a paso</h2>
<ol>
<li><strong>Recaptcha.</strong> Activa el interruptor para que el donante siempre escriba un código de verificación de 6 caracteres. Sin él, el captcha igual puede aparecer ante un intento sospechoso.</li>
<li><strong>Google Tag Manager 4.</strong> Pega tu <strong>Código de seguimiento</strong> (ID del contenedor) para recibir los eventos del recorrido del donante.</li>
<li><strong>Protocolo de medición.</strong> Completa <strong>Measurement Id</strong> y <strong>Api secret</strong> de GA4: AFRUS envía los eventos, incluida la compra, también desde el servidor.</li>
<li><strong>Facebook Capi.</strong> Completa <strong>Pixel id</strong> y <strong>Access Token</strong>: AFRUS envía los eventos a Meta desde el navegador y desde el servidor.</li>
<li><strong>Face to Face</strong> (widgets transaccionales). Para donaciones presenciales: activa <strong>Face to Face</strong> y completa <strong>Correo del captador</strong> (obligatorio) y <strong>Correo del supervisor</strong>. El autocompletado del navegador se desactiva solo.</li>
<li><strong>Guarda.</strong> Haz clic en "Guardar Widget".</li>
</ol>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Qué reciben el captador y el supervisor?</strong> Un email por cada donación exitosa o fallida de ese widget.</p>
<p><strong>¿El Pixel de mi landing se configura aquí?</strong> No. El Pixel y Google Analytics de una landing se configuran en la landing.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo insertar un widget en tu sitio web
Slug: como-insertar-un-widget-en-tu-sitio-web
Categoría: Widgets
Resumen: Aprende a copiar el código de tu widget de AFRUS y pegarlo en tu sitio web, con ancho personalizado si lo necesitas.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-un-widget, opciones-avanzadas-del-widget, como-configurar-una-pagina-de-agradecimiento-en-el-widget, cover-your-cost
--- CUERPO (HTML) ---
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre el código.</strong> En <strong>Fundraising &gt; Widgets</strong>, haz clic en el icono de código de la fila del widget. Se abre <strong>Código del widget</strong>.</li>
<li><strong>Copia el código.</strong> Haz clic en "Copiar".</li>
<li><strong>Pégalo en tu página.</strong> En un bloque o componente HTML de tu sitio. El widget aparecerá ahí.</li>
</ol>
<h2>Si necesitas otro ancho</h2>
<p>En el editor del widget, pestaña <strong>Instalar</strong>, define el ancho en <strong>Configura el ancho del formulario</strong> (px, %, em, rem o vw), haz clic en "Guardar Widget" y copia el <strong>Código de inserción</strong>.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Necesito un código por país?</strong> No. El código es el mismo para todos los países; el país se elige solo.</p>
<p><strong>¿Por qué no recibe donaciones?</strong> Revisa que el interruptor <strong>Estado</strong> del widget esté activo.</p>
=== FIN ===
```

## English

```text
=== TUTORIAL ===
Idioma: en
Título: What a widget is
Slug: what-is-a-widget
Categoría: Widgets
Resumen: Learn what an AFRUS widget is: a donation, registration or payment form built from blocks and embedded on your website.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-widget-for, widget-types-in-afrus, how-to-change-the-widget-styles, how-to-add-a-new-country-to-a-widget, required-and-suggested-snippets, how-to-set-up-widget-payment-methods, how-to-set-up-the-donation-snippet, scape-recurrent-one-time-donation-as-link, conversion-cards-one-time-to-recurring, cover-your-cost-donors-cover-costs, how-to-set-up-a-thank-you-page-in-the-widget, advanced-widget-options, how-to-embed-a-widget-on-your-website
--- CUERPO (HTML) ---
<p><strong>A widget is an AFRUS form (donation, registration, payment, etc.) built from blocks called snippets and embedded on any website or landing page with a short code.</strong></p>
<p>Each widget has an <strong>Objetivo</strong> (Goal), one or more countries with their language and currency, and a list of snippets: personal information, amounts, payment method, terms and conditions, button, etc.</p>
<h2>Where to find it</h2>
<p>Labels are shown as they appear in the Spanish version of the console.</p><p>In <strong>Fundraising &gt; Widgets</strong> you will see the <strong>Gestión de Widgets</strong> (Widget management) screen, with the "Nuevo widget" (New widget) button, filters (campaign, goal, status, default, tag) and a table with status, name, date, goal, amount raised, transactions, subscriptions, views and registrations.</p>
<h2>Frequently asked questions</h2>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: What a widget is for
Slug: what-is-a-widget-for
Categoría: Widgets
Resumen: Learn what a widget is for: receiving donations, capturing leads, collecting payments and measuring results on your own website.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-widget, widget-types-in-afrus, how-to-change-the-widget-styles, how-to-add-a-new-country-to-a-widget
--- CUERPO (HTML) ---
<p>A widget is an AFRUS form you embed on your site or landing page. This is what it lets you do:</p>
<ul>
<li><strong>Receive donations on your site.</strong> One-time, monthly or yearly, without donors leaving your page.</li>
<li><strong>Capture leads, sell products or tickets and collect payments.</strong> Each use has its own widget type.</li>
<li><strong>Speak to each visitor in their language and currency.</strong> The widget shows the country the person is browsing from, if you set it up.</li>
<li><strong>Measure performance.</strong> The <strong>Dashboard de Widget</strong> shows views, conversions and revenue for each form.</li>
<li><strong>Send conversions to Google and Meta.</strong> With Google Tag Manager, GA4, Pixel and Conversions API.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: Which widget types exist and what each one is for
Slug: widget-types-in-afrus
Categoría: Widgets
Resumen: Learn which widget types (goals) AFRUS offers, what each one is for and how to create the one you need.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-widget, what-is-a-widget-for, how-to-change-the-widget-styles, how-to-add-a-new-country-to-a-widget
--- CUERPO (HTML) ---
<p>Labels are shown as they appear in the Spanish version of the console.</p><p>The widget type is its <strong>Objetivo</strong> (Goal). It is chosen when you create the widget and defines which snippets are added automatically. The goals you see are the ones AFRUS has enabled for your organization.</p>
<ul>
<li><strong>Transacción</strong> (Transaction): one-time, monthly or yearly donations.</li>
<li><strong>Registros / Registro</strong> (Registration): capturing people's details (leads), no payment.</li>
<li><strong>Ofrece Misas / Regala Misas</strong> (Masses): mass and intention forms.</li>
<li><strong>Pagos</strong> (Payments): collecting a payment with a fixed value or a min/max.</li>
<li><strong>Producto</strong> (Product): selling products or raffle tickets with price and stock.</li>
<li><strong>Sign up</strong>: registering an organization with a pricing plan.</li>
</ul>
<h2>Step by step</h2>
<ol>
<li><strong>Open the editor.</strong> In <strong>Fundraising &gt; Widgets</strong>, click "Nuevo widget". The editor opens in a new tab; there, click "Nuevo formulario".</li>
<li><strong>Choose the goal.</strong> Type the <strong>Nombre del formulario</strong> (Form name, up to 50 characters), choose the <strong>Objetivo</strong> and click "Crear" (Create).</li>
<li><strong>Link a campaign.</strong> In <strong>Renderización</strong>, choose at least one in <strong>Elige tus campañas</strong>. It is required.</li>
<li><strong>Choose how it is displayed.</strong> In <strong>Mecanismo de renderización</strong>, choose <strong>Estandar</strong> (embedded in the page) or <strong>Popup</strong> (opens from a button; fill in <strong>Texto del botón Pop up</strong>).</li>
<li><strong>Set it up and turn it on.</strong> Set up the snippets, click "Guardar Widget" (Save widget) and turn on the <strong>Estado</strong> (Status) switch.</li>
</ol>
<h2>Frequently asked questions</h2>
<p><strong>Why can't I save?</strong> "Guardar Widget" shows a red <strong>Errores</strong> (Errors) button with the reason, for example a missing campaign or missing terms and conditions.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to change the widget's styles
Slug: how-to-change-the-widget-styles
Categoría: Widgets
Resumen: Learn how to change the field shape, colors, fonts, header and footer of your AFRUS widget.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-widget, widget-types-in-afrus, how-to-add-a-new-country-to-a-widget, what-is-a-widget-for
--- CUERPO (HTML) ---
<p>The widget editor opens in a new tab. To open it, in <strong>Fundraising &gt; Widgets</strong> click "Editar" (Edit) on the widget's row.</p><p>Labels are shown as they appear in the Spanish version of the console.</p><h2>Step by step</h2>
<ol>
<li><strong>Open the Estilo panel.</strong> In the editor's <strong>Editar</strong> tab, open <strong>Estilo</strong> (Style).</li>
<li><strong>Choose the field shape.</strong> In <strong>Seleccione un estilo para el formulario</strong>: <strong>Cuadrado</strong>, <strong>Cuadrado redondeado</strong>, <strong>Redondeado</strong> or <strong>Línea</strong> (square, rounded square, rounded, line).</li>
<li><strong>Adjust colors and fonts.</strong> In <strong>Estilo del formulario</strong>, change the font family, the main, button, background, text and error colors, the box, the border and the shadow.</li>
<li><strong>Adjust header and footer.</strong> In <strong>Encabezado</strong> change the background color; in <strong>Pie de página</strong>, alignment, colors and typography. "REINICIAR" (Reset) restores the default values.</li>
<li><strong>Review and save.</strong> Check the result with "Vista previa" (Preview) and click "Guardar Widget".</li>
</ol>
<h2>Frequently asked questions</h2>
<p><strong>Can I have different styles per country?</strong> No. Styles apply to the whole widget.</p>
<p><strong>Where do I change the width?</strong> In the editor's <strong>Instalar</strong> (Install) tab.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to add a new country to a widget and why
Slug: how-to-add-a-new-country-to-a-widget
Categoría: Widgets
Resumen: Learn how to add a country to your widget so each visitor sees their language, currency, amounts and gateways.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-widget, how-to-change-the-widget-styles, required-and-suggested-snippets, widget-types-in-afrus
--- CUERPO (HTML) ---
<p>Each country in the widget has its own language, currency and snippets (amounts, gateways, fields). Whoever opens the widget sees the country they are browsing from, if it is set up; otherwise they see the default country (with a star).</p>
<p>The widget editor opens in a new tab. To open it, in <strong>Fundraising &gt; Widgets</strong> click "Editar" (Edit) on the widget's row.</p><p>Labels are shown as they appear in the Spanish version of the console.</p><h2>Step by step</h2>
<ol>
<li><strong>Add the country.</strong> In the center column, click <strong>Nuevo país</strong> (New country).</li>
<li><strong>Fill in language and currency.</strong> Choose <strong>Seleccione un país</strong> (Select a country), the <strong>Idioma</strong> (Español, English, Portugues, Italian or Deutsch) and check the <strong>Moneda</strong> (currency). In <strong>Pagos</strong> widgets, also choose the decimal format.</li>
<li><strong>Add a footer (optional).</strong> Up to 250 characters.</li>
<li><strong>Save.</strong> Click "Guardar" (Save). You will see <em>"¡País añadido satisfactoriamente!"</em> (Country added successfully).</li>
<li><strong>Set up its snippets.</strong> The country starts with only the required snippets. Set up amounts and payment method and click "Guardar Widget".</li>
</ol>
<h2>Frequently asked questions</h2>
<p><strong>Are amounts copied from another country?</strong> No. Amounts and gateways are not copied between countries.</p>
<p><strong>Can I change the currency later?</strong> Yes, but that country's <strong>Medio de pago</strong> (Payment method) snippet settings are deleted and must be redone.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: Which widget snippets are required and which are suggested
Slug: required-and-suggested-snippets
Categoría: Widgets
Resumen: Learn which snippets are required in each widget, which are optional, and how to add and order them.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-widget, how-to-add-a-new-country-to-a-widget, how-to-set-up-widget-payment-methods, how-to-change-the-widget-styles
--- CUERPO (HTML) ---
<p>Labels are shown as they appear in the Spanish version of the console.</p><p>In the editor, snippets are either <strong>required</strong> or <strong>optional</strong>. AFRUS does not mark snippets as "suggested": which ones are worth using depends on your form.</p>
<h2>Required</h2>
<ul>
<li><strong>Información personal</strong> (Personal information): always first.</li>
<li><strong>Términos y condiciones</strong> (Terms and conditions): without it, with text and URL, no widget can be saved. In <strong>Registro</strong> widgets you add it manually.</li>
<li><strong>Medio de pago</strong> (Payment method) and <strong>Botón</strong> (Button): fixed at the end.</li>
<li><strong>By goal:</strong> Donation, Mass types, Generic payment, Product, or Sign up with Registration address and Pricing model.</li>
<li><strong>Those required by the gateway:</strong> added automatically when you save the payment method, with the notice <em>"¡IMPORTANTE! Este snippet es requerido por la pasarela de pago"</em> (required by the payment gateway).</li>
</ul>
<h2>Optional</h2>
<p>Image, Text, Separator, Custom field, Default field, Address or Fixed address, ID document, Offer one-time to recurring, Salesforce campaign ID and, for masses, Image with text, Intention and Gift intention. Some only appear if AFRUS enabled them for your organization.</p>
<h2>Step by step</h2>
<ol>
<li><strong>Open the widget editor.</strong> In <strong>Fundraising &gt; Widgets</strong>, click "Editar" (Edit).</li>
<li><strong>Add the snippet.</strong> Click "Agregar" (Add) and choose it.</li>
<li><strong>Set it up.</strong> Fill it in under <strong>Configuración del snippet</strong> and save it with <strong>Guardar Snippet</strong>.</li>
<li><strong>Order it.</strong> Drag it into position.</li>
</ol>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to set up payment methods in your widget
Slug: how-to-set-up-widget-payment-methods
Categoría: Widgets
Resumen: Learn how to choose frequencies, gateways and payment methods in your widget, and the order donors see them in.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-widget, required-and-suggested-snippets, how-to-set-up-the-donation-snippet, how-to-add-a-new-country-to-a-widget
--- CUERPO (HTML) ---
<p>Labels are shown as they appear in the Spanish version of the console.</p><h2>Before you start</h2>
<ul><li><strong>Connect the gateway</strong> in <strong>Ajustes de Organización &gt; Pasarelas de pago</strong> (Organization settings &gt; Payment gateways). The widget only shows connected gateways that accept the country's currency.</li></ul>
<h2>Step by step</h2>
<ol>
<li><strong>Open the Medio de pago snippet.</strong> In the widget editor, choose the country and click <strong>Medio de pago</strong>.</li>
<li><strong>Choose the frequencies.</strong> In <strong>Seleccionar periodicidades</strong>, check <strong>Única</strong>, <strong>Mensual</strong> and/or <strong>Anual</strong> (one-time, monthly, yearly).</li>
<li><strong>Choose the gateways.</strong> In <strong>Selecionar pasarelas de pago</strong>.</li>
<li><strong>Match method and frequency.</strong> In <strong>Empatar periodicidad y método de pago</strong>, check which frequencies each method is offered in.</li>
<li><strong>Order the methods.</strong> Drag them and mark the preselected one with "set default".</li>
<li><strong>Save.</strong> <strong>Guardar Snippet</strong> and then "Guardar Widget".</li>
</ol>
<h2>Frequently asked questions</h2>
<p><strong>Can I offer Pix or boleto as monthly?</strong> No. Pix, boleto and cash are offered only as <strong>Única</strong>, except Pix with Infopago, which also allows monthly.</p>
<p><strong>What happens if I change the country's currency?</strong> These settings are deleted and must be redone.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to set up the Donation snippet in your widget
Slug: how-to-set-up-the-donation-snippet
Categoría: Widgets
Resumen: Learn how to set up suggested amounts, a free amount field, images and one-time and monthly frequencies in the Donation snippet.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-widget, how-to-set-up-widget-payment-methods, scape-recurrent-one-time-donation-as-link, required-and-suggested-snippets
--- CUERPO (HTML) ---
<p>Labels are shown as they appear in the Spanish version of the console.</p><h2>Before you start</h2>
<ul><li><strong>Set up the payment method first.</strong> The Donation snippet frequencies come from the frequencies checked there.</li></ul>
<h2>Step by step</h2>
<ol>
<li><strong>Open the Donation snippet.</strong> In the widget editor, choose the country and click <strong>Donación</strong>.</li>
<li><strong>Choose the options.</strong> <strong>Quiero campo de monto</strong> (free amount field), <strong>No quiero sugerir cantidades.</strong> (don't suggest amounts), <strong>Quiero escribir una frase de solicitud para cada cantidad</strong> (a phrase per amount) and <strong>Quiero poner una imagen y descripción por cada cantidad</strong> (an image per amount).</li>
<li><strong>Set the amounts.</strong> Click "Configurar frecuencias" (Set up frequencies). On each tab add up to 4 amounts, mark the default with the star (required) and, optionally, a <strong>Mínimo</strong> (minimum). With several frequencies, choose the preselected one with <strong>Seleccionar frecuencia por defecto</strong>.</li>
<li><strong>Add images (optional).</strong> One per amount, with "Subir imagen" (Upload image) or from <strong>Galería</strong>: jpg, webp or png, recommended 150 × 150 pixels and up to 1 MB.</li>
<li><strong>Save.</strong> "Guardar" in the window and then <strong>Guardar Snippet</strong>.</li>
<li><strong>Order the frequencies (optional).</strong> In <strong>Orden de las frecuencias</strong>.</li>
</ol>
<h2>Frequently asked questions</h2>
<p><strong>How many amounts can I suggest?</strong> Up to 4 per frequency.</p>
<p><strong>Are amounts the same in every country?</strong> No. Each country has its own Donation snippet.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: Scape recurrent: show the one-time donation only as a link
Slug: scape-recurrent-one-time-donation-as-link
Categoría: Widgets
Resumen: Learn how to show only the monthly donation in your widget and leave the one-time donation as a link below the payment button.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-widget, how-to-set-up-the-donation-snippet, conversion-cards-one-time-to-recurring, how-to-set-up-widget-payment-methods
--- CUERPO (HTML) ---
<p>Labels are shown as they appear in the Spanish version of the console.</p><p>With this option, the form shows only the monthly donation and leaves the one-time option as a link. This pushes recurring giving without taking away the option to give once.</p>
<h2>Before you start</h2>
<ul><li><strong>In the Donation snippet</strong>, <strong>Mensual</strong> must be active with at least one amount, and <strong>Única</strong> must also be active.</li></ul>
<h2>Step by step</h2>
<ol>
<li><strong>Open the Donation snippet</strong> in the widget editor.</li>
<li><strong>Turn on the option.</strong> Check <strong>Mostrar la donación única solo como enlace debajo del botón de pago</strong> (show the one-time donation only as a link below the payment button).</li>
<li><strong>Save.</strong> <strong>Guardar Snippet</strong> and then "Guardar Widget".</li>
</ol>
<p>Donors will see only the monthly frequency and, below the payment button, the link <em>"Hacer donación única"</em> (Make a one-time donation).</p>
<h2>Frequently asked questions</h2>
<p><strong>Why doesn't the link appear?</strong> It only appears if the one-time frequency has amounts or if <strong>Quiero campo de monto</strong> is on.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: Conversion cards: from one-time to recurring donation
Slug: conversion-cards-one-time-to-recurring
Categoría: Widgets
Resumen: Learn how to set up the card that invites one-time donors to become monthly donors, in the form and after paying.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-widget, scape-recurrent-one-time-donation-as-link, cover-your-cost-donors-cover-costs, how-to-set-up-the-donation-snippet
--- CUERPO (HTML) ---
<p>Labels are shown as they appear in the Spanish version of the console.</p><h2>Before you start</h2>
<ul>
<li><strong>AFRUS must enable</strong> the <strong>Ofrecer única a recurrente</strong> (Offer one-time to recurring) snippet for your organization. It only exists in <strong>Transacción</strong> widgets.</li>
<li><strong>The monthly frequency</strong> must be enabled in the Donation snippet with at least one amount.</li>
</ul>
<h2>Step by step</h2>
<ol>
<li><strong>Add the snippet.</strong> In the widget editor, click "Agregar" and choose <strong>Ofrecer única a recurrente</strong>. It is placed right after Donation.</li>
<li><strong>Turn it on.</strong> Turn on <strong>Habilitar</strong> (Enable).</li>
<li><strong>Customize the card (optional).</strong> <strong>Título</strong>, <strong>Subtítulo</strong> and colors.</li>
<li><strong>Set the rates.</strong> <strong>Tasa 1 (%)</strong> and <strong>Tasa 2 (%)</strong>, whole numbers from 1 to 99 (default 50 and 25): the percentages of the one-time amount proposed as monthly.</li>
<li><strong>Save.</strong> <strong>Guardar Snippet</strong> and then "Guardar Widget".</li>
</ol>
<h2>What donors see</h2>
<ul>
<li><strong>During the form:</strong> the card <em>"Conviértete en donante mensual"</em> (Become a monthly donor) with two monthly amounts and the option to keep their one-time donation.</li>
<li><strong>After paying</strong> (one-time card donation through a gateway managed by AFRUS): <em>"Conviértelo en un regalo mensual"</em> (Make it a monthly gift). If they accept, a monthly subscription is also created; the donation already charged does not change.</li>
</ul>
<h2>Frequently asked questions</h2>
<p><strong>Does it work with PayPal or Pix?</strong> Only the in-form offer. The after-payment offer requires a card through a gateway managed by AFRUS.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: Cover your cost: let donors cover the costs
Slug: cover-your-cost-donors-cover-costs
Categoría: Widgets
Resumen: Learn how to turn on Cover Your Cost so donors can cover the fees and your organization receives the full amount.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-widget, conversion-cards-one-time-to-recurring, how-to-set-up-a-thank-you-page-in-the-widget, scape-recurrent-one-time-donation-as-link
--- CUERPO (HTML) ---
<p>Labels are shown as they appear in the Spanish version of the console.</p><p>With <strong>Cover Your Cost</strong>, donors can cover the gateway fee, so your organization receives the full donation amount.</p>
<h2>Before you start</h2>
<ul>
<li><strong>AFRUS must turn it on</strong> for your organization; it can't be turned on from the console.</li>
<li><strong>It is set up per gateway</strong>, not inside the widget.</li>
</ul>
<h2>Step by step</h2>
<ol>
<li><strong>Open the gateway.</strong> In <strong>Ajustes de Organización &gt; Pasarelas de pago</strong>.</li>
<li><strong>Turn it on.</strong> In <strong>Cover Your Cost</strong>, turn on <strong>Activar Cover Your Cost</strong>.</li>
<li><strong>Set the fee.</strong> <strong>Comisión de pasarela (%)</strong> (gateway fee), minimum 0.01. Together with the <strong>Comisión AFRUS (%)</strong> it must be under 80%.</li>
<li><strong>Choose whether it is preselected.</strong> With <strong>Preseleccionar la opción para el donante</strong>.</li>
<li><strong>Save the gateway.</strong> Repeat for each gateway that should offer it.</li>
</ol>
<p>In the widget's last step, donors will see <em>"Cubrir el 100% los costos de donación"</em> (Cover 100% of the donation costs) with the base donation, the approximate cost and the total.</p>
<h2>Frequently asked questions</h2>
<p><strong>Why is the total slightly more than the sum of the percentages?</strong> Because it is calculated so that, after fees, your organization receives at least the base amount, rounded up.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to set up a thank-you page in your widget
Slug: how-to-set-up-a-thank-you-page-in-the-widget
Categoría: Widgets
Resumen: Learn how to send donors, after giving, to your campaign's thank-you page or to the URL of your choice.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-widget, cover-your-cost-donors-cover-costs, advanced-widget-options, conversion-cards-one-time-to-recurring
--- CUERPO (HTML) ---
<p>The widget editor opens in a new tab. To open it, in <strong>Fundraising &gt; Widgets</strong> click "Editar" (Edit) on the widget's row.</p><p>Labels are shown as they appear in the Spanish version of the console.</p><h2>Step by step</h2>
<ol>
<li><strong>Open the panel.</strong> In the <strong>Editar</strong> tab, open the <strong>Avanzado</strong> (Advanced) panel and, inside it, <strong>Página de agradecimiento</strong> (Thank-you page).</li>
<li><strong>Option A: the campaign's page.</strong> Check <strong>Usa la página de agradecimiento de la campaña.</strong> (Use the campaign's thank-you page).</li>
<li><strong>Option B: your own URLs.</strong> Click "Configurar", turn on <strong>Habilitar página de agradecimiento</strong> and use a <strong>Página de agradecimiento general</strong> (general page) or a <strong>Página de agradecimiento personalizada</strong> (custom page), with URLs for successful and pending transactions, for one-time and recurring.</li>
<li><strong>Save.</strong> "Guardar" and then "Guardar Widget".</li>
</ol>
<h2>Frequently asked questions</h2>
<p><strong>What format must the URLs have?</strong> They must start with http:// or https:// and be under 255 characters.</p>
<p><strong>What if the donation is declined?</strong> It doesn't redirect to any custom page.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: Advanced widget options: captcha, analytics, Face to Face and more
Slug: advanced-widget-options
Categoría: Widgets
Resumen: Learn how to set up Recaptcha, Google Tag Manager, GA4 measurement protocol, Facebook CAPI and Face to Face in your widget.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-widget, how-to-set-up-a-thank-you-page-in-the-widget, how-to-embed-a-widget-on-your-website, cover-your-cost-donors-cover-costs
--- CUERPO (HTML) ---
<p>The widget editor opens in a new tab. To open it, in <strong>Fundraising &gt; Widgets</strong> click "Editar" (Edit) on the widget's row.</p><p>Labels are shown as they appear in the Spanish version of the console.</p><p>All these options are in the <strong>Avanzado</strong> (Advanced) panel and are saved with "Guardar Widget".</p>
<h2>Step by step</h2>
<ol>
<li><strong>Recaptcha.</strong> Turn on the switch so donors always type a 6-character verification code. Without it, the captcha can still appear on a suspicious attempt.</li>
<li><strong>Google Tag Manager 4.</strong> Paste your <strong>Código de seguimiento</strong> (container ID) to receive the donor journey events.</li>
<li><strong>Protocolo de medición</strong> (Measurement protocol). Fill in GA4's <strong>Measurement Id</strong> and <strong>Api secret</strong>: AFRUS sends events, including the purchase, also from the server.</li>
<li><strong>Facebook Capi.</strong> Fill in <strong>Pixel id</strong> and <strong>Access Token</strong>: AFRUS sends events to Meta from the browser and from the server.</li>
<li><strong>Face to Face</strong> (transaction widgets). For in-person donations: turn on <strong>Face to Face</strong> and fill in <strong>Correo del captador</strong> (fundraiser email, required) and <strong>Correo del supervisor</strong> (supervisor email). Browser autofill is turned off automatically.</li>
<li><strong>Save.</strong> Click "Guardar Widget".</li>
</ol>
<h2>Frequently asked questions</h2>
<p><strong>What do the fundraiser and supervisor receive?</strong> An email for every successful or failed donation in that widget.</p>
<p><strong>Is my landing page's Pixel set up here?</strong> No. A landing's Pixel and Google Analytics are set up in the landing.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to embed a widget on your website
Slug: how-to-embed-a-widget-on-your-website
Categoría: Widgets
Resumen: Learn how to copy your AFRUS widget's code and paste it on your website, with a custom width if you need one.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-a-widget, advanced-widget-options, how-to-set-up-a-thank-you-page-in-the-widget, cover-your-cost-donors-cover-costs
--- CUERPO (HTML) ---
<p>Labels are shown as they appear in the Spanish version of the console.</p><h2>Step by step</h2>
<ol>
<li><strong>Open the code.</strong> In <strong>Fundraising &gt; Widgets</strong>, click the code icon on the widget's row. <strong>Código del widget</strong> (Widget code) opens.</li>
<li><strong>Copy the code.</strong> Click "Copiar" (Copy).</li>
<li><strong>Paste it on your page.</strong> In an HTML block or component on your site. The widget will appear there.</li>
</ol>
<h2>If you need a different width</h2>
<p>In the widget editor, <strong>Instalar</strong> (Install) tab, set the width in <strong>Configura el ancho del formulario</strong> (px, %, em, rem or vw), click "Guardar Widget" and copy the <strong>Código de inserción</strong> (Embed code).</p>
<h2>Frequently asked questions</h2>
<p><strong>Do I need one code per country?</strong> No. The code is the same for all countries; the country is chosen automatically.</p>
<p><strong>Why isn't it receiving donations?</strong> Check that the widget's <strong>Estado</strong> (Status) switch is on.</p>
=== FIN ===
```

## Português

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: O que é um widget
Slug: o-que-e-um-widget
Categoría: Widgets
Resumen: Aprenda o que é um widget da AFRUS: um formulário de doação, cadastro ou pagamento montado por blocos e inserido no seu site.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-serve-um-widget, tipos-de-widget-na-afrus, como-mudar-os-estilos-do-widget, como-adicionar-um-novo-pais-a-um-widget, snippets-obrigatorios-e-sugeridos, como-configurar-os-metodos-de-pagamento-do-widget, como-configurar-o-snippet-doacao, scape-recurrent-doacao-unica-como-link, cards-de-conversao-unica-para-recorrente, cover-your-cost-doador-cobre-os-custos, como-configurar-uma-pagina-de-agradecimento-no-widget, opcoes-avancadas-do-widget, como-inserir-um-widget-no-seu-site
--- CUERPO (HTML) ---
<p><strong>Um widget é um formulário da AFRUS (de doação, de cadastro, de pagamento etc.) montado com blocos chamados snippets e inserido em qualquer site ou landing com um pequeno código.</strong></p>
<p>Cada widget tem um <strong>Objetivo</strong>, um ou mais países com seu idioma e moeda, e uma lista de snippets: informações pessoais, valores, meio de pagamento, termos e condições, botão etc.</p>
<h2>Onde encontrar</h2>
<p>Os nomes de tela aparecem como na versão em espanhol do console.</p><p>Em <strong>Fundraising &gt; Widgets</strong> você verá a tela <strong>Gestión de Widgets</strong> (Gestão de widgets), com o botão "Nuevo widget" (Novo widget), filtros (campanha, objetivo, status, padrão, etiqueta) e uma tabela com status, nome, data, objetivo, arrecadado, transações, assinaturas, visualizações e cadastros.</p>
<h2>Perguntas frequentes</h2>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Para que serve um widget
Slug: para-que-serve-um-widget
Categoría: Widgets
Resumen: Aprenda para que serve um widget: receber doações, captar cadastros, cobrar pagamentos e medir resultados no seu próprio site.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-um-widget, tipos-de-widget-na-afrus, como-mudar-os-estilos-do-widget, como-adicionar-um-novo-pais-a-um-widget
--- CUERPO (HTML) ---
<p>Um widget é um formulário da AFRUS que você insere no seu site ou landing. Veja o que ele permite fazer:</p>
<ul>
<li><strong>Receber doações no seu site.</strong> Únicas, mensais ou anuais, sem o doador sair da sua página.</li>
<li><strong>Captar cadastros (leads), vender produtos ou tickets e cobrar pagamentos.</strong> Cada uso tem seu tipo de widget.</li>
<li><strong>Falar com cada visitante no idioma e na moeda dele.</strong> O widget mostra o país de onde a pessoa navega, se você o configurou.</li>
<li><strong>Medir o desempenho.</strong> O <strong>Dashboard de Widget</strong> mostra visualizações, conversões e receita de cada formulário.</li>
<li><strong>Enviar as conversões para o Google e a Meta.</strong> Com Google Tag Manager, GA4, Pixel e Conversions API.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Quais tipos de widget existem e para que serve cada um
Slug: tipos-de-widget-na-afrus
Categoría: Widgets
Resumen: Aprenda quais tipos de widget (objetivos) a AFRUS oferece, para que serve cada um e como criar o que você precisa.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-um-widget, para-que-serve-um-widget, como-mudar-os-estilos-do-widget, como-adicionar-um-novo-pais-a-um-widget
--- CUERPO (HTML) ---
<p>Os nomes de tela aparecem como na versão em espanhol do console.</p><p>O tipo de widget é o seu <strong>Objetivo</strong>. Ele é escolhido na criação e define quais snippets são adicionados automaticamente. Os objetivos que você vê são os que a AFRUS habilitou para a sua organização.</p>
<ul>
<li><strong>Transacción</strong> (Transação): doações únicas, mensais ou anuais.</li>
<li><strong>Registros / Registro</strong> (Cadastro): captar dados de pessoas (leads), sem pagamento.</li>
<li><strong>Ofrece Misas / Regala Misas</strong> (Missas): formulários de missas e intenções.</li>
<li><strong>Pagos</strong> (Pagamentos): cobrar um pagamento com valor fixo ou com mínimo e máximo.</li>
<li><strong>Producto</strong> (Produto): vender produtos ou tickets de rifa com preço e estoque.</li>
<li><strong>Sign up</strong>: cadastro de uma organização com plano de preços.</li>
</ul>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra o editor.</strong> Em <strong>Fundraising &gt; Widgets</strong>, clique em "Nuevo widget". O editor abre em uma nova aba; lá, clique em "Nuevo formulario".</li>
<li><strong>Escolha o objetivo.</strong> Digite o <strong>Nombre del formulario</strong> (nome, até 50 caracteres), escolha o <strong>Objetivo</strong> e clique em "Crear" (Criar).</li>
<li><strong>Vincule uma campanha.</strong> Em <strong>Renderización</strong>, escolha pelo menos uma em <strong>Elige tus campañas</strong>. É obrigatório.</li>
<li><strong>Escolha como ele aparece.</strong> Em <strong>Mecanismo de renderización</strong>, escolha <strong>Estandar</strong> (incorporado na página) ou <strong>Popup</strong> (abre a partir de um botão; preencha <strong>Texto del botón Pop up</strong>).</li>
<li><strong>Configure e ative.</strong> Configure os snippets, clique em "Guardar Widget" (Salvar widget) e ative a chave <strong>Estado</strong> (Status).</li>
</ol>
<h2>Perguntas frequentes</h2>
<p><strong>Por que não consigo salvar?</strong> "Guardar Widget" mostra um botão vermelho <strong>Errores</strong> (Erros) com o motivo, por exemplo falta de campanha ou de termos e condições.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como mudar os estilos do widget
Slug: como-mudar-os-estilos-do-widget
Categoría: Widgets
Resumen: Aprenda a mudar o formato dos campos, as cores, a tipografia, o cabeçalho e o rodapé do seu widget da AFRUS.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-um-widget, tipos-de-widget-na-afrus, como-adicionar-um-novo-pais-a-um-widget, para-que-serve-um-widget
--- CUERPO (HTML) ---
<p>O editor do widget abre em uma nova aba. Para abri-lo, em <strong>Fundraising &gt; Widgets</strong> clique em "Editar" na linha do widget.</p><p>Os nomes de tela aparecem como na versão em espanhol do console.</p><h2>Passo a passo</h2>
<ol>
<li><strong>Abra o painel Estilo.</strong> Na aba <strong>Editar</strong> do editor, abra <strong>Estilo</strong>.</li>
<li><strong>Escolha o formato dos campos.</strong> Em <strong>Seleccione un estilo para el formulario</strong>: <strong>Cuadrado</strong>, <strong>Cuadrado redondeado</strong>, <strong>Redondeado</strong> ou <strong>Línea</strong> (quadrado, quadrado arredondado, arredondado, linha).</li>
<li><strong>Ajuste cores e tipografia.</strong> Em <strong>Estilo del formulario</strong>, mude a fonte, as cores principal, de botões, de fundo, de texto e de erro, a caixa, a borda e a sombra.</li>
<li><strong>Ajuste cabeçalho e rodapé.</strong> Em <strong>Encabezado</strong> mude a cor de fundo; em <strong>Pie de página</strong>, alinhamento, cores e tipografia. "REINICIAR" (Redefinir) volta aos valores de fábrica.</li>
<li><strong>Revise e salve.</strong> Veja o resultado em "Vista previa" (Pré-visualização) e clique em "Guardar Widget".</li>
</ol>
<h2>Perguntas frequentes</h2>
<p><strong>Posso ter estilos diferentes por país?</strong> Não. Os estilos valem para o widget inteiro.</p>
<p><strong>Onde mudo a largura?</strong> Na aba <strong>Instalar</strong> do editor.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como adicionar um novo país a um widget e para quê
Slug: como-adicionar-um-novo-pais-a-um-widget
Categoría: Widgets
Resumen: Aprenda a adicionar um país ao seu widget para mostrar a cada visitante seu idioma, sua moeda e seus próprios valores e gateways.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-um-widget, como-mudar-os-estilos-do-widget, snippets-obrigatorios-e-sugeridos, tipos-de-widget-na-afrus
--- CUERPO (HTML) ---
<p>Cada país do widget tem seu próprio idioma, moeda e snippets (valores, gateways, campos). Quem abre o widget vê o país de onde navega, se ele estiver configurado; se não, vê o país padrão (com estrela).</p>
<p>O editor do widget abre em uma nova aba. Para abri-lo, em <strong>Fundraising &gt; Widgets</strong> clique em "Editar" na linha do widget.</p><p>Os nomes de tela aparecem como na versão em espanhol do console.</p><h2>Passo a passo</h2>
<ol>
<li><strong>Adicione o país.</strong> Na coluna central, clique em <strong>Nuevo país</strong> (Novo país).</li>
<li><strong>Preencha idioma e moeda.</strong> Escolha <strong>Seleccione un país</strong> (Selecione um país), o <strong>Idioma</strong> (Español, English, Portugues, Italian ou Deutsch) e confira a <strong>Moneda</strong> (moeda). Em widgets de <strong>Pagos</strong>, escolha também o formato decimal.</li>
<li><strong>Adicione um rodapé (opcional).</strong> Até 250 caracteres.</li>
<li><strong>Salve.</strong> Clique em "Guardar" (Salvar). Você verá <em>"¡País añadido satisfactoriamente!"</em> (País adicionado com sucesso).</li>
<li><strong>Configure os snippets dele.</strong> O país começa só com os snippets obrigatórios. Configure valores e meio de pagamento e clique em "Guardar Widget".</li>
</ol>
<h2>Perguntas frequentes</h2>
<p><strong>Os valores são copiados de outro país?</strong> Não. Valores e gateways não são copiados entre países.</p>
<p><strong>Posso mudar a moeda depois?</strong> Sim, mas a configuração do snippet <strong>Medio de pago</strong> (Meio de pagamento) desse país é apagada e precisa ser refeita.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Quais snippets do widget são obrigatórios e quais são sugeridos
Slug: snippets-obrigatorios-e-sugeridos
Categoría: Widgets
Resumen: Aprenda quais snippets são obrigatórios em cada widget, quais são opcionais e como adicioná-los e ordená-los.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-um-widget, como-adicionar-um-novo-pais-a-um-widget, como-configurar-os-metodos-de-pagamento-do-widget, como-mudar-os-estilos-do-widget
--- CUERPO (HTML) ---
<p>Os nomes de tela aparecem como na versão em espanhol do console.</p><p>No editor, os snippets são <strong>obrigatórios</strong> ou <strong>opcionais</strong>. A AFRUS não marca snippets como "sugeridos": quais vale a pena usar depende do seu formulário.</p>
<h2>Obrigatórios</h2>
<ul>
<li><strong>Información personal</strong> (Informações pessoais): sempre vem primeiro.</li>
<li><strong>Términos y condiciones</strong> (Termos e condições): sem ele, com texto e URL, nenhum widget pode ser salvo. Em widgets de <strong>Registro</strong> é preciso adicioná-lo manualmente.</li>
<li><strong>Medio de pago</strong> (Meio de pagamento) e <strong>Botón</strong> (Botão): fixos no final.</li>
<li><strong>Conforme o objetivo:</strong> Doação, Tipos de missas, Pagamento genérico, Produto, ou Sign up com Endereço de cadastro e Modelo de preços.</li>
<li><strong>Os exigidos pelo gateway:</strong> adicionados automaticamente ao salvar o meio de pagamento, com o aviso <em>"¡IMPORTANTE! Este snippet es requerido por la pasarela de pago"</em> (exigido pelo gateway de pagamento).</li>
</ul>
<h2>Opcionais</h2>
<p>Imagem, Texto, Separador, Campo personalizado, Campo padrão, Endereço ou Endereço fixo, Documento, Oferecer única para recorrente, ID da campanha do Salesforce e, em missas, Imagem com texto, Intenção e Presentear intenção. Alguns só aparecem se a AFRUS os habilitou para a sua organização.</p>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra o editor do widget.</strong> Em <strong>Fundraising &gt; Widgets</strong>, clique em "Editar".</li>
<li><strong>Adicione o snippet.</strong> Clique em "Agregar" (Adicionar) e escolha-o.</li>
<li><strong>Configure-o.</strong> Preencha em <strong>Configuración del snippet</strong> e salve com <strong>Guardar Snippet</strong>.</li>
<li><strong>Ordene-o.</strong> Arraste-o para a posição desejada.</li>
</ol>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como configurar os métodos de pagamento do seu widget
Slug: como-configurar-os-metodos-de-pagamento-do-widget
Categoría: Widgets
Resumen: Aprenda a escolher periodicidades, gateways e métodos de pagamento no seu widget, e em que ordem o doador os vê.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-um-widget, snippets-obrigatorios-e-sugeridos, como-configurar-o-snippet-doacao, como-adicionar-um-novo-pais-a-um-widget
--- CUERPO (HTML) ---
<p>Os nomes de tela aparecem como na versão em espanhol do console.</p><h2>Antes de começar</h2>
<ul><li><strong>Conecte o gateway</strong> em <strong>Ajustes de Organización &gt; Pasarelas de pago</strong> (Ajustes da organização &gt; Gateways de pagamento). O widget mostra apenas os gateways conectados que aceitam a moeda do país.</li></ul>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra o snippet Medio de pago.</strong> No editor do widget, escolha o país e clique em <strong>Medio de pago</strong>.</li>
<li><strong>Escolha as periodicidades.</strong> Em <strong>Seleccionar periodicidades</strong>, marque <strong>Única</strong>, <strong>Mensual</strong> e/ou <strong>Anual</strong>.</li>
<li><strong>Escolha os gateways.</strong> Em <strong>Selecionar pasarelas de pago</strong>.</li>
<li><strong>Combine método e periodicidade.</strong> Em <strong>Empatar periodicidad y método de pago</strong>, marque em quais periodicidades cada método é oferecido.</li>
<li><strong>Ordene os métodos.</strong> Arraste-os e marque o pré-selecionado com "set default".</li>
<li><strong>Salve.</strong> <strong>Guardar Snippet</strong> e depois "Guardar Widget".</li>
</ol>
<h2>Perguntas frequentes</h2>
<p><strong>Posso oferecer Pix ou boleto como mensal?</strong> Não. Pix, boleto e dinheiro são oferecidos só como <strong>Única</strong>, exceto Pix com Infopago, que também aceita mensal.</p>
<p><strong>O que acontece se eu mudar a moeda do país?</strong> Essa configuração é apagada e precisa ser refeita.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como configurar o snippet Doação do seu widget
Slug: como-configurar-o-snippet-doacao
Categoría: Widgets
Resumen: Aprenda a configurar valores sugeridos, valor livre, imagens e frequências única e mensal no snippet Doação.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-um-widget, como-configurar-os-metodos-de-pagamento-do-widget, scape-recurrent-doacao-unica-como-link, snippets-obrigatorios-e-sugeridos
--- CUERPO (HTML) ---
<p>Os nomes de tela aparecem como na versão em espanhol do console.</p><h2>Antes de começar</h2>
<ul><li><strong>Configure primeiro o meio de pagamento.</strong> As frequências do snippet Doação vêm das periodicidades marcadas lá.</li></ul>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra o snippet Donación.</strong> No editor do widget, escolha o país e clique em <strong>Donación</strong> (Doação).</li>
<li><strong>Escolha as opções.</strong> <strong>Quiero campo de monto</strong> (valor livre), <strong>No quiero sugerir cantidades.</strong> (não sugerir valores), <strong>Quiero escribir una frase de solicitud para cada cantidad</strong> (uma frase por valor) e <strong>Quiero poner una imagen y descripción por cada cantidad</strong> (uma imagem por valor).</li>
<li><strong>Configure os valores.</strong> Clique em "Configurar frecuencias". Em cada aba, adicione até 4 valores, marque o padrão com a estrela (obrigatório) e, se quiser, um <strong>Mínimo</strong>. Com várias frequências, escolha a pré-selecionada com <strong>Seleccionar frecuencia por defecto</strong>.</li>
<li><strong>Adicione imagens (opcional).</strong> Uma por valor, com "Subir imagen" ou da <strong>Galería</strong>: jpg, webp ou png, recomendado 150 × 150 pixels e até 1 MB.</li>
<li><strong>Salve.</strong> "Guardar" na janela e depois <strong>Guardar Snippet</strong>.</li>
<li><strong>Ordene as frequências (opcional).</strong> Em <strong>Orden de las frecuencias</strong>.</li>
</ol>
<h2>Perguntas frequentes</h2>
<p><strong>Quantos valores posso sugerir?</strong> Até 4 por frequência.</p>
<p><strong>Os valores são iguais em todos os países?</strong> Não. Cada país tem seu próprio snippet Doação.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Scape recurrent: mostre a doação única só como link
Slug: scape-recurrent-doacao-unica-como-link
Categoría: Widgets
Resumen: Aprenda a mostrar só a doação mensal no seu widget e deixar a doação única como um link abaixo do botão de pagamento.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-um-widget, como-configurar-o-snippet-doacao, cards-de-conversao-unica-para-recorrente, como-configurar-os-metodos-de-pagamento-do-widget
--- CUERPO (HTML) ---
<p>Os nomes de tela aparecem como na versão em espanhol do console.</p><p>Com esta opção, o formulário mostra apenas a doação mensal e deixa a única como um link. Assim você incentiva a recorrência sem tirar do doador a opção de doar uma vez.</p>
<h2>Antes de começar</h2>
<ul><li><strong>No snippet Doação</strong>, <strong>Mensual</strong> precisa estar ativa com pelo menos um valor, e <strong>Única</strong> também precisa estar ativa.</li></ul>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra o snippet Donación</strong> no editor do widget.</li>
<li><strong>Ative a opção.</strong> Marque <strong>Mostrar la donación única solo como enlace debajo del botón de pago</strong> (mostrar a doação única só como link abaixo do botão de pagamento).</li>
<li><strong>Salve.</strong> <strong>Guardar Snippet</strong> e depois "Guardar Widget".</li>
</ol>
<p>O doador verá apenas a frequência mensal e, abaixo do botão de pagamento, o link <em>"Hacer donación única"</em> (Fazer doação única).</p>
<h2>Perguntas frequentes</h2>
<p><strong>Por que o link não aparece?</strong> Ele só aparece se a frequência Única tiver valores ou se <strong>Quiero campo de monto</strong> estiver ativo.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Cards de conversão: de doação única para recorrente
Slug: cards-de-conversao-unica-para-recorrente
Categoría: Widgets
Resumen: Aprenda a configurar o cartão que convida quem doa uma vez a se tornar doador mensal, no formulário e depois do pagamento.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-um-widget, scape-recurrent-doacao-unica-como-link, cover-your-cost-doador-cobre-os-custos, como-configurar-o-snippet-doacao
--- CUERPO (HTML) ---
<p>Os nomes de tela aparecem como na versão em espanhol do console.</p><h2>Antes de começar</h2>
<ul>
<li><strong>A AFRUS precisa habilitar</strong> o snippet <strong>Ofrecer única a recurrente</strong> (Oferecer única para recorrente) para a sua organização. Ele só existe em widgets de <strong>Transacción</strong>.</li>
<li><strong>A frequência mensal</strong> precisa estar habilitada no snippet Doação com pelo menos um valor.</li>
</ul>
<h2>Passo a passo</h2>
<ol>
<li><strong>Adicione o snippet.</strong> No editor do widget, clique em "Agregar" e escolha <strong>Ofrecer única a recurrente</strong>. Ele é colocado logo depois de Doação.</li>
<li><strong>Ative-o.</strong> Ative <strong>Habilitar</strong>.</li>
<li><strong>Personalize o cartão (opcional).</strong> <strong>Título</strong>, <strong>Subtítulo</strong> e cores.</li>
<li><strong>Defina as taxas.</strong> <strong>Tasa 1 (%)</strong> e <strong>Tasa 2 (%)</strong>, inteiros de 1 a 99 (vêm com 50 e 25): as porcentagens do valor único propostas como mensal.</li>
<li><strong>Salve.</strong> <strong>Guardar Snippet</strong> e depois "Guardar Widget".</li>
</ol>
<h2>O que o doador vê</h2>
<ul>
<li><strong>Durante o formulário:</strong> o cartão <em>"Conviértete en donante mensual"</em> (Torne-se doador mensal) com dois valores mensais e a opção de manter a doação única.</li>
<li><strong>Depois de pagar</strong> (doação única com cartão em um gateway gerenciado pela AFRUS): <em>"Conviértelo en un regalo mensual"</em> (Transforme em uma doação mensal). Se aceitar, é criada também uma assinatura mensal; a doação já cobrada não muda.</li>
</ul>
<h2>Perguntas frequentes</h2>
<p><strong>Funciona com PayPal ou Pix?</strong> Só a oferta dentro do formulário. A oferta depois do pagamento exige cartão em um gateway gerenciado pela AFRUS.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Cover your cost: o doador cobre os custos
Slug: cover-your-cost-doador-cobre-os-custos
Categoría: Widgets
Resumen: Aprenda a ativar o Cover Your Cost para que o doador cubra as taxas e sua organização receba o valor integral.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-um-widget, cards-de-conversao-unica-para-recorrente, como-configurar-uma-pagina-de-agradecimento-no-widget, scape-recurrent-doacao-unica-como-link
--- CUERPO (HTML) ---
<p>Os nomes de tela aparecem como na versão em espanhol do console.</p><p>Com <strong>Cover Your Cost</strong>, o doador pode cobrir a taxa do gateway, para que sua organização receba o valor integral da doação.</p>
<h2>Antes de começar</h2>
<ul>
<li><strong>A AFRUS precisa ativá-lo</strong> para a sua organização; não dá para ativar pelo console.</li>
<li><strong>Ele é configurado por gateway</strong>, não dentro do widget.</li>
</ul>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra o gateway.</strong> Em <strong>Ajustes de Organización &gt; Pasarelas de pago</strong>.</li>
<li><strong>Ative a opção.</strong> Em <strong>Cover Your Cost</strong>, ative <strong>Activar Cover Your Cost</strong>.</li>
<li><strong>Defina a taxa.</strong> <strong>Comisión de pasarela (%)</strong> (taxa do gateway), mínimo 0.01. Somada à <strong>Comisión AFRUS (%)</strong> precisa ser menor que 80%.</li>
<li><strong>Escolha se vem pré-selecionada.</strong> Com <strong>Preseleccionar la opción para el donante</strong>.</li>
<li><strong>Salve o gateway.</strong> Repita em cada gateway que deve oferecê-lo.</li>
</ol>
<p>Na última etapa do widget, o doador verá <em>"Cubrir el 100% los costos de donación"</em> (Cobrir 100% dos custos da doação) com a doação base, o custo aproximado e o total.</p>
<h2>Perguntas frequentes</h2>
<p><strong>Por que o total é um pouco maior que a soma das porcentagens?</strong> Porque ele é calculado para que, depois das taxas, sua organização receba pelo menos o valor base, arredondado para cima.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como configurar uma página de agradecimento no seu widget
Slug: como-configurar-uma-pagina-de-agradecimento-no-widget
Categoría: Widgets
Resumen: Aprenda a levar o doador, depois de doar, à página de agradecimento da sua campanha ou à URL que você escolher.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-um-widget, cover-your-cost-doador-cobre-os-custos, opcoes-avancadas-do-widget, cards-de-conversao-unica-para-recorrente
--- CUERPO (HTML) ---
<p>O editor do widget abre em uma nova aba. Para abri-lo, em <strong>Fundraising &gt; Widgets</strong> clique em "Editar" na linha do widget.</p><p>Os nomes de tela aparecem como na versão em espanhol do console.</p><h2>Passo a passo</h2>
<ol>
<li><strong>Abra o painel.</strong> Na aba <strong>Editar</strong>, abra o painel <strong>Avanzado</strong> (Avançado) e, dentro dele, <strong>Página de agradecimiento</strong> (Página de agradecimento).</li>
<li><strong>Opção A: a da campanha.</strong> Marque <strong>Usa la página de agradecimiento de la campaña.</strong> (Usar a página de agradecimento da campanha).</li>
<li><strong>Opção B: suas URLs.</strong> Clique em "Configurar", ative <strong>Habilitar página de agradecimiento</strong> e use uma <strong>Página de agradecimiento general</strong> (página geral) ou uma <strong>Página de agradecimiento personalizada</strong> (personalizada), com URLs para transação bem-sucedida e pendente, em únicas e recorrentes.</li>
<li><strong>Salve.</strong> "Guardar" e depois "Guardar Widget".</li>
</ol>
<h2>Perguntas frequentes</h2>
<p><strong>Qual formato as URLs devem ter?</strong> Devem começar com http:// ou https:// e ter menos de 255 caracteres.</p>
<p><strong>E se a doação for recusada?</strong> Não há redirecionamento para nenhuma página personalizada.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Opções avançadas do widget: captcha, analytics, Face to Face e mais
Slug: opcoes-avancadas-do-widget
Categoría: Widgets
Resumen: Aprenda a configurar Recaptcha, Google Tag Manager, protocolo de medição GA4, Facebook CAPI e Face to Face no seu widget.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-um-widget, como-configurar-uma-pagina-de-agradecimento-no-widget, como-inserir-um-widget-no-seu-site, cover-your-cost-doador-cobre-os-custos
--- CUERPO (HTML) ---
<p>O editor do widget abre em uma nova aba. Para abri-lo, em <strong>Fundraising &gt; Widgets</strong> clique em "Editar" na linha do widget.</p><p>Os nomes de tela aparecem como na versão em espanhol do console.</p><p>Todas estas opções ficam no painel <strong>Avanzado</strong> (Avançado) e são salvas com "Guardar Widget".</p>
<h2>Passo a passo</h2>
<ol>
<li><strong>Recaptcha.</strong> Ative a chave para que o doador sempre digite um código de verificação de 6 caracteres. Sem ela, o captcha ainda pode aparecer em uma tentativa suspeita.</li>
<li><strong>Google Tag Manager 4.</strong> Cole o seu <strong>Código de seguimiento</strong> (ID do contêiner) para receber os eventos da jornada do doador.</li>
<li><strong>Protocolo de medición</strong> (Protocolo de medição). Preencha <strong>Measurement Id</strong> e <strong>Api secret</strong> do GA4: a AFRUS envia os eventos, incluindo a compra, também a partir do servidor.</li>
<li><strong>Facebook Capi.</strong> Preencha <strong>Pixel id</strong> e <strong>Access Token</strong>: a AFRUS envia os eventos à Meta pelo navegador e pelo servidor.</li>
<li><strong>Face to Face</strong> (widgets de transação). Para doações presenciais: ative <strong>Face to Face</strong> e preencha <strong>Correo del captador</strong> (e-mail do captador, obrigatório) e <strong>Correo del supervisor</strong> (e-mail do supervisor). O preenchimento automático do navegador é desativado sozinho.</li>
<li><strong>Salve.</strong> Clique em "Guardar Widget".</li>
</ol>
<h2>Perguntas frequentes</h2>
<p><strong>O que o captador e o supervisor recebem?</strong> Um e-mail para cada doação bem-sucedida ou com falha desse widget.</p>
<p><strong>O Pixel da minha landing é configurado aqui?</strong> Não. O Pixel e o Google Analytics de uma landing são configurados na landing.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como inserir um widget no seu site
Slug: como-inserir-um-widget-no-seu-site
Categoría: Widgets
Resumen: Aprenda a copiar o código do seu widget da AFRUS e colá-lo no seu site, com largura personalizada se precisar.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-um-widget, opcoes-avancadas-do-widget, como-configurar-uma-pagina-de-agradecimento-no-widget, cover-your-cost-doador-cobre-os-custos
--- CUERPO (HTML) ---
<p>Os nomes de tela aparecem como na versão em espanhol do console.</p><h2>Passo a passo</h2>
<ol>
<li><strong>Abra o código.</strong> Em <strong>Fundraising &gt; Widgets</strong>, clique no ícone de código da linha do widget. Abre <strong>Código del widget</strong> (Código do widget).</li>
<li><strong>Copie o código.</strong> Clique em "Copiar".</li>
<li><strong>Cole na sua página.</strong> Em um bloco ou componente HTML do seu site. O widget aparecerá ali.</li>
</ol>
<h2>Se precisar de outra largura</h2>
<p>No editor do widget, aba <strong>Instalar</strong>, defina a largura em <strong>Configura el ancho del formulario</strong> (px, %, em, rem ou vw), clique em "Guardar Widget" e copie o <strong>Código de inserción</strong> (código de inserção).</p>
<h2>Perguntas frequentes</h2>
<p><strong>Preciso de um código por país?</strong> Não. O código é o mesmo para todos os países; o país é escolhido automaticamente.</p>
<p><strong>Por que ele não recebe doações?</strong> Confira se a chave <strong>Estado</strong> do widget está ativa.</p>
=== FIN ===
```
