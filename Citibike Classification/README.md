# ML-Projects

## Citibike User Classification Study

### Overview
This project utilizes approximately 2.9 million rows of public Citibike data from March 2026 to distinguish between **Annual Members** and **Casual Riders**. By deploying a **Random Forest** and a **Logistic Regression** model, I successfully identified key behavioral triggers that separate these two groups

* **Key Insight:** Annual Members dominate the "Very Short" trip category (<10 minutes), accounting for **90.49%** of ridership in that bucket.
* **Methodology:** Utilized **50/50 Undersampling** to address class imbalance and ensure robust detection of the "Casual" rider class.

### Objective 
The primary objective was to determine if user status (Member vs. Casual) could be accurately predicted using existing data and engineered features, such as duration buckets and cross-borough trip indicators.

### Data Acquisition 
Citi Bike trip data was sourced from the [Official Citi Bike System Data Page](https://citibikenyc.com/system-data). The analysis specifically utilized data from **March 2026**.

### Full Analysis & Documentation
* **Technical Write-up:** For results, methods, and statistical methodology, please review the **[Citibike Classification - Write Up.pdf](./Citibike%20Classification%20-%20Write%20Up.pdf)**
* **Source Code:** Data cleaning, merging, and modeling scripts are located in the **`notebooks/`** directory.

### Technical Process Note 
Generative AI was utilized as a productivity tool for borough coordinate mapping and data visualization syntax. All statistical interpretation, model tuning strategy, and analysis are original.

### Sources
* **Géron, Aurélien.** *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow*. 2nd ed., O'Reilly Media, 2019.
* **NYC Open Data Portal.** "Citi Bike System Data" & "Borough Boundaries," 2026.
* **Lyft Bikes and Scooters, LLC.** "System Data," Citi Bike NYC, 2026.
*   Gemini 3 Flash

