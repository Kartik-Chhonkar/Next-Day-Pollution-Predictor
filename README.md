# 🌍 Next-Day Pollution Predictor

> Predicting environmental pollution patterns using Machine Learning and real-world air quality indicators.

## 📌 Overview

The **Next-Day Pollution Predictor** is a machine learning project designed to analyze air quality parameters and classify environmental zones based on pollution characteristics. Using historical pollution measurements such as CO, NO₂, SO₂, O₃, PM2.5, and PM10, the model learns patterns that distinguish between different urban environments and predicts pollution categories with high accuracy.

This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and prediction.

---

## 🚀 Features

✅ Data cleaning and preprocessing

✅ Exploratory Data Analysis (EDA)

✅ Pollution trend analysis

✅ Feature scaling and transformation

✅ Logistic Regression implementation

✅ Model evaluation using multiple metrics

✅ Classification of city pollution types

✅ Reproducible Jupyter Notebook workflow

---

## 📊 Dataset Information

The dataset contains over **52,000 environmental records** collected from multiple cities worldwide.

### Attributes

| Feature | Description                          |
| ------- | ------------------------------------ |
| Date    | Timestamp of observation             |
| City    | City name                            |
| CO      | Carbon Monoxide concentration        |
| NO₂     | Nitrogen Dioxide concentration       |
| SO₂     | Sulfur Dioxide concentration         |
| O₃      | Ozone concentration                  |
| PM2.5   | Fine particulate matter              |
| PM10    | Coarse particulate matter            |
| Type    | Pollution category (Target Variable) |

### Cities Included

* Moscow
* Delhi
* Beijing
* Zurich
* Vancouver
* Stockholm

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook
* Google Colab

---

## 📂 Project Structure

```bash
Next-Day-Pollution-Predictor/
│
├── logisticReg.ipynb
├── City_Types.csv
├── README.md
│
└── outputs/
    ├── visualizations
    ├── confusion_matrix
    └── model_results
```

---

## ⚙️ Machine Learning Pipeline

### 1. Data Collection

Air quality data was collected and consolidated into a structured dataset.

### 2. Data Preprocessing

* Missing value handling
* Datetime conversion
* Feature selection
* Encoding categorical variables

### 3. Feature Scaling

* StandardScaler
* QuantileTransformer

### 4. Model Training

A Logistic Regression classifier was trained using pollution indicators as input features.

### 5. Model Evaluation

Performance was evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Precision
* Recall
* F1 Score

---

## 📈 Key Insights

* Industrial regions generally exhibited higher concentrations of CO, SO₂, and particulate matter.
* Residential regions showed comparatively lower pollutant concentrations.
* PM2.5 and PM10 were among the most influential indicators in determining pollution categories.
* Feature scaling significantly improved model stability and prediction performance.

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/Kartik-Chhonkar/Next-Day-Pollution-Predictor.git
```

### Navigate to Project Directory

```bash
cd Next-Day-Pollution-Predictor
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run Notebook

```bash
jupyter notebook logisticReg.ipynb
```

or open directly in Google Colab.

---

## 🎯 Future Improvements

* Random Forest Classification
* XGBoost Implementation
* Deep Learning Models
* Air Quality Index (AQI) Prediction
* Time-Series Forecasting
* Real-Time Pollution Monitoring Dashboard
* API Deployment using Flask/FastAPI

---



