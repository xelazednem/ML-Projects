# ML-Projects

This repository serves as a centralized collection of my ongoing machine learning projects, focusing on predictive modeling, statistical analysis, and data engineering. Each project is organized into its own directory containing documented source code, raw data documentation, and executive reports.

---

## 🚲 Project 1: Citibike User Classification Study

### Overview
This project utilizes approximately 2.9 million rows of public Citibike data from March 2026 to distinguish between **Annual Members** and **Casual Riders**. By deploying a **Random Forest** and a **Logistic Regression** model, I successfully identified key behavioral triggers that separate these two cohorts.

* **Key Insight:** Annual Members dominate the "Very Short" trip category (<10 minutes), accounting for **90.49%** of ridership in that bucket.
* **Methodology:** Utilized **50/50 Undersampling** to address class imbalance and ensure robust detection of the "Casual" rider class.

### Directory Structure
* **[Citibike Classification/](./Citibike%20Classification/)**
    * **`notebooks/`**: End-to-end Python implementation, including automated data merging with `glob`.
    * **`reports/`**: Executive summary and technical write-up (PDF).
    * **`data/`**: Documentation for primary datasets and supporting spatial files.

---

## Technical Process Note 
Generative AI was utilized as a productivity tool for borough coordinate mapping and data visualization syntax. All statistical interpretation and model tuning are original.

## Sources & References
* **Géron, Aurélien.** *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow*. 2nd ed., O'Reilly Media, 2019.
* **NYC Open Data Portal.** "Citi Bike System Data" & "Borough Boundaries," 2026.
* **Lyft Bikes and Scooters, LLC.** "System Data," Citi Bike NYC, 2026.
*   Gemini 3 Flash
