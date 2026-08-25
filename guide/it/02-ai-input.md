# 2. Inserimento rapido AI

[← Indice](./README.md)

---

Descrivi quello che vuoi in linguaggio naturale e l'app lo costruisce per te: «pranzo con Sara venerdì a mezzogiorno», «sposta il dentista a martedì prossimo», «segna il bucato come fatto». Niente moduli, nessuna data da cercare su una rotella.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/it/ai-input.png" alt="Inserimento rapido AI" width="280">

L'inserimento rapido AI richiede l'accesso a un account. Tutto il resto dell'app funziona anche senza.

---

## Cosa può fare

- Creare da fare e pianificazioni, deducendo orario, ricorrenza e tipo di evento da quello che hai detto
- Modificare un evento esistente: spostarlo, rinominarlo, cambiarne l'orario
- Completare un da fare, o annullarne il completamento
- Eliminare un evento
- Gestire più cose in un'unica richiesta («aggiungi palestra lunedì, mercoledì e venerdì alle 7»)

---

## Come inviare una richiesta

### Nell'app

Tocca il pulsante AI nella schermata del calendario. Si apre il pannello di inserimento con due modalità tra cui puoi passare in qualsiasi momento:

- **Voce** — parla e guarda la trascrizione comparire in tempo reale. Servono le autorizzazioni per microfono e riconoscimento vocale; se una delle due viene negata, l'app ti propone di aprire le impostazioni di iOS oppure di passare alla tastiera.
- **Tastiera** — scrivilo. Utile quando sei dove non puoi parlare.

### Da un'immagine

**Leggi da un'immagine** trasforma una foto in eventi. **Scatta una foto** o **scegli dalla libreria**: l'app legge il testo che c'è sopra — un orario delle lezioni, la locandina di un evento, lo screenshot di un messaggio — e ti mostra quello che ha trovato, così puoi correggere quello che è venuto storto prima di inviare.

Puoi allegare un'istruzione per orientare il risultato, tipo «aggiungi questi come da fare». Se nell'immagine non c'è testo leggibile, l'app te lo dice invece di inviare una richiesta vuota.

### Siri

Di' **«Aggiungi con l'IA in To-do Calendar»** — oppure «Aggiungi una pianificazione in To-do Calendar» / «Aggiungi un'attività da fare in To-do Calendar». Siri ti chiede che cosa vuoi aggiungere e la richiesta viene eseguita **in background senza aprire l'app**. Siri risponde «Ricevuto. Ti avviserò quando sarà fatto.» e ricevi una notifica quando il risultato è pronto.

### Tasto Azione

Assegna al tasto Azione il comando rapido **Aggiungi con l'IA**. Una pressione, dici la cosa, fatto: l'app non deve mai passare in primo piano.

### Widget e Centro di Controllo

- **Widget Aggiungi con l'AI** — un widget per la schermata Home o per la schermata di blocco che apre la schermata di inserimento AI con un tocco.
- **Centro di Controllo** (iOS 18 e successivi) — aggiungi lo stesso controllo al Centro di Controllo per avere un accesso a portata di scorrimento.

### Foglio di condivisione

Condividi **testo o un'immagine da qualsiasi altra app** direttamente con l'AI di To-do Calendar. Mentre leggi un messaggio con i dettagli di un incontro, o guardi una locandina in Foto: tocca condividi, scegli To-do Calendar, se vuoi aggiungi un'istruzione e invia.

Anche la richiesta dal foglio di condivisione viene eseguita in background. Ricevi la conferma che è stata inviata e il risultato lo controlli nell'app.

---

## Come viene elaborata una richiesta

1. **Inviata** — la tua richiesta parte. Se arriva da Siri, dal tasto Azione o dal foglio di condivisione, non devi tenere l'app aperta.
2. **Elaborazione** — l'app mostra l'avanzamento. Puoi **interrompere** una richiesta mentre è in corso, ma l'interruzione scarta l'attività in corso e non potrà essere ripresa.
3. **Conferma, quando serve** — se la richiesta comporta un cambiamento importante, l'app ti chiede prima di approvarla e ti mostra esattamente che cosa sta per fare. C'è un conto alla rovescia; se scade, basta chiedere di nuovo.
4. **Attività completata** — il risultato arriva subito sul tuo calendario, con un riepilogo di che cosa è cambiato.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/it/ai-result.png" alt="Risultato AI" width="280">

Viene elaborata una sola richiesta alla volta. Se ne invii un'altra mentre la prima è ancora in attesa della tua approvazione, l'app ti invita a occuparti prima di quella.

---

## Crediti

Le richieste AI attingono a una **quota giornaliera che si azzera ogni giorno**. Quanto ne resta è indicato in cima alla schermata di inserimento AI, così sai sempre come sei messo prima di inviare.

Se la quota si esaurisce, l'inserimento rapido AI si ferma fino al prossimo azzeramento. Tutto il resto dell'app continua a funzionare.

---

## Autorizzazioni che potrebbe chiedere

| Autorizzazione | Serve per |
|---|---|
| Microfono + riconoscimento vocale | Inserimento vocale |
| Fotocamera | Scattare una foto per **Leggi da un'immagine** |
| Libreria foto | Scegliere un'immagine già esistente |
| Notifiche | Comunicarti il risultato di una richiesta in background |

Ciascuna viene chiesta solo quando usi per la prima volta la funzione che la richiede, e l'app continua a funzionare anche senza: l'inserimento vocale ripiega sulla tastiera, quello da immagine sulla scrittura.

---

[← Indice](./README.md) · [Avanti: Widget e schermata di blocco →](./03-widgets.md)
