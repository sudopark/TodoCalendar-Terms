# 2. Brzi AI unos

[← Sadržaj](./README.md)

---

Opišite običnim riječima što želite i aplikacija to složi umjesto vas — „ručak sa Sarom u petak u podne”, „pomakni zubara na idući utorak”, „označi rublje kao gotovo”. Bez obrazaca, bez biranja datuma s kotačića.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hr/ai-input.png" alt="Brzi AI unos" width="280">

Brzi AI unos zahtijeva prijavljeni račun. Sve ostalo u aplikaciji radi i bez njega.

---

## Što može

- Stvarati zadatke i termine, s vremenom, ponavljanjem i tipom događaja izvedenima iz onoga što ste rekli
- Promijeniti postojeći događaj — pomaknuti ga, preimenovati, promijeniti mu vrijeme
- Dovršiti zadatak ili poništiti dovršenje
- Obrisati događaj
- Obaviti više stvari u jednom zahtjevu („dodaj teretanu u ponedjeljak, srijedu i petak u 7 ujutro”)

---

## Načini slanja zahtjeva

### U aplikaciji

Dodirnite AI gumb na zaslonu kalendara. Otvara se list za unos s dva načina rada između kojih možete prelaziti kad god želite:

- **Glas** — govorite i gledajte kako se prijepis pojavljuje uživo. Treba dozvolu za mikrofon i prepoznavanje govora; ako je bilo koja odbijena, aplikacija nudi otvaranje Postavki ili prelazak na tipkovnicu.
- **Tipkovnica** — upišite. Korisno kad ste negdje gdje ne možete govoriti.

### Iz slike

**Čitaj iz slike** pretvara sliku u događaje. Fotografirajte ili odaberite postojeću sliku iz knjižnice; aplikacija pročita tekst s nje — raspored nastave, plakat za događaj, snimku zaslona poruke — i pokaže vam što je pronašla kako biste ispravili sve što je krivo ispalo prije slanja.

Možete priložiti i uputu koja usmjerava rezultat, npr. „dodaj ovo kao zadatke”. Ako na slici nema čitljivog teksta, aplikacija će vam to reći umjesto da pošalje prazan zahtjev.

### Siri

Recite **„Hej To-do Calendar”** — rade i „Zahtjev u To-do Calendar”, „Pitaj aplikaciju To-do Calendar”, „Pošalji zahtjev aplikaciji To-do Calendar” i „Dodaj pomoću AI u To-do Calendar”. Možete reći i „Todo Calendar”, bez crtice. Siri pita što treba učiniti, a zahtjev se izvršava **u pozadini, bez otvaranja aplikacije**. Siri odgovori „U redu. Obavijestit ću vas kad bude gotovo.”, a kad rezultat bude spreman, dobijete obavijest.

### Gumb Radnja

Dodijelite gumbu Radnja prečac **Pošalji**. Jedan pritisak, izgovorite stvar, gotovo — aplikacija se nikad ne mora pojaviti u prvom planu.

### Widget i Kontrolni centar

- Widget **Dodaj pomoću AI** — widget za početni ili zaključani zaslon koji jednim dodirom otvara zaslon AI unosa.
- **Kontrolni centar** (iOS 18 i noviji) — dodajte istu kontrolu u Kontrolni centar za ulaz povlačenjem prema dolje.

### Izbornik dijeljenja

Podijelite **tekst ili sliku iz bilo koje druge aplikacije** izravno u brzi AI unos aplikacije To-do Calendar. Čitate poruku s detaljima o dogovoru ili gledate plakat u Fotografijama — dodirnite dijeljenje, odaberite To-do Calendar, po želji dodajte uputu i pošaljite.

I zahtjev iz izbornika dijeljenja izvršava se u pozadini. Dobit ćete potvrdu da je poslan, a rezultat provjerite u aplikaciji.

---

## Kako teče zahtjev

1. **Poslano** — vaš zahtjev odlazi. Ako je stigao sa Sirija, gumba Radnja ili iz izbornika dijeljenja, ne morate držati aplikaciju otvorenom.
2. **Obrada u tijeku** — aplikacija prikazuje napredak. Zahtjev možete **zaustaviti** dok traje, ali zaustavljanje odbacuje posao u tijeku i on se ne može nastaviti.
3. **Potvrda, kad je potrebna** — ako bi zahtjev promijenio nešto značajno, aplikacija najprije traži vaše odobrenje i točno pokaže što namjerava učiniti. Postoji odbrojavanje; ako istekne, jednostavno pitajte ponovno.
4. **Naredba dovršena** — rezultat odmah sleti u vaš kalendar, uz sažetak onoga što se promijenilo.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/hr/ai-result.png" alt="Rezultat AI obrade" width="280">

Odjednom se izvršava samo jedan zahtjev. Ako pošaljete drugi dok prvi još čeka vaše odobrenje, aplikacija će vam reći da najprije riješite prvi.

---

## Krediti

Svaki AI zahtjev troši **kredite**, a krediti se obnavljaju svaki dan. Koliko ih je ostalo prikazano je na vrhu zaslona AI unosa, pa uvijek znate na čemu ste prije slanja.

Kad se krediti potroše, brzi AI unos miruje do sljedećeg dnevnog obnavljanja. Sve ostalo u aplikaciji nastavlja raditi.

---

## Dozvole koje može zatražiti

| Dozvola | Za što se koristi |
|---|---|
| Mikrofon + prepoznavanje govora | Glasovni unos |
| Kamera | Fotografiranje za **Čitaj iz slike** |
| Foto knjižnica | Odabir postojeće slike |
| Obavijesti | Javljanje rezultata zahtjeva iz pozadine |

Svaka se traži tek kad prvi put upotrijebite funkciju kojoj treba, a aplikacija radi i bez nje — glasovni unos prelazi na tipkovnicu, unos slikom na tipkanje.

---

[← Sadržaj](./README.md) · [Sljedeće: Widgeti i zaključani zaslon →](./03-widgets.md)
