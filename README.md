# COVID-19


The aim of this project was to check whether on the basis of the collected data the global and local prediction of 
- the number of cases,
- the number of deaths 

casued by COVID-19 disease can be made.

Data used in this project was collected by Emanuele Guidotti and David Ardia: https://covid19datahub.io/

Because of the fact, that the dataset consists of many variables, some of the variables were removed - they were redundant while making prediction. Additionaly, the collinearity of the variables was checked.
The problem of missing values was adressed adequately to both global and local case.

Linear regression models for a set of previously selected variables were created in a loop.
Linear and multivariate regression models were compared to each other and summarized by metrcis like: R2, RMSE and MAE for both training and testing sets.



The global and local cases were considered during analysis.

What is more the output of:
- SVR,
- Regression Trees,
- Random Regression Forest 

algorithms were compared and summarized by basic metrics.

--NOTE:  The above mentioned algorithms were performed with the most basic and default parameters -> there is no hypertuning of the parameters.
