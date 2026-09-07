# 📊 Startups Profit Prediction using Multiple Linear Regression

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hadi-Faraj/simple-linear-regression-project/blob/main/simple_linear_regrresion_project.ipynb)
[![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📝 Overview
This project predicts the **Profit** of 50 Startups based on their expenditures across different departments (**R&D Spend**, **Administration**, and **Marketing Spend**) using a **Multiple Linear Regression** model implemented with `scikit-learn`.

---

## 🔍 Exploratory Data Analysis (EDA) & Workflow
1. **Data Inspection & Cleaning:** Checked dataset dimensions, summary statistics, missing values, and duplicates.
2. **Correlation Analysis:** Generated a correlation heatmap to analyze relationships between features and Profit.
3. **Distribution & Outliers:** Plotted box plots and distribution plots (`histplot`, `pairplot`) to detect potential outliers and feature distributions across states.
4. **Data Splitting:** Split data into **70% Training** and **30% Testing** sets (`random_state=42`).
5. **Model Training & Evaluation:** Trained a `LinearRegression` model and evaluated performance using metrics like $R^2$, MSE, RMSE, and MAE.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn`

---

## 🚀 How to Run

### Option 1: Open Directly in Google Colab
Click the **Open in Colab** badge above to launch and run the notebook instantly.

### Option 2: Run Locally
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Hadi-Faraj/simple-linear-regression-project.git](https://github.com/Hadi-Faraj/simple-linear-regression-project.git)
   cd simple-linear-regression-project
