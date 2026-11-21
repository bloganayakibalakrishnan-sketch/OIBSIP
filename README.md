# Iris Flower Classification

**Oasis Infobyte SIP | Data Science Track | Task 1**

Classifies iris flowers (Setosa, Versicolor, Virginica) from sepal and petal measurements using scikit-learn.

## What the notebook covers
- Loads the Iris dataset from `sklearn.datasets.load_iris()`
- EDA: shape, dtypes, null check, descriptive statistics, class balance
- Visualisations: pairplot, box plots, correlation heatmap
- Feature selection discussion (petal length and width are the most discriminative)
- 80/20 stratified train/test split
- Four classifiers trained and compared, with accuracy, confusion matrix and classification report
- Random Forest feature importance, 5-fold cross-validation, best model declared with justification

## Tech stack
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Jupyter Notebook

## How to run
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook Iris_Flower_Classification.ipynb
```

## Files
- `Iris_Flower_Classification.ipynb`: full notebook with outputs
