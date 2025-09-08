# Empirical-Models-for-Tropical-Storm-Windspeeds-After-Landfall
Análisis y modelado de huracanes con Python. Incluye procesamiento de tracks históricos, detección de landfall mediante shapefiles/raster, ajuste de modelos de decaimiento del viento tras el impacto en tierra y visualización de resultados en Jupyter Notebook.

# 🌀 Análisis y Modelado de Huracanes con Python

Este repositorio contiene un conjunto de **herramientas en Python para el análisis de huracanes**, con un enfoque en el **procesamiento de tracks históricos, detección de landfall y ajuste de modelos de decaimiento del viento en tierra**.  
Se utilizan datos de huracanes del Atlántico (ejemplo: **Huracán Michael, 2018**) para validar los métodos implementados.

---

## 📖 Contenido del repositorio

- `notebooks/`
  - `1-116-S-TropicalStormWindspeeds-StudentVersion` → Guia del proyecto
  - `Track_huracán.ipynb` → Lectura y limpieza de datos de tracks (NOAA/NHC), estimación de parámetros.
  - `ne_10m_land` → Mapa mundi: Natural Earth Land polygons including major islands.
  - `nhc_hurdat2` → Datos del NHC de diversos huracánes.
  - `consensus_full` → Mapas de terreno (aún no está aplicado)

---

## ⚙️ Requisitos

El proyecto utiliza Python 3 y las siguientes librerías:

```bash
pip install numpy pandas matplotlib scipy geopandas shapely rasterio
