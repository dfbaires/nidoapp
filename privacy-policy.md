# Política de Privacidad — Nido

**Última actualización:** marzo de 2026

Esta Política de Privacidad describe cómo la aplicación **Nido** ("la app", "nosotros") trata la información de sus usuarios. Nos comprometemos a proteger tu privacidad y a ser transparentes sobre el uso de tus datos.

---

## 1. Datos que se almacenan en tu dispositivo

Toda la información financiera que registrás en Nido —transacciones, cuentas, categorías, deudas, presupuestos, metas de ahorro— se almacena **exclusivamente en tu dispositivo**, en una base de datos local cifrada por el sistema operativo Android.

**Nido no tiene servidores propios donde se guarden tus datos financieros.** No se requiere crear una cuenta para usar la app. Si desinstalás la app, todos tus datos se eliminan de tu dispositivo.

---

## 2. Funciones que usan internet

### 2.1 Asistente de IA y entrada por lenguaje natural

Cuando usás las funciones de inteligencia artificial (asesor financiero, entrada por voz, registro por lenguaje natural), se envía texto al servidor de procesamiento de Nido (alojado en Cloudflare). Desde ahí, ese texto se reenvía a la API de Anthropic (Claude) para generar la respuesta.

**Qué se envía a Anthropic (para generar la respuesta):**
- El texto o transcripción de voz que vos ingresás
- El texto extraído de fotos de tickets (cuando usás la función de escaneo): la foto nunca sale del dispositivo, pero el texto reconocido en ella sí se envía para que la IA interprete el monto y la descripción
- Resúmenes numéricos de tus finanzas (totales del mes, sin detalle de cada transacción) cuando usás el asesor
- Nunca se envían fotos ni imágenes, solo el texto que contienen

**Qué registra el servidor intermediario (Cloudflare Worker):**
El servidor propio de Nido solo almacena un contador anónimo por dispositivo: cuántas veces usaste cada función de IA (voz, foto, chat) en el mes en curso. Este contador se usa exclusivamente para controlar el límite de uso mensual. **No se almacena el contenido de ninguna consulta.**

**Límites de uso mensual de las funciones de IA:**
Las funciones de inteligencia artificial tienen un límite de consultas por mes que se reinicia el primer día de cada mes:

| Función | Límite mensual |
|---|---|
| Entrada por voz | 500 consultas |
| Chat con asesor financiero | 150 consultas |
| Escaneo de tickets (OCR) | 100 consultas |
| Análisis e insights | 30 consultas |
| Plan financiero | 15 consultas |

Cuando se alcanza el límite mensual, la función queda deshabilitada hasta el siguiente ciclo. El contador se reinicia automáticamente el primer día de cada mes.

Podés consultar la política de privacidad de Anthropic en: [https://www.anthropic.com/privacy](https://www.anthropic.com/privacy)

### 2.2 Escaneo de tickets (OCR)

El reconocimiento de texto en fotos de tickets se realiza en dos pasos: primero, Google ML Kit extrae el texto **localmente en tu dispositivo** (la foto nunca sale del teléfono); luego, ese texto extraído se envía al servidor de IA (ver sección 2.1) para interpretar el monto y la descripción del gasto.

### 2.3 Analíticas de uso

Nido utiliza **Firebase Analytics** (Google) para recopilar datos anónimos sobre cómo se usa la app: qué pantallas se visitan, qué funciones se usan con más frecuencia, errores técnicos. Esta información no contiene datos financieros ni información personal identificable. Su único propósito es mejorar la app.

Podés consultar la política de privacidad de Google en: [https://policies.google.com/privacy](https://policies.google.com/privacy)

### 2.4 Publicidad

La versión gratuita de Nido muestra anuncios a través de **Google AdMob**. AdMob puede utilizar un identificador de publicidad de tu dispositivo para mostrar anuncios relevantes. Podés limitar la personalización de anuncios desde la configuración de tu dispositivo Android en: *Configuración → Privacidad → Anuncios*.

### 2.5 Pagos

La suscripción premium se gestiona íntegramente a través de **Google Play Billing**. Nido no tiene acceso a tu información de pago ni a los datos de tu tarjeta. Consultá las condiciones de Google Play en: [https://play.google.com/about/play-terms](https://play.google.com/about/play-terms)

---

## 3. Permisos que solicita la app

| Permiso | Para qué se usa |
|---|---|
| Cámara | Fotografiar tickets para OCR y adjuntar comprobantes a transacciones |
| Micrófono | Entrada por voz para registrar transacciones por lenguaje natural |
| Acceso a imágenes | Adjuntar imágenes existentes a transacciones |
| Notificaciones | Recordatorios de gastos y alertas de presupuesto |
| Alarmas exactas | Programar recordatorios a la hora indicada |
| Inicio del dispositivo | Restaurar recordatorios programados después de reiniciar el teléfono |

Ningún permiso se usa para recopilar datos sin tu conocimiento.

---

## 4. Datos de menores

Nido no está dirigida a menores de 13 años y no recopila intencionalmente información de menores. Si sos padre/madre o tutor y creés que tu hijo/a ha proporcionado información personal, contactanos para eliminarla.

---

## 5. Tus derechos

- **Acceso:** todos tus datos financieros están visibles dentro de la app en todo momento.
- **Eliminación:** desinstalando la app se eliminan todos los datos locales. Para solicitar la eliminación de datos de analíticas, podés contactarnos.
- **Portabilidad:** la app ofrece función de exportación/backup de tus datos.

---

## 6. Cambios en esta política

Si realizamos cambios importantes en esta política, lo notificaremos a través de una actualización de la app. La fecha de "última actualización" al inicio de este documento siempre refleja la versión vigente.

---

## 7. Contacto

Si tenés preguntas sobre esta política de privacidad, podés contactarnos en:

**Email:** info@nidoapp.com

---

*Nido es desarrollada de forma independiente. No somos responsables por las políticas de privacidad de terceros enlazados en este documento.*
