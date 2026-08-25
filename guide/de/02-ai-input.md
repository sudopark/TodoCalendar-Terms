# 2. KI-Schnelleingabe

[← Inhalt](./README.md)

---

Beschreiben Sie in normaler Sprache, was Sie möchten, und die App baut es für Sie — „Mittagessen mit Sara am Freitag um 12 Uhr“, „verschiebe den Zahnarzt auf nächsten Dienstag“, „hake die Wäsche ab“. Keine Formulare, kein Datum aus einem Drehrad.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/de/ai-input.png" alt="KI-Schnelleingabe" width="280">

Die KI-Schnelleingabe setzt ein angemeldetes Konto voraus. Alles andere in der App funktioniert auch ohne.

---

## Was sie kann

- Aufgaben und Termine anlegen, mit Zeit, Wiederholung und Ereignistyp, abgeleitet aus dem, was Sie gesagt haben
- Ein bestehendes Ereignis ändern — verschieben, umbenennen, neu terminieren
- Eine Aufgabe erledigen oder eine Erledigung rückgängig machen
- Ein Ereignis löschen
- Mehrere Dinge in einer Anfrage erledigen („trage Sport montags, mittwochs und freitags um 7 Uhr ein“)

---

## Wege, eine Anfrage zu senden

### In der App

Tippen Sie im Kalender auf die KI-Taste. Das Eingabeblatt öffnet sich mit zwei Modi, zwischen denen Sie jederzeit wechseln können:

- **Sprache** — sprechen Sie und sehen Sie zu, wie die Transkription live erscheint. Braucht die Berechtigung für Mikrofon und Spracherkennung; wird eine davon verweigert, bietet die App an, die iOS-Einstellungen zu öffnen oder auf **Stattdessen tippen** zu wechseln.
- **Tastatur** — tippen Sie es ein. Nützlich, wenn Sie an einem Ort sind, an dem Sie nicht sprechen können.

### Aus einem Bild

**Aus Bild lesen** macht aus einem Bild Ereignisse. **Foto aufnehmen** oder **aus Mediathek wählen** — die App liest den Text darauf, etwa einen Stundenplan, ein Veranstaltungsplakat oder den Screenshot einer Nachricht, und zeigt Ihnen das Gefundene, damit Sie vor dem Senden korrigieren können, was schiefgegangen ist.

Sie können **zusätzliche Anweisungen (optional)** anhängen, um das Ergebnis zu steuern, etwa „als Aufgaben hinzufügen“. Ist im Bild kein lesbarer Text, sagt die App das, statt eine leere Anfrage zu senden.

### Siri

Sagen Sie **„Mit KI in To-do Calendar hinzufügen“** — oder „Einen Termin in To-do Calendar hinzufügen“ / „Eine Aufgabe in To-do Calendar hinzufügen“. Siri fragt, was Sie hinzufügen möchten, und die Anfrage läuft **im Hintergrund, ohne die App zu öffnen**. Siri antwortet „Alles klar. Ich benachrichtige Sie, wenn es fertig ist.“, und Sie bekommen eine Mitteilung, sobald das Ergebnis bereit ist.

### Action-Taste

Belegen Sie die Action-Taste mit dem Kurzbefehl **Mit KI hinzufügen**. Einmal drücken, sagen, worum es geht, fertig — die App muss nie in den Vordergrund kommen.

### Widget und Kontrollzentrum

- **Widget „Mit KI hinzufügen“** — ein Widget für Home- oder Sperrbildschirm, das die KI-Eingabe mit einem Tipp öffnet.
- **Kontrollzentrum** (ab iOS 18) — legen Sie dasselbe Bedienelement ins Kontrollzentrum, um es mit einem Wischen von oben zu erreichen.

### Teilen-Menü

Teilen Sie **Text oder ein Bild aus jeder anderen App** direkt mit der KI von To-do Calendar. Wenn Sie gerade eine Nachricht mit den Details eines Treffens lesen oder ein Plakat in „Fotos“ ansehen: auf Teilen tippen, To-do Calendar wählen, bei Bedarf eine Anweisung ergänzen und senden.

Auch die Anfrage aus dem Teilen-Menü läuft im Hintergrund. Sie erhalten eine Bestätigung, dass sie gesendet wurde, und prüfen das Ergebnis in der App.

---

## So läuft eine Anfrage ab

1. **Gesendet** — Ihre Anfrage geht raus. Kam sie von Siri, der Action-Taste oder aus dem Teilen-Menü, müssen Sie die App nicht offen halten.
2. **Wird verarbeitet** — die App zeigt den Fortschritt. Sie können eine laufende Anfrage mit **Stopp** abbrechen; dabei wird der laufende Befehl verworfen und kann nicht fortgesetzt werden.
3. **Bestätigung erforderlich** — würde die Anfrage etwas Wesentliches ändern, bittet die App zuerst um Ihre Zustimmung und zeigt genau, was sie vorhat. Dafür läuft ein Countdown; ist er abgelaufen, fragen Sie einfach erneut.
4. **Befehl abgeschlossen** — das Ergebnis landet sofort in Ihrem Kalender, mit einer Zusammenfassung der Änderungen.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/de/ai-result.png" alt="KI-Ergebnis" width="280">

Es läuft immer nur eine Anfrage. Senden Sie eine weitere, während die erste noch auf Ihre Zustimmung wartet, weist die App Sie darauf hin, zuerst die erste zu erledigen.

---

## Guthaben

KI-Anfragen greifen auf ein **tägliches Guthaben zu, das sich jeden Tag zurücksetzt**. Wie viel übrig ist, steht oben in der KI-Eingabe, sodass Sie vor dem Senden immer wissen, woran Sie sind.

Ist das Guthaben aufgebraucht, pausiert die KI-Schnelleingabe bis zum nächsten Zurücksetzen. Alles andere in der App funktioniert weiter.

---

## Berechtigungen, die abgefragt werden können

| Berechtigung | Wofür |
|---|---|
| Mikrofon + Spracherkennung | Spracheingabe |
| Kamera | Ein Foto aufnehmen für **Aus Bild lesen** |
| Fotomediathek | Ein vorhandenes Bild auswählen |
| Mitteilungen | Ihnen das Ergebnis einer Anfrage im Hintergrund melden |

Jede wird erst abgefragt, wenn Sie die zugehörige Funktion zum ersten Mal nutzen, und die App funktioniert auch ohne sie weiter — die Spracheingabe weicht auf die Tastatur aus, die Bildeingabe auf das Tippen.

---

[← Inhalt](./README.md) · [Weiter: Widgets und Sperrbildschirm →](./03-widgets.md)
