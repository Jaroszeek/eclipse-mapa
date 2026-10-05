# Eclipse — mapa Krakowa

Plik mapy Krakowa i okolic (`krakow.pmtiles`) dla prywatnej aplikacji Eclipse. Aplikacja pobiera go raz, w całości,
i potem rysuje mapę bez internetu.

Pliki są w zakładce [Releases](../../releases).

## Co jest w pliku

- Format: [PMTiles](https://github.com/protomaps/PMTiles) v3, kafelki wektorowe (MVT), przybliżenia 0–15.
- Obszar: 19.5838–20.3526 E, 49.9025–50.2453 N (wszystkie przystanki ZTP Kraków).
- Źródło: wycinek mapy [Protomaps Basemap](https://docs.protomaps.com/basemaps/downloads) (build 2026-10-05),
  zrobiony poleceniem `pmtiles extract … --bbox=19.5838,49.9025,20.3526,50.2453 --maxzoom=15`.

## Licencja i autorzy danych

Dane mapy: © autorzy [OpenStreetMap](https://www.openstreetmap.org/copyright), udostępnione na licencji
[Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/). Wycinek jest „bazą danych
wytworzoną” w rozumieniu ODbL i podlega tej samej licencji. Część danych na małych przybliżeniach pochodzi
z [Natural Earth](https://www.naturalearthdata.com/) (domena publiczna). Schemat kafelków: Protomaps.

---

Kraków map extract for a private app. Map data © OpenStreetMap contributors, ODbL 1.0.
