# 1. Noțiuni de bază

[← Cuprins](./README.md)

---

## Calendarul

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ro/calendar.png" alt="Calendar" width="280">

Calendarul lunar este ecranul principal. Glisați stânga-dreapta ca să treceți de la o lună la alta și atingeți o zi ca să deschideți dedesubt lista ei de evenimente.

- Fiecare zi arată câte o bară colorată pentru fiecare eveniment, plus un indicator **+N** atunci când ziua are mai multe evenimente decât încap pe rând.
- Lista zilei este ordonată astfel: sarcini fără oră → sarcini cu oră → programări → sărbători → evenimente din calendarele externe.
- Atingeți antetul ca să săriți la orice dată sau folosiți **Mută data** ca să alegeți una direct.

Cât arată fiecare zi depinde de dvs.: cât de detaliat apare un eveniment, dimensiunea textului, culorile, numele sărbătorilor și calendarul lunar. [Personalizare](./05-personalization.md) trece prin fiecare setare pe nume.

---

## Sarcini și programări

Aplicația are două feluri de evenimente, iar diferența e una singură: dacă îl bifați sau nu.

| | Sarcină | Programare |
|---|---|---|
| Ora | Opțională | Obligatorie |
| Finalizare | Da — o bifați | Nu |
| Fără oră | Rămâne în **Lista actuală de sarcini** până o terminați | Nu se poate |

O **sarcină fără oră** e potrivită pentru ceva ce trebuie făcut curând, dar pentru care nu ați stabilit un moment. Stă în partea de sus a calendarului și în widgetul **Lista actuală de sarcini** până când e gata.

Puteți face conversia în ambele sensuri oricând — **Convertește în programare** / **Convertește în sarcină**, din meniul de acțiuni suplimentare al evenimentului. Conversia unei sarcini în programare cere o oră.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ro/event-detail.png" alt="Detaliile evenimentului" width="280">

Orice eveniment poate avea **Locație**, **Link** și **Notă**. Locația vine cu previzualizare pe hartă și se deschide dintr-o singură atingere în aplicația de hărți preferată, iar linkul are propria previzualizare.

---

## Adăugarea evenimentelor

Trei moduri de a adăuga un eveniment, în funcție de cât vreți să scrieți:

- **Adăugare rapidă** — câmpul de introducere din josul listei zilei. Scrieți un nume, apăsați Enter și sarcina e creată.
- **Detaliere completă** — atingeți **+** ca să deschideți editorul cu oră, repetare, notificări, tip de eveniment, locație, link și notă.
- **Introducere rapidă AI** — descrieți evenimentul în limbaj obișnuit și lăsați aplicația să îl construiască. Vedeți [Introducere rapidă AI](./02-ai-input.md).

O sarcină are nevoie doar de un nume. O programare are nevoie de nume și de oră.

---

## Evenimente repetitive

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ro/repeat-options.png" alt="Opțiuni de repetare" width="240">

În loc să vă ceară să asamblați o regulă de repetare din liste derulante, aplicația citește data aleasă și vă oferă opțiuni gata făcute pentru ea. Alegeți o zi de joi și lista vă oferă **În fiecare joi** și **A treia joi din fiecare lună**.

**Intervale obișnuite**

- În fiecare zi
- În fiecare săptămână · La fiecare 2 săptămâni · La fiecare 3 săptămâni · La fiecare 4 săptămâni — în aceeași zi a săptămânii ca evenimentul
- În fiecare lună — la aceeași dată în fiecare lună
- În fiecare an
- În fiecare an (calendar lunar) — pentru zile de naștere și aniversări ținute după calendarul lunar

**După poziția în lună**

- În fiecare zi lucrătoare — de luni până vineri. Se oferă atunci când evenimentul începe într-o zi lucrătoare
- Toate zilele din ultima săptămână a fiecărei luni
- Prima / A doua / A treia / A patra / Ultima **joi** din fiecare lună — ziua săptămânii se completează din data aleasă, așa că un eveniment de vineri vă oferă **Ultima vineri din fiecare lună**

**Sfârșitul repetării**

După ce alegeți o repetare, stabiliți cum se oprește: **Niciodată**, **La data** unei anumite zile sau **După** un număr de apariții.

Sarcinile repetitive se comportă altfel decât programările repetitive:

- O repetare nefinalizată rămâne vizibilă în calendarul de azi chiar și după ce ora ei trece — nu trece singură la apariția următoare.
- Finalizarea ei trece acea apariție în sarcinile finalizate și o creează pe următoarea.
- **Omite această sarcină** vă duce la apariția următoare fără a o marca drept făcută.
- Când repetarea are o condiție de încheiere și nu mai există o apariție următoare, seria se termină.

Când modificați sau ștergeți o apariție a unui eveniment repetitiv, alegeți domeniul: **Doar de această dată**, **De acum înainte** sau **Toate evenimentele**.

Pentru evenimentele dintr-un calendar extern conectat, opțiunea lunară nu este oferită — calendarele externe nu au unde să păstreze o regulă de repetare lunară.

---

## Tipuri de evenimente și culori

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ro/event-type-list.png" alt="Tipuri de evenimente" width="280">

Tipurile de evenimente sunt categoriile dvs. și ele poartă culoarea cu care apare un eveniment în calendar. Creați câte doriți, fiecare cu propria culoare.

- Dezactivați un tip și toate evenimentele de acel fel dispar din calendar — util ca să reduceți la tăcere un calendar de serviciu aglomerat fără a-l deconecta.
- La ștergerea unui tip puteți alege dacă păstrați sau ștergeți evenimentele asociate.
- Stabiliți un **Tip de eveniment implicit**, ca noile evenimente să ajungă unde trebuie fără să alegeți de fiecare dată.

Sărbătorile și calendarele externe conectate au tipurile lor proprii, așa că le puteți ascunde și pe acelea separat.

---

## Notificări

Puneți câte notificări aveți nevoie pentru fiecare eveniment.

- **Evenimente cu oră** — la ora evenimentului sau cu 1 / 5 / 10 / 15 / 30 de minute, 1 / 2 ore, 1 / 2 / 7 zile înainte.
- **Evenimente de toată ziua** — la ora 9:00 sau la prânz în acea zi ori la ora 9:00 cu 1 / 2 / 7 zile înainte.
- **Personalizat** — alegeți orice decalaj doriți.

Valorile implicite pentru evenimentele cu oră și cele de toată ziua se stabilesc separat în Setări, astfel încât evenimentele noi vin deja pregătite. Notificările au nevoie de permisiunea de notificare; dacă e dezactivată, aplicația vă îndrumă spre Setările iOS.

---

## Eveniment principal

Fixați singurul lucru pe care nu aveți voie să îl ratați. Evenimentul principal rămâne în capul calendarului indiferent de data la care vă uitați și are propriul widget.

Sarcinile și programările care nu se repetă pot fi marcate ca principale. Programările repetitive nu pot.

---

## Sarcini neterminate

Sarcinile a căror oră a trecut fără să fie finalizate se adună într-o secțiune **Sarcini neterminate** în capul calendarului, ca o sarcină ratată să nu rămână îngropată pe o dată trecută.

Sarcinile fără oră și cele viitoare nu se socotesc drept neterminate — pur și simplu nu le-a venit încă scadența. Puteți ascunde secțiunea cu totul din Setări, dacă preferați să nu o vedeți.

---

## Sarcini finalizate

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ro/done-todos.png" alt="Sarcini finalizate" width="280">

Tot ce bifați se păstrează, grupat după momentul în care ați terminat — astăzi, ieri, luna aceasta, apoi pe luni și pe ani.

- Anulați o finalizare ca să readuceți sarcina.
- Faceți curat în bloc: ștergeți tot sau doar ce e mai vechi de 1 lună, 3 luni, 6 luni ori 1 an.

---

## Distribuire

Distribuiți **o zi, o săptămână sau o lună** ca text sau ca imagine.

Înainte de a distribui puteți filtra ce tipuri de evenimente să fie incluse și puteți alege dacă apar și numele tipurilor, ca să îi puteți trimite cuiva săptămâna dvs. fără să dezvăluiți tot ce e în ea.

---

[← Cuprins](./README.md) · [Următorul: Introducere rapidă AI →](./02-ai-input.md)
