# 1. Alapok

[← Tartalom](./README.md)

---

## A naptár

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/calendar.png" alt="Naptár" width="280">

A havi rács a kezdőképernyő. Húzza balra vagy jobbra az ujját a hónapok közti váltáshoz, és koppintson egy napra, hogy alatta megnyíljon az aznapi eseménylista.

- Minden nap eseményenként egy színes sávot mutat, és **+N** jelzést, ha több esemény van, mint amennyi elfér.
- A napi lista sorrendje: időpont nélküli feladatok → időponthoz kötött feladatok → programok → ünnepek → külső naptárak eseményei.
- Koppintson a fejlécre, hogy bármelyik dátumra ugorjon, vagy válasszon ki egyet közvetlenül a **Dátum áthelyezése** funkcióval.

Az, hogy mennyire sűrű a rács — a sormagasság, az események szövegmérete, a félkövér szöveg, a színsávok, az ünnepnevek, a holdnaptár —, mind kapcsolható. Lásd: [Személyre szabás](./05-personalization.md).

---

## Feladatok és programok

Az alkalmazásban kétféle esemény van, és a különbség az, hogy az adott dolog *befejezhető*-e.

| | Feladat | Program |
|---|---|---|
| Időpont | Nem kötelező | Kötelező |
| Befejezés | Igen — pipálja ki | Nem |
| Időpont nélkül | Az **Aktuális feladatlista** részben marad, amíg el nem végzi | Nem lehetséges |

Az **időpont nélküli feladat** olyasmire való, amit hamarosan meg kell tennie, de még nem ütemezett be. A naptár tetején és az Aktuális feladatlista widgetben ül, amíg el nem készül.

Bármikor átalakíthatja bármelyik irányba — **Átalakítás programmá** / **Átalakítás feladattá** az esemény további műveletek menüjéből. A feladat programmá alakításához időpont kell.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/event-detail.png" alt="Esemény részletei" width="280">

Minden eseményhez tartozhat **Helyszín** (térkép-előnézettel és egykoppintásos megnyitással a kedvenc térképalkalmazásában), **Hivatkozás** előnézettel, valamint **Jegyzet**.

---

## Események hozzáadása

Három út befelé, attól függően, mennyit szeretne gépelni:

- **Gyors hozzáadás** — a beviteli mező a napi lista alján. Írjon be egy nevet, nyomjon entert, és kész is a feladat.
- **Teljes részletesség** — koppintson a **+** gombra, hogy megnyíljon a szerkesztő időponttal, ismétléssel, értesítésekkel, eseménytípussal, helyszínnel, hivatkozással és jegyzettel.
- **AI gyorsbevitel** — írja le hétköznapi nyelven, és hagyja, hogy az alkalmazás felépítse az eseményt. Lásd: [AI gyorsbevitel](./02-ai-input.md).

A feladathoz csak név kell. A programhoz név és időpont.

---

## Ismétlődő események

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/repeat-options.png" alt="Ismétlési beállítások" width="240">

Ahelyett, hogy legördülő menükből kellene összeraknia egy szabályt, az alkalmazás elolvassa a kiválasztott dátumot, és kész lehetőségeket kínál hozzá. Válasszon egy csütörtököt, és a listában szó szerint az áll, hogy **Minden Csütörtök** és **Minden hónap harmadik Csütörtök**.

**Gyakori időközök**

- Minden nap
- Minden héten · Minden 2. héten · Minden 3. héten · Minden 4. héten — az eseménnyel azonos hétköznapon
- Minden hónapban — minden hónap ugyanazon a napján
- Minden évben
- Minden évben (holdnaptár szerint) — a holdnaptár szerint tartott születésnapokhoz és évfordulókhoz

**A hónapon belüli hely szerint**

- Minden munkanapon — hétfőtől péntekig. Akkor kínálja fel, ha az esemény hétköznap kezdődik
- Minden hónap utolsó hetének minden napja
- Minden hónap első / második / harmadik / negyedik / utolsó *kiválasztott napja* — az olyasmikhez, mint „a hónap utolsó péntekje”

**Ismétlés vége**

Ha kiválasztott egy ismétlést, adja meg, hogyan álljon le: **Soha**, **Ekkor** egy adott dátumon, vagy **Ezután** egy megadott számú alkalom után.

Az ismétlődő feladatok másképp viselkednek, mint az ismétlődő programok:

- Egy be nem fejezett ismétlődés a mai naptárban akkor is látható marad, ha az időpontja már elmúlt — nem gördül tovább csendben.
- Ha befejezi, az adott alkalom a befejezett feladatok közé kerül, és létrejön a következő.
- A **Feladat kihagyása** a következő alkalomra viszi anélkül, hogy késznek jelölné.
- Ha az ismétlésnek van befejező feltétele, és nincs következő alkalom, a sorozat véget ér.

Amikor egy ismétlődő esemény egyik alkalmát szerkeszti vagy törli, kiválaszthatja a kört: **Csak ez alkalommal**, **Mostantól kezdve** vagy **Minden esemény**.

Csatlakoztatott külső naptáron lévő eseményeknél a holdnaptár szerinti lehetőség nem jelenik meg — az a naptár nem tudja kifejezni.

---

## Eseménytípusok és színek

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/event-type-list.png" alt="Eseménytípusok" width="280">

Az eseménytípusok az Ön saját kategóriái, és ezek hordozzák azt a színt, amellyel az esemény megjelenik a naptárban. Hozzon létre belőlük, amennyit csak szeretne, mindegyiket saját színnel.

- Kapcsoljon ki egy típust, és az adott típus minden eseménye eltűnik a naptárból — hasznos, ha el akar némítani egy zsúfolt munkanaptárt anélkül, hogy leválasztaná.
- Egy típus törlésekor eldöntheti, hogy megtartja vagy törli a hozzá kapcsolódó eseményeket.
- Állítson be **Alapértelmezett eseménytípus**t, hogy az új események a megfelelő helyre kerüljenek anélkül, hogy minden alkalommal választania kellene.

Az ünnepek és a csatlakoztatott külső naptárak saját típust kapnak, így ezeket is külön-külön elrejtheti.

---

## Értesítések

Eseményenként annyi értesítést állíthat be, amennyire szüksége van.

- **Időponthoz kötött események** — az esemény időpontjában, vagy 1 / 5 / 10 / 15 / 30 perccel, 1 / 2 órával, illetve 1 / 2 / 7 nappal korábban.
- **Egész napos események** — aznap reggel 9-kor vagy délben, illetve 1 / 2 / 7 nappal korábban reggel 9-kor.
- **Egyéni** — válasszon tetszőleges eltolást.

Az időponthoz kötött és az egész napos események alapértelmezései külön állíthatók a Beállításokban, így az új események eleve fel vannak készítve. Az értesítésekhez értesítési engedély kell; ha ki van kapcsolva, az alkalmazás elirányítja az iOS Beállításokhoz.

---

## Legfontosabb esemény

Tűzze ki azt az egy dolgot, amiről nem maradhat le. A legfontosabb esemény a naptár tetején marad, bármelyik dátumot is nézi, és saját widgetje is van.

Feladatok és nem ismétlődő programok állíthatók be legfontosabbként. Ismétlődő programok nem.

---

## Befejezetlen feladatok

Azok a feladatok, amelyeknek az időpontja már elmúlt, de nem lettek befejezve, a naptár tetején a **Befejezetlen feladatok** szakaszban gyűlnek össze, így egy elmulasztott tétel nem csúszik ki a látómezőből a múlt hétre.

Az időpont nélküli és a jövőbeli feladatok nem számítanak befejezetlennek — egyszerűen még nem esedékesek. A szakaszt teljesen el is rejtheti a Beállításokban, ha inkább nem látná.

---

## Befejezett feladatok

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/done-todos.png" alt="Befejezett feladatok" width="280">

Minden kipipált tétel megmarad, aszerint csoportosítva, hogy mikor végzett vele — ma, tegnap, ebben a hónapban, azután pedig hónapok és évek szerint.

- Vonja vissza a befejezést, és a feladat visszatér.
- Takarítson nagyban: törölje az összeset, vagy csak az 1 / 3 / 6 hónapnál, illetve 1 évnél régebbieket.

---

## Megosztás

Osszon meg **egy napot, egy hetet vagy egy hónapot** szövegként vagy képkártyaként.

Megosztás előtt szűrheti, mely eseménytípusok kerüljenek bele, és eldöntheti, megjelenjen-e a típusok neve — így elküldheti valakinek a hetét anélkül, hogy mindent kiteregetne belőle.

---

[← Tartalom](./README.md) · [Következő: AI gyorsbevitel →](./02-ai-input.md)
