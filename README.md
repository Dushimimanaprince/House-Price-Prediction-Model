# 🏠 House Price Prediction Model

A machine learning project focused on understanding how **feature engineering** improves house price prediction using **Linear Regression** through structured experimentation and evaluation.

---

## 📊 Dataset Overview

The dataset contains real estate information including:

- **Numerical Features:** bedrooms, bathrooms, stories, parking, area  
- **Binary Features:** mainroad, guestroom, basement, hotwaterheating, airconditioning, preferred area  
- **Target Variable:** `price`

### Price Distribution

| Metric | Value |
|------|------|
Mean | 4.77 million |
Min | 1.75 million |
Max | 13.3 million |
Std Dev | 1.87 million |

---

## 🧪 Modeling Process

We followed a professional ML workflow:

### 🔹 Model 1 — Baseline (Raw Numerical Data)

Features:
bedrooms, bathrooms, stories, parking


| Metric | Value |
|------|------|
MAE | 1,185,619 |
RMSE | 1,573,782 |

The baseline model underfit due to limited feature representation.

---

### 🔹 Model 2 — Feature Engineering with Binary Variables

Binary features encoded:
mainroad, guestroom, basement, hotwaterheating, airconditioning
Mapping:
yes → 1
no → 0


| Metric | Value |
|------|------|
MAE | 1,041,152 |
RMSE | 1,400,855 |

The model gained real-world context and showed strong improvement.

---

### 🔹 Model 3 — Enhanced Model with Area

Added:

| Metric | Value |
|------|------|
MAE | **956,726** |
RMSE | **1,299,365** |

Overall improvement: **~19% reduction in prediction error**

---

## 🧠 Key Insights

- Feature engineering is critical for model performance.
- Understanding target scale prevents misinterpretation of error metrics.
- Iterative modeling produces measurable improvements.
- Linear Regression remains a powerful baseline for predictive modeling.

---

## 🧰 Tools & Technologies

- Python  
- pandas  
- scikit-learn  
- Jupyter Notebook  

---

## 🚀 Future Work

- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting  
- Hyperparameter tuning  
- Cross-validation

---

## 👤 Author

**Prince Dushimimana**
