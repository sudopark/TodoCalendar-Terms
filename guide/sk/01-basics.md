# 1. Základy

[← Obsah](./README.md)

---

## Kalendár

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/calendar.png" alt="Kalendár" width="280">

Mesačná mriežka je domovská obrazovka. Potiahnutím doľava a doprava sa presúvate medzi mesiacmi, klepnutím na deň sa pod ním otvorí zoznam jeho udalostí.

- Pri každom dni je farebný pruh za každú udalosť a značka **+N**, keď sa ich viac nezmestí.
- Denný zoznam má poradie: úlohy bez času → úlohy s časom → termíny → sviatky → udalosti z externých kalendárov.
- Klepnutím na hlavičku preskočíte na ľubovoľný dátum, alebo si ho vyberte priamo cez **Presunúť dátum**.

Ako hustá mriežka bude — výška riadka, veľkosť písma udalostí, tučný text, farebné pruhy, názvy sviatkov, lunárny kalendár — sa dá celé prepnúť. Pozrite si [Prispôsobenie](./05-personalization.md).

---

## Úlohy a termíny

Aplikácia má dva druhy udalostí a rozdiel je v tom, či sa daná vec dá *splniť*.

| | Úloha | Termín |
|---|---|---|
| Čas | Voliteľný | Povinný |
| Splnenie | Áno — odškrtnete ju | Nie |
| Bez času | Zostáva v sekcii **Aktuálny zoznam úloh**, kým ju nedokončíte | Nie je možné |

**Úloha bez času** je na niečo, čo treba urobiť čoskoro, ale ešte to nemá svoj termín. Zostáva navrchu kalendára a vo widgete Aktuálny zoznam úloh, kým ju nesplníte.

Kedykoľvek môžete prevádzať oboma smermi — **Zmeniť na termín** / **Zmeniť na úlohu** v ponuke ďalších možností udalosti. Na prevod úlohy na termín je potrebný čas.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/event-detail.png" alt="Detail udalosti" width="280">

Každá udalosť môže niesť **miesto** (s náhľadom mapy a otvorením v obľúbenej mapovej aplikácii jedným klepnutím), **odkaz** s náhľadom a **poznámku**.

---

## Pridávanie udalostí

Tri cesty dnu, podľa toho, koľko toho chcete napísať:

- **Rýchle pridanie** — vstupné pole naspodku denného zoznamu. Napíšte názov, potvrďte a máte úlohu.
- **Podrobné zadanie** — klepnutím na **+** otvoríte editor s časom, opakovaním, upozorneniami, typom udalosti, miestom, odkazom a poznámkou.
- **Rýchle zadávanie AI** — opíšte to bežnou rečou a aplikácia udalosť zostaví za vás. Pozrite si [Rýchle zadávanie AI](./02-ai-input.md).

Úloha potrebuje iba názov. Termín potrebuje názov a čas.

---

## Opakujúce sa udalosti

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/repeat-options.png" alt="Možnosti opakovania" width="240">

Namiesto skladania pravidla z rozbaľovacích ponúk aplikácia prečíta dátum, ktorý ste vybrali, a ponúkne k nemu hotové možnosti. Vyberte štvrtok a v zozname doslova stojí **Každý štvrtok** a **Tretí štvrtok každého mesiaca**.

**Bežné intervaly**

- Každý deň
- Každý týždeň · Každých 2 týždňov · Každých 3 týždňov · Každých 4 týždňov — v ten istý deň v týždni ako udalosť
- Každý mesiac — v ten istý dátum každého mesiaca
- Každý rok
- Každý rok (lunárny kalendár) — pre narodeniny a výročia držané podľa lunárneho kalendára

**Podľa pozície v mesiaci**

- Každý pracovný deň — od pondelka do piatka. Ponúkne sa, keď sa udalosť začína v pracovný deň
- Všetky dni posledného týždňa každého mesiaca
- Prvý / Druhý / Tretí / Štvrtý / Posledný *deň v týždni* každého mesiaca — na veci ako „posledný piatok v mesiaci“

**Koniec opakovania**

Keď si vyberiete opakovanie, zvoľte, ako sa skončí: **Nikdy**, **Dňa** ku konkrétnemu dátumu, alebo **Po** určitom počte výskytov.

Opakujúce sa úlohy sa správajú inak ako opakujúce sa termíny:

- Nesplnené opakovanie zostáva viditeľné v dnešnom kalendári aj po tom, čo jeho čas uplynie — nepresunie sa potichu dopredu.
- Splnením sa daný výskyt zaradí medzi splnené úlohy a vytvorí sa ďalší.
- **Preskočiť túto úlohu** vás posunie na ďalší výskyt bez toho, aby sa označila ako splnená.
- Keď má opakovanie podmienku konca a ďalší výskyt už neexistuje, séria sa skončí.

Keď upravujete alebo mažete jeden výskyt opakujúcej sa udalosti, vyberáte si rozsah: **Iba tentokrát**, **Od teraz**, alebo **Všetky udalosti**.

Pri udalostiach z pripojeného externého kalendára sa lunárna možnosť neponúka — taký kalendár ju nevie vyjadriť.

---

## Typy udalostí a farby

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/event-type-list.png" alt="Typy udalostí" width="280">

Typy udalostí sú vaše kategórie a nesú farbu, ktorou sa udalosť zobrazí v kalendári. Vytvorte si ich, koľko chcete, každý s vlastnou farbou.

- Vypnutím typu skryjete z kalendára všetky udalosti daného typu — hodí sa na stíšenie rušného pracovného kalendára bez toho, aby ste ho odpojili.
- Pri mazaní typu si vyberiete, či si súvisiace udalosti ponecháte, alebo ich odstránite.
- Nastavte si **Predvolený typ udalosti**, aby nové udalosti padali na správne miesto a nemuseli ste ho vyberať zakaždým.

Sviatky aj pripojené externé kalendáre majú vlastné typy, takže ich viete skrývať nezávisle.

---

## Upozornenia

Ku každej udalosti si nastavte toľko upozornení, koľko potrebujete.

- **Udalosti s časom** — v čase udalosti, alebo 1 / 5 / 10 / 15 / 30 minút, 1 / 2 hodiny, 1 / 2 / 7 dní pred ňou.
- **Celodenné udalosti** — o 9:00 alebo na obed v daný deň, prípadne o 9:00 1 / 2 / 7 dní vopred.
- **Vlastný čas** — vyberte si ľubovoľný odstup.

Predvolené hodnoty pre udalosti s časom a pre celodenné udalosti sa v Nastaveniach určujú osobitne, takže nové udalosti prídu už pripravené. Upozornenia potrebujú povolenie na upozornenia; ak je vypnuté, aplikácia vás nasmeruje do Nastavení iOS.

---

## Najdôležitejšia udalosť

Pripnite si tú jednu vec, ktorú si nesmiete nechať ujsť. Najdôležitejšia udalosť zostáva navrchu kalendára bez ohľadu na to, na ktorý dátum sa práve pozeráte, a má vlastný widget.

Ako najdôležitejšie sa dajú nastaviť úlohy a neopakujúce sa termíny. Opakujúce sa termíny nie.

---

## Nesplnené úlohy

Úlohy, ktorým už uplynul čas a neboli splnené, sa zbierajú v sekcii **Nesplnené úlohy** navrchu kalendára, takže zmeškaná vec neodroluje z dohľadu do minulého týždňa.

Úlohy bez času a budúce úlohy sa medzi nesplnené nerátajú — jednoducho ešte nie sú po termíne. Ak túto sekciu nechcete vidieť, v Nastaveniach ju môžete celú skryť.

---

## Splnené úlohy

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/done-todos.png" alt="Splnené úlohy" width="280">

Všetko, čo odškrtnete, sa uchová a zoskupí podľa toho, kedy ste to dokončili — dnes, včera, tento mesiac a ďalej po mesiacoch a rokoch.

- Vrátením dokončenia späť sa úloha vráti medzi nesplnené.
- Upratujte aj hromadne: odstráňte všetko, alebo všetko staršie ako 1 / 3 / 6 mesiacov či rok.

---

## Zdieľanie

Zdieľajte **deň, týždeň alebo mesiac** ako text alebo ako obrázkovú kartu.

Pred zdieľaním si viete vyfiltrovať, ktoré typy udalostí sa zahrnú, a určiť, či sa majú zobraziť aj ich názvy — takže niekomu pošlete svoj týždeň bez toho, aby ste odhalili všetko v ňom.

---

[← Obsah](./README.md) · [Ďalej: Rýchle zadávanie AI →](./02-ai-input.md)
