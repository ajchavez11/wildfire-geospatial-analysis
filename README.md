# Wildfire Geospatial Analysis

🔥 Geospatial Python toolkit for wildfire detection, monitoring, and burn severity analysis in Alaska using satellite remote sensing.

## 🎯 Project Goals

This repository documents my learning journey and project work in geospatial Python for wildfire applications, focusing on:
- Active fire detection using MODIS/VIIRS satellite data
- Burn severity mapping with Landsat/Sentinel imagery
- Historical fire pattern analysis
- Forest health monitoring (spruce bark beetle damage)
- Integration of remote sensing with machine learning

## 🛠️ Tech Stack

**Core Libraries:**
- `geopandas` - Vector data analysis
- `rasterio` - Raster data processing
- `earthengine-api` & `geemap` - Google Earth Engine workflows
- `xarray` - Multi-dimensional array operations
- `folium` - Interactive mapping

**Data Sources:**
- NASA FIRMS (Fire Information for Resource Management System)
- USGS Landsat & Sentinel satellite imagery
- Alaska Interagency Coordination Center fire perimeters
- Google Earth Engine Data Catalog

## 📁 Repository Structure
```
├── notebooks/       # Jupyter notebooks for analysis and exploration
├── scripts/         # Production Python scripts
├── data/           # Data files (see .gitignore for exclusions)
├── outputs/        # Generated maps, figures, and reports
└── docs/           # Documentation and guides
```

## 🚀 Getting Started

### Environment Setup
```bash
conda create -n wildfire_geo python=3.11
conda activate wildfire_geo
conda install -c conda-forge geopandas rasterio folium matplotlib jupyter
pip install earthengine-api geemap
```

## 📊 Projects

### Month 1: Foundations (November 2025)
- [ ] Week 1: Vector analysis with GeoPandas
- [ ] Week 2: Raster processing and spectral indices
- [ ] Week 3: Google Earth Engine workflows
- [ ] Week 4: Automated fire monitoring system

_(Projects will be added as completed)_

## 📝 Notes

This is an active learning repository. Projects are being developed as part of a 6-month intensive study (Nov 2025 - May 2026).

---

⭐ Star this repo if you find it useful!