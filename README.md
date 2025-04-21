# 🏡 Predict Real Estate Prices with Machine Learning

A data science project focused on predicting real estate prices using machine learning techniques in Python. The goal of this project is to build a robust regression model that can estimate property prices based on various features such as location, size, number of bedrooms, and more.

---

## 📌 Project Overview

This project demonstrates the end-to-end process of building a machine learning model to predict house prices. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, model building, evaluation, and deployment-ready insights.

---

## 🚀 Key Features

- Cleaned and preprocessed real estate dataset
- Exploratory Data Analysis with insights and visualizations
- Feature engineering for better model performance
- Trained multiple regression models: Linear Regression, Random Forest, etc.
- Hyperparameter tuning using GridSearchCV
- Model evaluation with R², MAE, MSE, and RMSE
- Visual comparison of model performance
- Price prediction interface or notebook (optional)

---

## 🛠️ Tech Stack & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure
```bash
📁 Real-Estate-Price-Prediction/
│
├── data/ # Raw and cleaned datasets
├── notebooks/ # Jupyter notebooks with full pipeline
├── models/ # Saved ML models (if applicable)
├── images/ # EDA graphs, model evaluation plots
├── real_estate_price_prediction.ipynb # Main notebook
└── README.md # Project documentation
```



---

## 📊 Dataset

The dataset includes the following features:

| Column Name     | Description                                |
|-----------------|--------------------------------------------|
| `status`        | Sale status (e.g., for sale, sold, etc.)   |
| `price`         | Property price (target variable)           |
| `bed`           | Number of bedrooms                         |
| `bath`          | Number of bathrooms                        |
| `acre_lot`      | Land area in acres                         |
| `street`        | Street address (can be cleaned/ignored)    |
| `city`          | City name                                  |
| `state`         | U.S. state                                 |
| `house_size`    | Size of the house in square feet           |
| `prev_sold_date`| Previous sale date                         |

> 🗃️ Total Records: 11,086,768 rows 


---

## 🧪 Model Performance

| Model              | R² Score | RMSE   |
|-------------------|----------|--------|
| Linear Regression | 0.78     | 4.2    |
| Random Forest     | 0.91     | 2.7    |

> 📈 *Add your actual results here*

---

## 💡 Insights

- Location plays a significant role in pricing
- Feature scaling improved the model’s performance
- Random Forest performed better than linear models
- Model can generalize well to unseen listings

---

## ▶️ How to Run

1. Clone the repository  
```bash
git clone https://github.com/Akshay8087/real-estate-price-prediction.git
```

2. Navigate to the project directory
 ```bash
cd real-estate-price-prediction
```

3. Install dependencies
```bash
pip install -r requirements.txt
```
