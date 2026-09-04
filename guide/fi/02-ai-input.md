# 2. AI-pikasyöttö

[← Sisällys](./README.md)

---

Kuvaile tavallisin sanoin, mitä haluat, ja sovellus rakentaa sen puolestasi — ”lounas Saran kanssa perjantaina keskipäivällä”, ”siirrä hammaslääkäri ensi tiistaille”, ”merkitse pyykit tehdyiksi”. Ei lomakkeita, ei päivämäärävalitsimia.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fi/ai-input.png" alt="AI-pikasyöttö" width="280">

AI-pikasyöttö vaatii sisäänkirjautumisen. Kaikki muu sovelluksessa toimii ilman tiliä.

---

## Mihin se pystyy

- Luo tehtäviä ja aikataulutapahtumia niin, että aika, toisto ja tapahtumatyyppi päätellään sanomastasi
- Muuttaa olemassa olevaa tapahtumaa — siirtää sen, nimeää sen uudelleen, vaihtaa sen ajankohdan
- Merkitsee tehtävän valmiiksi tai kumoaa merkinnän
- Poistaa tapahtuman
- Hoitaa useita asioita yhdellä pyynnöllä (”lisää sali maanantaille, keskiviikolle ja perjantaille klo 7”)

---

## Tavat lähettää pyyntö

### Sovelluksessa

Napauta kalenterinäkymän AI-painiketta. Syöttönäkymä avautuu, ja siinä on kaksi tilaa, joiden välillä voit vaihtaa milloin tahansa:

- **Ääni** — puhu ja katso, kuinka puheentunnistus etenee reaaliajassa. Vaatii mikrofonin ja puheentunnistuksen käyttöoikeuden; jos jompikumpi on evätty, sovellus tarjoutuu avaamaan iOS:n asetukset tai vaihtamaan näppäimistöön.
- **Näppäimistö** — kirjoita se. Kätevää silloin, kun olet paikassa, jossa et voi puhua.

### Kuvasta

**Lue kuvasta** muuttaa kuvan tapahtumiksi. **Ota kuva** tai **Valitse kirjastosta** — sovellus lukee siinä olevan tekstin — lukujärjestyksen, tapahtumajulisteen, kuvakaappauksen viestistä — ja näyttää löytämänsä, jotta voit korjata virheet ennen lähettämistä.

Voit ohjata lopputulosta kohdassa **Lisäohjeet (valinnainen)**, esimerkiksi ”lisää nämä tehtävinä”. Jos kuvassa ei ole luettavaa tekstiä, sovellus kertoo siitä sen sijaan, että lähettäisi tyhjän pyynnön.

### Siri

Sano **”Hei To-do Calendar”** — myös ”Pyyntö sovellukseen To-do Calendar”, ”Kysy sovellukselta To-do Calendar”, ”Lähetä pyyntö sovellukselle To-do Calendar” ja ”Lisää AI:lla sovelluksessa To-do Calendar” toimivat. Voit sanoa myös ”Todo Calendar” ilman yhdysmerkkiä. Siri kysyy, mitä sen pitää tehdä, ja pyyntö suoritetaan **taustalla avaamatta sovellusta**. Siri vastaa ”Selvä. Ilmoitan sinulle, kun se on valmis”, ja saat ilmoituksen, kun tulos on valmis.

### Toimintopainike

Määritä toimintopainikkeeseen **Lähetä**-oikopolku. Yksi painallus, sanot asian, valmista — sovelluksen ei tarvitse tulla lainkaan etualalle.

### Widget ja Ohjauskeskus

- **Lisää AI:lla -widget** — Home-valikon tai lukitusnäytön widget, joka avaa AI-syöttönäkymän yhdellä napautuksella.
- **Ohjauskeskus** (iOS 18 ja uudemmat) — lisää sama säädin Ohjauskeskukseen, niin saat sisäänmenon pyyhkäisemällä alas.

### Jakovalikko

Jaa **tekstiä tai kuva mistä tahansa muusta sovelluksesta** suoraan To-do Calendarin AI:lle. Luet viestiä, jossa on tapaamisen tiedot, tai katselet julistetta Kuvat-sovelluksessa — napauta jakamista, valitse To-do Calendar, lisää halutessasi ohje ja lähetä.

Myös jakovalikosta lähetetty pyyntö suoritetaan taustalla. Saat vahvistuksen lähettämisestä, ja tuloksen tarkistat sovelluksesta.

---

## Näin pyyntö etenee

1. **Lähetetty** — pyyntösi lähtee matkaan. Jos se tuli Siriltä, toimintopainikkeesta tai jakovalikosta, sovellusta ei tarvitse pitää auki.
2. **Käsitellään** — sovellus näyttää edistymisen. Voit **pysäyttää** pyynnön kesken suorituksen, mutta pysäyttäminen hylkää käynnissä olevan työn eikä sitä voi jatkaa.
3. **Vahvistus tarvittaessa** — jos pyyntö muuttaisi jotain merkittävää, sovellus pyytää ensin hyväksyntääsi ja näyttää tarkalleen, mitä se aikoo tehdä. Aikaa on rajallisesti; jos se loppuu, pyydä vain uudelleen.
4. **Komento suoritettu** — tulos päätyy kalenteriisi välittömästi, ja mukana on yhteenveto siitä, mikä muuttui.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fi/ai-result.png" alt="AI:n tulos" width="280">

Vain yksi pyyntö suoritetaan kerrallaan. Jos lähetät toisen, kun edellinen odottaa vielä hyväksyntääsi, sovellus kehottaa hoitamaan ensimmäisen ensin.

---

## Krediitit

Jokainen AI-pyyntö kuluttaa **krediittejä**, ja krediittisi täydentyvät joka päivä. Jäljellä oleva määrä näkyy AI-syöttönäkymän ylälaidassa, joten tiedät sen jo ennen lähettämistä.

Kun krediitit loppuvat, AI-pikasyöttö odottaa seuraavan päivän täydennystä. Kaikki muu sovelluksessa toimii edelleen.

---

## Käyttöoikeudet, joita se voi pyytää

| Käyttöoikeus | Mihin sitä käytetään |
|---|---|
| Mikrofoni + puheentunnistus | Äänisyöttö |
| Kamera | Kuvan ottaminen **Lue kuvasta** -toimintoa varten |
| Kuvakirjasto | Olemassa olevan kuvan valitseminen |
| Ilmoitukset | Taustalla suoritetun pyynnön tuloksesta kertominen |

Kutakin niistä kysytään vasta, kun käytät ensimmäisen kerran sitä tarvitsevaa toimintoa, ja sovellus toimii ilmankin — äänisyöttö korvautuu näppäimistöllä ja kuvasyöttö kirjoittamalla.

---

[← Sisällys](./README.md) · [Seuraava: Widgetit ja lukitusnäyttö →](./03-widgets.md)
