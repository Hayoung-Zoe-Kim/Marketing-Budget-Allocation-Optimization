# Marketing-Budget-Allocation-Optimization

## Project Overview

#### Purpose & Methodology
The purpose of this project is to utilize linear programming, with the aid of Gurobi, to develop an optimal marketing budget allocation strategy for a company with a fixed budget of $10 million. The project aims to maximize the return on investment (ROI) for various advertising platforms while considering budget constraints and the potential impact of different ROI data sources. It explores the stability of the budget allocation and the effects of reinvesting a portion of the returns.

## Highlights of Analysis

#### Optimized Budget Allocation based on two different ROI data
![image](https://github.com/Hayoung-Zoe-Kim/Marketing-Budget-Allocation-Optimization/blob/main/Allocation1,2.png)

#### Budget Sensitivity Ranges
Allowable variations or adjustments in budget allocations without significantly impacting the overall optimization objective or outcomes
![image](https://github.com/Hayoung-Zoe-Kim/Marketing-Budget-Allocation-Optimization/blob/main/Sensitivity_table.png)

![image](https://github.com/Hayoung-Zoe-Kim/Marketing-Budget-Allocation-Optimization/blob/main/Sensitivity_line.png)

#### Reinvesting Half of the Returns in the Upcoming Year: Optimized Monthly Allocation
![image](https://github.com/Hayoung-Zoe-Kim/Marketing-Budget-Allocation-Optimization/blob/main/Next_Year_Budget_table.png)

![image](https://github.com/Hayoung-Zoe-Kim/Marketing-Budget-Allocation-Optimization/blob/main/Next_Year_Budget_bar.png)

![image](https://github.com/Hayoung-Zoe-Kim/Marketing-Budget-Allocation-Optimization/blob/main/Next_Year_Budget_heatmap.png)

#### Stability Analysis
Stable budget = for each platform the monthly change in spend is no more than $1M
![image](https://github.com/Hayoung-Zoe-Kim/Marketing-Budget-Allocation-Optimization/blob/main/Stability_Analysis.png)

## Conclusion
- Sensitivity analysis also reveals the vulnerability and flexibility of our advertising channels. While platforms such as Instagram and Email were noted for their resilience and growth potential, SEO and AdWords appeared more susceptible to fluctuation in ROI. 
- Stability analysis has highlighted potential operational challenges associated with significant monthly budget fluctuations, indicating the need for a more consistent allocation strategy
- In order to maintain the efficiency of our budgeting decisions, it is imperative to regularly refresh ROI data.
- Additionally, it would be prudent to develop a refined model that takes into account month-to-month budgetary constraints in order to ensure stability in the allocation of budgets across channels.
