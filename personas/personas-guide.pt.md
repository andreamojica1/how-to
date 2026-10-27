# Guia de Personas (Pessoas)

Depois de ler este guia, você vai saber o que é Personas, para que serve e como criar, filtrar, baixar, gerenciar e excluir seus contatos, além de usar tudo o que o perfil de cada pessoa oferece.

*Módulo: Personas (Pessoas) · Menu: **Personas** · Público: equipes de captação, relacionamento com doadores e comunicação*

> **Sobre os nomes de tela neste guia:** botões, campos e menus estão escritos exatamente como aparecem na versão em espanhol do console, com a explicação em português quando ajuda.

---

## O que é Personas

**Personas é a base de contatos da sua organização na AFRUS.** Ali está cada pessoa que se cadastrou, doou ou foi criada manualmente pela sua equipe, com seus dados, tags, consentimentos de comunicação (opt-in), transações, assinaturas, notas, lembretes e o histórico do que ela fez.

Ao entrar, você verá os **Indicadores globales** (Indicadores globais: **Total de personas**, **Activos**, **Suscriptores** e **Monto total** — total de pessoas, ativos, assinantes e valor total), uma busca, uma barra de datas, os botões "Crear persona" (Criar pessoa), "Acciones" (Ações) e "Ver procesos" (Ver processos), e a tabela de pessoas. Ao clicar no **ID** de uma pessoa, abre-se o perfil dela, com as abas **Contacto** (Contato), **Transacciones** (Transações), **Subscripciones** (Assinaturas), **Recordatorios** (Lembretes), **Notas** e **Eventos**.

## Para que serve

- **Encontrar seus contatos.** Busque e filtre por tag, tipo, scoring, campanha, widget, UTM, se são contatáveis e datas.
- **Conhecer cada pessoa.** Veja o perfil completo e o histórico de tudo o que ela fez.
- **Registrar e cobrar doações.** Registre doações manuais, cobre em um cartão salvo ou crie assinaturas pelo perfil.
- **Respeitar as preferências.** Gerencie o consentimento de comunicação (opt-in) por canal.
- **Falar diretamente com ela.** Envie um link de pagamento personalizado ou um e-mail.
- **Trabalhar com grupos.** Exporte, aplique tags ou exclua grupos de pessoas.

## Antes de começar

- **Permissões.** Para excluir pessoas, seu usuário precisa de permissão para editar pessoas.

---

# Passo a passo

## Como criar uma pessoa

1. **Abra o formulário.** Em **Personas**, clique em "Crear persona" (Criar pessoa).
   ![Formulário Crear Persona com Información Básica, Más información, Etiquetas e Opt In](img/como-crear-una-persona-01.webp)

2. **Preencha os dados.** O **Correo electrónico** (e-mail) é obrigatório e precisa ter formato válido; **Nombre** (nome) e **Apellido** (sobrenome) só aceitam letras. Você também pode preencher **Número de teléfono** (telefone), **Tipo de documento**, **Documento**, **Campaña** (campanha), **Widget**, data de nascimento, país, estado, cidade, CEP, fuso horário, endereço, empresa e **Etiquetas** (tags). Quanto mais dados você preencher, melhor poderá segmentar depois.

3. **Preencha os campos personalizados.** A seção **Información Personalizada** (Informação personalizada) mostra os campos próprios da sua organização.

4. **Registre o consentimento, se houver.** Marque **Aceptación de términos y condiciones y políticas de privacidad** (aceite dos termos, condições e políticas de privacidade) somente se a pessoa aceitou receber comunicações. Essa caixa aceita **todos** os canais de comunicação de uma vez.

5. **Salve.** Clique em "Guardar" (Salvar) para voltar à lista, ou em "Guardar y crear otro" (Salvar e criar outro) para limpar o formulário e criar outra pessoa.

Ao terminar, você verá *"Lead creado con éxito"* (Lead criado com sucesso) e a pessoa aparecerá na lista.

> **Importante:** não é possível criar uma pessoa com um e-mail que já existe na sua organização. Se você tentar, o erro pode aparecer como o texto técnico `already_exists_email`: significa que esse e-mail já está cadastrado. Procure-o na lista e edite essa pessoa.

## Como filtrar um grupo de pessoas

1. **Use a barra de filtros.** Acima da tabela há **Tags**, **Tipo** (**Lead**, **Activo** — ativo — ou **Recurrente** — recorrente), **Scoring** (uma faixa), **Campaña** (campanha), **Widgets**, **UtmCampaign** e o botão "Solo contactables" (Somente contatáveis).
   ![Barra de filtros de Personas com Tags, Tipo, Scoring, Campaña, Widgets, UtmCampaign e Solo contactables](img/como-filtrar-un-grupo-de-personas-01.webp)

2. **Busque alguém específico.** Na busca, escolha pesquisar por **Nombre** (nome), **Documento de identidad** (documento de identidade), **Correo electrónico** (e-mail), **Teléfono** (telefone) ou **ID de Lead**.

3. **Ajuste as datas.** A barra de datas filtra pela data de criação da pessoa.

4. **Revise ou limpe os filtros.** Cada filtro ativo aparece como uma tag que você pode remover pelo X. Para limpar tudo, clique em "Restablecer" (Redefinir).

Ao terminar, a tabela e o texto *"Total de personas que coinciden: N."* (Total de pessoas correspondentes: N.) são atualizados.

> **Importante:** ao abrir a lista, o período é **o mês atual**. Assim que você aplica um filtro ou uma busca, o período passa para **ALL** (todas as datas).

- **Widget de origen** (widget de origem) e **UTM Campaign de origen** (UTM de origem) mostram o primeiro cadastro da pessoa. Se você filtrar por outro widget ou UTM e ela aparecer, é porque também pertence a ele, embora tenha se cadastrado primeiro no que é mostrado.
- **Solo contactables** deixa de fora hard bounces, descadastros e e-mails desativados. Por isso os totais podem ser menores que os de Segmentos.

## Como baixar um grupo de pessoas

1. **Filtre a lista.** Aplique os filtros, a busca e as datas de que precisa.

2. **Escolha quais linhas exportar (opcional).** Marque as linhas que quiser. Se marcar a página inteira, aparece o link **Seleccionar las N personas de la base.** (Selecionar as N pessoas da base).

3. **Abra a exportação.** Clique em "Acciones" (Ações) e escolha "Exportar".
   ![Janela Descargas com Fuente de datos e Tipo de archivo](img/como-descargar-un-grupo-de-personas-03.webp)

4. **Escolha a fonte de dados.** Em **Fuente de datos** (Fonte de dados), escolha **Base de datos en tiempo real** (base em tempo real: dados atuais) ou **Datos analizados** (dados analisados: *"Estos datos se actualizan cada 24 horas"* — atualizados a cada 24 horas).

5. **Escolha o formato e confirme.** Em **Tipo de archivo** (Tipo de arquivo), escolha xlsx ou csv e clique em "Confirmar".

Ao terminar, você verá *"El proceso de exportacion ha comenzado, ten en cuenta que puede demorar unos minutos en completarse."* (A exportação começou; pode levar alguns minutos) com o link **Ir a descargas** (Ir para downloads). O arquivo fica em **Data > Descargas** e pode ser baixado por até 7 dias depois de gerado.

- Se você marcou linhas (sem selecionar a base inteira), só elas são exportadas. Se não marcou nada ou escolheu a base inteira, são exportadas as pessoas que atendem aos filtros, à busca e às datas.
- A exportação em tempo real inclui uma coluna para cada campo personalizado.
- Pessoas marcadas como spam não são exportadas.
- Se ninguém corresponder, você verá *"No se encontraron personas que coincidan con los filtros seleccionados. Ajusta los criterios e intenta nuevamente."* (Nenhuma pessoa corresponde aos filtros. Ajuste os critérios e tente de novo.)

> **Importante:** o filtro "Solo contactables" não é aplicado à exportação: o arquivo pode incluir pessoas não contatáveis mesmo com o filtro ativo. Por enquanto não há alternativa nesta tela; revise o arquivo antes de usá-lo em um envio.

## Como ver os eventos de uma pessoa

1. **Abra o perfil.** Em **Personas**, clique no **ID** da pessoa.

2. **Entre na aba Eventos.** No topo você verá o **Estado opt-in / opt-out** de cada canal (*"Activo desde …"* — ativo desde… — ou *"No registrado"* — não registrado).
   ![Aba Eventos do perfil com Estado opt-in / opt-out e Registro de eventos](img/como-ver-los-eventos-de-una-persona-02.webp)

3. **Percorra o histórico.** Em **Registro de eventos** você verá o **Total de eventos**, agrupado por mês. São carregados 10 eventos e aparecem mais ao rolar. Dá para filtrar por datas.

4. **Abra um evento.** Clique nele para ver o detalhe: **ID del evento** (ID do evento), **Monto** (valor), **Score** e, se for uma mensagem, o modelo, o remetente e o destinatário, entre outros dados.

5. **Atualize a lista se precisar.** O botão com o horário da última atualização recarrega os eventos.

## Como ativar ou desativar o opt-in

1. **Abra a janela de opt-in.** No perfil da pessoa, clique em "Editar Opt In".
   ![Janela Editar Opt In com a aceitação universal e os canais de comunicação](img/como-activar-o-desactivar-el-opt-in-01.webp)

2. **Marque ou desmarque os consentimentos.**
   - **Aceptación de terminos y Condiciones Universal** (aceite universal dos termos): marca tudo e bloqueia as outras opções.
   - **Aceptación de terminos condiciones** (aceite dos termos).
   - **Aceptación de comunicaciones de marketing** (aceite de comunicações de marketing): marca ou desmarca todos os canais de uma vez.
   - **Recibir comunicaciones por** (receber comunicações por), canal a canal: email, sms, whatsapp, voice (voz) e direct_mail (correio).

3. **Salve.** Clique em "Guardar" (Salvar). Assim seus envios respeitam o que a pessoa aceitou.

Ao terminar, você verá *"El Opt In se ha cambiado correctamente"* (Opt-in alterado com sucesso). O cartão **Opt in** do perfil mostra **Sí** (Sim) se houver consentimento em pelo menos um canal (passe o mouse para ver quais), e a aba **Contacto** mostra **Opt In WhatsApp**, **Opt In Email** e **Opt In SMS**.

> **Importante:** enquanto **Aceptación de terminos y Condiciones Universal** estiver marcada, as outras opções ficam bloqueadas. Para remover um canal, desmarque-a primeiro.

> **Dá para desfazer?** Sim. Abra "Editar Opt In" de novo e mude as caixas.

## Como excluir uma pessoa

**Uma pessoa, pelo perfil:**

1. **Abra o perfil e clique em "Borrar" (Excluir).**
2. **Confirme.** Na janela *"Eliminar persona"* / *"¿Estás seguro que deseas eliminar esta persona?"* (Excluir pessoa / Tem certeza de que deseja excluir esta pessoa?), confirme.

Você verá *"La persona se ha eliminado correctamente"* (Pessoa excluída com sucesso) e voltará para **Personas**. Se a pessoa tinha assinaturas com Débito Recurrente Bancario ou Recurrent Payments, elas são canceladas na hora nesse gateway.

**Várias pessoas, pela lista:**

1. **Marque as linhas.** Marque pelo menos uma linha, ou selecione a base inteira.
2. **Escolha Excluir.** Clique em "Acciones" (Ações) e escolha "Eliminar" (Excluir). Confirme *"¿Estás seguro de que deseas eliminar a las personas seleccionadas?"* (Tem certeza de que deseja excluir as pessoas selecionadas?).
3. **Se escolheu a base inteira, confirme por escrito.** Aparece *"[CUIDADO] Zona de peligro"* ([CUIDADO] Zona de perigo) e você precisa digitar `borrar_toda_la_base` para confirmar.

Você verá *"El proceso de borrado de leads ha comenzado, ten en cuenta que puede demorar unos minutos en completarse."* (A exclusão começou; pode levar alguns minutos.)

> **Dá para desfazer?** Não. *"Esta acción es irreversible. Eliminará permanentemente a la persona, junto con todas sus acciones, eventos, transacciones y suscripciones asociadas."* (Esta ação é irreversível. Excluirá permanentemente a pessoa, com todas as suas ações, eventos, transações e assinaturas.) Se você só quer parar de se comunicar com ela, desative o opt-in em vez de excluí-la.

> **Importante:** evite excluir pessoas que tenham ou tenham tido transações ou assinaturas: essas transações e assinaturas ficarão órfãs e você perde a rastreabilidade delas.

## Como ver as transações e assinaturas de uma pessoa

1. **Abra o perfil.** Em **Personas**, clique no **ID** da pessoa.

2. **Confira o resumo.** A aba **Contacto** mostra os cartões **Total transacciones** (total de transações), **Valor de transacciones** (valor das transações), **Valor Medio** (valor médio), **Ingresos por suscripciones** (receita de assinaturas) e **Scoring**.

3. **Abra a aba Transacciones.** Você verá cada pagamento com **ID**, **Fecha** (data), **Tipo de frecuencia** (tipo de frequência), **Estado** (status), **Valor**, **Pasarela de pago** (gateway de pagamento), **Metodo de pago** (forma de pagamento), **Email**, **Widget**, **Campaña**, **URL**, **Campaign Code** e **UTM campaign**. No menu de cada linha, **Detalles** (Detalhes) abre a transação em outra aba, e **Reembolsar** aparece só em transações aprovadas de gateways que permitem reembolso.
   ![Aba Transacciones do perfil com a lista de pagamentos da pessoa](img/como-ver-las-transacciones-y-suscripciones-de-una-persona-03.webp)

4. **Abra a aba Subscripciones.** Em *"Lista de Subscripciones"* (Lista de assinaturas) você verá **ID de subscripción** (ID da assinatura), **Monto** (valor), **Estado** (status) e **Fecha de creación** (data de criação).

## Para que servem e como usar os lembretes e as notas

**Lembretes: para não esquecer um acompanhamento.** Você agenda um aviso sobre a pessoa e, na data, a AFRUS envia um e-mail para você (o usuário que o criou) com o nome, o e-mail e o telefone da pessoa e a sua mensagem.

1. **Crie o lembrete.** No perfil, aba **Recordatorios**, clique em "Crear recordatorio" (Criar lembrete).
2. **Preencha.** Escreva **Nombre** (nome) e **Mensaje** (mensagem), escolha a data em **Seleccionar Fecha** (Selecionar data) e o horário, e salve.

Você verá *"El recordatorio se ha creado correctamente"* (Lembrete criado com sucesso). A *"Lista de recordatorios"* mostra **ID**, **Nombre**, data de criação e **Estado**, com filtros por **Estado** (**Creado** — criado, **Completado** — concluído, **Programado** — agendado, **Todos**) e por datas. Cada linha pode ser editada ou excluída. A AFRUS verifica os lembretes a cada 10 minutos, então o e-mail pode chegar até uns 10 minutos depois do horário escolhido; depois de enviado, o status passa para **Completado**.

**Notas: para registrar o que já aconteceu.** Servem para registrar uma interação que já ocorreu com a pessoa, para que toda a equipe tenha o contexto.

1. **Crie a nota.** No perfil, aba **Notas**, clique em "Crear nota" (Criar nota).
2. **Preencha.** Escolha a **Categoría** (categoria: **General** — geral, **Correo** — e-mail, **Teléfono** — telefone, ou **Reunión** — reunião) e a **Fecha** (data), e escreva a **Descripción** (descrição, até 500 caracteres).
3. **Salve.** Clique em "Crear nota".

Você verá *"La nota se ha creado correctamente"* (Nota criada com sucesso). A *"Lista de notas"* mostra **Responsable** (quem a criou), **Fecha**, **Categoría** e **Nota**; dá para filtrar por categoria, atualizar e excluir notas.

## Onde ver as informações dos campos personalizados

- **No perfil:** aba **Contacto**, cartão **Más información** (Mais informações), seção **Información Personalizada** (Informação personalizada). Cada campo aparece com seu valor, ou com "-" se estiver vazio. A seção só aparece se a pessoa tiver algum campo personalizado.
- **Ao criar ou editar:** são preenchidos na seção **Información Personalizada** de "Crear persona" ou de "Editar" (na aba **Contacto**).
- **Na exportação:** saem como colunas ao baixar com **Base de datos en tiempo real**.
- **Onde são definidos:** em **Ajustes de Organización > Campos personalizados**.

## Como enviar links personalizados para uma pessoa

**Antes de começar:** sua organização precisa de um Business profile com URL e de um widget de doação padrão.

1. **Abra o quadro de link de pagamento.** No perfil da pessoa, aba **Contacto**, encontre o quadro **Link de pago** (link de pagamento). O nome e o e-mail da pessoa já vêm preenchidos.
   ![Quadro Link de pago na aba Contacto do perfil](img/como-enviar-links-personalizados-01.webp)

2. **Escolha a frequência.** Em **Seleccionar la frecuencia** (Selecionar a frequência), escolha **Único** ou **Mensual** (mensal).

3. **Defina o valor.** Digite o **Monto** (valor, maior que 0) ou ative **Valor abierto** (valor aberto) para que a pessoa escolha quanto doar.

4. **Personalize a mensagem.** Escreva a **Mensaje personalizado** (mensagem personalizada). Uma mensagem próxima aumenta as chances de doação.

5. **Defina a validade (opcional).** Marque **Caducar enalce** (expirar link) e escolha data e hora.

6. **Envie.** Clique em "Enviar" e confirme *"Desea enviar el link de pago?"* (Deseja enviar o link de pagamento?).

Ao terminar, você verá *"¡Link de pago creado con éxito!"* (Link de pagamento criado com sucesso!) e *"Link de pago enviado exitosamente al siguiente correo: …"* (Link enviado para o seguinte e-mail: …). O link leva à página do seu Business profile.

- Pelo perfil, o link é enviado só por e-mail, para o e-mail da pessoa.
- Enviar o link cadastra a pessoa no widget padrão.
- **Outra opção:** o botão "Enviar Mensaje" (Enviar mensagem) do perfil envia um e-mail livre para a pessoa, com remetente, **Asunto** (assunto) e **Mensaje** (mensagem).

## Como criar uma nova transação e uma nova assinatura pelo perfil de uma pessoa

### Nova transação

1. **Abra a janela.** No perfil, clique em "Nueva transacción" (Nova transação).

2. **Escolha o tipo e clique em "Continuar".**
   - **Electrónica** (Eletrônica — *"Pagos con tarjeta, Paypal u otros medios digitales"*: cartão, PayPal ou outros meios digitais): cobra em um cartão salvo da pessoa ou em outro meio configurado.
   - **Manual** (*"Pagos en efectivo, consignación, billetera o cheque"*: dinheiro, depósito, carteira ou cheque): registra um pagamento que você já recebeu fora da AFRUS.

3. **Preencha os dados.**
   - Em **Electrónica**: **Método de pago** (forma de pagamento — o cartão usado mais recentemente aparece primeiro, marcado **Usado recientemente**), **Monto** (valor), **Moneda** (moeda), **Campaña** e **Widget**.
   - Em **Manual**: **Método de pago** (**Efectivo** — dinheiro, **Cheque**, **Transferencia** — transferência, ou **Billetera digital** — carteira digital), **Monto**, **Moneda**, **Referencia (Opcional)**, **Fecha de transacción** (data da transação), **Fecha de registro en afrus** (data de registro na AFRUS), **Campaña** e **Widget**. Se o widget for de produtos, você escolhe produtos e quantidades e o valor é calculado automaticamente.
   - O **Widget** é escolhido depois da **Campaña**.

4. **Crie a transação.** Clique em "Crear transacción" (Criar transação).

Você verá *"La transacción se ha creado correctamente"* (Transação criada com sucesso).

> **Importante:** a opção **Electrónica** só fica disponível se a pessoa já tiver uma transação com cartão aprovada em um gateway que permite cobranças manuais. Caso contrário, você verá *"No hay pasarelas de pago configuradas"* (Não há gateways de pagamento configurados); nesse caso, você pode registrar um pagamento já recebido com **Manual**.

### Nova assinatura

1. **Abra a janela.** No perfil, clique em "Nueva suscripción" (Nova assinatura); abre-se a janela *"Nueva subscripcion"*.

2. **Escolha a forma de pagamento e o valor.** Em **Metodo de pago**, escolha um cartão salvo da pessoa ou outro meio configurado, e digite o **Monto** (obrigatório, maior que 0).

3. **Escolha o dia da cobrança, se aparecer.** Se o cartão usa o motor de recorrência da AFRUS, escolha **Fecha automática (recomendada)** (data automática, recomendada), **Fecha de creación de la suscripción** (data de criação da assinatura) ou **Fecha de cobro** (data de cobrança: um dia de 1 a 28).

4. **Associe a campanha e o widget.** Escolha **Campaña** e depois **Widget**, para que a assinatura conte nos resultados deles.

5. **Crie a assinatura.** Clique em "Crear subscripcion" (Criar assinatura).

Você verá *"La subscripción se ha creado correctamente"* (Assinatura criada com sucesso) e ela aparecerá na aba **Subscripciones**.

> **Importante:** nesta janela, as opções **Modo enhanced** e **Modo de reintentos** (modo de novas tentativas) não são salvas: a assinatura é criada sem elas. Por enquanto não há alternativa nesta janela.

---

## Dados e status

| Dado | Valores |
|---|---|
| **Tipo** | **Lead**, **Activo** (Ativo), **Recurrente** (Recorrente) |
| Status do e-mail | **No verificado** (Não verificado), **Verificado**, **Soft Bounce**, **Hard Bounce**, **Opt Out**, **Deshabilitado** (Desativado) |
| Colunas da lista | **ID**, **Nombre**, **Correo electrónico**, **Fecha**, **Tipo**, **Scoring**, **Total de transacciones ($)**, **Campaña**, **Widget de origen**, **UTM Campaign de origen**, **Tags** |

> **O que significa cada tipo:** **Lead** é uma pessoa sem nenhuma transação; **Activo** (Ativo) é uma pessoa com pelo menos uma transação; e **Recurrente** (Recorrente) é uma pessoa com uma assinatura.

Se o e-mail voltou, o perfil mostra *"Tiene Hard Bounce"* ou *"Tiene Soft Bounce"*. Se a pessoa foi marcada como spam, o perfil mostra *"Esta persona fue marcada como spam y está oculta de listas, segmentos, exportaciones y envíos."* (Esta pessoa foi marcada como spam e está oculta de listas, segmentos, exportações e envios.) com o botão "No es spam" (Não é spam).

## Frequências e prazos

| O quê | Quando |
|---|---|
| Lista de Personas | Atualiza ao abrir ou mudar um filtro; o período inicial é o mês atual |
| Download com **Datos analizados** | A cada 24 horas |
| Arquivos em **Data > Descargas** | Disponíveis por 7 dias |
| Exportação e exclusão em massa | Em segundo plano; pode levar alguns minutos |
| Lembretes | A AFRUS verifica a cada 10 minutos |

## Perguntas frequentes

**Por que a lista mostra menos pessoas do que eu esperava?**
Ao abrir, o período é o mês atual. Aplique qualquer filtro ou busca (o período passa para **ALL**) ou ajuste a barra de datas.

**Por que os totais com e sem "Solo contactables" não batem?**
Porque esse filtro deixa de fora hard bounces, descadastros e e-mails desativados.

**Posso enviar o link de pagamento por WhatsApp pelo perfil?**
Não. Pelo perfil, o link é enviado só por e-mail, para o e-mail da pessoa.

**Posso recuperar uma pessoa que excluí?**
Não. A exclusão é permanente e inclui eventos, transações e assinaturas.

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-27*
