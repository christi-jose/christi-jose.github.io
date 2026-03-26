---
layout: page
title: Land Use Regression & Spatial Modeling
description: Developing predictive models for urban pollutant distributions
img: assets/img/spatial-analysis.jpg
importance: 2
category: postdoc
---

## Overview
**Duration:** May 2024 – Present  
**Location:** Greater Toronto Area (GTA), Ontario  
**Organization:** SOCAAR, University of Toronto

Land Use Regression (LUR) is a statistical technique relating ambient air pollutant concentrations to surrounding land use characteristics.

## Methodology

### Data Foundation
- Field measurements from 40+ monitoring sites across Toronto
- High-resolution AirSENCE real-time sensor data
- Mobile measurements using electric vehicle campaigns
- Satellite data (impervious surface, vegetation, industrial facilities)

### GIS Predictor Development
Using Python (geopandas) and QGIS to generate spatial layers:
- Traffic density and proximity to major roads
- Land use classification (residential, commercial, industrial, green space)
- Urban morphology (building height, street width, intersection density)
- Emission sources (power plants, waste facilities, ports)

### Model Building
- Linear regression for base LUR model
- Machine learning (scikit-learn) for non-linear relationships
- Cross-validation to prevent overfitting
- Spatial autocorrelation accounting

## Applications

### Urban Air Quality Assessment
- Created detailed maps of PM₂.₅, PM₁₀, NO₂, NOₓ distributions
- Identified high-risk areas for targeted pollution reduction
- Support for municipal air quality management

### Exposure Assessment
- Population exposure analysis
- Vulnerable population targeting
- Health impact modeling

### Policy Support
- Evidence for traffic emission reduction strategies
- Optimal monitoring network expansion locations
- Evaluation of emission control effectiveness

## Impact
LUR models enable policy makers to focus pollution reduction efforts where populations are most exposed, supporting urban environmental justice and climate action.
