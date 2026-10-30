# Where are Spain's mobile towers?

Voronoi diagram of mobile network sites in Spain, filterable by radio technology (GSM, UMTS, LTE, NR). Each cell is the area closest to one site. It is not a coverage map.

This repo only has the built site, which is served with GitHub Pages.

## Data

- Tower data from [OpenCelliD](https://opencellid.org) ([CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)), downloaded on 25 October 2026. It is crowdsourced, so positions are estimates.
- Processing: only Spain was kept and records with identical coordinates were grouped. The result is `data/spain-towers.json`, shared under the same CC BY-SA 4.0 license.
- Basemap: [OpenStreetMap contributors](https://www.openstreetmap.org/copyright).

## License

The code is MIT (see `LICENSE`). The files in `data/` are CC BY-SA 4.0. See `THIRD-PARTY-LICENSES.txt`.
