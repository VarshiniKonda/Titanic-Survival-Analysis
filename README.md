# Titanic Survival Prediction Using Machine Learning

## Project Overview
This project focuses on analyzing the Titanic passenger dataset and predicting passenger survival using Machine Learning algorithms.

The project includes data cleaning, preprocessing, exploratory data analysis, feature encoding, model training, evaluation, and survival prediction for new passenger records.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

## Project Workflow
1. Data Loading and Exploration
2. Data Cleaning and Missing Value Handling
3. Exploratory Data Analysis (EDA)
4. Categorical Feature Encoding
5. Train-Test Split
6. Data Preprocessing using Scikit-learn Pipeline
7. Model Training:
   - Logistic Regression
   - Random Forest Classifier
8. Model Evaluation
9. Model Comparison
10. Feature Importance Analysis
11. Passenger Survival Prediction
12. Model Saving using Joblib

## Model Performance

Evaluation results on the 20% test dataset:

| Metric | Logistic Regression | Random Forest |
|---|---:|---:|
| Accuracy | 80.45% | 79.33% |
| Precision | 79.31% | 76.67% |
| Recall | 66.67% | 66.67% |
| F1-Score | 72.44% | 71.32% |

**Best Performing Model:** Logistic Regression

## Sample Prediction
The trained Logistic Regression model was used to predict survival for a sample passenger.

- Predicted Result: Survived
- Survival Probability: 59.77%
- Non-Survival Probability: 40.23%

## Project Files
- `Titanic_Survival_Analysis.ipynb` – Complete project implementation.
- `cleaned_titanic.csv` – Preprocessed Titanic dataset.
- `titanic_survival_model.pkl` – Saved machine learning pipeline.

## How to Run
1. Clone or download this repository.
2. Open the notebook using Google Colab or Jupyter Notebook.
3. Upload the original Titanic `train.csv` dataset.
4. Run the notebook cells sequentially.

## Dataset
Titanic passenger dataset from the Kaggle Titanic Machine Learning Competition.

Dataset: https://www.kaggle.com/competitions/titanic/data

## Conclusion
This project demonstrates the application of Python and Machine Learning techniques to analyze passenger data and predict survival outcomes. Logistic Regression achieved 80.45% accuracy on the test dataset.

---
**Developed using Python and Machine Learning.**
