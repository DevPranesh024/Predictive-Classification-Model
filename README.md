Titanic Survival Prediction using Machine Learning

 Overview

This project predicts whether a passenger would survive the Titanic disaster using Machine Learning. The dataset is preprocessed, analyzed, and used to train a Random Forest Classifier. Hyperparameter tuning is performed using GridSearchCV to improve the model's performance.

This project demonstrates a complete Machine Learning workflow including data preprocessing, visualization, model training, evaluation, and prediction.



Objectives

- Clean and preprocess the Titanic dataset
- Perform exploratory data analysis (EDA)
- Train a Random Forest Classification model
- Optimize the model using GridSearchCV
- Evaluate model performance
- Predict survival for new passengers


Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib



Dataset

Dataset:Titanic Dataset

The dataset contains passenger information such as:

- Passenger Class
- Sex
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Fare
- Embarked Port
- Survival Status

---

 Machine Learning Workflow

Data Preprocessing

- Loaded the Titanic dataset
- Handled missing values
- Removed unnecessary columns
- Encoded categorical variables
- Applied One-Hot Encoding
- Standardized numerical features

---

Exploratory Data Analysis

Visualization includes:

- Survival Rate by Passenger Class
- Survival Rate by Gender

The project uses Seaborn and Matplotlib to understand relationships between passenger features and survival.


Model Training

Algorithm Used:

- Random Forest Classifier

The dataset is divided into:

- 80% Training Data
- 20% Testing Data

Feature scaling is applied using StandardScaler.

---

Hyperparameter Tuning

GridSearchCV is used to find the optimal values for:

- Number of Estimators
- Maximum Depth
- Minimum Samples Split

This improves the overall model performance.



Model Evaluation

The trained model is evaluated using:

- Classification Report
- Precision
- Recall
- F1-Score
- Accuracy



Prediction

A prediction function is implemented to estimate whether a passenger would survive based on:

- Passenger Class
- Gender
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Fare
- Embarked Port



Project Structure

```
Titanic-Survival-Prediction/
│
├── ML Project.ipynb
├── Titanic-Dataset.csv
├── titanic_rf_model.pkl
├── README.md
└── requirements.txt
```

---




Results

✔ Data cleaned and preprocessed

✔ Exploratory Data Analysis completed

✔ Random Forest model trained

✔ Hyperparameter tuning performed using GridSearchCV

✔ Machine Learning model saved as:

```
titanic_rf_model.pkl
```

✔ Survival prediction function implemented

---



Author

Dev Pranesh

B.Tech Computer Science Student

Areas of Interest

- Machine Learning
- Data Science
- Data Analytics
- Artificial Intelligence
- Data Engineering
