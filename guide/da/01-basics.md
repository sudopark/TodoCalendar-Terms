# 1. Det grundlæggende

[← Indhold](./README.md)

---

## Kalenderen

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/da/calendar.png" alt="Kalender" width="280">

Månedskalenderen er appens forside. Stryg til venstre og højre for at skifte måned, og tryk på en dag for at åbne dagens begivenhedsliste nedenunder.

- Hver dag viser en farvet bjælke pr. begivenhed plus et **+N**, når dagen har flere begivenheder, end rækken kan vise.
- Dagens liste er sorteret sådan: opgaver uden tidspunkt → opgaver med tidspunkt → aftaler → helligdage → begivenheder fra eksterne kalendere.
- Tryk på overskriften for at hoppe til en anden dato, eller brug **Flyt dato** til at vælge en direkte.

Hvor meget hver dag viser, bestemmer du selv: hvor mange detaljer hver begivenhed får, tekststørrelsen, farverne, navnene på helligdage og månekalenderen. [Tilpasning](./05-personalization.md) gennemgår hver enkelt indstilling ved navn.

---

## Opgaver og aftaler

Appen har to slags begivenheder, og forskellen er, om det er noget, du sætter flueben ved.

| | Opgave | Aftale |
|---|---|---|
| Tidspunkt | Valgfrit | Påkrævet |
| Udførelse | Ja – sæt flueben ved den | Nej |
| Uden tidspunkt | Bliver i **Aktuel opgaveliste**, indtil du er færdig | Ikke muligt |

En **opgave uden tidspunkt** er til noget, du skal have gjort snart, men ikke har lagt i kalenderen. Den ligger øverst i kalenderen og i widgeten Aktuel opgaveliste, indtil den er udført.

Du kan konvertere begge veje når som helst – **Konverter til aftale** / **Konverter til opgave** i begivenhedens menu. For at konvertere en opgave til en aftale skal der være et tidspunkt.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/da/event-detail.png" alt="Begivenhedsdetaljer" width="280">

Enhver begivenhed kan have et **Sted**, et **Link** og et **Notat**. Stedet vises med kortforhåndsvisning og åbner med ét tryk i din foretrukne kortapp, og linket får sin egen forhåndsvisning.

---

## Tilføjelse af begivenheder

Der er tre måder at tilføje en begivenhed på, alt efter hvor meget du gider skrive:

- **Hurtig tilføjelse** – indtastningsfeltet nederst i dagens liste. Skriv et navn, tryk retur, så er opgaven oprettet.
- **Fuld detalje** – tryk på **+** for at åbne editoren med tidspunkt, gentagelse, påmindelser, begivenhedstype, sted, link og notat.
- **AI-hurtigindtastning** – beskriv den i almindeligt sprog, og lad appen bygge begivenheden. Se [AI-hurtigindtastning](./02-ai-input.md).

En opgave kræver kun et navn. En aftale kræver et navn og et tidspunkt.

---

## Gentagne begivenheder

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/da/repeat-options.png" alt="Gentagelsesmuligheder" width="240">

I stedet for at bede dig sætte en gentagelsesregel sammen af rullemenuer læser appen den dato, du har valgt, og tilbyder færdige valgmuligheder til netop den. Vælger du en torsdag, tilbyder listen **Hver torsdag** og **Den tredje torsdag i hver måned**.

**Almindelige intervaller**

- Hver dag
- Hver uge · Hver 2. uge · Hver 3. uge · Hver 4. uge – på samme ugedag som begivenheden
- Hver måned – på samme dato hver måned
- Hvert år
- Hvert år (månekalender) – til fødselsdage og mærkedage, der følger månekalenderen

**Efter placering i måneden**

- Hver hverdag – mandag til fredag. Tilbydes, når begivenheden starter på en hverdag
- Alle dage i den sidste uge i hver måned
- Den første / anden / tredje / fjerde / sidste **torsdag** i hver måned – ugedagen udfyldes ud fra den dato, du valgte, så en begivenhed om fredagen giver **Den sidste fredag i hver måned** i stedet

**Gentagelse slutter**

Når du har valgt en gentagelse, vælger du, hvornår den stopper: **Aldrig** lader den løbe videre, **Den** sætter en bestemt slutdato, og **Efter** stopper den efter et antal **forekomster**.

Gentagne opgaver opfører sig anderledes end gentagne aftaler:

- En gentagelse, der ikke er udført, bliver ved med at stå i dagens kalender, også efter tidspunktet er passeret – den går ikke videre til næste forekomst af sig selv.
- Når du udfører den, ryger netop den forekomst over i listen over udførte opgaver, og den næste bliver oprettet.
- **Spring denne opgave over** flytter dig til næste forekomst uden at markere den som udført.
- Har gentagelsen en slutbetingelse, og er der ingen næste forekomst, slutter serien.

Når du redigerer eller sletter en forekomst af en gentagen begivenhed, vælger du omfanget: **Kun denne gang**, **Fra dette tidspunkt** eller **Alle begivenheder**.

For begivenheder i en forbundet ekstern kalender tilbydes månekalenderen ikke – eksterne kalendere har ingen plads til at gemme en gentagelsesregel efter månekalenderen.

---

## Begivenhedstyper og farver

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/da/event-type-list.png" alt="Begivenhedstyper" width="280">

Begivenhedstyper er dine egne kategorier, og de bestemmer den farve, en begivenhed får i kalenderen. Opret lige så mange, du vil, hver med sin egen farve.

- Slå en type fra for at skjule alle begivenheder af den type i kalenderen – nyttigt, hvis du vil dæmpe en travl arbejdskalender uden at afbryde forbindelsen til den.
- Når du sletter en type, kan du vælge at beholde eller slette de begivenheder, der hører til den.
- Vælg en **Standardbegivenhedstype**, så nye begivenheder lander det rigtige sted, uden at du skal vælge hver gang.

Helligdage og forbundne eksterne kalendere får deres egne typer, så dem kan du også skjule hver for sig.

---

## Påmindelser

Sæt så mange påmindelser pr. begivenhed, du har brug for.

- **Begivenheder med tidspunkt** – på begivenhedens tidspunkt, eller 1 / 5 / 10 / 15 / 30 minutter, 1 / 2 timer eller 1 / 2 / 7 dage før.
- **Heldagsbegivenheder** – kl. 9 eller kl. 12 den dag, eller kl. 9 1 / 2 / 7 dage før.
- **Brugerdefineret** – vælg lige præcis det tidspunkt, du vil.

Standardpåmindelser for begivenheder med tidspunkt og for heldagsbegivenheder sættes hver for sig under Indstillinger, så nye begivenheder allerede har deres påmindelser sat. Påmindelser kræver tilladelse til notifikationer, og appen guider dig til Indstillinger i iOS, hvis den er slået fra.

---

## Vigtigste begivenhed

Fastgør den ene ting, du ikke må gå glip af. Den vigtigste begivenhed bliver stående øverst i kalenderen, uanset hvilken dato du kigger på, og den har sin egen widget.

Opgaver og ikke-gentagende aftaler kan markeres som vigtigst. Gentagende aftaler kan ikke.

---

## Uafsluttede opgaver

Opgaver, hvis tidspunkt er passeret, uden at de er udført, samles i afsnittet **Uafsluttede opgaver** øverst i kalenderen, så en overset opgave ikke bliver liggende begravet på en dato, der allerede er passeret.

Opgaver uden tidspunkt og opgaver, der ligger frem i tiden, tælles ikke som uafsluttede – de er bare ikke forfaldne endnu. Vil du helst ikke se afsnittet, kan du skjule det helt under Indstillinger.

---

## Udførte opgaver

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/da/done-todos.png" alt="Udførte opgaver" width="280">

Alt, du sætter flueben ved, bliver gemt og grupperet efter, hvornår du blev færdig – I dag, I går, Denne måned og derefter efter måned og år.

- Fortryd en fuldførelse for at hente opgaven tilbage.
- Ryd op i én omgang: slet alle udførte opgaver, eller alt der er ældre end 1 / 3 / 6 måneder eller 1 år.

---

## Deling

Del **en dag, en uge eller en måned** som tekst eller som et billedkort.

Inden du deler, kan du filtrere, hvilke begivenhedstyper der skal med, og vælge om navnene på typerne skal vises – så du kan sende din uge til nogen uden at afsløre alt i den.

---

[← Indhold](./README.md) · [Næste: AI-hurtigindtastning →](./02-ai-input.md)
