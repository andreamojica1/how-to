# Guia do Boleto Itaú

Depois de ler este guia, você vai saber o que é o **Boleto Itaú**, para que serve e como gerar boletos em lote para um grupo de pessoas e acompanhar a cobrança.

*Módulo: Follow up · Menu: **Follow up > Boleto Itaú** · Público: equipes de captação e financeiro de organizações no Brasil*

> **Sobre os nomes de tela neste guia:** botões, campos e menus estão escritos exatamente como aparecem na versão em espanhol do console, com a explicação em português quando ajuda.

---

## O que é o Boleto Itaú

**O Boleto Itaú é a tela onde você acompanha os lotes de boletos bancários (banco Itaú) que sua organização gera para um grupo de pessoas, e o resultado da cobrança.**

Cada lote prepara um boleto por pessoa, em reais (BRL), e gera o arquivo de remessa que é enviado ao banco. Quando o banco devolve a resposta e você a carrega em **Follow up > Importaciones - itaú**, esta tela mostra quais boletos foram pagos e quais não.

> **Importante:** gerar boletos só está disponível para organizações com país Brasil. O menu aparece em todas as organizações, mas a opção de gerar só aparece nas do Brasil.

## Para que serve

- **Gerar boletos em lote** para um segmento de pessoas, com valor e vencimento comuns.
- **Obter o arquivo de remessa** de cada lote para enviar ao banco.
- **Acompanhar a cobrança**: quantos boletos estão **Generados** (Gerados), **Emitidos sin error** (Emitidos sem erro), **Efectivamente cobrados** (Efetivamente pagos), **Rechazados** (Rejeitados) e **Sin retorno todavía** (Sem retorno ainda).
- **Revisar o detalhe por pessoa**: o status de cada boleto, seus erros e a resposta do banco.

## Antes de começar

- **Sua organização precisa ser do Brasil.**
- **Cada pessoa precisa de CEP, tipo de documento e número de documento.** Se faltar algum, o boleto dela fica com erro. Confira isso no segmento antes de gerar.
- **Tenha o segmento pronto** com as pessoas para quem quer enviar boletos, em **Data > Segmentos > Básico**.

---

# Passo a passo

## Como funciona e como os boletos são gerados

O caminho completo tem quatro momentos:

1. **Você gera o lote** na AFRUS (passos abaixo).
2. **Você baixa o arquivo de remessa** e o envia ao banco Itaú. Esse envio é feito fora da AFRUS.
3. **O banco entrega um arquivo de retorno** com o resultado de cada boleto.
4. **Você carrega esse arquivo** em **Follow up > Importaciones - itaú**: a AFRUS registra as doações pagas e atualiza os indicadores desta tela (veja o guia de Importaciones - itaú).

### Parte 1 — Gerar o lote

1. **Abra o Boleto Itaú.** Acesse **Follow up > Boleto Itaú** e clique em "Crear Boleto Remessa" (Criar boleto remessa). Ele leva a **Segmentos**; você também pode ir direto a **Data > Segmentos > Básico**.
   ![Tela Procesos de generación de boleto com o botão Crear Boleto Remessa](img/boleto-itau-01.webp)

2. **Escolha o segmento.** Selecione o segmento e abra **Acciones** (Ações) > **Generar Archivos de Remessa (Boleto Brasil)** (Gerar arquivos de remessa). Também dá para fazer em **Personas** (Pessoas): selecione as pessoas e use a mesma opção em **Acciones**.

3. **Defina valor e vencimento.** Em **Generar archivo de remessa**, preencha **Monto (BRL)** (Valor, mínimo R$ 2,99) e **Fecha de vencimiento** (Data de vencimento — precisa ser depois de hoje; por padrão, daqui a 3 meses). O valor e o vencimento são os mesmos para todos os boletos do lote.

4. **Crie o arquivo.** Clique em "Crear archivo de remessa" (Criar arquivo de remessa).

Você verá *"El archivo de Remessa se está generando. En unos minutos podrás descargar el archivo."* (O arquivo de remessa está sendo gerado. Em alguns minutos você poderá baixá-lo.) com o botão "Ver procesos" (Ver processos). Um lote é criado em **Procesos de generación de boleto** (Processos de geração de boleto).

> **Dá para desfazer?** **Pendente de confirmação:** se um lote gerado pode ser cancelado. Confira bem o segmento, o valor e o vencimento antes de criar o arquivo.

### Parte 2 — Baixar e acompanhar o lote

5. **Espere o lote terminar.** Em **Follow up > Boleto Itaú** você verá o lote com o status e o **%** de avanço. A tela não se atualiza sozinha: recarregue para ver o avanço.

6. **Baixe o arquivo.** Quando estiver pronto, escolha "Descargar" (Baixar) no menu da linha. Esse é o arquivo que você envia ao banco.

7. **Revise o detalhe por pessoa.** No menu da linha, escolha "Ver detalle por lead" (Ver detalhe por lead). Você verá o status de cada boleto, seus erros, a transação e, quando carregar a resposta do banco, o **Estado de retorno** (Status de retorno).

---

## Indicadores

Aparecem no geral, na lista, e por lote, no detalhe.

| Indicador | O que significa |
|---|---|
| **Generados** (Gerados) | Total de boletos gerados |
| **Emitidos sin error** (Emitidos sem erro) | Boletos gerados corretamente, sem erro nos dados da pessoa nem do gateway de pagamento |
| **Efectivamente cobrados** (Efetivamente pagos) | Boletos que, ao carregar o arquivo de retorno do banco, ficaram confirmados como doação na AFRUS. Inclui o valor recebido |
| **Rechazados** (Rejeitados) | Boletos que o banco informou como rejeitados no arquivo de retorno |
| **Sin retorno todavía** (Sem retorno ainda) | Boletos emitidos para os quais ainda não foi carregado um arquivo de retorno |

## Status de retorno por pessoa

| Status | O que significa | O que você pode fazer |
|---|---|---|
| **Sin retorno** (Sem retorno) | A resposta do banco para este boleto ainda não foi carregada | Carregar o arquivo de retorno quando o banco entregar |
| **Cobrado** (Pago) | O banco confirmou e ficou registrado como doação na AFRUS | Nada |
| **Rechazado** (Rejeitado) | O banco rejeitou | Revisar o caso com a pessoa |
| **Pagado - no registrado** (Pago - não registrado) | O banco confirmou o pagamento, mas não ficou registrado como doação, normalmente por dados incompletos (CEP ou documento) | Completar os dados da pessoa |
| **Otro** (Outro) | Outra resposta do banco | Revisar o detalhe |

> **Pendente de confirmação:** como registrar a doação de um boleto **Pagado - no registrado** depois de completar os dados.

## Status de um lote

Aparecem em inglês, como estão: `created` (criado), `queued` (na fila), `pending` (em processamento), `succeeded` (concluído com sucesso) e `failed` (falhou).

## Com que frequência é atualizado

- **A geração acontece em segundo plano** e leva alguns minutos, segundo a mensagem da tela.
- **A tela não se atualiza sozinha.** Ela carrega ao ser aberta e ao mudar de página.
- **Os indicadores de cobrança** mudam quando o arquivo de retorno do banco é carregado em **Follow up > Importaciones - itaú**.

## Perguntas frequentes

**A AFRUS envia o arquivo ao banco?**
Não. Você baixa o arquivo de remessa e o envia ao banco fora da AFRUS.

**Quais dados bancários o arquivo usa e quem os configura?**
> **Pendente de confirmação:** quais dados bancários da organização (agência, conta, carteira) o arquivo usa e como são configurados. Fale com a gente para revisar.

**Ao gerar o boleto é criada uma transação pendente?**
> **Pendente de confirmação.**

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-20*
