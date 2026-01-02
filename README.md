# Bank Marketing Decision Tree Classifier

This project demonstrates how to build a **Decision Tree Classifier** to predict whether a customer will purchase a product/service (`y`) based on demographic and behavioral data.

## Dataset
We use the **Bank Marketing Dataset** from the UCI Machine Learning Repository.

### Download Instructions
1. Visit: https://archive.ics.uci.edu/ml/datasets/Bank+Marketing
2. Download **bank-additional.zip**
3. Extract it and place `bank-additional-full.csv` inside the `data/` folder.

## Project Structure
```
.
├── data/
│   └── bank-additional-full.csv
├── bank_marketing_decision_tree.ipynb
└── README.md
```

## Requirements
- Python 3.8+
- pandas
- scikit-learn
- matplotlib
- seaborn

Install dependencies:
```bash
pip install pandas scikit-learn matplotlib seaborn
```

## Steps Covered
- Data loading and exploration
- Preprocessing (encoding categorical variables)
- Train-test split
- Decision Tree training
- Model evaluation
- Tree visualization

## Output
The model predicts whether a client subscribes to a term deposit (`yes` / `no`).

---
Author: laxman Tekale 
