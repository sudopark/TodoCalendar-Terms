# 1. Osnove

[← Sadržaj](./README.md)

---

## Kalendar

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/calendar.png" alt="Kalendar" width="280">

Mjesečna mreža je početni zaslon. Povlačite lijevo i desno za promjenu mjeseca, a dodirom na dan otvarate popis njegovih događaja ispod.

- Svaki dan prikazuje obojenu crticu po događaju te oznaku **+N** kad ih ima više nego što stane.
- Redoslijed dnevnog popisa: zadaci bez vremena → zadaci s vremenom → termini → blagdani → događaji vanjskih kalendara.
- Dodirnite zaglavlje da skočite na bilo koji datum ili odaberite **Pomakni datum** i upišite ga izravno.

Koliko je mreža gusta — visina retka, veličina teksta događaja, podebljani tekst, obojene crtice, nazivi blagdana, lunarni kalendar — sve se može mijenjati. Pogledajte [Personalizaciju](./05-personalization.md).

---

## Zadaci i termini

Aplikacija ima dvije vrste događaja, a razlika je u tome može li se stvar *dovršiti*.

| | Zadatak | Termin |
|---|---|---|
| Vrijeme | Neobavezno | Obavezno |
| Dovršavanje | Da — označite kvačicom | Ne |
| Bez vremena | Ostaje u popisu **Trenutni popis zadataka** dok ga ne dovršite | Nije moguće |

**Zadatak bez vremena** je za nešto što morate obaviti uskoro, ali još niste odredili kada. Stoji na vrhu kalendara i u widgetu Trenutni popis zadataka dok ne bude gotov.

Pretvorbu možete napraviti u oba smjera i bilo kada — **Pretvori u termin** / **Pretvori u zadatak** iz izbornika s više radnji na događaju. Za pretvaranje zadatka u termin potrebno je vrijeme.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/event-detail.png" alt="Detalji događaja" width="280">

Svaki događaj može nositi **Lokaciju** (s pregledom karte i otvaranjem u vašoj omiljenoj aplikaciji za karte jednim dodirom), **Poveznicu** s pregledom i **Bilješku**.

---

## Dodavanje događaja

Tri načina, ovisno o tome koliko želite tipkati:

- **Brzo dodavanje** — polje za unos na dnu dnevnog popisa. Upišite naziv, potvrdite i imate zadatak.
- **Puni detalji** — dodirnite **+** da otvorite uređivač s vremenom, ponavljanjem, podsjetnicima, tipom događaja, lokacijom, poveznicom i bilješkom.
- **Brzi AI unos** — opišite ga običnim riječima i pustite aplikaciju da složi događaj. Pogledajte [Brzi AI unos](./02-ai-input.md).

Zadatku treba samo naziv. Terminu trebaju naziv i vrijeme.

---

## Ponavljajući događaji

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/repeat-options.png" alt="Opcije ponavljanja" width="240">

Umjesto da od vas traži slaganje pravila iz padajućih izbornika, aplikacija čita datum koji ste odabrali i nudi gotove opcije za njega. Odaberite četvrtak i na popisu doslovno piše **Svaki Četvrtak** i **Treći Četvrtak svakog mjeseca**.

**Uobičajeni intervali**

- Svaki dan
- Svaki tjedan · Svaka 2 tjedna · Svaka 3 tjedna · Svaka 4 tjedna — na isti dan u tjednu kao i događaj
- Svaki mjesec — na isti datum svakog mjeseca
- Svake godine
- Svake godine (lunarni kalendar) — za rođendane i godišnjice koje se prate po lunarnom kalendaru

**Po položaju u mjesecu**

- Svaki radni dan — od ponedjeljka do petka. Nudi se kad događaj počinje radnim danom
- Svi dani zadnjeg tjedna svakog mjeseca
- Prvi / Drugi / Treći / Četvrti / Zadnji *dan u tjednu* svakog mjeseca — za stvari poput „zadnjeg petka u mjesecu”

**Kraj ponavljanja**

Kad odaberete ponavljanje, odredite i kako prestaje: **Nikada**, **Na dan** određenog datuma ili **Nakon** određenog broja ponavljanja.

Ponavljajući zadaci ponašaju se drugačije od ponavljajućih termina:

- Nedovršeno ponavljanje ostaje vidljivo u današnjem kalendaru i nakon što mu vrijeme prođe — ne prelazi tiho na sljedeće.
- Dovršavanje sprema to ponavljanje među dovršene zadatke i stvara sljedeće.
- **Preskoči ovaj zadatak** vodi vas na sljedeće ponavljanje bez označavanja kao dovršeno.
- Kad ponavljanje ima uvjet završetka i nema sljedećeg ponavljanja, serija završava.

Kad uređujete ili brišete jedno ponavljanje ponavljajućeg događaja, birate opseg: **Samo ovaj put**, **Od sada** ili **Svi događaji**.

Za događaje na povezanom vanjskom kalendaru lunarna opcija se ne nudi — taj je kalendar nema kako izraziti.

---

## Tipovi događaja i boje

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/event-type-list.png" alt="Tipovi događaja" width="280">

Tipovi događaja su vaše kategorije i nose boju kojom se događaj prikazuje u kalendaru. Stvorite ih koliko god želite, svaki sa svojom bojom.

- Isključite tip da sakrijete svaki događaj tog tipa iz kalendara — zgodno kad želite utišati pretrpan poslovni kalendar bez prekidanja veze.
- Pri brisanju tipa možete zadržati ili obrisati događaje koji su uz njega vezani.
- Postavite **Zadani tip događaja** pa novi događaji odmah završe na pravom mjestu bez biranja svaki put.

Blagdani i povezani vanjski kalendari dobivaju vlastite tipove, pa i njih možete sakriti neovisno.

---

## Podsjetnici

Postavite koliko god podsjetnika po događaju trebate.

- **Događaji s vremenom** — u vrijeme događaja ili 1 / 5 / 10 / 15 / 30 minuta, 1 / 2 sata, 1 / 2 / 7 dana prije.
- **Cjelodnevni događaji** — u 9:00 ili u podne tog dana, ili u 9:00 jedan / dva / sedam dana ranije.
- **Prilagođeno vrijeme** — odaberite bilo koji pomak koji želite.

Zadane vrijednosti za događaje s vremenom i za cjelodnevne postavljaju se odvojeno u Postavkama, pa novi događaji dolaze već pripremljeni. Podsjetnici trebaju dozvolu za obavijesti; ako je isključena, aplikacija vas uputi na postavke sustava.

---

## Najvažniji događaj

Prikvačite onu jednu stvar koju ne smijete propustiti. Najvažniji događaj ostaje na vrhu kalendara bez obzira na to koji datum gledate i ima vlastiti widget.

Kao najvažniji se mogu postaviti zadaci i termini koji se ne ponavljaju. Ponavljajući termini ne mogu.

---

## Nedovršeni zadaci

Zadaci kojima je vrijeme prošlo, a nisu dovršeni, skupljaju se u odjeljku **Nedovršeni zadaci** na vrhu kalendara, pa propuštena stavka ne odluta izvan vidokruga u prošli tjedan.

Zadaci bez vremena i budući zadaci ne broje se kao nedovršeni — jednostavno im rok još nije stigao. Ako ih radije ne biste gledali, cijeli odjeljak možete sakriti u Postavkama.

---

## Dovršeni zadaci

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/done-todos.png" alt="Dovršeni zadaci" width="280">

Sve što označite kvačicom ostaje sačuvano, grupirano prema tome kad ste to dovršili — danas, jučer, ovaj mjesec, a zatim po mjesecima i godinama.

- Poništite dovršenje da vratite zadatak natrag.
- Počistite skupno: obrišite sve ili sve starije od 1 / 3 / 6 mjeseci ili godine dana.

---

## Dijeljenje

Podijelite **dan, tjedan ili mjesec** kao tekst ili kao sliku.

Prije dijeljenja možete filtrirati koje tipove događaja uključiti i odabrati hoće li se prikazati nazivi tipova, pa nekome možete poslati svoj tjedan bez otkrivanja svega što je u njemu.

---

[← Sadržaj](./README.md) · [Sljedeće: Brzi AI unos →](./02-ai-input.md)
