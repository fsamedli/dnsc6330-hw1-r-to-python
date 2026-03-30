# DNSC 6330 - Individual Homework 1  
**Translating an R Machine Learning Workflow into Python**

## Purpose
This repository reproduces **exactly** the R script from the end of Lecture 01 (COMPAS/ProPublica two-year recidivism analysis).  
It includes:
- Full EDA  
- Exact preprocessing & factor engineering (with correct reference levels)  
- Logistic regression model (`glm` equivalent)  
- Model diagnostics and fairness/error-rate analysis by race

## Libraries Used
- `pandas`, `numpy`
- `statsmodels` (for exact `glm` equivalence)
- `matplotlib` + `seaborn` (visualizations)
- `scikit-learn` (confusion matrices)

## How to Reproduce
1. Clone the repo:  
   `git clone https://github.com/fsamedli/dnsc6330-hw1-r-to-python.git`
2. Install requirements:  
   `pip install pandas numpy statsmodels matplotlib seaborn scikit-learn`
3. Open `hw1_compas_python.ipynb` and run all cells (or `python hw1_compas_python.py`)

All outputs are deterministic and match the R workflow.

## Files
- `hw1_compas_python.ipynb` ← main notebook
- `README.md`
## AI Assistance Statement
AI assistance (Grok) was used solely to draft and refine this README.md file to improve clarity and professionalism.  
The entire Python notebook (`hw1_compas_python.ipynb`) — including data loading, preprocessing, factor engineering, logistic regression, model diagnostics, and fairness analysis — was implemented by the author. Only minor guidance was received on GitHub navigation and repository setup.
