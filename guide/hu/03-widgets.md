# 3. Widgetek és zárolási képernyő

[← Tartalom](./README.md)

---

A widget azért van, hogy ne kelljen megnyitnia az alkalmazást csak azért, hogy lássa, mi következik. A To-do Calendar bőséges készletet ad, hogy azt választhassa, amelyik illik ahhoz, ahogyan valóban átnézi a napját — egyetlen következő esemény, egy teljes hónap, vagy a feladatlistája koppintható jelölőkkel.

---

## Kezdőképernyős widgetek

### Ma és ami ezután következik

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/widget-today-and-next.png" alt="Ma és ami ezután következik widget" width="360">

Balra a mai dátum és az, ami a mai napból hátravan, jobbra pedig ami következik. Egyetlen másik widget sem mutat ennyit egyszerre.

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

### Visszaszámlálás

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/widget-dday.png" alt="Visszaszámlálás widget" width="200">

Visszaszámlálás egy Ön által kiválasztott eseményig — a neve, a hátralévő napok száma és a dátum.

- **Az esemény kiválasztása** — nyomja hosszan a widgetet, válassza a Widget szerkesztése lehetőséget, és koppintson az **Esemény** elemre. A listában a mai nap körüli programok és ünnepek jelennek meg.
- **Események kitűzése a lista elejére** — válassza a **Hozzáadás a Visszaszámlálás widgethez** lehetőséget egy program további műveletek menüjéből, vagy nyomja hosszan a programot a nap eseménylistájában. A kitűzött események jelennek meg elsőként, amikor legközelebb szerkeszti a widgetet.
- **Ismétlődő programok** — miután kiválasztott egyet, az **Ismétlési forduló** pontban adja meg, melyik alkalomig számoljon vissza.

*Zárolási képernyős kör alakú · téglalap alakú · beágyazott · Kicsi · Közepes.*

### Hónap és hetek

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/widget-month.png" alt="Hónap widget" width="360">

Maga a naptár, abban a tartományban, amelyikben szeretné:

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
| MA + Naptár | A mai összefoglaló a havi naptár mellett | Közepes |
| Események + Naptár | A közelgő események a havi naptár mellett | Közepes |
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

Több widgetnek van zárolási képernyős formája: **Következő esemény** (beágyazott és téglalap alakú), **A mai nap következő eseményei** (téglalap alakú), **Legfontosabb esemény** (beágyazott), **Visszaszámlálás** (kör alakú, téglalap alakú és beágyazott) és **Hozzáadás AI-val** (kör alakú).

### Élő tevékenység visszaszámlálás

Tegyen ki egy eseményt a zárolási képernyőjére, és nézze, ahogy visszaszámlál — ugyanez a nézet a Dynamic Islandben is látszik. Válassza a **Megjelenítés a zárolási képernyőn** lehetőséget az esemény további műveletek menüjéből.

- A következő 8 órán belül kezdődő eseményeknél érhető el.
- Egyszerre egy esemény — válasszon újat, és az alkalmazás megkérdezi, lecserélje-e a jelenlegit.
- A feladatok közvetlenül az Élő tevékenységből is befejezhetők.

---

## Vezérlőközpont

iOS 18 és újabb rendszeren hozzáadhatja a **Hozzáadás AI-val** vezérlőt a Vezérlőközponthoz, így egy lehúzás és egy koppintás bárhonnan elviszi az AI-beviteli képernyőre.

---

## Widgetek testreszabása

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/widget-gallery.png" alt="Widgetgaléria" width="280">

Nyissa meg a **Beállítások › Megjelenés › Widgetgaléria** menüpontot, és láthatja az összes widgetet és a méreteket, amelyekben elérhetők. Válasszon egy widgetet, és koppintson a **Testreszabás** gombra.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hu/widget-style-edit.png" alt="Widget testreszabása" width="280">

- **Részletek** — kapcsolja be vagy ki a widget egyes részeit, például az ünnep nevét, az időzónát vagy az események számát. Hogy mit lehet kikapcsolni, az a widgettől függ.
- **Háttérszín** — hagyja meg **A közös widgettéma követése** beállítást, vagy adjon ennek a stílusnak saját színt vagy fotót.
- **Új stílus** — mentsen el több kinézetet ugyanahhoz a widgethez, mindegyiket saját névvel. A **Duplikálás** segítségével egy másolatból indulhat.

Az előnézet a módosításokkal együtt frissül. Egy stílus használatához nyomja hosszan a widgetet a kezdőképernyőn, válassza a Widget szerkesztése lehetőséget, és válassza ki a stílust a **Widget stílusa** pontban — ugyanannak a widgetnek minden példánya más-más stílust kaphat. Ha töröl egy stílust, az azt használó widgetek visszaállnak az **Alapértelmezett** stílusra.

A zárolási képernyős widgetek megtartják a rendszertől kapott kinézetet.

---

## Megjelenés

A widgetek alapból a rendszer világos/sötét beállítását követik, vagy rögzítheti őket egy tetszőleges háttérszínre — az alkalmazás automatikusan olvasható szövegszínt választ aszerint, hogy az a szín mennyire világos. A **Beállítások › Megjelenés › Widgetgaléria** tetején lévő **Widget témája** pontban állíthatja be. Ha egy stílusnak saját háttérszíne van, az elsőbbséget élvez ezzel szemben. Lásd: [Személyre szabás](./05-personalization.md).

A widgetek a nap folyamán maguktól frissülnek, és rögtön frissülnek azután is, hogy megváltoztat valamit az alkalmazásban.

---

[← Tartalom](./README.md) · [Következő: Külső naptárak →](./04-external-calendars.md)
