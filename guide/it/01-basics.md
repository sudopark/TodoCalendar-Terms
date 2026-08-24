# 1. Le basi

[← Indice](./README.md)

---

## Il calendario

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/calendar.png" alt="Calendario" width="280">

La griglia del mese è la schermata principale. Scorri a destra e a sinistra per cambiare mese, tocca un giorno per aprire sotto l'elenco dei suoi eventi.

- Ogni giorno mostra una barra colorata per evento, più un indicatore **+N** quando ce ne sono più di quanti ne entrino.
- L'elenco del giorno è ordinato così: da fare senza orario → da fare con orario → pianificazioni → festività → eventi dei calendari esterni.
- Tocca l'intestazione per saltare a una data qualsiasi, oppure usa **Sposta data** per sceglierla direttamente.

Quanto è densa la griglia — altezza delle righe, dimensione del testo degli eventi, grassetto, barre colorate, nomi delle festività, calendario lunare — è tutto modificabile. Vedi [Personalizzazione](./05-personalization.md).

---

## Da fare e pianificazioni

L'app ha due tipi di evento, e la differenza sta nel fatto che la cosa si possa *completare* oppure no.

| | Da fare | Pianificazione |
|---|---|---|
| Orario | Facoltativo | Obbligatorio |
| Completamento | Sì, lo spunti | No |
| Senza orario | Resta in **Elenco da fare attuale** finché non lo concludi | Non possibile |

Un **da fare senza orario** serve per qualcosa che devi fare presto ma che non hai ancora messo in agenda. Resta in cima al calendario e nel widget Elenco da fare attuale finché non è concluso.

Puoi convertire un tipo nell'altro in qualsiasi momento — **Converti in pianificazione** / **Converti in da fare** dal menu Altro dell'evento. Per convertire un da fare in pianificazione serve un orario.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/event-detail.png" alt="Dettaglio evento" width="280">

Ogni evento può portare con sé un **Luogo** (con anteprima della mappa e apertura con un tocco nell'app mappe che preferisci), un **Link** con anteprima e una **Nota**.

---

## Aggiungere eventi

Tre modi per entrare, a seconda di quanto vuoi scrivere:

- **Aggiunta rapida** — il campo di inserimento in fondo all'elenco del giorno. Scrivi un nome, premi invio e hai un da fare.
- **Dettaglio completo** — tocca **+** per aprire l'editor con orario, ricorrenza, promemoria, tipo di evento, luogo, link e nota.
- **Inserimento rapido AI** — descrivilo in linguaggio naturale e lascia che sia l'app a costruire l'evento. Vedi [Inserimento rapido AI](./02-ai-input.md).

A un da fare basta un nome. A una pianificazione servono un nome e un orario.

---

## Eventi ricorrenti

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/repeat-options.png" alt="Opzioni di ricorrenza" width="240">

Invece di chiederti di comporre una regola con una serie di menu a discesa, l'app legge la data che hai scelto e ti propone opzioni già pronte per quella data. Scegli un giovedì e l'elenco dice letteralmente **Ogni giovedì** e **Il terzo giovedì di ogni mese**.

**Intervalli più comuni**

- Ogni giorno
- Ogni settimana · Ogni 2 settimane · Ogni 3 settimane · Ogni 4 settimane — nello stesso giorno della settimana dell'evento
- Ogni mese — nello stesso giorno di ogni mese
- Ogni anno
- Ogni anno (calendario lunare) — per compleanni e ricorrenze che segui sul calendario lunare

**In base alla posizione nel mese**

- Ogni giorno feriale — dal lunedì al venerdì. Viene proposto quando l'evento inizia in un giorno feriale
- Tutti i giorni dell'ultima settimana di ogni mese
- Il primo / secondo / terzo / quarto / l'ultimo *giorno della settimana* di ogni mese — per cose come «l'ultimo venerdì del mese»

**Fine ricorrenza**

Una volta scelta la ricorrenza, decidi come si ferma: **Mai**, **Il giorno** di una data precisa, oppure **Dopo** un certo numero di occorrenze.

I da fare ricorrenti si comportano diversamente dalle pianificazioni ricorrenti:

- Una ricorrenza non completata resta visibile sul calendario di oggi anche dopo che il suo orario è passato: non scivola in avanti in silenzio.
- Completandola, quell'occorrenza finisce tra i da fare completati e viene creata la successiva.
- **Salta questo da fare** ti porta all'occorrenza successiva senza segnarla come conclusa.
- Quando la ricorrenza ha una condizione di fine e non c'è un'occorrenza successiva, la serie si conclude.

Quando modifichi o elimini un'occorrenza di un evento ricorrente, scegli l'ambito: **Solo questa volta**, **Da questo momento** oppure **Tutti gli eventi**.

Per gli eventi su un calendario esterno collegato l'opzione lunare non viene proposta: quel calendario non ha modo di esprimerla.

---

## Tipi di evento e colori

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/event-type-list.png" alt="Tipi di evento" width="280">

I tipi di evento sono le tue categorie, e portano con sé il colore con cui un evento appare sul calendario. Creane quanti vuoi, ciascuno con il suo colore.

- Disattiva un tipo per nascondere dal calendario tutti gli eventi di quel tipo: comodo per silenziare un calendario di lavoro affollato senza scollegarlo.
- Quando elimini un tipo puoi scegliere se tenere o eliminare anche gli eventi collegati.
- Imposta un **Tipo di evento predefinito** così i nuovi eventi finiscono nel posto giusto senza doverlo scegliere ogni volta.

Anche le festività e i calendari esterni collegati hanno i propri tipi, quindi puoi nascondere pure quelli in modo indipendente.

---

## Promemoria

Imposta tutti i promemoria che ti servono per ogni evento.

- **Eventi con orario** — all'orario dell'evento, oppure 1 / 5 / 10 / 15 / 30 minuti, 1 / 2 ore, 1 / 2 / 7 giorni prima.
- **Eventi di tutto il giorno** — alle 9:00 o a mezzogiorno di quel giorno, oppure alle 9:00 di 1 / 2 / 7 giorni prima.
- **Personalizzato** — scegli l'anticipo che preferisci.

I valori predefiniti per gli eventi con orario e per quelli di tutto il giorno si impostano separatamente nelle Impostazioni, così i nuovi eventi arrivano già pronti. I promemoria richiedono l'autorizzazione alle notifiche; se è disattivata, l'app ti indirizza alle impostazioni di iOS.

---

## Evento principale

Fissa l'unica cosa che non puoi perderti. L'evento principale resta in cima al calendario qualunque data tu stia guardando, e ha un widget tutto suo.

I da fare e le pianificazioni non ricorrenti possono essere impostati come principali. Le pianificazioni ricorrenti no.

---

## Da fare non completati

I da fare il cui orario è già passato senza che siano stati completati vengono raccolti in una sezione **Da fare non completati** in cima al calendario, così una cosa mancata non scivola fuori vista nella settimana scorsa.

I da fare senza orario e quelli futuri non contano come non completati: semplicemente non sono ancora scaduti. Se preferisci non vederla, puoi nascondere del tutto la sezione nelle Impostazioni.

---

## Da fare completati

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/done-todos.png" alt="Da fare completati" width="280">

Tutto quello che spunti viene conservato e raggruppato in base a quando l'hai concluso: oggi, ieri, questo mese, poi per mese e per anno.

- Annulla un completamento per far tornare il da fare.
- Fai pulizia in blocco: elimina tutto, oppure tutto quello più vecchio di 1 / 3 / 6 mesi o di un anno.

---

## Condivisione

Condividi **un giorno, una settimana o un mese** come testo o come immagine.

Prima di condividere puoi filtrare quali tipi di evento includere e scegliere se mostrarne i nomi, così puoi mandare a qualcuno la tua settimana senza rivelarne ogni dettaglio.

---

[← Indice](./README.md) · [Avanti: Inserimento rapido AI →](./02-ai-input.md)
