# Tickets — tutoriales web (afrus.ai/howto)

Un bloque por tutorial, listo para pegar. Orden: español, inglés, portugués.

## Español

```text
=== TUTORIAL ===
Idioma: es
Título: Qué son los Tickets
Slug: que-son-los-tickets
Categoría: Tickets
Resumen: Aprende qué son los Tickets en AFRUS: rifas con un rango de números que vendes desde un widget y que se asignan a cada comprador.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-sirven-los-tickets, cada-cuanto-se-actualizan-los-tickets, como-crear-un-widget-de-producto, como-incluir-el-numero-de-ticket-en-mi-autoresponder
--- CUERPO (HTML) ---
<p><strong>Un Ticket es una rifa con un rango de números, por ejemplo del 1 al 500.</strong> Cuando la vinculas a un widget de producto, cada persona que compra recibe un número de ticket consecutivo por cada unidad que compra.</p>
<p>Los encuentras en <strong>Fundraising &gt; Tickets</strong>. Desde ahí creas la rifa con su <strong>Nombre</strong>, <strong>Descripción</strong>, <strong>Estado</strong> y <strong>Rango</strong> (<strong>Número Inicial</strong> y <strong>Número Final</strong>), y ves quién compró cada número.</p>
<p>Cada número se muestra con ceros a la izquierda hasta el largo del Número Final: con un rango hasta 500, el ticket 42 se ve como 042.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Puedo vender entradas para eventos con QR?</strong> Todavía no. Esa función está en desarrollo; hoy Tickets se usa para rifas.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Para qué sirven los Tickets
Slug: para-que-sirven-los-tickets
Categoría: Tickets
Resumen: Aprende para qué sirven los Tickets: vender números de rifa en línea, asignarlos automáticamente y saber quién compró cada uno.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-los-tickets, cada-cuanto-se-actualizan-los-tickets, como-crear-un-widget-de-producto, como-incluir-el-numero-de-ticket-en-mi-autoresponder
--- CUERPO (HTML) ---
<p>Con Tickets organizas una rifa en línea. Esto es lo que te permite hacer:</p>
<ul>
<li><strong>Vender números de rifa en línea.</strong> Los vendes desde un widget, con un precio por ticket.</li>
<li><strong>Asignar los números automáticamente.</strong> Cada comprador recibe sus números, y puedes mostrárselos en la página de agradecimiento y en el autoresponder.</li>
<li><strong>Saber quién compró cada número.</strong> Ves la persona, la transacción, el widget y el país de cada ticket, para hacer el sorteo y contactar al ganador.</li>
</ul>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Qué reviso antes del sorteo?</strong> Que cada número corresponda a una transacción exitosa (los pagos rechazados también reciben número) y que no haya números repetidos.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cada cuánto se actualizan los Tickets
Slug: cada-cuanto-se-actualizan-los-tickets
Categoría: Tickets
Resumen: Aprende cuándo se asignan los números de rifa y cuándo se actualizan las pantallas de Tickets en AFRUS.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-los-tickets, para-que-sirven-los-tickets, como-crear-un-widget-de-producto
--- CUERPO (HTML) ---
<ul>
<li><strong>Los números se asignan en el momento</strong> en que se registra la compra en el widget.</li>
<li><strong>Las pantallas muestran los datos al abrirlas.</strong> La lista <strong>Tickets generados por transacción</strong> y la sección <strong>Productos y tickets</strong> del panel del widget consultan los datos cuando abres la pantalla o cambias un filtro. No hay que esperar a ningún proceso.</li>
<li><strong>No se refrescan solas.</strong> Para ver compras nuevas, recarga la pantalla o vuelve a buscar.</li>
</ul>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Por qué "Tickets vendidos" no coincide con la lista de tickets?</strong> <strong>Tickets vendidos</strong> cuenta solo compras exitosas, mientras que la lista también muestra los números asignados a pagos rechazados.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo crear un widget de producto para vender tickets
Slug: como-crear-un-widget-de-producto
Categoría: Tickets
Resumen: Aprende a crear una rifa en Tickets y un widget de producto que venda sus números con un precio por ticket.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-los-tickets, cada-cuanto-se-actualizan-los-tickets, como-incluir-el-numero-de-ticket-en-mi-autoresponder
--- CUERPO (HTML) ---
<p>Para vender tickets necesitas la rifa (con su rango de números) y un widget con objetivo <strong>Producto</strong> que la venda.</p>
<h2>Paso a paso</h2>
<ol>
<li><strong>Crea la rifa.</strong> Ve a <strong>Fundraising &gt; Tickets</strong> y haz clic en "Crear Ticket".</li>
<li><strong>Completa los datos.</strong> Escribe <strong>Nombre</strong> (hasta 25 caracteres para poder usarla en un widget) y <strong>Descripción</strong> (hasta 80; si la dejas vacía verás <em>"Error al crear ticket"</em>). Deja <strong>Estado</strong> en <strong>Activo</strong>.</li>
<li><strong>Define el rango.</strong> En <strong>Rango</strong>, indica <strong>Número Inicial</strong> y <strong>Número Final</strong> y haz clic en "Crear Ticket".</li>
<li><strong>Crea un widget.</strong> Ve a <strong>Fundraising &gt; Widgets</strong> y haz clic en "Nuevo widget". El editor se abre en otra pestaña, en la versión anterior de AFRUS.</li>
<li><strong>Elige el objetivo Producto.</strong> En <strong>Objetivo</strong>, elige <strong>Producto</strong>.</li>
<li><strong>Agrega el ticket.</strong> Agrega el bloque <strong>Producto</strong>, haz clic en "Agregar Producto" y en <strong>Tipo de Producto</strong> elige <strong>Ticket</strong>.</li>
<li><strong>Elige la rifa y el precio.</strong> En <strong>Seleccionar Ticket</strong>, elige tu rifa y escribe el <strong>Precio del producto</strong> (precio de cada ticket). Haz clic en "Agregar Producto".</li>
<li><strong>Guarda y publica el widget.</strong></li>
</ol>
<p>Al terminar, el donante elige cuántos tickets quiere y, en la página final, ve una tarjeta por cada número.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Puedo poner dos rifas en el mismo widget?</strong> No. Cada widget admite una sola rifa, y no se pueden mezclar productos normales con tickets.</p>
<p><strong>¿Por qué no veo mi rifa en Seleccionar Ticket?</strong> La lista muestra solo las 10 rifas creadas más recientemente.</p>
<p><strong>¿Marcarla como Inactivo detiene la venta?</strong> No. Para dejar de vender, quita el producto del widget o desactiva el widget.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo incluir el número de ticket y la cantidad en mi autoresponder
Slug: como-incluir-el-numero-de-ticket-en-mi-autoresponder
Categoría: Tickets
Resumen: Aprende a enviar a cada comprador sus números de rifa y la cantidad comprada en el autoresponder, con los merge tags de rifas.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-los-tickets, como-crear-un-widget-de-producto, para-que-sirven-los-tickets
--- CUERPO (HTML) ---
<h2>Antes de empezar</h2>
<ul>
<li><strong>Ten un autoresponder de transacción</strong> (correo o WhatsApp) que se envíe con las compras de tu widget de producto con ticket.</li>
</ul>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre tu autoresponder.</strong> Ve a <strong>Interacciones &gt; Autoresponders</strong> y abre el autoresponder.</li>
<li><strong>Abre el mapa de merge tags.</strong> Abre <strong>Merge tags</strong> y busca la categoría <strong>Merge Tags de Rifas</strong>. Al hacer clic en una tarjeta, el merge tag se copia.</li>
<li><strong>Pega los merge tags en tu texto.</strong> Escríbelos exactamente así:
<ul>
<li><strong>{{ticket_id}}</strong>: todos los números de ticket de esa compra, separados por coma.</li>
<li><strong>{{raffle_name}}</strong>: nombre de la rifa.</li>
<li><strong>{{raffle_description}}</strong>: descripción de la rifa.</li>
<li><strong>{{raffle_price}}</strong>: precio de un ticket.</li>
<li><strong>{{raffle_reference}}</strong>: número de la transacción.</li>
</ul></li>
<li><strong>Muestra la cantidad con los números.</strong> No hay un merge tag de cantidad: la cantidad es igual a cuántos números aparecen en {{ticket_id}}. Ejemplo: <em>"Tus números de la rifa {{raffle_name}} son: {{ticket_id}}"</em>.</li>
</ol>
<p>Al enviarse el mensaje, cada merge tag se reemplaza por el dato de esa compra. Puedes usar los mismos merge tags en la página de agradecimiento.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Puedo usar "Número de Ticket" o "Fecha de Sorteo" del mapa?</strong> No. Aparecen en el mapa, pero no corresponden a ningún merge tag real de rifas. Usa solo los de esta lista.</p>
<p><strong>¿Cómo compruebo que funciona?</strong> Haz una compra de prueba en tu widget y revisa el mensaje que llega.</p>
=== FIN ===
```

## English

```text
=== TUTORIAL ===
Idioma: en
Título: What Tickets are
Slug: what-are-tickets
Categoría: Tickets
Resumen: Learn what Tickets are in AFRUS: raffles with a number range that you sell from a widget and that are assigned to each buyer.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-tickets-for, how-often-do-tickets-update, how-to-create-a-product-widget, how-to-include-the-ticket-number-in-my-autoresponder
--- CUERPO (HTML) ---
<p><strong>A Ticket is a raffle with a range of numbers, for example from 1 to 500.</strong> When you link it to a product widget, each buyer receives one consecutive ticket number for every unit they buy.</p>
<p>You'll find them in <strong>Fundraising &gt; Tickets</strong>. There you create the raffle with its <strong>Nombre</strong> (Name), <strong>Descripción</strong> (Description), <strong>Estado</strong> (Status) and <strong>Rango</strong> (Range: <strong>Número Inicial</strong> and <strong>Número Final</strong>), and see who bought each number. Labels are shown as they appear in the Spanish version of the console.</p>
<p>Each number is shown with leading zeros up to the length of the end number: with a range up to 500, ticket 42 shows as 042.</p>
<h2>Frequently asked questions</h2>
<p><strong>Can I sell event tickets with QR codes?</strong> Not yet. That feature is in development; today Tickets is used for raffles.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: What Tickets are for
Slug: what-are-tickets-for
Categoría: Tickets
Resumen: Learn what Tickets are for: selling raffle numbers online, assigning them automatically and knowing who bought each one.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-tickets, how-often-do-tickets-update, how-to-create-a-product-widget, how-to-include-the-ticket-number-in-my-autoresponder
--- CUERPO (HTML) ---
<p>With Tickets you run a raffle online. This is what it lets you do:</p>
<ul>
<li><strong>Sell raffle numbers online.</strong> You sell them from a widget, with a price per ticket.</li>
<li><strong>Assign numbers automatically.</strong> Each buyer receives their numbers, and you can show them on the thank-you page and in the autoresponder.</li>
<li><strong>Know who bought each number.</strong> You see the person, transaction, widget and country of each ticket, so you can hold the draw and contact the winner.</li>
</ul>
<h2>Frequently asked questions</h2>
<p><strong>What should I check before the draw?</strong> That each number belongs to a successful transaction (declined payments also get a number) and that there are no repeated numbers.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How often Tickets update
Slug: how-often-do-tickets-update
Categoría: Tickets
Resumen: Learn when raffle numbers are assigned and when the Tickets screens update in AFRUS.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-tickets, what-are-tickets-for, how-to-create-a-product-widget
--- CUERPO (HTML) ---
<ul>
<li><strong>Numbers are assigned instantly</strong>, at the moment the purchase is recorded in the widget.</li>
<li><strong>Screens show the data when you open them.</strong> The <strong>Tickets generados por transacción</strong> (Tickets generated per transaction) list and the <strong>Productos y tickets</strong> (Products and tickets) section of the widget dashboard read the data when you open the screen or change a filter. There is no process to wait for.</li>
<li><strong>They don't refresh on their own.</strong> To see new purchases, reload the screen or search again.</li>
</ul>
<h2>Frequently asked questions</h2>
<p><strong>Why doesn't "Tickets vendidos" match the ticket list?</strong> <strong>Tickets vendidos</strong> (Tickets sold) counts only successful purchases, while the list also shows numbers assigned to declined payments.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to create a product widget to sell tickets
Slug: how-to-create-a-product-widget
Categoría: Tickets
Resumen: Learn how to create a raffle in Tickets and a product widget that sells its numbers with a price per ticket.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-tickets, how-often-do-tickets-update, how-to-include-the-ticket-number-in-my-autoresponder
--- CUERPO (HTML) ---
<p>To sell tickets you need the raffle (with its number range) and a widget with the <strong>Producto</strong> (Product) goal that sells it. Labels are shown as they appear in the Spanish version of the console.</p>
<h2>Step by step</h2>
<ol>
<li><strong>Create the raffle.</strong> Go to <strong>Fundraising &gt; Tickets</strong> and click "Crear Ticket" (Create ticket).</li>
<li><strong>Fill in the details.</strong> Type the <strong>Nombre</strong> (Name — up to 25 characters so it can be used in a widget) and <strong>Descripción</strong> (Description — up to 80; if you leave it empty you'll see <em>"Error al crear ticket"</em>). Leave <strong>Estado</strong> as <strong>Activo</strong> (Active).</li>
<li><strong>Set the range.</strong> In <strong>Rango</strong> (Range), enter <strong>Número Inicial</strong> (start) and <strong>Número Final</strong> (end) and click "Crear Ticket".</li>
<li><strong>Create a widget.</strong> Go to <strong>Fundraising &gt; Widgets</strong> and click "Nuevo widget" (New widget). The editor opens in another tab, in the previous version of AFRUS.</li>
<li><strong>Choose the Product goal.</strong> In <strong>Objetivo</strong> (Goal), choose <strong>Producto</strong>.</li>
<li><strong>Add the ticket.</strong> Add the <strong>Producto</strong> block, click "Agregar Producto" (Add product) and in <strong>Tipo de Producto</strong> (Product type) choose <strong>Ticket</strong>.</li>
<li><strong>Choose the raffle and price.</strong> In <strong>Seleccionar Ticket</strong> (Select ticket), choose your raffle and type the <strong>Precio del producto</strong> (price of each ticket). Click "Agregar Producto".</li>
<li><strong>Save and publish the widget.</strong></li>
</ol>
<p>When you finish, donors choose how many tickets they want and see one card per number on the final page.</p>
<h2>Frequently asked questions</h2>
<p><strong>Can I put two raffles in the same widget?</strong> No. Each widget accepts only one raffle, and regular products can't be mixed with tickets.</p>
<p><strong>Why don't I see my raffle in Seleccionar Ticket?</strong> The list only shows the 10 most recently created raffles.</p>
<p><strong>Does marking it Inactivo (Inactive) stop sales?</strong> No. To stop selling, remove the product from the widget or deactivate the widget.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to include the ticket number and quantity in my autoresponder
Slug: how-to-include-the-ticket-number-in-my-autoresponder
Categoría: Tickets
Resumen: Learn how to send each buyer their raffle numbers and the quantity bought in the autoresponder, using the raffle merge tags.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-tickets, how-to-create-a-product-widget, what-are-tickets-for
--- CUERPO (HTML) ---
<h2>Before you start</h2>
<ul>
<li><strong>Have a transaction autoresponder</strong> (email or WhatsApp) that is sent for purchases in your product widget with a ticket.</li>
</ul>
<h2>Step by step</h2>
<ol>
<li><strong>Open your autoresponder.</strong> Go to <strong>Interacciones &gt; Autoresponders</strong> and open the autoresponder.</li>
<li><strong>Open the merge tag map.</strong> Open <strong>Merge tags</strong> and find the <strong>Merge Tags de Rifas</strong> (Raffle merge tags) category. Clicking a card copies the merge tag.</li>
<li><strong>Paste the merge tags into your text.</strong> Write them exactly like this:
<ul>
<li><strong>{{ticket_id}}</strong>: all ticket numbers from that purchase, separated by commas.</li>
<li><strong>{{raffle_name}}</strong>: raffle name.</li>
<li><strong>{{raffle_description}}</strong>: raffle description.</li>
<li><strong>{{raffle_price}}</strong>: price of one ticket.</li>
<li><strong>{{raffle_reference}}</strong>: transaction number.</li>
</ul></li>
<li><strong>Show the quantity with the numbers.</strong> There is no quantity merge tag: the quantity equals how many numbers appear in {{ticket_id}}. Example: <em>"Your numbers for the {{raffle_name}} raffle are: {{ticket_id}}"</em>.</li>
</ol>
<p>When the message is sent, each merge tag is replaced with that purchase's data. You can use the same merge tags on the thank-you page.</p>
<h2>Frequently asked questions</h2>
<p><strong>Can I use "Número de Ticket" or "Fecha de Sorteo" from the map?</strong> No. They appear in the map, but they don't match any real raffle merge tag. Use only the ones in this list.</p>
<p><strong>How do I check it works?</strong> Make a test purchase in your widget and check the message you receive.</p>
=== FIN ===
```

## Português

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: O que são os Tickets
Slug: o-que-sao-os-tickets
Categoría: Tickets
Resumen: Aprenda o que são os Tickets na AFRUS: rifas com uma faixa de números que você vende por um widget e que são atribuídos a cada comprador.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-servem-os-tickets, com-que-frequencia-os-tickets-sao-atualizados, como-criar-um-widget-de-produto, como-incluir-o-numero-do-ticket-no-meu-autoresponder
--- CUERPO (HTML) ---
<p><strong>Um Ticket é uma rifa com uma faixa de números, por exemplo do 1 ao 500.</strong> Quando você a vincula a um widget de produto, cada comprador recebe um número de ticket consecutivo para cada unidade que compra.</p>
<p>Você os encontra em <strong>Fundraising &gt; Tickets</strong>. Ali você cria a rifa com <strong>Nombre</strong> (Nome), <strong>Descripción</strong> (Descrição), <strong>Estado</strong> (Status) e <strong>Rango</strong> (Faixa: <strong>Número Inicial</strong> e <strong>Número Final</strong>), e vê quem comprou cada número. Os nomes de tela aparecem como na versão em espanhol do console.</p>
<p>Cada número aparece com zeros à esquerda até o tamanho do Número Final: com uma faixa até 500, o ticket 42 aparece como 042.</p>
<h2>Perguntas frequentes</h2>
<p><strong>Posso vender ingressos para eventos com QR code?</strong> Ainda não. Essa função está em desenvolvimento; hoje Tickets é usado para rifas.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Para que servem os Tickets
Slug: para-que-servem-os-tickets
Categoría: Tickets
Resumen: Aprenda para que servem os Tickets: vender números de rifa on-line, atribuí-los automaticamente e saber quem comprou cada um.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-os-tickets, com-que-frequencia-os-tickets-sao-atualizados, como-criar-um-widget-de-produto, como-incluir-o-numero-do-ticket-no-meu-autoresponder
--- CUERPO (HTML) ---
<p>Com Tickets você organiza uma rifa on-line. Veja o que ele permite fazer:</p>
<ul>
<li><strong>Vender números de rifa on-line.</strong> Você os vende por um widget, com preço por ticket.</li>
<li><strong>Atribuir os números automaticamente.</strong> Cada comprador recebe seus números, e você pode mostrá-los na página de agradecimento e no autoresponder.</li>
<li><strong>Saber quem comprou cada número.</strong> Você vê a pessoa, a transação, o widget e o país de cada ticket, para fazer o sorteio e contatar o ganhador.</li>
</ul>
<h2>Perguntas frequentes</h2>
<p><strong>O que conferir antes do sorteio?</strong> Se cada número corresponde a uma transação aprovada (pagamentos recusados também recebem número) e se não há números repetidos.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Com que frequência os Tickets são atualizados
Slug: com-que-frequencia-os-tickets-sao-atualizados
Categoría: Tickets
Resumen: Aprenda quando os números de rifa são atribuídos e quando as telas de Tickets são atualizadas na AFRUS.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-os-tickets, para-que-servem-os-tickets, como-criar-um-widget-de-produto
--- CUERPO (HTML) ---
<ul>
<li><strong>Os números são atribuídos na hora</strong>, no momento em que a compra é registrada no widget.</li>
<li><strong>As telas mostram os dados ao abrir.</strong> A lista <strong>Tickets generados por transacción</strong> (Tickets gerados por transação) e a seção <strong>Productos y tickets</strong> (Produtos e tickets) do painel do widget consultam os dados quando você abre a tela ou muda um filtro. Não há processo para esperar.</li>
<li><strong>Elas não se atualizam sozinhas.</strong> Para ver compras novas, recarregue a tela ou busque de novo.</li>
</ul>
<h2>Perguntas frequentes</h2>
<p><strong>Por que "Tickets vendidos" não bate com a lista de tickets?</strong> <strong>Tickets vendidos</strong> conta só as compras aprovadas, enquanto a lista também mostra os números atribuídos a pagamentos recusados.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como criar um widget de produto para vender tickets
Slug: como-criar-um-widget-de-produto
Categoría: Tickets
Resumen: Aprenda a criar uma rifa em Tickets e um widget de produto que venda seus números com preço por ticket.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-os-tickets, com-que-frequencia-os-tickets-sao-atualizados, como-incluir-o-numero-do-ticket-no-meu-autoresponder
--- CUERPO (HTML) ---
<p>Para vender tickets você precisa da rifa (com sua faixa de números) e de um widget com o objetivo <strong>Producto</strong> (Produto) que a venda. Os nomes de tela aparecem como na versão em espanhol do console.</p>
<h2>Passo a passo</h2>
<ol>
<li><strong>Crie a rifa.</strong> Acesse <strong>Fundraising &gt; Tickets</strong> e clique em "Crear Ticket" (Criar ticket).</li>
<li><strong>Preencha os dados.</strong> Digite o <strong>Nombre</strong> (Nome — até 25 caracteres para poder usá-la em um widget) e a <strong>Descripción</strong> (Descrição — até 80; se ficar vazia, você verá <em>"Error al crear ticket"</em>). Deixe <strong>Estado</strong> como <strong>Activo</strong> (Ativo).</li>
<li><strong>Defina a faixa.</strong> Em <strong>Rango</strong> (Faixa), informe <strong>Número Inicial</strong> e <strong>Número Final</strong> e clique em "Crear Ticket".</li>
<li><strong>Crie um widget.</strong> Acesse <strong>Fundraising &gt; Widgets</strong> e clique em "Nuevo widget" (Novo widget). O editor abre em outra aba, na versão anterior da AFRUS.</li>
<li><strong>Escolha o objetivo Produto.</strong> Em <strong>Objetivo</strong>, escolha <strong>Producto</strong>.</li>
<li><strong>Adicione o ticket.</strong> Adicione o bloco <strong>Producto</strong>, clique em "Agregar Producto" (Adicionar produto) e em <strong>Tipo de Producto</strong> escolha <strong>Ticket</strong>.</li>
<li><strong>Escolha a rifa e o preço.</strong> Em <strong>Seleccionar Ticket</strong> (Selecionar ticket), escolha sua rifa e digite o <strong>Precio del producto</strong> (preço de cada ticket). Clique em "Agregar Producto".</li>
<li><strong>Salve e publique o widget.</strong></li>
</ol>
<p>Ao terminar, o doador escolhe quantos tickets quer e vê, na página final, um cartão por número.</p>
<h2>Perguntas frequentes</h2>
<p><strong>Posso colocar duas rifas no mesmo widget?</strong> Não. Cada widget aceita uma única rifa, e não é possível misturar produtos comuns com tickets.</p>
<p><strong>Por que não vejo minha rifa em Seleccionar Ticket?</strong> A lista mostra só as 10 rifas criadas mais recentemente.</p>
<p><strong>Marcar como Inactivo (Inativo) interrompe a venda?</strong> Não. Para parar de vender, retire o produto do widget ou desative o widget.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como incluir o número do ticket e a quantidade no meu autoresponder
Slug: como-incluir-o-numero-do-ticket-no-meu-autoresponder
Categoría: Tickets
Resumen: Aprenda a enviar a cada comprador seus números de rifa e a quantidade comprada no autoresponder, com os merge tags de rifas.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-os-tickets, como-criar-um-widget-de-produto, para-que-servem-os-tickets
--- CUERPO (HTML) ---
<h2>Antes de começar</h2>
<ul>
<li><strong>Tenha um autoresponder de transação</strong> (e-mail ou WhatsApp) que seja enviado para as compras do seu widget de produto com ticket.</li>
</ul>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra seu autoresponder.</strong> Acesse <strong>Interacciones &gt; Autoresponders</strong> e abra o autoresponder.</li>
<li><strong>Abra o mapa de merge tags.</strong> Abra <strong>Merge tags</strong> e procure a categoria <strong>Merge Tags de Rifas</strong>. Ao clicar em um cartão, o merge tag é copiado.</li>
<li><strong>Cole os merge tags no seu texto.</strong> Escreva-os exatamente assim:
<ul>
<li><strong>{{ticket_id}}</strong>: todos os números de ticket daquela compra, separados por vírgula.</li>
<li><strong>{{raffle_name}}</strong>: nome da rifa.</li>
<li><strong>{{raffle_description}}</strong>: descrição da rifa.</li>
<li><strong>{{raffle_price}}</strong>: preço de um ticket.</li>
<li><strong>{{raffle_reference}}</strong>: número da transação.</li>
</ul></li>
<li><strong>Mostre a quantidade com os números.</strong> Não existe merge tag de quantidade: a quantidade é igual a quantos números aparecem em {{ticket_id}}. Exemplo: <em>"Seus números da rifa {{raffle_name}} são: {{ticket_id}}"</em>.</li>
</ol>
<p>Quando a mensagem é enviada, cada merge tag é substituído pelo dado daquela compra. Você pode usar os mesmos merge tags na página de agradecimento.</p>
<h2>Perguntas frequentes</h2>
<p><strong>Posso usar "Número de Ticket" ou "Fecha de Sorteo" do mapa?</strong> Não. Eles aparecem no mapa, mas não correspondem a nenhum merge tag real de rifas. Use só os desta lista.</p>
<p><strong>Como confiro se funciona?</strong> Faça uma compra de teste no seu widget e confira a mensagem que chega.</p>
=== FIN ===
```
