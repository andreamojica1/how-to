# Pasarela Afrus — entrega y hand-off

## Nota sobre la fuente (importante)

Esta guía **no sale de un archivo de hechos verificado**. Se escribió a partir de la reunión del 25/9/2026 (grabación tl;dv), en la que el ingeniero mostró una pantalla **todavía en desarrollo**. Varias etiquetas iban a cambiar después de esa reunión. **Tecnología debe validar la guía contra la pantalla real antes de publicarla.**

## Línea para el README raíz

```markdown
### [Pasarela Afrus](./pasarela-afrus/)

Las transferencias (dispersiones) que Afrus le hace a tu organización con el dinero de tus donaciones.

- [Guía de Pasarela Afrus](./pasarela-afrus/pasarela-afrus-guide.md)
```

## Estado de video por tutorial

| Tutorial | Video |
|---|---|
| Qué es la Pasarela Afrus | Sin video |
| Para qué sirve la Pasarela Afrus | Sin video |
| Cómo se configura la Pasarela Afrus | Sin video |
| Cómo leer una dispersión | Sin video |

Tutoriales web: 4 × 3 idiomas = 12 bloques (`tutoriales-web.md`).

## Capturas pendientes (ES; mismos puntos en EN/PT)

1. `como-se-configura-la-pasarela-afrus-01` — menú de perfil con la opción Pasarela Afrus.
2. `como-se-configura-la-pasarela-afrus-02` — lista de dispersiones.
3. `como-leer-una-dispersion-01` — detalle de una dispersión con sus montos.
4. `como-descargar-el-detalle-de-una-dispersion-01` — detalle por transacción.

Hay que tomarlas en una organización que tenga la pasarela de Afrus activa; en las demás la sección no aparece.

## Vacíos de información para tecnología

1. **Etiquetas finales.** En la reunión se acordó:
   - renombrar "Dispersión" a un nombre general (el menú ya muestra **Pasarela Afrus**);
   - renombrar "Total servicio tarjeta" a **Comisión pasarela**;
   - agregar tooltips que expliquen Retención ICA y Retención en la fuente;
   - mostrar el **valor recaudado** aparte, arriba;
   - agregar el tipo de transacción (única / recurrente) a la descarga;
   - poner bordes a las tablas y formato de moneda a todos los valores.

   Confirmar qué quedó implementado y con qué nombres exactos (incluidos el costo de transferencia y el valor transferido).
2. **Frecuencia de las dispersiones:** cada cuánto se hacen y cómo pide una organización cambiarla.
3. **Detalle y descarga:** cómo se abre el detalle de una dispersión y en qué formato se descarga el archivo.
4. **Costo de transferencia:** en la reunión se dijo que es un estándar de 7.000 COP para todos los clientes. ¿Se publica la cifra en la guía o se deja general?
5. **Roles:** qué usuarios de la organización pueden ver esta sección.
6. **Etiquetas en inglés y portugués** de la pantalla.

## Contexto interno (no va en textos para clientes)

- Afrus maneja dos unidades de negocio: la pasarela de pagos (Colombia) y el uso de la plataforma (Estados Unidos). Por eso los cobros de la plataforma no se pueden descontar de las dispersiones. A los clientes solo se les dice, de forma neutra, que son dos cobros separados.
- Hoy tienen acceso unas 28 a 30 organizaciones.
- Las consultas a fondo sobre tarifas y comisiones las atiende el equipo de finanzas (según la reunión, Estefany).

## Acción pendiente acordada en la reunión

- Enviar un mensaje masivo a las organizaciones con pasarela de Afrus para avisarles de la nueva sección.

## Defectos encontrados

Ninguno confirmado. La pantalla estaba en desarrollo; los cambios acordados están en el punto 1 de los vacíos.
