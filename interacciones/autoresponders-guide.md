# Guía de Autoresponders

Con esta guía vas a poder enviar correos automáticos a tus donantes y contactos: un agradecimiento cuando donan, un aviso cuando un pago falla y mucho más, sin tener que escribirlos uno por uno.

*Módulo: Autoresponders · Menú: **Interacciones > Autoresponders** · Audiencia: equipos de comunicaciones y recaudación*

---

## Qué es un autoresponder

**Un autoresponder es un correo que Afrus envía solo, a una persona, cuando pasa algo.** Por ejemplo: cuando alguien se registra, cuando su donación se confirma o falla, o cuando se le cobra su donación mensual.

Tú escribes el correo una vez y Afrus lo envía cada vez que ocurre ese evento.

## Para qué sirve

- **Agradecer cada donación al instante.** El donante recibe tu mensaje a los pocos minutos, sin trabajo manual.
- **Avisar cuando algo sale mal.** Por ejemplo, si un pago falla, queda pendiente o la persona no terminó de donar.
- **Hablarle a cada persona en su idioma.** Puedes tener el mismo correo en español, inglés y portugués.
- **Personalizar por campaña o por formulario.** Puedes tener un mensaje general para toda la organización y mensajes especiales para una campaña o un formulario de donación.

## Antes de empezar

- **Un correo desde el cual enviar.** Siempre puedes usar el correo de Afrus. Si quieres enviar desde el correo de tu organización (por ejemplo, donaciones@tuorg.org), primero hay que verificar tu dominio. Lo ves en la tarjeta que aparece arriba de la lista de autoresponders.
- **Tener claro el evento.** Piensa en qué momento quieres que llegue el correo: al donar, al registrarse, al fallar un pago…

> **Recomendado:** verificar tu dominio ayuda a que tus correos lleguen a la bandeja de entrada. El botón "Configurar DNS" de la tarjeta abre la versión anterior de Afrus, por eso se ve distinta. La verificación puede tardar hasta 48 horas.

---

# Paso a paso

## Cómo se usa

### Parte 1 — Elige dónde y cuándo se envía

1. **Abre los autoresponders.** Ve a **Interacciones > Autoresponders**.
   <!-- captura pendiente: autoresponders-01 — lista de Autoresponders con las pestañas Genérico, Por Campaña, Por widget y el selector de idioma -->

2. **Elige el idioma.** Arriba de la lista, elige **Español (ES)**, **Inglés (EN)** o **Portugués (PT)**. El autoresponder que crees quedará en ese idioma.

3. **Empieza uno nuevo.** Haz clic en "Nuevo autoresponder".

4. **Elige dónde aplica.** En **Contexto**, elige **Genérico** (para toda la organización), **Por campaña** (y elige la campaña) o **Por formulario** (y elige el formulario). Haz clic en "Siguiente".
   <!-- captura pendiente: autoresponders-04 — asistente Nuevo autoresponder, paso Contexto -->

5. **Elige el momento.** En **Evento**, elige cuándo se envía, por ejemplo **Transacción registrada** ("Cuando se confirma una transacción exitosa"). Solo aparecen los eventos que todavía no tienen correo en ese idioma.

6. **Elige el modo.** En **Modo y canal**, elige **Manual** para diseñar tú el correo. El canal es **Email**.

7. **Confirma.** Revisa el resumen y haz clic en "Confirmar e ir al editor".

### Parte 2 — Escribe los datos del correo

8. **Elige el remitente.** En **Correo de envío**, elige desde qué correo sale.
   <!-- captura pendiente: autoresponders-08 — editor del autoresponder, paso Configuración -->

9. **Ponle un nombre interno (opcional).** En **Nombre interno** escribe un nombre que solo verá tu equipo.

10. **Escribe el asunto.** En **Asunto del correo** escribe lo que verá la persona en su bandeja. Con "Mapa de mergetags" puedes agregar datos de la persona, como su nombre, para que el correo sea más cercano. Debajo está el **Evento disparador**: viene puesto desde el asistente, así que solo revisa que sea el correcto.

11. **Adjunta un archivo (opcional).** En **Archivo adjunto** puedes elegir uno. Por defecto no lleva adjunto.

12. **Continúa.** Haz clic en "Siguiente". Si aún no tienes el contenido listo, usa "Guardar borrador".

### Parte 3 — Diseña el correo y publícalo

13. **Elige cómo diseñarlo.** Tienes cuatro opciones:
    - **Diseño en blanco:** empiezas desde cero con el editor visual.
    - **Galería de diseños:** partes de una plantilla ya hecha.
    - **Autoresponders:** copias un correo que ya tienes.
    - **Editor con código:** para quien trabaja con HTML.
    <!-- captura pendiente: autoresponders-13 — paso Diseño con las cuatro opciones -->

14. **Publícalo.** Arriba a la derecha, enciende **Publicado**.

15. **Guarda.** Haz clic en "Guardar". Verás *"Autoresponder creado correctamente"*.

Al terminar, el autoresponder aparece en la lista como **Activo** y se envía cada vez que ocurre el evento.

> **Importante:** no publiques un correo sin contenido. Revisa siempre el diseño antes de encender **Publicado**.

### Crear un autoresponder con IA

Si prefieres que Afrus escriba el correo por ti:

1. **Busca el evento.** En la pestaña **Genérico**, busca un evento que diga **No configurado** y haz clic en "Configurar".
2. **Elige Con IA.** En **Modo de creación**, elige **Con IA**.
3. **Completa los datos.** Elige el **Remitente**, el **Diseño** (**Plantilla IA** con diseño visual, o **Solo texto**) y, en **URL call to action**, el enlace del botón que llevará el correo.
4. **Guarda.** El autoresponder queda creado y publicado.

> **Importante:** usa el botón "Configurar" de la fila del evento. Si eliges **Con IA** desde "Nuevo autoresponder", se abre igual el editor manual. Y no dejes vacía la **URL call to action**: si lo haces, la lista sigue mostrando el evento como **No configurado**, aunque el correo sí quedó publicado.

### Editar, pausar o eliminar un autoresponder

- **Editar:** en la fila del evento, usa el ícono de editar, cambia lo que necesites y haz clic en "Guardar".
- **Pausar:** apaga el interruptor de la fila. Queda **Inactivo** y no se envía.
- **Ver resultados:** el ícono de ver abre **Ver detalles**, con cuántos correos se enviaron, cuántos se abrieron y cuántos tuvieron clics, y una vista previa del correo. Con "Ver log" ves la lista de cada correo enviado o fallido.
  <!-- captura pendiente: autoresponders-ver-01 — pantalla Ver detalles con las estadísticas -->
- **Eliminar:** ícono de eliminar en la fila.

> **¿Se puede deshacer?** No. Eliminar un autoresponder lo borra al instante, sin pedir confirmación. Si solo quieres dejar de enviarlo por un tiempo, mejor apágalo con el interruptor.

## Qué tener en cuenta si tienes un formulario en varios idiomas

- **Cada idioma es un correo distinto.** Para tener la versión en inglés, cambia el selector de idioma a **Inglés (EN)** y créala aparte. Lo mismo para portugués.
- **Afrus elige el idioma de la persona.** Si la persona tiene un idioma, recibe el correo en ese idioma.
- **Si falta un idioma, se usa el genérico.** Si no tienes el correo en el idioma de la persona, Afrus le envía tu autoresponder **Genérico**, aunque esté en otro idioma. Es mejor recibir un agradecimiento en otro idioma que no recibir nada.
- **Los de campaña y de formulario son más estrictos.** Solo se envían en su idioma exacto. Si no existen en el idioma de la persona, le llega el genérico.

**Recomendación:** si tu formulario recibe donaciones en varios idiomas, crea el autoresponder en cada uno de esos idiomas, empezando por el **Genérico**.

## Cuándo crear un autoresponder genérico, por campaña o por formulario

| Tipo | Cuándo usarlo | Ejemplo |
|---|---|---|
| **Genérico** | Siempre, como base. Es el correo que llega cuando no hay uno más específico | Un agradecimiento general por cualquier donación |
| **Por campaña** | Cuando una campaña necesita un mensaje propio | "Gracias por apoyar nuestra campaña de Navidad" |
| **Por formulario** | Cuando un formulario concreto necesita un mensaje propio | Un correo especial para quienes donan desde tu página de emergencias |

**Cómo elige Afrus qué correo enviar:** busca primero el más específico y, si no lo hay, el más general. El orden es: campaña y formulario juntos, después campaña, después formulario y, al final, el **Genérico**. Solo cuenta lo que esté **Activo**.

**Recomendación:** crea primero el **Genérico** de cada evento importante. Así nadie se queda sin respuesta, aunque una campaña o un formulario no tenga su propio correo.

---

## Estados

| Estado | Qué significa |
|---|---|
| **Activo** | Publicado: se envía cuando ocurre el evento |
| **Inactivo** | Configurado pero apagado: no se envía |
| **Borrador** | Guardado sin diseño: no se envía |
| **No configurado** | No hay correo para ese evento en el idioma elegido |

## Cuándo llega el correo

Afrus revisa los eventos nuevos cada 5 minutos, así que el correo suele llegar a los pocos minutos de que pase el evento.

## Para tener en cuenta

- Por ahora los autoresponders nuevos solo se pueden enviar por correo (no por WhatsApp).
- En **Ver detalles**, la tasa de desuscripción y los errores aparecen como "No registrado": esos datos no se miden en los autoresponders.
- Si tu organización nunca configuró un dominio, la tarjeta de arriba puede decir **Error en registros DNS** en lugar de "No tienes un dominio verificado". En los dos casos, lo que falta es configurar tu dominio.
- Si apagas un autoresponder de campaña o de formulario, y hay un **Genérico** activo para ese evento, se envía el genérico en su lugar.

## Preguntas frecuentes

**¿Desde qué correo salen mis autoresponders?**
Desde el correo de Afrus, hasta que verifiques tu dominio. Después podrás elegir los correos de los usuarios de tu organización que terminen en tu dominio.

**¿Puedo poner el nombre del donante en el correo?**
Sí. Usa el "Mapa de mergetags" para copiar el dato que quieras, por ejemplo el nombre, y pégalo en el asunto o en el cuerpo del correo.

**¿Los autoresponders se envían a personas que se dieron de baja o cuyo correo rebota?**
> **Pendiente de confirmar:** si se excluyen esas personas.

**¿Qué usuarios pueden crear autoresponders?**
> **Pendiente de confirmar:** qué perfiles de usuario tienen permiso.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-26*
