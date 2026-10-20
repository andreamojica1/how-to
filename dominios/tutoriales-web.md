# Dominios — tutoriales web (afrus.ai/howto)

Un bloque por tutorial, listo para pegar. Orden: español, inglés, portugués.

## Español

```text
=== TUTORIAL ===
Idioma: es
Título: Qué es Dominios en Afrus
Slug: que-es-dominios
Categoría: Dominios
Resumen: Aprende qué es el módulo Dominios: donde registras el dominio propio de tu organización para publicar tus landings con tu dirección.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-sirven-los-dominios, como-agregar-y-configurar-mi-dominio-en-afrus, como-cambiar-la-url-de-mi-landing
--- CUERPO (HTML) ---
<p><strong>Dominios es la pantalla donde registras el dominio o subdominio propio de tu organización (por ejemplo <em>donaciones.miorganizacion.org</em>) para que tus landing pages se publiquen con esa dirección</strong>, en lugar de la dirección por defecto de Afrus (<em>web.afrus.org</em>).</p>
<p>Como dice la propia pantalla: <em>"Asocia un dominio propio para que tus landing pages se vean con la URL de tu organización, fortaleciendo tu marca y generando más confianza en tus campañas."</em></p>
<h2>Dónde lo encuentras</h2>
<p>En <strong>Fundraising &gt; Dominios</strong>. Ahí agregas dominios y ves tu <strong>Lista de dominios</strong>, con su <strong>Status</strong> (activo o inactivo), su <strong>Versión</strong>, la <strong>Fecha</strong> de registro y cuántas <strong>Páginas</strong> (landings) usan cada uno.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Afrus me vende el dominio?</strong> No. Lo compras con un proveedor (GoDaddy, Media Temple u otro) y lo configuras allí.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Para qué sirven los dominios propios
Slug: para-que-sirven-los-dominios
Categoría: Dominios
Resumen: Aprende para qué sirve registrar tu dominio en Afrus: landings con tu marca, más confianza y certificado de seguridad automático.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-dominios, como-agregar-y-configurar-mi-dominio-en-afrus
--- CUERPO (HTML) ---
<ul>
<li><strong>Publicar tus landings con tu marca.</strong> El donante ve la dirección web de tu organización, lo que genera más confianza.</li>
<li><strong>Tener varias direcciones propias</strong> y elegir cuál usa cada landing.</li>
<li><strong>Controlar tus dominios:</strong> ver cuántas landings usa cada uno (columna <strong>Páginas</strong>) y activarlos o desactivarlos.</li>
<li><strong>Seguridad sin trámites.</strong> Afrus gestiona automáticamente el certificado de seguridad (el candado, HTTPS): no tienes que comprar ni instalar certificados.</li>
</ul>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Puedo usar mi dominio como página principal?</strong> Sí. En la landing, usa la ruta / con tu dominio.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo agregar y configurar mi dominio en Afrus
Slug: como-agregar-y-configurar-mi-dominio-en-afrus
Categoría: Dominios
Resumen: Aprende a crear el registro CNAME en tu proveedor, agregar tu dominio en Afrus y usarlo en tus landings.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: que-es-dominios, para-que-sirven-los-dominios, como-cambiar-la-url-de-mi-landing
--- CUERPO (HTML) ---
<h2>Antes de empezar</h2>
<ul>
<li><strong>Compra el dominio con un proveedor.</strong> Afrus no vende dominios.</li>
<li><strong>Ten acceso a la configuración DNS</strong> del dominio, o pide ayuda a tu equipo de TI.</li>
<li><strong>Usa un subdominio</strong> (por ejemplo donaciones.miorganizacion.org): la pantalla solo pide un registro CNAME y muchos proveedores no lo permiten en el dominio principal.</li>
</ul>
<h2>Paso a paso</h2>
<ol>
<li><strong>Crea un registro CNAME en tu proveedor.</strong> Nombre o host: tu subdominio (por ejemplo <em>donaciones</em>). Valor o destino: <em>landings2.afrus.org</em>. Si la pantalla de Afrus muestra otro valor, usa siempre el de la pantalla.</li>
<li><strong>Espera a que el cambio se propague.</strong> El tiempo depende de tu proveedor, no de Afrus.</li>
<li><strong>Abre Dominios.</strong> Entra a <strong>Fundraising &gt; Dominios</strong>.</li>
<li><strong>Escribe tu dominio.</strong> En <strong>Agregar dominio personalizado</strong>, escribe el dominio sin http://, https://, barras ni rutas.</li>
<li><strong>Agrégalo.</strong> Pulsa "Agregar dominio". Verás <em>"Dominio registrado con exito"</em> y el dominio aparecerá en la lista como activo.</li>
<li><strong>Úsalo en una landing.</strong> Al crear o editar una landing, en <strong>Datos básicos</strong>, elige tu dominio en <strong>Dominio</strong>.</li>
</ol>
<p>Afrus solicita automáticamente el certificado de seguridad (HTTPS) y comprueba el dominio durante unos 15 minutos. No hay botón "Verificar". Si la comprobación falla, el dominio pasa a inactivo por sí solo. La pantalla no se actualiza sola: recárgala para ver el estado.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Qué significa "Dominio existente, prueba otro"?</strong> Ese dominio ya está registrado en Afrus; cada dominio se registra una sola vez en toda la plataforma.</p>
<p><strong>¿Qué significa "El dominio no se encuentra apuntando al Host (landings2.afrus.org)"?</strong> Tu registro CNAME todavía no apunta a Afrus. Revísalo y espera a que se propague.</p>
<p><strong>Mi dominio pasó a inactivo, ¿qué hago?</strong> Revisa el registro CNAME con tu proveedor. Si ya está bien y sigue inactivo, escríbenos a soporte: volver a encender el interruptor no repite la comprobación.</p>
<p><strong>¿www.miorganizacion.org y miorganizacion.org son lo mismo?</strong> No. Cada uno se registra por separado y necesita su propio registro DNS.</p>
=== FIN ===
```

## English

```text
=== TUTORIAL ===
Idioma: en
Título: What Domains is in Afrus
Slug: what-is-domains
Categoría: Dominios
Resumen: Learn what the Domains module is: where you register your organization's own domain to publish your landings with your address.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-custom-domains-are-for, how-to-add-and-set-up-my-domain-in-afrus, how-to-change-my-landing-url
--- CUERPO (HTML) ---
<p><strong>Dominios (Domains) is the screen where you register your organization's own domain or subdomain (for example <em>donate.myorganization.org</em>) so your landing pages are published with that address</strong>, instead of the default Afrus address (<em>web.afrus.org</em>).</p>
<p>As the screen itself says, linking your own domain makes your landing pages show your organization's URL, strengthening your brand and building more trust in your campaigns.</p>
<h2>Where to find it</h2>
<p>In <strong>Fundraising &gt; Dominios</strong>. Labels are shown as they appear in the Spanish version of the console. There you add domains and see your <strong>Lista de dominios</strong> (Domain list), with each one's <strong>Status</strong> (active or inactive), <strong>Versión</strong>, registration <strong>Fecha</strong> (date) and how many <strong>Páginas</strong> (landings) use it.</p>
<h2>Frequently asked questions</h2>
<p><strong>Does Afrus sell me the domain?</strong> No. You buy it from a provider (GoDaddy, Media Temple or another) and set it up there.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: What custom domains are for
Slug: what-custom-domains-are-for
Categoría: Dominios
Resumen: Learn why to register your domain in Afrus: landings under your brand, more trust and an automatic security certificate.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-domains, how-to-add-and-set-up-my-domain-in-afrus
--- CUERPO (HTML) ---
<ul>
<li><strong>Publish your landings under your brand.</strong> Donors see your organization's web address, which builds more trust.</li>
<li><strong>Have several addresses of your own</strong> and choose which one each landing uses.</li>
<li><strong>Keep your domains under control:</strong> see how many landings use each one (<strong>Páginas</strong> column) and turn them on or off.</li>
<li><strong>Security without the paperwork.</strong> Afrus manages the security certificate (the padlock, HTTPS) automatically: you don't need to buy or install certificates.</li>
</ul>
<h2>Frequently asked questions</h2>
<p><strong>Can I use my domain as a home page?</strong> Yes. On the landing, use the path / with your domain.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to add and set up my domain in Afrus
Slug: how-to-add-and-set-up-my-domain-in-afrus
Categoría: Dominios
Resumen: Learn how to create the CNAME record at your provider, add your domain in Afrus and use it on your landings.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-is-domains, what-custom-domains-are-for, how-to-change-my-landing-url
--- CUERPO (HTML) ---
<p>Labels are shown as they appear in the Spanish version of the console.</p>
<h2>Before you start</h2>
<ul>
<li><strong>Buy the domain from a provider.</strong> Afrus doesn't sell domains.</li>
<li><strong>Have access to the domain's DNS settings</strong>, or ask your IT team for help.</li>
<li><strong>Use a subdomain</strong> (for example donate.myorganization.org): the screen only asks for a CNAME record, and many providers don't allow one on the main domain.</li>
</ul>
<h2>Step by step</h2>
<ol>
<li><strong>Create a CNAME record at your provider.</strong> Name or host: your subdomain (for example <em>donate</em>). Value or target: <em>landings2.afrus.org</em>. If the Afrus screen shows a different value, always use the one on the screen.</li>
<li><strong>Wait for the change to propagate.</strong> How long it takes depends on your provider, not on Afrus.</li>
<li><strong>Open Domains.</strong> Go to <strong>Fundraising &gt; Dominios</strong>.</li>
<li><strong>Type your domain.</strong> In <strong>Agregar dominio personalizado</strong> (Add custom domain), type the domain without http://, https://, slashes or paths.</li>
<li><strong>Add it.</strong> Click "Agregar dominio" (Add domain). You will see <em>"Dominio registrado con exito"</em> (Domain registered successfully) and the domain will appear in the list as active.</li>
<li><strong>Use it on a landing.</strong> When creating or editing a landing, in <strong>Datos básicos</strong> (Basic data), choose your domain under <strong>Dominio</strong>.</li>
</ol>
<p>Afrus automatically requests the security certificate (HTTPS) and checks the domain for about 15 minutes. There is no "Verify" button. If the check fails, the domain becomes inactive on its own. The screen doesn't refresh by itself: reload it to see the status.</p>
<h2>Frequently asked questions</h2>
<p><strong>What does "Dominio existente, prueba otro" mean?</strong> That domain is already registered in Afrus; each domain can be registered only once across the platform.</p>
<p><strong>What does "El dominio no se encuentra apuntando al Host (landings2.afrus.org)" mean?</strong> Your CNAME record doesn't point to Afrus yet. Check it and wait for it to propagate.</p>
<p><strong>My domain became inactive. What do I do?</strong> Check the CNAME record with your provider. If it's correct and the domain is still inactive, contact support: turning the switch back on doesn't repeat the check.</p>
<p><strong>Are www.myorganization.org and myorganization.org the same?</strong> No. Each is registered separately and needs its own DNS record.</p>
=== FIN ===
```

## Português

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: O que é Domínios na Afrus
Slug: o-que-e-dominios
Categoría: Dominios
Resumen: Aprenda o que é o módulo Domínios: onde você cadastra o domínio próprio da sua organização para publicar suas landings com seu endereço.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-servem-os-dominios, como-adicionar-e-configurar-meu-dominio-na-afrus, como-mudar-a-url-da-minha-landing
--- CUERPO (HTML) ---
<p><strong>Dominios (Domínios) é a tela onde você cadastra o domínio ou subdomínio próprio da sua organização (por exemplo <em>doe.minhaorganizacao.org</em>) para que suas landing pages sejam publicadas com esse endereço</strong>, em vez do endereço padrão da Afrus (<em>web.afrus.org</em>).</p>
<p>Como diz a própria tela, associar um domínio próprio faz suas landing pages aparecerem com a URL da sua organização, fortalecendo sua marca e gerando mais confiança nas suas campanhas.</p>
<h2>Onde encontrar</h2>
<p>Em <strong>Fundraising &gt; Dominios</strong>. Os nomes de tela aparecem como na versão em espanhol do console. Ali você adiciona domínios e vê sua <strong>Lista de dominios</strong>, com o <strong>Status</strong> (ativo ou inativo), a <strong>Versión</strong>, a <strong>Fecha</strong> (data) de cadastro e quantas <strong>Páginas</strong> (landings) usam cada um.</p>
<h2>Perguntas frequentes</h2>
<p><strong>A Afrus me vende o domínio?</strong> Não. Você compra com um provedor (GoDaddy, Media Temple ou outro) e configura lá.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Para que servem os domínios próprios
Slug: para-que-servem-os-dominios
Categoría: Dominios
Resumen: Aprenda para que serve cadastrar seu domínio na Afrus: landings com sua marca, mais confiança e certificado de segurança automático.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-dominios, como-adicionar-e-configurar-meu-dominio-na-afrus
--- CUERPO (HTML) ---
<ul>
<li><strong>Publicar suas landings com a sua marca.</strong> O doador vê o endereço web da sua organização, o que gera mais confiança.</li>
<li><strong>Ter vários endereços próprios</strong> e escolher qual cada landing usa.</li>
<li><strong>Controlar seus domínios:</strong> ver quantas landings usam cada um (coluna <strong>Páginas</strong>) e ativá-los ou desativá-los.</li>
<li><strong>Segurança sem burocracia.</strong> A Afrus gerencia automaticamente o certificado de segurança (o cadeado, HTTPS): você não precisa comprar nem instalar certificados.</li>
</ul>
<h2>Perguntas frequentes</h2>
<p><strong>Posso usar meu domínio como página principal?</strong> Sim. Na landing, use o caminho / com seu domínio.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como adicionar e configurar meu domínio na Afrus
Slug: como-adicionar-e-configurar-meu-dominio-na-afrus
Categoría: Dominios
Resumen: Aprenda a criar o registro CNAME no seu provedor, adicionar seu domínio na Afrus e usá-lo nas suas landings.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-e-dominios, para-que-servem-os-dominios, como-mudar-a-url-da-minha-landing
--- CUERPO (HTML) ---
<p>Os nomes de tela aparecem como na versão em espanhol do console.</p>
<h2>Antes de começar</h2>
<ul>
<li><strong>Compre o domínio com um provedor.</strong> A Afrus não vende domínios.</li>
<li><strong>Tenha acesso à configuração de DNS</strong> do domínio, ou peça ajuda à sua equipe de TI.</li>
<li><strong>Use um subdomínio</strong> (por exemplo doe.minhaorganizacao.org): a tela só pede um registro CNAME, e muitos provedores não o permitem no domínio principal.</li>
</ul>
<h2>Passo a passo</h2>
<ol>
<li><strong>Crie um registro CNAME no seu provedor.</strong> Nome ou host: seu subdomínio (por exemplo <em>doe</em>). Valor ou destino: <em>landings2.afrus.org</em>. Se a tela da Afrus mostrar outro valor, use sempre o da tela.</li>
<li><strong>Espere a alteração se propagar.</strong> O tempo depende do seu provedor, não da Afrus.</li>
<li><strong>Abra Domínios.</strong> Acesse <strong>Fundraising &gt; Dominios</strong>.</li>
<li><strong>Digite seu domínio.</strong> Em <strong>Agregar dominio personalizado</strong> (Adicionar domínio personalizado), digite o domínio sem http://, https://, barras nem caminhos.</li>
<li><strong>Adicione.</strong> Clique em "Agregar dominio" (Adicionar domínio). Você verá <em>"Dominio registrado con exito"</em> (Domínio cadastrado com sucesso) e o domínio aparecerá na lista como ativo.</li>
<li><strong>Use em uma landing.</strong> Ao criar ou editar uma landing, em <strong>Datos básicos</strong> (Dados básicos), escolha seu domínio em <strong>Dominio</strong>.</li>
</ol>
<p>A Afrus solicita automaticamente o certificado de segurança (HTTPS) e verifica o domínio durante cerca de 15 minutos. Não existe botão "Verificar". Se a verificação falhar, o domínio passa a inativo sozinho. A tela não se atualiza sozinha: recarregue-a para ver o status.</p>
<h2>Perguntas frequentes</h2>
<p><strong>O que significa "Dominio existente, prueba otro"?</strong> Esse domínio já está cadastrado na Afrus; cada domínio é cadastrado uma única vez em toda a plataforma.</p>
<p><strong>O que significa "El dominio no se encuentra apuntando al Host (landings2.afrus.org)"?</strong> Seu registro CNAME ainda não aponta para a Afrus. Confira e espere a propagação.</p>
<p><strong>Meu domínio ficou inativo. O que faço?</strong> Confira o registro CNAME com seu provedor. Se estiver certo e o domínio continuar inativo, fale com o suporte: religar a chave não repete a verificação.</p>
<p><strong>www.minhaorganizacao.org e minhaorganizacao.org são a mesma coisa?</strong> Não. Cada um é cadastrado separadamente e precisa do seu próprio registro DNS.</p>
=== FIN ===
```
