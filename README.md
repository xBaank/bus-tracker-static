# bus-tracker-static
Static data obtained from https://data-crtm.opendata.arcgis.com/ using [madrid-data-extractor](https://github.com/xBaank/madrid-data-extractor)

- `stops.json` is extracted from cercanias gtfs data of madrid and converted from `csv` to `json`
- `stops-info.json` is extracted from `Paradas` and `Estaciones` and converted from `csv` to `json` (Currently we this is only used for extracting the 
alternative id used in the services of `Metro` and `Cercanias`)
