# Iris Flower Classification

Oasis Infobyte Internship (OIBSIP) | Data Science | Task 1

## Objective
Build a machine learning model that predicts the species of an iris flower (Setosa, Versicolor or Virginica) from its sepal and petal measurements.

## Steps Performed
1. Loaded the Iris dataset from `sklearn.datasets`
2. EDA: shape, data types, null check, descriptive statistics, class balance
3. Visualisations: pairplot, box plots, correlation heatmap
4. Feature importance analysis (petal features are the most discriminative)
5. 80/20 stratified train/test split
6. Trained Logistic Regression, KNN, Decision Tree and Random Forest
7. Evaluated with accuracy, confusion matrix and classification report
8. Compared models and picked the best one

## Tools Used
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Jupyter Notebook

## Outcome
Best model: **<model name>** with a test accuracy of **<xx%>**. Petal length and petal width were the strongest predictors, and the only confusion was between Versicolor and Virginica.

## How to Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook Iris_Flower_Classification.ipynb
```

## Demo Video
<YouTube/LinkedIn link>
