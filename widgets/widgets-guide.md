# Guía de Widgets

Después de leer esta guía sabrás qué es un widget, qué tipos existen y cómo configurarlo de punta a punta: estilos, países, snippets, métodos de pago, montos, ofertas de recurrencia, página de agradecimiento, opciones avanzadas e inserción en tu sitio web.

*Módulo: Widgets · Menú: **Fundraising > Widgets** · Audiencia: equipos de recaudación, marketing digital y web*

---

## Qué es un widget

**Un widget es un formulario de AFRUS (de transacción, de registro, de producto) que se arma por bloques llamados snippets y se inserta en cualquier sitio web o landing con un pequeño código.**

Cada widget tiene un **Objetivo** (por ejemplo, transacción o registro), uno o varios países con su idioma y moneda, y una lista de snippets: información personal, montos, medio de pago, términos y condiciones, botón, etc.

En **Fundraising > Widgets** verás la pantalla **Gestión de Widgets**, con el botón "Nuevo widget", filtros (**Campaña**, **Objetivo**, **Estado**, **Por defecto**, **Etiqueta**) y una tabla con **Estado**, **Nombre**, **Fecha**, **Objetivo**, **Recaudado**, **Transacciones**, **Suscripciones**, **Vistas** y **Registros**.

## Para qué sirve

- **Recibir donaciones desde tu sitio.** Únicas, mensuales o anuales, sin que el donante salga de tu página.
- **Captar registros (leads) y vender productos o tickets.** Cada uso tiene su propio tipo de widget.
- **Hablarle a cada visitante en su idioma y su moneda.** El widget muestra el país desde donde navega la persona, si lo configuraste.
- **Medir el rendimiento.** El **Dashboard de Widget** muestra vistas, conversiones e ingresos de cada formulario.
- **Enviar las conversiones a Google y a Meta.** Con Google Tag Manager, GA4, Pixel y Conversions API.

## Antes de empezar

- **Permisos.** Para ver el botón "Nuevo widget" necesitas el permiso de edición de formularios de donación o de leads.
- **El editor se abre en una pestaña nueva.** "Nuevo widget" y "Editar" abren el editor en una pestaña nueva del navegador. Ahí el botón de crear dice "Nuevo formulario".
- **Cómo está organizado el editor.** Tiene dos pestañas, **Editar** e **Instalar**. En **Editar**: a la izquierda, el objetivo y los paneles **Renderización**, **Estilo** y **Avanzado**; al centro, los países ("Nuevo país"), los snippets ("Agregar") y "Vista previa"; a la derecha, **Configuración del snippet**, con el botón de guardar (**Guardar Snippet**). Arriba, el nombre del widget, el interruptor **Estado** y "Guardar Widget".
- **Pasarelas conectadas.** Para cobrar, la pasarela tiene que estar conectada en **Ajustes de Organización > Pasarelas de pago**.

---

# Paso a paso

## Qué tipos de widgets existen y para qué se usa cada uno

El tipo de widget es su **Objetivo**. Se elige al crearlo y define qué snippets se agregan solos y qué opciones aparecen. Los objetivos que ves son los que AFRUS tiene habilitados para tu organización.

| Objetivo | Para qué se usa | Snippets que se agregan solos |
|---|---|---|
| **Transacción** | Donaciones únicas, mensuales o anuales | Información personal, Donación, Términos y condiciones, Medio de pago, Botón |
| **Registro** | Captar datos de personas (leads), sin pago | Información personal, Botón (Términos y condiciones hay que agregarlo para poder guardar) |
| **Producto** | Vender productos o tickets de rifa con precio y stock | Información personal, Producto, Términos y condiciones, Medio de pago, Botón |

Para crear un widget del tipo que necesitas:

1. **Abre el editor.** En **Fundraising > Widgets**, haz clic en "Nuevo widget". Se abre en una pestaña nueva; ahí haz clic en "Nuevo formulario".
   <!-- captura pendiente: que-tipos-de-widgets-existen-01 — ventana Selecciona el objetivo de tu formulario -->
2. **Elige el objetivo.** En la ventana **Selecciona el objetivo de tu formulario**, escribe el **Nombre del formulario** (máximo 50 caracteres), elige el **Objetivo** y haz clic en "Crear". Verás *"¡Widget creado satisfactoriamente!"* y el editor se abre solo.
3. **Vincula una campaña.** En el panel **Renderización**, elige al menos una campaña en **Elige tus campañas**. Es obligatorio para poder guardar.
4. **Elige cómo se muestra.** En el panel **Renderización**, en **Mecanismo de renderización**, elige **Estandar** (el formulario se ve incrustado en la página) o **Popup** (se abre desde un botón; en ese caso completa **Texto del botón Pop up**). En el mismo panel puedes activar el selector de idiomas, el selector de países y la barra de progreso.
5. **Configura los snippets y guarda.** Guarda cada snippet con **Guardar Snippet** y el widget con "Guardar Widget". Luego activa el interruptor **Estado** para que quede activo.

Si falta algo, "Guardar Widget" muestra un botón rojo **Errores** con el motivo, por ejemplo *"Debe seleccionar al menos una campaña en la pestaña de configuración"* o *"Debe configurar los términos y condiciones para poder guardar el widget"*.

## Cómo crear un widget de producto

Un widget de producto sirve para vender productos o tickets de rifa con precio y stock.

1. **Crea el widget con el objetivo Producto.** En **Fundraising > Widgets**, haz clic en "Nuevo widget" y, en la pestaña nueva, en "Nuevo formulario". Escribe el **Nombre del formulario**, elige el **Objetivo** **Producto** y haz clic en "Crear". El editor agrega solos los snippets **Información personal**, **Producto**, **Términos y condiciones**, **Medio de pago** y **Botón**.
2. **Vincula una campaña.** En el panel **Renderización**, elige al menos una campaña en **Elige tus campañas**. Es obligatorio para poder guardar.
3. **Agrega el producto.** Abre el snippet **Producto** y haz clic en "Agregar Producto".
4. **Elige el tipo de producto y completa sus datos.** En **Tipo de Producto**, elige qué vas a vender y completa el nombre, la descripción, el precio y el stock del producto. Si vas a vender números de una rifa, elige **Ticket** y luego tu rifa en **Seleccionar Ticket**: el nombre, la descripción y el stock se completan solos y solo debes escribir el **Precio del producto** (el precio de cada ticket). Antes debes haber creado la rifa en **Fundraising > Tickets** (ver la [Guía de Tickets](../tickets/tickets-guide.md)).
5. **Confirma el producto.** Haz clic en "Agregar Producto". Verás *"¡Producto agregado satisfactoriamente!"*.
6. **Completa el resto y guarda.** Configura **Términos y condiciones** y **Medio de pago** (ver "Cómo configurar los métodos de pago en tu widget"), guarda cada snippet con **Guardar Snippet** y el widget con "Guardar Widget". Luego activa el interruptor **Estado**.

> **Importante:** en un mismo snippet **Producto** no se pueden mezclar productos normales con tickets (*"No se pueden mezclar tipos de productos"*), y cada widget admite una sola rifa.

## Cómo cambiar los estilos del widget

1. **Abre el editor del widget.** En **Fundraising > Widgets**, haz clic en "Editar" en la fila del widget. Se abre en una pestaña nueva.
2. **Elige la forma de los campos.** En la pestaña **Editar**, panel **Estilo**, en **Seleccione un estilo para el formulario** elige **Cuadrado**, **Cuadrado redondeado**, **Redondeado** o **Línea**.
   <!-- captura pendiente: como-cambiar-los-estilos-del-widget-02 — panel Estilo -->
3. **Ajusta colores y tipografía.** Abre **Estilo del formulario** y cambia la **Familia tipográfica** (Roboto, Arial, Calibri, Univers LT Pro), el **Color principal**, **Color de botones**, **Color de fondo**, **Color de texto**, **Color del texto de error**, **Color de fondo de la caja**, **Color del texto de la caja**, el **Borde de la caja**, el **Borde** (con **Radio del border**) y la **Sombra**. Así el formulario se ve como parte de tu marca.
4. **Ajusta encabezado y pie.** En **Encabezado** cambia el **Color de fondo**. En **Pie de página** ajusta la alineación, el **Color de texto**, el color del texto de seguridad y la tipografía. El botón "REINICIAR" vuelve a los valores de fábrica.
5. **Revisa y guarda.** Mira el resultado con "Vista previa" y haz clic en "Guardar Widget".

Al terminar verás los nuevos estilos en la vista previa y en el widget publicado.

> **Importante:** los estilos son del widget completo, no de cada país. El ancho del formulario se define en la pestaña **Instalar** (ver "Cómo insertar un widget en tu sitio web").

> **¿Se puede deshacer?** Sí. Vuelve a cambiar los valores, o usa "REINICIAR" en **Pie de página** para volver a los valores de fábrica de esa sección.

## Cómo agregar un nuevo país y para qué sirve

**Para qué sirve:** cada país del widget tiene su propio **Idioma**, su propia **Moneda** y su propia lista de snippets (montos, pasarelas, campos). Cuando alguien abre el widget, ve el país desde donde navega, si está configurado; si no, ve el país por defecto (marcado con estrella). Si activas **Habilitar el selector de paises en este formulario**, el donante también puede cambiar de país.

1. **Abre el editor del widget.** En **Fundraising > Widgets**, haz clic en "Editar".
2. **Agrega el país.** En la columna central, haz clic en la tarjeta **Nuevo país**.
   <!-- captura pendiente: como-agregar-un-nuevo-pais-02 — ventana Idioma y moneda -->
3. **Completa idioma y moneda.** En **Idioma y moneda**, elige **Seleccione un país**, el **Idioma** (Español, English, Portugues, Italian o Deutsch) y revisa la **Moneda** (se completa sola con la del país, pero puedes cambiarla).
4. **Agrega un pie de página (opcional).** Escribe un texto de **Pie de página** de hasta 250 caracteres.
5. **Guarda el país.** Haz clic en "Guardar". Verás *"¡País añadido satisfactoriamente!"*.
6. **Configura sus snippets.** El país nuevo empieza sin snippets propios: al abrirlo, el editor le agrega solo los obligatorios de su objetivo. Configura montos y medio de pago, y haz clic en "Guardar Widget".

> **Importante:** los montos y las pasarelas de los otros países **no se copian**. Configúralos de nuevo para el país nuevo.

> **Importante:** si después cambias la moneda de un país, se borra la configuración de su snippet **Medio de pago** (pasarelas y periodicidades) y tendrás que volver a configurarla.

Con el menú de tres puntos de cada país puedes usar **Seleccionar por defecto**, **Editar** y **Eliminar**. Al editar, puedes cambiar idioma, moneda, formato decimal y pie de página, pero no el país. Un país por defecto no se puede eliminar, y no se puede agregar dos veces el mismo país (*"El País ya existe en este Widget"*).

> **¿Se puede deshacer?** No. Eliminar un país no se puede deshacer.

## Cuáles son los snippets obligatorios y sugeridos

En el editor, los snippets son **obligatorios** u **opcionales**. AFRUS no marca snippets como "sugeridos": cuáles conviene usar depende de tu formulario.

**Obligatorios** (el editor los agrega solo y no deja borrarlos):

- **Información personal**: siempre va primero.
- **Términos y condiciones**: sin este snippet, configurado con texto y URL, no se puede guardar ningún widget. Se agrega solo en todos los objetivos menos **Registro**, donde hay que agregarlo con "Agregar".
- **Medio de pago** y el botón final (**Botón**): van fijos al final y no se pueden mover. **Medio de pago** se agrega en los objetivos Transacción y Producto.
- Según el objetivo: **Donación** (Transacción) o **Producto** (Producto).
- **Los que exige la pasarela:** al guardar **Medio de pago**, el editor agrega solo los campos que pide cada pasarela, con el aviso *"¡IMPORTANTE! Este snippet es requerido por la pasarela de pago"*. Pueden ser nombre, apellido o email, **Dirección** (no se exige en Brasil), **Documento** (no se exige con PayPal ni con débito directo; con AvalPay siempre se exigen **Documento** y teléfono) y otros campos como teléfono, género, fecha de nacimiento, país, organización o código postal.

**Opcionales:** **Imagen**, **Texto**, **Separador** (divide el formulario en pasos), **Campo personalizado**, **Campo predeterminado**, **Dirección** o **Dirección Fija** (no puedes usar ambos), **Documento**, **Ofrecer única a recurrente**, **ID de la campaña de Salesforce** (no se ve en el formulario). Algunos solo aparecen si AFRUS los habilitó para tu organización.

Para agregar un snippet:

1. **Abre el editor del widget** y el país que quieres configurar.
2. **Agrega el snippet.** En la columna central, haz clic en "Agregar" y elige el snippet.
3. **Configúralo.** Haz clic sobre él, complétalo en **Configuración del snippet** y guárdalo con **Guardar Snippet**.
4. **Ordénalo.** Arrástralo a la posición que quieras.

La mayoría de los snippets solo se pueden agregar una vez por país; **Texto**, **Imagen**, **Separador**, **Campo personalizado** y **Campo predeterminado** se pueden repetir. Un snippet con borde rojo y un icono de alerta tiene la configuración incompleta o inválida.

## Cómo configurar los métodos de pago en tu widget

**Antes de empezar:** la pasarela tiene que estar conectada en **Ajustes de Organización > Pasarelas de pago**. En el snippet solo aparecen las pasarelas conectadas que aceptan la moneda del país.

1. **Abre el snippet Medio de pago.** En el editor del widget, elige el país y haz clic en el snippet **Medio de pago**.
   <!-- captura pendiente: como-configurar-los-metodos-de-pago-01 — snippet Medio de pago -->
2. **Elige las periodicidades.** En **Seleccionar periodicidades** marca **Única**, **Mensual** y/o **Anual** (al menos una).
3. **Elige las pasarelas.** En **Selecionar pasarelas de pago** elige una o varias.
4. **Empata método y periodicidad.** En **Empatar periodicidad y método de pago**, marca para cada pasarela y cada método (tarjeta, Pix, boleto, etc.) en qué periodicidades se ofrece.
5. **Ordena los métodos.** En **Orden de los métodos de pago Única / Mensual / Anual**, arrastra los métodos. Con el botón "set default" marcas el método preseleccionado (aparece con una estrella).
6. **Guarda.** Haz clic en **Guardar Snippet** y después en "Guardar Widget".

Al terminar, el donante verá solo los métodos habilitados para la periodicidad que eligió, en el orden que definiste.

- Un mismo método no puede quedar asignado a dos pasarelas en la misma periodicidad.
- Hay métodos que solo se muestran para ciertos países.
- Cambiar la moneda del país borra esta configuración.

## Cómo configurar el snippet Donación (montos, imágenes, única y mensual)

**Antes de empezar:** configura primero **Medio de pago**. Las frecuencias del snippet Donación (Única / Mensual / Anual) salen de las periodicidades que marcaste ahí. El editor lo avisa: *"IMPORTANTE: Para realizar sugerencias de cantidades, es imprescindible haber configurado previamente el snippet de 'MEDIOS DE PAGO'."*

1. **Abre el snippet Donación.** En el editor del widget, elige el país y haz clic en **Donación**.
2. **Elige las opciones.** Marca las que necesites:
   - **Quiero campo de monto**: un campo libre para que el donante escriba su monto. También te deja cambiar el **Texto personalizado para el campo de monto libre** (hasta 250 caracteres).
   - **No quiero sugerir cantidades.**: oculta los botones de montos (solo con el campo de monto activo).
   - **Quiero escribir una frase de solicitud para cada cantidad**: con su color de fondo.
   - **Quiero poner una imagen y descripción por cada cantidad**.
3. **Configura los montos por frecuencia.** Haz clic en "Configurar frecuencias". En la ventana **Selecciones las cantidades por frecuencias**, en cada pestaña:
   - agrega hasta 4 montos con "Agregar cantidad";
   - marca con la estrella el monto predeterminado (uno por frecuencia, obligatorio);
   - si quieres, fija un monto **Mínimo** y cambia el nombre que ve el donante con **Editar texto de frecuencía**;
   - si hay varias frecuencias, elige la preseleccionada con **Seleccionar frecuencia por defecto**.
   <!-- captura pendiente: configuracion-del-snippet-donacion-03 — ventana Selecciones las cantidades por frecuencias -->
4. **Agrega imágenes (si las activaste).** Sube una imagen por monto con "Subir imagen" o elígela desde **Galería**, y escribe una descripción opcional. Usa jpg, webp o png, máximo recomendado de 150 × 150 píxeles y 1 MB.
5. **Guarda.** Haz clic en "Guardar" dentro de la ventana y después en **Guardar Snippet**.
6. **Ordena las frecuencias (opcional).** En **Orden de las frecuencias**, arrastra para decidir en qué orden se ven Única, Mensual y Anual.

Al terminar, el donante verá una pestaña por frecuencia con tus montos sugeridos y, si lo activaste, el campo de monto libre.

- Máximo 4 montos por frecuencia (*"Límite de campos de montos alcanzado"*).
- Si falta la estrella en una frecuencia, verás *"Selecciona un monto predeterminado para: …"*.
- El texto de **Editar texto de frecuencía** no se traduce a otros idiomas.
- Cada país tiene su propio snippet Donación.

## Scape recurrent: mostrar la donación única solo como enlace

Con esta opción, el formulario muestra solo la donación mensual y deja la única como un enlace discreto. Sirve para empujar la recurrencia sin quitarle al donante la opción de dar una sola vez.

**Antes de empezar:** en el snippet **Donación**, la frecuencia **Mensual** tiene que estar activa con al menos un monto, y **Única** también tiene que estar activa. Si no, la casilla no aparece.

1. **Abre el snippet Donación** en el editor del widget.
2. **Activa la opción.** Marca **Mostrar la donación única solo como enlace debajo del botón de pago**.
   <!-- captura pendiente: scape-recurrent-02 — casilla en el snippet Donación -->
3. **Guarda.** Haz clic en **Guardar Snippet** y después en "Guardar Widget".

Al terminar, se oculta la pestaña **Única** y el donante ve solo la frecuencia mensual. Debajo del botón de pago aparece el enlace *"Hacer donación única"*, que cambia la donación a única.

> **Importante:** el enlace solo aparece si la frecuencia Única tiene montos configurados o si está activo **Quiero campo de monto**.

> **¿Se puede deshacer?** Sí. Desmarca la casilla y guarda.

## Cards de conversión: ofrecer pasar de única a recurrente

El snippet **Ofrecer única a recurrente** muestra una tarjeta que invita a quien dona una vez a convertirse en donante mensual.

**Antes de empezar:**
- AFRUS tiene que habilitar este snippet para tu organización, y solo existe en widgets de objetivo **Transacción**.
- La frecuencia mensual debe estar habilitada en el snippet **Donación** con al menos un monto. Si no, verás: *"La frecuencia mensual debe estar habilitada y tener al menos un monto configurado en el snippet de Donación antes de usar esta función."*

1. **Agrega el snippet.** En el editor del widget, haz clic en "Agregar" y elige **Ofrecer única a recurrente**. Se coloca solo justo después de **Donación**, con un separador, y se mueve junto con Donación.
2. **Actívalo.** Activa **Habilitar**.
3. **Personaliza la tarjeta (opcional).** Completa **Título** y **Subtítulo**, y elige **Color del botón**, **Color de degradado superior** y **Color de fondo de la tarjeta**. Si dejas un color vacío, se usa la paleta del panel **Estilo**.
   <!-- captura pendiente: cards-de-conversion-03 — configuración de Ofrecer única a recurrente -->
4. **Define las tasas.** Completa **Tasa 1 (%)** y **Tasa 2 (%)**, números enteros de 1 a 99 (vienen en 50 y 25). Son los porcentajes del monto único que se proponen como donación mensual.
5. **Guarda.** Haz clic en **Guardar Snippet** y después en "Guardar Widget".

**Qué ve el donante:**
- **Durante el formulario:** si eligió una donación única, ve la tarjeta *"Conviértete en donante mensual"* con dos botones *"Donar {monto}/mes"*, calculados con la Tasa 1 y la Tasa 2 sobre su monto, y la opción *"Mantener mi donación única de {monto}"*. Si acepta, la donación pasa a mensual.
- **Después de pagar:** si pagó una donación única con tarjeta en una pasarela gestionada por AFRUS, ve *"Conviértelo en un regalo mensual"* antes de la página de agradecimiento. Si acepta, se crea además una suscripción mensual; la donación única ya cobrada no cambia.

> **Importante:** si el donante ya aceptó la oferta dentro del formulario, no ve la oferta después del pago. Con PayPal, débito bancario, Pix u otras pasarelas no gestionadas por AFRUS, solo puede aparecer la oferta dentro del formulario.

> **¿Se puede deshacer?** Sí, desactiva **Habilitar** y guarda.

## Cover your cost: que el donante cubra los costos

Con **Cover Your Cost**, el donante puede cubrir la comisión de la pasarela, para que tu organización reciba el monto completo de la donación.

**Antes de empezar:** AFRUS tiene que activar Cover Your Cost para tu organización; no se puede activar desde la consola. Mientras no esté activo, la sección no aparece. Se configura **por pasarela**, no dentro del editor del widget.

1. **Abre la pasarela.** Ve a **Ajustes de Organización > Pasarelas de pago** y abre la pasarela.
   ![Ventana de la pasarela con la sección Cover Your Cost y el interruptor Activar Cover Your Cost](img/cover-your-cost-01.webp)
2. **Activa la opción.** En la sección **Cover Your Cost**, activa **Activar Cover Your Cost**.
3. **Define la comisión.** Completa **Comisión de pasarela (%)** (mínimo 0.01). La **Comisión AFRUS (%)** se muestra solo para lectura. La suma de ambas tiene que ser menor a 80 %.
4. **Elige si viene preseleccionada.** Con **Preseleccionar la opción para el donante** activado, el donante ve el interruptor encendido y puede rechazarlo; desactivado, lo ve apagado y debe activarlo.
5. **Guarda la pasarela.** Repite en cada pasarela que deba ofrecerlo.

Al terminar, en el último paso del widget, con esa pasarela seleccionada, el donante verá la tarjeta *"Cubrir el 100% los costos de donación"*, con **Donación base**, **Costo aproximado de transacción** y **Total**. El total se calcula para que, después de las comisiones, tu organización reciba al menos el monto base, redondeado hacia arriba; por eso el donante paga un poco más que la suma simple de los porcentajes.

> **Importante:** si la comisión AFRUS no se puede cargar, la pasarela no se puede guardar (*"No se pudo cargar la comisión de AFRUS. Inténtalo de nuevo."*). Vuelve a intentarlo.

> **¿Se puede deshacer?** Sí. Desactiva **Activar Cover Your Cost** en la pasarela y guarda.

## Cómo configurar una página de agradecimiento

1. **Abre el panel.** En el editor del widget, pestaña **Editar**, abre el panel **Avanzado** y, dentro, **Página de agradecimiento**.
   <!-- captura pendiente: como-configurar-una-pagina-de-agradecimiento-01 — panel Página de agradecimiento -->
2. **Opción A: usa la de la campaña.** Marca **Usa la página de agradecimiento de la campaña.** Después del pago, el donante va a la página de agradecimiento que creaste en la campaña. Revisa los países que no tengan la misma traducción en la campaña, como avisa el editor.
3. **Opción B: configura tus URL.** Haz clic en "Configurar". En la ventana **Páginas de agradecimiento**, activa **Habilitar página de agradecimiento** y elige:
   - una URL de **Página de agradecimiento general**, para todos los casos; o
   - **Página de agradecimiento personalizada** (solo en widgets transaccionales): en **Transacciones unicas** y **Transacciones recurrentes** completa **Redirección de transacción exitosa** y **Redirección de transacción pendiente de confirmación**. En misas, una URL por tipo de misa.
4. **Guarda.** Haz clic en "Guardar" y después en "Guardar Widget".

Al terminar, después de la operación el donante irá a la URL que corresponde. Si la página de agradecimiento está deshabilitada, verá la confirmación propia del formulario.

- Las URL deben empezar con `http://` o `https://` y tener menos de 255 caracteres.
- Si marcaste la página de la campaña y la campaña tiene una configurada, esa tiene prioridad.
- Una donación rechazada no redirige a ninguna página personalizada.

## Opciones de "Avanzado": captcha, analytics, Face to Face, Facebook CAPI y protocolo de medición

Todas se configuran en el panel **Avanzado** del editor del widget y se guardan con "Guardar Widget".

1. **Recaptcha.** Activa el interruptor **Recaptcha** (*"Permitir que se requiera la validación de captcha en todo momento"*) para que el donante siempre tenga que escribir un código de verificación de 6 caracteres. Sin el interruptor, el captcha igual puede aparecer cuando el sistema detecta un intento sospechoso.
2. **Google Tag Manager 4 (analytics).** Pega tu **Código de seguimiento** (el ID de tu contenedor). El widget envía los eventos del recorrido del donante a tu contenedor, para que los midas en tus herramientas.
3. **Protocolo de medición.** Completa **Measurement Id** y **Api secret** de tu propiedad GA4. Con estos datos, AFRUS envía los eventos a GA4, incluida la compra, también desde el servidor.
4. **Facebook Capi.** Completa **Pixel id** y **Access Token**. AFRUS envía los eventos a Meta desde el navegador (Pixel) y desde el servidor (Conversions API), incluida la conversión de compra o registro.
5. **Face to Face** (solo en widgets transaccionales). Úsalo para donaciones presenciales, cuando un captador llena el formulario por cada donante en un dispositivo compartido:
   - activa **Face to Face** (*"Habilitar configuración Face to Face para transacciones presenciales"*);
   - completa **Correo del captador** (obligatorio) y, si quieres, **Correo del supervisor**;
   - **Desactivar autocompletado del navegador** se marca solo, para que el navegador no ofrezca los datos del donante anterior.
   <!-- captura pendiente: opciones-de-avanzado-05 — panel Avanzado con Face to Face -->
6. **Guarda.** Haz clic en "Guardar Widget".

Al terminar:
- **Face to Face:** el captador y el supervisor reciben un email por cada donación exitosa o fallida de ese widget.
- **Analytics:** los eventos llegan a las cuentas configuradas. El Pixel y Google Analytics de una landing se configuran aparte, en la landing.

> **Importante:** con Face to Face activo no se puede guardar el widget sin **Correo del captador**. Si tu organización tiene una configuración de Meta a nivel de organización, AFRUS puede usar ese token en lugar del que pusiste en el widget.

## Cómo insertar un widget en tu sitio web

**Opción rápida (desde el listado):**

1. **Abre el código.** En **Fundraising > Widgets**, haz clic en el icono de código de la fila del widget. Se abre **Código del widget**.
   ![Ventana Código del widget abierta desde el icono de código de la fila](img/como-insertar-un-widget-01.webp)
2. **Copia el código.** Haz clic en "Copiar".
3. **Pégalo en tu página.** Pégalo en un bloque o componente HTML de tu sitio. El widget aparecerá ahí.

**Opción con ancho personalizado (desde el editor):**

1. **Abre la pestaña Instalar.** En el editor del widget, abre **Instalar**.
2. **Define el ancho.** En **Configura el ancho del formulario**, usa Pixeles (px), Porcentaje (%), Ems (em), Rems (rem) o Ancho de la ventana (vw). Si quieres otro ancho en pantallas más angostas, activa "Aplicar ancho especifico" con un **Ancho de aplicación**.
3. **Guarda y copia.** Haz clic en "Guardar Widget" y copia el **Código de inserción** con "Copiar".
4. **Pégalo en tu página**, en un bloque HTML.

- El código es el mismo para todos los países del widget; el país se elige solo al abrirlo.
- Si el widget está inactivo (**Estado** apagado), no recibe donaciones.
- Para revisarlo sin publicarlo, usa "Vista previa" o, en el **Dashboard de Widget**, "Abrir para probar".

Los cambios que guardas se ven de inmediato en el widget ya publicado.

---

## Otras acciones del listado

| Acción | Qué hace |
|---|---|
| "Clonar" | Crea una copia del widget |
| **Establecer como predeterminado** | Marca el widget como formulario por defecto de su objetivo |
| **Asignar tags** | Le asigna etiquetas para filtrarlo |
| Interruptor **Estado** | Activa o desactiva el widget |
| **Eliminar** | Borra el widget; pide escribir su nombre para confirmar |

> **¿Se puede deshacer?** Eliminar un widget no se puede deshacer. Un widget con donaciones asociadas no se puede eliminar: archívalo o desactívalo en su lugar.

## Preguntas frecuentes

**¿Puedo tener montos distintos por país?**
Sí. Cada país tiene su propio snippet Donación y su propio Medio de pago.

**¿Dónde activo Cover Your Cost dentro del widget?**
En ningún lado del widget: se configura por pasarela, en **Ajustes de Organización > Pasarelas de pago**, y solo si AFRUS lo activó para tu organización.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-27*
