# CS316-project
# Cardiovascular Disease Prediction Using Machine Learning

## 1. Project Overview
This project aims to develop machine learning models to predict cardiovascular disease outcomes using patient medical and clinical information. The project explores different classification algorithms and compares their performance to identify the most effective model.

## 2. Dataset
The project uses the Heart Failure Clinical Records Dataset.

The dataset contains 299 patient records and 13 variables, including:
- Age
- Anaemia
- Diabetes
- High blood pressure
- Ejection fraction
- Serum creatinine
- Serum sodium
- Platelets
- Smoking
- Sex
- Follow-up time

The target variable is `DEATH_EVENT`, which indicates whether the patient died during the follow-up period.

## 3. Data Preprocessing
The preprocessing stage includes:
- Checking and cleaning the dataset.
- Examining missing values and invalid data.
- Handling outliers, if applicable.
- Preparing features for model training.
- Splitting the dataset into training and testing sets.

## 4. Machine Learning Models
The following classification models were implemented and evaluated:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree

Hyperparameter tuning was also performed using GridSearchCV to improve model performance.

## 5. Model Evaluation
The models were evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

These metrics were used to compare the models and understand their prediction performance.

## 6. Results
The models were compared based on their performance on the test dataset.

The results showed differences in accuracy, precision, recall, and F1-score. The best-performing model was selected based on the evaluation results.

## 7. Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 8. How to Run the Project
1. Clone or download this repository.
2. Open the notebook using Google Colab.
3. Upload the dataset.
4. Run the notebook cells in order.
5. Review the model training, evaluation, and comparison results.

## 9. Team Members
- Member 1: [Name]
- Member 2: [Name]
- Member 3: [Name]

## 10. Conclusion
This project demonstrates the use of machine learning classification algorithms for predicting mortality outcomes among patients with heart failure. The results provide a comparison of different models and highlight opportunities for further improvement.
