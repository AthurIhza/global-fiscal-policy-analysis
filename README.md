# Navigating the Fiscal Matrix: Global Fiscal Policy & GDP Growth Analysis (2010-2025)

## 📌 Project Overview
This repository contains a data analytics and econometrics project that evaluates how global crises (such as the COVID-19 pandemic) and country income levels moderate the effectiveness of fiscal policies. Using a multi-stage linear regression framework, this study analyzes data from the World Bank to measure the elasticity of government spending, tax revenue, and public debt on annual GDP growth.

Complete article and narrative breakdown can be read on my [Medium Article](https://medium.com/@ihza.athur/navigating-the-fiscal-matrix-how-crisis-income-and-policy-elasticity-shape-global-growth-757d1f8d06fc?postPublishedType=initial).

---

## 🎯 Research Objectives
1. **Objective 1:** Extract and analyze descriptive statistics for global baseline economic rates.
2. **Objective 2:** Conduct an Independent Sample T-Test to check structural growth differences between High-Income and Low-Income countries.
3. **Objective 3:** Build a baseline Simple Linear Regression model for pure government expenditure.
4. **Objective 4:** Develop a Controlled Multiple Linear Regression model accounting for tax, debt, eras, and income clusters.
5. **Objective 5:** Perform Interaction/Moderation Analysis to assess government spending elasticity during crisis periods.
6. **Objective 6:** Implement Data Transformation (Log-Linear) to mitigate public debt skewness and optimize model robustness.

---

## 📊 Dataset & Source
* **Data Source:** [Global Economic Indicators (2010-2025) on Kaggle](https://www.kaggle.com/datasets/tanishksharma9905/global-economic-indicators-20102025) compiled from World Bank data.
* **Target Variable:** `GDP Growth (% Annual)`
* **Key Features:** `Government Expense (% of GDP)`, `Tax Revenue (% of GDP)`, `Public Debt (% of GDP)`, `GDP per Capita`.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation:** `pandas`, `numpy`
* **Statistical Modeling:** `statsmodels` (OLS Regression), `scipy.stats` (T-Test)
* **Data Visualization:** `matplotlib`, `seaborn`

---

## 📈 Key Insights
* **The Crisis Shock:** The transition into the COVID-19 era caused a statistically significant drop ($p < 0.001$) in economic growth globally compared to pre-crisis baselines.
* **The Counter-Cyclical Rescue:** While aggressive government spending often correlates with inefficiencies during stable periods, its interaction effect during a global crisis is positive and highly significant—proving that state spending acts as a vital economic stabilizer during shocks.
* **Model Integrity > R-squared:** Applying a natural log transformation ($\ln(x+1)$) to `Public Debt` stabilized the model residuals and resolved outlier skewness, providing reliable statistical inferences over a raw linear approach.

---

## 📂 Repository Structure
* `world_bank_data_2025.csv` : Raw/cleaned dataset used for the analysis.
* `fiscal_policy_analysis.ipynb` : Jupyter Notebook containing the full source code (Objectives 1-6) and visualizations.
* `README.md` : Project documentation.

---

## 👥 Connect with Me
* **Medium:** [My Data Stories](INSERT_YOUR_MEDIUM_PROFILE_LINK_HERE)
* **LinkedIn:** [Your Name](INSERT_YOUR_LINKEDIN_LINK_HERE)
