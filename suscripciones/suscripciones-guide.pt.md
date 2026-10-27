# Guia de Assinaturas

Depois de ler este guia, você vai saber o que é o módulo Suscripciones (Assinaturas), para que serve e como filtrar, baixar, modificar, cancelar ou marcar como fraude as doações recorrentes da sua organização.

*Módulo: Suscripciones · Menu: **Suscripciones** · Público: equipes de captação, atendimento a doadores e administração*

> **Sobre os nomes de tela neste guia:** botões, campos e menus estão escritos exatamente como aparecem na versão em espanhol do console, com a explicação em português quando ajuda.

---

## O que é Assinaturas

**Suscripciones é a lista das doações recorrentes da sua organização.** Cada linha é uma assinatura, não cada cobrança mensal: as cobranças de cada mês aparecem em **Transacciones** (Transações) e no histórico do detalhe da assinatura.

A partir daqui você pode buscar e filtrar assinaturas, exportá-las, marcá-las como fraude e abrir o detalhe para modificá-las ou cancelá-las.

## Para que serve

- **Saber quantas assinaturas você tem e em que status estão.** A coluna **Estado** (Status) mostra, por exemplo, se estão ativas, com falha ou canceladas.
- **Encontrar a assinatura de um doador.** Busque por nome, documento, e-mail, telefone ou ID.
- **Baixar um grupo de assinaturas.** Exporte em Excel as assinaturas filtradas para analisá-las ou compartilhá-las.
- **Mudar o valor ou a data de cobrança.** Atenda aos pedidos dos seus doadores sem que precisem doar de novo.
- **Cancelar uma assinatura.** Quando o doador pedir.
- **Marcar assinaturas fraudulentas.** Para tirá-las das suas listas e relatórios.

## Antes de começar

- **Permissões.** Para cancelar ou modificar assinaturas você precisa de permissão para ver e operar assinaturas. Se não vir as opções, peça acesso ao administrador da sua organização.
- **A lista é atualizada ao abri-la ou ao mudar um filtro.** Ela não se atualiza sozinha enquanto está aberta.

---

# Passo a passo

## Como filtrar um grupo de assinaturas

1. **Abra o módulo.** Acesse **Suscripciones**.
   ![Lista de assinaturas com a barra de datas e a linha de filtros](img/como-filtrar-un-grupo-de-suscripciones-01.webp)

2. **Escolha o período.** Use a barra de datas: **1W**, **4W**, **1Y**, **MTD**, **QTD**, **YTD**, **ALL** ou **PERSONALIZADO** (Personalizado, com **DESDE** (De) e **HASTA** (Até)). Por padrão você vê o mês atual (**MTD**).

   > **Importante:** o período filtra pela **data de criação** da assinatura, não pela data de cobrança. Se procura uma assinatura antiga, amplie o período (por exemplo, **ALL**).

3. **Busque um doador (opcional).** Clique em **Buscar por**, escolha **Nombre** (Nome), **Documento de identidad** (Documento), **Correo electrónico** (E-mail), **Teléfono** (Telefone) ou **ID de subscripcion** (ID da assinatura), digite o valor e clique em "Buscar". A busca é feita dentro do período escolhido.

4. **Aplique os filtros da tabela.** Na linha com o ícone de funil, escolha o filtro, marque o que precisa e clique em "Aplicar" (ou "Restablecer" (Redefinir) para limpá-lo):
   - **Valor:** compara o valor, convertido para a moeda da sua organização, com **Mayor que** (Maior que), **Igual que** (Igual a) ou **Menor que**.
   - **Estados** (Status)
   - **Pasarela de pago** (Gateway de pagamento)
   - **Metodo de pago** (Forma de pagamento)
   - **Campaña** (Campanha)
   - **Widgets**
   - **Lapsed:** botão que liga e desliga; mostra só as assinaturas marcadas como caducadas.
   - **Reset:** limpa todos os filtros de uma vez.

5. **Ajuste quantas linhas vê.** Na paginação você pode mostrar 10, 25, 50 ou 100 linhas por página.

Ao terminar, você verá a tabela e o contador atualizados. Os filtros ficam salvos no endereço da página, então você pode copiá-lo e compartilhá-lo com sua equipe.

> **Importante:** a lista nunca mostra assinaturas com status **Fraude**, **Reintentando** (Tentando novamente) ou **Expirada**. Se você escolher **Reintentando** ou **Expirada** no filtro **Estados**, o resultado ficará vazio.

## Como baixar um grupo de assinaturas

1. **Filtre as assinaturas.** Ajuste as datas e os filtros como explicado em "Como filtrar um grupo de assinaturas".

2. **Escolha o que vai exportar.** "Exportar" fica desativado até você marcar pelo menos uma linha.
   - Para exportar só algumas, marque a caixa delas.
   - Para exportar tudo o que foi filtrado, marque a caixa do cabeçalho (seleciona a página) e depois clique em **Seleccionar las N subscripciones de la base.** (Selecionar as N assinaturas da base). Você verá *"Las N subscripciones de tu base estan seleccionadas"* (As N assinaturas da sua base estão selecionadas).
   ![Mensagem para selecionar todas as assinaturas da base](img/como-descargar-un-grupo-de-suscripciones-02.webp)

3. **Exporte.** Clique em "Acciones" (Ações) e escolha **Exportar**.

4. **Confirme.** Na janela **Descargas** (Downloads), escolha o **Tipo de archivo** (Tipo de arquivo) e clique em "Confirmar". Você verá *"El proceso de exportacion ha comenzado, ten en cuenta que puede demorar unos minutos en completarse."* (A exportação começou; pode levar alguns minutos para terminar.)

5. **Baixe o arquivo.** Quando estiver pronto, baixe em **Data > Descargas**. Os arquivos podem ser baixados por até 7 dias depois de gerados.

Ao terminar, você terá um arquivo Excel (.xlsx) com uma linha por assinatura. As cobranças mensais não vão neste arquivo; para isso, baixe em **Transacciones**.

> **Atenção:**
> - O arquivo sempre sai em Excel (.xlsx), mesmo se você escolher CSV.
> - Se você marcou linhas soltas, só essas linhas são exportadas, sem aplicar datas nem filtros.
> - Se exportar toda a base, são aplicadas as datas e os filtros **Valor**, **Estados**, **Pasarela de pago**, **Metodo de pago**, **Campaña** e **Widgets**. **Lapsed** e a busca não são aplicados; se você usou a busca, a exportação pode falhar. Para um resultado confiável, limpe a busca antes de exportar toda a base.
> - Se não escolher nenhum status, o total do arquivo pode não coincidir com o da tabela. Para que coincidam, escolha em **Estados** os status que quer exportar.

## Como mudar a data de cobrança de uma assinatura

1. **Abra a assinatura.** Em **Suscripciones**, clique no **ID** da linha.
   ![Detalhe da assinatura com os botões Enviar Mensaje, Modificar e Cancelar Suscripción](img/como-cambiar-la-fecha-de-cobro-01.webp)

2. **Clique em "Modificar".** Dependendo de como o gateway de pagamento da assinatura está conectado, abre-se uma destas três janelas:

   **Se a janela se chama "Modificar fecha" (Modificar data)** — assinaturas cobradas pelo motor da AFRUS:
   - Escolha uma opção:
     - **Fecha automática (recomendada)** (Data automática, recomendada): mantém a data que a AFRUS calcula.
     - **Fecha de creación de la suscripción** (Data de criação da assinatura): cobra no mesmo dia do mês em que foi criada (se esse dia for maior que 28, usa o dia 28).
     - **Fecha manual** (Data manual): em **Fecha de cobro** (Data de cobrança), escolha um dia de 1 a 28.
   - Se o dia escolhido for depois de hoje, a próxima cobrança será nesse dia deste mês; se for hoje ou antes, nesse dia do mês seguinte.
   - Você também pode mudar o valor.

   **Se a janela se chama "Modificar Suscripción" e mostra "Fecha actual de cobro:" (Data atual de cobrança)**:
   - Em **Fecha** (Data), escolha a nova data de cobrança (deve ser depois de hoje) e, se quiser, mude o **Monto** (Valor).

   **Se a janela se chama "Modificar Suscripción" sem "Fecha actual de cobro:"**:
   - Em **Fecha**, escolha a nova data de cobrança (a partir de amanhã) e, se quiser, mude o **Monto** (maior que 0).

3. **Salve e confirme.** Clique em "Guardar" (Salvar) e depois confirme ("Confirmar", "Confirmar modificación" ou "Actualizar Suscripción", conforme a janela).

Ao terminar, você verá *"Suscripción actualizada correctamente."* ou *"Suscripción actualizada exitosamente"* (Assinatura atualizada com sucesso). Se a assinatura estava **Activa** (Ativa), continua **Activa**.

> **Atenção:**
> - Na janela **Modificar fecha**, a mensagem de confirmação aparece em inglês (*"Update subscription"*); isso é normal.
> - Alguns gateways não permitem mudanças pela AFRUS. Nesse caso você verá *"Este gateway actualmente no soporta la actualización de suscripciones."* (Este gateway não permite atualizar assinaturas no momento.)
> - Assinaturas que esperam a aceitação do pagador não podem ser modificadas: você verá *"Acción no disponible"* (Ação não disponível).
> - Com o gateway Recurrent Payments não há campo de data. A tela informa: *"Los pagos recurrentes se realizan el primer día hábil de cada mes. Si el pago falla, se reintenta semanalmente hasta que sea exitoso."* (Os pagamentos recorrentes são feitos no primeiro dia útil de cada mês. Se o pagamento falhar, é tentado de novo toda semana até dar certo.)

> **Dá para desfazer?** Sim. Clique de novo em "Modificar" e coloque a data ou o valor anteriores.

## Como cancelar uma assinatura

**Antes de começar:** só podem ser canceladas assinaturas com status **Activa** ou **Fallido** (Com falha) — com alguns gateways, também **Pendiente** (Pendente) e **Revisión pendiente** (Revisão pendente). O botão aparece em qualquer status, mas nos demais o cancelamento dá erro.

1. **Abra a assinatura.** Em **Suscripciones**, clique no **ID** da linha.

2. **Clique em "Cancelar Suscripción" (Cancelar assinatura).** É o texto em vermelho do detalhe.
   ![Botão Cancelar Suscripción no detalhe da assinatura](img/como-cancelar-una-suscripcion-02.webp)

3. **Confirme.** Na janela *"¿Estás seguro de que deseas cancelar tu suscripción?"* (Tem certeza de que deseja cancelar sua assinatura?), clique em "Confirmar" (ou "Cerrar" (Fechar) para sair sem cancelar).

Ao terminar, você verá *"La suscripción se ha cancelado correctamente"* (A assinatura foi cancelada com sucesso). A assinatura passa para **Cancelada** e as cobranças pendentes que a AFRUS tinha programado são apagadas. O cancelamento é imediato; não existe a opção de cancelar no fim do período.

> **Dá para desfazer?** Não. Não há botão para reativar a assinatura: como a janela avisa, ela *"no podrá ser reactivada automáticamente"* (não poderá ser reativada automaticamente). Se o doador quiser voltar, precisará criar uma nova doação recorrente.

> **Se algo der errado:**
> - Se você vir *"Error al cancelar la suscripción"* (Erro ao cancelar a assinatura), verifique o status. Dependendo de como sua organização está conectada, alguns gateways também não permitem cancelar pela AFRUS.
> - Se nada acontecer ao clicar em "Confirmar" e nenhuma mensagem aparecer, a assinatura não foi cancelada.
>
> Nos dois casos, escreva para o suporte da AFRUS com o ID da assinatura.

> **Pendente de confirmação:** a janela diz que o doador será notificado, mas não está confirmado que um aviso seja enviado. Se quiser ter certeza, avise o doador você mesmo.

## Como marcar uma assinatura como fraude

> **Importante:** marcar como fraude faz três coisas ao mesmo tempo: a assinatura passa para **Fraude**, some da lista **Suscripciones** e **a pessoa doadora associada é excluída da sua base de Personas (Pessoas)**. Não dá para desfazer.

**Antes de começar:** marcar como fraude só muda o status dentro da AFRUS; não cancela nada no gateway de pagamento. Se o gateway cobra por conta própria (por exemplo Stripe), **cancele a assinatura primeiro** (veja "Como cancelar uma assinatura") para que as cobranças parem.

1. **Selecione as assinaturas.** Em **Suscripciones**, marque a caixa de cada uma. Sem nenhuma marcada, as opções de "Acciones" ficam desativadas.

2. **Escolha a ação.** Clique em "Acciones" e escolha **Marcar como Fraude**.
   ![Menu Acciones com a opção Marcar como Fraude](img/como-marcar-como-fraude-una-suscripcion-02.webp)

3. **Confirme.** Na janela **Marcar como fraude**, clique em "Confirmar". A janela fala em "transacción(es)" (transações): é normal, vale para as assinaturas que você marcou.

Ao terminar, você verá *"Transacciones marcadas como fraude"* (Transações marcadas como fraude) e a tabela será recarregada sem essas assinaturas.

> **Dá para desfazer?** Não. A tela avisa e não há botão para reverter.

> **Atenção:** se você usou **Seleccionar las N subscripciones de la base**, só as linhas da página atual são marcadas, mesmo que a mensagem mencione mais. Marque as assinaturas página por página.

---

## De quanto em quanto tempo as recorrências são cobradas

Depende do gateway de pagamento de cada assinatura:

| Caso | Quem decide a data | O que sabemos |
|---|---|---|
| Gateways que cobram por conta própria (Stripe, PayU, Pagar.me) | O gateway | O gateway decide quando cobra, não a AFRUS |
| Recurrent Payments | O gateway | A tela informa: primeiro dia útil de cada mês; se falhar, nova tentativa semanal até dar certo |
| Assinaturas cobradas pelo motor da AFRUS | A AFRUS | Você pode escolher o dia de cobrança com "Modificar" (veja "Como mudar a data de cobrança") |

Além disso, em **Configuración > Pagos > Servicio de recurrencia** (Configurações > Pagamentos > Serviço de recorrência; tela **Configuración del Motor de Recurrencia**) sua organização pode escolher **Modo mejorado** (Modo aprimorado: Standard ou Charities), **Periodicidad** (Periodicidade: Mensual, Trimestral, Semestral ou Anual) e **Modo de reintento** (Modo de nova tentativa: Standard retries, Charities retries ou Custom). A tela informa: *"Los cambios se aplicarán a los próximos ciclos de cobro."* (As mudanças serão aplicadas aos próximos ciclos de cobrança.)

> **Pendente de confirmação:** o horário exato de cobrança do motor da AFRUS, quantas novas tentativas ele faz quando uma cobrança falha, quando uma assinatura é cancelada sozinha por falhas, e se as periodicidades Trimestral e Semestral e a configuração de **Servicio de recurrencia** já se aplicam às cobranças reais.

## Status de uma assinatura

| Status (coluna **Estado**) | Observação | Aparece na lista? |
|---|---|---|
| **Activa** (Ativa) | | Sim |
| **Pendiente** (Pendente) | Qualquer status que a tela não reconhece também aparece assim | Sim |
| **Fallido** (Com falha) | | Sim |
| **Cancelada** | | Sim |
| **PRENOTIFICATION_OK** (no filtro, **Prenotificada**) | Espera a aceitação do pagador; não pode ser modificada | Sim |
| **Pendiente de confirmación** (Pendente de confirmação) | | Sim |
| **Rechazada** (Recusada) | | Sim |
| **Revisión pendiente** (Revisão pendente) | Há dados do pagador a corrigir (veja abaixo) | Sim |
| **TRIALING** (no filtro, **Reintentando**) | | Não |
| **LAPSED** (no filtro, **Expirada**) | Expirada ou caducada | Não |
| **Fraude** | Marcada como fraude | Não |

**Revisión pendiente:** ao lado do status aparece um lápis. Clique nele, preencha **Número de documento**, **Tipo de documento**, **Número de cuenta** (Número da conta), **Banco**, **Tipo de cuenta** (Tipo de conta) e **Monto** (Valor) em **Editar datos del pagador** (Editar dados do pagador) e clique em "Guardar y reenviar" (Salvar e reenviar). Você verá *"Datos del pagador actualizados y reenvío iniciado"* (Dados do pagador atualizados e reenvio iniciado).

## Limitações conhecidas

- **Marcar como fraude exclui a pessoa doadora** da sua base de Personas. Use só quando tiver certeza.
- **O arquivo de exportação é sempre Excel (.xlsx)**, mesmo se você escolher CSV.
- **Os totais exportados podem não coincidir com a tabela** se você não escolher status, ou se usar **Lapsed** ou a busca. Escolha os status no filtro e limpe a busca antes de exportar.
- **Alguns status aparecem em inglês na tabela** (**PRENOTIFICATION_OK**, **TRIALING**, **LAPSED**), embora no filtro apareçam traduzidos.
- **Reintentando e Expirada no filtro Estados** sempre dão uma lista vazia, porque a lista não mostra esses status.
- **Cohorts, Evolution e "Exportar del datawarehouse"** estão desativados desde 22 de setembro de 2026.

## Perguntas frequentes

**Por que não encontro uma assinatura que sei que existe?**
Verifique o período: ele filtra pela data de criação da assinatura. Tente **ALL**. Lembre também que assinaturas em **Fraude**, **Reintentando** ou **Expirada** não aparecem na lista.

**Onde vejo as cobranças de cada mês?**
Em **Transacciones**, ou no histórico do detalhe da assinatura.

**Posso cancelar no fim do período?**
Não. O cancelamento pela AFRUS é sempre imediato.

**Posso reativar uma assinatura cancelada?**
Não. O doador precisará criar uma nova doação recorrente.

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-20*
