# Analysis-of-UK-housing-and-cost-of-living-crisis
This project uses machine learning to analyze factors influencing the UK housing market and cost of living crisis. By examining data like housing prices, wages, and inflation, to identify key drivers  offering insights into housing affordability and living costs.
Here's a GitHub-style `README.md` you can copy and paste into your GitHub repository for the project titled **"UK Housing Market & Cost of Living Crisis"**:

---

# 🏡 UK Housing Market & Cost of Living Crisis

A data science project exploring the impact of the cost-of-living crisis on housing prices across Lower Super Output Areas (LSOAs) in Wales and England using machine learning models.

## 📘 Project Overview

This MSc Data Science project investigates how various socio-economic factors influence housing prices, especially in light of the UK's cost-of-living crisis. It leverages multiple machine learning algorithms to predict housing prices and provides insights for policymakers and stakeholders.

## 📌 Objectives

* Perform exploratory data analysis on LSOA housing datasets.
* Preprocess and clean data for machine learning readiness.
* Develop and evaluate predictive models (Linear Regression, Decision Tree, Random Forest, XGBoost).
* Interpret model results using SHAP for feature importance.
* Recommend actionable solutions to housing affordability issues.

## 📊 Datasets

* Sources: Office for National Statistics (ONS), HM Land Registry, UK Government portals (Wales & England).
* Features include: income, employment, health, education, energy consumption, property type, population density, property sales, etc.
* Target variable: Median housing prices (2021).

## 🧠 Machine Learning Models

| Model             | R² (Test)  | RMSE (£)      | MAE (£)       |
| ----------------- | ---------- | ------------- | ------------- |
| Linear Regression | 60.52%     | 134,182.07    | 83,366.59     |
| Decision Tree     | 46.26%     | 156,554.39    | 85,834.67     |
| Random Forest     | **78.79%** | **98,350.97** | **58,405.53** |
| XGBoost           | 76.01%     | 104,610.36    | 65,255.53     |

➡️ **Best performing model:** Random Forest

## 🔍 Feature Importance (SHAP)

Top influential features:

1. Health
2. Commercial Buildings
3. Gas Consumption per Person
4. Education Level
5. Population Density
6. Electricity Usage
7. Temporary Structures
8. Property Sales Count

## 🛠 Tools & Technologies

* **Language**: Python 3.11
* **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost, SHAP
* **Environment**: Jupyter Notebook, Anaconda

## 📈 Insights & Conclusions

* Health and environmental factors (e.g., energy usage) strongly influence property prices.
* Machine learning offers accurate and scalable prediction capabilities for real estate forecasting.
* Policymakers should consider holistic development across areas to improve affordability and access.

## 🚧 Limitations & Future Work

* Time-sensitive housing price data may affect long-term prediction accuracy.
* Incorporating geospatial and satellite data could improve model performance.
* Future extensions: interactive dashboards, real-time price recommender systems.

## 📄 Author

**Wilhelm Fiifi Awuah**
MSc Data Science, University of South Wales
Supervisor: Adeesha Gamage

---


