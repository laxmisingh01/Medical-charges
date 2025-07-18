# Medical-charges

# Medical Charges Prediction using Scikit-Learn

This project demonstrates the use of **regression techniques** in **Scikit-learn** to predict medical charges based on patient attributes. The analysis is performed using Python in a Google Colab notebook and covers both simple and multiple linear regression, handling categorical variables, and comparison with other regression models.

## 📌 Project Objectives

- Understand and formulate a regression problem
- Load and explore a real-world medical cost dataset
- Apply:
  - Linear Regression with a single feature
  - Multiple Linear Regression with multiple features
  - One-Hot Encoding for categorical variables
- Evaluate and compare model performance
- Experiment with additional regression algorithms (like Ridge, Lasso, etc.)

## 📂 Dataset

- File: `medical-charges.csv`
- Attributes: age, sex, BMI, children, smoker status, region, charges
- Target Variable: `charges` (medical insurance cost)
- Dataset link: https://www.kaggle.com/datasets/mirichoi0218/insurance

## 📊 Algorithms Used

- Linear Regression
- Ridge Regression
- Lasso Regression
- Polynomial Regression (if implemented)
- Feature Engineering with `pandas.get_dummies()`

## ⚙️ Libraries Required

```python
pandas
numpy
matplotlib
seaborn
sklearn
```

Install with:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🚀 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload the `medical-charges.csv` dataset
3. Run all cells step-by-step for full analysis

## 📈 Sample Output

- Regression coefficients and intercept
- R² Score, Mean Absolute Error (MAE), Mean Squared Error (MSE)
- Visualizations of prediction vs actual charges

## 🧠 Learning Outcomes

- Clear understanding of regression workflow in Scikit-learn
- Handling categorical data in ML pipelines
- Evaluating model accuracy with various metrics
