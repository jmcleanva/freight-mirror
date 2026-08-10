# Freight Mirror Data Sources

## Primary source

Freight Mirror v1.0 uses the U.S. Department of Transportation’s Freight Analysis Framework (FAF) 6.0 Regional 2022 dataset.

Primary source files used in the project:

- FAF 6.0 Regional Access database
- FAF 6.0 metadata workbook
- FAF 6.0 User Guide

## Dataset scope

The FAF 6.0 Regional dataset provides freight flows by:

- domestic origin FAF zone
- domestic destination FAF zone
- commodity
- domestic transportation mode
- trade type
- foreign origin region
- foreign destination region
- foreign inbound mode
- foreign outbound mode

The v1.0 report uses 2022 regional freight-flow data.

## Measures from source data

The primary reported quantitative fields used in Freight Mirror are:

- freight tonnage, reported in thousands of tons
- freight value, reported in millions of constant 2022 dollars

## Project-created calculation

Freight Mirror calculates:

- **Average Value per Ton**

This measure is derived from reported freight value and freight tonnage and is not a directly reported FAF field.

## Source classifications

Freight Mirror preserves FAF source classifications for:

- FAF zones
- commodities
- modes
- trade types
- foreign regions

Role-playing dimensions are created within the Power BI semantic model so the same source classifications can be used separately for origin and destination analysis.

## Notes

The FAF trade classification includes an **Intransit** category. No Intransit records are present in the FAF 6.0 Regional 2022 data used in Freight Mirror v1.0.

Earlier FAF 5.7.1 files were reviewed during initial project exploration but are not used in Freight Mirror v1.0.