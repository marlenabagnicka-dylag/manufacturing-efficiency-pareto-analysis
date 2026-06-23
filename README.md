**Production Efficiency & Pareto Analysis**

**Goal**

The goal of this project is to identify products that consume the most production time and evaluate their efficiency using Pareto Analysis.

**Business Problem**

In manufacturing, a small number of products often account for the majority of production workload. Identifying these products helps prioritize improvement activities and allocate resources more effectively.

**Objective**

This analysis aims to:

identify products with the highest impact on total production time,
evaluate production efficiency by product,
determine which products contribute to approximately 80% of total production time,
support decision-making for process improvement initiatives.

**Dataset**

The dataset contains production data with the following information:

* Product
* Actual Time
* Standard Time
* Efficiency %

**Business Questions**

* Which products consume the most production time?
* What is the efficiency level of each product?
* Which products are responsible for 80% of total production time?
* Which products should be prioritized for process improvement?

**Methodology**

  The analysis was performed in SQL and included:

1. Filtering invalid efficiency values.
2. Aggregating production time by product.
3. Calculating:
* weighted efficiency,
* share of total production time,
* cumulative share of production time.
4. Applying the Pareto principle to identify the most important products.

 **Production Efficiency Dashboard**

 An interactive Tableau dashboard was created to visualize:

Production time by product,
Product efficiency,
Pareto chart,
Cumulative share of production time.

Click the image below to open the interactive Tableau dashboard.

[![Production Efficiency Dashboard](images/dashboard.png)](https://public.tableau.com/views/pareto_analysis_v201/ProductionEfficiencyDashboard?:language=en-US&:display_count=n&:origin=viz_share_link)

**Key Findings**


