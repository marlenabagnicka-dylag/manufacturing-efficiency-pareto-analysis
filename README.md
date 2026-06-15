**Production Efficiency & Pareto Analysis**

**Goal**

Identify which products contribute most to total production time and evaluate their efficiency using Pareto analysis (80/20 rule).

**Dataset**

Production dataset containing:

product
actual_time
standard_time
efficiency_pct

**Business Questions**

1. Which products consume the most production time?
2. What is the efficiency level per product?
3. Which products contribute to 80% of total production time?
4. Where should optimization efforts be focused?

**Approach**

1.Filter invalid efficiency values (outliers)
2. Aggregate time per product
3. Calculate:
- weighted efficiency
- share of total time
- cumulative share (Pareto)
4. Select top contributors (80%)

 **Production Efficiency Dashboard**

Click the image below to open the interactive Tableau dashboard.

[![Production Efficiency Dashboard](images/dashboard.png)](https://public.tableau.com/views/pareto_analysis_v201/ProductionEfficiencyDashboard?:language=en-US&:display_count=n&:origin=viz_share_link)
