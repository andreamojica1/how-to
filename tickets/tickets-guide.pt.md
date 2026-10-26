# Guia de Tickets

Depois de ler este guia, você vai saber o que são os Tickets de rifa na Afrus, como vendê-los com um widget de produto e como enviar a cada comprador os números dele no autoresponder.

*Módulo: Tickets · Menu: **Fundraising > Tickets** · Público: equipes de captação, eventos e comunicação*

> **Sobre os nomes de tela neste guia:** botões, campos e menus estão escritos exatamente como aparecem na versão em espanhol do console, com a explicação em português quando ajuda.

---

## O que são os Tickets

**Um Ticket é uma rifa com uma faixa de números, por exemplo do 1 ao 500.** Quando você a vincula a um widget de produto, cada comprador recebe um número de ticket consecutivo para cada unidade que compra.

> **Importante:** a venda de ingressos para eventos com QR code ainda não está disponível. Hoje, **Tickets** é usado para rifas.

## Para que serve

- **Vender números de rifa on-line.** Você os vende por um widget, com preço por ticket.
- **Atribuir os números automaticamente.** Cada comprador recebe seus números, e você pode mostrá-los na página de agradecimento e no autoresponder.
- **Saber quem comprou cada número.** Você vê a pessoa, a transação, o widget e o país de cada ticket, para fazer o sorteio e contatar o ganhador.

## Com que frequência é atualizado

- **Os números são atribuídos na hora**, no momento em que a compra é registrada no widget.
- **As telas mostram os dados ao abrir.** A lista **Tickets generados por transacción** (Tickets gerados por transação) e a seção **Productos y tickets** (Produtos e tickets) do painel do widget consultam os dados quando você abre a tela ou muda um filtro. Não há processo para esperar.
- **Elas não se atualizam sozinhas.** Para ver compras novas, recarregue a tela ou busque de novo.

---

# Passo a passo

## Como criar um widget de produto

Para vender tickets você precisa de duas coisas: a rifa (o Ticket, com sua faixa de números) e um widget com o objetivo **Producto** (Produto) que a venda.

### Parte 1 — Crie a rifa

1. **Abra Tickets.** Acesse **Fundraising > Tickets** e clique em "Crear Ticket" (Criar ticket).
   ![Tela Tickets com o botão Crear Ticket e a lista de tickets](img/como-crear-un-widget-de-producto-01.webp)

2. **Dê um nome.** Preencha **Nombre** (Nome, no mínimo 3 caracteres).

   > **Importante:** para poder adicionar a rifa a um widget, o nome não pode passar de 25 caracteres e a descrição de 80.

3. **Escreva uma descrição.** Preencha **Descripción** (Descrição, até 500 caracteres). Embora a tela não a marque como obrigatória, se ficar vazia você verá *"Error al crear ticket"* (Erro ao criar ticket).

4. **Escolha o status.** Em **Estado** (Status), deixe **Activo** (Ativo) — é a opção padrão.

5. **Defina a faixa.** Em **Rango** (Faixa), informe **Número Inicial** (no mínimo 1) e **Número Final**, que deve ser maior que o inicial. O primeiro comprador recebe o Número Inicial.

6. **Crie a rifa.** Clique em "Crear Ticket". Você verá *"Ticket creado exitosamente"* (Ticket criado com sucesso) e a rifa aparecerá na **Lista de Tickets** com seu **ID**.

### Parte 2 — Crie o widget que a vende

7. **Crie um widget novo.** Acesse **Fundraising > Widgets** e clique em "Nuevo widget" (Novo widget). O editor de widgets abre em uma nova aba. Esta tela abre na versão anterior da Afrus, por isso tem uma aparência diferente.

8. **Escolha o objetivo Produto.** Em **Objetivo**, escolha **Producto**. Só os widgets com esse objetivo atribuem números de ticket.

   > **Pendente de confirmação:** em que tela exata do editor se escolhe o objetivo e se adiciona o bloco **Producto**.

9. **Adicione o produto.** Adicione o bloco **Producto** e clique em "Agregar Producto" (Adicionar produto). Em **Tipo de Producto** (Tipo de produto), escolha **Ticket**.

10. **Escolha a rifa.** Em **Seleccionar Ticket** (Selecionar ticket), escolha sua rifa. O **Nombre del producto** (nome do produto), a **Descripción del producto** (descrição), o **Límite Inicial**, o **Límite Final** e o **Stock del producto** (estoque) são preenchidos sozinhos e não podem ser editados.

11. **Defina o preço.** Digite o **Precio del producto** (preço do produto): é o preço de cada ticket. Só aceita números. A tela não o exige, então confira se você o preencheu.

12. **Confirme o produto.** Clique em "Agregar Producto". Você verá *"¡Producto agregado satisfactoriamente!"* (Produto adicionado com sucesso).

13. **Salve e publique o widget.** Faça como com qualquer outro widget.

Ao terminar, no widget o doador escolhe quantos tickets quer. Na página final, ele vê um cartão por ticket, com **Cantidad** (Quantidade), **Precio unitario** (Preço unitário) e o rótulo "Ticket <número>".

> **Importante:** cada widget aceita uma única rifa, e no mesmo bloco não é possível misturar produtos comuns com tickets (*"No se pueden mezclar tipos de productos"*).

## Como incluir no meu autoresponder o número do ticket e a quantidade de tickets comprados

**Antes de começar:** você precisa de um autoresponder de transação (e-mail ou WhatsApp) que seja enviado para as compras feitas no seu widget de produto com ticket.

1. **Abra o editor do seu autoresponder.** Acesse **Interacciones > Autoresponders** e abra o autoresponder.
2. **Abra o mapa de merge tags.** Abra **Merge tags** (**Mapa de merge tags**) e procure a categoria **Merge Tags de Rifas** (Merge tags de rifas). Ao clicar em um cartão, o merge tag é copiado.
   ![Mapa de merge tags com a categoria de rifas selecionada](img/como-incluir-ticket-en-autoresponder-02.webp)
3. **Cole os merge tags no seu texto.** Escreva-os exatamente assim:

   | Merge tag | Nome no mapa | O que mostra |
   |---|---|---|
   | `{{ticket_id}}` | Ticket ID | **Todos** os números de ticket daquela compra, separados por vírgula (ex.: `0042, 0043, 0044`) |
   | `{{raffle_name}}` | Raffle Name | Nome da rifa |
   | `{{raffle_description}}` | Raffle Description | Descrição da rifa |
   | `{{raffle_price}}` | Price | Preço de um ticket |
   | `{{raffle_reference}}` | Reference | Número da transação (ID da doação) |

4. **Mostre a quantidade com os números.** Não existe merge tag de quantidade. Como é gerado um número para cada ticket comprado, a quantidade é igual a quantos números aparecem em `{{ticket_id}}`. Por exemplo: *"Seus números da rifa {{raffle_name}} são: {{ticket_id}}"*.

Quando o e-mail ou o WhatsApp é enviado, cada merge tag é substituído pelo dado daquela compra. Você pode usar os mesmos merge tags na página de agradecimento.

> **Importante:** o mapa também mostra "Número de Ticket" e "Fecha de Sorteo" (data do sorteio), mas eles não correspondem a nenhum merge tag real de rifas. Use apenas os da tabela.

> **Pendente de confirmação:** se, com algum tipo de pagamento, o autoresponder pode sair antes de os números existirem. Faça uma compra de teste para conferir sua mensagem.

## Como ver quem comprou cada número

1. **Abra a rifa.** Em **Fundraising > Tickets**, clique no **ID** da rifa. Abre **Tickets generados por transacción**.
2. **Ajuste as datas.** Por padrão, mostra do início do mês até hoje.
3. **Filtre se precisar.** Em **Buscar por**, escolha **ID de Lead**, **ID de Donación** (ID da doação), **Email de Lead**, **Nombre de Ticket** (nome do ticket) ou **Descripción de Ticket** (descrição do ticket), digite o valor e pressione Enter.

Você verá uma linha por número, com **ID de Ticket**, **Nombre**, **Precio**, **ID de Donación**, **ID de Lead**, **Cantidad** (sempre 1), **Nombre de Widget** e **Código de País** (código do país).

---

## Dados e status

| Dado | O que significa |
|---|---|
| **Activo** / **Inactivo** (Ativo / Inativo) | É só um rótulo. Uma rifa **Inactivo** que já está em um widget publicado continua vendendo |
| **ID de Ticket** | Número atribuído, com zeros à esquerda até o tamanho do Número Final (com Número Final 500, o 42 aparece como `042`) |
| **Cantidad** | Sempre 1 por linha: cada ticket comprado é uma linha |
| **Tickets vendidos** (painel do widget) | Tickets vendidos em compras **aprovadas** no período |

## Limitações conhecidas

- **Confira antes do sorteio.** Também são atribuídos números a compras com pagamento recusado; esses números ficam ocupados. Confira o status de cada transação pelo link **ID de Donación**. Por isso **Tickets vendidos** (só compras aprovadas) pode não bater com a lista.
- **Números repetidos.** Se duas compras acontecerem quase ao mesmo tempo, elas podem receber o mesmo número. Antes do sorteio, confira se não há números repetidos em **Tickets generados por transacción**.
- **A venda não para sozinha no Número Final.** Podem ser atribuídos números acima da faixa. Controle o estoque do produto no widget.
- **Stock del producto** é uma unidade menor que a quantidade real da faixa (do 1 ao 100 mostra 99).
- **Inactivo não interrompe a venda.** Para parar de vender, retire o produto do widget ou desative o widget.
- **Cada rifa tem sua própria numeração.** Identifique um ticket sempre pela rifa e pelo número.
- **Preço em US$.** A coluna **Precio** de **Tickets generados por transacción** sempre mostra o símbolo de dólar, seja qual for a moeda do widget.
- **Só as 10 rifas mais recentes.** **Seleccionar Ticket** mostra só as 10 rifas criadas mais recentemente; as mais antigas não podem ser escolhidas.
- **Não é possível excluir uma rifa**, só editá-la. Você pode editar a faixa mesmo depois de vender números.

## Perguntas frequentes

**Posso vender ingressos para eventos com QR code?**
Ainda não. Essa função está em desenvolvimento.

**Existe um merge tag com a quantidade de tickets comprados?**
Não. Use `{{ticket_id}}`, que lista todos os números da compra.

**Posso colocar duas rifas no mesmo widget?**
Não. Cada widget aceita uma única rifa.

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-20*
