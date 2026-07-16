# 🌱 AgroTech Satellite Labs

Repository containing the practical work developed during the **Master in Agro 4.0**, focused on satellite remote sensing and precision agriculture.

The project follows a complete workflow using **Sentinel-2 imagery** to monitor crop development, analyze vegetation dynamics and generate agronomic information.

## Technologies

- Python
- Jupyter Notebook
- Sentinel-2 L2A
- STAC API
- GeoPandas
- Rasterio
- Rioxarray
- Xarray
- Matplotlib
- Scikit-learn
- NASA POWER
- Isolation Forest

## Repository Structure

```
data/
    parcela.geojson

lab1_anatomia_de_tu_parcela.ipynb
lab2_abre_el_cubo.ipynb
lab3_indices.ipynb
lab4_series_clima.ipynb
lab5_anomalias_prescripcion.ipynb

environment.yml
README.md
```

## Study Area

The original laboratory has been adapted to a **real agricultural field located in Argentina**, replacing the default sample area provided in the course.

The objective is to analyze the complete agricultural season through satellite imagery and geospatial analysis.

## Main Results

- Real agricultural parcel in Buenos Aires Province, Argentina
- 18 Sentinel-2 L2A scenes for the 2024–2025 soybean season
- NDVI peak close to 0.87 during March 2025
- NDVI integral: 79 NDVI·day
- Z-score anomalies: 15.4%
- Isolation Forest anomalies: 10.0%
- Final prescription doses: 0, 60, 90 and 110 kg N/ha
- Exported georeferenced prescription map: `prescripcion_N.tif`

## Laboratories

- ✅ Lab 1 – Parcel anatomy and Sentinel-2 inventory
- ✅ Lab 2 – Multiband data cube and SCL mask
- ✅ Lab 3 – NDVI, EVI, NDRE, NDWI and vigor zoning
- ✅ Lab 4 – NDVI time series and NASA POWER climate integration
- ✅ Lab 5 – Anomaly detection and variable-rate prescription map

## Author

Juan Ignacio Bastonero

Master's Student in Agro 4.0  
Agribusiness Technician  
Backend .NET Developer  
Precision Agriculture & IoT Enthusiast