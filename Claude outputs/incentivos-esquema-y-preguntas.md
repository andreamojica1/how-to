# Incentivos: esquema de la guía y preguntas para tecnología

*Estado: **sin hechos verificados**. Todavía no hay un archivo de hechos del módulo Incentivos, así que esto es solo el esquema y la lista de lo que falta. Los pasos se escriben cuando tecnología confirme las respuestas. Fecha: 2026-10-26.*

## Lo que sí está verificado (desde otros módulos)

- **Menú:** **Fundraising > Incentivos**.
- **Campañas:** el detalle de una campaña tiene una pestaña **Incentivos**.
- **Flujos de trabajo** (**Interacciones > Flujos de trabajo**): hay un disparador **Recompensa asignada**.
  - Texto de la pantalla: *"Inicia el workflow cada vez que se asigna una recompensa pagada: al confirmarse la donación o, en obsequios programados, en la fecha elegida."*
  - Filtros opcionales: **Campaña (opcional)**, **Incentivo (opcional)** y **Para terceros**, con las opciones **Todas las recompensas**, **Solo obsequios para terceros** y **Solo recompensas del propio donante**.
  - Exige tener activado **Permitir reinscripción**, porque cada recompensa es una nueva inscripción.
  - Si el flujo tiene más de un paso, aparece el aviso *"Los workflows de entrega funcionan mejor con un solo paso…"*.
  - En el correo se pueden usar los merge tags de la transacción y de terceros, y adjuntar una plantilla PDF.
  - Hay un estado **Entrega fallida (se reintentará)**: el correo de entrega falló y se vuelve a intentar.
- **Transacciones:**
  - El filtro **Tipo de origen** tiene la opción **Incentivo**.
  - La tabla tiene las columnas **Incentivo** y **Cupón**.

## Esquema propuesto (un tutorial por punto, ES/EN/PT, sin video)

| # | Tutorial | Qué se puede escribir hoy | Qué falta |
|---|---|---|---|
| 1 | Qué son los incentivos | Nada seguro, salvo dónde está en el menú | Definición: qué es un incentivo y qué es una recompensa o un obsequio |
| 2 | Para qué sirven | Nada seguro | Beneficios y casos de uso confirmados |
| 3 | Cómo crear incentivos | Solo la ruta **Fundraising > Incentivos** | Botones, campos, obligatorios, límites, resultado y si se puede editar o eliminar |
| 4 | Para qué son los cupones | Que existe la columna **Cupón** en Transacciones | Qué es un cupón, cómo se crea y cómo lo recibe o usa el donante |
| 5 | Cómo configurar un incentivo para un tercero | Que existen los obsequios para terceros (filtro del flujo) | Dónde se activa, qué datos del tercero se piden, cómo se le entrega |
| 6 | Qué tipos de widgets pueden tener incentivos | Nada | Objetivos de widget compatibles; si va por widget o por campaña (pestaña **Incentivos**) |
| 7 | Cuántos incentivos puedo configurar | Nada | Límite por widget, campaña u organización |
| 8 | Para qué crear un workflow en los incentivos | El disparador **Recompensa asignada**: entrega por correo, con adjunto PDF, al confirmarse la donación o en la fecha programada | Confirmar que el workflow es la forma de entregar el incentivo |
| 9 | Qué incentivos requieren un workflow | Nada | Qué tipos lo exigen y qué pasa si no hay workflow |
| 10 | Para qué ocasiones a terceros puedo donar un incentivo | Que existen los "obsequios programados" con fecha elegida | Lista de ocasiones (cumpleaños, aniversario…) y cómo se elige la fecha |
| 11 | Qué pasa si el incentivo ya no tiene stock | Nada | Si el stock existe, qué ve el donante, si se oculta o bloquea, y si se avisa a la organización |
| 12 | Cómo hacer seguimiento a los incentivos donados | Filtro **Tipo de origen > Incentivo** y columnas **Incentivo** y **Cupón** en Transacciones; estados del workflow de entrega | Si hay un reporte o pantalla propia en **Fundraising > Incentivos** o en la pestaña de la campaña |

## Preguntas para tecnología

1. ¿Qué es exactamente un incentivo en AFRUS? ¿Qué diferencia hay entre incentivo, recompensa y obsequio?
2. Pantalla **Fundraising > Incentivos**: ¿qué columnas, filtros y acciones tiene la lista?
3. Crear un incentivo: ¿qué botones hay, qué campos (y cuáles son obligatorios), qué límites de caracteres y de imagen, qué mensajes aparecen? ¿Se puede editar, desactivar o eliminar?
4. ¿Cómo se vincula un incentivo a una campaña (pestaña **Incentivos**) y a un widget? ¿Qué objetivos de widget lo admiten?
5. ¿Hay un monto mínimo de donación para recibirlo? ¿Aplica a donaciones únicas, recurrentes o a ambas?
6. ¿Cuántos incentivos se pueden configurar por widget, campaña u organización?
7. Cupones: ¿qué son, cómo se crean o cargan, cómo se asignan al donante y qué pasa cuando se acaban?
8. Obsequios para terceros: ¿dónde se activan? ¿Qué datos del tercero pide el formulario? ¿Qué ocasiones existen y cómo se programa la fecha?
9. ¿Qué tipos de incentivo requieren un workflow con **Recompensa asignada**? ¿Qué pasa si no existe ninguno: se entrega de otra forma o no se entrega?
10. Stock: ¿existe? ¿Qué ve el donante cuando se agota? ¿Se avisa a la organización?
11. Seguimiento: ¿hay alguna pantalla o reporte propio, además del filtro de Transacciones y el estado del workflow de entrega? ¿Se puede exportar?
12. ¿Hace falta tener contratado algo para ver **Fundraising > Incentivos**? ¿Qué roles pueden crear incentivos?
13. ¿Qué etiquetas usa la consola en inglés y en portugués?

## Siguiente paso

Cuando tecnología agregue el archivo de hechos del módulo (o responda estas preguntas), escribo los 12 tutoriales y la guía en ES, EN y PT, con el mismo formato que los demás, y los copio a tu repositorio **how-to**.
