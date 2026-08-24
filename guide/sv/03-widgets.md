# 3. Widgetar och låsskärm

[← Innehåll](./README.md)

---

Poängen med en kalenderwidget är att slippa öppna kalendern. To-do Calendar levererar ett brett utbud så att du kan välja den som passar hur du faktiskt kollar din dag – en enda nästa händelse, en hel månad, eller din uppgiftslista med rutor du kan trycka på.

---

## Widgetar för hemskärmen

### Idag och vad som väntar

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/widget-today-and-next.png" alt="Widgeten Idag och vad som väntar" width="360">

Dagens datum och det som är kvar av idag till vänster, det som kommer härnäst till höger. Den tätaste enskilda vyn av "vad nu, vad sen".

*Mellan.*

### Händelser

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/widget-event-list.png" alt="Widgeten Händelser" width="300">

En löpande lista över kommande händelser grupperade per dag, inklusive din Aktuella uppgiftslista. Finns i tre storlekar och visar fler dagar ju större den blir.

*Liten · Mellan · Stor.*

### IDAG

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/widget-today.png" alt="Widgeten IDAG" width="200">

Bara idag – datumet, helgdagen om det finns någon, och hur många uppgifter och möten du har.

*Liten.*

### Viktigaste händelsen

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/widget-foremost.png" alt="Widgeten Viktigaste händelsen" width="200">

Den enda händelse du fäst som viktigast, alltid i blickfånget. Se [Viktigaste händelsen](./01-basics.md#viktigaste-händelsen).

*Låsskärm inline · Liten · Mellan.*

### Månad och veckor

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/widget-month.png" alt="Widgeten Kalender" width="360">

Själva kalenderrutnätet, i det omfång du vill ha:

| Widget | Storlek |
|---|---|
| Kalender | Liten |
| Den här veckan · 2 veckor | Mellan |
| 3 veckor · 4 veckor | Stor |
| Förra månaden · Den här månaden · Nästa månad | Stor |

### Kombinationer

Två paneler i en widget, när en enda vy inte räcker:

| Widget | Visar | Storlek |
|---|---|---|
| IDAG + Kalender | Dagens sammanfattning bredvid månadsrutnätet | Mellan |
| Händelser + Kalender | Kommande händelser bredvid månadsrutnätet | Mellan |
| Händelser + Viktigast | Kommande händelser bredvid din fästa händelse | Mellan |
| Kalender + Kalender | Två månader sida vid sida | Mellan |

### Lägg till med AI

Ett tryck rakt in i [AI-snabbinmatning](./02-ai-input.md).

*Låsskärm cirkulär · Liten.*

---

## Vad du kan göra från en widget

- **Bocka av en uppgift** – tryck på cirkeln vid en uppgift i en widget så slutförs den, utan att appen öppnas.
- **Tryck dig vidare till händelsen** – trycker du på en händelse öppnas den direkt i detaljvyn.
- **Filtrera på händelsetyp** – håll in en widget, välj Redigera widget, och begränsa den till vissa händelsetyper. Både dina egna typer och anslutna externa kalendrar dyker upp i väljaren.

---

## Låsskärm

### Widgetar för låsskärmen

Flera widgetar har former för låsskärmen: **Nästa händelse** (inline och rektangulär), **Dagens kommande händelser** (rektangulär), **Viktigaste händelsen** (inline) och **Lägg till med AI** (cirkulär).

### Nedräkning med liveaktivitet

Lägg en händelse på låsskärmen och se tiden till den räknas ned, med samma vy i Dynamic Island. Välj **Visa på låsskärmen** i händelsens meny.

- Tillgängligt för händelser som börjar inom de närmaste 8 timmarna.
- En händelse åt gången – väljer du en ny får du frågan om den ska ersätta den nuvarande.
- Uppgifter kan slutföras direkt från liveaktiviteten.

---

## Kontrollcenter

På iOS 18 och senare kan du lägga till reglaget **Lägg till med AI** i Kontrollcenter, så att ett svep nedåt och ett tryck tar dig till AI-inmatningen varifrån som helst.

---

## Utseende

Widgetar följer systemets ljusa eller mörka läge som standard, eller så låser du dem till en bakgrundsfärg du väljer själv – appen väljer läsbar text automatiskt utifrån hur ljus färgen är. Ställ in det under **Inställningar › Utseende › Widget-tema**. Se [Anpassning](./05-personalization.md).

Widgetar uppdaterar sig själva under dagen och uppdateras direkt när du ändrar något i appen.

---

[← Innehåll](./README.md) · [Nästa: Externa kalendrar →](./04-external-calendars.md)
