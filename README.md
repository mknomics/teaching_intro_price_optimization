# soda 
This repository is for teaching purposes only and intended to be an introduction to basic data science and price optimization concepts, which is estimated by linear regression.  Economics students who have no technical background may use the Elasticity_Tool.ipynb, which condenses all the functionality into widgets. 

Price optimization is achieved by estimating a price response function using sales data and then estimating elasticity of demand based on the slope of the price response function.  Regression methods are used because they are easy to teach and it is important to emphasize that regressions show correlations not causal effects.  The price response function is a causal relationship that traces the demand response to price changes and it is critical for students to discover the limitation of the method within class discussions.  

Some files will need to be opened in colab to be properly rendered.  

Data: soda.csv.  The dataset includes 7561 observations of soda price sales and price for specific shops in various cities over time. 
This data is  taken from https://www.kaggle.com/veeralakrishna/predict-demand and is uploaded here simply to help students learn how to import csv files from Github using Colab. 

Learning Objectives:
1) Data Types, basic pandas methods, problem introduced: Demand_Estimation.ipynb
2) Python functions: Demand_2.ipynb
3) Load Data and visually explore seasonality and trends:  Soda_Time_Variations.ipynb
4) Explore dimensions of variation, estimate elasticity and interpret results both statistically and in business terms: Elasticity_Intro.ipynb
   

 
