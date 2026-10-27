# Guia de Landings

Depois de ler este guia, você vai saber criar e publicar landing pages na AFRUS, colocar um widget nelas, acompanhá-las com analytics, usá-las como página de agradecimento e mudar o endereço delas.

*Módulo: Landings · Menu: **Fundraising > Landings** · Público: equipes de captação, marketing digital e comunicação*

> **Sobre os nomes de tela neste guia:** botões, campos e menus estão escritos exatamente como aparecem na versão em espanhol do console, com a explicação em português quando ajuda.

---

## O que é Landings

**Landings é o módulo da AFRUS para criar e publicar landing pages: páginas web de campanha, de doação ou de agradecimento.** Você as monta com um editor visual de arrastar e soltar, a partir de um modelo, de uma página sua anterior ou do seu próprio código HTML.

Cada landing é publicada no endereço da AFRUS (`web.afrus.org`) ou em um domínio próprio da sua organização, por exemplo `doe.minhaorganizacao.org`.

## Para que serve

- **Publicar páginas de campanha sem programar**, com um widget de doação ou de cadastro incorporado.
- **Agradecer de forma pessoal.** Uma landing pode ser sua página de agradecimento, com o nome do doador, o valor e a campanha.
- **Medir suas visitas** com Google Analytics, Google Tag Manager ou o Pixel da Meta (Facebook), e **melhorar o SEO** com meta título, descrição, palavras-chave e imagem para redes.
- **Usar seu próprio endereço web**, com um domínio cadastrado em **Fundraising > Dominios**.
- **Reaproveitar seu trabalho:** clonar landings e passar as landings clássicas para a versão 2.0.
- **Testar o que funciona melhor** com testes A/B (botão "Experimentos"). Veja o [guia de experimentos de landings](../landing-experiments/ab-testing-guide.md).

## Antes de começar

- **Acesso ao menu Fundraising.** Se você vê **Fundraising > Landings**, pode usar o módulo.
- **Para incorporar um formulário, tenha um widget ativo.** Só os widgets ativos aparecem na lista.
- **Para usar seu domínio,** cadastre-o antes em **Fundraising > Dominios** e espere até que esteja ativo.

---

# Passo a passo

## Como criar uma landing

### Parte 1 — Dados básicos

1. **Abra o módulo.** Acesse **Fundraising > Landings** e clique em "Nueva landing" (Nova landing).
   ![Lista de landings com o botão Nueva landing](img/como-crear-una-landing-01.webp)

2. **Preencha os dados básicos.** Na aba **Datos básicos** (Dados básicos), preencha:
   - **Nombre interno** (nome interno): só você vê; ajuda a encontrar a landing na lista.
   - **Título de la página** (título da página): o que aparece na aba do navegador (até 255 caracteres).
   - **Dominio** (domínio): `web.afrus.org` por padrão; seus domínios próprios ativos também aparecem.
   - **Ruta** (caminho): a parte final do endereço, por exemplo `/minha-campanha`.
   - Opcional: **Icono landing page (favicon)** com o botão "Subir" (Enviar) — jpg, png ou svg, até 1 MB; recomendado 16 × 16 pixels.

   O caminho deve começar com `/`, sem espaços (são trocados por hífens automaticamente), só com letras sem acento, números, `/` e `-`, e sem `//` seguidos.

3. **Decida se fica ativa.** Deixe ou desative a chave **Activar landing** (Ativar landing).

4. **Salve.** Clique em "Guardar" (Salvar) ou passe para a aba **Landing page**: nesse momento a landing é criada e você verá *"Landing creada exitosamente"* (Landing criada com sucesso). A aba **Landing page** fica disponível quando nome interno, título e caminho estão preenchidos e o caminho começa com `/`.

### Parte 2 — Design

5. **Escolha como começar o design.** A aba **Landing page** tem quatro opções:
   - **Página de cero** (Página em branco): clique em "Crear página" (Criar página) para abrir o editor visual vazio.
   - **Mis páginas** (Minhas páginas): suas landings 2.0; clique em "Usar" para abrir o editor com uma cópia desse design.
   - **Plantillas** (Modelos): galeria de designs prontos; clique em "Usar plantilla" (Usar modelo).
   - **HTML**: cole seu próprio código em **Ingresar HTML** (Inserir HTML), confira com "Vista previa" (Pré-visualização) e clique em "Guardar".
   <!-- captura pendente: como-criar-uma-landing-05 — aba Landing page com os quatro cartões -->

6. **Monte e salve.** No editor visual, monte sua página e clique em "Guardar" (*"Landing page HTML guardada con éxito"*, salva com sucesso). "Ver" abre a página publicada em outra aba.

   > **Importante:** "Volver" (Voltar) retorna à edição da landing **sem salvar** o design. Salve antes de sair.

7. **Configure analytics e SEO (opcional).** A aba **Datos avanzados** (Dados avançados) fica disponível depois de visitar **Landing page**. Veja a próxima seção.

Ao terminar, sua página fica publicada em `https://<domínio><caminho>`, por exemplo `https://web.afrus.org/minha-campanha`. Não existe um botão "Publicar" separado: **salvar o design é publicar**. Na lista, "Copiar link" copia esse endereço.

> **Importante:** enquanto você não salvar um design, a landing existe, mas não tem página publicada; o ícone de olho e "Copiar link" ficam desativados.

**Outras ações da lista:**
- **Clonar** (menu de três pontos, landings 2.0): cria uma cópia com nome e caminho terminados em `-copy-N`, no mesmo domínio, e publica a página.
- **Clonar a 2.0** (Clonar para 2.0; landings **Clásica**): as landings clássicas não são editadas aqui; este botão cria uma cópia 2.0 ativa em `web.afrus.org`, com nome, título e caminho terminados em `-copy-AAAAMMDD`.
- **Status**: desligar a chave retira a página do endereço; ligar publica de novo com o último design salvo.
- **Borrar** (Excluir): exclui a landing e sua página publicada.

> **Dá para desfazer?** Excluir uma landing, não: a tela avisa *"Esta acción no se puede deshacer."* (Esta ação não pode ser desfeita.) Desligar o **Status**, sim: é só ligar de novo.

## Como acompanhar minha landing com analytics

A AFRUS adiciona à sua página o código do Google Analytics ou do Google Tag Manager e o Pixel da Meta. As visitas e conversões são medidas **nessas ferramentas**, não dentro da AFRUS.

**Antes de começar:** a landing precisa ter um design salvo. Se não tiver, ao salvar você verá *"Error al guardar datos avanzados"* (Erro ao salvar dados avançados).

1. **Abra a landing.** Em **Fundraising > Landings**, clique no lápis da landing e vá até a aba **Datos avanzados**.
   ![Aba Datos avanzados com a seção Analytics](img/como-hacer-seguimiento-con-analitica-a-mi-landing-01.webp)

2. **Escolha sua ferramenta de analytics.** Na seção **Analytics**, em **Analytics track**, escolha **Google Analytics** ou **Google Tag Manager V4** e digite o ID em **Google Analytics ID** (formato `G-XXXXXXXXXX` ou `UA-XXXXX-Y`) ou em **Google Tag Manager V4 ID** (formato `GTM-XXXXXX`).

3. **Adicione seu Pixel da Meta.** Em **Facebook Pixel**, digite o ID do seu pixel (15 ou 16 dígitos). Assim você mede as visitas que chegam pelos seus anúncios.

4. **Melhore o SEO (opcional).** Na seção **SEO**, preencha **Meta Title** (60 caracteres recomendados), **Meta Description** (160), **Palabras clave** (palavras-chave; digite e pressione Enter), **Meta Robots Avanzado** e **Subir foto destacada** (foto em destaque; jpg, gif, webp ou png; até 500 KB; recomendado 1200 × 628). Confira o resultado em **Vista previa en buscadores** (pré-visualização nos buscadores).

5. **Adicione código próprio (opcional).** Em **Custom Code**, clique em "Agregar HTML" (Adicionar HTML) para colar seus scripts (até 10 blocos), escolhendo **Head** ou **Body** em cada um.

6. **Salve.** Clique em "Guardar Cambios" (Salvar alterações) ou em "Guardar" no topo. Você verá *"Datos avanzados y bloques de código guardados con éxito"* (salvos com sucesso).

Ao terminar, a AFRUS publica a página de novo com seu código de analytics, o Pixel, as tags de SEO e seus blocos de código.

> **Importante:** você só pode usar **um** dos dois, Google Analytics **ou** Google Tag Manager; trocar o tipo apaga o ID digitado. Se precisar dos dois, carregue um como bloco em **Custom Code** ou pelo Google Tag Manager.

Se o formato de um ID não for válido, ele não é salvo e você verá *"ID de Google Analytics no válido"*, *"ID de Google Tag Manager no válido"* ou *"El ID de Pixel debe tener entre 15 y 16 dígitos"* (o ID do Pixel deve ter 15 ou 16 dígitos). Um bloco de código vazio também impede salvar.

## Como colocar um widget em uma landing

**Antes de começar:** tenha um widget **ativo**; só esses aparecem na lista.

1. **Abra o editor visual.** Na aba **Landing page** da sua landing, crie a página (**Página de cero** > "Crear página") ou clique em "Editar" no design existente.

2. **Escolha o widget.** Na barra superior, em **Seleccionar widget** (Selecionar widget), escolha o widget pelo nome. A AFRUS copia o código dele e você verá *"Código del widget copiado al portapapeles"* (Código do widget copiado para a área de transferência).
   ![Barra do editor de landing pages com o seletor Seleccionar widget](img/como-poner-un-widget-en-una-landing-02.webp)

3. **Cole o código em um bloco HTML.** Arraste para a tela um bloco **HTML** do painel de ferramentas e cole o código ali.

   > **Importante:** escolher o widget não o insere sozinho. Sempre é preciso colar o código em um bloco HTML.

4. **Salve.** Clique em "Guardar".

Ao terminar, o widget aparece dentro da página publicada, igual a qualquer site onde você o incorpora.

Os formulários sempre são adicionados como widget da AFRUS: a ferramenta de formulário do próprio editor está desativada. Se você montou sua landing com a opção **HTML**, não há seletor: cole à mão o código de incorporação do widget.

## Para que criar uma página de agradecimento

Uma landing de agradecimento mostra ao doador, logo depois de doar, **uma página própria da sua organização** com seu design, sua mensagem e suas chamadas para ação, em vez da página padrão. Você ainda pode personalizá-la com os dados dele: nome, valor e campanha. É a sua primeira oportunidade de fidelizar quem acabou de doar.

**Antes de começar:** você precisa de uma landing 2.0 ativa e com design salvo.

1. **Crie a landing de agradecimento.** Siga "Como criar uma landing".

2. **Personalize o texto.** Nos blocos de texto do editor visual, escreva estas variáveis exatamente assim, com chaves duplas:

   | Variável | Mostra |
   |---|---|
   | `{{first_name}}` | Nome do doador |
   | `{{last_name}}` | Sobrenome |
   | `{{email}}` | E-mail |
   | `{{phone}}` | Telefone |
   | `{{amount}}` | Valor (só o número, ex. 250.00) |
   | `{{currency}}` | Moeda (código, ex. BRL) |
   | `{{campaign_name}}` | Nome da campanha |
   | `{{organization_name}}` | Nome da organização |
   | `{{donation_id}}` | ID da doação |

   Por exemplo: *"Obrigado, {{first_name}}. Sua doação de {{amount}} {{currency}} para {{campaign_name}} já está fazendo a diferença."*

3. **Salve.** Clique em "Guardar" no editor; isso publica a página com a personalização ativada.

4. **Indique onde ela é usada como agradecimento.** Escolha uma destas duas formas:
   - **Pela campanha:** na seção **Página de agradecimiento** (Página de agradecimento) da campanha, escolha **Tipo** = **Landings**, depois **Elegir una landing** (Escolher uma landing), confira a pré-visualização e clique em "Usar plantilla" (salva sem mostrar mensagem). Além disso, no editor do widget, no painel **Pagina de agradecimiento**, marque **Usa la página de agradecimiento de la campaña.** (Usa a página de agradecimento da campanha). Sem essa caixa, o widget não usa a página da campanha.
   - **Pelo widget:** em **URL de la página de agradecimiento** (URL da página de agradecimento), cole o link da landing ("Copiar link" na lista de landings).

5. **Teste com uma doação real.** Assim você confirma que o doador chega à sua página e vê os dados dele.

Ao terminar, depois de uma doação com sucesso, o doador chega à sua landing com os dados já preenchidos.

**Lembre-se:**
- **Só essas nove variáveis funcionam.** Qualquer outra (por exemplo `{{campaign}}`, campos personalizados ou variáveis dos e-mails) aparece do jeito que está, com as chaves. O botão "Merge tags" do editor mostra o catálogo completo de variáveis da AFRUS, mas a maioria **não** funciona em landings.
- **Só no texto do corpo.** Não funcionam no título da página, na meta descrição, nos links de botões, nos textos alternativos de imagens nem nos valores de campos.
- **Quando aparecem em branco.** Se o pagamento precisa de uma etapa posterior (verificação 3-D Secure, ou métodos com confirmação posterior como OXXO, PSE ou SEPA), ou se alguém abre a página diretamente, recarrega depois de 15 minutos ou a compartilha, as variáveis aparecem vazias. Escreva seus textos para que funcionem bem assim também.
- Enquanto a página carrega os dados, o texto `{{...}}` pode aparecer por um instante.
- Só as landings 2.0 são personalizadas; as clássicas não.
- Se você desativar a landing ou mudar o caminho dela, o doador não a verá. Se colou o link no widget, atualize-o.

## Como mudar a URL da minha landing

**Antes de começar:** a landing precisa ser 2.0 e ter um design salvo. Se nunca salvou um design, você verá *"Error al actualizar datos"* (Erro ao atualizar dados) e nada é publicado.

1. **Abra a landing.** Em **Fundraising > Landings**, clique no lápis da landing e vá até a aba **Datos básicos**.

2. **Mude o endereço.** Altere a **Ruta** (caminho), o **Dominio** (domínio) ou os dois. Para usar seu próprio domínio, cadastre-o antes em **Fundraising > Dominios**. Com domínio próprio, você pode usar o caminho `/` para que a landing seja a página principal do domínio.
   ![Aba Datos básicos com os campos Dominio e Ruta](img/como-cambiar-la-url-de-mi-landing-02.webp)

3. **Salve.** Clique em "Guardar". Você verá *"Datos actualizados con éxito"* (Dados atualizados com sucesso).

Ao terminar, a página é publicada no novo endereço `https://<domínio><caminho>`.

> **Dá para desfazer?** Você pode voltar ao endereço anterior, mas enquanto isso **o link antigo deixa de funcionar e não redireciona para o novo**. Atualize todos os lugares onde você o colou: widgets, e-mails, anúncios e redes.

> **Importante:** a AFRUS não verifica se o caminho está livre. Se duas landings usarem o mesmo domínio e o mesmo caminho, nesse endereço aparece a última que foi salva. Use sempre caminhos únicos.

---

## Status e colunas da lista

| Elemento | Valores | O que significa |
|---|---|---|
| **Status** | ligado / desligado | Ligado: página publicada. Desligado: a página é retirada do endereço. |
| **Versión** | **2.0** / **Clásica** | 2.0: criada com o editor atual (editável e clonável). Clásica (Clássica): criada na versão anterior (só ver ou "Clonar a 2.0"). |
| **Filtrar por campaña** (Filtrar por campanha) | campanhas | Mostra as landings que têm incorporado um widget dessa campanha. Não se combina com o período nem com a busca por URL. |
| Busca **Nombre** / **URL** | texto | **Nombre** busca pelo nome interno; **URL** busca pelo nome ou caminho. |

**Outras ferramentas do editor visual:**
- **Fuentes personalizadas** (Fontes personalizadas): adicione fontes do Google Fonts (nome e URL). Recarregue a página para vê-las.
- **CSS personalizado:** crie estilos e atribua-os à landing. Também exige recarregar.
- **Indicadores de impacto:** lista os KPIs configurados nas suas campanhas com uma variável entre colchetes que você copia e cola no design; na página publicada, ela é trocada pelo valor calculado. Os KPIs são criados na configuração da campanha.

## Perguntas frequentes

**Preciso clicar em um botão para publicar?**
Não. Salvar o design no editor (ou na opção HTML) publica a página.

**Posso usar Google Analytics e Google Tag Manager ao mesmo tempo?**
Não pelo seletor: só um. Carregue o outro como bloco em **Custom Code** ou pelo Google Tag Manager.

**Onde vejo quantas visitas minha landing teve?**
Na sua ferramenta de analytics (Google Analytics, Google Tag Manager ou Meta). A AFRUS não tem uma tela de estatísticas por landing.

**Posso editar uma landing clássica?**
Não. Use "Clonar a 2.0" para criar uma cópia editável.

**Mudei a URL e o link antigo não funciona mais. É normal?**
Sim. A página é retirada do endereço anterior e não redireciona. Compartilhe o link novo.

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-27*
