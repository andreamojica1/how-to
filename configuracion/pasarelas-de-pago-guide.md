# Guía de Pasarelas de pago

Con esta guía vas a entender qué son las pasarelas de pago en Afrus, para qué las necesitas y cómo activar Cover Your Cost para que tus donantes puedan cubrir la comisión.

*Módulo: Configuración · Menú: **Configuración > Pagos > Pasarelas de pago** · Audiencia: administración y equipos de recaudación*

---

## Qué son las pasarelas de pago

**Una pasarela de pago es el servicio que cobra las donaciones de tu organización.** Es la que procesa la tarjeta, el Pix, el boleto u otro medio de pago que use el donante.

Las pasarelas se configuran una vez para toda tu organización, en **Configuración > Pagos > Pasarelas de pago**. También llegas ahí desde el menú de perfil (esquina superior), opción **Ajustes de organización**.

<!-- captura pendiente: que-son-las-pasarelas-de-pago-01 — pantalla Pasarelas de pago con la lista de pasarelas de la organización -->

## Para qué sirven

- **Cobrar las donaciones de tus formularios.** Un formulario de donación (widget) solo puede ofrecer las pasarelas que tu organización tiene conectadas.
- **Decidir qué medios de pago ve el donante.** Lo que ve el donante depende de las pasarelas que activaste y de lo que elijas en cada formulario.
- **Ofrecer pagos según el país y la moneda.** En cada país del formulario solo aparecen las pasarelas conectadas que aceptan la moneda de ese país.
- **Permitir que el donante cubra la comisión (Cover Your Cost).** Se configura en cada pasarela.

**Para tener en cuenta sobre los medios de pago:**
- Pix, boleto y efectivo solo se ofrecen para donaciones únicas. La excepción es Pix con InfoPago, que también admite donaciones mensuales.
- Algunos medios de pago quedan **pendientes** hasta que la pasarela o el banco confirman el pago. Por eso una donación puede aparecer primero como pendiente y cambiar después.
- En los formularios de registro con pago (objetivo **Sign up**) solo se ofrecen Stripe y Niubiz.

Después de tener una pasarela conectada, la eliges en cada formulario, en el bloque **Medio de pago** del editor. Te lo explicamos en la guía de Widgets.

---

# Paso a paso

## Cómo activar o desactivar Cover Your Cost

Con Cover Your Cost, el donante puede pagar un poco más para cubrir la comisión de la pasarela. Así tu organización recibe el monto completo de la donación.

**Antes de empezar:** Afrus tiene que activar Cover Your Cost para tu organización. Si no ves la sección **Cover Your Cost** al abrir una pasarela, escríbenos para activarla.

1. **Abre la pasarela.** Ve a **Configuración > Pagos > Pasarelas de pago** y abre la pasarela donde quieres ofrecerlo.
   <!-- captura pendiente: como-activar-o-desactivar-cover-your-cost-01 — pasarela abierta con la sección Cover Your Cost -->

2. **Enciende la opción.** En la sección **Cover Your Cost**, activa **Activar Cover Your Cost**.

3. **Escribe la comisión de la pasarela.** En **Comisión de pasarela (%)** pon el porcentaje que te cobra esa pasarela (mínimo 0.01). La **Comisión Afrus (%)** aparece solo para que la veas; no se cambia.

4. **Elige cómo la ve el donante.** Con **Preseleccionar la opción para el donante** encendido, el donante la ve ya activada y puede quitarla. Apagado, la ve desactivada y la activa si quiere.

5. **Guarda.** Guarda la pasarela. Repite estos pasos en cada pasarela donde quieras ofrecerlo.

Al terminar, cuando el donante paga con esa pasarela, en el último paso del formulario ve la tarjeta *"Cubrir el 100% los costos de donación"*, con su **Donación base**, el **Costo aproximado de transacción** y el **Total**. El total está calculado para que, después de las comisiones, tu organización reciba al menos el monto de la donación. Por eso el donante paga un poco más que la suma simple de los porcentajes.

**Para desactivarlo:** abre la pasarela, apaga **Activar Cover Your Cost** y guarda.

> **¿Se puede deshacer?** Sí. Puedes encenderlo y apagarlo cuando quieras.

**Ten en cuenta:**
- Se configura en cada pasarela, no en cada formulario.
- La comisión de la pasarela más la comisión de Afrus tienen que sumar menos de 80 %.
- Si ves *"No se pudo cargar la comisión de Afrus. Inténtalo de nuevo."*, la pasarela no se puede guardar en ese momento. Vuelve a intentarlo.

---

## Conectar una pasarela

> **Pendiente de confirmar:** si tu organización puede conectar una pasarela por su cuenta, qué datos pide cada una y cuáles son los pasos para AvalPay, Stripe, Payments Way, Pagar.me, InfoPago, Niubiz, PayPal y Conekta. Mientras tanto, si necesitas conectar una pasarela nueva, escribe a soporte de Afrus.

## Preguntas frecuentes

**¿Por qué no aparece mi pasarela en el formulario?**
En cada país del formulario solo aparecen las pasarelas conectadas que aceptan la moneda de ese país. Revisa que la pasarela esté conectada y que acepte esa moneda.

**¿Puedo ofrecer Pix en donaciones mensuales?**
Solo con InfoPago. Con las demás pasarelas, Pix es solo para donaciones únicas.

**¿Cover Your Cost se activa en el formulario?**
No. Se activa en cada pasarela, en **Configuración > Pagos > Pasarelas de pago**.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-26*
