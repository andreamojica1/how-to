# Logs de analytics — tutoriales web (afrus.ai/howto)

Un bloque por tutorial, listo para pegar. Orden: español, inglés, portugués.

## Español

```text
=== TUTORIAL ===
Idioma: es
Título: Qué es Logs de analytics
Slug: que-es-logs-de-analytics
Categoría: Trackers
Resumen: Aprende qué es Logs de analytics: el registro de los avisos que tus formularios envían a Google Analytics 4, Meta o Tag Manager.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-sirve-logs-de-analytics, como-analizar-logs-de-analytics
--- CUERPO (HTML) ---
<p><strong>Logs de analytics es el registro de cada aviso que tus formularios de donación enviaron a Google Analytics 4, a Meta (Facebook) o a Google Tag Manager.</strong> Lo encuentras en <strong>Trackers &gt; Logs de analytics</strong>.</p>
<p>Si tienes conectada alguna de esas herramientas a un formulario, cada vez que una persona lo abre, avanza un paso o completa su donación, AFRUS le avisa. A cada aviso se le llama <strong>evento</strong>. Aquí ves cada evento, qué se envió y qué respondió la herramienta.</p>
<p>Si tu formulario no tiene ninguna de esas herramientas configurada, no se envía nada y la pantalla queda vacía.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿La pantalla se actualiza sola?</strong> No. Recárgala para ver eventos nuevos.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Para qué sirve Logs de analytics
Slug: para-que-sirve-logs-de-analytics
Categoría: Trackers
Resumen: Aprende para qué sirve Logs de analytics: comprobar que tu medición funciona y encontrar errores de configuración.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-logs-de-analytics, como-analizar-logs-de-analytics
--- CUERPO (HTML) ---
<p>Logs de analytics (<strong>Trackers &gt; Logs de analytics</strong>) te sirve para:</p>
<ul>
<li><strong>Comprobar que tu medición funciona.</strong> Ves si los eventos de tus formularios salen hacia Google o Meta.</li>
<li><strong>Encontrar errores de configuración.</strong> Por ejemplo, si al formulario le faltan los datos de conexión de Google o de Meta.</li>
<li><strong>Revisar los eventos de una persona.</strong> Útil para comprobar una donación de prueba.</li>
</ul>
<h2>Preguntas frecuentes</h2>
<p><strong>No veo ninguna fila de mi formulario.</strong> Lo más probable es que no tenga configurado Google Analytics 4, el Pixel de Meta ni Google Tag Manager.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo analizar los Logs de analytics
Slug: como-analizar-logs-de-analytics
Categoría: Trackers
Resumen: Aprende a comprobar en Logs de analytics que Google Analytics 4, Meta o Tag Manager reciben los eventos de tus formularios.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-logs-de-analytics, para-que-sirve-logs-de-analytics
--- CUERPO (HTML) ---
<h2>Paso a paso</h2>
<ol>
<li><strong>Haz una donación de prueba</strong> o espera donaciones reales.</li>
<li><strong>Abre la pantalla.</strong> Entra a <strong>Trackers &gt; Logs de analytics</strong> y elige un rango de fechas que incluya la prueba (al abrir muestra el mes en curso).</li>
<li><strong>Busca a la persona.</strong> Escribe su correo o su ID y pulsa la <strong>lupa</strong> (con Enter no busca).</li>
<li><strong>Lee la Descripción.</strong> <em>GOOGLE-…</em> es Google Analytics 4, <em>FACEBOOK-…</em> es Meta y <em>GOOGLE-TAG-MANAGER-…</em> es Tag Manager. La parte final dice qué pasó: <em>START</em> (se abrió el formulario), <em>PURCHASE</em> (pago confirmado), <em>REGISTER</em> (registro); los demás son pasos intermedios.</li>
<li><strong>Abre el detalle.</strong> Pulsa el ojo de la fila para ver lo que se envió y lo que respondió la herramienta.</li>
</ol>
<h2>Cómo leer la respuesta</h2>
<ul>
<li><strong>Meta:</strong> si falló, verás <em>success: false</em> y el motivo, por ejemplo que faltan los datos del Pixel.</li>
<li><strong>Google Analytics 4:</strong> <em>missing_ga_credentials</em> quiere decir que al formulario le faltan los datos de GA4 y el evento no se envió. Si no hay error, confírmalo en el informe en tiempo real de GA4.</li>
<li><strong>Tag Manager:</strong> lo normal es <em>logged_only: true</em>; a Tag Manager le llega directo desde el navegador de la persona.</li>
</ul>
<h2>Preguntas frecuentes</h2>
<p><strong>El filtro Google Analytics no muestra nada.</strong> Es un problema conocido. Escribe en el buscador <em>google</em> y el evento (por ejemplo <em>google purchase</em>) y pulsa la lupa.</p>
<p><strong>¿Por qué la hora no dice si es de mañana o de tarde?</strong> Se muestra en formato de 12 horas sin AM/PM.</p>
=== FIN ===
```

## English

```text
=== TUTORIAL ===
Idioma: en
Título: What Logs de analytics is
Slug: what-is-logs-de-analytics
Categoría: Trackers
Resumen: Learn what Logs de analytics is: the record of the notices your forms send to Google Analytics 4, Meta or Tag Manager.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-logs-de-analytics-for, how-to-read-logs-de-analytics
--- CUERPO (HTML) ---
<p><strong>Logs de analytics (Analytics logs) is the record of every notice your donation forms sent to Google Analytics 4, Meta (Facebook) or Google Tag Manager.</strong> You'll find it in <strong>Trackers &gt; Logs de analytics</strong>. Labels are shown as they appear in the Spanish version of the console.</p>
<p>If one of those tools is connected to a form, every time a person opens it, moves forward a step or completes their donation, AFRUS notifies it. Each notice is called an <strong>event</strong>. Here you see each event, what was sent and what the tool answered.</p>
<p>If your form has none of those tools set up, nothing is sent and the screen stays empty.</p>
<h2>Frequently asked questions</h2>
<p><strong>Does the screen refresh by itself?</strong> No. Reload it to see new events.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: What Logs de analytics is for
Slug: what-is-logs-de-analytics-for
Categoría: Trackers
Resumen: Learn what Logs de analytics is for: checking that your tracking works and finding setup errors.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-logs-de-analytics, how-to-read-logs-de-analytics
--- CUERPO (HTML) ---
<p>Logs de analytics (<strong>Trackers &gt; Logs de analytics</strong>) helps you:</p>
<ul>
<li><strong>Check that your tracking works.</strong> See whether your forms' events go out to Google or Meta.</li>
<li><strong>Find setup errors.</strong> For example, if the form is missing its Google or Meta connection details.</li>
<li><strong>Review one person's events.</strong> Useful for checking a test donation.</li>
</ul>
<h2>Frequently asked questions</h2>
<p><strong>I don't see any rows for my form.</strong> Most likely it doesn't have Google Analytics 4, the Meta Pixel or Google Tag Manager set up.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to read the Logs de analytics
Slug: how-to-read-logs-de-analytics
Categoría: Trackers
Resumen: Learn how to check in Logs de analytics that Google Analytics 4, Meta or Tag Manager receive your forms' events.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-logs-de-analytics, what-is-logs-de-analytics-for
--- CUERPO (HTML) ---
<h2>Step by step</h2>
<ol>
<li><strong>Make a test donation</strong> or wait for real donations.</li>
<li><strong>Open the screen.</strong> Go to <strong>Trackers &gt; Logs de analytics</strong> and choose a date range that includes the test (it opens on the current month).</li>
<li><strong>Search for the person.</strong> Type their email or ID and click the <strong>magnifying glass</strong> (Enter doesn't search).</li>
<li><strong>Read the Descripción (Description).</strong> <em>GOOGLE-…</em> is Google Analytics 4, <em>FACEBOOK-…</em> is Meta and <em>GOOGLE-TAG-MANAGER-…</em> is Tag Manager. The last part says what happened: <em>START</em> (form opened), <em>PURCHASE</em> (payment confirmed), <em>REGISTER</em> (sign-up); the rest are steps in between.</li>
<li><strong>Open the detail.</strong> Click the eye on the row to see what was sent and what the tool answered.</li>
</ol>
<h2>How to read the answer</h2>
<ul>
<li><strong>Meta:</strong> if it failed, you'll see <em>success: false</em> and the reason, for example missing Pixel details.</li>
<li><strong>Google Analytics 4:</strong> <em>missing_ga_credentials</em> means the form is missing its GA4 details and the event was not sent. If there's no error, confirm it in GA4's real-time report.</li>
<li><strong>Tag Manager:</strong> <em>logged_only: true</em> is normal; Tag Manager receives it directly from the person's browser.</li>
</ul>
<h2>Frequently asked questions</h2>
<p><strong>The Google Analytics filter shows nothing.</strong> It's a known problem. Type <em>google</em> and the event (for example <em>google purchase</em>) in the search box and click the magnifying glass.</p>
<p><strong>Why doesn't the time say morning or afternoon?</strong> It's shown in 12-hour format without AM/PM.</p>
=== FIN ===
```

## Português

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: O que é Logs de analytics
Slug: o-que-e-logs-de-analytics
Categoría: Trackers
Resumen: Aprenda o que é Logs de analytics: o registro dos avisos que seus formulários enviam ao Google Analytics 4, à Meta ou ao Tag Manager.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-serve-logs-de-analytics, como-analisar-logs-de-analytics
--- CUERPO (HTML) ---
<p><strong>Logs de analytics é o registro de cada aviso que seus formulários de doação enviaram ao Google Analytics 4, à Meta (Facebook) ou ao Google Tag Manager.</strong> Fica em <strong>Trackers &gt; Logs de analytics</strong>. Os nomes de tela aparecem como na versão em espanhol do console.</p>
<p>Se uma dessas ferramentas está conectada a um formulário, toda vez que uma pessoa o abre, avança uma etapa ou conclui a doação, a AFRUS avisa a ferramenta. Cada aviso se chama <strong>evento</strong>. Aqui você vê cada evento, o que foi enviado e o que a ferramenta respondeu.</p>
<p>Se o seu formulário não tem nenhuma dessas ferramentas configurada, nada é enviado e a tela fica vazia.</p>
<h2>Perguntas frequentes</h2>
<p><strong>A tela se atualiza sozinha?</strong> Não. Recarregue para ver eventos novos.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Para que serve Logs de analytics
Slug: para-que-serve-logs-de-analytics
Categoría: Trackers
Resumen: Aprenda para que serve Logs de analytics: conferir se a sua medição funciona e encontrar erros de configuração.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-logs-de-analytics, como-analisar-logs-de-analytics
--- CUERPO (HTML) ---
<p>Logs de analytics (<strong>Trackers &gt; Logs de analytics</strong>) serve para:</p>
<ul>
<li><strong>Conferir se a sua medição funciona.</strong> Você vê se os eventos dos seus formulários saem para o Google ou a Meta.</li>
<li><strong>Encontrar erros de configuração.</strong> Por exemplo, se faltam no formulário os dados de conexão do Google ou da Meta.</li>
<li><strong>Revisar os eventos de uma pessoa.</strong> Útil para conferir uma doação de teste.</li>
</ul>
<h2>Perguntas frequentes</h2>
<p><strong>Não vejo nenhuma linha do meu formulário.</strong> O mais provável é que ele não tenha configurado o Google Analytics 4, o Pixel da Meta nem o Google Tag Manager.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como analisar os Logs de analytics
Slug: como-analisar-logs-de-analytics
Categoría: Trackers
Resumen: Aprenda a conferir em Logs de analytics se o Google Analytics 4, a Meta ou o Tag Manager recebem os eventos dos seus formulários.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-logs-de-analytics, para-que-serve-logs-de-analytics
--- CUERPO (HTML) ---
<h2>Passo a passo</h2>
<ol>
<li><strong>Faça uma doação de teste</strong> ou espere doações reais.</li>
<li><strong>Abra a tela.</strong> Acesse <strong>Trackers &gt; Logs de analytics</strong> e escolha um período que inclua o teste (ao abrir, mostra o mês atual).</li>
<li><strong>Busque a pessoa.</strong> Digite o e-mail ou o ID e clique na <strong>lupa</strong> (o Enter não busca).</li>
<li><strong>Leia a Descripción (Descrição).</strong> <em>GOOGLE-…</em> é o Google Analytics 4, <em>FACEBOOK-…</em> é a Meta e <em>GOOGLE-TAG-MANAGER-…</em> é o Tag Manager. A parte final diz o que aconteceu: <em>START</em> (formulário aberto), <em>PURCHASE</em> (pagamento confirmado), <em>REGISTER</em> (cadastro); os outros são etapas intermediárias.</li>
<li><strong>Abra o detalhe.</strong> Clique no olho da linha para ver o que foi enviado e o que a ferramenta respondeu.</li>
</ol>
<h2>Como ler a resposta</h2>
<ul>
<li><strong>Meta:</strong> se falhou, você verá <em>success: false</em> e o motivo, por exemplo que faltam os dados do Pixel.</li>
<li><strong>Google Analytics 4:</strong> <em>missing_ga_credentials</em> quer dizer que faltam no formulário os dados do GA4 e o evento não foi enviado. Se não houver erro, confirme no relatório em tempo real do GA4.</li>
<li><strong>Tag Manager:</strong> o normal é <em>logged_only: true</em>; o Tag Manager recebe direto do navegador da pessoa.</li>
</ul>
<h2>Perguntas frequentes</h2>
<p><strong>O filtro Google Analytics não mostra nada.</strong> É um problema conhecido. Digite <em>google</em> e o evento (por exemplo <em>google purchase</em>) no campo de busca e clique na lupa.</p>
<p><strong>Por que a hora não diz se é de manhã ou de tarde?</strong> Ela aparece no formato de 12 horas sem AM/PM.</p>
=== FIN ===
```
