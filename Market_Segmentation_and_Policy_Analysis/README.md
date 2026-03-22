# 📊 Market Segmentation & Policy Analysis: Predictive Insights for Tourism and Public Health

This repository contains a comprehensive data science portfolio consisting of two distinct, independent studies developed for a single project. While presented together, each study utilizes its own unique dataset and analytical pipeline to address specific challenges in **Market Segmentation** (Tourism) and **Public Health Policy** (Illicit Drug Use).

---

## 🛠️ Phase 1: Methodology & Data Synthesis
Both projects followed a systematic data development process to ensure high-quality foundations for analysis.

1.  **Instrument Design:** Two independent, custom-designed questionnaires were developed to capture complex variables specific to each domain.
2.  **Validation:** Both instruments were validated through initial sampling, receiving 20–25 valid responses each to ensure response integrity.
3.  **Data Augmentation (SPSS & ChatGPT):** To enable advanced machine learning, the validated real-world distributions were used to synthesize robust datasets of 200–250 responses per study using **SPSS** and **LLM-assisted synthesis (ChatGPT)**. This demonstrates a creative approach to generating statistically viable data for modeling.
4.  **Processing Pipeline:** Each dataset was cleaned and structured using a dedicated Python pipeline (`clean.ipynb`) to ensure data quality.

---

## 📊 Phase 2: Analytical Depth & Inferential Statistics
Moving beyond basic descriptive charts, this work employs thorough **Inferential Statistics** to identify true drivers of behavior in both domains.

*   **Significance Testing:** Using **One-Way ANOVA** and **T-Tests**, we proved which demographic factors (like employment or education) actually drive behavior and spending, providing a evidence-based foundation for recommendations.
*   **Correlation Analysis:** Multi-variable relationships were mapped to understand how age, income, and initiation timing interact.

![Statistical Depth](./Pictures_in_Readme/Figure%202.7_ANOVA-Weekly%20Spend%20by%20Education%20Level.png)
*Visualizing statistical significance: ANOVA results showing spending drivers in the Public Health dataset.*

---

## 🔬 Phase 3: Machine Learning & Predictive Modeling
The technical analysis involved building classification models to predict traveler preferences and help-seeking interest.

### Model Selection & Strategy
To ensure the most reliable results, we compared **Random Forest, Logistic Regression, Decision Tree, and Naive Bayes** for both projects:
*   **Comparison Strategy:** We used **10-fold Cross-Validation** to find the most stable model for each unique dataset.
*   **Random Forest:** Selected as the primary model for its ability to handle non-linear survey data and provide thorough **Feature Importance** rankings.

![Model Comparison](./Pictures_in_Readme/Figure%201.17_Model%20Performance%20Comparison.png)

### Extracting "The Why"
Machine Learning was used for **discovery** across both studies. By analyzing feature importance, we identified the true keys to behavior:
*   **Tourism:** Age and Customization are the primary drivers for the "Adventure" segment.
*   **Public Health:** Current age and age of initiation are the most critical predictors for help-seeking interest.

![Feature Importance](./Pictures_in_Readme/Figure%201.18_Top%2010%20Feature%20Importances%20for%20Predicting%20Adventure%20Travel%20Preference_Random%20Forest.png)

---

## 📄 Phase 4: Professional Deliverables & Reports
The final results of these two independent studies are distilled into professional reports located in the [`/Reports`](./Reports) directory:

1.  [**Executive Report**](./Reports/Executive_Report.pdf): A business and policy-focused document providing high-level findings and actionable strategic recommendations for both domains.
2.  [**Statistical Analysis Report**](./Reports/Statistical_analysis_report.pdf): A comprehensive technical document covering the thorough methodology, model performance metrics, and detailed statistical tables for both projects.

---

## 📂 Repository Structure
*   `Analysis.ipynb`: The primary technical showcase (Full ML & Statistical Pipeline for both datasets).
*   `clean.ipynb`: The data preprocessing and cleaning stage.
*   `Reports/`: Professional PDF deliverables for stakeholders.
*   `*.csv`: Structured datasets for local reproduction.
*   `Pictures_in_Readme/`: Visual assets used in this documentation.

---
*Created by [TaimanJoker](https://github.com/TaimanJoker) - Data Science Portfolio*
