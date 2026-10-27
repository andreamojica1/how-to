# Guia de Transações

Depois de ler este guia, você vai saber o que é o módulo Transações, para que serve e como agradecer com IA, reembolsar, marcar fraude, baixar, filtrar e ver por que um pagamento falhou.

*Módulo: Transacciones (Transações) · Menu: **Transacciones** · Público: equipes de captação, relacionamento com doadores e financeiro*

> **Sobre os nomes de tela neste guia:** botões, campos e menus estão escritos exatamente como aparecem na versão em espanhol do console, com a explicação em português quando ajuda.

---

## O que é Transações

**Transações é a lista de todos os pagamentos da sua organização.** Aqui você vê as doações únicas e cada cobrança das doações recorrentes, com status, valor, gateway de pagamento, método de pagamento, campanha e widget de origem.

As assinaturas em si (o compromisso de doar todo mês) não ficam aqui: elas aparecem em **Suscripciones** (Assinaturas). O que aparece em Transações é cada pagamento que a assinatura gera.

## Para que serve

- **Encontrar qualquer pagamento.** Busque por nome, documento, e-mail, telefone ou ID e abra o detalhe, incluindo a resposta do gateway quando um pagamento falha.
- **Reembolsar doações.** Devolva doações aprovadas nos gateways que permitem.
- **Limpar fraudes.** Marque pagamentos fraudulentos para tirá-los da lista e da sua base.
- **Exportar para Excel.** Baixe um grupo de transações: as que você escolher ou todas as que correspondem aos seus filtros.
- **Agradecer com IA.** Envie ao doador um e-mail de agradecimento escrito com IA.

## Antes de começar

- **Por padrão, a lista mostra o mês atual** (**MTD**). Mude o período na barra de datas se procura pagamentos mais antigos.
- **A lista é atualizada ao abrir a tela ou mudar um filtro.** Ela não se atualiza sozinha enquanto está aberta.

---

# Passo a passo

## Como criar um agradecimento com IA em Transações

**Você precisa:**
- que a transação esteja com status **Exitoso** (Aprovada);
- ter o **Business profile** ativo (sem ele, a opção não aparece);
- pelo menos um usuário com assinatura de e-mail configurada em **AI > Firmas de usuarios** (Assinaturas de usuários). Só esses usuários aparecem como remetentes.

1. **Abra o agradecimento.** Em **Transacciones**, abra o menu de três pontos no início da linha e escolha **Agradecimiento personalizado IA** (Agradecimento personalizado com IA). Você também pode usar o botão com ícone de brilho ao lado do status **Exitoso**.
   ![Menu de três pontos de uma transação com a opção Agradecimiento personalizado IA](img/como-crear-un-agradecimiento-con-ia-desde-transacciones-01.webp)
2. **Escolha o remetente.** Na etapa **Seleccionar el remitente con el que enviarás el agradecimiento** (Selecionar o remetente), escolha um usuário e clique em "Continuar". O e-mail sai do endereço da assinatura dele.
3. **Aguarde o rascunho.** Você verá *AI preparando tu mensaje* (A IA está preparando sua mensagem) enquanto a IA escreve o e-mail.
4. **Revise e edite.** Ajuste **Asunto** (Assunto, até 128 caracteres) e **Cuerpo del correo** (Corpo do e-mail, até 1600). "Regenerar" pede outra versão de cada campo; "Volver" (Voltar) retorna à etapa anterior.
5. **Envie.** Clique em "Enviar mensaje" (Enviar mensagem). O botão fica ativo quando assunto e corpo têm texto.

Ao terminar, você verá *Mensaje enviado* / *"El agradecimiento se ha enviado correctamente"* (O agradecimento foi enviado com sucesso). O e-mail vai para o endereço da pessoa dessa transação. Se algo falhar, você verá *"Error al enviar el agradecimiento"*.

> **Importante:** não use os botões **Merge tags** neste e-mail. Por enquanto, as variáveis são enviadas como texto literal, sem serem substituídas pelos dados do doador. Escreva o nome e os dados diretamente no texto.

> **Dá para desfazer?** Não. Depois de enviado, o e-mail já está na caixa do doador: revise bem antes de clicar em "Enviar mensaje".

## Como reembolsar uma doação

**Você precisa:**
- que a transação esteja com status **Exitoso**;
- que o gateway dela permita reembolsos pela AFRUS (senão, a opção **Reembolsar** não aparece);
- que seu usuário tenha permissão para operações bancárias com transações. Sem ela, o reembolso falha: peça a um administrador da sua organização.

1. **Abra o menu da linha.** Em **Transacciones**, encontre a doação, abra o menu de três pontos no início da linha e escolha **Reembolsar**.
   ![Menu de três pontos de uma transação bem-sucedida com a opção Reembolsar](img/como-reembolsar-una-donacion-01.webp)
2. **Confirme.** Na janela **Reembolsar Cargo** (Reembolsar cobrança) — *"Estas seguro que deseas reembolsar este cargo?"* (Tem certeza de que deseja reembolsar esta cobrança?) —, clique em "Confirmar". Para cancelar, clique em "Cerrar" (Fechar).

Ao terminar, você verá *"Reembolsado con éxito."* (Reembolsado com sucesso) e a transação passará para **Reembolsado**. Se a doação tinha um certificado de doação válido, ele é anulado. Se o gateway recusar o reembolso, você verá *"Error al reembolsar el cargo."* (Erro ao reembolsar a cobrança) e a transação não muda.

> **Importante:** o valor total é sempre reembolsado. Nesta tela não é possível fazer reembolsos parciais.

> **Dá para desfazer?** Não. O dinheiro é devolvido pelo gateway e não há opção para reverter o reembolso.

> **Pendente de confirmação:** quanto tempo o dinheiro leva para chegar ao doador e até quantos dias depois da cobrança cada gateway aceita reembolsos; e também se reembolsar um **Cargo** (cobrança) cancela a assinatura. Se quiser parar as cobranças futuras, cancele a assinatura em **Suscripciones**.

## Como marcar uma transação como fraude

> **Importante:** ao marcar uma transação como fraude, **as pessoas (doadores) vinculadas a ela são excluídas da sua base**, mesmo que tenham outras doações legítimas. Revise bem antes de confirmar.

1. **Selecione as transações.** Na tabela de **Transacciones**, marque a caixa de uma ou mais linhas da página.
   ![Duas transações selecionadas e o menu Acciones transacciones aberto com Marcar como Fraude](img/como-marcar-como-fraude-una-transaccion-01.webp)
2. **Escolha a ação.** Clique em "Acciones transacciones" (Ações de transações) e escolha **Marcar como Fraude**. A opção fica desativada se nada estiver selecionado.
3. **Confirme.** Na janela **Marcar como fraude**, leia o aviso (*"…Esta acción no se puede deshacer."* — Esta ação não pode ser desfeita) e clique em "Confirmar".

Ao terminar, você verá *Transacciones marcadas como fraude* (Transações marcadas como fraude). Cada transação passa para o status **Fraude**, some de **Transacciones** e aparece em **Follow up > Radar - monitor de fraude**, onde você vê o **Estado anterior** (Status anterior) e a data em **Marcada como fraude el** (Marcada como fraude em).

> **Importante:** marcar como fraude só muda o status na AFRUS. Não reembolsa o pagamento nem cancela nenhuma assinatura no gateway.

> **Importante:** só as linhas selecionadas na página atual são marcadas. Mesmo usando "Seleccionar las N transacciones de la base." (Selecionar as N transações da base), esta ação não se aplica à base inteira. Se forem muitas, marque página por página.

> **Dá para desfazer?** Não. A própria janela avisa, e no Radar não há opção para reverter.

## Como baixar um grupo de transações

1. **Filtre o que precisa.** Ajuste datas, busca e filtros (veja "Como filtrar um grupo de transações").
2. **Selecione as transações.** Marque as linhas que quer. Para exportar tudo o que foi filtrado, marque a caixa do cabeçalho e clique em "Seleccionar las N transacciones de la base."
   ![Caixa do cabeçalho marcada e link para selecionar todas as transações da base](img/como-descargar-un-grupo-de-transacciones-02.webp)
3. **Exporte.** Clique em "Acciones transacciones" e escolha **Exportar**. A opção fica desativada se nada estiver selecionado.
4. **Confirme o arquivo.** Na janela **Descargas** (Downloads), escolha **Tipo de archivo** (Tipo de arquivo) e clique em "Confirmar". Você verá *Exportar archivo* (*"El proceso de exportacion ha comenzado…"* — a exportação começou e pode levar alguns minutos).
5. **Baixe o arquivo.** Acesse **Data > Descargas** e baixe quando estiver pronto.

Você terá um arquivo Excel. Se selecionou linhas avulsas, ele traz exatamente essas, independentemente do período; se escolheu a base inteira, traz tudo o que corresponde a datas, busca e filtros.

> **Importante:** o arquivo é sempre gerado em Excel (.xlsx), mesmo que você escolha CSV. Além disso, o filtro **CYC** não é aplicado na exportação com "base inteira": se precisar dele, filtre por **CYC** na tela e marque as linhas uma a uma, porque assim são exportadas exatamente as que você escolher.

> **Importante:** os arquivos podem ser baixados por até 7 dias depois de gerados.

## Como filtrar um grupo de transações

1. **Escolha o período.** Na barra de datas, clique em **1W**, **4W**, **1Y**, **MTD**, **QTD**, **YTD**, **ALL** ou **PERSONALIZADO** (personalizado). O padrão é **MTD** (do início do mês até hoje). O período se aplica à **Fecha inicial** (Data inicial) da transação, no seu fuso horário.
   ![Barra de datas com os períodos e linha de filtros de Transacciones](img/como-filtrar-un-grupo-de-transacciones-01.webp)
2. **Busque (opcional).** Use **Buscar por** com **Nombre** (Nome), **Documento de identidad** (Documento), **Correo electrónico** (E-mail), **Teléfono** (Telefone) ou **ID de transaccion** (ID da transação).
3. **Aplique filtros.** Na linha com o ícone de funil, escolha:
   - **Tipo**: **Unicas** (Únicas) / **Cargos** (Cobranças)
   - **Tipo de origen** (Tipo de origem): Estándar, Incentivo, Peer to peer, Producto
   - **Estados** (Status), **Pasarela de pago** (Gateway), **Metodo de pago** (Método de pagamento)
   - **Valor**: Mayor que / Igual que / Menor que (maior / igual / menor que), comparando o valor convertido para a moeda da sua organização
   - **Campaña** (Campanha), **Widgets**
   - **CYC**: Con CYC / Sin CYC, para ver doações em que o doador cobriu o custo
4. **Limpe quando quiser.** "Reset" remove todos os filtros.

A tabela e os totais são recalculados. Os filtros ficam no endereço da página, então você pode copiar o link e compartilhar a mesma visão com sua equipe.

> **Importante:** se marcar ao mesmo tempo **Unicas** e **Cargos** em **Tipo**, só as doações únicas aparecem. Para ver as duas, deixe **Tipo** vazio.

## Como saber o motivo da falha de uma transação

A lista não tem uma coluna de motivo: ele aparece no detalhe da transação.

1. **Abra o detalhe.** Na linha de uma transação **Fallido** (Falhou) ou **Rechazada** (Recusada), abra o menu de três pontos e escolha **Detalles** (Detalhes), ou clique no **ID**. Ele abre em uma nova aba.
   ![Detalhe de uma transação com falha com o cartão Resultado de suscripción e a análise com IA](img/como-saber-la-razon-del-fallo-de-una-transaccion-01.webp)
2. **Leia a explicação da IA.** O cartão **Resultado de suscripción** (**Analisis de la respuesta con IA** — Análise da resposta com IA) explica em linguagem simples o que o gateway respondeu. Exige o **Business profile** ativo; sem ele, você verá *Activación necesaria para ver la respuesta con IA* (Ativação necessária) e o botão "Ir a business profile".
3. **Consulte a resposta original.** Em **Respuesta** > **Respuesta Gateway** (Resposta do gateway) está a resposta do gateway, com o código ou a mensagem de recusa que ele enviou.

A análise é gerada na primeira vez que você abre o detalhe e depois aparece com a etiqueta **Cacheado** (Em cache). Se o pagamento não tem resposta do gateway, não há análise.

---

## Única e Cargo: qual é a diferença

A coluna **Tipo de frecuencia** (Tipo de frequência) e o filtro **Tipo** distinguem dois tipos de pagamento:

| Na coluna | No filtro **Tipo** | O que é |
|---|---|---|
| **Única** | **Unicas** | Uma doação de pagamento único. Não vem de uma assinatura. |
| **Cargo** (Cobrança) | **Cargos** | Uma cobrança de uma doação recorrente. Cada mês ou ciclo da assinatura gera uma nova cobrança. |

A assinatura em si (o registro "mãe", **Recurrente**) não aparece nesta lista: ela fica em **Suscripciones**.

## Status de uma transação

| Status | O que significa |
|---|---|
| **Exitoso** (Aprovada) | O pagamento foi concluído. Você pode agradecer com IA ou reembolsar |
| **Pendiente** (Pendente) | O pagamento ainda não foi confirmado (alguns métodos demoram) |
| **Pendiente de confirmación** (Aguardando confirmação) | Sua equipe precisa confirmar ou recusar com **Confirmar transacción** / **Rechazar transacción** |
| **Fallido** / **Rechazada** (Falhou / Recusada) | O pagamento não foi concluído. Veja o motivo no detalhe |
| **Reembolsado** | O pagamento foi devolvido ao doador |
| **Propuesta** (Proposta) | Pendente de confirmação do que significa este status |
| "PRENOTIFICATION_OK" | Aparece assim, como texto técnico, em transações pré-notificadas |

Transações em **Fraude**, **Cancelada** ou **Contracargo** (Chargeback) não aparecem em **Transacciones**. As de fraude ficam em **Follow up > Radar - monitor de fraude**.

## Perguntas frequentes

**Posso fazer um reembolso parcial?**
Não. Pela AFRUS, o valor total da transação é sempre reembolsado.

**Por que não vejo a opção Reembolsar?**
Ela só aparece em transações **Exitoso** cujo gateway permite reembolsos pela AFRUS.

**Marcar como fraude devolve o dinheiro?**
Não. Só muda o status na AFRUS. Se também precisar devolver o pagamento, reembolse antes de marcar como fraude.

**Onde vejo as assinaturas?**
Em **Suscripciones**. Em Transações você vê cada cobrança (**Cargo**) que elas geram.

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-20*
