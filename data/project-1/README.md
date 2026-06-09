# Week 1 Project 1 Data Extracts

These cleaned extracts support Project 1A: Data Orientation And First Evidence. They are intentionally small enough for beginner Python work in Google Colab or Jupyter.

## Files

- `week1_ca_county_environmental_burden_starter.csv`: recommended starter file for students. It joins California county-level EPA AirData annual AQI summaries for 2024 to county summaries derived from CalEnviroScreen 4.0 tract records.
- `week1_ca_county_air_quality_aqi_2024.csv`: cleaned California rows from EPA AirData `annual_aqi_by_county_2024`.
- `week1_ca_county_calenviroscreen_summary.csv`: county-level summary derived from CalEnviroScreen 4.0 tract data. Percentile and demographic fields are population-weighted across tracts unless otherwise noted.
- `week1_data_dictionary.csv`: variable definitions, units, and sources for the starter extract.

## Recommended Week 1 Use

Students can begin with `week1_ca_county_environmental_burden_starter.csv` and practice:

1. Loading a CSV.
2. Inspecting rows, columns, data types, and missing values.
3. Reading the data dictionary.
4. Making one chart, such as `median_aqi` by county or `avg_ces_percentile_pop_weighted` by county.
5. Writing a short interpretation with at least one limitation.

## Source Notes

EPA AirData source: `https://aqs.epa.gov/aqsweb/airdata/annual_aqi_by_county_2024.zip`

CalEnviroScreen 4.0 source: `https://gis.data.ca.gov/api/download/v1/items/b6e0a01c423b489f8d98af641445da28/csv?layers=0`

Important caveat: the joined starter file combines 2024 county AQI summaries with CalEnviroScreen 4.0 indicators that come from multiple underlying years. It is appropriate for descriptive teaching and data-orientation practice, not causal inference.
