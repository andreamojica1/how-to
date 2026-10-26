# Guia de Importações

Com este guia você vai poder subir para a Afrus, de uma só vez, uma lista de contatos ou de doações que você tem em Excel ou em outro sistema.

*Módulo: Data · Menu: **Data > Importaciones** · Público: equipes de dados, captação e administração*

> **Sobre os nomes de tela neste guia:** botões e campos estão escritos como aparecem na versão em espanhol do console, com a explicação em português.

---

## O que são as importações

**Importar é subir para a Afrus muitos dados de uma vez a partir de um arquivo**, em vez de cadastrá-los um por um.

Em **Data > Importaciones** (Importações) você pode subir dois tipos de listas:

- **Leads:** seus contatos (pessoas).
- **Transacciones** (Transações): doações que você recebeu antes ou fora da Afrus.

Esta tela abre na versão anterior da Afrus, por isso tem outra aparência.

> Se sua organização está no Brasil e você quer subir o arquivo de boletos pagos do banco, isso é feito em outra tela. Veja o [guia de Importaciones - itaú](../follow-up/importaciones-itau-guide.pt.md).

## Para que servem

- **Trazer seus contatos de outro sistema** sem digitá-los.
- **Carregar seu histórico de doações,** para ter na Afrus a informação completa de cada doador.
- **Atualizar pessoas que você já tem.** Se uma pessoa do arquivo já existe na Afrus, ela é atualizada com os dados novos.
- **Agrupar o que você importa.** Você pode colocar uma tag em todas as pessoas do arquivo para encontrá-las depois.

## Antes de começar

- **Seu arquivo em Excel ou CSV** (`.xlsx`, `.xls` ou `.csv`), de até 20 MB.
- **Para importar doações:** sua organização precisa ter ativo o gateway "Simple Afrus" na moeda dessas doações. Se não tiver, fale com a gente.
- **Revise seu arquivo** com a lista "O que considerar ao importar" deste guia. Isso evita erros.

---

# Passo a passo

## Como importar um arquivo

1. **Abra as importações.** Acesse **Data > Importaciones** e clique em "Importar".
   <!-- captura pendente: como-importar-um-arquivo-01 — lista de importações com o botão Importar -->

2. **Escolha o que vai importar.** Em "¿Qué desea importar?" (O que deseja importar?) escolha **Leads** (contatos) ou **Transacciones** (doações) e clique em "Continuar".
   <!-- captura pendente: como-importar-um-arquivo-02 — tela O que deseja importar com as opções Leads e Transacciones -->

3. **Suba seu arquivo.** Clique em "Añadir archivos" (Adicionar arquivos) ou arraste o arquivo. Você pode subir vários de uma vez.

4. **Confirme a permissão dos seus contatos (só Leads).** Marque a caixa *"Certifico que cuento con el consentimiento de las personas incluidas en este archivo para importar sus datos y enviarles comunicaciones multicanal (email, WhatsApp, SMS)."* (Certifico que tenho o consentimento das pessoas deste arquivo para importar seus dados e enviar comunicações multicanal) e clique em "Importar".

5. **Ligue cada coluna ao seu campo na Afrus.** Para cada coluna do seu arquivo ("Datos archivos importados", dados dos arquivos importados), escolha a qual dado da Afrus ela corresponde ("Campos de Afrus", campos da Afrus). Por exemplo: sua coluna "Mail" vai com e-mail. Assim a Afrus sabe onde guardar cada dado.
   <!-- captura pendente: como-importar-um-arquivo-05 — tela para ligar as colunas do arquivo aos campos da Afrus -->

6. **Coloque uma tag (opcional).** Em **Tag** você pode escrever uma etiqueta para todas as pessoas do arquivo, por exemplo o nome do evento onde você as conheceu.

7. **Só para doações, preencha:** a moeda (**Selección de moneda**), o status das doações (**Estatus de la transacción**: Exitosa/Bem-sucedida, Pendiente/Pendente, Fallida/Falhou ou Reembolsado) e a **Campaña** (Campanha) a que pertencem. A caixa **Disparar eventos** já vem marcada; deixe assim se quiser que essas doações sejam compartilhadas com os sistemas conectados à Afrus.

8. **Envie.** Clique em "Siguiente" (Próximo) e depois em "Enviar". Você verá *"¡Listo!"* (Pronto!); clique em "Aceptar" (OK).

Ao terminar, sua importação aparece na lista. Primeiro ela mostra **En cola** (Na fila) ou **Procesando** (Processando) e, quando termina, **Finalizado** (Finalizado) ou **Finalizado con errores** (Finalizado com erros). Dentro do console você verá o aviso *"Importación finalizada"* (Importação finalizada).

> **Dá para desfazer?** Não há um botão para desfazer uma importação. Se você importar doações duas vezes, elas ficam repetidas. Revise bem o arquivo antes de enviar.

## O que considerar ao importar

**Sobre o arquivo:**

- **Use só a primeira planilha.** Se seu Excel tem várias abas, a Afrus só lê a primeira.
- **A primeira linha deve ter os títulos** de cada coluna (Nome, E-mail, Valor…).
- **Escreva as datas como dia/mês/ano**, por exemplo 25/10/2026.

**Dados obrigatórios:**

| Se você importa… | Seu arquivo deve ter |
|---|---|
| **Leads** (contatos) | E-mail e nome |
| **Transacciones** (doações) | Valor (só números), e-mail e nome |

Se faltar o e-mail, a tela deixa você continuar, mas todas as linhas falham. Confira se você o ligou ao campo certo.

**Sobre nomes, telefones e documentos:**

- **Nome e sobrenome:** você pode usar uma só coluna com o nome completo ou colunas separadas para nome e sobrenome. A Afrus aceita as duas formas.
  > **Pendente de confirmação:** se é melhor separar nome e sobrenome para a Afrus guardá-los melhor.
- **Telefones:**
  > **Pendente de confirmação:** em que formato devem estar os telefones (por exemplo, com o código do país e o sinal "+").
- **Tipo de documento:**
  > **Pendente de confirmação:** como deve ser escrito o tipo de documento (por exemplo, com um número ou código equivalente).

**Pessoas repetidas:**

- A Afrus reconhece cada pessoa pelo **e-mail**. Se ela já existe, é **atualizada** com os dados do arquivo que não estejam vazios. Se não existe, é criada.

**Doações repetidas:**

- Cada linha cria uma doação nova. **Se você subir o mesmo arquivo duas vezes, as doações ficam duplicadas.**

> **Importante, permissões de contato:** ao importar, a Afrus marca cada pessoa do arquivo como **aceitando comunicações por todos os canais**, mesmo que antes tenha pedido para sair. Por isso, inclua só pessoas que deram permissão e tire do arquivo quem pediu para não receber mensagens.

**O que a Afrus adiciona sozinha:**

- Cada pessoa importada recebe uma tag automática com a data e a hora da importação (começa com "import-"). Assim você sempre sabe de qual importação ela veio.
- As doações importadas não enviam avisos para sua equipe.

## Resultados de uma importação

Na lista de **Data > Importaciones** você vê todas as suas importações com o **Status**, o **Archivo** (Arquivo), a **Fecha** (Data) e quem fez (**Importación por**, Importado por). Por padrão aparecem as do mês; você pode buscar e mudar as datas.
<!-- captura pendente: resultados-de-uma-importacao-01 — lista de importações com as colunas Status, Archivo, Fecha e Importación por -->

| Status | O que significa |
|---|---|
| **En cola** (Na fila) | Esperando a vez |
| **Procesando** (Processando) | A Afrus está carregando |
| **Finalizado** | Terminou sem erros |
| **Finalizado con errores** (com erros) | Algumas linhas (ou todas) não puderam ser carregadas |

**Se mostrar "Finalizado con errores":**

1. **Abra os erros.** Clique no lápis dessa importação. Você verá as linhas que falharam.
2. **Corrija o arquivo.** Por enquanto, corrigir as linhas nessa tela e reenviá-las não funciona. O mais seguro é corrigir essas linhas no seu arquivo e importar de novo **só essas linhas**.

> **Importante:** "Finalizado con errores" aparece tanto se falharam poucas linhas quanto se falharam todas. Sempre revise o detalhe.

Cada usuário vê só as importações que ele fez. Se não encontrar uma, pergunte à pessoa da sua equipe que a subiu.

---

## Perguntas frequentes

**Quantas linhas posso subir?**
O arquivo pode ter até 20 MB.
> **Pendente de confirmação:** se há um limite de linhas.

**Os contatos importados recebem meus e-mails automáticos?**
> **Pendente de confirmação:** se as pessoas ou doações importadas ativam seus autoresponders ou fluxos de trabalho.

**Recebo um e-mail quando a importação termina?**
Não. O aviso *"Importación finalizada"* aparece dentro do console.

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-26*
