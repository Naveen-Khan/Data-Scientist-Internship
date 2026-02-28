# Task 1: 🚢 Titanic Survival Classification 
Use the Titanic dataset, build a machine learning model to predict whether a
passenger survived or not based on features like age, gender, ticket class, and fare.
Your task is to clean and preprocess the data, train a classification model, and
evaluate its performance.

# 📌Project Overview

- This project builds a Machine Learning Classification Model to predict whether a passenger survived the Titanic disaster using the famous Titanic Dataset.
- The model uses passenger information such as age, gender, ticket class, fare, and family details to predict survival.

  ### Dataset Features

- The dataset includes the following features:
- PassengerId
- Pclass (Ticket Class)
- Name
- Sex
- Age
- SibSp (Siblings/Spouses)
- Parch (Parents/Children)
- Fare
- Embarked

Survived (Target Variable)


### Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values (Age, Embarked)
- Encoding categorical variables (Sex, Embarked)
- Feature selection
- Train-Test split (80% Training, 20% Testing)
- No data shuffling to maintain consistency

# 🤖 Model Used
###  Decision Tree Classifier

Implemented using:
      
      from sklearn.tree import DecisionTreeClassifier
Key parameters used:

    - max_depth=5 (to prevent overfitting)

    - random_state=42 (for reproducibility)

###  Model Evaluation

Evaluation metrics used:
- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-Score

###  Final Results
Training Accuracy: 93%
Testing Accuracy: 92%

### 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
