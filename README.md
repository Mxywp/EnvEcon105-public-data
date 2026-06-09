# EnvEcon 105 Public Data

Public teaching data files for UC Berkeley EnvEcon 105, Data Tools for Sustainability and the Environment.

This repository is intentionally data-only so students can access small course CSV files from Google Colab or Jupyter without needing access to the private course-materials repository.

## Project 1 Data

Files for Project 1 are in `data/project-1/`:

- `week1_ca_county_environmental_burden_starter.csv`
- `week1_ca_county_air_quality_aqi_2024.csv`
- `week1_ca_county_calenviroscreen_summary.csv`
- `week1_data_dictionary.csv`
- `README.md`

## Student URL Pattern

Use the raw GitHub URL pattern below in notebooks:

```python
base = "https://raw.githubusercontent.com/Mxywp/EnvEcon105-public-data/main/data/project-1"
```

Example:

```python
import pandas as pd

df = pd.read_csv(base + "/week1_ca_county_environmental_burden_starter.csv")
data_dictionary = pd.read_csv(base + "/week1_data_dictionary.csv")
```

## Source Notes

The Project 1 starter file joins California county-level EPA AirData annual AQI summaries for 2024 to county summaries derived from CalEnviroScreen 4.0 tract records. It is appropriate for descriptive teaching and data-orientation practice, not causal inference.

EPA AirData source: `https://aqs.epa.gov/aqsweb/airdata/annual_aqi_by_county_2024.zip`

CalEnviroScreen 4.0 source: `https://gis.data.ca.gov/api/download/v1/items/b6e0a01c423b489f8d98af641445da28/csv?layers=0`
