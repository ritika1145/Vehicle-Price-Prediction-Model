# Vehicle Price Prediction Model

End-to-end machine learning project for predicting used car prices using feature engineering, regression models, and performance evaluation.

---

## Project Overview

This project aims to predict vehicle prices based on various features such as mileage, age, condition, fuel type, and vehicle characteristics. The workflow includes data cleaning, exploratory data analysis (EDA), feature engineering, and training multiple regression models.

---

## Models Used

* Linear Regression
* Ridge Regression
* Decision Tree Regressor
* Random Forest Regressor

---

## Model Performance

| Model             | R² Score  | Notes                                        |
| ----------------- | --------- | -------------------------------------------- |
| Linear Regression | ~0.66     | Baseline model, struggles with non-linearity |
| Ridge Regression  | ~0.66     | Similar to Linear, slightly more stable      |
| Decision Tree     | ~0.76     | Captures non-linear patterns                 |
| Random Forest     | **~0.83** | Best performance, most accurate predictions  |

---

## Key Insights

* Vehicle price has a **non-linear relationship** with features like mileage and age
* Feature engineering (e.g., `car_age`, `miles_per_year`) significantly improved model performance
* Tree-based models outperform linear models due to their ability to capture complex patterns
* Random Forest provided the most accurate and stable predictions

---

## Limitations

* Model performance decreases for very high-priced vehicles
* Some outliers still affect predictions
* Further tuning could improve results

---

## Future Improvements

* Hyperparameter tuning for Random Forest
* Feature importance analysis
* Log transformation of price to reduce skewness
* Testing advanced models (e.g., Gradient Boosting)

---

## Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

