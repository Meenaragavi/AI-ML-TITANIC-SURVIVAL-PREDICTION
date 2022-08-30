# AI-ML-TITANIC-SURVIVAL-PREDICTION

Titanic disaster occurred 100 years ago on April 15, 1912, killing about 1500 passengers
and crew members. The fateful incident still compel the researchers and analysts to understand
what can have led to the survival of some passengers and demise of the others. With the use of
machine learning methods and a dataset consisting of 891 rows in the train set and 418 rows in the
test set, the research attempts to determine the correlation between factors such as age, sex,
passenger class, fare etc. to the chance of survival of the passengers. These factors may or may not
have impacted the survival rates of the passengers. The sinking of the RMS Titanic caused the
death of thousands of passengers and crew is one of the deadliest maritime disasters in history.
One of the reasons that the shipwreck led to such loss of life was that there were not enough
lifeboats for the passengers and crew. The interesting observation which comes out from the
sinking is that some people were more likely to survive than others, like women, children were the
one who got the priority to rescue. The objective is to first explore hidden or previously unknown
information by applying exploratory data analytics on available dataset and then apply different
machine learning models to complete the analysis of what sorts of people were likely to survive.
After this the results of applying machine learning models are compared and analyzed on the basis
of accuracy.

Titanic Dataset:

Data set consists of 12 attributes mixed of Qualitative(categorical) and Quantitative(numeric).
Qualitative Attributes: PassengerId, Survived, Pclass, Sex, Ticket, Cabin & Embarked.
Quantitative Attributes: SlibSp, Parch & Fare.
The data has been split into two groups:
training set(train.csv)
test set(test.csv)

DATA DICTIONARY:

Variable                      Definition
Survival                      survival
Pclass                        ticket class
Sex                           sex
Age                           age in years
Sibsp                         # of siblings / spouses abroad the titanic
Parch                         # of parents / children abroad the titanic
Ticket                        ticket number
Fare                          passenger fare
Cabin                         cabin number
Embarked                      port of embarkation

This is a dataset of Titanic ship passengers & here

a) Each row represents the data of 1 passenger.
b) Columns represent the features. We have 10 features/ variables in this dataset.



1. survival: This variable shows whether the person survived or not. This is our target variable
& we have to predict its value. It’s a binary variable. 0 means not survived and 1 means
survived.
2. pclass: The ticket class of passengers. 1st (upper class), 2nd (middle), or 3rd (lower).
3. Sex: Gender of passenger
4. Age: Age (in years) of a passenger
5. sibsp: The no. of siblings/spouses of a particular passenger who were there on the ship.
6. parch: The no. of parents/children of a particular passenger who were there on the ship.
7. ticket: Ticket Number
8. fare: Passenger fare (like 1st class ticket fare must be greater than 2nd pr 3rd class ticket
right)
9. cabin: Cabin Number
10. embarked: Port of Embarkation; From where that passenger took the ship. ( C = Cherbourg,
Q = Queenstown, S = Southampton)


Dataset from kaggle: https://www.kaggle.com/competitions/titanic/data
