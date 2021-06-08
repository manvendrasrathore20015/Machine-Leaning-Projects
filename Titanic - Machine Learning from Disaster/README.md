
## Problem Statement
Use machine learning to create a model that predicts which passengers survived the Titanic shipwreck or not.

## Dataset
1). train.csv:- training dataset, contains all attributes required to make a predictive model along with the outcome attribute i.e. "ground truth".

2). test.csv:- testing dataset, contains all attributes except outcome.

3). gender_submission.csv:- a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like.

## Attributes Dictionary

PassengerID:- Unique Id's of passenger

Survived:- Target column
1 = Survived
0 = Not Survived.

Pclass: Ticket Class
1 = Upper class
2 = Middle class
3 = Lower class

Name:- Name of passenger.

Sex:- Sex of passenger.

Age:- Age of passenger in years.

Sibsp:- The dataset defines family relations in this way.
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

Parch:- The dataset defines family relations in this way.
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.

Ticket:- Ticket number of passenger.

Fare:- Passenger Fare.

Cabin:- Cabin Number.

Embarked:- Port of Embarkation(port on which passenger started journey).
C = Cherbourg
Q = Queenstown
S = Southampton.
