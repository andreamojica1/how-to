# Imports guide

With this guide you will be able to upload to Afrus, all at once, a list of contacts or donations you have in Excel or in another system.

*Module: Data · Menu: **Data > Importaciones** · Audience: data, fundraising and admin teams*

> **About the labels in this guide:** buttons and fields are written as they appear in the Spanish version of the console, with an English explanation.

---

## What imports are

**Importing means uploading a lot of data to Afrus at once from a file**, instead of entering it one by one.

In **Data > Importaciones** (Imports) you can upload two kinds of lists:

- **Leads:** your contacts (people).
- **Transacciones** (Transactions): donations you received earlier or outside Afrus.

This screen opens in the previous version of Afrus, so it looks different.

> If your organization is in Brazil and you want to upload the bank's file of paid boletos, that is done on another screen. See the [Importaciones - itaú guide](../follow-up/importaciones-itau-guide.en.md).

## What imports are for

- **Bringing your contacts from another system** without typing them in.
- **Loading your donation history,** so Afrus has each donor's full information.
- **Updating people you already have.** If a person in the file already exists in Afrus, they are updated with the new data.
- **Grouping what you import.** You can give everyone in the file a tag to find them later.

## Before you start

- **Your file in Excel or CSV** (`.xlsx`, `.xls` or `.csv`), up to 20 MB.
- **To import donations:** your organization needs the "Simple Afrus" gateway active in the currency of those donations. If you don't have it, contact us.
- **Check your file** against the "What to check before importing" list in this guide. It will save you errors.

---

# Step by step

## How to import a file

1. **Open imports.** Go to **Data > Importaciones** and click "Importar" (Import).
   <!-- screenshot pending: how-to-import-a-file-01 — import list with the Importar button -->

2. **Choose what you will import.** Under "¿Qué desea importar?" (What do you want to import?) choose **Leads** (contacts) or **Transacciones** (donations) and click "Continuar" (Continue).
   <!-- screenshot pending: how-to-import-a-file-02 — What do you want to import screen with the Leads and Transacciones options -->

3. **Upload your file.** Click "Añadir archivos" (Add files) or drag the file in. You can upload several at once.

4. **Confirm your contacts' permission (Leads only).** Check the box *"Certifico que cuento con el consentimiento de las personas incluidas en este archivo para importar sus datos y enviarles comunicaciones multicanal (email, WhatsApp, SMS)."* (I certify that I have the consent of the people in this file to import their data and send them multichannel communications) and click "Importar".

5. **Match each column to its Afrus field.** For each column in your file ("Datos archivos importados", imported file data), choose which Afrus data it matches ("Campos de Afrus", Afrus fields). For example: your "Mail" column goes with email. This way Afrus knows where to save each piece of data.
   <!-- screenshot pending: how-to-import-a-file-05 — screen to match file columns with Afrus fields -->

6. **Add a tag (optional).** In **Tag** you can write a tag for everyone in the file, for example the name of the event where you met them.

7. **For donations only, fill in:** the currency (**Selección de moneda**), the donations' status (**Estatus de la transacción**: Exitosa/Successful, Pendiente/Pending, Fallida/Failed or Reembolsado/Refunded) and the **Campaña** (Campaign) they belong to. The **Disparar eventos** (Trigger events) box comes checked; leave it that way if you want those donations shared with the systems you have connected to Afrus.

8. **Send.** Click "Siguiente" (Next) and then "Enviar" (Send). You will see *"¡Listo!"* (Done!); click "Aceptar" (OK).

When you finish, your import appears in the list. First it says **En cola** (Queued) or **Procesando** (Processing) and, when done, **Finalizado** (Finished) or **Finalizado con errores** (Finished with errors). Inside the console you will see the notice *"Importación finalizada"* (Import finished).

> **Can it be undone?** There is no button to undo an import. If you import donations twice, they are duplicated. Check the file carefully before sending it.

## What to check before importing

**About the file:**

- **Use only the first sheet.** If your Excel file has several sheets, Afrus only reads the first one.
- **The first row must have the column titles** (Name, Email, Amount…).
- **Write dates as day/month/year**, for example 25/10/2026.

**Required data:**

| If you import… | Your file must have |
|---|---|
| **Leads** (contacts) | Email and name |
| **Transacciones** (donations) | Amount (numbers only), email and name |

If the email is missing, the screen lets you continue, but every row fails. Make sure you matched it to its field.

**About names, phones and documents:**

- **First and last name:** you can use one column with the full name or separate columns for first and last name. Afrus accepts both.
  > **Pending confirmation:** whether it is better to separate first and last name so Afrus stores them better.
- **Phones:**
  > **Pending confirmation:** what format phone numbers should have (for example, with the country code and a "+" sign).
- **Document type:**
  > **Pending confirmation:** how the document type should be written (for example, as an equivalent number or code).

**Repeated people:**

- Afrus recognizes each person by their **email**. If they already exist, they are **updated** with the file's non-empty data. If not, they are created.

**Repeated donations:**

- Each row creates a new donation. **If you upload the same file twice, the donations are duplicated.**

> **Important, contact permissions:** when importing, Afrus marks each person in the file as **accepting communications on all channels**, even if they had unsubscribed before. So include only people who gave you their permission, and remove from the file anyone who asked not to receive messages.

**What Afrus adds automatically:**

- Each imported person gets an automatic tag with the import's date and time (it starts with "import-"). That way you always know which import they came from.
- Imported donations don't send notifications to your team.

## Import results

In the **Data > Importaciones** list you see all your imports with their **Status**, **Archivo** (File), **Fecha** (Date) and who did it (**Importación por**, Imported by). By default the current month is shown; you can search and change the dates.
<!-- screenshot pending: import-results-01 — import list with the Status, Archivo, Fecha and Importación por columns -->

| Status | What it means |
|---|---|
| **En cola** (Queued) | Waiting its turn |
| **Procesando** (Processing) | Afrus is loading it |
| **Finalizado** (Finished) | Finished without errors |
| **Finalizado con errores** (Finished with errors) | Some rows (or all) couldn't be loaded |

**If it says "Finalizado con errores":**

1. **Open the errors.** Click the pencil on that import. You will see the rows that failed.
2. **Fix the file.** For now, fixing the rows on that screen and resending them doesn't work. The safest way is to fix those rows in your file and import **only those rows** again.

> **Important:** "Finalizado con errores" appears whether a few rows failed or all of them. Always check the detail.

Each user only sees the imports they did. If you can't find one, ask the person on your team who uploaded it.

---

## Frequently asked questions

**How many rows can I upload?**
The file can be up to 20 MB.
> **Pending confirmation:** whether there is a row limit.

**Do imported contacts receive my automatic emails?**
> **Pending confirmation:** whether imported people or donations trigger your autoresponders or workflows.

**Do I get an email when the import finishes?**
No. The *"Importación finalizada"* notice appears inside the console.

---

> **[Back to section index](./README.md)** · **[Back to main index](../README.md)**

*Last updated: 2026-10-26*
