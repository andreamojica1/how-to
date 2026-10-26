# Procesos en ejecucion guide

With this guide you will know whether an action you ran on many people at once (for example, tagging them or deleting them) has finished.

*Module: Trackers · Menu: **Trackers > Procesos en ejecucion** (Running processes) · Audience: fundraising, data and communications teams*

> **About the labels in this guide:** buttons, fields and menus are written exactly as they appear in the Spanish version of the console, with an English explanation where it helps.

---

## What Procesos en ejecucion is

**It is a list of the actions you ran on a large group of people, with the progress of each one.**

When you do something to many people at once, Afrus doesn't do it all in one second: it goes person by person, in the background, while you keep working. This screen shows how far along each of those actions is.

Four actions appear here:

- **Adding a tag** to a group of people.
- **Deleting** a group of people.
- **Changing the communication permission** (opt-in) of a group.
- **Enrolling** a group of people in a workflow.

Imports, downloads and email sends do not appear here.

## What it is for

- **Knowing whether an action has finished.** For example, before emailing the people you just tagged.
- **Seeing how much is left.** You compare how many people the group had with how many have been processed.
- **Knowing who ran each action and when.** Useful when several people on your team work with the same database.

---

# Step by step

## What information you find there and how to read it

1. **Open the screen.** Go to **Trackers > Procesos en ejecucion**. You can also get there with the "Ver procesos" (View processes) button in **Personas**, **Transacciones**, **Suscripciones**, **Segmentos** and **Data > Tags**.
   <!-- screenshot pending: procesos-en-ejecucion-01 — Procesos screen with the search box and the process table -->

2. **Find your process.** To see only the processes run by someone on your team, type their email in **Buscar por email** (Search by email) and press Enter or the magnifying glass.

3. **See the newest first.** The list starts with the oldest processes. Click the **ID** or **Creado en** (Created on) column title to see the newest first.

4. **Check the progress.** Compare **Total de leads** (how many people the group had) with **Total de leads procesados** (how many have been done). When it's done, the **Finalizado** (Finished) column says "Sí" (Yes); until then it says "No".
   <!-- screenshot pending: procesos-en-ejecucion-04 — a process row with Total de leads, Total de leads procesados and Finalizado -->

5. **Reload to see changes.** The screen does not refresh by itself. Reload the page to see the progress.

**The table columns:**

| Column | What it tells you |
|---|---|
| **ID** | The process number. Write it down if you need to contact support |
| **ID de usuario** and **Correo electrónico** (user ID and email) | Who on your team ran the action |
| **Total de leads** | How many people the group had |
| **Total de leads procesados** | How many people have been processed |
| **Finalizado** | "Sí" if it finished, "No" if it's still running |
| **Creado en** | When it was started |
| **Actualizado en** (Updated on) | The last time it moved forward |
| **Tipo** (Type) | Which action it is (see the table below) |

**The Tipo column** shows an English name:

| Tipo | Which action |
|---|---|
| `tag` | Adding a tag to a group |
| `delete` | Deleting a group of people |
| `opt-in` | Changing a group's communication permission |
| `workflow_enroll` | Enrolling a group in a workflow |

> **Tip:** if the **Actualizado en** time doesn't change for a long time, the process has stopped.

When a tagging action finishes, Afrus also leaves a notice in your notifications: *"Tag Leads Process for tag: '…' finished"*.

## What to do if a process doesn't finish

If, after reloading, **Finalizado** still says "No" and **Total de leads procesados** isn't moving, the process has stopped. This screen has no retry button.

- **If it was a tag:** add it again to the same group. People who already have the tag won't get it twice.
- **If it was a deletion, a permission change or a workflow enrollment:** write down the process **ID** and contact Afrus support.

---

## Known limitations

- **A tag can stay on "No" forever.** If someone in the group couldn't be processed (for example, because they were deleted in the meantime), the process can stay on **Finalizado** "No" even though everyone else got the tag. To check, look at the tag in **Data > Tags**.
- **The Tipo column is in English.**
- **Only the four actions in this guide appear.** Imports, downloads and sends have their own screens.

## Frequently asked questions

**Does the screen refresh by itself?**
No. Reload it to see the progress.

**Why don't I see my import here?**
Because imports are not shown on this screen. This list only shows tags, deletions, permission changes and workflow enrollments.

**How long is the history kept?**
> **Pending confirmation:** how long the process history is kept.

---

> **[Back to section index](./README.md)** · **[Back to main index](../README.md)**

*Last updated: 2026-10-26*
