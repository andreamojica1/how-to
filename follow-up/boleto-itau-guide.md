# Guía de Boleto Itaú

Después de leer esta guía sabrás qué es **Boleto Itaú**, para qué sirve y cómo generar boletos en lote para un grupo de personas y seguir su cobro.

*Módulo: Follow up · Menú: **Follow up > Boleto Itaú** · Audiencia: equipos de recaudación y finanzas de organizaciones en Brasil*

---

## Qué es Boleto Itaú

**Boleto Itaú es la pantalla donde sigues los lotes de boletos bancarios (Brasil, banco Itaú) que tu organización genera para un grupo de personas, y su resultado de cobro.**

Cada lote prepara un boleto por persona, en reales (BRL), y produce el archivo "remessa" que se envía al banco. Cuando el banco devuelve su respuesta y la cargas en **Follow up > Importaciones - itaú**, esta pantalla muestra qué boletos se cobraron y cuáles no.

> **Importante:** generar boletos solo está disponible para organizaciones con país Brasil. El menú aparece en todas las organizaciones, pero la opción para generarlos solo se muestra en las de Brasil.

## Para qué sirve

- **Generar boletos en lote** para un segmento de personas, con un monto y un vencimiento comunes.
- **Obtener el archivo remessa** de cada lote para enviarlo al banco.
- **Ver el avance del cobro**: cuántos boletos hay **Generados**, **Emitidos sin error**, **Efectivamente cobrados**, **Rechazados** y **Sin retorno todavía**.
- **Revisar el detalle por persona**: el estado de cada boleto, sus errores y la respuesta del banco.

## Antes de empezar

- **Tu organización debe ser de Brasil.**
- **Cada persona necesita CEP, tipo de documento y número de documento.** Si falta alguno, su boleto queda con error. Revísalo en el segmento antes de generar.
- **Ten listo el segmento** de personas a las que quieres enviar boletos, en **Data > Segmentos > Básico**.

---

# Paso a paso

## Cómo funciona y cómo se generan los boletos

El recorrido completo tiene cuatro momentos:

1. **Generas el lote** en AFRUS (pasos de abajo).
2. **Descargas el archivo remessa** y lo envías al banco Itaú. Este envío se hace fuera de AFRUS.
3. **El banco te entrega un archivo de retorno** con el resultado de cada boleto.
4. **Cargas ese archivo** en **Follow up > Importaciones - itaú**: AFRUS registra las donaciones pagadas y actualiza los indicadores de esta pantalla (ver la guía de Importaciones - itaú).

### Parte 1 — Generar el lote

1. **Abre Boleto Itaú.** Entra a **Follow up > Boleto Itaú** y pulsa "Crear Boleto Remessa". Te lleva a **Segmentos** (también puedes ir directo a **Data > Segmentos > Básico**).
   ![Pantalla Procesos de generación de boleto con el botón Crear Boleto Remessa](img/boleto-itau-01.webp)

2. **Elige el segmento.** Selecciona el segmento de personas y abre **Acciones** > **Generar Archivos de Remessa (Boleto Brasil)**. También puedes hacerlo desde **Personas**: selecciona las personas y usa la misma opción en **Acciones**.

3. **Define monto y vencimiento.** En **Generar archivo de remessa**, completa **Monto (BRL)** (mínimo 2.99 BRL) y **Fecha de vencimiento** (debe ser posterior a hoy; por defecto, dentro de 3 meses). El monto y el vencimiento son los mismos para todos los boletos del lote.

4. **Crea el archivo.** Pulsa "Crear archivo de remessa".

Verás *"El archivo de Remessa se está generando. En unos minutos podrás descargar el archivo."* con el botón "Ver procesos". Se crea un lote en **Procesos de generación de boleto**.

> **¿Se puede deshacer?** **Pendiente de confirmar:** si un lote generado se puede anular. Revisa bien el segmento, el monto y el vencimiento antes de crear el archivo.

### Parte 2 — Descargar y seguir el lote

5. **Espera a que el lote termine.** En **Follow up > Boleto Itaú** verás el lote con su estado y su **%** de avance. La pantalla no se refresca sola: vuelve a cargarla para ver el avance.

6. **Descarga el archivo.** Cuando esté listo, en el menú de la fila elige "Descargar". Ese es el archivo que envías al banco.

7. **Revisa el detalle por persona.** En el menú de la fila elige "Ver detalle por lead". Verás el estado de cada boleto, sus errores, la transacción y, cuando cargues la respuesta del banco, el **Estado de retorno**.

---

## Indicadores

Se muestran en general en la lista y por lote en el detalle.

| Indicador | Qué significa |
|---|---|
| **Generados** | Total de boletos generados |
| **Emitidos sin error** | Boletos generados correctamente, sin error en los datos de la persona ni de la pasarela |
| **Efectivamente cobrados** | Boletos que, al cargar el archivo de retorno del banco, quedaron confirmados como donación en AFRUS. Incluye el monto cobrado |
| **Rechazados** | Boletos que el banco reportó como rechazados en el archivo de retorno |
| **Sin retorno todavía** | Boletos emitidos para los que todavía no se cargó un archivo de retorno |

## Estado de retorno por persona

| Estado | Qué significa | Qué puedes hacer |
|---|---|---|
| **Sin retorno** | Aún no se cargó la respuesta del banco para este boleto | Cargar el archivo de retorno cuando el banco lo entregue |
| **Cobrado** | El banco lo confirmó y quedó como donación en AFRUS | Nada |
| **Rechazado** | El banco lo rechazó | Revisar el caso con la persona |
| **Pagado - no registrado** | El banco lo confirmó como pagado, pero no quedó como donación, normalmente por datos incompletos (CEP o documento) | Completar los datos de la persona |
| **Otro** | Otra respuesta del banco | Revisar el detalle |

## Estados de un lote

Se muestran en inglés tal cual: `created` (creado), `queued` (en cola), `pending` (en proceso), `succeeded` (terminado con éxito) y `failed` (falló).

## Cada cuánto se actualiza

- **La generación es en segundo plano** y tarda unos minutos, según el mensaje de la pantalla.
- **La pantalla no se refresca sola.** Carga al abrirla y al cambiar de página.
- **Los indicadores de cobro** cambian cuando se carga el archivo de retorno del banco en **Follow up > Importaciones - itaú**.

## Preguntas frecuentes

**¿AFRUS envía el archivo al banco?**
No. Descargas el archivo remessa y lo envías al banco por fuera de AFRUS.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-27*
