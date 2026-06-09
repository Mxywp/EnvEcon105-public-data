# Week 2 TRI Source Note

This file records the source selection for the Week 2 Wednesday Studio public data copy.

- Dataset: EPA Toxics Release Inventory (TRI) Basic Data File
- Reporting year: 2024
- Geographic area: CA
- Source page: https://www.epa.gov/toxics-release-inventory-tri-program/tri-basic-data-files-calendar-years-1987-present
- EPA download service URL: https://data.epa.gov/efservice/downloads/tri/mv_tri_basic_download/2024_CA/csv

The GitHub Actions workflow `.github/workflows/fetch-week2-tri.yml` downloads the CSV from EPA and commits it as `data/week-2/tri_ca_basic_2024.csv`.
