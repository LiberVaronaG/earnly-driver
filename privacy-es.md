---
layout: default
title: Política de Privacidad — Earnly Driver
permalink: /privacidad/
---

# Política de Privacidad

**Última actualización:** 17 de mayo de 2026
**Fecha de entrada en vigor:** 17 de mayo de 2026

Earnly Driver ("la App") es desarrollada y operada por **Liber Varona** ("nosotros" o "el Desarrollador"). Esta Política de Privacidad describe cómo la App maneja tu información.

**Resumen:** Earnly Driver funciona completamente en tu iPhone. No tiene servidores, ni cuentas de usuario, ni analítica, ni publicidad. Tus datos de turnos y tu historial de ubicación permanecen en tu dispositivo de forma predeterminada. Lo único que puede salir de tu dispositivo lo hace solo cuando tú lo eliges explícitamente: al exportar un CSV, o al activar el ajuste opcional "Buscar direcciones del turno" (desactivado por defecto), que envía únicamente las coordenadas de inicio y fin de tu turno a Apple para obtener una dirección. No podemos ver, acceder ni recuperar tus datos, y el Desarrollador nunca los recibe.

---

## 1. Información que Recopilamos

Earnly Driver recopila únicamente la información que tú ingresas explícitamente al usar la App, y los datos de ubicación necesarios para rastrear un turno activo que tú hayas iniciado.

### 1.1 Información del turno que ingresas
- Hora de inicio y fin del bloque de turno
- Millaje (cuando se edita manualmente; de lo contrario, se calcula desde el GPS)
- Notas personales que decidas agregar al turno
- Motivo de cualquier edición que hagas a un turno guardado (para registro de auditoría)

### 1.2 Datos de ubicación (solo durante un turno activo)
Cuando tocas **Iniciar Turno**, la App comienza a registrar la ubicación de tu dispositivo para calcular la distancia recorrida, la duración y la tarifa efectiva por hora. El rastreo de ubicación se detiene automáticamente cuando tocas **Finalizar Turno**.

- La ubicación se recopila **únicamente** mientras un turno está activo y tú lo has iniciado explícitamente.
- La ubicación se recopila en segundo plano para que la App pueda continuar rastreando cuando tu pantalla esté bloqueada o tengas otra app abierta durante tu turno.
- **No** transmitimos tu ubicación fuera del dispositivo, con una única excepción opcional que tú controlas: si activas **Buscar direcciones del turno** en Ajustes (desactivado por defecto), solo se envían las coordenadas del inicio y fin de tu turno al servicio de geocodificación de Apple para obtener una dirección. No se envía nada más, y nunca se envía nada al Desarrollador. Consulta la Sección 4.

### 1.3 Información que NO recopilamos
- No recopilamos tu nombre, correo electrónico, número de teléfono, foto, ni ninguna otra información identificable.
- No requerimos que crees una cuenta ni inicies sesión.
- No recopilamos identificadores del dispositivo (IDFA, ID de publicidad, etc.).
- No usamos SDKs de analítica (Firebase Analytics, Mixpanel, Amplitude, Google Analytics, etc.).
- No usamos SDKs de reporte de errores (Crashlytics, Sentry, etc.).
- No usamos redes de publicidad.
- No te rastreamos a través de otras apps o sitios web.

---

## 2. Cómo se Almacenan tus Datos

Toda la información descrita en la Sección 1 se almacena **localmente** en tu iPhone usando el framework SwiftData de Apple. Los datos residen en el contenedor privado (sandbox) de la App, cifrados en reposo por iOS.

- Los datos **no** se sincronizan con iCloud a menos que una versión futura de la App ofrezca esa función y tú actives la opción explícitamente. La versión actual no sincroniza datos a ningún lugar.
- Salvo la búsqueda de direcciones opcional descrita en la Sección 4, los datos **no** se transmiten a ningún servidor. El Desarrollador no opera ningún servidor y nunca recibe tus datos bajo ninguna circunstancia.
- Los datos se incluyen en el respaldo estándar de tu iPhone (iCloud Backup o respaldo local cifrado) solo si tú tienes esos respaldos activados en los Ajustes de tu iPhone. Esos respaldos están controlados completamente por Apple y tu Apple ID; el Desarrollador no tiene acceso a ellos.

---

## 3. Cómo Usamos tus Datos

La App usa los datos que ingresas y los datos de ubicación que autorizas **únicamente** para los fines por los que tú la iniciaste:

- Calcular el total de millas por turno, semana y mes
- Estimar la deducción de millaje del IRS basada en la tarifa estándar
- Mostrar tu historial de turnos
- Exportar tus propios datos cuando tú decidas hacerlo (exportación CSV a la app Archivos o vía el menú Compartir)

No usamos tus datos para ningún otro propósito. No te perfilamos, no te puntuamos, no vendemos información sobre ti, ni compartimos tus datos con nadie.

---

## 4. Compartir Información

**No** vendemos, rentamos, intercambiamos ni compartimos tus datos personales con ningún tercero.

Existen tres situaciones en las que tus datos pueden salir del dispositivo, y cada una ocurre únicamente por tu instrucción explícita:

1. **Exportación CSV.** Puedes tocar **Exportar Datos** para generar un archivo CSV con tu historial de turnos. La exportación se entrega vía el menú Compartir de iOS, y tú eliges el destino (correo, Archivos, AirDrop, etc.). Hasta que tú inicies esta exportación y elijas un destino, tus datos permanecen en tu dispositivo.
2. **Respaldo estándar del iPhone.** Como se indica en la Sección 2, tus datos se incluyen en el respaldo estándar de tu iPhone si tienes los respaldos activados. Esto se rige por los términos de iCloud de Apple y los ajustes de tu dispositivo, no por nosotros.
3. **Búsqueda de direcciones opcional.** El ajuste **Buscar direcciones del turno** está **desactivado por defecto**. Si lo activas, cada vez que terminas un turno la app envía únicamente las coordenadas GPS de inicio y fin de ese turno al servicio de geocodificación de Apple para obtener una dirección legible que se muestra en el Detalle del Turno. Solo se envían esos dos pares de coordenadas; ningún otro dato del turno, y nada al Desarrollador. Puedes desactivarlo en cualquier momento en Ajustes, y nunca se ejecuta mientras está desactivado. Usa CLGeocoder de Apple y está sujeto a los términos de privacidad de Apple.

---

## 5. Tus Derechos y Controles

Como todos los datos permanecen en tu dispositivo, tienes control completo:

- **Eliminar un turno:** Abre cualquier turno en la pestaña de historial y toca eliminar.
- **Eliminar todos los datos:** Desinstala la App de tu iPhone. Todos los datos se eliminan junto con la App según las reglas de sandbox de iOS.
- **Revocar acceso a ubicación:** Ve a **Ajustes → Privacidad y Seguridad → Servicios de Ubicación → Earnly Driver** y cambia los permisos en cualquier momento. Ten en cuenta que desactivar la ubicación mientras un turno está activo impedirá que la App calcule la distancia de ese turno.
- **Exportar tus datos:** Usa la función **Exportar Datos** dentro de la App para recibir un archivo CSV de todo tu historial de turnos.

No podemos eliminar datos en tu nombre porque no tenemos acceso a ellos. No podemos recuperar datos en tu nombre por la misma razón. Si desinstalas la App sin exportar primero, los datos se pierden permanentemente (a menos que se restauren desde un respaldo del dispositivo).

---

## 6. Privacidad de Menores

Earnly Driver está dirigida a conductores de Amazon Flex, quienes deben tener al menos 21 años para conducir para Amazon Flex en los Estados Unidos. La App no está dirigida a menores de 13 años y no recopilamos a sabiendas ninguna información de nadie, incluyendo menores.

---

## 7. Permisos Solicitados

La App solicita los siguientes permisos de iOS:

| Permiso | Por qué | Cuándo |
|---|---|---|
| **Ubicación — Siempre** | Para rastrear distancia y ruta durante un turno, incluso cuando la pantalla está bloqueada u otra app está en primer plano | Solo mientras un turno está activo. El rastreo se detiene automáticamente al tocar Finalizar Turno. |
| **Notificaciones** | Para recordarte iniciar un bloque de turno a tiempo, y para mostrar el contador Live Activity en tu Pantalla Bloqueada durante un turno activo | Opcional. La App funciona sin notificaciones activadas. |
| **Movimiento y Estado Físico** *(si se solicita en una actualización futura)* | Para mejorar la precisión de distancia cuando la señal GPS es débil | No se solicita en la versión actual. |

Puedes otorgar, denegar o revocar cualquiera de estos permisos en cualquier momento en **Ajustes → Privacidad y Seguridad**.

---

## 8. Seguridad

Tus datos están protegidos por el modelo de seguridad estándar de iOS:
- Cifrados en reposo en tu dispositivo usando la protección de datos de Apple
- Almacenados en el sandbox privado de la App, inaccesibles para otras apps
- Protegidos por el código de acceso de tu iPhone, Face ID o Touch ID

Como no transmitimos ni almacenamos tus datos en ningún servidor, no existe riesgo de filtración del lado del servidor.

---

## 9. Servicios de Terceros

Earnly Driver no se integra con ningún SDK de terceros, plataforma de analítica, red de publicidad ni herramienta de redes sociales.

Earnly Driver utiliza los frameworks propios de Apple (CoreLocation, MapKit, SwiftData, ActivityKit, UserNotifications, y CLGeocoder para la función opcional de geocoding inverso). Las prácticas de privacidad de Apple para estos frameworks se describen en la política de privacidad propia de Apple en <https://www.apple.com/legal/privacy/>. Cuando utilizas la función opcional de geocoding inverso, las coordenadas de tu turno se envían al servicio de geocodificación de Apple y están sujetas a las prácticas de privacidad de Apple, no a las del Desarrollador.

---

## 10. Cambios a esta Política

Si actualizamos esta Política de Privacidad en una versión futura de la App, la política actualizada se publicará en esta URL y la fecha de "Última actualización" en la parte superior cambiará. Los cambios importantes se destacarán en las notas de versión de la App.

---

## 11. Contacto

Si tienes preguntas sobre esta Política de Privacidad o sobre cómo la App maneja los datos, contacta al Desarrollador en:

**Correo:** earnlydriver@gmail.com

Normalmente respondemos en un plazo de 2 días hábiles.

---

*Earnly Driver es una app independiente y no está afiliada, respaldada ni patrocinada por Amazon.com, Inc. ni ninguna de sus subsidiarias. "Amazon Flex" es una marca registrada de Amazon.com, Inc.*
