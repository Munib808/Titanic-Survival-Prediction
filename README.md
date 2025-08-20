# Titanic Survival Prediction Project

## Project Overview
The goal of this project is to build a classifier that predicts whether a passenger survived the Titanic disaster based on various features like age, sex, class, etc. The project follows a typical data science workflow: data loading, exploration, preprocessing, model training, and evaluation.

## Dataset
The dataset used is the Titanic dataset, which contains information about 891 passengers. The features include:

- **PassengerId**: Unique ID for each passenger  
- **Survived**: Survival status (0 = No, 1 = Yes)  
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- **Name**: Passenger name  
- **Sex**: Gender  
- **Age**: Age in years  
- **SibSp**: Number of siblings/spouses aboard  
- **Parch**: Number of parents/children aboard  
- **Ticket**: Ticket number  
- **Fare**: Passenger fare  
- **Cabin**: Cabin number  
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)  

## Installation
To run this notebook, you need to have Python installed along with the following libraries:

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- xgboost
  
## Usage
1. Clone the repository or download the notebook.  
2. Ensure the dataset `Titanic-Dataset.csv` is in the correct path (update the path in the notebook if necessary).  
3. Run the notebook cells sequentially to reproduce the analysis and models.  

## Data Preprocessing
- Handling missing values in `Age`, `Cabin`, and `Embarked`.  
- Encoding categorical variables like `Sex` and `Embarked`.  
- Scaling numerical features for better model performance.  

## Exploratory Data Analysis (EDA)
- Distribution of survival rates.  
- Analysis of survival based on `Pclass` and `Sex`.  
- Visualization of correlations and patterns in the data.  

## Model Training and Evaluation
Multiple models are trained and evaluated:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- XGBoost  

Models are evaluated using:  
- Accuracy  
- Confusion Matrix  
- Classification Reports  

Cross-validation and hyperparameter tuning (`GridSearchCV`) are employed to optimize performance.  

## Results
- The best-performing model is selected based on cross-validation scores and test accuracy.  
- Detailed results including confusion matrices and classification reports are provided for each model.  
