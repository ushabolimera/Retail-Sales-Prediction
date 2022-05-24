# Retail-Sales-Prediction
# Problem Statement
This project involves solving a real-world business problem of sales forecasting and building up a machine learning model for the same. Our goal here is to forecast the sales for six weeks for each store and find out the factors influencing it and recommend ways in order to improve the numbers.

# Data Description
Id - an Id that represents a (Store, Date) duple within the set

Store - a unique Id for each store

Sales - the turnover for any given day (Dependent Variable)

Customers - the number of customers on a given day

Open - an indicator for whether the store was open: 0 = closed, 1 = open

StateHoliday - indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are closed on public holidays and weekends. a = public holiday, b = Easter holiday, c = Christmas, 0 = None

SchoolHoliday - indicates if the (Store, Date) was affected by the closure of public schools

StoreType - differentiates between 4 different store models: a, b, c, d

Assortment - describes an assortment level: a = basic, b = extra, c = extended. An assortment strategy in retailing involves the number and type of products that stores display for purchase by consumers.

CompetitionDistance - distance in meters to the nearest competitor store

CompetitionOpenSince[Month/Year] -gives the approximate year and month of the time the nearest competitor was opened

Promo - indicates whether a store is running a promo on that day

Promo2 - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating

Promo2Since[Year/Week] – describes the year and calendar week when the store started participating in Promo2

PromoInterval - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store.

# Data Pipeline
# Data Processing
Understanding and cleaning the data

# Data Exploration
Analyse the data through visualization

# Model Performed
Linear Regression

Decision Tree

Random Forest

# Conclusion
Upon having this analysis, it can be established that given the dataset, the model developed is able to explain 95.5878 % of the variations and is able to predict the sales values in a good range.

Random Forest Tuned Model gave the best results and only 0.062% improvement was seen from the basic random forest model which indicates that all the trends and patterns that could be captured by these models without overfitting were done and maximum level of performance achievable by the model was achieved.

The outliers in the dataset showed justifiable behavior. The outliers were either of store type b or had promotion going on which increased sales.

Most stores have competition distance within the range of 0 to 10 kms and had more sales than stores far away, probably indicating competition in busy locations vs remote locations.
