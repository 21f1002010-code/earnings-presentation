---
marp: true
theme: default
title: Quarterly Earnings Report
paginate: true
---

# Quarterly Earnings Report

**Email:** 21f1002010@ds.study.iitm.ac.in

---

## Highlights

- Revenue up 12%
- Expenses reduced by 8%
- Net profit margin improved

---

## Key Drivers

- Cost Efficiency
- Digital Adoption
- Risk Management

---

## Python Example

```python
import pandas as pd
df = pd.read_csv("earnings.csv")
df["margin"] = df["net_income"] / df["revenue"]
print(df.head())
