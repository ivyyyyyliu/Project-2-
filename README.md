# Project-2-

# Author:LiPing Liu

### Goal: 

The goal of this project is to predict the patient whether have stroke based on gender, age, disease, smoke status,etc.

## Data Source

https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

## Method:
   - Data was preprocessed by using SimpleImputer, pipelines and column transfer.
   - Maching Learning Using the Following Models:
      - Decision Tree Regressor Model
      - KNN Model

## Visualization:

<img src="https://github.com/ivyyyyyliu/Project-2-/blob/main/Average%20age%20of%20Patients%20got%20stroke%20or%20not.png" height="500" width="800" >
   0 indicates the patients do not have stroke. 1 indicates the patients do not have stroke
   This graph shows that people who have stroke usually with higher average age. The average age for people who have stroke are about almost 70 years old.
   

<img src="https://github.com/ivyyyyyliu/Project-2-/blob/main/Project%202.png" height="400" width="600" >
   
   This graph shows relationship between smoking status and average BMI. People who never smoked have lower BMI that people who foremely smoked and smokes. Furthmore, smoking might cause people who have higher BMI.

## Models Evaluated & Results
- Decision Tree Regressor Model (Testing Set): 0.8982785602503912
- Tuned Decision Tree Regressor Model (Testing Set):0.9374021909233177
- kNN Model (Testing Set):0.9366197183098591
- Tuned kNN Model (Testing Set):0.9374021909233177

## Model Performance

Overall, the best model is definitely the tuned KNN Model. Even though they both have same score after the tuned but  before the tuned it has better score than the decision tree.


## For Further Information
### For any additional questions, please contact:
- LiPing Liu
- ivyliuzp@gmail.com
