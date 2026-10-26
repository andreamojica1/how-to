# Guia do Reporte general (Relatório geral)

Com este guia você vai poder ver em uma única tela como está a sua organização: quanto você arrecadou, quantas pessoas novas chegaram, como estão as suas doações mensais e de onde vêm os seus doadores.

*Módulo: Data · Menu: **Data > Reporte general** · Público: direção, equipes de captação e comunicação*

> **Sobre os nomes de tela neste guia:** botões, campos e menus estão escritos exatamente como aparecem na versão em espanhol do console, com a explicação em português quando ajuda.

---

## O que é o Reporte general

**O Reporte general (Relatório geral) é um painel com os números mais importantes da sua organização no período que você escolher.** Ele reúne em um só lugar suas pessoas, suas assinaturas (doações mensais), suas transações e suas comunicações.

Os números são calculados na hora, com os dados mais recentes, toda vez que você abre a tela ou muda o período.

## Para que serve

- **Ver de relance como você está.** Quanto arrecadou, quantas pessoas novas chegaram e como estão as doações mensais.
- **Saber o que funciona.** Você vê de qual campanha, formulário (widget), UTM ou página vêm suas pessoas, assinaturas e doações.
- **Compartilhar resultados.** Você pode baixar os números para a sua equipe ou o seu conselho.

---

# Passo a passo

## Como analisar o Reporte general

1. **Abra o relatório.** Acesse **Data > Reporte general**. Ao abrir, você verá o último mês completo (por exemplo, se estamos em outubro, verá setembro).
   <!-- captura pendente: relatorio-geral-01 — tela Vista general com o seletor de período e a zona Global -->

2. **Escolha o período.** Use os filtros de cima (explicamos em "Para que servem os filtros Presets, Año e Mes").

3. **Revise as 5 zonas, de cima para baixo.** Cada uma responde a uma pergunta diferente:

| Zona | O que mostra | O que observar |
|---|---|---|
| **01 Global** | Quantas pessoas novas chegaram e quantas viraram doadoras | A passagem de **Leads** para **Donantes** (Doadores) e para **Donantes recurrentes** (Doadores recorrentes): a porcentagem mostra quantas pessoas novas decidiram doar |
| **02 Suscripciones** (Assinaturas) | Como estão suas doações mensais | **Activas** (Ativas), **Fallidas** (Com falha) e **Canceladas**; **MRR** (o que suas novas assinaturas ativas somam em um mês) e **ARR** (esse valor projetado para um ano) |
| **03 Transacciones** (Transações) | Quanto você arrecadou | **Ingresos totales** (Receita total), as doações **Confirmadas** e as **Otras** (Outras: pendentes, com falha e reembolsadas) |
| **04 Personas** (Pessoas) | Quantos contatos novos você tem | **Personas nuevas** (Pessoas novas), **Leads**, **Donantes** e **Donantes recurrentes** |
| **05 Comunicaciones** (Comunicações) | Quanto você se comunicou | **Emails enviados** (E-mails enviados) e **Mensajes WhatsApp enviados** (Mensagens de WhatsApp enviadas) |

   <!-- captura pendente: relatorio-geral-03 — zonas Suscripciones e Transacciones com seus indicadores -->

4. **Veja de onde vêm.** As tabelas "por origem" (**Nuevas suscripciones por origen**, **Transacciones por origen** e **Nuevos leads por origen**) separam os resultados **Por campaña** (Por campanha), **Por widget**, **Por UTM campaign**, **Por UTM medium**, **Por UTM source** e **Por URL de landing**. Assim você sabe qual campanha ou qual formulário traz mais doadores.
   <!-- captura pendente: relatorio-geral-04 — tabela Transacciones por origen com a aba Por campaña -->

**Algumas dicas para ler bem:**

- **Total fallidas** (Total com falha) conta só as doações únicas que falharam. As cobranças mensais que falharam ficam em **Cargos fallidos** (Cobranças com falha).
- Os valores estão na moeda da sua organização.
- **ARR** é uma projeção (o MRR multiplicado por 12), não dinheiro recebido.

## Para que servem os filtros Presets, Año e Mes

Eles servem para escolher o período que você quer ver e baixar.

**Presets** são atalhos de um clique:

| Preset | Período que mostra |
|---|---|
| **Todo** (Tudo) | Toda a história da sua organização |
| **Año anterior** (Ano anterior) | O ano passado completo |
| **YTD** | De 1º de janeiro deste ano até hoje |
| **Trimestre anterior** | Os três meses do trimestre passado |
| **QTD** | Do início deste trimestre até hoje |
| **Mes anterior** (Mês anterior) | O mês passado completo |
| **MTD** | Do início deste mês até hoje |

**Año** (Ano) e **Mes** (Mês) servem para escolher um mês ou um ano específico, até 8 anos atrás. Por exemplo, para comparar a campanha de dezembro deste ano com a do ano passado, veja primeiro um dezembro e depois o outro.

<!-- captura pendente: filtros-presets-ano-e-mes-01 — seletor de período com Presets, Año e Mes -->

> **Atenção:** não há filtro por campanha nem por moeda, nem intervalo de datas livre, nem comparação automática com o período anterior.

## O que o botão Descargar baixa

- **O botão "Descargar" (Baixar) de cima** baixa um arquivo CSV (abre no Excel ou no Google Sheets) com todos os indicadores do período escolhido. Ele tem quatro colunas: **Sección** (Seção), **KPI**, **Actual** (Atual) e **Unidad** (Unidade).
- **Cada tabela "por origem" tem seu próprio botão "Descargar"**, que baixa só aquela tabela.

<!-- captura pendente: o-que-baixa-o-botao-descargar-01 — botão Descargar no alto da tela -->

> **Atenção:** se uma tabela por origem tiver mais de 5.000 linhas, ela não pode ser baixada e você verá uma mensagem de erro. Escolha um período mais curto e tente de novo.

---

## Limitações conhecidas

- **Pequenas diferenças perto da meia-noite.** **Ingresos totales** e as médias contam os dias com um horário diferente do de **Confirmadas** e **Otras**; por isso, se houve doações perto da virada do dia, os totais podem variar um pouco.
- **MRR e ARR com doações que não são mensais.** Se você tem assinaturas trimestrais, semestrais ou anuais, o MRR e o ARR podem parecer mais altos do que são, porque são contadas como se fossem mensais.
- **A tela não mostra a hora da última atualização,** embora os dados sejam calculados na hora.

## Perguntas frequentes

**Os números estão atualizados?**
Sim. São calculados na hora, toda vez que você abre a tela ou muda o período.

**Posso ver o relatório de uma única campanha?**
Não com um filtro, mas nas tabelas por origem, em **Por campaña**, você vê os resultados de cada campanha.

**Por que o relatório abre no mês passado?**
Porque mostra o último mês completo, que já tem todos os seus resultados. Se quiser ver o mês atual, use **MTD**.

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-26*
