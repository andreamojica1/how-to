# Guía de Servicio de recurrencia

Con esta guía sabrás qué es el Servicio de recurrencia, para qué sirve y qué opciones puedes configurar en él.

*Módulo: Configuración · Menú: **Ajustes de Organización > Servicio de recurrencia** · Audiencia: administradores de la organización*

---

## Qué es el Servicio de recurrencia

**Es la pantalla donde configuras cómo AFRUS hace los cobros automáticos de tus donaciones mensuales y recurrentes.** En la pantalla aparece con el título **Configuración del Motor de Recurrencia**.

Ahí eliges, por ejemplo, cada cuánto se cobra y qué hacer cuando un cobro falla.

> **Importante:** esta configuración aplica a las donaciones recurrentes que cobra AFRUS. Si tu pasarela cobra las suscripciones por su cuenta (por ejemplo Stripe, PayU o Pagar.me), es la pasarela la que decide cuándo se cobra.

## Para qué sirve

- **Elegir cada cuánto se cobra** una donación recurrente: cada mes, cada tres meses, cada seis meses o cada año.
- **Decidir qué pasa si un cobro falla:** cuántas veces se vuelve a intentar y en qué fechas.
- **Elegir los días de cobro**, si usas el modo **Charities**.
- **Volver a la configuración original** con un solo botón si algo no te convence.

## Antes de empezar

- **Necesitas acceso a Configuración** de tu organización.
- **Los cambios no son inmediatos:** la pantalla avisa *"Los cambios se aplicarán a los próximos ciclos de cobro."*

---

# Paso a paso

## Cómo configurar el Servicio de recurrencia

1. **Abre la pantalla.** Ve a **Ajustes de Organización > Servicio de recurrencia**. Verás el título **Configuración del Motor de Recurrencia**.
   ![Pantalla Configuración del Motor de Recurrencia con Configuración actual y los campos Modo mejorado, Periodicidad y Modo de reintento](img/como-configurar-el-servicio-de-recurrencia-01.webp)

2. **Elige el modo.** En **Modo mejorado**, elige **Standard** o **Charities**. Con **Charities** podrás elegir además los días de cobro.

3. **Elige cada cuánto se cobra.** En **Periodicidad**, elige **Mensual**, **Trimestral**, **Semestral** o **Anual**.
   ![Lista Periodicidad abierta con Mensual, Trimestral, Semestral y Anual](img/como-configurar-el-servicio-de-recurrencia-03.webp)

4. **Si elegiste Charities, marca los días de cobro.** Aparece **Días de cobro (Charities)** para que elijas en qué días se cobra.

5. **Decide qué pasa si un cobro falla.** En **Modo de reintento**, elige **Standard retries**, **Charities retries** o **Custom** (personalizado).
   ![Lista Modo de reintento abierta con Standard retries, Charities retries y Custom](img/como-configurar-el-servicio-de-recurrencia-05.webp)

6. **Si elegiste Custom, define los reintentos.** En **Tipo de configuración de reintentos** elige:
   - **Consecutivo:** indica el **Máximo de intentos**.
   - **Fechas específicas:** elige las **Fechas específicas de reintento**.
   ![Modo de reintento Custom con Tipo de configuración de reintentos y Máximo de intentos](img/como-configurar-el-servicio-de-recurrencia-06.webp)

7. **Guarda los cambios.** Se aplicarán a los próximos ciclos de cobro.

> **¿Se puede deshacer?** Sí. Puedes cambiar las opciones cuando quieras, o pulsar "Restaurar valores por defecto" para volver a la configuración original.

---

## Preguntas frecuentes

**¿A qué hora se hacen los cobros?**
Inician a las 5 a. m., pero se procesan en colas y la hora puede variar un poco.

**¿Cuántas veces se reintenta un cobro fallido antes de cancelar la suscripción?**
Por defecto, se intenta cobrar 3 veces por mes durante 12 meses antes de cancelar la recurrencia. Puedes ajustar los reintentos en esta pantalla, en **Modo de reintento**.

**¿Los cambios afectan a las suscripciones que ya existen?**
La pantalla indica que los cambios se aplican a los próximos ciclos de cobro.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-27*
