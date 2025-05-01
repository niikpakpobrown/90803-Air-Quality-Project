# 90803-Air-Quality-Project
A machine learning project focused on predicting air quality in Allegheny County, leveraging historical environmental data to forecast pollutant levels, inform policy decisions, and guide sustainable urban development. The project includes predictive modeling, spatial analysis, and ethical considerations surrounding environmental monitoring.

# Predicting Allegheny County Air Quality

## Overview
This project aims to predict air quality levels in Allegheny County using machine learning techniques. By analyzing historical air quality data, including particulate matter (PM2.5), ozone (O₃), and other environmental factors, the goal is to forecast pollution levels and provide actionable insights to inform policy decisions. These insights will help guide urban planning, improve environmental sustainability, and ensure the health of the community.

## Project Goals
* **Predictive Modeling**: Use machine learning to predict future pollutant levels (e.g., PM2.5, SO₂, NO₂) in the county.
* **Spatial Analysis**: Identify geographic hotspots of poor air quality to guide policy decisions.
* **Ethical Considerations**: Ensure that model predictions account for potential biases in data collection and sensor placement.
* **Policy Impact**: Provide evidence-based recommendations for air quality improvement programs and regulations.

## Dataset
The project uses hourly air quality data collected from monitoring stations across Allegheny County from 2016-present. The dataset includes the following:
* Air quality measurements: PM2.5, PM10, Ozone, NO, NO2, SOx, and more.
* Environmental data: temperature, wind speed, humidity, etc.
* Sensor location data: coordinates and metadata about detection sites.

The [hourly air quality dataset](https://data.wprdc.org/dataset/allegheny-county-air-quality/resource/36fb4629-8003-4acc-a1ca-3302778a530d) can be downloaded from  from the Western Pennsylvania Regional Data Center. They also supply a [data dictionary](https://data.wprdc.org/dataset/allegheny-county-air-quality/resource/01297a0a-4160-41b3-8caf-90f7857ab7bd) for the dataset.

## Structure of Repository
* Descriptive_analytics.ipynb: 
* Data_cleaning.ipynb: 
* ML_models_validation.ipynb: ML models, hyperparameter tuning, validation metrics
* Bias_checking.ipynb: 
