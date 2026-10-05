# Peligrafiikoiden Luominen

## Johdatus

Tämä tiedosto keskittyy yleisesti niin 2D- ja 3D-taiteen sekä animaation peruspilareihin, joista tulee olemaan apua peligrafiikoiden luomisessa.

### Visuaalinen Tyyli

**Esimerkkejä erilaisista tyyleistä, joilla tehdä peligrafiikkaa**

- 2D-rasteritaide
  - Muistuttaa paperille piirtämistä; Suurimmat erot ovat hyödynnettävissä olevat kerrokset, asetukset ja mahdollisuus poistaa ja lisätä asioita saman piirustukseen lähes ikuisesti
  - Skaalautuu huonosti, joten rasterigrafiikat täytyy tehdä mahdollisimman lähelle haluttua kokoa tai hieman suuremmiksi riippuen siitä, sisältääkö grafiikkasi esim. ääriviivoja, jotka eivät saa ohentua kuvaa kutistaessa
- Pikselitaide
  - Erittäin vanha ja tehokas tapa tehdä 2D-grafiikkaa, eikä välttämättä vaadi piirtämistaitoja
  - Pikseligrafiikka perustuu siihen, kuinka pelaajan mielikuvitus täyttää matalan resoluution jättämät aukot
- Vektorigrafiikka
  - Vaatii paljon teknisempää lähestymistapaa kuin rasterigrafiikka
  - Vektorigrafiikka on monikäyttöistä ja skaalautuu hyvin, minkä vuoksi sitä käytetään paljon esim. logoissa
  - Vector-tiedostot voivat tarvita paljon tilaa koneelta sekä toimenpiteitä pelimoottorissa, minkä vuoksi monet tallentavat vektorigrafiikalla tekemänsä grafiikat esim. .png -muodossa ja käyttävät vektorigrafiikkaa vain apuna mm. animointivaiheessa
- 3D-mallintaminen polygonien avulla
  - Perustuu polygonien lisäämiseen ja siirtelyyn 3D-ohjelmassa
  - Peligrafiikassa kannattaa minimoida polygonien määrä, sillä suuri määrä polygoneja voi aiheuttaa paljon viivettä pelin sisällä aina, kun kyseinen malli on ruudulla
- 3D-kaivertaminen
  - Monissa 3D-ohjelmissa voi "kaivertaa" malleja samalla tavalla kuin savitöitä
  - Mahdollistaa erittäin yksityiskohtaiset 3D-mallit

### Värimaailma

- Värit, kontrasti ja valot ovat erittäin tärkeitä luomaan peliin tunnelmaa, selkeyttä ja omaa visuaalista ilmettä
  - Ei ole tarpeeksi, että grafiikka näyttää hyvälle; Esimerkiksi visuaalinen selkeys on erittäin tärkeää
- Konseptivaiheessa kannattaa luoda suuntaa antava väripaletti
  - Pelistä riippuen esim. eri alueet voivat vaatia oman väripaletin
  - Visuaalista selkeyttä tavoitellessa voi hyödyntää mm. vastavärejä tai suurta kontrastia
  - Pikimustaa ja vitivalkoista kannattaa käyttää monissa tapauksissa harkiten, mutta esim. mustavalkoisissa tai muuten korkeaa kontrastia omaavissa peleissä ne voivat toimia hyvin

### Käyttöliittymä

- Jopa pelin käyttöliittymään, eli menuihin, nappeihin yms. usein tarvitaan grafiikkaa
- Käyttöliittymän kohdalla visuaalinen selkeys on erityisen tärkeää
- Fonttien valitseminen tai tekeminen on myös osa UI(user interface) -grafiikkaa

### Animaatio

- 2D-rasterigrafiikassa animointi tapahtuu yleensä joko frame-by-frame -tekniikalla, eli kuva kuvalta tai riggaamalla
  - Riggaaminen mahdollistaa hahmon liikuttelun ja tiettyjen työvaiheiden ohittamisen, mutta omaa silti omat rajoitteensa ja vaatii paljon valmistelua
- Pikseligrafiikkaa myös animoidaan usein yksi kuva kerrallaan
- Vektorigrafiikan animointi perustuu pitkälti asioiden liikutteluun valmiissa vector-hahmoissa samalla tyylillä, kuin rigatuissa rasteri-grafiikoissa
  - Vector-grafiikkaa voi myös suurentaa menettämättä laatua
- 3D-mallien animoiminen painottuu erittäin paljon keyframeihin, joiden väliin luodaan tarpeen mukaan lisää frameja tekemään liikkeestä luontevampaa
  - Lisäksi 3D-mallit tarvitsevat armaturen eri oman luurankonsa, jotta niiden eri osia voi liikuttaa
  - Weight paint ja monet muut tekijät vaikuttavat siihen, miten malli taipuu

## Yhteenveto

Tapoja tehdä peligrafiikkaa on yhtä paljon, kuin tapoja luoda mitään muuta taidetta. Perusteet ja yleiset tyylit on hyvä tietää, mutta älä pelkää tietoisesti rikkoa yleisiä sääntöjä oman visiosi saavuttamiseksi. Ajan saatossa videopelit ovat todistaneet, että grafiikkaa voi luoda jopa stop-motion-animaatiolla, konekirjomalla sprite sheettejä tai vaikka pelkillä teksteillä. Peligrafiikka on pitkälti tasapainottelua taiteellisen vision ja teknisen toimivuuden välillä.
