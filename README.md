# life-expectancy-analysis
Machine learning analysis of life expectancy data across countries based on health and economic indicators.
# Predictive Analysis of Life Expectancy in Countries

This project investigates how various health, demographic, and economic indicators affect life expectancy across different countries. Using a combination of statistical testing and machine learning models, we identify the most significant predictors of life expectancy.

---

## 📊 Overview

This project uses a dataset from [Kaggle](https://www.kaggle.com/datasets/arunjangir245/life-expectancy-data) that contains health indicators for multiple countries. We analyze the impact of factors like BMI, immunization coverage, schooling, and health expenditure on life expectancy.

---

## 🔧 Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **pandas**, **numpy**
- **matplotlib**, **seaborn**
- **scikit-learn**
- **CatBoost**
- **SQL / phpMyAdmin**

---

## 📁 Repository Contents

- `life_expectancy_analysis.ipynb` – Main Jupyter notebook with data analysis, modeling, and output.
- `Project_Report.pdf` – Full academic project write-up with visualizations and methodology.
- `README.md` – Project summary and usage instructions.

---

## 🧪 Project Workflow

1. Data Collection & Storage (SQL via phpMyAdmin)
2. Data Cleaning & Preprocessing (null values, outliers, IQR)
3. Exploratory Data Analysis & Visualization
4. Statistical Analysis:
   - Normality tests
   - Kruskal-Wallis
   - Wilcoxon signed-rank
5. Machine Learning Models:
   - Linear Regression
   - Random Forest Regressor (with tuning)
   - CatBoost Regressor
6. Performance Evaluation (MAE, MSE, RMSE, R², MAPE)

---

## 🎯 Results

- **Best Model**: Tuned Random Forest Regressor
- **Accuracy (R²)**: 91%
- **Conclusion**: Attributes like immunizations, under-five deaths, and schooling are strongly correlated with life expectancy.

---

## ▶️ How to Use

This notebook contains saved outputs and does not require re-running.

To explore the full analysis:
- View the `life_expectancy_analysis.ipynb` file
- Read the `Project_Report.pdf` for detailed methodology and visuals

---

## 📚 Authors

- Lakshmi Menon
- Harsha Kamineni
- Adekola Adepoju
- Lavanya Pragada
- Pooja Manikonda

Supervised at Indiana University–Purdue University, Indianapolis.

---

## 📌 Note

This is an academic project completed as part of a group course assignment. Outputs and graphs are available within the files provided, and no rerun is required.

