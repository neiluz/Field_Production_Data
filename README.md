# Production Wells Analysis Streamlit App

This app is an interactive tool developed as an outcome of a workshop with the Petroleum Engineering Association, designed for the analysis of oil, gas, and water production data from production wells.

## Data
The data used in this application is public data available at the following location:
[Equinor's Volve Field Data](https://www.equinor.com/en/what-we-do/digitalisation-in-our-dna/volve-field-data-village-download.html)
The data has been made publicly available by Equinor under this license: [click here](https://www.equinor.com/en/what-we-do/digitalisation-in-our-dna/volve-field-data-village-download.html).

## Variables
- `DATEPRD`: The date of production.
- `WELL_TYPE`: The type of well (OP for Oil Producer).
- `BORE_OIL_VOL`: The volume of oil produced.
- `BORE_GAS_VOL`: The volume of gas produced.
- `BORE_WAT_VOL`: The volume of water produced.
- `NPD_WELL_BORE_NAME`: The name of the well bore.

The application allows the user to select a date to display production data and provides interactive visualizations of production metrics over time.

## Library
The list of libraries used in your Streamlit app:
- streamlit==1.12.0
- pandas==1.4.1
- plotly==5.8.0
- seaborn==0.11.2
- matplotlib==3.5.1
- openpyxl==3.0.9
