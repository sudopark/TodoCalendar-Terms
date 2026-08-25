# 3. Widgetek és zárolási képernyő

[← Tartalom](./README.md)

---

A naptárwidget értelme az, hogy ne kelljen megnyitnia a naptárt. A To-do Calendar bőséges készletet ad, hogy azt választhassa, amelyik illik ahhoz, ahogyan valóban átnézi a napját — egyetlen következő esemény, egy teljes hónap, vagy a feladatlistája koppintható jelölőkkel.

---

## Kezdőképernyős widgetek

### Ma és ami ezután következik

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/widget-today-and-next.png" alt="Ma és ami ezután következik widget" width="360">

Balra a mai dátum és az, ami a mai napból hátravan, jobbra pedig ami következik. A „mi most, mi utána” legsűrűbb egyetlen nézete.

*Közepes.*

### Események

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/widget-event-list.png" alt="Eseménylista widget" width="300">

A közelgő események folyó listája napok szerint csoportosítva, benne az aktuális feladataival is. Három méretben kapható, és minél nagyobb, annál több napot mutat.

*Kicsi · Közepes · Nagy.*

### MA

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/widget-today.png" alt="MA widget" width="200">

Csak a mai nap — a dátum, az ünnep, ha van, és hogy hány feladata és programja van.

*Kicsi.*

### Legfontosabb esemény

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/widget-foremost.png" alt="Legfontosabb esemény widget" width="200">

Az az egy esemény, amelyet a legfontosabbként tűzött ki, mindig szem előtt. Lásd: [Legfontosabb esemény](./01-basics.md#legfontosabb-esemény).

*Zárolási képernyős beágyazott · Kicsi · Közepes.*

### Hónap és hetek

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/widget-month.png" alt="Hónap widget" width="360">

Maga a naptárrács, abban a tartományban, amelyikben szeretné:

| Widget | Méret |
|---|---|
| Naptár | Kicsi |
| Ez a hét · 2 hét | Közepes |
| 3 hét · 4 hét | Nagy |
| Előző hónap · Ez a hónap · Következő hónap | Nagy |

### Kombinációk

Két panel egy widgetben, amikor egyetlen nézet nem elég:

| Widget | Mit mutat | Méret |
|---|---|---|
| MA + Naptár | A mai összefoglaló a havi rács mellett | Közepes |
| Események + Naptár | A közelgő események a havi rács mellett | Közepes |
| Események + Legfontosabb | A közelgő események a kitűzött eseménye mellett | Közepes |
| Naptár + Naptár | Két hónap egymás mellett | Közepes |

### Hozzáadás AI-val

Egyetlen koppintás egyenesen az [AI gyorsbevitelhez](./02-ai-input.md).

*Zárolási képernyős kör alakú · Kicsi.*

---

## Mit tehet egy widgetből

- **Feladat kipipálása** — koppintson a körre bármelyik feladatnál a widgetben, és befejeződik, anélkül hogy megnyitná az alkalmazást.
- **Átkoppintás az eseményre** — egy eseményre koppintva egyenesen a részletei képernyő nyílik meg.
- **Szűrés eseménytípus szerint** — nyomja hosszan a widgetet, válassza a Widget szerkesztése lehetőséget, és korlátozza adott eseménytípusokra. A saját típusai és a csatlakoztatott külső naptárak egyaránt megjelennek a választóban.

---

## Zárolási képernyő

### Zárolási képernyős widgetek

Több widgetnek van zárolási képernyős formája: **Következő esemény** (beágyazott és téglalap alakú), **A mai nap következő eseményei** (téglalap alakú), **Legfontosabb esemény** (beágyazott) és **Hozzáadás AI-val** (kör alakú).

### Élő tevékenység visszaszámlálás

Tegyen ki egy eseményt a zárolási képernyőjére, és nézze, ahogy visszaszámlál a hátralévő idő — ugyanez a nézet a Dynamic Islandben is látszik. Válassza a **Megjelenítés a zárolási képernyőn** lehetőséget az esemény további műveletek menüjéből.

- A következő 8 órán belül kezdődő eseményeknél érhető el.
- Egyszerre egy esemény — ha újat választ, megkérdezi, lecserélje-e a jelenlegit.
- A feladatok közvetlenül az Élő tevékenységből is befejezhetők.

---

## Vezérlőközpont

iOS 18 és újabb rendszeren hozzáadhatja a **Hozzáadás AI-val** vezérlőt a Vezérlőközponthoz, így egy lehúzás és egy koppintás bárhonnan elviszi az AI-beviteli képernyőre.

---

## Megjelenés

A widgetek alapból a rendszer világos/sötét beállítását követik, vagy rögzítheti őket egy tetszőleges háttérszínre — az alkalmazás automatikusan olvasható szövegszínt választ aszerint, hogy az a szín mennyire világos. A **Beállítások › Megjelenés › Widget témája** menüpontban állíthatja be. Lásd: [Személyre szabás](./05-personalization.md).

A widgetek a nap folyamán maguktól frissülnek, és rögtön frissülnek azután is, hogy megváltoztat valamit az alkalmazásban.

---

[← Tartalom](./README.md) · [Következő: Külső naptárak →](./04-external-calendars.md)
