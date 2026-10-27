# Guia de Tarefas de assinaturas

Depois de ler este guia, você vai saber o que são as Tarefas de assinaturas, quando elas aparecem, o que significa cada status e como gerenciá-las para recuperar seus doadores recorrentes.

*Módulo: Follow up · Menu: **Follow up > Tareas de suscripciones** · Público: equipes de relacionamento com doadores e captação*

> **Sobre os nomes de tela neste guia:** botões, campos e menus estão escritos exatamente como aparecem na versão em espanhol do console, com a explicação em português quando ajuda.

---

## O que são as Tarefas de assinaturas

**As Tarefas de assinaturas são uma lista de acompanhamento que a AFRUS cria automaticamente quando a cobrança de uma assinatura falha.** Cada tarefa é um caso para sua equipe entrar em contato com o doador e recuperar a doação recorrente.

A tela se chama **Tareas de Suscripciones** (Tarefas de assinaturas) e mostra, para cada caso, a assinatura, o valor, o gateway de pagamento, a pessoa, o responsável e a data.

## Para que serve

- **Ver em um só lugar as cobranças recorrentes que falharam.** Você não precisa procurar caso a caso em **Suscripciones** (Assinaturas).
- **Dividir o trabalho.** Atribua cada caso a um **Responsable** (responsável) da sua equipe.
- **Controlar o que já foi resolvido.** Marque a tarefa como **Completada** (Concluída) quando terminar.
- **Ter o contexto à mão.** Você vê **Monto** (valor), **Pasarela** (gateway), **Persona** (pessoa) e **Razón de fallo** (motivo da falha), e abre a assinatura pela coluna **Suscripción**.
- **Trabalhar a lista fora da AFRUS.** Exporte todas as tarefas ou uma seleção; o arquivo fica em **Descargas** (Downloads).

## Antes de começar

- **Só vale para assinaturas.** As tarefas são criadas quando falha a cobrança de uma doação recorrente, não de uma doação única.
- **Gateways exibidos.** Esta tela mostra as tarefas de assinaturas com gateway **Recurrent Payments** ou **PTESA**.

---

# Passo a passo

## Com que frequência é atualizado

- **As tarefas são criadas na hora.** A AFRUS cria a tarefa assim que processa a cobrança que falhou; não espera uma revisão diária.
- **Quando uma tarefa nova é criada**, os usuários com papel owner ou admin da sua organização recebem uma notificação na AFRUS.
- **Se a assinatura já tinha uma tarefa**, a AFRUS não cria outra: reabre a existente (volta para **Pendiente**, Pendente) e remove o **Responsable**, para que alguém a retome.
- **A tela não se atualiza sozinha.** Os dados são carregados ao abrir e ao mudar datas, busca, filtro, ordem ou página. Se você espera um caso novo, recarregue a página.

## Quando a assinatura volta a ser cobrada com sucesso, a tarefa sai da lista?

**Não.** Quando a assinatura volta a ser cobrada com sucesso, a tarefa não é concluída nem excluída automaticamente. Ela continua na lista com o status atual até que alguém da sua equipe a marque como **Completada**.

Por isso recomendamos conferir a assinatura (coluna **Suscripción**) antes de trabalhar um caso: se ela já foi cobrada com sucesso, basta marcar a tarefa como concluída.

## Status das tarefas

A coluna **Completada** mostra o status de cada tarefa:

| Status | O que significa |
|---|---|
| **Pendiente** (Pendente) | A tarefa está aberta e ninguém a marcou como resolvida. É o status com que ela é criada, e também o de uma tarefa reaberta por uma nova falha de cobrança. |
| **Completada** (Concluída) | Alguém da sua equipe a marcou como resolvida. |

Cada tarefa também tem um **Tipo**, que você pode mudar manualmente:

| Tipo | O que significa |
|---|---|
| **General** (Geral) | O tipo com que a AFRUS cria as tarefas automaticamente. |
| **Fallo Mensual** (Falha mensal) | Etiqueta disponível para classificar o caso manualmente. |
| **Cancelada por el Sistema** (Cancelada pelo sistema) | Etiqueta disponível para classificar o caso manualmente. |

> **Pendente de confirmação:** se algum processo da AFRUS atribui automaticamente os tipos **Fallo Mensual** e **Cancelada por el Sistema**.

## O que posso fazer em cada status

| Status | O que você pode fazer |
|---|---|
| **Pendiente** | Atribuir um **Responsable**, mudar **Nombre** (nome) ou **Tipo**, marcá-la como concluída, abrir a assinatura e exportá-la. |
| **Completada** | Desmarcá-la para voltar a **Pendiente**, reatribuí-la, editá-la e exportá-la. |

### Como revisar e filtrar as tarefas

1. **Abra a lista.** Acesse **Follow up > Tareas de suscripciones**.
   ![Lista de Tareas de Suscripciones com o intervalo de datas, o filtro Responsable e o botão Acciones](img/tareas-de-suscripciones-01.webp)
2. **Escolha as datas.** Na barra de datas, escolha o período. Por padrão aparece todo o histórico. O filtro usa a data de criação da tarefa: uma tarefa reaberta mantém a data original.
3. **Busque ou filtre.** Busque pelo **Nombre** da tarefa ou filtre por **Responsable** para ver apenas os casos de uma pessoa da equipe.

A tabela mostra 25 tarefas por página (você pode mudar para 10, 50 ou 100), da mais nova para a mais antiga.

### Como atribuir, editar ou concluir uma tarefa

1. **Abra a tarefa.** Na linha, clique no menu de três pontos (coluna sem título, à esquerda).
2. **Edite.** Em **Editar Tarea** (Editar tarefa), preencha **Nombre**, **Tipo**, **Responsable** ou a caixa **Marcar como completada** (Marcar como concluída). O **Responsable** precisa ser um usuário da sua organização.
3. **Salve.** Clique em "Guardar" (Salvar). Você verá *"Tarea actualizada correctamente"* (Tarefa atualizada com sucesso) e a tabela será recarregada.

> **Dá para desfazer?** Sim. Abra de novo **Editar Tarea** e desmarque **Marcar como completada** ou troque o responsável.

### Como exportar as tarefas

1. **Selecione as tarefas.** Marque as linhas que quiser, ou use o aviso *"Seleccionar las {total} tareas que coinciden con los filtros actuales."* (Selecionar as {total} tarefas que correspondem aos filtros atuais) para pegar todas.
2. **Exporte.** Clique em "Acciones" (Ações) e escolha **Exportar**. Você verá *"La exportación ha comenzado. Puede tardar unos minutos en completarse; encontrarás el archivo en Descargas."* (A exportação começou. Pode levar alguns minutos; o arquivo ficará em Downloads.)

---

## Limitações conhecidas

- **Só alguns gateways aparecem.** A tela lista as tarefas de assinaturas com gateway **Recurrent Payments** ou **PTESA**. As de outros gateways não aparecem aqui; confira em **Suscripciones**.
- **O motivo da falha pode aparecer vazio** ("-"). Nesse caso, procure a cobrança que falhou em **Transacciones** (Transações) e abra o detalhe: o motivo da falha aparece ali.
- **Não há filtro por status.** A lista mostra juntas as tarefas **Pendiente** e **Completada**; ordene ou exporte para separá-las.

## Perguntas frequentes

**São criadas tarefas para doações únicas que falham?**
Não. Elas só são criadas quando falha a cobrança de uma assinatura.

**Por que uma tarefa concluída voltou para Pendente e sem responsável?**
Porque a assinatura teve uma nova falha de cobrança. A AFRUS reabre a mesma tarefa em vez de criar outra.

**Quem recebe o aviso de uma tarefa nova?**
Os usuários com papel owner ou admin da sua organização, com uma notificação na AFRUS.

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-20*
