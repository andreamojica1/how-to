# Incentivos — entrega y hand-off

## Entrada para el README raíz

Agregar bajo **Contenido disponible**, después de Widgets; actualizar *Última actualización del índice* a 2026-10-26:

```markdown
### [Incentivos](./incentivos/)

Obsequios para quienes donan desde un monto mínimo, cupones, donaciones a nombre de otra persona y seguimiento de entregas.

- [Guía de Incentivos](./incentivos/incentivos-guide.md)
```

## Estado de video por tutorial

| Tutorial | Video |
|---|---|
| Qué son los incentivos | Sin video |
| Para qué sirven los incentivos | Sin video |
| Cómo crear incentivos | Sin video |
| Para qué son los cupones | Sin video |
| Cómo configurar un incentivo para un tercero | Sin video |
| Qué widgets pueden tener incentivos | Sin video |
| Cuántos incentivos puedo configurar | Sin video |
| Para qué crear un workflow en los incentivos | Sin video |
| Qué incentivos requieren un workflow | Sin video |
| Ocasiones para donar un incentivo a terceros | Sin video |
| Qué pasa si un incentivo no tiene stock | Sin video |
| Cómo hacer seguimiento a los incentivos donados | Sin video |

Tutoriales web: 12 × 3 idiomas = 36 bloques (`tutoriales-web.md`). Capturas pendientes, marcadas en las guías con `<!-- captura pendiente -->`.

**Etiquetas EN/PT:** las que trae el archivo de hechos (por ejemplo Create incentive / Criar incentivo, Save selection / Salvar seleção, Reward assigned / Recompensa atribuída) se usan tal cual. Las demás van en español con traducción entre paréntesis.

## Vacíos de información para tecnología

1. **Reserva de 60 minutos:** ¿qué ve el donante si tarda más de 60 minutos en pagar?
2. **Borrado de datos por privacidad:** ¿cuántos días se conservan la dirección y los datos del homenajeado antes de borrarse?
3. **Pasarelas y métodos de pago:** ¿cuáles admiten el obsequio? Solo se revisaron algunas (tarjeta y PayPal en varias pasarelas); faltan Pix, boleto, efectivo y el resto, una por una.
4. **Correo al homenajeado:** no hay una plantilla única (depende del flujo de cada organización). ¿AFRUS ofrece una plantilla recomendada de tarjeta o certificado?
5. **Devolver stock tras un reembolso:** ¿hay alguna forma? Hoy es manual.
6. **Etiquetas EN/PT restantes:** faltan del en.json/pt.json los textos de ayuda, mensajes y campos que no están en la tabla del archivo de hechos (Seleccionar widgets, Subir foto, Nombre, Descripción, Código, Vence, Usos totales, Ocasión y sus opciones, estados de entrega, etc.). En la guía EN algunos textos de ayuda van traducidos entre comillas: confirmar contra el en.json.
7. **Pasos para crear el flujo:** la guía describe crear el flujo y activarlo con palabras genéricas ("crea uno nuevo", "activa el flujo"); confirmar las etiquetas exactas en `flujos-de-trabajo.md` si se quiere más detalle.

## Defectos encontrados

El archivo de hechos no marca ningún "(defecto conocido)" en Incentivos. Observaciones de producto, para que las evalúe tecnología:

1. **El stock no se devuelve tras un reembolso o contracargo** y no hay acción para devolverlo; la organización lo resuelve a mano.
2. **Mensaje de cupón genérico:** el donante ve "Cupón inválido o vencido" sin saber si venció, se agotó, ya lo usó o no aplica a esa frecuencia.
3. **Sobreventa:** si el stock se agota mientras alguien paga, el obsequio se asigna igual y queda una alerta para resolver a mano.
4. **Datos de envío borrados en pagos tardíos:** si el pago se confirma después del plazo de privacidad, el obsequio queda "Con problema" y hay que resolverlo a mano.

¿Quieres que los abra como tickets con `/ticket`? Solo con tu OK.
