# Titanic Survival Prediction

## Project Overview

This project uses machine learning to predict whether a passenger survived the Titanic disaster.

The project covers the complete machine learning workflow:

- Data cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Data preprocessing
- Model training
- Model evaluation
- Hyperparameter tuning
- Model comparison

## Dataset

The dataset contains information about Titanic passengers, including:

- Passenger class
- Sex
- Age
- Number of siblings/spouses
- Number of parents/children
- Fare
- Port of embarkation
- Cabin information

## Feature Engineering

The following features were created:

- `FamilySize`
- `IsAlone`
- `Title`
- `Deck`
- `AgeGroup`
- `TicketGroupSize`
- `Cabin_known`

## Machine Learning Models

The following classification models were tested:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K-Nearest Neighbors (KNN)
5. Tuned Random Forest

## Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 83.80% |
| Tuned Random Forest | 79.33% |
| Random Forest | 78.77% |
| KNN (Scaled) | 77.09% |
| Decision Tree | 76.54% |

Logistic Regression achieved the highest test accuracy on this dataset split with an accuracy of approximately **83.8%**.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
01-Titanic-Survival-Prediction/
├── Titanic_Survival_Prediction.ipynb
├── titanic.csv
└── README.md