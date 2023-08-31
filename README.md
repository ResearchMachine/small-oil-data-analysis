# (2020) Statistical Data Analysis for Recommendations of Improving Oil Production Process. Small Size Data Analysis
**Project Type:**  Commercial Data Science project, Statistical Analysis  
**Programming Language:**  Python 3  
**Project Сode:** [EDA Python Notebook](https://github.com/ResearchMachine/commercial-project-small-oil-data-analysis/blob/main/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D0%BE%D0%B9%20%D0%B1%D0%BB%D0%BE%D0%BA%D0%BD%D0%BE%D1%82.ipynb), [MVP GUI Python App](https://github.com/ResearchMachine/commercial-project-small-oil-data-analysis/blob/main/%D0%9F%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5%20%20%D0%B4%D0%BB%D1%8F%20%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%20%D0%BC%D0%B0%D0%BB%D1%8B%D1%85%20%D0%B2%D1%8B%D0%B1%D0%BE%D1%80%D0%BE%D0%BA/RUN.ipynb)  
**Project Full Description**: **[Research Article](https://drive.google.com/file/d/1VDWvMugO1Xi0vq9hw1JTXwHYWVGlFPih/view?usp=sharing) (2021)**  
**Company:**  [Gazprom Neft](https://en.wikipedia.org/wiki/Gazprom_Neft)  




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
**[Research Article](https://drive.google.com/file/d/1VDWvMugO1Xi0vq9hw1JTXwHYWVGlFPih/view?usp=sharing) (2021, Scopus).**

**The project code contains 2 scripts**:
1. [EDA Python Notebook](https://github.com/ResearchMachine/commercial-project-small-oil-data-analysis/blob/main/%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D0%BE%D0%B9%20%D0%B1%D0%BB%D0%BE%D0%BA%D0%BD%D0%BE%D1%82.ipynb);  
2. [MVP GUI Python App](https://github.com/ResearchMachine/commercial-project-small-oil-data-analysis/blob/main/%D0%9F%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5%20%20%D0%B4%D0%BB%D1%8F%20%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%20%D0%BC%D0%B0%D0%BB%D1%8B%D1%85%20%D0%B2%D1%8B%D0%B1%D0%BE%D1%80%D0%BE%D0%BA/RUN.ipynb).

![image](https://github.com/ResearchMachine/commercial-project-small-oil-data-analysis/assets/70639823/bca2cecb-58bd-4e96-a371-a6ed7dfd07fb)

