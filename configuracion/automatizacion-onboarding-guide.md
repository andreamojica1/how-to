# Guía de Automatización Onboarding: tu dominio de correo

Con esta guía vas a configurar tus DNS para que Afrus envíe tus correos con el dominio de tu organización (por ejemplo, `tuorg.org`).

*Módulo: Configuración · Se abre desde el botón "Configurar DNS" en **Interacciones > Autoresponders**, **Interacciones > Blast** o **Interacciones > Flujos de trabajo** · Audiencia: administración, comunicaciones y quien gestiona el dominio*

---

## Qué es

**Es el paso en el que autorizas a Afrus a enviar correos con el dominio de tu organización.** Para eso se crean unos registros (DNS) en el proveedor donde tienes tu dominio.

Mientras no lo configures, tus correos salen desde una cuenta de Afrus.

La pantalla se llama **Dominios de correo electrónico** y se abre en la versión anterior de Afrus, por eso se ve distinta.

## Para qué sirve

- **Enviar desde tu propio correo.** Tus donantes reciben los correos desde una dirección de tu organización, por ejemplo `donaciones@tuorg.org`.
- **Llegar mejor a la bandeja de entrada.** Como dice la pantalla, configurar tus DNS te permite "usar tu correo con tu dominio y mejorar la entregabilidad".
- **Crear flujos de trabajo.** Para crear un flujo en **Interacciones > Flujos de trabajo** necesitas el dominio verificado.
- **Elegir remitente.** Al verificar el dominio, en el remitente de autoresponders y Blast aparecen los correos de los usuarios de tu organización que terminan en ese dominio.

## Cómo saber si ya está configurado

Arriba de **Interacciones > Autoresponders** y de **Interacciones > Blast** verás una tarjeta con uno de estos estados:

| Tarjeta | Qué significa |
|---|---|
| **Dominio verificado** | Ya está listo: tus correos salen con tu dominio |
| **No tienes un dominio verificado para Email** | Tus correos salen desde una cuenta de Afrus |
| **Error en registros DNS** | Hay un problema con los registros; hay que corregirlos |

![Tarjeta del dominio de envío arriba de Autoresponders con el botón Configurar DNS](img/que-es-la-automatizacion-onboarding-01.webp)

---

# Paso a paso

## Cómo configurar mis DNS en Afrus

**Antes de empezar:**
- **Ten acceso al panel de tu proveedor de dominio** (donde compraste el dominio) o pide ayuda a quien lo maneja en tu equipo.
- **La cuenta de envío de tu organización debe estar configurada por Afrus.** Si al empezar ves *"Hubo un error al crear el dominio"*, escríbenos.

1. **Abre la configuración.** En **Interacciones > Autoresponders** o **Interacciones > Blast**, haz clic en "Configurar DNS" en la tarjeta del dominio.

2. **Escribe tu dominio.** En el paso 1, **Configurar dominio**, escribe tu **Dominio** (por ejemplo, `ejemplo.com`), haz clic en "Iniciar autenticación" y luego en "Continuar".
   <!-- captura pendiente: como-configurar-mis-dns-en-afrus-02 — paso 1 del asistente con el campo Dominio -->

3. **Indica tu proveedor.** En el paso 2, responde *"¿Cuál es tu proveedor de DNS?"* y sigue las instrucciones para entrar a su panel. Haz clic en "Continuar".

4. **Crea los registros DKIM.** En el paso 3, la pantalla te muestra 3 registros de tipo **CNAME**, cada uno con su **Nombre** y su **Valor**. Cópialos con el botón de copiar y créalos en el panel de tu proveedor. Haz clic en "Continuar".
   <!-- captura pendiente: como-configurar-mis-dns-en-afrus-04 — paso 3 con los tres registros CNAME -->

5. **Crea los registros DMARC.** En el paso 4, crea en tu proveedor los registros que muestra la tabla: dos de tipo **TXT** y uno de tipo **MX** con **Prioridad** 10. Haz clic en "Finalizar".

Al terminar, la pantalla muestra tu dominio y su estado: **Pendiente**, **Exitoso**, **Fallido**, **Fallido temporalmente** o **No iniciado**. Como dice la pantalla: *"La validación puede tardar hasta 48 horas, aunque, por lo general, el proceso es mucho más rápido."*

**Para revisar el estado:** el estado se actualiza cuando abres la pantalla o cuando haces clic en "Comprobar estado".

> **¿Se puede deshacer?** El icono de borrar junto al dominio lo elimina. Si lo borras, tus correos vuelven a salir desde una cuenta de Afrus.
> **Pendiente de confirmar:** si al borrar el dominio hay una confirmación.

**Para enviar desde una dirección concreta** (por ejemplo `donaciones@tuorg.org`): esa dirección tiene que ser de un usuario de tu organización.

---

## Limitaciones conocidas

- Si tu organización nunca configuró un dominio, la tarjeta puede mostrar **Error en registros DNS** en lugar de "No tienes un dominio verificado". En ese caso, sigue igual los pasos de esta guía.
- El estado no se actualiza solo mientras tienes la pantalla abierta: usa "Comprobar estado".

## Preguntas frecuentes

**¿Cuánto tarda la verificación?**
Puede tardar hasta 48 horas, aunque por lo general es mucho más rápido.

**¿Afrus me avisa cuando termina?**
> **Pendiente de confirmar:** si Afrus envía un correo cuando termina la validación.

**¿Dónde está "Automatización Onboarding" en el menú?**
> **Pendiente de confirmar:** si existe una opción de menú con ese nombre. Hoy llegas a esta pantalla con el botón "Configurar DNS".

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-26*
