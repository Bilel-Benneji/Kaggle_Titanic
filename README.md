# Titanic: Machine Learning from Disaster

In this repository, you will find the road map that I followed to build a machine learning model for a Kaggle competition. The model's predictions gave me a score of **79% score**. <br>


You can find further information about the competition [here](https://www.kaggle.com/c/titanic)<br><br>

Workflow: <br>
- Exploratory Data Analysis. <br>
  - Surviving rate
  - Pclass
  - Name
  - Sex
  - Age
  - SibSp, Parch
  - Ticket
  - Fare
  - Cabin
  - Embarked
- Feature Engineering  <br>
  - Imputation on Embarked and Age columns
  - Title extraction
  - New features based on cabin and ticket
  - Encoding sex column
  - Family size
  - Is Alone
  - One Hot Encoding for all categorical variables
- Machine Learning
  - Split data into train and test sets
  - Initialize a Random Forest Classifier along with Gradient Boosting Classifier
  - Train a Logistic Regression Model based on the previous two models
  - Hyperparameter Tuning with Grid Search and Randomized Search
  - Prediction
