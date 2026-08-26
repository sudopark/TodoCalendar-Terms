# 1. Det grunnleggende

[← Innhold](./README.md)

---

## Kalenderen

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/nb/calendar.png" alt="Kalender" width="280">

Månedskalenderen er appens hjemskjerm. Sveip til venstre og høyre for å bla mellom måneder, og trykk på en dag for å åpne hendelseslisten under.

- Hver dag viser en fargestripe per hendelse, pluss en **+N**-indikator når dagen har flere hendelser enn raden får plass til.
- Dagslisten er sortert slik: oppgaver uten tidspunkt → oppgaver med tidspunkt → avtaler → helligdager → hendelser fra eksterne kalendere.
- Trykk på toppen for å hoppe til hvilken som helst dato, eller bruk **Flytt dato** for å velge én direkte.

Hvor mye hver dag viser, bestemmer du selv: hvor mye detaljer hver hendelse får, tekststørrelsen, fargene, navnene på helligdagene og månekalenderen. [Tilpasning](./05-personalization.md) går gjennom hver enkelt innstilling ved navn.

---

## Oppgaver og avtaler

Appen har to slags hendelser, og forskjellen er om det er noe du krysser av.

| | Oppgave | Avtale |
|---|---|---|
| Tidspunkt | Valgfritt | Påkrevd |
| Fullføring | Ja – kryss den av | Nei |
| Uten tidspunkt | Blir liggende i **Gjeldende oppgaveliste** til du fullfører den | Ikke mulig |

En **oppgave uten tidspunkt** er for noe du må gjøre snart, men ikke har satt av tid til. Den ligger øverst i kalenderen og i widgeten Gjeldende oppgaveliste til den er fullført.

Du kan konvertere begge veier når som helst – **Konverter til avtale** / **Konverter til oppgave** fra mer-menyen til hendelsen. Å konvertere en oppgave til en avtale krever et tidspunkt.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/nb/event-detail.png" alt="Hendelsesdetaljer" width="280">

Hver hendelse kan ha et **sted**, en **lenke** og et **notat**. Stedet vises med kartforhåndsvisning og åpnes med ett trykk i kartappen du foretrekker, og lenken får sin egen forhåndsvisning.

---

## Å legge til hendelser

Tre måter å legge til en hendelse på, avhengig av hvor mye du har lyst til å skrive:

- **Hurtigtillegg** – inntastingsfeltet nederst i dagslisten. Skriv et navn, trykk enter, så er oppgaven opprettet.
- **Full detalj** – trykk på **+** for å åpne redigeringen med tidspunkt, gjentakelse, varsler, hendelsestype, sted, lenke og notat.
- **AI-hurtiginntasting** – beskriv den med vanlige ord og la appen bygge hendelsen. Se [AI-hurtiginntasting](./02-ai-input.md).

En oppgave trenger bare et navn. En avtale trenger både navn og tidspunkt.

---

## Gjentakende hendelser

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/nb/repeat-options.png" alt="Alternativer for gjentakelse" width="240">

I stedet for å be deg sette sammen en gjentakelsesregel av nedtrekksmenyer, leser appen datoen du valgte og tilbyr ferdige alternativer for akkurat den. Velger du en torsdag, tilbyr listen **Hver torsdag** og **Den tredje torsdag i hver måned**.

**Vanlige intervaller**

- Hver dag
- Hver uke · Hver 2. uke · Hver 3. uke · Hver 4. uke – på samme ukedag som hendelsen
- Hver måned – på samme dato hver måned
- Hvert år
- Hvert år (månekalender) – for bursdager og merkedager som følger månekalenderen

**Etter plassering i måneden**

- Hver ukedag – mandag til fredag. Tilbys når hendelsen starter på en hverdag
- Alle dager i siste uke av hver måned
- Den første / andre / tredje / fjerde / siste **torsdag** i hver måned – ukedagen fylles inn fra datoen du valgte, så en hendelse på en fredag gir **Den siste fredag i hver måned** i stedet

**Gjentakelse avsluttes**

Når du har valgt en gjentakelse, velger du når den stopper: **Aldri** lar den løpe videre, **Den** setter en bestemt sluttdato, og **Etter** stopper den etter et antall **forekomster**.

Gjentakende oppgaver oppfører seg annerledes enn gjentakende avtaler:

- En gjentakelse som ikke er fullført, blir stående synlig i dagens kalender selv etter at tidspunktet har passert – den går ikke videre til neste forekomst av seg selv.
- Fullfører du den, havner den forekomsten under Fullførte oppgaver, og den neste blir opprettet.
- **Hopp over denne oppgaven** flytter deg til neste forekomst uten å markere den som fullført.
- Når gjentakelsen har en sluttbetingelse og det ikke finnes noen neste forekomst, avsluttes serien.

Når du redigerer eller sletter én forekomst av en gjentakende hendelse, velger du omfanget: **Bare denne gangen**, **Fra dette tidspunktet** eller **Alle hendelser**.

For hendelser i en tilkoblet ekstern kalender tilbys ikke månekalender-alternativet – eksterne kalendere har ingen plass til å lagre en gjentakelsesregel etter månekalenderen.

---

## Hendelsestyper og farger

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/nb/event-type-list.png" alt="Hendelsestyper" width="280">

Hendelsestyper er dine egne kategorier, og de bestemmer fargen en hendelse får i kalenderen. Lag så mange du vil, hver med sin egen farge.

- Slå av en type for å skjule alle hendelser av den typen fra kalenderen – nyttig for å dempe en travel jobbkalender uten å koble den fra.
- Når du sletter en type, kan du velge om hendelsene som hører til, skal beholdes eller slettes.
- Angi en **Standard hendelsestype** så nye hendelser havner på rett sted uten at du må velge hver gang.

Helligdager og tilkoblede eksterne kalendere får sine egne typer, så du kan skjule dem uavhengig av hverandre.

---

## Varsler

Sett så mange varsler per hendelse som du trenger.

- **Hendelser med tidspunkt** – **På hendelsestidspunktet**, eller 1 / 5 / 10 / 15 / 30 minutter, 1 / 2 timer, 1 / 2 / 7 dager før.
- **Hele dagen-hendelser** – kl. 09.00 eller kl. 12.00 samme dag, eller kl. 09.00 1 / 2 / 7 dager før.
- **Egendefinert tid** – velg akkurat det tidspunktet du vil.

Standardverdiene for hendelser med tidspunkt og for hele dagen-hendelser settes hver for seg i Innstillinger, så nye hendelser allerede har varslene sine satt. Varsler krever varslingstillatelse, og appen viser deg veien til iOS-innstillingene hvis den er slått av.

---

## Viktigste hendelse

Fest den ene tingen du ikke kan gå glipp av. Den viktigste hendelsen blir stående øverst i kalenderen uansett hvilken dato du ser på, og den har sin egen widget.

Oppgaver og ikke-gjentakende avtaler kan markeres som viktigst. Gjentakende avtaler kan ikke.

---

## Uferdige oppgaver

Oppgaver som har passert tidspunktet sitt uten å bli fullført, samles i seksjonen **Uferdige oppgaver** øverst i kalenderen, slik at en oppgave du gikk glipp av, ikke blir liggende begravd på en dato som allerede er passert.

Oppgaver uten tidspunkt og oppgaver fram i tid regnes ikke som uferdige – de har rett og slett ikke forfalt ennå. Du kan skjule hele seksjonen i Innstillinger hvis du heller vil slippe å se den.

---

## Fullførte oppgaver

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/nb/done-todos.png" alt="Fullførte oppgaver" width="280">

Alt du krysser av, blir tatt vare på og gruppert etter når du ble ferdig – **I dag**, **I går**, **Denne måneden**, og deretter etter måned og år.

- **Angre fullføring** henter oppgaven tilbake.
- Rydd opp i bulk: slett **Alle fullførte oppgaver**, eller alt som er **Eldre enn 1 måned** / **3 måneder** / **6 måneder** / **1 år**.

---

## Deling

Del **denne dagen**, **denne uken** eller **denne måneden** som **tekst** eller som et **bilde**.

Før du deler, kan du filtrere hvilke hendelsestyper som skal være med, og velge om navnene på typene skal vises – slik at du kan sende noen uken din uten å avsløre alt som ligger i den.

---

[← Innhold](./README.md) · [Neste: AI-hurtiginntasting →](./02-ai-input.md)
