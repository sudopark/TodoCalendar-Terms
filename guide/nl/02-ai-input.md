# 2. AI-snelinvoer

[← Inhoud](./README.md)

---

Beschrijf in gewone taal wat je wilt en de app bouwt het voor je — "vrijdag om twaalf uur lunchen met Sara", "verplaats de tandarts naar volgende week dinsdag", "vink de was af". Geen formulieren, geen datumkiezers.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/nl/ai-input.png" alt="AI-snelinvoer" width="280">

Voor AI-snelinvoer moet je ingelogd zijn. Al het andere in de app werkt zonder account.

---

## Wat het kan

- Taken en afspraken aanmaken, met tijd, herhaling en gebeurtenistype afgeleid uit wat je zei
- Een bestaande gebeurtenis wijzigen — verplaatsen, hernoemen, opnieuw inplannen
- Een taak voltooien, of een voltooiing ongedaan maken
- Een gebeurtenis verwijderen
- Meerdere dingen in één verzoek afhandelen ("voeg sporten toe op maandag, woensdag en vrijdag om 7 uur")

---

## Manieren om een verzoek te sturen

### In de app

Tik op de AI-knop op het kalenderscherm. Het invoerpaneel opent met twee modi waartussen je op elk moment kunt wisselen:

- **Spraak** — spreek en zie de transcriptie live verschijnen. Hiervoor is toegang tot de microfoon en spraakherkenning nodig; wordt een van beide geweigerd, dan biedt de app aan om de instellingen van iOS te openen of over te stappen op het toetsenbord.
- **Toetsenbord** — typ het in. Handig als je ergens bent waar je niet kunt praten.

### Vanuit een afbeelding

**Lezen vanuit afbeelding** maakt van een foto gebeurtenissen. Kies **Foto maken** of **Kiezen uit bibliotheek**; de app leest de tekst erop — een lesrooster, een evenementenposter, een schermafbeelding van een bericht — en toont je wat hij gevonden heeft, zodat je iets wat er verkeerd uit kwam kunt corrigeren voor je het verstuurt.

Je kunt **Extra instructies (optioneel)** meegeven om het resultaat te sturen, zoals "voeg deze toe als taken". Staat er geen leesbare tekst in de afbeelding, dan zegt de app dat in plaats van een leeg verzoek te sturen.

### Siri

Zeg **"Hé To-do Calendar"** — "Verzoek aan To-do Calendar", "Iets aan To-do Calendar vragen", "Een verzoek naar To-do Calendar sturen" en "Met AI in To-do Calendar toevoegen" werken ook. Je kunt ook "Todo Calendar" zeggen, zonder het koppelteken. Siri vraagt wat ze moet doen, en het verzoek draait **op de achtergrond zonder de app te openen**. Siri antwoordt "Begrepen. Ik laat het je weten zodra het klaar is." en je krijgt een melding zodra het resultaat er is.

### Actieknop

Koppel de actieknop aan de opdracht **Sturen**. Eén keer drukken, het ding zeggen, klaar — de app hoeft nooit naar de voorgrond te komen.

### Widget en bedieningspaneel

- **Widget Toevoegen met AI** — een widget voor het beginscherm of toegangsscherm die met één tik het AI-invoerscherm opent.
- **Bedieningspaneel** (iOS 18 en later) — voeg dezelfde bediening toe aan het bedieningspaneel, zodat je er met een veeg omlaag bij kunt.

### Deelmenu

Deel **tekst of een afbeelding uit elke andere app** rechtstreeks met de AI van To-do Calendar. Lees je een bericht met de details van een afspraak, of bekijk je een poster in Foto's — tik op delen, kies To-do Calendar, voeg desgewenst een instructie toe, en verstuur.

Ook een verzoek uit het deelmenu draait op de achtergrond. Je krijgt een bevestiging dat het verzonden is, en het resultaat bekijk je in de app.

---

## Hoe een verzoek verloopt

1. **Verzonden** — je verzoek gaat op pad. Kwam het van Siri, de actieknop of het deelmenu, dan hoef je de app niet open te houden.
2. **Verwerken** — de app toont de voortgang. Je kunt een lopend verzoek **Stoppen**, maar dan wordt het werk in uitvoering verworpen en kan het niet worden hervat.
3. **Bevestiging vereist** — zou het verzoek iets ingrijpends veranderen, dan vraagt de app eerst om je goedkeuring en laat precies zien wat er staat te gebeuren. Er loopt een aftelling; verloopt die, dan vraag je het gewoon opnieuw.
4. **Opdracht voltooid** — het resultaat landt meteen op je kalender, met een samenvatting van wat er veranderd is.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/nl/ai-result.png" alt="AI-resultaat" width="280">

Er draait maar één verzoek tegelijk. Stuur je er nog een terwijl het vorige nog op je goedkeuring wacht, dan zegt de app dat je eerst het eerste moet afhandelen.

---

## Credits

Elk AI-verzoek kost **credits**, en je credits worden elke dag bijgevuld. Hoeveel je er nog hebt staat boven aan het AI-invoerscherm, dus je weet het al voor je verstuurt.

Zijn ze op, dan wacht AI-snelinvoer op de bijvulling van de volgende dag. Al het andere in de app blijft gewoon werken.

---

## Toestemming die het kan vragen

| Toestemming | Waarvoor |
|---|---|
| Microfoon + spraakherkenning | Spraakinvoer |
| Camera | Een foto maken voor **Lezen vanuit afbeelding** |
| Fotobibliotheek | Een bestaande afbeelding kiezen |
| Meldingen | Je het resultaat van een achtergrondverzoek laten weten |

Elke toestemming wordt pas gevraagd als je de bijbehorende functie voor het eerst gebruikt, en de app blijft ook zonder werken — spraakinvoer valt terug op het toetsenbord, afbeeldingsinvoer op typen.

---

[← Inhoud](./README.md) · [Volgende: Widgets en toegangsscherm →](./03-widgets.md)
