# DS 4002 Case Study: STEM vs. Humanities — Sentiment Analysis of UVA Course Reviews

**Created by:** Alison Pike 
**Course:** DS 4002 | Spring 2026  
**Target Audience:** 2nd Year UVA Data Science Students

---

## Overview

Do UVA students talk about their STEM courses differently than their Humanities courses? This case study challenges you to find out using sentiment analysis and real student review data scraped from [theCourseForum](https://thecourseforum.com/).

You will collect text data, apply a sentiment analysis tool, and use a statistical test to determine whether any difference you find is meaningful — or just noise.

---

## Repository Structure

```
CS3_repo/
├── HOOK/
│   └── hook_document.pdf        # One-page mission document to get you started
├── RUBRIC/
│   └── rubric.pdf               # Full rubric describing the deliverable and criteria
├── MATERIALS/
│   ├── explainer_sentiment.pdf  # Blog-style explainer on sentiment analysis with VADER
│   └── reference_ttest.pdf      # Reference article on Welch's t-test
├── DATA/
│   ├── uva_reviews_final.csv           # Pre-scraped raw review data
│   └── uva_reviews_with_sentiment.csv  # Reviews with VADER sentiment scores applied
└── README.md
```

---

## Your Mission

You are a data scientist trying to understand student experience at UVA. Using course reviews from theCourseForum, your job is to:

1. Collect and preprocess text review data across STEM and Humanities departments
2. Apply VADER sentiment analysis to score each review
3. Run a statistical test to determine if the difference in sentiment is significant
4. Summarize your findings in a short written report

See the **HOOK** document to get started and the **RUBRIC** for full deliverable details.

---

## Data

The `DATA/` folder contains pre-scraped review data from theCourseForum, covering 8 departments:
- **STEM:** CS, BIOL, CHEM, APMA  
- **Humanities:** SOC, PHIL, HIST, PSYC

If you wish to re-scrape the data yourself, refer to the scraping approach described in the rubric. Note that theCourseForum may restrict automated requests from certain environments.

---

## References

1. Hutto, C.J. & Gilbert, E.E. (2014). VADER: A Parsimonious Rule-based Model for Sentiment Analysis of Social Media Text. *ICWSM*.
2. Duke University. "Welch's T-test." Statistical Education Resource Center, 2024. https://sites.nicholas.duke.edu/statsreview/means/welch/
3. theCourseForum. https://thecourseforum.com/
