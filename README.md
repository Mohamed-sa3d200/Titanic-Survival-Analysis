# 🚢 Titanic Survival Analysis & Logistic Regression Model

## 📌 Project Overview

This project explores the famous **Titanic dataset** to analyze the factors that influenced passenger survival.

The main objectives of this project are:

- Perform Exploratory Data Analysis (EDA)
- Visualize survival patterns
- Clean and preprocess the dataset
- Build a Logistic Regression model
- Evaluate model performance

This project is part of my journey in Data Science & Machine Learning.

---

## 📊 Dataset Information

Dataset: Titanic - Machine Learning from Disaster  
Source: Kaggle  

The dataset includes passenger information such as:

- Passenger Class (`Pclass`)
- Gender (`Sex`)
- Age (`Age`)
- Number of siblings/spouses aboard (`SibSp`)
- Number of parents/children aboard (`Parch`)
- Ticket Fare (`Fare`)
- Port of Embarkation (`Embarked`)
- Survival (`Survived`) – Target Variable

Target Variable:
- `0` → Did not survive  
- `1` → Survived  

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Overall survival distribution
- Survival rate by gender
- Survival rate by passenger class
- Age distribution analysis
- Basic correlation analysis

### 📌 Key Insights

- Female passengers had a significantly higher survival rate.
- First-class passengers were more likely to survive.
- Children had higher survival probabilities.
- Gender and passenger class were strong predictive features.

---

## 🧹 Data Preprocessing

Data cleaning and preprocessing steps:

- Handled missing values:
  - Replaced missing `Age` values with the mean
  - Filled missing `Embarked` values with the mode
  - Dropped `Cabin` column due to excessive missing values
- Converted categorical variables into numerical format:
  - `Sex` → Binary encoding
  - `Embarked` → One-hot encoding
- Selected relevant features for modeling

---

## 🤖 Machine Learning Model

Model Used:
- Logistic Regression

Why Logistic Regression?

Because this is a **binary classification problem** (Survived / Not Survived).

The model estimates survival probability using the sigmoid function:

P(y=1) = 1 / (1 + e^-(b0 + b1x1 + ... + bnxn))

---

## 📈 Model Evaluation

Evaluation metrics used:

- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

### ✅ Model Accuracy:
Approximately **75% – 80%** (depending on train-test split)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 👨‍💻 Author

Data Science & Machine Learning Enthusiast  
Continuously building real-world ML projects to strengthen practical skills.