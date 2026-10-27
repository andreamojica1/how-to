# Transacciones — tutoriales web (afrus.ai/howto)

Un bloque por tutorial, listo para pegar. Orden: español, inglés, portugués.

## Español

```text
=== TUTORIAL ===
Idioma: es
Título: Qué son las Transacciones en AFRUS
Slug: que-son-las-transacciones
Categoría: Transacciones
Resumen: Aprende qué es el módulo Transacciones: la lista de todos los pagos de tu organización, únicos y recurrentes.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-sirven-las-transacciones, como-crear-un-agradecimiento-con-ia-desde-transacciones, como-reembolsar-una-donacion, como-marcar-como-fraude-una-transaccion, como-descargar-un-grupo-de-transacciones, como-filtrar-un-grupo-de-transacciones, como-saber-la-razon-del-fallo-de-una-transaccion, diferencia-entre-unica-y-cargo
--- CUERPO (HTML) ---
<p><strong>Transacciones es la lista de todos los pagos de tu organización.</strong> Aquí ves las donaciones únicas y cada cobro de las donaciones recurrentes, con su estado, monto, pasarela, método de pago, campaña y widget de origen.</p>
<p>Las suscripciones en sí no están aquí: se ven en <strong>Suscripciones</strong>. En Transacciones aparece cada pago que una suscripción genera.</p>
<h2>Dónde lo encuentras</h2>
<p>En el menú lateral, <strong>Transacciones</strong>. Por defecto la lista muestra el mes en curso (<strong>MTD</strong>) y se actualiza al abrir la pantalla o cambiar un filtro.</p>
<h2>Estados más comunes</h2>
<ul>
<li><strong>Exitoso:</strong> el pago se completó.</li>
<li><strong>Pendiente:</strong> el pago aún no se confirma.</li>
<li><strong>Pendiente de confirmación:</strong> tu equipo debe confirmarlo o rechazarlo.</li>
<li><strong>Fallido</strong> / <strong>Rechazada:</strong> el pago no se completó.</li>
<li><strong>Reembolsado:</strong> el pago se devolvió al donante.</li>
</ul>
<p>Las transacciones marcadas como fraude no aparecen aquí: se ven en <strong>Follow up &gt; Radar - monitor de fraude</strong>.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Para qué sirven las Transacciones
Slug: para-que-sirven-las-transacciones
Categoría: Transacciones
Resumen: Aprende para qué sirve el módulo Transacciones: buscar pagos, reembolsar, limpiar fraude, exportar y agradecer con IA.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-las-transacciones, como-reembolsar-una-donacion, como-descargar-un-grupo-de-transacciones, como-filtrar-un-grupo-de-transacciones
--- CUERPO (HTML) ---
<p>El módulo Transacciones te permite:</p>
<ul>
<li><strong>Encontrar cualquier pago.</strong> Busca por nombre, documento, correo, teléfono o ID y abre su detalle, incluida la respuesta de la pasarela cuando un pago falla.</li>
<li><strong>Reembolsar donaciones.</strong> Devuelve donaciones exitosas en las pasarelas que lo permiten.</li>
<li><strong>Limpiar el fraude.</strong> Marca pagos fraudulentos para sacarlos de la lista y de tu base.</li>
<li><strong>Exportar a Excel.</strong> Descarga las transacciones que elijas o todas las que coinciden con tus filtros.</li>
<li><strong>Agradecer con IA.</strong> Envía al donante un correo de agradecimiento redactado con IA.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo crear un agradecimiento con IA desde Transacciones
Slug: como-crear-un-agradecimiento-con-ia-desde-transacciones
Categoría: Transacciones
Resumen: Aprende a enviar a un donante un correo de agradecimiento redactado con IA desde una transacción exitosa.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-las-transacciones, como-reembolsar-una-donacion, como-saber-la-razon-del-fallo-de-una-transaccion
--- CUERPO (HTML) ---
<h2>Antes de empezar</h2>
<ul>
<li>La transacción debe estar en estado <strong>Exitoso</strong>.</li>
<li>Tu organización debe tener activo el <strong>Business profile</strong>; si no, la opción no aparece.</li>
<li>Necesitas al menos un usuario con firma en <strong>AI &gt; Firmas de usuarios</strong>. Solo esos usuarios aparecen como remitentes.</li>
</ul>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre el agradecimiento.</strong> En <strong>Transacciones</strong>, abre el menú de tres puntos de la fila y elige <strong>Agradecimiento personalizado IA</strong> (o usa el botón con destellos junto al estado <strong>Exitoso</strong>).</li>
<li><strong>Elige el remitente.</strong> Selecciona un usuario y pulsa "Continuar". El correo sale desde la dirección de su firma.</li>
<li><strong>Espera el borrador.</strong> Verás <em>AI preparando tu mensaje</em>.</li>
<li><strong>Revisa y edita.</strong> Ajusta <strong>Asunto</strong> (máx. 128 caracteres) y <strong>Cuerpo del correo</strong> (máx. 1600). "Regenerar" pide otra versión.</li>
<li><strong>Envía.</strong> Pulsa "Enviar mensaje".</li>
</ol>
<p>Verás <em>"El agradecimiento se ha enviado correctamente"</em>. El correo llega al email de la persona de esa transacción.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Puedo usar Merge tags?</strong> Por ahora no: las variables se envían como texto literal. Escribe el nombre y los datos directamente.</p>
<p><strong>¿Se puede deshacer?</strong> No. Una vez enviado, el correo ya está en la bandeja del donante.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo reembolsar una donación
Slug: como-reembolsar-una-donacion
Categoría: Transacciones
Resumen: Aprende a reembolsar una donación exitosa desde Transacciones y qué pasa después.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-las-transacciones, como-crear-un-agradecimiento-con-ia-desde-transacciones, como-marcar-como-fraude-una-transaccion, como-saber-la-razon-del-fallo-de-una-transaccion
--- CUERPO (HTML) ---
<h2>Antes de empezar</h2>
<ul>
<li>La transacción debe estar en estado <strong>Exitoso</strong>.</li>
<li>Su pasarela debe permitir reembolsos desde AFRUS; si no, la opción <strong>Reembolsar</strong> no aparece.</li>
<li>Tu usuario necesita permiso para operaciones bancarias con transacciones. Si el reembolso falla por eso, pide a un administrador que lo haga.</li>
</ul>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre el menú de la fila.</strong> En <strong>Transacciones</strong>, abre el menú de tres puntos y elige <strong>Reembolsar</strong>.</li>
<li><strong>Confirma.</strong> En <strong>Reembolsar Cargo</strong>, pulsa "Confirmar".</li>
</ol>
<p>Verás <em>"Reembolsado con éxito."</em> y la transacción pasará a <strong>Reembolsado</strong>. Si tenía un certificado de donación vigente, se anula. Si la pasarela lo rechaza, verás <em>"Error al reembolsar el cargo."</em> y nada cambia.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Puedo reembolsar solo una parte?</strong> No. Siempre se reembolsa el monto completo.</p>
<p><strong>¿Se puede deshacer?</strong> No. El dinero se devuelve en la pasarela y no hay opción para revertirlo.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo marcar como fraude una transacción
Slug: como-marcar-como-fraude-una-transaccion
Categoría: Transacciones
Resumen: Aprende a marcar transacciones como fraude, qué pasa con ellas y con los donantes asociados.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-las-transacciones, como-reembolsar-una-donacion, como-filtrar-un-grupo-de-transacciones
--- CUERPO (HTML) ---
<p><strong>Importante:</strong> al marcar una transacción como fraude, las personas asociadas se eliminan de tu base, aunque tengan otras donaciones legítimas. Revisa bien antes de confirmar.</p>
<h2>Paso a paso</h2>
<ol>
<li><strong>Selecciona las transacciones.</strong> En <strong>Transacciones</strong>, marca la casilla de una o varias filas de la página.</li>
<li><strong>Elige la acción.</strong> Pulsa "Acciones transacciones" y elige <strong>Marcar como Fraude</strong>.</li>
<li><strong>Confirma.</strong> Lee el aviso y pulsa "Confirmar".</li>
</ol>
<p>Las transacciones pasan a <strong>Fraude</strong>, desaparecen de la lista y aparecen en <strong>Follow up &gt; Radar - monitor de fraude</strong>.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Devuelve el dinero o cancela la suscripción?</strong> No. Solo cambia el estado en AFRUS. Si necesitas devolver el pago, reembólsalo antes.</p>
<p><strong>¿Puedo marcar toda la base de una vez?</strong> No. Solo se marcan las filas seleccionadas en la página actual.</p>
<p><strong>¿Se puede deshacer?</strong> No. No hay opción para revertirlo.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo descargar un grupo de transacciones
Slug: como-descargar-un-grupo-de-transacciones
Categoría: Transacciones
Resumen: Aprende a exportar a Excel las transacciones que elijas o todas las que coinciden con tus filtros.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-las-transacciones, como-filtrar-un-grupo-de-transacciones, diferencia-entre-unica-y-cargo
--- CUERPO (HTML) ---
<h2>Paso a paso</h2>
<ol>
<li><strong>Filtra lo que necesitas.</strong> Ajusta fechas, búsqueda y filtros.</li>
<li><strong>Selecciona.</strong> Marca las filas que quieres, o marca la casilla del encabezado y pulsa "Seleccionar las N transacciones de la base." para exportar todo lo filtrado.</li>
<li><strong>Exporta.</strong> Pulsa "Acciones transacciones" y elige <strong>Exportar</strong>.</li>
<li><strong>Confirma.</strong> En <strong>Descargas</strong>, elige <strong>Tipo de archivo</strong> y pulsa "Confirmar". La exportación puede tardar unos minutos.</li>
<li><strong>Descarga el archivo.</strong> Entra a <strong>Data &gt; Descargas</strong>.</li>
</ol>
<h2>Preguntas frecuentes</h2>
<p><strong>¿En qué formato llega?</strong> Siempre en Excel (.xlsx), aunque elijas CSV.</p>
<p><strong>¿Se aplica el filtro CYC?</strong> No al exportar toda la base. Si lo necesitas, filtra con CYC en pantalla y marca las filas una por una.</p>
<p><strong>¿Cuánto tiempo está disponible el archivo?</strong> Hasta 7 días después de generado.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo filtrar un grupo de transacciones
Slug: como-filtrar-un-grupo-de-transacciones
Categoría: Transacciones
Resumen: Aprende a filtrar transacciones por fecha, tipo, estado, pasarela, monto, campaña, widget y más.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-las-transacciones, como-descargar-un-grupo-de-transacciones, diferencia-entre-unica-y-cargo
--- CUERPO (HTML) ---
<h2>Paso a paso</h2>
<ol>
<li><strong>Elige el periodo.</strong> En la barra de fechas, pulsa <strong>1W</strong>, <strong>4W</strong>, <strong>1Y</strong>, <strong>MTD</strong>, <strong>QTD</strong>, <strong>YTD</strong>, <strong>ALL</strong> o <strong>PERSONALIZADO</strong>. Se aplica sobre la <strong>Fecha inicial</strong>, en tu zona horaria.</li>
<li><strong>Busca (opcional).</strong> Usa <strong>Buscar por</strong> con nombre, documento, correo, teléfono o ID de transacción.</li>
<li><strong>Aplica filtros.</strong> En la fila con el icono de embudo: <strong>Tipo</strong>, <strong>Tipo de origen</strong>, <strong>Estados</strong>, <strong>Pasarela de pago</strong>, <strong>Metodo de pago</strong>, <strong>Valor</strong>, <strong>Campaña</strong>, <strong>Widgets</strong> y <strong>CYC</strong>.</li>
<li><strong>Limpia cuando quieras.</strong> "Reset" quita todos los filtros.</li>
</ol>
<p>La tabla y los totales se recalculan, y puedes compartir el enlace de la página con los mismos filtros.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Puedo ver únicas y cargos a la vez?</strong> Sí, dejando <strong>Tipo</strong> sin seleccionar. Si marcas ambos, solo se muestran las únicas.</p>
<p><strong>¿En qué moneda compara Valor?</strong> En la moneda de tu organización, con el monto convertido.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo saber la razón del fallo de una transacción
Slug: como-saber-la-razon-del-fallo-de-una-transaccion
Categoría: Transacciones
Resumen: Aprende a ver por qué falló un pago: la explicación con IA y la respuesta original de la pasarela.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-las-transacciones, como-reembolsar-una-donacion, como-filtrar-un-grupo-de-transacciones
--- CUERPO (HTML) ---
<p>La lista no tiene columna de motivo: la razón se ve en el detalle de la transacción.</p>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre el detalle.</strong> En una transacción <strong>Fallido</strong> o <strong>Rechazada</strong>, elige <strong>Detalles</strong> en el menú de tres puntos o haz clic en el <strong>ID</strong>.</li>
<li><strong>Lee la explicación con IA.</strong> La tarjeta <strong>Resultado de suscripción</strong> explica en lenguaje claro lo que respondió la pasarela. Requiere tener activo el <strong>Business profile</strong>.</li>
<li><strong>Consulta la respuesta original.</strong> En <strong>Respuesta</strong> &gt; <strong>Respuesta Gateway</strong> está el código o mensaje de rechazo.</li>
</ol>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Qué significa la etiqueta Cacheado?</strong> Que el análisis se generó la primera vez que abriste el detalle y ahora se reutiliza.</p>
<p><strong>¿Por qué no veo análisis?</strong> Si el pago no tiene respuesta de la pasarela, no hay análisis.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Diferencia entre Única y Cargo en Transacciones
Slug: diferencia-entre-unica-y-cargo
Categoría: Transacciones
Resumen: Aprende qué significan Única y Cargo en Transacciones y dónde ver las suscripciones.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-las-transacciones, para-que-sirven-las-transacciones, como-filtrar-un-grupo-de-transacciones
--- CUERPO (HTML) ---
<p>La columna <strong>Tipo de frecuencia</strong> y el filtro <strong>Tipo</strong> distinguen dos clases de pago:</p>
<ul>
<li><strong>Única</strong> (filtro <strong>Unicas</strong>): una donación de un solo pago. No viene de una suscripción.</li>
<li><strong>Cargo</strong> (filtro <strong>Cargos</strong>): un cobro de una donación recurrente. Cada mes o ciclo de la suscripción genera un cargo nuevo.</li>
</ul>
<p>La suscripción en sí (el registro <strong>Recurrente</strong>) no aparece en esta lista: se ve en <strong>Suscripciones</strong>.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Cómo veo solo los cobros recurrentes?</strong> En el filtro <strong>Tipo</strong>, elige solo <strong>Cargos</strong>.</p>
=== FIN ===
```

## English

```text
=== TUTORIAL ===
Idioma: en
Título: What Transactions are in AFRUS
Slug: what-are-transactions
Categoría: Transacciones
Resumen: Learn what the Transactions module is: the list of every payment your organization receives, one-time and recurring.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-transactions-for, how-to-create-an-ai-thank-you-from-transactions, how-to-refund-a-donation, how-to-mark-a-transaction-as-fraud, how-to-download-a-group-of-transactions, how-to-filter-a-group-of-transactions, how-to-find-out-why-a-transaction-failed, difference-between-one-time-and-charge
--- CUERPO (HTML) ---
<p><em>Labels are shown as they appear in the Spanish version of the console.</em></p>
<p><strong>Transactions is the list of every payment your organization receives.</strong> Here you see one-time donations and each charge of recurring donations, with their status, amount, gateway, payment method, campaign and source widget.</p>
<p>Subscriptions themselves are not here: you see them in <strong>Suscripciones</strong> (Subscriptions). Transactions shows each payment a subscription generates.</p>
<h2>Where to find it</h2>
<p>In the side menu, <strong>Transacciones</strong>. By default the list shows the current month (<strong>MTD</strong>) and updates when you open the screen or change a filter.</p>
<h2>Most common statuses</h2>
<ul>
<li><strong>Exitoso</strong> (Successful): the payment went through.</li>
<li><strong>Pendiente</strong> (Pending): the payment is not confirmed yet.</li>
<li><strong>Pendiente de confirmación</strong> (Awaiting confirmation): your team must confirm or reject it.</li>
<li><strong>Fallido</strong> / <strong>Rechazada</strong> (Failed / Rejected): the payment did not go through.</li>
<li><strong>Reembolsado</strong> (Refunded): the payment was returned to the donor.</li>
</ul>
<p>Transactions marked as fraud don't appear here: they are in <strong>Follow up &gt; Radar - monitor de fraude</strong>.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: What Transactions are for
Slug: what-are-transactions-for
Categoría: Transacciones
Resumen: Learn what the Transactions module is for: finding payments, refunding, cleaning up fraud, exporting and AI thank-yous.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-transactions, how-to-refund-a-donation, how-to-download-a-group-of-transactions, how-to-filter-a-group-of-transactions
--- CUERPO (HTML) ---
<p><em>Labels are shown as they appear in the Spanish version of the console.</em></p>
<p>The Transactions module lets you:</p>
<ul>
<li><strong>Find any payment.</strong> Search by name, ID document, email, phone or ID and open its details, including the gateway's response when a payment fails.</li>
<li><strong>Refund donations.</strong> Return successful donations on gateways that allow it.</li>
<li><strong>Clean up fraud.</strong> Mark fraudulent payments to remove them from the list and your database.</li>
<li><strong>Export to Excel.</strong> Download the transactions you choose or all those matching your filters.</li>
<li><strong>Say thank you with AI.</strong> Send the donor a thank-you email written with AI.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to create an AI thank-you from Transactions
Slug: how-to-create-an-ai-thank-you-from-transactions
Categoría: Transacciones
Resumen: Learn how to send a donor a thank-you email written with AI from a successful transaction.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-transactions, how-to-refund-a-donation, how-to-find-out-why-a-transaction-failed
--- CUERPO (HTML) ---
<p><em>Labels are shown as they appear in the Spanish version of the console.</em></p>
<h2>Before you start</h2>
<ul>
<li>The transaction must be <strong>Exitoso</strong> (Successful).</li>
<li>Your organization needs an active <strong>Business profile</strong>; otherwise the option doesn't appear.</li>
<li>You need at least one user with a signature in <strong>AI &gt; Firmas de usuarios</strong> (User signatures). Only those users appear as senders.</li>
</ul>
<h2>Step by step</h2>
<ol>
<li><strong>Open the thank-you.</strong> In <strong>Transacciones</strong>, open the row's three-dot menu and choose <strong>Agradecimiento personalizado IA</strong> (AI personalized thank-you), or use the sparkle button next to <strong>Exitoso</strong>.</li>
<li><strong>Choose the sender.</strong> Select a user and click "Continuar" (Continue). The email is sent from their signature address.</li>
<li><strong>Wait for the draft.</strong> You will see <em>AI preparando tu mensaje</em> (AI preparing your message).</li>
<li><strong>Review and edit.</strong> Adjust <strong>Asunto</strong> (Subject, max. 128 characters) and <strong>Cuerpo del correo</strong> (Body, max. 1600). "Regenerar" (Regenerate) asks for another version.</li>
<li><strong>Send.</strong> Click "Enviar mensaje" (Send message).</li>
</ol>
<p>You will see <em>"El agradecimiento se ha enviado correctamente"</em> (The thank-you was sent successfully). The email goes to that transaction's person.</p>
<h2>Frequently asked questions</h2>
<p><strong>Can I use Merge tags?</strong> Not for now: variables are sent as literal text. Type the name and details directly.</p>
<p><strong>Can it be undone?</strong> No. Once sent, the email is in the donor's inbox.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to refund a donation
Slug: how-to-refund-a-donation
Categoría: Transacciones
Resumen: Learn how to refund a successful donation from Transactions and what happens next.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-transactions, how-to-create-an-ai-thank-you-from-transactions, how-to-mark-a-transaction-as-fraud, how-to-find-out-why-a-transaction-failed
--- CUERPO (HTML) ---
<p><em>Labels are shown as they appear in the Spanish version of the console.</em></p>
<h2>Before you start</h2>
<ul>
<li>The transaction must be <strong>Exitoso</strong> (Successful).</li>
<li>Its gateway must allow refunds from AFRUS; otherwise the <strong>Reembolsar</strong> (Refund) option doesn't appear.</li>
<li>Your user needs permission for banking operations on transactions. If the refund fails for that reason, ask an administrator to do it.</li>
</ul>
<h2>Step by step</h2>
<ol>
<li><strong>Open the row menu.</strong> In <strong>Transacciones</strong>, open the three-dot menu and choose <strong>Reembolsar</strong>.</li>
<li><strong>Confirm.</strong> In <strong>Reembolsar Cargo</strong> (Refund charge), click "Confirmar" (Confirm).</li>
</ol>
<p>You will see <em>"Reembolsado con éxito."</em> (Refunded successfully) and the transaction changes to <strong>Reembolsado</strong> (Refunded). If it had a valid donation certificate, it is voided. If the gateway rejects it, you will see <em>"Error al reembolsar el cargo."</em> and nothing changes.</p>
<h2>Frequently asked questions</h2>
<p><strong>Can I refund only part of it?</strong> No. The full amount is always refunded.</p>
<p><strong>Can it be undone?</strong> No. The money is returned through the gateway and there is no option to reverse it.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to mark a transaction as fraud
Slug: how-to-mark-a-transaction-as-fraud
Categoría: Transacciones
Resumen: Learn how to mark transactions as fraud and what happens to them and to the linked donors.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-transactions, how-to-refund-a-donation, how-to-filter-a-group-of-transactions
--- CUERPO (HTML) ---
<p><em>Labels are shown as they appear in the Spanish version of the console.</em></p>
<p><strong>Important:</strong> when you mark a transaction as fraud, the linked people are deleted from your database, even if they have other legitimate donations. Check carefully before confirming.</p>
<h2>Step by step</h2>
<ol>
<li><strong>Select the transactions.</strong> In <strong>Transacciones</strong>, tick one or more rows on the page.</li>
<li><strong>Choose the action.</strong> Click "Acciones transacciones" (Transaction actions) and choose <strong>Marcar como Fraude</strong> (Mark as fraud).</li>
<li><strong>Confirm.</strong> Read the warning and click "Confirmar" (Confirm).</li>
</ol>
<p>The transactions change to <strong>Fraude</strong>, disappear from the list and appear in <strong>Follow up &gt; Radar - monitor de fraude</strong>.</p>
<h2>Frequently asked questions</h2>
<p><strong>Does it return the money or cancel the subscription?</strong> No. It only changes the status in AFRUS. If you need to return the payment, refund it first.</p>
<p><strong>Can I mark the whole database at once?</strong> No. Only the rows selected on the current page are marked.</p>
<p><strong>Can it be undone?</strong> No. There is no option to reverse it.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to download a group of transactions
Slug: how-to-download-a-group-of-transactions
Categoría: Transacciones
Resumen: Learn how to export to Excel the transactions you choose or all those matching your filters.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-transactions, how-to-filter-a-group-of-transactions, difference-between-one-time-and-charge
--- CUERPO (HTML) ---
<p><em>Labels are shown as they appear in the Spanish version of the console.</em></p>
<h2>Step by step</h2>
<ol>
<li><strong>Filter what you need.</strong> Set dates, search and filters.</li>
<li><strong>Select.</strong> Tick the rows you want, or tick the header box and click "Seleccionar las N transacciones de la base." (Select all N transactions) to export everything filtered.</li>
<li><strong>Export.</strong> Click "Acciones transacciones" and choose <strong>Exportar</strong> (Export).</li>
<li><strong>Confirm.</strong> In <strong>Descargas</strong> (Downloads), choose <strong>Tipo de archivo</strong> (File type) and click "Confirmar". The export may take a few minutes.</li>
<li><strong>Download the file.</strong> Go to <strong>Data &gt; Descargas</strong>.</li>
</ol>
<h2>Frequently asked questions</h2>
<p><strong>What format is it?</strong> Always Excel (.xlsx), even if you choose CSV.</p>
<p><strong>Is the CYC filter applied?</strong> Not when exporting the whole database. If you need it, filter by CYC on screen and tick the rows one by one.</p>
<p><strong>How long is the file available?</strong> Up to 7 days after it is generated.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to filter a group of transactions
Slug: how-to-filter-a-group-of-transactions
Categoría: Transacciones
Resumen: Learn how to filter transactions by date, type, status, gateway, amount, campaign, widget and more.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-transactions, how-to-download-a-group-of-transactions, difference-between-one-time-and-charge
--- CUERPO (HTML) ---
<p><em>Labels are shown as they appear in the Spanish version of the console.</em></p>
<h2>Step by step</h2>
<ol>
<li><strong>Choose the period.</strong> In the date bar, click <strong>1W</strong>, <strong>4W</strong>, <strong>1Y</strong>, <strong>MTD</strong>, <strong>QTD</strong>, <strong>YTD</strong>, <strong>ALL</strong> or <strong>PERSONALIZADO</strong> (custom). It applies to the <strong>Fecha inicial</strong> (Start date), in your time zone.</li>
<li><strong>Search (optional).</strong> Use <strong>Buscar por</strong> (Search by) with name, ID document, email, phone or transaction ID.</li>
<li><strong>Apply filters.</strong> In the funnel row: <strong>Tipo</strong> (Type), <strong>Tipo de origen</strong> (Source type), <strong>Estados</strong> (Statuses), <strong>Pasarela de pago</strong> (Gateway), <strong>Metodo de pago</strong> (Payment method), <strong>Valor</strong> (Amount), <strong>Campaña</strong> (Campaign), <strong>Widgets</strong> and <strong>CYC</strong>.</li>
<li><strong>Clear whenever you want.</strong> "Reset" removes all filters.</li>
</ol>
<p>The table and totals are recalculated, and you can share the page link with the same filters.</p>
<h2>Frequently asked questions</h2>
<p><strong>Can I see one-time donations and charges together?</strong> Yes, by leaving <strong>Tipo</strong> empty. If you tick both, only one-time donations are shown.</p>
<p><strong>Which currency does Valor compare?</strong> Your organization's currency, using the converted amount.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to find out why a transaction failed
Slug: how-to-find-out-why-a-transaction-failed
Categoría: Transacciones
Resumen: Learn how to see why a payment failed: the AI explanation and the gateway's original response.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-transactions, how-to-refund-a-donation, how-to-filter-a-group-of-transactions
--- CUERPO (HTML) ---
<p><em>Labels are shown as they appear in the Spanish version of the console.</em></p>
<p>The list has no reason column: the reason is in the transaction details.</p>
<h2>Step by step</h2>
<ol>
<li><strong>Open the details.</strong> On a <strong>Fallido</strong> (Failed) or <strong>Rechazada</strong> (Rejected) transaction, choose <strong>Detalles</strong> (Details) in the three-dot menu or click the <strong>ID</strong>.</li>
<li><strong>Read the AI explanation.</strong> The <strong>Resultado de suscripción</strong> card explains in plain language what the gateway answered. It requires an active <strong>Business profile</strong>.</li>
<li><strong>Check the original response.</strong> Under <strong>Respuesta</strong> &gt; <strong>Respuesta Gateway</strong> (Gateway response) is the decline code or message.</li>
</ol>
<h2>Frequently asked questions</h2>
<p><strong>What does the Cacheado label mean?</strong> The analysis was generated the first time you opened the details and is now reused.</p>
<p><strong>Why don't I see an analysis?</strong> If the payment has no gateway response, there is no analysis.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: Difference between One-time and Charge in Transactions
Slug: difference-between-one-time-and-charge
Categoría: Transacciones
Resumen: Learn what Única (one-time) and Cargo (charge) mean in Transactions and where to see subscriptions.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-transactions, what-are-transactions-for, how-to-filter-a-group-of-transactions
--- CUERPO (HTML) ---
<p><em>Labels are shown as they appear in the Spanish version of the console.</em></p>
<p>The <strong>Tipo de frecuencia</strong> (Frequency type) column and the <strong>Tipo</strong> filter distinguish two kinds of payment:</p>
<ul>
<li><strong>Única</strong> (One-time; filter <strong>Unicas</strong>): a single-payment donation. It does not come from a subscription.</li>
<li><strong>Cargo</strong> (Charge; filter <strong>Cargos</strong>): a charge of a recurring donation. Each month or cycle of the subscription creates a new charge.</li>
</ul>
<p>The subscription itself (the <strong>Recurrente</strong> record) does not appear in this list: you see it in <strong>Suscripciones</strong>.</p>
<h2>Frequently asked questions</h2>
<p><strong>How do I see only recurring charges?</strong> In the <strong>Tipo</strong> filter, choose only <strong>Cargos</strong>.</p>
=== FIN ===
```

## Português

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: O que são as Transações na AFRUS
Slug: o-que-sao-as-transacoes
Categoría: Transacciones
Resumen: Aprenda o que é o módulo Transações: a lista de todos os pagamentos da sua organização, únicos e recorrentes.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-servem-as-transacoes, como-criar-um-agradecimento-com-ia-em-transacoes, como-reembolsar-uma-doacao, como-marcar-uma-transacao-como-fraude, como-baixar-um-grupo-de-transacoes, como-filtrar-um-grupo-de-transacoes, como-saber-o-motivo-da-falha-de-uma-transacao, diferenca-entre-unica-e-cargo
--- CUERPO (HTML) ---
<p><em>Os nomes de tela aparecem como na versão em espanhol do console.</em></p>
<p><strong>Transações é a lista de todos os pagamentos da sua organização.</strong> Aqui você vê as doações únicas e cada cobrança das doações recorrentes, com status, valor, gateway, método de pagamento, campanha e widget de origem.</p>
<p>As assinaturas em si não ficam aqui: elas aparecem em <strong>Suscripciones</strong> (Assinaturas). Em Transações aparece cada pagamento que uma assinatura gera.</p>
<h2>Onde encontrar</h2>
<p>No menu lateral, <strong>Transacciones</strong>. Por padrão a lista mostra o mês atual (<strong>MTD</strong>) e é atualizada ao abrir a tela ou mudar um filtro.</p>
<h2>Status mais comuns</h2>
<ul>
<li><strong>Exitoso</strong> (Aprovada): o pagamento foi concluído.</li>
<li><strong>Pendiente</strong> (Pendente): o pagamento ainda não foi confirmado.</li>
<li><strong>Pendiente de confirmación</strong> (Aguardando confirmação): sua equipe precisa confirmar ou recusar.</li>
<li><strong>Fallido</strong> / <strong>Rechazada</strong> (Falhou / Recusada): o pagamento não foi concluído.</li>
<li><strong>Reembolsado</strong>: o pagamento foi devolvido ao doador.</li>
</ul>
<p>As transações marcadas como fraude não aparecem aqui: elas ficam em <strong>Follow up &gt; Radar - monitor de fraude</strong>.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Para que servem as Transações
Slug: para-que-servem-as-transacoes
Categoría: Transacciones
Resumen: Aprenda para que serve o módulo Transações: buscar pagamentos, reembolsar, limpar fraudes, exportar e agradecer com IA.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-as-transacoes, como-reembolsar-uma-doacao, como-baixar-um-grupo-de-transacoes, como-filtrar-um-grupo-de-transacoes
--- CUERPO (HTML) ---
<p><em>Os nomes de tela aparecem como na versão em espanhol do console.</em></p>
<p>O módulo Transações permite:</p>
<ul>
<li><strong>Encontrar qualquer pagamento.</strong> Busque por nome, documento, e-mail, telefone ou ID e abra o detalhe, incluindo a resposta do gateway quando um pagamento falha.</li>
<li><strong>Reembolsar doações.</strong> Devolva doações aprovadas nos gateways que permitem.</li>
<li><strong>Limpar fraudes.</strong> Marque pagamentos fraudulentos para tirá-los da lista e da sua base.</li>
<li><strong>Exportar para Excel.</strong> Baixe as transações que escolher ou todas as que correspondem aos seus filtros.</li>
<li><strong>Agradecer com IA.</strong> Envie ao doador um e-mail de agradecimento escrito com IA.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como criar um agradecimento com IA em Transações
Slug: como-criar-um-agradecimento-com-ia-em-transacoes
Categoría: Transacciones
Resumen: Aprenda a enviar a um doador um e-mail de agradecimento escrito com IA a partir de uma transação aprovada.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-as-transacoes, como-reembolsar-uma-doacao, como-saber-o-motivo-da-falha-de-uma-transacao
--- CUERPO (HTML) ---
<p><em>Os nomes de tela aparecem como na versão em espanhol do console.</em></p>
<h2>Antes de começar</h2>
<ul>
<li>A transação precisa estar com status <strong>Exitoso</strong> (Aprovada).</li>
<li>Sua organização precisa ter o <strong>Business profile</strong> ativo; senão, a opção não aparece.</li>
<li>É preciso ter pelo menos um usuário com assinatura em <strong>AI &gt; Firmas de usuarios</strong> (Assinaturas de usuários). Só esses usuários aparecem como remetentes.</li>
</ul>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra o agradecimento.</strong> Em <strong>Transacciones</strong>, abra o menu de três pontos da linha e escolha <strong>Agradecimiento personalizado IA</strong> (Agradecimento personalizado com IA), ou use o botão de brilho ao lado de <strong>Exitoso</strong>.</li>
<li><strong>Escolha o remetente.</strong> Selecione um usuário e clique em "Continuar". O e-mail sai do endereço da assinatura dele.</li>
<li><strong>Aguarde o rascunho.</strong> Você verá <em>AI preparando tu mensaje</em> (A IA está preparando sua mensagem).</li>
<li><strong>Revise e edite.</strong> Ajuste <strong>Asunto</strong> (Assunto, máx. 128 caracteres) e <strong>Cuerpo del correo</strong> (Corpo, máx. 1600). "Regenerar" pede outra versão.</li>
<li><strong>Envie.</strong> Clique em "Enviar mensaje" (Enviar mensagem).</li>
</ol>
<p>Você verá <em>"El agradecimiento se ha enviado correctamente"</em> (O agradecimento foi enviado com sucesso). O e-mail vai para a pessoa dessa transação.</p>
<h2>Perguntas frequentes</h2>
<p><strong>Posso usar Merge tags?</strong> Por enquanto, não: as variáveis são enviadas como texto literal. Escreva o nome e os dados diretamente.</p>
<p><strong>Dá para desfazer?</strong> Não. Depois de enviado, o e-mail já está na caixa do doador.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como reembolsar uma doação
Slug: como-reembolsar-uma-doacao
Categoría: Transacciones
Resumen: Aprenda a reembolsar uma doação aprovada em Transações e o que acontece depois.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-as-transacoes, como-criar-um-agradecimento-com-ia-em-transacoes, como-marcar-uma-transacao-como-fraude, como-saber-o-motivo-da-falha-de-uma-transacao
--- CUERPO (HTML) ---
<p><em>Os nomes de tela aparecem como na versão em espanhol do console.</em></p>
<h2>Antes de começar</h2>
<ul>
<li>A transação precisa estar com status <strong>Exitoso</strong> (Aprovada).</li>
<li>O gateway dela precisa permitir reembolsos pela AFRUS; senão, a opção <strong>Reembolsar</strong> não aparece.</li>
<li>Seu usuário precisa de permissão para operações bancárias com transações. Se o reembolso falhar por isso, peça a um administrador.</li>
</ul>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra o menu da linha.</strong> Em <strong>Transacciones</strong>, abra o menu de três pontos e escolha <strong>Reembolsar</strong>.</li>
<li><strong>Confirme.</strong> Em <strong>Reembolsar Cargo</strong> (Reembolsar cobrança), clique em "Confirmar".</li>
</ol>
<p>Você verá <em>"Reembolsado con éxito."</em> (Reembolsado com sucesso) e a transação passará para <strong>Reembolsado</strong>. Se havia um certificado de doação válido, ele é anulado. Se o gateway recusar, você verá <em>"Error al reembolsar el cargo."</em> e nada muda.</p>
<h2>Perguntas frequentes</h2>
<p><strong>Posso reembolsar só uma parte?</strong> Não. O valor total é sempre reembolsado.</p>
<p><strong>Dá para desfazer?</strong> Não. O dinheiro é devolvido pelo gateway e não há opção para reverter.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como marcar uma transação como fraude
Slug: como-marcar-uma-transacao-como-fraude
Categoría: Transacciones
Resumen: Aprenda a marcar transações como fraude e o que acontece com elas e com os doadores vinculados.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-as-transacoes, como-reembolsar-uma-doacao, como-filtrar-um-grupo-de-transacoes
--- CUERPO (HTML) ---
<p><em>Os nomes de tela aparecem como na versão em espanhol do console.</em></p>
<p><strong>Importante:</strong> ao marcar uma transação como fraude, as pessoas vinculadas são excluídas da sua base, mesmo que tenham outras doações legítimas. Revise bem antes de confirmar.</p>
<h2>Passo a passo</h2>
<ol>
<li><strong>Selecione as transações.</strong> Em <strong>Transacciones</strong>, marque uma ou mais linhas da página.</li>
<li><strong>Escolha a ação.</strong> Clique em "Acciones transacciones" (Ações de transações) e escolha <strong>Marcar como Fraude</strong>.</li>
<li><strong>Confirme.</strong> Leia o aviso e clique em "Confirmar".</li>
</ol>
<p>As transações passam para <strong>Fraude</strong>, somem da lista e aparecem em <strong>Follow up &gt; Radar - monitor de fraude</strong>.</p>
<h2>Perguntas frequentes</h2>
<p><strong>Devolve o dinheiro ou cancela a assinatura?</strong> Não. Só muda o status na AFRUS. Se precisar devolver o pagamento, reembolse antes.</p>
<p><strong>Posso marcar a base inteira de uma vez?</strong> Não. Só as linhas selecionadas na página atual são marcadas.</p>
<p><strong>Dá para desfazer?</strong> Não. Não há opção para reverter.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como baixar um grupo de transações
Slug: como-baixar-um-grupo-de-transacoes
Categoría: Transacciones
Resumen: Aprenda a exportar para Excel as transações que escolher ou todas as que correspondem aos seus filtros.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-as-transacoes, como-filtrar-um-grupo-de-transacoes, diferenca-entre-unica-e-cargo
--- CUERPO (HTML) ---
<p><em>Os nomes de tela aparecem como na versão em espanhol do console.</em></p>
<h2>Passo a passo</h2>
<ol>
<li><strong>Filtre o que precisa.</strong> Ajuste datas, busca e filtros.</li>
<li><strong>Selecione.</strong> Marque as linhas que quer, ou marque a caixa do cabeçalho e clique em "Seleccionar las N transacciones de la base." (Selecionar as N transações da base) para exportar tudo o que foi filtrado.</li>
<li><strong>Exporte.</strong> Clique em "Acciones transacciones" e escolha <strong>Exportar</strong>.</li>
<li><strong>Confirme.</strong> Em <strong>Descargas</strong> (Downloads), escolha <strong>Tipo de archivo</strong> (Tipo de arquivo) e clique em "Confirmar". A exportação pode levar alguns minutos.</li>
<li><strong>Baixe o arquivo.</strong> Acesse <strong>Data &gt; Descargas</strong>.</li>
</ol>
<h2>Perguntas frequentes</h2>
<p><strong>Em que formato chega?</strong> Sempre em Excel (.xlsx), mesmo que você escolha CSV.</p>
<p><strong>O filtro CYC é aplicado?</strong> Não ao exportar a base inteira. Se precisar dele, filtre por CYC na tela e marque as linhas uma a uma.</p>
<p><strong>Por quanto tempo o arquivo fica disponível?</strong> Até 7 dias depois de gerado.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como filtrar um grupo de transações
Slug: como-filtrar-um-grupo-de-transacoes
Categoría: Transacciones
Resumen: Aprenda a filtrar transações por data, tipo, status, gateway, valor, campanha, widget e mais.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-as-transacoes, como-baixar-um-grupo-de-transacoes, diferenca-entre-unica-e-cargo
--- CUERPO (HTML) ---
<p><em>Os nomes de tela aparecem como na versão em espanhol do console.</em></p>
<h2>Passo a passo</h2>
<ol>
<li><strong>Escolha o período.</strong> Na barra de datas, clique em <strong>1W</strong>, <strong>4W</strong>, <strong>1Y</strong>, <strong>MTD</strong>, <strong>QTD</strong>, <strong>YTD</strong>, <strong>ALL</strong> ou <strong>PERSONALIZADO</strong>. Ele se aplica à <strong>Fecha inicial</strong> (Data inicial), no seu fuso horário.</li>
<li><strong>Busque (opcional).</strong> Use <strong>Buscar por</strong> com nome, documento, e-mail, telefone ou ID da transação.</li>
<li><strong>Aplique filtros.</strong> Na linha do funil: <strong>Tipo</strong>, <strong>Tipo de origen</strong> (Tipo de origem), <strong>Estados</strong> (Status), <strong>Pasarela de pago</strong> (Gateway), <strong>Metodo de pago</strong> (Método de pagamento), <strong>Valor</strong>, <strong>Campaña</strong> (Campanha), <strong>Widgets</strong> e <strong>CYC</strong>.</li>
<li><strong>Limpe quando quiser.</strong> "Reset" remove todos os filtros.</li>
</ol>
<p>A tabela e os totais são recalculados, e você pode compartilhar o link da página com os mesmos filtros.</p>
<h2>Perguntas frequentes</h2>
<p><strong>Posso ver únicas e cobranças juntas?</strong> Sim, deixando <strong>Tipo</strong> vazio. Se marcar as duas, só as únicas aparecem.</p>
<p><strong>Em que moeda o Valor compara?</strong> Na moeda da sua organização, com o valor convertido.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como saber o motivo da falha de uma transação
Slug: como-saber-o-motivo-da-falha-de-uma-transacao
Categoría: Transacciones
Resumen: Aprenda a ver por que um pagamento falhou: a explicação com IA e a resposta original do gateway.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-as-transacoes, como-reembolsar-uma-doacao, como-filtrar-um-grupo-de-transacoes
--- CUERPO (HTML) ---
<p><em>Os nomes de tela aparecem como na versão em espanhol do console.</em></p>
<p>A lista não tem coluna de motivo: ele aparece no detalhe da transação.</p>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra o detalhe.</strong> Em uma transação <strong>Fallido</strong> (Falhou) ou <strong>Rechazada</strong> (Recusada), escolha <strong>Detalles</strong> (Detalhes) no menu de três pontos ou clique no <strong>ID</strong>.</li>
<li><strong>Leia a explicação da IA.</strong> O cartão <strong>Resultado de suscripción</strong> explica em linguagem simples o que o gateway respondeu. Exige o <strong>Business profile</strong> ativo.</li>
<li><strong>Consulte a resposta original.</strong> Em <strong>Respuesta</strong> &gt; <strong>Respuesta Gateway</strong> (Resposta do gateway) está o código ou a mensagem de recusa.</li>
</ol>
<h2>Perguntas frequentes</h2>
<p><strong>O que significa a etiqueta Cacheado?</strong> Que a análise foi gerada na primeira vez que você abriu o detalhe e agora é reutilizada.</p>
<p><strong>Por que não vejo análise?</strong> Se o pagamento não tem resposta do gateway, não há análise.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Diferença entre Única e Cargo em Transações
Slug: diferenca-entre-unica-e-cargo
Categoría: Transacciones
Resumen: Aprenda o que significam Única e Cargo (cobrança) em Transações e onde ver as assinaturas.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-as-transacoes, para-que-servem-as-transacoes, como-filtrar-um-grupo-de-transacoes
--- CUERPO (HTML) ---
<p><em>Os nomes de tela aparecem como na versão em espanhol do console.</em></p>
<p>A coluna <strong>Tipo de frecuencia</strong> (Tipo de frequência) e o filtro <strong>Tipo</strong> distinguem dois tipos de pagamento:</p>
<ul>
<li><strong>Única</strong> (filtro <strong>Unicas</strong>): uma doação de pagamento único. Não vem de uma assinatura.</li>
<li><strong>Cargo</strong> (Cobrança; filtro <strong>Cargos</strong>): uma cobrança de uma doação recorrente. Cada mês ou ciclo da assinatura gera uma nova cobrança.</li>
</ul>
<p>A assinatura em si (o registro <strong>Recurrente</strong>) não aparece nesta lista: ela fica em <strong>Suscripciones</strong>.</p>
<h2>Perguntas frequentes</h2>
<p><strong>Como vejo só as cobranças recorrentes?</strong> No filtro <strong>Tipo</strong>, escolha só <strong>Cargos</strong>.</p>
=== FIN ===
```
