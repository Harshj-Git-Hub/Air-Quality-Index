# Air-Quality-Index
Here we're going to predict AQI using Python, leveraging data science tools and machine learning algorithms.

AQI -
The Air Quality Index (AQI) is a standardized indicator used to communicate how polluted the air currently is or how polluted it is forecast to become. 

The dataset -
It contains 7 attributes, of which 6 are chemical pollution quantities and one is Air Quality Index. AQI Value, CO AQI Value, Ozone AQI Value, NO2 AQI Value, PM2.5 AQI Value, lat,LNG are independent attributes. air_quality_index is a dependent attribute. Since air_quality_index is calculated based on the 7 attributes.
As the data is numeric and there are no missing values in the data, so no preprocessing is required. Our goal is to predict the AQI, so this task is either Classification or regression. So as our class label is continuous, regression technique is required.
