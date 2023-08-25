# Title
**Project Type:** 
**Programming Language:** 
**Project Сode:** 
**Project Full Description** (in Russian): 
**Company:** 




### I. Motivation
The company has accumulated data on a special group of wells. The task was set to find correlations between technological indicators and the volume of oil production.

### II. Problem
The main purpose of this work is to give recommendations on the configuration of the hydraulic fracturing design to maximize the volume of oil production based on historical data, the definition of technological limits for the development of construction design.
Project tasks:
* search for the factors most influencing the increase in cumulative production;  
* making a production forecast;  
* prototype implementation in Python.

Input data: dataset of the company's field data, cleaned by the company's field specialists from wells with technological anomalies, consisting of 23 observations (wells) with gaps in factors and target variables (oil production for 30 60 90 180 and 360 days with and without normalization to wellbore length).  
Problems: small data, importance of interpretation.  
Methods: classical ML statistics and models, Python 3, Jupyter Notebook.


### III. Key Results 
* Developed a forecasting tool that consists of 3 elements:
selection of a segment of wells with a high correlation on average by factors;
selection of highly correlated and statistically significant factors;
building a regression model and forecasting the production volume using the Monte Carlo method;  
* up to +110% projected growth in oil production in compliance with the developed recommendations;  
* Developed an MVP GUI application for re-forecasting (Python 3, Jupyter Notebook, sklearn).  

  

### III. Content


**The project code contains 2 scripts**:
1. EDA Python Notebook;  
2. MVP GUI Python App.
