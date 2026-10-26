# Guía de Monitor de interacciones

Con esta guía vas a saber si tu organización puede seguir enviando correos masivos sin riesgo de bloqueo, y qué envío está causando problemas.

*Módulo: Trackers · Menú: **Trackers > Monitor de interacciones** · Audiencia: equipos de comunicaciones y email marketing*

---

## Qué es Monitor de interacciones

**Es un tablero que muestra la salud de tus correos masivos (blasts).** Te dice cuántos correos enviaste, cuántos rebotaron, cuántos se marcaron como spam y si tu cuenta de envío está en riesgo.

Un correo **rebota** cuando no llega a su destino, por ejemplo porque la dirección no existe. Una **queja** (complaint) es cuando la persona marca tu correo como spam. Si hay demasiados rebotes o quejas, Afrus puede limitar o bloquear tus envíos.

Este tablero solo cuenta los correos masivos. No incluye los correos automáticos (autoresponders), los correos de transacciones ni los WhatsApp.

## Para qué sirve

- **Saber si puedes seguir enviando.** Ves si tu cuenta está activa, en alerta o bloqueada.
- **Cuidar tu tasa de rebotes y quejas.** Comparas tus números con los límites de Afrus.
- **Encontrar el envío que causó problemas.** Así sabes qué lista limpiar.

---

# Paso a paso

## Qué información encuentro allí y cómo analizarla

### Parte 1 — Revisa el estado de tu cuenta

1. **Abre el monitor.** Entra a **Trackers > Monitor de interacciones**. Se abre la pestaña **Monitor Email**.
   <!-- captura pendiente: monitor-de-interacciones-01 — pantalla Monitor de interacciones con el Estado de la cuenta, la Variable de notificación y los Indicadores principales -->

2. **Mira el Estado de la cuenta.** Verás una de estas etiquetas:

| Etiqueta | Qué significa | Qué hacer |
|---|---|---|
| **Activa** | Puedes enviar sin problema | Nada |
| **Alerta** | Tus rebotes o quejas pasaron el primer límite. Todavía puedes enviar, pero tu cuenta está en riesgo de bloqueo | Limpia tus listas antes del próximo envío |
| **Bloqueada** | Tus rebotes o quejas pasaron el límite de bloqueo, o Afrus bloqueó la cuenta. No puedes enviar | Escribe a soporte en support@afrus.app |
| **Envío limitado** | La cuenta estaba bloqueada, pero Afrus te habilitó un número de envíos | Limpia tus listas y envía solo a grupos más pequeños que tu saldo de envíos |

> **Importante:** si Afrus bloqueó tu cuenta, sigue **Bloqueada** aunque tus números mejoren. Para desbloquearla, escribe a soporte.

Con **Envío limitado**, una campaña con más destinatarios que envíos disponibles no se envía.

### Parte 2 — Compara tus tasas con los límites

3. **Revisa la Variable de notificación.** Muestra cuatro líneas, cada una con tu tasa actual frente al límite ("X% de Y%"):
   - **MNB** y **MBB**: tu tasa de rebotes frente al límite de alerta y al de bloqueo.
   - **MNC** y **MBC**: tu tasa de quejas frente al límite de alerta y al de bloqueo.

   La tasa de rebotes suma los rebotes duros y los blandos.

4. **Revisa los Indicadores principales.** **Enviados**, **Hard bounces** (rebotes duros), **Soft bounces** (rebotes blandos) y **Complaints** (quejas). Estos números cuentan **todo tu historial** de correos masivos.

Los límites solo se aplican a partir de 1.000 correos enviados. Si tienes menos, verás: *"El bloqueo de la cuenta solo se aplicará cuando se superen los 1000 envíos."*

### Parte 3 — Encuentra el envío que causa rebotes

5. **Elige las fechas.** Usa la barra de fechas para ver los envíos de un periodo. Al abrir, muestra todas las fechas. Las fechas solo cambian la tabla de envíos; el estado de la cuenta y los indicadores siempre usan todo el historial.

6. **Revisa la Lista de blast.** Mira **Bounce Rate (%)** (rebotes) y **Complaint Rate (%)** (quejas) de cada envío. Los colores te ayudan:
   - **Verde:** por debajo del límite de alerta.
   - **Amarillo:** entre el límite de alerta y el de bloqueo.
   - **Rojo:** en el límite de bloqueo o por encima.
   <!-- captura pendiente: monitor-de-interacciones-06 — tabla Lista de blast con las tasas en verde, amarillo y rojo -->

7. **Abre el envío.** Haz clic en su **ID** para ver el detalle. La tabla muestra 5 envíos por página; puedes cambiarlo a 10, 25 o 50.

---

## Limitaciones conocidas

- **Solo cuenta correos masivos.** No incluye autoresponders, correos de transacciones ni WhatsApp.
- **Los rebotes blandos también suben tu tasa de rebotes.**
- **Algunos textos están en inglés** (**Monitor Email**, **Hard Bounces**, **Bounce Rate (%)**…).
- **Al hacer clic en los títulos ID o Nombre, la tabla no cambia de orden.** Siempre muestra primero el envío más reciente.
- **La pantalla no se actualiza sola:** recárgala para ver cambios.

## Preguntas frecuentes

**Mi cuenta está en Alerta. ¿Puedo enviar?**
Sí, pero estás en riesgo de bloqueo. Antes del próximo envío, quita de tus listas los correos inválidos o muy antiguos.

**¿Cuáles son los límites de Afrus?**
Los ves en la sección **Variable de notificación**, junto a tu tasa actual. Son los mismos para todas las organizaciones.

**¿Cuánto tarda en aparecer un rebote?**
> **Pendiente de confirmar:** no hay un tiempo fijo.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-26*
