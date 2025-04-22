# 🚗 Vehicle Emission Classification

This project classifies vehicles into emission categories (A, B, or C) based on engine size, fuel type, and CO₂ emissions using machine learning.

## 📌 Problem Statement
Predict the emission category of a vehicle using engine and fuel-related features to assist in environmental monitoring and automotive regulation.

## 👩‍💻 Author
**Name:** Diya Maheshwari  
**Roll Number:** 202401100300108  
**Branch:** CSE (AI)  
**Section:** B

## 📊 Dataset
The dataset includes the following columns:
- `engine_size`
- `fuel_type`
- `co2_emissions`
- `emission_category`

## ⚙️ Methodology
- Data loading and preprocessing using `pandas`
- Encoding of categorical variables using `LabelEncoder`
- Splitting the dataset into training and test sets
- Training a `RandomForestClassifier`
- Evaluating performance using a classification report
- Making predictions on new user input

## 🧠 Algorithms Used
- **Random Forest Classifier**: A robust ensemble learning method for classification.

## 💾 Libraries Required
- `pandas`
- `scikit-learn`

Install them via:
```bash
pip install pandas scikit-learn
