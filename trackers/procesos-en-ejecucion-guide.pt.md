# Guia de Procesos en ejecucion

Com este guia, você vai saber se uma ação que fez sobre muitas pessoas de uma vez (por exemplo, colocar uma etiqueta ou excluí-las) já terminou.

*Módulo: Trackers · Menu: **Trackers > Procesos en ejecucion** (Processos em execução) · Público: equipes de captação, dados e comunicação*

> **Sobre os nomes de tela neste guia:** botões, campos e menus estão escritos exatamente como aparecem na versão em espanhol do console, com a explicação em português quando ajuda.

---

## O que é Procesos en ejecucion

**É uma lista das ações que você fez sobre um grupo grande de pessoas, com o andamento de cada uma.**

Quando você faz algo com muitas pessoas de uma vez, a Afrus não faz tudo em um segundo: ela vai pessoa por pessoa, em segundo plano, enquanto você continua trabalhando. Esta tela mostra em que ponto está cada uma dessas ações.

Aparecem aqui quatro ações:

- **Colocar uma etiqueta** em um grupo de pessoas.
- **Excluir** um grupo de pessoas.
- **Mudar a permissão de comunicação** (opt-in) de um grupo.
- **Inscrever** um grupo de pessoas em um fluxo de trabalho.

Importações, downloads e envios de e-mail não aparecem aqui.

## Para que serve

- **Saber se uma ação já terminou.** Por exemplo, antes de enviar um e-mail para as pessoas que você acabou de etiquetar.
- **Ver quanto falta.** Você compara quantas pessoas o grupo tinha com quantas já foram processadas.
- **Saber quem fez cada ação e quando.** Útil quando várias pessoas da sua equipe trabalham com a mesma base.

---

# Passo a passo

## Que informação encontro ali e como analisá-la

1. **Abra a tela.** Acesse **Trackers > Procesos en ejecucion**. Você também chega pelo botão "Ver procesos" (Ver processos) de **Personas**, **Transacciones**, **Suscripciones**, **Segmentos** e **Data > Tags**.
   <!-- captura pendente: procesos-en-ejecucion-01 — tela Procesos com o campo de busca e a tabela de processos -->

2. **Encontre seu processo.** Para ver só os processos de uma pessoa da sua equipe, digite o e-mail dela em **Buscar por email** e pressione Enter ou a lupa.

3. **Veja os mais recentes primeiro.** A lista começa pelos processos mais antigos. Clique no título da coluna **ID** ou **Creado en** (Criado em) para ver os mais novos primeiro.

4. **Confira o andamento.** Compare **Total de leads** (quantas pessoas o grupo tinha) com **Total de leads procesados** (quantas já foram processadas). Quando termina, a coluna **Finalizado** mostra "Sí" (Sim); enquanto isso, mostra "No" (Não).
   <!-- captura pendente: procesos-en-ejecucion-04 — linha de um processo com Total de leads, Total de leads procesados e Finalizado -->

5. **Recarregue para ver mudanças.** A tela não se atualiza sozinha. Recarregue a página para ver o andamento.

**As colunas da tabela:**

| Coluna | O que mostra |
|---|---|
| **ID** | O número do processo. Anote se precisar falar com o suporte |
| **ID de usuario** e **Correo electrónico** (ID do usuário e e-mail) | Quem da sua equipe fez a ação |
| **Total de leads** | Quantas pessoas o grupo tinha |
| **Total de leads procesados** | Quantas pessoas já foram processadas |
| **Finalizado** | "Sí" se terminou, "No" se ainda está em andamento |
| **Creado en** | Quando foi iniciado |
| **Actualizado en** (Atualizado em) | A última vez que avançou |
| **Tipo** | Qual ação é (veja a tabela abaixo) |

**A coluna Tipo** mostra um nome em inglês:

| Tipo | Qual ação |
|---|---|
| `tag` | Colocar uma etiqueta em um grupo |
| `delete` | Excluir um grupo de pessoas |
| `opt-in` | Mudar a permissão de comunicação de um grupo |
| `workflow_enroll` | Inscrever um grupo em um fluxo de trabalho |

> **Dica:** se o horário de **Actualizado en** não muda por muito tempo, o processo parou.

Quando termina de colocar uma etiqueta, a Afrus também deixa um aviso nas suas notificações, em inglês: *"Tag Leads Process for tag: '…' finished"*.

## O que fazer se um processo não termina

Se, depois de recarregar, **Finalizado** continua em "No" e **Total de leads procesados** não avança, o processo parou. Esta tela não tem botão para tentar de novo.

- **Se era uma etiqueta:** coloque-a de novo no mesmo grupo. Quem já tem a etiqueta não fica duplicado.
- **Se era uma exclusão, uma mudança de permissão ou uma inscrição em fluxo:** anote o **ID** do processo e fale com o suporte da Afrus.

---

## Limitações conhecidas

- **Uma etiqueta pode ficar em "No" para sempre.** Se alguma pessoa do grupo não pôde ser processada (por exemplo, porque foi excluída nesse meio-tempo), o processo pode ficar em **Finalizado** "No" mesmo que todas as outras tenham recebido a etiqueta. Para conferir, veja a etiqueta em **Data > Tags**.
- **A coluna Tipo está em inglês.**
- **Só aparecem as quatro ações deste guia.** Importações, downloads e envios têm suas próprias telas.

## Perguntas frequentes

**A tela se atualiza sozinha?**
Não. Recarregue para ver o andamento.

**Por que não vejo minha importação aqui?**
Porque as importações não aparecem nesta tela. Esta lista mostra só etiquetas, exclusões, mudanças de permissão e inscrições em fluxos.

**Por quanto tempo o histórico é guardado?**
> **Pendente de confirmação:** por quanto tempo o histórico de processos é mantido.

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-26*
