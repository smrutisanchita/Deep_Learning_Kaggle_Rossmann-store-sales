# Deep_Learning_Kaggle_Rossmann-store-sales

This Repository contains 3 Deep Learning model on Kaggle Rossmann store Dataset.

## Detail regarding the Dataset

Dataset can be obtained from below link:
https://www.kaggle.com/c/rossmann-store-sales/data

### Overview
Rossmann operates over 3,000 drug stores in 7 European countries. Rossmann store managers were tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality.
Data with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. 

### Files
train.csv 			- historical data including Sales
test.csv 				- historical data excluding Sales
sample_submission.csv	- sample submission file in the correct format
store.csv 			- supplemental information about the stores

### Major Data fields
Id  				 - an Id that represents a (Store, Date) duple within the test set
Store 				 - a unique Id for each store
Sales				 - the turnover for any given day (this is what you are predicting)
Customers 			 - the number of customers on a given day
Open 				 - an indicator for whether the store was open: 0 = closed, 1 = open
StateHoliday 			 - indicates a state holiday.  a = public holiday, b = Easter holiday, c = Christmas, 0 = None
SchoolHoliday 			 - indicates if the (Store, Date) was affected by the closure of public schools
StoreType 			 - differentiates between 4 different store models: a, b, c, d
Assortment 			 - describes an assortment level: a = basic, b = extra, c = extended
CompetitionDistance 	 - distance in meters to the nearest competitor store
CompetitionOpenSince	 - gives the approximate year and month of the time the nearest competitor was opened
Promo 				 - indicates whether a store is running a promo on that day
Promo2 				 - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating
Promo2Since[Year/Week] 	 - describes the year and calendar week when the store started participating in Promo2
PromoInterval 			 - describes the consecutive intervals Promo2 is started
![image](https://user-images.githubusercontent.com/10609710/111902476-8689a700-8a35-11eb-9687-2d7e1e1a58dd.png)

