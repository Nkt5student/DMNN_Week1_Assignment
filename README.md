# Online Retail Analysis 

**Summary:** Minimal, reproducible exploratory analysis of the Online Retail dataset using invoice/basket as the unit of analysis. Cleaned data and charts are saved to `outputs/`.

## Project structure

- `data/online_retail.csv` — raw dataset
- `notebooks/week1_analysis.ipynb` — analysis notebook (load, clean, visualize)
- `outputs/` — charts and exported results


Run `notebooks/week1_analysis.ipynb` top-to-bottom to reproduce results.



# Online Retail Analysis – Week 3

**Summary**  
Responsible tree-based modelling (decision trees, random forests, gradient boosting) on the Online Retail dataset, using invoice/basket as the unit of analysis.  
Built directly on Week 1 cleaning and EDA decisions.

**Project structure**

- `data/online_retail.csv` — raw dataset  
- `notebooks/week1_analysis.ipynb` — Week 1: cleaning + EDA  
- `notebooks/week3_modelling.ipynb` — Week 3: target definition, feature engineering, tree-based models, evaluation  
- `outputs/` — saved charts and figures (from Week 1)

**How to run**

1. Open `notebooks/week3_modelling.ipynb`  
2. Execute all cells top-to-bottom  

This notebook:
- reloads the cleaned invoice-level dataset  
- defines target & features  
- trains and compares simple tree models  
- shows validation + final test performance

**Important notes**

- Focus is on **clear reasoning** and **responsible modelling**, **not** high accuracy  
- All choices are explicit, justified, and consistent with Week 1 insights  
- No aggressive hyperparameter tuning  
- Train / validation / test split used correctly  
- Small performance differences are **not** over-interpreted

**Assignment context**  
Week 3 Project Task – DMNN  
From EDA to Modelling (Trees & Ensembles)  
Submission: GitHub Classroom repository  
Deadline: Friday 06.02.2026 11:59 AM (midday)

