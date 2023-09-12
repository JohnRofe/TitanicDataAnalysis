# TitanicDataAnalysis
Data Analysis of the Titanic Dataset

Project Overview

The purpose of this project is to use machine learning  to create a model that predicts which passengers survived the Titanic shipwreck. In this project, I will apply the skills I learned in the Data Analyst Advanced Google Certificate. 

Business Understanding 

This problem represents the analysis of an event in a binary outcome. This project shocase the data analysis and the ability to explore the data, understand its structure and make data-driven decisions. 

Data Understanding 

This data requieres feature engineering to create new variables that improve the model performance, data preprocessing and cleaning as handling missing values, outliers and encoding categorical variables. 

# Data Dictionary

| Variable  | Definition                     | Key                                      |
|-----------|--------------------------------|------------------------------------------|
| survival  | Survival                       | 0 = No, 1 = Yes                           |
| pclass    | Ticket class                   | 1 = 1st, 2 = 2nd, 3 = 3rd                 |
| sex       | Sex                            |                                          |
| Age       | Age in years                   |                                          |
| sibsp     | # of siblings / spouses aboard the Titanic |                                  |
| parch     | # of parents / children aboard the Titanic |                                  |
| ticket    | Ticket number                  |                                          |
| fare      | Passenger fare                 |                                          |
| cabin     | Cabin number                   |                                          |
| embarked  | Port of Embarkation            | C = Cherbourg, Q = Queenstown, S = Southampton |

## Variable Notes
- **pclass**: A proxy for socio-economic status (SES)
  - 1st = Upper
  - 2nd = Middle
  - 3rd = Lower
- **age**: Age is fractional if less than 1. If the age is estimated, it is in the form of xx.5
- **sibsp**: The dataset defines family relations in this way...
  - Sibling = brother, sister, stepbrother, stepsister
  - Spouse = husband, wife (mistresses and fiancés were ignored)
- **parch**: The dataset defines family relations in this way...
  - Parent = mother, father
  - Child = daughter, son, stepdaughter, stepson
  - Some children traveled only with a nanny, therefore parch=0 for them.



Modeling and Evaluation 

The models are evaluated using accuracy, precision, recall and F1-score, as well as Hyperparameter tunning to achieve best results.

Execution 

Trough data visualization the information is compiled in a presentation, which highlights the abilities of communication and story-telling. 

Conclusion

Recommendations based on the insights found during the project
