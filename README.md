# Retail-Analysis-with-Walmart-Data
The aim of this project  is to get the Walmart data and analyse the required statements.

# Retail Analysis with Walmart Data

1. [ProjectMotivation](#ProjectMotivation)
2. [Installation](#Installation)
3. [Data](#Data)
4. [Machine Learning Models](#model)
5. [Communication/Result](#results)

## 1. Project Motivation <a name="ProjectMotivation"></a> 

**In this project we focused retail analysis with Walmart data and answer the following questions:**
1. Which store has minimum and maximum sales?
2. Which store has maximum standard deviation i.e., the sales vary a lot. Also, find out the
coefficient of mean to standard deviation
3. Which store/s has good quarterly growth rate in Q3’2012
4. Some holidays have a negative impact on sales. Find out holidays which have higher sales
than the mean sales in non-holiday season for all stores together
5. Provide a monthly and semester view of sales in units and give insights
Statistical Model
6. Build prediction to forecast demand.
Linear Regression – Utilize variables like date and restructure dates as 1 for 5 Feb 2010 (starting from the earliest date in order). Hypothesize if CPI, unemployment, and fuel price have any impact on sales. Change dates into days by creating new variable.


## 2. Required Python Modules/Libraries <a name="Installation"></a>

- Python versions 3.*.
- Python Libraries:
    - sklearn.
    - Pandas.
    - numpy.
    - seaborn
    - matplotlib.
    - datetime.

## 3. Data<a name="data"></a> 

There are sales data available for 45 stores of Walmart. Avialable as Walmart_data.csv. This is the data that covers sales from 2010-02-05 to 2012-11-01. 



## 4. Machine Learning Models <a name="model"></a> 
In this project, we used [RandomForestRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html), [LinearRegression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html),  [ExtraTreesRegressor]([https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.ExtraTreesRegressor.html)),  [DecisionTreeRegressor]([https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html)) to predict of sales. The data have been split into training and testing with a ratio of 80:20.



## 5. Communication/Result<a name="results"></a>
The details of the results show in the code.
