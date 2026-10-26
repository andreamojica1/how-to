# Guia de Leads spam

Depois de ler este guia, você vai saber o que é **Leads spam**, para que serve, quando a Afrus considera um cadastro como spam e como devolver à sua base uma pessoa real que foi separada.

*Módulo: Follow up · Menu: **Follow up > Leads spam** · Público: equipes de captação, dados e relacionamento com doadores*

> **Sobre os nomes de tela neste guia:** botões, campos e menus estão escritos exatamente como aparecem na versão em espanhol do console, com a explicação em português quando ajuda.

---

## O que é Leads spam

**Leads spam é a lista de pessoas que a Afrus separou automaticamente, em "quarentena", porque o cadastro feito por um formulário parece ter sido feito por um robô.**

Essas pessoas não são excluídas: ficam guardadas nesta lista para que sua equipe as revise e, se alguma for real, a devolva à base com um clique.

## Para que serve

- **Manter limpa a sua base de Pessoas.** Os cadastros automatizados não se misturam com seus doadores e contatos reais.
- **Não perder ninguém.** As pessoas separadas ficam guardadas, e você pode revisá-las quando quiser.
- **Corrigir a tempo.** Com "No es spam" (Não é spam) você devolve à base qualquer pessoa real que tenha sido separada.
- **Proteger seus números.** As pessoas em quarentena não contam em segmentos, campanhas, relatórios nem no painel inicial, e não recebem e-mails automáticos.

---

# Passo a passo

## Como revisar os leads spam e restaurar uma pessoa

1. **Abra a lista.** Acesse **Follow up > Leads spam**.
   ![Tela Leads spam com a busca, o intervalo de datas e a tabela com a coluna Motivo](img/leads-spam-01.webp)

2. **Escolha o período.** Por padrão aparece o **mês atual**. O filtro usa a data de criação da pessoa.

3. **Revise cada linha.** Veja o nome, o e-mail, a **Campaña** (Campanha), o widget de origem e a coluna **Motivo**, que mostra por que a Afrus separou o cadastro (veja a tabela de motivos abaixo).

4. **Restaure as pessoas reais.** Se reconhecer uma pessoa real, clique em "No es spam" na linha dela. Assim ela volta para **Personas** (Pessoas), para seus segmentos e para suas comunicações automáticas.

Ao terminar, a pessoa deixa de aparecer na lista e volta para a sua base. Se algo falhar, você verá *"Error al restaurar la persona"* (Erro ao restaurar a pessoa).

> **Importante:** a restauração é feita uma pessoa por vez. Nesta tela não há seleção múltipla nem ações em massa (exportar, etiquetar ou excluir), de propósito, para que cada caso seja revisado com cuidado.

---

## Com que frequência é atualizado

- **A decisão é tomada em tempo real**, no momento em que a pessoa se cadastra por um formulário ou widget.
- **A tela não se atualiza sozinha.** Ela carrega ao ser aberta e quando você muda datas, ordem ou página. Se estiver esperando um cadastro novo, recarregue.

## Quando um lead é considerado spam

A Afrus avalia cada cadastro no momento em que ele chega de um formulário ou widget. Ela o separa como spam quando o cadastro **reúne vários sinais típicos de cadastros automatizados**. A coluna **Motivo** mostra os sinais encontrados, com estes códigos (aparecem em inglês, como estão):

| Motivo | O que significa |
|---|---|
| `no_origin_metadata` | O cadastro chegou sem os dados de origem que um widget normalmente envia |
| `ua_missing_or_blocklisted` | O navegador não se identificou ou se identificou como uma ferramenta automatizada |
| `ip_velocity` | Chegaram cadastros demais da mesma conexão em pouco tempo |
| `implausible_identity` | Os dados de identidade não são plausíveis (por exemplo, e-mails descartáveis ou dados inconsistentes) |

Se uma pessoa em quarentena concluir uma doação confirmada, a Afrus a restaura automaticamente.

## Quais mecanismos a Afrus tem para combater o spam

- **Classificação automática de cada cadastro de formulário**, com os sinais descritos acima.
- **Quarentena:** as pessoas separadas ficam guardadas, mas fora de **Personas**, segmentos, contagens de campanhas, relatórios, painel inicial, etiquetas e e-mails automáticos até que alguém as restaure.
- **Restauração automática** de quem conclui uma doação confirmada.
- **Controles antifraude nos formulários**, como a verificação anti-robôs. Veja mais no guia do **Radar - monitor de fraude**.

## Limitações conhecidas

- **A coluna Motivo mostra códigos técnicos em inglês**, sem tradução. Use a tabela deste guia para interpretá-los.
- **Não há ações em massa** nesta tela: a revisão é pessoa por pessoa.

## Perguntas frequentes

**As pessoas em Leads spam são excluídas?**
Não. Elas ficam guardadas nesta lista até você restaurá-las.

**As pessoas em quarentena recebem meus e-mails?**
Não. Elas ficam fora dos e-mails automáticos, segmentos e relatórios até você restaurá-las.

**Essa classificação está ativa na minha organização?**
> **Pendente de confirmação:** se a classificação está ativa em todas as organizações. Em caso de dúvida, fale com a gente.

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-20*
