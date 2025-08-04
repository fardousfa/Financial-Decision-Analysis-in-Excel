# Financial-Decision-Analysis-in-Excel
This project explores the financial impact of implementing a price reduction strategy for Country X, using real-world business data. The objective is to support the CEO's decision on whether to reduce prices—balancing sales growth with net profit. Using Excel's data modeling and regression analysis tools, the goal is to identify the optimal price reduction that maximizes profitability without compromising margins beyond acceptable thresholds.

## Project Objectives

  - Evaluate the financial impact of various price cuts (up to 10%) on sales volume, net profit, and margin.

 - Use historical price reductions from other countries to forecast sales uplift in Country X.

 - Build a regression model to quantify the relationship between price cut % and sales uplift %.

  - Perform a what-if analysis to identify the optimal price point.

  - Compare outcomes in terms of both net profit and net profit margin.

  - Recommend a data-driven strategy aligned with the CEO’s goals: sales growth + profitability.

## The Problem Statement

<img width="794" height="721" alt="The Case   Information" src="https://github.com/user-attachments/assets/7997b246-b455-42ed-955f-2c4e7fff6b02" />

## Solution Overview

- Data Collection & Preparation:

        Collected current financial data for Country X.

        Extracted previous price investment data across other countries for regression modeling.



- Analysis Performed in Excel:

        Built a linear regression model (R² = 0.9796) to predict sales uplift.

        Developed a dynamic scenario model using Excel formulas.

        Created a what-if analysis table to simulate net profit and margins at different price cuts.
<img width="525" height="268" alt="Regression Analysis" src="https://github.com/user-attachments/assets/3d041acb-1ac8-477f-a5bb-05ec1f88d5c3" />


- Assumptions Documented:

        Sales uplift is linearly correlated with price cut %.

        Fixed overhead remains constant.

        Variable costs (COGS + supply chain) are based on per-unit basis.

## Key Findings: Net Profit Analysis at Different Price Reductions

At 0% price reduction (Current Scenario), the company achieves:
•	Net Profit: £80,000
•	Net Profit Margin: 8.00%

An Excel data model was developed to analyse the impact of price reductions on net profit and net profit margins. The model dynamically calculates changes in profitability as price reductions vary, providing clear insights into optimal pricing strategies.

***Excel What-if Analysis***

<img width="393" height="385" alt="Data Model" src="https://github.com/user-attachments/assets/7cf540d3-541d-4642-afb4-d9d589aed56c" />

***Visualization***

<img width="860" height="476" alt="Visual Presentation" src="https://github.com/user-attachments/assets/b64fd686-9a5c-4d47-bbdc-efdccc35c30f" />

***Microsoft Solver Solution***

<img width="735" height="566" alt="Solver Report" src="https://github.com/user-attachments/assets/c9fe754d-4634-4503-ac2e-c89c145784a5" />


<br>



### Findings


- 10% Price Cut → Highest total profit (£83,600), net margin falls slightly to 6.78%.

- 8% Cut → Best balance for margin-sensitive strategy.

- Reductions beyond 10% lead to declining profits despite sales growth.

- The regression model had R² = 0.9796, indicating strong reliability.


### Recommendations

- Implement a 10% Price Reduction:

        This could increase net profit to £83,600, provided sales volume grows sufficiently to offset the lower margins.
        Monitor sales uplift closely to ensure the reduction drives the desired volume growth.
        
- Control Operating Costs:

        Focus on reducing fixed overheads and supply chain costs to amplify the benefits of the price reduction.
        Even a 2-5% reduction in these costs could significantly boost net profit.


## Tools & Skills Demonstrated
- Skill/Tool	Description
- Excel	Financial modeling, formulas, dashboard creation
- Scenario Analysis	What-if modeling to evaluate profitability under different assumptions
- Linear Regression	Sales uplift forecast from historical price reductions
- Business Analysis	Recommendation based on margin vs. volume trade-off
- Data Visualization	Trendline chart, summary tables


