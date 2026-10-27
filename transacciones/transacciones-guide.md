# Guía de Transacciones

Después de leer esta guía sabrás qué es el módulo Transacciones, para qué sirve y cómo agradecer con IA, reembolsar, marcar fraude, descargar, filtrar y revisar por qué falló un pago.

*Módulo: Transacciones · Menú: **Transacciones** · Audiencia: equipos de recaudación, atención al donante y finanzas*

---

## Qué es Transacciones

**Transacciones es la lista de todos los pagos de tu organización.** Aquí ves las donaciones únicas y cada cobro de las donaciones recurrentes, con su estado, monto, pasarela, método de pago, campaña y widget de origen.

Las suscripciones en sí (el compromiso de donar cada mes) no están aquí: se ven en **Suscripciones**. Lo que aparece en Transacciones es cada pago que esa suscripción genera.

## Para qué sirve

- **Encontrar cualquier pago.** Busca por nombre, documento, correo, teléfono o ID y abre su detalle, incluida la respuesta de la pasarela cuando un pago falla.
- **Reembolsar donaciones.** Devuelve donaciones exitosas en las pasarelas que lo permiten.
- **Limpiar el fraude.** Marca pagos fraudulentos para sacarlos de la lista y de tu base.
- **Exportar a Excel.** Descarga un grupo de transacciones: las que elijas o todas las que coinciden con tus filtros.
- **Agradecer con IA.** Envía al donante un correo de agradecimiento redactado con IA.

## Antes de empezar

- **La lista muestra por defecto el mes en curso** (**MTD**). Cambia el periodo en la barra de fechas si buscas pagos más antiguos.
- **La lista se actualiza al abrir la pantalla o cambiar un filtro.** No se refresca sola mientras está abierta.

---

# Paso a paso

## Cómo crear un agradecimiento con IA desde Transacciones

**Necesitas:**
- que la transacción esté en estado **Exitoso**;
- tener activo el **Business profile** (si no lo tienes, la opción no aparece);
- al menos un usuario con firma configurada en **AI > Firmas de usuarios**. Solo esos usuarios aparecen como remitentes.

1. **Abre el agradecimiento.** En **Transacciones**, abre el menú de tres puntos al inicio de la fila y elige **Agradecimiento personalizado IA**. También puedes usar el botón con el icono de destellos que aparece junto al estado **Exitoso**.
   ![Menú de tres puntos de una transacción con la opción Agradecimiento personalizado IA](img/como-crear-un-agradecimiento-con-ia-desde-transacciones-01.webp)
2. **Elige el remitente.** En el paso **Seleccionar el remitente con el que enviarás el agradecimiento**, elige un usuario y pulsa "Continuar". El correo sale desde la dirección de su firma.
3. **Espera el borrador.** Verás *AI preparando tu mensaje* mientras la IA redacta el correo.
4. **Revisa y edita.** Ajusta **Asunto** (máximo 128 caracteres) y **Cuerpo del correo** (máximo 1600). Con "Regenerar" pides otra versión de cada campo; con "Volver" regresas al paso anterior.
5. **Envía.** Pulsa "Enviar mensaje" (se activa cuando el asunto y el cuerpo tienen texto).

Al terminar verás *Mensaje enviado* / *"El agradecimiento se ha enviado correctamente"*. El correo llega al email de la persona de esa transacción. Si algo falla, verás *"Error al enviar el agradecimiento"*.

> **Importante:** no uses los botones **Merge tags** en este correo. Por ahora las variables se envían como texto literal, sin reemplazarse por los datos del donante. Escribe el nombre y los datos directamente en el texto.

> **¿Se puede deshacer?** No. Una vez enviado, el correo ya está en la bandeja del donante: revísalo bien antes de pulsar "Enviar mensaje".

## Cómo reembolsar una donación

**Necesitas:**
- que la transacción esté en estado **Exitoso**;
- que su pasarela permita reembolsos desde AFRUS (si no, la opción **Reembolsar** no aparece);
- que tu usuario tenga permiso para hacer operaciones bancarias con transacciones. Si no lo tiene, el reembolso falla: pide a un administrador de tu organización que lo haga.

1. **Abre el menú de la fila.** En **Transacciones**, busca la donación, abre el menú de tres puntos al inicio de la fila y elige **Reembolsar**.
   ![Menú de tres puntos de una transacción exitosa con la opción Reembolsar](img/como-reembolsar-una-donacion-01.webp)
2. **Confirma.** En el diálogo **Reembolsar Cargo** (*"Estas seguro que deseas reembolsar este cargo?"*), pulsa "Confirmar". Si te arrepientes, pulsa "Cerrar".

Al terminar verás *"Reembolsado con éxito."* y la transacción pasará a **Reembolsado**. Si la donación tenía un certificado de donación vigente, se anula. Si la pasarela rechaza el reembolso, verás *"Error al reembolsar el cargo."* y la transacción no cambia.

> **Importante:** siempre se reembolsa el monto completo. Desde esta pantalla no se pueden hacer reembolsos parciales.

> **¿Se puede deshacer?** No. El dinero se devuelve en la pasarela y no hay opción para revertir el reembolso.

> **Pendiente de confirmar:** cuánto tarda el dinero en llegar al donante y hasta cuántos días después del cobro acepta reembolsos cada pasarela; también si reembolsar un **Cargo** cancela la suscripción. Si quieres detener los cobros futuros, cancela la suscripción en **Suscripciones**.

## Cómo marcar como fraude una transacción

> **Importante:** al marcar una transacción como fraude, **las personas (donantes) asociadas se eliminan de tu base**, aunque tengan otras donaciones legítimas. Revisa bien antes de confirmar.

1. **Selecciona las transacciones.** En la tabla de **Transacciones**, marca la casilla de una o varias filas de la página.
   ![Dos transacciones seleccionadas y el menú Acciones transacciones abierto con Marcar como Fraude](img/como-marcar-como-fraude-una-transaccion-01.webp)
2. **Elige la acción.** Pulsa "Acciones transacciones" y elige **Marcar como Fraude** (la opción está desactivada si no hay nada seleccionado).
3. **Confirma.** En el diálogo **Marcar como fraude**, lee el aviso (*"…Esta acción no se puede deshacer."*) y pulsa "Confirmar".

Al terminar verás *Transacciones marcadas como fraude*. Cada transacción pasa al estado **Fraude**, desaparece de **Transacciones** y aparece en **Follow up > Radar - monitor de fraude**, donde ves su **Estado anterior** y la fecha en **Marcada como fraude el**.

> **Importante:** marcar como fraude solo cambia el estado en AFRUS. No reembolsa el pago ni cancela ninguna suscripción en la pasarela.

> **Importante:** solo se marcan las filas seleccionadas en la página actual. Aunque uses "Seleccionar las N transacciones de la base.", esta acción no se aplica a toda la base. Si son muchas, márcalas página por página.

> **¿Se puede deshacer?** No. El propio diálogo lo advierte y en el Radar no hay opción para revertirlo.

## Cómo descargar un grupo de transacciones

1. **Filtra lo que necesitas.** Ajusta las fechas, la búsqueda y los filtros (ver "Cómo filtrar un grupo de transacciones").
2. **Selecciona las transacciones.** Marca las casillas de las filas que quieres. Para exportar todo lo filtrado, marca la casilla del encabezado y pulsa "Seleccionar las N transacciones de la base."
   ![Casilla del encabezado marcada y enlace para seleccionar todas las transacciones de la base](img/como-descargar-un-grupo-de-transacciones-02.webp)
3. **Exporta.** Pulsa "Acciones transacciones" y elige **Exportar** (está desactivada si no hay nada seleccionado).
4. **Confirma el archivo.** En el diálogo **Descargas**, elige **Tipo de archivo** y pulsa "Confirmar". Verás *Exportar archivo* (*"El proceso de exportacion ha comenzado, ten en cuenta que puede demorar unos minutos en completarse."*).
5. **Descarga el archivo.** Entra a **Data > Descargas** y descárgalo cuando esté listo.

Al terminar tendrás un archivo de Excel. Si seleccionaste filas sueltas, trae exactamente esas, sin importar el rango de fechas; si elegiste toda la base, trae todo lo que coincide con fechas, búsqueda y filtros.

> **Importante:** el archivo siempre se genera en Excel (.xlsx), aunque elijas CSV. Además, el filtro **CYC** no se aplica a la exportación con "toda la base": si lo necesitas, filtra con **CYC** en pantalla y marca las filas una por una, porque así se exportan exactamente las que eliges.

> **Importante:** los archivos se pueden descargar hasta 7 días después de generados.

## Cómo filtrar un grupo de transacciones

1. **Elige el periodo.** En la barra de fechas, pulsa **1W**, **4W**, **1Y**, **MTD**, **QTD**, **YTD**, **ALL** o **PERSONALIZADO**. Por defecto es **MTD** (desde el inicio del mes hasta hoy). El periodo se aplica sobre la **Fecha inicial** de la transacción, en tu zona horaria.
   ![Barra de fechas con los periodos y fila de filtros de Transacciones](img/como-filtrar-un-grupo-de-transacciones-01.webp)
2. **Busca (opcional).** Usa **Buscar por** con **Nombre**, **Documento de identidad**, **Correo electrónico**, **Teléfono** o **ID de transaccion**.
3. **Aplica filtros.** En la fila con el icono de embudo elige:
   - **Tipo** (**Unicas** / **Cargos**)
   - **Tipo de origen** (Estándar, Incentivo, Peer to peer, Producto)
   - **Estados**, **Pasarela de pago**, **Metodo de pago**
   - **Valor** (Mayor que / Igual que / Menor que), que compara el monto convertido a la moneda de tu organización
   - **Campaña**, **Widgets**
   - **CYC** (Con CYC / Sin CYC), para ver donaciones en las que el donante cubrió el costo
4. **Limpia cuando quieras.** "Reset" quita todos los filtros.

Al terminar, la tabla y los totales se recalculan. Los filtros quedan en la dirección de la página, así que puedes copiar el enlace y compartir la misma vista con tu equipo.

> **Importante:** si marcas a la vez **Unicas** y **Cargos** en **Tipo**, solo se muestran las únicas. Para ver ambas, deja **Tipo** sin seleccionar.

## Cómo saber la razón del fallo de una transacción

La lista no tiene una columna de motivo: la razón se ve en el detalle de la transacción.

1. **Abre el detalle.** En la fila de una transacción **Fallido** o **Rechazada**, abre el menú de tres puntos y elige **Detalles**, o haz clic en el **ID**. Se abre en una pestaña nueva.
   ![Detalle de una transacción fallida con la tarjeta Resultado de suscripción y el análisis con IA](img/como-saber-la-razon-del-fallo-de-una-transaccion-01.webp)
2. **Lee la explicación con IA.** En la tarjeta **Resultado de suscripción** (**Analisis de la respuesta con IA**) verás una explicación en lenguaje claro de lo que respondió la pasarela. Requiere tener activo el **Business profile**; si no lo está, verás *Activación necesaria para ver la respuesta con IA* y el botón "Ir a business profile".
3. **Consulta la respuesta original.** En **Respuesta** > **Respuesta Gateway** está la respuesta de la pasarela, con el código o mensaje de rechazo que envió.

El análisis se genera la primera vez que abres el detalle y después se muestra con la etiqueta **Cacheado**. Si el pago no tiene respuesta de la pasarela, no hay análisis.

---

## Única y Cargo: cuál es la diferencia

La columna **Tipo de frecuencia** y el filtro **Tipo** distinguen dos clases de pago:

| En la columna | En el filtro **Tipo** | Qué es |
|---|---|---|
| **Única** | **Unicas** | Una donación de un solo pago. No viene de una suscripción. |
| **Cargo** | **Cargos** | Un cobro de una donación recurrente. Cada mes o ciclo de la suscripción genera un cargo nuevo. |

La suscripción en sí (el registro "madre", **Recurrente**) no aparece en esta lista: se ve en **Suscripciones**.

## Estados de una transacción

| Estado | Qué significa |
|---|---|
| **Exitoso** | El pago se completó. Puedes agradecer con IA o reembolsar |
| **Pendiente** | El pago aún no se confirma (algunos métodos tardan) |
| **Pendiente de confirmación** | Requiere que tu equipo lo confirme o rechace con **Confirmar transacción** / **Rechazar transacción** |
| **Fallido** / **Rechazada** | El pago no se completó. Revisa la razón en el detalle |
| **Reembolsado** | El pago se devolvió al donante |
| **Propuesta** | Pendiente de confirmar qué significa este estado |
| "PRENOTIFICATION_OK" | Se muestra así, con texto técnico, para transacciones prenotificadas |

Las transacciones en **Fraude**, **Cancelada** o **Contracargo** no aparecen en **Transacciones**. Las de fraude se ven en **Follow up > Radar - monitor de fraude**.

## Preguntas frecuentes

**¿Puedo hacer un reembolso parcial?**
No. Desde AFRUS siempre se reembolsa el monto completo de la transacción.

**¿Por qué no veo la opción Reembolsar?**
Aparece solo en transacciones **Exitoso** cuya pasarela permite reembolsos desde AFRUS.

**¿Marcar como fraude devuelve el dinero?**
No. Solo cambia el estado en AFRUS. Si además necesitas devolver el pago, reembólsalo antes de marcarlo como fraude.

**¿Dónde veo las suscripciones?**
En **Suscripciones**. En Transacciones ves cada cobro (**Cargo**) que generan.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-20*
