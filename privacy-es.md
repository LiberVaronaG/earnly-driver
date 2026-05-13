---
layout: default
title: Política de Privacidad — Earnly Driver
permalink: /privacidad/
---

# Política de Privacidad

**Última actualización:** 13 de mayo de 2026
**Fecha de entrada en vigor:** 13 de mayo de 2026

Earnly Driver ("la App") es desarrollada y operada por **Liber Varona** ("nosotros" o "el Desarrollador"). Esta Política de Privacidad describe cómo la App maneja tu información.

**Resumen:** Earnly Driver funciona completamente en tu iPhone. No tiene servidores, ni cuentas de usuario, ni analítica, ni publicidad. Tus datos de turnos y tu historial de ubicación nunca salen de tu dispositivo. No podemos ver, acceder ni recuperar tus datos.

---

## 1. Información que Recopilamos

Earnly Driver recopila únicamente la información que tú ingresas explícitamente al usar la App, y los datos de ubicación necesarios para rastrear un turno activo que tú hayas iniciado.

### 1.1 Información del turno que ingresas
- Hora de inicio y fin del bloque de turno
- Ganancias estimadas y reales (montos en dólares)
- Propinas
- Millaje (cuando no se rastrea por GPS)
- Notas personales que decidas agregar al turno
- Gastos del vehículo que registres

### 1.2 Datos de ubicación (solo durante un turno activo)
Cuando tocas **Iniciar Turno**, la App comienza a registrar la ubicación de tu dispositivo para calcular la distancia recorrida, la duración y la tarifa efectiva por hora. El rastreo de ubicación se detiene automáticamente cuando tocas **Finalizar Turno**.

- La ubicación se recopila **únicamente** mientras un turno está activo y tú lo has iniciado explícitamente.
- La ubicación se recopila en segundo plano para que la App pueda continuar rastreando cuando tu pantalla esté bloqueada o tengas otra app abierta durante tu turno.
- **No** transmitimos tu ubicación fuera del dispositivo bajo ninguna circunstancia.

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
- Los datos **no** se transmiten a ningún servidor operado por el Desarrollador ni por terceros.
- Los datos se incluyen en el respaldo estándar de tu iPhone (iCloud Backup o respaldo local cifrado) solo si tú tienes esos respaldos activados en los Ajustes de tu iPhone. Esos respaldos están controlados completamente por Apple y tu Apple ID; el Desarrollador no tiene acceso a ellos.

---

## 3. Cómo Usamos tus Datos

La App usa los datos que ingresas y los datos de ubicación que autorizas **únicamente** para los fines por los que tú la iniciaste:

- Calcular ganancias totales por turno, por semana y por mes
- Calcular tarifa efectiva por hora (ganancias ÷ tiempo de turno)
- Calcular costo por milla y ganancia neta
- Mostrar tu historial de turnos y tendencias de ganancias
- Exportar tus propios datos cuando tú decidas hacerlo (exportación CSV a la app Archivos o vía el menú Compartir)

No usamos tus datos para ningún otro propósito. No te perfilamos, no te puntuamos, no vendemos información sobre ti, ni compartimos tus datos con nadie.

---

## 4. Compartir Información

**No** vendemos, rentamos, intercambiamos ni compartimos tus datos personales con ningún tercero.

Existen dos situaciones en las que tus datos pueden salir del dispositivo, y ambas ocurren únicamente por tu instrucción explícita:

1. **Exportación CSV.** Puedes tocar **Exportar Datos** para generar un archivo CSV con tu historial de turnos. La exportación se entrega vía el menú Compartir de iOS, y tú eliges el destino (correo, Archivos, AirDrop, etc.). Hasta que tú inicies esta exportación y elijas un destino, tus datos permanecen en tu dispositivo.
2. **Respaldo estándar del iPhone.** Como se indica en la Sección 2, tus datos se incluyen en el respaldo estándar de tu iPhone si tienes los respaldos activados. Esto se rige por los términos de iCloud de Apple y los ajustes de tu dispositivo, no por nosotros.

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

Earnly Driver utiliza los frameworks propios de Apple (CoreLocation, MapKit, SwiftData, ActivityKit, UserNotifications). Las prácticas de privacidad de Apple para estos frameworks se describen en la política de privacidad propia de Apple en <https://www.apple.com/legal/privacy/>.

---

## 10. Cambios a esta Política

Si actualizamos esta Política de Privacidad en una versión futura de la App, la política actualizada se publicará en esta URL y la fecha de "Última actualización" en la parte superior cambiará. Los cambios importantes se destacarán en las notas de versión de la App.

---

## 11. Contacto

Si tienes preguntas sobre esta Política de Privacidad o sobre cómo la App maneja los datos, contacta al Desarrollador en:

**Correo:** megashoponline826@gmail.com

Normalmente respondemos en un plazo de 2 días hábiles.

---

*Earnly Driver es una app independiente y no está afiliada, respaldada ni patrocinada por Amazon.com, Inc. ni ninguna de sus subsidiarias. "Amazon Flex" es una marca registrada de Amazon.com, Inc.*
