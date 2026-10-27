# Guía de Logs de interacciones

Con esta guía vas a poder comprobar si a una persona se le envió un correo o un WhatsApp desde Afrus, ver qué se le envió y volver a enviarlo si falló.

*Módulo: Trackers · Menú: **Trackers > Logs de interacciones** · Audiencia: equipos de comunicaciones y atención a donantes*

---

## Qué es Logs de interacciones

**Es el historial de cada correo y cada WhatsApp que Afrus preparó para una persona, con su estado de envío.**

Cada vez que Afrus prepara un mensaje para alguien (por ejemplo, un correo de agradecimiento automático o un envío masivo), deja una fila en esta lista. Ahí ves a quién iba, por qué vía salió y si se envió bien.

## Para qué sirve

- **Responder a un donante que dice que no recibió un correo.** Buscas su correo y ves si se le envió, cuándo y desde dónde.
- **Ver qué se le envió.** Puedes abrir la vista previa del mensaje tal como salió.
- **Encontrar envíos con error y reenviarlos.**

---

# Paso a paso

## Qué información encuentro allí y cómo analizarla

### Parte 1 — Busca a la persona

1. **Abre la pantalla.** Entra a **Trackers > Logs de interacciones**.
   ![Pantalla Logs de interacciones con las tarjetas de totales, el buscador, los filtros y la tabla](img/logs-de-interacciones-01.webp)

2. **Busca a la persona.** En el buscador elige **Lead ID**, **Correo electrónico** o **Teléfono** y escribe el dato **completo y exacto**. Si escribes solo una parte, no la encuentra.

3. **Filtra si lo necesitas.** Puedes filtrar por **Canal** (**Email** o **WhatsApp**), por **Estado**, por **Eventos** (de dónde salió el mensaje) y por **Origen**. Elige una sola opción en cada filtro (ver Limitaciones).

4. **Lee la columna Estado.** Te dice qué pasó con el mensaje (ver la tabla de abajo).

5. **Mira el mensaje.** Pulsa "Ver detalle" para ver la fecha y hora exactas y la vista previa del correo o del WhatsApp.
   ![Detalle de una interacción con la sección Detalles y la Previsualización](img/logs-de-interacciones-05.webp)

**Qué significa cada estado:**

| Estado | Qué significa |
|---|---|
| **Procesado** | Afrus entregó el mensaje al servicio de correo o de WhatsApp sin error. **No confirma** que llegó a la bandeja ni que se leyó |
| **En cola** | El mensaje está esperando su turno para salir |
| **Fallido** | Hubo un error al enviarlo |
| **No enviado** | Afrus decidió no enviarlo, por ejemplo porque la persona no se puede contactar por ese canal o porque el envío masivo se detuvo |

> **Importante:** las filas **No enviado** no aparecen al abrir la pantalla. Para verlas, filtra **Estado** por **No enviado**.

Si no aparece ninguna fila, Afrus no preparó ningún mensaje para esa persona.

**¿Quieres saber si el correo se abrió o rebotó?** Esta pantalla no lo dice. Revísalo en la pestaña **Eventos** del perfil de la persona o en el detalle del envío masivo.

**De dónde salió el mensaje (columna Evento):**

| Evento | En el detalle se ve como | Qué es |
|---|---|---|
| `autoresponder` | Autoresponder | Un correo automático, como un agradecimiento |
| `blast` | Blast | Un envío masivo de correo o de WhatsApp |
| `api` | Mensaje personalizado | Un mensaje escrito por el agente de IA (su **Origen** es **Alma**) |
| `custom` | WhatsApp personalizado | Un WhatsApp enviado a una persona desde una línea conectada |

**Las tarjetas de arriba:**

- **Interacciones** cuenta las filas que ves con tu búsqueda y tus filtros.
- **Procesado**, **Fallidos de sistema**, **En cola** y **No enviado** cuentan **todo el historial de tu organización**, sin filtros. Por eso no suman lo mismo que **Interacciones**.

### Parte 2 — Reenvía un mensaje que falló

6. **Elige el mensaje.** Desde la lista, marca una o varias filas con estado **Fallido** y pulsa "Acciones" > "Reenviar". Desde el detalle, pulsa "Reenviar".

7. **Comprueba.** Verás *"Comunicación reenviada correctamente"* y la fila pasará a **En cola**. Afrus vuelve a enviar exactamente el mismo mensaje.

> **¿Se puede deshacer?** No. Una vez reenviado, el mensaje sale de nuevo. Reenvía solo los mensajes **Fallido**: si reenvías uno **Procesado**, la persona lo recibe dos veces. Los mensajes **En cola** no se pueden reenviar.

---

## Limitaciones conocidas

- Los envíos de **WhatsApp Business > Blast** no aparecen aquí. Su estado (**Entregado**, **Leído**) se ve en el detalle de ese blast.
- **Un solo valor por filtro.** Si marcas dos opciones en el mismo filtro (por ejemplo **Email** y **WhatsApp**), solo se usa la primera; si marcas todas, el filtro se quita. Para ver los dos canales, deja **Canal** sin marcar.
- **La búsqueda necesita el dato exacto.** Escribe el correo o el teléfono completos.
- **La columna Fecha no muestra la hora.** La hora está en "Ver detalle".
- **No hay filtro de fechas:** la lista recorre todo el historial, del más reciente al más antiguo.
- **La pantalla no se actualiza sola:** recárgala para ver cambios.

## Preguntas frecuentes

**¿"Procesado" quiere decir que la persona recibió el correo?**
No. Quiere decir que Afrus lo entregó al servicio de envío sin error. Para saber si llegó, se abrió o rebotó, revisa la pestaña **Eventos** del perfil de la persona.

**¿Cuánto tarda un mensaje en pasar de "En cola" a "Procesado"?**
> **Pendiente de confirmar:** no hay un tiempo fijo; depende de cuántos mensajes estén esperando.

**¿Cuánto tiempo se guardan estos registros?**
> **Pendiente de confirmar:** cuánto tiempo se conserva el historial.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-26*
