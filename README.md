# World-Happiness-Insights-A-Data-Driven-Predictive-Analysis
World Happiness Insights analyzes global happiness data (2015–2019) using machine learning. It identifies key factors like GDP, health, and social support influencing happiness, builds regression models, compares performance, visualizes insights, and offers policy recommendations to improve global well-being.
# 🌍 World Happiness Insights: A Data-Driven Predictive Analysis

## 📖 Overview
*Project Description (200 words):*

The *World Happiness Insights* project is a comprehensive data-driven analysis designed to explore and predict global happiness levels using the *World Happiness Report* datasets (2015–2019). It identifies the key socio-economic and governance factors influencing happiness—such as GDP per capita, social support, health, freedom, generosity, and corruption perception—through an automated machine learning pipeline.

The project performs end-to-end data processing, including automatic dataset detection, cleaning, feature engineering, and scaling. It applies three regression models—*Ordinary Least Squares (OLS), **Generalized Linear Model (GLM), and **Robust Linear Model (RLM)*—to evaluate and compare predictive performance. Visual analyses such as correlation heatmaps, feature importance charts, residual plots, and model comparison graphs provide deep interpretive insights into global well-being trends.

Additionally, the analysis includes *Variance Inflation Factor (VIF)* calculations to detect multicollinearity and uses permutation-based feature importance to rank influential predictors. The findings are summarized into clear, actionable *policy recommendations* aimed at improving happiness through better healthcare, social support, freedom, equality, and transparency.

By merging statistical modeling with social insight, *World Happiness Insights* not only predicts happiness scores but also translates data into meaningful strategies for governments, researchers, and policymakers to enhance global quality of life.
---

## 🎯 Objectives
- Automatically detect and clean yearly World Happiness datasets  
- Model the relationship between happiness and influencing factors  
- Compare regression models (OLS, GLM, RLM)  
- Generate visualizations and interpret results  
- Provide data-backed policy insights  

---

## 🧩 Key Features
✅ Automatic dataset detection for selected year (2015–2019)  
✅ Cleans, imputes, and scales data dynamically  
✅ Builds and compares models:
   - **OLS (Ordinary Least Squares)**
   - **GLM (Generalized Linear Model)**
   - **RLM (Robust Linear Model)**
✅ Evaluates with **R² Score** and **RMSE**  
✅ Creates:
   - Correlation Heatmaps  
   - Model Comparison Charts  
   - Residual Distributions  
   - Feature Importance Plots  
✅ Calculates **Variance Inflation Factor (VIF)** for multicollinearity  
✅ Offers key insights and policy recommendations
worldshappinessfactorprediction/
│
├── 2015.csv
├── 2016.csv
├── 2017.csv
├── 2018.csv
├── 2019.csv
│
├── plots/
│ ├── correlation_matrix_2019.png
│ ├── model_comparison_2019.png
│ ├── actual_vs_predicted_2019.png
│ ├── residual_distribution_2019.png
│ └── feature_importance_2019.png
│
└── happiness_analysis.py ← main script

---

## ⚙️ Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/world-happiness-insights.git
cd world-happiness-insights
Install Dependencies
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
Run the script and enter a year (2015–2019) when prompted
python happinessfactor.ipynb
Enter year (20Enter year (2015, 2016, 2017, 2018, or 2019): 2019
Outputs

Correlation Matrix – Displays relationships among happiness factors

Model Comparison Plot – Compares OLS, GLM, and RLM model performance

Actual vs Predicted Plot – Visualizes model accuracy

Residual Distribution – Shows model error distribution

Feature Importance Chart – Ranks key predictors

VIF Table – Checks for multicollinearity

Policy Recommendations – Actionable insights based on findings


