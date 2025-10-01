# Simple Data Processing — 3 Notebook Samples

Fast, standardized **data cleaning + 5 to 10-chart EDA** workflows in Jupyter notebooks.  
These samples showcase how messy CSV/Excel data is turned into decision-ready outputs with **transparent, reproducible code**.

## What’s inside

**Three focused cases** (each is self-contained):

1. **E-commerce Sales** — cleaning orders data; monthly revenue, top countries/categories, distribution checks.
2. **SaaS Users & Churn** — cleaning user table; plan mix, churn flag, ARPU, simple retention curves.
3. **Marketing Performance** — cleaning ad spend logs; spend by channel, ROAS/CVR views, 60-day series.

> Each case folder contains a Jupyter notebook and supporting data/artifacts (e.g., charts).  
> Folders present: `case1_ecommerce_sales/`, `case2_saas_churn/`, `case3_marketing_perf/`.

## Why this repo

- **Productized service demo**: A tight, repeatable scope clients understand (clean dataset + 5 charts + notebook).
- **Reproducibility**: Every step is visible in the notebook; clients can rerun or extend it.
- **Speed**: Guardrails keep delivery predictable (single file, column/row limits, basic EDA).

## Quickstart

1. **Environment**
   - Python 3.10+
   - `pip install jupyterlab pandas numpy matplotlib`

   *(Optional)* If you prefer conda:

   ```bash
   conda create -n sdp python=3.11 -y
   conda activate sdp
   pip install jupyterlab pandas numpy matplotlib
