📌 Overview
---
This project analyzes the environmental footprint of 43 common food products across multiple sustainability dimensions.
Using both exploratory data analysis (Python + Jupyter Notebook) and an interactive Power BI dashboard, the study highlights which food groups contribute most to greenhouse gas emissions, water use, land use, and nutrient pollution.

The dataset provides a global overview (not country-specific), making it a useful reference point for sustainability research, food policy, and consumer awareness.

📂 Dataset
---
The dataset includes 23 metrics measuring environmental impact:

Greenhouse Gas (GHG) Emissions → from land use change, farming, processing, transport, etc.

Water Use → freshwater withdrawals and scarcity-weighted water use.

Land Use → land per kilogram, per kcal, and per protein unit.

Nutrient Pollution → eutrophication from nutrient runoff.

Food products are grouped into 10 categories:
Vegetables, Fruits, Legumes, Sugars, Beverages, Meat, Animal Products, Seafood, Oils, and Carbohydrates.

🔎 Analysis Approach
---
1. Exploratory Data Analysis (Python)

Conducted in a Jupyter Notebook. Key visualizations:

Boxplots → Compare food groups across each environmental metric group.

Scatter/Trade-off plots → Show two-way interactions (e.g., GHG vs Water).

Lifecycle breakdowns → For specific food groups (e.g., Meat), showing stage-wise contributions (farm, transport, packaging, etc.).

Per-product bar charts → Highlight dominant environmental impacts per food product.

2. Dashboard (Power BI)

An interactive dashboard was developed with slicers for:

Food product

Food group

Metric group

🔐 Key features:
---
Compare food groups by selected metric.

Explore trade-offs between sustainability metrics.

Deep-dive into lifecycle breakdowns for specific products.

📊 Key Insights
---
Scarcity-weighted water use dominates in many food products, its value numbers often overshadowing other metrics.

Meat and animal products contribute disproportionately across GHG and land-use dimensions.

Trade-offs are visible: foods low in GHG emissions may still be high in water use (and vice versa).

The dataset provides a global generic view, not region-specific.
