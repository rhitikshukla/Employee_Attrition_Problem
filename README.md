# Employee_Attrition_Problem

Employee Attrition refers to the rate at which employees leave a company. High attrition can have negative consequences for an organization.
The project 'Employee Attrition Problem' is regression model to predict the salaries of the employees to understand what factors affect the company's finance and revenue.

## Problem Statement:
To predict the salary of the employee based on the information provided in the dataset. Columns Provided in the Dataset are:
1. **jobId** - Unique ID that indicates the employee
2. **companyId** - Unique ID that idicates the company
3. **jobType** - shows which post the employee is working for the company
4. **degree** - shows which degree is completed by the employee
5. **major** - shows the field in which the employee is specialised in
6. **industry** - show the industry in which the employee is working
7. **yearsExperience** - years of working experience the employee is having
8. **milesFromMetropolis** - distance in miles between the comapny and home of the employee
9. **salary** - salary given to the employee.(eg. 250 indicates 2,50,000 in dollars)

#### Link to Dataset: https://drive.google.com/drive/folders/1nW6cTtkMwENbP7Hfnul4dAZlmdLHbmhe?usp=sharing

## Steps:
1. **Importing the Dataset**
2. **EDA**
3. **Correlation Matrix, Chi-square Test, ANOVA Test**
4. **Checked for Multi-collinearity using VIF**
5. **Scaling the Data using MinMaxScaler**
6. **Encoding using OneHotEncoding**
7. **Modelling using various Machine Learning Algorithms like Linear Regression, Random Forest Regressor, Gradient Boosting Regressor, Decision Tree Regressor, AdaBoost Regressor, XGBoost and Light Gradient Boosting Machine**
8. **Compared all the models based on Metrics**
9. **Hyper Parameter Tuning using RandomizedSearchCV**
10. **Training the models using best Parameters**
11. **Compared the metrics for tuned models**
12. **Working with the test data using the best model, i.e, GradientBoostingRegressor**

## Metric comparison for tuned models:
![image](https://github.com/rhitikshukla/Employee_Attrition_Problem/assets/118650619/0547721b-1202-4481-b5eb-066a7e2fa7a2)


## Conclusion:
The company gets an optimised range of salaries that should be given to the employees based on factors given in the dataset that will help in reducing the extra money the company is spending.
Also, the company gets a rough idea of revenue so that they can allocate an adequate amount for their employees.
At last, we can compare the predicted salary and the actual salary that the employee is getting. If the difference is high then the employee is certain to leave the company.

