# 3. Widgetit ja lukitusnäyttö

[← Sisällys](./README.md)

---

Kalenteriwidgetin koko idea on siinä, ettei kalenteria tarvitse avata. To-do Calendarissa on laaja valikoima, joten voit valita sen, joka vastaa omaa tapaasi tarkistaa päiväsi — yksittäinen seuraava tapahtuma, koko kuukausi tai tehtäväluettelo valintaympyröineen.

---

## Home-valikon widgetit

### Tänään ja mitä seuraavaksi

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fi/widget-today-and-next.png" alt="Tänään ja mitä seuraavaksi -widget" width="360">

Vasemmalla tämän päivän päivämäärä ja se, mitä päivästä on jäljellä; oikealla se, mitä on tulossa seuraavaksi. Tiivein yksittäinen näkymä siihen, mitä nyt ja mitä sen jälkeen.

*Keskikokoinen.*

### Tapahtumat

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fi/widget-event-list.png" alt="Tapahtumaluettelo-widget" width="300">

Jatkuva luettelo tulevista tapahtumista päivittäin ryhmiteltynä, mukaan lukien nykyiset tehtäväsi. Kolmessa koossa: mitä isompi, sitä useampi päivä näkyy.

*Pieni · Keskikokoinen · Suuri.*

### TÄNÄÄN

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fi/widget-today.png" alt="TÄNÄÄN-widget" width="200">

Pelkkä tämä päivä — päivämäärä, mahdollinen vapaapäivä ja se, montako tehtävää ja aikataulutapahtumaa sinulla on.

*Pieni.*

### Tärkein tapahtuma

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fi/widget-foremost.png" alt="Tärkein tapahtuma -widget" width="200">

Se yksi tapahtuma, jonka kiinnitit tärkeimmäksi, aina näkyvissä. Katso [Tärkein tapahtuma](./01-basics.md#tärkein-tapahtuma).

*Lukitusnäytön rivi · Pieni · Keskikokoinen.*

### Kuukausi ja viikot

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fi/widget-month.png" alt="Kuukausiwidget" width="360">

Itse kalenteriruudukko haluamallasi aikavälillä:

| Widget | Koko |
|---|---|
| Kalenteri | Pieni |
| Tämä viikko · 2 viikkoa | Keskikokoinen |
| 3 viikkoa · 4 viikkoa | Suuri |
| Edellinen kuukausi · Tämä kuukausi · Seuraava kuukausi | Suuri |

### Yhdistelmät

Kaksi paneelia yhdessä widgetissä silloin, kun yksi näkymä ei riitä:

| Widget | Mitä näyttää | Koko |
|---|---|---|
| TÄNÄÄN + Kalenteri | Päivän yhteenveto kuukausiruudukon vierellä | Keskikokoinen |
| Tapahtumat + Kalenteri | Tulevat tapahtumat kuukausiruudukon vierellä | Keskikokoinen |
| Tapahtumat + Tärkein | Tulevat tapahtumat kiinnittämäsi tapahtuman vierellä | Keskikokoinen |
| Kalenteri + Kalenteri | Kaksi kuukautta rinnakkain | Keskikokoinen |

### Lisää AI:lla

Yhdellä napautuksella suoraan [AI-pikasyöttöön](./02-ai-input.md).

*Lukitusnäytön ympyrä · Pieni.*

---

## Mitä widgetistä voi tehdä

- **Merkitse tehtävä valmiiksi** — napauta widgetissä olevan tehtävän ympyrää, niin se valmistuu avaamatta sovellusta.
- **Siirry tapahtumaan** — tapahtumaa napauttamalla se avautuu suoraan tietonäkymäänsä.
- **Suodata tapahtumatyypin mukaan** — paina widgetiä pitkään, valitse widgetin muokkaus ja rajaa se tiettyihin tapahtumatyyppeihin. Valitsimessa näkyvät sekä omat tyyppisi että yhdistetyt ulkoiset kalenterit.

---

## Lukitusnäyttö

### Lukitusnäytön widgetit

Useilla widgeteillä on lukitusnäytön muoto: **Seuraava tapahtuma** (rivi ja suorakulmio), **Tämän päivän tulevat tapahtumat** (suorakulmio), **Tärkein tapahtuma** (rivi) ja **Lisää AI:lla** (ympyrä).

### Live-toiminnon lähtölaskenta

Nosta tapahtuma lukitusnäytöllesi ja katso, kuinka aika siihen vähenee; sama näkymä on myös Dynamic Islandissa. Valitse tapahtuman lisävalikosta **Näytä lukitusnäytöllä**.

- Käytettävissä tapahtumille, jotka alkavat seuraavan 8 tunnin sisällä.
- Yksi tapahtuma kerrallaan — uutta valitessasi sovellus kysyy, korvataanko nykyinen.
- Tehtävät voi merkitä valmiiksi suoraan Live-toiminnosta.

---

## Ohjauskeskus

iOS 18:ssa ja uudemmissa voit lisätä **Lisää AI:lla** -säätimen Ohjauskeskukseen, jolloin pääset AI-syöttönäkymään mistä tahansa pyyhkäisemällä alas ja napauttamalla kerran.

---

## Ulkoasu

Widgetit noudattavat oletuksena järjestelmän vaalea/tumma-asetusta, tai voit kiinnittää ne valitsemaasi taustaväriin — sovellus valitsee luettavan tekstivärin automaattisesti sen mukaan, kuinka kirkas väri on. Aseta se kohdassa **Asetukset › Ulkoasu › Widgetin teema**. Katso [Mukauttaminen](./05-personalization.md).

Widgetit päivittyvät itsestään pitkin päivää ja heti, kun muutat jotain sovelluksessa.

---

[← Sisällys](./README.md) · [Seuraava: Ulkoiset kalenterit →](./04-external-calendars.md)
