# Guia de Campanhas

Depois de ler este guia, você vai saber o que é uma campanha na AFRUS, para que serve, como vincular widgets e uma página de agradecimento a ela, como mostrar o progresso e os doadores no seu site e como medir o retorno com custos, Analytics e KPI Merge Tags.

*Módulo: Campanhas · Menu: **Fundraising > Campañas** · Público: equipes de captação, marketing digital e direção*

> **Sobre os nomes de tela neste guia:** botões, campos e menus estão escritos exatamente como aparecem na versão em espanhol do console, com a explicação em português quando ajuda.

---

## O que é uma campanha

**Uma campanha agrupa as doações e os cadastros que chegam por um ou vários widgets sob um mesmo objetivo de captação.** Ela tem um nome interno, um nome público, uma descrição, uma meta na moeda da sua organização e um status (ativa ou inativa).

Você encontra suas campanhas em **Fundraising > Campañas**. Na lista, você pode criar uma campanha com "Crear campaña" (Criar campanha), buscar pelo nome e filtrar por **Estado** (Status), **Tipo de Campaña** (Tipo de campanha) e **Total Recaudado** (Total arrecadado). Para ver esta seção, seu perfil de usuário precisa da permissão de ver campanhas.

## Para que serve

- **Acompanhar sua meta.** Você vê em um só lugar quanto uma iniciativa já arrecadou em relação à meta (**Total recaudado**, com barra de progresso).
- **Medir a conversão dos seus widgets.** A **Tasa de conversión** (Taxa de conversão) compara doações e cadastros com o número de vezes que os widgets da campanha foram exibidos.
- **Usar uma página de agradecimento comum** para todos os widgets da campanha que a utilizem.
- **Medir o retorno.** Você registra os custos da campanha e vê ROI, custo por transação, custo por doador recorrente, Lifetime Value e mais no painel de Analytics.
- **Mostrar sua campanha no seu site.** Com o **Crowdfunding widget** você mostra o progresso até a meta; com o **Componente donantes** (Componente de doadores), a lista de pessoas que doaram.
- **Contar o impacto em números.** Com os **KPI Merge Tags** você insere números calculados (por exemplo, "refeições doadas") em e-mails automáticos ou em landings.

## Antes de começar

- **Tenha a campanha criada.** Em **Fundraising > Campañas**, clique em "Crear campaña" e preencha **Nombre de campaña** (nome da campanha, até 100 caracteres), **Descripción** (descrição, até 500), **Nombre público** (nome público, até 100) e **Meta de recaudación** (meta de captação). Deixe **Campaña activa** (Campanha ativa) ligado e clique em "Crear" (Criar). A meta é sempre salva na moeda da sua organização.
- **Para editá-la**, na lista, abra o menu de três pontos da linha e escolha **Editar** (ou clique no ID). As mudanças de texto são salvas sozinhas um instante depois que você para de digitar; não há botão de salvar nessa aba.

---

# Passo a passo

## Como vincular um widget a uma campanha

Ao vincular um widget, as doações e os cadastros feitos nele ficam associados à campanha e contam nos resultados dela.

**Antes de começar:** a campanha precisa estar **ativa**. O editor de widgets só mostra campanhas ativas, pelo nome público.

1. **Abra o widget.** Acesse **Fundraising > Widgets** e edite o widget que quer vincular. O editor abre em uma nova aba.
   <!-- captura pendente: como-vincular-um-widget-a-uma-campanha-01 — editor de widgets, painel Renderización -->

2. **Escolha a campanha.** No painel **Renderización** (Renderização), no campo **Elige tus campañas** (Escolha suas campanhas), selecione uma ou várias campanhas.

3. **Salve as alterações do widget.**

Ao terminar, o widget aparece na tabela **Widgets de la campaña** (Widgets da campanha), no detalhe da campanha, e as doações e cadastros dele ficam associados a ela.

- **Com uma só campanha**, o doador não vê nada diferente no formulário.
- **Com mais de uma campanha**, o doador vê uma lista suspensa **Elige tu campaña** (Escolha sua campanha) no formulário, com a primeira campanha já selecionada. Assim ele pode decidir para qual iniciativa vai a doação.

> **Dá para desfazer?** Sim. Volte a **Elige tus campañas** no editor do widget, remova a campanha e salve.

## Como vincular uma página de agradecimento a uma campanha

Assim, todos os widgets da campanha podem levar o doador para a mesma página depois da doação. São duas partes: escolher a página na campanha e ativá-la em cada widget.

**Antes de começar:** tenha criada a página que quer usar, como experiência em **Fundraising > Experiences AI** ou como landing em **Fundraising > Landings**.

**Parte 1 — Na campanha**

1. **Abra a campanha.** Em **Fundraising > Campañas**, abra o menu de três pontos da linha e escolha **Editar**.
2. **Vá até a aba Página de agradecimiento (Página de agradecimento).** Ela também aparece ao criar a campanha.
   ![Aba Página de agradecimiento da campanha com o tipo de página e a landing escolhida](img/como-vincular-una-pagina-de-agradecimiento-a-una-campana-02.webp)
3. **Escolha o tipo de página.** Em **Tipo**, escolha **Experiences** ou **Landings**.
4. **Escolha a página.** Em **Elegir una experiencia** (Escolher uma experiência) ou **Elegir una landing** (Escolher uma landing), selecione a página. Você verá uma prévia **Mobile**.
5. **Clique em "Usar plantilla" (Usar modelo).** Esse botão não mostra mensagem de confirmação: para conferir se ficou salvo, recarregue a campanha e veja se a aba mostra a página escolhida.

**Parte 2 — Em cada widget que deve usá-la**

6. **Abra o widget.** Em **Fundraising > Widgets**, edite o widget.
7. **Ative a página da campanha.** Na seção **Avanzado** (Avançado), área **Página de agradecimiento**, marque **Usa la página de agradecimiento de la campaña.** (Usa a página de agradecimento da campanha). Ao marcar, o botão "Configurar" da página de agradecimento própria do widget desaparece.
8. **Salve as alterações do widget.**

Ao terminar, depois de doar, o doador chega à landing ou experiência escolhida na campanha à qual a doação foi associada.

> **Importante:** se a campanha não tiver página escolhida, ou se a página não existir mais, é usada a página de agradecimento normal do widget. O editor também avisa: *"Los países que no tienen la misma traducción en las campañas, por favor revise sus páginas de agradecimiento."* (Países que não têm a mesma tradução nas campanhas: revise suas páginas de agradecimento.) Revise suas páginas se o seu widget é usado em vários países.

> **Dá para desfazer?** Sim. Desmarque a opção no widget para voltar à página de agradecimento própria dele, ou escolha outra página na campanha.

## O que é o Crowdfunding widget

**O Crowdfunding widget é um bloco que você cola em qualquer site e que mostra ao vivo o progresso da sua campanha até uma meta.** Ele mostra o total alcançado, a meta, uma barra de progresso, o número de doações e, se você definiu uma data de encerramento, quantos dias faltam ou *"Campaña finalizada"* (Campanha encerrada). Os dados são consultados toda vez que a página carrega.

Você pode medir três tipos de meta, em **Tipo de componente**:

| Tipo | O que conta |
|---|---|
| **Meta de Recaudación** (Meta de captação) | A soma das doações aprovadas |
| **Meta de Suscriptores** (Meta de assinantes) | As assinaturas ativas |
| **Meta de Registros** (Meta de cadastros) | As pessoas cadastradas, sem repetição |

E duas formas de definir a meta, em **Tipo de meta**:

- **Fija** (Fixa): você digita a meta, escolhe a moeda (só em captação) e a **Fecha** (data) e **Hora** de encerramento.
- **Dinámica** (Dinâmica): usa a **Meta de recaudación** da campanha; não pede meta, moeda, data nem hora.

**Como configurar:**

1. **Abra o configurador.** Em **Fundraising > Campañas**, abra o menu de três pontos da linha e escolha **Crowdfunding widget**.
   ![Configurador do Crowdfunding widget com Tipo de componente, Tipo de meta e o botão Copiar código de inserción](img/que-es-el-crowdfunding-widget-01.webp)
2. **Configure a meta.** Na aba **Configuración** (Configuração), escolha **Tipo de componente** e **Tipo de meta**, e preencha os dados pedidos.
3. **Ajuste o visual.** Na aba **Estilos**, escolha **Tipografía** (Fonte: Roboto, Arial, Open Sans ou Times New Roman), **Tamaño de tipografía** (Tamanho da fonte, de 12 a 20) e **Color primario** (Cor primária), para combinar com o seu site.
4. **Salve.** Clique em "Guardar" (Salvar). Cada salvamento cria uma nova versão, que você pode escolher em **Versiones** (Versões).
5. **Copie o código.** Clique em "Copiar código de inserción" (Copiar código de incorporação) e cole no HTML do seu site.

> **Importante:** fonte, tamanho, cor e idioma vão dentro do código copiado. Se você mudar algo e salvar, copie e cole o código de novo para que o site use a nova versão.

## O que é o Componente de doadores

**O Componente donantes (Componente de doadores) é um bloco para o seu site que mostra a lista de pessoas que doaram para a campanha.** Por padrão, o título é *"Personas que también donaron"* (Pessoas que também doaram) e ele mostra nome, sobrenome e valor de cada doação aprovada, da mais recente para a mais antiga, com rolagem vertical. Se ainda não houver doações, mostra *"No hay donantes disponibles"* (Não há doadores disponíveis).

**Como configurar:**

1. **Abra o configurador.** Em **Fundraising > Campañas**, abra o menu de três pontos da linha e escolha **Componente donantes**.
   ![Configurador do Componente donantes com o título, a tipografia, a cor e a pré-visualização](img/que-es-el-componente-donantes-01.webp)
2. **Personalize.** Configure **Título**, **Tipografía** (Fonte), **Color primario** (Cor primária), o tema **Light** ou **Dark** e a chave **Activo** / **Inactivo** (Ativo / Inativo). A prévia usa nomes de exemplo, não seus doadores reais.
3. **Salve.** Clique em "Guardar" (ou "Actualizar" — Atualizar — se já existia).
4. **Copie o código** de incorporação e cole no seu site.

> **Importante:** título, tema e **Activo** / **Inactivo** são aplicados sem mexer no seu site. Fonte e cor vão dentro do código: se você mudá-las, copie e cole o código de novo. Se colocar em **Inactivo**, o bloco deixa de aparecer.

> **Atenção:** o bloco publica nome, sobrenome e valor de cada doador. Não há opção para ocultar nomes ou valores, então confirme que sua organização pode publicar essas informações. Os valores aparecem com o símbolo da moeda da sua organização.

## Para que serve e como usar o centro de custos

Na campanha, o centro de custos é a aba **Costos** (Custos): *"Agrega en esta sección todos los costos implicados en la realización de tu campaña"* (Adicione nesta seção todos os custos envolvidos na realização da sua campanha).

**Para que serve:**

- **Saber quanto você investiu** na campanha, com um total filtrável por datas.
- **Calcular o retorno.** Com seus custos, a AFRUS calcula Resultado, ROI, custo por transação, custo por doador recorrente e outros indicadores.
- **Ativar o painel de Analytics.** O botão "Ver Analytics" só é habilitado quando a campanha tem pelo menos um custo registrado.

**Como registrar um custo:**

1. **Abra a campanha** e vá até a aba **Costos**.
   ![Aba Costos com a lista de custos, o total e o botão Agregar costo](img/centro-de-costos-de-una-campana-01.webp)
2. **Clique em "Agregar costo" (Adicionar custo).**
3. **Preencha os dados.**
   - **Costo** (Custo): obrigatório, maior que 0.
   - **Tipo:** obrigatório, **Publicidad (working media)** (Publicidade) ou **Costos de apoyo y producción** (Custos de apoio e produção).
   - **Fecha de gasto** (Data do gasto): obrigatória.
   - **Widget:** opcional, só widgets desta campanha. Um custo atribuído a um widget conta na análise desse widget; um sem widget só conta na análise da campanha inteira.
   - **Nota:** opcional, até 1000 caracteres.
4. **Clique em "Agregar" (Adicionar)** (ou "Guardar" se estiver editando).

Ao terminar, o custo aparece em **Lista de costos** (Lista de custos — colunas **Fecha**, **Valor**, **Widget**, **Tipo**, **Nota** e **Acciones**) e soma no **Total**, que você pode filtrar por período.

> **Leve em conta:** o valor é salvo sem centavos (por exemplo, 150,75 vira 150). Registre valores arredondados. Os custos são sempre registrados na moeda da sua organização.

> **Dá para desfazer?** Você pode editar um custo. Excluí-lo pede confirmação e não pode ser desfeito.

## Analytics de campanhas: que dados você obtém, como ativar e como analisar

**Como ativar:** registre pelo menos um custo na aba **Costos**. Até lá, "Ver Analytics" fica desabilitado com o aviso *"Para acceder a las analíticas, primero debes registrar al menos un costo en la sección de Costos."* (Para acessar as análises, primeiro registre pelo menos um custo na seção de Custos.)

**Como abrir e usar:**

1. **Abra o painel.** No detalhe da campanha, clique em "Ver Analytics".
   ![Painel de Analytics na aba Resumen com receita, custo e resultado](img/analytics-de-campanas-01.webp)
2. **Escolha o período.** Na aba **Resumen** (Resumo), escolha o período (por padrão, todo o histórico). Os cartões de indicadores são recalculados para esse período.
3. **Baixe os indicadores (opcional).** Clique em "Descargar KPIs" (Baixar KPIs) para baixar um arquivo CSV com todos os indicadores do período (colunas KPI, Valor e Unidade).
4. **Veja um widget em detalhe.** Em **Rendimiento por Widget** (Desempenho por widget), clique em um widget para abrir o **Analytics del Widget**: os mesmos indicadores, só desse widget e dos custos dele.
5. **Veja a evolução.** Na aba **Tendencias** (Tendências), escolha o período (por padrão, o mês atual). A AFRUS agrupa por dia até 31 dias, por semana até 90 dias e por mês acima disso.

**Que dados você obtém no Resumen (cartões):**

| Indicador | O que é |
|---|---|
| Ingresos Totales / Costos (Receita total / Custos) | Receita de doações aprovadas em relação à soma dos custos registrados |
| Resultado | Receita menos custos |
| ROI | (receita − custos) / custos |
| MRR Adquirido / ARR Adquirido | Receita mensal das assinaturas ativas adquiridas; o ARR é o MRR × 12 |
| CPT Bruto / CPR Bruto | Custo por transação / custo por doador recorrente |
| CPT Neto / CPR Neto (Líquido) | O mesmo, usando só a perda líquida (0 se a campanha for rentável) |
| Punto de Equilibrio (Ponto de equilíbrio) | Meses para recuperar a perda líquida com o MRR |
| Inversión (Investimento) | Perda líquida (0 se a campanha for rentável) |
| RCR | Assinaturas / (assinaturas + pagamentos únicos) |
| Tasa de Calidad (Taxa de qualidade) | Assinaturas / transações |
| Tasa de Abandono (Taxa de cancelamento) | Assinaturas canceladas / assinaturas novas |
| Vida del Donante (Vida do doador) | 1 / taxa de cancelamento, em meses |
| Lifetime Value | AMV × 12 / taxa de cancelamento |
| Eficiencia de Adquisición (Eficiência de aquisição) | LTV / CPR; deve ser maior que 1 |
| AMV | MRR / assinaturas |
| Quantidades e médias | Transações aprovadas, novas assinaturas ativadas e valor médio de pagamentos únicos e de assinaturas |

Se ainda não houver assinaturas canceladas, a tela usa um valor de referência de 3% para calcular Taxa de cancelamento, Vida do doador e Lifetime Value, e informa isso no texto de ajuda.

**Que dados você obtém nas tabelas Histórico:** **Rendimiento por Widget**, **Rendimiento por UTM Source**, **UTM Medium**, **UTM Campaign** e **Rendimiento por URL**, com transações, valores, assinaturas e valores de assinaturas. Elas mostram qual widget, qual fonte de tráfego e qual página trazem mais doações.

**Como analisar:**

- **A campanha é rentável?** Veja **Resultado** e **ROI**. Se houver perda, **Punto de Equilibrio** mostra em quantos meses seus doadores recorrentes a recuperam.
- **Você está captando bem?** Compare **Lifetime Value** com **CPR**: se **Eficiencia de Adquisición** for maior que 1, cada doador recorrente vale mais do que custa conquistá-lo.
- **Você está conquistando doadores recorrentes?** **RCR** e **Tasa de Calidad** mostram que parte das suas doações são assinaturas.
- **Onde investir?** As tabelas por widget, UTM e URL mostram quais canais e páginas trazem mais receita.

**Com que frequência os dados são atualizados:**

| Onde | Quando atualiza |
|---|---|
| Cartões do **Resumen** e **Analytics del Widget** | Na hora, com os dados atuais |
| Tabelas **Histórico** (por widget, UTM e URL) | Uma vez por dia: podem não incluir o dia de hoje. Mostram o total de sempre e não respeitam o período escolhido |
| Aba **Tendencias** | Uma vez por dia: pode não incluir o dia de hoje |

**Taxa de conversão (em Datos de la campaña):** além do painel, a aba **Datos de la campaña** (Dados da campanha) mostra **Donaciones** (Doações, %), **Registros** (Cadastros, %) e **Visualizaciones** (Visualizações) dos widgets da campanha. O texto de ajuda diz *"Este dato se calcula cada 24 horas y puede no reflejar cambios recientes"* (Este dado é calculado a cada 24 horas e pode não refletir mudanças recentes).

## Para que servem e como usar os KPI Merge Tags

**Os KPI Merge Tags são números calculados com uma fórmula que você insere em e-mails automáticos ou em landings.** Eles servem para contar o impacto de forma concreta: por exemplo, transformar o valor de uma doação em "refeições doadas". São criados na aba **KPI Merge Tag** da campanha, e há dois tipos:

| Tipo | Onde é usado | Com que dados calcula |
|---|---|---|
| **KPI Transaccional** (KPI transacional) | E-mails automáticos (**Interacciones > Autoresponders**) | O **Monto** (Valor) da doação que dispara o e-mail |
| **KPI Global** | Landings | **Total Recaudado** (Total arrecadado) e **Cantidad de Donantes** (Quantidade de doadores) da campanha |

**Como criar um KPI Transacional:**

1. **Abra a aba.** Na campanha, vá até **KPI Merge Tag**, seção **KPI Transaccional** e clique em "Agregar KPI Merge Tag" (Adicionar KPI Merge Tag).
   ![Formulário Crear KPI Merge Tag com o construtor de fórmula](img/kpi-merge-tags-01.webp)
2. **Dê um nome.** Digite **Nombre del KPI** (Nome do KPI) e uma **Descripción** opcional. Em **Variable generada** (Variável gerada) você verá a tag que vai usar.
3. **Monte a fórmula.** Em **Constructor de Fórmula** (Construtor de fórmula), alterne "Agregar Variable" (Adicionar variável) e "Agregar Operador" (Adicionar operador: +, -, ×, ÷). A variável disponível é **Monto**. Com "Agregar Variable Multiplicador" (Adicionar variável multiplicadora) você cria uma constante (**Nombre de la variable** e **Valor constante**) para usar na fórmula. "Limpiar" (Limpar) e "Quitar Último" (Remover último) ajudam a corrigir. A fórmula deve terminar em uma variável.
4. **Clique em "Crear" (Criar)** (ou "Actualizar" se estiver editando).
5. **Use no seu e-mail automático.** A tag tem este formato: `{{kpi_<ID da campanha>_<nome>}}`, com o nome em minúsculas e os espaços trocados por `_`. Por exemplo, campanha 88 e nome "Comidas Donadas" → `{{kpi_88_comidas_donadas}}`.

Quando o e-mail é enviado, a tag é substituída pelo resultado da fórmula com o valor daquela doação, com 2 casas decimais. Multiplicação e divisão são calculadas antes de soma e subtração.

**Como criar um KPI Global:**

1. **Abra a aba.** Na campanha, vá até **KPI Merge Tag**, seção **KPI Global** e clique em "Agregar KPI global" (Adicionar KPI global).
2. **Dê um nome e monte a fórmula** como no anterior. As variáveis disponíveis são **Total Recaudado** e **Cantidad de Donantes** (mais constantes). Use no nome só letras sem acento, números e espaços.
3. **Clique em "Crear".**
4. **Use na sua landing, entre colchetes.** A tela mostra a tag com chaves (`{{global_kpi_88_comidas_donadas}}`), mas na landing você precisa escrevê-la entre colchetes: `[global_kpi_88_comidas_donadas]`.

Ao abrir a landing publicada, a tag mostra o valor calculado naquele momento com todas as doações aprovadas da campanha, com até 2 casas decimais.

> **Importante (KPI Global):** as operações são aplicadas da esquerda para a direita; multiplicação e divisão não vêm primeiro. Ordene sua fórmula na ordem em que quer que ela seja calculada.

> **Dá para desfazer?** Você pode editar um KPI Merge Tag, mas não há botão para excluí-lo.

---

## Status de uma campanha

| Status | O que significa | O que você pode fazer |
|---|---|---|
| **activo** (ativo) | A campanha está ativa e pode ser escolhida no editor de widgets | Vinculá-la aos seus widgets |
| **inactivo** (inativo) | A campanha está desligada (chave **Campaña activa** desligada) | Ligar **Campaña activa** no detalhe para usá-la de novo |
| **archivado** (arquivado) | A campanha está arquivada | Consultá-la |

## Perguntas frequentes

**O que faz "Seleccionar por defecto" (Definir como padrão) no menu de uma campanha?**
Marca a campanha padrão da sua organização (só pode haver uma). A ela são atribuídas as transações que chegam de alguns gateways de pagamento sem uma campanha conhecida, por exemplo cobranças de assinaturas criadas fora da AFRUS.

**Por que não vejo minha campanha ao vinculá-la no widget?**
Porque ela está inativa. O editor de widgets só mostra campanhas ativas: ligue **Campaña activa** no detalhe da campanha.

**A campanha pode ter outra moeda?**
Não. A meta e os custos são sempre registrados na moeda da sua organização.

**Posso usar um KPI Global em um e-mail?**
Por enquanto, o uso só está confirmado em landings. Para e-mails automáticos, use um KPI Transacional.

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-26*
