# 1. De basis

[← Inhoud](./README.md)

---

## De kalender

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/nl/calendar.png" alt="Kalender" width="280">

Het maandraster is het startscherm. Veeg naar links en rechts om van maand te wisselen, en tik op een dag om eronder de lijst met gebeurtenissen van die dag te openen.

- Elke dag toont een gekleurde balk per gebeurtenis, plus een **+N** als er meer zijn dan er passen.
- De daglijst staat in deze volgorde: taken zonder tijd → taken met tijd → afspraken → feestdagen → gebeurtenissen uit externe agenda's.
- Tik op de kop om naar een willekeurige datum te springen, of kies er direct een met **Datum verplaatsen**.

Hoe dicht het raster is — rijhoogte, lettergrootte van gebeurtenistekst, vetgedrukte tekst, kleurbalken, namen van feestdagen, de maankalender — is allemaal instelbaar. Zie [Personalisatie](./05-personalization.md).

---

## Taken en afspraken

De app kent twee soorten gebeurtenissen, en het verschil zit in of iets *voltooid* kan worden.

| | Taak | Afspraak |
|---|---|---|
| Tijd | Optioneel | Verplicht |
| Voltooien | Ja — vink hem af | Nee |
| Zonder tijd | Blijft in **Huidige takenlijst** tot je hem afrondt | Niet mogelijk |

Een **taak zonder tijd** is bedoeld voor iets dat je binnenkort moet doen maar nog niet hebt ingepland. Hij staat boven aan de kalender en in de widget Huidige takenlijst tot hij klaar is.

Je kunt op elk moment beide kanten op omzetten — **Omzetten naar afspraak** / **Omzetten naar taak** in het meer-menu van de gebeurtenis. Voor het omzetten van een taak naar een afspraak is een tijdstip nodig.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/nl/event-detail.png" alt="Gebeurtenisdetails" width="280">

Elke gebeurtenis kan een **Locatie** dragen (met kaartvoorbeeld en met één tik openen in je favoriete kaarten-app), een **Link** met voorbeeld, en een **Notitie**.

---

## Gebeurtenissen toevoegen

Er zijn drie ingangen, afhankelijk van hoeveel je wilt typen:

- **Snel toevoegen** — het invoerveld onder aan de daglijst. Typ een naam, druk op return, en je hebt een taak.
- **Volledige details** — tik op **+** om de editor te openen met tijd, herhaling, meldingen, gebeurtenistype, locatie, link en notitie.
- **AI-snelinvoer** — beschrijf het in gewone taal en laat de app de gebeurtenis bouwen. Zie [AI-snelinvoer](./02-ai-input.md).

Een taak heeft alleen een naam nodig. Een afspraak heeft een naam en een tijdstip nodig.

---

## Herhalende gebeurtenissen

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/nl/repeat-options.png" alt="Herhaalopties" width="240">

In plaats van je een regel uit dropdowns te laten samenstellen, leest de app de datum die je koos en biedt daar kant-en-klare opties bij aan. Kies een donderdag en de lijst zegt letterlijk **Elke donderdag** en **De derde donderdag van elke maand**.

**Gebruikelijke intervallen**

- Elke dag
- Elke week · Elke 2 weken · Elke 3 weken · Elke 4 weken — op dezelfde dag van de week als de gebeurtenis
- Elke maand — op dezelfde datum in elke maand
- Elk jaar
- Elk jaar (maankalender) — voor verjaardagen en jubilea die je op de maankalender houdt

**Op positie in de maand**

- Elke werkdag — maandag tot en met vrijdag. Wordt aangeboden als de gebeurtenis op een werkdag begint
- Alle dagen van de laatste week van elke maand
- De eerste / tweede / derde / vierde / laatste *dag van de week* van elke maand — voor dingen als "de laatste vrijdag van de maand"

**Einde van de herhaling**

Zodra je een herhaling kiest, bepaal je hoe die stopt: **Nooit**, **Op** een bepaalde datum, of **Na** een aantal keer.

Herhalende taken gedragen zich anders dan herhalende afspraken:

- Een niet-voltooide herhaling blijft zichtbaar op de kalender van vandaag, ook nadat het tijdstip voorbij is — hij schuift niet stilletjes door.
- Voltooi je hem, dan gaat die keer naar Voltooide taken en wordt de volgende aangemaakt.
- **Deze taak overslaan** brengt je naar de volgende keer zonder hem als voltooid te markeren.
- Heeft de herhaling een einde en is er geen volgende keer meer, dan stopt de reeks.

Als je één keer van een herhalende gebeurtenis bewerkt of verwijdert, kies je het bereik: **Alleen deze keer**, **Vanaf nu**, of **Alle gebeurtenissen**.

Voor gebeurtenissen in een gekoppelde externe agenda wordt de maankalender-optie niet aangeboden — die agenda kan zoiets niet uitdrukken.

---

## Gebeurtenistypen en kleuren

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/nl/event-type-list.png" alt="Gebeurtenistypen" width="280">

Gebeurtenistypen zijn jouw categorieën, en ze bepalen de kleur waarmee een gebeurtenis op de kalender verschijnt. Maak er zoveel als je wilt, elk met een eigen kleur.

- Zet een type uit om alle gebeurtenissen van dat type op de kalender te verbergen — handig om een drukke werkagenda te dempen zonder de koppeling te verbreken.
- Bij het verwijderen van een type kies je of de bijbehorende gebeurtenissen blijven of meegaan.
- Stel een **Standaard gebeurtenistype** in, dan belanden nieuwe gebeurtenissen op de juiste plek zonder dat je elke keer kiest.

Feestdagen en gekoppelde externe agenda's krijgen hun eigen typen, dus die kun je ook los verbergen.

---

## Meldingen

Stel per gebeurtenis zoveel meldingen in als je nodig hebt.

- **Gebeurtenissen met tijd** — op het tijdstip van de gebeurtenis, of 1 / 5 / 10 / 15 / 30 minuten, 1 / 2 uur, 1 / 2 / 7 dagen van tevoren.
- **Gebeurtenissen van de hele dag** — om 9.00 of 12.00 uur die dag, of om 9.00 uur 1 / 2 / 7 dagen van tevoren.
- **Aangepast** — kies zelf welk moment je wilt.

De standaardwaarden voor gebeurtenissen met tijd en voor de hele dag stel je apart in bij Instellingen, zodat nieuwe gebeurtenissen meteen goed staan. Meldingen hebben meldingstoestemming nodig; staat die uit, dan wijst de app je naar de instellingen van iOS.

---

## Belangrijkste gebeurtenis

Zet dat ene ding vast dat je niet mag missen. De belangrijkste gebeurtenis blijft boven aan de kalender staan, welke datum je ook bekijkt, en heeft een eigen widget.

Taken en niet-herhalende afspraken kun je als belangrijkste instellen. Herhalende afspraken niet.

---

## Onvoltooide taken

Taken waarvan het tijdstip al voorbij is zonder dat ze voltooid zijn, worden verzameld in het onderdeel **Onvoltooide taken** boven aan de kalender. Zo schuift iets wat je gemist hebt niet naar vorige week uit beeld.

Taken zonder tijd en toekomstige taken tellen niet als onvoltooid — die zijn simpelweg nog niet aan de beurt. Zie je dit onderdeel liever niet, dan kun je het helemaal verbergen bij Instellingen.

---

## Voltooide taken

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/nl/done-todos.png" alt="Voltooide taken" width="280">

Alles wat je afvinkt wordt bewaard, gegroepeerd op wanneer je het afrondde — vandaag, gisteren, deze maand, en daarna per maand en jaar.

- Maak een voltooiing ongedaan om de taak terug te halen.
- Ruim in één keer op: verwijder alles, of alles wat ouder is dan 1 / 3 / 6 maanden of een jaar.

---

## Delen

Deel **een dag, een week of een maand** als tekst of als afbeeldingskaart.

Voor het delen kun je filteren welke gebeurtenistypen meegaan en kiezen of de naam van het type wordt getoond, zodat je iemand je week kunt sturen zonder alles erop prijs te geven.

---

[← Inhoud](./README.md) · [Volgende: AI-snelinvoer →](./02-ai-input.md)
