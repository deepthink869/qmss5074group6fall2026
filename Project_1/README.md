# 5074group6project1

Changyang Zhu cz3003 & Yizhang Mu ym3178

Repository: https://github.com/deepthink869/qmss5074group6fall2026

## Files

`Project_1.ipynb` contains the analysis and saved results. 
The two supplied CSVs are in `data.

## Run

Use Python create a fresh environment, install the versions in `requirements.txt`, 
and open the notebook with Jupyter, also uses the PyTorch CPU backend.

bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt notebook
python -m notebook
```

On Windows, activate with `.venv\Scripts\activate`. 
Restart the kernel and run all cells in order. Keep `data/` beside the notebook. 
Running `artifacts/`. 

Analysis

We keep the assigned 95/42 train/test split. 
Random Forest grid search fits preprocessing within each training fold.  
The final comparison has 12 distinct model configurations;
the ReLU model is reused in the activation comparison. 
Course references are listed in the notebook.
