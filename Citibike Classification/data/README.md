# Data Documentation

This directory contains the supporting spatial data used for feature engineering, along with documentation for acquiring the primary trip datasets.

## 1. Primary Citibike Trip Data
Due to GitHub's file size limitations (files >100MB), the raw trip data used for this analysis is not hosted in this repository.

* **Dataset:** Citibike Trip Data (March 2026)
* **Scale:** ~2.9 Million Observations
* **Source:** [Official Citi Bike System Data](https://citibikenyc.com/system-data)
* **Access:** Data was accessed via the NYC Open Data Portal under the "Citi Bike System Data" dataset.

## 2. Supporting Datasets
The following files are included in this directory:

* **Borough_Boundaries_20260421.csv:** 
  - **Source:** [NYC Open Data - Borough Boundaries](https://data.cityofnewyork.us/City-Government/Borough-Boundaries/gthc-hcne/about_data).
  - **Usage:** This file was merged with trip start/end coordinates to engineer the `start station’ and ‘end station’ feature, identifying trips that traveled between different NYC boroughs.

## 3. Data Privacy & Processing
All data utilized is publicly available and anonymized by the provider. The processing scripts found in the `../notebooks/` directory detail the cleaning steps, including the removal of trips under 60 seconds (potential false starts) and the implementation of a **50/50 Undersampling** strategy to balance the classes for modeling.

