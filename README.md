# Health & Lifestyle Data Analysis (with Custom Health Indicator)

This project explores a dataset containing information about individuals' health, lifestyle, and habits. The main goal is to analyze how different factors (such as stress, sleep, physical activity, diet, etc.) relate to overall health — and to define a custom feature that indicates whether a person can be considered *"healthy"* or not.

Kaggle Link: https://www.kaggle.com/code/viktoriiakazniienko/health-analysis-eda-with-custom-feature

## Project Objectives

1. Analyze relationships between key features

   * Explore correlations between stress, sleep duration, physical activity, BMI, diet, and chronic diseases.
   * Identify patterns and connections that might help explain variations in perceived or actual health.

2. **Create a custom Healthy feature**

   * Construct a new binary indicator (Healthy) based on multiple lifestyle factors such as sleep, stress, BMI, alcohol, smoking, chronic disease presence, and physical activity.
   * Use this feature as a simplified proxy for overall health status.

   * Determine whether the dataset has enough clean, structured data.
Visualize data and draw insightsts**

   * Use clear visualizations to support analysis.
   * Highlight which features most strongly relate to the defined Healthy status.

---

## Dataset Overview

| Column                                                      | Description                                                                            |
| ----------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| Age, Gender                                             | Demographic information                                                                |
| Sleep_Hours, Stress_Level,Exercise_Freq | Lifestyle indicators                                                                   |
| BMI, Chronic_Disease                 | Health-related metrics                                                                 |
| Smoker, Alcohol_Consumption, Diet_Quality                    | Habits                                                                                 |                                                         |
| Healthy                                                   | Custom binary feature indicating simplified health status (engineered in this project) |

 Note: The data used in this project syntheticic** and for educational purposes only.

---

## Key Visualizations

* Distribution of age, BMI, and chronic diseases.
* Heat map of correlation between numerical characteristics.
* Relationship between stress level and smokers, quality of diet, and hours of sleep.
* Health status depends on diet, activity level, stress, smoking, and chronic diseases.
* Relationship between alcohol consumption and smoking status.
* Distribution of the user indicator "Healthy".

---

## Main Insights

* A healthy diet and regular physical activity are key contributors to better health.
* Smoking and alcohol consumption tend to correlate negatively with perceived health.
* The Healthy indicator effectively captures the influence of lifestyle factors in a simple binary format.
* A conditional feature Healthy has been created, which determines whether a person has a sufficient number of healthy habits**.
* Those who meet at least 4 of the 6 features are considered healthy:
* Absence of chronic diseases
* Low stress level (≤ 4)
* Sufficient sleep (≥ 7 hours)
* Regular physical activity
* Balanced diet
* Refusal to smoke and drink excessively
* According to this criterion, approximately 27% of people in the sample are considered healthy

---

## Limitations

* The dataset is synthetic**, so insights may not reflect real-world distributions.
* The Healthy featuresubjective and simplifieded** — not medically validated.
* Some feature distributions are imbalanced, which may affect modeling potential.

---

## Project Structure


├──  notebook/eda.ipynb                

├──  data/

├──  README.md
---
##!Built for educational purposes.
