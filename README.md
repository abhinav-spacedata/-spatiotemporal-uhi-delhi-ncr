# 🌍 Multi-Decadal Spatio-Temporal Dynamics & Predictive Modelling of Urban Heat Island (UHI) Intensity: Delhi-NCR (1995–2045)

<p align="center">
  <img src="./figures/fig1.jpg" width="900" alt="fig1.jpg">
</p>

<p align="center">
  <strong>fig1.jpg — Project Overview / Research Cover</strong>
</p>

<p align="center">
  <strong>Earth Observation • Remote Sensing • GIS • Google Earth Engine • Python • Machine Learning • Climate & Urban Analytics</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Research%20Period-1995--2045-blue">
  <img src="https://img.shields.io/badge/Historical-1995--2025-green">
  <img src="https://img.shields.io/badge/Future%20Projection-2025--2045-orange">
  <img src="https://img.shields.io/badge/Platform-Google%20Earth%20Engine-yellow">
  <img src="https://img.shields.io/badge/Language-Python-blue">
  <img src="https://img.shields.io/badge/Domain-Urban%20Climate-red">
  <img src="https://img.shields.io/badge/Organization-ESARC-purple">
</p>

---

# 🛰️ SCI Journal Title

**Spatio-Temporal Analysis and Machine Learning-Based Prediction of Urban Heat Island Intensity over Delhi-NCR Region Using Multi-Temporal Landsat and ESA WorldCover**

---

# 📌 Project Overview

This research investigates the **multi-decadal evolution, spatial distribution, controlling factors, hotspot formation, and future projection of Urban Heat Island (UHI) intensity over Delhi-NCR** using multi-source Earth Observation data, Remote Sensing, GIS, Google Earth Engine, Python, statistical modelling, and Machine Learning.

The study covers:

- **Historical analysis:** 1995–2025
- **Future projection:** 2025–2045
- **Total research horizon:** 1995–2045
- **Study centre:** 28.6139° N, 77.2090° E
- **Approximate AOI:** 150 km buffer
- **Primary variables:** LST, NDVI, NDBI, NDWI, emissivity and land-cover classes
- **Satellite datasets:** Landsat 5/7/8/9 and MODIS
- **Land-cover dataset:** ESA WorldCover
- **Elevation:** SRTM
- **Processing:** Google Earth Engine + Python
- **Machine Learning:** Linear Regression, Random Forest, Gradient Boosting and LSTM
- **Analysis:** Spatial, temporal, statistical, hotspot, correlation, regression and predictive analysis

<p align="center">
  <img src="./figures/fig2.jpg" width="900" alt="fig2.jpg">
</p>

<p align="center">
  <strong>fig2.jpg — Integrated Conceptual Research Framework</strong>
</p>

---

# 🔭 Research Vision

The central objective is to develop an integrated Earth Observation and Machine Learning framework capable of explaining:

**How Delhi-NCR has thermally transformed since 1995, which land-surface and environmental factors are responsible for this transformation, where UHI hotspots are concentrated, and how the thermal environment may evolve toward 2045 under changing urban conditions.**

The project integrates:

**Satellite Observations → Spectral Indices → Land Surface Temperature → UHI Intensity → Spatial Statistics → Machine Learning → Future Projection → Urban Climate Interpretation**

---

# 📊 Project Metadata

| Parameter | Description |
|---|---|
| Project Title | Multi-Decadal Spatio-Temporal Dynamics & Predictive Modelling of Urban Heat Island (UHI) Intensity: Delhi-NCR (1995–2045) |
| SCI Journal Title | Spatio-Temporal Analysis and Machine Learning-Based Prediction of Urban Heat Island Intensity over Delhi-NCR Region Using Multi-Temporal Landsat and ESA WorldCover |
| Organization | ESARC — Earth & Space Applications Research Centre |
| Study Region | Delhi-NCR and surrounding region |
| Study Centre | 28.6139° N, 77.2090° E |
| Approximate AOI | 150 km buffer |
| Historical Period | 1995–2025 |
| Future Projection | 2025–2045 |
| Total Research Period | 1995–2045 |
| Primary Satellite | Landsat 5/7/8/9 |
| Supporting Satellite | MODIS |
| Land Cover | ESA WorldCover |
| DEM | SRTM |
| Processing Platform | Google Earth Engine |
| Programming | Python |
| GIS | QGIS / Google Earth Engine |
| Statistical Analysis | Correlation, Regression, Trend Analysis |
| ML Models | Linear Regression, Random Forest, Gradient Boosting, LSTM |
| Major Output | Historical UHI reconstruction + predictive modelling |
| Research Organisation | ESARC |

---

# 📝 Abstract

Urban Heat Island (UHI) represents one of the major environmental consequences of rapid urbanisation, land-cover transformation, vegetation loss, surface sealing and anthropogenic development.

Delhi-NCR has experienced substantial demographic, infrastructural and land-use transformation during the last several decades. Such changes can modify surface energy balance and consequently influence Land Surface Temperature (LST) and spatial UHI patterns.

This research develops a multi-decadal Earth Observation framework for analysing UHI dynamics across Delhi-NCR from **1995 to 2045**.

The historical component covers **1995–2025** using multi-temporal Landsat observations supported by MODIS, ESA WorldCover, SRTM and additional environmental datasets. LST is derived from satellite thermal observations, while NDVI, NDBI and NDWI are calculated to quantify vegetation, built-up intensity and surface-water conditions.

The study investigates relationships between:

- Urbanisation
- Vegetation
- Surface water
- Land-cover transformation
- Surface emissivity
- Land Surface Temperature
- UHI intensity

Statistical and Machine Learning models are subsequently applied to identify nonlinear relationships and develop predictive frameworks for future thermal conditions.

The future component extends the analysis toward **2045** using scenario-based predictive modelling.

The final research framework is intended to provide a reproducible methodology for:

- Multi-decadal UHI analysis
- Urban thermal hotspot detection
- Land-cover and thermal interaction analysis
- Satellite-based environmental monitoring
- Machine Learning-based prediction
- Urban climate assessment
- Future thermal-risk interpretation

---

# ⚠️ Scientific Declaration

The **1995–2025 period represents historical Earth Observation-based analysis**, while the **2025–2045 period represents modelled future projection/scenario analysis**.

Projected values are not direct satellite observations.

All future estimates must therefore be reported as:

> **Modelled / projected values under defined assumptions and scenarios**

and not as observed future temperatures.

---

# 🌆 Background & Rationale

Rapid urbanisation modifies the physical characteristics of the land surface.

Common urban transformations include:

- Conversion of vegetation into built-up surfaces
- Increase in impervious surfaces
- Reduction in exposed soil and agricultural land
- Fragmentation of water bodies
- Increase in building density
- Road-network expansion
- Industrial development
- Reduction in evapotranspiration
- Modification of surface albedo
- Modification of thermal emissivity
- Increased anthropogenic heat release

These processes influence the surface energy balance.

A simplified conceptual relationship is:

**Urbanisation → Land-Cover Change → Surface Properties → Energy Balance → LST → UHI**

---

# ❓ Research Problem

The research addresses the following broad problem:

> How has the spatial and temporal behaviour of Urban Heat Island intensity changed across Delhi-NCR between 1995 and 2025, what environmental and land-surface factors explain these changes, and how can Machine Learning be used to project possible UHI behaviour toward 2045?

---

# 🧪 Research Hypotheses

### H1 — Urbanisation Hypothesis

Increasing built-up intensity represented by NDBI is associated with increasing LST and UHI intensity.

### H2 — Vegetation Cooling Hypothesis

Increasing vegetation represented by NDVI is associated with lower LST and reduced UHI intensity.

### H3 — Water-Body Cooling Hypothesis

Higher surface-water presence represented by NDWI is associated with comparatively lower LST.

---

# ❓ Research Questions

### RQ1
How has LST changed across Delhi-NCR between 1995 and 2025?

### RQ2
How has UHI intensity changed spatially and temporally?

### RQ3
Which areas represent persistent thermal hotspots?

### RQ4
How strongly is NDVI related to LST?

### RQ5
How strongly is NDBI related to LST?

### RQ6
How does NDWI influence local thermal conditions?

### RQ7
How has land-cover transformation contributed to UHI development?

### RQ8
Which Machine Learning model provides the most reliable predictive performance under the selected validation framework?

### RQ9
What thermal conditions may develop toward 2045 under the defined scenarios?

### RQ10
How can Earth Observation-based UHI information support future urban environmental planning?

---

# 🎯 Research Objectives

1. Develop a consistent multi-decadal satellite-based UHI dataset.
2. Estimate historical LST across Delhi-NCR.
3. Derive NDVI, NDBI and NDWI.
4. Analyse land-cover transformation.
5. Quantify relationships between land-cover variables and LST.
6. Identify spatial UHI hotspots.
7. Analyse long-term thermal trends.
8. Develop statistical prediction models.
9. Develop Machine Learning prediction models.
10. Validate model performance.
11. Estimate future thermal behaviour toward 2045.
12. Develop reproducible research workflows.
13. Produce publication-quality figures and maps.
14. Establish a framework suitable for future updates.

---

# 🗺️ Study Area

<p align="center">
  <img src="./figures/fig3.jpg" width="900" alt="fig3.jpg">
</p>

<p align="center">
  <strong>fig3.jpg — Delhi-NCR Study Area and 150 km AOI</strong>
</p>

The research focuses on the Delhi-NCR region and surrounding areas using an approximate **150 km buffer** around the study centre:

**28.6139° N, 77.2090° E**

The larger buffer is used to provide regional environmental context and enable comparison between:

- Dense urban areas
- Peri-urban zones
- Agricultural regions
- Forest/vegetated areas
- Water bodies
- Industrial areas
- Rural surroundings

---

# 🛰️ Data Sources

<p align="center">
  <img src="./figures/fig4.jpg" width="900" alt="fig4.jpg">
</p>

<p align="center">
  <strong>fig4.jpg — Multi-Temporal Satellite Data Strategy</strong>
</p>

| Dataset | Application |
|---|---|
| Landsat 5 TM | Historical LST and spectral analysis |
| Landsat 7 ETM+ | Historical LST and spectral analysis |
| Landsat 8 OLI/TIRS | LST and spectral analysis |
| Landsat 9 OLI-2/TIRS-2 | Recent LST and spectral analysis |
| MODIS | Temporal thermal support and validation |
| ESA WorldCover | Land-cover classification |
| SRTM | Elevation and terrain variables |
| Administrative Boundaries | Spatial reporting |
| Meteorological Data | Validation where available |
| Additional EO datasets | Supporting environmental analysis |

---

# 🌡️ Land Surface Temperature Methodology

The LST processing chain generally follows:

**Thermal Digital Number / Radiance → Brightness Temperature → NDVI → Vegetation Proportion → Emissivity → Land Surface Temperature**

---

# 📅 Historical Analysis: 1995–2025

---

# 🌡️ 1995 Historical LST

<p align="center">
  <img src="./figures/fig5.jpg" width="900" alt="fig5.jpg">
</p>

<p align="center">
  <strong>fig5.jpg — 1995 Historical LST</strong>
</p>

---

# 🌡️ 2005 Historical LST

<p align="center">
  <img src="./figures/fig6.jpg" width="900" alt="fig6.jpg">
</p>

<p align="center">
  <strong>fig6.jpg — 2005 Historical LST</strong>
</p>

---

# 🌡️ 2015 Historical LST

<p align="center">
  <img src="./figures/fig7.jpg" width="900" alt="fig7.jpg">
</p>

<p align="center">
  <strong>fig7.jpg — 2015 Historical LST</strong>
</p>

---

# 🌡️ 2025 Historical LST

<p align="center">
  <img src="./figures/fig8.jpg" width="900" alt="fig8.jpg">
</p>

<p align="center">
  <strong>fig8.jpg — 2025 Historical LST</strong>
</p>

---

# 🔥 UHI Hotspot Detection

<p align="center">
  <img src="./figures/fig9.jpg" width="900" alt="fig9.jpg">
</p>

<p align="center">
  <strong>fig9.jpg — UHI Hotspot Detection</strong>
</p>

---

# 🤖 Machine Learning Framework & Predictive Modelling

<p align="center">
  <img src="./figures/fig10.jpg" width="900" alt="fig10.jpg">
</p>

<p align="center">
  <strong>fig10.jpg — Machine Learning / Predictive Modelling</strong>
</p>

---

# 🔮 Future Projection Framework: 2025–2045

<p align="center">
  <img src="./figures/fig11.jpg" width="900" alt="fig11.jpg">
</p>

<p align="center">
  <strong>fig11.jpg — 2045 Future UHI Projection</strong>
</p>

---

# 🎬 Research Demonstrations & Video Embeddings

## 🎬 video1.mp4 — Google Earth Engine Processing Demonstration
[▶️ Open video1.mp4](./videos/video1.mp4)

## 🎬 video2.mp4 — LST Processing Demonstration
[▶️ Open video2.mp4](./videos/video2.mp4)

## 🎬 video3.mp4 — Python & Machine Learning Demonstration
[▶️ Open video3.mp4](./videos/video3.mp4)

## 🎬 video4.mp4 — Final Integrated Research Demonstration
[▶️ Open video4.mp4](./videos/video4.mp4)

---

# 📁 Repository Structure

<pre><code>
UHI-Delhi-NCR-1995-2045/
│
├── README.md
│
├── figures/
│   ├── fig1.jpg
│   ├── fig2.jpg
│   ├── fig3.jpg
│   ├── fig4.jpg
│   ├── fig5.jpg
│   ├── fig6.jpg
│   ├── fig7.jpg
│   ├── fig8.jpg
│   ├── fig9.jpg
│   ├── fig10.jpg
│   └── fig11.jpg
│
├── videos/
│   ├── video1.mp4
│   ├── video2.mp4
│   ├── video3.mp4
│   └── video4.mp4
│
├── gee/
├── python/
├── data/
├── results/
└── documentation/
</code></pre>

---

# 🛰️ Research Organisation

**ESARC — Earth & Space Applications Research Centre**

---

# 📖 Citation

```bibtex
Chaudhari, A. (2026). Multi-Decadal Spatio-Temporal Dynamics & Predictive Modelling of Urban Heat Island (UHI) Intensity: Delhi-NCR (1995–2045). ESARC.
