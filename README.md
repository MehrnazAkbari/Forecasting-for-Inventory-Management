# Forecasting-for-Inventory-Management
This project aims to predict the quantity of flower containers that will be transacted in the future. The structures of forecasting models used in this project are summarized in this repository. All files are started with DataPipeline preprocessing steps. After collecting, cleaning, filtering, aggregating and analysing data, the forecasting models are implemented and compared in terms of accuracy.

Each file contains a concept as explained the following:

## FileName: Diverse Aggregations & AR Methods
In this file the quantity of transacted containers in all italian inventories are shown. Various time aggregations (Daily, Weekly, Monthly and seasonally) are analysed. Moreover, ARMA and ARIMA methods are modeled through the analysis of AutoCorrelation Function(ACF) and Partial AutoCorrelation Function(PACF). The comparison among the results of AR family models and the outcome of the forecast() function of python is shown in this file. Then the most accurate model is chosen.


