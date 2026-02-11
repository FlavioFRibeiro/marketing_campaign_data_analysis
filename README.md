# Marketing Campaign Data Analysis

## Overview
This project delivers a multivariate exploratory analysis of marketing campaign data to understand customer behavior and drivers of campaign response. The analysis combines:
- Descriptive statistics;
- Outlier treatment;
- Feature engineering;
- Correlation analysis;
- Hypothesis testing,
- Uses a Random Forest model for feature importance to highlight the most influential predictors.

## Deliverables
- `marketing_campaign_data_analysis.ipynb`: Main analysis notebook (English narrative and labels).
- `dataset.csv`: Source dataset (local file).
- `requirements.txt`: Minimal Python dependencies to reproduce the analysis.

## Questions Answered
- What is the distribution of key variables?
- What proportion of customers accepted the campaign?
- Which campaigns performed best?
- How do age, income, and total spend relate to response?
- Which features are most important for explaining response?
- Are differences in income statistically significant across education groups?

## Project Structure
```
+- marketing_campaign_data_analysis.ipynb
+- dataset.csv
+- requirements.txt
+- README.md
```

## Setup
Create and activate a virtual environment (optional), then install dependencies:
```bash
pip install -r requirements.txt
```

## Run
Open the notebook and run all cells:
```bash
marketing_campaign_data_analysis.ipynb
```

## Reproducibility Notes
- The dataset is read from `dataset.csv`.
- Models that use randomness are configured with `random_state=43`.
- The analysis assumes the dataset columns as provided (some column names are in Portuguese).

## Notes
- The notebook is fully in English (text, comments, and plot labels), while dataset column names remain in Portuguese to preserve data integrity and avoid breaking outputs.
