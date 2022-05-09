# Time-Series-Forecasting

In this report, we will work with two datasets. The first one gives us the date
of a property’s sale, the price, the property type (unit or house) and finally the number
of bedrooms (1, 2, 3, 4 or 5). The second dataset transforms the raw sales data (first
dataset), by re-sampling it at quarterly intervals with median price aggregation and step
4 moving average smoothing. The date range of these sales is from 09/2007 to 09/2019.
To better understand our data, we will first conduct a Exploratory Data Analysis (EDA).
Then we will focus on the goal of the report which is to forecast for the 8 future quarters,
the sale price for each property type and number of bedroom. In order to forecast, we
will build and compare two types of models: one model from the traditional multi-variate
forecasting models from the VARMAX family and one model from Recurrent Neural
Network (RNN) such as the Long Short-Term Memory (LSTM) model.
