# Satellite-Image-Analysis
# 🌍 Satellite Image Analysis using Python & Remote Sensing

This project focuses on analyzing **multi-band Sentinel-2 satellite imagery** to extract meaningful environmental insights. It utilizes geospatial processing techniques to compute important indices and visualize them effectively using heatmaps.

## ✅ Key Environmental Indices

- **NDVI** (Normalized Difference Vegetation Index)  
  → Indicates vegetation health.

- **BSI** (Bare Soil Index)  
  → Detects areas with exposed or bare soil.

- **IOI** (Iron Oxide Index)  
  → Highlights iron-rich regions in soil and rocks.

## 🛠️ How It Works

1. **Loaded** Sentinel-2 bands (B2, B4, B8, B11) using **Rasterio** for geospatial raster processing.
2. **Normalized** the band values for accurate computations.
3. Handled edge cases like divide-by-zero using **NumPy**.
4. Created **heatmaps** using **Seaborn** and **Matplotlib** for visual interpretation.

## 🧪 Technologies Used

- Python
- Rasterio
- NumPy
- Pandas
- Seaborn
- Matplotlib
- Plotly

## 📁 Repository Structure

