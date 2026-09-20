# Decision Tree ML Case Study

This project covers exploratory data analysis, data processing, feature engineering, and a decision-tree classifier with pre-pruning and post-pruning.

## Project layout

- `data/raw/` — immutable source data
- `data/interim/` — temporary cleaned or transformed data
- `data/processed/` — modelling-ready datasets
- `notebooks/` — EDA and experiment notebooks
- `src/` — reusable Python modules
- `models/` — saved model artifacts
- `reports/figures/` — exported charts and evaluation visuals
- `tests/` — automated checks for reusable code

## Suggested workflow

1. Place the dataset in `data/raw/`.
2. Perform EDA in `notebooks/01_eda.ipynb`.
3. Build preprocessing and feature engineering functions in `src/`.
4. Train and compare pre-pruned and post-pruned decision trees.
5. Save final artefacts and figures in `models/` and `reports/figures/`.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
