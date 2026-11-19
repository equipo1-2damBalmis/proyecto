---
asignatura: PI2
proyecto: Comunify
sprint: 1 - Prototipado UI/UX
tarea: "1.3 Prompt pantalla Chats (MÓVIL)"
issue: https://github.com/equipo1-2damBalmis/hada-task-tracker/issues/26
autor: Gor Ghazaryan
---

# 1.3 · Prompt pantalla Chats (app móvil)

Prompt para generar el prototipo navegable de la pantalla de **Chats** de la app móvil de Comunify (vista de vecino) en Figma/Penpot.
Basado en el caso de uso **Sistema de Chats** de `docs/PROYECTO.md` y en el boceto del equipo (Inicio · Chats · Historial de gastos).
Sin estilos concretos: solo funcionalidad, contenido y orden. Los colores y la tipografía se unificarán con el resto de pantallas.

---

## Prompt

```text
Diseña el prototipo navegable de la sección "Chats" de una app móvil Android llamada Comunify,
una app para gestionar comunidades de propietarios (gastos, avisos y comunicación entre vecinos).
El usuario es un vecino (beneficiario). No apliques un estilo visual concreto: usa una estética
neutra y limpia, centrada en la estructura, el contenido y la navegación. Formato de pantalla móvil vertical.

Genera 2 pantallas:

PANTALLA 1 – LISTA DE CHATS
1. Cabecera con el título "Chats".
2. Lista de 4 canales FIJOS, en este orden exacto (el usuario no puede crear ni borrar canales):
   1. Presidente: conversación privada del vecino con el presidente de la comunidad.
   2. Bloque: chat de los vecinos de su bloque/portal.
   3. Comunidad: chat de todos los vecinos de la comunidad.
   4. Avisos: canal de comunicados oficiales; solo publica el administrador.
3. Cada fila muestra: un icono o avatar circular a la izquierda, el nombre del canal,
   una línea con la vista previa del último mensaje (con el nombre de quien lo escribió),
   la hora del último mensaje y un contador de mensajes no leídos si los hay.
   El canal "Avisos" lleva una pequeña marca de "Oficial".
4. Barra de navegación inferior con 3 pestañas, en este orden: Inicio (icono de casa),
   Chats (icono de bocadillo de chat, marcada como activa) e Historial de gastos (icono de documento).

PANTALLA 2 – CONVERSACIÓN (se abre al pulsar un canal)
1. Cabecera con flecha para volver atrás, el nombre del canal y debajo el número de participantes
   (en "Presidente" muestra el nombre del presidente en lugar del número).
2. Lista de mensajes separada por fechas ("Ayer", "Hoy").
   - Mensajes propios alineados a la derecha, con la hora.
   - Mensajes de otros vecinos alineados a la izquierda, con nombre y vivienda (por ejemplo "Laura · 3ºB") y la hora.
3. Barra inferior para escribir: campo de texto "Escribe un mensaje..." y botón de enviar.
4. Variante del canal "Avisos": no hay campo de texto; en su lugar aparece el texto
   "Solo el administrador puede publicar en este canal". Cada aviso se muestra como una tarjeta
   con título, fecha y texto del comunicado.

NAVEGACIÓN (prototipo navegable)
- Pulsar cualquier canal de la lista abre su conversación (Pantalla 2).
- La flecha atrás de la conversación vuelve a la lista de chats.
- Las pestañas de la barra inferior llevan a Inicio, Chats e Historial de gastos.
- Desde la tarjeta "Avisos" de la pantalla de Inicio se entra directamente en la conversación del canal "Avisos".

DATOS DE EJEMPLO (en español, realistas)
- Presidente: "Antonio (Presidente): El técnico del ascensor viene el lunes a las 10:00."
- Bloque: "Laura · 3ºB: ¿Alguien más tiene problemas con la luz del portal?"
- Comunidad: "Javier · 1ºA: Recordad que el jueves a las 19:00 hay reunión en el local."
- Avisos: "Derrama aprobada para la reparación de la fachada" y "Corte de agua el martes de 9:00 a 13:00".
- Algún mensaje sobre ruidos en el 2ºA y la avería del ascensor.

NO INCLUIR: adjuntar fotos o archivos, crear chats privados entre vecinos, ni votaciones dentro del chat.
```

---

## Decisiones

- Orden de canales, 4 canales fijos y barra inferior de 3 pestañas: según el boceto del equipo.
- Pantalla de conversación: no está en el boceto; se añade para que el prototipo sea navegable dentro de los chats.
- Fuera del prompt: adjuntos (son del módulo de incidencias), chats privados entre vecinos (el proyecto habla de canales fijos) y votaciones (tienen su propio módulo).
