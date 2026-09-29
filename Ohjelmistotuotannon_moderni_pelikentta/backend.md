# Backend-kehitys, palvelinteknologiat ja tietokannat

## Backend-kehitys
Backend on sovelluksen tai verkkosivuston näkymätön puoli, sen "konehuone". Kun painat nappia, kirjaudut sisään tai teet tilauksen, backend hoitaa taustalla varsinaisen työn: se käsittelee pyynnön, suorittaa logiikan ja palauttaa vastauksen. Käyttäjä näkee vain lopputuloksen.

## Palvelinteknologiat
Backend-koodi pyörii palvelimilla, jotka ovat jatkuvasti päällä ja vastaavat käyttäjien pyyntöihin ympäri vuorokauden. Palvelimet voivat olla omia koneita tai pilvipalveluja, kuten AWS tai Azure.

## Tietokannat
Tietokannat ovat sovelluksen muisti. Ne säilyttävät datan, kuten käyttäjätiedot, tilaukset ja viestit, pysyvästi tallessa. Sovellukset ja sivustot hakevat tietokannasta dataa tarvittaessa ja tallentavat sinne uutta. Domain Name System (DNS) Resoluutio: Kun syötät "youtube.com”heidän verkkoselaimessaan ensimmäinen vaihe on DNS päätöslauselma.

Selain pyytää DNS palvelimen muuntaakseen verkkotunnuksen IP-osoitteeksi. Kun IP-osoite on saatu, selain voi muodostaa yhteyden siihen liittyvään palvelimeen.

Asiakaspyyntö: Käyttäjän verkkoselain lähettää HTTP-pyynnön IP-osoitteeseen, joka on liitetty osoitteeseen ”youtube.com”.

Tämä pyyntö sisältää tietoja pyydetystä sisällöstä (kuten tietyn verkkosivun) ja lisätietoja, kuten otsikot.

Palvelimen tunnistus: Verkkosivustoa ” youtube.com ” ylläpitävä verkkopalvelin vastaanottaa saapuvan pyynnön.

Palvelimen IP-osoite on liitetty useisiin verkkotunnuksiin jaetuissa sopimuksissa , mutta jos käytät VPS:ää tai dedikoitua palvelimia, sinulla saattaa olla vain yksi verkkosivusto kyseisellä IP-osoitteella, ja pyyntöotsikoiden perusteella se tunnistaa, että pyyntö on tarkoitettu osoitteelle ”youtube.com”.

Sisällön haku ja luominen: Verkkopalvelin hakee tarvittavat tiedostot tai luo palvelimella isännöidyn dynaamisen sisällön. Tämä voi olla HTML-tiedostoja, kuvia, CSS-tyylitiedostoja, JavaScript-skriptejä tai muita verkkosivun näyttämiseen tarvittavia tiedostoja.

Selainrenderöinti: Verkkopalvelin lähettää HTTP-vastauksen takaisin käyttäjän verkkoselaimelle muodostuneen yhteyden kautta, ja käyttäjän selain vastaanottaa HTTP-vastauksen verkkosivun renderöintiä varten. Se käsittelee HTML:ää sivurakenteen luomiseksi, hakee ulkoisia resursseja (tyylitiedostot, skriptit, kuvat) ja näyttää lopullisen renderöidyn verkkosivun käyttäjälle.

## ohjelmointikielet
Backendiin käytetään montaa eri ohjelmointikieltä, kuten esimerkiksi Node.js, Javascript, python tai GO.