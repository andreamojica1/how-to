# Guía de Dominios

Después de leer esta guía sabrás qué es un dominio propio en Afrus, para qué te sirve y cómo configurarlo para que tus landings se publiquen con la dirección de tu organización.

*Módulo: Dominios · Menú: **Fundraising > Dominios** · Audiencia: equipos de marketing digital, comunicaciones y TI*

---

## Qué es Dominios

**Dominios es la pantalla donde registras el dominio o subdominio propio de tu organización (por ejemplo `donaciones.miorganizacion.org`) para que tus landing pages se publiquen con esa dirección**, en lugar de la dirección por defecto de Afrus (`web.afrus.org`).

Como dice la propia pantalla: *"Asocia un dominio propio para que tus landing pages se vean con la URL de tu organización, fortaleciendo tu marca y generando más confianza en tus campañas."*

## Para qué sirve

- **Publicar tus landings con tu marca.** El donante ve la dirección web de tu organización, lo que genera más confianza.
- **Tener varias direcciones propias** y elegir cuál usa cada landing.
- **Controlar tus dominios:** ver cuántas landings usa cada uno (columna **Páginas**) y activarlos o desactivarlos.
- **Seguridad sin trámites.** Afrus gestiona automáticamente el certificado de seguridad del dominio (el candado, HTTPS): no tienes que comprar ni instalar certificados.

## Antes de empezar

- **Compra el dominio con un proveedor.** Afrus no vende dominios: *"afrus no proporciona los dominios y deben comprarse y configurarse con un proveedor como GoDaddy, Media Temple, etc."*
- **Ten acceso a la configuración DNS** del dominio, en tu proveedor o con tu equipo de TI.
- **Usa un subdominio** (por ejemplo `donaciones.miorganizacion.org`). Es lo recomendado: la pantalla solo pide un registro CNAME y muchos proveedores no permiten un CNAME en el dominio principal (`miorganizacion.org`).

---

# Paso a paso

## Cómo agregar y configurar mi dominio en Afrus

### Parte 1 — En tu proveedor de dominio (fuera de Afrus)

1. **Crea un registro CNAME.** En la configuración DNS de tu dominio, crea este registro, tal como lo indica el recuadro **Importante** de la pantalla de Afrus:

   | Tipo | Nombre / Host | Valor / Destino |
   |---|---|---|
   | CNAME | el subdominio que quieres usar (por ejemplo `donaciones` para `donaciones.miorganizacion.org`; según el proveedor se escribe solo `donaciones` o el nombre completo) | `landings2.afrus.org` |

   Si el valor que muestra la pantalla de Afrus es distinto, usa siempre el de la pantalla.

2. **Espera a que el cambio se propague.** Los cambios de DNS pueden tardar; el tiempo depende de tu proveedor, no de Afrus. Conviene crear el registro y esperar antes de agregar el dominio en Afrus.

### Parte 2 — En Afrus

3. **Abre Dominios.** Entra a **Fundraising > Dominios**.
   <!-- captura pendiente: como-agregar-y-configurar-mi-dominio-03 — tarjeta Agregar dominio personalizado -->

4. **Escribe tu dominio.** En la tarjeta **Agregar dominio personalizado**, en el campo bajo *"¿Cuál es el dominio que te gustaría usar con afrus?"*, escribe tu dominio sin `http://`, `https://`, barras ni rutas, por ejemplo `donaciones.miorganizacion.org`. El campo pasa todo a minúsculas.

5. **Agrégalo.** Pulsa "Agregar dominio" (arriba a la derecha de la tarjeta; se habilita cuando el texto es válido).

Al terminar verás *"Dominio registrado con exito"*, y tu dominio aparecerá en **Lista de dominios** con el **Status** encendido (activo) y la **Versión** "CDN Hosted".

**Qué pasa después:** Afrus deja el dominio listo y solicita automáticamente su certificado de seguridad (HTTPS). Comprueba que el dominio responda de inmediato y luego cada 30 segundos, durante unos 15 minutos. No hay un botón "Verificar" ni tienes que esperar a que nuestro equipo lo apruebe.
- Si la comprobación sale bien, el dominio queda confirmado.
- Si después de esos 15 minutos no lo logra (normalmente porque el registro DNS no está bien o aún no se propagó), el dominio pasa a **inactivo** por sí solo.

> **Importante:** la pantalla no se actualiza sola. Para ver el estado actual, recárgala o cambia el filtro. Mientras el certificado no esté emitido, el dominio figura como activo y ya puedes elegirlo en una landing, pero la dirección `https://` todavía no abre correctamente.

### Parte 3 — Úsalo en tus landings

6. **Asígnalo a una landing.** Al crear o editar una landing, en **Datos básicos**, elige tu dominio en el selector **Dominio**. La landing se publica en `https://<tu-dominio><ruta>`. Lo explicamos en la [guía de Landings](../landings/landings-guide.md).

> **Importante:** agregar el dominio no publica nada por sí solo. Si ninguna landing lo usa, al abrirlo no se verá tu contenido.

### Mensajes que puedes ver

| Mensaje | Qué significa | Qué hacer |
|---|---|---|
| *"Dominio existente, prueba otro"* | Ese dominio ya está registrado en Afrus. Cada dominio solo se puede registrar una vez en toda la plataforma. | Revisa tu **Lista de dominios** o usa otro subdominio. |
| *"El dominio no se encuentra apuntando al Host (landings2.afrus.org)"* | Afrus revisó el DNS y el dominio todavía no apunta a Afrus. | Revisa el registro CNAME y espera a que se propague. |
| *"Error al registrar dominio"* | Otro error. | Vuelve a intentarlo; si persiste, escríbenos a soporte. |
| *"El dominio no puede contener espacios"*, *"El dominio solo puede contener letras, números, puntos y guiones"*, *"El formato del dominio no es válido (ejemplo: dominio.com)"*, *"El dominio debe tener entre 3 y 253 caracteres"* | El texto del campo no es válido. | Corrige el dominio. |

---

## Otras tareas

### Cómo activar o desactivar un dominio

En **Lista de dominios**, usa el interruptor de la columna **Status**. Verás *"Dominio actualizado con exito"*. Un dominio inactivo deja de ofrecerse en el selector **Dominio** de las landings.

> **Pendiente de confirmar:** si desactivar un dominio hace que las landings ya publicadas en él dejen de verse. Para dejar de usar un dominio con seguridad, quítalo de tus landings o elimínalo.

### Cómo eliminar un dominio

1. **Abre el menú de la fila.** En **Lista de dominios**, abre el menú de tres puntos del dominio y elige **Eliminar**.
2. **Confirma.** En el diálogo **Confirmar eliminación**, pulsa "Confirmar".

Verás *"Dominio eliminado con exito"*. Ten en cuenta:
- Aunque el aviso dice que *"las landings asociadas se borrarán"*, **no se borran**: quedan sin dominio y desactivadas. Para seguir usándolas, reactívalas y asígnales otro dominio (o el de Afrus).
- Afrus deja de servir el dominio. El registro DNS en tu proveedor no se toca: puedes borrarlo tú.
- El dominio queda libre para volver a registrarse.

> **¿Se puede deshacer?** No desde la pantalla. Puedes volver a registrar el dominio y reasignarlo a tus landings.

---

## Columnas y estados de la lista

| Columna | Qué muestra |
|---|---|
| **Status** | Interruptor: encendido = activo, apagado = inactivo. Bloqueado cuando el dominio está pendiente de eliminación. |
| **Dominio** | El nombre registrado. |
| **Versión** | "CDN Hosted" (registrado con el sistema actual; los únicos que se pueden elegir en las landings) o "Classic" (dominios del sistema anterior). |
| **Fecha** | Fecha de registro o "Sin fecha". |
| **Páginas** | Cuántas landings usan ese dominio. |

| Situación | Se ve como |
|---|---|
| Certificado de seguridad confirmado | Activo |
| Recién registrado, comprobación en curso | Activo |
| Desactivado por ti, o la comprobación falló tras unos 15 minutos | Inactivo |
| Pendiente de eliminación | Inactivo, con el interruptor bloqueado |

Usa **Filtrar por estado** (Todos / Activos / Inactivos) para encontrar tus dominios.

## Limitaciones conocidas

- **Solo se indica un registro CNAME.** La pantalla no ofrece una alternativa para usar el dominio principal (`miorganizacion.org`); por eso recomendamos un subdominio.
- **`www.miorganizacion.org` y `miorganizacion.org` son dominios distintos:** cada uno se registra por separado y necesita su propio registro DNS.
- **Reactivar no repite la comprobación.** Si el dominio pasó a inactivo porque falló la comprobación, volver a encender el interruptor lo marca como activo, pero no vuelve a solicitar el certificado.

  > **Pendiente de confirmar:** cómo volver a lanzar la comprobación en ese caso. Mientras tanto, escríbenos a soporte.
- **Los dominios "Classic"** no aparecen en el selector de dominio de las landings actuales.
- **Mensajes de error técnicos.** Si falla la eliminación o la carga de la lista, el mensaje puede verse como un texto técnico. Recarga la pantalla y, si persiste, escríbenos a soporte.

## Preguntas frecuentes

**¿Afrus me vende el dominio?**
No. Lo compras con un proveedor (GoDaddy, Media Temple u otro) y lo configuras allí.

**¿Tengo que comprar un certificado de seguridad?**
No. Afrus lo gestiona automáticamente.

**¿Puedo usar mi dominio principal, sin subdominio?**
La pantalla lo acepta, pero solo indica un registro CNAME, que muchos proveedores no permiten en el dominio principal. Te recomendamos usar un subdominio.

> **Pendiente de confirmar:** qué registro usar para el dominio principal.

**¿Cuánto tarda en estar listo?**
Depende de cuánto tarde tu proveedor en propagar el DNS. Una vez agregado, Afrus comprueba el dominio durante unos 15 minutos.

**Mi dominio pasó a inactivo, ¿qué hago?**
Normalmente el registro CNAME no está bien o aún no se propagó. Revísalo con tu proveedor. Si el registro ya está bien y el dominio sigue inactivo, escríbenos a soporte: volver a encender el interruptor no repite la comprobación.

**¿Puedo usar mi dominio como página principal?**
Sí. En la landing, usa la ruta `/` con tu dominio.

---

> **[Volver al índice de la sección](./README.md)** · **[Volver al índice general](../README.md)**

*Última actualización: 2026-10-20*
