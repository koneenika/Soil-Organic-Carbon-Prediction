Soil Organic Carbon Prediction (MODIS + WoSIS)

This project uses MODIS vegetation indices and WoSIS soil data in Google Earth Engine to predict Soil Organic Carbon (SOC) across a selected region.

Overview

Uses MODIS NDVI & EVI (2000–2020) annual means as predictors.

Trains a Random Forest regression model with WoSIS soil point data.

Generates a continuous SOC prediction map and evaluates performance using scatter plots for training and validation sets.

Visualizes results with a color-coded SOC map and legend.

Data Sources

MODIS MYD13Q1: NDVI & EVI (250m, 16-day composites)

WoSIS: Soil Organic Carbon (%) measurements

Workflow

Load and preprocess MODIS NDVI & EVI.

Filter and split WoSIS points into training and validation sets.

Train Random Forest model to predict SOC.

Create prediction map and assess accuracy.

Visualize and optionally export results.

Outputs

SOC prediction map for the study area.

Scatter plots showing model fit (R² values).

Optional GeoTIFF export for further analysis.
