# 1. Lo básico

[← Contenido](./README.md)

---

## El calendario

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/calendar.png" alt="Calendario" width="280">

La cuadrícula del mes es la pantalla principal. Desliza a izquierda y derecha para cambiar de mes, y toca un día para abrir debajo su lista de eventos.

- Cada día muestra una barra de color por evento, y un indicador **+N** cuando hay más de los que caben.
- La lista del día va en este orden: tareas sin hora → tareas con hora → eventos de calendario → días festivos → eventos de calendarios externos.
- Toca la cabecera para saltar a cualquier fecha, o usa **Mover fecha** para elegirla directamente.

Lo densa que sea la cuadrícula — la altura de las filas, el tamaño del texto de los eventos, el texto en negrita, las barras de color, los nombres de los días festivos, el calendario lunar — se puede cambiar entero. Consulta [Personalización](./05-personalization.md).

---

## Tareas y eventos de calendario

La app tiene dos tipos de eventos, y la diferencia está en si la cosa se puede *completar*.

| | Tarea | Evento de calendario |
|---|---|---|
| Hora | Opcional | Obligatoria |
| Finalización | Sí — la marcas y listo | No |
| Sin hora | Se queda en **Lista de tareas actuales** hasta que la termines | No es posible |

Una **tarea sin hora** es para algo que necesitas hacer pronto pero que aún no has programado. Se queda arriba del todo en el calendario y en el widget Lista de tareas actuales hasta que la completas.

Puedes convertir en cualquier dirección y en cualquier momento — **Convertir en evento de calendario** / **Convertir en tarea**, desde el menú de más opciones del evento. Convertir una tarea en un evento de calendario necesita una hora.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/event-detail.png" alt="Detalle del evento" width="280">

Todos los eventos pueden llevar una **Ubicación** (con vista previa del mapa y apertura con un toque en tu app de mapas preferida), un enlace con **Vista previa de URL** y una **Nota**.

---

## Agregar eventos

Tres formas de entrar, según cuánto quieras escribir:

- **Agregado rápido** — el campo de entrada al final de la lista del día. Escribe un nombre, pulsa intro y ya tienes una tarea.
- **Detalle completo** — toca **+** para abrir el editor con hora, repetición, recordatorios, tipo de evento, ubicación, enlace y nota.
- **Entrada rápida con IA** — descríbelo en lenguaje natural y deja que la app construya el evento. Consulta [Entrada rápida con IA](./02-ai-input.md).

Una tarea solo necesita un nombre. Un evento de calendario necesita un nombre y una hora.

---

## Eventos repetidos

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/repeat-options.png" alt="Opciones de repetición" width="240">

En lugar de pedirte que montes una regla a base de desplegables, la app lee la fecha que elegiste y te ofrece opciones ya hechas para ella. Elige un jueves y la lista dirá literalmente **Cada jueves** y **El tercer jueves de cada mes**.

**Intervalos habituales**

- Todos los días
- Cada semana · Cada 2 semanas · Cada 3 semanas · Cada 4 semanas — el mismo día de la semana que el evento
- Cada mes — el mismo día de cada mes
- Cada año
- Cada año (calendario lunar) — para cumpleaños y aniversarios que se llevan por el calendario lunar

**Por posición dentro del mes**

- Cada día laborable — de lunes a viernes. Se ofrece cuando el evento empieza en un día laborable
- Todos los días de la última semana de cada mes
- El primer / segundo / tercer / cuarto / último *día de la semana* de cada mes — para cosas como "el último viernes del mes"

**Fin de la repetición**

Una vez que eliges una repetición, decide cómo termina: **Nunca**, **El** (una fecha concreta) o **Después de** un número de repeticiones.

Las tareas repetidas se comportan de forma distinta a los eventos de calendario repetidos:

- Una repetición sin completar sigue visible en el calendario de hoy aunque pase su hora — no salta a la siguiente en silencio.
- Al completarla, esa repetición se archiva en las tareas completadas y se crea la siguiente.
- **Omitir esta tarea** te lleva a la siguiente repetición sin marcarla como hecha.
- Cuando la repetición tiene una condición de fin y no hay una siguiente, la serie termina.

Cuando editas o eliminas una repetición de un evento repetido, eliges el alcance: **Solo esta vez**, **Desde este momento** o **Todos los eventos**.

En los eventos de un calendario externo conectado no se ofrece la opción lunar — ese calendario no tiene forma de expresarla.

---

## Tipos de evento y colores

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/event-type-list.png" alt="Tipos de evento" width="280">

Los tipos de evento son tus categorías, y llevan el color con el que el evento se muestra en el calendario. Crea todos los que quieras, cada uno con su propio color.

- Desactiva un tipo para ocultar del calendario todos los eventos de ese tipo — útil para silenciar un calendario de trabajo muy cargado sin desconectarlo.
- Al eliminar un tipo puedes conservar o eliminar los eventos asociados a él.
- Define un **Tipo de evento predeterminado** para que los eventos nuevos caigan en el sitio correcto sin tener que elegirlo cada vez.

Los días festivos y los calendarios externos conectados tienen sus propios tipos, así que también puedes ocultarlos por separado.

---

## Recordatorios

Pon todos los recordatorios que necesites en cada evento.

- **Eventos con hora** — en el momento del evento, o 1 / 5 / 10 / 15 / 30 minutos, 1 / 2 horas, 1 / 2 / 7 días antes.
- **Eventos de todo el día** — a las 9:00 a. m. o al mediodía de ese día, o a las 9:00 a. m. 1 / 2 / 7 días antes.
- **Personalizado** — elige el momento que quieras.

Los valores predeterminados para los eventos con hora y los de todo el día se definen por separado en Ajustes, así que los eventos nuevos ya vienen preparados. Los recordatorios necesitan el permiso de notificaciones; si está desactivado, la app te lleva a los Ajustes de iOS.

---

## Evento principal

Fija esa única cosa que no puedes perderte. El evento principal se queda arriba del todo en el calendario, mires la fecha que mires, y tiene su propio widget.

Las tareas y los eventos de calendario que no se repiten se pueden marcar como principales. Los eventos de calendario repetidos, no.

---

## Tareas pendientes

Las tareas cuya hora ya pasó sin haberlas completado se recogen en una sección **Tareas pendientes** arriba del calendario, para que algo que se te ha escapado no se pierda de vista en la semana pasada.

Las tareas sin hora y las futuras no cuentan como pendientes — simplemente aún no han vencido. Puedes ocultar la sección entera en Ajustes si prefieres no verla.

---

## Tareas completadas

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/done-todos.png" alt="Tareas completadas" width="280">

Todo lo que marcas se guarda, agrupado por cuándo lo terminaste — hoy, ayer, este mes, y después por mes y año.

- Deshaz una finalización para recuperar la tarea.
- Limpia en bloque: **Todas las tareas completadas**, o solo las **Más antiguas de** 1 mes / 3 meses / 6 meses / 1 año.

---

## Compartir

Comparte **un día, una semana o un mes** como texto o como tarjeta de imagen.

Antes de compartir puedes filtrar qué tipos de evento se incluyen y decidir si aparecen los nombres de los tipos, así que puedes enviarle tu semana a alguien sin enseñar todo lo que hay en ella.

---

[← Contenido](./README.md) · [Siguiente: Entrada rápida con IA →](./02-ai-input.md)
