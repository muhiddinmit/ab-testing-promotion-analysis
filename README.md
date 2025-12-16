# A/B Testing Analysis: Promotion Effectiveness on Store Sales

## Project Overview
This project analyzes the effectiveness of two promotional strategies using A/B testing to determine which promotion leads to higher weekly sales.

## Business Question
Does Promotion 2 improve sales compared to Promotion 1?

## Experiment Design
- Control Group: Promotion 1  
- Treatment Group: Promotion 2  
- Metric: Weekly sales (SalesInThousands)  
- Sample size:
  - Promotion 1: 172 observations
  - Promotion 2: 188 observations

## Tools & Skills
- Python
- Pandas, NumPy
- SciPy (t-test)
- Matplotlib
- A/B Testing
- Statistical Analysis

## Key Results
- Promotion 1 average sales: 58.10
- Promotion 2 average sales: 47.33
- Mean difference: -10.77
- Percent change: -18.54%
- p-value: 4.29e-10 (statistically significant)

## Conclusion
Promotion 1 significantly outperformed Promotion 2. Promotion 2 resulted in lower sales and should not be rolled out.

## ## 📊 Final Results Visualization

![Average Weekly Sales by Promotion (95% CI)](result.png)

The visualization shows average weekly sales with 95% confidence intervals. Promotion 1 clearly outperforms Promotion 2, confirming the statistical test results.

