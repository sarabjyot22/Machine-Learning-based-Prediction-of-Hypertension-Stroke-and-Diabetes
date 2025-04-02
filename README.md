# 📌 Diabetes, Hypertension, and Stroke Prediction

## 📖 Overview
This project focuses on predicting diabetes, hypertension, and stroke using machine learning models based on health and lifestyle factors. The dataset contains demographic, medical history, and lifestyle information to train predictive models for early detection of these conditions.

## 📊 Dataset Description

The dataset includes the following features:

**Age** – Age category

**Sex** – 0 = Female, 1 = Male

**BMI** – Body Mass Index

**HighChol** – 0 = No, 1 = High cholesterol

**CholCheck** – 0 = No cholesterol check in 5 years, 1 = Yes

**Smoker** – 0 = No, 1 = Yes

**HeartDisease** – 0 = No, 1 = Yes

**PhysActivity** – 0 = No, 1 = Yes

**Fruits** – 0 = No, 1 = Yes

**Veggies** – 0 = No, 1 = Yes

**HvyAlcoholConsumption** – 0 = No, 1 = Yes

**GenHlth** – Self-reported health status (1-5 scale)

**Diabetes** – 0 = No, 1 = Yes

**Hypertension** – 0 = No, 1 = Yes

**Stroke** – 0 = No, 1 = Yes                   

## ⚙️ Installation
To install the required dependencies, run:
```
pip install -r requirements.txt
```
## 🚀 Usage
- ## 1️⃣ Load the dataset

- Ensure the dataset (data.csv) is available in the project directory.

- ## 2️⃣ Run the Jupyter Notebook

Open and execute the notebook:
```
jupyter notebook diabetes-hypertension-and-stroke-prediction.ipynb
```
- ## 3️⃣ Perform Exploratory Data Analysis (EDA)

- Analyze feature distributions and correlations.

- ## 4️⃣ Preprocess the Data

- Handle missing values and encode categorical variables.

- ## 5️⃣ Train Machine Learning Models

- Models used in this project:

- Logistic Regression

- Decision Trees

- Random Forest

- Support Vector Machine (SVM)

- ## 6️⃣ Evaluate Model Performance

- Metrics used:

- Accuracy

- Precision

- Recall

- F1-score

## 🛠 Project Structure
📁 Classification Project
- ├── 📜 diabetes-hypertension-and-stroke-prediction.ipynb  # Jupyter Notebook
- ├── 📊 data.csv                                           # Dataset
- ├── 📦 requirements.txt                                   # Dependencies
- ├── 📘 README.md                                         # Project Documentation

## 📌 Notes
- The dataset undergoes preprocessing to clean missing values and encode categorical features.

- Feature importance analysis helps identify key health indicators.

- Models are optimized for better classification performance.

## 🤝 Contributing
Contributions are welcome! Feel free to improve model performance and data analysis by submitting a pull request. 🚀

