# Guía de Tareas de suscripciones

Después de leer esta guía sabrás qué son las Tareas de suscripciones, cuándo aparecen, qué significa cada estado y cómo gestionarlas para recuperar a tus donantes recurrentes.

*Módulo: Follow up · Menú: **Follow up > Tareas de suscripciones** · Audiencia: equipos de atención a donantes y recaudación*

---

## Qué son las Tareas de suscripciones

**Las Tareas de suscripciones son una lista de seguimiento que Afrus crea automáticamente cuando falla el cobro de una suscripción.** Cada tarea es un caso para que tu equipo contacte al donante y recupere su donación recurrente.

La pantalla se llama **Tareas de Suscripciones** y muestra, para cada caso, la suscripción, el monto, la pasarela, la persona, el responsable y la fecha.

## Para qué sirve

- **Ver en un solo lugar los cobros recurrentes fallidos.** No tienes que buscar caso por caso en **Suscripciones**.
- **Repartir el trabajo.** Asigna cada caso a un **Responsable** de tu equipo.
- **Llevar el control de lo resuelto.** Marca la tarea como **Completada** cuando terminaste la gestión.
- **Tener el contexto a mano.** Ves **Monto**, **Pasarela**, **Persona** y **Razón de fallo**, y abres la suscripción desde la columna **Suscripción**.
- **Trabajar la lista fuera de Afrus.** Exporta todas las tareas o una selección; el archivo queda en **Descargas**.

## Antes de empezar

- **Solo aplica a suscripciones.** Las tareas se crean cuando falla el cobro de una donación recurrente, no de una donación única.
- **Pasarelas que se muestran.** En esta pantalla aparecen las tareas de suscripciones con pasarela **Recurrent Payments** o **PTESA**.

---

# Paso a paso

## Cada cuánto se actualiza

- **Las tareas se crean en el momento.** Afrus crea la tarea en cuanto procesa el cobro fallido; no espera a una revisión diaria.
- **Al crearse una tarea nueva**, los usuarios con rol owner o admin de tu organización reciben una notificación en Afrus.
- **Si la suscripción ya tenía una tarea**, Afrus no crea otra: reabre la existente (vuelve a **Pendiente**) y le quita el **Responsable**, para que alguien la retome.
- **La pantalla no se refresca sola.** Los datos se cargan al abrirla y al cambiar fechas, búsqueda, filtro, orden o página. Si esperas un caso nuevo, recarga la página.

## ¿Cuando una suscripción vuelve a cobrarse bien, la tarea sale de la lista?

**No.** Cuando la suscripción vuelve a cobrarse con éxito, la tarea no se completa ni se elimina sola. Sigue en la lista con su estado actual hasta que alguien de tu equipo la marque como **Completada**.

Por eso te recomendamos revisar la suscripción (columna **Suscripción**) antes de gestionar un caso: si ya se cobró bien, solo tienes que marcar la tarea como completada.

## Estados de las tareas

La columna **Completada** muestra el estado de cada tarea:

| Estado | Qué significa |
|---|---|
| **Pendiente** | La tarea está abierta y nadie la ha marcado como resuelta. Es el estado con el que se crea, y también el de una tarea que se reabre por un nuevo cobro fallido. |
| **Completada** | Alguien de tu equipo la marcó como resuelta. |

Además, cada tarea tiene un **Tipo**, que puedes cambiar a mano:

| Tipo | Qué significa |
|---|---|
| **General** | El tipo con el que Afrus crea las tareas automáticamente. |
| **Fallo Mensual** | Etiqueta disponible para clasificar el caso a mano. |
| **Cancelada por el Sistema** | Etiqueta disponible para clasificar el caso a mano. |

> **Pendiente de confirmar:** si algún proceso de Afrus asigna automáticamente los tipos **Fallo Mensual** y **Cancelada por el Sistema**.

## Qué puedo hacer en cada estado

| Estado | Qué puedes hacer |
|---|---|
| **Pendiente** | Asignar un **Responsable**, cambiar **Nombre** o **Tipo**, marcarla como completada, abrir la suscripción y exportarla. |
| **Completada** | Desmarcarla para que vuelva a **Pendiente**, reasignarla, editarla y exportarla. |

### Cómo revisar y filtrar las tareas

1. **Abre la lista.** Entra a **Follow up > Tareas de suscripciones**.
   <!-- captura pendiente: tareas-de-suscripciones-01 — lista de Tareas de Suscripciones -->
2. **Elige las fechas.** En la barra de fechas, elige el rango. Por defecto se muestra todo el historial. El filtro usa la fecha en que se creó la tarea: una tarea reabierta conserva su fecha original.
3. **Busca o filtra.** Busca por **Nombre** de la tarea o filtra por **Responsable** para ver solo los casos de una persona del equipo.

La tabla muestra 25 tareas por página (puedes cambiarlo a 10, 50 o 100), de la más nueva a la más antigua.

### Cómo asignar, editar o completar una tarea

1. **Abre la tarea.** En la fila, haz clic en el menú de tres puntos (columna sin título, a la izquierda).
2. **Edítala.** En **Editar Tarea**, completa **Nombre**, **Tipo**, **Responsable** o la casilla **Marcar como completada**. El **Responsable** debe ser un usuario de tu organización.
3. **Guarda.** Pulsa "Guardar". Verás *"Tarea actualizada correctamente"* y la tabla se recargará.

> **¿Se puede deshacer?** Sí. Puedes volver a abrir **Editar Tarea** y desmarcar **Marcar como completada** o cambiar el responsable.

### Cómo exportar las tareas

1. **Selecciona las tareas.** Marca las filas que quieras, o usa el aviso *"Seleccionar las {total} tareas que coinciden con los filtros actuales."* para tomarlas todas.
2. **Exporta.** Pulsa "Acciones" y elige **Exportar**. Verás *"La exportación ha comenzado. Puede tardar unos minutos en completarse; encontrarás el archivo en Descargas."*

---

## Limitaciones conocidas

- **Solo se ven algunas pasarelas.** La pantalla lista las tareas de suscripciones con pasarela **Recurrent Payments** o **PTESA**. Las de otras pasarelas no aparecen aquí; revísalas desde **Suscripciones**.
- **La Razón de fallo puede aparecer vacía** ("-"). En ese caso, busca el cobro fallido en **Transacciones** y abre su detalle: ahí se ve la razón del fallo.
- **No hay filtro por estado.** La lista muestra juntas las tareas **Pendiente** y **Completada**; ordénalas o expórtalas para separarlas.

## Preguntas frecuentes

**¿Se crean tareas para donaciones únicas que fallan?**
No. Solo se crean cuando falla el cobro de una suscripción.

**¿Por qué una tarea que ya estaba completada volvió a Pendiente y sin responsable?**
Porque la suscripción volvió a tener un cobro fallido. Afrus reabre la misma tarea en lugar de crear otra.

**¿Quién recibe el aviso de una tarea nueva?**
Los usuarios con rol owner o admin de tu organización, con una notificación en Afrus.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-20*
