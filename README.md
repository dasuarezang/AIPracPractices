# AIPracPractices

My Jupyter notebooks for a practical **machine learning** course in Telecommunications Engineering at UPC. Every session takes one real dataset through the usual workflow: describing the problem, exploring the data, preprocessing it, training a model, evaluating it, and writing up conclusions.

The notebooks are written in Catalan.

## Sessions

| Folder | Technique | Dataset | Goal |
|---|---|---|---|
| `p1/` | k-means clustering | Carseats | Group stores and estimate car seat sales |
| `p2/` | Linear regression | Brain Cancer | Predict survival time and read the model's coefficients |
| `p3/` | Logistic regression | South African Heart Disease | Classify patients at risk of coronary heart disease |
| `p4/` | Regularization (Ridge and Lasso) | Wage | Model salaries and study underfitting vs overfitting |
| `p5/` | Decision trees and cross-validation | Orange Juice (OJ) | Predict which orange juice brand a customer buys |
| `p6/` | Random Forest | Breast Cancer Wisconsin (scikit-learn) | Diagnose tumours as benign or malignant and rank the most important features |

Each folder has my solved notebook (`.ipynb`), and some also include an HTML export.

The `(empty)/` folder holds the original material for sessions 1–5: the datasets (`.csv`), the explanatory images, and PDF/HTML versions of the notebooks.

## Tech stack

- Python and Jupyter
- pandas, NumPy
- Matplotlib, seaborn
- scikit-learn (`KMeans`, `LinearRegression`, `LogisticRegression`, `Ridge`, `Lasso`, `DecisionTreeClassifier`, `RandomForestClassifier`, `train_test_split`, `StandardScaler`, ...)

## Running

```bash
pip install jupyter pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
```

Sessions 1–5 read their CSV files from the `(empty)/pN/...` folders, so you may need to copy the dataset next to the notebook or update its path.
