# Luotea Porraskartoitus

Porraskohteen tilakartoitus kentällä puhelimella, tabletilla tai koneella. Korvaa Porrasmitoituksen paperisen tilakartoituslomakkeen.

**Käyttö:** avaa sivu puhelimessa ja valitse selaimen valikosta *Lisää kotinäytölle*. Sovellus toimii sen jälkeen myös ilman verkkoa (kellarit, porraskäytävät).

Käyttöohje: [ohje.html](https://juntsa.github.io/porraskartoitus/ohje.html) (asennus, tallennus puhelimeen, vienti).

## Mitä lomakkeella kerätään

- Useita rakennuksia, ja jokaisella rakennuksella useita rappuja (*Kopioi rappu* samanlaisille rapuille)
- Rappu: ala-aulat, hissit, tuulikaapit sekä askelmat ja tasanteet (m²/krs × kerrokset, useita rivejä)
- Rakennuksen yhteiset tilat: saunaosastot, pesulat ja kuivaushuoneet, ulkoiluvälinevarastot, kellarikäytävät, irtaimistovarastokäytävät, kerhohuoneet ja kuntosali
- Mittalaskin kenttiin: `4,2*3,1` tai `2,1x1,5+3`

## Tiedot

- Luonnos tallentuu laitteelle automaattisesti. Mitään ei lähetetä palvelimelle.
- **Vie Porrasmitoitukseen** tuottaa tiedoston `LuoteaPorras_….json`, jonka Luotea Porrasmitoitus avaa *Avaa laskelma* -napista. Jokaisesta rakennuksesta tulee oma kohde, ja pinta-alat säilyvät tarkkoina.
- **Tallenna kartoitus** / **Avaa kartoitus**: keskeneräisen kartoituksen siirto laitteelta toiselle.
- **Tulosta / PDF**: A4-yhteenveto.

## Julkaisu

GitHub Pages julkaisee `main`-haaran juuren. Päivitys: korvaa `index.html` ja nosta `sw.js`:n `VERSIO`, jotta puhelimet hakevat uuden version.

Tiedostot: `index.html` (sovellus), `manifest.webmanifest` ja `icons/` (kotinäyttö), `sw.js` (offline).
