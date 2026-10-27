# Campos personalizados — tutoriales web (afrus.ai/howto)

Un bloque por tutorial, listo para pegar. Orden: español, inglés, portugués.

## Español

```text
=== TUTORIAL ===
Idioma: es
Título: Qué son los campos personalizados
Slug: que-son-los-campos-personalizados
Categoría: Configuración
Resumen: Aprende qué son los campos personalizados: datos extra que tu organización guarda de cada persona en AFRUS.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-sirven-los-campos-personalizados, como-incluir-un-campo-personalizado-en-mi-widget, donde-se-guardan-los-campos-personalizados, donde-ver-los-campos-personalizados
--- CUERPO (HTML) ---
<p><strong>Son datos extra que tu organización quiere guardar de cada persona, además de los que AFRUS ya trae</strong> (nombre, correo, teléfono, documento, dirección…). Por ejemplo: "¿Cómo nos conociste?" o "Área de interés".</p>
<p>Se definen en <strong>Ajustes de Organización &gt; Campos personalizados</strong>.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Para qué sirven los campos personalizados
Slug: para-que-sirven-los-campos-personalizados
Categoría: Configuración
Resumen: Aprende para qué sirven los campos personalizados: pedir datos en tus formularios, verlos en el perfil y usarlos en tus correos.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-los-campos-personalizados, como-incluir-un-campo-personalizado-en-mi-widget, donde-se-guardan-los-campos-personalizados, donde-ver-los-campos-personalizados
--- CUERPO (HTML) ---
<ul>
<li><strong>Conocer mejor a tus donantes.</strong> Guardas la información que es importante para tu organización.</li>
<li><strong>Pedir esos datos en tus formularios.</strong> Puedes agregar el campo a tus formularios de donación o de registro.</li>
<li><strong>Completarlos a mano.</strong> También los llenas al crear o editar una persona.</li>
<li><strong>Usarlos en tus correos.</strong> En los autoresponders puedes insertar el valor de un campo con un merge tag.</li>
<li><strong>Analizarlos fuera de AFRUS.</strong> Cada campo sale como una columna al descargar tu lista de personas.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo incluir un campo personalizado en mi widget
Slug: como-incluir-un-campo-personalizado-en-mi-widget
Categoría: Configuración
Resumen: Aprende a agregar un campo personalizado a tu formulario de donación o de registro para que el donante lo complete.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-los-campos-personalizados, para-que-sirven-los-campos-personalizados, donde-se-guardan-los-campos-personalizados, donde-ver-los-campos-personalizados
--- CUERPO (HTML) ---
<h2>Antes de empezar</h2>
<ul><li><strong>El campo ya tiene que existir</strong> en <strong>Ajustes de Organización &gt; Campos personalizados</strong>.</li></ul>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre el editor del formulario.</strong> En <strong>Fundraising &gt; Widgets</strong>, edita el formulario. El editor se abre en la versión anterior de AFRUS.</li>
<li><strong>Agrega el bloque.</strong> Haz clic en "Agregar" y elige <strong>Campo personalizado</strong>.</li>
<li><strong>Configúralo.</strong> Haz clic sobre el bloque y configúralo en <strong>Configuración del snippet</strong>.</li>
<li><strong>Ordénalo.</strong> Arrástralo hasta el lugar donde quieres que aparezca.</li>
<li><strong>Guarda.</strong> Haz clic en "Guardar Snippet" y después en "Guardar Widget".</li>
</ol>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Puedo pedir varios campos en el mismo formulario?</strong> Sí. Agrega un bloque <strong>Campo personalizado</strong> por cada uno.</p>
<p><strong>Mi formulario tiene varios países, ¿lo agrego en cada uno?</strong> Sí. Cada país tiene su propia lista de bloques.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Dónde se guardan los campos personalizados
Slug: donde-se-guardan-los-campos-personalizados
Categoría: Configuración
Resumen: Aprende dónde queda guardada la información de los campos personalizados que llenan tus donantes o tu equipo.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-los-campos-personalizados, para-que-sirven-los-campos-personalizados, como-incluir-un-campo-personalizado-en-mi-widget, donde-ver-los-campos-personalizados
--- CUERPO (HTML) ---
<p><strong>En el perfil de cada persona, dentro de Personas.</strong> Lo que el donante escribe en el formulario, o lo que tu equipo llena a mano, queda guardado en su perfil.</p>
<p>Los campos se llenan:</p>
<ul>
<li>cuando la persona completa un formulario que tiene el campo;</li>
<li>cuando tu equipo crea una persona con "Crear persona" o la edita, en la sección <strong>Información Personalizada</strong>.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Dónde ver los campos personalizados
Slug: donde-ver-los-campos-personalizados
Categoría: Configuración
Resumen: Aprende dónde ver los campos personalizados: en el perfil de la persona, en la descarga de personas y en tus correos.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-los-campos-personalizados, para-que-sirven-los-campos-personalizados, como-incluir-un-campo-personalizado-en-mi-widget, donde-se-guardan-los-campos-personalizados
--- CUERPO (HTML) ---
<ol>
<li><strong>En el perfil de la persona.</strong> Abre la persona en <strong>Personas</strong>, pestaña <strong>Contacto</strong>, tarjeta <strong>Más información</strong>, sección <strong>Información Personalizada</strong>. La sección solo aparece si la persona tiene algún campo personalizado.</li>
<li><strong>En la descarga de personas.</strong> Al descargar con <strong>Base de datos en tiempo real</strong>, cada campo sale en su propia columna.</li>
<li><strong>En tus correos.</strong> En un autoresponder puedes mostrar el valor con el merge tag <em>{{customFields.&lt;campo&gt;}}</em>, cambiando &lt;campo&gt; por el nombre de tu campo.</li>
</ol>
<p><strong>Ojo:</strong> en las landings, los campos personalizados no funcionan como variables: el donante vería el texto tal cual.</p>
=== FIN ===
```

## English

```text
=== TUTORIAL ===
Idioma: en
Título: What custom fields are
Slug: what-are-custom-fields
Categoría: Configuración
Resumen: Learn what custom fields are: extra details your organization keeps about each person in AFRUS.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-custom-fields-for, how-to-add-a-custom-field-to-my-widget, where-custom-fields-are-stored, where-to-see-custom-fields
--- CUERPO (HTML) ---
<p><strong>They are extra details your organization wants to keep about each person, on top of the ones AFRUS already has</strong> (name, email, phone, ID, address…). For example: "How did you hear about us?" or "Area of interest". Labels are shown as they appear in the Spanish version of the console.</p>
<p>They are defined in <strong>Ajustes de Organización &gt; Campos personalizados</strong> (Organization settings &gt; Custom fields).</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: What custom fields are for
Slug: what-are-custom-fields-for
Categoría: Configuración
Resumen: Learn what custom fields are for: asking for details in your forms, seeing them in the profile and using them in your emails.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-custom-fields, how-to-add-a-custom-field-to-my-widget, where-custom-fields-are-stored, where-to-see-custom-fields
--- CUERPO (HTML) ---
<ul>
<li><strong>Knowing your donors better.</strong> You keep the information that matters to your organization.</li>
<li><strong>Asking for them in your forms.</strong> You can add the field to your donation or registration forms.</li>
<li><strong>Filling them in by hand.</strong> You can also fill them in when you create or edit a person.</li>
<li><strong>Using them in your emails.</strong> In autoresponders you can insert a field's value with a merge tag.</li>
<li><strong>Analyzing them outside AFRUS.</strong> Each field comes out as a column when you download your list of people.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to add a custom field to my widget
Slug: how-to-add-a-custom-field-to-my-widget
Categoría: Configuración
Resumen: Learn how to add a custom field to your donation or registration form so donors fill it in.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-custom-fields, what-are-custom-fields-for, where-custom-fields-are-stored, where-to-see-custom-fields
--- CUERPO (HTML) ---
<p>Labels are shown as they appear in the Spanish version of the console.</p>
<h2>Before you start</h2>
<ul><li><strong>The field must already exist</strong> in <strong>Ajustes de Organización &gt; Campos personalizados</strong>.</li></ul>
<h2>Step by step</h2>
<ol>
<li><strong>Open the form editor.</strong> In <strong>Fundraising &gt; Widgets</strong>, edit the form. The editor opens in the previous version of AFRUS.</li>
<li><strong>Add the block.</strong> Click "Agregar" (Add) and choose <strong>Campo personalizado</strong> (Custom field).</li>
<li><strong>Set it up.</strong> Click the block and set it up in <strong>Configuración del snippet</strong> (Snippet settings).</li>
<li><strong>Place it.</strong> Drag it to where you want it to appear.</li>
<li><strong>Save.</strong> Click "Guardar Snippet" (Save snippet) and then "Guardar Widget" (Save widget).</li>
</ol>
<h2>Frequently asked questions</h2>
<p><strong>Can I ask for several fields in the same form?</strong> Yes. Add one <strong>Campo personalizado</strong> block for each.</p>
<p><strong>My form has several countries. Do I add it in each one?</strong> Yes. Each country has its own list of blocks.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: Where custom fields are stored
Slug: where-custom-fields-are-stored
Categoría: Configuración
Resumen: Learn where the information from custom fields filled in by donors or your team is stored.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-custom-fields, what-are-custom-fields-for, how-to-add-a-custom-field-to-my-widget, where-to-see-custom-fields
--- CUERPO (HTML) ---
<p><strong>In each person's profile, in Personas (People).</strong> What the donor writes in the form, or what your team fills in by hand, is saved in their profile. Labels are shown as they appear in the Spanish version of the console.</p>
<p>Fields are filled in:</p>
<ul>
<li>when the person completes a form that has the field;</li>
<li>when your team creates a person with "Crear persona" (Create person) or edits one, in the <strong>Información Personalizada</strong> (Custom information) section.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: Where to see custom fields
Slug: where-to-see-custom-fields
Categoría: Configuración
Resumen: Learn where to see custom fields: in the person's profile, in the people download and in your emails.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-custom-fields, what-are-custom-fields-for, how-to-add-a-custom-field-to-my-widget, where-custom-fields-are-stored
--- CUERPO (HTML) ---
<p>Labels are shown as they appear in the Spanish version of the console.</p>
<ol>
<li><strong>In the person's profile.</strong> Open the person in <strong>Personas</strong>, <strong>Contacto</strong> (Contact) tab, <strong>Más información</strong> (More information) card, <strong>Información Personalizada</strong> section. The section only appears if the person has a custom field.</li>
<li><strong>In the people download.</strong> When you download with <strong>Base de datos en tiempo real</strong> (Real-time database), each field comes out in its own column.</li>
<li><strong>In your emails.</strong> In an autoresponder you can show the value with the merge tag <em>{{customFields.&lt;field&gt;}}</em>, replacing &lt;field&gt; with your field's name.</li>
</ol>
<p><strong>Note:</strong> in landings, custom fields don't work as variables: the donor would see the text as is.</p>
=== FIN ===
```

## Português

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: O que são os campos personalizados
Slug: o-que-sao-os-campos-personalizados
Categoría: Configuración
Resumen: Aprenda o que são os campos personalizados: dados extras que sua organização guarda de cada pessoa na AFRUS.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-servem-os-campos-personalizados, como-incluir-um-campo-personalizado-no-meu-widget, onde-ficam-salvos-os-campos-personalizados, onde-ver-os-campos-personalizados
--- CUERPO (HTML) ---
<p><strong>São dados extras que sua organização quer guardar de cada pessoa, além dos que a AFRUS já tem</strong> (nome, e-mail, telefone, documento, endereço…). Por exemplo: "Como você nos conheceu?" ou "Área de interesse". Os nomes de tela aparecem como na versão em espanhol do console.</p>
<p>Eles são definidos em <strong>Ajustes de Organización &gt; Campos personalizados</strong> (Ajustes da organização &gt; Campos personalizados).</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Para que servem os campos personalizados
Slug: para-que-servem-os-campos-personalizados
Categoría: Configuración
Resumen: Aprenda para que servem os campos personalizados: pedir dados nos formulários, vê-los no perfil e usá-los nos seus e-mails.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-os-campos-personalizados, como-incluir-um-campo-personalizado-no-meu-widget, onde-ficam-salvos-os-campos-personalizados, onde-ver-os-campos-personalizados
--- CUERPO (HTML) ---
<ul>
<li><strong>Conhecer melhor seus doadores.</strong> Você guarda as informações importantes para sua organização.</li>
<li><strong>Pedir esses dados nos seus formulários.</strong> Você pode adicionar o campo aos formulários de doação ou de cadastro.</li>
<li><strong>Preenchê-los à mão.</strong> Você também os preenche ao criar ou editar uma pessoa.</li>
<li><strong>Usá-los nos seus e-mails.</strong> Nos autoresponders você pode inserir o valor de um campo com um merge tag.</li>
<li><strong>Analisá-los fora da AFRUS.</strong> Cada campo sai como uma coluna ao baixar sua lista de pessoas.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como incluir um campo personalizado no meu widget
Slug: como-incluir-um-campo-personalizado-no-meu-widget
Categoría: Configuración
Resumen: Aprenda a adicionar um campo personalizado ao seu formulário de doação ou de cadastro para que o doador o preencha.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-os-campos-personalizados, para-que-servem-os-campos-personalizados, onde-ficam-salvos-os-campos-personalizados, onde-ver-os-campos-personalizados
--- CUERPO (HTML) ---
<p>Os nomes de tela aparecem como na versão em espanhol do console.</p>
<h2>Antes de começar</h2>
<ul><li><strong>O campo já precisa existir</strong> em <strong>Ajustes de Organización &gt; Campos personalizados</strong>.</li></ul>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra o editor do formulário.</strong> Em <strong>Fundraising &gt; Widgets</strong>, edite o formulário. O editor abre na versão anterior da AFRUS.</li>
<li><strong>Adicione o bloco.</strong> Clique em "Agregar" (Adicionar) e escolha <strong>Campo personalizado</strong>.</li>
<li><strong>Configure.</strong> Clique no bloco e configure-o em <strong>Configuración del snippet</strong> (Configuração do snippet).</li>
<li><strong>Posicione.</strong> Arraste-o até o lugar onde quer que apareça.</li>
<li><strong>Salve.</strong> Clique em "Guardar Snippet" (Salvar snippet) e depois em "Guardar Widget" (Salvar widget).</li>
</ol>
<h2>Perguntas frequentes</h2>
<p><strong>Posso pedir vários campos no mesmo formulário?</strong> Sim. Adicione um bloco <strong>Campo personalizado</strong> para cada um.</p>
<p><strong>Meu formulário tem vários países. Adiciono em cada um?</strong> Sim. Cada país tem sua própria lista de blocos.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Onde ficam salvos os campos personalizados
Slug: onde-ficam-salvos-os-campos-personalizados
Categoría: Configuración
Resumen: Aprenda onde ficam salvas as informações dos campos personalizados preenchidos pelos doadores ou pela sua equipe.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-os-campos-personalizados, para-que-servem-os-campos-personalizados, como-incluir-um-campo-personalizado-no-meu-widget, onde-ver-os-campos-personalizados
--- CUERPO (HTML) ---
<p><strong>No perfil de cada pessoa, em Personas (Pessoas).</strong> O que o doador escreve no formulário, ou o que sua equipe preenche à mão, fica salvo no perfil dele. Os nomes de tela aparecem como na versão em espanhol do console.</p>
<p>Os campos são preenchidos:</p>
<ul>
<li>quando a pessoa completa um formulário que tem o campo;</li>
<li>quando sua equipe cria uma pessoa com "Crear persona" (Criar pessoa) ou a edita, na seção <strong>Información Personalizada</strong> (Informação personalizada).</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Onde ver os campos personalizados
Slug: onde-ver-os-campos-personalizados
Categoría: Configuración
Resumen: Aprenda onde ver os campos personalizados: no perfil da pessoa, no download de pessoas e nos seus e-mails.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-os-campos-personalizados, para-que-servem-os-campos-personalizados, como-incluir-um-campo-personalizado-no-meu-widget, onde-ficam-salvos-os-campos-personalizados
--- CUERPO (HTML) ---
<p>Os nomes de tela aparecem como na versão em espanhol do console.</p>
<ol>
<li><strong>No perfil da pessoa.</strong> Abra a pessoa em <strong>Personas</strong>, aba <strong>Contacto</strong> (Contato), cartão <strong>Más información</strong> (Mais informações), seção <strong>Información Personalizada</strong>. A seção só aparece se a pessoa tiver algum campo personalizado.</li>
<li><strong>No download de pessoas.</strong> Ao baixar com <strong>Base de datos en tiempo real</strong> (Base de dados em tempo real), cada campo sai em uma coluna própria.</li>
<li><strong>Nos seus e-mails.</strong> Em um autoresponder você pode mostrar o valor com o merge tag <em>{{customFields.&lt;campo&gt;}}</em>, trocando &lt;campo&gt; pelo nome do seu campo.</li>
</ol>
<p><strong>Atenção:</strong> nas landings, os campos personalizados não funcionam como variáveis: o doador veria o texto como está.</p>
=== FIN ===
```

