# Pult – map packages

The downloadable map packages of [Pult](https://j555g.github.io/lesepult/) (☰ → Instruments → Maps). The list of packages
is `maps/maps.json` in the app; the files are downloaded from this site and kept on the device. Files over 90 MB are
published in parts (`name.0`, `name.1` …) and joined again by the app.

This repository holds only the current files: its history is replaced when the packages are rebuilt
(builder: `gd.py maps / relief / itinere` in the Pult toolkit).

| Folder | Package | Source and licence |
|---|---|---|
| `base/` | Base map, map engines | Natural Earth (public domain); MapLibre GL JS 4.7 and 5.24, pmtiles.js (BSD-3-Clause) |
| `ancient/` | Ancient world | Ancient World Mapping Center, geodata after the Barrington Atlas (ODbL 1.0) |
| `places/` | Ancient places | Pleiades (CC BY 3.0); Hanson 2016, Hanson & Ortman 2017 (CC BY-SA 4.0) |
| `landscape/` | Landscape – detailed | © OpenStreetMap contributors, as edited by the AWMC (ODbL 1.0); Natural Earth |
| `ne2/` | Natural Earth II | Natural Earth II with Shaded Relief, Water and Drainages, Tom Patterson (public domain) |
| `itinere/` | Roman roads (Itiner-e) | Itiner-e, de Soto et al. 2025 (CC BY 4.0) |
| `relief/` | Relief – overview and regions | Copernicus DEM GLO-90: © DLR e.V. 2010–2014 and © Airbus Defence and Space GmbH 2014–2018, provided under COPERNICUS by the European Union and ESA; sea depths: Natural Earth (public domain); maplibre-contour (BSD-3-Clause) |
