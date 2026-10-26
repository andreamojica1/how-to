# Guía de Importaciones

Con esta guía vas a poder subir a Afrus, de una sola vez, una lista de contactos o de donaciones que tienes en un Excel o en otro sistema.

*Módulo: Data · Menú: **Data > Importaciones** · Audiencia: equipos de datos, recaudación y administración*

---

## Qué son las importaciones

**Importar es subir a Afrus muchos datos a la vez desde un archivo**, en lugar de cargarlos uno por uno.

En **Data > Importaciones** puedes subir dos tipos de listas:

- **Leads:** tus contactos (personas).
- **Transacciones:** donaciones que recibiste antes o por fuera de Afrus.

Esta pantalla se abre en la versión anterior de Afrus, por eso se ve distinta.

> Si tu organización está en Brasil y quieres subir el archivo de boletos pagados del banco, eso se hace en otra pantalla. Mira la [Guía de Importaciones - itaú](../follow-up/importaciones-itau-guide.md).

## Para qué sirven

- **Traer tus contactos desde otro sistema** sin escribirlos a mano.
- **Cargar tu historial de donaciones,** para tener en Afrus la información completa de cada donante.
- **Actualizar datos de personas que ya tienes.** Si una persona del archivo ya existe en Afrus, se actualiza con los datos nuevos.
- **Agrupar lo que importas.** Puedes ponerle un tag a todas las personas del archivo para encontrarlas después.

## Antes de empezar

- **Tu archivo en Excel o CSV** (`.xlsx`, `.xls` o `.csv`), de hasta 20 MB.
- **Para importar donaciones:** tu organización necesita tener activa la pasarela "Simple Afrus" en la moneda de esas donaciones. Si no la tienes, escríbenos.
- **Revisa tu archivo** con la lista de "Qué tener en cuenta al importar" de esta guía. Te ahorrará errores.

---

# Paso a paso

## Cómo importar un archivo

1. **Abre las importaciones.** Ve a **Data > Importaciones** y haz clic en "Importar".
   <!-- captura pendiente: como-importar-un-archivo-01 — lista de importaciones con el botón Importar -->

2. **Elige qué vas a importar.** En "¿Qué desea importar?" elige **Leads** (contactos) o **Transacciones** (donaciones) y haz clic en "Continuar".
   <!-- captura pendiente: como-importar-un-archivo-02 — pantalla ¿Qué desea importar? con las opciones Leads y Transacciones -->

3. **Sube tu archivo.** Haz clic en "Añadir archivos" o arrastra el archivo. Puedes subir varios a la vez.

4. **Confirma el permiso de tus contactos (solo Leads).** Marca la casilla *"Certifico que cuento con el consentimiento de las personas incluidas en este archivo para importar sus datos y enviarles comunicaciones multicanal (email, WhatsApp, SMS)."* y haz clic en "Importar".

5. **Une cada columna con su campo en Afrus.** Por cada columna de tu archivo ("Datos archivos importados"), elige a qué dato de Afrus corresponde ("Campos de Afrus"). Por ejemplo: tu columna "Mail" va con correo electrónico. Así Afrus sabe dónde guardar cada dato.
   <!-- captura pendiente: como-importar-un-archivo-05 — pantalla para unir las columnas del archivo con los campos de Afrus -->

6. **Ponle un tag (opcional).** En **Tag** puedes escribir una etiqueta para todas las personas del archivo, por ejemplo el nombre del evento donde las conociste.

7. **Solo para donaciones, completa estos datos:** la moneda (**Selección de moneda**), el estado de las donaciones (**Estatus de la transacción**: Exitosa, Pendiente, Fallida o Reembolsado) y la **Campaña** a la que pertenecen. La casilla **Disparar eventos** viene marcada; déjala así si quieres que esas donaciones se compartan con los sistemas que tengas conectados a Afrus.

8. **Envía.** Haz clic en "Siguiente" y luego en "Enviar". Verás *"¡Listo!"*; haz clic en "Aceptar".

Al terminar, tu importación aparece en la lista. Primero dirá **En cola** o **Procesando** y, cuando termine, **Finalizado** o **Finalizado con errores**. Dentro de la consola verás el aviso *"Importación finalizada"*.

> **¿Se puede deshacer?** No hay un botón para deshacer una importación. Si importas donaciones dos veces, quedan repetidas. Revisa bien el archivo antes de enviarlo.

## Qué tener en cuenta al importar

**Sobre el archivo:**

- **Usa solo la primera hoja.** Si tu Excel tiene varias hojas, Afrus solo lee la primera.
- **La primera fila debe tener los títulos** de cada columna (Nombre, Correo, Monto…).
- **Escribe las fechas como día/mes/año**, por ejemplo 25/10/2026.

**Datos obligatorios:**

| Si importas… | Tu archivo debe tener |
|---|---|
| **Leads** (contactos) | Correo electrónico y nombre |
| **Transacciones** (donaciones) | Monto (solo números), correo electrónico y nombre |

Si falta el correo, la pantalla te deja seguir, pero todas las filas fallan. Revisa que lo hayas unido a su campo.

**Sobre los nombres, teléfonos y documentos:**

- **Nombre y apellido:** puedes usar una sola columna con el nombre completo o columnas separadas para nombre y apellido. Afrus acepta las dos formas.
  > **Pendiente de confirmar:** si conviene separar nombre y apellido para que Afrus los guarde mejor.
- **Teléfonos:**
  > **Pendiente de confirmar:** en qué formato deben ir los teléfonos (por ejemplo, con el indicativo del país y el signo "+").
- **Tipo de documento:**
  > **Pendiente de confirmar:** cómo debe escribirse el tipo de documento (por ejemplo, con un número o código equivalente).

**Personas repetidas:**

- Afrus reconoce a cada persona por su **correo electrónico**. Si ya existe, la **actualiza** con los datos del archivo que no estén vacíos. Si no existe, la crea.

**Donaciones repetidas:**

- Cada fila crea una donación nueva. **Si subes el mismo archivo dos veces, las donaciones quedan duplicadas.**

> **Importante, permisos de contacto:** al importar, Afrus marca a cada persona del archivo como que **acepta recibir comunicaciones por todos los canales**, incluso si antes se había dado de baja. Por eso, incluye solo a personas que te dieron su permiso, y saca del archivo a quienes pidieron no recibir mensajes.

**Lo que Afrus agrega solo:**

- Cada persona importada recibe un tag automático con la fecha y la hora de la importación (empieza por "import-"). Así siempre sabes de qué importación vino.
- Las donaciones importadas no envían avisos a tu equipo.

## Resultados de una importación

En la lista de **Data > Importaciones** ves todas tus importaciones con su **Status** (estado), el **Archivo**, la **Fecha** y quién la hizo (**Importación por**). Por defecto se muestran las del mes; puedes buscar y cambiar las fechas.
<!-- captura pendiente: resultados-de-una-importacion-01 — lista de importaciones con las columnas Status, Archivo, Fecha e Importación por -->

| Estado | Qué significa |
|---|---|
| **En cola** | Está esperando su turno |
| **Procesando** | Afrus la está cargando |
| **Finalizado** | Terminó sin errores |
| **Finalizado con errores** | Algunas filas (o todas) no se pudieron cargar |

**Si dice "Finalizado con errores":**

1. **Abre los errores.** Haz clic en el lápiz de esa importación. Verás las filas que fallaron.
2. **Corrige el archivo.** Por ahora, corregir las filas desde esa pantalla y reenviarlas no funciona. Lo más seguro es corregir esas filas en tu archivo y volver a importar **solo esas filas**.

> **Importante:** "Finalizado con errores" aparece tanto si fallaron unas pocas filas como si fallaron todas. Revisa siempre el detalle.

Cada usuario ve solo las importaciones que hizo él. Si no encuentras una, pregúntale a la persona de tu equipo que la subió.

---

## Preguntas frecuentes

**¿Cuántas filas puedo subir?**
El archivo puede pesar hasta 20 MB.
> **Pendiente de confirmar:** si hay un límite de filas.

**¿Los contactos importados reciben mis correos automáticos?**
> **Pendiente de confirmar:** si las personas o donaciones importadas activan tus autoresponders o flujos de trabajo.

**¿Me llega un correo cuando termina la importación?**
No. El aviso *"Importación finalizada"* aparece dentro de la consola.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-26*
