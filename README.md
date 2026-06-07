# AAPL Stock Return — Statistical Analysis

A statistical analysis of Apple (AAPL) daily log returns using core concepts from probability and inferential statistics.

---

## Overview

| Topic | Method |
|-------|--------|
| Return computation | Daily log returns |
| Descriptive statistics | Mean, Std Dev, Skewness, Kurtosis |
| Distribution analysis | Histogram vs. fitted normal curve |
| Central Limit Theorem | Bootstrap resampling (1,000 samples, n=30) |
| Confidence interval | 95% CI for mean return (Z-interval) |
| Hypothesis test | One-sided t-test: H₁ — mean return > 0 |

---

## Key Results

- AAPL delivered a **statistically significant positive return** over 2020–2025
- Annualized return ≈ 23% | Annualized volatility ≈ 30%
- **Fat tails** observed (excess kurtosis > 0) — returns are not perfectly normal
- CLT confirmed: sample means converge to normal regardless of the raw distribution

---

## Project Structure

```
aapl-statistics-analysis/
├── AAPL_Statistics_Analysis.ipynb   # Main notebook
├── requirements.txt
├── plots/
│   ├── return_distribution.png
│   └── clt_demo.png
└── README.md
```

---

## Quickstart

```bash
git clone https://github.com/<your-username>/aapl-statistics-analysis.git
cd aapl-statistics-analysis
pip install -r requirements.txt
mkdir plots
jupyter notebook AAPL_Statistics_Analysis.ipynb
```

---

## Author

**Lijin Gao**  
M.Sc. Financial Engineering — HEC Montréal

> *For educational purposes only. Not investment advice.*
