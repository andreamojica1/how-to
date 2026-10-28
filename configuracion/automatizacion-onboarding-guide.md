# Guía de Automatización Onboarding: tu dominio de correo

Con esta guía vas a configurar tus DNS para que AFRUS envíe tus correos con el dominio de tu organización (por ejemplo, `tuorg.org`).

*Módulo: Configuración · Se abre desde el botón "Configurar DNS" en **Interacciones > Autoresponders**, **Interacciones > Blast** o **Interacciones > Flujos de trabajo** · Audiencia: administración, comunicaciones y quien gestiona el dominio*

---

## Qué es

**Es el paso en el que autorizas a AFRUS a enviar correos con el dominio de tu organización.** Para eso se crean unos registros (DNS) en el proveedor donde tienes tu dominio.

Mientras no lo configures, tus correos salen desde una cuenta de AFRUS.

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
| **No tienes un dominio verificado para Email** | Tus correos salen desde una cuenta de AFRUS |
| **Error en registros DNS** | Hay un problema con los registros; hay que corregirlos |

![Tarjeta del dominio de envío arriba de Autoresponders con el botón Configurar DNS](img/que-es-la-automatizacion-onboarding-01.webp)

---

# Paso a paso

## Cómo configurar mis DNS en AFRUS

**Antes de empezar:**
- **Ten acceso al panel de tu proveedor de dominio** (donde compraste el dominio) o pide ayuda a quien lo maneja en tu equipo.
- **La cuenta de envío de tu organización debe estar configurada por AFRUS.** Si al empezar ves *"Hubo un error al crear el dominio"*, escríbenos.

1. **Abre la configuración.** En **Interacciones > Autoresponders** o **Interacciones > Blast**, haz clic en "Configurar DNS" en la tarjeta del dominio.

2. **Escribe tu dominio.** En el paso 1, **Configurar dominio**, escribe tu **Dominio** (por ejemplo, `ejemplo.com`), haz clic en "Iniciar autenticación" y luego en "Continuar".
   ![Paso 1 del asistente con el campo Dominio](img/como-configurar-mis-dns-en-afrus-02.webp)

3. **Indica tu proveedor.** En el paso 2, responde *"¿Cuál es tu proveedor de DNS?"* y sigue las instrucciones para entrar a su panel. Haz clic en "Continuar".

4. **Crea los registros DKIM.** En el paso 3, la pantalla te muestra 3 registros de tipo **CNAME**, cada uno con su **Nombre** y su **Valor**. Cópialos con el botón de copiar y créalos en el panel de tu proveedor. Haz clic en "Continuar".
   ![Paso 3 con los tres registros CNAME](img/como-configurar-mis-dns-en-afrus-04.webp)

5. **Crea los registros DMARC.** En el paso 4, crea en tu proveedor los registros que muestra la tabla: dos de tipo **TXT** y uno de tipo **MX** con **Prioridad** 10. Haz clic en "Finalizar".

Al terminar, la pantalla muestra tu dominio y su estado: **Pendiente**, **Exitoso**, **Fallido**, **Fallido temporalmente** o **No iniciado**. Como dice la pantalla: *"La validación puede tardar hasta 48 horas, aunque, por lo general, el proceso es mucho más rápido."*

**Para revisar el estado:** el estado se actualiza cuando abres la pantalla o cuando haces clic en "Comprobar estado".

> **¿Se puede deshacer?** El icono de borrar junto al dominio lo elimina. Si lo borras, tus correos vuelven a salir desde una cuenta de AFRUS.

**Para enviar desde una dirección concreta** (por ejemplo `donaciones@tuorg.org`): esa dirección tiene que ser de un usuario de tu organización.

---

## Preguntas frecuentes

**¿Cuánto tarda la verificación?**
Puede tardar hasta 48 horas, aunque por lo general es mucho más rápido.

**¿AFRUS me avisa cuando termina?**
No, no te avisa. Debes revisar si el dominio quedó validado: cuando lo esté, verás el dominio verificado en **Interacciones > Blast** o en **Interacciones > Autoresponders**.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-28*
