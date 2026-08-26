# 2. Entrada rápida con IA

[← Contenido](./README.md)

---

Describe en lenguaje natural lo que quieres y la app lo construye por ti — "comida con Sara el viernes a mediodía", "pasa el dentista al martes que viene", "marca la colada como hecha". Sin formularios y sin selectores de fecha.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/es/ai-input.png" alt="Entrada rápida con IA" width="280">

La entrada rápida con IA necesita una cuenta con la sesión iniciada. Todo lo demás en la app funciona sin ella.

---

## Lo que puede hacer

- Crear tareas y eventos de calendario, deduciendo la hora, la repetición y el tipo de evento de lo que dijiste
- Cambiar un evento existente — moverlo, renombrarlo, cambiarle la hora
- Completar una tarea, o deshacer una finalización
- Eliminar un evento
- Ocuparse de varias cosas en una sola solicitud ("añade gimnasio el lunes, el miércoles y el viernes a las 7")

---

## Formas de enviar una solicitud

### En la app

Toca el botón de IA en la pantalla del calendario. La hoja de entrada se abre con dos modos entre los que puedes cambiar cuando quieras:

- **Voz** — habla y mira cómo aparece la transcripción en vivo. Necesita el permiso de micrófono y de reconocimiento de voz; si se deniega alguno, la app te ofrece abrir los Ajustes de iOS o **Escribir en su lugar**.
- **Teclado** — escríbelo. Va bien cuando estás en un sitio donde no puedes hablar.

### Desde una imagen

**Leer desde una imagen** convierte una foto en eventos. Elige **Hacer una foto** o **Elegir de la biblioteca**; la app lee el texto que hay en ella — un horario de clases, un cartel de un evento, una captura de un mensaje — y te muestra lo que ha encontrado para que corrijas lo que haya salido mal antes de enviarlo.

Puedes añadir unas **Instrucciones adicionales (opcional)** para orientar el resultado, del tipo "añade esto como tareas". Si en la imagen no hay texto legible, la app te lo dice en vez de enviar una solicitud vacía.

### Siri

Di **"Añadir con IA en To-do Calendar"** — o "Añadir un evento de calendario en To-do Calendar" / "Añadir una tarea en To-do Calendar". Siri te pregunta qué quieres añadir, y la solicitud se ejecuta **en segundo plano sin abrir la app**. Siri responde "Entendido. Te avisaré cuando esté listo." y recibes una notificación cuando el resultado está preparado.

### Botón de Acción

Asigna el botón de Acción al atajo **Añadir con IA**. Una pulsación, dices lo que quieres añadir y se envía — la app no tiene ni que abrirse.

### Widget y Centro de Control

- **Widget Añadir con IA** — un widget para la pantalla de inicio o la pantalla bloqueada que abre la pantalla de entrada de IA con un solo toque.
- **Centro de Control** (iOS 18 y posteriores) — añade el mismo control al Centro de Control para tener una entrada deslizando hacia abajo.

### Hoja de compartir

Comparte **texto o una imagen desde cualquier otra app** directamente con la IA de To-do Calendar. Estás leyendo un mensaje con los detalles de una quedada, o mirando un cartel en Fotos — pulsa compartir, elige To-do Calendar, añade una instrucción si quieres y envía.

La solicitud de la hoja de compartir también se ejecuta en segundo plano. Recibes una confirmación de que se envió, y el resultado lo consultas en la app.

---

## Cómo se procesa una solicitud

1. **Enviada** — tu solicitud sale. Si vino de Siri, del botón de Acción o de la hoja de compartir, no hace falta que dejes la app abierta.
2. **Procesando** — la app muestra el progreso. Puedes **Detener** una solicitud mientras se ejecuta, aunque al detenerla se descarta el trabajo en curso y no se puede reanudar.
3. **Se necesita confirmación** — si la solicitud va a cambiar algo importante, la app te pide que lo apruebes primero y te enseña exactamente lo que va a hacer. Hay una cuenta atrás; si se acaba, solo tienes que pedirlo otra vez.
4. **Comando completado** — el resultado aparece en tu calendario al momento, con un resumen de lo que cambió.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/es/ai-result.png" alt="Resultado de la IA" width="280">

Solo se ejecuta una solicitud a la vez. Si envías otra mientras una sigue esperando tu aprobación, la app te pide que revises primero la que está pendiente.

---

## Créditos

Cada solicitud de IA gasta **créditos**, y tus créditos se recargan cada día. Los que te quedan se muestran arriba en la pantalla de entrada de IA, así que lo sabes antes de enviar.

Cuando se te acaban, la entrada rápida con IA espera a la recarga del día siguiente. Todo lo demás en la app sigue funcionando.

---

## Permisos que puede pedir

| Permiso | Para qué se usa |
|---|---|
| Micrófono + reconocimiento de voz | Entrada por voz |
| Cámara | Hacer una foto para **Leer desde una imagen** |
| Fototeca | Elegir una imagen ya existente |
| Notificaciones | Avisarte del resultado de una solicitud en segundo plano |

Cada uno se pide solo la primera vez que usas la función que lo necesita, y la app sigue funcionando sin él — la entrada por voz recurre al teclado, y la de imagen a escribir.

---

[← Contenido](./README.md) · [Siguiente: Widgets y pantalla bloqueada →](./03-widgets.md)
