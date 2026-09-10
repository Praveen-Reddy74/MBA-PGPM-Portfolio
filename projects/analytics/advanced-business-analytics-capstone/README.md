# Advanced Business Analytics Capstone — Telco Customer Churn

**Term:** 2 · **Subject:** BA — Business Analytics · **Professor:** Dr. Bappaditya (per subject workbook)
**Type:** Capstone project · **Status:** Appears individually authored (self-contained notebook pipeline; no team roster found in any project file)

## Objective
Build an end-to-end analytics pipeline on the public Telco Customer Churn dataset — from data cleaning through predictive modeling to executive-level business recommendations.

## Approach
A structured, notebook-by-notebook pipeline:
1. **EDA** — data understanding, distributions, correlations
2. **Feature Engineering** — preparing the dataset for modeling
3. **Clustering Analysis** — unsupervised customer segmentation
4. **Regression Analysis** — statistical modeling (OLS)
5. **Logistic Regression** — churn classification
6. **Model Comparison** — evaluating candidate models against each other
7. **Executive Insights** — translating model outputs into business recommendations

A custom script (`generate_notebooks.py`) programmatically generates the notebook structure — evidence of a deliberate, reusable pipeline rather than one-off analysis.

## Methods / Tools
Python (pandas, scikit-learn, matplotlib/seaborn), Jupyter notebooks, an executive PowerPoint summary.

## Output
Seven sequential Jupyter notebooks, supporting data files, generated plots (correlation heatmaps, ROC curve, confusion matrix, financial-impact chart), an OLS summary table, a model-comparison table, and a 25-slide executive presentation.

## What this demonstrates
Full-cycle applied analytics: EDA → feature engineering → both unsupervised (clustering) and supervised (regression, classification) modeling → model comparison → business-facing communication of results.

## Academic context
Capstone coursework for Term 2's Business Analytics course, Great Lakes Institute of Management PGPM program.

## Repository contents
- `notebooks/` — the 7 pipeline notebooks
- `data/` — source and processed datasets
- `plots/` — generated visualizations
- `tables/` — OLS summary and model-comparison outputs
- `presentation/` — executive summary deck
- `generate_notebooks.py` — notebook-generation script
