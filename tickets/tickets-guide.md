# Guía de Tickets

Después de leer esta guía sabrás qué son los Tickets de rifa en AFRUS, cómo venderlos con un widget de producto y cómo enviar a cada comprador sus números en el autoresponder.

*Módulo: Tickets · Menú: **Fundraising > Tickets** · Audiencia: equipos de recaudación, eventos y comunicaciones*

---

## Qué son los Tickets

**Un Ticket es una rifa con un rango de números, por ejemplo del 1 al 500.** Cuando la vinculas a un widget de producto, cada persona que compra recibe un número de ticket consecutivo por cada unidad que compra.

> **Importante:** la venta de entradas para eventos con código QR todavía no está disponible. Hoy, **Tickets** se usa para rifas.

## Para qué sirve

- **Vender números de rifa en línea.** Los vendes desde un widget, con un precio por ticket.
- **Asignar los números automáticamente.** Cada comprador recibe sus números, y puedes mostrárselos en la página de agradecimiento y en el autoresponder.
- **Saber quién compró cada número.** Ves la persona, la transacción, el widget y el país de cada ticket, para hacer el sorteo y contactar al ganador.

## Cada cuánto se actualiza

- **Los números se asignan en el momento** en que se registra la compra en el widget.
- **Las pantallas muestran los datos al abrirlas.** La lista **Tickets generados por transacción** y la sección **Productos y tickets** del panel del widget consultan los datos cuando abres la pantalla o cambias un filtro. No hay que esperar a ningún proceso.
- **No se refrescan solas.** Para ver compras nuevas, recarga la pantalla o vuelve a buscar.

---

# Paso a paso

## Cómo crear un widget de producto

Para vender tickets necesitas dos cosas: la rifa (el Ticket, con su rango de números) y un widget con objetivo **Producto** que la venda.

### Parte 1 — Crea la rifa

1. **Abre Tickets.** Ve a **Fundraising > Tickets** y haz clic en "Crear Ticket".
   ![Pantalla Tickets con el botón Crear Ticket y la Lista de Tickets](img/como-crear-un-widget-de-producto-01.webp)

2. **Ponle nombre.** Completa **Nombre** (mínimo 3 caracteres).

   > **Importante:** para poder agregar la rifa a un widget, el nombre no debe pasar de 25 caracteres y la descripción de 80.

3. **Escribe una descripción.** Completa **Descripción** (hasta 500 caracteres). Aunque la pantalla no la marca como obligatoria, si la dejas vacía verás *"Error al crear ticket"*.

4. **Elige el estado.** En **Estado**, deja **Activo** (es la opción por defecto).

5. **Define el rango.** En **Rango**, indica **Número Inicial** (mínimo 1) y **Número Final**, que debe ser mayor que el inicial. El primer comprador recibe el Número Inicial.

6. **Crea la rifa.** Haz clic en "Crear Ticket". Verás *"Ticket creado exitosamente"* y la rifa aparecerá en la **Lista de Tickets** con su **ID**.

### Parte 2 — Crea el widget que la vende

7. **Crea un widget nuevo.** Ve a **Fundraising > Widgets** y haz clic en "Nuevo widget". El editor de widgets se abre en una pestaña nueva.

8. **Elige el objetivo Producto.** En **Objetivo**, elige **Producto**. Solo los widgets con este objetivo asignan números de ticket.

   > **Pendiente de confirmar:** en qué pantalla exacta del editor se elige el objetivo y se agrega el bloque **Producto**.

9. **Agrega el producto.** Agrega el bloque **Producto** y haz clic en "Agregar Producto". En **Tipo de Producto**, elige **Ticket**.

10. **Elige la rifa.** En **Seleccionar Ticket**, elige tu rifa. Se completan solos (y no se pueden editar) el **Nombre del producto**, la **Descripción del producto**, el **Límite Inicial**, el **Límite Final** y el **Stock del producto**.

11. **Pon el precio.** Escribe el **Precio del producto**: es el precio de cada ticket. Solo acepta números. La pantalla no lo exige, así que revisa que lo hayas puesto.

12. **Confirma el producto.** Haz clic en "Agregar Producto". Verás *"¡Producto agregado satisfactoriamente!"*.

13. **Guarda y publica el widget.** Hazlo como con cualquier otro widget.

Al terminar, en el widget el donante elige cuántos tickets quiere. En la página final ve una tarjeta por ticket, con **Cantidad**, **Precio unitario** y la etiqueta "Ticket <número>".

> **Importante:** cada widget admite una sola rifa, y en el mismo bloque no se pueden mezclar productos normales con tickets (*"No se pueden mezclar tipos de productos"*).

## Cómo incluir en mi autoresponder el número de ticket y la cantidad de tickets comprados

**Antes de empezar:** necesitas un autoresponder de transacción (correo o WhatsApp) que se envíe con las compras hechas en tu widget de producto con ticket.

1. **Abre el editor de tu autoresponder.** Ve a **Interacciones > Autoresponders** y abre el autoresponder.
2. **Abre el mapa de merge tags.** Abre **Merge tags** (**Mapa de merge tags**) y busca la categoría **Merge Tags de Rifas** ("Datos de rifas y tickets"). Al hacer clic en una tarjeta, el merge tag se copia.
   ![Mapa de merge tags con la categoría de rifas seleccionada](img/como-incluir-ticket-en-autoresponder-02.webp)
3. **Pega los merge tags en tu texto.** Escríbelos exactamente así:

   | Merge tag | Nombre en el mapa | Qué muestra |
   |---|---|---|
   | `{{ticket_id}}` | Ticket ID | **Todos** los números de ticket de esa compra, separados por coma (ej.: `0042, 0043, 0044`) |
   | `{{raffle_name}}` | Raffle Name | Nombre de la rifa |
   | `{{raffle_description}}` | Raffle Description | Descripción de la rifa |
   | `{{raffle_price}}` | Price | Precio de un ticket |
   | `{{raffle_reference}}` | Reference | Número de la transacción (ID de donación) |

4. **Muestra la cantidad con los números.** No existe un merge tag de cantidad. Como se genera un número por cada ticket comprado, la cantidad es igual a cuántos números aparecen en `{{ticket_id}}`. Por ejemplo: *"Tus números de la rifa {{raffle_name}} son: {{ticket_id}}"*.

Al enviarse el correo o el WhatsApp, cada merge tag se reemplaza por el dato de esa compra. Puedes usar los mismos merge tags en la página de agradecimiento.

> **Importante:** el mapa también muestra "Número de Ticket" y "Fecha de Sorteo", pero no corresponden a ningún merge tag real de rifas. Usa solo los de la tabla.

> **Pendiente de confirmar:** si con algún tipo de pago el autoresponder puede salir antes de que existan los números. Haz una compra de prueba para revisar tu mensaje.

## Cómo ver quién compró cada número

1. **Abre la rifa.** En **Fundraising > Tickets**, haz clic en el **ID** de la rifa. Se abre **Tickets generados por transacción**.
2. **Ajusta las fechas.** Por defecto muestra desde el inicio del mes hasta hoy.
3. **Filtra si lo necesitas.** En **Buscar por**, elige **ID de Lead**, **ID de Donación**, **Email de Lead**, **Nombre de Ticket** o **Descripción de Ticket**, escribe el valor y presiona Enter.

Verás una fila por cada número, con **ID de Ticket**, **Nombre**, **Precio**, **ID de Donación**, **ID de Lead**, **Cantidad** (siempre 1), **Nombre de Widget** y **Código de País**.

---

## Datos y estados

| Dato | Qué significa |
|---|---|
| **Activo** / **Inactivo** | Es solo una etiqueta. Una rifa **Inactivo** que ya está en un widget publicado sigue vendiendo |
| **ID de Ticket** | Número asignado, con ceros a la izquierda hasta el largo del Número Final (con Número Final 500, el 42 se ve como `042`) |
| **Cantidad** | Siempre 1 por fila: cada ticket comprado es una fila |
| **Tickets vendidos** (panel del widget) | Tickets vendidos en compras **exitosas** del período |

## Preguntas frecuentes

**¿Puedo vender entradas para eventos con QR?**
Todavía no. Esa función está en desarrollo.

**¿Hay un merge tag con la cantidad de tickets comprados?**
No. Usa `{{ticket_id}}`, que lista todos los números de la compra.

**¿Puedo poner dos rifas en el mismo widget?**
No. Cada widget admite una sola rifa.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-20*
