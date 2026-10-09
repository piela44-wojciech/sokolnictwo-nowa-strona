# Sokolnictwo i Jastrzębiarstwo — nowa strona

Nowa, responsywna rekonstrukcja wizualna strony o sokolnictwie, utrzymana w stylistyce dawnej księgi przyrodniczej: papier, ciemna zieleń, ozdobne ramki i ilustracje ptaków.

## Podgląd
https://piela44-wojciech.github.io/sokolnictwo-nowa-strona/

## Edycja ilustracji
Grafiki są osobnymi plikami SVG w katalogu `public/images/`:
- `scenes/hero-landscape.svg` — panorama w nagłówku,
- `scenes/falcon-flight-lake.svg` — scena wprowadzająca,
- `scenes/falconer-vintage.svg` — ilustracja w menu,
- `scenes/news-hawking.svg` — ilustracja aktualności,
- `scenes/hunting-dog-engraving.svg` — pies myśliwski,
- `birds/` — osobne ryciny sokoła i jastrzębia.

Można zastąpić dowolny plik grafiką o tej samej nazwie i zachować układ strony. Style oraz układ znajdują się głównie w `src/pages/index.astro`, a menu i boczne panele w `src/components/`.

## Technologia
Astro, statyczny build i GitHub Pages. Zmiany w gałęzi `main` uruchamiają workflow publikacji.
