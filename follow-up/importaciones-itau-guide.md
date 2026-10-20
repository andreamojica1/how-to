# Guía de Importaciones - itaú

Después de leer esta guía sabrás qué es **Importaciones - itaú**, para qué sirve y cómo cargar el archivo de retorno del banco Itaú para que Afrus registre las donaciones de boletos pagados.

*Módulo: Follow up · Menú: **Follow up > Importaciones - itaú** · Audiencia: equipos de recaudación y finanzas de organizaciones en Brasil*

---

## Qué es Importaciones - itaú

**Importaciones - itaú es donde cargas el archivo de retorno que te entrega el banco Itaú (formato CNAB 400) después de procesar tus boletos, para que Afrus registre como donaciones los boletos pagados.**

Es el último paso del recorrido de **Follow up > Boleto Itaú**: generas los boletos, los envías al banco, el banco te devuelve el resultado y lo cargas aquí.

## Para qué sirve

- **Registrar automáticamente los pagos de boletos** a partir del archivo del banco, asociándolos a la persona correcta.
- **Ver el resultado línea por línea**, con estados **Éxito**, **Error**, **Pendiente** y **Omitido**, y el mensaje de cada error.
- **Alimentar los indicadores de Boleto Itaú**: cobrados, rechazados y sin retorno.

## Antes de empezar

- **Ten el archivo de retorno del banco** (CNAB 400) de boletos generados con Afrus.
- **Ten una campaña activa** donde registrar las donaciones.
- **Revisa los datos de las personas.** Para registrar la donación, cada persona necesita CEP, tipo de documento y número de documento.

---

# Paso a paso

## Cuál es el proceso para crear una importación

1. **Abre Importaciones.** Entra a **Follow up > Importaciones - itaú** y pulsa "Crear importación".
   <!-- captura pendiente: como-crear-una-importacion-itau-01 — lista Importaciones con el botón Crear importación -->

2. **Revisa el tipo.** En **Tipo de importación** deja **Boleto** (es la única opción).

3. **Elige la campaña.** En **Campaña**, elige una campaña activa (obligatorio). Ahí quedarán registradas las donaciones.

4. **Elige el widget (opcional).** En **Formulario / Widget** aparecen los widgets activos de esa campaña. Si no eliges ninguno, *"Se usará el widget predeterminado si no se selecciona ningún formulario"*.

5. **Sube el archivo.** Pulsa "Subir archivos" o arrástralo a la zona *"Arrastra archivos para subirlos"*. Tamaño máximo: 64 MB.

6. **Importa.** Pulsa "Importar".

Verás el diálogo **Importación en proceso**: *"El proceso de importación comenzó con éxito. En minutos podrás ver los resultados"*, con el botón "Ver procesos de importación".

> **Importante:** este diálogo puede aparecer aunque la subida del archivo haya fallado. Confirma siempre que tu importación figure en la lista de **Follow up > Importaciones - itaú**.

> **¿Se puede deshacer?** **Pendiente de confirmar:** si una importación se puede anular. Revisa la campaña y el archivo antes de pulsar "Importar".

### Qué hace Afrus con el archivo

Por cada línea del archivo, Afrus identifica a la persona del boleto. Si tiene CEP, tipo y número de documento, registra una **donación exitosa** por el valor del boleto, en reales (BRL), con método boleto, en la campaña y el widget elegidos. Si le faltan esos datos, la línea queda en **Error** y el boleto aparece como **Pagado - no registrado** en **Follow up > Boleto Itaú**.

La importación queda finalizada cuando todas las líneas terminaron de procesarse.

## Cómo revisar el resultado

1. **Abre la lista.** Entra a **Follow up > Importaciones - itaú**.
2. **Abre la importación.** En el menú de la fila elige:
   - "Registros", con las pestañas **Detalles de transacciones** y **Registros** y un resumen de **Encontradas** / **No encontradas**, o
   - "Ver Líneas", que abre **Líneas de Importación**.
3. **Revisa cada línea.** En **Líneas de Importación** verás **Línea #**, **ID de Lead**, **ID de Donación**, el estado y el **Mensaje de Error**. Haz clic en una línea para ver los **Datos en Bruto**.

---

## Estados

| Estado de la importación (en inglés) | Qué significa |
|---|---|
| `queue` | En cola |
| `processing` | Se está procesando |
| `finished` | Todas las líneas terminaron de procesarse |
| `error` | La importación falló |

| Estado de línea | Qué significa | Qué puedes hacer |
|---|---|---|
| **Pendiente** | La línea está en proceso | Esperar y volver a cargar la pantalla |
| **Éxito** | Se registró la donación | Nada |
| **Error** | No se pudo registrar | Leer el **Mensaje de Error**; si faltan CEP o documento, completar los datos de la persona |
| **Omitido** | La línea se saltó | Revisar los **Datos en Bruto** |

## Cada cuánto se actualiza

- **El procesamiento es en segundo plano** y tarda unos minutos, según el mensaje de la pantalla.
- **La pantalla no se refresca sola.** Vuelve a cargarla para ver el avance.

## Limitaciones conocidas

- **El diálogo "Importación en proceso" aparece aunque la subida haya fallado.** Comprueba que la importación figure en la lista.
- **Los estados de la importación se muestran en inglés.**
- **Solo sirve para boletos Itaú (Brasil)**, aunque el menú aparece para todas las organizaciones.

## Preguntas frecuentes

**¿Qué pasa con los boletos que el banco rechazó?**
Aparecen como **Rechazado** en **Follow up > Boleto Itaú**.
> **Pendiente de confirmar:** cómo trata la importación las líneas de boletos rechazados. Escríbenos si ves una donación que no corresponde.

**¿Qué pasa si cargo dos veces el mismo archivo?**
> **Pendiente de confirmar.** Mientras tanto, revisa la lista antes de volver a cargar un archivo.

**¿Puedo usar una campaña inactiva?**
No. Solo aparecen campañas activas.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-20*
