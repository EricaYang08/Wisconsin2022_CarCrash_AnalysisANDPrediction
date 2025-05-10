# Wisconsin 2022 Car Crash Analysis & Prediction

## Project Overview

This project explores injury severity in Wisconsin’s 2022 motor vehicle crash dataset through a combination of **exploratory data analysis (EDA)**, **statistical modeling**, and **machine learning**. The goals are to:

1. Perform **EDA** to identify patterns in crash timing, location, and frequency.
2. Apply **statistical tests** to explore associations between crash factors and injury severity.
3. Train **predictive models** to classify injury severity using interpretable and advanced algorithms.

---

## Project Structure

### `Wisconsin_CarCrash_DataAnalysis.ipynb`

**Focus:** Exploratory Data Analysis + Statistical Testing

- Municipality crash distribution and seasonal patterns
- Radar chart for binary crash flags
- Correlation heatmap for numeric features
- **Statistical Tests:**
  - Chi-square (e.g., alcohol vs. injury severity)
  - T-test (e.g., speeding vs. total injuries)
  - ANOVA (e.g., notification hour vs. injury level)
- **Interactive Plot:** Injuries vs. crash time

---

### `Wisconsin2022_Car_Crash_Prediction.ipynb`

**Focus:** Machine Learning Models for Injury Severity Classification

- Models: XGBoost (baseline, tuned, weighted), Logistic Regression (binary baseline)
- Feature engineering and preprocessing
- Hyperparameter tuning with `GridSearchCV`
- Class imbalance handling using weighted training
- Feature importance visualization
- Odds ratio interpretation from logistic regression
- Sample prediction using a hypothetical crash profile

Note: Due to the size of the file, please check input file `2022crashdata.csv` in zip file: Data_Source.zip

---

## Why This Project Matters

Motor vehicle crashes are a leading cause of injury and death in the U.S. This project shows how real-world crash data can be analyzed and modeled to:

- Reveal key risk factors (e.g., alcohol, speeding, pedestrian involvement)
- Assist in early injury prediction and response prioritization
- Support public health and safety research using both statistical rigor and machine learning techniques

---

## Tools Used

- **Languages & Libraries**: Python, pandas, numpy, matplotlib, seaborn, plotly, scikit-learn, xgboost, scipy
- **Techniques**: Chi-square test, t-test, ANOVA, logistic regression, XGBoost classification, class balancing
- **Visuals**: Radar chart, bar plots, heatmaps, interactive scatter plot

---
