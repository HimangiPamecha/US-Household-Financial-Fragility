# US-Household-Financial-Fragility
# Inflation & Financial Fragility: Has the Post-2021 Surge Caused a Structural Rise in U.S. Household Financial Fragility?

**Course:** Econometrics | T. A. Pai Management Institute, Bangalore (Batch 2023–2027)  
**Faculty:** Prof. Abhishek Kumar Rohit  
**Submitted:** December 2025  
**Authors:** Himangi Pamecha · Ananya Pillai · Krish Subharwal

---

## Overview

This project investigates whether the post-2021 U.S. inflation surge caused a **structural, permanent shift** in household financial fragility — beyond what inflation levels alone can explain. Using FINRA's National Financial Capability Study (NFCS) data (2009–2024) and macroeconomic data from FRED, we construct a composite **Financial Fragility Index (FFI)** via Principal Component Analysis (PCA) and test for a structural break using the **Chow test**.

---

## Key Finding

> **Post-2021 average fragility was ~10 points higher on the 0–100 FFI scale, independent of inflation levels.**  
> Chow Structural Break Test: **F = 6.35, df₁ = 48, df₂ = 125,109, p < 5.75 × 10⁻³⁹**

This confirms a statistically significant structural break — U.S. households did not simply experience transitory stress, but underwent a **persistent, structural deterioration** in financial resilience.

---

## Methodology

### Financial Fragility Index (PCA-Based)
Six dimensions from NFCS surveys were combined into a single FFI score:

| Dimension | NFCS Variable | Inflation Channel |
|-----------|--------------|-------------------|
| Expenses–Income Balance | J3, J4 | Real income erosion |
| Emergency Funds / Liquidity | J5 | Savings capacity reduction |
| Financial Anxiety & Stress | G23 | Uncertainty amplification |
| Credit Card Stress | F2_2–F2_4 | Budget deficit → debt reliance |
| Savings Behaviour | J8, J9, B2 | Essential expense crowding-out |
| Financial Literacy | M4 | Protective (moderates fragility) |

### Statistical Tests Applied
- **Principal Component Analysis (PCA)** — dimensionality reduction for FFI construction
- **Chow Structural Break Test** — to identify whether 2021 marks a regime change
- **OLS Regression** — FFI regressed on CPI inflation and control variables

---

## Data Sources

| Dataset | Source | Period |
|---------|--------|--------|
| FINRA NFCS Survey | FINRA Investor Education Foundation | 2009–2024 |
| CPI / Inflation Data | FRED (Federal Reserve Economic Data) | 2009–2024 |

---

## Theoretical Framework

The project builds on foundational work by Lusardi, Schneider & Tufano (2011) on household financial fragility, GFLEC's NFCS-based research, and PCA-based index construction approaches from Lenka (2015) and Gharbi et al. (2023). Six theoretical transmission pathways link inflation to each fragility dimension.

---

## Contents

```
├── US_Household_FF_Report.docx     # Project report
└── README.md
```

---

## 🏫 Institution

T. A. Pai Management Institute (TAPMI), Bangalore  
BBA in Finance (BBAF) · Batch 2023–2027
