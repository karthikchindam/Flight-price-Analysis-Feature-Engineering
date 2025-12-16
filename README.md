# Flight Price Analysis & Feature Engineering

## Project Overview
Analyzed 10,000 Plus flight booking records to identify key factors influencing ticket prices and transformed raw, inconsistent data into a clean, analysis-ready dataset suitable for analytics and predictive modeling.

This project focuses on data quality, feature logic, and business interpretability rather than black-box modeling.

---

## Business Objective
- Identify primary drivers of flight ticket pricing
- Remove noisy and unreliable features
- Engineer structured, meaningful variables from raw data
- Deliver a modeling-ready dataset with zero missing values

---

## Tools & Skills Used
- Python (Pandas, NumPy)
- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Feature Engineering
- Categorical Encoding
- Business Insight Generation

---

## Key Insights from Exploratory Data Analysis
- Airline choice is the strongest pricing driver; premium carriers show significantly higher fare dispersion.
- Number of stops has a direct impact on ticket prices, with non-stop flights consistently cheaper.
- Longer journey durations correlate with higher fares, especially on multi-stop routes.
- Departure timing influences price patterns; late-night and red-eye flights show distinct behavior.
- Columns such as Route were dropped due to high inconsistency and low analytical value.

---

## Data Cleaning & Standardization
- Standardized inconsistent date and time formats across multiple columns
- Parsed and normalized duration strings into structured numeric values
- Split departure and arrival times into hour and minute components
- Removed noisy, redundant, and text-heavy columns

---

## Feature Engineering
- Extracted day, month, and year from journey dates
- Converted journey duration into total minutes
- Encoded number of stops as numeric values
- Cleaned and encoded Additional_Info
- Applied one-hot encoding to all categorical variables
- Removed raw text columns after feature extraction

---

## Final Dataset
The final dataset is:
- Fully numeric and encoded
- Free of missing values
- Consistent and standardized
- Ready for advanced analytics or machine learning


---

## Next Steps
- Build regression and tree-based pricing models
- Perform feature importance analysis
- Apply explainability techniques

