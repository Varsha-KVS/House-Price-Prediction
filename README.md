# House-Price-Prediction
Predicting house prices using machine learning techniques and feature analysis on real-world housing data.

# 🏠 House Price Prediction

## 📌 Project Overview

This project focuses on predicting house prices using Machine Learning techniques. The dataset contains various housing features such as area, number of bedrooms, bathrooms, stories, parking spaces, furnishing status, and amenities. The goal is to build regression models that can estimate house prices based on these features and identify the factors that have the greatest influence on property value.

---

## 🎯 Objectives

* Perform data exploration and preprocessing.
* Handle categorical variables using encoding techniques.
* Train and evaluate regression models.
* Compare the performance of multiple models.
* Visualize relationships between features and house prices.
* Identify the most influential features affecting house prices.

---

## 📊 Dataset

* Dataset: Housing Prices Dataset
* Source: Kaggle Housing Dataset
* Records: 545 houses
* Features include:

  * Area
  * Bedrooms
  * Bathrooms
  * Stories
  * Parking
  * Main Road Access
  * Guest Room
  * Basement
  * Hot Water Heating
  * Air Conditioning
  * Preferred Area
  * Furnishing Status

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 🔄 Project Workflow

1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Encoding Categorical Features
4. Train-Test Split (80:20)
5. Linear Regression Model
6. Random Forest Regressor Model
7. Model Evaluation
8. Data Visualization
9. Feature Importance Analysis

---

## 📈 Model Performance

### Linear Regression

* MAE: 970,043.40
* RMSE: 1,324,506.96
* R² Score: 0.653

### Random Forest Regressor

* MAE: 1,021,546.04
* RMSE: 1,400,565.97
* R² Score: 0.612

### Best Performing Model

Linear Regression achieved the highest R² score and performed better than Random Forest on this dataset.

---

## 🔍 Key Insights

* Bathrooms had the strongest influence on house prices.
* Air conditioning significantly increased property value.
* Hot water heating and preferred area positively affected prices.
* Furnishing status also played an important role in determining house prices.
* Linear Regression provided more reliable predictions for this dataset.

---

## 📊 Visualizations

The project includes:

1. House Price Distribution Histogram
2. Correlation Heatmap
3. Actual vs Predicted Price Scatter Plot

---

## 🚀 Future Improvements

* Experiment with additional regression algorithms.
* Perform hyperparameter tuning.
* Use larger and more diverse housing datasets.
* Deploy the model as a web application.

---

## 👩‍💻 Author

Varsha KVS

B.Tech – Artificial Intelligence & Machine Learning

