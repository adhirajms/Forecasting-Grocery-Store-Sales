# msca-31006-time-series-forecasting-project

# Forecasting Store Sales in Ecuador 
This project is a part of the Time Series Forecasting Class at the University of Chicago's Master in Science in Analytics Program.  


## Project Intro/Objective
The purpose of this project is to forecast the sales of multiple Favorita stores located in Ecuador. The end goal is to be able to accurately predict sales, in order to help Favorita make better decisions around the amount of inventory to buy for each store to decrease waste and increase customer satisfaction. 


### Methods Used
* Time Series Forecasting
* Machine Learning
* Data Visualization
* Predictive Modeling


### Technologies
* R 
* Excel

## Dataset
The dataset, with more information can be found on kaggle, linked [here](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data?select=oil.csv) 

The dataset includes daily data from 2013-01-01 to 2017-08-15

There are multiple datasets as part of this project (all can be found in the /Data folder):
- train.csv: daily data for each store, product family, dollar value of sales, and promotion data
- oil.csv: daily data for oil prices 
- holidays_events.csv: data about when a holiday/event happened and whether it was a local, regional or national event. 
- stores.csv: meta data around each stores
- transactions.csv: daily data for each store, product family, and the number of transactions. 


## Methodology

For this analysis we narrowed our scope to just the top 5 stores by sales. We used 4 different time series models to predict the weekly sales:
- ARIMA
- Dynamic Regression 
- Prophet 
- Hierarihcal TS Modeling 


## Contributing Members

|Name     |  GitHub Handle   | 
|---------|-----------------|
|[Priyank Shroff](https://github.com/[shroffp05])| @shroffp05        |
|[Aman Gupta](https://github.com/[aman-221]) |     @aman-221    |
|[Michelle Tang](https://github.com/[michelle-h-tang])| @michelle-h-tang        |
|[Adhiraj M Srivastava](https://github.com/[adhirajms]) |     @adhirajms   |
