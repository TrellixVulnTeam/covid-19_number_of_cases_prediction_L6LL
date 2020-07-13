# Predict number of COVID-19 cases (in progress)
Based on which measures have been taken when by governments, the goal of this project is to predict the current number of COVID-19 cases per country. 

## How?
Using a dataset on government measures against COVID-19, we train a randomforest regressor to predict the current number of COVID-19 cases in a country. 
So far, the regressor performs poorly. Therefore, in a next step, more information shall be included in the model. 


## Data

### Government measures
The #COVID19 Government Measures Dataset is put togther by the [Assessment Capacities Project] (https://data.humdata.org/organization/acaps?sort=metadata_modified+desc).
It summarizes the measures implemented by governments worldwide in response to the Coronavirus pandemic according to five categories: 
* social distancing
* movement restrictions
* public health measures
* social and economic measures
* and lockdowns. 

The dataset is updated weekly. Source: https://data.humdata.org/dataset/acaps-covid19-government-measures-dataset

### COVID-19 cases per country
The time_series_covid19_confirmed_global dataset contains a summary of confirmed COVID-19 cases per country as reported by the John Hopkins University. 
It is updated daily. Source: https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv

