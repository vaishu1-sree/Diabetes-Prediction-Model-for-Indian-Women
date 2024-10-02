<img src="https://github.com/user-attachments/assets/77e19eaf-e812-4c30-99fc-c81f6759f31a" alt="image description" width="600" />


# Diabetes Prediction Model for Indian Women

This project is a **machine learning** initiative aimed at diagnosing diabetes based on medical data from women of **Pima Indian heritage**. Diabetes is a metabolic disorder characterized by prolonged high blood sugar levels. If left untreated, diabetes can lead to severe complications such as cardiovascular disease, kidney failure, and nerve damage.

## Objective
The goal of this project is to develop a **machine learning model** that accurately predicts whether a patient has diabetes based on various medical diagnostic factors. These factors include:

- Number of pregnancies
- BMI (Body Mass Index)
- Insulin levels
- Age
- And other health metrics

## Dataset Overview
The dataset used in this project comes from the **National Institute of Diabetes and Digestive and Kidney Diseases**. It includes several medical predictor variables and one target variable, `Outcome`, which indicates whether the patient has diabetes or not. Some key predictor variables include:

- Blood pressure
- Glucose levels
- Skin thickness

This dataset focuses specifically on **female patients** aged **21 or older**.

## Results
After experimenting with various machine learning techniques, the final model was **optimized using XGBoost** along with **hyperparameter tuning**. This model achieved the best performance, with a **Cross Validation Score of 0.90**, making it the most accurate in predicting diabetes from the dataset.

## Conclusion
This project demonstrates how machine learning models, particularly XGBoost, can be effectively utilized for **medical diagnosis** tasks like predicting diabetes. With further optimization and data collection, such models could be instrumental in clinical decision-making.
