# Payment links guide

After reading this guide you will know what a payment link is, what it is for, where it is created and how to send it to a person so they can donate.

*Module: Follow up · Menu: **Follow up > Links de pago** · Audience: fundraising and donor care teams*

> **About the labels in this guide:** buttons, fields and menus are written exactly as they appear in the Spanish version of the console, with an English explanation where it helps.

---

## What a payment link is

**A payment link is a personalized link you send by email to a person so they can donate a set amount (or one they choose), once or monthly.**

The link opens your organization's default widget, already prepared with the person's details and the amount, so they only need to complete the payment.

## What it is for

- **Asking a specific person for a specific donation**, without them having to look for your form.
- **Offering a one-time or monthly donation**, with a fixed or open amount.
- **Tracking each link**: whether it was sent, used (**Finalizado** — Completed) or expired (**Expirado** — Expired).
- **Resending a link** from the list, if the person can't find it.

## Before you start

- **Your organization needs a default widget.** The link uses that widget; without one, sending fails. You choose it in **Fundraising > Widgets** (see the Business profile guide).
- **Your Business profile must have a URL.** The link is built on that address; without it, the card to create links doesn't appear on **Home**.

---

# Step by step

## Where payment links are created

You can create a payment link from two places:

| Where | When to use it |
|---|---|
| **Home**, **Link de pago** (Payment link) card | To send a link to anyone: you type their first name, last name and email. Only appears if your Business profile has a URL |
| A person's profile in **Personas** (People), **Contacto** (Contact) tab, **Link de pago** card | To send a link to someone already in your database: uses their name and email |

The **Follow up > Links de pago** screen has no create button: it is for viewing, filtering and resending the links you already sent.

## How to create a payment link

1. **Open the Link de pago card.** On **Home**, or in the person's profile (**Personas**, **Contacto** tab).
   ![Link de pago card on a person's profile, with frequency, amount, custom message and the Enviar button](img/como-crear-un-link-de-pago-01.webp)

2. **Enter the person's details.** From **Home**, fill in **Nombre** (first name), **Apellido** (last name) and **Correo electrónico** (email, required). From a person's profile, these come from their record.

3. **Check the sending channel.** In **Envíar por** (Send by), **Correo electrónico** (Email) is selected. For now, links are sent by email only.

4. **Add a phone number (optional).** In **Teléfono** (Phone); Afrus checks the format.

5. **Choose the frequency.** In **Seleccionar la frecuencia** (Select frequency), choose **Único** (One-time) or **Mensual** (Monthly).

6. **Set the amount.** Type the **Monto** (Amount, greater than 0) or tick **Valor abierto** (Open amount) so the person chooses how much to give.

7. **Personalize the message (optional).** In **Mensaje personalizado** (Custom message), write a few words for the person. A warm message helps them give.

8. **Set an expiry date (optional).** Tick **Caducar enalce** (Expire link) and choose **Seleccionar fecha** (date) and **Seleccionar hora** (time). Read the expiry limitation below first.

9. **Send.** Click "Enviar" (Send) and, in *"Desea enviar el link de pago?"* (Do you want to send the payment link?), click "Confirmar" (Confirm).

When you finish you will see *"¡Link de pago creado con éxito!"* (Payment link created successfully) with the destination email. The person is registered (or updated) in the default widget's campaign, receives the email with the link, and the link appears in **Follow up > Links de pago** with status **Creado** (Created). If the email fails you will see *"¡Hubo un error al crear el link de pago!"* (There was an error creating the payment link).

> **Can it be undone?** No. Once confirmed, the email is sent. If you made a mistake, send a new link with the right details.

## How to resend a link

1. **Open the list.** Go to **Follow up > Links de pago**.
2. **Find the link.** Use the search or the **Estado** (Status) filter.
3. **Resend.** Click "Reenviar" (Resend) in the row (or open it with the eye icon and resend from the detail).

---

## Payment link statuses

| Status | What it means | When it changes |
|---|---|---|
| **Creado** (Created) | The link was sent and hasn't been used successfully yet | When it is sent |
| **Finalizado** (Completed) | The person completed a successful donation with the link | As soon as the donation is confirmed |
| **Expirado** (Expired) | It had an expiry date and that date has passed | In a daily automatic check. Also, if the person opens an expired link, the form tells them |

The list shows **ID**, email, amount (or "Abierto" — Open — for open amounts), creation date, **Enviado** (Sent: Si/No), **Language Code**, **Estado** and actions.

## Known limitations

- **Email only.** WhatsApp and **Mensaje de texto** (Text message) appear disabled.
- **Expiry in another month:** if you choose an expiry date in a later month but on a lower day of the month than today (for example, it expires on the 5th of next month and today is the 11th), the link may be marked or shown as **Expirado** too early. The same can happen with the chosen time. For now there is no alternative within Afrus, other than sending the link without an expiry date.
- **Creation time in the list:** the month is shown instead of the minutes. Use the date as reference.
- **The "Caducar enalce" option** has a typo on screen: it is the option to make the link expire.
- **If the donation fails,** the link stays in **Creado**.

## Frequently asked questions

**Can I send the link by WhatsApp?**
Not for now. Afrus sends payment links by email only.

**Does the link work for a monthly donation?**
Yes. In **Seleccionar la frecuencia** choose **Mensual**.

**What does the person see if they open a link they already used?**
> **Pending confirmation:** what the form shows when a **Finalizado** link is opened.

**What language is the email in?**
> **Pending confirmation:** Afrus picks the template by organization type and language; not every case has been verified.

---

> **[Back to section index](./README.md)** · **[Back to main index](../README.md)**

*Last updated: 2026-10-20*
