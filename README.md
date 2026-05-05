# DS 4002 Case Study: Policy Uncertainty and Housing Market Volatility in Charlottesville

**Created by:** Alison Pike  
**Course:** DS 4002 | Spring 2026  
**Target Audience:** 2nd Year UVA Data Science Students  

---

## Overview

Can the language used in local government meetings predict housing price swings in Charlottesville? This case study challenges you to find out by combining text analysis of Charlottesville Housing Advisory Committee (HAC) meeting minutes with real housing market data from the Charlottesville Area Association of Realtors (CAAR).

You will scrape and process text data, build an uncertainty score, merge it with housing market data, and use a time-series regression model to evaluate whether policy uncertainty predicts short-term housing price volatility.

---

## Repository Structure

```
CS3_housing/
├── HOOK/
│   └── hook_document.pdf        # One-page mission document to get you started
├── RUBRIC/
│   └── rubric.pdf               # Full rubric describing the deliverable and criteria
├── MATERIALS/
│   ├── explainer_timeseries.pdf # Blog-style explainer on time-series regression
│   └── reference_uncertainty.pdf # Reference article on text-based uncertainty measurement
├── DATA/
│   └── cleaned_housing_market_data.csv  # Pre-cleaned combined dataset
└── README.md
```

---

## Your Mission

You are a data analyst for the City of Charlottesville. Your supervisor wants to know: does the level of uncertainty-related language in local Housing Advisory Committee meetings predict short-term housing price volatility in Charlottesville?

Your job is to:
1. Collect and process text from HAC meeting minutes
2. Build a quantitative uncertainty score from the text
3. Merge it with monthly CAAR housing market data
4. Run a time-series regression to evaluate the relationship
5. Report your findings and interpret what they mean for the Charlottesville housing market

---

## Data

The `DATA/` folder contains the pre-cleaned combined dataset. Raw data sources include:

- **HAC Meeting Minutes** — Charlottesville Housing Advisory Committee, available at:  
  https://www.charlottesville.gov/1077/Agendas-Minutes
- **CAAR Monthly Housing Reports** — Charlottesville Area Association of Realtors, available at:  
  https://www.virginiacountryliving.com/caar-market-reports.php

The dataset covers 8 usable months of 2025 (months without meetings or CAAR reports were excluded).

---

## References

1. "Agendas & Minutes | Charlottesville, VA," Charlottesville.gov, 2023. https://www.charlottesville.gov/1077/Agendas-Minutes
2. "2025 CAAR Market Trends," Virginiacountryliving.com, 2025. https://www.virginiacountryliving.com/caar-market-reports.php
3. GeeksforGeeks, "Time Series Regression," 2025. https://www.geeksforgeeks.org/data-science/time-series-regression/
4. Original project repository: https://github.com/emilyjmoore/DS_4002_Project_1
