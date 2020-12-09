# Play with models (Prophet & LSTM) for energy-demand time series

Time series are one of the most commonly used data types to measure our human and economic activity and could be defined as a collection of observations of a variable collected sequentially over time. Stock prices, sales, climate data, physiological measurements such as our weight or temperature, or others such as energy consumption, on which we will base this article, are just some of the examples of data that are measured at regular time intervals. Most data scientists have encountered the challenge of analyzing data in the form of time series and being able to handle it effectively is a skill that must be present in our "toolbox".  

In this article we will discuss with an example of predicting the demand for energy in homes to start playing with time series in Python, using for prediction a couple of models of the most used such as **Prophet** (Facebook) and Recurrent Neural Networks using **Long Short-Term Memory** (LSTM). Before applying the models and especially in the time series, some data manipulation is necessary to use them in supervised models, so we don't have a separate variable as such, but must be generated to apply the models to it.  

In this notebook, you will see about an approximation:  
-	Exploratory analysis of time series data and trend visualization and seasonality.
-	An approximation to feature engineering in time series.
-	Preparation of data for supervised models in time series.
-	Application, analysis and comparison between Prophet and LSTM models.
