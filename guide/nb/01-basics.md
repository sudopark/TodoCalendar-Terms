# 1. Det grunnleggende

[← Innhold](./README.md)

---

## Kalenderen

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/nb/calendar.png" alt="Kalender" width="280">

Månedsrutenettet er appens hjemskjerm. Sveip til venstre og høyre for å bla mellom måneder, og trykk på en dag for å åpne hendelseslisten under.

- Hver dag viser en fargestripe per hendelse, pluss en **+N**-indikator når det er flere enn det er plass til.
- Dagslisten er sortert slik: oppgaver uten tidspunkt → oppgaver med tidspunkt → avtaler → helligdager → hendelser fra eksterne kalendere.
- Trykk på toppen for å hoppe til hvilken som helst dato, eller bruk **Flytt dato** for å velge én direkte.

Hvor tett rutenettet er – radhøyde, skriftstørrelse for hendelsestekst, fet tekst, fargestriper, navn på helligdager, månekalenderen – kan du styre selv. Se [Tilpasning](./05-personalization.md).

---

## Oppgaver og avtaler

Appen har to slags hendelser, og forskjellen er om tingen kan *fullføres*.

| | Oppgave | Avtale |
|---|---|---|
| Tidspunkt | Valgfritt | Påkrevd |
| Fullføring | Ja – kryss den av | Nei |
| Uten tidspunkt | Blir liggende i **Gjeldende oppgaveliste** til du fullfører den | Ikke mulig |

En **oppgave uten tidspunkt** er for noe du må gjøre snart, men ikke har satt av tid til. Den ligger øverst i kalenderen og i widgeten Gjeldende oppgaveliste til den er fullført.

Du kan konvertere begge veier når som helst – **Konverter til avtale** / **Konverter til oppgave** fra mer-menyen til hendelsen. Å konvertere en oppgave til en avtale krever et tidspunkt.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/nb/event-detail.png" alt="Hendelsesdetaljer" width="280">

Hver hendelse kan ha et **sted** (med kartforhåndsvisning og ett trykk for å åpne den i kartappen du foretrekker), en **lenke** med forhåndsvisning, og et **notat**.

---

## Å legge til hendelser

Tre veier inn, avhengig av hvor mye du har lyst til å skrive:

- **Hurtigtillegg** – inntastingsfeltet nederst i dagslisten. Skriv et navn, trykk enter, og du har en oppgave.
- **Full detalj** – trykk på **+** for å åpne redigeringen med tidspunkt, gjentakelse, varsler, hendelsestype, sted, lenke og notat.
- **AI-hurtiginntasting** – beskriv den med vanlige ord og la appen bygge hendelsen. Se [AI-hurtiginntasting](./02-ai-input.md).

En oppgave trenger bare et navn. En avtale trenger både navn og tidspunkt.

---

## Gjentakende hendelser

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/nb/repeat-options.png" alt="Alternativer for gjentakelse" width="240">

I stedet for å be deg sette sammen en regel av nedtrekksmenyer, leser appen datoen du valgte og tilbyr ferdige alternativer for akkurat den. Velg en torsdag, og listen sier bokstavelig talt **Hver Torsdag** og **Den tredje Torsdag i hver måned**.

**Vanlige intervaller**

- Hver dag
- Hver uke · Hver 2. uke · Hver 3. uke · Hver 4. uke – på samme ukedag som hendelsen
- Hver måned – på samme dato hver måned
- Hvert år
- Hvert år (månekalender) – for bursdager og merkedager som følger månekalenderen

**Etter plassering i måneden**

- Hver ukedag – mandag til fredag. Tilbys når hendelsen starter på en hverdag
- Alle dager i siste uke av hver måned
- Den første / andre / tredje / fjerde / siste *ukedagen* i hver måned – for ting som «den siste fredagen i måneden»

**Gjentakelse avsluttes**

Når du har valgt en gjentakelse, velger du hvordan den stopper: **Aldri**, på en bestemt dato (**Den**), eller etter et antall forekomster (**Etter**).

Gjentakende oppgaver oppfører seg annerledes enn gjentakende avtaler:

- En gjentakelse som ikke er fullført, blir stående synlig i dagens kalender selv etter at tidspunktet har passert – den ruller ikke stille videre.
- Fullfører du den, havner den forekomsten under Fullførte oppgaver, og den neste blir opprettet.
- **Hopp over denne oppgaven** flytter deg til neste forekomst uten å markere den som fullført.
- Når gjentakelsen har en sluttbetingelse og det ikke finnes noen neste forekomst, avsluttes serien.

Når du redigerer eller sletter én forekomst av en gjentakende hendelse, velger du omfanget: **Bare denne gangen**, **Fra dette tidspunktet** eller **Alle hendelser**.

For hendelser i en tilkoblet ekstern kalender tilbys ikke månekalender-alternativet – den kalenderen har ingen måte å uttrykke det på.

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

Standardverdiene for hendelser med tidspunkt og for hele dagen-hendelser settes hver for seg i Innstillinger, så nye hendelser er ferdig innstilt. Varsler krever varslingstillatelse, og appen viser deg veien til iOS-innstillingene hvis den er slått av.

---

## Viktigste hendelse

Fest den ene tingen du ikke kan gå glipp av. Den viktigste hendelsen blir stående øverst i kalenderen uansett hvilken dato du ser på, og den har sin egen widget.

Oppgaver og ikke-gjentakende avtaler kan markeres som viktigst. Gjentakende avtaler kan ikke.

---

## Uferdige oppgaver

Oppgaver som har passert tidspunktet sitt uten å bli fullført, samles i seksjonen **Uferdige oppgaver** øverst i kalenderen, slik at noe du gikk glipp av, ikke sklir ut av syne inn i forrige uke.

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
