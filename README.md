# Urban Vulnerability Index Web App

This Streamlit-based web application calculates and visualizes a Vulnerability Index for urban environments by integrating:

- **Built-up area change** from GHSL (1975–2020)
- **Land Surface Temperature (LST)** from MODIS
- **Built-Up Index (BUI)** from Landsat
- **Population Density** from WorldPop

## Features
- Visualize input raster datasets
- Generate a composite vulnerability index
- Export results as CSV
- Interactive map-based visualization
- Ready for deployment on Streamlit Community Cloud

## Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

## Running the App

```bash
streamlit run app.py
```

## Data Sources
- [GHSL - JRC](https://ghsl.jrc.ec.europa.eu/)
- [MODIS LST - NASA](https://modis.gsfc.nasa.gov/)
- [Landsat - USGS](https://landsat.gsfc.nasa.gov/)
- [WorldPop - Southampton](https://www.worldpop.org/)

## Authors
Developed by ##Ishaq Ali Shah using Google Earth Engine and Python.

---

*Deployed via [Streamlit Community Cloud](https://streamlit.io/cloud).*
