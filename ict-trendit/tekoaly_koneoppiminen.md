# Tekoälyn ja koneoppimisen nykytila

## 1. Tiivistelmä

Tekoälymallit, kuten ChatGPT, Claude ja Gemini, ovat tekstiä, koodia ja analyysiä kirjottavia keinöälyjä, joilla pystyy myös tekemään videoita ja kuvia esim. Pixverse, Higgsfield. Uudet mallit pystyvät myös tekemään itsenäisesti asioita mcp avulla esim. hallitsemaan tietokonetta. Tekoäly on muuttanut työmarkkinaa huomattavasti, joista suurimpina aloina on ohjelmistokehitys, web-koodaus, sillä tekoälyllä luotuja ohjelmia ja nettisivuja on luodaan päivässä enemmän kun aurajoessa virtaa vettä. Isoimpana ongelmana tällä hetkellä asiassa on iso sähkön kulutus, joka johtuu datakeskuksien suuresta sähkön tarpeesta. Suomeen olla rakentamassa uusia datakeskuksia, jotka vaatisi olkiluoto 3 koko vuosittais sähkön. Mallit antavat myös vääriä vastauksia ja ihmiset tekee todella vakavia elämän tai työelämän päätöksiä sen varassa, jotka näiden virheiden takia menevät sitten pahasti mönkään. Myös tekoälysäädös tuo yrityksille uusia, velvotteita esim. markkinoinnin suhteen.

## 2. Johdanto

Keinoälyllä tarkoitetaan järjestelmiä, jotka hoitavat tehtäviä, joihin tarvitaan ihmistä yleensä, kuten kielen ymmärtämistä, ongelman ratkaisua tai asioiden tunnistamista. Keinoäly ei itse osaa asioita vaan se opiskelee ne dataasta, jolla se on koulutettu ja joissain tapauksissa kouluttaa itsensä.

IT-Firmoissa tekoäly on nykypäivää ja sitä käytetään useasti ongelmanratkasu kamuna, brainstormerina ja testaajana. Tämä on kiva lisä, mutta tiedämme että ainakun, jotain saa pitää antaa jotain vastineeksi. Data, eli ainakun haluat johkin vastauksen annat dataa esim. Haluat tehdä yrityksesi uudesta koodista analyysiä ja buggausta. Päätät laittaa koko koodin sinne ja kaikki firman datan, saat toki vastauksia ja varmasti apua, siihen mitä koodisasi vois parantaaa ja mitä pitää korjata, mutta nyt ulkoisella firmalla on teidän dataa, joka vuotaessaan aiheuttaa massiiviset vauriot teidän firmalle, eli älä tee näin. Tästä syystä monella yrityksellä on omia tekoälymalleja. Tässä kohtaa jos paska osuu tuulettimeen, se on teidän vika ja yleensä siinä kohtaa tietomurossa on saatu teidän data anycase, joten asia on enemmän perusteltua.

Esimerkki työtehtäviä, joita on alettu korvaamaan tai automatisoimaan keinoälyllä. Rutiinityöt, kuten anturivalvonta, kulunvalvonta ja asiakaspalvelu. Anturivalvonta on mittaustyötä, jolla mitataan jonkin objectin välittämää arvoa, jossain asteikossa, kuten happi tai lämpöarvo, näitä käytetään esimerkiksi rakennustyömaalla tai turvallisuusalalla. Kulunvalvonta on osa jokaista isoa corporaatiota, sillä varmistetaan turvallisuutta ja sillä on aina live data, missä kukakin on käyny tai tällä hetkellä on. Tämä auttaa selvittämään rikoksia tai palotulessa, ketä on rakenuksessa. Asiakaspalvelussa saadaan vähenettyä työvoimaa ja kuluja tekemällä itsepalvelu automaatteja esim. lentokentällä checkin.

## 3. Työkaluja

Työkaluja löytyy monenlaisia, osa valmiita ja osan joutuu itse conffaan, promtaan tai asentaan. Toiset on ympäristöjä ja toiset kirjastoja. Näitä käyttämällä pystytään myös tekemään omia malleja.

### 3.1. Claude Anthropic
Claude Anthropic on todella suosittu ja kehuttu malli, joka on tällä hetkellä kärkikahinoissa mallikehityksessä. Sillä pystyy hallitsemaan tietokonetta, luomaan kuvia, kirjottaan koodia, tekemään analyysejä ja tekemään todella isoja projekteja, joissa pystyy hyödyntämään multi mcp tooleja, eli monen agentin saman aikaista käyttöä.

Palvelua pystyy käyttämään selaimessa, koneella ja puhelimella. Sitä voi käyttää yksityishenkilö, yritys tai järjestö. Sen käyttönotto on todella helppo, se ladataan ja sitten se on käyttö valmis.


Claudella saa automatisoitua helppoja tehtäviä, sillä pystyy automatisoimaan konetehtäviä, markkinointia, ja ihan mitä vaan mieleen tulee. Mutta pitää muistaa ettei ikinä syötä keinoälylle dataa, jota et haluaisi kenenkään muun näkevän.

### 3.2. GitHub Copilot

GitHub Copilot toimii koodarin koodieditorissa. Se ehdottaa seuraavia rivejä jo kirjoittamisen aikana. Copilot selittää vierasta koodia ja kirjoittaa testejä.

Käyttöönotto vaatii laajennuksen asentamisen editoriin, esimerkiksi Visual Studio Codeen, ja kirjautumisen GitHub-tilillä. Ilmaisversiossa on rajoituksia. Opiskelijana voit saada laajemman version maksutta GitHub Educationin kautta!

Copilot sopii sekä aloittelijoille että kokeneille ohjelmoijille. Toistuvaa pohjakoodia tarvitsee kirjoittaa vähemmän, ja esimerkin saa suoraan editoriin. Jokainen ehdotus pitää silti lukea ja ymmärtää ennen hyväksymistä, koska joukossa voi olla virheitä tai tietoturva-aukkoja.

### 3.3. PyTorch

PyTorch on avoimen lähdekoodin Python-kirjasto, jolla tehdään ja koulutetaan neuroverkkoja. Se on Metan kehittämä, ja nykyään sitä ylläpitää PyTorch Foundation. Tutkijat ja yritykset käyttävät sitä enemmän kuin mitään muuta syväoppimiskehystä, ja monet tunnetut kielimallit ovat koulutettu juuri tällä.

PyTorch on ilmainen. Sen voi asentaa komennolla `pip install torch`. Näytönohjain nopeuttaa laskentaa huomattavasti, mutta pieniä kokeiluja voi tehdä heikkommillakin spekseillä. Käyttäjältä vaaditaan Python taitoja ja koneoppimisen perusteita.
PyTorchilla voi kouluttaa oman mallin Sitä on helppo muokata  ja virheet on helppo jäljittää.

### 3.4. Hugging Face

Hugging Face on verkkopalvelu, johon käyttäjät ovat jakaneet satojatuhansia valmiita malleja ja datajoukkoja. Palvelun Transformers-kirjastolla kielimallin saa käyttöön muutamalla Python-rivillä. Joukossa on myös suomea osaavia malleja.

Osittain palvelu on ilmainen. Malleja voi selata Hugging Facen sivuilla ilman tiliä, ja asentaa kirjaston komennolla `pip install transformers`. Maksullisia ovat palvelut, joissa malleja ajetaan Hugging Facen pilvessä.

Valmis malli säästää aikaa, sillä sitä ei tarvitse kouluttaa alusta. Voit ottaa käyttöön sellaisenaan tai hienosäätää sitä omalla datalla. Hugging Face sopii yrityksille, jotka haluavat pitää datan omilla palvelimillaan ja käyttää avoimia malleja.

## 4. Yhteenveto

Tekoäly siirtyy kokoajan enemmän yksinkertaisten kysymyksien vastaamisesta kokonaisten tehtävien tekemiseen ja prosessien automointiin. Työssä tämä näkyy jo nyt. Koodin kirjoittamiseen kuluu vähemmän aikaa ja ihminen valvoo ja suunnittelee koodin sanallisesti jonka tekoäly sitten kirjoittaa.

Suosittelen lämpimästi, että opiskelijat testaa ainakin yhtä tekoälyavustajaa, kuten Clauda, Grokia tai ChatGPT:tä. Koodiavustajaksi esimerkiksi Github Copilot. Niiden kanssa voi suunnitella ja toteuttaa yksin tunnissa projekteja jotka olisivat ennen vaatineet 4 hengen ryhmän ja useita tunteja yhdessä tekemistä. EU:n Tekoälysäädösten perusajatus on hyvä tuntea. Pitäkää myös mielessä yksityisyys, tekijänoikeudet ja tekoälyn hallusinointi, koska työpaikoissa niistä puhutaan yhä useammin.

## 5. Lähteet

- [Selkosanomat: Google rakentaa Suomeen suuria datakeskuksia](https://selkosanomat.fi/suomi/google-rakentaa-suomeen-suuria-datakeskuksia/)
- [Elements of AI: ilmainen tekoälykurssi](https://www.elementsofai.fi/)
- [Euroopan komissio: tekoälysäädös](https://digital-strategy.ec.europa.eu/fi/policies/regulatory-framework-ai)
- [Stanford AI Index -raportti](https://aiindex.stanford.edu/)
- [Vaswani ym. (2017): Attention Is All You Need](https://arxiv.org/abs/1706.03762)
- [ChatGPT](https://chatgpt.com/)
- [Claude](https://claude.ai/)
- [GitHub Copilot](https://github.com/features/copilot)
- [PyTorch](https://pytorch.org/)
- [Hugging Face](https://huggingface.co/)
