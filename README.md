# Jasveen Klair

I am an experienced data and business intelligence professional returning to hands-on data analysis work.

I am building a portfolio around realistic business questions, with an emphasis on sound data preparation, SQL and Python analysis, appropriate use of statistics and clear recommendations for decision-makers.

## Portfolio projects

### Project 04: Great Britain Day-Ahead Electricity Demand Forecasting

A leakage-aware forecasting case study using National Energy System Operator (NESO) electricity-demand data.

The project tests how accurately Great Britain National Demand can be forecast half-hour by half-hour, one day ahead, while preventing the models from using information that would only have become available later.

On the untouched 2025 test period, the best project model was about **1,576 MW away from actual demand on average**, compared with **2,179 MW** for a simple forecast based on the same half-hour one week earlier. NESO's operational forecast was considerably more accurate at about **679 MW average absolute error**.

The project uses chronological validation, a separate 2026 robustness check and a reproducible BigQuery/dbt/Python pipeline.

**Tools:** SQL, BigQuery, dbt, Python, pandas, scikit-learn, Matplotlib, Git and GitHub

[Repository](https://github.com/jsklair/project_04_gb_electricity_demand_forecasting) | [Published analysis](https://jsklair.github.io/project_04_gb_electricity_demand_forecasting/)

### Project 03: Customer Value & Retention Segmentation

An end-to-end customer segmentation analysis using real UK online-retail transaction data, built around the decision of which customer groups should receive different retention, growth and reactivation treatment.

The project uses Python and SQL to profile and classify more than one million transaction rows, build a reproducible SQLite analytical layer and create eight commercially interpretable customer segments. Segment definitions are fixed at a historical snapshot and then tested against six months of held-out purchasing behaviour.

High-value active customers represent 16.4% of the eligible customer population but generated 71.7% of positive held-out customer value, while future purchase rates also showed clear differentiation across repeat, recent, cooling, drifting and lapsed customer groups.

**Tools:** SQL, SQLite, Python, pandas, Matplotlib, Git and GitHub

[Repository](https://github.com/jsklair/project_03_customer_value_segmentation) | [Published analysis](https://jsklair.github.io/project_03_customer_value_segmentation/)

### Project 02: Checkout Conversion Experiment

A synthetic A/B test of a redesigned e-commerce checkout, built around the decision of whether the new experience should be rolled out.

The project uses relational event and order data, SQL validation and user-level metric construction, followed by statistical analysis in Python. The treatment increased checkout conversion from 59.90% to 61.32% and revenue per checkout user from £46.65 to £48.89. The final recommendation was to roll out the redesign while continuing to monitor the technical payment-error guardrail.

**Tools:** SQL, SQLite, Python, pandas, NumPy, SciPy, Matplotlib, Git and GitHub

[Repository](https://github.com/jsklair/project_02_checkout_ab_test_analysis) | [Published analysis](https://jsklair.github.io/project_02_checkout_ab_test_analysis/)

### Project 01: First-Time Buyer Affordability Pressure by Area

An end-to-end analysis of housing affordability across England and Wales using official ONS data.

The analysis uses lower-quartile house prices and workplace-based earnings to compare affordability pressure by area. It includes data preparation, SQL analysis, Python exploration, an Excel review workbook and a Power BI dashboard.

**Tools:** SQL, Python, Excel, Power BI, Git and GitHub

[Repository](https://github.com/jsklair/project_01_uk_house_price_analysis) | [Published analysis](https://jsklair.github.io/project_01_uk_house_price_analysis/)

## Rapid analyses

### Rapid Analysis 02: Outer London ULEZ and Roadside NO₂

A quick-turn comparative time-series analysis of roadside nitrogen dioxide after the August 2023 London-wide ULEZ expansion. It compares two outer-London roadside monitors with three screened non-London comparison sites and examines whether the relative change persisted into the second operational year.

The preferred model shows a larger relative improvement in the outer-London sites after the expansion, particularly in year two, while model-specification sensitivity means the analysis stops short of attributing the whole difference to ULEZ.

**Tools:** Python, pandas, statsmodels, Matplotlib, Git and GitHub

[Repository](https://github.com/jsklair/rapid_analysis_02_london_ulez_no2) | [Published analysis](https://jsklair.github.io/rapid_analysis_02_london_ulez_no2/)

### Rapid Analysis 01: The Developing 2026 El Niño in Historical Context

A quick-turn analysis using NOAA Relative Oceanic Niño Index (RONI) data to compare the developing 2026 El Niño with previous major events at the same seasonal stage, while keeping observed conditions separate from forecast uncertainty.

**Tools:** Python, pandas, Matplotlib, Git and GitHub

[Repository](https://github.com/jsklair/rapid_analysis_01_2026_el_nino) | [Published analysis](https://jsklair.github.io/rapid_analysis_01_2026_el_nino/)

## Current focus

With four substantial portfolio projects and two rapid analyses now published, I am continuing to strengthen the portfolio through differentiated analytical work rather than repeating the same problem types or techniques.
