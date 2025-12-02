# Customer Insights – A Statistical Investigation

## Project Overview
This project analyzes a synthetic customer dataset for a mid-sized Indian retail company. The goal is to uncover behavioral patterns, spending trends, and demographic influences using statistical and data visualization techniques.

## Business Problem
The company has extensive customer data but lacks clarity on actionable insights. The analysis aims to validate business assumptions, reveal hidden patterns, and support data-driven decision-making.

## Key Activities

## Dataset Description
 - **Age Distribution:** Most customers are aged 30–50, with a right-skewed distribution and some outliers.
 - **Monthly Spend:** Majority spend below the median, with a few high spenders creating a long tail.
 - **Gender:** Gender distribution is nearly balanced; spending is statistically similar for males and females.
 - **Education:** Customers with higher education (Master’s, PhD) spend significantly more per month.
 - **State:** California and New York have the highest average monthly spend; these are high-value markets for targeted campaigns.
 - **Engagement:** No strong correlation between age and days since last interaction; engagement strategies should be broad-based.
 - **Pets & Marital Status:** Marital status is not significantly related to pet ownership, but non-married customers with pets may be a unique segment for re-engagement and cross-selling.
 - **Bivariate Analysis:** Monthly spend and age have a weak positive correlation; other numeric variables are largely independent.
 - **Hypothesis Testing:**
     - No significant difference in spend between males and females (t-test)
     - Education level impacts monthly spend (ANOVA)
     - Marital status and number of pets are independent (chi-square)
     - No significant correlation between age and engagement (Pearson)
     - State-wise spend varies significantly (ANOVA)
- **Rows:** 10,675
- **Columns:**
  - CustomerID, Name, State, Education, Gender, Age, Married, NumPets, MonthlySpend, DaysSinceLastInteraction
- **Features:** Demographics, behavioral signals, lifestyle choices

## Step-by-Step Approach
3. **Data Visualization:** Reveal patterns and trends
4. **Bivariate Analysis:** Explore relationships between attributes
5. **Formulate Hypotheses:** Define business questions and statistical tests
6. **Run Hypothesis Tests:** Validate or reject assumptions

## Key Insights
- Customers with Master’s/PhD degrees spend up to 18% more per month
- No significant difference in spend between males and females
- California and New York are high-value markets
- No strong correlation between age and engagement
- Non-married customers with pets may be a unique segment for re-engagement

## How to Run
1. Open `Statistics_project.ipynb` in Jupyter or VS Code
2. Run cells sequentially for full analysis and insights

## Requirements
- Python 3.x
- pandas, numpy, matplotlib, seaborn, scipy

## Author
Sumit Rana

