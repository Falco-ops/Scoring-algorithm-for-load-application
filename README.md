# Scoring algorithm for load application
Development of a scoring model for loan application.

## Data
Dataset contains information about borrower loan histories, borrower finances and borrower behaviors.

## Models
The following models were tested :
* Logistic regression
* Random Forest
* XG Boost

Additionnaly multiple features were added to the best performing model : polynomial and feature designed based on exploratory analysis.
See main notebook for more details.
Hyper parameters were tuned with RandomizedSearchCV to gain computing time accross 5 parameters (3 values per parameters).

## Performance
Best performing model was XGBoost after tuning and feature engineering with a score of 0.7633.

## Notebook table of content 

![Table_of_contact](https://user-images.githubusercontent.com/65543520/224170546-a94ded05-ab15-4f12-955d-fedea659e668.png)
