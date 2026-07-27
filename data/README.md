# Data

The dataset is **not included** in this repository (it is covered by the
original competition's terms of use).

## Dataset

**Financial Inclusion in Africa** — survey data on whether individuals have a
bank account, across four East African countries (Kenya, Rwanda, Tanzania,
Uganda).

| Property | Value |
|---|---|
| Records | 23,524 |
| Columns | 13 |
| Target | `bank_account` (Yes / No) |
| Class balance | 14.08% banked vs 85.92% unbanked |

- **Source (Zindi):** https://zindi.africa/competitions/financial-inclusion-in-africa/data
- **File used:** `Train.csv`

## How to set up

1. Download `Train.csv` from the link above (free Zindi account required).
2. Place it in this `data/` folder:

   ```
   data/Train.csv
   ```

3. The notebook (`notebooks/financial_inclusion_analysis.ipynb`) loads it via the
   relative path `../data/Train.csv`.
