# ECE-225 Final Project

## US Unemployment Rate Analysis
Problem:
In this project we plan to address various questions regarding unemployment in the United States
using data from the United States Department of Labor’s Bureau of Labor Statistics.

## Dataset:
1. US Unemployment Rate by county
2. Additional data scraping using Python from the BLS Public Data API


Proposed Solution and Real-world Application :
The proposed plan is to analyze Unemployment data from 1990 to 2020 to answer questions
about unemployment rate in relation to geographic location over time. We plan to analyse critical
events such as the Financial crisis in 2007-2008 , global events which resulted in mass layoffs in
the United States and change of government administration. In addition, our goal is to create
visualizations that make it clear whether there are any meaningful relationships to derive from
the data. We also plan to create a regression model that will predict the unemployment rate in a
county based on data from the previous years. Our final goal is to employ these heuristics and
present our findings in a concise and visual manner to make any correlations apparent to the
user.


### We hope to answer the following questions:

- s there a correlation between unemployment rate and county? Positive? Negative?
- Is there a trend to be seen over time that is independent of location?
- What events, if any, have a significant impact on unemployment rate in certain counties?
- Can a model be generated that can accurately predict unemployment rate by county?
Project steps

| Step | Estimated Completion | Plan |
|---|---|---|
| 1. Extracting and cleaning up data |One week |Extracting additional data for 2016-2020|
|2. Data Visualizations| Two week| Assign Geo Codes to Counties, Map Distribution|
|3. Regression Model| One week |Using time series data to create a regression model|

## New York Plots 

### Rolling Averages
![alt text](https://github.com/ArthDh/ECE-225/blob/dev/Images/ny_rolling_avg.png "Rolling Averages")

### Historcial Crashes
![alt text](https://github.com/ArthDh/ECE-225/blob/dev/Images/ny_ca_events.png)

### ARIMA Model
![alt text](https://github.com/ArthDh/ECE-225/blob/dev/Images/ny_county_model.png)
