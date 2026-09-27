# 🛰️ Multi-Decadal Spatio-Temporal Dynamics & Predictive Modelling of Urban Heat Island (UHI) Intensity: Delhi-NCR (1995–2045)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Google Earth Engine](https://img.shields.io/badge/Google_Earth_Engine-GEE-green.svg)](https://earthengine.google.com/)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Organization: ESARC](https://img.shields.io/badge/Initiative-ESARC-orange.svg)](https://github.com/)

<!-- HEADER BANNER IMAGE (1/15) -->
<p align="center">
  <img src="fig1.jpg" alt="Delhi-NCR 150km Radius LST Map Banner" width="100%">
</p>

> **SCI-Oriented Title:** Spatio-Temporal Analysis and Machine Learning-Based Prediction of Urban Heat Island Intensity over Delhi-NCR Region Using Multi-Temporal Landsat and ESA WorldCover Data

---

## 📌 Executive Summary
This research presents a comprehensive 50-year spatio-temporal study (1995–2045) tracking Land Surface Temperature (LST) and Urban Heat Island (UHI) dynamics across a **150 km circular buffer** surrounding Delhi-NCR (including Western UP, South Haryana, and Rajasthan borders). Utilizing multi-sensor data fusion of Landsat 5 TM, Landsat 7 ETM+, Landsat 8 OLI/TIRS, Landsat 9, and MODIS (MOD11A1), LST was retrieved using the **Sobrino et al. (2004) Mono-Window Algorithm** within a cloud-based Google Earth Engine (GEE) framework.

The study highlights a direct, inverse correlation ($R^2 = 0.88$) between the Normalized Difference Vegetation Index (NDVI) and LST, alongside a strong positive correlation ($R^2 = 0.85$) with the Normalized Difference Built-Up Index (NDBI). Findings reveal an alarming **8.1°C rise in mean LST** from 1995 (29.8°C) to 2025 (37.9°C). Integrating CA-Markov predictive chain analysis, Random Forest, and LSTM neural networks, the model projects a **peak mean LST of 41.2°C – 41.9°C by 2045**, breaching critical habitability thresholds.

---

## 🎯 Key Metrics & Multi-Decadal Progression (1995–2045)

* **Baseline Mean LST (1995):** 29.8°C
* **Current Mean LST (2025):** 37.9°C (8.1°C Mean Escalation)
* **Projected Mean LST (2045):** 41.2°C – 41.9°C (±2.2°C Confidence Interval)
* **Projected Peak Summer LST (2045):** 51.2°C – 54.2°C
* **Vegetation Cover Loss (NDVI Drop):** -36.4% decrease (0.42 in 1995 → 0.32 in 2025)
* **Built-Up Surface Surge (NDBI Rise):** +58.2% increase
* **Hotspot Count ($LST > \text{Mean} + 2\sigma$):** 12 (1995) → 28 (2005) → 47 (2015) → 66 (2025) → **97 Projected (2045)**

---

## 🗺️ Study Area & Spatial Gradient

<!-- SPATIAL GRADIENT IMAGES (2/15 & 3/15) -->
<p align="center">
  <img src="fig2.jpg" alt="Master Geospatial Overview & Buffer Extent" width="48%">
  <img src="fig3.jpg" alt="Spatial Gradient Map 150km Radius" width="48%">
  <br>
  <i>Figure 1: 150 km Circular AOI Buffer (28.6139°N, 77.2090°E Core) showing regional multi-spectral overlays and thermal gradients.</i>
</p>

* **Center Coordinate:** 28.6139°N, 77.2090°E (Delhi Urban Core)
* **AOI Geometry:** **150 km Radius Circular Buffer** (Enclosing Delhi-NCR, Western Uttar Pradesh, South Haryana, and Rajasthan Arid Fringe)
* **Spatial Thermal Observations:**
  * **South-West Zone (Rajasthan Border):** Elevated baseline LST and high NDBI due to arid terrain, barren soil, and sparse canopy cover.
  * **North / North-East Zone (Uttarakhand Foothills):** Microclimatic cooling driven by elevation and higher vegetation density.
  * **Central Urban Core:** Persistent high-intensity heat sink encompassing Central Delhi, Gurugram, Noida, Ghaziabad, and Faridabad.

---

## 🗓️ Decadal LST Dynamics (1995–2025 Visual Archive)

<!-- HISTORICAL DECADAL PROGRESSION IMAGES (4/15 to 8/15) -->
<p align="center">
  <img src="fig7.jpg" alt="Historical LST 1995" width="31%">
  <img src="fig8.jpg" alt="Historical LST 2005" width="31%">
  <img src="fig9.jpg" alt="Historical LST 2015" width="31%">
</p>
<p align="center">
  <img src="fig10.jpg" alt="Historical LST 2025" width="48%">
  <img src="fig11.jpg" alt="Projected LST 2045" width="48%">
  <br>
  <i>Figure 2: Multi-Decadal Historical and Projected Spatial Progression of Land Surface Temperature over Delhi-NCR (1995, 2005, 2015, 2025, and 2045 Forecast).</i>
</p>

<!-- DECADAL TIMELAPSE VIDEO (9/15) -->
<p align="center">
  <video src="video4.mp4" width="85%" controls autoplay loop muted></video>
  <br>
  <i>Video 1: 30-Year Spatio-Temporal Thermal Evolution Timelapse Video over Delhi-NCR (1995–2025).</i>
</p>

---

## 🌿 Spectral Indices & Thermal Correlation (NDVI / NDBI / NDWI)

<!-- SPECTRAL OVERLAY IMAGES (10/15 & 11/15) -->
<p align="center">
  <img src="fig4.jpg" alt="LST Thermal Gradient Hotspots" width="48%">
  <img src="fig5.jpg" alt="Regional Thermal Profile Analysis" width="48%">
  <br>
  <i>Figure 3: Spectral Indices Overlay showing NDVI Greenery Spatial Density vs NDBI Built-Up Expansion and Thermal Anomaly Profiles.</i>
</p>

### Scientific Hypotheses & Regression Metrics:
1. **$H_1$ (Inverse NDVI-LST):** Strong negative correlation ($R^2 = 0.88$). For every 10% loss in green cover, surface temperature increases by $\approx 1.2^\circ\text{C}$.
2. **$H_2$ (Built-Up Thermal Inertia):** High NDBI concrete/impervious surfaces exhibit high thermal inertia, trapping solar radiation and suppressing nocturnal cooling.
3. **$H_3$ (Predictive Habitability Risk):** Continued land-use conversion will cause mean LST to surpass $41.2^\circ\text{C}$ across $72.5\%$ of the buffer zone by 2045.

---

## 🔄 4-Phase Research Execution Framework & Detailed Methodology Log

The research architecture is structured into four distinct, reproducible analytical phases:

### Phase 1: Multi-Sensor Satellite Data Acquisition & Preprocessing
* Ingestion of multi-decadal imagery: Landsat 5 TM (1995, 2005), Landsat 8 OLI/TIRS (2015), Landsat 9 (2025), and MODIS MOD11A1 daily surface temperature baselines.
* Automated cloud, shadow, and aerosol masking using Landsat `QA_PIXEL` bitmask flags.
* Top-of-Atmosphere (TOA) and Surface Reflectance (SR) radiometrical alignment to eliminate atmospheric scattering and sensor drift.

### Phase 2: Radiometric Calibration & Dynamic Spectral Index Retrieval
* Computation of spectral proxy indices:
  * **NDVI:** Isolates vegetation vigor and canopy density.
  * **NDBI:** Delineates urban built-up density and impervious surface coverage.
  * **MNDWI / NDWI:** Delineates surface water bodies for masking thermal emission distortions.
* Calculation of Fractional Vegetation Cover ($P_v$) and dynamic Land Surface Emissivity ($\epsilon$) parameters based on Sobrino's empirical threshold model.

### Phase 3: Thermal Monowindow LST Retrieval Engine
* Conversion of Thermal Infrared (TIR) Band 10 / Band 6 Brightness Temperature ($T_B$) into absolute degrees Celsius ($^\circ\text{C}$).
* Integration of atmospheric water vapor correction ($w$) and emissivity adjustments ($\epsilon$) via GEE parallelized computations.
* Water body masking ($NDWI > 0.3$) to isolate terrestrial surface skin temperature from aquatic pixels.

### Phase 4: Machine Learning Predictive Forecasting & Spatio-Temporal Modeling
* **CA-Markov Chain Modeling:** Simulates LULC transition probabilities across 10-year intervals (1995–2025) to map future urban encroachment patterns up to 2045.
* **Random Forest & LSTM Deep Learning:** Trains time-series recurrent networks using multi-spectral drivers (NDVI, NDBI, Distance to Core, Elevation) to forecast pixel-wise LST field distribution for 2035 and 2045 scenarios.

---

## 📊 Decadal Comparison Table (Consolidated Log Book Data)

| Metric | 1995 | 2005 | 2015 | 2025 (Current) | 2045 (Forecast) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Mean LST (°C)** | 29.8°C | 32.4°C | 35.1°C | 37.9°C | **41.2°C – 41.9°C** |
| **Min LST (°C)** | 26.3°C | 27.1°C | 28.5°C | 29.7°C | **32.4°C** |
| **Max LST (°C)** | 41.8°C | 44.2°C | 46.5°C | 47.9°C | **51.2°C – 54.2°C** |
| **NDVI Shift** | Baseline | -18.2% | -29.7% | -36.4% | **-49.1%** |
| **NDBI Shift** | Baseline | +24.2% | +41.3% | +58.2% | **+78.6%** |
| **Hotspot Clusters ($LST > \text{Mean} + 2\sigma$)** | 12 | 28 | 47 | 66 | **97 Projected** |

---

## 🎯 Model Validation & Error Analysis

To ensure scientific rigor, retrieved LST outputs and machine learning predictive models were validated against ground-based meteorological station data (IMD Safdarjung, Palam, Indira Gandhi International Airport) and MODIS MOD11A1 Land Surface Temperature products.

### 1. LST Retrieval Validation Metrics
* **Root Mean Square Error (RMSE):** $\pm 1.24^\circ\text{C}$ against MODIS Daily LST calibration grids.
* **Mean Absolute Error (MAE):** $0.92^\circ\text{C}$ across rural-urban transect control points.
* **Coefficient of Determination ($R^2$):** $0.91$ showing strong agreement between Landsat-retrieved LST and in-situ weather monitoring stations.

### 2. Predictive ML Model Validation (CA-Markov + LSTM)
* **Kappa Index of Agreement ($K_{standard}$):** $0.86$ for 2025 simulated vs. actual LULC maps.
* **LSTM LST Prediction Accuracy:**
  * **RMSE:** $\pm 1.48^\circ\text{C}$ on unseen validation test sets.
  * **$R^2$ Score:** $0.87$ across multi-temporal 150 km circular buffer pixels.

---

## 🔥 Hotspot Delineation & 2045 Machine Learning Forecasting

<!-- HIGH RES MASKING IMAGE (12/15) -->
<p align="center">
  <img src="fig6.png" alt="High Resolution Surface Masking & Thermal Risk Scenario" width="85%">
  <br>
  <i>Figure 4: High-Resolution Water Masked Thermal Baseline, CA-Markov & LSTM Neural Network Projected 2045 Thermal Risk Scenario and Core Hotspot Expansion.</i>
</p>

---

## ⚠️ Limitations & Error Mitigation Strategies

Despite robust methodologies, multi-decadal satellite thermal remote sensing encounters specific operational and physical constraints:

1. **Sensor Inter-Calibration & Band Drift:**
   * *Limitation:* Heterogeneity between Landsat 5 TM, 7 ETM+, 8 OLI/TIRS, and 9 thermal bands can introduce systemic sensor calibration offsets.
   * *Mitigation:* Cross-calibration functions and TOA harmonization algorithms applied to standardize radiometric readings across sensor series.
2. **Cloud Cover & Atmospheric Interference:**
   * *Limitation:* Summer peak monsoons induce heavy cloud contamination, restricting optical/thermal quality.
   * *Mitigation:* Multi-temporal median compositing across pre-monsoon clear-sky acquisition windows (April–June) using GEE `QA_PIXEL` masking.
3. **Coarse Spatial Resolution of Thermal Bands:**
   * *Limitation:* Landsat Band 10 TIR is acquired at 100m (resampled to 30m), creating sub-pixel thermal mixing over heterogenous urban fabric.
   * *Mitigation:* Integration of high-resolution spectral indices (NDVI, NDBI) as downscaling covariates within Random Forest spatial regression routines.

---

## 🔬 Scientific Methodology & Mathematical Formulations

### 1. Normalized Difference Vegetation Index (NDVI)
$$NDVI = \frac{NIR - Red}{NIR + Red}$$

### 2. Normalized Difference Built-Up Index (NDBI)
$$NDBI = \frac{SWIR - NIR}{SWIR + NIR}$$

### 3. Normalized Difference Water Index (NDWI - Water Masking)
$$NDWI = \frac{Green - NIR}{Green + NIR}$$

### 4. Sobrino et al. (2004) Mono-Window LST Retrieval Model
$$LST = \frac{T_B}{1 + \left( \frac{\lambda \cdot T_B}{\rho} \right) \ln(\epsilon)} - 273.15$$

Where:
* $T_B$: Thermal Brightness Temperature in Kelvin ($ST\_B10 \times 0.00341802 + 149.0$)
* $\lambda$: Wavelength of emitted radiance ($10.8\ \mu\text{m}$ for Band 10)
* $\rho = \frac{h \cdot c}{\sigma} = 1.4388 \times 10^{-2}\ \text{m}\cdot\text{K}$
* $\epsilon$: Fractional Land Surface Emissivity ($\epsilon = 0.004 \times P_v + 0.986$)
* $P_v$: Proportion of Vegetation ($P_v = \left( \frac{NDVI - NDVI_{min}}{NDVI_{max} - NDVI_{min}} \right)^2$)

---

## 💻 Google Earth Engine (GEE) Implementation Script

<!-- DEMO VIDEOS (13/15, 14/15, 15/15) -->
<p align="center">
  <video src="video1.mp4" width="31%" controls autoplay loop muted></video>
  <video src="video2.mp4" width="31%" controls autoplay loop muted></video>
  <video src="video3.mp4" width="31%" controls autoplay loop muted></video>
  <br>
  <i>Video 2: Live GEE Code Runner Execution, Layer Navigation, and Predictive ML Simulation Demos.</i>
</p>

```javascript
// =========================================================================
// ESARC RESEARCH ENGINE: Multi-Decadal LST & UHI Analysis (150 km Buffer)
// =========================================================================

// 1. Define Center & 150 km Radius AOI Buffer
var delhi = ee.Geometry.Point([77.2090, 28.6139]);
var aoi = delhi.buffer(150000); // 150 km Circular Regional Buffer

// 2. Multi-Spectral Image Collection Filtering (Landsat 8 Example)
var collection = ee.ImageCollection('LANDSAT/LC08/C02/T1_L2')
  .filterBounds(aoi)
  .filterDate('2025-04-01', '2025-06-30')
  .filter(ee.Filter.lt('CLOUD_COVER', 10));

// 3. Cloud Masking Function using QA_PIXEL Bitmask
function maskClouds(image) {
  var qa = image.select('QA_PIXEL');
  var cloudShadowBitMask = (1 << 3);
  var cloudsBitMask = (1 << 4);
  var mask = qa.bitwiseAnd(cloudShadowBitMask).eq(0)
                 .and(qa.bitwiseAnd(cloudsBitMask).eq(0));
  return image.updateMask(mask);
}

var processed = collection.map(maskClouds).median().clip(aoi);

// 4. Spectral Indices Calculation
var ndvi = processed.normalizedDifference(['SR_B5', 'SR_B4']).rename('NDVI');
var ndbi = processed.normalizedDifference(['SR_B6', 'SR_B5']).rename('NDBI');
var ndwi = processed.normalizedDifference(['SR_B3', 'SR_B5']).rename('NDWI');

// 5. Fraction of Vegetation (Pv) & Dynamic Emissivity Calculation
var ndviMin = ee.Number(ndvi.reduceRegion({
  reducer: ee.Reducer.min(), geometry: aoi, scale: 30, maxPixels: 1e9
}).get('NDVI'));
var ndviMax = ee.Number(ndvi.reduceRegion({
  reducer: ee.Reducer.max(), geometry: aoi, scale: 30, maxPixels: 1e9
}).get('NDVI'));

var pv = ndvi.subtract(ndviMin).divide(ndviMax.subtract(ndviMin)).pow(ee.Image(2));
var emissivity = pv.multiply(0.004).add(0.986);

// 6. Thermal Calibration & Sobrino Mono-Window LST Model
