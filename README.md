# 🏥 Medicare Cost Analysis Projects

This repository contains multiple projects analyzing Medicare provider data using Python and data science techniques.

---

## 📊 Project 1: State-Level Medicare Cost Analysis

**Goal:** Compare average Medicare payments across U.S. states.

### ✅ Skills Used
- Data Cleaning (Pandas)
- Grouping & Aggregation
- Bar Chart Visualization
- Geographic Filtering (excludes non-states)

### 🔍 Key Insight
States vary significantly in their average Medicare allowed amounts. This could reflect differences in provider behavior, patient demographics, or cost of living.

📁 Files: 
- https://github.com/tyohannes2/Healthcare-Cost-Analysis/blob/main/Medicaid.ipynb
- https://github.com/tyohannes2/Healthcare-Cost-Analysis/blob/main/Average%20Medicare%20Payment%20by%20State%202023.png 

---

## 📈 Project 2: Linear Regression Modeling

**Goal:** Predict the Medicare allowed amount based on total services and submitted charges.

### ✅ Skills Used
- Regression Modeling (Scikit-Learn)
- Model Evaluation (R², MSE)
- Feature Engineering
- Data Visualization

### 🔍 Key Findings
- 💲 Medicare pays about **$0.17** per dollar billed on average
- ➖ More services are weakly associated with slightly lower payments
- 📊 Model explains **59%** of variance in payments

📁 File: 
- https://github.com/tyohannes2/Healthcare-Cost-Analysis/blob/main/medicare_cost_analysis_linear_regression.ipynb

---

## 📌 Data Source
Data from [Centers for Medicare & Medicaid Services (CMS)](https://data.cms.gov/).

---

## 🚀 Next Steps
- Add Poisson or Logarithmic Regression
- Cluster cost patterns by region
- Build a dashboard or app interface
