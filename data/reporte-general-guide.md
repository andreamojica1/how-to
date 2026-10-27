# Guía de Reporte general

Con esta guía vas a poder ver en una sola pantalla cómo le va a tu organización: cuánto recaudaste, cuántas personas nuevas llegaron, cómo van tus donaciones mensuales y de dónde vienen tus donantes.

*Módulo: Data · Menú: **Data > Reporte general** · Audiencia: dirección, equipos de recaudación y comunicaciones*

---

## Qué es el Reporte general

**El Reporte general es un tablero con los números más importantes de tu organización para el período que elijas.** Reúne en un solo lugar tus personas, tus suscripciones (donaciones mensuales), tus transacciones y tus comunicaciones.

Los números se calculan en el momento, con los datos más recientes, cada vez que abres la pantalla o cambias el período.

## Para qué sirve

- **Ver de un vistazo cómo vas.** Cuánto recaudaste, cuántas personas nuevas llegaron y cómo van las donaciones mensuales.
- **Saber qué funciona.** Ves de qué campaña, formulario (widget), UTM o página vienen tus personas, suscripciones y donaciones.
- **Compartir resultados.** Puedes descargar los números para tu equipo o tu junta directiva.

---

# Paso a paso

## Cómo analizar el Reporte general

1. **Abre el reporte.** Ve a **Data > Reporte general**. Al abrirlo, verás el último mes completo (por ejemplo, si estamos en octubre, verás septiembre).
   ![Pantalla Vista general con el selector Presets y la zona Global](img/reporte-general-01.webp)

2. **Elige el período.** Usa los filtros de arriba (te los explicamos en "Para qué son los filtros Presets, Año y Mes").

3. **Revisa las 5 zonas, de arriba hacia abajo.** Cada una responde una pregunta distinta:

| Zona | Qué te dice | Qué mirar |
|---|---|---|
| **01 Global** | Cuántas personas nuevas llegaron y cuántas se volvieron donantes | El paso de **Leads** a **Donantes** y a **Donantes recurrentes**: el porcentaje te dice cuántas personas nuevas se animaron a donar |
| **02 Suscripciones** | Cómo van tus donaciones mensuales | **Activas**, **Fallidas** y **Canceladas**; **MRR** (lo que suman al mes las suscripciones activas creadas en el período) y **ARR** (esa cifra proyectada a un año) |
| **03 Transacciones** | Cuánto recaudaste | **Ingresos totales**, las donaciones **Confirmadas** y las **Otras** (pendientes, fallidas y reembolsadas) |
| **04 Personas** | Cuántos contactos nuevos tienes | **Personas nuevas**, **Leads**, **Donantes** y **Donantes recurrentes** |
| **05 Comunicaciones** | Cuánto te comunicaste | **Emails enviados** y **Mensajes WhatsApp enviados** |

   ![Zonas Suscripciones y Transacciones con sus indicadores](img/reporte-general-03.webp)

4. **Mira de dónde vienen.** Las tablas "por origen" (**Nuevas suscripciones por origen**, **Transacciones por origen** y **Nuevos leads por origen**) separan los resultados en bloques, uno debajo de otro: **Por campaña**, **Por widget**, **Por UTM campaign**, **Por UTM medium**, **Por UTM source** y **Por URL de landing**. Cada tabla aparece cerrada: haz clic en su título para abrirla. Cada bloque tiene su propio botón "Descargar". Así sabes qué campaña o qué formulario te trae más donantes.
   ![Tabla Transacciones por origen abierta, con Por campaña y Por widget](img/reporte-general-04.webp)

**Algunas claves para leerlo bien:**

- **Total fallidas** cuenta solo las donaciones únicas que fallaron. Los cobros mensuales que fallaron están en **Cargos fallidos**.
- Los montos están en la moneda de tu organización.
- **ARR** es una proyección (el MRR multiplicado por 12), no dinero recibido.

## Para qué son los filtros Presets, Año y Mes

Sirven para elegir el período que quieres ver y descargar.

**Presets** son atajos de un clic:

| Preset | Qué período muestra |
|---|---|
| **Todo** | Toda la historia de tu organización |
| **Año anterior** | El año pasado completo |
| **YTD** | Desde el 1 de enero de este año hasta hoy |
| **Trimestre anterior** | Los tres meses del trimestre pasado |
| **QTD** | Desde el inicio de este trimestre hasta hoy |
| **Mes anterior** | El mes pasado completo |
| **MTD** | Desde el inicio de este mes hasta hoy |

**Año** y **Mes** sirven para elegir un mes o un año concreto, hasta 8 años atrás. Por ejemplo, para comparar tu campaña de diciembre de este año con la del año pasado, mira primero un diciembre y luego el otro.

![Selector de período con el menú Presets abierto y los selectores Año y Mes](img/para-que-son-los-filtros-presets-ano-y-mes-01.webp)

> **Ten en cuenta:** no hay filtro por campaña ni por moneda, ni un rango de fechas libre, ni comparación automática con el período anterior.

## Qué descarga el botón Descargar

- **El botón "Descargar" de arriba** baja un archivo CSV (se abre con Excel o Google Sheets) con todos los indicadores del período elegido. Tiene cuatro columnas: **Sección**, **KPI**, **Actual** y **Unidad**.
- **Cada tabla "por origen" tiene su propio botón "Descargar"**, que baja solo esa tabla.

![Botón Descargar arriba de la pantalla del reporte](img/que-descarga-el-boton-descargar-01.webp)

> **Ten en cuenta:** si una tabla por origen tiene más de 5000 filas, no se puede descargar y verás un mensaje de error. Elige un período más corto y vuelve a intentarlo.

---

## Preguntas frecuentes

**¿Los números están al día?**
Sí. Se calculan en el momento cada vez que abres la pantalla o cambias el período.

**¿Puedo ver el reporte de una sola campaña?**
No con un filtro, pero en las tablas por origen, en **Por campaña**, ves los resultados de cada campaña.

**¿Por qué el reporte abre en el mes pasado?**
Porque muestra el último mes completo, que es el que ya tiene todos sus resultados. Si quieres ver el mes actual, usa **MTD**.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-26*
