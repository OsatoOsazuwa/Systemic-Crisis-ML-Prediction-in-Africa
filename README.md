# Systemic Crisis Prediction in Africa

## Table of Contents

1. [Project Summary](#Project-Summary)
2. [Dataset](Dataset)
3. [Machine Learning Algorithms Used](#Machine-Learning-Algorithms-Used)
4. [Methodology](#Methodology)
5. [Project Files](#Project-Files)
6. [How to Run](#How-to-Run)
7. [Results](#Results)
8. [Future Work](#Future-Work)

## Project Summary

This project predicts systemic crises in 13 African countries (1860-2014) using a dataset of financial indicators like annual inflation rates. The aim is to develop a classification model to assess the likelihood of systemic crisis emergence.

## Dataset
Dataset can be found [here]

## Machine Learning Algorithms Used

The following algorithms were implemented and compared:

- Logistic Regression
- Random Forest Classifier
- Decision Tree Classifier
- Support Vector Machines (SVM)
- XGBoost Classifier
- KNN

## Methodology

- **Data Preprocessing**:
  - Addressed missing values and outliers.
  - Encoded categorical variables into numerical formats.
- **Model Training and Optimization**:
  - Split dataset into training (80%) and test (20%) sets.
  - Used cross-validation for performance evaluation.
  - Hyperparameter tuning with RandomisedSearchCV to optimize model performance.
- **Evaluation**:
  - Analyzed model predictions using confusion matrix.
  - Accuracy, precision, recall and F1-score metrics were computed also.

## Project Files

[Systemic_Crisis_ML_Prediction.ipynb](Systemic_Crisis_ML_Prediction.ipynb): Contains the full implementation, including data preprocessing, model training, evaluation, and results.

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter notebook:
   ```bash
   jupyter notebook Systemic_Crisis_ML_Prediction.ipynb
   ```

## Results

The project successfully identifies patterns in financial indicators that predict systemic crises. Models are evaluated and compared based on performance metrics, with recommendations for improvements.

## Future Work

- Incorporate additional financial and macroeconomic data for better insights.
- Experiment with advanced ensemble models (e.g., CatBoost, LightGBM).
- Deploy the model for real-time crisis prediction and monitoring.
