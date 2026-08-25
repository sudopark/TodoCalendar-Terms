# 2. AI gyorsbevitel

[← Tartalom](./README.md)

---

Írja le hétköznapi nyelven, mit szeretne, és az alkalmazás felépíti — „ebéd Sárával pénteken délben”, „tedd át a fogorvost jövő keddre”, „a mosás kész”. Semmi űrlap, semmi dátumtárcsázás.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/ai-input.png" alt="AI gyorsbevitel" width="280">

Az AI gyorsbevitelhez bejelentkezett fiók kell. Az alkalmazásban minden más fiók nélkül is működik.

---

## Mire képes

- Feladatok és programok létrehozása — az időpontot, az ismétlést és az eseménytípust abból következteti ki, amit mondott
- Meglévő esemény módosítása — áthelyezés, átnevezés, időpont-változtatás
- Feladat befejezése vagy a befejezés visszavonása
- Esemény törlése
- Több dolog elintézése egyetlen kérésben („add hozzá az edzést hétfőn, szerdán és pénteken reggel 7-re”)

---

## A kérés elküldésének módjai

### Az alkalmazásban

Koppintson az AI gombra a naptárképernyőn. Megnyílik a beviteli lap két móddal, amelyek között bármikor válthat:

- **Hang** — beszéljen, és nézze, ahogy az átirat élőben megjelenik. Mikrofon- és beszédfelismerési engedély kell hozzá; ha bármelyiket megtagadja, az alkalmazás felajánlja az iOS Beállítások megnyitását vagy a **Gépelés helyette** lehetőséget.
- **Billentyűzet** — gépelje be. Hasznos ott, ahol nem tud beszélni.

### Képből

Az **Olvasás képből** egy képet alakít eseményekké. Válassza a **Fénykép készítése** vagy a **Kiválasztás a könyvtárból** lehetőséget; az alkalmazás kiolvassa a képen lévő szöveget — órarendet, rendezvényplakátot, egy üzenet képernyőképét —, és megmutatja, mit talált, hogy küldés előtt kijavíthassa, ami félresikerült.

A **További utasítások (opcionális)** mezőben utasítást is csatolhat az eredmény tereléséhez, például „ezeket adja hozzá feladatként”. Ha nincs olvasható szöveg a képen, az alkalmazás szól, ahelyett hogy üres kérést küldene.

### Siri

Mondja azt: **„Hozzáadás AI-val itt: To-do Calendar”** — vagy „Program hozzáadása itt: To-do Calendar” / „Feladat hozzáadása itt: To-do Calendar”. A Siri megkérdezi, mit szeretne hozzáadni, és a kérés **az alkalmazás megnyitása nélkül, a háttérben** fut le. A Siri azt válaszolja: „Rendben. Szólok, ha elkészült.”, Ön pedig értesítést kap, amint az eredmény kész van.

### Action gomb

Rendelje az Action gombhoz a **Hozzáadás AI-val** parancsot. Egy nyomás, mondja ki, kész — az alkalmazásnak sosem kell előtérbe kerülnie.

### Widget és Vezérlőközpont

- **Hozzáadás AI-val widget** — kezdőképernyős vagy zárolási képernyős widget, amely egyetlen koppintással megnyitja az AI-beviteli képernyőt.
- **Vezérlőközpont** (iOS 18 és újabb) — adja hozzá ugyanezt a vezérlőt a Vezérlőközponthoz egy lehúzásnyira lévő belépési pontért.

### Megosztási lap

Osszon meg **szöveget vagy képet bármely másik alkalmazásból** egyenesen a To-do Calendar AI-jával. Épp egy üzenetet olvas egy találkozó részleteivel, vagy egy plakátot néz a Fotókban — nyomja meg a megosztást, válassza a To-do Calendart, adjon hozzá utasítást, ha szeretne, és küldje el.

A megosztási lapról indított kérés is a háttérben fut. Visszajelzést kap arról, hogy elment, az eredményt pedig az alkalmazásban nézheti meg.

---

## Hogyan fut le egy kérés

1. **Elküldve** — a kérése útnak indul. Ha a Siritől, az Action gombtól vagy a megosztási lapról jött, nem kell nyitva tartania az alkalmazást.
2. **Feldolgozás** — az alkalmazás mutatja a haladást. Futás közben **leállíthatja** a kérést, a leállítás azonban elveti a folyamatban lévő munkát, és az nem folytatható.
3. **Megerősítés, ha kell** — ha a kérés valami lényegeset változtatna, az alkalmazás előbb jóváhagyást kér, és pontosan megmutatja, mire készül. Van visszaszámlálás; ha lejár, egyszerűen kérje újra.
4. **Kész** — az eredmény azonnal megjelenik a naptárában, összefoglalóval arról, mi változott.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/ai-result.png" alt="AI-eredmény" width="280">

Egyszerre csak egy kérés fut. Ha küld egy másikat, miközben az előző még a jóváhagyására vár, az alkalmazás szól, hogy előbb az elsővel foglalkozzon.

---

## Kreditek

Az AI-kérések a **naponta visszaálló napi keretből** fogynak. Ami maradt, az AI-beviteli képernyő tetején látszik, így küldés előtt mindig tudja, hol tart.

Ha elfogy a keret, az AI gyorsbevitel a következő visszaállásig szünetel. Az alkalmazásban minden más tovább működik.

---

## Engedélyek, amelyeket kérhet

| Engedély | Mire szolgál |
|---|---|
| Mikrofon + beszédfelismerés | Hangbevitel |
| Kamera | Fénykép készítése az **Olvasás képből** funkcióhoz |
| Fotókönyvtár | Meglévő kép kiválasztása |
| Értesítések | A háttérben futó kérés eredményének jelzése |

Mindegyiket csak akkor kéri, amikor először használja az adott funkciót, és nélküle is működik tovább — a hangbevitel helyett a billentyűzet, a képbevitel helyett a gépelés marad.

---

[← Tartalom](./README.md) · [Következő: Widgetek és zárolási képernyő →](./03-widgets.md)
