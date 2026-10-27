# Guía de Links de pago

Después de leer esta guía sabrás qué es un link de pago, para qué sirve, desde dónde se crea y cómo enviarlo a una persona para que done.

*Módulo: Follow up · Menú: **Follow up > Links de pago** · Audiencia: equipos de recaudación y atención a donantes*

---

## Qué es un link de pago

**Un link de pago es un enlace personalizado que envías por correo a una persona para que done un monto definido (o el que ella elija), de forma única o mensual.**

El link abre el widget predeterminado de tu organización, ya preparado con los datos de la persona y el monto, así que solo tiene que completar el pago.

## Para qué sirve

- **Pedir una donación concreta a una persona específica**, sin que tenga que buscar tu formulario.
- **Ofrecer donación única o mensual**, con monto fijo o abierto.
- **Hacer seguimiento de cada link**: si se envió, si se usó (**Finalizado**) o si caducó (**Expirado**).
- **Reenviar un link** desde la lista, si la persona no lo encuentra.

## Antes de empezar

- **Tu organización necesita un widget predeterminado.** El link usa ese widget; si no hay uno, el envío falla. Lo eliges en **Fundraising > Widgets** (ver la guía de Business profile).
- **Tu Business profile debe tener URL.** El link se arma sobre esa dirección; sin ella, la tarjeta para crear links no aparece en **Home**.

---

# Paso a paso

## Desde dónde se crean los links de pago

Puedes crear un link de pago desde dos lugares:

| Dónde | Cuándo usarlo |
|---|---|
| **Home**, tarjeta **Link de pago** | Para enviar un link a cualquier persona: escribes su nombre, apellido y correo. Solo aparece si tu Business profile tiene URL |
| Perfil de una persona en **Personas**, pestaña **Contacto**, tarjeta **Link de pago** | Para enviar un link a una persona que ya está en tu base: usa su nombre, apellido y correo |

La pantalla **Follow up > Links de pago** no tiene botón para crear: sirve para ver, filtrar y reenviar los links que ya enviaste.

## Cómo crear un link de pago

1. **Abre la tarjeta Link de pago.** En **Home**, o en el perfil de la persona (**Personas**, pestaña **Contacto**).
   ![Tarjeta Link de pago en el perfil de una persona, con la frecuencia, el monto, el mensaje personalizado y el botón Enviar](img/como-crear-un-link-de-pago-01.webp)

2. **Escribe los datos de la persona.** Desde **Home**, completa **Nombre**, **Apellido** y **Correo electrónico** (obligatorio). Desde el perfil de una persona, estos datos ya vienen de su ficha.

3. **Revisa el canal de envío.** En **Envíar por** queda marcado **Correo electrónico**. Por ahora los links se envían solo por correo.

4. **Agrega el teléfono (opcional).** En **Teléfono**; AFRUS valida el formato.

5. **Elige la frecuencia.** En **Seleccionar la frecuencia**, marca **Único** o **Mensual**.

6. **Define el monto.** Escribe el **Monto** (mayor a 0) o marca **Valor abierto** para que la persona elija cuánto donar.

7. **Personaliza el mensaje (opcional).** En **Mensaje personalizado**, escribe unas palabras para la persona. Un mensaje cercano ayuda a que done.

8. **Pon fecha de vencimiento (opcional).** Marca **Caducar enalce** y elige **Seleccionar fecha** y **Seleccionar hora**. Lee antes la limitación sobre vencimientos más abajo.

9. **Envía.** Pulsa "Enviar" y, en *"Desea enviar el link de pago?"*, pulsa "Confirmar".

Al terminar verás *"¡Link de pago creado con éxito!"* con el correo de destino. La persona queda registrada (o actualizada) en la campaña del widget predeterminado, recibe el correo con el link, y el link aparece en **Follow up > Links de pago** con estado **Creado**. Si el correo falla verás *"¡Hubo un error al crear el link de pago!"*.

> **¿Se puede deshacer?** No. Una vez confirmado, el correo se envía. Si te equivocaste, envía un nuevo link con los datos correctos.

## Cómo reenviar un link

1. **Abre la lista.** Entra a **Follow up > Links de pago**.
2. **Busca el link.** Usa la búsqueda o el filtro **Estado**.
3. **Reenvía.** Pulsa "Reenviar" en la fila (o ábrelo con el ícono de ojo y reenvíalo desde el detalle).

---

## Estados de un link de pago

| Estado | Qué significa | Cuándo cambia |
|---|---|---|
| **Creado** | El link se envió y todavía no se usó con éxito | Al enviarlo |
| **Finalizado** | La persona completó una donación exitosa con el link | En el momento en que se confirma la donación |
| **Expirado** | Tenía fecha de vencimiento y esa fecha ya pasó | En una revisión automática diaria. Además, si la persona abre el link vencido, el formulario le avisa |

La lista muestra **ID**, correo, monto (o "Abierto" si es de valor abierto), fecha de creación, **Enviado** (Si/No), **Language Code**, **Estado** y acciones.

## Limitaciones conocidas

- **Solo se envía por correo electrónico.** WhatsApp y **Mensaje de texto** aparecen deshabilitados.
- **Vencimiento en otro mes:** si eliges una fecha de vencimiento en un mes posterior pero en un día del mes menor al de hoy (por ejemplo, vence el 5 del mes siguiente y hoy es 11), el link puede marcarse o mostrarse como **Expirado** antes de tiempo. Lo mismo puede pasar con la hora elegida. Por ahora no hay una alternativa dentro de AFRUS, salvo enviar el link sin fecha de vencimiento.
- **Hora de creación en la lista:** en lugar de los minutos se muestra el mes. Usa la fecha como referencia.
- **La opción "Caducar enalce"** tiene un error de tipeo en la pantalla: es la opción para que el enlace caduque.
- **Si la donación falla,** el link sigue en **Creado**.

## Preguntas frecuentes

**¿Puedo enviar el link por WhatsApp?**
No por ahora. AFRUS envía los links de pago solo por correo electrónico.

**¿El link sirve para una donación mensual?**
Sí. En **Seleccionar la frecuencia** elige **Mensual**.

**¿Qué ve la persona si abre un link que ya usó?**
> **Pendiente de confirmar:** qué muestra el formulario al abrir un link **Finalizado**.

**¿En qué idioma llega el correo?**
> **Pendiente de confirmar:** AFRUS elige la plantilla según el tipo de organización y el idioma; no está verificado cada caso.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-20*
