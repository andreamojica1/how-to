# Importaciones — tutoriales web (afrus.ai/howto)

Un bloque por tutorial, listo para pegar. Orden: español, inglés, portugués.

## Español

```text
=== TUTORIAL ===
Idioma: es
Título: Qué son las importaciones
Slug: que-son-las-importaciones
Categoría: Data
Resumen: Aprende qué son las importaciones en AFRUS: subir de una vez una lista de contactos o de donaciones desde un archivo.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-sirven-las-importaciones, como-importar-un-archivo, que-tener-en-cuenta-al-importar, resultados-de-una-importacion
--- CUERPO (HTML) ---
<p><strong>Importar es subir a AFRUS muchos datos a la vez desde un archivo</strong>, en lugar de cargarlos uno por uno.</p>
<p>En <strong>Data &gt; Importaciones</strong> puedes subir dos tipos de listas:</p>
<ul>
<li><strong>Leads:</strong> tus contactos (personas).</li>
<li><strong>Transacciones:</strong> donaciones que recibiste antes o por fuera de AFRUS.</li>
</ul>
<p>Si tu organización está en Brasil y quieres subir el archivo de boletos pagados del banco, eso se hace en <strong>Follow up &gt; Importaciones - itaú</strong>.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Para qué sirven las importaciones
Slug: para-que-sirven-las-importaciones
Categoría: Data
Resumen: Aprende para qué sirven las importaciones: traer contactos, cargar tu historial de donaciones y actualizar datos.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-las-importaciones, como-importar-un-archivo, que-tener-en-cuenta-al-importar
--- CUERPO (HTML) ---
<ul>
<li><strong>Traer tus contactos desde otro sistema</strong> sin escribirlos a mano.</li>
<li><strong>Cargar tu historial de donaciones,</strong> para tener en AFRUS la información completa de cada donante.</li>
<li><strong>Actualizar datos de personas que ya tienes.</strong> Si una persona del archivo ya existe, se actualiza con los datos nuevos.</li>
<li><strong>Agrupar lo que importas.</strong> Puedes ponerle un tag a todas las personas del archivo para encontrarlas después.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Cómo importar un archivo
Slug: como-importar-un-archivo
Categoría: Data
Resumen: Aprende a subir a AFRUS un archivo de Excel o CSV con tus contactos o tus donaciones, paso a paso.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-las-importaciones, que-tener-en-cuenta-al-importar, resultados-de-una-importacion
--- CUERPO (HTML) ---
<h2>Antes de empezar</h2>
<ul>
<li><strong>Tu archivo en Excel o CSV</strong> (.xlsx, .xls o .csv), de hasta 20 MB.</li>
<li><strong>Para importar donaciones,</strong> tu organización necesita tener activa la pasarela "Simple AFRUS" en la moneda de esas donaciones.</li>
</ul>
<h2>Paso a paso</h2>
<ol>
<li><strong>Abre las importaciones.</strong> Ve a <strong>Data &gt; Importaciones</strong> y haz clic en "Importar".</li>
<li><strong>Elige qué vas a importar.</strong> Elige <strong>Leads</strong> (contactos) o <strong>Transacciones</strong> (donaciones) y haz clic en "Continuar".</li>
<li><strong>Sube tu archivo.</strong> Haz clic en "Añadir archivos" o arrástralo.</li>
<li><strong>Confirma el permiso de tus contactos (solo Leads).</strong> Marca la casilla de consentimiento y haz clic en "Importar".</li>
<li><strong>Une cada columna con su campo en AFRUS.</strong> Por ejemplo, tu columna "Mail" va con correo electrónico.</li>
<li><strong>Ponle un tag (opcional)</strong> para encontrar después a todas las personas del archivo.</li>
<li><strong>Solo para donaciones,</strong> elige la moneda, el estado de las donaciones y la campaña.</li>
<li><strong>Envía.</strong> Haz clic en "Siguiente" y luego en "Enviar". Verás <em>"¡Listo!"</em>.</li>
</ol>
<p>Tu importación aparece en la lista como <strong>En cola</strong> o <strong>Procesando</strong>, y luego como <strong>Finalizado</strong> o <strong>Finalizado con errores</strong>.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Se puede deshacer?</strong> No hay un botón para deshacer una importación. Si importas donaciones dos veces, quedan repetidas.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Qué tener en cuenta al importar
Slug: que-tener-en-cuenta-al-importar
Categoría: Data
Resumen: Aprende a preparar tu archivo antes de importarlo a AFRUS para evitar errores y datos repetidos.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-las-importaciones, como-importar-un-archivo, resultados-de-una-importacion
--- CUERPO (HTML) ---
<h2>Sobre el archivo</h2>
<ul>
<li><strong>Usa solo la primera hoja.</strong> AFRUS solo lee la primera hoja del Excel.</li>
<li><strong>La primera fila debe tener los títulos</strong> de cada columna.</li>
<li><strong>Escribe las fechas como día/mes/año,</strong> por ejemplo 25/10/2026.</li>
</ul>
<h2>Datos obligatorios</h2>
<ul>
<li><strong>Leads:</strong> correo electrónico y nombre.</li>
<li><strong>Transacciones:</strong> monto (solo números), correo electrónico y nombre.</li>
</ul>
<p>Si falta el correo, la pantalla te deja seguir, pero todas las filas fallan.</p>
<h2>Personas y donaciones repetidas</h2>
<ul>
<li><strong>AFRUS reconoce a cada persona por su correo.</strong> Si ya existe, la actualiza; si no, la crea.</li>
<li><strong>Cada fila crea una donación nueva.</strong> Si subes el mismo archivo dos veces, las donaciones quedan duplicadas.</li>
</ul>
<h2>Permisos de contacto</h2>
<p>Al importar, AFRUS marca a cada persona como que <strong>acepta recibir comunicaciones por todos los canales</strong>, incluso si antes se había dado de baja. Incluye solo a personas que te dieron su permiso.</p>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Cómo escribo los teléfonos y el tipo de documento?</strong> Los teléfonos van con el indicativo del país y el signo "+". Para el tipo de documento, escribe el número que corresponde:</p><ul><li>National Identification Document: <strong>4</strong></li><li>CPF: <strong>8</strong> (Brasil)</li><li>CNPJ: <strong>9</strong></li><li>NIE: <strong>13</strong> (España)</li><li>NIF: <strong>14</strong> (España)</li><li>Passport: <strong>1</strong></li><li>Cédula de ciudadanía: <strong>16</strong></li><li>Cédula de extranjería: <strong>17</strong></li><li>RUC: <strong>18</strong></li></ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: es
Título: Resultados de una importación
Slug: resultados-de-una-importacion
Categoría: Data
Resumen: Aprende a revisar si tu importación terminó bien y qué hacer si quedó con errores.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: que-son-las-importaciones, como-importar-un-archivo, que-tener-en-cuenta-al-importar
--- CUERPO (HTML) ---
<p>En <strong>Data &gt; Importaciones</strong> ves todas tus importaciones con su <strong>Status</strong>, el <strong>Archivo</strong>, la <strong>Fecha</strong> y quién la hizo.</p>
<ul>
<li><strong>En cola:</strong> espera su turno.</li>
<li><strong>Procesando:</strong> AFRUS la está cargando.</li>
<li><strong>Finalizado:</strong> terminó sin errores.</li>
<li><strong>Finalizado con errores:</strong> algunas filas, o todas, no se pudieron cargar.</li>
</ul>
<h2>Si quedó con errores</h2>
<ol>
<li><strong>Abre los errores.</strong> Haz clic en el lápiz de la importación para ver las filas que fallaron.</li>
<li><strong>Corrige el archivo.</strong> Por ahora, reenviar las filas desde esa pantalla no funciona. Corrige esas filas en tu archivo y vuelve a importar solo esas filas.</li>
</ol>
<h2>Preguntas frecuentes</h2>
<p><strong>¿Por qué no veo la importación de un compañero?</strong> Cada usuario ve solo las importaciones que hizo él.</p>
=== FIN ===
```

## English

```text
=== TUTORIAL ===
Idioma: en
Título: What imports are
Slug: what-are-imports
Categoría: Data
Resumen: Learn what imports are in AFRUS: uploading a list of contacts or donations from a file, all at once.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-imports-for, how-to-import-a-file, what-to-check-before-importing, import-results
--- CUERPO (HTML) ---
<p><strong>Importing means uploading a lot of data to AFRUS at once from a file</strong>, instead of entering it one by one.</p>
<p>In <strong>Data &gt; Importaciones</strong> (Imports) you can upload two kinds of lists:</p>
<ul>
<li><strong>Leads:</strong> your contacts (people).</li>
<li><strong>Transacciones</strong> (Transactions): donations you received earlier or outside AFRUS.</li>
</ul>
<p>If your organization is in Brazil and you want to upload the bank's file of paid boletos, that is done in <strong>Follow up &gt; Importaciones - itaú</strong>.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: What imports are for
Slug: what-are-imports-for
Categoría: Data
Resumen: Learn what imports are for: bringing in contacts, loading your donation history and updating data.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-imports, how-to-import-a-file, what-to-check-before-importing
--- CUERPO (HTML) ---
<ul>
<li><strong>Bringing your contacts from another system</strong> without typing them in.</li>
<li><strong>Loading your donation history,</strong> so AFRUS has each donor's full information.</li>
<li><strong>Updating people you already have.</strong> If a person in the file already exists, they are updated with the new data.</li>
<li><strong>Grouping what you import.</strong> You can give everyone in the file a tag to find them later.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: How to import a file
Slug: how-to-import-a-file
Categoría: Data
Resumen: Learn how to upload an Excel or CSV file with your contacts or donations to AFRUS, step by step.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-imports, what-to-check-before-importing, import-results
--- CUERPO (HTML) ---
<p>Labels are shown as they appear in the Spanish version of the console.</p>
<h2>Before you start</h2>
<ul>
<li><strong>Your file in Excel or CSV</strong> (.xlsx, .xls or .csv), up to 20 MB.</li>
<li><strong>To import donations,</strong> your organization needs the "Simple AFRUS" gateway active in the currency of those donations.</li>
</ul>
<h2>Step by step</h2>
<ol>
<li><strong>Open imports.</strong> Go to <strong>Data &gt; Importaciones</strong> and click "Importar" (Import).</li>
<li><strong>Choose what you will import.</strong> Choose <strong>Leads</strong> (contacts) or <strong>Transacciones</strong> (donations) and click "Continuar" (Continue).</li>
<li><strong>Upload your file.</strong> Click "Añadir archivos" (Add files) or drag it in.</li>
<li><strong>Confirm your contacts' permission (Leads only).</strong> Check the consent box and click "Importar".</li>
<li><strong>Match each column to its AFRUS field.</strong> For example, your "Mail" column goes with email.</li>
<li><strong>Add a tag (optional)</strong> to find everyone in the file later.</li>
<li><strong>For donations only,</strong> choose the currency, the donations' status and the campaign.</li>
<li><strong>Send.</strong> Click "Siguiente" (Next) and then "Enviar" (Send). You will see <em>"¡Listo!"</em> (Done!).</li>
</ol>
<p>Your import appears in the list as <strong>En cola</strong> (Queued) or <strong>Procesando</strong> (Processing), then as <strong>Finalizado</strong> (Finished) or <strong>Finalizado con errores</strong> (Finished with errors).</p>
<h2>Frequently asked questions</h2>
<p><strong>Can it be undone?</strong> There is no button to undo an import. If you import donations twice, they are duplicated.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: What to check before importing
Slug: what-to-check-before-importing
Categoría: Data
Resumen: Learn how to prepare your file before importing it into AFRUS to avoid errors and duplicates.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-imports, how-to-import-a-file, import-results
--- CUERPO (HTML) ---
<h2>About the file</h2>
<ul>
<li><strong>Use only the first sheet.</strong> AFRUS only reads the first sheet of the Excel file.</li>
<li><strong>The first row must have the column titles.</strong></li>
<li><strong>Write dates as day/month/year,</strong> for example 25/10/2026.</li>
</ul>
<h2>Required data</h2>
<ul>
<li><strong>Leads:</strong> email and name.</li>
<li><strong>Transacciones</strong> (donations): amount (numbers only), email and name.</li>
</ul>
<p>If the email is missing, the screen lets you continue, but every row fails.</p>
<h2>Repeated people and donations</h2>
<ul>
<li><strong>AFRUS recognizes each person by their email.</strong> If they exist, they are updated; if not, they are created.</li>
<li><strong>Each row creates a new donation.</strong> If you upload the same file twice, the donations are duplicated.</li>
</ul>
<h2>Contact permissions</h2>
<p>When importing, AFRUS marks each person as <strong>accepting communications on all channels</strong>, even if they had unsubscribed before. Include only people who gave you their permission.</p>
<h2>Frequently asked questions</h2>
<p><strong>How do I write phone numbers and document type?</strong> Phone numbers must include the country code and the "+" sign. For the document type, write the matching number:</p><ul><li>National Identification Document: <strong>4</strong></li><li>CPF: <strong>8</strong> (Brazil)</li><li>CNPJ: <strong>9</strong></li><li>NIE: <strong>13</strong> (Spain)</li><li>NIF: <strong>14</strong> (Spain)</li><li>Passport: <strong>1</strong></li><li>Cédula de ciudadanía: <strong>16</strong></li><li>Cédula de extranjería: <strong>17</strong></li><li>RUC: <strong>18</strong></li></ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: en
Título: Import results
Slug: import-results
Categoría: Data
Resumen: Learn how to check whether your import finished correctly and what to do if it has errors.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: what-are-imports, how-to-import-a-file, what-to-check-before-importing
--- CUERPO (HTML) ---
<p>In <strong>Data &gt; Importaciones</strong> you see all your imports with their <strong>Status</strong>, <strong>Archivo</strong> (File), <strong>Fecha</strong> (Date) and who did it.</p>
<ul>
<li><strong>En cola</strong> (Queued): waiting its turn.</li>
<li><strong>Procesando</strong> (Processing): AFRUS is loading it.</li>
<li><strong>Finalizado</strong> (Finished): finished without errors.</li>
<li><strong>Finalizado con errores</strong> (Finished with errors): some rows, or all, couldn't be loaded.</li>
</ul>
<h2>If it has errors</h2>
<ol>
<li><strong>Open the errors.</strong> Click the pencil on the import to see the rows that failed.</li>
<li><strong>Fix the file.</strong> For now, resending rows from that screen doesn't work. Fix those rows in your file and import only those rows again.</li>
</ol>
<h2>Frequently asked questions</h2>
<p><strong>Why can't I see a teammate's import?</strong> Each user only sees the imports they did.</p>
=== FIN ===
```

## Português

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: O que são as importações
Slug: o-que-sao-as-importacoes
Categoría: Data
Resumen: Aprenda o que são as importações na AFRUS: subir de uma vez uma lista de contatos ou de doações a partir de um arquivo.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: para-que-servem-as-importacoes, como-importar-um-arquivo, o-que-considerar-ao-importar, resultados-de-uma-importacao
--- CUERPO (HTML) ---
<p><strong>Importar é subir para a AFRUS muitos dados de uma vez a partir de um arquivo</strong>, em vez de cadastrá-los um por um.</p>
<p>Em <strong>Data &gt; Importaciones</strong> (Importações) você pode subir dois tipos de listas:</p>
<ul>
<li><strong>Leads:</strong> seus contatos (pessoas).</li>
<li><strong>Transacciones</strong> (Transações): doações que você recebeu antes ou fora da AFRUS.</li>
</ul>
<p>Se você quer subir o arquivo de boletos pagos do banco, isso é feito em <strong>Follow up &gt; Importaciones - itaú</strong>.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Para que servem as importações
Slug: para-que-servem-as-importacoes
Categoría: Data
Resumen: Aprenda para que servem as importações: trazer contatos, carregar seu histórico de doações e atualizar dados.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-as-importacoes, como-importar-um-arquivo, o-que-considerar-ao-importar
--- CUERPO (HTML) ---
<ul>
<li><strong>Trazer seus contatos de outro sistema</strong> sem digitá-los.</li>
<li><strong>Carregar seu histórico de doações,</strong> para ter na AFRUS a informação completa de cada doador.</li>
<li><strong>Atualizar pessoas que você já tem.</strong> Se uma pessoa do arquivo já existe, ela é atualizada com os dados novos.</li>
<li><strong>Agrupar o que você importa.</strong> Você pode colocar uma tag em todas as pessoas do arquivo para encontrá-las depois.</li>
</ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Como importar um arquivo
Slug: como-importar-um-arquivo
Categoría: Data
Resumen: Aprenda a subir para a AFRUS um arquivo Excel ou CSV com seus contatos ou doações, passo a passo.
Tiempo de lectura: 2 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-as-importacoes, o-que-considerar-ao-importar, resultados-de-uma-importacao
--- CUERPO (HTML) ---
<p>Os nomes de tela aparecem como na versão em espanhol do console.</p>
<h2>Antes de começar</h2>
<ul>
<li><strong>Seu arquivo em Excel ou CSV</strong> (.xlsx, .xls ou .csv), de até 20 MB.</li>
<li><strong>Para importar doações,</strong> sua organização precisa ter ativo o gateway "Simple AFRUS" na moeda dessas doações.</li>
</ul>
<h2>Passo a passo</h2>
<ol>
<li><strong>Abra as importações.</strong> Acesse <strong>Data &gt; Importaciones</strong> e clique em "Importar".</li>
<li><strong>Escolha o que vai importar.</strong> Escolha <strong>Leads</strong> (contatos) ou <strong>Transacciones</strong> (doações) e clique em "Continuar".</li>
<li><strong>Suba seu arquivo.</strong> Clique em "Añadir archivos" (Adicionar arquivos) ou arraste-o.</li>
<li><strong>Confirme a permissão dos seus contatos (só Leads).</strong> Marque a caixa de consentimento e clique em "Importar".</li>
<li><strong>Ligue cada coluna ao seu campo na AFRUS.</strong> Por exemplo, sua coluna "Mail" vai com e-mail.</li>
<li><strong>Coloque uma tag (opcional)</strong> para encontrar depois todas as pessoas do arquivo.</li>
<li><strong>Só para doações,</strong> escolha a moeda, o status das doações e a campanha.</li>
<li><strong>Envie.</strong> Clique em "Siguiente" (Próximo) e depois em "Enviar". Você verá <em>"¡Listo!"</em> (Pronto!).</li>
</ol>
<p>Sua importação aparece na lista como <strong>En cola</strong> (Na fila) ou <strong>Procesando</strong> (Processando), e depois como <strong>Finalizado</strong> ou <strong>Finalizado con errores</strong> (com erros).</p>
<h2>Perguntas frequentes</h2>
<p><strong>Dá para desfazer?</strong> Não há um botão para desfazer uma importação. Se você importar doações duas vezes, elas ficam repetidas.</p>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: O que considerar ao importar
Slug: o-que-considerar-ao-importar
Categoría: Data
Resumen: Aprenda a preparar seu arquivo antes de importá-lo para a AFRUS para evitar erros e dados repetidos.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-as-importacoes, como-importar-um-arquivo, resultados-de-uma-importacao
--- CUERPO (HTML) ---
<h2>Sobre o arquivo</h2>
<ul>
<li><strong>Use só a primeira planilha.</strong> A AFRUS só lê a primeira aba do Excel.</li>
<li><strong>A primeira linha deve ter os títulos</strong> de cada coluna.</li>
<li><strong>Escreva as datas como dia/mês/ano,</strong> por exemplo 25/10/2026.</li>
</ul>
<h2>Dados obrigatórios</h2>
<ul>
<li><strong>Leads:</strong> e-mail e nome.</li>
<li><strong>Transacciones</strong> (doações): valor (só números), e-mail e nome.</li>
</ul>
<p>Se faltar o e-mail, a tela deixa você continuar, mas todas as linhas falham.</p>
<h2>Pessoas e doações repetidas</h2>
<ul>
<li><strong>A AFRUS reconhece cada pessoa pelo e-mail.</strong> Se ela já existe, é atualizada; se não, é criada.</li>
<li><strong>Cada linha cria uma doação nova.</strong> Se você subir o mesmo arquivo duas vezes, as doações ficam duplicadas.</li>
</ul>
<h2>Permissões de contato</h2>
<p>Ao importar, a AFRUS marca cada pessoa como <strong>aceitando comunicações por todos os canais</strong>, mesmo que antes tenha pedido para sair. Inclua só pessoas que deram permissão.</p>
<h2>Perguntas frequentes</h2>
<p><strong>Como escrevo os telefones e o tipo de documento?</strong> Os telefones devem ter o código do país e o sinal "+". Para o tipo de documento, escreva o número correspondente:</p><ul><li>National Identification Document: <strong>4</strong></li><li>CPF: <strong>8</strong> (Brasil)</li><li>CNPJ: <strong>9</strong></li><li>NIE: <strong>13</strong> (Espanha)</li><li>NIF: <strong>14</strong> (Espanha)</li><li>Passport: <strong>1</strong></li><li>Cédula de ciudadanía: <strong>16</strong></li><li>Cédula de extranjería: <strong>17</strong></li><li>RUC: <strong>18</strong></li></ul>
=== FIN ===
```

```text
=== TUTORIAL ===
Idioma: pt-BR
Título: Resultados de uma importação
Slug: resultados-de-uma-importacao
Categoría: Data
Resumen: Aprenda a conferir se sua importação terminou bem e o que fazer se ela ficou com erros.
Tiempo de lectura: 1 min
Video: no
Imagen de portada: pendiente
Relacionados: o-que-sao-as-importacoes, como-importar-um-arquivo, o-que-considerar-ao-importar
--- CUERPO (HTML) ---
<p>Em <strong>Data &gt; Importaciones</strong> você vê todas as suas importações com o <strong>Status</strong>, o <strong>Archivo</strong> (Arquivo), a <strong>Fecha</strong> (Data) e quem fez.</p>
<ul>
<li><strong>En cola</strong> (Na fila): esperando a vez.</li>
<li><strong>Procesando</strong> (Processando): a AFRUS está carregando.</li>
<li><strong>Finalizado:</strong> terminou sem erros.</li>
<li><strong>Finalizado con errores</strong> (com erros): algumas linhas, ou todas, não puderam ser carregadas.</li>
</ul>
<h2>Se ficou com erros</h2>
<ol>
<li><strong>Abra os erros.</strong> Clique no lápis da importação para ver as linhas que falharam.</li>
<li><strong>Corrija o arquivo.</strong> Por enquanto, reenviar as linhas nessa tela não funciona. Corrija essas linhas no seu arquivo e importe de novo só essas linhas.</li>
</ol>
<h2>Perguntas frequentes</h2>
<p><strong>Por que não vejo a importação de um colega?</strong> Cada usuário vê só as importações que ele fez.</p>
=== FIN ===
```
