# Covid-19-Prediction
## Problem Statement

*   Based on Comfirmed cases,Death cases,Recover cases of per days we have to predict/Forecast how much cases will come in future days and create a predictive model.
*   Fix a period for prediction of confirmed cases/deaths. Create a predictive model to forecast the Covid19 cases based on past cases for a specific country or region.
*   Prepare a complete data analysis report on the given data.
*   Make suggestions to the government health department of the country/region for preparation based on your predictions.
  
### Dataset Information :

This is a daily updating version of COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University (JHU). The data updates every day at 6am UTC, which updates just after the raw JHU data typically updates.
I'm making it available in both a raw form (files with the prefix RAW) and convenient form (files prefixed with CONVENIENT).
The data covers:
  ●	confirmed cases and deaths on a country level
  ●	confirmed cases and deaths by US county
  ●	some metadata that's available in the raw JHU data
The RAW version is exactly as it's distributed in the original dataset.
The CONVENIENT version is aiming to be easier to analyze. The data is organized by column rather than by row. The metadata is stripped out into a separate file. And it converted to daily change rather than cumulative totals.
I have a notebook that updates just after each data dump updates, giving a brief overview of the latest data. It's also a useful reference if you want to see how to read the CONVENIENT data into a pandas DataFrame.

### Attribute information
*   confirmed cases of Covid-19 based on global (whole Country).
*   Death cases of COVID-19 based on global (whole Country).
*   Recovery cases of COVID-19 based on global (whole Country).
*   Province/State are showing COVID-19 cases of State of country.
*   Country/Region are showing COVID-19 cases based on Country.
*   Latitude is showing measurment of globe or map of location north or south of the equator.
*   Longitude is showing measurment of globe or map of location east or west of the equator.
*   Dates are showing how many cases came per day.

### Suggestions to the government health department of the country for preparation

*   According to this dataset of Comfirmed,Recovered and Death cases of world level and EDA (EXPLORATORY DATA ANALYSIS) and my experience we got some information and what WHO and Government health department should do. Firstly WHO (world heath organization) and Government health department should declare alert of COVID-19 and according to this datset most of the people infected with COVID-19 virus.The virus can spread from an infected person’s mouth or nose in small liquid particles when they cough, sneeze, speak, sing or breathe.So Doctor should suggest this best way to safe and slow down transmission is to be well informed about the diease and how the virus spreads.Protect yourself and others from infection by staying at 2 meters far from others,wear a proper fitted mask and wash your hand or use an alcohol based rub frequently.Get vaccinated when it's your turn come and follow local guidance. and WHO and our Government health department should increase bed in Hospital for infected people and try to vaccinated all people as soon as possible

### Conclusion of Model Comparison Report

*   I have used 7 Algorithmns which name are LinearRegression, KNN DecisionTreeRegressor,RandomForestRegressor,XGBRegressor, ANN_MLPRegressor and Time Series for training the model. I got 99.97 percentage in RandomForestRegressor ,99.95 percentage in KNN, 99.95 Percentage in DecisionTreeRegressor,99.92 percentage in LinearRegression and 99.90 percentage in XGBRegressor . which are maximum than all Algorithmn and its working Mindblowing. So,I am perfering RandomForestRegressor and KNN for predicting the COVID-19 CASE of World and INDIA. Here, I didn't use hyperparameter tunning because without hyperparameter tunning i got 99.97 and 99.95 percentage. Here, I am suggesting two model because is Specially use for forcasting. So, you can use both of them model.
