# 🏥 Health Insurance Prediction

A Machine Learning project that predicts **health insurance charges** based on customer demographic and health-related information.

## 📌 Project Overview

This project builds a predictive model to estimate **health insurance costs** using historical insurance data.
The workflow includes:

* Data loading and preprocessing
* Data cleaning
* Exploratory analysis
* Encoding categorical variables
* Multicollinearity analysis using VIF
* Model training using Linear Regression
* Performance evaluation

The goal is to understand how factors such as age, smoking habits, hospitalizations, and family information affect insurance charges.

---

## 📂 Dataset

The project uses an insurance dataset containing features such as:

* Age
* Number of children
* Smoker status
* Number of past hospitalizations
* Other demographic and medical-related attributes
* Insurance charges (Target Variable)

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels

---

## 📊 Project Workflow

### 1. Data Loading

Import dataset and inspect structure.

### 2. Data Cleaning

* Check missing values
* Validate data types
* Prepare dataset for modeling

### 3. Feature Engineering

* Encode categorical variables using **LabelEncoder**

### 4. Multicollinearity Analysis

* Calculate **Variance Inflation Factor (VIF)**
* Identify highly correlated independent variables

### 5. Model Building

* Split dataset into training and testing sets
* Train model using **Linear Regression**

### 6. Model Evaluation

Evaluate performance using:

* R² Score
* Mean Squared Error (MSE)

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/health-insurance-prediction.git
```

Move into project directory:

```bash
cd health-insurance-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run notebook:

```bash
jupyter notebook
```

---

## ▶️ Usage

Open:

```text
Health_insurance_prediction.ipynb
```

Run all cells sequentially to:

* preprocess data
* train the model
* generate predictions
* evaluate results

---

## 📈 Model

Algorithm used:

* Linear Regression

Evaluation Metrics:

* R² Score
* Mean Squared Error

---

## 📁 Project Structure

```text
Health-Insurance-Prediction/
│
├── Health_insurance_prediction.ipynb
├── insurance.csv
├── README.md
└── requirements.txt
```

---

## 🔮 Future Improvements

* Add multiple ML algorithms
* Hyperparameter tuning
* Feature scaling
* Deploy using Streamlit or Flask
* Build an interactive dashboard

---

## 👤 Author

**Rajguru Hiremath**

If you found this project useful, consider giving it a ⭐ on GitHub.
# Health-insurance-prediction-using-Linear-Regression-ML-Model
