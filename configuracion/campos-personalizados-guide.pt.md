# Guia de Campos personalizados

Com este guia você vai entender o que são os campos personalizados, como pedi-los nos seus formulários e onde ver as informações que seus doadores preenchem.

*Módulo: Configurações · Menu: **Ajustes de Organización > Campos personalizados** (Ajustes da organização > Campos personalizados) · Público: equipes de captação, comunicação e dados*

> **Sobre os nomes de tela neste guia:** botões, campos e menus estão escritos como aparecem na versão em espanhol do console, com a explicação em português quando ajuda.

---

## O que são os campos personalizados

**São dados extras que sua organização quer guardar de cada pessoa, além dos que a AFRUS já tem** (nome, e-mail, telefone, documento, endereço…). Por exemplo: "Como você nos conheceu?" ou "Área de interesse".

Eles são definidos em **Ajustes de Organización > Campos personalizados**.

## Para que servem

- **Conhecer melhor seus doadores.** Você guarda as informações importantes para sua organização.
- **Pedir esses dados nos seus formulários.** Você pode adicionar o campo aos seus formulários de doação ou de cadastro.
- **Preenchê-los à mão.** Você também os preenche ao criar ou editar uma pessoa.
- **Usá-los nos seus e-mails.** Nos autoresponders você pode inserir o valor de um campo personalizado com um merge tag.
- **Analisá-los fora da AFRUS.** Cada campo sai como uma coluna ao baixar sua lista de pessoas.

---

# Passo a passo

## Como configurar um campo personalizado

1. **Abra a tela.** Acesse **Ajustes de Organización > Campos personalizados**.
   <!-- captura pendente: como-configurar-um-campo-personalizado-01 — tela Campos personalizados -->

## Como incluir um campo personalizado no meu widget

**Antes de começar:** o campo já precisa existir em **Ajustes de Organización > Campos personalizados**.

1. **Abra o editor do formulário.** Em **Fundraising > Widgets**, edite o formulário.

2. **Adicione o bloco.** Clique em "Agregar" (Adicionar) e escolha **Campo personalizado**.
   <!-- captura pendente: como-incluir-um-campo-personalizado-no-meu-widget-02 — menu Agregar com a opção Campo personalizado -->

3. **Configure.** Clique no bloco e configure-o em **Configuración del snippet** (Configuração do snippet).

4. **Posicione.** Arraste-o até o lugar onde quer que apareça no formulário.

5. **Salve.** Clique em "Guardar Snippet" (Salvar snippet) e depois em "Guardar Widget" (Salvar widget).

Ao terminar, o doador verá o campo ao preencher o formulário.

**Lembre-se:**
- Você pode adicionar **Campo personalizado** várias vezes no mesmo país do formulário, para pedir vários campos.
- Cada país do formulário tem sua própria lista de blocos: se o seu formulário tem vários países, adicione em cada um.
- Se o bloco aparecer com borda vermelha e um ícone de alerta, falta configuração.

## Onde ficam salvas essas informações

**No perfil de cada pessoa, em Personas (Pessoas).** O que o doador escreve no formulário, ou o que sua equipe preenche à mão, fica salvo no perfil dele.

Os campos são preenchidos:
- quando a pessoa completa um formulário que tem o campo;
- quando sua equipe cria uma pessoa com "Crear persona" (Criar pessoa) ou a edita, na seção **Información Personalizada** (Informação personalizada).

## Onde posso vê-las

1. **No perfil da pessoa.** Abra a pessoa em **Personas**, aba **Contacto** (Contato), cartão **Más información** (Mais informações), seção **Información Personalizada**. Você verá cada campo com seu valor, ou "-" se estiver vazio. A seção só aparece se a pessoa tiver algum campo personalizado.
   ![Perfil de uma pessoa, aba Contacto, com a seção Información Personalizada no cartão Más información](img/donde-ver-los-campos-personalizados-01.webp)

2. **No download de pessoas.** Ao baixar sua lista de pessoas com **Base de datos en tiempo real** (Base de dados em tempo real), cada campo personalizado sai em uma coluna própria.

3. **Nos seus e-mails.** Em um autoresponder você pode mostrar o valor com o merge tag `{{customFields.<campo>}}`, trocando `<campo>` pelo nome do seu campo.

**Atenção:** nas landings, os campos personalizados não funcionam como variáveis: se você os escrever, o doador vê o texto como está, com as chaves.

---

## Perguntas frequentes

**Posso pedir vários campos personalizados no mesmo formulário?**
Sim. Adicione um bloco **Campo personalizado** para cada um.

**Posso ver os campos personalizados no Excel?**
Sim. Baixe sua lista de pessoas com **Base de datos en tiempo real**: cada campo sai em uma coluna.

---

> **[Voltar ao índice da seção](./README.md)** · **[Voltar ao índice geral](../README.md)**

*Última atualização: 2026-10-26*
