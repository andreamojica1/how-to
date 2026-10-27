# Recurrence service guide

With this guide you will know what the Recurrence service is, what it is for and which options you can set in it.

*Module: Configuración (Settings) · Menu: **Configuración > Pagos > Servicio de recurrencia** · Audience: organization administrators*

> **About the labels in this guide:** buttons, fields and menus are written exactly as they appear in the Spanish version of the console, with an English explanation where it helps.

---

## What the Recurrence service is

**It is the screen where you set how Afrus makes the automatic charges of your monthly and recurring donations.** On screen its title is **Configuración del Motor de Recurrencia** (Recurrence engine settings).

There you choose, for example, how often a donation is charged and what to do when a charge fails.

> **Important:** these settings apply to the recurring donations that Afrus charges. If your payment gateway charges subscriptions on its own (for example Stripe, PayU or Pagar.me), the gateway decides when the charge happens.

## What it is for

- **Choosing how often** a recurring donation is charged: every month, every three months, every six months or every year.
- **Deciding what happens if a charge fails:** how many times it is retried and on which dates.
- **Choosing the charge days**, if you use the **Charities** mode.
- **Going back to the original settings** with a single button if something doesn't convince you.

> **Pending confirmation:** that changes on this screen modify the real charges. Before changing anything important, check with the Afrus team.

## Before you start

- **You need access to Configuración** (Settings) for your organization.
- **Changes are not immediate:** the screen says *"Los cambios se aplicarán a los próximos ciclos de cobro."* (Changes will apply to the next billing cycles.)

---

# Step by step

## How to set up the Recurrence service

1. **Open the screen.** Go to **Configuración > Pagos > Servicio de recurrencia**. You will see the title **Configuración del Motor de Recurrencia**.
   ![Configuración del Motor de Recurrencia screen with the current settings and the Modo mejorado, Periodicidad and Modo de reintento fields](img/como-configurar-el-servicio-de-recurrencia-01.webp)

2. **Choose the mode.** In **Modo mejorado** (Enhanced mode), choose **Standard** or **Charities**. With **Charities** you can also choose the charge days.

3. **Choose how often to charge.** In **Periodicidad** (Frequency), choose **Mensual** (monthly), **Trimestral** (quarterly), **Semestral** (every six months) or **Anual** (yearly).
   ![Periodicidad list open with Mensual, Trimestral, Semestral and Anual](img/como-configurar-el-servicio-de-recurrencia-03.webp)

4. **If you chose Charities, pick the charge days.** **Días de cobro (Charities)** (Charge days) appears so you can choose which days to charge.

5. **Decide what happens if a charge fails.** In **Modo de reintento** (Retry mode), choose **Standard retries**, **Charities retries** or **Custom**.
   ![Modo de reintento list open with Standard retries, Charities retries and Custom](img/como-configurar-el-servicio-de-recurrencia-05.webp)

6. **If you chose Custom, set the retries.** In **Tipo de configuración de reintentos** (Retry setup type) choose:
   - **Consecutivo** (Consecutive): set the **Máximo de intentos** (Maximum attempts).
   - **Fechas específicas** (Specific dates): choose the **Fechas específicas de reintento** (Specific retry dates).
   ![Custom retry mode with Tipo de configuración de reintentos and Máximo de intentos](img/como-configurar-el-servicio-de-recurrencia-06.webp)

7. **Save your changes.** They will apply to the next billing cycles.

> **Pending confirmation:** the exact name of the save button.

> **Can it be undone?** Yes. You can change the options at any time, or click "Restaurar valores por defecto" (Restore default values) to go back to the original settings.

---

## Known limitations

- **Gateways that charge on their own:** with Stripe, PayU or Pagar.me, the gateway decides when to charge; this screen does not change those charges.
- **Effect on real charges:** it is not yet confirmed that these settings change the charges. Check with the Afrus team before making changes.
- **Frequencies other than monthly and yearly:** it is not confirmed how **Trimestral** and **Semestral** are calculated.

## Frequently asked questions

**At what time are charges made?**
> **Pending confirmation:** the schedule of automatic charges.

**How many times is a failed charge retried before the subscription is cancelled?**
> **Pending confirmation:** the number of retries and when a subscription is cancelled automatically.

**Do the changes affect existing subscriptions?**
The screen says changes apply to the next billing cycles.

---

> **[Back to section index](./README.md)** · **[Back to main index](../README.md)**

*Last updated: 2026-10-26*
