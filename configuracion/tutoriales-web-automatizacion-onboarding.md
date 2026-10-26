# Automatización Onboarding — tutoriales web (afrus.ai/howto)

Un bloque por tutorial, listo para pegar. Orden: español, inglés, portugués.

## Español

```text
=== TUTORIAL ===
Idioma: es
Título: Qué es la Automatización Onboarding
Slug: que-es-la-automatizacion-onboarding
Categoría: Configuración
Resumen: Aprende qué es configurar tu dominio de correo en Afrus y cómo saber si ya está listo.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-sirve-la-automatizacion-onboarding, como-configurar-mis-dns-en-afrus
--- CUERPO (HTML) ---
<p><strong>Es el paso en el que autorizas a Afrus a enviar correos con el dominio de tu organización</strong> (por ejemplo, <em>tuorg.org</em>). Para eso se crean unos registros (DNS) en el proveedor donde tienes tu dominio. Mientras no lo configures, tus correos salen desde una cuenta de Afrus.</p>
<h2>Cómo saber si ya está configurado</h2>
<p>Arriba de <strong>Interacciones &gt; Autoresponders</strong> y de <strong>Interacciones &gt; Blast</strong> verás una tarjeta:</p>
<ul>
<li><strong>Dominio verificado:</strong> tus correos ya salen con tu dominio.</li>
<li><strong>No tienes un dominio verificado para Email:</strong> tus correos salen desde una cuenta de Afrus.</li>
<li><strong>Error en registros DNS:</strong> hay un problema con los registros y hay que corregirlos.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Para qué sirve la Automatización Onboarding
Slug: para-que-sirve-la-automatizacion-onboarding
Categoría: Configuración
Resumen: Aprende para qué sirve verificar tu dominio de correo: enviar desde tu propio correo, llegar mejor a la bandeja y crear flujos.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-la-automatizacion-onboarding, como-configurar-mis-dns-en-afrus
--- CUERPO (HTML) ---
<ul>
<li><strong>Enviar desde tu propio correo.</strong> Tus donantes reciben los correos desde una dirección de tu organización.</li>
<li><strong>Llegar mejor a la bandeja de entrada.</strong> Configurar tus DNS mejora la entregabilidad de tus correos.</li>
<li><strong>Crear flujos de trabajo.</strong> Para crear un flujo en <strong>Interacciones &gt; Flujos de trabajo</strong> necesitas el dominio verificado.</li>
<li><strong>Elegir remitente.</strong> Al verificar, en el remitente de autoresponders y Blast aparecen los correos de tus usuarios que terminan en ese dominio.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo configurar mis DNS en Afrus
Slug: como-configurar-mis-dns-en-afrus
Categoría: Configuración
Resumen: Aprende a configurar los DNS de tu dominio paso a paso para que Afrus envíe tus correos con el dominio de tu organización.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-la-automatizacion-onboarding, para-que-sirve-la-automatizacion-onboarding
--- CUERPO (HTML) ---
<h2>Antes de empezar</h2>
<ul>
<li><strong>Ten acceso al panel de tu proveedor de dominio</strong> o pide ayuda a quien lo maneja en tu equipo.</li>
<li><strong>La cuenta de envío de tu organización debe estar configurada por Afrus.</strong> Si ves <em>"Hubo un error al crear el dominio"</em>, escríbenos.</li>
</ul>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre la configuración.</strong> En <strong>Interacciones &gt; Autoresponders</strong> o <strong>Interacciones &gt; Blast</strong>, haz clic en "Configurar DNS" en la tarjeta del dominio. La pantalla se abre en la versión anterior de Afrus.</li>
<li><strong>Escribe tu dominio.</strong> En <strong>Configurar dominio</strong>, escribe tu <strong>Dominio</strong>, haz clic en "Iniciar autenticación" y luego en "Continuar".</li>
<li><strong>Indica tu proveedor.</strong> Responde <em>"¿Cuál es tu proveedor de DNS?"</em>, sigue las instrucciones y haz clic en "Continuar".</li>
<li><strong>Crea los registros DKIM.</strong> Copia los 3 registros <strong>CNAME</strong> que muestra la pantalla y créalos en tu proveedor. Haz clic en "Continuar".</li>
<li><strong>Crea los registros DMARC.</strong> Crea en tu proveedor los registros de la tabla: dos <strong>TXT</strong> y un <strong>MX</strong> con <strong>Prioridad</strong> 10. Haz clic en "Finalizar".</li>
</ol>
<p>Al terminar verás tu dominio y su estado. La validación puede tardar hasta 48 horas, aunque por lo general es mucho más rápida. Usa "Comprobar estado" para revisarlo.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Cómo envío desde una dirección concreta?</strong> Esa dirección tiene que ser de un usuario de tu organización.</p>
=== FIN ===
```

## English

```text
=== TUTORIAL ===
Idioma: en
Título: What onboarding automation is
Slug: what-is-onboarding-automation
Categoría: Configuración
Resumen: Learn what setting up your email domain in Afrus means and how to know if it's ready.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-onboarding-automation-for, how-to-set-up-my-dns-in-afrus
--- CUERPO (HTML) ---
<p><strong>It is the step where you authorize Afrus to send emails with your organization's domain</strong> (for example, <em>yourorg.org</em>). To do this, you create some records (DNS) at the provider where your domain is hosted. Until you set it up, your emails go out from an Afrus account. Labels are shown as they appear in the Spanish version of the console.</p>
<h2>How to know if it's already set up</h2>
<p>At the top of <strong>Interacciones &gt; Autoresponders</strong> and <strong>Interacciones &gt; Blast</strong> you'll see a card:</p>
<ul>
<li><strong>Dominio verificado</strong> (Verified domain): your emails go out with your domain.</li>
<li><strong>No tienes un dominio verificado para Email</strong> (No verified email domain): your emails go out from an Afrus account.</li>
<li><strong>Error en registros DNS</strong> (DNS record error): there is a problem with the records and they need fixing.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: What onboarding automation is for
Slug: what-is-onboarding-automation-for
Categoría: Configuración
Resumen: Learn why to verify your email domain: send from your own address, reach the inbox more often and create workflows.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-onboarding-automation, how-to-set-up-my-dns-in-afrus
--- CUERPO (HTML) ---
<ul>
<li><strong>Sending from your own email address.</strong> Donors receive emails from an address of your organization.</li>
<li><strong>Reaching the inbox more often.</strong> Setting up your DNS improves your emails' deliverability.</li>
<li><strong>Creating workflows.</strong> To create a workflow in <strong>Interacciones &gt; Flujos de trabajo</strong> you need a verified domain.</li>
<li><strong>Choosing a sender.</strong> Once verified, the sender options for autoresponders and Blast include your users' emails that end in that domain.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to set up my DNS in Afrus
Slug: how-to-set-up-my-dns-in-afrus
Categoría: Configuración
Resumen: Learn how to set up your domain's DNS step by step so Afrus sends your emails with your organization's domain.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-onboarding-automation, what-is-onboarding-automation-for
--- CUERPO (HTML) ---
<p>Labels are shown as they appear in the Spanish version of the console.</p>
<h2>Before you start</h2>
<ul>
<li><strong>Have access to your domain provider's panel</strong>, or ask whoever manages it on your team.</li>
<li><strong>Your organization's sending account must be set up by Afrus.</strong> If you see <em>"Hubo un error al crear el dominio"</em> (There was an error creating the domain), write to us.</li>
</ul>
<h2>Step by step</h2>
<ol>
<li><strong>Open the setup.</strong> In <strong>Interacciones &gt; Autoresponders</strong> or <strong>Interacciones &gt; Blast</strong>, click "Configurar DNS" (Set up DNS) on the domain card. The screen opens in the previous version of Afrus.</li>
<li><strong>Enter your domain.</strong> In <strong>Configurar dominio</strong> (Set up domain), type your <strong>Dominio</strong> (Domain), click "Iniciar autenticación" (Start authentication) and then "Continuar" (Continue).</li>
<li><strong>Choose your provider.</strong> Answer <em>"¿Cuál es tu proveedor de DNS?"</em> (Who is your DNS provider?), follow the instructions and click "Continuar".</li>
<li><strong>Create the DKIM records.</strong> Copy the 3 <strong>CNAME</strong> records shown on screen and create them at your provider. Click "Continuar".</li>
<li><strong>Create the DMARC records.</strong> Create at your provider the records in the table: two <strong>TXT</strong> and one <strong>MX</strong> with <strong>Prioridad</strong> (Priority) 10. Click "Finalizar" (Finish).</li>
</ol>
<p>When you finish you'll see your domain and its status. Validation can take up to 48 hours, although it's usually much faster. Use "Comprobar estado" (Check status) to check it.</p>
<h2>Frequently asked questions</h2>
<p><strong>How do I send from a specific address?</strong> That address has to belong to a user of your organization.</p>
=== FIN ===
```

## Português

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: O que é a Automação Onboarding
Slug: o-que-e-a-automacao-onboarding
Categoría: Configuración
Resumen: Aprenda o que é configurar seu domínio de e-mail na Afrus e como saber se já está pronto.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-serve-a-automacao-onboarding, como-configurar-meus-dns-na-afrus
--- CUERPO (HTML) ---
<p><strong>É a etapa em que você autoriza a Afrus a enviar e-mails com o domínio da sua organização</strong> (por exemplo, <em>suaorg.org</em>). Para isso, você cria alguns registros (DNS) no provedor do seu domínio. Enquanto não configurar, seus e-mails saem de uma conta da Afrus. Os nomes de tela aparecem como na versão em espanhol do console.</p>
<h2>Como saber se já está configurado</h2>
<p>No topo de <strong>Interacciones &gt; Autoresponders</strong> e de <strong>Interacciones &gt; Blast</strong> você verá um cartão:</p>
<ul>
<li><strong>Dominio verificado</strong> (Domínio verificado): seus e-mails já saem com o seu domínio.</li>
<li><strong>No tienes un dominio verificado para Email</strong> (Você não tem um domínio verificado): seus e-mails saem de uma conta da Afrus.</li>
<li><strong>Error en registros DNS</strong> (Erro nos registros DNS): há um problema nos registros e é preciso corrigi-los.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Para que serve a Automação Onboarding
Slug: para-que-serve-a-automacao-onboarding
Categoría: Configuración
Resumen: Aprenda para que serve verificar seu domínio de e-mail: enviar do seu próprio e-mail, chegar mais à caixa de entrada e criar fluxos.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-a-automacao-onboarding, como-configurar-meus-dns-na-afrus
--- CUERPO (HTML) ---
<ul>
<li><strong>Enviar do seu próprio e-mail.</strong> Seus doadores recebem os e-mails de um endereço da sua organização.</li>
<li><strong>Chegar mais à caixa de entrada.</strong> Configurar seus DNS melhora a entregabilidade dos seus e-mails.</li>
<li><strong>Criar fluxos de trabalho.</strong> Para criar um fluxo em <strong>Interacciones &gt; Flujos de trabajo</strong> você precisa do domínio verificado.</li>
<li><strong>Escolher o remetente.</strong> Ao verificar, no remetente de autoresponders e Blast aparecem os e-mails dos seus usuários que terminam nesse domínio.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como configurar meus DNS na Afrus
Slug: como-configurar-meus-dns-na-afrus
Categoría: Configuración
Resumen: Aprenda a configurar os DNS do seu domínio passo a passo para que a Afrus envie seus e-mails com o domínio da sua organização.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-a-automacao-onboarding, para-que-serve-a-automacao-onboarding
--- CUERPO (HTML) ---
<p>Os nomes de tela aparecem como na versão em espanhol do console.</p>
<h2>Antes de começar</h2>
<ul>
<li><strong>Tenha acesso ao painel do seu provedor de domínio</strong> ou peça ajuda a quem cuida disso na sua equipe.</li>
<li><strong>A conta de envio da sua organização precisa estar configurada pela Afrus.</strong> Se aparecer <em>"Hubo un error al crear el dominio"</em> (Houve um erro ao criar o domínio), escreva para nós.</li>
</ul>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra a configuração.</strong> Em <strong>Interacciones &gt; Autoresponders</strong> ou <strong>Interacciones &gt; Blast</strong>, clique em "Configurar DNS" no cartão do domínio. A tela abre na versão anterior da Afrus.</li>
<li><strong>Digite seu domínio.</strong> Em <strong>Configurar dominio</strong> (Configurar domínio), digite seu <strong>Dominio</strong> (Domínio), clique em "Iniciar autenticación" (Iniciar autenticação) e depois em "Continuar".</li>
<li><strong>Informe seu provedor.</strong> Responda <em>"¿Cuál es tu proveedor de DNS?"</em> (Qual é o seu provedor de DNS?), siga as instruções e clique em "Continuar".</li>
<li><strong>Crie os registros DKIM.</strong> Copie os 3 registros <strong>CNAME</strong> da tela e crie-os no seu provedor. Clique em "Continuar".</li>
<li><strong>Crie os registros DMARC.</strong> Crie no seu provedor os registros da tabela: dois <strong>TXT</strong> e um <strong>MX</strong> com <strong>Prioridad</strong> (Prioridade) 10. Clique em "Finalizar".</li>
</ol>
<p>Ao terminar, você verá seu domínio e o status. A validação pode levar até 48 horas, mas em geral é muito mais rápida. Use "Comprobar estado" (Verificar status) para conferir.</p>
<h2>Perguntas frequentes</h2>
<p><strong>Como envio de um endereço específico?</strong> Esse endereço precisa ser de um usuário da sua organização.</p>
=== FIN ===
```

