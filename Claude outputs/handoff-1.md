# Glosario — entrega y hand-off

## Entrada para el README raíz

Va al inicio de **Contenido**, antes de Business profile (ya agregada en `README-how-to.md`):

```markdown
### [Glosario](./glosario/)

Las palabras que más vas a ver en Afrus, explicadas en lenguaje sencillo.

- [Glosario de Afrus](./glosario/glosario-guide.md) (también en inglés y portugués)
```

## Entregables

- `glosario-guide.md`, `.en.md`, `.pt.md`: 37 términos en 5 grupos (Pagos y donaciones · Personas y correos · Comunicaciones · Campañas, formularios y reportes · Pasarela Afrus).
- `tutoriales-web.md`: 3 tutoriales por idioma, 9 bloques. Sin video ni capturas.

## Vacíos para tecnología

1. **Contracargo:** ¿Afrus avisa a la organización? ¿Tiene costo para la organización? ¿En qué pantalla se consultan, si no aparecen en **Transacciones**?
2. **Tipo de persona:** la regla exacta que convierte a una persona en **Lead**, **Activo** o **Recurrente** (ya pendiente en la guía de Personas). La definición de Lead se apoya en el embudo Leads → Donantes → Donantes recurrentes del Reporte general.
3. **Grupo Pasarela Afrus:** sale de la reunión del 25/9/2026, no de información verificada. Tecnología debe validar nombres y definiciones (Comisión pasarela, costo de transferencia, Dispersión, Fecha de corte, Retenciones).
4. **Etiquetas EN/PT** de la consola.

## Términos dejados fuera

Ninguno de la lista pedida. "Fraude" y "Radar" se agruparon en un solo término; "Donante" y "Donante recurrente", también; "Retención ICA" y "Retención en la fuente", también.

## Fuentes por término

| Término | Fuente |
|---|---|
| Cargo, Única, Recurrente, Transacción, Pendiente de confirmación, Reembolso | `transacciones.md` / guía de Transacciones |
| Suscripción | `suscripciones.md` / guía de Suscripciones |
| Contracargo | Definición general + `transacciones.md` (no aparece en la lista) + `incentivos.md` (Donación revertida) |
| Cover your cost | `widgets.md`, `transacciones.md` (etiqueta y filtro CYC) |
| Cupón, Incentivo, Sobreventa | `incentivos.md` |
| Fraude y Radar | `follow-up.md`, `transacciones.md` |
| Link de pago | `follow-up.md` |
| Pasarela de pago | guía de Pasarelas de pago (Configuración), `widgets.md` |
| Persona, Lead, Donante, Opt-in/Opt-out, Soft/Hard bounce, Solo contactables | `personas.md`, `data.md` (Reporte general); definiciones generales de rebote |
| Tag, Segmento | `data.md` |
| Autoresponder, Blast, Merge tag | `interacciones.md` |
| Campaña, UTM | `campanas.md`, `data.md`; definición general de UTM |
| MRR, ARR | `data.md` (Reporte general) |
| Widget | `widgets.md` |
| Comisión pasarela, Costo de transferencia, Dispersión, Fecha de corte, Retenciones | Guía de Pasarela Afrus (reunión 25/9/2026, sin validar) |
