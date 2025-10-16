# DA5401 A6: Imputation via Regression for Missing Data
**Name:** Samyam Rishika  
**Roll Number:** CE22B101  

---

## Project Overview
This project studies how **different missing data imputation methods** affect model performance in predicting credit card default (UCI dataset).  
Missing values are introduced (MAR) and handled using:  

1. **Median Imputation (A)**  
2. **Linear Regression Imputation (B)**  
3. **Non-linear Regression Imputation (C1: KNN, C2: Decision Tree)**  
4. **Listwise Deletion (D)**  

Each dataset is used to train a **Logistic Regression** model, and results are compared.
## Folder Structure
```bash
├── assignment6.ipynb # Main Jupyter Notebook (all code, plots, analysis, narrative)
├── UCI_Credit_Card.csv
└── README.md # Project description and instructions
```

## How to Run
1. Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/Rishika-28/assignment-6-Rishika-28.git
cd assignment-6-Rishika-28
```
2. Open assignment6 in Jupyter Notebook.

3. Run all cells in sequence.

## Notes
1. The dataset UCI_Credit_Card.csv is uploaded but the code has provision to download it there, skip the block if you wish to use the dataset directly.
2. KNN imputation is slower due to repeated neighbor search on a large dataset.

## Requirements
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```


