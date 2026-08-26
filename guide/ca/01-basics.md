# 1. Els conceptes bàsics

[← Índex](./README.md)

---

## El calendari

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ca/calendar.png" alt="Calendari" width="280">

El calendari del mes és la pantalla principal. Llisqueu cap a l'esquerra i cap a la dreta per canviar de mes, i toqueu un dia per obrir-ne la llista d'esdeveniments a sota.

- Cada dia mostra una barra de color per esdeveniment, més un indicador **+N** quan el dia té més esdeveniments dels que la fila pot mostrar.
- La llista del dia va ordenada: tasques sense hora → tasques amb hora → cites → festius → esdeveniments de calendaris externs.
- Toqueu la capçalera per saltar a qualsevol data, o feu servir **Mou la data** per triar-ne una directament.

Sou vosaltres qui decidiu quant mostra cada dia: la quantitat de detall per esdeveniment, la mida del text, els colors, els noms dels festius i el calendari lunar. [Personalització](./05-personalization.md) repassa cada opció pel seu nom.

---

## Tasques i cites

L'aplicació té dos tipus d'esdeveniment, i la diferència és si es tracta d'una cosa que marqueu quan està feta.

| | Tasca | Cita |
|---|---|---|
| Hora | Opcional | Obligatòria |
| Completar | Sí, la podeu marcar | No |
| Sense hora | Es queda a la **Llista de tasques actuals** fins que l'acabeu | No és possible |

Una **tasca sense hora** serveix per a allò que heu de fer aviat però encara no heu programat. Es queda a la part de dalt del calendari i al widget Llista de tasques actuals fins que està feta.

Podeu convertir-les en tots dos sentits quan vulgueu: **Converteix en cita** / **Converteix en tasca** des del menú de més opcions de l'esdeveniment. Només convertir una tasca en cita demana una hora.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ca/event-detail.png" alt="Detall de l'esdeveniment" width="280">

Tot esdeveniment pot portar una **Ubicació**, un **Enllaç** i una **Nota**. La ubicació mostra una previsualització al mapa i s'obre amb un sol toc a la vostra aplicació de mapes preferida; l'enllaç té la seva pròpia previsualització.

---

## Afegir esdeveniments

Hi ha tres maneres d'afegir un esdeveniment, segons quant vulgueu escriure:

- **Afegir ràpid** — el camp d'entrada a la part inferior de la llista del dia. Escriviu un nom, premeu Retorn i la tasca es crea.
- **Detall complet** — toqueu **+** per obrir l'editor amb hora, repetició, recordatoris, tipus d'esdeveniment, ubicació, enllaç i nota.
- **Entrada ràpida amb IA** — descriviu-ho en llenguatge natural i deixeu que l'aplicació munti l'esdeveniment. Consulteu [Entrada ràpida amb IA](./02-ai-input.md).

Una tasca només necessita un nom. Una cita necessita un nom i una hora.

---

## Esdeveniments repetitius

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ca/repeat-options.png" alt="Opcions de repetició" width="240">

En comptes de fer-vos muntar una regla de repetició a base de desplegables, l'aplicació llegeix la data que heu triat i us ofereix opcions ja fetes. Trieu un dijous i la llista us ofereix **Cada dijous** i **El tercer dijous de cada mes**.

**Intervals habituals**

- Cada dia
- Cada setmana · Cada 2 setmanes · Cada 3 setmanes · Cada 4 setmanes — el mateix dia de la setmana que l'esdeveniment
- Cada mes — el mateix dia de cada mes
- Cada any
- Cada any (calendari lunar) — per a aniversaris i commemoracions que se celebren pel calendari lunar

**Per posició dins del mes**

- Cada dia laborable — de dilluns a divendres. S'ofereix quan l'esdeveniment comença en un dia laborable
- Tots els dies de l'última setmana de cada mes
- El primer / segon / tercer / quart / últim **dijous** de cada mes — el dia de la setmana es completa a partir de la data que heu triat, de manera que un esdeveniment de divendres ofereix **L'últim divendres de cada mes**

**Final de la repetició**

Un cop trieu una repetició, decidiu quan s'atura: **Mai** perquè continuï indefinidament, **El** per fixar la data en què acaba, o **Després de** un nombre determinat de **vegades**.

Les tasques repetitives es comporten de manera diferent de les cites repetitives:

- Una repetició sense completar es continua veient al calendari d'avui fins i tot quan ja ha passat l'hora: no passa tota sola a la repetició següent.
- Completar-la arxiva aquella repetició a les tasques completades i en crea la següent.
- **Omet aquesta tasca** us porta a la repetició següent sense marcar-la com a feta.
- Quan la repetició té una condició de final i no hi ha repetició següent, la sèrie s'acaba.

Quan editeu o suprimiu una repetició d'un esdeveniment repetitiu, trieu l'abast: **Només aquesta vegada**, **A partir d'ara** o **Tots els esdeveniments**.

Per als esdeveniments d'un calendari extern connectat, l'opció lunar no s'ofereix: els calendaris externs no tenen on desar una regla de repetició lunar.

---

## Tipus d'esdeveniment i colors

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ca/event-type-list.png" alt="Tipus d'esdeveniments" width="280">

Els tipus d'esdeveniment són les vostres categories, i porten el color amb què un esdeveniment es mostra al calendari. Creeu-ne tants com vulgueu, cadascun amb el seu color.

- Desactiveu un tipus per amagar del calendari tots els esdeveniments d'aquell tipus: va bé per silenciar un calendari de feina atapeït sense desconnectar-lo.
- En suprimir un tipus podeu conservar o eliminar els esdeveniments que hi estan associats.
- Establiu un **Tipus d'esdeveniment per defecte** perquè els esdeveniments nous vagin al lloc adequat sense haver-lo de triar cada vegada.

Els festius i els calendaris externs connectats tenen els seus propis tipus, així que també els podeu amagar per separat.

---

## Recordatoris

Poseu tants recordatoris per esdeveniment com necessiteu.

- **Esdeveniments amb hora** — a l'hora de l'esdeveniment, o 1 / 5 / 10 / 15 / 30 minuts, 1 / 2 hores, 1 / 2 / 7 dies abans.
- **Esdeveniments de tot el dia** — a les 9 del matí o al migdia d'aquell dia, o a les 9 del matí 1 / 2 / 7 dies abans.
- **Personalitzat** — trieu el moment que vulgueu.

Els valors per defecte dels esdeveniments amb hora i dels de tot el dia s'estableixen per separat a la configuració, de manera que els esdeveniments nous ja porten els recordatoris posats. Els recordatoris necessiten el permís de notificacions; si el teniu desactivat, l'aplicació us porta a la configuració d'iOS.

---

## Esdeveniment principal

Fixeu l'única cosa que no us podeu perdre. L'esdeveniment principal es queda a la part de dalt del calendari sigui quina sigui la data que estigueu mirant, i té el seu propi widget.

Les tasques i les cites no repetitives es poden marcar com a principals. Les cites repetitives, no.

---

## Tasques pendents

Les tasques que ja han passat d'hora sense completar-se es recullen en una secció **Tasques pendents** a la part de dalt del calendari, de manera que una tasca oblidada no queda enterrada en una data ja passada.

Les tasques sense hora i les futures no compten com a pendents: simplement encara no han vençut. Podeu amagar la secció del tot a la configuració si preferiu no veure-la.

---

## Tasques completades

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ca/done-todos.png" alt="Tasques completades" width="280">

Tot el que marqueu es conserva, agrupat pel moment en què les vau acabar: avui, ahir, aquest mes i, després, per mes i any.

- Desfeu una finalització per recuperar la tasca.
- Feu-hi neteja en bloc: suprimiu-ho tot, o tot el que sigui més antic d'1 / 3 / 6 mesos o d'un any.

---

## Compartir

Compartiu **un dia, una setmana o un mes** com a text o com a targeta d'imatge.

Abans de compartir podeu filtrar quins tipus d'esdeveniment s'hi inclouen i decidir si hi apareixen els noms dels tipus, de manera que podeu enviar la vostra setmana a algú sense ensenyar-ne tot el contingut.

---

[← Índex](./README.md) · [Següent: Entrada ràpida amb IA →](./02-ai-input.md)
