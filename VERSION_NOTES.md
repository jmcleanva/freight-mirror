# Freight Mirror Version Notes

## Version 1.0

Initial release of Freight Mirror.

### Included

- FAF 6.0 Regional 2022 freight-flow data
- Origin Profile
- Destination Profile
- Mode & Trade analysis
- Domestic Flow Explorer
- International Flow Explorer
- About the Data page
- Freight tonnage, freight value, and average value per ton measures
- Domestic and foreign geography dimensions
- Commodity, mode, and trade-type analysis
- Release screenshots for all report pages

### Data and model

- Source: U.S. Department of Transportation, Freight Analysis Framework (FAF) 6.0
- Regional 2022 dataset
- Power BI semantic model built around the FAF regional freight-flow fact table
- Role-playing dimensions used for origin/destination and foreign geography
- Average Value per Ton calculated within Freight Mirror

### Known limitations

- No historical trend analysis
- No FAF forecasts
- No state-level analysis
- No network assignment analysis
- No internal-versus-outbound flow classification
- FAF defines an Intransit trade category, but no Intransit records are present in the FAF 6.0 Regional 2022 data used in this release