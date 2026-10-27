# Guía de Campañas

Después de leer esta guía sabrás qué es una campaña en AFRUS, para qué sirve, cómo vincularle widgets y una página de agradecimiento, cómo mostrar su progreso y sus donantes en tu web, y cómo medir su rentabilidad con costos, Analytics y KPI Merge Tags.

*Módulo: Campañas · Menú: **Fundraising > Campañas** · Audiencia: equipos de recaudación, marketing digital y dirección*

---

## Qué es una campaña

**Una campaña agrupa las donaciones y los registros que entran por uno o varios widgets bajo un mismo objetivo de recaudación.** Tiene un nombre interno, un nombre público, una descripción, una meta en la moneda de tu organización y un estado (activa o inactiva).

Encuentras tus campañas en **Fundraising > Campañas**. Desde la lista puedes crear una campaña con "Crear campaña", buscarla por nombre y filtrarla por **Estado**, **Tipo de Campaña** y **Total Recaudado**. Para ver esta sección, tu rol de usuario necesita el permiso de ver campañas.

## Para qué sirve

- **Seguir tu meta.** Ves en un solo lugar cuánto lleva recaudado una iniciativa frente a su meta (**Total recaudado**, con barra de progreso).
- **Medir la conversión de tus widgets.** La **Tasa de conversión** compara donaciones y registros con las veces que se mostraron los widgets de la campaña.
- **Usar una página de agradecimiento común** para todos los widgets de la campaña que la usen.
- **Medir la rentabilidad.** Registras los costos de la campaña y ves ROI, costo por transacción, costo por donante recurrente, Lifetime Value y más en el Dashboard de Analytics.
- **Mostrar tu campaña en tu web.** Con el **Crowdfunding widget** muestras el progreso hacia la meta; con el **Componente donantes**, la lista de personas que donaron.
- **Contar el impacto en cifras.** Con los **KPI Merge Tags** insertas cifras calculadas (por ejemplo, "comidas donadas") en correos automáticos o en landings.

## Antes de empezar

- **Ten creada la campaña.** En **Fundraising > Campañas**, pulsa "Crear campaña" y completa **Nombre de campaña** (hasta 100 caracteres), **Descripción** (hasta 500), **Nombre público** (hasta 100) y **Meta de recaudación**. Deja encendido **Campaña activa** y pulsa "Crear". La meta se guarda siempre en la moneda de tu organización.
- **Para editarla**, en la lista abre el menú de tres puntos de la fila y elige **Editar** (o haz clic en el ID). Los cambios de texto se guardan solos un instante después de dejar de escribir; no hay botón de guardar en esa pestaña.

---

# Paso a paso

## Cómo vincular un widget con una campaña

Al vincular un widget, sus donaciones y registros quedan asociados a la campaña y cuentan en sus resultados.

**Antes de empezar:** la campaña debe estar **activa**. El editor de widgets solo muestra campañas activas, por su nombre público.

1. **Abre el widget.** Entra a **Fundraising > Widgets** y edita el widget que quieres vincular. El editor se abre en una pestaña nueva. Esta pantalla se abre en la versión anterior de AFRUS, por eso se ve distinta.
   <!-- captura pendiente: como-vincular-un-widget-con-una-campana-01 — editor de widgets, panel Renderización -->

2. **Elige la campaña.** En el panel **Renderización**, en el campo **Elige tus campañas**, selecciona una o varias campañas.

3. **Guarda los cambios del widget.**

   > **Pendiente de confirmar:** el nombre exacto del botón para guardar en el editor de widgets.

Al terminar, el widget aparece en la tabla **Widgets de la campaña**, dentro del detalle de la campaña, y sus donaciones y registros quedan asociados a ella.

- **Con una sola campaña**, el donante no ve nada distinto en el formulario.
- **Con más de una campaña**, el donante ve un desplegable **Elige tu campaña** dentro del formulario, con la primera campaña ya elegida. Así puede decidir a qué iniciativa va su donación.

> **¿Se puede deshacer?** Sí. Vuelve a **Elige tus campañas** en el editor del widget, quita la campaña y guarda.

## Cómo vincular una página de agradecimiento a una campaña

Así todos los widgets de la campaña pueden llevar al donante a la misma página después de donar. Son dos partes: elegir la página en la campaña y activarla en cada widget.

**Antes de empezar:** ten creada la página que quieres usar, como experiencia en **Fundraising > Experiences AI** o como landing en **Fundraising > Landings**.

**Parte 1 — En la campaña**

1. **Abre la campaña.** En **Fundraising > Campañas**, abre el menú de tres puntos de la fila y elige **Editar**.
2. **Ve a la pestaña Página de agradecimiento.** También la encuentras al crear la campaña.
   ![Pestaña Página de agradecimiento de la campaña con el tipo de página y la landing elegida](img/como-vincular-una-pagina-de-agradecimiento-a-una-campana-02.webp)
3. **Elige el tipo de página.** En **Tipo**, elige **Experiences** o **Landings**.
4. **Elige la página.** En **Elegir una experiencia** o **Elegir una landing**, selecciona la página. Verás una vista previa **Mobile**.
5. **Pulsa "Usar plantilla".** Este botón no muestra un mensaje de confirmación: para comprobar que quedó guardada, recarga la campaña y revisa que la pestaña muestre la página elegida.

**Parte 2 — En cada widget que deba usarla**

6. **Abre el widget.** En **Fundraising > Widgets**, edita el widget. Esta pantalla se abre en la versión anterior de AFRUS, por eso se ve distinta.
7. **Activa la página de la campaña.** En la sección **Avanzado**, apartado **Página de agradecimiento**, marca **Usa la página de agradecimiento de la campaña.** Al marcarla, desaparece el botón "Configurar" de la página de agradecimiento propia del widget.
8. **Guarda los cambios del widget.**

Al terminar, después de donar, el donante llega a la landing o experiencia elegida en la campaña a la que se asoció su donación.

> **Importante:** si la campaña no tiene página elegida, o la página ya no existe, se usa la página de agradecimiento normal del widget. El editor también avisa: *"Los países que no tienen la misma traducción en las campañas, por favor revise sus páginas de agradecimiento."* Revisa tus páginas si tu widget se usa en varios países.

> **¿Se puede deshacer?** Sí. Desmarca la casilla en el widget para volver a su página de agradecimiento propia, o elige otra página en la campaña.

## Qué es el Crowdfunding widget

**El Crowdfunding widget es un bloque que pegas en cualquier web y que muestra en vivo el progreso de tu campaña hacia una meta.** Muestra el total alcanzado, la meta, una barra de avance, el número de donaciones y, si pusiste fecha de cierre, cuántos días faltan o *"Campaña finalizada"*. Los datos se consultan cada vez que se carga la página.

Puedes medir tres tipos de meta, en **Tipo de componente**:

| Tipo | Qué cuenta |
|---|---|
| **Meta de Recaudación** | La suma de las donaciones exitosas |
| **Meta de Suscriptores** | Las suscripciones activas |
| **Meta de Registros** | Las personas registradas, sin repetir |

Y dos formas de fijar la meta, en **Tipo de meta**:

- **Fija:** escribes la meta, eliges la moneda (solo en recaudación) y la **Fecha** y **Hora** de cierre.
- **Dinámica:** usa la **Meta de recaudación** de la campaña; no te pide meta, moneda, fecha ni hora.

**Cómo configurarlo:**

1. **Abre el configurador.** En **Fundraising > Campañas**, abre el menú de tres puntos de la fila y elige **Crowdfunding widget**.
   ![Configurador del Crowdfunding widget con Tipo de componente, Tipo de meta y el botón Copiar código de inserción](img/que-es-el-crowdfunding-widget-01.webp)
2. **Configura la meta.** En la pestaña **Configuración**, elige **Tipo de componente** y **Tipo de meta**, y completa los datos que te pida.
3. **Ajusta el diseño.** En la pestaña **Estilos**, elige **Tipografía** (Roboto, Arial, Open Sans o Times New Roman), **Tamaño de tipografía** (de 12 a 20) y **Color primario**, para que combine con tu web.
4. **Guarda.** Pulsa "Guardar". Cada guardado crea una versión nueva, que puedes elegir en **Versiones**.
5. **Copia el código.** Pulsa "Copiar código de inserción" y pégalo en el HTML de tu sitio.

> **Importante:** la tipografía, el tamaño, el color y el idioma van dentro del código que copias. Si cambias algo y guardas, copia y pega el código de nuevo para que tu web use la versión nueva.

> **Limitación conocida:** con **Meta de Suscriptores** o **Meta de Registros** y meta **Dinámica**, el bloque muestra una meta de 0. Para esos tipos, usa meta **Fija**.

## Qué es el Componente donantes

**El Componente donantes es un bloque para tu web que muestra la lista de personas que donaron a la campaña.** Por defecto se titula *"Personas que también donaron"* y muestra el nombre, el apellido y el monto de cada donación exitosa, de la más reciente a la más antigua, con desplazamiento vertical. Si todavía no hay donaciones, muestra *"No hay donantes disponibles"*.

**Cómo configurarlo:**

1. **Abre el configurador.** En **Fundraising > Campañas**, abre el menú de tres puntos de la fila y elige **Componente donantes**.
   ![Configurador del Componente donantes con el título, la tipografía, el color y la vista previa](img/que-es-el-componente-donantes-01.webp)
2. **Personalízalo.** Configura **Título**, **Tipografía**, **Color primario**, el tema **Light** o **Dark** y el interruptor **Activo** / **Inactivo**. La vista previa usa nombres de ejemplo, no tus donantes reales.
3. **Guarda.** Pulsa "Guardar" (o "Actualizar" si ya existía).
4. **Copia el código** de inserción y pégalo en tu web.

> **Importante:** el título, el tema y **Activo** / **Inactivo** se aplican sin tocar tu web. La tipografía y el color van dentro del código: si los cambias, copia y pega el código de nuevo. Si lo pones en **Inactivo**, el bloque deja de mostrarse.

> **Ten en cuenta:** el bloque publica el nombre, el apellido y el monto de cada donante. No hay opción para ocultar nombres o montos, así que asegúrate de que tu organización puede publicar esa información. Los montos se muestran con el símbolo de la moneda de tu organización.

## Para qué sirve y cómo se usa el centro de costos

En la campaña, el centro de costos es la pestaña **Costos**: *"Agrega en esta sección todos los costos implicados en la realización de tu campaña"*.

**Para qué sirve:**

- **Saber cuánto invertiste** en la campaña, con un total filtrable por fechas.
- **Calcular la rentabilidad.** Con tus costos, AFRUS calcula Resultado, ROI, costo por transacción, costo por donante recurrente y otros indicadores.
- **Activar el Dashboard de Analytics.** El botón "Ver Analytics" solo se habilita cuando la campaña tiene al menos un costo registrado.

**Cómo registrar un costo:**

1. **Abre la campaña** y ve a la pestaña **Costos**.
   ![Pestaña Costos con la lista de costos, el total y el botón Agregar costo](img/centro-de-costos-de-una-campana-01.webp)
2. **Pulsa "Agregar costo".**
3. **Completa los datos.**
   - **Costo:** obligatorio, mayor que 0.
   - **Tipo:** obligatorio, **Publicidad (working media)** o **Costos de apoyo y producción**.
   - **Fecha de gasto:** obligatoria.
   - **Widget:** opcional, solo widgets de esta campaña. Un costo asignado a un widget cuenta en la analítica de ese widget; uno sin widget solo cuenta en la analítica de la campaña completa.
   - **Nota:** opcional, hasta 1000 caracteres.
4. **Pulsa "Agregar"** (o "Guardar" si estás editando).

Al terminar, el costo aparece en **Lista de costos** (columnas **Fecha**, **Valor**, **Widget**, **Tipo**, **Nota** y **Acciones**) y suma en el **Total**, que puedes filtrar por rango de fechas.

> **Limitación conocida:** el valor se guarda sin decimales (por ejemplo, 150,75 queda como 150). Registra los montos redondeados. Los costos se registran siempre en la moneda de tu organización.

> **¿Se puede deshacer?** Puedes editar un costo. Eliminarlo pide confirmación y no se puede deshacer.

## Analytics de campañas: qué datos obtienes, cómo se activa y cómo analizarlos

**Cómo se activa:** registra al menos un costo en la pestaña **Costos**. Hasta entonces, "Ver Analytics" está deshabilitado con el aviso *"Para acceder a las analíticas, primero debes registrar al menos un costo en la sección de Costos."*

**Cómo abrirlo y usarlo:**

1. **Abre el Dashboard.** En el detalle de la campaña, pulsa "Ver Analytics".
   ![Dashboard de Analytics en la pestaña Resumen con ingresos, costo y resultado](img/analytics-de-campanas-01.webp)
2. **Elige el periodo.** En la pestaña **Resumen**, elige el rango de fechas (por defecto, todo el historial). Las tarjetas de indicadores se recalculan para ese rango.
3. **Descarga los indicadores (opcional).** Pulsa "Descargar KPIs" para bajar un archivo CSV con todos los indicadores del rango (columnas KPI, Valor y Unidad).
4. **Mira un widget en detalle.** En **Rendimiento por Widget**, pulsa un widget para abrir su **Analytics del Widget**: los mismos indicadores, solo de ese widget y sus costos.
5. **Mira la evolución.** En la pestaña **Tendencias**, elige el rango (por defecto, el mes en curso). AFRUS agrupa por día hasta 31 días, por semana hasta 90 días y por mes si es mayor.

**Qué datos obtienes en Resumen (tarjetas):**

| Indicador | Qué es |
|---|---|
| Ingresos Totales / Costos | Ingresos de donaciones exitosas frente a la suma de costos registrados |
| Resultado | Ingresos menos costos |
| ROI | (ingresos − costos) / costos |
| MRR Adquirido / ARR Adquirido | Ingreso mensual de las suscripciones activas adquiridas; el ARR es el MRR × 12 |
| CPT Bruto / CPR Bruto | Costo por transacción / costo por donante recurrente |
| CPT Neto / CPR Neto | Lo mismo, usando solo la pérdida neta (0 si la campaña es rentable) |
| Punto de Equilibrio | Meses para recuperar la pérdida neta con el MRR |
| Inversión | Pérdida neta (0 si la campaña es rentable) |
| RCR | Suscripciones / (suscripciones + pagos únicos) |
| Tasa de Calidad | Suscripciones / transacciones |
| Tasa de Abandono | Suscripciones canceladas / suscripciones nuevas |
| Vida del Donante | 1 / tasa de abandono, en meses |
| Lifetime Value | Valor de vida del donante: AMV × 12 / tasa de abandono |
| Eficiencia de Adquisición | LTV / CPR; debería ser mayor que 1 |
| AMV | MRR / suscripciones |
| Cantidades y promedios | Transacciones exitosas, suscripciones nuevas activadas y monto promedio de pagos únicos y de suscripciones |

Si todavía no hay suscripciones canceladas, la pantalla usa un valor de referencia del 3% para calcular Tasa de Abandono, Vida del Donante y Lifetime Value, y lo indica en su texto de ayuda.

**Qué datos obtienes en las tablas Histórico:** **Rendimiento por Widget**, **Rendimiento por UTM Source**, **UTM Medium**, **UTM Campaign** y **Rendimiento por URL**, con transacciones, montos, suscripciones y montos de suscripciones. Te dicen qué widget, qué fuente de tráfico y qué página traen más donaciones.

**Cómo analizarlos:**

- **¿La campaña es rentable?** Mira **Resultado** y **ROI**. Si hay pérdida, **Punto de Equilibrio** te dice en cuántos meses la recuperan tus donantes recurrentes.
- **¿Estás captando bien?** Compara **Lifetime Value** con **CPR**: si **Eficiencia de Adquisición** es mayor que 1, cada donante recurrente vale más de lo que te cuesta conseguirlo.
- **¿Captas donantes recurrentes?** **RCR** y **Tasa de Calidad** muestran qué parte de tus donaciones son suscripciones.
- **¿Dónde invertir?** Las tablas por widget, UTM y URL muestran qué canales y páginas traen más ingresos.

**Cada cuánto se actualizan los datos:**

| Dónde | Cuándo se actualiza |
|---|---|
| Tarjetas del **Resumen** y **Analytics del Widget** | En el momento, con los datos actuales |
| Tablas **Histórico** (por widget, UTM y URL) | Una vez al día: pueden no incluir lo de hoy. Muestran el total de siempre y no respetan el rango de fechas |
| Pestaña **Tendencias** | Una vez al día: puede no incluir lo de hoy |

> **Pendiente de confirmar:** la hora exacta en que se actualizan las tablas Histórico y la pestaña Tendencias.

**Tasa de conversión (en Datos de la campaña):** además del Dashboard, la pestaña **Datos de la campaña** muestra **Donaciones** (%), **Registros** (%) y **Visualizaciones** de los widgets de la campaña. Su texto de ayuda dice que *"Este dato se calcula cada 24 horas y puede no reflejar cambios recientes"*.

## Para qué sirven y cómo se usan los KPI Merge Tags

**Los KPI Merge Tags son cifras calculadas con una fórmula que insertas en correos automáticos o en landings.** Sirven para contar el impacto de forma concreta: por ejemplo, convertir el monto de una donación en "comidas donadas". Se crean en la pestaña **KPI Merge Tag** de la campaña, y hay dos tipos:

| Tipo | Dónde se usa | Con qué datos calcula |
|---|---|---|
| **KPI Transaccional** | Correos automáticos (**Interacciones > Autoresponders**) | El **Monto** de la donación que dispara el correo |
| **KPI Global** | Landings | **Total Recaudado** y **Cantidad de Donantes** de la campaña |

**Cómo crear un KPI Transaccional:**

1. **Abre la pestaña.** En la campaña, ve a **KPI Merge Tag**, apartado **KPI Transaccional** y pulsa "Agregar KPI Merge Tag".
   ![Formulario Crear KPI Merge Tag con el Constructor de Fórmula](img/kpi-merge-tags-01.webp)
2. **Ponle nombre.** Escribe **Nombre del KPI** (y una **Descripción** opcional). En **Variable generada** verás la etiqueta que vas a usar.
3. **Arma la fórmula.** En **Constructor de Fórmula**, alterna "Agregar Variable" y "Agregar Operador" (+, -, ×, ÷). La variable disponible es **Monto**. Con "Agregar Variable Multiplicador" creas una constante (**Nombre de la variable** y **Valor constante**) para usarla en la fórmula. "Limpiar" y "Quitar Último" te ayudan a corregir. La fórmula debe terminar en una variable.
4. **Pulsa "Crear"** (o "Actualizar" si la estás editando).
5. **Úsala en tu correo automático.** La etiqueta tiene esta forma: `{{kpi_<ID de campaña>_<nombre>}}`, con el nombre en minúsculas y los espacios cambiados por `_`. Por ejemplo, campaña 88 y nombre "Comidas Donadas" → `{{kpi_88_comidas_donadas}}`.

Al enviarse el correo, la etiqueta se reemplaza por el resultado de la fórmula con el monto de esa donación, con 2 decimales. La multiplicación y la división se calculan antes que la suma y la resta.

> **Pendiente de confirmar:** si los KPI Transaccionales aparecen en el selector de merge tags del editor de correos. Mientras tanto, escribe la etiqueta tal como aparece en **Variable generada**.

**Cómo crear un KPI Global:**

1. **Abre la pestaña.** En la campaña, ve a **KPI Merge Tag**, apartado **KPI Global** y pulsa "Agregar KPI global".
2. **Ponle nombre y arma la fórmula** igual que en el anterior. Las variables disponibles son **Total Recaudado** y **Cantidad de Donantes** (más constantes). Usa en el nombre solo letras sin tilde, números y espacios.
3. **Pulsa "Crear".**
4. **Úsalo en tu landing, entre corchetes.** La pantalla muestra la etiqueta con llaves (`{{global_kpi_88_comidas_donadas}}`), pero en una landing tienes que escribirla entre corchetes: `[global_kpi_88_comidas_donadas]`.

Al abrir la landing publicada, la etiqueta muestra el valor calculado en ese momento con todas las donaciones exitosas de la campaña, con hasta 2 decimales.

> **Importante (KPI Global):** las operaciones se aplican de izquierda a derecha; la multiplicación y la división no van primero. Ordena tu fórmula en el orden en que quieres que se calcule.

> **¿Se puede deshacer?** Puedes editar un KPI Merge Tag, pero no hay botón para eliminarlo.

---

## Estados de una campaña

| Estado | Qué significa | Qué puedes hacer |
|---|---|---|
| **activo** | La campaña está activa y se puede elegir en el editor de widgets | Vincularla a tus widgets |
| **inactivo** | La campaña está apagada (interruptor **Campaña activa** apagado) | Encender **Campaña activa** en el detalle para volver a usarla |
| **archivado** | La campaña está archivada | Consultarla |

## Limitaciones conocidas

- **"Ver Analytics" está deshabilitado** hasta que registres al menos un costo.
- **Los costos se guardan sin decimales.** Registra montos redondeados.
- **"Usar plantilla" no confirma** que la página de agradecimiento quedó guardada: recarga la campaña para comprobarlo.
- **Crowdfunding widget con meta Dinámica** de suscriptores o registros muestra meta 0: usa meta **Fija**.
- **KPI Global en landings** se escribe entre corchetes `[...]`, aunque la pantalla lo muestre con llaves; y su nombre no debe llevar tildes, ñ ni símbolos.
- **Los KPI Merge Tags no se pueden eliminar.**
- **El Componente donantes no tiene opción de anonimato.**
- **Las tablas Histórico del Analytics** no se filtran por fecha.
- **Las cohortes de suscripciones** están desactivadas temporalmente en el detalle de campaña.

## Preguntas frecuentes

**¿Qué hace "Seleccionar por defecto" en el menú de una campaña?**
Marca la campaña por defecto de tu organización (solo puede haber una). A ella se asignan las transacciones que llegan desde algunas pasarelas sin una campaña conocida, por ejemplo cobros de suscripciones creadas fuera de AFRUS.

**¿Por qué no veo mi campaña al vincularla en el widget?**
Porque está inactiva. El editor de widgets solo muestra campañas activas: enciende **Campaña activa** en el detalle de la campaña.

**¿La campaña puede tener una moneda distinta?**
No. La meta y los costos se registran siempre en la moneda de tu organización.

**¿Puedo usar un KPI Global en un correo?**
Por ahora solo está confirmado su uso en landings. Para correos automáticos usa un KPI Transaccional.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-20*
