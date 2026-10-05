# Versionhallinta Tiimissä

## Johdanto
<!-- Muiden tiedostojen alaotsikot oli nimetty "johdanto/tiivistelmä" niin sitä vois harkita tässäkin, että tiedostoista tulisi yhtenäisemmän oloisia? (ks. article-template.md) -IM -->
Git versionhallinta mahdollistaa usean kehittäjän työskentelyn saman projektin parissa.

Code review on koodin vertaisarviointi, joka auttaa kehittäjiä varmistamaan tai parantamaan koodin laatua.

## Git
Yksi Gitin keskeisimpiä etuja on mahdollisuus seurata muutoksia tiedostoihin ja kansiohin ajan kuluessa. Tämä varmistaa ettei tehty työ valu hukkaan ja jos virheitä tapahtuu ne voidaan kumota. Tiimin jäsenet voivat huoletta testata eri lähestymistapoja, koska he voivat aina palata aikaisempaan tilaan jos on tarvetta.

Gitin ominaisuudet projektin haarautumiseen ja yhdistamiseen mahdollistavat rinnakkaiskehityksen. Jokainen tiimin jäsen voi luoda oman haaransa ja työskennellä tiettyjen ominaisuuksien parissa ilman että häiritsee pääprojektia. Kun muutokset ovat valmiit ne voidaan yhdistää takaisin pääprojektiin, mikä optimoi yhteistyötä ja vähentää ristiriitoja.

Gitin jakautettu luonne on ihanteellinen etätyöskentelyyn. Tiimin jäsenet voivat osallistua tehokkasti projektiin paikasta riippumatta. Keskitetyt repositoriot erilaisilla alustoilla (esim. GitHub, GitLab tai Bitbucket) mahdollistavat vaivattoman yhteistyön, varmistaen että tiimit voivat työskennellä yhdessä tehokkasti etänä.

<!-- Saanko ehdottaa "Keskitettyjä repoja on erilaisilla... Bitbucket)" piste. "Alustat mahdollistavat..." :) -IS -->
<!-- Hyvää jälkeä, no notes -MM -->

## Code review
Code review (koodikatselmointi) on koodin vertaisarviointi, jossa toinen kehittäjä tarkastaa kollegansa kirjoittaman koodin ennen sen käyttöönottoa. Tarkoituksena on varmistaa, että ratkaisu toimii oikein, on laadukkaasti toteutettu ja noudattaa sovittuja käytäntöjä. Samalla pyritään löytämään mahdolliset virheet, loogiset puutteet ja muut ongelmat mahdollisimman varhaisessa vaiheessa.

<!-- onko tarkoituksella loohiset? :D -IS -->
<!-- ei ollut: korjattu -JS -->

Koodikatselmointi voidaan toteuttaa usealla eri tavalla riippuen tiimin työskentelytavoista. Kehittäjät voivat tarkastella koodia yhdessä pariohjelmoinnin aikana, keskutella muutoksista suoraan toistensa kanssa, hyödyntää katselmointiin tarkoitettuja työkaluja tai jakaa pienet muutokset tarkistettavaksi sähköpostin tai versionhallintajärjestelmän kauttta. Kaikkien menetelmien tavoitteena on löytää mahdolliset virheet ja parantaa koodin laatua ennen sen käyttöönottoa.

Koodikatselmoinnin tärkeimpiä hyötyjä ovat osaamisen jakaminen ja ohjelmiston laadun parantaminen. Kun useampi kehittäjä tutustuu samaan koodiin, tieto ei jää vain yhden henkilön varaan. Katselmointi auttaa myös havaitsemaan virheet, tietoturvariskit ja laatuongelmat aikaisessa vaiheessa, jolloin niiden korjaaminen on helpompaa ja edullisempaa. Lisäksi se edistää tiimityötä ja varmistaa, että koodi noudattaa yhteisiä käytäntöjä ja standardeja.

Vaikka koodikatselmoinnista on paljon hyötyä, siihen liittyy myös haasteita. Katselmointi voi hidastaa kehitysprosessia, koska koodia ei voida ottaa käyttöön ennen kuin toinen kehittäjä on tarkistanut sen. Lisäksi katselmointeihin käytetty aika on pois muista työtehtävistä. Erityisesti suurten koodimuutosten tarkastaminen voi olla työlästä, jolloin osa ongelmista saattaa jäädä huomaamatta ja palautteen laatu voi kärsiä. Siksi koodikatselmoinnit kannattaa tehdä säännöllisesti ja riittävän pienissä kokonaisuuksissa.

<!-- onko joku selitys MIKSI koodia ei voisi ottaa käyttöön ennen kuin toinen on tarkastanut sen? vai onko enemmän että ei kannata/ei pitäisi/olisi parempi olla ottamatta -IS -->

## Yhteenveto
Git on versionhallintajärjestelmä, joka auttaa tiimiä seuraamaan koodimuutoksia, hallitsemaan eri versioita ja tekemään yhteistyötä tehokkaasti. Koodikatselmointi tukee laadukasta ohjelmistokehitystä varmistamalla, että koodi tarkistetaan ennen käyttöönottoa. Yhdessä Git ja koodikatselmointi parantavat koodin laatua, jakavat osaamista sekä vähentävä virheiden ja tietoturvaongelmien riskiä.

## Lähteet
- [What is a code review?](https://about.gitlab.com/topics/version-control/what-is-code-review/)
- [Unlock the Full Potential of Git Collaboration: A Guide to Effective Teamwork](https://devot.team/blog/git-collaboration)
