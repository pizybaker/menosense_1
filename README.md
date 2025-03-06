

# MenoSense: Predicting Menopause Onset with Machine Learning

## 🚀 Project Overview
MenoSense is an AI-driven tool designed to predict menopause onset using household information, medical data, lifestyle, genetics, and health factors. The model provides personalized insights to support healthcare professionals and empower women with data-driven predictions.

## 📂 Dataset
- **Source:** Adapted from the SWAN (Study of Women's Health Across the Nation) study.
- **Data Handling:** Class imbalance was addressed using **oversampling**, leading to improved model performance.

## 🧠 Machine Learning Approach
- **Model Used:** Gradient Boosting Classifier. Gradient Boosting Regressor
- **Accuracy:** 97.78%
- **F1 Score:** 0.98
- **Improvements:** Applied oversampling to reduce bias towards the majority class.

## ✨ Features
- Predicts **menopause status** and **years until menopause**.
- **User-friendly interface** for easy data input and interpretation.


## 📝 Input Guidance
Users need to provide:
- **LMP Day:** Day of the month of the last menstrual period.
- **Ethnicity:** Select from 1-White, 2-Black, 3-Hispanic, 4-Asian, 5-Other.
- **Pregnancy Status, BMI, Smoking Status, Alcohol Consumption**: Categorical and numeric inputs.
- **Lifestyle, Health, and Stress Factors:** Scaled from 0 to 10.

## 📈 Model Performance
- **Confusion Matrix:** Shows strong performance in predicting post-menopausal status.
- **F1 score** 
