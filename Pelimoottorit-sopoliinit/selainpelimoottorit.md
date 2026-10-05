# Selainpelimoottorit

## 1. Tiivistys

Selainpelimoottorit mahdollistavat webselain pelit, niihin käy monia muita pelimoottoreita, kuten Unity, Godot, Phaser, joihin käytetään esim. WebGPU tai WebGL API:a jotka sitten mahdollistavat grafiikkakiihdytyksen ja muut graafiset käytänteet


### 2.1. PlayCanvas

- Open-source 3D pelimoottori
- WebGPU / WebGL tuki
- Toimii moderneissa selaimissa kuten Firefox ja Chrome
- 3D animaatioita ja ääniä
- Mahdollistaa yhteistyöskentelyn samaanaikaisesti
- JavaScript
- Live testaus

### 2.2. Phaser

- Kevyt open-source 2D
- Nykyisin myös mahdollista 3D peleille (Käyttäen WebGL:ää)
- HMTL5 Canvas ja WebGL dynaaminen tuki
- JavaScript / TypeScript
- AI Integrointi
- Web ja HTML5 äänituki
- Kaksi fysiikkamoottoria, Arcade Physics sekä MatterJS

### 2.3. Babylon.js

- Babylon.js on avoimen lähdekoodin grafiikka-ja pelimoottori, jonka
avulla tehdään selainpohjaisia 3D-pelejä, visualisointeja ja
simulaatioita.
- Ohjelmointikielenä käyttää JavaScriptiä.
- Toimii WebGL:n ja WebGPU:n päällä eli ei tarvitse kirjoittaa matalan
tason grafiikkakoodia.
- Sisältää valmiita ominaisuuksia, työkaluja peleille ja fyysikan ja
animaatioiden tuen.
- Playground-ominaisuus, jossa voit kirjoittaa koodia selaimeen ja
nähdä tuloksen 3D-näkymässä.

### 2.4. WebGPU / WebGL

#### WebGL

- WebGL eli Web Graphics Library on teknologia, jota käytetään 2D-ja
3D-grafiikan piirtämisessä selaimessa. Kuitenkin enemmän 3D-grafiikkaan,
koska se piirtää sitä nopeasti näytönohjaimen avulla.
- WebGL perustuu OpenGL ES- standardiin (OpenGL ES:llä tehdään
mobiilipelejä) eli kirjasto muuntaa koodin WebGL-kutsuiksi, jotka
sitten vastaavat OpenGL ES:n standardeja.
- WebGL on matalan tason grafiikkarajapinta, joten se on monimutkainen
ja hankala, joten yleensä WebGL:ää käyttäessä käytetäänkin toisija
kirjastoja.
- WebGL-kirjastoja:
  - Three.js
  - Babylon.js
  - PlayCanvas
  - PixiJS
- Shader-kielenä käyttää GLSL-kieltä.

#### WebGPU

- WebGPU on modernimpi versio WebGL:stä, ja se on suorituskyvyltään
tehokkaampi sekä antaa selaimelle suoremman pääsyn näytönohjaimeen.
- Sen shader-kielenä se käyttää WGSL-kieltä.
- WebGPU muistuttaa grafiikkarajapintoja:
  - Vulkan
  - DirectX 12
  - Metal

## 3. Lähteet

- [PlayCanvas Wikipedia](https://en.wikipedia.org/wiki/PlayCanvas)
- [Phaser Wikipedia](en.wikipedia.org/wiki/Phaser_(game_framework))
- [Babylon.js Wikipedia](https://en.wikipedia.org/wiki/Babylon.js)
- [WebGPU Wikipedia](https://en.wikipedia.org/wiki/WebGPU)
- [Babylon.js sivusto](https://www.babylonjs.com/)
- [Developer.mozilla.org sivusto WebGL](https://developer.mozilla.org/docs/Web/API/WebGL_API)
- [Developer.mozilla.org sivusto WebGPU](https://developer.mozilla.org/docs/Web/API/WebGPU_API)
