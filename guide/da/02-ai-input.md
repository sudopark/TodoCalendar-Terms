# 2. AI-hurtigindtastning

[← Indhold](./README.md)

---

Beskriv, hvad du vil, i almindeligt sprog, og appen bygger det for dig – "frokost med Sara fredag kl. 12", "flyt tandlægen til på tirsdag", "marker vasketøjet som udført". Ingen formularer, intet datohjul.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/da/ai-input.png" alt="AI-hurtigindtastning" width="280">

AI-hurtigindtastning kræver, at du er logget ind. Alt andet i appen virker uden konto.

---

## Hvad den kan

- Oprette opgaver og aftaler, hvor tidspunkt, gentagelse og begivenhedstype udledes af det, du sagde
- Ændre en eksisterende begivenhed – flytte den, omdøbe den, give den et nyt tidspunkt
- Udføre en opgave eller fortryde en fuldførelse
- Slette en begivenhed
- Klare flere ting i én anmodning ("tilføj træning mandag, onsdag og fredag kl. 7")

---

## Måder at sende en anmodning på

### I appen

Tryk på AI-knappen på kalenderskærmen. Indtastningsarket åbner med to tilstande, du kan skifte mellem når som helst:

- **Stemme** – tal, og se teksten dukke op undervejs. Kræver tilladelse til mikrofon og talegenkendelse; er en af dem nægtet, tilbyder appen at åbne Indstillinger i iOS eller at **Skriv i stedet**.
- **Tastatur** – skriv det. Nyttigt, når du er et sted, hvor du ikke kan tale.

### Fra et billede

**Læs fra billede** gør et billede om til begivenheder. **Tag et billede**, eller **Vælg fra bibliotek**; appen læser teksten på det – et skema, en plakat, et skærmbillede af en besked – og viser dig, hvad den fandt, så du kan rette det, der kom skævt ud, inden du sender.

Du kan vedhæfte **Ekstra instruktioner (valgfrit)** for at styre resultatet, f.eks. "tilføj disse som opgaver". Er der ingen læsbar tekst i billedet, siger appen det i stedet for at sende en tom anmodning.

### Siri

Sig **"Tilføj med AI i To-do Calendar"** – eller "Tilføj en aftale i To-do Calendar" / "Tilføj en opgave i To-do Calendar". Siri spørger, hvad du gerne vil tilføje, og anmodningen kører **i baggrunden uden at åbne appen**. Siri svarer "Modtaget. Jeg giver dig besked, når det er klar", og du får en notifikation, når resultatet er klart.

### Handlingsknappen

Tildel Handlingsknappen genvejen **Tilføj med AI**. Ét tryk, sig tingen, færdig – appen behøver aldrig komme i forgrunden.

### Widget og Kontrolcenter

- **Tilføj med AI**-widgeten – en widget til hjemmeskærmen eller låseskærmen, der åbner AI-indtastningen med ét tryk.
- **Kontrolcenter** (iOS 18 og nyere) – læg den samme betjening i Kontrolcenter, så du kan stryge ned og komme direkte ind.

### Delingsarket

Del **tekst eller et billede fra en hvilken som helst anden app** direkte til To-do Calendars AI. Læser du en besked med detaljerne om en aftale, eller kigger du på en plakat i Fotos – tryk på del, vælg To-do Calendar, tilføj eventuelt en instruktion, og send.

Anmodninger fra delingsarket kører også i baggrunden. Du får en bekræftelse på, at den blev sendt, og resultatet ser du i appen.

---

## Sådan forløber en anmodning

1. **Sendt** – din anmodning ryger afsted. Kom den fra Siri, Handlingsknappen eller delingsarket, behøver du ikke holde appen åben.
2. **Behandler** – appen viser forløbet. Du kan trykke **Stop** undervejs, men så kasseres det igangværende arbejde, og det kan ikke genoptages.
3. **Bekræftelse påkrævet** – ville anmodningen ændre noget væsentligt, beder appen dig godkende den først og viser præcis, hvad den er ved at gøre. Der er en nedtælling; udløber den, spørger du bare igen.
4. **Kommando fuldført** – resultatet lander i din kalender med det samme sammen med et resumé af, hvad der blev ændret.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/da/ai-result.png" alt="AI-resultat" width="280">

Der kører kun én anmodning ad gangen. Sender du en ny, mens en anden stadig venter på din godkendelse, beder appen dig om at tage den første først.

---

## Kreditter

AI-anmodninger trækker på en **daglig pulje af kreditter, der nulstilles hver dag**. Hvor meget der er tilbage, står øverst på AI-indtastningsskærmen, så du altid ved, hvor du står, inden du sender.

Løber puljen tør, holder AI-hurtigindtastning pause til næste nulstilling. Alt andet i appen kører videre.

---

## Tilladelser, appen kan bede om

| Tilladelse | Bruges til |
|---|---|
| Mikrofon + talegenkendelse | Stemmeindtastning |
| Kamera | Tage et billede til **Læs fra billede** |
| Fotobibliotek | Vælge et eksisterende billede |
| Notifikationer | Fortælle dig resultatet af en anmodning i baggrunden |

Der bliver kun spurgt om hver enkelt, første gang du bruger den funktion, der har brug for den, og appen virker videre uden – stemmeindtastning falder tilbage på tastaturet, billedindtastning på almindelig skrivning.

---

[← Indhold](./README.md) · [Næste: Widgets og låseskærm →](./03-widgets.md)
