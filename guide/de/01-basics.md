# 1. Grundlagen

[← Inhalt](./README.md)

---

## Der Kalender

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/de/calendar.png" alt="Kalender" width="280">

Der Monatskalender ist der Startbildschirm. Wischen Sie nach links und rechts, um zwischen Monaten zu wechseln, und tippen Sie auf einen Tag, um darunter seine Ereignisliste zu öffnen.

- Jeder Tag zeigt pro Ereignis einen farbigen Balken und ein **+N**, wenn der Tag mehr Ereignisse hat, als die Zeile zeigen kann.
- Die Tagesliste ist so sortiert: Aufgaben ohne Zeit → Aufgaben mit Zeit → Termine → Feiertage → Ereignisse aus externen Kalendern.
- Tippen Sie auf die Kopfzeile, um zu einem beliebigen Datum zu springen, oder wählen Sie eines direkt über **Datum verschieben**.

Wie viel jeder Tag zeigt, entscheiden Sie: der Detailgrad je Ereignis, die Schriftgröße, die Farben, die Feiertagsnamen und der Mondkalender. [Personalisierung](./05-personalization.md) geht jede Einstellung einzeln durch.

---

## Aufgaben und Termine

Die App kennt zwei Arten von Ereignissen, und der Unterschied liegt darin, ob Sie es abhaken, wenn es erledigt ist.

| | Aufgabe | Termin |
|---|---|---|
| Zeit | Optional | Erforderlich |
| Erledigen | Ja — abhaken | Nein |
| Ohne Zeit | Bleibt im Bereich **Aktuelle Aufgabenliste**, bis Sie sie erledigen | Nicht möglich |

Eine **Aufgabe ohne Zeit** ist für etwas gedacht, das Sie bald erledigen müssen, aber noch nicht eingeplant haben. Sie steht oben im Kalender und im Widget „Aktuelle Aufgabenliste“, bis sie erledigt ist.

Sie können jederzeit in beide Richtungen umwandeln — **In Termin umwandeln** / **In Aufgabe umwandeln** im Mehr-Menü des Ereignisses. Für die Umwandlung einer Aufgabe in einen Termin ist eine Zeitangabe erforderlich.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/de/event-detail.png" alt="Ereignisdetails" width="280">

Jedes Ereignis kann einen **Ort**, einen **Link** und eine **Notiz** enthalten. Der Ort zeigt eine Kartenvorschau und öffnet sich mit einem Tipp in Ihrer bevorzugten Karten-App; der Link hat eine eigene Vorschau.

---

## Ereignisse hinzufügen

Drei Wege, ein Ereignis anzulegen — je nachdem, wie viel Sie eintippen möchten:

- **Schnell hinzufügen** — das Eingabefeld unter der Tagesliste. Namen eintippen, Eingabetaste drücken, und die Aufgabe ist angelegt.
- **Vollständige Eingabe** — tippen Sie auf **+** und öffnen Sie den Editor mit Zeit, Wiederholung, Benachrichtigungen, Ereignistyp, Ort, Link und Notiz.
- **KI-Schnelleingabe** — beschreiben Sie es in normaler Sprache und lassen Sie die App das Ereignis bauen. Siehe [KI-Schnelleingabe](./02-ai-input.md).

Eine Aufgabe braucht nur einen Namen. Ein Termin braucht einen Namen und eine Zeit.

---

## Wiederkehrende Ereignisse

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/de/repeat-options.png" alt="Wiederholungsoptionen" width="240">

Statt Sie eine Wiederholungsregel aus Auswahlmenüs zusammenbauen zu lassen, liest die App das gewählte Datum und bietet passende, fertige Optionen an. Wählen Sie einen Donnerstag, und die Liste bietet Ihnen **Jeden Donnerstag** und **Der dritte Donnerstag jeden Monats** an.

**Gängige Intervalle**

- Täglich
- Wöchentlich · Alle 2 Wochen · Alle 3 Wochen · Alle 4 Wochen — am selben Wochentag wie das Ereignis
- Monatlich — jeden Monat am selben Datum
- Jährlich
- Jährlich (Mondkalender) — für Geburtstage und Jahrestage, die nach dem Mondkalender begangen werden

**Nach Position im Monat**

- Jeden Wochentag — Montag bis Freitag. Wird angeboten, wenn das Ereignis an einem Wochentag beginnt
- Alle Tage der letzten Woche jeden Monats
- Der erste / zweite / dritte / vierte / letzte **Donnerstag** jeden Monats — der Wochentag wird aus dem gewählten Datum übernommen, ein Freitagsereignis bietet also **Der letzte Freitag jeden Monats**

**Wiederholung endet**

Sobald Sie eine Wiederholung gewählt haben, legen Sie fest, wann sie aufhört: **Nie**, damit sie unbegrenzt weiterläuft, **Am** für ein festes Enddatum oder **Nach** einer Anzahl von **Wiederholungen**.

Wiederkehrende Aufgaben verhalten sich anders als wiederkehrende Termine:

- Eine unerledigte Wiederholung bleibt im heutigen Kalender sichtbar, auch wenn ihre Zeit vorbei ist — sie rückt nicht von selbst zur nächsten Wiederholung vor.
- Wird sie erledigt, wandert diese Wiederholung in die erledigten Aufgaben und die nächste wird angelegt.
- **Diese Aufgabe überspringen** bringt Sie zur nächsten Wiederholung, ohne sie als erledigt zu markieren.
- Hat die Wiederholung eine Endbedingung und gibt es keine nächste Wiederholung mehr, endet die Reihe.

Wenn Sie eine Wiederholung eines Ereignisses bearbeiten oder löschen, wählen Sie den Umfang: **Nur dieses Mal**, **Ab diesem Zeitpunkt** oder **Alle Ereignisse**.

Für Ereignisse in einem verbundenen externen Kalender wird die Mondkalender-Option nicht angeboten — externe Kalender haben keinen Platz, um eine Mondkalender-Wiederholungsregel zu speichern.

---

## Ereignistypen und Farben

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/de/event-type-list.png" alt="Ereignistypen" width="280">

Ereignistypen sind Ihre Kategorien, und sie tragen die Farbe, mit der ein Ereignis im Kalender erscheint. Legen Sie so viele an, wie Sie möchten, jeden mit eigener Farbe.

- Schalten Sie einen Typ aus, und alle Ereignisse dieses Typs verschwinden aus dem Kalender — praktisch, um einen vollen Arbeitskalender stummzuschalten, ohne ihn zu trennen.
- Beim Löschen eines Typs können Sie die zugehörigen Ereignisse behalten oder mitlöschen.
- Legen Sie einen **Standard-Ereignistyp** fest, damit neue Ereignisse an der richtigen Stelle landen, ohne dass Sie jedes Mal auswählen müssen.

Feiertage und verbundene externe Kalender bekommen eigene Typen, sodass Sie auch diese unabhängig ausblenden können.

---

## Benachrichtigungen

Legen Sie pro Ereignis so viele Benachrichtigungen fest, wie Sie brauchen.

- **Ereignisse mit Zeit** — zur Ereigniszeit oder 1 / 5 / 10 / 15 / 30 Minuten, 1 / 2 Stunden, 1 / 2 / 7 Tage vorher.
- **Ganztägige Ereignisse** — um 9 Uhr oder 12 Uhr am Tag selbst oder um 9 Uhr 1 / 2 / 7 Tage vorher.
- **Benutzerdefiniert** — wählen Sie einen beliebigen Abstand.

Die Standardwerte für Ereignisse mit Zeit und für ganztägige Ereignisse werden in den Einstellungen getrennt festgelegt, sodass neue Ereignisse sie gleich mitbringen. Benachrichtigungen brauchen die Mitteilungsberechtigung; ist sie aus, verweist die App auf die iOS-Einstellungen.

---

## Wichtigstes Ereignis

Heften Sie das eine an, das Sie nicht verpassen dürfen. Das wichtigste Ereignis bleibt oben im Kalender, egal welches Datum Sie gerade ansehen, und es hat ein eigenes Widget.

Aufgaben und nicht wiederkehrende Termine lassen sich als wichtigstes Ereignis festlegen. Wiederkehrende Termine nicht.

---

## Unerledigte Aufgaben

Aufgaben, deren Zeit ohne Erledigung verstrichen ist, sammeln sich oben im Kalender im Bereich **Unerledigte Aufgaben**, damit eine verpasste Aufgabe nicht an einem vergangenen Datum liegen bleibt und aus dem Blick gerät.

Aufgaben ohne Zeit und Aufgaben in der Zukunft zählen nicht als unerledigt — sie sind schlicht noch nicht fällig. Sie können den Bereich in den Einstellungen komplett ausblenden, wenn Sie ihn lieber nicht sehen möchten.

---

## Erledigte Aufgaben

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/de/done-todos.png" alt="Erledigte Aufgaben" width="280">

Alles, was Sie abhaken, bleibt erhalten, gruppiert nach dem Zeitpunkt der Erledigung — heute, gestern, diesen Monat, danach nach Monat und Jahr.

- Machen Sie eine Erledigung rückgängig, und die Aufgabe kommt zurück.
- Räumen Sie in einem Rutsch auf: alles löschen oder alles, was älter als 1 / 3 / 6 Monate oder ein Jahr ist.

---

## Teilen

Teilen Sie **einen Tag, eine Woche oder einen Monat** als Text oder als Bildkarte.

Vor dem Teilen können Sie filtern, welche Ereignistypen enthalten sind, und wählen, ob die Typnamen erscheinen — so schicken Sie jemandem Ihre Woche, ohne alles darin offenzulegen.

---

[← Inhalt](./README.md) · [Weiter: KI-Schnelleingabe →](./02-ai-input.md)
