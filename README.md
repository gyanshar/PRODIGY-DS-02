# Titanic Exploratory Data Analysis and Prediction
This project aims to perform exploratory data analysis on the Titanic disaster dataset and predict which people are more likely to survive.


## Problem Statement:
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.
While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).


## Dataset Overview:

The data has been split into two groups:

- training set (train.csv)
- test set (test.csv)

#### Data Dictionary: 

- survival: Survival	(0 = No, 1 = Yes)
- pclass:	Ticket class	(1 = 1st, 2 = 2nd, 3 = 3rd)
- sex:	Sex	
- Age:	Age in years	
- sibsp:	# of siblings / spouses aboard the Titanic	
- parch:	# of parents / children aboard the Titanic	
- ticket:	Ticket number	
- fare:	Passenger fare	
- cabin:	Cabin number	
- embarked:	Port of Embarkation	(C = Cherbourg, Q = Queenstown, S = Southampton)

#### Variable Notes
- pclass: A proxy for socio-economic status (SES) <br>
1st = Upper <br>
2nd = Middle <br>
3rd = Lower
- age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5
- sibsp: The dataset defines family relations in this way... <br>
Sibling = brother, sister, stepbrother, stepsister <br>
Spouse = husband, wife (mistresses and fiancés were ignored)
- parch: The dataset defines family relations in this way... <br>
Parent = mother, father <br>
Child = daughter, son, stepdaughter, stepson <br>
Some children travelled only with a nanny, therefore parch=0 for them.


## Key Visualizations:
- Correlations between different variables
- Survival rate by gender and passenger class
- Survival rate by number of siblings/ spouses on the ship and number of parents/children on the ship


## Insights:
- Survival rate of women is higher even though there were more men
- Most people had passenger class 3 ticket
- Most people were w/o siblings/spouses

## Model Building:
- Algorithms Used:
   - Logistic Regression: 0.7988826815642458
   - Support Vector Machine: 0.6536312849162011
   - KNN Classifier: 0.7094972067039106
   - Naive Bayes: 0.770949720670391
   - Decision Tree: 0.776536312849162
   - Random Forest Classifier: 0.8156424581005587
    
