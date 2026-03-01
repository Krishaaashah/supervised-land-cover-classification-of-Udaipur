# 🌍 Land Use / Land Cover (LULC) Mapping of Udaipur Using Landsat 9 & QGIS

##  Project Overview

This project presents a detailed **Land Use / Land Cover (LULC) classification of Udaipur, Rajasthan** using **Landsat 9 satellite imagery** and **QGIS (Semi-Automatic Classification Plugin - SCP)**.

The goal of this study is to classify major land cover types and generate a thematic map to support urban planning and environmental monitoring.

---

##  Objectives

- Download and document Landsat 9 satellite imagery.
- Understand spatial and spectral resolution of satellite data.
- Perform band stacking and False Color Composite (FCC) generation.
- Apply supervised classification using training samples (ROIs).
- Generate a classified land cover map.
- Prepare a cartographically correct final output map.

---

##  Study Area

**Udaipur, Rajasthan, India**

Udaipur is located in southern Rajasthan and is known for:

- Multiple lakes (Pichola, Fateh Sagar, Udai Sagar)
- Urban settlements
- Agricultural fields
- Surrounding Aravalli hills

This diverse landscape makes it ideal for LULC classification.

---

##  Data Used

| Parameter | Details |
|------------|----------|
| Satellite | Landsat 9 |
| Source | USGS Earth Explorer |
| Spatial Resolution | 30 meters |
| Spectral Bands Used | B2, B3, B4, B5, B6, B7 |
| Projection | WGS 84 / UTM Zone 43N |
| Product Level | Level-1 |

---

##  Software & Tools

- QGIS
- Semi-Automatic Classification Plugin (SCP)
- Landsat 9 imagery
- Raster Calculator
- QGIS Print Layout

---

##  Methodology

### 1️ Data Acquisition
- Download Landsat 9 imagery from USGS Earth Explorer.
- Select image with low cloud cover.

### 2️ Preprocessing
- Load bands in QGIS.
- Create Band Set using SCP.
- Generate False Color Composite (FCC).
- Verify projection and alignment.

### 3️ Training Sample Creation (ROI)
- Define land cover classes:
  - Water
  - Vegetation
  - Built-up
  - Agriculture
  - Barren Land
- Draw multiple polygons over representative areas.
- Calculate spectral signatures.

### 4️ Supervised Classification
- Apply Maximum Likelihood Classification.
- Generate classified raster output (`Classified.tif`).

### 5️ Post Processing
- Refine classification.
- Remove noise.
- Improve visualization.

### 6️ Map Layout Preparation
- Create final map using Print Layout.
- Add:
  - Title
  - Legend
  - North Arrow
  - Scale Bar
  - Coordinate System

---

##  Output

- False Color Composite (FCC)
- Classified LULC Map
- Thematic Map Layout (PDF/PNG)
- Area statistics for each land cover class

---

##  Results

The classification successfully identified:

- Water bodies concentrated around lake regions.
- Vegetation in surrounding hilly and peripheral areas.
- Built-up areas in urban core regions.
- Agricultural and barren lands in outer zones.

The results demonstrate the effectiveness of supervised classification for urban land cover mapping.

---

##  Applications

- Urban planning and development monitoring
- Environmental impact assessment
- Land resource management
- Change detection studies


