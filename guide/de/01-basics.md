# 1. Grundlagen

[← Inhalt](./README.md)

---

## Der Kalender

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/de/calendar.png" alt="Kalender" width="280">

Das Monatsraster ist der Startbildschirm. Wischen Sie nach links und rechts, um zwischen Monaten zu wechseln, und tippen Sie auf einen Tag, um darunter seine Ereignisliste zu öffnen.

- Jeder Tag zeigt pro Ereignis einen farbigen Balken und ein **+N**, wenn mehr Ereignisse anstehen, als hineinpassen.
- Die Tagesliste ist so sortiert: Aufgaben ohne Zeit → Aufgaben mit Zeit → Termine → Feiertage → Ereignisse aus externen Kalendern.
- Tippen Sie auf die Kopfzeile, um zu einem beliebigen Datum zu springen, oder wählen Sie eines direkt über **Datum verschieben**.

Wie dicht das Raster ist — Zeilenhöhe, Schriftgröße für Ereignistext, fetter Text, Farbbalken, Feiertagsnamen, Mondkalender — lässt sich vollständig umschalten. Siehe [Personalisierung](./05-personalization.md).

---

## Aufgaben und Termine

Die App kennt zwei Arten von Ereignissen, und der Unterschied liegt darin, ob sich die Sache *erledigen* lässt.

| | Aufgabe | Termin |
|---|---|---|
| Zeit | Optional | Erforderlich |
| Erledigen | Ja — abhaken | Nein |
| Ohne Zeit | Bleibt in der **Aktuellen Aufgabenliste**, bis Sie sie erledigen | Nicht möglich |

Eine **Aufgabe ohne Zeit** ist für etwas gedacht, das Sie bald erledigen müssen, aber noch nicht eingeplant haben. Sie steht oben im Kalender und im Widget „Aktuelle Aufgabenliste“, bis sie erledigt ist.

Sie können jederzeit in beide Richtungen umwandeln — **In Termin umwandeln** / **In Aufgabe umwandeln** im Mehr-Menü des Ereignisses. Für die Umwandlung einer Aufgabe in einen Termin ist eine Zeitangabe erforderlich.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/de/event-detail.png" alt="Ereignisdetails" width="280">

Jedes Ereignis kann einen **Ort** (mit Kartenvorschau und einem Tipp zum Öffnen in Ihrer bevorzugten Karten-App), einen **Link** mit Vorschau und eine **Notiz** enthalten.

---

## Ereignisse hinzufügen

Drei Wege hinein, je nachdem, wie viel Sie eintippen möchten:

- **Schnell hinzufügen** — das Eingabefeld unter der Tagesliste. Namen eintippen, Eingabetaste drücken, fertig ist die Aufgabe.
- **Vollständige Eingabe** — tippen Sie auf **+** und öffnen Sie den Editor mit Zeit, Wiederholung, Benachrichtigungen, Ereignistyp, Ort, Link und Notiz.
- **KI-Schnelleingabe** — beschreiben Sie es in normaler Sprache und lassen Sie die App das Ereignis bauen. Siehe [KI-Schnelleingabe](./02-ai-input.md).

Eine Aufgabe braucht nur einen Namen. Ein Termin braucht einen Namen und eine Zeit.

---

## Wiederkehrende Ereignisse

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/de/repeat-options.png" alt="Wiederholungsoptionen" width="240">

Statt Sie eine Regel aus Auswahlmenüs zusammenbauen zu lassen, liest die App das gewählte Datum und bietet passende, fertige Optionen an. Wählen Sie einen Donnerstag, und in der Liste steht wörtlich **Jeden Donnerstag** und **Der dritte Donnerstag jeden Monats**.

**Gängige Intervalle**

- Täglich
- Wöchentlich · Alle 2 Wochen · Alle 3 Wochen · Alle 4 Wochen — am selben Wochentag wie das Ereignis
- Monatlich — jeden Monat am selben Datum
- Jährlich
- Jährlich (Mondkalender) — für Geburtstage und Jahrestage, die nach dem Mondkalender begangen werden

**Nach Position im Monat**

- Jeden Wochentag — Montag bis Freitag. Wird angeboten, wenn das Ereignis an einem Werktag beginnt
- Alle Tage der letzten Woche jeden Monats
- Der erste / zweite / dritte / vierte / letzte *Wochentag* jeden Monats — für Fälle wie „der letzte Freitag im Monat“

**Wiederholung endet**

Sobald Sie eine Wiederholung gewählt haben, legen Sie fest, wie sie aufhört: **Nie**, **Am** einem bestimmten Datum oder **Nach** einer Anzahl von Wiederholungen.

Wiederkehrende Aufgaben verhalten sich anders als wiederkehrende Termine:

- Eine unerledigte Wiederholung bleibt im heutigen Kalender sichtbar, auch wenn ihre Zeit vorbei ist — sie rückt nicht stillschweigend weiter.
- Wird sie erledigt, wandert diese Wiederholung in die erledigten Aufgaben und die nächste wird angelegt.
- **Diese Aufgabe überspringen** bringt Sie zur nächsten Wiederholung, ohne sie als erledigt zu markieren.
- Hat die Wiederholung eine Endbedingung und gibt es keine nächste Wiederholung mehr, endet die Reihe.

Wenn Sie eine Wiederholung eines Ereignisses bearbeiten oder löschen, wählen Sie den Umfang: **Nur dieses Mal**, **Ab diesem Zeitpunkt** oder **Alle Ereignisse**.

Für Ereignisse in einem verbundenen externen Kalender wird die Mondkalender-Option nicht angeboten — dieser Kalender kann sie nicht ausdrücken.

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

Aufgaben, deren Zeit ohne Erledigung verstrichen ist, sammeln sich oben im Kalender im Bereich **Unerledigte Aufgaben**, damit ein verpasster Punkt nicht in die letzte Woche rutscht und aus dem Blick gerät.

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
