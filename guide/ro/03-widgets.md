# 3. Widget-uri și ecranul de blocare

[← Cuprins](./README.md)

---

Rostul unui widget de calendar este să nu mai fiți nevoit să deschideți calendarul. To-do Calendar vine cu un set larg, ca să îl alegeți pe cel care se potrivește cu felul în care vă verificați cu adevărat ziua — un singur eveniment următor, o lună întreagă sau lista de sarcini cu bifele la îndemână.

---

## Widget-uri pentru ecranul principal

### Astăzi și ce urmează

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/widget-today-and-next.png" alt="Widgetul Astăzi și ce urmează" width="360">

În stânga, data de azi și ce a mai rămas din zi; în dreapta, ce urmează. Cea mai densă privire de ansamblu asupra lui „ce acum, ce după”.

*Mediu.*

### Evenimente

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/widget-event-list.png" alt="Widgetul Evenimente" width="300">

O listă continuă a evenimentelor viitoare, grupate pe zile, inclusiv lista actuală de sarcini. Vine în trei dimensiuni și arată cu atât mai multe zile cu cât e mai mare.

*Mic · Mediu · Mare.*

### ASTĂZI

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/widget-today.png" alt="Widgetul ASTĂZI" width="200">

Doar ziua de azi — data, sărbătoarea dacă există și câte sarcini și programări aveți.

*Mic.*

### Eveniment principal

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/widget-foremost.png" alt="Widgetul Eveniment principal" width="200">

Singurul eveniment pe care l-ați fixat drept cel mai important, mereu la vedere. Vedeți [Eveniment principal](./01-basics.md#eveniment-principal).

*Inline pe ecranul de blocare · Mic · Mediu.*

### Calendarul și săptămânile

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/widget-month.png" alt="Widgetul Calendar" width="360">

Grila calendarului în sine, pe intervalul dorit:

| Widget | Dimensiune |
|---|---|
| Calendar | Mic |
| Săptămâna aceasta · 2 săptămâni | Mediu |
| 3 săptămâni · 4 săptămâni | Mare |
| Luna trecută · Luna aceasta · Luna viitoare | Mare |

### Widget-uri combinate

Două panouri într-un singur widget, atunci când o singură priveliște nu ajunge:

| Widget | Ce arată | Dimensiune |
|---|---|---|
| ASTĂZI + Calendar | Rezumatul zilei de azi lângă grila lunară | Mediu |
| Evenimente + Calendar | Evenimentele viitoare lângă grila lunară | Mediu |
| Evenimente + Principal | Evenimentele viitoare lângă evenimentul fixat | Mediu |
| Calendar + Calendar | Două luni una lângă alta | Mediu |

### Adăugați cu AI

O atingere și intrați direct în [Introducerea rapidă AI](./02-ai-input.md).

*Circular pe ecranul de blocare · Mic.*

---

## Ce puteți face dintr-un widget

- **Bifați o sarcină** — atingeți cerculețul oricărei sarcini dintr-un widget și se finalizează, fără să deschideți aplicația.
- **Treceți la eveniment** — atingerea unui eveniment îl deschide direct la ecranul lui de detalii.
- **Filtrați după tipul de eveniment** — țineți apăsat pe un widget, alegeți Editează widgetul și limitați-l la anumite tipuri de evenimente. În selector apar atât tipurile proprii, cât și calendarele externe conectate.

---

## Ecranul de blocare

### Widget-uri pentru ecranul de blocare

Mai multe widget-uri au și forme pentru ecranul de blocare: **Următorul eveniment** (inline și dreptunghiular), **Evenimentele următoare de astăzi** (dreptunghiular), **Eveniment principal** (inline) și **Adăugați cu AI** (circular).

### Numărătoare inversă cu Activitate live

Puneți un eveniment pe ecranul de blocare și priviți cum se scurge timpul până la el, cu aceeași priveliște și în Dynamic Island. Alegeți **Afișează pe ecranul de blocare** din meniul de acțiuni suplimentare al unui eveniment.

- Disponibil pentru evenimentele care încep în următoarele 8 ore.
- Câte un singur eveniment pe rând — dacă alegeți altul, sunteți întrebat dacă îl înlocuiți pe cel curent.
- Sarcinile pot fi finalizate direct din Activitatea live.

---

## Centrul de control

Pe iOS 18 și mai nou puteți adăuga controlul **Adaugă cu AI** în Centrul de control, așa că o glisare în jos și o atingere vă duc de oriunde la ecranul de introducere AI.

---

## Aspect

Widget-urile urmează implicit setarea de sistem pentru mod luminos/întunecat sau le puteți fixa pe o culoare de fundal la alegere — aplicația stabilește singură un text lizibil, în funcție de cât de deschisă e culoarea. Se reglează din **Setări › Aspect › Tema widgetului**. Vedeți [Personalizare](./05-personalization.md).

Widget-urile se împrospătează singure în cursul zilei și se actualizează imediat după ce schimbați ceva în aplicație.

---

[← Cuprins](./README.md) · [Următorul: Calendare externe →](./04-external-calendars.md)
