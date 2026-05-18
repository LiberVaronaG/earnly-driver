---
layout: default
title: Política de Privacidad — Earnly Driver
permalink: /privacidad/
---

# Política de Privacidad

**Última actualización:** 18 de mayo de 2026
**Fecha de entrada en vigor:** 18 de mayo de 2026

Earnly Driver ("la App") es desarrollada y operada por **Liber Varona** ("nosotros" o "el Desarrollador"). Esta Política de Privacidad describe cómo la App maneja tu información.

**Resumen:** Earnly Driver funciona completamente en tu iPhone. No tiene servidores, ni cuentas de usuario, ni analítica, ni publicidad. Tus datos de turnos, tus viajes personales y tu historial de ubicación permanecen en tu dispositivo. Lo único que puede salir de tu dispositivo lo hace solo cuando tú lo eliges explícitamente: al exportar un CSV o un PDF, o al activar el ajuste opcional "Buscar direcciones" (desactivado por defecto), que envía únicamente las coordenadas de inicio y fin de un turno o viaje personal a Apple para obtener una dirección. No podemos ver, acceder ni recuperar tus datos, y el Desarrollador nunca los recibe.

---

## 1. Información que Recopilamos

Earnly Driver recopila únicamente la información que tú proporcionas explícitamente al usar la App, los datos de ubicación necesarios para rastrear un turno de trabajo que tú hayas iniciado y —solo si tú lo activas— los datos de ubicación y movimiento necesarios para detectar tus viajes personales.

### 1.1 Información del turno que ingresas o generas
- Horas de inicio y fin de los turnos de trabajo
- La plataforma para la que manejaste (por ejemplo Amazon Flex, Uber, Lyft, DoorDash, Instacart, Spark Driver, GrubHub), incluyendo más de una plataforma cuando combinas apps en un mismo viaje
- Millaje (calculado por GPS durante un turno rastreado, o ingresado y editado por ti)
- Ganancias que decides ingresar: pago bruto, propinas y el pago de cualquier plataforma adicional que hayas combinado
- Notas personales que decides añadir a un turno
- El motivo de cualquier edición que hagas a un turno guardado (se conserva para tu propio registro de auditoría)

### 1.2 Información de vehículo, gastos e impuestos que ingresas
- Marca, modelo, año y tipo de combustible del vehículo
- Precio del combustible por galón o por kWh, si decides ingresarlo (se usa para estimar el costo de combustible)
- Gastos operativos del vehículo que registras — por ejemplo gasolina, cambios de aceite, reparaciones, seguro, registro — incluyendo el monto, la fecha, la categoría y el porcentaje de uso de negocio que asignas a cada uno
- Tu meta de ingreso neto por hora, si decides configurarla
- Tu estado de EE. UU., si decides configurarlo
- "Estaciones" guardadas — lugares que tú nombras y guardas (por ejemplo un almacén de reparto), cada uno almacenado como un nombre, una coordenada, un radio, una dirección resuelta opcional, una ventana opcional de horas de silencio, y cualquier nota de texto libre que añadas (como un código de puerta o instrucciones de estacionamiento)

### 1.3 Datos de ubicación — turnos de trabajo
Cuando tocas **Iniciar Turno**, la App comienza a registrar la ubicación de tu dispositivo para calcular la distancia recorrida, la ruta, la duración y la tarifa efectiva por hora. El rastreo de ubicación se detiene automáticamente cuando tocas **Finalizar Turno**.

- La ubicación se recopila **únicamente** mientras un turno de trabajo está activo y tú lo has iniciado explícitamente.
- La ubicación se recopila en segundo plano para que la App pueda seguir rastreando cuando tu pantalla está bloqueada u otra app está abierta durante tu turno.
- Tu ubicación **no** se transmite fuera del dispositivo, excepto por la búsqueda de direcciones opcional descrita en la Sección 4.

### 1.4 Datos de ubicación y movimiento — viajes personales (opcional, desactivado por defecto)
Earnly Driver incluye una función opcional, **Trackear millas personales automáticamente**, ubicada en Ajustes. Está **desactivada por defecto**. Tú mismo debes activarla.

Cuando —y solo cuando— la activas:
- La App usa el framework **Core Motion** de Apple para detectar cuándo estás manejando en un vehículo. Los datos de movimiento se procesan completamente en tu dispositivo y nunca se transmiten a ningún lado.
- Cuando se detecta un viaje personal (no de trabajo), la App registra su ruta, distancia y horas como un "viaje personal", almacenado localmente en tu dispositivo.
- Los viajes personales se mantienen completamente separados de los datos de trabajo. Nunca cuentan en tus ganancias, en tus "millas de hoy", en tus totales mensuales ni en tu exportación del IRS.
- El rastreo de viajes personales se desactiva automáticamente siempre que hay un turno de trabajo activo. Las millas de trabajo siempre las inicias tú, a mano — la App nunca convierte un viaje detectado en un turno de trabajo automáticamente.
- Puedes desactivar esta función en cualquier momento en Ajustes. Cuando está desactivada, no se recopilan datos de movimiento ni de ubicación en segundo plano para viajes personales.

### 1.5 Información que NO recopilamos
- No recopilamos tu nombre, correo electrónico, número de teléfono, foto, ni ninguna otra información de identificación.
- No requerimos que crees una cuenta ni que inicies sesión.
- No recopilamos identificadores de dispositivo (IDFA, ID de publicidad, etc.).
- No usamos SDKs de analítica (Firebase Analytics, Mixpanel, Amplitude, Google Analytics, etc.).
- No usamos SDKs de reporte de fallos (Crashlytics, Sentry, etc.).
- No usamos redes de publicidad.
- No te rastreamos a través de otras apps o sitios web.

---

## 2. Cómo se Almacenan tus Datos

Todos los datos descritos en la Sección 1 se almacenan **localmente** en tu iPhone usando el framework SwiftData de Apple. Los datos residen en el contenedor sandbox privado de la App, cifrados en reposo por iOS.

- Los datos **no** se sincronizan con iCloud a menos que una versión futura de la App ofrezca esa función y tú la actives explícitamente. La versión actual no sincroniza ningún dato en ningún lado.
- Excepto por la búsqueda de direcciones opcional descrita en la Sección 4, los datos **no** se transmiten a ningún servidor. El Desarrollador no opera ningún servidor y nunca recibe tus datos bajo ninguna circunstancia.
- Los datos se incluyen en la copia de seguridad estándar de tu iPhone (copia de iCloud o copia local cifrada) solo si tienes esas copias activadas en los Ajustes de tu iPhone. Esas copias las controlan completamente Apple y tu Apple ID; el Desarrollador no tiene acceso a ellas.

---

## 3. Cómo Usamos tus Datos

La App usa los datos que ingresas y los datos de ubicación que autorizas **únicamente** para los fines por los que instalaste la App:

- Calcular el total de millas recorridas por turno, semana y mes
- Calcular tus ganancias reales por hora, costo por milla y ganancia neta después de combustible
- Estimar tu deducción de millaje estándar del IRS
- Comparar el método de millaje estándar con los gastos operativos reales que registras
- Estimar el impuesto de trabajo por cuenta propia que debes apartar
- Mostrar tu historial de turnos y tu historial de viajes personales
- Ayudarte a decidir si un bloque de reparto u oferta vale la pena aceptar
- Exportar tus propios datos cuando tú lo decides (exportación CSV o PDF a la app Archivos o mediante la Hoja para Compartir de iOS)

No usamos tus datos para ningún otro propósito. No te perfilamos, no te puntuamos, no vendemos información sobre ti, ni compartimos tus datos con nadie.

---

## 4. Compartir Información

**No** vendemos, alquilamos, intercambiamos ni compartimos tus datos personales con ningún tercero.

Hay tres situaciones en las que tus datos pueden salir de tu dispositivo, y cada una ocurre solo por tu indicación explícita:

1. **Exportación CSV y PDF.** Puedes exportar tu historial de turnos como archivo CSV, o un resumen del año fiscal como PDF. La exportación se entrega mediante la Hoja para Compartir de iOS, y tú eliges a dónde va (correo, Archivos, AirDrop, etc.). Hasta que inicies una exportación y elijas un destino, tus datos permanecen en tu dispositivo.
2. **Copia de seguridad estándar del iPhone.** Como se indica en la Sección 2, tus datos se incluyen en la copia de seguridad estándar de tu iPhone si tienes las copias activadas. Esto se rige por los términos de iCloud de Apple y los ajustes de tu dispositivo, no por nosotros.
3. **Búsqueda de direcciones opcional.** El ajuste **Buscar direcciones** está **desactivado por defecto**. Si lo activas, entonces cada vez que termina un turno de trabajo o un viaje personal, la App envía únicamente las coordenadas GPS de inicio y fin de ese turno o viaje al servicio de geocodificación de Apple para obtener una dirección legible que se muestra en la pantalla de detalle. Solo se envían esos pares de coordenadas; ningún otro dato de turno, viaje, ganancias o vehículo, y nada al Desarrollador. Puedes desactivarlo en cualquier momento en Ajustes, y nunca se ejecuta mientras está desactivado. Esto usa CLGeocoder de Apple y está sujeto a los términos de privacidad de Apple.

---

## 5. Tus Derechos y Controles

Como todos los datos permanecen en tu dispositivo, tienes control completo:

- **Eliminar un turno o viaje personal:** Ábrelo en la pestaña Historial y elimínalo. Los elementos eliminados van a la Papelera y pueden restaurarse durante 30 días, tras lo cual se eliminan permanentemente.
- **Eliminar todos los datos:** Elimina la App de tu iPhone. Todos los datos se borran con la App según las reglas del sandbox de iOS.
- **Revocar el acceso a la ubicación:** Ve a **Ajustes → Privacidad y Seguridad → Localización → Earnly Driver** y cambia los permisos en cualquier momento. Ten en cuenta que desactivar la ubicación mientras un turno está activo impedirá que la App calcule la distancia de ese turno.
- **Revocar el acceso al movimiento:** Ve a **Ajustes → Privacidad y Seguridad → Movimiento y Forma Física** y cambia el permiso en cualquier momento. También puedes desactivar **Trackear millas personales automáticamente** directamente en los Ajustes de la App.
- **Exportar tus datos:** Usa la función **Exportar** en la App para recibir un CSV o un PDF de tu historial.

No podemos eliminar datos en tu nombre porque no tenemos acceso a ellos. No podemos recuperar datos en tu nombre por la misma razón. Si desinstalas la App sin exportar primero, los datos se pierden permanentemente (a menos que se restauren desde una copia de seguridad del dispositivo).

---

## 6. Privacidad de los Menores

Earnly Driver es una herramienta para conductores de apps de reparto y transporte, quienes deben ser adultos para manejar con las plataformas de reparto y transporte que la App admite. La App no está dirigida a menores de 13 años, y no recopilamos conscientemente información de nadie, incluidos menores.

---

## 7. Permisos Solicitados

La App solicita los siguientes permisos de iOS:

| Permiso | Por qué | Cuándo |
|---|---|---|
| **Ubicación — Al usar la app** | Para rastrear la distancia y la ruta durante un turno de trabajo | Solo mientras un turno está activo |
| **Ubicación — Siempre** | Para seguir rastreando un turno cuando la pantalla está bloqueada u otra app está abierta, y —solo si activas Trackear millas personales automáticamente— para detectar viajes personales en segundo plano | Durante un turno activo; para viajes personales solo si lo activas |
| **Movimiento y Forma Física** | Para detectar cuándo estás manejando, y así registrar viajes personales automáticamente | Solo si activas Trackear millas personales automáticamente en Ajustes (desactivado por defecto) |
| **Notificaciones** | Para recordarte si olvidas finalizar un turno, mostrar el contador de Live Activity, avisarte al llegar a una estación guardada, y avisarte cuando el rastreo de viajes personales está activo | Opcional. La App funciona sin notificaciones activadas |

Puedes conceder, denegar o revocar cualquiera de estos permisos en cualquier momento en **Ajustes → Privacidad y Seguridad**.

---

## 8. Seguridad

Tus datos están protegidos por el modelo de seguridad estándar de iOS:
- Cifrados en reposo en tu dispositivo usando la protección de datos de Apple
- Almacenados en el sandbox privado de la App, inaccesible para otras apps
- Protegidos por el código de tu iPhone, Face ID o Touch ID

Como no transmitimos ni almacenamos tus datos en ningún servidor, no hay riesgo de filtración del lado del servidor.

---

## 9. Servicios de Terceros

Earnly Driver no se integra con ningún SDK de terceros, plataforma de analítica, red de publicidad ni herramienta de redes sociales.

Earnly Driver usa los propios frameworks de Apple (CoreLocation, CoreMotion, MapKit, SwiftData, ActivityKit, WidgetKit, App Intents, UserNotifications, y CLGeocoder para la función opcional de geocodificación inversa). Las prácticas de privacidad de Apple para estos frameworks se describen en la propia política de privacidad de Apple en <https://www.apple.com/legal/privacy/>. Cuando usas la función opcional de geocodificación inversa, las coordenadas de tu turno o viaje se envían al servicio de geocodificación de Apple y están sujetas a las prácticas de privacidad de Apple, no a las del Desarrollador.

Si decides usar los atajos de Siri de la App, tus comandos de voz son procesados por Siri de Apple y están sujetos a las prácticas de privacidad de Apple. La App en sí solo recibe la acción resultante de "iniciar turno" o "finalizar turno".

---

## 10. Cambios a Esta Política

Si actualizamos esta Política de Privacidad en una versión futura de la App, la política actualizada se publicará en esta URL y la fecha de "Última actualización" en la parte superior cambiará. Los cambios materiales se destacarán en las notas de la versión de la App.

---

## 11. Contacto

Si tienes preguntas sobre esta Política de Privacidad o sobre cómo la App maneja los datos, contacta al Desarrollador en:

**Correo:** earnlydriver@gmail.com

Normalmente respondemos dentro de 2 días hábiles.

---

*Earnly Driver es una app independiente y no está afiliada, respaldada ni patrocinada por Amazon.com, Inc., Uber Technologies, Inc., Lyft, Inc., DoorDash, Inc., Maplebear Inc. (Instacart), Walmart Inc. (Spark Driver), ni Just Eat Takeaway.com (GrubHub), ni ninguna de sus subsidiarias. Todos los nombres de plataformas y marcas registradas son propiedad de sus respectivos dueños.*
