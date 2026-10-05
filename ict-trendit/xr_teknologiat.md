# XR teollisuudessa ja viihteessä

## 1. Tiivistelmä

<Lyhyt, yhden kappaleen tiivistelmä aiheesta>

XR tarkoittaa extended realitya, johon lukeutuu VR (virtual reality), AR
(augmented reality) ja MR (mixed reality).

VR korvaa kokonaan todellisuuden ja olet osana virtuaalimaailmaa. AR lisää
virtuaalisia elementtejä oikeaan maailmaan ja MR yhdistää molemmat, jolloin
oikeat ja virtuaaliset objektit ovat vuorovaikutuksessa toistensa kanssa.

## 2. Johdanto

<Selitys, mistä artikkelin aiheessa on kyse>

<Rooli IT-alalla; paljonko käytetään, mihin tarkoitukseen, miksi tärkeää>

Extended realitya käytetään IT-alalla moniin eri tarkoituksiin. VR:ää käytetään
paljon esimerkiksi pelituotannossa ja tunnettuja VR pelejä on paljon. Pelien
lisäksi sitä käyteään esim. simulaatiotarkoituksiin ja kyberturvallisuus
skenaarioihin.

AR:ää käytetään esim. asennustöitä tehdessä reaaliaikaisesti ohjeiden näkemiseen
virtuaalisesti tai näkemään esim. informaatiota liittyen työkaluihin.

MR:ää käytetään mm. IT-tuessa, jossa teknikot voi saada reaaliaikaista apua
etänä esim. kehittäjiltä antamalla ohjeita ja kontrolloimalla laitteita muualta
käsin.

<!-- Tarvittaessa avaa termejä, tee bullet point -lista -->

## 3. Työkaluja

XR-sovellusten kehittämiseen ja käyttämiseen on saatavilla useita ohjelmistoja ja kehitysalustoja.

3.1. Unity

Unity on pelimoottori, jolla tehdään reaaliaikaista 3D-sisältöä. Sillä voi rakentaa VR-, AR- ja MR-sovelluksia usealle laitteelle. XR-tuki toimii plug-in-järjestelmän kautta: kohdealusta valitaan XR Plug-in Management -asetuksista, ja päälle voi lisätä paketteja, kuten AR Foundationin, XR Interaction Toolkitin tai käsiseurannan tuovan XR Handsin. Tuettujen laitteiden joukossa ovat muun muassa Meta Quest 2, 3, 3S ja Pro sekä Android XR.

Aloittaminen on melko helppoa. Unity Hubissa luodaan projekti XR-pohjalla, joka tuo tarvittavat paketit valmiiksi, ja XR-providerina suositellaan nykyään OpenXR-pluginia. Tekijältä odotetaan C#-osaamista ja jonkin verran 3D-ymmärrystä. Osa paketeista vaatii maksullisen Pro-, Enterprise- tai Industry-tilauksen.

Suurin etu on, että samalla koodilla pääsee OpenXR:n kautta usealle laitteelle eikä perusinteraktioita tarvitse ohjelmoida alusta asti. Unity sopii hyvin peleihin, koulutussimulaatioihin ja prototyyppien tekoon.

3.3. Meta Quest ja Meta XR SDK

Meta Quest on yksi yleisimmistä itsenäisistä VR- ja MR-laitteista, eli se ei tarvitse toimiakseen tietokonetta. Metan Unitylle tarjoamat Meta XR SDK:t, kuten Core SDK, Interaction SDK ja Voice SDK, tuovat sovelluksiin muun muassa XR-kameran, käsi- ja ohjaintulot ja puheentunnistuksen. Building Blocks -työkalulla pääsee nopeasti alkuun prototyypin kanssa. Meta XR Simulatorilla ja Link-yhteydellä voi testata ilman, että laseja tarvitsee pitää koko ajan päässä.

Käyttöönotossa asennetaan Unity, lisätään Meta XR Core SDK Unity Asset Storesta ja valitaan Unity OpenXR Plugin XR-providerksi (Unity 6:ssa suositus). Laitteen voi kytkeä kehitystilaan ja testata suoraan USB:llä tai Linkillä. Käyttäjiä voivat olla yksittäiset kehittäjät, pienet studiot ja yritykset, joilla on Quest-laitteita.

Quest sopii VR-peleihin, harjoitussimulaatioihin, virtuaalisiin yhteistyötiloihin ja MR-kokeiluihin.

## 4. Yhteenveto

XR ei ole vielä kaikkien työkalu, mutta tietyissä tehtävissä se toimii jo hyvin. Selkeimmät käyttökohteet ovat koulutus, koneiden huolto, etätuki, tuotteiden suunnittelu ja pelit.

Aloittamisen kynnys on semi-matala, koska Unityä ja Unrealia voi kokeilla ilmaiseksi, mutta itsenäiset VR-lasit, kuten Quest, maksavat ihan kivasti. Tärkeintä on valita työkalu sen mukaan, mitä haluaa tehdä:

Peleihin, mobiili-AR:ään ja nopeisiin kokeiluihin sopii Unity.
Kohteisiin, joissa kuvan pitää näyttää todelliselta, sopii Unreal Engine.

## 5. Lähteet

https://www.techtarget.com/WhatIs/definition/What-is-extended-reality
https://docs.unity3d.com/6000.0/Documentation/Manual/xr-support-packages.html
https://docs.unity3d.com/6000.1/Documentation/Manual/configuring-project-for-xr.html
https://docs.unity3d.com/6/Documentation/Manual/xr-meta-quest-develop.html
https://developers.meta.com/vr/documentation/unity/unity-development-overview/
https://developers.meta.com/vr/documentation/unity/unity-project-setup/
https://developers.meta.com/vr/blog/openxr-standard-quest-horizonos-unity-unreal-godot-developer-success/
<!-- Muista rivinvaihto myös viimeisen tekstirivin jälkeen! -->