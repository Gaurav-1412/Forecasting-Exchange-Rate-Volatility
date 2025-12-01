# Forecasting Exchange‑Rate Volatility  
Multivariate Staked LSTM + Attention model to forecast USD/INR realized volatility. This repo contains code, cleaned data, notebooks and scripts to reproduce the results reported in the project.

**Repository:** https://github.com/Gaurav-1412/Forecasting-Exchange-Rate-Volatility
  


---

## Quick summary
- `maincode.ipynb` — end‑to‑end pipeline: data ingestion, preprocessing, feature engineering, model definitions, walk‑forward training and evaluation, figures/tables export.  
- `final_predictors_2003_onwards.csv` — cleaned dataset used for experiments.  
- `eda_output.xlsx` — exploratory data outputs.  
- `results_Baseline.csv` — baseline model outputs (GARCH/HAR etc.).  
- `requirements.txt` — pip environment specification.  
- `run_notebooks.ps1` / `run_notebooks.sh` — reproducible headless runners (Windows / macOS/Linux).  
- `outputs/` — generated tables and figures when notebooks are executed.

---

## Reproducibility — exact minimal steps (one‑line commands included)

> **Clone the repository**
```bash
git clone https://github.com/Gaurav-1412/Forex-Volatility-Forecasting.git
cd Forex-Volatility-Forecasting
