# 🏡 House Price Prediction - ML Project

This project is a machine learning regression model designed to predict **house prices** based on various features such as area, number of rooms, and amenities. It's ideal for beginners looking to understand model evaluation and comparison.

---

## 📂 Dataset Info

- Source: Kaggle
- Rows: 545
- Features:
  - `price` (Target)
  - `area`, `bedrooms`, `bathrooms`, `stories`, `parking`
  - Categorical: `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`, `furnishingstatus`

---

## 🔍 Objective

To compare different regression models and evaluate which performs best for house price prediction.

---

## 📈 Models Implemented

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

---

## 📊 Evaluation Metrics Used

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score (explained variance)

➡️ **Best model:** Linear Regression

---

## 📋 Model Comparison (Evaluation Results)

| Model                   | MAE        | MSE      | RMSE       | R² Score |
| ----------------------- | ---------- | -------- | ---------- | -------- |
| Linear Regression       | ₹979,112   | 1.80e+12 | ₹1,341,936 | 0.6437   |
| Random Forest Regressor | ₹1,053,391 | 1.98e+12 | ₹1,408,434 | 0.6075   |
| Gradient Boosting       | ₹1,012,781 | 1.84e+12 | ₹1,358,058 | 0.6351   |

---

## 🖼️ Visualizations

- Scatter plot comparing actual vs. predicted prices.
- Reference line (y = x) to assess prediction closeness.

---

## 🧾 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

Required packages:

```
pandas
numpy
matplotlib
scikit-learn
```

---

## 🚀 Future Enhancements

- Hyperparameter tuning with GridSearchCV
- Include other models like XGBoost or CatBoost
- Deploy as a web app with Streamlit or Flask

---



## 👨‍💻 Author

Created by Haripriya- built as part of learning and applying machine learning concepts in real-world datasets.

---

Feel free to fork, clone, and modify! Suggestions and improvements are welcome 😊

