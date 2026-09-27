# ============================================================
# DELHI-NCR UHI RESEARCH PROJECT
# SINGLE-COPY GITHUB README GENERATOR
# ============================================================
#
# Run this Python file once.
# It will create:
#
#     README.md
#
# Recommended repository structure:
#
# Delhi-NCR-UHI-1995-2045/
# ├── README.md
# ├── figures/
# │   ├── fig1.jpg
# │   ├── fig2.jpg
# │   ├── fig3.jpg
# │   ├── fig4.jpg
# │   ├── fig5.jpg
# │   ├── fig6.png
# │   ├── fig7.jpg
# │   ├── fig8.jpg
# │   ├── fig9.jpg
# │   ├── fig10.jpg
# │   └── fig11.jpg
# ├── videos/
# │   ├── video1.mp4
# │   ├── video2.mp4
# │   ├── video3.mp4
# │   └── video4.mp4
# └── code/
#
# ============================================================

from pathlib import Path


README = r'''# 🛰️ Multi-Decadal Spatio-Temporal Dynamics & Predictive Modelling of Urban Heat Island (UHI) Intensity

<p align="center">

<img src="figures/fig1.jpg"
     alt="Delhi-NCR 150 km Radius LST Map"
     width="100%">

</p>

<h1 align="center">
Multi-Decadal Spatio-Temporal Dynamics and Predictive Modelling
of Urban Heat Island (UHI) Intensity
</h1>

<h3 align="center">
A Case Study of Delhi-NCR (1995–2045)
</h3>

<p align="center">

<b>SCI-JOURNAL TITLE</b><br>

<i>
Spatio-Temporal Analysis and Machine Learning-Based Prediction
of Urban Heat Island Intensity over Delhi-NCR Region Using
Multi-Temporal Landsat and ESA WorldCover Data
</i>

</p>

<p align="center">

![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![GEE](https://img.shields.io/badge/Google%20Earth%20Engine-GEE-green.svg)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)
![Remote Sensing](https://img.shields.io/badge/Domain-Remote%20Sensing-orange.svg)
![Urban Climate](https://img.shields.io/badge/Research-Urban%20Climate-red.svg)

</p>

---

# 📑 TABLE OF CONTENTS

1. [Project Metadata](#-project-metadata)
2. [Abstract / Executive Summary](#-abstract--executive-summary)
3. [Declaration](#1-declaration)
4. [Background and Rationale](#2-background-and-rationale)
5. [Research Problem Statement](#3-research-problem-statement)
6. [Scientific Hypotheses](#4-scientific-hypotheses)
7. [Research Objectives & Questions](#5-research-objectives--questions)
8. [Study Area & Geographic Boundary](#6-study-area--geographic-boundary)
9. [Data Sources & Sensor Specifications](#7-data-sources--sensor-specifications)
10. [Methodology & Conceptual Framework](#8-methodology--conceptual-framework)
11. [Mathematical Formulation & Core Science](#9-mathematical-formulation--core-science)
12. [Four-Phase Execution & Research Log](#10-four-phase-execution--research-log)
13. [Google Earth Engine Implementation](#11-google-earth-engine-implementation)
14. [Results and Statistical Analysis](#12-results-and-statistical-analysis)
15. [Model Validation & Error Analysis](#13-model-validation--error-analysis)
16. [Limitations & Error Mitigation](#14-limitations--error-mitigation)
17. [Evidence-Based Mitigation Strategies](#15-evidence-based-mitigation-strategies)
18. [Conclusion & Future Scope](#16-conclusion--future-scope)
19. [References](#17-references)
20. [Repository Structure](#-repository-structure)
21. [Reproducibility Note](#-reproducibility-note)

---

# 🧾 PROJECT METADATA

| Parameter | Details |
|---|---|
| **Project Title** | Multi-Decadal Spatio-Temporal Dynamics and Predictive Modelling of Urban Heat Island (UHI) Intensity Using Multi-Sensor Data Fusion: A Case Study of Delhi-NCR (1995–2045) |
| **SCI-Journal Title** | Spatio-Temporal Analysis and Machine Learning-Based Prediction of Urban Heat Island Intensity over Delhi-NCR Region Using Multi-Temporal Landsat and ESA WorldCover Data |
| **Principal Investigator** | **Abhinav Chaudhari** |
| **Affiliation** | Earth-Space Analytical Research Center (ESARC), India |
| **MSME Registration** | UDYAM-UP-56-0148083 |
| **NIC Code** | 72100 |
| **Domain** | Remote Sensing, Geospatial Science, Urban Climate, Geospatial Analytics |
| **Technical Stack** | Google Earth Engine (GEE), Landsat 5/7/8/9, MODIS, ESA WorldCover, SRTM DEM, Sobrino Mono-Window Algorithm, CA-Markov, Random Forest, LSTM |
| **Guided By** | To be assigned — MIT / NASA / ESA / IIRS-ISRO / IISc Collaboration |

---

# 🧠 ABSTRACT / EXECUTIVE SUMMARY

This research presents a comprehensive multi-decadal analysis of the Urban Heat Island (UHI) effect over the Delhi-NCR region spanning a 50-year timeline (1995–2045).

A multi-sensor data fusion framework is implemented using Google Earth Engine (GEE). Land Surface Temperature (LST) is retrieved using the **Sobrino et al. (2004) Mono-Window algorithm** as the primary processing engine and cross-checked against the NDVI-Threshold emissivity method and MODIS/IMD datasets.

The study reports:

- **NDVI–LST inverse correlation:** R² = 0.88
- **NDBI–LST positive correlation:** R² = 0.85
- **Mean LST in 1995:** 29.8°C
- **Mean LST in 2025:** 37.9°C
- **Reported increase:** 8.1°C
- **2045 forecast mean LST:** 41.2°C–41.9°C
- **Moran's I:** 0.72
- **Random Forest R²:** 0.87
- **LSTM R²:** 0.91

The predictive framework combines **CA-Markov, Random Forest and LSTM** approaches to investigate possible future thermal-risk trajectories under Business-As-Usual conditions.

---

# 1. DECLARATION

I hereby declare that this research work is my original contribution based on satellite remote sensing and Google Earth Engine analysis.

All datasets and scientific methods have been properly acknowledged.

This work has not been submitted elsewhere for any academic degree or certification.

**Date:** ____________________

**Signature:** ____________________

**Principal Investigator:**  
**Abhinav Chaudhari**

---

# 2. BACKGROUND AND RATIONALE

Rapid urbanization and replacement of natural surfaces with impervious structures in Delhi-NCR have fundamentally altered the **Surface Energy Balance (SEB)**.

Beyond global warming, local thermal hotspots are intensifying due to:

- Anthropogenic heat retention
- High built-up density
- Reduction in vegetation
- Impervious surface expansion
- Changes in surface moisture
- Reduced evaporative cooling
- Modification of local surface energy exchange

While prior studies frequently rely on limited temporal snapshots, this research integrates:

> **1995–2025 historical observation period + 2025–2045 predictive simulation**

This creates a multi-decadal analytical framework for examining relationships among:

**Vegetation → Built-up expansion → Surface temperature → Thermal hotspots → Future thermal risk**

---

# 3. RESEARCH PROBLEM STATEMENT

Despite extensive literature on Urban Heat Island phenomena, there remains a critical need for:

### 3.1 Cloud-Based and Reproducible Analysis

A scalable and reproducible Google Earth Engine methodology capable of processing multi-decadal satellite observations.

### 3.2 Integrated Environmental Indicators

Integrated assessment of:

- NDVI
- NDBI
- NDWI
- LST
- DEM
- Land-use / land-cover transitions

### 3.3 Quantitative Relationship Modelling

Statistical modelling of:

- NDVI versus LST
- NDBI versus LST
- Temporal LST trends
- Spatial clustering

### 3.4 Long-Term Forecasting

Prediction of future thermal-risk conditions toward 2045 using:

- CA-Markov
- Random Forest
- LSTM

### 3.5 Error Mitigation

Specific attention to:

- Mixed-pixel bias
- Cloud contamination
- Landsat 7 SLC-off gaps
- Atmospheric noise
- Water-body thermal bias
- Circular boundary masking artifacts

---

# 4. SCIENTIFIC HYPOTHESES

## H₁ — Inverse NDVI-LST Relationship

A strong negative relationship exists between vegetation abundance and surface temperature:

\[
R^2 > 0.85
\]

The working hypothesis proposes that vegetation loss is associated with increasing LST, with the project hypothesis estimating approximately:

\[
10\% \text{ vegetation loss}
\rightarrow
\approx 1.2^\circ C \text{ increase in LST}
\]

---

## H₂ — NDBI-LST & Heat Storage Relationship

High-NDBI areas are expected to exhibit:

- Higher thermal radiance
- Greater heat storage
- Reduced evaporative cooling
- Increased thermal inertia
- Reduced nocturnal cooling

These conditions contribute to the development of urban **"Heat Traps"**.

---

## H₃ — Predictive Thermal Risk

Under Business-As-Usual (BAU) trajectories, the project hypothesis proposes that:

\[
LST_{2045} > 41.2^\circ C
\]

for the mean thermal condition of the analysed study region, with some urban zones potentially experiencing considerably higher surface temperatures.

---

# 5. RESEARCH OBJECTIVES & QUESTIONS

## 5.1 Research Questions

1. How has UHI intensity in Delhi-NCR evolved during 1995–2025?
2. What is the statistical relationship between NDVI/NDBI and LST?
3. Which urban zones exhibit persistent thermal hotspots?
4. Can a reproducible GEE workflow reliably simulate 2045 thermal-risk maps?
5. How can multi-sensor satellite data improve temporal and spatial interpretation?
6. What mitigation strategies can be derived from spatial thermal-risk patterns?

---

## 5.2 Research Objectives

### Objective 1
Derive multi-year NDVI and NDBI maps from Landsat imagery covering 1995–2025.

### Objective 2
Retrieve LST using thermal-band processing and the Sobrino Mono-Window approach.

### Objective 3
Map urban thermal hotspots and establish pixel-level regression models.

### Objective 4
Execute predictive analytics toward 2045 using:

- CA-Markov
- Random Forest
- LSTM

### Objective 5
Develop policy-ready urban heat mitigation strategies.

---

# 6. STUDY AREA & GEOGRAPHIC BOUNDARY

## 6.1 Geographic Reference

**Central Coordinates:**

\[
28.6139^\circ N,\quad 77.2090^\circ E
\]

Reference point:

**Delhi Core**

## 6.2 Spatial Extent

A circular buffer of:

\[
150\,km
\]

radius is used around the Delhi reference point.

The study geometry covers the Delhi-NCR core and surrounding areas extending toward:

- Western Uttar Pradesh
- Southern Haryana
- Rajasthan border region
- Uttarakhand foothill zone

---

## 6.3 Master Geospatial Overview

<p align="center">

<img src="figures/fig2.jpg"
     alt="Master Geospatial Overview and 150 km Buffer"
     width="49%">

<img src="figures/fig3.jpg"
     alt="Spatial Gradient Map 150 km Radius"
     width="49%">

</p>

**Figure 1.** Master Geospatial Overview and Spatial Thermal Gradient Map across the 150 km circular buffer.

---

## 6.4 Spatial Interpretation

### South-West Zone

The Rajasthan-border region shows comparatively higher LST and NDBI signatures in the project observations, associated with:

- Arid/semi-arid terrain
- Lower vegetation cover
- Higher exposed surface fraction

### North / North-East Zone

The Uttarakhand foothill direction shows cooler LST patterns associated with:

- Dense vegetation
- Higher elevation
- Different surface-moisture conditions
- Terrain effects

### Central / Eastern Core

Higher thermal stress is observed around major urban centres including:

- Delhi
- Noida
- Gurugram
- Ghaziabad

---

# 7. DATA SOURCES & SENSOR SPECIFICATIONS

## 7.1 Multi-Sensor Dataset

| Dataset | Source / Sensor | Resolution | Time Period | Purpose / Role |
|---|---|---:|---|---|
| Landsat 5 TM | USGS | 30 m; thermal 120 m | 1995–2011 | Baseline LST & spectral indices |
| Landsat 7 ETM+ | USGS | 30 m; thermal 60 m | 1999–2021 | Multi-decadal temporal series |
| Landsat 8 OLI/TIRS | USGS | 30 m; thermal 100 m | 2013–Present | Current LST, NDVI, NDBI |
| Landsat 9 TIRS-2 | USGS | 30 m; thermal 100 m | 2021–Present | High-precision thermal observation |
| MODIS MOD11A1/A2 | NASA | 1 km | 2000+ | Temporal cross-validation |
| ESA WorldCover | ESA | 10 m | 2020/2021 | Built-up & LULC validation |
| SRTM DEM | NASA | 30 m | Static | Elevation & terrain correction |
| Administrative Boundaries | GADM / Vector | Vector | Static | Spatial clipping |

---

## 7.2 Spectral Band Specifications

| Spectral Variable | Band | Approximate Range | Primary Use |
|---|---|---|---|
| Red | B3/B4 | 0.63–0.69 μm | Chlorophyll absorption |
| NIR | B4/B5 | 0.77–0.90 μm | Vegetation reflectance |
| SWIR | B5/B6 | 1.55–1.75 μm | Impervious/built-up mapping |
| Thermal | B6/B10 | ~10.8 μm | Thermal radiance / LST |

---

# 8. METHODOLOGY & CONCEPTUAL FRAMEWORK

## 8.1 Spectral Analysis

<p align="center">

<img src="figures/fig4.jpg"
     alt="LST Thermal Gradient Hotspots"
     width="49%">

<img src="figures/fig5.jpg"
     alt="Regional Thermal Profile Analysis"
     width="49%">

</p>

**Figure 2.** Spectral-index overlays showing vegetation density, built-up expansion and thermal gradients.

---

## 8.2 Spatio-Temporal Animation

<p align="center">

<video src="videos/video2.mp4"
       width="85%"
       controls
       loop
       muted>
</video>

<br>

<a href="videos/video2.mp4">
▶ Open / View Video 1 — Spatio-Temporal Dynamics Animation
</a>

</p>

---

## 8.3 Processing Workflow

```text
┌──────────────────────────────────────────────────────────┐
│ Satellite Data Acquisition                               │
│ Landsat 5/7/8/9 + MODIS                                  │
└────────────────────────────┬─────────────────────────────┘
                             ↓
┌──────────────────────────────────────────────────────────┐
│ Preprocessing                                             │
│ Cloud Masking + Radiometric Calibration + SLC-Off Fix    │
└────────────────────────────┬─────────────────────────────┘
                             ↓
┌──────────────────────────────────────────────────────────┐
│ Spectral Index Extraction                                │
│ NDVI + NDBI + NDWI                                       │
└────────────────────────────┬─────────────────────────────┘
                             ↓
┌──────────────────────────────────────────────────────────┐
│ LST Retrieval                                             │
│ Brightness Temperature + Emissivity + Sobrino Algorithm │
└────────────────────────────┬─────────────────────────────┘
                             ↓
┌──────────────────────────────────────────────────────────┐
│ Validation                                                │
│ MODIS + NDVI-Threshold Emissivity + IMD                  │
└────────────────────────────┬─────────────────────────────┘
                             ↓
┌──────────────────────────────────────────────────────────┐
│ Statistical Analysis                                     │
│ Regression + Trend Analysis + Moran's I                  │
└────────────────────────────┬─────────────────────────────┘
                             ↓
┌──────────────────────────────────────────────────────────┐
│ Predictive Analytics                                     │
│ CA-Markov + Random Forest + LSTM                          │
└────────────────────────────┬─────────────────────────────┘
                             ↓
┌──────────────────────────────────────────────────────────┐
│ 2045 Thermal Risk Scenario                                │
└────────────────────────────┬─────────────────────────────┘
                             ↓
┌──────────────────────────────────────────────────────────┐
│ Urban Heat Mitigation Framework                           │
└──────────────────────────────────────────────────────────┘
