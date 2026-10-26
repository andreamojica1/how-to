# Guia de Logs de analytics

Com este guia, você vai conseguir conferir se seus formulários de doação estão avisando o Google Analytics 4, a Meta (Facebook) ou o Google Tag Manager toda vez que alguém começa ou conclui uma doação.

*Módulo: Trackers · Menu: **Trackers > Logs de analytics** · Público: equipes de marketing digital e mídia paga*

> **Sobre os nomes de tela neste guia:** botões, campos e menus estão escritos exatamente como aparecem na versão em espanhol do console, com a explicação em português quando ajuda.

---

## O que é Logs de analytics

**É o registro de cada aviso que seus formulários de doação enviaram ao Google Analytics 4, à Meta ou ao Google Tag Manager.**

Se uma dessas ferramentas está conectada a um formulário (widget), toda vez que uma pessoa abre o formulário, avança uma etapa ou conclui a doação, a Afrus avisa essa ferramenta. Cada aviso se chama **evento**. Esta tela mostra cada evento, o que foi enviado e o que a ferramenta respondeu.

Se o seu formulário não tem nenhuma dessas ferramentas configurada, nada é enviado e esta tela fica vazia.

## Para que serve

- **Conferir se a sua medição funciona.** Você vê se os eventos dos seus formulários estão saindo para o Google ou a Meta.
- **Encontrar erros de configuração.** Por exemplo, se faltam no formulário os dados de conexão do Google ou da Meta.
- **Revisar os eventos de uma pessoa.** Útil para conferir uma doação de teste.

---

# Passo a passo

## Que informação encontro ali e como analisá-la

1. **Faça uma doação de teste** no seu formulário, ou espere chegarem doações reais.

2. **Abra a tela.** Acesse **Trackers > Logs de analytics** e escolha um período que inclua o seu teste. Ao abrir, aparece o mês atual.
   <!-- captura pendente: logs-de-analytics-02 — tela Logs de analytics com a barra de datas, o campo de busca, os filtros e a tabela -->

3. **Busque a pessoa.** Digite o e-mail ou o ID dela no campo de busca e clique na **lupa**. O Enter não busca.

4. **Leia a coluna Descripción (Descrição).** Ela diz para qual ferramenta o evento foi enviado e qual foi:
   - `GOOGLE-…` é o Google Analytics 4.
   - `FACEBOOK-…` é a Meta.
   - `GOOGLE-TAG-MANAGER-…` é o Google Tag Manager.

5. **Abra o detalhe.** Clique no ícone do olho na linha. A janela **Log** mostra o que foi enviado e o que a ferramenta respondeu.
   <!-- captura pendente: logs-de-analytics-05 — janela Log com o que foi enviado e a resposta -->

**Qual evento é cada um** (a parte final da **Descripción**):

| Termina em | O que aconteceu no formulário |
|---|---|
| `START` | O formulário foi aberto |
| `ADD_TO_CART`, `BEGIN_CHECKOUT`, `ADD_PAYMENT_INFO`, `GENERATE_LEAD` | A pessoa avançou uma etapa com o botão de continuar |
| `PURCHASE` | O pagamento foi confirmado |
| `REGISTER` | A pessoa se cadastrou em um formulário de cadastro |

**Como ler a resposta na janela Log:**

- **Meta:** se funcionou, você verá o que a Meta devolveu. Se falhou, verá `success: false` e uma mensagem com o motivo, por exemplo que faltam no formulário os dados do Pixel.
- **Google Analytics 4:** se aparecer `missing_ga_credentials`, faltam no formulário os dados de conexão com o GA4 e **o evento não foi enviado**. Se aparecer `success: false`, o Google respondeu com erro. Se não houver erro, o Google recebeu o aviso; para confirmar que registrou, veja o relatório em tempo real do GA4.
- **Google Tag Manager:** o normal é ver `logged_only: true`. A Afrus só anota o evento aqui; o Tag Manager o recebe diretamente do navegador da pessoa.

Se você tem a conversão da Meta pela Afrus ativada, também verá linhas `FACEBOOK-…` criadas pela Afrus depois de cada pagamento.

---

## Limitações conhecidas

- **O filtro do Google Analytics não mostra nada.** No filtro **Plataforma**, a opção **Google Analytics** não traz resultados. Para ver só os eventos do GA4, não use esse filtro: digite `google` e o evento no campo de busca (por exemplo `google purchase`) e clique na lupa.
- **Alguns tipos de evento sempre vêm vazios.** Em **Tipo de evento**, só encontram resultados **Start** / **View Content**, **Add to Cart**, **Begin Checkout** / **Initiate Checkout**, **Add Payment Info** e **Purchase**. As outras opções vêm vazias porque os formulários não enviam eventos com esses nomes.
- **A hora não diz se é de manhã ou de tarde.** Aparece no formato de 12 horas sem AM/PM.
- **A coluna ID de Campaña (ID da campanha) aparece sempre vazia.**
- **Ao usar um filtro, as datas passam para "ALL"** (todas as datas).
- **Se você mudar um segundo filtro e a lista não mudar,** clique na lupa para recarregar.
- **A lista começa pelos eventos mais antigos** do período escolhido.
- **Se você excluir um formulário,** os eventos dele deixam de ser registrados aqui.
- **A tela não se atualiza sozinha.**

## Perguntas frequentes

**Não vejo nenhuma linha do meu formulário. O que está acontecendo?**
O mais provável é que o formulário não tenha configurado o Google Analytics 4, o Pixel da Meta nem o Google Tag Manager. Sem essa configuração, nada é enviado.

**Quanto tempo um evento leva para aparecer?**
> **Pendente de confirmação:** não há um tempo fixo.

**Por quanto tempo esses registros são guardados?**
> **Pendente de confirmação:** por quanto tempo o histórico é mantido.

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-26*
