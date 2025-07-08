# Medicare Cost Analysis by State (2023)

This project analyzes public Medicare Provider Utilization and Payment data from the Centers for Medicare & Medicaid Services (CMS) to compare **Average Medicare Payments** across U.S. states.

It uses Python libraries **pandas** and **matplotlib**, and is fully built in **Google Colab**. This project is part of my data portfolio to demonstrate real-world skills in public health data analysis and visualization.


## Objective

To identify how average Medicare payments vary by state and highlight any potential trends or cost disparities in healthcare reimbursement across the U.S.


## Key Features

- ✅ Filters dataset to only include the 50 U.S. states + D.C.
- ✅ Calculates average Medicare payment per state
- ✅ Creates a clear bar chart visualization of state-level averages
- ✅ Uses Python for data wrangling and analysis


## Tools Used

- Python 3
- pandas
- matplotlib
- Google Colab
- Public CMS dataset


## Sample Output

[![Average Medicare Payment by State](https://github.com/tyohannes2/healthcare-cost-analysis/blob/main/Average_Medicare_Payment_by_State_2023.png)](https://github.com/tyohannes2/Healthcare-Cost-Analysis/blob/main/Average%20Medicare%20Payment%20by%20State%202023.png)


## Data Source

[CMS.gov - Medicare Provider Utilization and Payment Data](https://data.cms.gov/)


# Medicare Cost Analysis — Regression Model

This project analyzes Medicare provider cost data using Python and linear regression.

## Project Summary
We explored the relationship between:
- **Average Submitted Charge** (`Avg_Sbmtd_Chrg`)
- **Total Services Provided** (`Tot_Srvcs`)
  
...to predict:
- **Average Medicare Allowed Amount** (`Avg_Mdcr_Alowd_Amt`)

### Key Insights
- For every $1 billed, Medicare pays about **$0.17**
- Each additional service very slightly **lowers** the average payment
- The model explains about **59%** of payment variation

### Files
- `Medicare_Regression_Project.ipynb`: Contains full code, model, and results

---

## Skills Used
- Data cleaning (Pandas)
- Regression modeling (Scikit-Learn)
- Data visualization (Matplotlib/Seaborn)
- Git & GitHub

---

## Future Work
We plan to test other models like:
- Poisson Regression
- Logarithmic Regression
- Geographic clustering (state-level cost trends)

