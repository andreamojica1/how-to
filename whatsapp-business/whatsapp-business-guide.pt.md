# Guia do WhatsApp Business

Depois de ler este guia, você vai saber conectar sua conta do WhatsApp Business à AFRUS, criar modelos (templates), fazer envios em massa, enviar imagens e responder seus contatos em **Conversaciones** (Conversas).

*Módulo: WhatsApp Business · Menu: **WhatsApp Business > Blast** e **WhatsApp Business > Conversaciones** · Público: equipes de captação, comunicação e relacionamento com doadores*

> **Sobre os nomes de tela neste guia:** botões, campos e menus estão escritos exatamente como aparecem na versão em espanhol do console, com a explicação em português quando ajuda. Na tela, "plantilla" é o modelo de mensagem (template).

---

## O que é o WhatsApp Business

**O WhatsApp Business na AFRUS é a conexão com a API oficial do WhatsApp Business da Meta.** Com ela você envia mensagens em massa usando modelos aprovados pela Meta e responde, pela AFRUS, aos contatos que escrevem para você.

O módulo tem duas telas: **WhatsApp Business > Blast**, o painel da sua conta com seus números, modelos e envios em massa, e **WhatsApp Business > Conversaciones**, onde você lê e responde as mensagens.

## Para que serve

- **Enviar campanhas em massa pelo WhatsApp.** Você envia um Blast para um segmento e cada contato recebe a mensagem personalizada com os próprios dados.
- **Criar e editar modelos na AFRUS.** Você os desenha na AFRUS e envia para revisão da Meta sem sair da plataforma.
- **Responder seus contatos.** Em **Conversaciones** você vê e responde as mensagens que chegam, em tempo real.
- **Medir seus envios.** Você vê quantas mensagens foram enviadas, entregues, lidas e com erro.

## Antes de começar

- **Uma conta no Meta Business Suite com WhatsApp Business.** A conexão é feita com sua conta da Meta.
- **Um método de pagamento no seu WhatsApp Business.** A tela de conexão recomenda isso como etapa prévia.
- **Números de envio validados na Meta.** Os números são adicionados pelo Gerenciador de Telefones da Meta, não pela AFRUS.

---

# Passo a passo

## Como conectar o WhatsApp Business na AFRUS

1. **Abra o módulo.** Acesse **WhatsApp Business > Blast**. Se ainda não houver conta conectada, a AFRUS leva você para a tela **Conecta tu WhatsApp Business** (Conecte seu WhatsApp Business), que lista as etapas prévias recomendadas.
   <!-- captura pendente: como-conectar-o-whatsapp-business-na-afrus-01 — tela Conecta tu WhatsApp Business -->

2. **Conecte-se com a Meta.** Clique em "Conectar con Facebook" (Conectar com o Facebook). Abre uma janela da Meta: faça login e escolha (ou crie) sua conta do WhatsApp Business e o número. Assim a AFRUS fica autorizada a enviar em nome da sua conta.

3. **Confira a verificação.** Ao terminar, a AFRUS sincroniza seus modelos e abre **Verificando tu configuración** (Verificando sua configuração, **PASO 2 DE 3** — etapa 2 de 3). Ela confere **Cuenta de WhatsApp Business conectada** (conta conectada), **Número de teléfono registrado** (número registrado) e **Plantillas sincronizadas** (modelos sincronizados).

4. **Envie uma mensagem de teste (opcional).** Em **Enviar mensaje de prueba (opcional)**, escolha o **Número de teléfono de envío** (número de envio), digite o **Número de teléfono del destinatario** (número do destinatário) e clique em "Enviar mensaje de prueba" (Enviar mensagem de teste). Depois clique em "Ir al Dashboard" (Ir para o painel).

Ao terminar, você verá no painel o chip **Conectado** e o nome do seu negócio. Seus números aparecem em **Números conectados**.

> **Importante:** a conexão com a Meta expira. A AFRUS avisa com *"Tu conexión expirará en N días"* (Sua conexão vai expirar em N dias) e, quando já expirou, mostra **Renueva tu conexión de WhatsApp Business** com o botão "Reconectar con Facebook" (Reconectar com o Facebook).

> **Dá para desfazer?** Você pode desconectar com "Desconectar cuenta" (Desconectar conta), mas os envios param e, como a tela avisa, você perde o acesso aos modelos pela AFRUS.

**Para adicionar um número novo:** adicione no Gerenciador de Telefones da Meta e depois clique em "Actualizar números" (Atualizar números) ou "Sincronizar con Meta" (Sincronizar com a Meta) na AFRUS.

### Habilitar o botão de envio em massa

O botão "Enviar blast masivo" (Enviar blast em massa) fica bloqueado até que duas condições sejam cumpridas:

- **As verificações obrigatórias estão em verde:** **Cuenta de WhatsApp Business Conectada**, **Número de Teléfono Registrado (Calidad OK)** (número registrado, qualidade OK), **Plantilla de Mensaje Aprobada** (modelo aprovado) e **Suscripción a Webhooks (seguimiento de entrega y lectura)** (acompanhamento de entrega e leitura). Você as vê no cartão **Preparación para Envío de Mensajes** (Preparação para envio de mensagens); clique em "Verificar" se precisar.
- **Há pelo menos uma mensagem de teste com sucesso.** Clique em "Enviar Mensaje de Prueba" no painel e envie para um número com WhatsApp.

> **Importante:** esse teste usa um modelo aprovado **sem variáveis nem mídia**. Se você não tiver nenhum assim, verá *"Aún no tienes plantillas de mensaje. Crea una en Facebook para poder enviar mensajes de prueba."* (Você ainda não tem modelos de mensagem…). Crie um modelo simples, só com texto, para conseguir completar o teste. O modelo de exemplo "hello_world" não conta.

**Método de Pago** (método de pagamento) e **Verificación del Negocio** (verificação do negócio) aparecem como **Recomendado**: não bloqueiam o envio, mas vale a pena tê-los.

## Como criar um modelo (template)

Para escrever primeiro a um contato pelo WhatsApp Business, você precisa de um modelo aprovado pela Meta.

1. **Abra os modelos.** Em **WhatsApp Business > Blast**, seção **Plantillas de WhatsApp Meta**, clique em "Crear plantilla" (Criar modelo).
   ![Seção Plantillas de WhatsApp Meta com o botão Crear plantilla](img/como-crear-una-plantilla-de-whatsapp-business-01.webp)

2. **Preencha as informações básicas.** Em **Información básica**, digite o **Nombre de la plantilla** (nome do modelo: só letras minúsculas, números e sublinhados, começando com letra), escolha a **Categoría** (**Marketing**, **Utilidad** — Utilidade — ou **Autenticación** — Autenticação) e o **Idioma del mensaje** (idioma da mensagem). Clique em "Continuar".

3. **Adicione mídia (opcional).** Em **Diseño del mensaje** (Design da mensagem), em **Contenido multimedia** (mídia) escolha **Ninguna** (Nenhuma), **Imagen** (Imagem), **Video** ou **Documento** e clique em "Subir" (Enviar arquivo). O arquivo substitui o cabeçalho de texto.

4. **Escreva o cabeçalho (opcional).** Se não usar mídia, você pode escrever um **Encabezado** (cabeçalho) de texto, com até 60 caracteres.

5. **Escreva o corpo.** Preencha o **Cuerpo del mensaje** (corpo da mensagem, até 1024 caracteres). Você pode usar variáveis como {{1}} para personalizar a mensagem com os dados de cada contato.

6. **Adicione rodapé e botões (opcional).** Escreva um **Pie de página** (rodapé, até 60 caracteres) e adicione **Botones** (botões): **Personalizado** (resposta rápida), **Ir al sitio web** (ir para o site, URL fixa ou dinâmica) ou **Llamar por teléfono** (ligar). O texto de cada botão aceita até 25 caracteres.

7. **Revise e envie para a Meta.** Confira a **Vista previa** (pré-visualização) e clique em "Enviar a Meta" (Enviar para a Meta).

Ao terminar, você verá *"Plantilla enviada para aprobación"* (Modelo enviado para aprovação) e o modelo ficará **Pendiente** (Pendente). Segundo a tela, a revisão da Meta leva entre 5 minutos e 24 horas. O status muda sozinho quando a Meta responde; você também pode clicar em "Sincronizar con Meta".

**Formatos de mídia:** imagem JPEG ou PNG de até 5MB; vídeo MP4 ou MOV de até 16MB; documento PDF de até 100MB.

> **Importante:** os modelos de **Autenticación** têm um texto fixo definido pela Meta, servem só para códigos de verificação e **não podem ser usados em envios em massa**.

> **Dá para desfazer?** Você pode editar um modelo, mas a Meta o revisa de novo e ele volta para **Pendiente**; enquanto está em revisão, não pode ser alterado. Excluir um modelo não pode ser desfeito e apaga também suas variantes de idioma.

## Como fazer um envio em massa (Blast) pelo WhatsApp Business

**Antes de começar:** o botão "Enviar blast masivo" deve estar habilitado (veja *Habilitar o botão de envio em massa*) e você precisa de pelo menos um modelo **Aprobada** (Aprovado) que não seja de Autenticação.

### Parte 1 — Crie o envio

1. **Inicie o envio.** Em **WhatsApp Business > Blast**, clique em "Enviar blast masivo". A criação do envio abre com o canal **WhatsApp Business** já escolhido.
   ![Painel do WhatsApp Business com o botão Enviar blast masivo](img/como-hacer-un-envio-masivo-por-whatsapp-business-01.webp)

2. **Dê um nome e escolha os destinatários.** Preencha **Nombre del envío** (nome do envio), escolha o segmento em **Seleccionar segmento** (Selecionar segmento) e clique em "Continuar".

### Parte 2 — Configure a mensagem

3. **Escolha número e modelo.** Escolha o **Número de teléfono** de envio e o modelo em **Plantilla de mensaje** (Modelo de mensagem).

4. **Associe as variáveis.** Em **Mapeo de Variables** (Mapeamento de variáveis), associe cada variável a um campo do contato (por exemplo, o nome). Assim cada pessoa recebe a mensagem personalizada. Se o modelo tiver mídia no cabeçalho, clique em "Seleccionar media de la galería" (Selecionar mídia da galeria) e escolha o arquivo.

5. **Teste a mensagem (opcional).** Use "Enviar prueba" (Enviar teste) para recebê-la em um número, com **Valores de prueba** (valores de teste) digitados à mão.

### Parte 3 — Envie ou agende

6. **Confira sua cota.** Clique em "Enviar". A AFRUS mostra **Estado de Cuota Diaria** (Status da cota diária) com os destinatários, a cota restante e o limite diário. Se não for suficiente, você verá **Cuota Diaria Insuficiente** (Cota diária insuficiente) e o botão "Enviar de todos modos" (Enviar mesmo assim).

7. **Envie ou agende.** Escolha **Enviar ahora** (Enviar agora) ou **Programar fecha** (Agendar, com data e hora) e confirme com "Enviar" ou "Programar".

Ao terminar, a AFRUS envia as mensagens uma a uma. No detalhe do envio você vê o status de cada destinatário: **En cola** (Na fila), **Enviado**, **Entregado** (Entregue), **Leído** (Lido), **Error** (Erro) ou **No enviado** (Não enviado).

> **Dá para desfazer?** Pendente de confirmação se um envio pode ser interrompido depois de iniciado. Sempre confira a mensagem com "Enviar prueba" antes de enviar.

**Quem recebe a mensagem:** só os contatos do segmento que têm telefone. A AFRUS deixa de fora quem recusou o canal WhatsApp Business e os números que a Meta informou como "não está no WhatsApp" (por 90 dias; a exclusão termina sozinha se a pessoa escrever para você). Se ninguém do segmento se encaixar, você verá *"No hay destinatarios entregables en este segmento..."* (Não há destinatários válidos neste segmento).

**Antes de enviar**, a AFRUS confere se o modelo continua aprovado. Se não estiver, você verá *"La plantilla ya no está aprobada"* (O modelo não está mais aprovado).

## Quantas mensagens posso enviar por dia

O limite diário é definido pela **Meta** de acordo com o nível da sua conta; a AFRUS o lê e mostra na barra **Límite diario compartido** (Limite diário compartilhado) em **Números conectados**.

| Nível da conta na Meta | Mensagens por dia |
|---|---|
| 0 (conta nova) | 250 |
| 1 | 2.000 |
| 2 | 10.000 |
| 3 | 100.000 |
| 4 | Ilimitado |

Tenha em mente:

- **O limite é do seu portfólio de negócios na Meta, não de cada número.** Todos os seus números compartilham a mesma cota.
- **A AFRUS só conta o que é enviado pela AFRUS.** As mensagens que você envia fora da AFRUS também consomem a cota, mas a AFRUS não as vê.
- **O contador "Enviados hoy" (Enviados hoje) funciona como uma janela de 24 horas.**
- **Se um envio atingir o limite**, ele fica em **Límite alcanzado** (Limite atingido) e é retomado sozinho quando há cota: a AFRUS verifica esses envios a cada 30 minutos. A tela avisa que as mensagens restantes são retomadas "em ~24 horas, quando a cota for liberada".

> **Pendente de confirmação:** o nível exato da sua conta é decidido pela Meta. Confira a barra **Límite diario compartido** para ver seu limite real.

## Como aumentar o número de envios diários

Seu limite diário aumenta quando a Meta atribui um nível mais alto à sua conta. O que sabemos hoje:

1. **Verifique seu negócio na Meta.** A passagem para o nível 1 acontece após a verificação do negócio. Na AFRUS, **Verificación del Negocio** aparece como **Recomendado** no cartão **Preparación para Envío de Mensajes**, com o aviso *"Verify your business to increase your daily messaging rate"* (Verifique seu negócio para aumentar sua taxa diária de mensagens).
2. **Cuide da qualidade das suas mensagens.** Os níveis 2 e 3 são atribuídos pela qualidade. Confira na AFRUS se o seu número continua em **Número de Teléfono Registrado (Calidad OK)** sem avisos.

> **Pendente de confirmação:** os critérios e prazos exatos que a Meta usa para subir o nível de uma conta. São definidos pela Meta e podem mudar.

## Como enviar imagens

As imagens são enviadas no cabeçalho de um modelo, dentro de um envio em massa.

1. **Crie um modelo com imagem.** Ao criar o modelo, em **Contenido multimedia** escolha **Imagen** e clique em "Subir" (JPEG ou PNG de até 5MB). Aguarde a aprovação da Meta.
2. **Tenha a imagem na galeria da AFRUS.** A imagem enviada ao criar o modelo serve só para a revisão da Meta e **não fica salva na galeria**. Envie-a para a galeria com "Subir imagen" (Enviar imagem).
3. **Escolha a imagem no envio.** No Blast, em **Mapeo de Variables**, seção **Media del Encabezado** (Mídia do cabeçalho), clique em "Seleccionar media de la galería" e escolha a imagem (até 5MB; a AFRUS aceita jpg, jpeg, png, gif e webp).

Ao terminar, todos os destinatários recebem essa mesma imagem no cabeçalho da mensagem.

> **Pendente de confirmação:** em qual tela do menu se abre a galeria para enviar a imagem antes do envio.

**Vídeos:** por enquanto **não é possível enviar um Blast com um modelo de vídeo pela AFRUS** (problema conhecido). Você pode criar o modelo de vídeo e a Meta o aprova, mas no envio o vídeo só pode ser escolhido na galeria, que só aceita imagens. Enquanto isso, use modelos com imagem ou adicione um botão **Ir al sitio web** que leve ao vídeo.

**Em Conversaciones** não é possível anexar arquivos: você verá *"Adjuntar archivos no está disponible aún"* (Anexar arquivos ainda não está disponível).

## Como responder em Conversaciones

1. **Abra a conversa.** Acesse **WhatsApp Business > Conversaciones** e escolha uma. Você pode usar **Buscar conversación...** (Buscar conversa) ou os filtros **Todos**, **No leídos** (Não lidos) e **Generado por IA** (Gerado por IA).
2. **Se aparecer "Abierta (expira en …)" (Aberta, expira em…), escreva.** Digite em **Escribe un mensaje...** (Escreva uma mensagem) e envie. Você pode enviar texto livre porque passaram menos de 24 horas desde a última mensagem do contato.
3. **Se aparecer "Cerrada" (Fechada), envie um modelo.** Você verá *"La ventana de 24h ha expirado. Envía un template para reabrir la conversación."* (A janela de 24h expirou. Envie um template para reabrir a conversa.) Clique em "Enviar plantilla" (Enviar modelo), escolha um modelo aprovado, preencha as variáveis e clique em "Enviar plantilla".

Ao terminar, sua mensagem aparece no chat na hora.

> **Importante:** se você enviar por Conversaciones um modelo com imagem, vídeo ou documento no cabeçalho, verá *"El encabezado multimedia no se envía en mensajes directos de conversación"* (O cabeçalho de mídia não é enviado em mensagens diretas da conversa): a AFRUS envia o modelo sem o arquivo e o envio pode falhar. Em Conversaciones, use modelos só de texto.

As imagens, vídeos, áudios e documentos que um contato envia aparecem no chat, mas a Meta faz com que expirem: depois de um tempo você verá *"Este recurso ya no está disponible. El contenido multimedia de WhatsApp expira y no puede recuperarse."* (Este recurso não está mais disponível…).

## O que são as mensagens geradas por IA em Conversaciones

**São as mensagens enviadas pela Alma, a agente autônoma de captação da AFRUS, que escreve por conta própria.** O filtro **Generado por IA** de **Conversaciones** mostra só as conversas com mensagens da Alma.

- **As mensagens que sua equipe escreve pela AFRUS não entram nesse filtro**, mesmo que sejam enviadas por Conversaciones.
- **Uma conversa com a Alma pode aparecer como uma entrada separada** da conversa normal com o mesmo contato.

---

## Status

| Status do modelo | O que significa | O que você pode fazer |
|---|---|---|
| **Aprobada** (Aprovado) | Pode ser usado em envios e conversas | Usar |
| **Pendiente** (Pendente) | A Meta está revisando | Aguardar; não pode ser alterado |
| **Rechazada** (Rejeitado) | A Meta rejeitou | Ver o motivo da Meta e corrigir |
| **Pausada** / **Deshabilitada** (Pausado / Desativado) | Status definidos pela Meta; não está aprovado para envio | Usar outro modelo |
| **En apelación** / **Eliminación pendiente** (Em recurso / Exclusão pendente) | Status definidos pela Meta | Aguardar a resposta da Meta |

| Janela da conversa | O que significa | O que você pode fazer |
|---|---|---|
| **Abierta (expira en …)** (Aberta) | Menos de 24 h desde a última mensagem do contato | Escrever texto livre |
| **Cerrada** (Fechada) | 24 h ou mais desde a última mensagem do contato | Só "Enviar plantilla" |

| Status do envio | O que significa |
|---|---|
| **Límite alcanzado** (Limite atingido) | O limite diário do seu portfólio da Meta foi atingido. O envio é retomado automaticamente quando há cota |

## Limitações conhecidas

- **Não é possível enviar Blasts com modelos de vídeo.** Alternativa: modelos com imagem ou um botão **Ir al sitio web** com link para o vídeo.
- **Modelos com mídia enviados por Conversaciones** saem sem o arquivo e podem falhar. Use modelos só de texto em Conversaciones.
- **O teste que habilita os Blasts só usa modelos sem variáveis nem mídia.** Tenha pelo menos um modelo assim.
- **A galeria e os modelos não compartilham arquivos:** o que você envia ao criar o modelo não aparece na galeria.
- **Em Conversaciones não é possível anexar arquivos.**
- **Não existe botão de "nova conversa".**
- **Os números são adicionados na Meta**, não na AFRUS.

## Perguntas frequentes

**Posso ser penalizado?**
Sim, pode acontecer: as penalidades são aplicadas pela Meta. A AFRUS mostra os sinais de risco: se a qualidade do seu número estiver vermelha, **Número de Teléfono Registrado (Calidad OK)** mostra um aviso de que o número pode ser limitado e cair de nível; se a Meta rejeitar o nome de exibição, essa verificação falha; e os modelos podem ficar **Pausada** ou **Deshabilitada**. Além disso, a AFRUS não tenta de novo as mensagens que a Meta rejeita de forma definitiva, por exemplo por conta bloqueada, limite por spam, conteúdo que viola as políticas ou pessoas que bloquearam suas mensagens de marketing. Nos modelos de **Marketing**, os usuários podem cancelar o recebimento.

> **Pendente de confirmação:** as regras de penalidade da Meta além desses sinais. São definidas pela Meta.

**Se eu enviar uma mensagem pela AFRUS, posso responder depois pelo celular, mesmo depois de 24 horas sem resposta do contato?**
Na AFRUS, não com texto livre: 24 horas depois da última mensagem do contato, a conversa fica **Cerrada** e você só pode enviar um modelo. Se o contato responder, a janela se abre de novo.

> **Pendente de confirmação:** se é possível usar o mesmo número no app do WhatsApp do celular ao mesmo tempo que na AFRUS. Depende da Meta e de como o número foi registrado.

**Posso iniciar uma conversa com um contato sem ter feito um envio antes?**
Não por **Conversaciones**: não há botão de "nova conversa", e a lista só mostra chats em que o contato escreveu para você pelo menos uma vez. Para escrever primeiro, faça um envio em massa com um modelo aprovado. Se a pessoa escrever primeiro para o seu número, a conversa aparece e você pode responder com texto livre por 24 horas.

> **Pendente de confirmação:** se outras funções da AFRUS, como as automações, podem enviar modelos do WhatsApp Business.

**Quanto tempo a Meta leva para aprovar um modelo?**
Segundo a tela, entre 5 minutos e 24 horas. O prazo é definido pela Meta.

**Por que não consigo clicar em "Enviar blast masivo"?**
Porque falta uma verificação obrigatória ou uma mensagem de teste com sucesso. Confira o cartão **Preparación para Envío de Mensajes**.

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-20*
