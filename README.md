# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview

This project implements a **Multiple Linear Regression** model to predict house prices based on the following features:

- 📏 Above Ground Living Area (`GrLivArea`)
- 🛏 Number of Bedrooms (`BedroomAbvGr`)
- 🛁 Number of Full Bathrooms (`FullBath`)

The model is built using Python and Scikit-learn and evaluated using standard regression metrics.

---

## 📂 Dataset

**Dataset:** House Prices - Advanced Regression Techniques (Kaggle)

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

**Files Used:**
- train.csv

---

## 🎯 Objective

To build a Linear Regression model that predicts house prices using selected house features and evaluates its performance using regression metrics.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Features Used

| Feature | Description |
|----------|-------------|
| GrLivArea | Above ground living area (square feet) |
| BedroomAbvGr | Number of bedrooms |
| FullBath | Number of full bathrooms |

### Target Variable

- SalePrice

---

## ⚙️ Project Workflow

1. Import required libraries
2. Load the dataset
3. Select relevant features
4. Handle missing values
5. Split the dataset into training and testing sets
6. Train the Linear Regression model
7. Predict house prices
8. Evaluate model performance
9. Visualize Actual vs Predicted prices

---

## 📈 Model Performance

| Metric | Value |
|---------|-------|
| R² Score | 0.6341 |
| Mean Absolute Error (MAE) | 35,788 |
| Mean Squared Error (MSE) | 2,806,426,667 |
| Root Mean Squared Error (RMSE) | 52,975 |

---

## 📉 Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 📷 Output

The project visualizes the relationship between actual and predicted house prices using a scatter plot.

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/House-Price-Prediction-Linear-Regression.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

Open

```
House_Price_Prediction.ipynb
```

---

## 📁 Repository Structure

```
House-Price-Prediction-Linear-Regression/
│
├── House_Price_Prediction.ipynb
├── train.csv
├── README.md
├── requirements.txt
└── prediction_plot.png
```

---

## 🚀 Future Improvements

- Feature Engineering
- Data Preprocessing
- Hyperparameter Tuning
- Random Forest Regressor
- XGBoost Regressor
- Gradient Boosting

---

## 👨‍💻 Author

**Anuj**

AI/ML Enthusiast | Python Developer | Data Science Learner

---

## ⭐ Acknowledgements

- Kaggle
- Scikit-learn
- ProDigy InfoTech Internship
