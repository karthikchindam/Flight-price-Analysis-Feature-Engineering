# Flight Price Analysis & Feature Engineering

## Business Objective
Analyze airline ticket pricing behavior to identify key cost drivers, eliminate data noise, and produce a clean, modeling-ready dataset for accurate price prediction and decision-making.

---

## Dataset Overview
- 10,000 plus real-world flight booking records
- Target variable: Ticket Price (INR)
- Mixed data types: categorical, temporal, numeric
- Challenges: inconsistent time formats, price skewness, noisy categorical fields

---

## Tools & Technologies
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

---

## Key Insights
- Ticket prices are heavily right-skewed; median pricing is more reliable than mean for decision-making.
- Non-stop flights are typically cheapest, while 1-stop flights often cost more than 2-stop flights due to airline pricing strategies.
- Route complexity and total journey duration explain pricing better than source or destination alone.
- Duration shows weak linear correlation with price, indicating rule-based airline pricing rather than cost-per-time models.

---

## Exploratory Data Analysis
- Identified extreme price outliers (₹50K–₹80K) affecting summary statistics.
- Compared pricing distributions across airlines, routes, stops, sources, and destinations.
- Used distribution plots and boxplots to assess pricing volatility.

---

## Data Cleaning
- Standardized date and time formats across all records.
- Converted duration values into total journey minutes.
- Removed redundant and noisy columns, example: raw route strings.
- Ensured a consistent dataset with no missing values.

---

## Feature Engineering
- Extracted day, month, and year from journey dates.
- Split departure and arrival times into hour and minute components.
- Encoded number of stops as ordinal numeric features.
- One-hot encoded categorical variables.
- Dropped raw text columns post feature extraction.

---

## Final Dataset
- Fully numeric and machine-learning ready
- Clean, consistent, and reproducible
- Suitable for regression and tree-based models

---

## Future Steps
- Build regression and ensemble models
- Evaluate feature importance and model explainability
- Apply SHAP for pricing driver interpretation

---

## Business Value
Demonstrates how structured EDA and feature engineering directly improve model reliability, pricing insights, and downstream analytics.

