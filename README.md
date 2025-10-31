# World-Happiness-Insights-A-Data-Driven-Predictive-Analysis
World Happiness Insights analyzes global happiness data (2015–2019) using machine learning. It identifies key factors like GDP, health, and social support influencing happiness, builds regression models, compares performance, visualizes insights, and offers policy recommendations to improve global well-being.
# 🌍 World Happiness Insights: A Data-Driven Predictive Analysis

## 📖 Overview
**World Happiness Insights** is a data-driven project that analyzes global happiness data (2015–2019) using machine learning and statistical modeling.  
It identifies key factors like GDP, health, social support, freedom, generosity, and corruption influencing happiness across countries.  
The project builds regression models, compares their performance, visualizes insights, and provides actionable policy recommendations to improve global well-being.

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


