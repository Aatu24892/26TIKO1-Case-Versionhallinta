# Grafiikat Pelimoottorissa

## Johdatus

Taitava artisi voi luoda kauniita kuvia ja animaatioita, mutta mitä täytyy huomioida sisällyttäessä niitä peliin? Entä mitä osia voidaan tehdä pelimoottorin ja koodin puolella?

[comment]: <> (tälle osiolle vois keksiä hyvän otsikon)

## Osat

### Peligrafiikkojen luonnissa huomioitavaa

**Perinteisen ja pelitaiteen ero**

- Taideteosta harvoin tehdään yhdelle "kankaalle", jokainen osa täytyy erotella, riippuen käyttötarkoituksesta
- Yksittäisenkin esineen tai hahmon osia saatta tarvita luoda ja tallentaa erikseen

**Tiedoston ominaisuudet**
- Valmis uvatiedosto tulee tallentaa käytettävässä muodossa, esim. PNG
- Animaatiosta tehdään spritesheet/kuvatiedosto, ei videotiedostoa
    - Poikkeuksena peliin tarkoituksella sisällytetyt videot
- Resoluutio valitaan käytön mukaan:
    - Pixel art pelissä täytyy olla tarkkana, resoluutio määrää koon
    - Pienet tai kaukaiset asiat ei välttämättä tarvitse olla niin tarkkaa kuin usein nähdyt ja lähellä kameraa olevat
    - Asioita skaalatessa resoluution muutos voi olla helposti huomattavissa, etenkin pienillä resoluutioilla


### Pelimoottorin & koodin puoli
**Pelimoottorin hyödyntäminen**
- Artistin ei tarvitse, eikä voi, tehdä kaikkea (kuten dynaamisia muutoksia). Tiettyjä asioita voidaan tehdä pelin sisäisesti:
    - Modulaariset animaatiot ja liike
    - Värin/läpinäkyvyyden muutokset
    - Koon muutokset
    - Rotaatio
    - Ja niin edelleen...

## Yhteenveto

Peliartistin tulee siis osata tietenkin luoda taidetta, mutta myös sellaisessa muodossa, että sitä voidaan käyttää pelissä. Hänen täytyy huomioida, miten ja millaisessa kontekstissa mitäkin grafiikkaa tarvitaan.
