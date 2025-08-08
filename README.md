
# 🏠 Airbnb Price Prediction | Machine Learning Regression Project

## 📌 Project Overview

This project aims to **predict the price of Airbnb listings** using machine learning regression techniques. Leveraging real-world data, the goal is to build a model that helps hosts and guests understand pricing patterns across different property types, locations, and amenities.

The project includes:

* Data cleaning & preprocessing
* Exploratory data analysis (EDA)
* Feature engineering
* Model training (Linear Regression, Random Forest, XGBoost, etc.)
* Model evaluation using MAE, RMSE, and R²
* Visual insights and interpretability

---

## 📊 Dataset

* **Source**: [Kaggle Airbnb Dataset](https://www.kaggle.com/)
* **Size**: \~50,000 listings
* **Key Features**:

  * `property_type`, `room_type`, `accommodates`, `bathrooms`, `bedrooms`
  * `neighbourhood`, `latitude`, `longitude`, `review_scores_rating`
  * `host_identity_verified`, `instant_bookable`, `cleaning_fee`
  * `price` (target variable)

---

## ⚙️ Tools & Technologies

* **Language**: Python
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
* **ML Models**:

  * Linear Regression
  * Random Forest Regressor
  * XGBoost Regressor
* **Evaluation Metrics**: RMSE, MAE, R²
* **Optional**: Streamlit for deployment

---

## 🔍 Project Structure

```bash
📁 Airbnb_Price_Prediction/
├── 📊 data/
│   └── airbnb.csv
├── 📈 notebooks/
│   └── EDA_and_Modeling.ipynb
├── 🧠 models/
│   └── trained_model.pkl
├── 📊 visuals/
│   └── eda_charts.png
├── app.py  (optional Streamlit app)
└── README.md
```

---

## 📌 Key Highlights

* Feature engineering of both categorical and numerical variables
* Geospatial insights using latitude and longitude
* Handled outliers and missing data effectively
* Built interpretable models and visualized feature importance
* Compared models using cross-validation and evaluation metrics


