# Analysis & Modeling Notebooks

This directory contains the end-to-end technical implementation of the Citibike User Classification project.

## Notebook Overview

### 1. Master_csv_citibike.ipynb
**Purpose:** Data Engineering, Ingestion & Automated Merging
* **Dynamic File Handling:** Utilizes the `glob` library to programmatically identify and ingest multiple raw CSV datasets from the local directory.
* **Large-Scale Integration:** Performs a successful union of three separate raw datasets into a single `master_df`, managing approximately 2.9 million total observations.
* **Output:** Generates the consolidated master dataset used for subsequent feature engineering and modeling.

### 2. Citibike Classification Analysis (Final).ipynb
**Purpose:** Statistical Modeling & Evaluation
* **Spatial Engineering:** Joins trip coordinates with the `Borough_Boundaries` dataset to enable borough-level behavioral analysis.
* **Algorithms:** Implements **Logistic Regression** (for generalization) and **Random Forest** (for complexity).
* **Sampling Strategy:** Deploys **50/50 Undersampling** to mitigate class imbalance between Annual Members and Casual riders.
* **Visualization:** Generates behavioral insights, including the analysis of user concentration by trip duration.

## Technical Stack
* **Language:** Python
* **Libraries:** `pandas`, `glob`, `NumPy`, `matplotlib`, `seaborn`, `scikit-learn`

