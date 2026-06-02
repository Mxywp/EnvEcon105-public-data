# Week 2 Studio Data

This folder contains the public course copy of the EPA Toxics Release Inventory (TRI) Basic Data File used in Week 2 Wednesday Studio.

## File

- `tri_ca_basic_2024.csv`

## Source

- Source page: https://www.epa.gov/toxics-release-inventory-tri-program/tri-basic-data-files-calendar-years-1987-present
- EPA download service URL used for this copy: https://data.epa.gov/efservice/downloads/tri/mv_tri_basic_download/2024_CA/csv
- Selection: reporting year 2024, geographic area CA

## Notes

EPA describes TRI Basic Data Files as CSV files containing commonly used fields from TRI reporting forms, including facility information, chemical identification, industry information, on-site releases, off-site transfers, and waste-management quantities.

EPA's CSV column names include numeric prefixes, such as `7. COUNTY`. Course notebooks normalize those labels before selecting columns.

EPA notes that dioxin and dioxin-like compounds are reported in grams, while most other TRI release quantities are reported in pounds. Course materials should handle or explicitly name that unit caveat before interpreting release totals.
