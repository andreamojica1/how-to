# Guia de Agentes para o site (Agentes para la web)

Com este guia você vai poder criar um chat com IA para o seu site, que responde aos visitantes com as informações da sua organização.

*Módulo: AI · Menu: **AI > Agentes para la web** · Público: equipes de comunicação e captação, e quem administra o site*

> **Sobre os nomes de tela neste guia:** botões, campos e menus estão escritos como aparecem na versão em espanhol do console, com a explicação em português quando ajuda.

---

## O que são os Agentes para o site

**Um agente é um chat com IA que você instala no seu próprio site.** O visitante deixa nome e e-mail e conversa com um assistente que responde com as informações que a sua organização enviou para a Afrus.

<!-- captura pendente: agentes-para-la-web-01 — lista Agentes IA com o botão Nuevo agente -->

## Para que servem

- **Responder às dúvidas dos visitantes a qualquer hora.** Por exemplo, o que a sua organização faz ou como doar.
- **Levá-los a agir.** O chat mostra um botão que leva aonde você quiser, como o seu formulário de doação.
- **Somar contatos à sua base.** Quem conversa fica registrado como pessoa na Afrus.
- **Saber o que as pessoas perguntam.** Você pode revisar depois as conversas e o resumo delas.

## Antes de começar

- **Ative a IA da Afrus** pelo **Business profile** (menu de perfil): crie seu perfil e clique em "Enviar AI" (enviar para a IA).
- **Envie pelo menos um documento em AI > Entrenamiento [AI RAG].** Sem documentos, o agente não pode ser salvo.
- **Tenha por perto quem administra o seu site,** para colar o código do chat.

---

# Passo a passo

## Como usar os Agentes para o site

### Parte 1 — Crie o agente

1. **Crie um agente novo.** Acesse **AI > Agentes para la web** e clique em "Nuevo agente" (Novo agente).

2. **Preencha a configuração.** Na aba **Configuración del Agente** (Configuração do agente), preencha:
   - **Nombre del agente** (nome do agente, obrigatório).
   - **Texto call to action**: o texto do botão, por exemplo "Doe aqui" (até 20 caracteres).
   - **URL del call to action**: para onde o botão leva, por exemplo seu formulário de doação (obrigatório).
   - **Descripción breve de la organización** (descrição breve da organização, obrigatória, até 200 caracteres).
   - **Comportamiento del agente** (comportamento do agente): **Cerrado** (Fechado) ou **Abierto** (Aberto).
   - **Instrucciones para el agente IA** (instruções para o agente de IA, obrigatórias): como você quer que ele fale e o que deve priorizar.
   <!-- captura pendente: agentes-para-la-web-02 — formulário Configuración del Agente com a pré-visualização à direita -->

   > **Importante:** mesmo que a tela deixe salvar com **Texto call to action** vazio, a Afrus recusa. Escreva sempre um texto para o botão.

3. **Melhore os textos (opcional).** "Mejorar respuesta" (Melhorar resposta), ao lado da descrição ou das instruções, reescreve seu texto com IA.

4. **Veja como fica.** À direita você tem uma pré-visualização em modo claro ou escuro (**Light** / **Dark**). Na aba **Organización** você verá o **Resumen de la organización** (resumo da organização), que a Afrus monta sozinha com seus documentos.

5. **Salve.** Deixe ligado **Activar configuración** (Ativar configuração) e clique em "Guardar" (Salvar). O botão fica ativo quando os campos obrigatórios estão preenchidos. Você verá *"Configuración creada correctamente"* (Configuração criada com sucesso).

> **Pendente de confirmação:** o que muda entre **Cerrado** e **Abierto**, e se o chat do seu site usa as instruções e a descrição de cada agente.

### Parte 2 — Instale no seu site

6. **Copie o código.** Na lista de agentes, clique em "Copiar codigo" (Copiar código) na linha do agente. Você verá *"Código copiado al portapapeles"* (Código copiado para a área de transferência). Também o encontra ao editar o agente, em "Copiar código de inserción" (Copiar código de incorporação).
   <!-- captura pendente: agentes-para-la-web-06 — linha do agente com o botão Copiar codigo -->

7. **Cole no seu site.** Entregue o código a quem administra o seu site para colá-lo nas páginas. A partir daí, o chat aparece para os seus visitantes.

### Parte 3 — Administre seus agentes

- **Ativar ou desativar:** use a chave **Estado** (Status) da linha.
- **Duplicar:** o ícone "Duplicar configuración" (Duplicar configuração) cria uma cópia **inativa**. A cópia não traz o comportamento nem o tema de cores: revise-os antes de ativá-la.
- **Excluir:** no menu de três pontos, escolha "Eliminar" (Excluir) e confirme.

> **Dá para desfazer?** Não. Excluir um agente é definitivo. Se só quiser pausá-lo, desative-o com a chave **Estado**.

### O que acontece quando alguém usa o chat

- O visitante escreve o **nome** e o **e-mail** (obrigatórios) e, se quiser, o telefone.
- Se o e-mail já está na sua base, a Afrus reconhece a pessoa. Se não, cria uma pessoa nova (como cadastro, não como doador).
- A IA responde com seus documentos e instruções do **Entrenamiento [AI RAG]** e com as informações do seu **Business profile** (descrição, "Sobre nosotros"/Sobre nós e perguntas frequentes).
- Cada resposta pode levar entre 30 segundos e 2 minutos.

### Como ver as conversas

Hoje as conversas não têm um botão no menu. Para vê-las, digite este endereço no navegador com sua sessão da Afrus aberta: `console.afrus.app/iachat-conversations-index`.

Lá você verá cada conversa com o e-mail, a data, o agente e um resumo. "Ver conversación" (Ver conversa) abre todas as mensagens e os dados de contato do visitante.

<!-- captura pendente: agentes-para-la-web-08 — lista de conversas com ID, Email, Fecha, Agente e Resumen -->

---

## Limitações conhecidas

- **As conversas não têm link no menu.** Use o endereço indicado acima.
- **Texto do botão:** o contador diz 20 caracteres, mas a mensagem de erro fala em 30. Use 20 ou menos.
- **Se um agente não carregar ao editá-lo,** a tela não volta sozinha para a lista: use "Volver a agentes" (Voltar para agentes).
- **As pessoas que chegam pelo chat** são criadas sem aceite dos termos e ficam associadas ao seu formulário e à sua campanha padrão.

## Perguntas frequentes

**O que o visitante vê se eu desativar o agente?**
> **Pendente de confirmação.**

**As conversas gastam créditos?**
> **Pendente de confirmação.**

**A mesma pessoa pode ter várias conversas?**
Não. Cada pessoa tem uma única conversa por agente.

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-26*
