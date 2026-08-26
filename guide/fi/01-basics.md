# 1. Perusteet

[← Sisällys](./README.md)

---

## Kalenterinäkymä

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fi/calendar.png" alt="Kalenteri" width="280">

Kuukausikalenteri on sovelluksen aloitusnäkymä. Pyyhkäise vasemmalle ja oikealle vaihtaaksesi kuukautta, ja napauta päivää avataksesi sen tapahtumaluettelon alapuolelle.

- Jokaisella päivällä näkyy värillinen palkki kutakin tapahtumaa kohden ja **+N**-merkintä silloin, kun päivällä on enemmän tapahtumia kuin riville mahtuu.
- Päivän luettelon järjestys on: ajattomat tehtävät → ajastetut tehtävät → aikataulutapahtumat → vapaapäivät → ulkoisten kalenterien tapahtumat.
- Napauta otsikkoa hypätäksesi mihin tahansa päivään, tai valitse päivä suoraan **Siirrä päivämäärää** -toiminnolla.

Kuinka paljon kukin päivä näyttää, on sinun päätettävissäsi: tapahtumakohtaisen tiedon määrä, tekstin koko, värit, vapaapäivien nimet ja kuukalenteri. [Mukauttaminen](./05-personalization.md) käy jokaisen asetuksen läpi nimeltä.

---

## Tehtävät ja aikataulutapahtumat

Sovelluksessa on kahdenlaisia tapahtumia, ja ero on siinä, onko kyse asiasta, jonka kuittaat valmiiksi.

| | Tehtävä | Aikataulutapahtuma |
|---|---|---|
| Aika | Valinnainen | Pakollinen |
| Valmiiksi merkitseminen | Kyllä — merkitse valmiiksi | Ei |
| Ilman aikaa | Pysyy **Nykyinen tehtäväluettelo** -osiossa, kunnes teet sen | Ei mahdollista |

**Ajaton tehtävä** on sitä varten, mikä pitää tehdä pian mutta jota et ole vielä aikatauluttanut. Se pysyy kalenterin ylälaidassa ja Nykyinen tehtäväluettelo -widgetissä, kunnes se on tehty.

Voit muuntaa tapahtuman kumpaan tahansa suuntaan milloin tahansa — **Muunna aikatauluksi** / **Muunna tehtäväksi** tapahtuman lisävalikosta. Tehtävän muuntaminen aikataulutapahtumaksi edellyttää ajankohtaa.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fi/event-detail.png" alt="Tapahtuman tiedot" width="280">

Jokaisessa tapahtumassa voi olla **sijainti**, **linkki** ja **muistiinpano**. Sijainnista näkyy karttaesikatselu, ja yksi napautus avaa sen haluamassasi karttasovelluksessa; linkillä on oma esikatselunsa.

---

## Tapahtumien lisääminen

Kolme tapaa lisätä tapahtuma, sen mukaan kuinka paljon haluat kirjoittaa:

- **Nopea lisäys** — päivän luettelon alalaidassa oleva syöttökenttä. Kirjoita nimi, paina rivinvaihtoa, ja tehtävä on luotu.
- **Täydet tiedot** — napauta **+** avataksesi muokkausnäkymän, jossa ovat aika, toisto, muistutukset, tapahtumatyyppi, sijainti, linkki ja muistiinpano.
- **AI-pikasyöttö** — kuvaile asia tavallisin sanoin ja anna sovelluksen rakentaa tapahtuma. Katso [AI-pikasyöttö](./02-ai-input.md).

Tehtävä tarvitsee vain nimen. Aikataulutapahtuma tarvitsee nimen ja ajankohdan.

---

## Toistuvat tapahtumat

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fi/repeat-options.png" alt="Toistovaihtoehdot" width="240">

Sen sijaan, että sinun pitäisi koota toistosääntö pudotusvalikoista, sovellus lukee valitsemasi päivän ja tarjoaa sille valmiita vaihtoehtoja. Valitse torstai, ja lista tarjoaa vaihtoehdot **Joka torstai** ja **Kuukauden kolmas torstai**.

**Tavalliset välit**

- Joka päivä
- Joka viikko · Joka 2. viikko · Joka 3. viikko · Joka 4. viikko — samana viikonpäivänä kuin tapahtuma
- Joka kuukausi — samana päivänä joka kuukausi
- Joka vuosi
- Joka vuosi (kuukalenteri) — syntymäpäiville ja vuosipäiville, joita vietetään kuukalenterin mukaan

**Järjestyksen mukaan kuukaudessa**

- Jokaisena arkipäivänä — maanantaista perjantaihin. Tarjolla silloin, kun tapahtuma alkaa arkipäivänä
- Kuukauden viimeisen viikon kaikki päivät
- Kuukauden ensimmäinen / toinen / kolmas / neljäs / viimeinen **torstai** — viikonpäivä tulee valitsemastasi päivästä, joten perjantain tapahtumalle tarjotaan **Kuukauden viimeinen perjantai**

**Toisto päättyy**

Kun olet valinnut toiston, valitse milloin se loppuu: **Ei koskaan** jättää toiston jatkumaan rajattomasti, **Päivänä** asettaa kiinteän päättymispäivän ja **Kun toistoja** rajaa toistokerrat tiettyyn määrään.

Toistuvat tehtävät käyttäytyvät eri tavalla kuin toistuvat aikataulutapahtumat:

- Keskeneräinen toisto pysyy näkyvissä tämän päivän kalenterissa, vaikka sen ajankohta menisi ohi — se ei siirry itsestään seuraavaan toistoon.
- Kun merkitset sen valmiiksi, kyseinen toisto siirtyy valmiiden tehtävien luetteloon ja seuraava toisto luodaan.
- **Ohita tämä tehtävä** siirtää sinut seuraavaan toistoon merkitsemättä tehtävää valmiiksi.
- Kun toistolla on päättymisehto eikä seuraavaa toistoa ole, sarja päättyy.

Kun muokkaat tai poistat toistuvan tapahtuman yhtä kertaa, valitset laajuuden: **Vain tämä kerta**, **Tästä hetkestä alkaen** tai **Kaikki tapahtumat**.

Yhdistetyn ulkoisen kalenterin tapahtumille kuukalenterivaihtoehtoa ei tarjota — ulkoisissa kalentereissa ei ole paikkaa, johon kuukalenterin toistosäännön voisi tallentaa.

---

## Tapahtumatyypit ja värit

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fi/event-type-list.png" alt="Tapahtumatyypit" width="280">

Tapahtumatyypit ovat omia luokkiasi, ja ne kantavat värin, jolla tapahtuma näkyy kalenterissa. Luo niitä niin monta kuin haluat, kullekin oma värinsä.

- Kytke tyyppi pois piilottaaksesi kaikki sen tyypin tapahtumat kalenterista — kätevä tapa vaimentaa kiireinen työkalenteri katkaisematta sen yhteyttä.
- Tyyppiä poistaessasi voit joko säilyttää siihen liitetyt tapahtumat tai poistaa nekin.
- Aseta **Oletustapahtumatyyppi**, niin uudet tapahtumat päätyvät oikeaan paikkaan ilman että valitset tyypin joka kerta.

Vapaapäivillä ja yhdistetyillä ulkoisilla kalentereilla on omat tyyppinsä, joten myös ne voi piilottaa erikseen.

---

## Muistutukset

Aseta tapahtumalle niin monta muistutusta kuin tarvitset.

- **Ajastetut tapahtumat** — tapahtuman alkaessa, tai 1 / 5 / 10 / 15 / 30 minuuttia, 1 / 2 tuntia tai 1 / 2 / 7 päivää ennen tapahtumaa.
- **Koko päivän tapahtumat** — klo 9 tai keskipäivällä samana päivänä, tai klo 9.00 1 / 2 / 7 päivää etukäteen.
- **Mukautettu ajankohta** — valitse haluamasi ajankohta itse.

Ajastettujen ja koko päivän tapahtumien oletukset asetetaan erikseen Asetuksissa, joten uusissa tapahtumissa muistutus on valmiina. Muistutukset vaativat ilmoitusluvan; jos se on pois päältä, sovellus ohjaa sinut iOS:n asetuksiin.

---

## Tärkein tapahtuma

Kiinnitä se yksi asia, jota et voi jättää väliin. Tärkein tapahtuma pysyy kalenterin ylimpänä riippumatta siitä, mitä päivää katsot, ja sillä on oma widget.

Tehtävät ja toistumattomat aikataulutapahtumat voi asettaa tärkeimmäksi. Toistuvia aikataulutapahtumia ei voi.

---

## Keskeneräiset tehtävät

Tehtävät, joiden ajankohta on jo mennyt ilman että ne on merkitty valmiiksi, kootaan kalenterin ylälaidan **Keskeneräiset tehtävät** -osioon, jottei unohtunut tehtävä jää piiloon menneelle päivälle.

Ajattomia ja tulevia tehtäviä ei lasketa keskeneräisiksi — ne eivät yksinkertaisesti ole vielä erääntyneet. Voit piilottaa osion kokonaan Asetuksista, jos et halua nähdä sitä.

---

## Valmiit tehtävät

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fi/done-todos.png" alt="Valmiit tehtävät" width="280">

Kaikki valmiiksi merkitsemäsi säilytetään ja ryhmitellään valmistumisajan mukaan — tänään, eilen, tämä kuukausi ja sen jälkeen kuukausittain ja vuosittain.

- Kumoa valmiiksi merkintä palauttaaksesi tehtävän.
- Siivoa kerralla: poista kaikki, tai kaikki yli 1 / 3 / 6 kuukautta tai vuoden vanhat.

---

## Jakaminen

Jaa **päivä, viikko tai kuukausi** tekstinä tai kuvakorttina.

Ennen jakamista voit suodattaa mukaan tulevat tapahtumatyypit ja valita, näkyvätkö tyyppien nimet — niin voit lähettää jollekulle viikkosi paljastamatta kaikkea siinä.

---

[← Sisällys](./README.md) · [Seuraava: AI-pikasyöttö →](./02-ai-input.md)
