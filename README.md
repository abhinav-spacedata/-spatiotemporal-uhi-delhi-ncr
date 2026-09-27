# 🛰️ Multi-Decadal Spatio-Temporal Dynamics & Predictive Modelling of Urban Heat Island (UHI) Intensity: Delhi-NCR (1995–2045)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Google Earth Engine](https://img.shields.io/badge/Google_Earth_Engine-GEE-green.svg)](https://earthengine.google.com/)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Organization: ESARC](https://img.shields.io/badge/Initiative-ESARC-orange.svg)](https://github.com/)

<!-- ITEM 1: HEADER BANNER IMAGE -->
<p align="center">
  <img src="fig1.jpg" alt="Delhi-NCR 150km Radius LST Map Banner" width="100%">
</p>

> **SCI-Oriented Title:** Spatio-Temporal Analysis and Machine Learning-Based Prediction of Urban Heat Island Intensity over Delhi-NCR Region Using Multi-Temporal Landsat and ESA WorldCover Data

---

## 📌 Executive Summary
This research presents a 50-year spatio-temporal study (1995–2045) tracking Land Surface Temperature (LST) and Urban Heat Island (UHI) dynamics over a **150 km circular buffer** around the Delhi-NCR region. Using Google Earth Engine (GEE), LST was retrieved using the **Sobrino et al. (2004) Mono-Window Algorithm** across Landsat 5/7/8/9 sensor streams. 

The study highlights a direct correlation between urban expansion and thermal stress, showing an **8.1°C rise in mean LST** over 30 years (1995–2025). Predictive modelling using CA-Markov, Random Forest, and LSTM algorithms projects mean LST levels reaching **41.2°C – 41.9°C by 2045**.

---

## 🗺️ Study Area & Spatial Thermal Gradient

<!-- ITEM 2: SPATIAL GRADIENT MAP -->
<p align="center">
  <img src="fig2.jpg" alt="Spatial Gradient Map 150km Radius" width="85%">
  <br>
  <i>Figure 1: 150 km AOI Buffer showing South-West arid warming vs. North-East foothills cooling.</i>
</p>

* **Center Coordinate:** 28.6139°N, 77.2090°E (Delhi Core)
* **AOI Geometry:** **150 km Radius Circular Buffer** (Enclosing Delhi-NCR, Western UP, South Haryana, and Rajasthan border)
* **Spatial Observations:**
  * **South-West Zone (Rajasthan Border):** Elevated LST / high NDBI due to arid terrain and sparse canopy cover.
  * **North / North-East Zone (Uttarakhand Foothills):** Cooler LST microclimates driven by vegetation density and elevation.
  * **Central Core:** Persistent high-intensity heat sink across Delhi, Noida, Gurugram, and Ghaziabad.

---

## 🎬 Multi-Decadal LST Dynamics (1995–2025 Timelapse)

<!-- ITEM 3: DECADAL TIMELAPSE VIDEO -->
<p align="center">
  <video src="video4.mp4" width="85%" controls autoplay loop muted></video>
  <br>
  <i>Video 1: 30-Year Spatio-Temporal Thermal Evolution Video over Delhi-NCR (1995–2025).</i>
</p>

---

## 🎯 Key Findings & Metric Progression

* **Baseline Mean LST (1995):** 29.8°C
* **Current Mean LST (2025):** 37.9°C
* **Projected Mean LST (2045):** 41.2°C – 41.9°C
* **Projected Max LST (2045):** 51.2°C
* **Vegetation Loss (NDVI Drop):** -36.4% decrease (1995–2025)
* **Built-Up Expansion (NDBI Surge):** +58.2% increase (1995–2025)

---

## 📊 Multi-Decadal Temporal Progression Maps (1995–2045)

<!-- ITEMS 4, 5, 6, 7, 8: TEMPORAL PROGRESSION IMAGES -->
<p align="center">
  <img src="fig7.jpg" alt="LST Map 1995" width="31%">
  <img src="fig8.jpg" alt="LST Map 2005" width="31%">
  <img src="fig9.jpg" alt="LST Map 2015" width="31%">
</p>
<p align="center">
  <img src="fig10.jpg" alt="LST Map 2025" width="48%">
  <img src="fig11.jpg" alt="Predicted LST Map 2045" width="48%">
  <br>
  <i>Figure 2: Multi-Decadal LST Progression showing regional warming dynamics from 1995 to 2045.</i>
</p>

---

## 🔥 Thermal Hotspots & 2045 Prediction Map

<!-- ITEMS 9 & 10: HOTSPOT & RISK MAPS -->
<p align="center">
  <img src="fig3.jpg" alt="Hotspot Density Map" width="48%">
  <img src="fig4.jpg" alt="2045 Predictive Thermal Risk Map" width="48%">
  <br>
  <i>Figure 3: (Left) Identified 66 Hotspots in 2025; (Right) ML-Based Predicted Thermal Risk Map for 2045.</i>
</p>

---

## 🔬 Regional Microclimate & High-Resolution Thermal Masking

<!-- ITEMS 11 & 12: REGIONAL GRADIENT & HIGH-RES MASKING -->
<p align="center">
  <img src="fig5.jpg" alt="Regional Thermal Gradient Analysis" width="48%">
  <img src="fig6.png" alt="High-Resolution Thermal Surface & Water Mask" width="48%">
  <br>
  <i>Figure 4: Regional thermal gradient distribution and masked water body thermal baseline.</i>
</p>

---

## 🔬 Scientific Methodology & LST Engine

### 1. Normalized Difference Vegetation Index (NDVI)
$$NDVI = \frac{NIR - Red}{NIR + Red}$$

### 2. Normalized Difference Built-Up Index (NDBI)
$$NDBI = \frac{SWIR - NIR}{SWIR + NIR}$$

### 3. Sobrino et al. (2004) Mono-Window LST Algorithm
$$LST = \frac{T_B}{1 + \left( \frac{\lambda \cdot T_B}{\rho} \right) \ln(\epsilon)} - 273.15$$

Where:
* $T_B$: Brightness Temperature in Kelvin
* $\lambda$: Effective thermal wavelength ($10.8\ \mu\text{m}$ for Landsat Band 10)
* $\rho$: $\frac{h \cdot c}{\sigma} = 1.4388 \times 10^{-2}\ \text{m}\cdot\text{K}$
* $\epsilon$: Fractional Emissivity ($\epsilon = 0.004 \times P_v + 0.986$)

---

## 💻 Google Earth Engine (GEE) Implementation & Interactive Demos

<!-- ITEMS 13, 14, 15: GEE INTERACTION VIDEOS -->
<p align="center">
  <video src="video1.mp4" width="31%" controls autoplay loop muted></video>
  <video src="video2.mp4" width="31%" controls autoplay loop muted></video>
  <video src="video3.mp4" width="31%" controls autoplay loop muted></video>
  <br>
  <i>Video 2: Live GEE Code Execution, Buffer Layer Generation, and Interactive Spatial Gradient Navigation.</i>
</p>

```javascript
// Define Center & 150 km Radius Buffer
var delhi = ee.Geometry.Point([77.2090, 28.6139]);
var aoi = delhi.buffer(150000); // 150 km Buffer Area

// Indices Calculation
var ndvi = image.normalizedDifference(['NIR', 'Red']);
var ndbi = image.normalizedDifference(['SWIR', 'NIR']);
var ndwi = image.normalizedDifference(['Green', 'NIR']);

// Emissivity & LST Calculation (Sobrino Engine)
var pv = ndvi.subtract(0.2).divide(0.3).pow(2);
var emissivity = pv.multiply(0.004).add(0.986);
var thermal = image.select('ST_B10').multiply(0.00341802).add(149.0);

var lstCelsius = thermal.divide(
  thermal.multiply(0.00115).divide(1.4388).multiply(emissivity.log()).add(1)
).subtract(273.15);

// Apply Water Mask and Visualization
var lstMasked = lstCelsius.updateMask(ndwi.lt(0.3));
Map.addLayer(lstMasked.clip(aoi), {
  min: 25.0, max: 50.0, 
  palette: ['#0000FF', '#00FFFF', '#FFFF00', '#FF7F00', '#FF0000']
}, 'LST 150km Buffer');
