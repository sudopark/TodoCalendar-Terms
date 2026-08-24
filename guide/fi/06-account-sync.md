# 6. Tili ja synkronointi

[← Sisällys](./README.md)

---

## Et tarvitse tiliä

To-do Calendar on **offline-first**. Jokainen luomasi tapahtuma kirjoitetaan ensin laitteellesi, joten sovellus avautuu välittömästi, toimii lentokoneessa eikä jää koskaan odottamaan verkkoyhteyttä.

Kyse ei ole riisutusta tilasta — tapahtumien luonti, toistosäännöt, muistutukset, tapahtumatyypit, vapaapäivät, widgetit ja ulkoiset kalenterit toimivat kaikki täysin ilman tiliä. Mitään ei ole pantu piiloon rekisteröitymisen taakse.

---

## Mitä sisäänkirjautuminen tuo lisää

Kirjaudu sisään **Googlella** tai **Applella**, niin saat lisäksi:

- **Varmuuskopion** — tapahtumasi ovat tililläsi, eivät vain tässä puhelimessa
- **Synkronoinnin laitteidesi välillä** — sama kalenteri jokaisella iOS-laitteella, jolla olet kirjautuneena
- **[AI-pikasyötön](./02-ai-input.md)** — ainoa toiminto, joka vaatii tilin, koska pyyntö suoritetaan palvelimella

---

## Aiemmin luomasi tapahtumat

Jos olet käyttänyt sovellusta ilman tiliä, sisäänkirjautuminen ei jätä sitä työtä taakse. Kaikki aiemmin luomasi **siirretään tilillesi automaattisesti** — ensin tapahtumatyypit, sitten tehtävät, aikataulutapahtumat, tapahtumien tiedot ja valmiit tehtävät — ja sovellus kertoo, montako tapahtumaa se siirtää ja milloin siirto on valmis.

Sinun ei tarvitse tehdä mitään, eikä matkan varrella poisteta mitään.

---

## Synkronoinnin ylläpito

Synkronointi tapahtuu itsestään taustalla — muutosten jälkeen, kun sovellus palaa etualalle, ja säännöllisesti silloinkin, kun et katso. Widgetit päivittyvät, kun se on valmis.

Jos jokin näyttää vanhentuneelta, tapahtuma-asetusten **Pakota synkronointi** heittää paikallisen synkronointikohdan pois ja hakee kaiken uudelleen alusta.

Jos samaa tapahtumaa on muutettu kahdessa paikassa, palvelimen versio voittaa.

---

## Tilin hallinta

Kohdassa **Asetukset › Tili** näet, miten kirjauduit sisään, tiliin liitetyn sähköpostiosoitteen ja viimeisimmän kirjautumisajan.

- **Kirjaudu ulos** — sovellus palaa offline-tilaan ja jatkaa toimintaansa paikallisilla tiedoilla.
- **Poista tili** — poistaa tilisi ja sen tiedot. Tätä ei voi kumota, ja sovellus pyytää sinulta vahvistuksen ennen kuin se etenee.

---

[← Sisällys](./README.md)
