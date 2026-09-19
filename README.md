# Heart-Disease-Prediction
A Machine Learning model predicting heart disease likelihood using Logistic Regression.


# Heart Disease Prediction 🫀

## Overview
This project aims to predict the likelihood of a patient having heart disease based on various medical attributes (e.g., age, cholesterol levels, maximum heart rate). Early detection through machine learning can significantly assist medical professionals in proactive diagnosis and treatment.

## The Approach & Technical Decisions
I performed a complete data science lifecycle, including:
1. **Exploratory Data Analysis (EDA):** Visualized feature distributions and correlation matrices to understand the medical indicators.
2. **Data Preprocessing:** Addressed missing values and applied `StandardScaler` to normalize feature scales.
3. **Model Selection (The "Why"):** 
   I trained and evaluated both **Random Forest** and **Logistic Regression**. 
   * *Logistic Regression* outperformed Random Forest, achieving an accuracy of **88.89%** (compared to RF's 87.04%). 
   * **Key Insight:** Due to the relatively small size of the medical dataset, complex ensemble models like Random Forest are prone to overfitting (memorizing the training data). Logistic Regression provided a more robust, generalized, and highly interpretable model, making it the optimal choice for this specific clinical dataset.

## Results
* **Algorithm Chosen:** Logistic Regression
* **Accuracy:** 88.89%
* **Feature Importance:** The model successfully identified key medical features influencing heart disease, mapped through coefficient analysis.

## Technologies Used
* **Python**
* **Pandas & NumPy** (Data Manipulation)
* **Scikit-Learn** (Machine Learning & Scaling)
* **Matplotlib & Seaborn** (Data Visualization)
