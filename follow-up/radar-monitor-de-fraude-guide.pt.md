# Guia do Radar - monitor de fraude

Depois de ler este guia, você vai saber o que é o Radar, quando uma transação aparece nele, como revisá-lo e como a Afrus protege você contra fraudes.

*Módulo: Follow up · Menu: **Follow up > Radar - monitor de fraude** · Público: equipes de finanças, captação e administração*

> **Sobre os nomes de tela neste guia:** botões, campos e menus estão escritos exatamente como aparecem na versão em espanhol do console, com a explicação em português quando ajuda.

---

## O que é o Radar - monitor de fraude

**O Radar é a lista das transações da sua organização que foram marcadas como fraude.** A tela se chama **Transacciones Fraudulentas** (Transações fraudulentas).

Para cada transação você vê, entre outros dados, o **Valor**, **Email**, **Nombre** (nome), **Estado** (status), **Estado anterior** (o status antes de ser marcada como fraude), a data **Marcada como fraude el** (marcada como fraude em), o **Pasarela de pago** (gateway de pagamento), o **Método de pago** (método de pagamento), o **Widget** e a **Campaña** (campanha).

## Para que serve

- **Revisar as fraudes em um só lugar.** Todas as transações marcadas como fraude, com o status anterior e a data em que foram marcadas.
- **Encontrar padrões.** Filtre por **Pasarela de pago**, **Metodo de pago**, **Campaña**, **Widgets**, **Tipo**, **Estado anterior** e faixa de valor.
- **Conciliar e analisar.** Exporte a lista com "Acciones" (Ações) > **Exportar**.
- **Ver o detalhe de cada caso.** Abra pelo menu da linha.

---

# Passo a passo

## Com que frequência é atualizado

- **Na hora.** Uma transação aparece no Radar assim que é marcada como fraude.
- **A tela não se atualiza sozinha.** Os dados são carregados ao abrir e ao mudar datas, filtros, ordem ou página. Recarregue a página para ver o mais recente.

## Quando uma transação é considerada fraudulenta

Uma transação aparece no Radar quando é marcada como fraude:

- **Pela sua equipe**, com a ação **Marcar como Fraude** em **Transacciones** (Transações), ou
- **Pela equipe da Afrus**, por exemplo ao carregar uma lista de transações fraudulentas.

O Radar mostra transações de pagamento; não mostra o registro da assinatura em si.

### Como marcar uma transação como fraude

Isso é feito em **Transacciones**, não no Radar (no Radar as linhas já são fraude).

1. **Selecione as transações.** Em **Transacciones**, marque uma ou várias linhas.
2. **Escolha a ação.** Clique em "Acciones" e escolha **Marcar como Fraude**.
3. **Confirme.** Na janela **Marcar como fraude**, leia o aviso *"¿Estás seguro de que quieres marcar {count} transacción(es) como fraudulenta(s)? Esta acción no se puede deshacer."* (Tem certeza de que quer marcar {count} transação(ões) como fraudulenta(s)? Esta ação não pode ser desfeita.) e confirme.

Você verá *"Transacciones marcadas como fraude"* (Transações marcadas como fraude) e as transações passarão para o Radar.

> **Dá para desfazer?** Não. Além disso, **as pessoas vinculadas** a essas transações **são excluídas**: deixam de aparecer em **Personas** (Pessoas). Confira bem a seleção antes de confirmar.

## Como revisar o Radar

1. **Abra o Radar.** Acesse **Follow up > Radar - monitor de fraude**.
   ![Lista de Transacciones Fraudulentas com a busca, o intervalo de datas e os filtros](img/radar-monitor-de-fraude-01.webp)
2. **Escolha as datas.** Por padrão aparece o mês atual. Atenção: o filtro usa a **data da transação**, não a data em que foi marcada como fraude.
3. **Filtre ou busque.** Use os filtros ou a busca para encontrar o que precisa. A tabela mostra 25 linhas por página.

## Quais mecanismos a Afrus tem para combater a fraude

A Afrus combina várias proteções. Algumas dependem da configuração de cada organização:

- **Verificação anti-bots (reCAPTCHA)** nos pagamentos com widgets, que pode ser ativada em um formulário quando é detectada atividade anômala.
- **Limites para tentativas de pagamento repetidas**, para frear quem testa muitos cartões.
- **Proteção automática de formulários:** diante de uma atividade incomum de pagamentos recusados, a Afrus pode exigir a verificação anti-bots, limitar temporariamente o formulário ou desativá-lo, e avisar você por e-mail.
- **Verificação por código:** diante de atividade suspeita em um formulário, pode ser pedido ao doador um código de verificação antes da cobrança.
- **Bloqueio de e-mails em lista negra** e outros controles em cada pagamento.
- **Detecção de cadastros automatizados (bots)** nos formulários de cadastro (veja **Follow up > Leads spam**).
- **Marcação manual de fraude** pela sua equipe, com o Radar para o acompanhamento.

> **Pendente de confirmação:** quais proteções estão ativas para a sua organização. Fale com a gente se quiser revisar.

---

## Limitações conhecidas

- **Filtro de datas:** usa a data da transação. Uma transação de um mês anterior marcada hoje não aparece no período padrão; amplie o período para vê-la.
- **Marcar como fraude é definitivo** e exclui as pessoas vinculadas.

## Perguntas frequentes

**Posso tirar a marca de fraude de uma transação?**
Não pelo console. Marcar como fraude não pode ser desfeito.

**Por que não vejo no Radar uma transação que marquei hoje?**
Provavelmente ela é de um mês anterior. O filtro usa a data da transação: amplie o período.

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-20*
