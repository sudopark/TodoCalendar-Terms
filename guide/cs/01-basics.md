# 1. Základy

[← Obsah](./README.md)

---

## Kalendář

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/calendar.png" alt="Kalendář" width="280">

Měsíční mřížka je domovská obrazovka. Přejetím doleva a doprava se posouváte mezi měsíci, klepnutím na den se pod ním otevře seznam jeho událostí.

- U každého dne se zobrazí barevný proužek za každou událost a k tomu ukazatel **+N**, když se jich nevejde tolik, kolik jich je.
- Seznam dne je řazený takto: úkoly bez času → úkoly s časem → termíny → svátky → události z externích kalendářů.
- Klepnutím na záhlaví přeskočíte na libovolné datum, nebo si ho vyberte přímo přes **Přesunout datum**.

Jak hustá mřížka bude — výška řádku, velikost písma událostí, tučný text, barevné proužky, názvy svátků, lunární kalendář — se dá všechno přepnout. Viz [Přizpůsobení](./05-personalization.md).

---

## Úkoly a termíny

Aplikace zná dva druhy událostí a rozdíl je v tom, jestli se ta věc dá *dokončit*.

| | Úkol | Termín |
|---|---|---|
| Čas | Volitelný | Povinný |
| Dokončení | Ano — odškrtnete ho | Ne |
| Bez času | Zůstává v sekci **Aktuální seznam úkolů**, dokud ho nedokončíte | Není možné |

**Úkol bez času** je pro něco, co potřebujete udělat brzy, ale ještě jste to nenaplánovali. Zůstává nahoře v kalendáři a ve widgetu Aktuální seznam úkolů, dokud ho nedokončíte.

Kdykoli můžete převádět oběma směry — **Převést na termín** / **Převést na úkol** v nabídce dalších akcí u události. K převodu úkolu na termín jsou potřeba informace o čase.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/event-detail.png" alt="Detail události" width="280">

Každá událost může nést **místo** (s náhledem mapy a otevřením ve vaší oblíbené mapové aplikaci jedním klepnutím), **odkaz** s náhledem a **poznámku**.

---

## Přidávání událostí

Tři cesty dovnitř podle toho, kolik toho chcete psát:

- **Rychlé přidání** — vstupní pole dole pod seznamem dne. Napíšete název, potvrdíte a máte úkol.
- **Podrobné zadání** — klepnutím na **+** otevřete editor s časem, opakováním, připomenutími, typem události, místem, odkazem a poznámkou.
- **Rychlé zadávání AI** — popište to běžnou řečí a aplikace událost sestaví za vás. Viz [Rychlé zadávání AI](./02-ai-input.md).

Úkolu stačí název. Termín potřebuje název a čas.

---

## Opakující se události

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/repeat-options.png" alt="Možnosti opakování" width="240">

Místo aby po vás aplikace chtěla poskládat pravidlo z rozbalovacích nabídek, přečte si datum, které jste vybrali, a nabídne k němu hotové možnosti. Vyberte čtvrtek a v seznamu doslova stojí **Každé Čtvrtek** a **Třetí Čtvrtek každého měsíce**.

**Běžné intervaly**

- Každý den
- Každý týden · Každých 2 týdnů · Každých 3 týdnů · Každých 4 týdnů — ve stejný den v týdnu jako událost
- Každý měsíc — vždy na stejné datum v měsíci
- Každý rok
- Každý rok (lunární kalendář) — pro narozeniny a výročí držená podle lunárního kalendáře

**Podle pozice v měsíci**

- Každý pracovní den — od pondělí do pátku. Nabízí se, když událost začíná v pracovní den
- Všechny dny posledního týdne každého měsíce
- První / Druhý / Třetí / Čtvrtý / Poslední *den v týdnu* každého měsíce — na věci typu „poslední pátek v měsíci“

**Konec opakování**

Jakmile vyberete opakování, zvolte, jak skončí: **Nikdy**, **Dne** ke konkrétnímu datu, nebo **Po** zadaném počtu **výskytech**.

Opakující se úkoly se chovají jinak než opakující se termíny:

- Nedokončené opakování zůstává vidět v dnešním kalendáři i poté, co jeho čas uplyne — nepřeskočí tiše dál.
- Když ho dokončíte, dané opakování se zařadí mezi dokončené úkoly a vytvoří se další.
- **Přeskočit tento úkol** vás posune na další opakování, aniž by se označilo za dokončené.
- Když má opakování podmínku konce a další opakování už neexistuje, série skončí.

Když upravujete nebo mažete jedno opakování opakující se události, vyberete si rozsah: **Pouze tentokrát**, **Od nynějška**, nebo **Všechny události**.

U událostí z připojeného externího kalendáře se lunární možnost nenabízí — takový kalendář ji nemá jak vyjádřit.

---

## Typy událostí a barvy

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/event-type-list.png" alt="Typy událostí" width="280">

Typy událostí jsou vaše kategorie a nesou barvu, kterou událost v kalendáři dostane. Vytvořte si jich, kolik chcete, každý s vlastní barvou.

- Vypnutím typu skryjete z kalendáře všechny události toho typu — hodí se, když chcete ztišit nabitý pracovní kalendář, aniž byste ho odpojili.
- Při mazání typu si vyberete, jestli související události zachovat, nebo smazat s ním.
- Nastavte si **Výchozí typ události**, aby nové události padaly na správné místo a vy ho nemuseli pokaždé vybírat.

Svátky a připojené externí kalendáře mají vlastní typy, takže i je můžete skrývat nezávisle.

---

## Připomenutí

K jedné události si nastavte tolik připomenutí, kolik potřebujete.

- **Události s časem** — **V čase události**, nebo 1 / 5 / 10 / 15 / 30 minut, 1 / 2 hodiny, 1 / 2 / 7 dní předem.
- **Celodenní události** — **V 9:00 daného dne** nebo **V poledne daného dne**, případně v 9:00 1 / 2 / 7 dní předem.
- **Vlastní** — vyberte si libovolný okamžik.

Výchozí hodnoty pro události s časem a pro celodenní události se v Nastavení určují zvlášť, takže nové události přicházejí rovnou nastavené. Připomenutí potřebují oprávnění k upozorněním; pokud je vypnuté, aplikace vás nasměruje do Nastavení iOS.

---

## Nejdůležitější událost

Připněte si tu jednu věc, kterou si nesmíte nechat ujít. Nejdůležitější událost zůstává nahoře v kalendáři bez ohledu na to, na jaké datum se zrovna díváte, a má vlastní widget.

Jako nejdůležitější lze nastavit úkoly a neopakující se termíny. Opakující se termíny ne.

---

## Nedokončené úkoly

Úkoly, kterým už uplynul čas a nebyly dokončeny, se sbírají v sekci **Nedokončené úkoly** nahoře v kalendáři, aby propásnutá věc neodrolovala z dohledu do minulého týdne.

Úkoly bez času a úkoly v budoucnu se mezi nedokončené nepočítají — prostě jim termín ještě neuplynul. Pokud tuhle sekci vidět nechcete, dá se v Nastavení úplně skrýt.

---

## Dokončené úkoly

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/done-todos.png" alt="Dokončené úkoly" width="280">

Všechno, co odškrtnete, se uchová a seskupí podle toho, kdy jste to dokončili — **Dnes**, **Včera**, **Tento měsíc** a dál po měsících a letech.

- **Vrátit dokončení zpět** přivede úkol zpátky.
- Ukliďte hromadně: smažte všechno, nebo jen to **Starší než 1 měsíc** / **3 měsíce** / **6 měsíců** / **1 rok**.

---

## Sdílení

Sdílejte **den, týden nebo měsíc** jako **Text**, nebo jako **Obrázek**.

Před sdílením si můžete vyfiltrovat, které typy událostí zahrnout, a rozhodnout, jestli se mají ukázat i jejich názvy — někomu tak pošlete svůj týden, aniž byste odhalili všechno, co v něm je.

---

[← Obsah](./README.md) · [Další: Rychlé zadávání AI →](./02-ai-input.md)
