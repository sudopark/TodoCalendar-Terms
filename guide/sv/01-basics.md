# 1. Grunderna

[← Innehåll](./README.md)

---

## Kalendern

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/sv/calendar.png" alt="Kalender" width="280">

Månadskalendern är appens startvy. Svep åt vänster och höger för att byta månad, och tryck på en dag för att öppna dagens händelselista under den.

- Varje dag visar ett färgat streck per händelse, plus en **+N**-markering när dagen har fler händelser än raden hinner visa.
- Dagslistan är sorterad så här: uppgifter utan tid → uppgifter med tid → möten → helgdagar → händelser från externa kalendrar.
- Tryck på rubriken för att hoppa till valfritt datum, eller använd **Flytta datum** för att välja ett direkt.

Hur mycket varje dag visar bestämmer du själv: hur mycket detalj varje händelse får, textstorleken, färgerna, helgdagarnas namn och månkalendern. [Anpassning](./05-personalization.md) går igenom varje inställning vid namn.

---

## Uppgifter och möten

Appen har två sorters händelser, och skillnaden är om det är något du bockar av.

| | Uppgift | Möte |
|---|---|---|
| Tid | Valfri | Krävs |
| Slutförande | Ja – bocka av den | Nej |
| Utan tid | Stannar i **Aktuell uppgiftslista** tills du blir klar | Går inte |

En **uppgift utan tid** är till för något du behöver göra snart men inte har lagt in en tid för. Den ligger högst upp i kalendern och i widgeten Aktuell uppgiftslista tills den är klar.

Du kan konvertera åt båda hållen när som helst – **Konvertera till möte** / **Konvertera till uppgift** från händelsens meny. För att konvertera en uppgift till ett möte krävs en tid.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/sv/event-detail.png" alt="Händelsedetaljer" width="280">

Varje händelse kan bära en **plats**, en **länk** och en **anteckning**. Platsen visas med kartförhandsvisning och öppnas med ett tryck i den kartapp du föredrar, och länken får en egen förhandsvisning.

---

## Lägga till händelser

Tre sätt att lägga till en händelse, beroende på hur mycket du vill skriva:

- **Snabbtillägg** – inmatningsfältet längst ned i dagslistan. Skriv ett namn, tryck retur, så skapas uppgiften.
- **Fullständig redigering** – tryck på **+** för att öppna redigeraren med tid, upprepning, påminnelser, händelsetyp, plats, länk och anteckning.
- **AI-snabbinmatning** – beskriv det med vanliga ord och låt appen bygga händelsen. Se [AI-snabbinmatning](./02-ai-input.md).

En uppgift behöver bara ett namn. Ett möte behöver ett namn och en tid.

---

## Återkommande händelser

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/sv/repeat-options.png" alt="Alternativ för upprepning" width="240">

I stället för att be dig sätta ihop en upprepningsregel av rullgardinsmenyer läser appen av datumet du valt och erbjuder färdiga alternativ för just det. Väljer du en torsdag erbjuder listan **Varje torsdag** och **Den tredje torsdagen i varje månad**.

**Vanliga intervall**

- Varje dag
- Varje vecka · Var 2:e vecka · Var 3:e vecka · Var 4:e vecka – på samma veckodag som händelsen
- Varje månad – på samma datum varje månad
- Varje år
- Varje år (månkalender) – för födelsedagar och årsdagar som följer månkalendern

**Efter placering i månaden**

- Varje vardag – måndag till fredag. Erbjuds när händelsen börjar på en vardag
- Alla dagar i den sista veckan varje månad
- Den första / andra / tredje / fjärde / sista **torsdagen** i varje månad – veckodagen fylls i från datumet du valt, så en händelse på en fredag ger **Den sista fredagen i varje månad** i stället

**Upprepning slutar**

När du valt en upprepning bestämmer du när den tar slut: **Aldrig** låter den löpa på, **Den** sätter ett bestämt slutdatum, och **Efter** stoppar den efter ett antal **gånger**.

Återkommande uppgifter beter sig annorlunda än återkommande möten:

- En upprepning som inte slutförts syns kvar i dagens kalender även efter att tiden passerat – den går inte vidare till nästa omgång av sig själv.
- Slutför du den hamnar den omgången bland slutförda uppgifter och nästa omgång skapas.
- **Hoppa över denna uppgift** tar dig till nästa omgång utan att markera den som klar.
- När upprepningen har ett slutvillkor och det inte finns någon nästa omgång avslutas serien.

När du redigerar eller tar bort en enskild omgång av en återkommande händelse väljer du omfattningen: **Endast denna gång**, **Från och med nu** eller **Alla händelser**.

För händelser i en ansluten extern kalender erbjuds inte månkalenderalternativet – externa kalendrar har ingenstans att lagra en regel för månkalenderupprepning.

---

## Händelsetyper och färger

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/sv/event-type-list.png" alt="Händelsetyper" width="280">

Händelsetyper är dina egna kategorier, och de bär färgen som händelsen visas med i kalendern. Skapa hur många du vill, var och en med sin egen färg.

- Stäng av en typ så döljs alla händelser av den typen från kalendern – praktiskt för att tysta en full jobbkalender utan att koppla från den.
- När du tar bort en typ får du välja om händelserna som hör till den ska behållas eller tas bort.
- Ange en **Standardhändelsetyp** så hamnar nya händelser rätt utan att du väljer varje gång.

Helgdagar och anslutna externa kalendrar får egna typer, så du kan dölja även dem var för sig.

---

## Påminnelser

Lägg till så många påminnelser per händelse som du behöver.

- **Händelser med tid** – vid händelsens tidpunkt, eller 1 / 5 / 10 / 15 / 30 minuter, 1 / 2 timmar, 1 / 2 / 7 dagar innan.
- **Heldagshändelser** – kl. 9 eller vid middagstid den dagen, eller kl. 9 1 / 2 / 7 dagar innan.
- **Anpassad** – välj precis hur långt före du vill bli påmind.

Standardvärden för händelser med tid och för heldagshändelser ställs in var för sig under Inställningar, så nya händelser redan har sina påminnelser inställda. Påminnelser kräver aviseringsbehörighet, och appen visar vägen till iOS-inställningarna om den är avstängd.

---

## Viktigaste händelsen

Fäst det enda du inte får missa. Den viktigaste händelsen stannar högst upp i kalendern oavsett vilket datum du tittar på, och den har en egen widget.

Uppgifter och möten som inte upprepas kan anges som viktigast. Återkommande möten kan det inte.

---

## Ej slutförda uppgifter

Uppgifter vars tid redan passerat utan att de slutförts samlas i avsnittet **Ej slutförda uppgifter** högst upp i kalendern, så att en missad uppgift inte blir liggande begravd på ett datum som redan passerat.

Uppgifter utan tid och uppgifter i framtiden räknas inte som ej slutförda – de har helt enkelt inte förfallit än. Du kan dölja hela avsnittet under Inställningar om du hellre slipper se det.

---

## Slutförda uppgifter

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/sv/done-todos.png" alt="Slutförda uppgifter" width="280">

Allt du bockar av sparas, grupperat efter när du blev klar – idag, igår, denna månad, och därefter per månad och år.

- Ångra ett slutförande för att få tillbaka uppgiften.
- Rensa i klump: ta bort allt, eller allt som är äldre än 1 / 3 / 6 månader eller 1 år.

---

## Delning

Dela **en dag, en vecka eller en månad** som text eller som ett bildkort.

Innan du delar kan du filtrera vilka händelsetyper som ska ingå och välja om typernas namn ska visas, så att du kan skicka din vecka till någon utan att avslöja allt som finns i den.

---

[← Innehåll](./README.md) · [Nästa: AI-snabbinmatning →](./02-ai-input.md)
