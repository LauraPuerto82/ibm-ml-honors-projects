# 📊 Honors Project: Linear Regression Analysis on Children's Screen Time

This project was completed as part of the **honors track** in the IBM Machine Learning Professional Certificate (Course 2: Regression).

## 🧪 Objective
To identify the key factors that influence children's average daily screen time and use this understanding to predict future screen time for children aged 11 to 15.

## 📌 Key Tasks
- Exploratory data analysis and variable transformation
- Data preprocessing with categorical encoding
- Training and comparison of three linear regression models:
  - Simple Linear Regression
  - Polynomial Regression
  - Regularized Regression (Ridge and Lasso)
- Model evaluation using R² and MSE
- Prediction of screen time for specific age groups

## 🧠 Tools Used
- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 📁 Files
- `children_screen_time_regression.ipynb` – Full notebook with code, analysis, and visualizations

## 🔍 Insights
- **Age** is the most influential variable: for each additional year, daily screen time increases by approximately 0.38 hours.
- Polynomial regression provided the best balance of accuracy and explainability, with an R² of 0.99.
- Regularized models (Ridge, Lasso) did not outperform the polynomial model in this case, and slightly underfit the data.

## 🚀 Next Steps (Suggested in Report)
- Collect more granular data on individual behavior rather than aggregated samples
- Include additional predictors such as socioeconomic status, parental screen usage, or internet access
