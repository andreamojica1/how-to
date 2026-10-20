# Guía de Transacciones abandonadas

Después de leer esta guía sabrás qué son las Transacciones abandonadas, cuándo Afrus considera que una donación se abandonó y cómo usar esta lista para recontactar a esas personas.

*Módulo: Follow up · Menú: **Follow up > Transacciones abandonadas** · Audiencia: equipos de recaudación y atención a donantes*

---

## Qué son las Transacciones abandonadas

**Las Transacciones abandonadas son la lista de personas que empezaron una donación en un widget, llegaron al paso de pago y no la terminaron.**

Para cada caso ves el **Lead ID**, el nombre, el **Email**, el teléfono, el **Widget** y la **Campaña** con los que empezó la donación, y la fecha en que se registró el abandono.

## Para qué sirve

- **Recuperar donaciones a medio camino.** Son personas que ya mostraron intención de donar: un buen recordatorio puede convertirlas.
- **Saber dónde se quedaron.** Ves con qué **Widget** y **Campaña** empezaron, para revisar si algo de ese formulario frena a tus donantes.
- **Tener los datos de contacto a mano.** **Email** y teléfono, listos para escribirles o llamarles.
- **Trabajar la lista fuera de Afrus.** Exporta la lista; el archivo queda en **Descargas**.

---

# Paso a paso

## Cada cuánto se actualiza

- **Afrus revisa los abandonos cada hora, en punto.**
- **Una donación aparece como abandonada entre 15 minutos y aproximadamente 1 hora y 15 minutos** después de que la persona dejó de avanzar.
- **La pantalla no se refresca sola.** Los datos se cargan al abrirla y al cambiar fechas, orden o página. Recarga la página para ver los casos nuevos.

## Cuándo una transacción se considera abandonada

1. **La persona inicia una donación en un widget y llega al paso de pago.** En ese momento Afrus la marca como "en proceso de donar".
2. **Si la donación termina, no es un abandono.** Tanto si el pago sale exitoso como si falla, esa marca se borra y la persona no aparece en esta lista.
3. **Si la marca sigue activa, la revisión horaria la registra como abandonada** cuando la última actividad de la persona fue hace entre 15 minutos y 1 hora y 15 minutos.
4. **Debe existir el registro de inicio de donación** para ese widget y esa campaña.

Las personas marcadas como spam (ver **Follow up > Leads spam**) no se registran como abandonadas.

## Cómo revisar y exportar las transacciones abandonadas

1. **Abre la lista.** Entra a **Follow up > Transacciones abandonadas**.
   <!-- captura pendiente: transacciones-abandonadas-01 — lista de Transacciones abandonadas -->
2. **Elige las fechas.** Por defecto se muestra el mes en curso. El filtro usa la fecha en que se registró el abandono.
3. **Selecciona las filas.** Marca las que quieras, o selecciona todas con el aviso de selección.
4. **Exporta.** Pulsa "Acciones" y elige **Exportar**. El archivo se genera en **Descargas**.

En esta pantalla, "Acciones" solo ofrece exportar: no permite asignar etiquetas ni borrar.

---

## Limitaciones conocidas

- **Minutos de la fecha:** la columna de fecha muestra mal los minutos (en su lugar aparece el número del mes). Si necesitas la hora exacta, por ahora no hay una alternativa dentro de esta pantalla.
- **Botón "Ver procesos":** hoy lleva a una página que no existe. Para seguir tu exportación, entra directamente a **Data > Descargas**.

## Preguntas frecuentes

**¿Si la donación falla, la persona aparece aquí?**
No. Si el pago termina, sea exitoso o fallido, no cuenta como abandono.

**¿Afrus les envía un correo automático a estas personas?**
> **Pendiente de confirmar:** existe una automatización para leads abandonados, pero depende de la configuración de cada organización.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-20*
